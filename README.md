# daiyu3659

用 Three.js 做一些能直接在浏览器里打开的 3D 页面：单文件、无构建、打开即用。

导航页：<https://daiyu3659.github.io/>

## 项目

| 项目 | 说明 | 在线演示 | 源码 |
| --- | --- | --- | --- |
| 水面时光 | 3D 钓鱼小游戏：抛竿、等鱼咬钩、收线搏鱼，最后把鱼拉上岸 | [打开](https://daiyu3659.github.io/fish/) | [fish](https://github.com/daiyu3659/fish) |
| 生产线实时可视化 | 卡通风格的 MES 产线场景，点击工位查看该工位的运行数据（演示数据） | [打开](https://daiyu3659.github.io/mes-production-line/) | [mes-production-line](https://github.com/daiyu3659/mes-production-line) |
| 药盒三维展示 | 单个药盒的实时渲染，支持拖拽旋转、滚轮或双指缩放 | [打开](https://daiyu3659.github.io/medicine-box-3d/) | [medicine-box-3d](https://github.com/daiyu3659/medicine-box-3d) |
| 咖啡机三维操作指南（德龙 ECAM350.55，技术验证） | 按步骤高亮按键与部件，可拖拽旋转；手机竖屏可收起步骤面板 | [打开](https://daiyu3659.github.io/coffee-machine-guide/) | [coffee-machine-guide](https://github.com/daiyu3659/coffee-machine-guide) |

## 技术说明

- 前三个场景都写在一个 HTML 文件里，Three.js 与贴图（base64）全部内联；咖啡机指南使用独立的模型与 Three.js 模块文件。统一没有构建步骤，也没有后端依赖。
- 前三个场景双击本地 `index.html` 即可运行；咖啡机指南含独立模型，需用静态服务器（如 `python3 -m http.server`）打开。也可以直接访问上面的 GitHub Pages 地址。
- 产线场景中的生产数据为演示用假数据，不对应任何真实产线。
