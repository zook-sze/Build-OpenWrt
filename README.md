#### 自动化编译OpenWRT路由固件

#### 源码来源：
[![garypang13](https://img.shields.io/badge/autoBuild-garypang13-red.svg?style=flat&logo=appveyor)](https://github.com/garypang13/OpenWrt)
[![Lienol](https://img.shields.io/badge/passwall-openwrt-blueviolet.svg?style=flat&logo=appveyor)](https://github.com/xiaorouji/openwrt-passwall) 
[![immortalwrt](https://img.shields.io/badge/immortalwrt-openwrt-orange.svg?style=flat&logo=appveyor)](https://github.com/immortalwrt/immortalwrt) 
[![P3TERX](https://img.shields.io/badge/Actions-P3TERX-success.svg?style=flat&logo=appveyor)](https://github.com/P3TERX/Actions-OpenWrt)


#### 固件下载:

[![GitHub release (latest by date)](https://img.shields.io/github/v/release/zook-sze/Build-OpenWrt?style=for-the-badge&label=Download)](https://github.com/zook-sze/Build-OpenWrt/releases/latest)

#### 特色:

+ Lean 源码,内核升级到5.4. 最新源码同步.

+ 原生极致纯净,固件默认只包含基础上网功能,主流开源插件

+ 性能,友好度,易用性,插件,以及针对国内特殊环境等的自定义优化

+ 自定制清爽主题风格

+ 无需专业知识,无需linux服务器,人人皆可通过云编译定制编译自己的专属固件.

+ 持续更新, 每周日零点定时自动云编译更新固件,不用再担心因停更而需更换固件.

#### 关于Secrets、TOKEN的小知识

* 云编译需要 [在此](https://github.com/settings/tokens) 创建个token,然后在此仓库Settings->Secrets中添加个名字为REPO_TOKEN的Secret,填入token值

* 在仓库Settings->Secrets中添加 SCKEY 可通过[Server酱](http://sc.ftqq.com) 推送编译结果到微信

* 在仓库Settings->Secrets中添加 TELEGRAM_CHAT_ID, TELEGRAM_TOKEN 可推送编译结果到Telegram Bot

##### 编译触发方式: 
   + 方式1: Actions页面选择 Repo Dispatcher 点击 Run workflow
   
   + 方式2: 请在支持油猴的浏览器中安装 [脚本](https://greasyfork.org/scripts/407616-github-actions-trigger/code/Github%20Actions%20Trigger.user.js) ,仓库右上角会出现 x86_64 Actions,K2P Actions等按钮,点击对应按钮即可.
   
   + 更多玩法 [repo-dispatcher](https://github.com/tete1030/github-repo-dispatcher)

[p3terx | 云编译教程](https://p3terx.com/archives/build-openwrt-with-github-actions.html)

#### 默认插件包含:

+ Opkg 软件包管理
+ ssr-plus
+ openclash
+ passwall
+ UPNP 自动端口转发
+ Turbo ACC 网络加速

#### 默认后台地址 192.168.3.1, 密码 password
