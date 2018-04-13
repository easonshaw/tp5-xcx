【TP5-XCX】 基于THINKPHP5 的微信小程序服务端
=========================================

 #环境配置
系统:CentOS7.0

WEB环境: LANMP（[OneinStack](http://oneinstack.com)）

CA证书: 阿里云 Symantec 免费SSL

证书配置: [nginx.conf](nginx.conf)


 #安装

  ##thinkphp5 安装
composer create-project topthink/think=5.0.* ./  --prefer-dist

  ##插件安装
composer require xxh/think-wxminihelper [github地址](https://github.com/wulongtao/think-wxminihelper)



