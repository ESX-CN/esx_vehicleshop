# esx_vehicleshop

## 要求

* 全自动模式（每个人都可以从经销商那里购买车辆）
  * 无需下载其他资源

* 玩家管理模式 (汽车经销商的工作): 账单, Boss操作等等！
  * [esx_society](https://github.com/ESX-CN/esx_society)
  * [esx_billing](https://github.com/ESX-CN/esx_billing)
  * [esx_addonaccount](https://github.com/ESX-CN/esx_addonaccount)
  * [esx_addoninventory](https://github.com/ESX-CN/esx_addoninventory)
  * [cron](https://github.com/ESX-CN/cron)

## 下载 & 安装

### 使用 [fvm](https://github.com/qlaffont/fvm-installer)
```
fvm install --save --folder=esx esx-cn/esx_vehicleshop
```

### 使用 Git
```
cd resources
git clone https://github.com/ESX-CN/esx_vehicleshop [esx]/esx_vehicleshop
```

### 手动下载
- 下载 https://github.com/ESX-CN/esx_vehicleshop/archive/master.zip
- 解压至 `[esx]` 目录

## 安装
- 导入 `esx_vehicleshop.sql` 至你的数据库
- 在你的服务器配置文件 `server.cfg`中加入

```
start esx_vehicleshop
```
- 如果你想要玩家管理工作，你需要在 `config.lua` 中配置 `Config.EnablePlayerManagement` 为 `true`

# Legal
### License
esx_vehicleshop - vehicle shop for ESX

Copyright (C) 2015-2018 Jérémie N'gadi

This program Is free software: you can redistribute it And/Or modify it under the terms Of the GNU General Public License As published by the Free Software Foundation, either version 3 Of the License, Or (at your option) any later version.

This program Is distributed In the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty Of MERCHANTABILITY Or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License For more details.

You should have received a copy Of the GNU General Public License along with this program. If Not, see http://www.gnu.org/licenses/.