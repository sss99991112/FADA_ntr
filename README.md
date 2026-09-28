# FADA / ICE-Cal 代码仓库

这里保存基于 UniLab 的 FADA 复现、目标域适配与 ICE-Cal 探索代码。
整个 FADA 工作目录的导航见[上一级首页](../README.md)。

## 按你现在要做的事进入

| 目的 | 入口 |
|---|---|
| 继续讨论新论文方向 | [方向 A：可行性、创新性与下一步验证](note/fada/concepts/2026-09-28-direction-a-discussion.md) |
| 查阅相关工作笔记 | [真实机器人适配相关工作](note/fada/related_work_real_robot_adaptation.md) |
| 查看 FADA 斜坡复现流程 | [斜坡适配操作手册](docs/runbooks/fada-slope-traversal.md) |
| 找采集数据、指标和演示视频 | [实验产物导航](artifacts/README.md) |
| 找本地模型 | [模型导航](checkpoints/README.md)与[早期 Planner–IDM 模型](../models/README.md) |
| 阅读代码结构与训练调用链 | [详细仓库地图](docs/engineering/repository-map.md) |
| 准备修改代码 | [开发说明](CONTRIBUTING.md)与[仓库约束](AGENTS.md) |
| 核对方法、训练边界及历史证据 | [研究索引](note/README.md)与[Contract 索引](note/fada/contracts/README.md) |

## 目录用途

| 目录 | 放什么 |
|---|---|
| `src/unilab/` | 算法、环境、后端及训练实现 |
| `conf/` | Hydra 任务和算法配置 |
| `scripts/` | 训练、回放、采集、适配、评估入口 |
| `tests/`、`benchmark/` | 测试与性能基准 |
| `docs/` | 工程说明及操作手册 |
| `note/` | 研究讨论、方法约定、设计图和历史证据 |
| `checkpoints/` | 本地 Oracle 和 Context 模型 |
| `artifacts/` | 目标域数据、评估指标、视频和 Context 产物 |
| `notebook/` | 探索性 Notebook |
| `work/` | 演示文稿构建材料和预览 |

## 阅读旧资料时注意

FADA 复现、Source Oracle、目标适配与 Context 探索是不同的记录对象。
用户已报告 FADA 复现成功；旧 v024/Context 设计的完成状态不能用来否定这项复现。

旧阶段游标已依据现有实现证据修正，过期讨论、方案和审查文件已清理。
判断具体模型能力仍需查看对应运行、Checkpoint 和评估证据。
新方向 A 目前是讨论与待验证假设。

维护代码前读取 [AGENTS.md](AGENTS.md)，使用 `uv run`。
完整入口、技术细节和旧首页内容已收进[详细仓库地图](docs/engineering/repository-map.md)。
