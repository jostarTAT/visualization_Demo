```
请编写 Plotnine（ggplot 风格）代码，对 Top10 国家绘制一个基础的 stacked bar chart：

- x 轴：国家名（按照 Rank 顺序手动设置 categorical 顺序）
- y 轴：Contribution
- fill：Factor_zh
- 使用 geom_col()
- 暂不美化，仅用于检查映射是否正确

请提供完整代码。

```

```
请编写美化后的 Plotnine stacked bar 图代码，要求：

1. 使用 Set2 调色板。
2. 添加主标题、副标题、轴标签。
3. x 轴国家名旋转 35 度、右对齐。
4. 图例放底部、横向排列、无标题。
5. 去掉 panel_border、小网格线，加粗坐标轴。

确保代码可直接运行。

```

```
我需要增强 Top10 的 stacked bar 图：

1. 在柱体内部添加 Contribution 标签（仅当值 > 0.25 时显示）。
2. 在柱体顶部添加每个国家的总幸福分（Life evaluation）。
3. 位置使用 position_stack(vjust=0.5)（内部）和手动偏移（顶部）。
4. 字体大小适当加大。

请生成完整代码。

```

```
请为 Bottom10 国家生成 stacked bar chart，要求：

1. 与 Top10 风格一致（Set2 配色、横向图例、白色主题）。
2. 内部标签阈值改为 >0.15。
3. 添加顶部总幸福指数标签。
4. x 轴国家顺序按照 Rank 排列。

请给出完整可用代码。

```

```
请生成一个 Plotnine 分面 stacked bar 图，将 Top10 和 Bottom10 合并后分面绘制：

- 使用 concat 拼接 long-format 数据
- 添加 Group 列：Top 10 / Bottom 10
- facet_wrap(~Group, nrow=2, scales="free_x")

保持与之前图表相同的风格。

请输出完整代码。

```

```
请编写代码，绘制 2024 年 Top10 国家近十年的幸福指数折线图：

1. 从原始数据中筛选 Top10 国家的所有年份。
2. 保留最近 10 年（max_year - 9 ~ max_year）。
3. 绘制 x=Year, y=Life evaluation，color=Country name 的折线图。
4. 颜色按国家自动区分，legend 在下方。
5. 使用白色主题、无 panel_border、坐标轴加粗。

请生成完整代码。

```

```
请为 Top10 国家生成一个 Year × Country 的幸福指数透视表：

- index 为 Year
- columns 为 Country name
- values 为 Life evaluation (3-year average)
- 小数保留 3 位

并打印出来。

请给我完整代码。

```

