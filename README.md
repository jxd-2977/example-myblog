# muses-web-portal

前端门户应用，基于 Vue 2.x + Element UI 开发，采用 Single SPA 架构，负责子应用的加载和生命周期管理。

## 技术栈

- **框架**: Vue 2.6.10, Vue Router 3.0.6, Vuex 3.1.0
- **UI 组件**: Element UI 2.x
- **构建工具**: Vue CLI 4.4.4
- **架构**: Single SPA
- **样式**: Less
- **图表**: ECharts

## 主要功能

### 门户首页
- 系统总览
- 快速导航
- 通知公告

### 应用管理
- 子应用加载
- 应用生命周期管理
- 应用间通信

### 用户中心
- 用户信息展示
- 个人设置
- 安全中心

## 开发命令

```bash
# 安装依赖
npm install

# 启动开发服务器
npm run dev

# 生产环境构建
npm run build:prod

# 预发布环境构建
npm run build:stage

# 代码 lint 检查
npm run lint

# 运行单元测试
npm run test:unit

# CI 流程（lint + 测试）
npm run test:ci

# 优化 SVG 图标
npm run svgo

# 预览构建结果
npm run preview
```

## 目录结构

```
muses-web-portal/
├── public/              # 静态资源
├── src/
│   ├── api/            # API 接口定义
│   ├── assets/         # 资源文件
│   ├── components/     # 通用组件
│   ├── icons/          # SVG 图标
│   ├── layout/         # 布局组件
│   ├── router/         # 路由配置
│   ├── store/          # Vuex 状态管理
│   ├── styles/         # 全局样式
│   ├── utils/          # 工具函数
│   └── views/          # 页面组件
├── package.json        # 依赖配置
└── vue.config.js       # Vue CLI 配置
```

## 注意事项

1. Node.js 版本 >= 8.9，npm 版本 >= 3.0.0
2. 开发时需要同时启动后端服
3. 子应用需要正确配置到 Single SPA 中
