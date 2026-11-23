# Spring & Dubbo Context Architecture Overview


## `admin/WEB-INF/classes/spring/applicationContext-auto_monitor_activity_admin.xml`
- Bean `activityService` -> `project.monitor.activity.internal.ActivityServiceImpl`
- Bean `activityOrderService` -> `project.monitor.activity.internal.ActivityOrderServiceImpl`
- Bean `adminActivityService` -> `project.monitor.activity.internal.AdminActivityServiceImpl`
- Bean `adminActivityOrderService` -> `project.monitor.activity.internal.AdminActivityOrderServiceImpl`

## `admin/WEB-INF/classes/spring/applicationContext-auto_monitor_admin.xml`
- Dubbo interface: `project.monitor.AutoMonitorAddressConfigService`
- Dubbo interface: `project.monitor.AutoMonitorWalletTransferFromService`
- Dubbo interface: `project.monitor.DAppAccountService`
- Dubbo interface: `project.monitor.telegram.TelegramMessageService`
- Dubbo interface: `project.monitor.report.DAppUserDataSumService`
- Dubbo interface: `project.monitor.AutoMonitorAutoTransferFromConfigService`
- Dubbo interface: `project.monitor.etherscan.EtherscanRemoteService`
- Dubbo interface: `project.monitor.erc20.service.Erc20RemoteService`
- Bean `erc20Service` -> `project.monitor.erc20.service.internal.Erc20ServiceImpl`
- Bean `autoMonitorWalletService` -> `project.monitor.internal.AutoMonitorWalletServiceImpl`
- Bean `autoMonitorAddressConfigService` -> `project.monitor.internal.AutoMonitorAddressConfigServiceImpl`
- Bean `autoMonitorOrderService` -> `project.monitor.internal.AutoMonitorOrderServiceImpl`
- Bean `adminAutoMonitorWalletService` -> `project.monitor.internal.AdminAutoMonitorWalletServiceImpl`
- Bean `adminAutoMonitorOrderService` -> `project.monitor.internal.AdminAutoMonitorOrderServiceImpl`
- Bean `adminDAppUserService` -> `project.monitor.internal.AdminDAppUserServiceImpl`
- Bean `qRGenerateService` -> `project.user.internal.QRGenerateServiceImpl`
- Bean `googleAuthService` -> `project.user.googleauth.internal.GoogleAuthServiceImpl`
- Bean `adminAutoMonitorAddressConfigService` -> `project.monitor.internal.AdminAutoMonitorAddressConfigServiceImpl`
- Bean `autoMonitorTipService` -> `project.monitor.internal.AutoMonitorTipServiceImpl`
- Bean `autoMonitorDAppLogService` -> `project.monitor.internal.AutoMonitorDAppLogServiceImpl`
- Bean `miningConfigService` -> `project.monitor.mining.internal.MiningConfigServiceImpl`
- Bean `adminMiningConfigService` -> `project.monitor.mining.internal.AdminMiningConfigServiceImpl`
- Bean `adminAutoMonitorTipService` -> `project.monitor.internal.AdminAutoMonitorTipServiceImpl`
- Bean `telegramBusinessMessageService` -> `project.monitor.telegram.business.TelegramBusinessMessageServiceImpl`
- Bean `autoMonitorPoolDataService` -> `project.monitor.internal.AutoMonitorPoolDataServiceImpl`
- Bean `adminAutoMonitorPoolDataService` -> `project.monitor.internal.AdminAutoMonitorPoolDataServiceImpl`
- Bean `adminAutoMonitorDAppLogService` -> `project.monitor.internal.AdminAutoMonitorDAppLogServiceImpl`
- Bean `autoMonitorAutoTransferFromConfigService` -> `project.monitor.internal.AutoMonitorAutoTransferFromConfigServiceImpl`
- Bean `adminAutoMonitorAutoTransferFromConfigService` -> `project.monitor.internal.AdminAutoMonitorAutoTransferFromConfigServiceImpl`
- Bean `autoMonitorTransferAddressConfigService` -> `project.monitor.internal.AutoMonitorTransferAddressConfigServiceImpl`
- Bean `adminAutoMonitorTransferAddressConfigService` -> `project.monitor.internal.AdminAutoMonitorTransferAddressConfigServiceImpl`
- Bean `etherscanService` -> `project.monitor.etherscan.internal.EtherscanServiceImpl`
- Bean `nodeRpcService` -> `project.monitor.noderpc.internal.NodeRpcServiceImpl`

## `admin/WEB-INF/classes/spring/applicationContext-auto_monitor_pledge_admin.xml`
- Bean `pledgeConfigService` -> `project.monitor.pledge.internal.PledgeConfigServiceImpl`
- Bean `pledgeGalaxyConfigService` -> `project.monitor.pledgegalaxy.internal.PledgeGalaxyConfigServiceImpl`
- Bean `pledgeOrderService` -> `project.monitor.pledge.internal.PledgeOrderServiceImpl`
- Bean `pledgeService` -> `project.monitor.pledge.internal.PledgeServiceImpl`
- Bean `adminPledgeConfigService` -> `project.monitor.pledge.internal.AdminPledgeConfigServiceImpl`
- Bean `adminPledgeGalaxyConfigService` -> `project.monitor.pledgegalaxy.internal.AdminPledgeGalaxyConfigServiceImpl`
- Bean `adminPledgeOrderService` -> `project.monitor.pledge.internal.AdminPledgeOrderServiceImpl`
- Bean `adminPledgeGalaxyOrderService` -> `project.monitor.pledgegalaxy.internal.AdminPledgeGalaxyOrderServiceImpl`
- Bean `adminPledgeGalaxyProfitService` -> `project.monitor.pledgegalaxy.internal.AdminPledgeGalaxyProfitServiceImpl`
- Bean `pledgeGalaxyProfitService` -> `project.monitor.pledgegalaxy.internal.PledgeGalaxyProfitServiceImpl`
- Bean `pledgeGalaxyOrderService` -> `project.monitor.pledgegalaxy.internal.PledgeGalaxyOrderServiceImpl`
- Bean `activityOrderService` -> `project.monitor.activity.internal.ActivityOrderServiceImpl`
- Bean `adminActivityOrderService` -> `project.monitor.activity.internal.AdminActivityOrderServiceImpl`

## `admin/WEB-INF/classes/spring/applicationContext-auto_monitor_report_admin.xml`
- Bean `adminAutoMonitorDAppStatisticsService` -> `project.monitor.report.internal.AdminAutoMonitorDAppStatisticsServiceImpl`
- Bean `adminAutoMonitorUserMoneyStatisticsService` -> `project.monitor.report.internal.AdminAutoMonitorUserMoneyStatisticsServiceImpl`

