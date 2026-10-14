# 随译 Suiyi

**正常打字，短时重复遇见词语，顺便记忆外语。**

随译基于小狼毫（Weasel）重新开发，首版面向 Windows 11 x64。默认是普通输入法；三语自动识别、学习提示、译词上屏由用户分别开启。第一版包含这三项可选能力，完整离线安装包提供全部必需资源。

| 当前输入 | 学习提示 |
|---|---|
| 中文词 | 日语译词＋假名 |
| 日语词 | 英语词 |
| 英语词 | 中文译词 |

逐词组成一句话仍逐词提示；一次输入整句不显示翻译。译词紧靠候选、内容简短；上屏后短暂显示再收起，重新遇到词可再出现。设置采用现代 Windows 风格，修改统一保存，可取消。

## 当前起点

旧实现与过时资料已经归档。当前根目录不含旧 src／tests／scripts，docs 仅保留新版有效规范。**新版源码尚未引入，也没有可运行的新版本或新构建命令。**

从 [第一版实现计划](docs/planning/V1-IMPLEMENTATION-PLAN.md) 开始：先固定上游与可行性、完成 UI／交互设计，再实现普通输入基础和三个可选模块，最后完整离线交付。具体事实见 [项目状态](docs/STATUS.md)。

## 阅读入口

| 内容 | 文档 |
|---|---|
| 开始协作 | [AGENTS](AGENTS.md)、[协作流程](docs/collaboration/WORKFLOW.md) |
| 产品与已确认决定 | [PRODUCT](PRODUCT.md)、[产品决定](docs/product/DECISIONS.md) |
| 功能、设置和 UI | [模块](docs/product/MODULES.md)、[设置](docs/product/SETTINGS.md)、[界面](docs/design/UI-REQUIREMENTS.md) |
| 第一版怎么做 | [实现计划](docs/planning/V1-IMPLEMENTATION-PLAN.md)、[路线图](docs/planning/ROADMAP.md) |
| 架构与验收 | [架构](docs/ARCHITECTURE.md)、[验收](docs/qa/ACCEPTANCE.md) |
| 全部当前文档 | [索引](docs/INDEX.md) |
| 历史经验与归档 | [经验](docs/planning/LEGACY-LESSONS.md)、[归档入口](archive/README.md) |

公开仓库：[ikaros0202/suiyi](https://github.com/ikaros0202/suiyi)。继续在主目录 main 单写入者串行协作；文档管理对话不编写产品代码。归档与制定计划不表示开始编码或发布。
