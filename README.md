# Rules
自用clash规则

如需要使用，请调整配置文件

Online.ini需要替换或去掉🗺️ 自定义代理,📍 自定义拦截,⛩️ 自定义直连

Rule.yaml需要替换或去掉对应的addproxy、addblock、adddirect

rule基于lhie1大佬规则修改

Online.ini基于ACL4SSR修改

- 修改策略组名称
- 更换steam、Domestic规则源为 LM-Firefly/Rules/master/Clash-RuleSet-Classical/
- 替换为自定义amazon规则，不含cn域名，便于拆分使用amazon国内外服务
- 添加niconico规则
- 添加Twitter、Facebook规则源（LM-Firefly/Rules/master/Clash-RuleSet-Classical/PROXY/），并与Telegram、Discord合并入SNS
- 添加Adblock（LM-Firefly/Rules/master/Clash-RuleSet-Classical/Adblock/）
- 去除部分重复规则

因谷歌ip定位问题YouTube premium易失效，需要经常更换ip，youtube及youtube music单独拆出

# 感谢

lhie1 / Rules

LM-Firefly / Rules

ACL4SSR / ACL4SSR

DivineEngine / Profiles
