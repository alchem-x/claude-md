## 项目工作规范

### 沟通语言

所有交流请使用**中文**进行，包括代码注释、提交信息等。

### 技术栈约定

- **脚本语言**：优先使用 Node.js 处理自动化任务
- **模块系统**：ES Modules 优先
  - 语法：`import` / `export`（现代标准）
  - 配置：package.json 添加 `"type": "module"`
  - 避免：`require()` / `module.exports`（CommonJS 弃用）
