# SNH48 Group 总选实时数据看板

每次打开页面自动从 xox48.top API 拉取最新数据，在浏览器端实时计算所有指标（基尼系数、帕累托、HHI、队内分析等），并渲染 ECharts 图表。

## 页面列表

| 文件 | 说明 |
|---|---|
| dashboard.html | 主仪表盘 - 8个图表，展示Top20、集团分布、粉丝榜等 |
| indicators.html | 量化指数 - 基尼系数、帕累托分布、竞争分析等 |
| zq_s2_analysis.html | 张倩 × Team SII 深度分析 |

## 技术说明

- 纯前端，无服务器依赖
- 数据来源: xox48.top (CORS 开放)
- 图表库: ECharts 5.4.3
- 所有数据在浏览器端实时计算


## 张倩专用页面

| 文件 | 说明 |
|---|---|
| zq_3year.html | 张倩三年总选完整数据对比 - 排名/票数/粉丝/礼物等10组图表 |
| zq_test.html | 张倩 ECharts 测试页 |
| zq_s2_analysis.html | 张倩 x Team SII 深度分析 |