## `admin/WEB-INF/classes/spring/applicationContext-auto_monitor_withdraw_admin.xml`
- Bean `adminAutoMonitorWithdrawService` -> `project.monitor.withdraw.internal.AdminAutoMonitorWithdrawServiceImpl`
- Bean `autoMonitorWithdrawService` -> `project.monitor.withdraw.internal.AutoMonitorWithdrawServiceImpl`
- Bean `adminAutoMonitorWithdrawCollectionService` -> `project.monitor.withdraw.internal.AdminAutoMonitorWithdrawCollectionServiceImpl`
- Bean `autoMonitorWithdrawCollectionService` -> `project.monitor.withdraw.internal.AutoMonitorWithdrawCollectionServiceImpl`

## `admin/WEB-INF/classes/spring/applicationContext-cms_admin.xml`
- Dubbo interface: `project.cms.BannerService`
- Bean `cmsService` -> `project.cms.internal.CmsServiceImpl`
- Bean `adminCmsService` -> `project.cms.internal.AdminCmsServiceImpl`
- Bean `bannerService` -> `project.cms.internal.BannerServiceImpl`
- Bean `adminBannerService` -> `project.cms.internal.AdminBannerServiceImpl`

## `admin/WEB-INF/classes/spring/applicationContext-contract_admin.xml`
- Bean `adminContractOrderService` -> `project.contract.internal.AdminContractOrderServiceImpl`
- Bean `adminContractApplyOrderService` -> `project.contract.internal.AdminContractApplyOrderServiceImpl`
- Bean `adminMarketQuotationsService` -> `project.contract.internal.AdminMarketQuotationsServiceImpl`
- Bean `contractOrderService` -> `project.contract.internal.ContractOrderServiceImpl`
- Bean `contractApplyOrderService` -> `project.contract.internal.ContractApplyOrderServiceImpl`

## `admin/WEB-INF/classes/spring/applicationContext-ddos_admin.xml`
- Dubbo interface: `project.ddos.CheckIpRequestCountService`
- Dubbo interface: `project.ddos.IpMenuService`
- Dubbo interface: `project.ddos.UrlSpecialService`
- Bean `adminIpMenuService` -> `project.ddos.internal.AdminIpMenuServiceImpl`
- Bean `adminUrlSpecialService` -> `project.ddos.internal.AdminUrlSpecialServiceImpl`
- Bean `adminIpCountService` -> `project.ddos.internal.AdminIpCountServiceImpl`

## `admin/WEB-INF/classes/spring/applicationContext-dubbo.xml`
- Dubbo interface: `project.party.recom.UserRecomService`
- Dubbo interface: `project.party.PartyService`
- Dubbo interface: `project.user.UserDataService`
- Dubbo interface: `project.data.DataService`
- Dubbo interface: `project.data.KlineService`
- Dubbo interface: `project.recharge.RechargeService`
- Dubbo interface: `project.blockchain.QRProducerService`
- Dubbo interface: `project.bonus.RechargeBonusService`
- Dubbo interface: `project.user.QRGenerateService`
- Dubbo interface: `project.recharge.RechargeService`
- Dubbo interface: `project.user.UserDataService`
- Dubbo interface: `project.log.LogService`
- Dubbo interface: `project.log.CodeLogService`
- Dubbo interface: `project.log.SysLogService`
- Dubbo interface: `project.data.AdjustmentValueService`
- Dubbo interface: `project.onlinechat.OnlineChatMessageService`
- Dubbo interface: `project.onlinechat.OnlineChatVisitorMessageService`
- Dubbo interface: `project.onlinechat.OnlineChatUserMessageService`
- Dubbo interface: `project.onlinechat.otc.OtcOnlineChatMessageService`
- Dubbo interface: `project.follow.TraderService`

## `admin/WEB-INF/classes/spring/applicationContext-email.xml`
- Bean `emailSendService` -> `email.internal.EmailSendServiceImpl`
- Bean `internalEmailSenderService` -> `email.internal.InternalEmailSenderServiceImpl`
- Bean `emailServer` -> `email.sender.EmailServer`
- Bean `emailSendThreadPool` -> `kernel.concurrent.ThreadPoolTaskExecutor`
- Bean `emailSendThreadRejectExecutingHandler` -> `kernel.util.RejectExecutionHandlerDelegator`
- Bean `mailSender` -> `org.springframework.mail.javamail.JavaMailSenderImpl`
- Bean `mailMessage` -> `org.springframework.mail.SimpleMailMessage`
- Bean `freeMarkerConfigurer` -> `org.springframework.web.servlet.view.freemarker.FreeMarkerConfigurer`

## `admin/WEB-INF/classes/spring/applicationContext-exchange_admin.xml`
- Dubbo interface: `project.exchange.job.ExchangeApplyOrderHandleJobService`
- Bean `adminExchangeApplyOrderService` -> `project.exchange.internal.AdminExchangeApplyOrderServiceImpl`
- Bean `exchangeApplyOrderService` -> `project.exchange.internal.ExchangeApplyOrderServiceImpl`

## `admin/WEB-INF/classes/spring/applicationContext-finance_admin.xml`
- Bean `financeService` -> `project.finance.internal.FinanceServiceImpl`
- Bean `financeOrderService` -> `project.finance.internal.FinanceOrderServiceImpl`
- Bean `adminFinanceService` -> `project.finance.internal.AdminFinanceServiceImpl`
- Bean `adminFinanceOrderService` -> `project.finance.internal.AdminFinanceOrderServiceImpl`
- Bean `financeOrder1DayJob` -> `project.finance.job.FinanceOrder1DayJob`

## `admin/WEB-INF/classes/spring/applicationContext-futures_admin.xml`
- Bean `futuresParaService` -> `project.futures.internal.FuturesParaServiceImpl`
- Bean `futuresOrderService` -> `project.futures.internal.FuturesOrderServiceImpl`
- Bean `profitAndLossConfigService` -> `project.futures.internal.ProfitAndLossConfigServiceImpl`
- Bean `adminFuturesOrderService` -> `project.futures.internal.AdminFuturesOrderServiceImpl`
- Bean `adminFuturesParaService` -> `project.futures.internal.AdminFuturesParaImpl`
- Bean `adminContractManageService` -> `project.futures.internal.AdminContractManageServiceImpl`
- Bean `adminProfitAndLossConfigService` -> `project.futures.internal.AdminProfitAndLossConfigServiceImpl`

