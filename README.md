{# 三角洲行动 - 小程序 (Taro + React + Rematch) 模板

说明：这是一个基于 Taro 的微信小程序骨架，包含路由、Rematch 状态管理与常见页面结构，供开发起步使用。

快速开始
1. 初始化（确保使用 Node 16+/pnpm/npm/yarn）
   - npm install
2. 开发（微信小程序）
   - npm run dev:weapp
   - 用微信开发者工具导入 `dist`（或 taro 输出目录）
3. 打包正式版
   - npm run build:weapp

常见目录
- src/pages: 页面
- src/components: 复用组件
- src/store: Rematch 模型与 store
- src/services: 后端请求封装
- src/styles: 全局样式/变量

备注
- 将 mock 接口替换为真实后端 API。
- 根据需要补充更多页面、权限校验、路由守卫与 platform-specific 逻辑.
}