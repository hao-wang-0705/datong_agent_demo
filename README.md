# 松果小铺 · datong_agent_demo

TrackPilot demo 的预置目标项目（静态站点，无埋点 / 未接入 SDK 的初始状态）。

- `index.html`：纯演示电商页面（无真实交易），尾部保留 `<!-- TRACKPILOT_SNIPPET -->` 占位符，供后续 AI 接入 SDK 时注入。
- `package.json`：本地预览脚本 `npm run dev`（基于 `serve`）。

本仓库代表「未接入、无埋点」的干净起点，用于走查完整的接入到分析流程。