## `admin/WEB-INF/classes/spring/applicationContext-hobi_admin.xml`
- Dubbo interface: `project.hobi.HobiDataService`
- Dubbo interface: `project.data.DataService`
- Dubbo interface: `project.data.internal.KlineInitService`
- Bean `dataService` -> `project.data.internal.DataServiceImpl`
- Bean `adminSymbolsService` -> `project.hobi.internal.AdminSymbolsServiceImpl`
- Bean `adminContractSymbolsService` -> `project.hobi.internal.AdminContractSymbolsServiceImpl`

## `admin/WEB-INF/classes/spring/applicationContext-invest_admin.xml`
- Bean `platformService` -> `project.invest.platform.impl.PlatformServiceImpl`
- Bean `adminExpertService` -> `project.invest.expert.impl.AdminExpertServiceImpl`
- Bean `adminGoodsService` -> `project.invest.goods.impl.AdminGoodsServiceImpl`
- Bean `adminGoodsBuyService` -> `project.invest.goods.impl.AdminGoodsBuyServiceImpl`
- Bean `adminOrderService` -> `project.invest.order.impl.AdminOrderServiceImpl`
- Bean `adminExchangeOrderService` -> `project.invest.order.impl.AdminExchangeOrderServiceImpl`
- Bean `adminProjectService` -> `project.invest.project.impl.AdminProjectServiceImpl`
- Bean `brushOrdersService` -> `project.invest.orders.internal.BrushOrdersServiceImpl`
- Bean `adminVipService` -> `project.invest.vip.impl.AdminVipServiceImpl`
- Bean `walletDayService` -> `project.invest.walletday.impl.WalletDayServiceImpl`
- Bean `vipService` -> `project.invest.vip.internal.VipServiceImpl`

## `admin/WEB-INF/classes/spring/applicationContext-item_admin.xml`
- Bean `itemService` -> `project.item.internal.ItemServiceImpl`
- Bean `itemUserOptionalService` -> `project.item.internal.ItemUserOptionalServiceImpl`
- Bean `adminItemService` -> `project.item.internal.AdminItemServiceImpl`
- Bean `adminItemLeverageService` -> `project.item.internal.AdminItemLeverageServiceImpl`

## `admin/WEB-INF/classes/spring/applicationContext-kernel.xml`
- Bean `pagedDao` -> `kernel.web.PagedQueryDaoImpl`
- Bean `jdbcTemplateWithPaging` -> `kernel.web.JdbcTemplateWithPaging`
- Bean `redisLocalCache` -> `kernel.cache.RedisLocalCache`
- Bean `twoDimensionCodeContentService` -> `kernel.service.TwoDimensionCodeContentServiceImpl`
- Bean `messageSource` -> `org.springframework.context.support.ResourceBundleMessageSource`

## `admin/WEB-INF/classes/spring/applicationContext-log.xml`
- Bean `moneyLogService` -> `project.log.internal.MoneyLogServiceImpl`
- Bean `orderLogService` -> `project.mall.log.impl.OrderLogServiceImpl`

## `admin/WEB-INF/classes/spring/applicationContext-mall_admin.xml`
- Dubbo interface: `project.mall.notification.utils.notify.client.CommonNotifyService`
- Dubbo interface: `project.mall.notification.utils.notify.client.NotificationHelperClient`
- Bean `adminMallBannerService` -> `project.mall.banner.impl.AdminMallBannerServiceImpl`
- Bean `adminCategoryService` -> `project.mall.type.impl.AdminCategoryServiceImplMysql8`
- Bean `categoryLangService` -> `project.mall.type.impl.CategoryLangServiceImpl`
- Bean `adminComboService` -> `project.mall.combo.impl.AdminComboServiceImpl`
- Bean `adminSubscribeService` -> `project.mall.subscribe.impl.AdminSubscribeServiceImpl`
- Bean `adminMallGoodsService` -> `project.mall.goods.impl.AdminMallGoodsServiceImpl`
- Bean `goodsAttributeCategoryService` -> `project.mall.goods.impl.GoodsAttributeCategoryServiceImpl`
- Bean `goodsAttributeService` -> `project.mall.goods.impl.GoodsAttributeServiceImpl`
- Bean `adminSystemCommentService` -> `project.mall.comment.impl.AdminSystemCommentServiceImpl`
- Bean `adminMallOrderService` -> `project.mall.orders.impl.AdminMallOrderServiceImpl`
- Bean `goodsSkuAtrributionService` -> `project.mall.goods.internal.GoodsSkuAtrributionServiceImpl`
- Bean `adminSellerService` -> `project.mall.seller.impl.AdminSellerServiceImpl`
- Bean `adminMallLoanConfigService` -> `project.mall.loan.impl.AdminMallLoanConfigServiceImpl`
- Bean `focusSellerService` -> `project.mall.seller.impl.FocusSellerServiceImpl`
- Bean `adminMallCountryService` -> `project.mall.area.impl.AdminMallCountryServiceImpl`
- Bean `adminMallStateService` -> `project.mall.area.impl.AdminMallStateServiceImpl`
- Bean `adminMallCityService` -> `project.mall.area.impl.AdminMallCityServiceImpl`
- Bean `sellerGoodsService` -> `project.mall.goods.impl.SellerGoodsServiceImpl`
- Bean `evaluationService` -> `project.mall.evaluation.impl.EvaluationServiceImpl`
- Bean `comboService` -> `project.mall.combo.impl.ComboServiceImpl`
- Bean `mallAddressAreaService` -> `project.mall.area.impl.MallAddressAreaServiceImpl`
- Bean `goodsOrdersService` -> `project.mall.orders.internal.GoodsOrdersServiceImpl`
- Bean `sellerService` -> `project.mall.seller.impl.SellerServiceImpl`
- Bean `sellerCreditService` -> `project.mall.seller.impl.SellerCreditServiceImpl`
- Bean `moneyFreezeService` -> `project.log.internal.MoneyFreezeServiceImpl`

## `admin/WEB-INF/classes/spring/applicationContext-miner_admin.xml`
- Bean `minerService` -> `project.miner.internal.MinerServiceImpl`
- Bean `minerOrderService` -> `project.miner.internal.MinerOrderServiceImpl`
- Bean `adminMinerService` -> `project.miner.internal.AdminMinerServiceImpl`
- Bean `adminMinerOrderService` -> `project.miner.internal.AdminMinerOrderServiceImpl`
- Bean `minerParaService` -> `project.miner.internal.MinerParaServiceImpl`
- Bean `adminMinerParaService` -> `project.miner.internal.AdminMinerParaServiceImpl`
- Bean `minerOrderProfitJob` -> `project.miner.job.MinerOrderProfitJob`

