
# 源码地址

- 官方源码：    https://github.com/openwrt/openwrt      

- lede源码：    https://github.com/coolsnowwolf/lede  

- lienol源码：  https://github.com/Lienol/openwrt 

- immortalwrt源码： https://github.com/immortalwrt/immortalwrt

### 操作教程由“实用技能”提供 @shiyongjineng

#### 观看视频教程↓↓点击下方↓↓进行观看！

[![从零开始：自己编译OpenWrt系统！一个视频就够了！](https://res.cloudinary.com/marcomontalbano/image/upload/v1692411463/video_to_markdown/images/youtube--_3B-y73JRQ4-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://youtu.be/_3B-y73JRQ4 "从零开始：自己编译OpenWrt系统！一个视频就够了！")

[![openwrt在线编译教程](https://res.cloudinary.com/marcomontalbano/image/upload/v1692156705/video_to_markdown/images/youtube--6j4ofS0GT38-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=6j4ofS0GT38 "openwrt在线编译教程")

[![电视盒子专用：利用Flippy内核工具打包，将OpenWrt固件转成img镜像文件，](https://res.cloudinary.com/marcomontalbano/image/upload/v1692927730/video_to_markdown/images/youtube--EPNsHRj3eXE-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://youtu.be/EPNsHRj3eXE "电视盒子专用：利用Flippy内核工具打包，将OpenWrt固件转成img镜像文件，")


## 使用方法

1. 注册账号

- 点击github.com 网站右上角的【Sign up】按钮，根据要求填写完成即可！


2. 设置权限

- 右上角点击自己的头像，下拉菜单中选择【Settings/设置】 > 【Developer settings/开发者设置】 > 【Personal access tokens/个人访问令牌 > 【Tokens（classic）/令牌（经典）】 > 【 Generate new token/生成新令牌 】 ( Name: GITHUB_TOKEN, Select: public_repo )，其他选项根据自己需要可以多选，提交保存，复制系统生成的加密 KEY 的值，先保存到自己电脑的记事本，下一步会用到这个值。

- 点击右上的 Fork 按钮，复制一份仓库代码到自己的账户下，稍等几秒钟，提示 Fork 完成后，到自己的账户下访问自己仓库里的AutoBuild-OpenWrt 。在右上角的 Settings > Secrets > Actions > New repostiory secret ( Name: TOKEN, Value: 填写刚才GITHUB_TOKEN的值 )，保存。并在左侧导航栏的 Actions > General > Workflow permissions 下选择 Read and write permissions 并保存。


3. 设置config
   
- 修改.config文件。


4. 自定义配置

 - diy-part1.sh文件主要是自定义软件仓库，diy-part2.sh文件主要是个性化配置。

    
   
5. 开始编译
 
 - 点击菜单栏的【Actions】，左边菜单栏选择对应的编译流程，Update Checker为自动更新插件。
 
 
6. 下载固件
 - 编译完成后会自动发布至release，自行前往下载。


 ## 特别感谢

 - [P3TERX/Actions-OpenWrt](https://github.com/P3TERX/Actions-OpenWrt)
 - [xinlingduyu/build-openwrt](https://github.com/xinlingduyu/build-openwrt)
 - [Microsoft Azure](https://azure.microsoft.com)
 - [GitHub Actions](https://github.com/features/actions)
 - [OpenWrt](https://github.com/openwrt/openwrt)
 - [coolsnowwolf/lede](https://github.com/coolsnowwolf/lede)
 - [Lienol/openwrt](https://github.com/Lienol/openwrt)
 - [immortalwrt/immortalwrt](https://github.com/immortalwrt/immortalwrt)
 - [Mikubill/transfer](https://github.com/Mikubill/transfer)
 - [softprops/action-gh-release](https://github.com/softprops/action-gh-release)
 - [Mattraks/delete-workflow-runs](https://github.com/Mattraks/delete-workflow-runs)
 - [dev-drprasad/delete-older-releases](https://github.com/dev-drprasad/delete-older-releases)
 - [peter-evans/repository-dispatch](https://github.com/peter-evans/repository-dispatch)

  
