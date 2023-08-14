# 介绍
* 自用Subconverter订阅转换配置文件，修改自原作者[ACL4SSR](https://github.com/ACL4SSR/ACL4SSR/)  
* 自用Loon配置文件，基于以上进一步修改
* ACL4SSR规则为基础，进行合并补充修改剔除重复  
        
* 规则数量: 8097条
* 最近更新: 2023年08月14日17:36:22
# Clash订阅转换远程配置:
    https://raw.githubusercontent.com/mphin/ACL4SSR/main/config/ACL4SSR_Online_Full_MultiMode_777.ini
注: Stash用户也可以通过订阅转换后的链接使用。
# Loon分流配置文件:
* 点击链接一键导入: 
        https://www.nsloon.com/openloon/import?sub=https://raw.githubusercontent.com/mphin/ACL4SSR/main/config/Loon_config_mphin.conf
* 或通过复制链接从URL下载:

      https://raw.githubusercontent.com/mphin/ACL4SSR/main/config/Loon_config_mphin.conf
# 策略组内容
* 🕹 手动切换
* ♻️ 自动选择
* 🚧 故障转移
* ⚖️ 负载均衡
* ✈️ 国外常规=https://raw.githubusercontent.com/mphin/ACL4SSR/main/rules/ProxyGFWlist.list
* 📲 电报消息=https://raw.githubusercontent.com/mphin/ACL4SSR/main/rules/Telegram.list
* 🎥 国外媒体=https://raw.githubusercontent.com/mphin/ACL4SSR/main/rules/ProxyMedia.list
* 🤖 AI｜奈飞=https://raw.githubusercontent.com/mphin/ACL4SSR/main/rules/OpenaiNetflix.list
* 📡 IP｜测速=https://raw.githubusercontent.com/mphin/ACL4SSR/main/rules/IpinfoSpeedtest.list
* 📢 谷歌服务=https://raw.githubusercontent.com/mphin/ACL4SSR/main/rules/Google.list
* Ⓜ️ 微软服务=https://raw.githubusercontent.com/mphin/ACL4SSR/main/rules/Microsoft.list
* 🍎 苹果服务=https://raw.githubusercontent.com/mphin/ACL4SSR/main/rules/Apple.list
* 📺 国内媒体=https://raw.githubusercontent.com/mphin/ACL4SSR/main/rules/ChinaMedia.list
* 🎮 游戏平台=https://raw.githubusercontent.com/mphin/ACL4SSR/main/rules/GamesPlatform.list
* 🎯 全球直连=https://raw.githubusercontent.com/mphin/ACL4SSR/main/rules/GlobalDirect.list                
  本地/局域网=https://raw.githubusercontent.com/mphin/ACL4SSR/main/rules/LocalAreaNetwork.list
* 🐟 漏网之鱼
* 🇭🇰 香港节点
* 🇨🇳 台湾节点
* 🇸🇬 狮城节点
* 🇺🇲 美国节点
* 🇯🇵 日本节点
* 🇰🇷 韩国节点
  
进阶玩法: 
可自行添加以上策略组，将以上规则集添加到相对应的策略组，注意规则集的先后顺序。
分享个自用Loon及Stash策略组图标集(圈X及其他未测试应该也支持):

    https://raw.githubusercontent.com/mphin/GroupIcons/main/GroupIcons_emoji.json

# Clash使用方法
1. 使用在线订阅转换，在订阅转换网站上填写远程配置参数：
   
       https://raw.githubusercontent.com/mphin/ACL4SSR/main/config/ACL4SSR_Online_Full_MultiMode_777.ini
1. 使用本地搭建的订阅转换，将配置文件放入subconverter目录下的config文件里，规则文件放入rules文件夹里，最后订阅转换网站上填写远程配置参数：
 
       config/ACL4SSR_Online_Full_MultiMode_777_local.ini
    




        
**本仓库创建于2023年7月2日**
