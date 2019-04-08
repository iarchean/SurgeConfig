# My Surge config

[配置示例](https://raw.githubusercontent.com/ydzydzydz/Rules/master/conf/zhuangzhuang/zhuangzhuang.conf)   

**在iCloud云盘Surge文件夹中加入[auto.list](https://raw.githubusercontent.com/ydzydzydz/Rules/master/proxy/auto.list) 和[all.list](https://raw.githubusercontent.com/ydzydzydz/Rules/master/proxy/all.list)**

----
# 规则参考

[lhie1](https://github.com/lhie1/Rules)   
[scomper](https://github.com/scomper/surge-list)  
[Blankwonder](https://github.com/Blankwonder/surge-list)  
[Hackl0us](https://github.com/Hackl0us/SS-Rule-Snippet)  
[ConnersHua](https://github.com/ConnersHua/Profiles)  

----
# RULE-SET

从GitHub更新RULE-SET规则提醒
```
AND,((DOMAIN,raw.githubusercontent.com),(USER-AGENT,Surge*)),DIRECT,notification-text="外部资源正在更新!😀",notification-interval=3
```
特殊代理示例
```
RULE-SET,https://raw.githubusercontent.com/ydzydzydz/Rules/master/special/apple.list,DIRECT
```
----
# 特殊代理
**将特殊代理放在规则最前生效** 

---

























