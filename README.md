# 星幕助理

演员创作与状态管理工作台。

在线访问：https://wujimu4-jpg.github.io/xingmu-assistant/

## 功能

剧本片段提取、角色笔记、台词挖空练习、浏览器语音朗读、呼吸计时、视频旁记、复盘卡、日程与社交备忘录。

## 本地运行

运行 `python3 -m http.server 8080` 后访问 http://localhost:8080 。

## 部署

GitHub Pages 从 main 分支根目录部署，提交更新后自动发布。

## 数据与能力边界

数据保存在使用者的浏览器 localStorage，可导出备份。视频仅本地播放，不上传。AI 深度分析、语音对戏、OCR、视频分析、云端同步尚未接入。
