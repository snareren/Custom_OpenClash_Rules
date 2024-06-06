## Fork from  
- [Aethersailor/Custom_OpenClash_Rules](https://github.com/Aethersailor/Custom_OpenClash_Rules)

## 目的 
* 媒体服务（Youtube、Netflix、Disney+ 等）走指定节点，特定网站（电报、ChatGPT 等）走指定区域节点测速选优或特定节点  
* 特定网站（苹果服务、微软服务以及国内域名 IP 等）走直连，其他国外网站走指定节点，节点需要按照区域自动测速选优     
* 杜绝 DNS 泄露，且大陆域名和 IP 绕过 OpenClash 内核提升访问速度和下载性能  
* 兼容 IPv6，实现 IPv6 完美分流  
* 广告拦截  
* 定时自动更新上游规则，无人值守

## 使用方法  

https://github.com/Aethersailor/Custom_OpenClash_Rules/wiki/OpenClash-设置教程  

## 关于 DNS 泄露  
配合以上订阅转换模板和教程正确设置 OpenClash 后，大陆域名将使用国内 DNS 解析，默认为运营商DNS，可自行设置其他国内 DNS，且大陆域名绕过 Clash 内核，可以返回真实 IP 
国外域名自动走节点远端默认 DNS 解析，一般为机场默认的 DNS 或者你的 VPS 中设置的 DNS  
理论上，以上取得的均为最快最佳的解析结果，且无污染，无泄露，无需套娃其他工具    

## IPv6 设置教程 
https://github.com/Aethersailor/Custom_OpenClash_Rules/wiki/OpenWrt-IPv6-设置教程  

## 控制面板效果截图  
![](https://github.com/Aethersailor/Custom_OpenClash_Rules/blob/main/doc/openclash/pics/db2.png)  

## 感谢  
- [Aethersailor/Custom_OpenClash_Rules](https://github.com/Aethersailor/Custom_OpenClash_Rules)
- [vernesong/OpenClash](https://github.com/vernesong/OpenClash)
- [MetaCubeX/mihomo](https://github.com/MetaCubeX/mihomo)
- [ACL4SSR/ACL4SSR](https://github.com/ACL4SSR/ACL4SSR)
- [blackmatrix7/ios_rule_script](https://github.com/blackmatrix7/ios_rule_script)
- [TraderWukong/demo](https://github.com/TraderWukong/demo)
- [dogfight360/UsbEAm](https://github.com/dogfight360/UsbEAm)
