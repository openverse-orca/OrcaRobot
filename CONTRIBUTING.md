# 贡献指南

感谢你对 OrcaRobot 项目的关注！本文档将帮助你快速了解如何参与贡献。

## 开始之前

1. 确保你已阅读项目的 [README.md](https://github.com/openverse-orca/orcarobot/blob/main/README.md)，了解项目的基本信息
2. 如果是报告问题，请先搜索 [Issues](https://github.com/openverse-orca/orcarobot/issues)，避免重复提交

## 如何贡献

### 报告 Bug

如果你发现了问题，请通过 [Issues](https://github.com/openverse-orca/orcarobot/issues) 提交，并包含以下信息：

- 问题的简要描述
- 复现步骤
- 期望行为与实际行为
- 运行环境（操作系统、Python 版本等）
- 相关的错误日志或截图

### 提交新示例

我们非常欢迎新的机器人仿真示例！添加新示例时请遵循以下规范：

1. **目录结构**：在 `examples/` 下新建分类目录，或使用 `XX-` 前缀进行编号
2. **必需文件**：
   - `README.md`：说明示例的功能、运行方式和依赖
   - `main.py`：示例的主程序入口
   - `config.yaml`：配置文件（如有需要）
3. **代码规范**：
   - 遵循 PEP 8 代码风格
   - 添加必要的注释说明关键逻辑
   - 确保代码可以在标准环境下直接运行
4. **测试**：提交 PR 前请确保示例可以正常运行，CI 测试会通过

### 改进文档

文档改进同样是非常有价值的贡献！你可以：

- 修正错别字或表述不清的地方
- 补充更详细的说明或示例
- 翻译文档到其他语言

### 提交代码更改

1. Fork 本仓库并克隆到本地
2. 创建一个新的分支：`git checkout -b feature/your-feature-name`
3. 进行你的修改并提交：`git commit -m "描述你的更改"`
4. 推送到你的 Fork：`git push origin feature/your-feature-name`
5. 在 GitHub 上提交 Pull Request

## Pull Request 规范

- 请确保 PR 描述清晰地说明了更改的内容和目的
- 如果 PR 与某个 Issue 相关，请在描述中引用该 Issue
- 保持提交历史整洁，避免不必要的合并提交
- 确保所有 CI 检查通过

## 行为准则

- 保持友善和尊重，欢迎所有水平的贡献者
- 接受建设性的批评和反馈
- 关注对社区最有利的事情

## 需要帮助？

如果你在贡献过程中遇到任何问题，欢迎：

- 在 [Issues](https://github.com/openverse-orca/orcarobot/issues) 中提问
- 联系维护团队

再次感谢你的贡献！
