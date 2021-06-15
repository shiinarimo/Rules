# Rules
自用clash规则

请在订阅转换器内使用[订阅转换规则](https://raw.githubusercontent.com/zy41501/Rules/main/%E8%A7%84%E5%88%99/%E8%AE%A2%E9%98%85%E8%BD%AC%E6%8D%A2%E8%A7%84%E5%88%99.ini)

基于lhie1大佬规则修改

基于ACL4SSR修改

- 修改策略组名称
- 更换steam、Domestic规则源为 LM-Firefly/Rules/master/Clash-RuleSet-Classical/
- 替换为自定义amazon规则，不含cn域名，便于拆分使用amazon国内外服务
- 添加niconico规则 
 
   // niconico部分视频播放依赖AWS（media-amazon.com），该条域名添加在amazon规则下
- 添加Twitter、Facebook规则源（LM-Firefly/Rules/master/Clash-RuleSet-Classical/PROXY/），并与Telegram、Discord合并入SNS
- 添加Adblock（LM-Firefly/Rules/master/Clash-RuleSet-Classical/Adblock/）
- 去除部分重复规则

因谷歌ip定位问题YouTube premium易失效，需要经常更换ip，youtube及youtube music单独拆出

# 感谢

lhie1 / Rules

LM-Firefly / Rules

ACL4SSR / ACL4SSR

DivineEngine / Profiles
