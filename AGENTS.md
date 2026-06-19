## Agent skills

### Issue tracker

GitHub Issues（使用 `gh` CLI）。当前仓库尚未初始化 git，需要先 `git init` 并 `git remote add origin <你的 GitHub 仓库 URL>`，否则 `gh` 无法自动推断仓库。详见 `docs/agents/issue-tracker.md`。

### Triage labels

默认的五种状态标签词汇（`needs-triage` / `needs-info` / `ready-for-agent` / `ready-for-human` / `wontfix`）。详见 `docs/agents/triage-labels.md`。

### Domain docs

单上下文：`CONTEXT.md` + `docs/adr/` 在仓库根。详见 `docs/agents/domain.md`。