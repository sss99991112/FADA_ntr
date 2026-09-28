# FADA 当前任务入口

2026-09-28：旧设计阶段游标已替换。不同研究轨道分别查看对应记录。

## 当前讨论

[方向 A：少量校准数据的跨指令动力学适配](concepts/2026-09-28-direction-a-discussion.md)。
值得验证，方法和创新性尚未定型；建议实验尚未执行。

## 原有实现与待验证边界

- Source v024：已有实现、离线模块验证和有界 reset/step smoke；完整正式运行验证及训练仍待完成。
  依据：[实现证据](evidence/2026-09-07-v024-command-gated-phase-contact-implementation.md)
  与[当前检查表](checklists/current.md)。
- FADA 目标适配：以有效 ADAPT v003 约定及具体模型、数据和评估记录为准。
- Context v009/v008：保留的工程提案；早期 Context 运行证据不证明当前提案有效。

[有效约定](contracts/README.md)记录现有方法边界。这份入口没有批准新实现或运行。
用户报告的 FADA 成功复现与旧 Source/Context 开发状态分别记录。
