# Discord-Toki-bot
起初为移植 [Tsuk1ko/CQ-picfinder-robot](https://github.com/Tsuk1ko/CQ-picfinder-robot) [(Blog)](https://moe.best/projects/qq-robot-picfinder.html) 而诞生。

使用 Python 在 DiscordAPI 中重写并实现。

[![](https://img.shields.io/badge/Made%20with-Python%203.8.1-brightgreen)](https://www.python.org/downloads/) [![](https://img.shields.io/badge/lib-discord.py-brightgreen)](https://github.com/Rapptz/discord.py/)

虽然目前WIP，但已经可以使用。机器人可邀请，但无义务维护，不能保证24小时的运行正常，本质为私用机器人，内加私货数量略多。

[![](https://img.shields.io/badge/Bot-invite%20link-blue)](https://discordapp.com/api/oauth2/authorize?client_id=687568148354170896&permissions=0&scope=bot) [![](https://img.shields.io/badge/Discord-Support%20server-blue)](https://discord.gg/MPU5qxE)

**作者技术力低下，所以本项目无任何注释，代码风格十分混乱且大概率不会有部署流程。**

## Commands
Commands prefix: `!`

Need Chinese command help? Just typing `!osu chinese`


We support **ANY** servers!

Bnacho: `!bancho`

Ripple: `!ripple`

Akatsuki: `!akatsuki`

Gatari: `!gatari`

Kawata: `!kawata`

ppy.sb: `!ppy.sb`


**[Options]**

Get an osu profile: `user [username/uid]`

If servers have relax u can also using `rx [username/uid]`

Get a recent play: `pr [username/uid]`

nIf servers have relax u can also using `prrx [username/uid]`


**[Example]**

``!bancho user Whitecat``

`!akatsuki rx skyapple`

``!ripple pr _nullptr``

`!ppy.sb prrx 1092`

## Preview
### osu!api
![stat](https://i.imgur.com/8ZI2lit.png)
![recent](https://i.imgur.com/dQ5ZxhM.png)

### 竹竹来张色图
![竹竹来张色图](https://i.imgur.com/oiVip6K.png)

# TODO

| Progress | 功能 |
|  ----    | ----  |
|          | [Saucenao](https://saucenao.com/) |
|          | [WhatAnime](https://trace.moe/) |
|          | [Ascii2d](https://ascii2d.net/) |
|√         | 竹竹来张色图 ([API](https://yww.uy/setuapi)) |
|          | 随机复读             |
|WIP       | COVID-19 实时数据 ([API](https://github.com/NovelCOVID/API)) |
|√         | osu!bancho-api       |
|√         | osu!ppy.sb-api       |
|√         | osu!akatsuki-api     |
|√         | osu!ripple-api       |
