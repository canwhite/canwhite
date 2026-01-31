# Production.md - 项目全局状态文档

**最后更新**: 2026-01-31
**仓库类型**: GitHub个人主页

## 项目定位
GitHub个人名片仓库，用于展示项目作品集和技术能力

## 核心架构
- 静态Markdown展示页
- 依赖GitHub原生渲染
- 无构建工具链

## 技术栈
- Markdown
- GitHub Flavored Markdown (GFM)
- 可能扩展: README徽章、可视化图表

## 目录结构
```
canwhite/
├── README.md          # 主入口文件（个人名片）
├── CLAUDE.md          # Claude Code 执行协议
├── production.md      # 本文件（全局状态）
├── .claudecode.json   # Claude Code 配置
└── schema/            # 任务文档目录
    ├── task_*.md      # 进行中的任务
    └── archive/       # 已归档任务
```

## 项目分类
1. **近期工作** - pronovel智能小说平台
2. **Agent** - wkagent-pure, agentic-ai
3. **Claude Code三件套** - cc-session, cc-json-parser, cc-communication
4. **LLM** - happy-llm-simple, qc-torch-study等
5. **Spec Driven** - SimpleSpec
6. **iOS/Android** - 移动端框架
7. **Web3** - 钱包和区块链
8. **Infrastructures** - bun-php, frer等

## 部署流程
- 直接推送到GitHub main分支
- GitHub自动渲染README.md
- 访问: https://github.com/canwhite/canwhite

## 维护记录
- 2026-01-31: 初始化production.md
