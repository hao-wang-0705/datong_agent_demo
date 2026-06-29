# 电影精选 Demo

这是一个用于埋点测试的演示项目，模拟一个内容平台的电影选择页面。

## 功能特性

- 🎬 电影列表展示（热门推荐、最新上线）
- 🔍 搜索功能
- 🏷️ 分类筛选（动作、科幻、爱情、喜剧、悬疑、动画）
- 📱 响应式设计
- 🎨 现代化 UI 设计

## 页面结构

- **首页**：电影列表 + 分类筛选 + 搜索
- **详情页**：电影详细信息 + 播放/收藏按钮

## 用途

本项目专门用于 TrackPilot 埋点测试：
- `main` 分支：用于埋点测试
- `baseline` 分支：原始状态，用于测试后快速恢复

## 本地运行

直接用浏览器打开 `index.html` 即可。

## 分支管理

```bash
# 测试完成后，从 baseline 恢复 main 分支
git checkout baseline
git branch -D main
git checkout -b main
git push origin main --force
```
