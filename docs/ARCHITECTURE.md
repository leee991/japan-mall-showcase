# 架构与线上调优记录 — TGShop 商城

## 1. Tomcat 9 里的 Context 分布

| Context Path | 作用 |
|---|---|
| `/` (`/pc`) | PC 商城前端 |
| `/www` · `/ww` | H5 商城与商户端 |
| `/wap` (`/api`) | 移动端与开放 API（Spring MVC + Dubbo） |
| `/admin` | 运营与商户后台（商品、SKU、订单、商户、资金） |
| `/data` | 行情与数据模块 |
| `/chat` | 客服聊天前端 |
| `/promote` · `/download` · `/pact` | 推广页、下载页与协议页 |

## 2. Spring / Dubbo 模块划分（`WEB-INF/classes/spring/`）
- 商城与商品：`mall_admin`、`sku`、`item_admin`
- 用户与权限：`party`、`security_systemuser_admin`
- 资金与财务：`recharge_blockchain_admin`、`auto_monitor_withdraw_admin`、`report_admin`
- 公共设施：`dubbo`、`kernel`、`log`、`ddos_admin`、`cms_admin`

## 3. 几个关键运维动作
- **防反序列化**：JVM 加 `-Dfastjson.parser.safeMode=true`。
- **Nginx 卸载压力**：图片目录全部 `alias` + 30 天 `immutable` 缓存 + `access_log off`；上游 Tomcat 配置长连接 keepalive。
