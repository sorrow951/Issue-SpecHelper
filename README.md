# Issue-SpecHelper · Ge Yunhao 课程项目记录

这是 Ge Yunhao 的 CS5351 软件工程课程项目记录。小组最终实现的 **GitHub Issue Quality Review** 是一款 JetBrains IDE 插件。开发者可以在 IDE 中连接 GitHub、浏览 Issue、查看带原文引文的六项质量检查，编辑建议后主动发布评论。[小组总仓库及安装说明](https://github.com/SeGroup11/scrum-workspace) · [小组证据索引](https://github.com/SeGroup11/scrum-workspace/blob/main/docs/evidence/index.md)

Week 1 和 Week 2 记录的是选题阶段的 VS Code 与 Python 方案。小组成品采用 Kotlin、Gradle 和 IntelliJ Platform，并复用 IDE 的 GitHub 登录与 Tasks 功能。[最终系统设计](https://github.com/SeGroup11/scrum-workspace/blob/main/docs/course/report.zh-CN.md#系统设计与实现)

## 进度总览

周次以 2026 年 9 月 20 日所在周为 Week 3，按周一至周日推算。Sprint 栏沿用课程计划，实际实现日期以提交、PR 和测试记录为准。小组仓库的三个 Sprint 均在 11 月 24 日留下实现与验收记录。补录个人活动时，可在对应周次注明完成事项、工时和相关 Issue、PR 或文档链接。

| 周次 | 日期 | 课程阶段 | 已核实的记录 |
| --- | --- | --- | --- |
| Week 1 | 8 月 31 日–9 月 6 日 | 组队 | 已记录 |
| Week 2 | 9 月 7–13 日 | Sprint 1 | 已记录 |
| Week 3 | 9 月 14–20 日 | Sprint 1 | 个人仓库和周报模板 |
| Week 4 | 9 月 21–27 日 | Sprint 1 | 待补当周资料 |
| Week 5 | 9 月 28 日–10 月 4 日 | Sprint 1 | 待补当周资料 |
| Week 6 | 10 月 5–11 日 | Sprint 2 | 待补当周资料 |
| Week 7 | 10 月 12–18 日 | Sprint 2 | 待补当周资料 |
| Week 8 | 10 月 19–25 日 | Sprint 2 | 待补当周资料 |
| Week 9 | 10 月 26 日–11 月 1 日 | Sprint 2 | 待补当周资料 |
| Week 10 | 11 月 2–8 日 | Sprint 3 | 待补当周资料 |
| Week 11 | 11 月 9–15 日 | Sprint 3 | 待补当周资料 |
| Week 12 | 11 月 16–22 日 | Sprint 3 | 待补当周资料 |
| Week 13 | 11 月 23–29 日 | Sprint 3 | 已记录 11 月 24 日的团队交付与验收 |

## Week 1 - 组队与选题

- 姓名 / 角色：Ge Yunhao / 团队成员（具体开发分工待确定）
- 本周完成事项：加入 8 人小组；参与课程项目要求讨论，确认项目必须是服务软件开发人员的软件工程工具；结合团队熟悉 Java、Python 以及 12 周内可完成的原则，比较多个 IDE 插件方向，初步选定 GitHub Issue 质量检查工具。
- Issue / PR / commit：暂无，本周处于组队和选题阶段。
- 测试或文档证据：参与确定项目名称 Issue-SpecHelper，并完成项目方向与可行性的初步讨论。
- 投入工时 / 故事点：待补充。
- 问题、风险或技术债务：团队缺少 VS Code 插件开发经验，需要学习 TypeScript 和 Webview；项目范围仍需进一步收敛。
- 下周计划：确认痛点、核心功能和技术方案，完成初步分工与 Sprint 规划。

## Week 2 - Sprint 1 启动

- 姓名 / 角色：Ge Yunhao / 团队成员（具体开发分工待确定）
- 本周完成事项：确认项目聚焦于检查 GitHub Issue 中缺失的验收标准、复现步骤、预期结果和边界条件；确定采用 VS Code Webview + TypeScript 薄前端、Python 后端和大模型 API 的方案；参与整理响应性能、鲁棒性和可扩展性三项非功能需求及其架构理由；讨论 8 人分工和三个 Sprint 的初步计划。
- Issue / PR / commit：暂无，本周主要完成需求和方案讨论，尚未进入正式编码。
- 测试或文档证据：项目方案中已形成痛点、核心功能、非功能需求、总体架构、团队分工和 Sprint 拆分草案。
- 投入工时 / 故事点：待补充。
- 问题、风险或技术债务：外部大模型调用可能难以稳定达到 3 秒响应要求；GitHub 认证、VS Code 插件与 Python 后端通信需要尽早验证。
- 下周计划：建立 GitHub 仓库，编写用户故事和验收标准，拆分任务 Issue，并开始验证最小端到端流程。

## Week 3 - 个人仓库与周报

9 月 20 日，Ge Yunhao 的个人仓库建立并加入了第 1–13 周记录模板，同时补录了组队与选题阶段的记录。[创建仓库](https://github.com/sorrow951/Issue-SpecHelper/commit/f659fcf22d7aef0b0502b601549b43a1d01c7a63) · [周报模板](https://github.com/sorrow951/Issue-SpecHelper/commit/d8145acf33a7d7558df77a9e6a4645c332596e) · [Week 1–2 补录](https://github.com/sorrow951/Issue-SpecHelper/commit/f08b24e6c49d275507d5f3248aa55f79aff76ba0)

## Week 4 - 编码、测试与集成

当周活动待补原始资料。

## Week 5 - Sprint 1 验收与复盘

当周活动待补原始资料。

## Week 6 - Sprint 2 启动

当周活动待补原始资料。

## Week 7 - 功能完善

当周活动待补原始资料。

## Week 8 - 代码质量与评审

当周活动待补原始资料。

## Week 9 - Sprint 2 验收与复盘

当周活动待补原始资料。

## Week 10 - Sprint 3 启动

当周活动待补原始资料。

## Week 11 - 评估实验与报告素材

当周活动待补原始资料。

## Week 12 - 演示与汇报准备

当周活动待补原始资料。

## Week 13 - 团队交付与验收

11 月 23 日，小组仓库建立了可追溯的初始版本。11 月 24 日的三个 Sprint PR 和验收记录如下。[小组仓库初始提交](https://github.com/SeGroup11/scrum-workspace/commit/5770c5b) · [小组证据索引](https://github.com/SeGroup11/scrum-workspace/blob/main/docs/evidence/index.md)

| 开发轮次 | 团队成果 | 证据 |
| --- | --- | --- |
| Sprint 1 | 构建 JetBrains 插件，接入 IDE 的 GitHub 账号，读取获授权仓库的 Issue，支持分页、筛选、查看原文及按需加载讨论。首个安装包的显示名未通过 Verifier，修正后复测四款 IDE。 | [PR #18](https://github.com/SeGroup11/scrum-workspace/pull/18) · [显示名修复](https://github.com/SeGroup11/scrum-workspace/commit/4bc2b85) |
| Sprint 2 | 支持配置模型服务，对实际现象、复现步骤、预期结果、功能目标、验收标准和边界情况逐项检查。分析在后台执行，报告展示可核对的原文引文，任务切换或重启后可恢复草稿，用户确认后发送评论。 | [PR #19](https://github.com/SeGroup11/scrum-workspace/pull/19) · [模型报告验证 #9](https://github.com/SeGroup11/scrum-workspace/issues/9) |
| Sprint 3 | 完成 0.2.4 候选包的干净构建与回归，核对冷启动、跨仓重新连接和评论回执丢失后的恢复，并归档演示、答辩和报告材料。 | [PR #21](https://github.com/SeGroup11/scrum-workspace/pull/21) · [验收 #14](https://github.com/SeGroup11/scrum-workspace/issues/14) · [冷启动回顾 #23](https://github.com/SeGroup11/scrum-workspace/issues/23) |

**验收结果**  
候选包 `github-issue-review-0.2.4.zip` 对应源码 `3cdfc4b`。干净构建通过 26 项自动测试。同一安装包在 IntelliJ IDEA、WebStorm、Rider 和 PyCharm 上通过 Plugin Verifier，并有安装和操作记录。受控慢请求测试将界面首次反馈与模型完成时间分别计量，四款 IDE 的首次反馈为 5–63 ms。团队以草稿与报告恢复、分析期间可操作性、四款 IDE 兼容性作为最终质量目标。[锁定源码](https://github.com/SeGroup11/scrum-workspace/commit/3cdfc4b5ccf22dd3792d6ade3c8952e9b32b0835) · [0.2.4 验收矩阵](https://github.com/SeGroup11/scrum-workspace/blob/main/docs/evidence/acceptance.md)

**课程材料与待核实事项**  
小组看板记录 12 个故事中的 10 个完成。团队已归档报告、答辩幻灯片和演示复跑说明。0.2.4 发布草稿的清单另列了演示视频及原始验收证据。#9 仍待独立人工标注及外部模型语义评估，#15 仍待同伴独立复现及反馈。受控样例中有一条复现步骤被误判为缺失，报告记录了该结果。[课程报告](https://github.com/SeGroup11/scrum-workspace/blob/main/docs/course/report.zh-CN.md) · [答辩 PPT](https://github.com/SeGroup11/scrum-workspace/blob/main/docs/course/CS5351-Group11-defense.pptx) · [演示与复跑说明](https://github.com/SeGroup11/scrum-workspace/blob/main/docs/course/demo-and-debug.zh-CN.md) · [同伴复现 #15](https://github.com/SeGroup11/scrum-workspace/issues/15) · [0.2.4 交付清单](https://github.com/SeGroup11/scrum-workspace/blob/main/docs/evidence/release-0.2.4.json)

## 个人贡献汇总

| 成员 | 角色 | 工时／故事点 | 可追溯记录 |
| --- | --- | --- | --- |
| Ge Yunhao | 团队成员，具体开发分工待确认 | 待补 | [周报模板](https://github.com/sorrow951/Issue-SpecHelper/commit/d8145acf33a7d7558df77a9e6a4645c332596e) · [Week 1–2 补录](https://github.com/sorrow951/Issue-SpecHelper/commit/f08b24e6c49d275507d5f3248aa55f79aff76ba0) |

小组公开仓库未记录可归于 Ge Yunhao 的实现提交、PR 或故事认领。Week 4–12 的个人记录可用当周会议纪要、任务认领或其他产出补充。