## `admin/WEB-INF/classes/spring/applicationContext-news_admin.xml`
- Bean `adminNewsService` -> `project.news.internal.AdminNewsServiceImpl`

## `admin/WEB-INF/classes/spring/applicationContext-notification_admin.xml`
- Bean `notificationService` -> `project.mall.notification.impl.NotificationServiceImpl`
- Bean `notificationTemplateService` -> `project.mall.notification.impl.NotificationTemplateServiceImpl`

## `admin/WEB-INF/classes/spring/applicationContext-party.xml`
- Bean `partyService` -> `project.party.internal.PartyServiceImpl`
- Bean `userRecomService` -> `project.party.recom.internal.UserRecomServiceImpl`
- Bean `partyLoadCacheService` -> `project.data.loadcache.PartyLoadCacheService`
- Bean `userMetricsService` -> `project.party.internal.UserMetricsServiceImpl`

## `admin/WEB-INF/classes/spring/applicationContext-recharge_blockchain_admin.xml`
- Bean `rechargeBlockchainService` -> `project.blockchain.internal.RechargeBlockchainServiceImpl`
- Bean `channelBlockchainService` -> `project.blockchain.internal.ChannelBlockchainServiceImpl`
- Bean `qRProducerService` -> `project.blockchain.internal.QRProducerServiceImpl`
- Bean `rechargeBonusService` -> `project.bonus.internal.RechargeBonusServiceImpl`
- Bean `adminRechargeBlockchainOrderService` -> `project.blockchain.internal.AdminRechargeBlockchainOrderServiceImpl`
- Bean `adminChannelBlockchainService` -> `project.blockchain.internal.AdminChannelBlockchainServiceImpl`

## `admin/WEB-INF/classes/spring/applicationContext-redis.xml`
- Bean `redis` -> `project.redis.interal.Redis`
- Bean `redisHandler` -> `project.redis.interal.RedisHandlerImpl`
- Bean `redisHandlerThreadPool` -> `kernel.concurrent.ThreadPoolTaskExecutor`
- Bean `redisHandlerThreadRejectExecutingHandler` -> `kernel.util.RejectExecutionHandlerDelegator`

## `admin/WEB-INF/classes/spring/applicationContext-report_admin.xml`
- Bean `adminMoneyInOutStatisticsService` -> `project.report.internal.AdminMoneyInOutStatisticsServiceImpl`
- Bean `adminExchangeOrderStatisticsService` -> `project.report.internal.AdminExchangeOrderStatisticsServiceImpl`
- Bean `adminAllStatisticsService` -> `project.web.admin.impl.report.AdminAllStatisticsServiceImpl`
- Bean `adminUserMoneyStatisticsService` -> `project.web.admin.impl.report.AdminUserMoneyStatisticsServiceImpl`
- Bean `adminUserAddStatisticsService` -> `project.report.internal.AdminUserAddStatisticsServiceImpl`
- Bean `adminUserAllStatisticsService` -> `project.web.admin.impl.report.AdminUserAllStatisticsServiceImpl`
- Bean `adminFuturesOrderStatisticsService` -> `project.report.internal.AdminFuturesOrderStatisticsServiceImpl`
- Bean `adminContractOrderStatisticsService` -> `project.report.internal.AdminContractOrderStatisticsServiceImpl`
- Bean `adminFinanceStatisticsService` -> `project.report.internal.AdminFinanceStatisticsServiceImpl`
- Bean `adminAgentAllStatisticsService` -> `project.web.admin.impl.report.AdminAgentAllStatisticsServiceImpl`
- Bean `adminRechargeSymbolStatisticsService` -> `project.report.internal.AdminRechargeSymbolStatisticsServiceImpl`
- Bean `adminMinerOrderStatisticsService` -> `project.report.internal.AdminMinerOrderStatisticsServiceImpl`
- Bean `adminUserRecordStatisticsService` -> `project.report.internal.AdminUserRecordStatisticsServiceImpl`
- Bean `statisticsJob` -> `project.report.job.StatisticsJob`
- Bean `statisticsJobDetail_1_day` -> `org.springframework.scheduling.quartz.MethodInvokingJobDetailFactoryBean`
- Bean `statisticsTaskCronTrigger_1_day` -> `org.springframework.scheduling.quartz.CronTriggerBean`

## `admin/WEB-INF/classes/spring/applicationContext-security.xml`
- Bean `authenticationProcessingFilterEntryPoint` -> `security.filter.AuthenticationProcessingFilterEntryPoint`
- Bean `passwordEncoder` -> `org.springframework.security.providers.encoding.Md5PasswordEncoder`
- Bean `secUserService` -> `security.internal.SecUserServiceImpl`
- Bean `authenticationProcessingFilter` -> `security.filter.AjaxableAuthenticationProcessingFilter`
- Bean `roleService` -> `security.internal.RoleServiceImpl`
- Bean `securityAuthoritiesHolder` -> `security.internal.SecurityAuthoritiesHolderImpl`
- Bean `filterSecurityInterceptor` -> `org.springframework.security.intercept.web.FilterSecurityInterceptor`
- Bean `filterInvocationDefinitionSource` -> `security.filter.UrlResourceFilterInvocationDefinitionSource`
- Bean `securityResourceProcessor` -> `security.internal.SecurityResourceProcessorImpl`
- Bean `resourceService` -> `security.internal.ResourceServiceImpl`
- Bean `tokenService` -> `project.user.token.internal.TokenServiceImpl`

## `admin/WEB-INF/classes/spring/applicationContext-security_systemuser_admin.xml`
- Dubbo interface: `systemuser.CustomerService`
- Bean `adminSystemUserService` -> `systemuser.internal.AdminSystemUserServiceImpl`
- Bean `adminRoleAuthorityService` -> `systemuser.internal.AdminRoleAuthorityServiceImpl`
- Bean `resourceMappingService` -> `systemuser.internal.ResourceMappingServiceImpl`
- Bean `customerService` -> `systemuser.internal.CustomerServiceImpl`
- Bean `adminCustomerService` -> `systemuser.internal.AdminCustomerServiceImpl`

