# React 项目模板

这是一个基于 React + TypeScript + Vite 的现代化前端项目模板。

## 特性

- ⚡️ [Vite](https://vitejs.dev/) - 极速的下一代前端构建工具。
- ⚛️ [React 19](https://react.dev/) - 用于构建用户界面的库。
- 📘 [TypeScript](https://www.typescriptlang.org/) - JavaScript 的超集，添加了类型支持。
- 🎨 [Biome](https://biomejs.dev/) - 高性能的代码格式化和 Lint 工具。
- 🧪 [Vitest](https://vitest.dev/) - 由 Vite 提供支持的极速单元测试框架。
- 🎭 [Playwright](https://playwright.dev/) - 可靠的端到端测试工具。
- 🔍 [Lefthook](https://github.com/evilmartians/lefthook) - 快速而强大的 Git 钩子管理器。
- 💬 [Commitlint](https://commitlint.js.org/) - 检查你的提交信息是否符合规范。
- 📦 [pnpm](https://pnpm.io/) - 快速、节省磁盘空间的前端包管理器。

## 如何开始

### 环境要求

- [Node.js](https://nodejs.org/) (>=20)
- [pnpm](https://pnpm.io/installation)

### 安装

```bash
pnpm install
```

### 可用脚本

- `pnpm dev` - 启动开发服务器。
- `pnpm build` - 构建生产环境的应用。
- `pnpm test` - 运行单元测试。
- `pnpm test:e2e` - 运行端到端测试。
- `pnpm format` - 使用 Biome 格式化代码。
- `pnpm lint` - 使用 Biome 检查代码。
- `pnpm preview` - 本地预览生产构建。

## Git 提交规范

本项目使用 [Commitlint](https://commitlint.js.org/) 来规范 Git 提交信息，并结合 [Lefthook](https://github.com/evilmartians/lefthook) 在 `commit-msg` 钩子中进行校验。请确保你的提交信息符合 [Conventional Commits](https://www.conventionalcommits.org/) 规范。
