# second-hand

## 项目介绍

second-hand 是一个基于 Uni-app 开发的校园二手交易平台。该项目允许用户在平台上发布、浏览和交易二手商品，方便快捷地实现物品的转让和获取。

## 功能特点

- **商品发布**：用户可以上传商品图片，填写商品名称、价格、描述等信息，发布自己的二手商品。
- **商品浏览**：用户可以浏览平台上的二手商品，查看商品的详细信息，包括图片、价格、描述等。
- **商品搜索**：用户可以通过搜索功能，快速找到自己需要的二手商品。
- **商品分类**：商品按照类别进行分类，用户可以根据类别浏览商品。
- **商品交易**：用户可以在线下进行商品交易，平台提供交易地点和时间的确认功能。

## 创新点

- **趣味功能**：提供了一些创新的功能，如 AI 辅助和地图浏览，增加了用户的使用体验。
- **视频滑动组件**：模仿抖音的视频滑动组件，用户可以以视频的形式浏览商品。

## 技术栈

- **前端**：Vue.js、Uni-app
- **后端**：Node.js、Express
- **其他**：WebSocket、讯飞星火

## 目录结构

```
- .hbuilderx
  └── launch.json
- babel.config.js
- jest.config.js
- package.json
- postcss.config.js
- project.config.json
- project.private.config.json
- public
- README.md
- shims-uni.d.ts
- shims-vue.d.ts
- src
  ├── App.vue
  ├── components
  │   ├── index.vue
  │   ├── map-popup
  │   │   └── map-popup.vue
  │   └── y-video-slide
  │       └── y-video-slide.vue
  ├── main.js
  ├── manifest.json
  ├── node-version
  ├── package.json
  ├── pages
  │   ├── addgoods
  │   │   └── addgoods.vue
  │   ├── addinfor
  │   │   └── addinfor.vue
  │   ├── admin
  │   │   └── admin.vue
  │   ├── ai
  │   │   └── ai.vue
  │   ├── detail
  │   │   └── detail.vue
  │   ├── goods
  │   │   └── goods.vue
  │   ├── home
  │   │   └── home.vue
  │   ├── homemap
  │   │   └── homemap.vue
  │   ├── index
  │   │   └── index.vue
  │   ├── myinfor
  │   │   └── myinfor.vue
  │   ├── myorder
  │   │   └── myorder.vue
  │   ├── spot
  │   │   └── spot.vue
  │   └── storeImage
  │       └── storeImage.vue
  ├── pages.json
  ├── static
  │   ├── css
  │   ├── index
  │   ├── markers
  │   └── tabbar
  └── uni_modules
      ├── uni-datetime-picker
      │   ├── changelog.md
      │   ├── components
      │   │   └── uni-datetime-picker
      │   │       ├── calendar-item.vue
      │   │       ├── calendar.vue
      │   │       ├── i18n
      │   │       │   ├── en.json
      │   │       │   ├── index.js
      │   │       │   ├── zh-Hans.json
      │   │       │   └── zh-Hant.json
      │   │       ├── time-picker.vue
      │   │       ├── uni-datetime-picker.vue
      │   │       └── util.js
      │   ├── package.json
      │   └── readme.md
      ├── uni-icons
      │   ├── changelog.md
      │   ├── components
      │   │   └── uni-icons
      │   │       ├── uni-icons.vue
      │   │       ├── uniicons_file.ts
      │   │       └── uniicons_file_vue.js
      │   ├── package.json
      │   └── readme.md
      └── uni-scss
          ├── changelog.md
          ├── package.json
          ├── readme.md
          └── styles
              ├── setting
              └── tools
```

## 目录说明

- `.hbuilderx`：HBuilderX 的配置文件。
- `babel.config.js`：Babel 的配置文件。
- `jest.config.js`：Jest 的配置文件。
- `package.json`：项目的依赖和脚本配置。
- `postcss.config.js`：PostCSS 的配置文件。
- `project.config.json`：项目的配置文件。
- `project.private.config.json`：项目的私有配置文件。
- `public`：公共资源目录。
- `README.md`：项目的说明文件。
- `shims-uni.d.ts`：Uni-app 的类型声明文件。
- `shims-vue.d.ts`：Vue 的类型声明文件。
- `src`：源码目录。
  - `App.vue`：项目的根组件。
  - `components`：组件目录。
  - `main.js`：项目的入口文件。
  - `manifest.json`：项目的清单文件。
  - `node-version`：项目的 Node.js 版本文件。
  - `pages`：页面目录。
  - `pages.json`：页面的配置文件。
  - `static`：静态资源目录。
  - `uni_modules`：Uni-app 的模块目录。
- `store`：Vuex 的状态管理目录。
- `utils`：工具函数目录。
- `vue.config.js`：Vue 的配置文件。

## 安装与运行

1. 克隆项目到本地
2. 进入项目目录
3. 安装依赖：`npm install`
4. 运行项目：`npm run wx`

## 贡献指南

如果您想为 second-hand 项目做出贡献，请遵循以下步骤：

1. Fork 项目到您的 GitHub 账户
2. 克隆 fork 过来的仓库到本地
3. 创建一个新的分支进行开发
4. 提交您的更改
5. 推送到您的 GitHub 仓库
6. 创建一个 Pull Request

## 联系方式

如果您有任何问题或建议，请通过以下方式联系：

- 邮箱：1028943406@qq.com
- GitHub：https://github.com/whr810012/