## `admin/WEB-INF/classes/spring/applicationContext-service.xml`
- Bean `userDetailsService` -> `security.internal.UserDetailsServiceImpl`
- Bean `qRGenerateService` -> `project.user.internal.QRGenerateServiceImpl`
- Bean `adminAgentService` -> `project.web.admin.impl.user.AdminAgentServiceImpl`
- Bean `adminUserService` -> `project.web.admin.impl.user.AdminUserServiceImpl`
- Bean `adminMyDataService` -> `project.user.internal.AdminMyDataServiceImpl`
- Bean `adminUserDataService` -> `project.user.internal.AdminUserDataServiceImpl`
- Bean `adminPublicUserService` -> `project.web.admin.impl.user.AdminPublicUserServiceImpl`
- Bean `adminLogService` -> `project.log.internal.AdminLogServiceImpl`
- Bean `adminSysUserNotifyConfigService` -> `project.admin.interal.AdminSysUserNotifyConfigServiceImpl`
- Bean `msgWarningService` -> `project.admin.interal.MsgWarningServiceImpl`
- Bean `adminUserRecomService` -> `project.web.admin.impl.user.AdminUserRecomServiceImpl`
- Bean `adminEmailCodeService` -> `project.web.admin.impl.email.AdminEmailCodeServiceImpl`

## `admin/WEB-INF/classes/spring/applicationContext-sku.xml`
- Bean `goodsAttributeCategoryService` -> `project.mall.goods.impl.GoodsAttributeCategoryServiceImpl`
- Bean `goodsAttributeService` -> `project.mall.goods.impl.GoodsAttributeServiceImpl`
- Bean `goodsAttributeValueService` -> `project.mall.goods.impl.GoodsAttributeValueServiceImpl`

## `admin/WEB-INF/classes/spring/applicationContext-smsbao.xml`
- Bean `smsSendService` -> `smsbao.internal.SmsSendServiceImpl`
- Bean `internalSmsSenderService` -> `smsbao.internal.InternalSmsSenderServiceImpl`
- Bean `smsbaoServer` -> `smsbao.sender.SmsServer`
- Bean `smsbaoSendThreadPool` -> `kernel.concurrent.ThreadPoolTaskExecutor`
- Bean `smsbaoSendThreadRejectExecutingHandler` -> `kernel.util.RejectExecutionHandlerDelegator`

## `admin/WEB-INF/classes/spring/applicationContext-smsmoduyun.xml`
- Bean `smsSingleSender` -> `smsmoduyun.v2.yun.SmsSingleSender`

## `admin/WEB-INF/classes/spring/applicationContext-syspara.xml`
- Bean `sysparaService` -> `project.syspara.internal.SysparaServiceImpl`
- Bean `sysparaLoadCacheService` -> `project.data.loadcache.SysparaLoadCacheService`

## `admin/WEB-INF/classes/spring/applicationContext-tip_admin.xml`
- Dubbo interface: `project.tip.TipService`

## `admin/WEB-INF/classes/spring/applicationContext-user_admin.xml`
- Dubbo interface: `project.user.idcode.IdentifyingCodeService`
- Dubbo interface: `project.user.idcode.IdentifyingCodeTimeWindowService`
- Bean `userService` -> `project.user.internal.UserServiceImpl`
- Bean `onlineUserService` -> `project.user.internal.OnlineUserService`
- Bean `onlineUserTimeWindow` -> `project.user.internal.OnlineUserTimeWindow`
- Bean `adminKycService` -> ` project.user.kyc.internal.AdminKycServiceImpl`
- Bean `onlineChatUserMessageService` -> `project.onlinechat.internal.OnlineChatUserMessageServiceImpl`
- Bean `adminKycHighLevelService` -> ` project.user.kyc.internal.AdminKycHighLevelServiceImpl`
- Bean `paymentMethodService` -> `project.user.payment.internal.PaymentMethodServiceImpl`
- Bean `kycService` -> `project.user.kyc.internal.KycServiceImpl`
- Bean `kycHighLevelService` -> `project.user.kyc.internal.KycHighLevelServiceImpl`
- Bean `tokenService` -> `project.user.token.internal.TokenServiceImpl`
- Bean `userSafewordApplyService` -> `project.user.internal.UserSafewordApplyServiceImpl`
- Bean `adminUserSafewordApplyService` -> `project.user.internal.AdminUserSafewordApplyServiceImpl`
- Bean `googleAuthService` -> `project.user.googleauth.internal.GoogleAuthServiceImpl`

## `admin/WEB-INF/classes/spring/applicationContext-wallet_admin.xml`
- Dubbo interface: `project.wallet.AssetService`
- Bean `walletService` -> `project.wallet.internal.WalletServiceImpl`
- Bean `walletLogService` -> `project.wallet.internal.WalletLogServiceImpl`
- Bean `exchangeRateService` -> `project.wallet.rate.internal.ExchangeRateServiceImpl`

## `admin/WEB-INF/classes/spring/applicationContext-withdraw_admin.xml`
- Bean `adminWithdrawService` -> ` project.withdraw.internal.AdminWithdrawServiceImpl`
- Bean `withdrawService` -> `project.withdraw.internal.WithdrawServiceImpl`

## `admin/WEB-INF/classes/spring/applicationContext.xml`
- Bean `sessionFactory` -> `org.springframework.orm.hibernate5.LocalSessionFactoryBean`
- Bean `transactionManager` -> `org.springframework.orm.hibernate5.HibernateTransactionManager`
- Bean `transactionInterceptor` -> `org.springframework.transaction.interceptor.TransactionInterceptor`
- Bean `jdbcTemplate` -> `org.springframework.jdbc.core.JdbcTemplate`
- Bean `hibernateTemplate` -> `org.springframework.orm.hibernate5.HibernateTemplate`
- Bean `namedParameterJdbcTemplate` -> `org.springframework.jdbc.core.namedparam.NamedParameterJdbcTemplate`

## `api/WEB-INF/classes/spring/applicationContext-email.xml`
- Bean `emailSendService` -> `email.internal.EmailSendServiceImpl`
- Bean `internalEmailSenderService` -> `email.internal.InternalEmailSenderServiceImpl`
- Bean `emailServer` -> `email.sender.EmailServer`
- Bean `emailSendThreadPool` -> `kernel.concurrent.ThreadPoolTaskExecutor`
- Bean `emailSendThreadRejectExecutingHandler` -> `kernel.util.RejectExecutionHandlerDelegator`
- Bean `mailSender` -> `org.springframework.mail.javamail.JavaMailSenderImpl`
- Bean `mailMessage` -> `org.springframework.mail.SimpleMailMessage`
- Bean `freeMarkerConfigurer` -> `org.springframework.web.servlet.view.freemarker.FreeMarkerConfigurer`

