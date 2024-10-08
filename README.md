# 批量打开网页脚本

## 脚本必须允许页面重定向！(例如: 在 A 网页使用此脚本则必须允许 A 网页进行重定向)

## 简介

一个浏览器脚本，支持多种打开方式和自定义设置，快速打开多个网页链接。

## 主要功能

1. 批量打开预设链接
2. 随机打开指定数量的链接
3. 鼠标框选打开页面上的链接
4. 自定义快捷键、最大打开数量和打开延迟
5. 可调整大小和位置的设置对话框

## 安装

1. 首先，确保您的浏览器已安装Tampermonkey扩展。
2. 点击[此处](https://greasyfork.org/zh-CN/scripts/502852-%E5%A2%9E%E5%BC%BA%E5%9E%8B%E6%89%B9%E9%87%8F%E6%89%93%E5%BC%80%E7%BD%91%E9%A1%B5)安装脚本。
3. Tampermonkey会自动打开安装页面，点击"安装"即可。

## 使用说明

### 批量打开链接

1. 点击Tampermonkey图标，选择"批量打开链接"。
2. 在弹出的对话框中输入要打开的链接（每行一个）。
3. 选择打开方式：全部打开或随机打开。
4. 如选择随机打开，可设置打开数量。
5. 点击"打开"按钮执行，或"保存"按钮仅保存链接列表。

![355758902-f48a8c9a-3bb2-4acb-ace3-96790e57b4ac_415x291](https://github.com/user-attachments/assets/dd72a3b1-60c2-49a6-bf1d-fc6821acb8bc)

### 鼠标框选打开链接

1. 按住设定的快捷键（默认为Z）。
2. 在页面上按住鼠标左键并拖动，创建一个选择框。
3. 选择框内的链接会被黄色虚线框高亮。
4. 释放鼠标，确认是否打开选中的链接。

![MD](https://github.com/user-attachments/assets/358e311e-1159-4fd5-ac84-0b7a89f72740)


### 自定义设置

1. 点击Tampermonkey图标，选择"设置"。
2. 在弹出的对话框中可以修改以下设置：
   - 快捷键
   - 最大打开数量
   - 打开延迟（毫秒）
3. 点击"保存"应用新设置。

![355758937-4f12a84a-d2e4-4dd4-9d22-96cc5ae2c332_460x207](https://github.com/user-attachments/assets/86e5eb15-832f-47d6-8ed1-2e55814efac8)

## 注意事项

- 请谨慎设置最大打开数量，避免一次性打开过多标签页影响浏览器性能。
- 使用随机打开功能时，实际打开的链接数量不会超过设定的最大打开数量。
- 对话框可以通过拖动标题栏移动位置，通过右下角调整大小。

## 更新日志

### 版本 3.1
- 添加鼠标框选功能
- 增加链接高亮显示
- 优化对话框拖动和缩放功能

### 版本 3.0
- 重新设计用户界面
- 添加随机打开功能
- 增加对话框大小和位置记忆功能

### 版本 2.0
- 添加自定义设置功能
- 优化打开逻辑，添加延迟打开

### 版本 1.0
- 支持基本的批量打开功能
