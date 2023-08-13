# AdguardFilter

> **Note**
> ### 本规则适用于
> - 规则无法去除的广告
> - DNS污染以及其他原因

## 功能介绍

|文件名|功能|
|-|-|
|dnsList.txt|基于DNS的广告过滤器，个人使用中为去除的广告|
|filterList.txt|基于过滤规则的过滤器，个人使用中为去除的广告|
|dnsSpecial.txt|受 `/etc/hosts/` 去广告语法启发，使用dsn过滤实现<br>安卓非root模式下无法编辑host的问题，实现域名<br>解析指定|

## Adguard规则介绍

### [过滤器](https://adguard.com/kb/zh-CN/general/ad-filtering/create-own-filters/)


### [DNS](https://adguardteam.github.io/KnowledgeBaseDNS/zh-CN/general/dns-filtering-syntax/)

- Adblock 风格语法
- `/etc/hosts/` 语法
- Domain-only 语法

## 过滤器和DNS的区别

过滤器相比于DNS而言，其功能更加强大，可以实现更加**精确**的广告过滤能力。  
DNS过滤相对而言过滤粗糙了点，但是其性能上应该是更高效的。  
选取时，根据场景使用即可，无好坏之分，只是在各个领域有不同的特定罢了。