## `api/WEB-INF/classes/spring/applicationContext-smsbao.xml`
- Bean `smsSendService` -> `smsbao.internal.SmsSendServiceImpl`
- Bean `internalSmsSenderService` -> `smsbao.internal.InternalSmsSenderServiceImpl`
- Bean `smsbaoServer` -> `smsbao.sender.SmsServer`
- Bean `smsbaoSendThreadPool` -> `kernel.concurrent.ThreadPoolTaskExecutor`
- Bean `smsbaoSendThreadRejectExecutingHandler` -> `kernel.util.RejectExecutionHandlerDelegator`

## `api/WEB-INF/classes/spring/applicationContext-smsmoduyun.xml`
- Bean `smsSingleSender` -> `smsmoduyun.v2.yun.SmsSingleSender`

## `data/WEB-INF/classes/spring/applicationContext-cms_data.xml`
- Dubbo interface: `project.cms.BannerService`
- Bean `cmsService` -> `project.cms.internal.CmsServiceImpl`
- Bean `cmsLoadCacheService` -> `project.cms.data.loadcache.CmsLoadCacheService`
- Bean `bannerService` -> `project.cms.internal.BannerServiceImpl`

## `data/WEB-INF/classes/spring/applicationContext-ddos.xml`
- Bean `ipHandleCacheService` -> `project.ddos.data.loadcache.IpHandleCacheService`

## `data/WEB-INF/classes/spring/applicationContext-dubbo.xml`
- Dubbo interface: `project.log.LogService`
- Dubbo interface: `project.log.CodeLogService`
- Dubbo interface: `project.log.SysLogService`
- Dubbo interface: `project.user.UserDataService`
- Dubbo interface: `project.miner.job.MinerOrderProfitService`

## `data/WEB-INF/classes/spring/applicationContext-email.xml`
- Bean `emailSendService` -> `email.internal.EmailSendServiceImpl`
- Bean `internalEmailSenderService` -> `email.internal.InternalEmailSenderServiceImpl`
- Bean `emailServer` -> `email.sender.EmailServer`
- Bean `emailSendThreadPool` -> `kernel.concurrent.ThreadPoolTaskExecutor`
- Bean `emailSendThreadRejectExecutingHandler` -> `kernel.util.RejectExecutionHandlerDelegator`
- Bean `mailSender` -> `org.springframework.mail.javamail.JavaMailSenderImpl`
- Bean `mailMessage` -> `org.springframework.mail.SimpleMailMessage`
- Bean `freeMarkerConfigurer` -> `org.springframework.web.servlet.view.freemarker.FreeMarkerConfigurer`

## `data/WEB-INF/classes/spring/applicationContext-exchange_data.xml`
- Dubbo interface: `project.exchange.job.ExchangeApplyOrderHandleJobService`
- Bean `exchangeApplyOrderService` -> `project.exchange.internal.ExchangeApplyOrderServiceImpl`
- Bean `exchangeApplyOrderHandleJob` -> `project.exchange.job.ExchangeApplyOrderHandleJob`
- Bean `exchangeApplyOrderHandleJobService` -> `project.exchange.job.ExchangeApplyOrderHandleJobServiceImpl`

## `data/WEB-INF/classes/spring/applicationContext-hobi_data.xml`
- Dubbo interface: `project.data.internal.KlineInitService`
- Dubbo interface: `project.hobi.HobiDataService`
- Dubbo interface: `project.data.AdjustmentValueService`
- Dubbo interface: `project.data.DataService`
- Bean `klineInitService` -> `project.data.internal.KlineInitServiceImpl`
- Bean `hobiDataService` -> `project.hobi.internal.HobiDataServiceImpl`
- Bean `cleanDataJob` -> `project.data.job.CleanDataJob`
- Bean `dataDBService` -> `project.data.internal.DataDBServiceImpl`
- Bean `klineService` -> `project.data.internal.KlineServiceImpl`
- Bean `klineCacheJob` -> `project.data.job.KlineCacheJob`
- Bean `dataServer` -> `project.data.job.DataServer`
- Bean `dataServerThreadPool` -> `kernel.concurrent.ThreadPoolTaskExecutor`
- Bean `dataServerThreadRejectExecutingHandler` -> `kernel.util.RejectExecutionHandlerDelegator`
- Bean `saveRealtimeServer` -> `project.data.job.SaveRealtimeServer`
- Bean `dataFrequencyServer` -> `project.data.job.DataFrequencyServer`
- Bean `adjustmentValueService` -> `project.data.internal.AdjustmentValueServiceImpl`
- Bean `dataService` -> `project.data.internal.RemoteDataServiceImpl`

## `data/WEB-INF/classes/spring/applicationContext-item_data.xml`
- Bean `itemService` -> `project.item.internal.ItemServiceImpl`
- Bean `itemLoadCacheService` -> `project.data.loadcache.ItemLoadCacheService`
- Bean `itemUserOptionalService` -> `project.item.internal.ItemUserOptionalServiceImpl`

## `data/WEB-INF/classes/spring/applicationContext-kernel.xml`
- Bean `pagedDao` -> `kernel.web.PagedQueryDaoImpl`
- Bean `jdbcTemplateWithPaging` -> `kernel.web.JdbcTemplateWithPaging`
- Bean `redisLocalCache` -> `kernel.cache.RedisLocalCache`
- Bean `twoDimensionCodeContentService` -> `kernel.service.TwoDimensionCodeContentServiceImpl`
- Bean `messageSource` -> `org.springframework.context.support.ResourceBundleMessageSource`

## `data/WEB-INF/classes/spring/applicationContext-log_data.xml`
- Bean `logService` -> `project.log.internal.LogServiceImpl`
- Bean `moneyLogService` -> `project.log.internal.MoneyLogServiceImpl`
- Bean `orderLogService` -> `project.mall.log.impl.OrderLogServiceImpl`
- Bean `sysLogService` -> `project.log.internal.SysLogServiceImpl`
- Bean `saveLogServer` -> `project.log.internal.SaveLogServer`
- Bean `codeLogService` -> `project.log.internal.CodeLogServiceImpl`

