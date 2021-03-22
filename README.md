# X  
#### *这是一组网络工具，可帮助您构建自己的计算机网络。它可以保护您的网络连接，从而保护您的隐私。*
## **ShadowsocksR（v.3.2.2）**
- 1.初次安装  
`bash <(curl -sL https://raw.githubusercontent.com/linrq233/X/main/ShadowsocksR/centos_install_ssr.sh)`
- 2.查看运行状态/配置  
`bash <(curl -sL https://raw.githubusercontent.com/linrq233/X/main/ShadowsocksR/centos_install_ssr.sh) info`
-  3.管理命令  
启动：`systemctl start shadowsocksR`  
停止：`systemctl stop shadowsocksR`  
重启：`systemctl restart shadowsocksR`  
- 4.更新组件、更改密码、端口、混淆参数：重新运行一次安装脚本（如不想更新组件，请使用第6条）  
- 5.卸载  
`bash <(curl -sL https://raw.githubusercontent.com/linrq233/X/main/ShadowsocksR/centos_install_ssr.sh) uninstall`
- 6.去除更新组件，适合更改密码、端口、混淆参数  
`bash <(curl -sL https://raw.githubusercontent.com/linrq233/X/main/ShadowsocksR/centos_install_ssr2.sh)`
  
  
  
## **V2ray（v4.34.0）**
- 1.安装  
`bash <(curl -sL curl -sL https://raw.githubusercontent.com/linrq233/X/main/V2ray/centos_install_v2ray.sh)`
- 2.查看运行状态/配置  
`bash <(curl -sL curl -sL https://raw.githubusercontent.com/linrq233/X/main/V2ray/centos_install_v2ray.sh) info`
-  3.管理命令  
启动：`systemctl start v2ray`  
停止：`systemctl stop v2ray`  
重启：`systemctl restart v2ray`
- 4.更改端口、alterid：重新运行一次安装脚本  
- 5.卸载  
`bash <(curl -sL https://raw.githubusercontent.com/linrq233/X/main/V2ray/centos_install_v2ray.sh) uninstall`  
  
  

## **说明**  
本资源仅供学习交流，严禁用于商业用途，请于24小时内删除。  
  
  
  
#### **文件与脚本引用参考**  
> https://github.com/shadowsocksrr  
> https://github.com/v2fly  
