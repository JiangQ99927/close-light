# 宿舍智能开灯装置
闲暇时间做了一个不用下床关灯的小装置^_^
基于Arduino+Blinker的宿舍智能开灯装置，实现手机远程控制、自动开关灯功能。

## 技术栈
- 硬件：ESP8266
- 开发：Arduino IDE
- 通信：Blinker物联网平台

## 核心内容
- 完整控制代码 `smartswitch.ino`
- 项目设计文档与接线说明
- 环境配置指南（不含安装包，可自行下载）

## 本地运行
1. 安装Arduino IDE与对应开发板包
2. 导入 `smartswitch.ino` 代码
3. 配置Blinker设备密钥，烧录到ESP8266
4. 手机连接Blinker，远程控制开灯
