# vscode-setting
vscode-setting

1、Settings Sync是vscode中同步设置和安装插件的小工具，在扩展商店中搜索并安装它 

2、登陆Github>Your profile> settings>Developer settings>personal access tokens>generate new token，输入名称，勾选Gist，提交

3、保存Github Access Token 

4、打开vscode，Ctrl+Shift+P打开命令框，输入sync，找到update/upload settings，输入Token，上传成功后会返回Gist ID，保存此Gist ID. 

5、若需在其他机器上DownLoad插件的话，同样，Ctrl+Shift+P打开命令框，输入sync，找到Download settings，会跳转到Github的Token编辑界面，点Edit，regenerate token，保存新生成的token，在vscode命令框中输入此Token，回车，再输入之前的Gist ID，即可同步插件和设置。

# GitHub Token: de02c01b1d7f4a6a052c083a818db3ac4d860258//已使用
# Github TOken：1adcf8bef829a0992f487da6ecea7761b356f829 //已使用 ubuntu
# GitHub Gist: 7b380e796ca673b48924b584fa81a280
