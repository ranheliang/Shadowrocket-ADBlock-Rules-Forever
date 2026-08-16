# Shadowrocket 规则配置

> 本仓库已改为使用 **ranheliang** 自己的导入地址；推荐使用 lazy_group_safe.conf 安全优化版。

## 推荐导入

### 懒人配置-含策略组（安全优化版）

小火箭导入地址：

`	ext
https://raw.githubusercontent.com/ranheliang/Shadowrocket-ADBlock-Rules-Forever/release/lazy_group_safe.conf
`

这个版本已做以下安全处理：

- DNS 使用 DoH：阿里 DNS / 腾讯 DNSPod
- 关闭 IPv6，减少异常解析和泄漏概率
- 默认不启用 MITM/HTTPS 解密
- 策略组名称保持原样，方便兼容原有节点/分组习惯
- 增加 社媒营销 策略组：WhatsApp / Instagram / LinkedIn / Facebook / TikTok / X / Telegram / Pinterest / Reddit

## 其它可选配置

### 懒人配置-含策略组（安全优化版）

推荐使用：DNS/IPv6/MITM 已做安全优化，策略组名称保持原样。

规则地址：<https://raw.githubusercontent.com/ranheliang/Shadowrocket-ADBlock-Rules-Forever/release/lazy_group_safe.conf>

![二维码](https://api.qrserver.com/v1/create-qr-code/?size=260x260&data=https%3A%2F%2Fraw.githubusercontent.com%2Franheliang%2FShadowrocket-ADBlock-Rules-Forever%2Frelease%2Flazy_group_safe.conf)

### 懒人配置-不含策略组

不含策略组版本。

规则地址：<https://raw.githubusercontent.com/ranheliang/Shadowrocket-ADBlock-Rules-Forever/release/lazy.conf>

![二维码](https://api.qrserver.com/v1/create-qr-code/?size=260x260&data=https%3A%2F%2Fraw.githubusercontent.com%2Franheliang%2FShadowrocket-ADBlock-Rules-Forever%2Frelease%2Flazy.conf)

### Top500 黑名单 + 去广告

常规代理分流，含广告过滤。

规则地址：<https://raw.githubusercontent.com/ranheliang/Shadowrocket-ADBlock-Rules-Forever/release/sr_top500_banlist_ad.conf>

![二维码](https://api.qrserver.com/v1/create-qr-code/?size=260x260&data=https%3A%2F%2Fraw.githubusercontent.com%2Franheliang%2FShadowrocket-ADBlock-Rules-Forever%2Frelease%2Fsr_top500_banlist_ad.conf)

### Top500 白名单 + 去广告

白名单分流，含广告过滤。

规则地址：<https://raw.githubusercontent.com/ranheliang/Shadowrocket-ADBlock-Rules-Forever/release/sr_top500_whitelist_ad.conf>

![二维码](https://api.qrserver.com/v1/create-qr-code/?size=260x260&data=https%3A%2F%2Fraw.githubusercontent.com%2Franheliang%2FShadowrocket-ADBlock-Rules-Forever%2Frelease%2Fsr_top500_whitelist_ad.conf)

### CNIP + 去广告

按中国 IP/域名分流，含广告过滤。

规则地址：<https://raw.githubusercontent.com/ranheliang/Shadowrocket-ADBlock-Rules-Forever/release/sr_cnip_ad.conf>

![二维码](https://api.qrserver.com/v1/create-qr-code/?size=260x260&data=https%3A%2F%2Fraw.githubusercontent.com%2Franheliang%2FShadowrocket-ADBlock-Rules-Forever%2Frelease%2Fsr_cnip_ad.conf)

### 全直连 + 去广告

仅保留广告拦截场景。

规则地址：<https://raw.githubusercontent.com/ranheliang/Shadowrocket-ADBlock-Rules-Forever/release/sr_direct_banad.conf>

![二维码](https://api.qrserver.com/v1/create-qr-code/?size=260x260&data=https%3A%2F%2Fraw.githubusercontent.com%2Franheliang%2FShadowrocket-ADBlock-Rules-Forever%2Frelease%2Fsr_direct_banad.conf)

### 全代理 + 去广告

全代理场景，含广告过滤。

规则地址：<https://raw.githubusercontent.com/ranheliang/Shadowrocket-ADBlock-Rules-Forever/release/sr_proxy_banad.conf>

![二维码](https://api.qrserver.com/v1/create-qr-code/?size=260x260&data=https%3A%2F%2Fraw.githubusercontent.com%2Franheliang%2FShadowrocket-ADBlock-Rules-Forever%2Frelease%2Fsr_proxy_banad.conf)

### 海外回国 + 去广告

海外访问中国服务场景。

规则地址：<https://raw.githubusercontent.com/ranheliang/Shadowrocket-ADBlock-Rules-Forever/release/sr_backcn_ad.conf>

![二维码](https://api.qrserver.com/v1/create-qr-code/?size=260x260&data=https%3A%2F%2Fraw.githubusercontent.com%2Franheliang%2FShadowrocket-ADBlock-Rules-Forever%2Frelease%2Fsr_backcn_ad.conf)

### 仅去广告

只做广告拦截规则。

规则地址：<https://raw.githubusercontent.com/ranheliang/Shadowrocket-ADBlock-Rules-Forever/release/sr_ad_only.conf>

![二维码](https://api.qrserver.com/v1/create-qr-code/?size=260x260&data=https%3A%2F%2Fraw.githubusercontent.com%2Franheliang%2FShadowrocket-ADBlock-Rules-Forever%2Frelease%2Fsr_ad_only.conf)

## 说明

- 小火箭扫码导入时，请确认地址开头是 https://raw.githubusercontent.com/ranheliang/Shadowrocket-ADBlock-Rules-Forever/release/。
- 如果看到旧地址，说明扫到的不是本仓库新版配置。
- 本仓库保留 LICENSE 开源许可证文件，避免许可证信息缺失。
