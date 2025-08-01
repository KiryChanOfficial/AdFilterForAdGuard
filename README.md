# Ad Filter For AdGuard  

> 　　这是一个适用于AdGuard的广告拦截规则，配合官方拦截规则能有效阻止绝大部分中国互联网的广告，目前已覆盖极光推送服务、腾讯崩溃日志分析平台、OPPO/VIVO/小米在部分界面提供的广告、部分App内的某些广告以及一些常见的广告联盟。由于此规则由个人维护且以个人使用为目的，所以可能有误拦截的情况发生。  

## 订阅链接:  
`https://ad.kirychan.com/KR_DNS_Filter.txt`  

## 重要通知  
　　由于个人原因已不再使用AdGuard且部分拦截规则搜集自网络，所以本订阅地址更新频率和拦截准确性将进一步降低。  

- [GitHub仓库](https://github.com/KiryChanOfficial/AdFilterForAdGuard)  
- [AdGuard官网](https://adguard.com/)  

## 已知问题  
- 目前已发现以下问题，如有以下需要请临时关闭此规则列表或AdGuard。  
> 1. 微信内网址反馈页面无法打开。  
> 2. 123云盘APP无法使用。  
> 3. 部分app在使用此规则首次打开时可能会功能异常，关闭重新进入app等几秒再打开拦截并重新进入app即可。

## 更新记录：  
- 2025.07.27  
> 已临时移除该拦截项 `api*.toutiaoapi.com` ，此问题可能导致导致iOS平台今日头条无法正常。感谢用户 [qq5460168](https://github.com/KiryChanOfficial/AdFilterForAdGuard/issues/4) 的反馈。

- 2025.07.19  
> 更新了部分规则。  

- 2025.07.13  
> 持续更新中，由于`七猫小说`的更新目前已无法做到完全无广。  
> 拦截列表排版更新，已经不想再查询ICP后手动分类了。  

- 2025.07.02  
> 继续屏蔽`七猫小说`内的广告和一个`哔哩哔哩`链接  
> 摆烂了，域名懒得去分类了，如果用不了反馈后可临时关闭软件或添加白名单。  
> 无法核实的软件若不提供白名单则不会处理。  

- 2025.06.21  
> 更新部分`腾讯`、`七猫小说`、`厂商广告`等拦截项  
> 牛马又进厂了，这个世界挣得少可不行  

- 2025.05.17  
> 新增`AM广告`  
> 合并并更新大量规则，可能出现不稳定情况。（规则搜集自[酷安用户@Appea](https://www.coolapk.com/feed/63858856)）  

- 2025.05.11  
> 新增拦截项`趣盟广告`、`拼多多某拦截项`（测试：因为此链接出现在不该出现的地方）。  
> 更新拦截项`VIVO广告服务`。  
> 调整了历史更新记录的内容（纯属强迫症）。  

- 2025.05.04  
> 已删除用户 [qq5460168
](https://github.com/KiryChanOfficial/AdFilterForAdGuard/issues/3) 反馈的链接。  

- 2025.03.20  
> 解决`京东APP`异常载入/无法载入  
> 新增`OPPO天气/浏览器广告`（规则收集自[酷安用户@皮城的小鳄鱼](https://www.coolapk.com/feed/62763861)）  

- 2025.03.02  
> 新增拦截项`佳投广告（测试）`  
> 优化`腾讯广告服务`（也可能优化了个寂寞）  
> 删除了合并之后的ADG官方规则  
> 添加仓库地址

- 2025.02.09  
> 新增拦截项`百度联盟`、`哔哩哔哩开屏广告（测试）`  
> `AdGuard DNS Filter (unofficial)` 日常更新。  

- 2024.12.28  
> 测试功能：新增VIVO广告拦截（由VIVO提供的广告服务，并非VIVO系统中的广告）  
> `AdGuard DNS Filter (unofficial)` 日常更新。  

- 2024.12.13  
> 解决了部分情况下`淘宝系APP`无法登录的情况。  
> 合并了AdGuard ios端与Android端的拦截列表，并经过去重操作。使用此订阅时可关闭官方拦截规则（但此规则更新不及时）。  

- 2024.11.24  
> 本次更新大量规则，可能会出现问题。  
> 包含`快手`、`百度`、`阿里`、`腾讯`、`京东`以及一些`无法确定归属`的服务。  

- 2024.10.05  
> `七猫小说`、`酷安`目前已实现无广告。  