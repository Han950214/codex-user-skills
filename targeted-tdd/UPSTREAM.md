# 上游与适配记录

- 上游仓库：`https://github.com/mattpocock/skills.git`
- 上游路径：`skills/engineering/tdd`
- 锁定版本：tag `v1.1.0`
- 上游 commit：`d574778f94cf620fcc8ce741584093bc650a61d3`
- 上游许可证：MIT，见 `LICENSE.txt`
- 安装日期：2026-07-16
- 是否复制脚本：否；未复制单独参考文件，必要原则已适配进 `SKILL.md`
- 本地适配：将触发范围收窄到稳定测试 seam；明确排除纯视觉、文档、安装包和无稳定入口问题；采用红、绿、重构循环；禁止为测试暴露内部实现或新增投机抽象。
