# 微信自动化工具 — 客户交付报告

在线阅读：**<https://pierrelzw.github.io/wechat-automation-report/>**

项目周期 2025-12-16 → 2026-07-23，交付版本 v3.14.2。
本仓库只存放面向客户的静态报告页面，源代码在另一个私有仓库。

| 页面 | 内容 |
|------|------|
| [index.html](https://pierrelzw.github.io/wechat-automation-report/) | **使用手册**（首页）：三种工作流的操作步骤、CSV 格式、常见问题 |
| [changelog.html](https://pierrelzw.github.io/wechat-automation-report/changelog.html) | 更新日志：全部发布版本，含客户视角的里程碑摘要 |
| [report.html](https://pierrelzw.github.io/wechat-automation-report/report.html) | 生产数据报告：按发起人 / 批次的运行明细与成功率 |
| [summary.html](https://pierrelzw.github.io/wechat-automation-report/summary.html) | 早期试运行数据：几天集中试跑的采样统计，**非全周期累计**，已停止更新 |
| [archive.html](https://pierrelzw.github.io/wechat-automation-report/archive.html) | 历史报告：按数据日期归档的快照 |

`manual.html` 是旧地址，现在会自动跳转到首页。

所有页面由源仓库的 `scripts/publish_report.sh` 从真实运行日志、`README.md`
与 `CHANGELOG.md` 自动生成，**请勿手工编辑**——下次发布会被覆盖。
姓名与微信号在生成时已脱敏，发布前有文件白名单与手机号扫描两道检查。
