<div align="center">

# ServerHelper
![GitHub repo size](https://img.shields.io/github/repo-size/Meltide/serverhelper)
![GitHub Repo stars](https://img.shields.io/github/stars/Meltide/serverhelper?style=flat)
![GitHub branch status](https://img.shields.io/github/checks-status/Meltide/serverhelper/main)
![GitHub commit activity](https://img.shields.io/github/commit-activity/t/Meltide/serverhelper)
![GitHub last commit](https://img.shields.io/github/last-commit/Meltide/serverhelper)
![GitHub Created At](https://img.shields.io/github/created-at/Meltide/serverhelper)

**一个并不全能的PocketMine-MP插件**

</div>

## 目前实现的功能

- [x] `/sh <页码>` 服务器帮助
- [x] `/shm` 管理命令
   - `/shm reload` 重载插件配置文件
   - `/shm version` 插件版本
- [x] `/bread` 给面包
- [x] 玩家进出服的人数提示

## 经过测试可用的版本

- [x] 0.12
- [x] 0.14

## 可能可用的版本

- 0.10
- 0.11
- 0.13
- 0.15 

## 配置文件

```
---
#玩家进出服提示(ON/OFF)
OnlineTip: "ON"
#给面包功能(ON/OFF)
GiveBread: "ON"
#给面包的个数
BreadNum: 16
#服务器帮助(ON/OFF)
ServerHelp: "ON"
#服务器帮助第一页
PlayerMessP1: |-
  §a==服务器帮助(1/5)==
  §a待修改
#服务器帮助第二页
PlayerMessP2: |-
  §a==服务器帮助(2/5)==
  §a待修改
#服务器帮助第三页
PlayerMessP3: |-
  §a==服务器帮助(3/5)==
  §a待修改
#服务器帮助第四页
PlayerMessP4: |-
  §a==服务器帮助(4/5)==
  §a待修改
#服务器帮助第五页
PlayerMessP5: |-
  §a==服务器帮助(5/5)==
  §a待修改
...
```

