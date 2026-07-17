# Codex 用户级全局 Skills 备份

本仓库备份 6 个用户级全局 Skill：

1. `project-handoff`
2. `systematic-debugging`
3. `targeted-tdd`
4. `phase-review`
5. `agent-browser`
6. `frontend-design`

## 本次新增

- `agent-browser`：在浏览器交互确有助于完成或验收当前任务时，允许 Codex 自动发现并按需调用。它还需要独立安装 npm CLI 和 Chrome for Testing 运行环境。
- `frontend-design`：在任务直接涉及新建或调整用户界面时，允许 Codex 自动发现并按需调用；不需要额外运行时。

自动调用始终服从用户当前指令、阶段目标、仓库范围、仓库内规范、设计参考、安全边界和最小必要原则。Skill 只能辅助当前任务，不能扩大范围或替代用户决定。完整边界见 [AUTO_INVOCATION.md](AUTO_INVOCATION.md)。

恢复 Skill 文件并不等于已经安装 `agent-browser` CLI。新电脑恢复步骤见 [RESTORE.md](RESTORE.md)。来源 commit、许可证和安装状态记录在各 Skill 的 `UPSTREAM.md` 与 `skill-install-manifest.json`。
