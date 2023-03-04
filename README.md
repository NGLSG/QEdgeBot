<p align="center">
    <img src="https://github.com/NGLSG/QEdgeBot/raw/main/img/self.png" width="200" height="200" alt="QEdgeBot">
</p>

<div align="center">

# QEdgeBot

_✨基于[EdgeGPT](https://github.com/acheong08/EdgeGPT)修改的,并使用[go-cqhttp](https://github.com/Mrs4s/go-cqhttp)
转发EdgeGPT的消息到QQ✨_

如果你喜欢这个项目请点一个⭐吧

</div>
<p align="center">
  <img src="https://img.shields.io/badge/Author-Ge%E6%B1%81%E8%8F%8C-yellow">
  <a href="https://raw.githubusercontent.com/NGLSG/QEdgeBot/main/LICENSE">
    <img src="https://img.shields.io/github/license/NGLSG/QEdgeBot" alt="license">
  </a>
  <img src="https://img.shields.io/github/stars/NGLSG/QEdgeBot.svg" alt="stars">
  <img src="https://img.shields.io/github/forks/NGLSG/QEdgeBot.svg" alt="forks">
</p>

# 要求

* Python3 版本 >= 3.9
* Rust

# 安装

```
git clone https://github.com/NGLSG/QEdgeBot.git
cd py/
运行安装依赖.bat或者DependenceInstaller.sh
```

# 使用

请修改py/config.json中的`qq_on*`为你的机器人的qq和`*admin_qq`你的qq

将Edge 的cookie粘贴复制到cookies里(建议使用Chrome , edge, firefox 浏览器,并使用Cookie-Editor导出)

修改QBot/config.yml中的 `uin`为机器人的qq `password`为机器人的qq密码

此后你只需要运行对应系统的启动脚本即可

# 注意

如果你是Arm架构的机型,请将对应go-cqhttp的可执行文件修改为你的架构对应的执行文件[下载链接](https://github.com/Mrs4s/go-cqhttp/releases)
