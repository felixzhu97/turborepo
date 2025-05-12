# TurboRepo 项目文档（中文版）

## 项目简介
TurboRepo 是一个基于Rust的高性能monorepo构建系统，专为现代前端和后端项目设计。

## 主要特性
- 🚀 极快的增量构建
- 🔗 智能任务依赖分析
- 💾 高效的缓存系统
- ⚡ 并行任务执行
- 🔧 可扩展的插件系统

## 架构设计
项目采用模块化设计，主要包含：
- CLI：命令行接口
- 核心引擎：任务调度和执行
- 缓存系统：本地和远程缓存
- 依赖分析：构建任务依赖图

详细架构图见C4模型文档：
1. [系统上下文图](c4_context.puml)
2. [容器图](c4_container.puml) 
3. [组件图](c4_component.puml)
4. [代码图](c4_code.puml)

## 快速开始
```bash
# 安装
npm install -g turbo

# 使用
turbo run build
```

## 贡献指南
欢迎通过GitHub提交Issue和PR，贡献前请阅读：
- [代码规范](CONTRIBUTING.md)
- [行为准则](CODE_OF_CONDUCT.md)
