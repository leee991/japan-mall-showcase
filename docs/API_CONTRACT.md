# 路由分流与后台模块 — TGShop 商城

## 1. Nginx 分流规则

| 路径 | 怎么处理 | 说明 |
|---|---|---|
| `^/www/js/.*-[0-9a-f]{8}\.js$` | Nginx 直出 | 文件名带 hash，走长缓存 |
| `^/(images|avatar|merchant|shopAvatar|customerService)/` | Nginx `alias` 直出 | 30 天 `immutable`，关访问日志 |
| `^/media/<bucket>/` | Nginx 反代缓存 | 带 `X-Image-Cache` 方便查缓存命中 |
| `/wap/api/*` | 反代到 Tomcat `/wap` | 动态接口 |
| `/admin/*` | 反代到 Tomcat `/admin` | 运营后台（拦截非预期诊断路径） |

## 2. 后台主要功能块
- **商品**：商品管理、系统商品库、分类与属性、套餐组合、评价管理
- **订单**：订单查询、派单与采购金额核对、商品上下架
- **商户与代理**：商户审核、VIP 配置、代理树、信用/贷款配置
- **财务与日志**：钱包日报、提现审核、充值监控、DDoS 和操作日志
