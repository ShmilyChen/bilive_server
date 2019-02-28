# bilive_server

* 这是一个次分支，感谢所有对[主分支](https://github.com/lzghzr/bilive_client)做出贡献的人及其他同类开源软件的开发者
* 有兴趣支持原作者的，请朝这里打钱=>[给lzghzr打钱](https://github.com/lzghzr/bilive_client/wiki)
* 有兴趣向我投喂的，请朝这里打钱=>[请给我钱](https://github.com/Vector000/Something_Serious/blob/master/pics/mm_reward_qrcode.png)

### 自行编译
  * 第一次使用
    1. 安装[Git](https://git-scm.com/downloads)
    2. 安装[Node.js](https://nodejs.org/)
    3. 命令行 `git clone https://github.com/Vector000/bilive_server.git`
    4. 命令行 `cd bilive_server`
    5. 命令行 `mkdir options`
    6. 命令行 `cp nedb/roomList.db options/roomList.db`
    7. 命令行 `npm install`
    8. 命令行 `npm run build`
    9. 命令行 `npm start`
  * 版本更新
    1. 定位到目录
    2. 命令行 `git pull`
    3. 命令行 `npm install`
    4. 命令行 `npm run build`
    5. 命令行 `npm start`

[点此进行设置](https://vector000.github.io/bilive_setting/#path=ws://localhost:20080&protocol=admin)

此为服务端, 仅用来监听房间弹幕, 更多功能请使用[客户端](https://github.com/Vector000/bilive_client)