# Ad Filter For AdGuard  

> 　　这是一个适用于AdGuard的广告拦截规则，配合官方拦截规则能有效阻止绝大部分中国互联网的广告，目前已覆盖极光推送服务、腾讯崩溃日志分析平台、OPPO/VIVO/小米在部分界面提供的广告、部分App内的某些广告以及一些常见的广告联盟。由于此规则由个人维护且以个人使用为目的，所以可能有误拦截的情况发生。最后个人的努力一定拧不过官方，所以拦不住也别怨我，除了手段不专业用的软件也少。  

- [GitHub仓库](https://github.com/KiryChanOfficial/AdFilterForAdGuard)  
- [AdGuard官网](https://adguard.com/)  

## 订阅链接:  
`https://ad.kirychan.com/KR_DNS_Filter.txt`  
`https://ad.kirychan.com/QuantunultX.conf`  

## 重要通知  
1. 由于个人原因已不再使用AdGuard且部分拦截规则搜集自网络，所以本订阅地址更新频率和拦截准确性将进一步降低。  
2. 于2025.08.03新增一个独立订阅规则，此规则收集自其他Github仓库并进行去重等操作，请酌情使用，仓库信息如下。  
    > [AWAvenue 秋风广告规则](https://raw.githubusercontent.com/TG-Twilight/AWAvenue-Ads-Rule/main/AWAvenue-Ads-Rule.txt)  
    > [不是DD啊](https://raw.githubusercontent.com/afwfv/DD-AD/main/rule/DD-AD.txt)  
    > [大萌主](https://raw.githubusercontent.com/damengzhu/banad/main/jiekouAD.txt)  
    > [海哥改](https://raw.githubusercontent.com/2771936993/HG/main/hg1.txt)  
    > [逆向涉猎](https://raw.githubusercontent.com/790953214/qy-Ads-Rule/main/black.txt)  
    > [下个ID见](https://raw.githubusercontent.com/2Gardon/SM-Ad-FuckU-hosts/master/SMAdHosts)  
    > [那个谁520](https://raw.githubusercontent.com/qq5460168/666/master/rules.txt)  


## 已知问题  
- 目前已发现以下问题，如有以下需要请临时关闭此规则列表或AdGuard。  
    > 1. 微信内网址反馈页面无法打开。  
    > 2. 123云盘APP无法使用。  
    > 3. 部分app在使用此规则首次打开时可能会功能异常，关闭重新进入app等几秒再打开拦截并重新进入app即可。

## 更新记录：  
- 2025.10.31  
    > 1. 修正Quantumult X规则（此后此规则的修正将不再写入记录，不包含更新）  

- 2025.10.29
    > 1. 将扩展规则整合进主规则  
	> 2. 拦截规则更新  
    > 3. 新增Quantumult X分流规则（测试），黑名单由主规则转换  

- 2025.10.24  
    > 1. 扩展规则更新  

- 2025.08.21  
    > 1. 再次更新两条有关`七猫小说`的拦截规则。  

- 2025.08.10  
    > 1. 主规则删除一条有关`七猫小说`的拦截规则，由用户 [qq5460168](https://github.com/KiryChanOfficial/AdFilterForAdGuard/issues/5) 提供。  
	> 2. 扩展规则删除一条有关`七猫小说`的拦截规则。  

- 2025.08.03  
    > 1. 新增两项VIVO浏览器拦截内容。  
    > 2. 新增测试版拦截内容，拦截规则收集自其他仓库，整合后可能出现不稳定情况。  
    > 3. 更改版本号建立规则。  

- 2025.07.27  
    > 1. 已临时移除该拦截项 `api*.toutiaoapi.com` ，此问题可能导致导致iOS平台今日头条无法正常。感谢用户 [qq5460168](https://github.com/KiryChanOfficial/AdFilterForAdGuard/issues/4) 的反馈。

- 2025.07.19  
    > 1. 更新了部分规则。  

- 2025.07.13  
    > 1. 持续更新中，由于`七猫小说`的更新目前已无法做到完全无广。  
    > 2. 拦截列表排版更新，已经不想再查询ICP后手动分类了。  

- 2025.07.02  
    > 1. 继续屏蔽`七猫小说`内的广告和一个`哔哩哔哩`链接  
    > 2. 摆烂了，域名懒得去分类了，如果用不了反馈后可临时关闭软件或添加白名单。  
    > 3. 无法核实的软件若不提供白名单则不会处理。  

- 2025.06.21  
    > 1. 更新部分`腾讯`、`七猫小说`、`厂商广告`等拦截项  
    > 2. 牛马又进厂了，这个世界挣得少可不行  

- 2025.05.17  
    > 1. 新增`AM广告`  
    > 2. 合并并更新大量规则，可能出现不稳定情况。（规则搜集自[酷安用户@Appea](https://www.coolapk.com/feed/63858856)）  

- 2025.05.11  
    > 1. 新增拦截项`趣盟广告`、`拼多多某拦截项`（测试：因为此链接出现在不该出现的地方）。  
    > 2. 更新拦截项`VIVO广告服务`。  
    > 3. 调整了历史更新记录的内容（纯属强迫症）。  

- 2025.05.04  
    > 1. 已删除用户 [qq5460168
](https://github.com/KiryChanOfficial/AdFilterForAdGuard/issues/3) 反馈的链接。  

- 2025.03.20  
    > 1. 解决`京东APP`异常载入/无法载入  
    > 2. 新增`OPPO天气/浏览器广告`（规则收集自[酷安用户@皮城的小鳄鱼](https://www.coolapk.com/feed/62763861)）  

- 2025.03.02  
    > 1. 新增拦截项`佳投广告（测试）`  
    > 2. 优化`腾讯广告服务`（也可能优化了个寂寞）  
    > 3. 删除了合并之后的ADG官方规则  
    > 4. 添加仓库地址

- 2025.02.09  
    > 1. 新增拦截项`百度联盟`、`哔哩哔哩开屏广告（测试）`  
    > 2. `AdGuard DNS Filter (unofficial)` 日常更新。  

- 2024.12.28  
    > 1. 测试功能：新增VIVO广告拦截（由VIVO提供的广告服务，并非VIVO系统中的广告）  
    > 2. `AdGuard DNS Filter (unofficial)` 日常更新。  

- 2024.12.13  
    > 1. 解决了部分情况下`淘宝系APP`无法登录的情况。  
    > 2. 合并了AdGuard ios端与Android端的拦截列表，并经过去重操作。使用此订阅时可关闭官方拦截规则（但此规则更新不及时）。  

- 2024.11.24  
    > 1. 本次更新大量规则，可能会出现问题。  
    > 2. 包含`快手`、`百度`、`阿里`、`腾讯`、`京东`以及一些`无法确定归属`的服务。  

- 2024.10.05  
    > 1. `七猫小说`、`酷安`目前已实现无广告。  