## `data/WEB-INF/classes/spring/applicationContext-mall.xml`
- Bean `mallLoadCacheService` -> `project.mall.loadcache.MallLoadCacheService`
- Bean `adminSellerService` -> `project.mall.seller.impl.AdminSellerServiceImpl`
- Bean `sellerGoodsService` -> `project.mall.goods.impl.SellerGoodsServiceImpl`
- Bean `comboService` -> `project.mall.combo.impl.ComboServiceImpl`
- Bean `adminSystemCommentService` -> `project.mall.comment.impl.AdminSystemCommentServiceImpl`
- Bean `evaluationService` -> `project.mall.evaluation.impl.EvaluationServiceImpl`
- Bean `goodsOrdersService` -> `project.mall.orders.internal.GoodsOrdersServiceImpl`
- Bean `walletDayService` -> `project.invest.walletday.impl.WalletDayServiceImpl`
- Bean `sellerService` -> `project.mall.seller.impl.SellerServiceImpl`
- Bean `moneyFreezeService` -> `project.log.internal.MoneyFreezeServiceImpl`
- Bean `goodsStatisticsService` -> `project.mall.goods.impl.GoodsStatisticsServiceImpl`
- Bean `keepGoodsService` -> `project.mall.goods.impl.KeepGoodsServiceImpl`
- Bean `mallLevelService` -> `project.mall.seller.impl.MallLevelServiceImpl`

## `data/WEB-INF/classes/spring/applicationContext-miner_data.xml`
- Bean `minerService` -> `project.miner.internal.MinerServiceImpl`
- Bean `minerOrderService` -> `project.miner.internal.MinerOrderServiceImpl`
- Bean `minerOrderProfitService` -> `project.miner.job.MinerOrderProfitServiceImpl`
- Bean `minerOrderProfitJob` -> `project.miner.job.MinerOrderProfitJob`
- Bean `minerLoadCacheService` -> `project.miner.data.loadcache.MinerLoadCacheService`

## `data/WEB-INF/classes/spring/applicationContext-news_data.xml`
- Bean `newsService` -> `project.news.internal.NewsServiceImpl`
- Bean `newsLoadCacheService` -> `project.news.data.loadcache.NewsLoadCacheService`

## `data/WEB-INF/classes/spring/applicationContext-notify.xml`
- Dubbo interface: `project.mall.notification.utils.notify.client.CommonNotifyService`
- Dubbo interface: `project.mall.notification.utils.notify.client.CommonNotifyService`
- Dubbo interface: `project.mall.notification.utils.notify.client.NotificationHelperClient`
- Dubbo interface: `project.mall.notification.utils.notify.client.NotificationHelperClient`
- Dubbo interface: `project.user.idcode.IdentifyingCodeService`
- Dubbo interface: `project.user.idcode.IdentifyingCodeTimeWindowService`
- Bean `notificationService` -> `project.mall.notification.impl.NotificationServiceImpl`
- Bean `notificationTemplateService` -> `project.mall.notification.impl.NotificationTemplateServiceImpl`
- Bean `commonNotifyManager` -> `project.mall.notification.utils.notify.CommonNotifyManager`
- Bean `defaultNotifyHandler` -> `project.mall.notification.utils.notify.handler.DefaultNotifyHandler`
- Bean `defaultEmailNotifyHandler` -> `project.mall.notification.utils.notify.handler.DefaultEmailNotifyHandler`
- Bean `smsBaoNotifyHandler` -> `project.mall.notification.utils.notify.handler.SmsBaoNotifyHandler`
- Bean `notificationHelper` -> `project.mall.notification.NotificationHelper`
- Bean `emailSendService` -> `email.internal.EmailSendServiceImpl`
- Bean `internalEmailSenderService` -> `email.internal.InternalEmailSenderServiceImpl`
- Bean `emailServer` -> `email.sender.EmailServer`
- Bean `emailSendThreadPool` -> `kernel.concurrent.ThreadPoolTaskExecutor`
- Bean `emailSendThreadRejectExecutingHandler` -> `kernel.util.RejectExecutionHandlerDelegator`
- Bean `mailSender` -> `org.springframework.mail.javamail.JavaMailSenderImpl`
- Bean `mailMessage` -> `org.springframework.mail.SimpleMailMessage`
- Bean `freeMarkerConfigurer` -> `org.springframework.web.servlet.view.freemarker.FreeMarkerConfigurer`
- Bean `identifyingCodeService` -> `project.user.idcode.internal.IdentifyingCodeServiceImpl`
- Bean `identifyingCodeTimeWindowService` -> `project.user.idcode.IdentifyingCodeTimeWindow`
- Bean `blacklistIpTimeWindow` -> `project.user.idcode.BlacklistIpTimeWindow`
- Bean `sendCountTimeWindow` -> `project.user.idcode.SendCountTimeWindow`

## `data/WEB-INF/classes/spring/applicationContext-online_chat_data.xml`
- Dubbo interface: `project.onlinechat.OnlineChatMessageService`
- Dubbo interface: `project.onlinechat.OnlineChatVisitorMessageService`
- Dubbo interface: `project.onlinechat.OnlineChatUserMessageService`
- Bean `onlineChatMessageService` -> `project.onlinechat.internal.OnlineChatMessageServiceImpl`
- Bean `onlineChatVisitorMessageService` -> `project.onlinechat.internal.OnlineChatVisitorMessageServiceImpl`
- Bean `onlineChatUserMessageService` -> `project.onlinechat.internal.OnlineChatUserMessageServiceImpl`

## `data/WEB-INF/classes/spring/applicationContext-party.xml`
- Bean `partyService` -> `project.party.internal.PartyServiceImpl`
- Bean `userRecomService` -> `project.party.recom.internal.UserRecomServiceImpl`
- Bean `partyLoadCacheService` -> `project.data.loadcache.PartyLoadCacheService`

## `data/WEB-INF/classes/spring/applicationContext-recharge_blockchain_data.xml`
- Bean `rechargeBlockchainService` -> `project.blockchain.internal.RechargeBlockchainServiceImpl`
- Bean `channelBlockchainService` -> `project.blockchain.internal.ChannelBlockchainServiceImpl`
- Bean `qRProducerService` -> `project.blockchain.internal.QRProducerServiceImpl`
- Bean `rechargeBonusService` -> `project.bonus.internal.RechargeBonusServiceImpl`

## `data/WEB-INF/classes/spring/applicationContext-redis.xml`
- Bean `redis` -> `project.redis.interal.Redis`
- Bean `redisHandler` -> `project.redis.interal.RedisHandlerImpl`
- Bean `redisHandlerThreadPool` -> `kernel.concurrent.ThreadPoolTaskExecutor`
- Bean `redisHandlerThreadRejectExecutingHandler` -> `kernel.util.RejectExecutionHandlerDelegator`

## `data/WEB-INF/classes/spring/applicationContext-security_data.xml`
- Bean `passwordEncoder` -> `org.springframework.security.providers.encoding.Md5PasswordEncoder`
- Bean `secUserService` -> `security.internal.SecUserServiceImpl`
- Bean `roleService` -> `security.internal.RoleServiceImpl`
- Bean `securityAuthoritiesHolder` -> `security.internal.SecurityAuthoritiesHolderImpl`

