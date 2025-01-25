# Mihomo-Party-Rules 仅个人托管配置使用！
对于 Apple 分流规则
请参考 blog.royli.dev/2019/better-proxy-rules-for-apple-services 这篇文章

对于本项目

AppleRules 是与本地化息息相关的规则，比如地图、天气、查找、Facetime、Apple Pay ( iCloud 上传与下载也归于此规则集

AppleCDNRules 是苹果的全球 CDN

AppleNoChinaCDNRules 是大陆没有的 CDN 节点

AppleAPIRules 是苹果的 API 域名

请把 NoChinaCDN 和 APIRules 放在最前面

使用中国区账号（App Store + iCloud）
AppleRules 直连

AppleCDNRules 直连

AppleNoChinaCDNRules 代理

AppleAPIRules 直连

使用美国区账号（App Store + iCloud）
AppleRules 直连

AppleCDNRules 直连

AppleNoChinaCDNRules 代理

AppleAPIRules 代理

建议 AppleAPIRules 依然直连，上文是根据上述文章给出的建议，请结合自身情况使用
