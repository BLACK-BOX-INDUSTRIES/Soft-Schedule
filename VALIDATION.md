# 1.4.0 试用分享包验证

- 签名、版本、Bundle ID及试用标记检查通过：BBDistributionKind=trial，BBTrialEnabled=true。
- ZIP只包含试用应用和说明，不含用户数据、试用记录、源码或开发版。
- 解压后程序与试用构建逐字节一致。
- 离线计时、回拨与恢复、到期操作限制及数据保留经过测试；到期界面已实际验证。
- SHA-256见 distribution.json。