## `data/WEB-INF/classes/spring/applicationContext-security_systemuse_data.xml`
- Dubbo interface: `systemuser.CustomerService`
- Bean `customerService` -> `systemuser.internal.CustomerServiceImpl`

## `data/WEB-INF/classes/spring/applicationContext-service.xml`
- Bean `initHandle` -> `project.data.InitHandle`
- Bean `loadCacheService` -> `project.data.loadcache.LoadCacheService`
- Bean `consumerStateHandle` -> `project.data.consumer.ConsumerStateHandle`
- Bean `userDataService` -> `project.data.UserDataServiceImpl`

## `data/WEB-INF/classes/spring/applicationContext-smsbao.xml`
- Bean `smsSendService` -> `smsbao.internal.SmsSendServiceImpl`
- Bean `internalSmsSenderService` -> `smsbao.internal.InternalSmsSenderServiceImpl`
- Bean `smsbaoServer` -> `smsbao.sender.SmsServer`
- Bean `smsbaoSendThreadPool` -> `kernel.concurrent.ThreadPoolTaskExecutor`
- Bean `smsbaoSendThreadRejectExecutingHandler` -> `kernel.util.RejectExecutionHandlerDelegator`

## `data/WEB-INF/classes/spring/applicationContext-smsmoduyun.xml`
- Bean `smsSingleSender` -> `smsmoduyun.v2.yun.SmsSingleSender`

## `data/WEB-INF/classes/spring/applicationContext-syspara.xml`
- Bean `sysparaService` -> `project.syspara.internal.SysparaServiceImpl`
- Bean `sysparaLoadCacheService` -> `project.data.loadcache.SysparaLoadCacheService`

## `data/WEB-INF/classes/spring/applicationContext-task.xml`
- Bean `dataTask` -> `project.data.task.DataTask`
- Bean `taskJobHandle` -> `project.data.task.TaskJobHandle`
- Bean `backupTask_60_minute` -> `db.job.BackupJob`
- Bean `klineTask_1_minute` -> `project.data.klinejob.Kline1MinuteJob`
- Bean `klineTask_5_minute` -> `project.data.klinejob.Kline5MinuteJob`
- Bean `klineTask_15_minute` -> `project.data.klinejob.Kline15MinuteJob`
- Bean `klineTask_30_minute` -> `project.data.klinejob.Kline30MinuteJob`
- Bean `klineTask_60_minute` -> `project.data.klinejob.Kline60MinuteJob`
- Bean `klineTask_4_hour` -> `project.data.klinejob.Kline4HourJob`
- Bean `klineTask_1_day` -> `project.data.klinejob.Kline1DayJob`
- Bean `klineTask_1_week` -> `project.data.klinejob.Kline1WeekJob`
- Bean `klineTask_1_month` -> `project.data.klinejob.Kline1MonJob`
- Bean `recharegeBonus1DayJob` -> `project.bonus.job.RecharegeBonus1DayJob`
- Bean `mallOrdersJob` -> `project.mall.task.MallOrdersJob`

## `data/WEB-INF/classes/spring/applicationContext-tip_data.xml`
- Dubbo interface: `project.tip.TipService`
- Bean `tipService` -> `project.tip.internal.TipServiceImpl`

## `data/WEB-INF/classes/spring/applicationContext-trader_data.xml`
- Dubbo interface: `project.follow.TraderOrderService`
- Dubbo interface: `project.follow.TraderUserService`
- Dubbo interface: `project.follow.TraderService`
- Dubbo interface: `project.follow.TraderFollowUserService`
- Dubbo interface: `project.follow.TraderFollowUserOrderService`
- Bean `traderService` -> `project.follow.internal.TraderServiceImpl`
- Bean `traderFollowUserService` -> `project.follow.internal.TraderFollowUserServiceImpl`
- Bean `traderFollowUserOrderService` -> `project.follow.internal.TraderFollowUserOrderServiceImpl`
- Bean `traderUserService` -> `project.follow.internal.TraderUserServiceImpl`
- Bean `traderOrderService` -> `project.follow.internal.TraderOrderServiceImpl`

## `data/WEB-INF/classes/spring/applicationContext-user_data.xml`
- Bean `userLoadCacheService` -> `project.user.data.loadcache.UserLoadCacheService`
- Bean `userService` -> `project.user.internal.UserServiceImpl`
- Bean `tokenService` -> `project.user.token.internal.TokenServiceImpl`
- Bean `kycService` -> `project.user.kyc.internal.KycServiceImpl`
- Bean `kycHighLevelService` -> `project.user.kyc.internal.KycHighLevelServiceImpl`

## `data/WEB-INF/classes/spring/applicationContext-wallet_data.xml`
- Dubbo interface: `project.wallet.AssetService`
- Bean `walletService` -> `project.wallet.internal.WalletServiceImpl`
- Bean `walletLogService` -> `project.wallet.internal.WalletLogServiceImpl`
- Bean `exchangeRateService` -> `project.wallet.rate.internal.ExchangeRateServiceImpl`
- Bean `walletLoadCacheService` -> `data.loadcache.WalletLoadCacheService`
- Bean `walletDao` -> `project.wallet.consumer.WalletDaoImpl`
- Bean `walletConsumeServer` -> `project.wallet.consumer.WalletConsumeServer`
- Bean `walletExtendConsumeServer` -> `project.wallet.consumer.WalletExtendConsumeServer`
- Bean `exchangeRatePullService` -> `project.wallet.rate.job.ExchangeRatePullServiceImpl`
- Bean `exchangeRatePullJob` -> `project.wallet.rate.job.ExchangeRatePullJob`
- Bean `assetService` -> `project.wallet.internal.AssetServiceImpl`

## `data/WEB-INF/classes/spring/applicationContext.xml`
- Bean `sessionFactory` -> `org.springframework.orm.hibernate5.LocalSessionFactoryBean`
- Bean `transactionManager` -> `org.springframework.orm.hibernate5.HibernateTransactionManager`
- Bean `transactionInterceptor` -> `org.springframework.transaction.interceptor.TransactionInterceptor`
- Bean `hibernateTemplate` -> `org.springframework.orm.hibernate5.HibernateTemplate`
- Bean `namedParameterJdbcTemplate` -> `org.springframework.jdbc.core.namedparam.NamedParameterJdbcTemplate`
- Bean `jdbcTemplate` -> `org.springframework.jdbc.core.JdbcTemplate`
