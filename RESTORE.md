# 新电脑恢复说明

1. 将 6 个 Skill 目录恢复到 `%USERPROFILE%\.agents\skills`，并将 `skill-install-manifest.json` 恢复到 `%USERPROFILE%\.agents`。
2. 确认 Node.js 与 npm 已安装；恢复时先阅读 agent-browser 当前官方 README，以当时的正式安装方式为准。
3. 若官方命令仍有效，执行 `npm install -g agent-browser`，再执行 `agent-browser install` 下载 Chrome for Testing。
4. 确认 npm 用户级全局目录已在用户级 PATH 中，然后执行 `agent-browser --version`、`agent-browser --help` 和 `agent-browser skills list`。
5. 重新打开终端并重启 Codex，确认 `agent-browser` 与 `frontend-design` 位于用户级全局可发现范围。

Skill 文件恢复不等于 `agent-browser` CLI 或浏览器运行环境已安装。不要恢复或备份 Cookie、密码、Token、浏览器 Profile、浏览器缓存、登录状态和浏览器二进制。
