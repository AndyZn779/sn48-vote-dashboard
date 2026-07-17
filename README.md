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

## LLM Generated Index
| Page | Description |
|------|-------------|
| dashboard.html | Main dashboard - shows Top20 rankings, group distributions, fan leaderboard (8 charts total) |
| indicators.html | Quantitative metrics - Gini coefficient, Pareto distribution, HHI, competition analysis, etc. |
| comparison.html | 3-year comparison dashboard - total votes, champion votes, cutoff trends, distribution histograms, radar charts, scatter/line curves for the entire election |
| zq_s2_analysis.html | Zhang Qian x Team SII deep analysis |
| zq_3year.html | Zhang Qian 3-year full comparison - ranking trend, vote growth, fan count, top fan contribution, Gini coefficient, Top20 fan comparison, gift breakdown, average fan vote, top1 fan share |
| zq_report.html | Zhang Qian historical election analysis report - comprehensive HTML report with detailed text analysis and 8 charts covering ranking, votes, fan structure, gifts, competition, and theoretical analysis |
| zq_test.html | Zhang Qian ECharts test page (simple chart verification) |

## Zhang Qian Analysis Report (Word)
\u5f20\u5029_\u5386\u5e74\u603b\u9009\u6570\u636e\u5206\u6790\u62a5\u544a.docx - Full Word report with 7 chapters including theoretical analysis models (fan lifecycle, Pareto, S-curve, dual-drive voting model, etc.)
