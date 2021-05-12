# datav-best

数据可视化-实践记录

### 参考文档

[数据可视化指南](http://www.youbaobao.xyz/datav-docs/guide/)

### 三个典型的商业级数据可视化项目

- 项目 1：PC 端数据报表
- 项目 2：PC 端数据大屏
- 项目 3：移动报表

### 数据报表项目

- Vue 2.6 + Element-UI + EChart4.7
- ECharts 常用报表 + 样式定制 + 自定义渲染
- vue-echarts + v-charts
- 地图可视化：散点图

### 数据大屏项目

- Vue 3.0 + Echarts 4.7 + Svg
- 地图可视化：飞线动画 + 3D 地图
- 大屏容器组件

### 移动报表项目

- Vue 3.0 + ECharts 4.7
- 移动报表 + 地图
- 移动项目构建 + px2rem

### 地图可视化

- 地图常见用法：控件、绘图、动画...(百度地图、高德地图)
- 地图可视化：散点、飞线动画、混合动画、3D 建筑...
- 地图 + Vue + ECharts

### 数据可视化解决方案

HighCharts Echarts AntV
three.js zrender d3
Canvas Svg WebGL HTML (浏览器提供的默认的绘图能力)
Chrome (使用 Skia 作为绘图引擎，向上层开放了 canvas、svg、WebGL、HTML 等绘图能力。)
Skia OpenGL (最底层绘图引擎)

zrender 是对 canvas 和 svg 的封装； 是 Echarts 的底层框架
