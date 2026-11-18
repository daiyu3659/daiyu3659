# daiyu3659

用 Three.js 做一些能直接在浏览器里打开的 3D 页面：单文件、无构建、打开即用。

导航页：<https://daiyu3659.github.io/>

## 项目

| 项目 | 说明 | 在线演示 | 源码 |
| --- | --- | --- | --- |
| 水面时光 | 3D 钓鱼小游戏：抛竿、等鱼咬钩、收线搏鱼，最后把鱼拉上岸 | [打开](https://daiyu3659.github.io/fish/) | [fish](https://github.com/daiyu3659/fish) |
| 生产线实时可视化 | 卡通风格的 MES 产线场景，点击工位查看该工位的运行数据（演示数据） | [打开](https://daiyu3659.github.io/mes-production-line/) | [mes-production-line](https://github.com/daiyu3659/mes-production-line) |
| 药盒三维展示 | 单个药盒的实时渲染，支持拖拽旋转、滚轮或双指缩放 | [打开](https://daiyu3659.github.io/medicine-box-3d/) | [medicine-box-3d](https://github.com/daiyu3659/medicine-box-3d) |

## 技术说明

- 每个场景都写在一个 HTML 文件里，Three.js 与贴图（base64）全部内联，没有构建步骤，也没有外部依赖。
- 双击本地 `index.html` 即可运行，也可以直接访问上面的 GitHub Pages 地址。
- 产线场景中的生产数据为演示用假数据，不对应任何真实产线。
