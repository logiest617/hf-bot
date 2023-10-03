## HF-bot

本插件将会指引你在huggingface部署koishi、qsign、vits等插件，从而实现不需要本地运行并且功能丰富的机器人

<details>
  <summary>部署qsign</summary>

### [文档原地址](https://github.com/CikeyQi/QQsign_docs)

# HuggingFace部署签名服务

文档作者：`0卡苏打水`   QQ交流群：`621069204`

截至当前，HuggingFace空间unidbg-fetch-qsign同步更新至 `1.1.9` 版本

优点：不需要服务器搭建，白嫖Huggingface的2核16G服务器，一键克隆即可运行，一人一地址

缺点：移动网络无法访问HuggingFace，部分地区网络可能存在一定延迟，如果出现timeout错误则是你运营商的问题，不是本教程的问题

**如果你是Windows，非常建议您查看我的这个项目：[unidbg-fetch-qsign-gui](https://ghproxy.com/https://github.com/CikeyQi/unidbg-fetch-qsign-gui)**

## 第一步：克隆空间

打开我已经部署好的空间：[QQsign](https://ghproxy.com/https://huggingface.co/spaces/CikeyQI/QQsign)，点击右上角三个点，点击 **Duplicate this Space** 
![克隆空间](https://github.com/CikeyQi/QQsign_docs/blob/main/src/1.png?raw=true)

## 第二步：填写相应的项

 **Visibility：**
 
 修改为**Public**，一定要公开，否则无法正常访问接口
 
 **TXLIB_VERSION：**
 
 本项请直接填写版本号即可，如 `8.9.68` ，不用填写路径！在本空间已经存放了官方提供的几个版本的so文件 `3.5.1` `3.5.2` `8.9.63` `8.9.68` `8.9.71` 和 `8.9.73` ，请将icqq更新到0.5.1版本以上以自动匹配协议版本，更新命令`pnpm add icqq@0.5.4 -w` 

<br>

填写好后，点击**Duplicate this Space**，将自动为您部署

![开始部署](https://github.com/CikeyQi/QQsign_docs/blob/main/src/5.png?raw=true)

## 第三步：获取地址

当状态变成**Running**时，即部署成功

![空间开始运行](https://github.com/CikeyQi/QQsign_docs/blob/main/src/6.png?raw=true)

点击右上角三个点，选择**Embed this Space**

![查看个人URL](https://github.com/CikeyQi/QQsign_docs/blob/main/src/7.png?raw=true)

下方Direct URL就是你的接口地址，点**copy**复制到剪切板

![查看个人URL](https://github.com/CikeyQi/QQsign_docs/blob/main/src/6.png?raw=true)

### 至此，你已经获得了成功部署qsign并且获得了其url以及key

## 后记：为什么我遇到了问题

1. 检查克隆时是否填写了**TXLIB_VERSION**，否则克隆后空间会报错

2. **Visibility**必须改成Public，否则第三步会没有**Embed this Space**，且机器人无法访问接口

3. 如果你遇到'ERR_INVALID_ARG_TYPE'的报错，请删除设备文件再试

4. 请检查服务器是否能访问huggingface.co

5. 若仍有问题，可加入QQ群：**621069204**，询问解决办法

## 致谢

- unidbg-fetch-qsign项目：[unidbg-fetch-qsign](https://github.com/fuqiuluo/unidbg-fetch-qsign)

</details>  

<br/>  

<details>
  <summary>部署koishi（快速）</summary>

## 第一步：复制空间
打开风佬已经部署好的koishi空间：[koishi](https://huggingface.co/spaces/initencunter/koishi)，点击右上角三个点，点击 **Duplicate this Space** 
![克隆空间](https://github.com/logiest617/hf-bot/blob/main/QQ%E6%88%AA%E5%9B%BE20231002212902.png?raw=true)


## 第二步：等候完成
接下来稍事等候：[koishi](https://huggingface.co/spaces/initencunter/koishi)，待出现状态变为running即部署成功
![克隆空间](https://github.com/logiest617/hf-bot/blob/main/QQ%E6%88%AA%E5%9B%BE20231002213507.png?raw=true)



</details>


<br/>    
<details>
  <summary>部署koishi（详细）</summary>
  
### [风佬嘴对嘴视频教程](https://www.bilibili.com/video/BV15H4y1f7nu)

</details>



<br/>    
<details>
  <summary>部署vits（包含hf注册教程）</summary>

### [部署vits](https://www.cnblogs.com/hanhanz/p/17110274.html#%E5%A6%82%E4%BD%95%E8%8E%B7%E5%8F%96%E8%AF%AD%E9%9F%B3%E6%A8%A1%E5%BC%8Fapi%E4%BB%A5%E5%8F%8Aapi%E9%85%8D%E7%BD%AE%E6%96%B9%E5%BC%8F)

</details>

<br/>    
<details>
  <summary>部署memes,（也可以直接填入我的url）</summary>

### [部署memes](https://huggingface.co/spaces/logier/memes)

</details>