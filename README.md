# 学习通任务整理表

基于 [Cooanyh/chaoxing-list](https://github.com/Cooanyh/chaoxing-list) 的用户脚本，增加待完成任务整理表。表格展示课程、任务名称、类型、开始时间、截止时间和状态，可按课程、类型筛选并导出 CSV。

## 安装

1. 在浏览器安装 ScriptCat 或 Tampermonkey。
2. 在脚本管理器中导入 `xuexitong-task-organizer.user.js`。
3. 登录学习通网页版 `https://i.chaoxing.com/`，刷新页面，点击“学习仪表盘”。
4. 点击页面上方“任务整理表”。

脚本只整理已读取的待完成任务。学习通未提供的时间会显示“未提供”。CSV 由浏览器在本地生成。操作前请以学习通任务原页面为准。

## 来源与许可

本项目基于 Cooanyh 的脚本修改，原脚本又基于 lcandy2/chaoxing-assignment。按原项目的 AGPL-3.0 许可证发布；许可证见 `LICENSE`。保留原作者署名和来源说明。
