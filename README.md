# BookmarkVision - 智能书签管理与可视化工具

BookmarkVision 是一个强大的 Chrome 浏览器扩展，它能够智能地管理和可视化您的书签，让书签管理变得更加简单和直观。

## 主要特性

### 1. 智能分类
- 自动对书签进行分类，支持科技、教育、娱乐、社交、新闻、购物、工具等多个类别
- 使用 Cursor API 进行智能分析，提供更准确的分类结果
- 支持自定义分类规则，满足个性化需求

### 2. 双视图模式
- **卡片视图**：以网格形式展示书签，清晰直观
- **网络图谱视图**：通过力导向图展示书签之间的关联关系，帮助发现书签之间的联系

### 3. 强大的搜索和过滤
- 实时搜索功能，支持按标题和URL搜索
- 多分类过滤，快速找到所需书签
- 分类统计信息，直观展示各类书签数量

### 4. 现代化界面
- 采用 Tailwind CSS 构建的现代化UI设计
- 响应式布局，完美适配不同屏幕尺寸
- 优雅的动画效果和交互体验

## 安装说明

1. 克隆项目到本地：
```bash
git clone https://github.com/xieburou0512/BookmarkVision.git
cd BookmarkVision
```

2. 安装依赖：
```bash
npm install
```

3. 构建项目：
```bash
npm run build
```

4. 在Chrome浏览器中加载扩展：
   - 打开 Chrome 扩展管理页面 (chrome://extensions/)
   - 开启"开发者模式"
   - 点击"加载已解压的扩展程序"
   - 选择项目中的 `dist` 目录

## 使用说明

1. 点击 Chrome 工具栏中的 BookmarkVision 图标打开扩展
2. 首次使用需要配置 Cursor API 密钥（可选）：
   - 右键点击扩展图标
   - 选择"选项"
   - 在设置页面输入并保存 API 密钥

3. 使用搜索栏和分类过滤器查找书签
4. 点击书签卡片在新标签页中打开链接
5. 切换视图模式查看不同的展示效果

## 技术栈

### 前端框架
- **React + TypeScript**
  - 使用 React 18 构建用户界面
  - TypeScript 提供类型安全
  - 采用函数式组件和 Hooks 开发
  - 使用 React Context 管理全局状态

### 样式解决方案
- **Tailwind CSS**
  - 原子化 CSS 框架
  - 响应式设计支持
  - 自定义主题配置
  - 按需编译优化

### 数据可视化
- **D3.js**
  - 实现网络图谱可视化
  - 力导向图布局算法
  - 交互式图表展示
  - 动态数据更新

### 浏览器扩展开发
- **Chrome Extension API**
  - 书签管理 API
  - 存储 API
  - 消息通信
  - 权限管理

### AI 服务集成
- **Cursor API**
  - 智能书签分类
  - 自然语言处理
  - 语义分析
  - 分类置信度评估

### 开发工具
- **Webpack**
  - 模块打包
  - 资源优化
  - 开发服务器
  - 热更新支持

- **ESLint + Prettier**
  - 代码规范检查
  - 自动格式化
  - TypeScript 支持
  - 团队协作规范

### 版本控制
- **Git**
  - 分支管理
  - 版本追踪
  - 协作开发
  - 代码审查

## 开发计划

- [ ] 支持书签标签管理
- [ ] 添加书签导入/导出功能
- [ ] 支持自定义主题
- [ ] 添加书签分享功能
- [ ] 支持多语言

## 贡献指南

欢迎提交 Issue 和 Pull Request 来帮助改进 BookmarkVision。在提交代码前，请确保：

1. 代码符合项目的代码规范
2. 所有测试通过
3. 提交信息清晰明了

## 许可证

本项目采用 MIT 许可证 - 详见 [LICENSE](LICENSE) 文件

## 致谢

- 感谢所有贡献者的付出
- 特别感谢 Cursor API 提供的智能分类服务
- 感谢 D3.js 提供的强大可视化能力

## 联系方式

- 项目主页：[GitHub](https://github.com/xieburou0512/BookmarkVision)
- 问题反馈：[Issues](https://github.com/xieburou0512/BookmarkVision/issues)
- 邮件联系：x8999296@gmail.com 