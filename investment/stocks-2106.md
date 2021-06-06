---
layout: full_width
title: 选股(2106)
---


<style>
table {font-size: 12px;}
</style>
# 选股

### 指标说明

1. 负债率: 总负债/总资产，最近一期年报
2. 应收比: 应收款/总营收，最近一期年报
3. 商誉比：商誉/总资产，最近一期年报
4. ROE：净利润/归属于上市公司股东净资产，4年平均值
5. 利润率：净利润/总营收，4年平均值
6. 收入增长：总营收年同比增长，3年平均
7. 盈利：净利润，4年平均
8. 盈利增长：净利润年同比增长，3年平均
9. FCF：自由现金流，4年平均
10. FCF增长：自由现金流年同比增长，3年平均
11. 波动：年同比增长的标准差
12. DCF：现金流折现，以FCF作为当前值，以FCF增长率增长3年，永续增长为0，折现率0.08
13. 盈利折现：以净利润折现
14. 折价率：(1 - 市值/DCF) * 100

## 中国A股

### 基本指标筛选

1. 负债率 <= 70%
2. 应收比 < 20%
3. 商誉比 < 10%
4. ROE >= 20%
5. 利润率 >= 20%
6. 收入增长 >= 15% 或 盈利增长(三年平均) >= 15%




<style  type="text/css" >
#T_d50ab_row0_col0,#T_d50ab_row0_col1,#T_d50ab_row0_col2,#T_d50ab_row0_col3,#T_d50ab_row0_col4,#T_d50ab_row0_col5,#T_d50ab_row0_col6,#T_d50ab_row0_col7,#T_d50ab_row0_col8,#T_d50ab_row0_col10,#T_d50ab_row0_col11,#T_d50ab_row0_col12,#T_d50ab_row0_col13,#T_d50ab_row0_col16,#T_d50ab_row0_col17,#T_d50ab_row0_col18,#T_d50ab_row0_col19,#T_d50ab_row0_col20,#T_d50ab_row0_col21,#T_d50ab_row0_col22,#T_d50ab_row0_col23,#T_d50ab_row1_col0,#T_d50ab_row1_col1,#T_d50ab_row1_col2,#T_d50ab_row1_col3,#T_d50ab_row1_col4,#T_d50ab_row1_col5,#T_d50ab_row1_col6,#T_d50ab_row1_col7,#T_d50ab_row1_col8,#T_d50ab_row1_col9,#T_d50ab_row1_col10,#T_d50ab_row1_col11,#T_d50ab_row1_col12,#T_d50ab_row1_col13,#T_d50ab_row1_col15,#T_d50ab_row1_col16,#T_d50ab_row1_col17,#T_d50ab_row1_col18,#T_d50ab_row1_col19,#T_d50ab_row1_col20,#T_d50ab_row1_col21,#T_d50ab_row1_col23,#T_d50ab_row1_col24,#T_d50ab_row2_col0,#T_d50ab_row2_col1,#T_d50ab_row2_col2,#T_d50ab_row2_col3,#T_d50ab_row2_col4,#T_d50ab_row2_col5,#T_d50ab_row2_col6,#T_d50ab_row2_col7,#T_d50ab_row2_col8,#T_d50ab_row2_col10,#T_d50ab_row2_col11,#T_d50ab_row2_col12,#T_d50ab_row2_col13,#T_d50ab_row2_col14,#T_d50ab_row2_col16,#T_d50ab_row2_col17,#T_d50ab_row2_col18,#T_d50ab_row2_col19,#T_d50ab_row2_col20,#T_d50ab_row2_col21,#T_d50ab_row2_col22,#T_d50ab_row2_col23,#T_d50ab_row3_col0,#T_d50ab_row3_col1,#T_d50ab_row3_col2,#T_d50ab_row3_col3,#T_d50ab_row3_col4,#T_d50ab_row3_col5,#T_d50ab_row3_col6,#T_d50ab_row3_col7,#T_d50ab_row3_col8,#T_d50ab_row3_col9,#T_d50ab_row3_col10,#T_d50ab_row3_col11,#T_d50ab_row3_col12,#T_d50ab_row3_col13,#T_d50ab_row3_col14,#T_d50ab_row3_col16,#T_d50ab_row3_col17,#T_d50ab_row3_col18,#T_d50ab_row3_col19,#T_d50ab_row3_col20,#T_d50ab_row3_col21,#T_d50ab_row3_col23,#T_d50ab_row3_col24,#T_d50ab_row4_col0,#T_d50ab_row4_col1,#T_d50ab_row4_col2,#T_d50ab_row4_col3,#T_d50ab_row4_col4,#T_d50ab_row4_col5,#T_d50ab_row4_col6,#T_d50ab_row4_col7,#T_d50ab_row4_col8,#T_d50ab_row4_col9,#T_d50ab_row4_col10,#T_d50ab_row4_col11,#T_d50ab_row4_col12,#T_d50ab_row4_col13,#T_d50ab_row4_col14,#T_d50ab_row4_col15,#T_d50ab_row4_col16,#T_d50ab_row4_col17,#T_d50ab_row4_col18,#T_d50ab_row4_col19,#T_d50ab_row4_col20,#T_d50ab_row4_col21,#T_d50ab_row4_col22,#T_d50ab_row4_col23,#T_d50ab_row4_col24,#T_d50ab_row5_col0,#T_d50ab_row5_col1,#T_d50ab_row5_col2,#T_d50ab_row5_col3,#T_d50ab_row5_col4,#T_d50ab_row5_col5,#T_d50ab_row5_col6,#T_d50ab_row5_col7,#T_d50ab_row5_col8,#T_d50ab_row5_col9,#T_d50ab_row5_col10,#T_d50ab_row5_col11,#T_d50ab_row5_col12,#T_d50ab_row5_col13,#T_d50ab_row5_col14,#T_d50ab_row5_col15,#T_d50ab_row5_col16,#T_d50ab_row5_col17,#T_d50ab_row5_col18,#T_d50ab_row5_col19,#T_d50ab_row5_col20,#T_d50ab_row5_col21,#T_d50ab_row5_col22,#T_d50ab_row5_col23,#T_d50ab_row5_col24,#T_d50ab_row6_col0,#T_d50ab_row6_col1,#T_d50ab_row6_col2,#T_d50ab_row6_col3,#T_d50ab_row6_col4,#T_d50ab_row6_col5,#T_d50ab_row6_col6,#T_d50ab_row6_col7,#T_d50ab_row6_col8,#T_d50ab_row6_col9,#T_d50ab_row6_col10,#T_d50ab_row6_col11,#T_d50ab_row6_col12,#T_d50ab_row6_col13,#T_d50ab_row6_col14,#T_d50ab_row6_col15,#T_d50ab_row6_col16,#T_d50ab_row6_col17,#T_d50ab_row6_col18,#T_d50ab_row6_col19,#T_d50ab_row6_col20,#T_d50ab_row6_col21,#T_d50ab_row6_col22,#T_d50ab_row6_col23,#T_d50ab_row6_col24,#T_d50ab_row7_col0,#T_d50ab_row7_col1,#T_d50ab_row7_col2,#T_d50ab_row7_col3,#T_d50ab_row7_col4,#T_d50ab_row7_col5,#T_d50ab_row7_col6,#T_d50ab_row7_col7,#T_d50ab_row7_col8,#T_d50ab_row7_col9,#T_d50ab_row7_col10,#T_d50ab_row7_col11,#T_d50ab_row7_col12,#T_d50ab_row7_col13,#T_d50ab_row7_col14,#T_d50ab_row7_col15,#T_d50ab_row7_col16,#T_d50ab_row7_col17,#T_d50ab_row7_col18,#T_d50ab_row7_col19,#T_d50ab_row7_col20,#T_d50ab_row7_col21,#T_d50ab_row7_col22,#T_d50ab_row7_col23,#T_d50ab_row8_col0,#T_d50ab_row8_col1,#T_d50ab_row8_col2,#T_d50ab_row8_col3,#T_d50ab_row8_col4,#T_d50ab_row8_col5,#T_d50ab_row8_col6,#T_d50ab_row8_col7,#T_d50ab_row8_col8,#T_d50ab_row8_col9,#T_d50ab_row8_col10,#T_d50ab_row8_col11,#T_d50ab_row8_col12,#T_d50ab_row8_col13,#T_d50ab_row8_col14,#T_d50ab_row8_col15,#T_d50ab_row8_col16,#T_d50ab_row8_col17,#T_d50ab_row8_col18,#T_d50ab_row8_col19,#T_d50ab_row8_col20,#T_d50ab_row8_col21,#T_d50ab_row8_col22,#T_d50ab_row8_col23,#T_d50ab_row9_col0,#T_d50ab_row9_col1,#T_d50ab_row9_col2,#T_d50ab_row9_col3,#T_d50ab_row9_col4,#T_d50ab_row9_col5,#T_d50ab_row9_col6,#T_d50ab_row9_col7,#T_d50ab_row9_col8,#T_d50ab_row9_col9,#T_d50ab_row9_col10,#T_d50ab_row9_col11,#T_d50ab_row9_col12,#T_d50ab_row9_col13,#T_d50ab_row9_col14,#T_d50ab_row9_col15,#T_d50ab_row9_col16,#T_d50ab_row9_col17,#T_d50ab_row9_col18,#T_d50ab_row9_col19,#T_d50ab_row9_col20,#T_d50ab_row9_col21,#T_d50ab_row9_col22,#T_d50ab_row9_col23,#T_d50ab_row10_col0,#T_d50ab_row10_col1,#T_d50ab_row10_col2,#T_d50ab_row10_col3,#T_d50ab_row10_col4,#T_d50ab_row10_col5,#T_d50ab_row10_col6,#T_d50ab_row10_col7,#T_d50ab_row10_col8,#T_d50ab_row10_col9,#T_d50ab_row10_col10,#T_d50ab_row10_col11,#T_d50ab_row10_col12,#T_d50ab_row10_col13,#T_d50ab_row10_col14,#T_d50ab_row10_col15,#T_d50ab_row10_col16,#T_d50ab_row10_col17,#T_d50ab_row10_col18,#T_d50ab_row10_col19,#T_d50ab_row10_col20,#T_d50ab_row10_col21,#T_d50ab_row10_col22,#T_d50ab_row10_col23,#T_d50ab_row11_col0,#T_d50ab_row11_col1,#T_d50ab_row11_col2,#T_d50ab_row11_col3,#T_d50ab_row11_col4,#T_d50ab_row11_col5,#T_d50ab_row11_col6,#T_d50ab_row11_col7,#T_d50ab_row11_col8,#T_d50ab_row11_col9,#T_d50ab_row11_col10,#T_d50ab_row11_col11,#T_d50ab_row11_col12,#T_d50ab_row11_col13,#T_d50ab_row11_col14,#T_d50ab_row11_col16,#T_d50ab_row11_col17,#T_d50ab_row11_col18,#T_d50ab_row11_col19,#T_d50ab_row11_col20,#T_d50ab_row11_col21,#T_d50ab_row11_col23,#T_d50ab_row11_col24,#T_d50ab_row12_col0,#T_d50ab_row12_col1,#T_d50ab_row12_col2,#T_d50ab_row12_col3,#T_d50ab_row12_col4,#T_d50ab_row12_col5,#T_d50ab_row12_col6,#T_d50ab_row12_col7,#T_d50ab_row12_col8,#T_d50ab_row12_col9,#T_d50ab_row12_col10,#T_d50ab_row12_col11,#T_d50ab_row12_col12,#T_d50ab_row12_col13,#T_d50ab_row12_col14,#T_d50ab_row12_col15,#T_d50ab_row12_col16,#T_d50ab_row12_col17,#T_d50ab_row12_col18,#T_d50ab_row12_col19,#T_d50ab_row12_col20,#T_d50ab_row12_col21,#T_d50ab_row12_col22,#T_d50ab_row12_col23,#T_d50ab_row13_col0,#T_d50ab_row13_col1,#T_d50ab_row13_col2,#T_d50ab_row13_col3,#T_d50ab_row13_col4,#T_d50ab_row13_col5,#T_d50ab_row13_col6,#T_d50ab_row13_col7,#T_d50ab_row13_col8,#T_d50ab_row13_col9,#T_d50ab_row13_col10,#T_d50ab_row13_col11,#T_d50ab_row13_col12,#T_d50ab_row13_col13,#T_d50ab_row13_col14,#T_d50ab_row13_col15,#T_d50ab_row13_col16,#T_d50ab_row13_col17,#T_d50ab_row13_col18,#T_d50ab_row13_col19,#T_d50ab_row13_col20,#T_d50ab_row13_col21,#T_d50ab_row13_col22,#T_d50ab_row13_col23,#T_d50ab_row14_col0,#T_d50ab_row14_col1,#T_d50ab_row14_col2,#T_d50ab_row14_col3,#T_d50ab_row14_col4,#T_d50ab_row14_col5,#T_d50ab_row14_col6,#T_d50ab_row14_col7,#T_d50ab_row14_col8,#T_d50ab_row14_col9,#T_d50ab_row14_col10,#T_d50ab_row14_col11,#T_d50ab_row14_col12,#T_d50ab_row14_col13,#T_d50ab_row14_col14,#T_d50ab_row14_col15,#T_d50ab_row14_col16,#T_d50ab_row14_col17,#T_d50ab_row14_col18,#T_d50ab_row14_col19,#T_d50ab_row14_col20,#T_d50ab_row14_col21,#T_d50ab_row14_col22,#T_d50ab_row14_col23,#T_d50ab_row15_col0,#T_d50ab_row15_col1,#T_d50ab_row15_col2,#T_d50ab_row15_col3,#T_d50ab_row15_col4,#T_d50ab_row15_col5,#T_d50ab_row15_col6,#T_d50ab_row15_col7,#T_d50ab_row15_col8,#T_d50ab_row15_col9,#T_d50ab_row15_col10,#T_d50ab_row15_col11,#T_d50ab_row15_col12,#T_d50ab_row15_col13,#T_d50ab_row15_col14,#T_d50ab_row15_col16,#T_d50ab_row15_col17,#T_d50ab_row15_col18,#T_d50ab_row15_col19,#T_d50ab_row15_col20,#T_d50ab_row15_col21,#T_d50ab_row15_col23,#T_d50ab_row15_col24,#T_d50ab_row16_col0,#T_d50ab_row16_col1,#T_d50ab_row16_col2,#T_d50ab_row16_col3,#T_d50ab_row16_col4,#T_d50ab_row16_col5,#T_d50ab_row16_col6,#T_d50ab_row16_col7,#T_d50ab_row16_col8,#T_d50ab_row16_col9,#T_d50ab_row16_col10,#T_d50ab_row16_col11,#T_d50ab_row16_col12,#T_d50ab_row16_col13,#T_d50ab_row16_col14,#T_d50ab_row16_col15,#T_d50ab_row16_col16,#T_d50ab_row16_col17,#T_d50ab_row16_col18,#T_d50ab_row16_col19,#T_d50ab_row16_col20,#T_d50ab_row16_col21,#T_d50ab_row16_col22,#T_d50ab_row16_col23,#T_d50ab_row17_col0,#T_d50ab_row17_col1,#T_d50ab_row17_col2,#T_d50ab_row17_col3,#T_d50ab_row17_col4,#T_d50ab_row17_col5,#T_d50ab_row17_col6,#T_d50ab_row17_col7,#T_d50ab_row17_col8,#T_d50ab_row17_col9,#T_d50ab_row17_col10,#T_d50ab_row17_col11,#T_d50ab_row17_col12,#T_d50ab_row17_col13,#T_d50ab_row17_col14,#T_d50ab_row17_col15,#T_d50ab_row17_col16,#T_d50ab_row17_col17,#T_d50ab_row17_col18,#T_d50ab_row17_col19,#T_d50ab_row17_col20,#T_d50ab_row17_col21,#T_d50ab_row17_col22,#T_d50ab_row17_col23,#T_d50ab_row17_col24,#T_d50ab_row18_col0,#T_d50ab_row18_col1,#T_d50ab_row18_col2,#T_d50ab_row18_col3,#T_d50ab_row18_col4,#T_d50ab_row18_col5,#T_d50ab_row18_col6,#T_d50ab_row18_col7,#T_d50ab_row18_col8,#T_d50ab_row18_col9,#T_d50ab_row18_col10,#T_d50ab_row18_col11,#T_d50ab_row18_col12,#T_d50ab_row18_col13,#T_d50ab_row18_col14,#T_d50ab_row18_col15,#T_d50ab_row18_col16,#T_d50ab_row18_col17,#T_d50ab_row18_col18,#T_d50ab_row18_col19,#T_d50ab_row18_col20,#T_d50ab_row18_col21,#T_d50ab_row18_col22,#T_d50ab_row18_col23,#T_d50ab_row19_col0,#T_d50ab_row19_col1,#T_d50ab_row19_col2,#T_d50ab_row19_col3,#T_d50ab_row19_col4,#T_d50ab_row19_col5,#T_d50ab_row19_col6,#T_d50ab_row19_col7,#T_d50ab_row19_col8,#T_d50ab_row19_col9,#T_d50ab_row19_col10,#T_d50ab_row19_col11,#T_d50ab_row19_col12,#T_d50ab_row19_col13,#T_d50ab_row19_col14,#T_d50ab_row19_col16,#T_d50ab_row19_col17,#T_d50ab_row19_col18,#T_d50ab_row19_col19,#T_d50ab_row19_col20,#T_d50ab_row19_col21,#T_d50ab_row19_col23,#T_d50ab_row19_col24,#T_d50ab_row20_col0,#T_d50ab_row20_col1,#T_d50ab_row20_col2,#T_d50ab_row20_col3,#T_d50ab_row20_col4,#T_d50ab_row20_col5,#T_d50ab_row20_col6,#T_d50ab_row20_col7,#T_d50ab_row20_col8,#T_d50ab_row20_col9,#T_d50ab_row20_col10,#T_d50ab_row20_col11,#T_d50ab_row20_col12,#T_d50ab_row20_col13,#T_d50ab_row20_col14,#T_d50ab_row20_col15,#T_d50ab_row20_col16,#T_d50ab_row20_col17,#T_d50ab_row20_col18,#T_d50ab_row20_col19,#T_d50ab_row20_col20,#T_d50ab_row20_col21,#T_d50ab_row20_col22,#T_d50ab_row20_col23,#T_d50ab_row21_col0,#T_d50ab_row21_col1,#T_d50ab_row21_col2,#T_d50ab_row21_col3,#T_d50ab_row21_col4,#T_d50ab_row21_col5,#T_d50ab_row21_col6,#T_d50ab_row21_col7,#T_d50ab_row21_col8,#T_d50ab_row21_col9,#T_d50ab_row21_col10,#T_d50ab_row21_col11,#T_d50ab_row21_col12,#T_d50ab_row21_col13,#T_d50ab_row21_col14,#T_d50ab_row21_col16,#T_d50ab_row21_col17,#T_d50ab_row21_col18,#T_d50ab_row21_col19,#T_d50ab_row21_col20,#T_d50ab_row21_col21,#T_d50ab_row21_col22,#T_d50ab_row21_col23,#T_d50ab_row22_col0,#T_d50ab_row22_col1,#T_d50ab_row22_col2,#T_d50ab_row22_col3,#T_d50ab_row22_col4,#T_d50ab_row22_col5,#T_d50ab_row22_col6,#T_d50ab_row22_col7,#T_d50ab_row22_col8,#T_d50ab_row22_col9,#T_d50ab_row22_col10,#T_d50ab_row22_col11,#T_d50ab_row22_col12,#T_d50ab_row22_col13,#T_d50ab_row22_col14,#T_d50ab_row22_col15,#T_d50ab_row22_col16,#T_d50ab_row22_col17,#T_d50ab_row22_col18,#T_d50ab_row22_col19,#T_d50ab_row22_col20,#T_d50ab_row22_col21,#T_d50ab_row22_col22,#T_d50ab_row22_col23,#T_d50ab_row23_col0,#T_d50ab_row23_col1,#T_d50ab_row23_col2,#T_d50ab_row23_col3,#T_d50ab_row23_col4,#T_d50ab_row23_col5,#T_d50ab_row23_col6,#T_d50ab_row23_col7,#T_d50ab_row23_col8,#T_d50ab_row23_col9,#T_d50ab_row23_col10,#T_d50ab_row23_col11,#T_d50ab_row23_col12,#T_d50ab_row23_col13,#T_d50ab_row23_col14,#T_d50ab_row23_col16,#T_d50ab_row23_col17,#T_d50ab_row23_col18,#T_d50ab_row23_col19,#T_d50ab_row23_col20,#T_d50ab_row23_col21,#T_d50ab_row23_col22,#T_d50ab_row23_col23,#T_d50ab_row24_col0,#T_d50ab_row24_col1,#T_d50ab_row24_col2,#T_d50ab_row24_col3,#T_d50ab_row24_col4,#T_d50ab_row24_col5,#T_d50ab_row24_col6,#T_d50ab_row24_col7,#T_d50ab_row24_col8,#T_d50ab_row24_col9,#T_d50ab_row24_col10,#T_d50ab_row24_col11,#T_d50ab_row24_col12,#T_d50ab_row24_col13,#T_d50ab_row24_col14,#T_d50ab_row24_col15,#T_d50ab_row24_col16,#T_d50ab_row24_col17,#T_d50ab_row24_col18,#T_d50ab_row24_col19,#T_d50ab_row24_col20,#T_d50ab_row24_col21,#T_d50ab_row24_col22,#T_d50ab_row24_col23,#T_d50ab_row25_col0,#T_d50ab_row25_col1,#T_d50ab_row25_col2,#T_d50ab_row25_col3,#T_d50ab_row25_col4,#T_d50ab_row25_col5,#T_d50ab_row25_col6,#T_d50ab_row25_col7,#T_d50ab_row25_col8,#T_d50ab_row25_col9,#T_d50ab_row25_col10,#T_d50ab_row25_col11,#T_d50ab_row25_col12,#T_d50ab_row25_col13,#T_d50ab_row25_col14,#T_d50ab_row25_col15,#T_d50ab_row25_col16,#T_d50ab_row25_col17,#T_d50ab_row25_col18,#T_d50ab_row25_col19,#T_d50ab_row25_col20,#T_d50ab_row25_col21,#T_d50ab_row25_col22,#T_d50ab_row25_col23,#T_d50ab_row26_col0,#T_d50ab_row26_col1,#T_d50ab_row26_col2,#T_d50ab_row26_col3,#T_d50ab_row26_col4,#T_d50ab_row26_col5,#T_d50ab_row26_col6,#T_d50ab_row26_col7,#T_d50ab_row26_col8,#T_d50ab_row26_col9,#T_d50ab_row26_col10,#T_d50ab_row26_col11,#T_d50ab_row26_col12,#T_d50ab_row26_col13,#T_d50ab_row26_col14,#T_d50ab_row26_col15,#T_d50ab_row26_col16,#T_d50ab_row26_col17,#T_d50ab_row26_col18,#T_d50ab_row26_col19,#T_d50ab_row26_col20,#T_d50ab_row26_col21,#T_d50ab_row26_col22,#T_d50ab_row26_col23,#T_d50ab_row27_col0,#T_d50ab_row27_col1,#T_d50ab_row27_col2,#T_d50ab_row27_col3,#T_d50ab_row27_col4,#T_d50ab_row27_col5,#T_d50ab_row27_col6,#T_d50ab_row27_col7,#T_d50ab_row27_col8,#T_d50ab_row27_col9,#T_d50ab_row27_col10,#T_d50ab_row27_col11,#T_d50ab_row27_col12,#T_d50ab_row27_col13,#T_d50ab_row27_col14,#T_d50ab_row27_col15,#T_d50ab_row27_col16,#T_d50ab_row27_col17,#T_d50ab_row27_col18,#T_d50ab_row27_col19,#T_d50ab_row27_col20,#T_d50ab_row27_col21,#T_d50ab_row27_col22,#T_d50ab_row27_col23,#T_d50ab_row28_col0,#T_d50ab_row28_col1,#T_d50ab_row28_col2,#T_d50ab_row28_col3,#T_d50ab_row28_col4,#T_d50ab_row28_col5,#T_d50ab_row28_col6,#T_d50ab_row28_col7,#T_d50ab_row28_col8,#T_d50ab_row28_col9,#T_d50ab_row28_col10,#T_d50ab_row28_col11,#T_d50ab_row28_col12,#T_d50ab_row28_col13,#T_d50ab_row28_col14,#T_d50ab_row28_col16,#T_d50ab_row28_col17,#T_d50ab_row28_col18,#T_d50ab_row28_col19,#T_d50ab_row28_col20,#T_d50ab_row28_col21,#T_d50ab_row28_col23,#T_d50ab_row28_col24,#T_d50ab_row29_col0,#T_d50ab_row29_col1,#T_d50ab_row29_col2,#T_d50ab_row29_col3,#T_d50ab_row29_col4,#T_d50ab_row29_col5,#T_d50ab_row29_col6,#T_d50ab_row29_col7,#T_d50ab_row29_col8,#T_d50ab_row29_col9,#T_d50ab_row29_col10,#T_d50ab_row29_col11,#T_d50ab_row29_col12,#T_d50ab_row29_col13,#T_d50ab_row29_col14,#T_d50ab_row29_col15,#T_d50ab_row29_col16,#T_d50ab_row29_col17,#T_d50ab_row29_col18,#T_d50ab_row29_col19,#T_d50ab_row29_col20,#T_d50ab_row29_col21,#T_d50ab_row29_col22,#T_d50ab_row29_col23,#T_d50ab_row30_col0,#T_d50ab_row30_col1,#T_d50ab_row30_col2,#T_d50ab_row30_col3,#T_d50ab_row30_col4,#T_d50ab_row30_col5,#T_d50ab_row30_col6,#T_d50ab_row30_col7,#T_d50ab_row30_col8,#T_d50ab_row30_col9,#T_d50ab_row30_col10,#T_d50ab_row30_col11,#T_d50ab_row30_col12,#T_d50ab_row30_col13,#T_d50ab_row30_col14,#T_d50ab_row30_col15,#T_d50ab_row30_col16,#T_d50ab_row30_col17,#T_d50ab_row30_col18,#T_d50ab_row30_col19,#T_d50ab_row30_col20,#T_d50ab_row30_col21,#T_d50ab_row30_col22,#T_d50ab_row30_col23,#T_d50ab_row31_col0,#T_d50ab_row31_col1,#T_d50ab_row31_col2,#T_d50ab_row31_col3,#T_d50ab_row31_col4,#T_d50ab_row31_col5,#T_d50ab_row31_col6,#T_d50ab_row31_col7,#T_d50ab_row31_col8,#T_d50ab_row31_col9,#T_d50ab_row31_col10,#T_d50ab_row31_col11,#T_d50ab_row31_col12,#T_d50ab_row31_col13,#T_d50ab_row31_col14,#T_d50ab_row31_col16,#T_d50ab_row31_col17,#T_d50ab_row31_col18,#T_d50ab_row31_col19,#T_d50ab_row31_col20,#T_d50ab_row31_col21,#T_d50ab_row31_col23,#T_d50ab_row31_col24{
            color:  black;
        }#T_d50ab_row0_col9,#T_d50ab_row0_col14,#T_d50ab_row0_col15,#T_d50ab_row0_col24,#T_d50ab_row1_col14,#T_d50ab_row1_col22,#T_d50ab_row2_col9,#T_d50ab_row2_col15,#T_d50ab_row2_col24,#T_d50ab_row3_col15,#T_d50ab_row3_col22,#T_d50ab_row7_col24,#T_d50ab_row8_col24,#T_d50ab_row9_col24,#T_d50ab_row10_col24,#T_d50ab_row11_col15,#T_d50ab_row11_col22,#T_d50ab_row12_col24,#T_d50ab_row13_col24,#T_d50ab_row14_col24,#T_d50ab_row15_col15,#T_d50ab_row15_col22,#T_d50ab_row16_col24,#T_d50ab_row18_col24,#T_d50ab_row19_col15,#T_d50ab_row19_col22,#T_d50ab_row20_col24,#T_d50ab_row21_col15,#T_d50ab_row21_col24,#T_d50ab_row22_col24,#T_d50ab_row23_col15,#T_d50ab_row23_col24,#T_d50ab_row24_col24,#T_d50ab_row25_col24,#T_d50ab_row26_col24,#T_d50ab_row27_col24,#T_d50ab_row28_col15,#T_d50ab_row28_col22,#T_d50ab_row29_col24,#T_d50ab_row30_col24,#T_d50ab_row31_col15,#T_d50ab_row31_col22{
            color:  red;
        }</style><table id="T_d50ab_" ><thead>    <tr>        <th class="blank level0" ></th>        <th class="col_heading level0 col0" >名称</th>        <th class="col_heading level0 col1" >行业</th>        <th class="col_heading level0 col2" >权重</th>        <th class="col_heading level0 col3" >负债率</th>        <th class="col_heading level0 col4" >应收比</th>        <th class="col_heading level0 col5" >商誉比</th>        <th class="col_heading level0 col6" >ROE</th>        <th class="col_heading level0 col7" >利润率</th>        <th class="col_heading level0 col8" >收入</th>        <th class="col_heading level0 col9" >收入增长</th>        <th class="col_heading level0 col10" >收入波动</th>        <th class="col_heading level0 col11" >盈利</th>        <th class="col_heading level0 col12" >盈利增长</th>        <th class="col_heading level0 col13" >盈利波动</th>        <th class="col_heading level0 col14" >FCF</th>        <th class="col_heading level0 col15" >FCF增长</th>        <th class="col_heading level0 col16" >FCF波动</th>        <th class="col_heading level0 col17" >PE</th>        <th class="col_heading level0 col18" >PE0</th>        <th class="col_heading level0 col19" >PEG</th>        <th class="col_heading level0 col20" >股息率</th>        <th class="col_heading level0 col21" >市值</th>        <th class="col_heading level0 col22" >DCF</th>        <th class="col_heading level0 col23" >盈利折现</th>        <th class="col_heading level0 col24" >折价率</th>    </tr>    <tr>        <th class="index_name level0" >Symbol</th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>    </tr></thead><tbody>
                <tr>
                        <th id="T_d50ab_level0_row0" class="row_heading level0 row0" >600738.SS</th>
                        <td id="T_d50ab_row0_col0" class="data row0 col0" >丽尚国潮</td>
                        <td id="T_d50ab_row0_col1" class="data row0 col1" >商业贸易</td>
                        <td id="T_d50ab_row0_col2" class="data row0 col2" >0.86</td>
                        <td id="T_d50ab_row0_col3" class="data row0 col3" >49.64</td>
                        <td id="T_d50ab_row0_col4" class="data row0 col4" >1.56</td>
                        <td id="T_d50ab_row0_col5" class="data row0 col5" >-</td>
                        <td id="T_d50ab_row0_col6" class="data row0 col6" >20.19</td>
                        <td id="T_d50ab_row0_col7" class="data row0 col7" >40.48</td>
                        <td id="T_d50ab_row0_col8" class="data row0 col8" >1,251.55</td>
                        <td id="T_d50ab_row0_col9" class="data row0 col9" >-5.90</td>
                        <td id="T_d50ab_row0_col10" class="data row0 col10" >57.73</td>
                        <td id="T_d50ab_row0_col11" class="data row0 col11" >515.14</td>
                        <td id="T_d50ab_row0_col12" class="data row0 col12" >285.05</td>
                        <td id="T_d50ab_row0_col13" class="data row0 col13" >623.06</td>
                        <td id="T_d50ab_row0_col14" class="data row0 col14" >-1.80</td>
                        <td id="T_d50ab_row0_col15" class="data row0 col15" >-147.69</td>
                        <td id="T_d50ab_row0_col16" class="data row0 col16" >206.14</td>
                        <td id="T_d50ab_row0_col17" class="data row0 col17" >82.59</td>
                        <td id="T_d50ab_row0_col18" class="data row0 col18" >13.89</td>
                        <td id="T_d50ab_row0_col19" class="data row0 col19" >0.05</td>
                        <td id="T_d50ab_row0_col20" class="data row0 col20" >-</td>
                        <td id="T_d50ab_row0_col21" class="data row0 col21" >7,154.54</td>
                        <td id="T_d50ab_row0_col22" class="data row0 col22" >2.59</td>
                        <td id="T_d50ab_row0_col23" class="data row0 col23" >326,085.66</td>
                        <td id="T_d50ab_row0_col24" class="data row0 col24" >-276,447.44</td>
            </tr>
            <tr>
                        <th id="T_d50ab_level0_row1" class="row_heading level0 row1" >002714.SZ</th>
                        <td id="T_d50ab_row1_col0" class="data row1 col0" >牧原股份</td>
                        <td id="T_d50ab_row1_col1" class="data row1 col1" >农林牧渔</td>
                        <td id="T_d50ab_row1_col2" class="data row1 col2" >21.74</td>
                        <td id="T_d50ab_row1_col3" class="data row1 col3" >46.09</td>
                        <td id="T_d50ab_row1_col4" class="data row1 col4" >0.13</td>
                        <td id="T_d50ab_row1_col5" class="data row1 col5" >-</td>
                        <td id="T_d50ab_row1_col6" class="data row1 col6" >28.10</td>
                        <td id="T_d50ab_row1_col7" class="data row1 col7" >26.61</td>
                        <td id="T_d50ab_row1_col8" class="data row1 col8" >24,982.24</td>
                        <td id="T_d50ab_row1_col9" class="data row1 col9" >87.55</td>
                        <td id="T_d50ab_row1_col10" class="data row1 col10" >79.09</td>
                        <td id="T_d50ab_row1_col11" class="data row1 col11" >9,112.88</td>
                        <td id="T_d50ab_row1_col12" class="data row1 col12" >448.77</td>
                        <td id="T_d50ab_row1_col13" class="data row1 col13" >583.13</td>
                        <td id="T_d50ab_row1_col14" class="data row1 col14" >-8,548.90</td>
                        <td id="T_d50ab_row1_col15" class="data row1 col15" >199.27</td>
                        <td id="T_d50ab_row1_col16" class="data row1 col16" >373.67</td>
                        <td id="T_d50ab_row1_col17" class="data row1 col17" >8.29</td>
                        <td id="T_d50ab_row1_col18" class="data row1 col18" >27.97</td>
                        <td id="T_d50ab_row1_col19" class="data row1 col19" >0.06</td>
                        <td id="T_d50ab_row1_col20" class="data row1 col20" >0.76</td>
                        <td id="T_d50ab_row1_col21" class="data row1 col21" >254,882.59</td>
                        <td id="T_d50ab_row1_col22" class="data row1 col22" >-2,566,745.35</td>
                        <td id="T_d50ab_row1_col23" class="data row1 col23" >16,539,658.80</td>
                        <td id="T_d50ab_row1_col24" class="data row1 col24" >-</td>
            </tr>
            <tr>
                        <th id="T_d50ab_level0_row2" class="row_heading level0 row2" >300418.SZ</th>
                        <td id="T_d50ab_row2_col0" class="data row2 col0" >昆仑万维</td>
                        <td id="T_d50ab_row2_col1" class="data row2 col1" >传媒</td>
                        <td id="T_d50ab_row2_col2" class="data row2 col2" >1.14</td>
                        <td id="T_d50ab_row2_col3" class="data row2 col3" >26.89</td>
                        <td id="T_d50ab_row2_col4" class="data row2 col4" >13.41</td>
                        <td id="T_d50ab_row2_col5" class="data row2 col5" >9.88</td>
                        <td id="T_d50ab_row2_col6" class="data row2 col6" >27.55</td>
                        <td id="T_d50ab_row2_col7" class="data row2 col7" >68.64</td>
                        <td id="T_d50ab_row2_col8" class="data row2 col8" >3,360.24</td>
                        <td id="T_d50ab_row2_col9" class="data row2 col9" >-6.17</td>
                        <td id="T_d50ab_row2_col10" class="data row2 col10" >16.93</td>
                        <td id="T_d50ab_row2_col11" class="data row2 col11" >2,073.26</td>
                        <td id="T_d50ab_row2_col12" class="data row2 col12" >105.00</td>
                        <td id="T_d50ab_row2_col13" class="data row2 col13" >156.97</td>
                        <td id="T_d50ab_row2_col14" class="data row2 col14" >1,091.13</td>
                        <td id="T_d50ab_row2_col15" class="data row2 col15" >-5.39</td>
                        <td id="T_d50ab_row2_col16" class="data row2 col16" >42.73</td>
                        <td id="T_d50ab_row2_col17" class="data row2 col17" >4.73</td>
                        <td id="T_d50ab_row2_col18" class="data row2 col18" >10.52</td>
                        <td id="T_d50ab_row2_col19" class="data row2 col19" >0.10</td>
                        <td id="T_d50ab_row2_col20" class="data row2 col20" >-</td>
                        <td id="T_d50ab_row2_col21" class="data row2 col21" >21,813.13</td>
                        <td id="T_d50ab_row2_col22" class="data row2 col22" >11,899.27</td>
                        <td id="T_d50ab_row2_col23" class="data row2 col23" >204,878.90</td>
                        <td id="T_d50ab_row2_col24" class="data row2 col24" >-83.31</td>
            </tr>
            <tr>
                        <th id="T_d50ab_level0_row3" class="row_heading level0 row3" >002932.SZ</th>
                        <td id="T_d50ab_row3_col0" class="data row3 col0" >明德生物</td>
                        <td id="T_d50ab_row3_col1" class="data row3 col1" >医药生物</td>
                        <td id="T_d50ab_row3_col2" class="data row3 col2" >0.07</td>
                        <td id="T_d50ab_row3_col3" class="data row3 col3" >21.85</td>
                        <td id="T_d50ab_row3_col4" class="data row3 col4" >19.76</td>
                        <td id="T_d50ab_row3_col5" class="data row3 col5" >-</td>
                        <td id="T_d50ab_row3_col6" class="data row3 col6" >21.76</td>
                        <td id="T_d50ab_row3_col7" class="data row3 col7" >36.58</td>
                        <td id="T_d50ab_row3_col8" class="data row3 col8" >370.44</td>
                        <td id="T_d50ab_row3_col9" class="data row3 col9" >146.32</td>
                        <td id="T_d50ab_row3_col10" class="data row3 col10" >245.19</td>
                        <td id="T_d50ab_row3_col11" class="data row3 col11" >159.34</td>
                        <td id="T_d50ab_row3_col12" class="data row3 col12" >330.21</td>
                        <td id="T_d50ab_row3_col13" class="data row3 col13" >605.52</td>
                        <td id="T_d50ab_row3_col14" class="data row3 col14" >82.28</td>
                        <td id="T_d50ab_row3_col15" class="data row3 col15" >-1,108.82</td>
                        <td id="T_d50ab_row3_col16" class="data row3 col16" >2,198.15</td>
                        <td id="T_d50ab_row3_col17" class="data row3 col17" >13.56</td>
                        <td id="T_d50ab_row3_col18" class="data row3 col18" >40.98</td>
                        <td id="T_d50ab_row3_col19" class="data row3 col19" >0.12</td>
                        <td id="T_d50ab_row3_col20" class="data row3 col20" >-</td>
                        <td id="T_d50ab_row3_col21" class="data row3 col21" >6,529.26</td>
                        <td id="T_d50ab_row3_col22" class="data row3 col22" >-903,760.76</td>
                        <td id="T_d50ab_row3_col23" class="data row3 col23" >140,190.50</td>
                        <td id="T_d50ab_row3_col24" class="data row3 col24" >-</td>
            </tr>
            <tr>
                        <th id="T_d50ab_level0_row4" class="row_heading level0 row4" >000672.SZ</th>
                        <td id="T_d50ab_row4_col0" class="data row4 col0" >上峰水泥</td>
                        <td id="T_d50ab_row4_col1" class="data row4 col1" >建筑材料</td>
                        <td id="T_d50ab_row4_col2" class="data row4 col2" >1.18</td>
                        <td id="T_d50ab_row4_col3" class="data row4 col3" >36.62</td>
                        <td id="T_d50ab_row4_col4" class="data row4 col4" >8.81</td>
                        <td id="T_d50ab_row4_col5" class="data row4 col5" >1.93</td>
                        <td id="T_d50ab_row4_col6" class="data row4 col6" >37.68</td>
                        <td id="T_d50ab_row4_col7" class="data row4 col7" >26.99</td>
                        <td id="T_d50ab_row4_col8" class="data row4 col8" >5,934.12</td>
                        <td id="T_d50ab_row4_col9" class="data row4 col9" >14.05</td>
                        <td id="T_d50ab_row4_col10" class="data row4 col10" >26.51</td>
                        <td id="T_d50ab_row4_col11" class="data row4 col11" >1,655.36</td>
                        <td id="T_d50ab_row4_col12" class="data row4 col12" >43.73</td>
                        <td id="T_d50ab_row4_col13" class="data row4 col13" >51.12</td>
                        <td id="T_d50ab_row4_col14" class="data row4 col14" >1,596.88</td>
                        <td id="T_d50ab_row4_col15" class="data row4 col15" >34.90</td>
                        <td id="T_d50ab_row4_col16" class="data row4 col16" >81.40</td>
                        <td id="T_d50ab_row4_col17" class="data row4 col17" >7.66</td>
                        <td id="T_d50ab_row4_col18" class="data row4 col18" >9.60</td>
                        <td id="T_d50ab_row4_col19" class="data row4 col19" >0.22</td>
                        <td id="T_d50ab_row4_col20" class="data row4 col20" >1.68</td>
                        <td id="T_d50ab_row4_col21" class="data row4 col21" >15,890.00</td>
                        <td id="T_d50ab_row4_col22" class="data row4 col22" >47,108.59</td>
                        <td id="T_d50ab_row4_col23" class="data row4 col23" >58,534.99</td>
                        <td id="T_d50ab_row4_col24" class="data row4 col24" >66.27</td>
            </tr>
            <tr>
                        <th id="T_d50ab_level0_row5" class="row_heading level0 row5" >600585.SS</th>
                        <td id="T_d50ab_row5_col0" class="data row5 col0" >海螺水泥</td>
                        <td id="T_d50ab_row5_col1" class="data row5 col1" >建筑材料</td>
                        <td id="T_d50ab_row5_col2" class="data row5 col2" >19.89</td>
                        <td id="T_d50ab_row5_col3" class="data row5 col3" >16.30</td>
                        <td id="T_d50ab_row5_col4" class="data row5 col4" >7.17</td>
                        <td id="T_d50ab_row5_col5" class="data row5 col5" >0.36</td>
                        <td id="T_d50ab_row5_col6" class="data row5 col6" >22.59</td>
                        <td id="T_d50ab_row5_col7" class="data row5 col7" >21.40</td>
                        <td id="T_d50ab_row5_col8" class="data row5 col8" >134,246.61</td>
                        <td id="T_d50ab_row5_col9" class="data row5 col9" >35.01</td>
                        <td id="T_d50ab_row5_col10" class="data row5 col10" >31.14</td>
                        <td id="T_d50ab_row5_col11" class="data row5 col11" >28,597.85</td>
                        <td id="T_d50ab_row5_col12" class="data row5 col12" >35.10</td>
                        <td id="T_d50ab_row5_col13" class="data row5 col13" >46.03</td>
                        <td id="T_d50ab_row5_col14" class="data row5 col14" >25,427.11</td>
                        <td id="T_d50ab_row5_col15" class="data row5 col15" >36.04</td>
                        <td id="T_d50ab_row5_col16" class="data row5 col16" >80.90</td>
                        <td id="T_d50ab_row5_col17" class="data row5 col17" >7.10</td>
                        <td id="T_d50ab_row5_col18" class="data row5 col18" >8.49</td>
                        <td id="T_d50ab_row5_col19" class="data row5 col19" >0.24</td>
                        <td id="T_d50ab_row5_col20" class="data row5 col20" >2.98</td>
                        <td id="T_d50ab_row5_col21" class="data row5 col21" >242,666.86</td>
                        <td id="T_d50ab_row5_col22" class="data row5 col22" >768,241.81</td>
                        <td id="T_d50ab_row5_col23" class="data row5 col23" >847,141.73</td>
                        <td id="T_d50ab_row5_col24" class="data row5 col24" >68.41</td>
            </tr>
            <tr>
                        <th id="T_d50ab_level0_row6" class="row_heading level0 row6" >603360.SS</th>
                        <td id="T_d50ab_row6_col0" class="data row6 col0" >百傲化学</td>
                        <td id="T_d50ab_row6_col1" class="data row6 col1" >化工</td>
                        <td id="T_d50ab_row6_col2" class="data row6 col2" >0.07</td>
                        <td id="T_d50ab_row6_col3" class="data row6 col3" >30.87</td>
                        <td id="T_d50ab_row6_col4" class="data row6 col4" >18.07</td>
                        <td id="T_d50ab_row6_col5" class="data row6 col5" >-</td>
                        <td id="T_d50ab_row6_col6" class="data row6 col6" >21.22</td>
                        <td id="T_d50ab_row6_col7" class="data row6 col7" >29.17</td>
                        <td id="T_d50ab_row6_col8" class="data row6 col8" >639.99</td>
                        <td id="T_d50ab_row6_col9" class="data row6 col9" >26.58</td>
                        <td id="T_d50ab_row6_col10" class="data row6 col10" >39.60</td>
                        <td id="T_d50ab_row6_col11" class="data row6 col11" >193.50</td>
                        <td id="T_d50ab_row6_col12" class="data row6 col12" >42.80</td>
                        <td id="T_d50ab_row6_col13" class="data row6 col13" >69.54</td>
                        <td id="T_d50ab_row6_col14" class="data row6 col14" >95.24</td>
                        <td id="T_d50ab_row6_col15" class="data row6 col15" >73.49</td>
                        <td id="T_d50ab_row6_col16" class="data row6 col16" >178.99</td>
                        <td id="T_d50ab_row6_col17" class="data row6 col17" >19.76</td>
                        <td id="T_d50ab_row6_col18" class="data row6 col18" >18.90</td>
                        <td id="T_d50ab_row6_col19" class="data row6 col19" >0.44</td>
                        <td id="T_d50ab_row6_col20" class="data row6 col20" >-</td>
                        <td id="T_d50ab_row6_col21" class="data row6 col21" >3,656.23</td>
                        <td id="T_d50ab_row6_col22" class="data row6 col22" >5,792.14</td>
                        <td id="T_d50ab_row6_col23" class="data row6 col23" >6,715.81</td>
                        <td id="T_d50ab_row6_col24" class="data row6 col24" >36.88</td>
            </tr>
            <tr>
                        <th id="T_d50ab_level0_row7" class="row_heading level0 row7" >300771.SZ</th>
                        <td id="T_d50ab_row7_col0" class="data row7 col0" >智莱科技</td>
                        <td id="T_d50ab_row7_col1" class="data row7 col1" >计算机</td>
                        <td id="T_d50ab_row7_col2" class="data row7 col2" >0.12</td>
                        <td id="T_d50ab_row7_col3" class="data row7 col3" >12.01</td>
                        <td id="T_d50ab_row7_col4" class="data row7 col4" >8.40</td>
                        <td id="T_d50ab_row7_col5" class="data row7 col5" >-</td>
                        <td id="T_d50ab_row7_col6" class="data row7 col6" >23.16</td>
                        <td id="T_d50ab_row7_col7" class="data row7 col7" >23.88</td>
                        <td id="T_d50ab_row7_col8" class="data row7 col8" >877.36</td>
                        <td id="T_d50ab_row7_col9" class="data row7 col9" >26.16</td>
                        <td id="T_d50ab_row7_col10" class="data row7 col10" >32.91</td>
                        <td id="T_d50ab_row7_col11" class="data row7 col11" >213.02</td>
                        <td id="T_d50ab_row7_col12" class="data row7 col12" >34.01</td>
                        <td id="T_d50ab_row7_col13" class="data row7 col13" >49.62</td>
                        <td id="T_d50ab_row7_col14" class="data row7 col14" >132.76</td>
                        <td id="T_d50ab_row7_col15" class="data row7 col15" >17.60</td>
                        <td id="T_d50ab_row7_col16" class="data row7 col16" >38.43</td>
                        <td id="T_d50ab_row7_col17" class="data row7 col17" >17.25</td>
                        <td id="T_d50ab_row7_col18" class="data row7 col18" >17.37</td>
                        <td id="T_d50ab_row7_col19" class="data row7 col19" >0.51</td>
                        <td id="T_d50ab_row7_col20" class="data row7 col20" >-</td>
                        <td id="T_d50ab_row7_col21" class="data row7 col21" >3,699.20</td>
                        <td id="T_d50ab_row7_col22" class="data row7 col22" >2,653.71</td>
                        <td id="T_d50ab_row7_col23" class="data row7 col23" >6,165.97</td>
                        <td id="T_d50ab_row7_col24" class="data row7 col24" >-39.40</td>
            </tr>
            <tr>
                        <th id="T_d50ab_level0_row8" class="row_heading level0 row8" >603160.SS</th>
                        <td id="T_d50ab_row8_col0" class="data row8 col0" >汇顶科技</td>
                        <td id="T_d50ab_row8_col1" class="data row8 col1" >电子</td>
                        <td id="T_d50ab_row8_col2" class="data row8 col2" >0.88</td>
                        <td id="T_d50ab_row8_col3" class="data row8 col3" >18.72</td>
                        <td id="T_d50ab_row8_col4" class="data row8 col4" >11.10</td>
                        <td id="T_d50ab_row8_col5" class="data row8 col5" >6.76</td>
                        <td id="T_d50ab_row8_col6" class="data row8 col6" >25.04</td>
                        <td id="T_d50ab_row8_col7" class="data row8 col7" >26.16</td>
                        <td id="T_d50ab_row8_col8" class="data row8 col8" >5,140.85</td>
                        <td id="T_d50ab_row8_col9" class="data row8 col9" >26.11</td>
                        <td id="T_d50ab_row8_col10" class="data row8 col10" >41.45</td>
                        <td id="T_d50ab_row8_col11" class="data row8 col11" >1,401.49</td>
                        <td id="T_d50ab_row8_col12" class="data row8 col12" >55.80</td>
                        <td id="T_d50ab_row8_col13" class="data row8 col13" >135.49</td>
                        <td id="T_d50ab_row8_col14" class="data row8 col14" >1,063.96</td>
                        <td id="T_d50ab_row8_col15" class="data row8 col15" >18.94</td>
                        <td id="T_d50ab_row8_col16" class="data row8 col16" >140.73</td>
                        <td id="T_d50ab_row8_col17" class="data row8 col17" >37.02</td>
                        <td id="T_d50ab_row8_col18" class="data row8 col18" >42.03</td>
                        <td id="T_d50ab_row8_col19" class="data row8 col19" >0.75</td>
                        <td id="T_d50ab_row8_col20" class="data row8 col20" >-</td>
                        <td id="T_d50ab_row8_col21" class="data row8 col21" >58,898.49</td>
                        <td id="T_d50ab_row8_col22" class="data row8 col22" >21,955.92</td>
                        <td id="T_d50ab_row8_col23" class="data row8 col23" >62,476.61</td>
                        <td id="T_d50ab_row8_col24" class="data row8 col24" >-168.26</td>
            </tr>
            <tr>
                        <th id="T_d50ab_level0_row9" class="row_heading level0 row9" >002677.SZ</th>
                        <td id="T_d50ab_row9_col0" class="data row9 col0" >浙江美大</td>
                        <td id="T_d50ab_row9_col1" class="data row9 col1" >家用电器</td>
                        <td id="T_d50ab_row9_col2" class="data row9 col2" >0.46</td>
                        <td id="T_d50ab_row9_col3" class="data row9 col3" >21.80</td>
                        <td id="T_d50ab_row9_col4" class="data row9 col4" >1.94</td>
                        <td id="T_d50ab_row9_col5" class="data row9 col5" >-</td>
                        <td id="T_d50ab_row9_col6" class="data row9 col6" >28.29</td>
                        <td id="T_d50ab_row9_col7" class="data row9 col7" >28.67</td>
                        <td id="T_d50ab_row9_col8" class="data row9 col8" >1,470.64</td>
                        <td id="T_d50ab_row9_col9" class="data row9 col9" >20.62</td>
                        <td id="T_d50ab_row9_col10" class="data row9 col10" >15.69</td>
                        <td id="T_d50ab_row9_col11" class="data row9 col11" >421.57</td>
                        <td id="T_d50ab_row9_col12" class="data row9 col12" >21.24</td>
                        <td id="T_d50ab_row9_col13" class="data row9 col13" >2.82</td>
                        <td id="T_d50ab_row9_col14" class="data row9 col14" >330.92</td>
                        <td id="T_d50ab_row9_col15" class="data row9 col15" >44.23</td>
                        <td id="T_d50ab_row9_col16" class="data row9 col16" >89.38</td>
                        <td id="T_d50ab_row9_col17" class="data row9 col17" >19.73</td>
                        <td id="T_d50ab_row9_col18" class="data row9 col18" >29.71</td>
                        <td id="T_d50ab_row9_col19" class="data row9 col19" >1.40</td>
                        <td id="T_d50ab_row9_col20" class="data row9 col20" >2.90</td>
                        <td id="T_d50ab_row9_col21" class="data row9 col21" >12,526.95</td>
                        <td id="T_d50ab_row9_col22" class="data row9 col22" >11,817.15</td>
                        <td id="T_d50ab_row9_col23" class="data row9 col23" >9,183.53</td>
                        <td id="T_d50ab_row9_col24" class="data row9 col24" >-6.01</td>
            </tr>
            <tr>
                        <th id="T_d50ab_level0_row10" class="row_heading level0 row10" >300033.SZ</th>
                        <td id="T_d50ab_row10_col0" class="data row10 col0" >同花顺</td>
                        <td id="T_d50ab_row10_col1" class="data row10 col1" >计算机</td>
                        <td id="T_d50ab_row10_col2" class="data row10 col2" >1.48</td>
                        <td id="T_d50ab_row10_col3" class="data row10 col3" >26.99</td>
                        <td id="T_d50ab_row10_col4" class="data row10 col4" >2.59</td>
                        <td id="T_d50ab_row10_col5" class="data row10 col5" >0.07</td>
                        <td id="T_d50ab_row10_col6" class="data row10 col6" >24.34</td>
                        <td id="T_d50ab_row10_col7" class="data row10 col7" >52.33</td>
                        <td id="T_d50ab_row10_col8" class="data row10 col8" >1,845.59</td>
                        <td id="T_d50ab_row10_col9" class="data row10 col9" >29.08</td>
                        <td id="T_d50ab_row10_col10" class="data row10 col10" >32.56</td>
                        <td id="T_d50ab_row10_col11" class="data row10 col11" >995.31</td>
                        <td id="T_d50ab_row10_col12" class="data row10 col12" >40.34</td>
                        <td id="T_d50ab_row10_col13" class="data row10 col13" >52.36</td>
                        <td id="T_d50ab_row10_col14" class="data row10 col14" >940.85</td>
                        <td id="T_d50ab_row10_col15" class="data row10 col15" >63.18</td>
                        <td id="T_d50ab_row10_col16" class="data row10 col16" >90.96</td>
                        <td id="T_d50ab_row10_col17" class="data row10 col17" >34.67</td>
                        <td id="T_d50ab_row10_col18" class="data row10 col18" >61.58</td>
                        <td id="T_d50ab_row10_col19" class="data row10 col19" >1.53</td>
                        <td id="T_d50ab_row10_col20" class="data row10 col20" >1.17</td>
                        <td id="T_d50ab_row10_col21" class="data row10 col21" >61,286.40</td>
                        <td id="T_d50ab_row10_col22" class="data row10 col22" >47,922.49</td>
                        <td id="T_d50ab_row10_col23" class="data row10 col23" >32,867.63</td>
                        <td id="T_d50ab_row10_col24" class="data row10 col24" >-27.89</td>
            </tr>
            <tr>
                        <th id="T_d50ab_level0_row11" class="row_heading level0 row11" >600989.SS</th>
                        <td id="T_d50ab_row11_col0" class="data row11 col0" >宝丰能源</td>
                        <td id="T_d50ab_row11_col1" class="data row11 col1" >化工</td>
                        <td id="T_d50ab_row11_col2" class="data row11 col2" >1.26</td>
                        <td id="T_d50ab_row11_col3" class="data row11 col3" >32.03</td>
                        <td id="T_d50ab_row11_col4" class="data row11 col4" >3.64</td>
                        <td id="T_d50ab_row11_col5" class="data row11 col5" >4.34</td>
                        <td id="T_d50ab_row11_col6" class="data row11 col6" >21.66</td>
                        <td id="T_d50ab_row11_col7" class="data row11 col7" >27.28</td>
                        <td id="T_d50ab_row11_col8" class="data row11 col8" >13,712.24</td>
                        <td id="T_d50ab_row11_col9" class="data row11 col9" >9.15</td>
                        <td id="T_d50ab_row11_col10" class="data row11 col10" >7.22</td>
                        <td id="T_d50ab_row11_col11" class="data row11 col11" >3,760.90</td>
                        <td id="T_d50ab_row11_col12" class="data row11 col12" >16.96</td>
                        <td id="T_d50ab_row11_col13" class="data row11 col13" >12.43</td>
                        <td id="T_d50ab_row11_col14" class="data row11 col14" >1,382.19</td>
                        <td id="T_d50ab_row11_col15" class="data row11 col15" >-184.25</td>
                        <td id="T_d50ab_row11_col16" class="data row11 col16" >173.78</td>
                        <td id="T_d50ab_row11_col17" class="data row11 col17" >18.16</td>
                        <td id="T_d50ab_row11_col18" class="data row11 col18" >26.95</td>
                        <td id="T_d50ab_row11_col19" class="data row11 col19" >1.59</td>
                        <td id="T_d50ab_row11_col20" class="data row11 col20" >-</td>
                        <td id="T_d50ab_row11_col21" class="data row11 col21" >101,347.03</td>
                        <td id="T_d50ab_row11_col22" class="data row11 col22" >-9,167.11</td>
                        <td id="T_d50ab_row11_col23" class="data row11 col23" >74,030.61</td>
                        <td id="T_d50ab_row11_col24" class="data row11 col24" >-</td>
            </tr>
            <tr>
                        <th id="T_d50ab_level0_row12" class="row_heading level0 row12" >300832.SZ</th>
                        <td id="T_d50ab_row12_col0" class="data row12 col0" >新产业</td>
                        <td id="T_d50ab_row12_col1" class="data row12 col1" >医药生物</td>
                        <td id="T_d50ab_row12_col2" class="data row12 col2" >0.47</td>
                        <td id="T_d50ab_row12_col3" class="data row12 col3" >9.45</td>
                        <td id="T_d50ab_row12_col4" class="data row12 col4" >10.07</td>
                        <td id="T_d50ab_row12_col5" class="data row12 col5" >-</td>
                        <td id="T_d50ab_row12_col6" class="data row12 col6" >25.97</td>
                        <td id="T_d50ab_row12_col7" class="data row12 col7" >46.52</td>
                        <td id="T_d50ab_row12_col8" class="data row12 col8" >1,600.18</td>
                        <td id="T_d50ab_row12_col9" class="data row12 col9" >24.46</td>
                        <td id="T_d50ab_row12_col10" class="data row12 col10" >5.26</td>
                        <td id="T_d50ab_row12_col11" class="data row12 col11" >735.99</td>
                        <td id="T_d50ab_row12_col12" class="data row12 col12" >20.61</td>
                        <td id="T_d50ab_row12_col13" class="data row12 col13" >8.85</td>
                        <td id="T_d50ab_row12_col14" class="data row12 col14" >497.94</td>
                        <td id="T_d50ab_row12_col15" class="data row12 col15" >27.94</td>
                        <td id="T_d50ab_row12_col16" class="data row12 col16" >13.10</td>
                        <td id="T_d50ab_row12_col17" class="data row12 col17" >25.82</td>
                        <td id="T_d50ab_row12_col18" class="data row12 col18" >35.56</td>
                        <td id="T_d50ab_row12_col19" class="data row12 col19" >1.73</td>
                        <td id="T_d50ab_row12_col20" class="data row12 col20" >-</td>
                        <td id="T_d50ab_row12_col21" class="data row12 col21" >26,171.86</td>
                        <td id="T_d50ab_row12_col22" class="data row12 col22" >12,632.32</td>
                        <td id="T_d50ab_row12_col23" class="data row12 col23" >15,799.22</td>
                        <td id="T_d50ab_row12_col24" class="data row12 col24" >-107.18</td>
            </tr>
            <tr>
                        <th id="T_d50ab_level0_row13" class="row_heading level0 row13" >002833.SZ</th>
                        <td id="T_d50ab_row13_col0" class="data row13 col0" >弘亚数控</td>
                        <td id="T_d50ab_row13_col1" class="data row13 col1" >机械设备</td>
                        <td id="T_d50ab_row13_col2" class="data row13 col2" >0.37</td>
                        <td id="T_d50ab_row13_col3" class="data row13 col3" >26.31</td>
                        <td id="T_d50ab_row13_col4" class="data row13 col4" >7.33</td>
                        <td id="T_d50ab_row13_col5" class="data row13 col5" >5.20</td>
                        <td id="T_d50ab_row13_col6" class="data row13 col6" >22.78</td>
                        <td id="T_d50ab_row13_col7" class="data row13 col7" >23.79</td>
                        <td id="T_d50ab_row13_col8" class="data row13 col8" >1,254.04</td>
                        <td id="T_d50ab_row13_col9" class="data row13 col9" >28.09</td>
                        <td id="T_d50ab_row13_col10" class="data row13 col10" >17.93</td>
                        <td id="T_d50ab_row13_col11" class="data row13 col11" >289.93</td>
                        <td id="T_d50ab_row13_col12" class="data row13 col12" >14.35</td>
                        <td id="T_d50ab_row13_col13" class="data row13 col13" >1.54</td>
                        <td id="T_d50ab_row13_col14" class="data row13 col14" >232.37</td>
                        <td id="T_d50ab_row13_col15" class="data row13 col15" >6.66</td>
                        <td id="T_d50ab_row13_col16" class="data row13 col16" >10.44</td>
                        <td id="T_d50ab_row13_col17" class="data row13 col17" >21.30</td>
                        <td id="T_d50ab_row13_col18" class="data row13 col18" >25.76</td>
                        <td id="T_d50ab_row13_col19" class="data row13 col19" >1.80</td>
                        <td id="T_d50ab_row13_col20" class="data row13 col20" >-</td>
                        <td id="T_d50ab_row13_col21" class="data row13 col21" >7,467.28</td>
                        <td id="T_d50ab_row13_col22" class="data row13 col22" >3,532.41</td>
                        <td id="T_d50ab_row13_col23" class="data row13 col23" >5,355.28</td>
                        <td id="T_d50ab_row13_col24" class="data row13 col24" >-111.39</td>
            </tr>
            <tr>
                        <th id="T_d50ab_level0_row14" class="row_heading level0 row14" >600570.SS</th>
                        <td id="T_d50ab_row14_col0" class="data row14 col0" >恒生电子</td>
                        <td id="T_d50ab_row14_col1" class="data row14 col1" >计算机</td>
                        <td id="T_d50ab_row14_col2" class="data row14 col2" >5.13</td>
                        <td id="T_d50ab_row14_col3" class="data row14 col3" >49.48</td>
                        <td id="T_d50ab_row14_col4" class="data row14 col4" >14.02</td>
                        <td id="T_d50ab_row14_col5" class="data row14 col5" >6.85</td>
                        <td id="T_d50ab_row14_col6" class="data row14 col6" >24.06</td>
                        <td id="T_d50ab_row14_col7" class="data row14 col7" >26.42</td>
                        <td id="T_d50ab_row14_col8" class="data row14 col8" >3,493.37</td>
                        <td id="T_d50ab_row14_col9" class="data row14 col9" >16.27</td>
                        <td id="T_d50ab_row14_col10" class="data row14 col10" >7.59</td>
                        <td id="T_d50ab_row14_col11" class="data row14 col11" >963.54</td>
                        <td id="T_d50ab_row14_col12" class="data row14 col12" >49.90</td>
                        <td id="T_d50ab_row14_col13" class="data row14 col13" >64.01</td>
                        <td id="T_d50ab_row14_col14" class="data row14 col14" >779.22</td>
                        <td id="T_d50ab_row14_col15" class="data row14 col15" >10.32</td>
                        <td id="T_d50ab_row14_col16" class="data row14 col16" >20.60</td>
                        <td id="T_d50ab_row14_col17" class="data row14 col17" >58.78</td>
                        <td id="T_d50ab_row14_col18" class="data row14 col18" >95.23</td>
                        <td id="T_d50ab_row14_col19" class="data row14 col19" >1.91</td>
                        <td id="T_d50ab_row14_col20" class="data row14 col20" >0.40</td>
                        <td id="T_d50ab_row14_col21" class="data row14 col21" >91,754.63</td>
                        <td id="T_d50ab_row14_col22" class="data row14 col22" >13,015.01</td>
                        <td id="T_d50ab_row14_col23" class="data row14 col23" >38,434.90</td>
                        <td id="T_d50ab_row14_col24" class="data row14 col24" >-604.99</td>
            </tr>
            <tr>
                        <th id="T_d50ab_level0_row15" class="row_heading level0 row15" >002507.SZ</th>
                        <td id="T_d50ab_row15_col0" class="data row15 col0" >涪陵榨菜</td>
                        <td id="T_d50ab_row15_col1" class="data row15 col1" >食品饮料</td>
                        <td id="T_d50ab_row15_col2" class="data row15 col2" >0.57</td>
                        <td id="T_d50ab_row15_col3" class="data row15 col3" >14.06</td>
                        <td id="T_d50ab_row15_col4" class="data row15 col4" >0.49</td>
                        <td id="T_d50ab_row15_col5" class="data row15 col5" >1.14</td>
                        <td id="T_d50ab_row15_col6" class="data row15 col6" >23.03</td>
                        <td id="T_d50ab_row15_col7" class="data row15 col7" >31.60</td>
                        <td id="T_d50ab_row15_col8" class="data row15 col8" >1,924.23</td>
                        <td id="T_d50ab_row15_col9" class="data row15 col9" >14.70</td>
                        <td id="T_d50ab_row15_col10" class="data row15 col10" >11.00</td>
                        <td id="T_d50ab_row15_col11" class="data row15 col11" >614.53</td>
                        <td id="T_d50ab_row15_col12" class="data row15 col12" >26.55</td>
                        <td id="T_d50ab_row15_col13" class="data row15 col13" >34.20</td>
                        <td id="T_d50ab_row15_col14" class="data row15 col14" >335.11</td>
                        <td id="T_d50ab_row15_col15" class="data row15 col15" >-290.57</td>
                        <td id="T_d50ab_row15_col16" class="data row15 col16" >344.89</td>
                        <td id="T_d50ab_row15_col17" class="data row15 col17" >38.74</td>
                        <td id="T_d50ab_row15_col18" class="data row15 col18" >51.25</td>
                        <td id="T_d50ab_row15_col19" class="data row15 col19" >1.93</td>
                        <td id="T_d50ab_row15_col20" class="data row15 col20" >0.72</td>
                        <td id="T_d50ab_row15_col21" class="data row15 col21" >31,495.35</td>
                        <td id="T_d50ab_row15_col22" class="data row15 col22" >-24,512.57</td>
                        <td id="T_d50ab_row15_col23" class="data row15 col23" >15,114.99</td>
                        <td id="T_d50ab_row15_col24" class="data row15 col24" >-</td>
            </tr>
            <tr>
                        <th id="T_d50ab_level0_row16" class="row_heading level0 row16" >300628.SZ</th>
                        <td id="T_d50ab_row16_col0" class="data row16 col0" >亿联网络</td>
                        <td id="T_d50ab_row16_col1" class="data row16 col1" >通信</td>
                        <td id="T_d50ab_row16_col2" class="data row16 col2" >3.62</td>
                        <td id="T_d50ab_row16_col3" class="data row16 col3" >9.97</td>
                        <td id="T_d50ab_row16_col4" class="data row16 col4" >18.77</td>
                        <td id="T_d50ab_row16_col5" class="data row16 col5" >-</td>
                        <td id="T_d50ab_row16_col6" class="data row16 col6" >24.39</td>
                        <td id="T_d50ab_row16_col7" class="data row16 col7" >46.38</td>
                        <td id="T_d50ab_row16_col8" class="data row16 col8" >2,111.69</td>
                        <td id="T_d50ab_row16_col9" class="data row16 col9" >26.19</td>
                        <td id="T_d50ab_row16_col10" class="data row16 col10" >13.83</td>
                        <td id="T_d50ab_row16_col11" class="data row16 col11" >989.07</td>
                        <td id="T_d50ab_row16_col12" class="data row16 col12" >30.91</td>
                        <td id="T_d50ab_row16_col13" class="data row16 col13" >23.73</td>
                        <td id="T_d50ab_row16_col14" class="data row16 col14" >731.11</td>
                        <td id="T_d50ab_row16_col15" class="data row16 col15" >28.68</td>
                        <td id="T_d50ab_row16_col16" class="data row16 col16" >12.49</td>
                        <td id="T_d50ab_row16_col17" class="data row16 col17" >51.88</td>
                        <td id="T_d50ab_row16_col18" class="data row16 col18" >67.87</td>
                        <td id="T_d50ab_row16_col19" class="data row16 col19" >2.20</td>
                        <td id="T_d50ab_row16_col20" class="data row16 col20" >-</td>
                        <td id="T_d50ab_row16_col21" class="data row16 col21" >67,129.93</td>
                        <td id="T_d50ab_row16_col22" class="data row16 col22" >18,854.21</td>
                        <td id="T_d50ab_row16_col23" class="data row16 col23" >26,782.56</td>
                        <td id="T_d50ab_row16_col24" class="data row16 col24" >-256.05</td>
            </tr>
            <tr>
                        <th id="T_d50ab_level0_row17" class="row_heading level0 row17" >603444.SS</th>
                        <td id="T_d50ab_row17_col0" class="data row17 col0" >吉比特</td>
                        <td id="T_d50ab_row17_col1" class="data row17 col1" >传媒</td>
                        <td id="T_d50ab_row17_col2" class="data row17 col2" >2.99</td>
                        <td id="T_d50ab_row17_col3" class="data row17 col3" >21.16</td>
                        <td id="T_d50ab_row17_col4" class="data row17 col4" >10.85</td>
                        <td id="T_d50ab_row17_col5" class="data row17 col5" >0.10</td>
                        <td id="T_d50ab_row17_col6" class="data row17 col6" >26.31</td>
                        <td id="T_d50ab_row17_col7" class="data row17 col7" >40.37</td>
                        <td id="T_d50ab_row17_col8" class="data row17 col8" >2,001.84</td>
                        <td id="T_d50ab_row17_col9" class="data row17 col9" >24.14</td>
                        <td id="T_d50ab_row17_col10" class="data row17 col10" >8.35</td>
                        <td id="T_d50ab_row17_col11" class="data row17 col11" >797.07</td>
                        <td id="T_d50ab_row17_col12" class="data row17 col12" >19.94</td>
                        <td id="T_d50ab_row17_col13" class="data row17 col13" >8.77</td>
                        <td id="T_d50ab_row17_col14" class="data row17 col14" >902.43</td>
                        <td id="T_d50ab_row17_col15" class="data row17 col15" >66.50</td>
                        <td id="T_d50ab_row17_col16" class="data row17 col16" >112.96</td>
                        <td id="T_d50ab_row17_col17" class="data row17 col17" >38.19</td>
                        <td id="T_d50ab_row17_col18" class="data row17 col18" >52.21</td>
                        <td id="T_d50ab_row17_col19" class="data row17 col19" >2.62</td>
                        <td id="T_d50ab_row17_col20" class="data row17 col20" >-</td>
                        <td id="T_d50ab_row17_col21" class="data row17 col21" >41,617.51</td>
                        <td id="T_d50ab_row17_col22" class="data row17 col22" >48,725.49</td>
                        <td id="T_d50ab_row17_col23" class="data row17 col23" >16,843.02</td>
                        <td id="T_d50ab_row17_col24" class="data row17 col24" >14.59</td>
            </tr>
            <tr>
                        <th id="T_d50ab_level0_row18" class="row_heading level0 row18" >603195.SS</th>
                        <td id="T_d50ab_row18_col0" class="data row18 col0" >公牛集团</td>
                        <td id="T_d50ab_row18_col1" class="data row18 col1" >轻工制造</td>
                        <td id="T_d50ab_row18_col2" class="data row18 col2" >2.96</td>
                        <td id="T_d50ab_row18_col3" class="data row18 col3" >26.53</td>
                        <td id="T_d50ab_row18_col4" class="data row18 col4" >3.09</td>
                        <td id="T_d50ab_row18_col5" class="data row18 col5" >-</td>
                        <td id="T_d50ab_row18_col6" class="data row18 col6" >50.07</td>
                        <td id="T_d50ab_row18_col7" class="data row18 col7" >20.55</td>
                        <td id="T_d50ab_row18_col8" class="data row18 col8" >9,099.16</td>
                        <td id="T_d50ab_row18_col9" class="data row18 col9" >12.02</td>
                        <td id="T_d50ab_row18_col10" class="data row18 col10" >12.60</td>
                        <td id="T_d50ab_row18_col11" class="data row18 col11" >1,894.86</td>
                        <td id="T_d50ab_row18_col12" class="data row18 col12" >22.75</td>
                        <td id="T_d50ab_row18_col13" class="data row18 col13" >19.65</td>
                        <td id="T_d50ab_row18_col14" class="data row18 col14" >1,760.45</td>
                        <td id="T_d50ab_row18_col15" class="data row18 col15" >61.00</td>
                        <td id="T_d50ab_row18_col16" class="data row18 col16" >30.19</td>
                        <td id="T_d50ab_row18_col17" class="data row18 col17" >49.70</td>
                        <td id="T_d50ab_row18_col18" class="data row18 col18" >61.28</td>
                        <td id="T_d50ab_row18_col19" class="data row18 col19" >2.69</td>
                        <td id="T_d50ab_row18_col20" class="data row18 col20" >-</td>
                        <td id="T_d50ab_row18_col21" class="data row18 col21" >116,121.37</td>
                        <td id="T_d50ab_row18_col22" class="data row18 col22" >86,267.80</td>
                        <td id="T_d50ab_row18_col23" class="data row18 col23" >42,752.23</td>
                        <td id="T_d50ab_row18_col24" class="data row18 col24" >-34.61</td>
            </tr>
            <tr>
                        <th id="T_d50ab_level0_row19" class="row_heading level0 row19" >300782.SZ</th>
                        <td id="T_d50ab_row19_col0" class="data row19 col0" >卓胜微</td>
                        <td id="T_d50ab_row19_col1" class="data row19 col1" >电子</td>
                        <td id="T_d50ab_row19_col2" class="data row19 col2" >2.75</td>
                        <td id="T_d50ab_row19_col3" class="data row19 col3" >14.18</td>
                        <td id="T_d50ab_row19_col4" class="data row19 col4" >13.48</td>
                        <td id="T_d50ab_row19_col5" class="data row19 col5" >-</td>
                        <td id="T_d50ab_row19_col6" class="data row19 col6" >39.60</td>
                        <td id="T_d50ab_row19_col7" class="data row19 col7" >32.25</td>
                        <td id="T_d50ab_row19_col8" class="data row19 col8" >1,364.09</td>
                        <td id="T_d50ab_row19_col9" class="data row19 col9" >83.09</td>
                        <td id="T_d50ab_row19_col10" class="data row19 col10" >87.66</td>
                        <td id="T_d50ab_row19_col11" class="data row19 col11" >475.55</td>
                        <td id="T_d50ab_row19_col12" class="data row19 col12" >105.87</td>
                        <td id="T_d50ab_row19_col13" class="data row19 col13" >105.71</td>
                        <td id="T_d50ab_row19_col14" class="data row19 col14" >257.43</td>
                        <td id="T_d50ab_row19_col15" class="data row19 col15" >-780.68</td>
                        <td id="T_d50ab_row19_col16" class="data row19 col16" >1,228.39</td>
                        <td id="T_d50ab_row19_col17" class="data row19 col17" >95.49</td>
                        <td id="T_d50ab_row19_col18" class="data row19 col18" >290.75</td>
                        <td id="T_d50ab_row19_col19" class="data row19 col19" >2.75</td>
                        <td id="T_d50ab_row19_col20" class="data row19 col20" >-</td>
                        <td id="T_d50ab_row19_col21" class="data row19 col21" >138,264.36</td>
                        <td id="T_d50ab_row19_col22" class="data row19 col22" >-865,911.79</td>
                        <td id="T_d50ab_row19_col23" class="data row19 col23" >47,572.66</td>
                        <td id="T_d50ab_row19_col24" class="data row19 col24" >-</td>
            </tr>
            <tr>
                        <th id="T_d50ab_level0_row20" class="row_heading level0 row20" >300529.SZ</th>
                        <td id="T_d50ab_row20_col0" class="data row20 col0" >健帆生物</td>
                        <td id="T_d50ab_row20_col1" class="data row20 col1" >医药生物</td>
                        <td id="T_d50ab_row20_col2" class="data row20 col2" >0.95</td>
                        <td id="T_d50ab_row20_col3" class="data row20 col3" >11.91</td>
                        <td id="T_d50ab_row20_col4" class="data row20 col4" >11.56</td>
                        <td id="T_d50ab_row20_col5" class="data row20 col5" >1.57</td>
                        <td id="T_d50ab_row20_col6" class="data row20 col6" >25.48</td>
                        <td id="T_d50ab_row20_col7" class="data row20 col7" >40.97</td>
                        <td id="T_d50ab_row20_col8" class="data row20 col8" >1,279.40</td>
                        <td id="T_d50ab_row20_col9" class="data row20 col9" >39.53</td>
                        <td id="T_d50ab_row20_col10" class="data row20 col10" >2.86</td>
                        <td id="T_d50ab_row20_col11" class="data row20 col11" >533.11</td>
                        <td id="T_d50ab_row20_col12" class="data row20 col12" >45.56</td>
                        <td id="T_d50ab_row20_col13" class="data row20 col13" >6.74</td>
                        <td id="T_d50ab_row20_col14" class="data row20 col14" >325.03</td>
                        <td id="T_d50ab_row20_col15" class="data row20 col15" >68.14</td>
                        <td id="T_d50ab_row20_col16" class="data row20 col16" >3.67</td>
                        <td id="T_d50ab_row20_col17" class="data row20 col17" >75.31</td>
                        <td id="T_d50ab_row20_col18" class="data row20 col18" >135.26</td>
                        <td id="T_d50ab_row20_col19" class="data row20 col19" >2.97</td>
                        <td id="T_d50ab_row20_col20" class="data row20 col20" >-</td>
                        <td id="T_d50ab_row20_col21" class="data row20 col21" >72,107.53</td>
                        <td id="T_d50ab_row20_col22" class="data row20 col22" >18,052.29</td>
                        <td id="T_d50ab_row20_col23" class="data row20 col23" >19,544.96</td>
                        <td id="T_d50ab_row20_col24" class="data row20 col24" >-299.44</td>
            </tr>
            <tr>
                        <th id="T_d50ab_level0_row21" class="row_heading level0 row21" >002901.SZ</th>
                        <td id="T_d50ab_row21_col0" class="data row21 col0" >大博医疗</td>
                        <td id="T_d50ab_row21_col1" class="data row21 col1" >医药生物</td>
                        <td id="T_d50ab_row21_col2" class="data row21 col2" >0.08</td>
                        <td id="T_d50ab_row21_col3" class="data row21 col3" >21.68</td>
                        <td id="T_d50ab_row21_col4" class="data row21 col4" >19.30</td>
                        <td id="T_d50ab_row21_col5" class="data row21 col5" >1.00</td>
                        <td id="T_d50ab_row21_col6" class="data row21 col6" >28.78</td>
                        <td id="T_d50ab_row21_col7" class="data row21 col7" >45.57</td>
                        <td id="T_d50ab_row21_col8" class="data row21 col8" >771.62</td>
                        <td id="T_d50ab_row21_col9" class="data row21 col9" >40.40</td>
                        <td id="T_d50ab_row21_col10" class="data row21 col10" >19.39</td>
                        <td id="T_d50ab_row21_col11" class="data row21 col11" >337.96</td>
                        <td id="T_d50ab_row21_col12" class="data row21 col12" >28.58</td>
                        <td id="T_d50ab_row21_col13" class="data row21 col13" >5.35</td>
                        <td id="T_d50ab_row21_col14" class="data row21 col14" >199.31</td>
                        <td id="T_d50ab_row21_col15" class="data row21 col15" >-2.48</td>
                        <td id="T_d50ab_row21_col16" class="data row21 col16" >56.39</td>
                        <td id="T_d50ab_row21_col17" class="data row21 col17" >52.44</td>
                        <td id="T_d50ab_row21_col18" class="data row21 col18" >86.03</td>
                        <td id="T_d50ab_row21_col19" class="data row21 col19" >3.01</td>
                        <td id="T_d50ab_row21_col20" class="data row21 col20" >-</td>
                        <td id="T_d50ab_row21_col21" class="data row21 col21" >29,075.70</td>
                        <td id="T_d50ab_row21_col22" class="data row21 col22" >2,362.88</td>
                        <td id="T_d50ab_row21_col23" class="data row21 col23" >8,697.39</td>
                        <td id="T_d50ab_row21_col24" class="data row21 col24" >-1,130.52</td>
            </tr>
            <tr>
                        <th id="T_d50ab_level0_row22" class="row_heading level0 row22" >600779.SS</th>
                        <td id="T_d50ab_row22_col0" class="data row22 col0" >水井坊</td>
                        <td id="T_d50ab_row22_col1" class="data row22 col1" >食品饮料</td>
                        <td id="T_d50ab_row22_col2" class="data row22 col2" >1.29</td>
                        <td id="T_d50ab_row22_col3" class="data row22 col3" >51.09</td>
                        <td id="T_d50ab_row22_col4" class="data row22 col4" >0.40</td>
                        <td id="T_d50ab_row22_col5" class="data row22 col5" >-</td>
                        <td id="T_d50ab_row22_col6" class="data row22 col6" >31.45</td>
                        <td id="T_d50ab_row22_col7" class="data row22 col7" >21.15</td>
                        <td id="T_d50ab_row22_col8" class="data row22 col8" >2,852.96</td>
                        <td id="T_d50ab_row22_col9" class="data row22 col9" >16.03</td>
                        <td id="T_d50ab_row22_col10" class="data row22 col10" >27.60</td>
                        <td id="T_d50ab_row22_col11" class="data row22 col11" >618.14</td>
                        <td id="T_d50ab_row22_col12" class="data row22 col12" >34.61</td>
                        <td id="T_d50ab_row22_col13" class="data row22 col13" >42.67</td>
                        <td id="T_d50ab_row22_col14" class="data row22 col14" >526.01</td>
                        <td id="T_d50ab_row22_col15" class="data row22 col15" >23.72</td>
                        <td id="T_d50ab_row22_col16" class="data row22 col16" >83.94</td>
                        <td id="T_d50ab_row22_col17" class="data row22 col17" >72.87</td>
                        <td id="T_d50ab_row22_col18" class="data row22 col18" >113.15</td>
                        <td id="T_d50ab_row22_col19" class="data row22 col19" >3.27</td>
                        <td id="T_d50ab_row22_col20" class="data row22 col20" >-</td>
                        <td id="T_d50ab_row22_col21" class="data row22 col21" >69,939.15</td>
                        <td id="T_d50ab_row22_col22" class="data row22 col22" >12,134.81</td>
                        <td id="T_d50ab_row22_col23" class="data row22 col23" >18,121.83</td>
                        <td id="T_d50ab_row22_col24" class="data row22 col24" >-476.35</td>
            </tr>
            <tr>
                        <th id="T_d50ab_level0_row23" class="row_heading level0 row23" >603983.SS</th>
                        <td id="T_d50ab_row23_col0" class="data row23 col0" >丸美股份</td>
                        <td id="T_d50ab_row23_col1" class="data row23 col1" >化工</td>
                        <td id="T_d50ab_row23_col2" class="data row23 col2" >0.13</td>
                        <td id="T_d50ab_row23_col3" class="data row23 col3" >20.93</td>
                        <td id="T_d50ab_row23_col4" class="data row23 col4" >0.50</td>
                        <td id="T_d50ab_row23_col5" class="data row23 col5" >-</td>
                        <td id="T_d50ab_row23_col6" class="data row23 col6" >24.39</td>
                        <td id="T_d50ab_row23_col7" class="data row23 col7" >26.16</td>
                        <td id="T_d50ab_row23_col8" class="data row23 col8" >1,618.48</td>
                        <td id="T_d50ab_row23_col9" class="data row23 col9" >9.24</td>
                        <td id="T_d50ab_row23_col10" class="data row23 col10" >10.74</td>
                        <td id="T_d50ab_row23_col11" class="data row23 col11" >426.62</td>
                        <td id="T_d50ab_row23_col12" class="data row23 col12" >15.77</td>
                        <td id="T_d50ab_row23_col13" class="data row23 col13" >22.62</td>
                        <td id="T_d50ab_row23_col14" class="data row23 col14" >231.93</td>
                        <td id="T_d50ab_row23_col15" class="data row23 col15" >-49.63</td>
                        <td id="T_d50ab_row23_col16" class="data row23 col16" >119.58</td>
                        <td id="T_d50ab_row23_col17" class="data row23 col17" >48.91</td>
                        <td id="T_d50ab_row23_col18" class="data row23 col18" >53.43</td>
                        <td id="T_d50ab_row23_col19" class="data row23 col19" >3.39</td>
                        <td id="T_d50ab_row23_col20" class="data row23 col20" >-</td>
                        <td id="T_d50ab_row23_col21" class="data row23 col21" >22,795.25</td>
                        <td id="T_d50ab_row23_col22" class="data row23 col22" >490.85</td>
                        <td id="T_d50ab_row23_col23" class="data row23 col23" >8,159.86</td>
                        <td id="T_d50ab_row23_col24" class="data row23 col24" >-4,544.03</td>
            </tr>
            <tr>
                        <th id="T_d50ab_level0_row24" class="row_heading level0 row24" >300760.SZ</th>
                        <td id="T_d50ab_row24_col0" class="data row24 col0" >迈瑞医疗</td>
                        <td id="T_d50ab_row24_col1" class="data row24 col1" >医药生物</td>
                        <td id="T_d50ab_row24_col2" class="data row24 col2" >3.28</td>
                        <td id="T_d50ab_row24_col3" class="data row24 col3" >30.07</td>
                        <td id="T_d50ab_row24_col4" class="data row24 col4" >8.72</td>
                        <td id="T_d50ab_row24_col5" class="data row24 col5" >5.26</td>
                        <td id="T_d50ab_row24_col6" class="data row24 col6" >29.36</td>
                        <td id="T_d50ab_row24_col7" class="data row24 col7" >27.54</td>
                        <td id="T_d50ab_row24_col8" class="data row24 col8" >15,627.25</td>
                        <td id="T_d50ab_row24_col9" class="data row24 col9" >23.49</td>
                        <td id="T_d50ab_row24_col10" class="data row24 col10" >3.33</td>
                        <td id="T_d50ab_row24_col11" class="data row24 col11" >4,411.68</td>
                        <td id="T_d50ab_row24_col12" class="data row24 col12" >37.24</td>
                        <td id="T_d50ab_row24_col13" class="data row24 col13" >9.89</td>
                        <td id="T_d50ab_row24_col14" class="data row24 col14" >4,455.57</td>
                        <td id="T_d50ab_row24_col15" class="data row24 col15" >43.62</td>
                        <td id="T_d50ab_row24_col16" class="data row24 col16" >44.39</td>
                        <td id="T_d50ab_row24_col17" class="data row24 col17" >83.38</td>
                        <td id="T_d50ab_row24_col18" class="data row24 col18" >133.43</td>
                        <td id="T_d50ab_row24_col19" class="data row24 col19" >3.58</td>
                        <td id="T_d50ab_row24_col20" class="data row24 col20" >-</td>
                        <td id="T_d50ab_row24_col21" class="data row24 col21" >588,637.08</td>
                        <td id="T_d50ab_row24_col22" class="data row24 col22" >157,189.72</td>
                        <td id="T_d50ab_row24_col23" class="data row24 col23" >136,697.11</td>
                        <td id="T_d50ab_row24_col24" class="data row24 col24" >-274.48</td>
            </tr>
            <tr>
                        <th id="T_d50ab_level0_row25" class="row_heading level0 row25" >600519.SS</th>
                        <td id="T_d50ab_row25_col0" class="data row25 col0" >贵州茅台</td>
                        <td id="T_d50ab_row25_col1" class="data row25 col1" >食品饮料</td>
                        <td id="T_d50ab_row25_col2" class="data row25 col2" >30.99</td>
                        <td id="T_d50ab_row25_col3" class="data row25 col3" >21.40</td>
                        <td id="T_d50ab_row25_col4" class="data row25 col4" >1.65</td>
                        <td id="T_d50ab_row25_col5" class="data row25 col5" >-</td>
                        <td id="T_d50ab_row25_col6" class="data row25 col6" >30.01</td>
                        <td id="T_d50ab_row25_col7" class="data row25 col7" >47.94</td>
                        <td id="T_d50ab_row25_col8" class="data row25 col8" >78,050.86</td>
                        <td id="T_d50ab_row25_col9" class="data row25 col9" >17.87</td>
                        <td id="T_d50ab_row25_col10" class="data row25 col10" >7.86</td>
                        <td id="T_d50ab_row25_col11" class="data row25 col11" >37,546.69</td>
                        <td id="T_d50ab_row25_col12" class="data row25 col12" >20.13</td>
                        <td id="T_d50ab_row25_col13" class="data row25 col13" >8.75</td>
                        <td id="T_d50ab_row25_col14" class="data row25 col14" >38,111.89</td>
                        <td id="T_d50ab_row25_col15" class="data row25 col15" >37.59</td>
                        <td id="T_d50ab_row25_col16" class="data row25 col16" >45.08</td>
                        <td id="T_d50ab_row25_col17" class="data row25 col17" >59.47</td>
                        <td id="T_d50ab_row25_col18" class="data row25 col18" >75.33</td>
                        <td id="T_d50ab_row25_col19" class="data row25 col19" >3.74</td>
                        <td id="T_d50ab_row25_col20" class="data row25 col20" >1.33</td>
                        <td id="T_d50ab_row25_col21" class="data row25 col21" >2,828,334.27</td>
                        <td id="T_d50ab_row25_col22" class="data row25 col22" >1,189,500.62</td>
                        <td id="T_d50ab_row25_col23" class="data row25 col23" >796,909.35</td>
                        <td id="T_d50ab_row25_col24" class="data row25 col24" >-137.77</td>
            </tr>
            <tr>
                        <th id="T_d50ab_level0_row26" class="row_heading level0 row26" >603288.SS</th>
                        <td id="T_d50ab_row26_col0" class="data row26 col0" >海天味业</td>
                        <td id="T_d50ab_row26_col1" class="data row26 col1" >食品饮料</td>
                        <td id="T_d50ab_row26_col2" class="data row26 col2" >5.03</td>
                        <td id="T_d50ab_row26_col3" class="data row26 col3" >31.72</td>
                        <td id="T_d50ab_row26_col4" class="data row26 col4" >0.21</td>
                        <td id="T_d50ab_row26_col5" class="data row26 col5" >0.15</td>
                        <td id="T_d50ab_row26_col6" class="data row26 col6" >31.42</td>
                        <td id="T_d50ab_row26_col7" class="data row26 col7" >26.24</td>
                        <td id="T_d50ab_row26_col8" class="data row26 col8" >18,551.89</td>
                        <td id="T_d50ab_row26_col9" class="data row26 col9" >16.05</td>
                        <td id="T_d50ab_row26_col10" class="data row26 col10" >0.85</td>
                        <td id="T_d50ab_row26_col11" class="data row26 col11" >4,913.07</td>
                        <td id="T_d50ab_row26_col12" class="data row26 col12" >21.95</td>
                        <td id="T_d50ab_row26_col13" class="data row26 col13" >2.08</td>
                        <td id="T_d50ab_row26_col14" class="data row26 col14" >5,564.91</td>
                        <td id="T_d50ab_row26_col15" class="data row26 col15" >11.37</td>
                        <td id="T_d50ab_row26_col16" class="data row26 col16" >15.72</td>
                        <td id="T_d50ab_row26_col17" class="data row26 col17" >66.07</td>
                        <td id="T_d50ab_row26_col18" class="data row26 col18" >90.64</td>
                        <td id="T_d50ab_row26_col19" class="data row26 col19" >4.13</td>
                        <td id="T_d50ab_row26_col20" class="data row26 col20" >1.20</td>
                        <td id="T_d50ab_row26_col21" class="data row26 col21" >445,301.26</td>
                        <td id="T_d50ab_row26_col22" class="data row26 col22" >95,461.96</td>
                        <td id="T_d50ab_row26_col23" class="data row26 col23" >108,814.57</td>
                        <td id="T_d50ab_row26_col24" class="data row26 col24" >-366.47</td>
            </tr>
            <tr>
                        <th id="T_d50ab_level0_row27" class="row_heading level0 row27" >300595.SZ</th>
                        <td id="T_d50ab_row27_col0" class="data row27 col0" >欧普康视</td>
                        <td id="T_d50ab_row27_col1" class="data row27 col1" >医药生物</td>
                        <td id="T_d50ab_row27_col2" class="data row27 col2" >1.19</td>
                        <td id="T_d50ab_row27_col3" class="data row27 col3" >10.02</td>
                        <td id="T_d50ab_row27_col4" class="data row27 col4" >18.19</td>
                        <td id="T_d50ab_row27_col5" class="data row27 col5" >9.82</td>
                        <td id="T_d50ab_row27_col6" class="data row27 col6" >21.91</td>
                        <td id="T_d50ab_row27_col7" class="data row27 col7" >48.20</td>
                        <td id="T_d50ab_row27_col8" class="data row27 col8" >571.90</td>
                        <td id="T_d50ab_row27_col9" class="data row27 col9" >40.94</td>
                        <td id="T_d50ab_row27_col10" class="data row27 col10" >6.26</td>
                        <td id="T_d50ab_row27_col11" class="data row27 col11" >276.83</td>
                        <td id="T_d50ab_row27_col12" class="data row27 col12" >42.15</td>
                        <td id="T_d50ab_row27_col13" class="data row27 col13" >1.09</td>
                        <td id="T_d50ab_row27_col14" class="data row27 col14" >174.99</td>
                        <td id="T_d50ab_row27_col15" class="data row27 col15" >54.08</td>
                        <td id="T_d50ab_row27_col16" class="data row27 col16" >33.61</td>
                        <td id="T_d50ab_row27_col17" class="data row27 col17" >114.88</td>
                        <td id="T_d50ab_row27_col18" class="data row27 col18" >220.13</td>
                        <td id="T_d50ab_row27_col19" class="data row27 col19" >5.22</td>
                        <td id="T_d50ab_row27_col20" class="data row27 col20" >-</td>
                        <td id="T_d50ab_row27_col21" class="data row27 col21" >60,938.51</td>
                        <td id="T_d50ab_row27_col22" class="data row27 col22" >7,554.71</td>
                        <td id="T_d50ab_row27_col23" class="data row27 col23" >9,483.90</td>
                        <td id="T_d50ab_row27_col24" class="data row27 col24" >-706.63</td>
            </tr>
            <tr>
                        <th id="T_d50ab_level0_row28" class="row_heading level0 row28" >600436.SS</th>
                        <td id="T_d50ab_row28_col0" class="data row28 col0" >片仔癀</td>
                        <td id="T_d50ab_row28_col1" class="data row28 col1" >医药生物</td>
                        <td id="T_d50ab_row28_col2" class="data row28 col2" >2.71</td>
                        <td id="T_d50ab_row28_col3" class="data row28 col3" >19.10</td>
                        <td id="T_d50ab_row28_col4" class="data row28 col4" >10.00</td>
                        <td id="T_d50ab_row28_col5" class="data row28 col5" >0.12</td>
                        <td id="T_d50ab_row28_col6" class="data row28 col6" >21.07</td>
                        <td id="T_d50ab_row28_col7" class="data row28 col7" >23.85</td>
                        <td id="T_d50ab_row28_col8" class="data row28 col8" >5,178.29</td>
                        <td id="T_d50ab_row28_col9" class="data row28 col9" >20.72</td>
                        <td id="T_d50ab_row28_col10" class="data row28 col10" >7.30</td>
                        <td id="T_d50ab_row28_col11" class="data row28 col11" >1,248.96</td>
                        <td id="T_d50ab_row28_col12" class="data row28 col12" >27.83</td>
                        <td id="T_d50ab_row28_col13" class="data row28 col13" >11.96</td>
                        <td id="T_d50ab_row28_col14" class="data row28 col14" >316.60</td>
                        <td id="T_d50ab_row28_col15" class="data row28 col15" >-166.81</td>
                        <td id="T_d50ab_row28_col16" class="data row28 col16" >136.30</td>
                        <td id="T_d50ab_row28_col17" class="data row28 col17" >137.41</td>
                        <td id="T_d50ab_row28_col18" class="data row28 col18" >194.48</td>
                        <td id="T_d50ab_row28_col19" class="data row28 col19" >6.99</td>
                        <td id="T_d50ab_row28_col20" class="data row28 col20" >0.48</td>
                        <td id="T_d50ab_row28_col21" class="data row28 col21" >242,895.42</td>
                        <td id="T_d50ab_row28_col22" class="data row28 col22" >-1,098.57</td>
                        <td id="T_d50ab_row28_col23" class="data row28 col23" >31,611.16</td>
                        <td id="T_d50ab_row28_col24" class="data row28 col24" >-</td>
            </tr>
            <tr>
                        <th id="T_d50ab_level0_row29" class="row_heading level0 row29" >300896.SZ</th>
                        <td id="T_d50ab_row29_col0" class="data row29 col0" >爱美客</td>
                        <td id="T_d50ab_row29_col1" class="data row29 col1" >医药生物</td>
                        <td id="T_d50ab_row29_col2" class="data row29 col2" >0.88</td>
                        <td id="T_d50ab_row29_col3" class="data row29 col3" >2.19</td>
                        <td id="T_d50ab_row29_col4" class="data row29 col4" >6.39</td>
                        <td id="T_d50ab_row29_col5" class="data row29 col5" >-</td>
                        <td id="T_d50ab_row29_col6" class="data row29 col6" >28.05</td>
                        <td id="T_d50ab_row29_col7" class="data row29 col7" >48.00</td>
                        <td id="T_d50ab_row29_col8" class="data row29 col8" >452.63</td>
                        <td id="T_d50ab_row29_col9" class="data row29 col9" >48.40</td>
                        <td id="T_d50ab_row29_col10" class="data row29 col10" >23.55</td>
                        <td id="T_d50ab_row29_col11" class="data row29 col11" >237.58</td>
                        <td id="T_d50ab_row29_col12" class="data row29 col12" >80.70</td>
                        <td id="T_d50ab_row29_col13" class="data row29 col13" >58.94</td>
                        <td id="T_d50ab_row29_col14" class="data row29 col14" >202.15</td>
                        <td id="T_d50ab_row29_col15" class="data row29 col15" >120.48</td>
                        <td id="T_d50ab_row29_col16" class="data row29 col16" >73.47</td>
                        <td id="T_d50ab_row29_col17" class="data row29 col17" >193.55</td>
                        <td id="T_d50ab_row29_col18" class="data row29 col18" >589.77</td>
                        <td id="T_d50ab_row29_col19" class="data row29 col19" >7.31</td>
                        <td id="T_d50ab_row29_col20" class="data row29 col20" >-</td>
                        <td id="T_d50ab_row29_col21" class="data row29 col21" >140,116.90</td>
                        <td id="T_d50ab_row29_col22" class="data row29 col22" >24,712.33</td>
                        <td id="T_d50ab_row29_col23" class="data row29 col23" >16,258.23</td>
                        <td id="T_d50ab_row29_col24" class="data row29 col24" >-466.99</td>
            </tr>
            <tr>
                        <th id="T_d50ab_level0_row30" class="row_heading level0 row30" >600763.SS</th>
                        <td id="T_d50ab_row30_col0" class="data row30 col0" >通策医疗</td>
                        <td id="T_d50ab_row30_col1" class="data row30 col1" >医药生物</td>
                        <td id="T_d50ab_row30_col2" class="data row30 col2" >2.16</td>
                        <td id="T_d50ab_row30_col3" class="data row30 col3" >23.37</td>
                        <td id="T_d50ab_row30_col4" class="data row30 col4" >4.92</td>
                        <td id="T_d50ab_row30_col5" class="data row30 col5" >2.34</td>
                        <td id="T_d50ab_row30_col6" class="data row30 col6" >23.98</td>
                        <td id="T_d50ab_row30_col7" class="data row30 col7" >21.89</td>
                        <td id="T_d50ab_row30_col8" class="data row30 col8" >1,686.17</td>
                        <td id="T_d50ab_row30_col9" class="data row30 col9" >21.36</td>
                        <td id="T_d50ab_row30_col10" class="data row30 col10" >11.87</td>
                        <td id="T_d50ab_row30_col11" class="data row30 col11" >376.85</td>
                        <td id="T_d50ab_row30_col12" class="data row30 col12" >33.13</td>
                        <td id="T_d50ab_row30_col13" class="data row30 col13" >24.64</td>
                        <td id="T_d50ab_row30_col14" class="data row30 col14" >394.02</td>
                        <td id="T_d50ab_row30_col15" class="data row30 col15" >38.60</td>
                        <td id="T_d50ab_row30_col16" class="data row30 col16" >81.59</td>
                        <td id="T_d50ab_row30_col17" class="data row30 col17" >176.39</td>
                        <td id="T_d50ab_row30_col18" class="data row30 col18" >315.32</td>
                        <td id="T_d50ab_row30_col19" class="data row30 col19" >9.52</td>
                        <td id="T_d50ab_row30_col20" class="data row30 col20" >-</td>
                        <td id="T_d50ab_row30_col21" class="data row30 col21" >118,829.19</td>
                        <td id="T_d50ab_row30_col22" class="data row30 col22" >12,555.97</td>
                        <td id="T_d50ab_row30_col23" class="data row30 col23" >10,705.43</td>
                        <td id="T_d50ab_row30_col24" class="data row30 col24" >-846.40</td>
            </tr>
            <tr>
                        <th id="T_d50ab_level0_row31" class="row_heading level0 row31" >000885.SZ</th>
                        <td id="T_d50ab_row31_col0" class="data row31 col0" >城发环境</td>
                        <td id="T_d50ab_row31_col1" class="data row31 col1" >交通运输</td>
                        <td id="T_d50ab_row31_col2" class="data row31 col2" >0.26</td>
                        <td id="T_d50ab_row31_col3" class="data row31 col3" >60.46</td>
                        <td id="T_d50ab_row31_col4" class="data row31 col4" >15.69</td>
                        <td id="T_d50ab_row31_col5" class="data row31 col5" >-</td>
                        <td id="T_d50ab_row31_col6" class="data row31 col6" >22.03</td>
                        <td id="T_d50ab_row31_col7" class="data row31 col7" >25.54</td>
                        <td id="T_d50ab_row31_col8" class="data row31 col8" >2,462.85</td>
                        <td id="T_d50ab_row31_col9" class="data row31 col9" >18.36</td>
                        <td id="T_d50ab_row31_col10" class="data row31 col10" >28.79</td>
                        <td id="T_d50ab_row31_col11" class="data row31 col11" >605.56</td>
                        <td id="T_d50ab_row31_col12" class="data row31 col12" >0.73</td>
                        <td id="T_d50ab_row31_col13" class="data row31 col13" >5.86</td>
                        <td id="T_d50ab_row31_col14" class="data row31 col14" >140.39</td>
                        <td id="T_d50ab_row31_col15" class="data row31 col15" >-328.78</td>
                        <td id="T_d50ab_row31_col16" class="data row31 col16" >483.06</td>
                        <td id="T_d50ab_row31_col17" class="data row31 col17" >6.56</td>
                        <td id="T_d50ab_row31_col18" class="data row31 col18" >10.59</td>
                        <td id="T_d50ab_row31_col19" class="data row31 col19" >14.45</td>
                        <td id="T_d50ab_row31_col20" class="data row31 col20" >0.68</td>
                        <td id="T_d50ab_row31_col21" class="data row31 col21" >6,414.36</td>
                        <td id="T_d50ab_row31_col22" class="data row31 col22" >-17,763.33</td>
                        <td id="T_d50ab_row31_col23" class="data row31 col23" >7,851.65</td>
                        <td id="T_d50ab_row31_col24" class="data row31 col24" >-</td>
            </tr>
    </tbody></table>



### 金融行业

1. ROE >= 10%
2. 商誉比 < 10%
3. 利润率 >= 20%
3. 盈利增长 >= 10% 或 收入增长 >= 10%




<style  type="text/css" >
#T_57516_row0_col0,#T_57516_row0_col1,#T_57516_row0_col2,#T_57516_row0_col3,#T_57516_row0_col4,#T_57516_row0_col5,#T_57516_row0_col6,#T_57516_row0_col7,#T_57516_row0_col8,#T_57516_row0_col9,#T_57516_row0_col10,#T_57516_row0_col11,#T_57516_row0_col12,#T_57516_row0_col13,#T_57516_row0_col14,#T_57516_row0_col16,#T_57516_row0_col17,#T_57516_row0_col18,#T_57516_row0_col19,#T_57516_row0_col20,#T_57516_row0_col21,#T_57516_row0_col23,#T_57516_row0_col24,#T_57516_row1_col0,#T_57516_row1_col1,#T_57516_row1_col2,#T_57516_row1_col3,#T_57516_row1_col4,#T_57516_row1_col5,#T_57516_row1_col6,#T_57516_row1_col7,#T_57516_row1_col8,#T_57516_row1_col9,#T_57516_row1_col10,#T_57516_row1_col11,#T_57516_row1_col12,#T_57516_row1_col13,#T_57516_row1_col16,#T_57516_row1_col17,#T_57516_row1_col18,#T_57516_row1_col19,#T_57516_row1_col20,#T_57516_row1_col21,#T_57516_row1_col22,#T_57516_row1_col23,#T_57516_row2_col0,#T_57516_row2_col1,#T_57516_row2_col2,#T_57516_row2_col3,#T_57516_row2_col4,#T_57516_row2_col5,#T_57516_row2_col6,#T_57516_row2_col7,#T_57516_row2_col8,#T_57516_row2_col9,#T_57516_row2_col10,#T_57516_row2_col11,#T_57516_row2_col12,#T_57516_row2_col13,#T_57516_row2_col14,#T_57516_row2_col16,#T_57516_row2_col17,#T_57516_row2_col18,#T_57516_row2_col19,#T_57516_row2_col20,#T_57516_row2_col21,#T_57516_row2_col23,#T_57516_row2_col24,#T_57516_row3_col0,#T_57516_row3_col1,#T_57516_row3_col2,#T_57516_row3_col3,#T_57516_row3_col4,#T_57516_row3_col5,#T_57516_row3_col6,#T_57516_row3_col7,#T_57516_row3_col8,#T_57516_row3_col9,#T_57516_row3_col10,#T_57516_row3_col11,#T_57516_row3_col12,#T_57516_row3_col13,#T_57516_row3_col14,#T_57516_row3_col16,#T_57516_row3_col17,#T_57516_row3_col18,#T_57516_row3_col19,#T_57516_row3_col20,#T_57516_row3_col21,#T_57516_row3_col23,#T_57516_row3_col24,#T_57516_row4_col0,#T_57516_row4_col1,#T_57516_row4_col2,#T_57516_row4_col3,#T_57516_row4_col4,#T_57516_row4_col5,#T_57516_row4_col6,#T_57516_row4_col7,#T_57516_row4_col8,#T_57516_row4_col9,#T_57516_row4_col10,#T_57516_row4_col11,#T_57516_row4_col12,#T_57516_row4_col13,#T_57516_row4_col16,#T_57516_row4_col17,#T_57516_row4_col18,#T_57516_row4_col19,#T_57516_row4_col20,#T_57516_row4_col21,#T_57516_row4_col22,#T_57516_row4_col23,#T_57516_row5_col0,#T_57516_row5_col1,#T_57516_row5_col2,#T_57516_row5_col3,#T_57516_row5_col4,#T_57516_row5_col5,#T_57516_row5_col6,#T_57516_row5_col7,#T_57516_row5_col8,#T_57516_row5_col9,#T_57516_row5_col10,#T_57516_row5_col11,#T_57516_row5_col12,#T_57516_row5_col13,#T_57516_row5_col16,#T_57516_row5_col17,#T_57516_row5_col18,#T_57516_row5_col19,#T_57516_row5_col20,#T_57516_row5_col21,#T_57516_row5_col22,#T_57516_row5_col23,#T_57516_row6_col0,#T_57516_row6_col1,#T_57516_row6_col2,#T_57516_row6_col3,#T_57516_row6_col4,#T_57516_row6_col5,#T_57516_row6_col6,#T_57516_row6_col7,#T_57516_row6_col8,#T_57516_row6_col9,#T_57516_row6_col10,#T_57516_row6_col11,#T_57516_row6_col12,#T_57516_row6_col13,#T_57516_row6_col16,#T_57516_row6_col17,#T_57516_row6_col18,#T_57516_row6_col19,#T_57516_row6_col20,#T_57516_row6_col21,#T_57516_row6_col22,#T_57516_row6_col23,#T_57516_row6_col24,#T_57516_row7_col0,#T_57516_row7_col1,#T_57516_row7_col2,#T_57516_row7_col3,#T_57516_row7_col4,#T_57516_row7_col5,#T_57516_row7_col6,#T_57516_row7_col7,#T_57516_row7_col8,#T_57516_row7_col9,#T_57516_row7_col10,#T_57516_row7_col11,#T_57516_row7_col12,#T_57516_row7_col13,#T_57516_row7_col14,#T_57516_row7_col15,#T_57516_row7_col16,#T_57516_row7_col17,#T_57516_row7_col18,#T_57516_row7_col19,#T_57516_row7_col20,#T_57516_row7_col21,#T_57516_row7_col22,#T_57516_row7_col23,#T_57516_row7_col24,#T_57516_row8_col0,#T_57516_row8_col1,#T_57516_row8_col2,#T_57516_row8_col3,#T_57516_row8_col4,#T_57516_row8_col5,#T_57516_row8_col6,#T_57516_row8_col7,#T_57516_row8_col8,#T_57516_row8_col9,#T_57516_row8_col10,#T_57516_row8_col11,#T_57516_row8_col12,#T_57516_row8_col13,#T_57516_row8_col16,#T_57516_row8_col17,#T_57516_row8_col18,#T_57516_row8_col19,#T_57516_row8_col20,#T_57516_row8_col21,#T_57516_row8_col22,#T_57516_row8_col23,#T_57516_row9_col0,#T_57516_row9_col1,#T_57516_row9_col2,#T_57516_row9_col3,#T_57516_row9_col4,#T_57516_row9_col5,#T_57516_row9_col6,#T_57516_row9_col7,#T_57516_row9_col8,#T_57516_row9_col9,#T_57516_row9_col10,#T_57516_row9_col11,#T_57516_row9_col12,#T_57516_row9_col13,#T_57516_row9_col14,#T_57516_row9_col15,#T_57516_row9_col16,#T_57516_row9_col17,#T_57516_row9_col18,#T_57516_row9_col19,#T_57516_row9_col20,#T_57516_row9_col21,#T_57516_row9_col22,#T_57516_row9_col23,#T_57516_row9_col24,#T_57516_row10_col0,#T_57516_row10_col1,#T_57516_row10_col2,#T_57516_row10_col3,#T_57516_row10_col4,#T_57516_row10_col5,#T_57516_row10_col6,#T_57516_row10_col7,#T_57516_row10_col8,#T_57516_row10_col9,#T_57516_row10_col10,#T_57516_row10_col11,#T_57516_row10_col12,#T_57516_row10_col13,#T_57516_row10_col16,#T_57516_row10_col17,#T_57516_row10_col18,#T_57516_row10_col19,#T_57516_row10_col20,#T_57516_row10_col21,#T_57516_row10_col23,#T_57516_row10_col24,#T_57516_row11_col0,#T_57516_row11_col1,#T_57516_row11_col2,#T_57516_row11_col3,#T_57516_row11_col4,#T_57516_row11_col5,#T_57516_row11_col6,#T_57516_row11_col7,#T_57516_row11_col8,#T_57516_row11_col9,#T_57516_row11_col10,#T_57516_row11_col11,#T_57516_row11_col12,#T_57516_row11_col13,#T_57516_row11_col14,#T_57516_row11_col16,#T_57516_row11_col17,#T_57516_row11_col18,#T_57516_row11_col19,#T_57516_row11_col20,#T_57516_row11_col21,#T_57516_row11_col23,#T_57516_row11_col24,#T_57516_row12_col0,#T_57516_row12_col1,#T_57516_row12_col2,#T_57516_row12_col3,#T_57516_row12_col4,#T_57516_row12_col5,#T_57516_row12_col6,#T_57516_row12_col7,#T_57516_row12_col8,#T_57516_row12_col9,#T_57516_row12_col10,#T_57516_row12_col11,#T_57516_row12_col12,#T_57516_row12_col13,#T_57516_row12_col15,#T_57516_row12_col16,#T_57516_row12_col17,#T_57516_row12_col18,#T_57516_row12_col19,#T_57516_row12_col20,#T_57516_row12_col21,#T_57516_row12_col23,#T_57516_row12_col24,#T_57516_row13_col0,#T_57516_row13_col1,#T_57516_row13_col2,#T_57516_row13_col3,#T_57516_row13_col4,#T_57516_row13_col5,#T_57516_row13_col6,#T_57516_row13_col7,#T_57516_row13_col8,#T_57516_row13_col9,#T_57516_row13_col10,#T_57516_row13_col11,#T_57516_row13_col12,#T_57516_row13_col13,#T_57516_row13_col14,#T_57516_row13_col16,#T_57516_row13_col17,#T_57516_row13_col18,#T_57516_row13_col19,#T_57516_row13_col20,#T_57516_row13_col21,#T_57516_row13_col23,#T_57516_row13_col24,#T_57516_row14_col0,#T_57516_row14_col1,#T_57516_row14_col2,#T_57516_row14_col3,#T_57516_row14_col4,#T_57516_row14_col5,#T_57516_row14_col6,#T_57516_row14_col7,#T_57516_row14_col8,#T_57516_row14_col9,#T_57516_row14_col10,#T_57516_row14_col11,#T_57516_row14_col12,#T_57516_row14_col13,#T_57516_row14_col16,#T_57516_row14_col17,#T_57516_row14_col18,#T_57516_row14_col19,#T_57516_row14_col20,#T_57516_row14_col21,#T_57516_row14_col23,#T_57516_row14_col24,#T_57516_row15_col0,#T_57516_row15_col1,#T_57516_row15_col2,#T_57516_row15_col3,#T_57516_row15_col4,#T_57516_row15_col5,#T_57516_row15_col6,#T_57516_row15_col7,#T_57516_row15_col8,#T_57516_row15_col9,#T_57516_row15_col10,#T_57516_row15_col11,#T_57516_row15_col12,#T_57516_row15_col13,#T_57516_row15_col16,#T_57516_row15_col17,#T_57516_row15_col18,#T_57516_row15_col19,#T_57516_row15_col20,#T_57516_row15_col21,#T_57516_row15_col23,#T_57516_row15_col24,#T_57516_row16_col0,#T_57516_row16_col1,#T_57516_row16_col2,#T_57516_row16_col3,#T_57516_row16_col4,#T_57516_row16_col5,#T_57516_row16_col6,#T_57516_row16_col7,#T_57516_row16_col8,#T_57516_row16_col9,#T_57516_row16_col10,#T_57516_row16_col11,#T_57516_row16_col12,#T_57516_row16_col13,#T_57516_row16_col16,#T_57516_row16_col17,#T_57516_row16_col18,#T_57516_row16_col19,#T_57516_row16_col20,#T_57516_row16_col21,#T_57516_row16_col23,#T_57516_row16_col24{
            color:  black;
        }#T_57516_row0_col15,#T_57516_row0_col22,#T_57516_row1_col14,#T_57516_row1_col15,#T_57516_row1_col24,#T_57516_row2_col15,#T_57516_row2_col22,#T_57516_row3_col15,#T_57516_row3_col22,#T_57516_row4_col14,#T_57516_row4_col15,#T_57516_row4_col24,#T_57516_row5_col14,#T_57516_row5_col15,#T_57516_row5_col24,#T_57516_row6_col14,#T_57516_row6_col15,#T_57516_row8_col14,#T_57516_row8_col15,#T_57516_row8_col24,#T_57516_row10_col14,#T_57516_row10_col15,#T_57516_row10_col22,#T_57516_row11_col15,#T_57516_row11_col22,#T_57516_row12_col14,#T_57516_row12_col22,#T_57516_row13_col15,#T_57516_row13_col22,#T_57516_row14_col14,#T_57516_row14_col15,#T_57516_row14_col22,#T_57516_row15_col14,#T_57516_row15_col15,#T_57516_row15_col22,#T_57516_row16_col14,#T_57516_row16_col15,#T_57516_row16_col22{
            color:  red;
        }</style><table id="T_57516_" ><thead>    <tr>        <th class="blank level0" ></th>        <th class="col_heading level0 col0" >名称</th>        <th class="col_heading level0 col1" >行业</th>        <th class="col_heading level0 col2" >权重</th>        <th class="col_heading level0 col3" >负债率</th>        <th class="col_heading level0 col4" >应收比</th>        <th class="col_heading level0 col5" >商誉比</th>        <th class="col_heading level0 col6" >ROE</th>        <th class="col_heading level0 col7" >利润率</th>        <th class="col_heading level0 col8" >收入</th>        <th class="col_heading level0 col9" >收入增长</th>        <th class="col_heading level0 col10" >收入波动</th>        <th class="col_heading level0 col11" >盈利</th>        <th class="col_heading level0 col12" >盈利增长</th>        <th class="col_heading level0 col13" >盈利波动</th>        <th class="col_heading level0 col14" >FCF</th>        <th class="col_heading level0 col15" >FCF增长</th>        <th class="col_heading level0 col16" >FCF波动</th>        <th class="col_heading level0 col17" >PE</th>        <th class="col_heading level0 col18" >PE0</th>        <th class="col_heading level0 col19" >PEG</th>        <th class="col_heading level0 col20" >股息率</th>        <th class="col_heading level0 col21" >市值</th>        <th class="col_heading level0 col22" >DCF</th>        <th class="col_heading level0 col23" >盈利折现</th>        <th class="col_heading level0 col24" >折价率</th>    </tr>    <tr>        <th class="index_name level0" >Symbol</th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>    </tr></thead><tbody>
                <tr>
                        <th id="T_57516_level0_row0" class="row_heading level0 row0" >601997.SS</th>
                        <td id="T_57516_row0_col0" class="data row0 col0" >贵阳银行</td>
                        <td id="T_57516_row0_col1" class="data row0 col1" >银行</td>
                        <td id="T_57516_row0_col2" class="data row0 col2" >0.64</td>
                        <td id="T_57516_row0_col3" class="data row0 col3" >92.80</td>
                        <td id="T_57516_row0_col4" class="data row0 col4" >1.28</td>
                        <td id="T_57516_row0_col5" class="data row0 col5" >-</td>
                        <td id="T_57516_row0_col6" class="data row0 col6" >17.47</td>
                        <td id="T_57516_row0_col7" class="data row0 col7" >54.49</td>
                        <td id="T_57516_row0_col8" class="data row0 col8" >8,736.19</td>
                        <td id="T_57516_row0_col9" class="data row0 col9" >13.83</td>
                        <td id="T_57516_row0_col10" class="data row0 col10" >9.08</td>
                        <td id="T_57516_row0_col11" class="data row0 col11" >4,780.68</td>
                        <td id="T_57516_row0_col12" class="data row0 col12" >16.76</td>
                        <td id="T_57516_row0_col13" class="data row0 col13" >6.26</td>
                        <td id="T_57516_row0_col14" class="data row0 col14" >14,131.23</td>
                        <td id="T_57516_row0_col15" class="data row0 col15" >-159.52</td>
                        <td id="T_57516_row0_col16" class="data row0 col16" >117.14</td>
                        <td id="T_57516_row0_col17" class="data row0 col17" >4.53</td>
                        <td id="T_57516_row0_col18" class="data row0 col18" >5.93</td>
                        <td id="T_57516_row0_col19" class="data row0 col19" >0.35</td>
                        <td id="T_57516_row0_col20" class="data row0 col20" >-</td>
                        <td id="T_57516_row0_col21" class="data row0 col21" >28,335.55</td>
                        <td id="T_57516_row0_col22" class="data row0 col22" >-35,892.16</td>
                        <td id="T_57516_row0_col23" class="data row0 col23" >93,650.87</td>
                        <td id="T_57516_row0_col24" class="data row0 col24" >-</td>
            </tr>
            <tr>
                        <th id="T_57516_level0_row1" class="row_heading level0 row1" >601229.SS</th>
                        <td id="T_57516_row1_col0" class="data row1 col0" >上海银行</td>
                        <td id="T_57516_row1_col1" class="data row1 col1" >银行</td>
                        <td id="T_57516_row1_col2" class="data row1 col2" >2.59</td>
                        <td id="T_57516_row1_col3" class="data row1 col3" >92.25</td>
                        <td id="T_57516_row1_col4" class="data row1 col4" >7.05</td>
                        <td id="T_57516_row1_col5" class="data row1 col5" >-</td>
                        <td id="T_57516_row1_col6" class="data row1 col6" >12.51</td>
                        <td id="T_57516_row1_col7" class="data row1 col7" >63.20</td>
                        <td id="T_57516_row1_col8" class="data row1 col8" >29,477.00</td>
                        <td id="T_57516_row1_col9" class="data row1 col9" >10.14</td>
                        <td id="T_57516_row1_col10" class="data row1 col10" >9.39</td>
                        <td id="T_57516_row1_col11" class="data row1 col11" >18,636.30</td>
                        <td id="T_57516_row1_col12" class="data row1 col12" >11.03</td>
                        <td id="T_57516_row1_col13" class="data row1 col13" >7.49</td>
                        <td id="T_57516_row1_col14" class="data row1 col14" >-20,440.42</td>
                        <td id="T_57516_row1_col15" class="data row1 col15" >-118.51</td>
                        <td id="T_57516_row1_col16" class="data row1 col16" >97.23</td>
                        <td id="T_57516_row1_col17" class="data row1 col17" >6.15</td>
                        <td id="T_57516_row1_col18" class="data row1 col18" >6.55</td>
                        <td id="T_57516_row1_col19" class="data row1 col19" >0.59</td>
                        <td id="T_57516_row1_col20" class="data row1 col20" >-</td>
                        <td id="T_57516_row1_col21" class="data row1 col21" >122,033.83</td>
                        <td id="T_57516_row1_col22" class="data row1 col22" >4,531.48</td>
                        <td id="T_57516_row1_col23" class="data row1 col23" >316,966.00</td>
                        <td id="T_57516_row1_col24" class="data row1 col24" >-2,593.02</td>
            </tr>
            <tr>
                        <th id="T_57516_level0_row2" class="row_heading level0 row2" >601838.SS</th>
                        <td id="T_57516_row2_col0" class="data row2 col0" >成都银行</td>
                        <td id="T_57516_row2_col1" class="data row2 col1" >银行</td>
                        <td id="T_57516_row2_col2" class="data row2 col2" >0.82</td>
                        <td id="T_57516_row2_col3" class="data row2 col3" >93.62</td>
                        <td id="T_57516_row2_col4" class="data row2 col4" >2.64</td>
                        <td id="T_57516_row2_col5" class="data row2 col5" >-</td>
                        <td id="T_57516_row2_col6" class="data row2 col6" >15.50</td>
                        <td id="T_57516_row2_col7" class="data row2 col7" >52.11</td>
                        <td id="T_57516_row2_col8" class="data row2 col8" >9,959.20</td>
                        <td id="T_57516_row2_col9" class="data row2 col9" >26.62</td>
                        <td id="T_57516_row2_col10" class="data row2 col10" >21.12</td>
                        <td id="T_57516_row2_col11" class="data row2 col11" >5,033.40</td>
                        <td id="T_57516_row2_col12" class="data row2 col12" >15.63</td>
                        <td id="T_57516_row2_col13" class="data row2 col13" >6.14</td>
                        <td id="T_57516_row2_col14" class="data row2 col14" >18,048.38</td>
                        <td id="T_57516_row2_col15" class="data row2 col15" >-141.63</td>
                        <td id="T_57516_row2_col16" class="data row2 col16" >148.74</td>
                        <td id="T_57516_row2_col17" class="data row2 col17" >8.41</td>
                        <td id="T_57516_row2_col18" class="data row2 col18" >10.08</td>
                        <td id="T_57516_row2_col19" class="data row2 col19" >0.65</td>
                        <td id="T_57516_row2_col20" class="data row2 col20" >-</td>
                        <td id="T_57516_row2_col21" class="data row2 col21" >50,752.11</td>
                        <td id="T_57516_row2_col22" class="data row2 col22" >-18,655.29</td>
                        <td id="T_57516_row2_col23" class="data row2 col23" >95,935.37</td>
                        <td id="T_57516_row2_col24" class="data row2 col24" >-</td>
            </tr>
            <tr>
                        <th id="T_57516_level0_row3" class="row_heading level0 row3" >601009.SS</th>
                        <td id="T_57516_row3_col0" class="data row3 col0" >南京银行</td>
                        <td id="T_57516_row3_col1" class="data row3 col1" >银行</td>
                        <td id="T_57516_row3_col2" class="data row3 col2" >2.08</td>
                        <td id="T_57516_row3_col3" class="data row3 col3" >93.45</td>
                        <td id="T_57516_row3_col4" class="data row3 col4" >9.80</td>
                        <td id="T_57516_row3_col5" class="data row3 col5" >-</td>
                        <td id="T_57516_row3_col6" class="data row3 col6" >16.29</td>
                        <td id="T_57516_row3_col7" class="data row3 col7" >49.90</td>
                        <td id="T_57516_row3_col8" class="data row3 col8" >20,684.31</td>
                        <td id="T_57516_row3_col9" class="data row3 col9" >10.15</td>
                        <td id="T_57516_row3_col10" class="data row3 col10" >5.23</td>
                        <td id="T_57516_row3_col11" class="data row3 col11" >10,364.05</td>
                        <td id="T_57516_row3_col12" class="data row3 col12" >14.67</td>
                        <td id="T_57516_row3_col13" class="data row3 col13" >2.28</td>
                        <td id="T_57516_row3_col14" class="data row3 col14" >28,442.56</td>
                        <td id="T_57516_row3_col15" class="data row3 col15" >-1,417.97</td>
                        <td id="T_57516_row3_col16" class="data row3 col16" >2,342.24</td>
                        <td id="T_57516_row3_col17" class="data row3 col17" >7.73</td>
                        <td id="T_57516_row3_col18" class="data row3 col18" >10.00</td>
                        <td id="T_57516_row3_col19" class="data row3 col19" >0.68</td>
                        <td id="T_57516_row3_col20" class="data row3 col20" >3.81</td>
                        <td id="T_57516_row3_col21" class="data row3 col21" >103,672.52</td>
                        <td id="T_57516_row3_col22" class="data row3 col22" >-697,759,978.24</td>
                        <td id="T_57516_row3_col23" class="data row3 col23" >192,986.56</td>
                        <td id="T_57516_row3_col24" class="data row3 col24" >-</td>
            </tr>
            <tr>
                        <th id="T_57516_level0_row4" class="row_heading level0 row4" >601577.SS</th>
                        <td id="T_57516_row4_col0" class="data row4 col0" >长沙银行</td>
                        <td id="T_57516_row4_col1" class="data row4 col1" >银行</td>
                        <td id="T_57516_row4_col2" class="data row4 col2" >0.40</td>
                        <td id="T_57516_row4_col3" class="data row4 col3" >93.51</td>
                        <td id="T_57516_row4_col4" class="data row4 col4" >2.67</td>
                        <td id="T_57516_row4_col5" class="data row4 col5" >-</td>
                        <td id="T_57516_row4_col6" class="data row4 col6" >14.98</td>
                        <td id="T_57516_row4_col7" class="data row4 col7" >43.03</td>
                        <td id="T_57516_row4_col8" class="data row4 col8" >10,934.36</td>
                        <td id="T_57516_row4_col9" class="data row4 col9" >10.42</td>
                        <td id="T_57516_row4_col10" class="data row4 col10" >5.63</td>
                        <td id="T_57516_row4_col11" class="data row4 col11" >4,706.99</td>
                        <td id="T_57516_row4_col12" class="data row4 col12" >10.82</td>
                        <td id="T_57516_row4_col13" class="data row4 col13" >4.97</td>
                        <td id="T_57516_row4_col14" class="data row4 col14" >-4,348.64</td>
                        <td id="T_57516_row4_col15" class="data row4 col15" >-149.80</td>
                        <td id="T_57516_row4_col16" class="data row4 col16" >106.99</td>
                        <td id="T_57516_row4_col17" class="data row4 col17" >6.50</td>
                        <td id="T_57516_row4_col18" class="data row4 col18" >8.16</td>
                        <td id="T_57516_row4_col19" class="data row4 col19" >0.75</td>
                        <td id="T_57516_row4_col20" class="data row4 col20" >-</td>
                        <td id="T_57516_row4_col21" class="data row4 col21" >38,405.80</td>
                        <td id="T_57516_row4_col22" class="data row4 col22" >6,955.98</td>
                        <td id="T_57516_row4_col23" class="data row4 col23" >79,624.71</td>
                        <td id="T_57516_row4_col24" class="data row4 col24" >-452.13</td>
            </tr>
            <tr>
                        <th id="T_57516_level0_row5" class="row_heading level0 row5" >002958.SZ</th>
                        <td id="T_57516_row5_col0" class="data row5 col0" >青农商行</td>
                        <td id="T_57516_row5_col1" class="data row5 col1" >银行</td>
                        <td id="T_57516_row5_col2" class="data row5 col2" >0.50</td>
                        <td id="T_57516_row5_col3" class="data row5 col3" >92.70</td>
                        <td id="T_57516_row5_col4" class="data row5 col4" >1.41</td>
                        <td id="T_57516_row5_col5" class="data row5 col5" >-</td>
                        <td id="T_57516_row5_col6" class="data row5 col6" >11.53</td>
                        <td id="T_57516_row5_col7" class="data row5 col7" >43.16</td>
                        <td id="T_57516_row5_col8" class="data row5 col8" >6,077.53</td>
                        <td id="T_57516_row5_col9" class="data row5 col9" >9.77</td>
                        <td id="T_57516_row5_col10" class="data row5 col10" >35.49</td>
                        <td id="T_57516_row5_col11" class="data row5 col11" >2,584.97</td>
                        <td id="T_57516_row5_col12" class="data row5 col12" >11.59</td>
                        <td id="T_57516_row5_col13" class="data row5 col13" >6.17</td>
                        <td id="T_57516_row5_col14" class="data row5 col14" >-129.71</td>
                        <td id="T_57516_row5_col15" class="data row5 col15" >-138.47</td>
                        <td id="T_57516_row5_col16" class="data row5 col16" >207.69</td>
                        <td id="T_57516_row5_col17" class="data row5 col17" >8.61</td>
                        <td id="T_57516_row5_col18" class="data row5 col18" >9.46</td>
                        <td id="T_57516_row5_col19" class="data row5 col19" >0.82</td>
                        <td id="T_57516_row5_col20" class="data row5 col20" >-</td>
                        <td id="T_57516_row5_col21" class="data row5 col21" >24,444.51</td>
                        <td id="T_57516_row5_col22" class="data row5 col22" >111.74</td>
                        <td id="T_57516_row5_col23" class="data row5 col23" >44,588.57</td>
                        <td id="T_57516_row5_col24" class="data row5 col24" >-21,775.93</td>
            </tr>
            <tr>
                        <th id="T_57516_level0_row6" class="row_heading level0 row6" >601658.SS</th>
                        <td id="T_57516_row6_col0" class="data row6 col0" >邮储银行</td>
                        <td id="T_57516_row6_col1" class="data row6 col1" >银行</td>
                        <td id="T_57516_row6_col2" class="data row6 col2" >1.20</td>
                        <td id="T_57516_row6_col3" class="data row6 col3" >94.07</td>
                        <td id="T_57516_row6_col4" class="data row6 col4" >2.27</td>
                        <td id="T_57516_row6_col5" class="data row6 col5" >-</td>
                        <td id="T_57516_row6_col6" class="data row6 col6" >11.82</td>
                        <td id="T_57516_row6_col7" class="data row6 col7" >26.06</td>
                        <td id="T_57516_row6_col8" class="data row6 col8" >215,288.00</td>
                        <td id="T_57516_row6_col9" class="data row6 col9" >6.04</td>
                        <td id="T_57516_row6_col10" class="data row6 col10" >2.30</td>
                        <td id="T_57516_row6_col11" class="data row6 col11" >56,281.50</td>
                        <td id="T_57516_row6_col12" class="data row6 col12" >10.52</td>
                        <td id="T_57516_row6_col13" class="data row6 col13" >5.61</td>
                        <td id="T_57516_row6_col14" class="data row6 col14" >-571,912.50</td>
                        <td id="T_57516_row6_col15" class="data row6 col15" >-173.49</td>
                        <td id="T_57516_row6_col16" class="data row6 col16" >250.48</td>
                        <td id="T_57516_row6_col17" class="data row6 col17" >7.68</td>
                        <td id="T_57516_row6_col18" class="data row6 col18" >8.74</td>
                        <td id="T_57516_row6_col19" class="data row6 col19" >0.83</td>
                        <td id="T_57516_row6_col20" class="data row6 col20" >-</td>
                        <td id="T_57516_row6_col21" class="data row6 col21" >492,089.84</td>
                        <td id="T_57516_row6_col22" class="data row6 col22" >2,581,413.65</td>
                        <td id="T_57516_row6_col23" class="data row6 col23" >944,821.81</td>
                        <td id="T_57516_row6_col24" class="data row6 col24" >80.94</td>
            </tr>
            <tr>
                        <th id="T_57516_level0_row7" class="row_heading level0 row7" >601128.SS</th>
                        <td id="T_57516_row7_col0" class="data row7 col0" >常熟银行</td>
                        <td id="T_57516_row7_col1" class="data row7 col1" >银行</td>
                        <td id="T_57516_row7_col2" class="data row7 col2" >0.63</td>
                        <td id="T_57516_row7_col3" class="data row7 col3" >90.84</td>
                        <td id="T_57516_row7_col4" class="data row7 col4" >0.65</td>
                        <td id="T_57516_row7_col5" class="data row7 col5" >-</td>
                        <td id="T_57516_row7_col6" class="data row7 col6" >11.06</td>
                        <td id="T_57516_row7_col7" class="data row7 col7" >36.04</td>
                        <td id="T_57516_row7_col8" class="data row7 col8" >4,393.57</td>
                        <td id="T_57516_row7_col9" class="data row7 col9" >12.82</td>
                        <td id="T_57516_row7_col10" class="data row7 col10" >5.59</td>
                        <td id="T_57516_row7_col11" class="data row7 col11" >1,584.70</td>
                        <td id="T_57516_row7_col12" class="data row7 col12" >12.89</td>
                        <td id="T_57516_row7_col13" class="data row7 col13" >10.37</td>
                        <td id="T_57516_row7_col14" class="data row7 col14" >2,259.06</td>
                        <td id="T_57516_row7_col15" class="data row7 col15" >170.81</td>
                        <td id="T_57516_row7_col16" class="data row7 col16" >457.78</td>
                        <td id="T_57516_row7_col17" class="data row7 col17" >10.40</td>
                        <td id="T_57516_row7_col18" class="data row7 col18" >11.83</td>
                        <td id="T_57516_row7_col19" class="data row7 col19" >0.92</td>
                        <td id="T_57516_row7_col20" class="data row7 col20" >-</td>
                        <td id="T_57516_row7_col21" class="data row7 col21" >18,747.48</td>
                        <td id="T_57516_row7_col22" class="data row7 col22" >505,121.49</td>
                        <td id="T_57516_row7_col23" class="data row7 col23" >28,240.00</td>
                        <td id="T_57516_row7_col24" class="data row7 col24" >96.29</td>
            </tr>
            <tr>
                        <th id="T_57516_level0_row8" class="row_heading level0 row8" >600928.SS</th>
                        <td id="T_57516_row8_col0" class="data row8 col0" >西安银行</td>
                        <td id="T_57516_row8_col1" class="data row8 col1" >银行</td>
                        <td id="T_57516_row8_col2" class="data row8 col2" >0.22</td>
                        <td id="T_57516_row8_col3" class="data row8 col3" >91.50</td>
                        <td id="T_57516_row8_col4" class="data row8 col4" >3.28</td>
                        <td id="T_57516_row8_col5" class="data row8 col5" >-</td>
                        <td id="T_57516_row8_col6" class="data row8 col6" >11.59</td>
                        <td id="T_57516_row8_col7" class="data row8 col7" >48.65</td>
                        <td id="T_57516_row8_col8" class="data row8 col8" >5,227.13</td>
                        <td id="T_57516_row8_col9" class="data row8 col9" >20.98</td>
                        <td id="T_57516_row8_col10" class="data row8 col10" >18.60</td>
                        <td id="T_57516_row8_col11" class="data row8 col11" >2,480.89</td>
                        <td id="T_57516_row8_col12" class="data row8 col12" >9.04</td>
                        <td id="T_57516_row8_col13" class="data row8 col13" >5.35</td>
                        <td id="T_57516_row8_col14" class="data row8 col14" >-1,120.64</td>
                        <td id="T_57516_row8_col15" class="data row8 col15" >-117.52</td>
                        <td id="T_57516_row8_col16" class="data row8 col16" >121.09</td>
                        <td id="T_57516_row8_col17" class="data row8 col17" >7.98</td>
                        <td id="T_57516_row8_col18" class="data row8 col18" >8.87</td>
                        <td id="T_57516_row8_col19" class="data row8 col19" >0.98</td>
                        <td id="T_57516_row8_col20" class="data row8 col20" >-</td>
                        <td id="T_57516_row8_col21" class="data row8 col21" >21,999.98</td>
                        <td id="T_57516_row8_col22" class="data row8 col22" >229.46</td>
                        <td id="T_57516_row8_col23" class="data row8 col23" >40,109.23</td>
                        <td id="T_57516_row8_col24" class="data row8 col24" >-9,487.69</td>
            </tr>
            <tr>
                        <th id="T_57516_level0_row9" class="row_heading level0 row9" >600926.SS</th>
                        <td id="T_57516_row9_col0" class="data row9 col0" >杭州银行</td>
                        <td id="T_57516_row9_col1" class="data row9 col1" >银行</td>
                        <td id="T_57516_row9_col2" class="data row9 col2" >1.37</td>
                        <td id="T_57516_row9_col3" class="data row9 col3" >93.08</td>
                        <td id="T_57516_row9_col4" class="data row9 col4" >1.08</td>
                        <td id="T_57516_row9_col5" class="data row9 col5" >-</td>
                        <td id="T_57516_row9_col6" class="data row9 col6" >11.24</td>
                        <td id="T_57516_row9_col7" class="data row9 col7" >48.22</td>
                        <td id="T_57516_row9_col8" class="data row9 col8" >12,283.02</td>
                        <td id="T_57516_row9_col9" class="data row9 col9" >15.82</td>
                        <td id="T_57516_row9_col10" class="data row9 col10" >7.40</td>
                        <td id="T_57516_row9_col11" class="data row9 col11" >5,925.26</td>
                        <td id="T_57516_row9_col12" class="data row9 col12" >16.34</td>
                        <td id="T_57516_row9_col13" class="data row9 col13" >7.30</td>
                        <td id="T_57516_row9_col14" class="data row9 col14" >34,656.90</td>
                        <td id="T_57516_row9_col15" class="data row9 col15" >41.76</td>
                        <td id="T_57516_row9_col16" class="data row9 col16" >194.69</td>
                        <td id="T_57516_row9_col17" class="data row9 col17" >14.15</td>
                        <td id="T_57516_row9_col18" class="data row9 col18" >16.37</td>
                        <td id="T_57516_row9_col19" class="data row9 col19" >1.00</td>
                        <td id="T_57516_row9_col20" class="data row9 col20" >-</td>
                        <td id="T_57516_row9_col21" class="data row9 col21" >97,018.08</td>
                        <td id="T_57516_row9_col22" class="data row9 col22" >1,178,052.67</td>
                        <td id="T_57516_row9_col23" class="data row9 col23" >114,901.02</td>
                        <td id="T_57516_row9_col24" class="data row9 col24" >91.76</td>
            </tr>
            <tr>
                        <th id="T_57516_level0_row10" class="row_heading level0 row10" >600919.SS</th>
                        <td id="T_57516_row10_col0" class="data row10 col0" >江苏银行</td>
                        <td id="T_57516_row10_col1" class="data row10 col1" >银行</td>
                        <td id="T_57516_row10_col2" class="data row10 col2" >3.08</td>
                        <td id="T_57516_row10_col3" class="data row10 col3" >93.39</td>
                        <td id="T_57516_row10_col4" class="data row10 col4" >0.84</td>
                        <td id="T_57516_row10_col5" class="data row10 col5" >-</td>
                        <td id="T_57516_row10_col6" class="data row10 col6" >12.02</td>
                        <td id="T_57516_row10_col7" class="data row10 col7" >46.07</td>
                        <td id="T_57516_row10_col8" class="data row10 col8" >32,085.45</td>
                        <td id="T_57516_row10_col9" class="data row10 col9" >34.52</td>
                        <td id="T_57516_row10_col10" class="data row10 col10" >46.74</td>
                        <td id="T_57516_row10_col11" class="data row10 col11" >13,656.14</td>
                        <td id="T_57516_row10_col12" class="data row10 col12" >8.32</td>
                        <td id="T_57516_row10_col13" class="data row10 col13" >4.65</td>
                        <td id="T_57516_row10_col14" class="data row10 col14" >-85,668.62</td>
                        <td id="T_57516_row10_col15" class="data row10 col15" >-16.35</td>
                        <td id="T_57516_row10_col16" class="data row10 col16" >18.66</td>
                        <td id="T_57516_row10_col17" class="data row10 col17" >6.94</td>
                        <td id="T_57516_row10_col18" class="data row10 col18" >8.57</td>
                        <td id="T_57516_row10_col19" class="data row10 col19" >1.03</td>
                        <td id="T_57516_row10_col20" class="data row10 col20" >-</td>
                        <td id="T_57516_row10_col21" class="data row10 col21" >116,975.24</td>
                        <td id="T_57516_row10_col22" class="data row10 col22" >-667,814.93</td>
                        <td id="T_57516_row10_col23" class="data row10 col23" >216,756.17</td>
                        <td id="T_57516_row10_col24" class="data row10 col24" >-</td>
            </tr>
            <tr>
                        <th id="T_57516_level0_row11" class="row_heading level0 row11" >002142.SZ</th>
                        <td id="T_57516_row11_col0" class="data row11 col0" >宁波银行</td>
                        <td id="T_57516_row11_col1" class="data row11 col1" >银行</td>
                        <td id="T_57516_row11_col2" class="data row11 col2" >5.60</td>
                        <td id="T_57516_row11_col3" class="data row11 col3" >92.69</td>
                        <td id="T_57516_row11_col4" class="data row11 col4" >4.58</td>
                        <td id="T_57516_row11_col5" class="data row11 col5" >-</td>
                        <td id="T_57516_row11_col6" class="data row11 col6" >16.34</td>
                        <td id="T_57516_row11_col7" class="data row11 col7" >49.03</td>
                        <td id="T_57516_row11_col8" class="data row11 col8" >25,251.48</td>
                        <td id="T_57516_row11_col9" class="data row11 col9" >19.23</td>
                        <td id="T_57516_row11_col10" class="data row11 col10" >7.17</td>
                        <td id="T_57516_row11_col11" class="data row11 col11" >12,321.23</td>
                        <td id="T_57516_row11_col12" class="data row11 col12" >17.40</td>
                        <td id="T_57516_row11_col13" class="data row11 col13" >6.78</td>
                        <td id="T_57516_row11_col14" class="data row11 col14" >15,353.54</td>
                        <td id="T_57516_row11_col15" class="data row11 col15" >-174.45</td>
                        <td id="T_57516_row11_col16" class="data row11 col16" >231.84</td>
                        <td id="T_57516_row11_col17" class="data row11 col17" >17.03</td>
                        <td id="T_57516_row11_col18" class="data row11 col18" >20.90</td>
                        <td id="T_57516_row11_col19" class="data row11 col19" >1.20</td>
                        <td id="T_57516_row11_col20" class="data row11 col20" >1.88</td>
                        <td id="T_57516_row11_col21" class="data row11 col21" >257,503.74</td>
                        <td id="T_57516_row11_col22" class="data row11 col22" >-71,858.58</td>
                        <td id="T_57516_row11_col23" class="data row11 col23" >245,093.33</td>
                        <td id="T_57516_row11_col24" class="data row11 col24" >-</td>
            </tr>
            <tr>
                        <th id="T_57516_level0_row12" class="row_heading level0 row12" >002948.SZ</th>
                        <td id="T_57516_row12_col0" class="data row12 col0" >青岛银行</td>
                        <td id="T_57516_row12_col1" class="data row12 col1" >银行</td>
                        <td id="T_57516_row12_col2" class="data row12 col2" >0.13</td>
                        <td id="T_57516_row12_col3" class="data row12 col3" >93.28</td>
                        <td id="T_57516_row12_col4" class="data row12 col4" >-</td>
                        <td id="T_57516_row12_col5" class="data row12 col5" >-</td>
                        <td id="T_57516_row12_col6" class="data row12 col6" >10.57</td>
                        <td id="T_57516_row12_col7" class="data row12 col7" >40.35</td>
                        <td id="T_57516_row12_col8" class="data row12 col8" >5,394.28</td>
                        <td id="T_57516_row12_col9" class="data row12 col9" >15.37</td>
                        <td id="T_57516_row12_col10" class="data row12 col10" >7.42</td>
                        <td id="T_57516_row12_col11" class="data row12 col11" >2,150.62</td>
                        <td id="T_57516_row12_col12" class="data row12 col12" >8.06</td>
                        <td id="T_57516_row12_col13" class="data row12 col13" >4.29</td>
                        <td id="T_57516_row12_col14" class="data row12 col14" >-27,608.33</td>
                        <td id="T_57516_row12_col15" class="data row12 col15" >16.72</td>
                        <td id="T_57516_row12_col16" class="data row12 col16" >104.19</td>
                        <td id="T_57516_row12_col17" class="data row12 col17" >11.95</td>
                        <td id="T_57516_row12_col18" class="data row12 col18" >9.77</td>
                        <td id="T_57516_row12_col19" class="data row12 col19" >1.21</td>
                        <td id="T_57516_row12_col20" class="data row12 col20" >-</td>
                        <td id="T_57516_row12_col21" class="data row12 col21" >21,004.68</td>
                        <td id="T_57516_row12_col22" class="data row12 col22" >-540,262.13</td>
                        <td id="T_57516_row12_col23" class="data row12 col23" >33,904.03</td>
                        <td id="T_57516_row12_col24" class="data row12 col24" >-</td>
            </tr>
            <tr>
                        <th id="T_57516_level0_row13" class="row_heading level0 row13" >600036.SS</th>
                        <td id="T_57516_row13_col0" class="data row13 col0" >招商银行</td>
                        <td id="T_57516_row13_col1" class="data row13 col1" >银行</td>
                        <td id="T_57516_row13_col2" class="data row13 col2" >22.26</td>
                        <td id="T_57516_row13_col3" class="data row13 col3" >91.27</td>
                        <td id="T_57516_row13_col4" class="data row13 col4" >0.15</td>
                        <td id="T_57516_row13_col5" class="data row13 col5" >1.44</td>
                        <td id="T_57516_row13_col6" class="data row13 col6" >15.46</td>
                        <td id="T_57516_row13_col7" class="data row13 col7" >43.54</td>
                        <td id="T_57516_row13_col8" class="data row13 col8" >195,736.25</td>
                        <td id="T_57516_row13_col9" class="data row13 col9" >11.97</td>
                        <td id="T_57516_row13_col10" class="data row13 col10" >4.30</td>
                        <td id="T_57516_row13_col11" class="data row13 col11" >85,229.75</td>
                        <td id="T_57516_row13_col12" class="data row13 col12" >11.65</td>
                        <td id="T_57516_row13_col13" class="data row13 col13" >5.92</td>
                        <td id="T_57516_row13_col14" class="data row13 col14" >76,865.50</td>
                        <td id="T_57516_row13_col15" class="data row13 col15" >-693.52</td>
                        <td id="T_57516_row13_col16" class="data row13 col16" >1,273.45</td>
                        <td id="T_57516_row13_col17" class="data row13 col17" >14.53</td>
                        <td id="T_57516_row13_col18" class="data row13 col18" >17.00</td>
                        <td id="T_57516_row13_col19" class="data row13 col19" >1.46</td>
                        <td id="T_57516_row13_col20" class="data row13 col20" >2.93</td>
                        <td id="T_57516_row13_col21" class="data row13 col21" >1,448,565.15</td>
                        <td id="T_57516_row13_col22" class="data row13 col22" >-171,200,164.68</td>
                        <td id="T_57516_row13_col23" class="data row13 col23" >1,472,131.36</td>
                        <td id="T_57516_row13_col24" class="data row13 col24" >-</td>
            </tr>
            <tr>
                        <th id="T_57516_level0_row14" class="row_heading level0 row14" >600015.SS</th>
                        <td id="T_57516_row14_col0" class="data row14 col0" >华夏银行</td>
                        <td id="T_57516_row14_col1" class="data row14 col1" >银行</td>
                        <td id="T_57516_row14_col2" class="data row14 col2" >1.24</td>
                        <td id="T_57516_row14_col3" class="data row14 col3" >91.08</td>
                        <td id="T_57516_row14_col4" class="data row14 col4" >11.77</td>
                        <td id="T_57516_row14_col5" class="data row14 col5" >-</td>
                        <td id="T_57516_row14_col6" class="data row14 col6" >10.30</td>
                        <td id="T_57516_row14_col7" class="data row14 col7" >35.99</td>
                        <td id="T_57516_row14_col8" class="data row14 col8" >62,424.25</td>
                        <td id="T_57516_row14_col9" class="data row14 col9" >28.76</td>
                        <td id="T_57516_row14_col10" class="data row14 col10" >40.00</td>
                        <td id="T_57516_row14_col11" class="data row14 col11" >20,963.25</td>
                        <td id="T_57516_row14_col12" class="data row14 col12" >2.46</td>
                        <td id="T_57516_row14_col13" class="data row14 col13" >4.62</td>
                        <td id="T_57516_row14_col14" class="data row14 col14" >-38,383.00</td>
                        <td id="T_57516_row14_col15" class="data row14 col15" >-54.10</td>
                        <td id="T_57516_row14_col16" class="data row14 col16" >105.75</td>
                        <td id="T_57516_row14_col17" class="data row14 col17" >5.41</td>
                        <td id="T_57516_row14_col18" class="data row14 col18" >4.67</td>
                        <td id="T_57516_row14_col19" class="data row14 col19" >1.90</td>
                        <td id="T_57516_row14_col20" class="data row14 col20" >2.67</td>
                        <td id="T_57516_row14_col21" class="data row14 col21" >97,862.59</td>
                        <td id="T_57516_row14_col22" class="data row14 col22" >-65,102.76</td>
                        <td id="T_57516_row14_col23" class="data row14 col23" >284,952.10</td>
                        <td id="T_57516_row14_col24" class="data row14 col24" >-</td>
            </tr>
            <tr>
                        <th id="T_57516_level0_row15" class="row_heading level0 row15" >002961.SZ</th>
                        <td id="T_57516_row15_col0" class="data row15 col0" >瑞达期货</td>
                        <td id="T_57516_row15_col1" class="data row15 col1" >非银金融</td>
                        <td id="T_57516_row15_col2" class="data row15 col2" >0.07</td>
                        <td id="T_57516_row15_col3" class="data row15 col3" >82.51</td>
                        <td id="T_57516_row15_col4" class="data row15 col4" >1.21</td>
                        <td id="T_57516_row15_col5" class="data row15 col5" >0.28</td>
                        <td id="T_57516_row15_col6" class="data row15 col6" >10.05</td>
                        <td id="T_57516_row15_col7" class="data row15 col7" >21.88</td>
                        <td id="T_57516_row15_col8" class="data row15 col8" >813.77</td>
                        <td id="T_57516_row15_col9" class="data row15 col9" >45.82</td>
                        <td id="T_57516_row15_col10" class="data row15 col10" >57.73</td>
                        <td id="T_57516_row15_col11" class="data row15 col11" >160.82</td>
                        <td id="T_57516_row15_col12" class="data row15 col12" >27.83</td>
                        <td id="T_57516_row15_col13" class="data row15 col13" >69.67</td>
                        <td id="T_57516_row15_col14" class="data row15 col14" >-649.82</td>
                        <td id="T_57516_row15_col15" class="data row15 col15" >-19.07</td>
                        <td id="T_57516_row15_col16" class="data row15 col16" >106.19</td>
                        <td id="T_57516_row15_col17" class="data row15 col17" >37.04</td>
                        <td id="T_57516_row15_col18" class="data row15 col18" >57.39</td>
                        <td id="T_57516_row15_col19" class="data row15 col19" >2.06</td>
                        <td id="T_57516_row15_col20" class="data row15 col20" >-</td>
                        <td id="T_57516_row15_col21" class="data row15 col21" >9,229.42</td>
                        <td id="T_57516_row15_col22" class="data row15 col22" >-4,633.55</td>
                        <td id="T_57516_row15_col23" class="data row15 col23" >4,070.08</td>
                        <td id="T_57516_row15_col24" class="data row15 col24" >-</td>
            </tr>
            <tr>
                        <th id="T_57516_level0_row16" class="row_heading level0 row16" >000001.SZ</th>
                        <td id="T_57516_row16_col0" class="data row16 col0" >平安银行</td>
                        <td id="T_57516_row16_col1" class="data row16 col1" >银行</td>
                        <td id="T_57516_row16_col2" class="data row16 col2" >8.42</td>
                        <td id="T_57516_row16_col3" class="data row16 col3" >91.85</td>
                        <td id="T_57516_row16_col4" class="data row16 col4" >2.89</td>
                        <td id="T_57516_row16_col5" class="data row16 col5" >2.20</td>
                        <td id="T_57516_row16_col6" class="data row16 col6" >10.19</td>
                        <td id="T_57516_row16_col7" class="data row16 col7" >35.71</td>
                        <td id="T_57516_row16_col8" class="data row16 col8" >73,795.25</td>
                        <td id="T_57516_row16_col9" class="data row16 col9" >10.19</td>
                        <td id="T_57516_row16_col10" class="data row16 col10" >4.91</td>
                        <td id="T_57516_row16_col11" class="data row16 col11" >26,282.50</td>
                        <td id="T_57516_row16_col12" class="data row16 col12" >7.74</td>
                        <td id="T_57516_row16_col13" class="data row16 col13" >5.54</td>
                        <td id="T_57516_row16_col14" class="data row16 col14" >-61,692.00</td>
                        <td id="T_57516_row16_col15" class="data row16 col15" >-44.54</td>
                        <td id="T_57516_row16_col16" class="data row16 col16" >13.22</td>
                        <td id="T_57516_row16_col17" class="data row16 col17" >17.15</td>
                        <td id="T_57516_row16_col18" class="data row16 col18" >18.12</td>
                        <td id="T_57516_row16_col19" class="data row16 col19" >2.34</td>
                        <td id="T_57516_row16_col20" class="data row16 col20" >-</td>
                        <td id="T_57516_row16_col21" class="data row16 col21" >476,220.78</td>
                        <td id="T_57516_row16_col22" class="data row16 col22" >-165,249.78</td>
                        <td id="T_57516_row16_col23" class="data row16 col23" >410,951.71</td>
                        <td id="T_57516_row16_col24" class="data row16 col24" >-</td>
            </tr>
    </tbody></table>



### 观察列表






<style  type="text/css" >
#T_13f52_row0_col0,#T_13f52_row0_col1,#T_13f52_row0_col2,#T_13f52_row0_col3,#T_13f52_row0_col4,#T_13f52_row0_col5,#T_13f52_row0_col6,#T_13f52_row0_col7,#T_13f52_row0_col8,#T_13f52_row0_col9,#T_13f52_row0_col10,#T_13f52_row0_col11,#T_13f52_row0_col12,#T_13f52_row0_col13,#T_13f52_row0_col14,#T_13f52_row0_col15,#T_13f52_row0_col16,#T_13f52_row0_col17,#T_13f52_row0_col18,#T_13f52_row0_col19,#T_13f52_row0_col20,#T_13f52_row0_col21,#T_13f52_row0_col22,#T_13f52_row0_col23,#T_13f52_row0_col24,#T_13f52_row1_col0,#T_13f52_row1_col1,#T_13f52_row1_col2,#T_13f52_row1_col3,#T_13f52_row1_col4,#T_13f52_row1_col5,#T_13f52_row1_col6,#T_13f52_row1_col7,#T_13f52_row1_col8,#T_13f52_row1_col9,#T_13f52_row1_col10,#T_13f52_row1_col11,#T_13f52_row1_col12,#T_13f52_row1_col13,#T_13f52_row1_col14,#T_13f52_row1_col15,#T_13f52_row1_col16,#T_13f52_row1_col17,#T_13f52_row1_col18,#T_13f52_row1_col19,#T_13f52_row1_col20,#T_13f52_row1_col21,#T_13f52_row1_col22,#T_13f52_row1_col23,#T_13f52_row2_col0,#T_13f52_row2_col1,#T_13f52_row2_col2,#T_13f52_row2_col3,#T_13f52_row2_col4,#T_13f52_row2_col5,#T_13f52_row2_col6,#T_13f52_row2_col7,#T_13f52_row2_col8,#T_13f52_row2_col9,#T_13f52_row2_col10,#T_13f52_row2_col11,#T_13f52_row2_col12,#T_13f52_row2_col13,#T_13f52_row2_col14,#T_13f52_row2_col15,#T_13f52_row2_col16,#T_13f52_row2_col17,#T_13f52_row2_col18,#T_13f52_row2_col19,#T_13f52_row2_col20,#T_13f52_row2_col21,#T_13f52_row2_col22,#T_13f52_row2_col23,#T_13f52_row2_col24,#T_13f52_row3_col0,#T_13f52_row3_col1,#T_13f52_row3_col2,#T_13f52_row3_col3,#T_13f52_row3_col4,#T_13f52_row3_col5,#T_13f52_row3_col6,#T_13f52_row3_col7,#T_13f52_row3_col8,#T_13f52_row3_col9,#T_13f52_row3_col10,#T_13f52_row3_col11,#T_13f52_row3_col12,#T_13f52_row3_col13,#T_13f52_row3_col14,#T_13f52_row3_col15,#T_13f52_row3_col16,#T_13f52_row3_col17,#T_13f52_row3_col18,#T_13f52_row3_col19,#T_13f52_row3_col20,#T_13f52_row3_col21,#T_13f52_row3_col22,#T_13f52_row3_col23,#T_13f52_row3_col24,#T_13f52_row4_col0,#T_13f52_row4_col1,#T_13f52_row4_col2,#T_13f52_row4_col3,#T_13f52_row4_col4,#T_13f52_row4_col5,#T_13f52_row4_col6,#T_13f52_row4_col7,#T_13f52_row4_col8,#T_13f52_row4_col9,#T_13f52_row4_col10,#T_13f52_row4_col11,#T_13f52_row4_col12,#T_13f52_row4_col13,#T_13f52_row4_col14,#T_13f52_row4_col15,#T_13f52_row4_col16,#T_13f52_row4_col17,#T_13f52_row4_col18,#T_13f52_row4_col19,#T_13f52_row4_col20,#T_13f52_row4_col21,#T_13f52_row4_col22,#T_13f52_row4_col23,#T_13f52_row4_col24,#T_13f52_row5_col0,#T_13f52_row5_col1,#T_13f52_row5_col2,#T_13f52_row5_col3,#T_13f52_row5_col4,#T_13f52_row5_col5,#T_13f52_row5_col6,#T_13f52_row5_col7,#T_13f52_row5_col8,#T_13f52_row5_col9,#T_13f52_row5_col10,#T_13f52_row5_col11,#T_13f52_row5_col12,#T_13f52_row5_col13,#T_13f52_row5_col14,#T_13f52_row5_col16,#T_13f52_row5_col17,#T_13f52_row5_col18,#T_13f52_row5_col19,#T_13f52_row5_col20,#T_13f52_row5_col21,#T_13f52_row5_col23,#T_13f52_row5_col24,#T_13f52_row6_col0,#T_13f52_row6_col1,#T_13f52_row6_col2,#T_13f52_row6_col3,#T_13f52_row6_col4,#T_13f52_row6_col5,#T_13f52_row6_col6,#T_13f52_row6_col7,#T_13f52_row6_col8,#T_13f52_row6_col9,#T_13f52_row6_col10,#T_13f52_row6_col11,#T_13f52_row6_col12,#T_13f52_row6_col13,#T_13f52_row6_col14,#T_13f52_row6_col15,#T_13f52_row6_col16,#T_13f52_row6_col17,#T_13f52_row6_col18,#T_13f52_row6_col19,#T_13f52_row6_col20,#T_13f52_row6_col21,#T_13f52_row6_col22,#T_13f52_row6_col23,#T_13f52_row7_col0,#T_13f52_row7_col1,#T_13f52_row7_col2,#T_13f52_row7_col3,#T_13f52_row7_col4,#T_13f52_row7_col5,#T_13f52_row7_col6,#T_13f52_row7_col7,#T_13f52_row7_col8,#T_13f52_row7_col9,#T_13f52_row7_col10,#T_13f52_row7_col11,#T_13f52_row7_col12,#T_13f52_row7_col13,#T_13f52_row7_col14,#T_13f52_row7_col16,#T_13f52_row7_col17,#T_13f52_row7_col18,#T_13f52_row7_col19,#T_13f52_row7_col20,#T_13f52_row7_col21,#T_13f52_row7_col22,#T_13f52_row7_col23,#T_13f52_row8_col0,#T_13f52_row8_col1,#T_13f52_row8_col2,#T_13f52_row8_col3,#T_13f52_row8_col4,#T_13f52_row8_col5,#T_13f52_row8_col6,#T_13f52_row8_col7,#T_13f52_row8_col8,#T_13f52_row8_col9,#T_13f52_row8_col10,#T_13f52_row8_col11,#T_13f52_row8_col12,#T_13f52_row8_col13,#T_13f52_row8_col16,#T_13f52_row8_col17,#T_13f52_row8_col18,#T_13f52_row8_col19,#T_13f52_row8_col20,#T_13f52_row8_col21,#T_13f52_row8_col22,#T_13f52_row8_col23,#T_13f52_row9_col0,#T_13f52_row9_col1,#T_13f52_row9_col2,#T_13f52_row9_col3,#T_13f52_row9_col4,#T_13f52_row9_col5,#T_13f52_row9_col6,#T_13f52_row9_col7,#T_13f52_row9_col8,#T_13f52_row9_col9,#T_13f52_row9_col10,#T_13f52_row9_col11,#T_13f52_row9_col12,#T_13f52_row9_col13,#T_13f52_row9_col14,#T_13f52_row9_col15,#T_13f52_row9_col16,#T_13f52_row9_col17,#T_13f52_row9_col18,#T_13f52_row9_col19,#T_13f52_row9_col20,#T_13f52_row9_col21,#T_13f52_row9_col22,#T_13f52_row9_col23,#T_13f52_row9_col24,#T_13f52_row10_col0,#T_13f52_row10_col1,#T_13f52_row10_col2,#T_13f52_row10_col3,#T_13f52_row10_col4,#T_13f52_row10_col5,#T_13f52_row10_col6,#T_13f52_row10_col7,#T_13f52_row10_col8,#T_13f52_row10_col9,#T_13f52_row10_col10,#T_13f52_row10_col11,#T_13f52_row10_col12,#T_13f52_row10_col13,#T_13f52_row10_col14,#T_13f52_row10_col15,#T_13f52_row10_col16,#T_13f52_row10_col17,#T_13f52_row10_col18,#T_13f52_row10_col19,#T_13f52_row10_col20,#T_13f52_row10_col21,#T_13f52_row10_col22,#T_13f52_row10_col23,#T_13f52_row11_col0,#T_13f52_row11_col1,#T_13f52_row11_col2,#T_13f52_row11_col3,#T_13f52_row11_col4,#T_13f52_row11_col5,#T_13f52_row11_col6,#T_13f52_row11_col7,#T_13f52_row11_col8,#T_13f52_row11_col9,#T_13f52_row11_col10,#T_13f52_row11_col11,#T_13f52_row11_col12,#T_13f52_row11_col13,#T_13f52_row11_col14,#T_13f52_row11_col15,#T_13f52_row11_col16,#T_13f52_row11_col17,#T_13f52_row11_col18,#T_13f52_row11_col19,#T_13f52_row11_col20,#T_13f52_row11_col21,#T_13f52_row11_col22,#T_13f52_row11_col23,#T_13f52_row11_col24,#T_13f52_row12_col0,#T_13f52_row12_col1,#T_13f52_row12_col2,#T_13f52_row12_col3,#T_13f52_row12_col4,#T_13f52_row12_col5,#T_13f52_row12_col6,#T_13f52_row12_col7,#T_13f52_row12_col8,#T_13f52_row12_col9,#T_13f52_row12_col10,#T_13f52_row12_col11,#T_13f52_row12_col12,#T_13f52_row12_col13,#T_13f52_row12_col16,#T_13f52_row12_col17,#T_13f52_row12_col18,#T_13f52_row12_col19,#T_13f52_row12_col20,#T_13f52_row12_col21,#T_13f52_row12_col23,#T_13f52_row12_col24,#T_13f52_row13_col0,#T_13f52_row13_col1,#T_13f52_row13_col2,#T_13f52_row13_col3,#T_13f52_row13_col4,#T_13f52_row13_col5,#T_13f52_row13_col6,#T_13f52_row13_col7,#T_13f52_row13_col8,#T_13f52_row13_col9,#T_13f52_row13_col10,#T_13f52_row13_col11,#T_13f52_row13_col12,#T_13f52_row13_col13,#T_13f52_row13_col16,#T_13f52_row13_col17,#T_13f52_row13_col18,#T_13f52_row13_col19,#T_13f52_row13_col20,#T_13f52_row13_col21,#T_13f52_row13_col23,#T_13f52_row13_col24,#T_13f52_row14_col0,#T_13f52_row14_col1,#T_13f52_row14_col2,#T_13f52_row14_col3,#T_13f52_row14_col4,#T_13f52_row14_col5,#T_13f52_row14_col6,#T_13f52_row14_col7,#T_13f52_row14_col8,#T_13f52_row14_col9,#T_13f52_row14_col10,#T_13f52_row14_col11,#T_13f52_row14_col12,#T_13f52_row14_col13,#T_13f52_row14_col14,#T_13f52_row14_col15,#T_13f52_row14_col16,#T_13f52_row14_col17,#T_13f52_row14_col18,#T_13f52_row14_col19,#T_13f52_row14_col20,#T_13f52_row14_col21,#T_13f52_row14_col22,#T_13f52_row14_col23,#T_13f52_row15_col0,#T_13f52_row15_col1,#T_13f52_row15_col2,#T_13f52_row15_col3,#T_13f52_row15_col4,#T_13f52_row15_col5,#T_13f52_row15_col6,#T_13f52_row15_col7,#T_13f52_row15_col8,#T_13f52_row15_col9,#T_13f52_row15_col10,#T_13f52_row15_col11,#T_13f52_row15_col12,#T_13f52_row15_col13,#T_13f52_row15_col14,#T_13f52_row15_col16,#T_13f52_row15_col17,#T_13f52_row15_col18,#T_13f52_row15_col19,#T_13f52_row15_col20,#T_13f52_row15_col21,#T_13f52_row15_col23,#T_13f52_row15_col24,#T_13f52_row16_col0,#T_13f52_row16_col1,#T_13f52_row16_col2,#T_13f52_row16_col3,#T_13f52_row16_col4,#T_13f52_row16_col5,#T_13f52_row16_col6,#T_13f52_row16_col7,#T_13f52_row16_col8,#T_13f52_row16_col9,#T_13f52_row16_col10,#T_13f52_row16_col11,#T_13f52_row16_col12,#T_13f52_row16_col13,#T_13f52_row16_col14,#T_13f52_row16_col15,#T_13f52_row16_col16,#T_13f52_row16_col17,#T_13f52_row16_col18,#T_13f52_row16_col19,#T_13f52_row16_col20,#T_13f52_row16_col21,#T_13f52_row16_col22,#T_13f52_row16_col23,#T_13f52_row17_col0,#T_13f52_row17_col1,#T_13f52_row17_col2,#T_13f52_row17_col3,#T_13f52_row17_col4,#T_13f52_row17_col5,#T_13f52_row17_col6,#T_13f52_row17_col7,#T_13f52_row17_col8,#T_13f52_row17_col9,#T_13f52_row17_col10,#T_13f52_row17_col11,#T_13f52_row17_col12,#T_13f52_row17_col13,#T_13f52_row17_col14,#T_13f52_row17_col15,#T_13f52_row17_col16,#T_13f52_row17_col17,#T_13f52_row17_col18,#T_13f52_row17_col19,#T_13f52_row17_col20,#T_13f52_row17_col21,#T_13f52_row17_col22,#T_13f52_row17_col23,#T_13f52_row17_col24,#T_13f52_row18_col0,#T_13f52_row18_col1,#T_13f52_row18_col2,#T_13f52_row18_col3,#T_13f52_row18_col4,#T_13f52_row18_col5,#T_13f52_row18_col6,#T_13f52_row18_col7,#T_13f52_row18_col8,#T_13f52_row18_col9,#T_13f52_row18_col10,#T_13f52_row18_col11,#T_13f52_row18_col12,#T_13f52_row18_col13,#T_13f52_row18_col14,#T_13f52_row18_col15,#T_13f52_row18_col16,#T_13f52_row18_col17,#T_13f52_row18_col18,#T_13f52_row18_col19,#T_13f52_row18_col20,#T_13f52_row18_col21,#T_13f52_row18_col22,#T_13f52_row18_col23,#T_13f52_row19_col0,#T_13f52_row19_col1,#T_13f52_row19_col2,#T_13f52_row19_col3,#T_13f52_row19_col4,#T_13f52_row19_col5,#T_13f52_row19_col6,#T_13f52_row19_col7,#T_13f52_row19_col8,#T_13f52_row19_col9,#T_13f52_row19_col10,#T_13f52_row19_col11,#T_13f52_row19_col12,#T_13f52_row19_col13,#T_13f52_row19_col14,#T_13f52_row19_col15,#T_13f52_row19_col16,#T_13f52_row19_col17,#T_13f52_row19_col18,#T_13f52_row19_col19,#T_13f52_row19_col20,#T_13f52_row19_col21,#T_13f52_row19_col22,#T_13f52_row19_col23,#T_13f52_row20_col0,#T_13f52_row20_col1,#T_13f52_row20_col2,#T_13f52_row20_col3,#T_13f52_row20_col4,#T_13f52_row20_col5,#T_13f52_row20_col6,#T_13f52_row20_col7,#T_13f52_row20_col8,#T_13f52_row20_col9,#T_13f52_row20_col10,#T_13f52_row20_col11,#T_13f52_row20_col12,#T_13f52_row20_col13,#T_13f52_row20_col14,#T_13f52_row20_col15,#T_13f52_row20_col16,#T_13f52_row20_col17,#T_13f52_row20_col18,#T_13f52_row20_col19,#T_13f52_row20_col20,#T_13f52_row20_col21,#T_13f52_row20_col22,#T_13f52_row20_col23,#T_13f52_row21_col0,#T_13f52_row21_col1,#T_13f52_row21_col2,#T_13f52_row21_col3,#T_13f52_row21_col4,#T_13f52_row21_col5,#T_13f52_row21_col6,#T_13f52_row21_col7,#T_13f52_row21_col8,#T_13f52_row21_col9,#T_13f52_row21_col10,#T_13f52_row21_col11,#T_13f52_row21_col12,#T_13f52_row21_col13,#T_13f52_row21_col14,#T_13f52_row21_col15,#T_13f52_row21_col16,#T_13f52_row21_col17,#T_13f52_row21_col18,#T_13f52_row21_col19,#T_13f52_row21_col20,#T_13f52_row21_col21,#T_13f52_row21_col22,#T_13f52_row21_col23,#T_13f52_row22_col0,#T_13f52_row22_col1,#T_13f52_row22_col2,#T_13f52_row22_col3,#T_13f52_row22_col4,#T_13f52_row22_col5,#T_13f52_row22_col6,#T_13f52_row22_col7,#T_13f52_row22_col8,#T_13f52_row22_col9,#T_13f52_row22_col10,#T_13f52_row22_col11,#T_13f52_row22_col12,#T_13f52_row22_col13,#T_13f52_row22_col14,#T_13f52_row22_col15,#T_13f52_row22_col16,#T_13f52_row22_col17,#T_13f52_row22_col18,#T_13f52_row22_col19,#T_13f52_row22_col20,#T_13f52_row22_col21,#T_13f52_row22_col22,#T_13f52_row22_col23,#T_13f52_row23_col0,#T_13f52_row23_col1,#T_13f52_row23_col2,#T_13f52_row23_col3,#T_13f52_row23_col4,#T_13f52_row23_col5,#T_13f52_row23_col6,#T_13f52_row23_col7,#T_13f52_row23_col8,#T_13f52_row23_col9,#T_13f52_row23_col10,#T_13f52_row23_col11,#T_13f52_row23_col12,#T_13f52_row23_col13,#T_13f52_row23_col14,#T_13f52_row23_col16,#T_13f52_row23_col17,#T_13f52_row23_col18,#T_13f52_row23_col19,#T_13f52_row23_col20,#T_13f52_row23_col21,#T_13f52_row23_col23,#T_13f52_row23_col24,#T_13f52_row24_col0,#T_13f52_row24_col1,#T_13f52_row24_col2,#T_13f52_row24_col3,#T_13f52_row24_col4,#T_13f52_row24_col5,#T_13f52_row24_col6,#T_13f52_row24_col7,#T_13f52_row24_col8,#T_13f52_row24_col9,#T_13f52_row24_col10,#T_13f52_row24_col11,#T_13f52_row24_col12,#T_13f52_row24_col13,#T_13f52_row24_col14,#T_13f52_row24_col16,#T_13f52_row24_col17,#T_13f52_row24_col18,#T_13f52_row24_col19,#T_13f52_row24_col20,#T_13f52_row24_col21,#T_13f52_row24_col23,#T_13f52_row24_col24,#T_13f52_row25_col0,#T_13f52_row25_col1,#T_13f52_row25_col2,#T_13f52_row25_col3,#T_13f52_row25_col4,#T_13f52_row25_col5,#T_13f52_row25_col6,#T_13f52_row25_col7,#T_13f52_row25_col8,#T_13f52_row25_col9,#T_13f52_row25_col10,#T_13f52_row25_col11,#T_13f52_row25_col12,#T_13f52_row25_col13,#T_13f52_row25_col14,#T_13f52_row25_col16,#T_13f52_row25_col17,#T_13f52_row25_col18,#T_13f52_row25_col19,#T_13f52_row25_col20,#T_13f52_row25_col21,#T_13f52_row25_col22,#T_13f52_row25_col23,#T_13f52_row26_col0,#T_13f52_row26_col1,#T_13f52_row26_col2,#T_13f52_row26_col3,#T_13f52_row26_col4,#T_13f52_row26_col5,#T_13f52_row26_col6,#T_13f52_row26_col7,#T_13f52_row26_col8,#T_13f52_row26_col9,#T_13f52_row26_col10,#T_13f52_row26_col11,#T_13f52_row26_col12,#T_13f52_row26_col13,#T_13f52_row26_col14,#T_13f52_row26_col15,#T_13f52_row26_col16,#T_13f52_row26_col17,#T_13f52_row26_col18,#T_13f52_row26_col19,#T_13f52_row26_col20,#T_13f52_row26_col21,#T_13f52_row26_col22,#T_13f52_row26_col23,#T_13f52_row27_col0,#T_13f52_row27_col1,#T_13f52_row27_col2,#T_13f52_row27_col3,#T_13f52_row27_col4,#T_13f52_row27_col5,#T_13f52_row27_col6,#T_13f52_row27_col7,#T_13f52_row27_col8,#T_13f52_row27_col9,#T_13f52_row27_col10,#T_13f52_row27_col11,#T_13f52_row27_col13,#T_13f52_row27_col15,#T_13f52_row27_col16,#T_13f52_row27_col17,#T_13f52_row27_col18,#T_13f52_row27_col19,#T_13f52_row27_col20,#T_13f52_row27_col21,#T_13f52_row27_col23,#T_13f52_row27_col24,#T_13f52_row28_col0,#T_13f52_row28_col1,#T_13f52_row28_col2,#T_13f52_row28_col3,#T_13f52_row28_col4,#T_13f52_row28_col5,#T_13f52_row28_col6,#T_13f52_row28_col7,#T_13f52_row28_col8,#T_13f52_row28_col9,#T_13f52_row28_col10,#T_13f52_row28_col11,#T_13f52_row28_col13,#T_13f52_row28_col16,#T_13f52_row28_col17,#T_13f52_row28_col18,#T_13f52_row28_col19,#T_13f52_row28_col20,#T_13f52_row28_col21,#T_13f52_row28_col22,#T_13f52_row28_col24,#T_13f52_row29_col0,#T_13f52_row29_col1,#T_13f52_row29_col2,#T_13f52_row29_col3,#T_13f52_row29_col4,#T_13f52_row29_col5,#T_13f52_row29_col6,#T_13f52_row29_col7,#T_13f52_row29_col8,#T_13f52_row29_col10,#T_13f52_row29_col11,#T_13f52_row29_col13,#T_13f52_row29_col14,#T_13f52_row29_col16,#T_13f52_row29_col17,#T_13f52_row29_col18,#T_13f52_row29_col19,#T_13f52_row29_col20,#T_13f52_row29_col21,#T_13f52_row29_col22,#T_13f52_row29_col23{
            color:  black;
        }#T_13f52_row1_col24,#T_13f52_row5_col15,#T_13f52_row5_col22,#T_13f52_row6_col24,#T_13f52_row7_col15,#T_13f52_row7_col24,#T_13f52_row8_col14,#T_13f52_row8_col15,#T_13f52_row8_col24,#T_13f52_row10_col24,#T_13f52_row12_col14,#T_13f52_row12_col15,#T_13f52_row12_col22,#T_13f52_row13_col14,#T_13f52_row13_col15,#T_13f52_row13_col22,#T_13f52_row14_col24,#T_13f52_row15_col15,#T_13f52_row15_col22,#T_13f52_row16_col24,#T_13f52_row18_col24,#T_13f52_row19_col24,#T_13f52_row20_col24,#T_13f52_row21_col24,#T_13f52_row22_col24,#T_13f52_row23_col15,#T_13f52_row23_col22,#T_13f52_row24_col15,#T_13f52_row24_col22,#T_13f52_row25_col15,#T_13f52_row25_col24,#T_13f52_row26_col24,#T_13f52_row27_col12,#T_13f52_row27_col14,#T_13f52_row27_col22,#T_13f52_row28_col12,#T_13f52_row28_col14,#T_13f52_row28_col15,#T_13f52_row28_col23,#T_13f52_row29_col9,#T_13f52_row29_col12,#T_13f52_row29_col15,#T_13f52_row29_col24{
            color:  red;
        }</style><table id="T_13f52_" ><thead>    <tr>        <th class="blank level0" ></th>        <th class="col_heading level0 col0" >名称</th>        <th class="col_heading level0 col1" >行业</th>        <th class="col_heading level0 col2" >权重</th>        <th class="col_heading level0 col3" >负债率</th>        <th class="col_heading level0 col4" >应收比</th>        <th class="col_heading level0 col5" >商誉比</th>        <th class="col_heading level0 col6" >ROE</th>        <th class="col_heading level0 col7" >利润率</th>        <th class="col_heading level0 col8" >收入</th>        <th class="col_heading level0 col9" >收入增长</th>        <th class="col_heading level0 col10" >收入波动</th>        <th class="col_heading level0 col11" >盈利</th>        <th class="col_heading level0 col12" >盈利增长</th>        <th class="col_heading level0 col13" >盈利波动</th>        <th class="col_heading level0 col14" >FCF</th>        <th class="col_heading level0 col15" >FCF增长</th>        <th class="col_heading level0 col16" >FCF波动</th>        <th class="col_heading level0 col17" >PE</th>        <th class="col_heading level0 col18" >PE0</th>        <th class="col_heading level0 col19" >PEG</th>        <th class="col_heading level0 col20" >股息率</th>        <th class="col_heading level0 col21" >市值</th>        <th class="col_heading level0 col22" >DCF</th>        <th class="col_heading level0 col23" >盈利折现</th>        <th class="col_heading level0 col24" >折价率</th>    </tr>    <tr>        <th class="index_name level0" >Symbol</th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>    </tr></thead><tbody>
                <tr>
                        <th id="T_13f52_level0_row0" class="row_heading level0 row0" >600585.SS</th>
                        <td id="T_13f52_row0_col0" class="data row0 col0" >海螺水泥</td>
                        <td id="T_13f52_row0_col1" class="data row0 col1" >建筑材料</td>
                        <td id="T_13f52_row0_col2" class="data row0 col2" >19.89</td>
                        <td id="T_13f52_row0_col3" class="data row0 col3" >16.30</td>
                        <td id="T_13f52_row0_col4" class="data row0 col4" >7.17</td>
                        <td id="T_13f52_row0_col5" class="data row0 col5" >0.36</td>
                        <td id="T_13f52_row0_col6" class="data row0 col6" >22.59</td>
                        <td id="T_13f52_row0_col7" class="data row0 col7" >21.40</td>
                        <td id="T_13f52_row0_col8" class="data row0 col8" >134,246.61</td>
                        <td id="T_13f52_row0_col9" class="data row0 col9" >35.01</td>
                        <td id="T_13f52_row0_col10" class="data row0 col10" >31.14</td>
                        <td id="T_13f52_row0_col11" class="data row0 col11" >28,597.85</td>
                        <td id="T_13f52_row0_col12" class="data row0 col12" >35.10</td>
                        <td id="T_13f52_row0_col13" class="data row0 col13" >46.03</td>
                        <td id="T_13f52_row0_col14" class="data row0 col14" >25,427.11</td>
                        <td id="T_13f52_row0_col15" class="data row0 col15" >36.04</td>
                        <td id="T_13f52_row0_col16" class="data row0 col16" >80.90</td>
                        <td id="T_13f52_row0_col17" class="data row0 col17" >7.10</td>
                        <td id="T_13f52_row0_col18" class="data row0 col18" >8.49</td>
                        <td id="T_13f52_row0_col19" class="data row0 col19" >0.24</td>
                        <td id="T_13f52_row0_col20" class="data row0 col20" >2.98</td>
                        <td id="T_13f52_row0_col21" class="data row0 col21" >242,666.86</td>
                        <td id="T_13f52_row0_col22" class="data row0 col22" >768,241.81</td>
                        <td id="T_13f52_row0_col23" class="data row0 col23" >847,141.73</td>
                        <td id="T_13f52_row0_col24" class="data row0 col24" >68.41</td>
            </tr>
            <tr>
                        <th id="T_13f52_level0_row1" class="row_heading level0 row1" >600489.SS</th>
                        <td id="T_13f52_row1_col0" class="data row1 col0" >中金黄金</td>
                        <td id="T_13f52_row1_col1" class="data row1 col1" >有色金属</td>
                        <td id="T_13f52_row1_col2" class="data row1 col2" >1.70</td>
                        <td id="T_13f52_row1_col3" class="data row1 col3" >44.27</td>
                        <td id="T_13f52_row1_col4" class="data row1 col4" >1.66</td>
                        <td id="T_13f52_row1_col5" class="data row1 col5" >3.12</td>
                        <td id="T_13f52_row1_col6" class="data row1 col6" >2.88</td>
                        <td id="T_13f52_row1_col7" class="data row1 col7" >1.29</td>
                        <td id="T_13f52_row1_col8" class="data row1 col8" >38,584.85</td>
                        <td id="T_13f52_row1_col9" class="data row1 col9" >13.63</td>
                        <td id="T_13f52_row1_col10" class="data row1 col10" >9.29</td>
                        <td id="T_13f52_row1_col11" class="data row1 col11" >554.33</td>
                        <td id="T_13f52_row1_col12" class="data row1 col12" >242.86</td>
                        <td id="T_13f52_row1_col13" class="data row1 col13" >456.40</td>
                        <td id="T_13f52_row1_col14" class="data row1 col14" >976.04</td>
                        <td id="T_13f52_row1_col15" class="data row1 col15" >33.70</td>
                        <td id="T_13f52_row1_col16" class="data row1 col16" >333.14</td>
                        <td id="T_13f52_row1_col17" class="data row1 col17" >27.32</td>
                        <td id="T_13f52_row1_col18" class="data row1 col18" >81.24</td>
                        <td id="T_13f52_row1_col19" class="data row1 col19" >0.33</td>
                        <td id="T_13f52_row1_col20" class="data row1 col20" >-</td>
                        <td id="T_13f52_row1_col21" class="data row1 col21" >45,031.51</td>
                        <td id="T_13f52_row1_col22" class="data row1 col22" >28,067.23</td>
                        <td id="T_13f52_row1_col23" class="data row1 col23" >248,781.76</td>
                        <td id="T_13f52_row1_col24" class="data row1 col24" >-60.44</td>
            </tr>
            <tr>
                        <th id="T_13f52_level0_row2" class="row_heading level0 row2" >601318.SS</th>
                        <td id="T_13f52_row2_col0" class="data row2 col0" >中国平安</td>
                        <td id="T_13f52_row2_col1" class="data row2 col1" >非银金融</td>
                        <td id="T_13f52_row2_col2" class="data row2 col2" >28.50</td>
                        <td id="T_13f52_row2_col3" class="data row2 col3" >89.63</td>
                        <td id="T_13f52_row2_col4" class="data row2 col4" >36.19</td>
                        <td id="T_13f52_row2_col5" class="data row2 col5" >3.02</td>
                        <td id="T_13f52_row2_col6" class="data row2 col6" >19.77</td>
                        <td id="T_13f52_row2_col7" class="data row2 col7" >10.76</td>
                        <td id="T_13f52_row2_col8" class="data row2 col8" >1,124,557.50</td>
                        <td id="T_13f52_row2_col9" class="data row2 col9" >8.44</td>
                        <td id="T_13f52_row2_col10" class="data row2 col10" >5.08</td>
                        <td id="T_13f52_row2_col11" class="data row2 col11" >122,249.50</td>
                        <td id="T_13f52_row2_col12" class="data row2 col12" >18.48</td>
                        <td id="T_13f52_row2_col13" class="data row2 col13" >21.74</td>
                        <td id="T_13f52_row2_col14" class="data row2 col14" >148,811.50</td>
                        <td id="T_13f52_row2_col15" class="data row2 col15" >30.57</td>
                        <td id="T_13f52_row2_col16" class="data row2 col16" >52.95</td>
                        <td id="T_13f52_row2_col17" class="data row2 col17" >8.73</td>
                        <td id="T_13f52_row2_col18" class="data row2 col18" >10.49</td>
                        <td id="T_13f52_row2_col19" class="data row2 col19" >0.57</td>
                        <td id="T_13f52_row2_col20" class="data row2 col20" >2.05</td>
                        <td id="T_13f52_row2_col21" class="data row2 col21" >1,282,987.13</td>
                        <td id="T_13f52_row2_col22" class="data row2 col22" >4,000,340.33</td>
                        <td id="T_13f52_row2_col23" class="data row2 col23" >2,495,684.00</td>
                        <td id="T_13f52_row2_col24" class="data row2 col24" >67.93</td>
            </tr>
            <tr>
                        <th id="T_13f52_level0_row3" class="row_heading level0 row3" >000002.SZ</th>
                        <td id="T_13f52_row3_col0" class="data row3 col0" >万  科Ａ</td>
                        <td id="T_13f52_row3_col1" class="data row3 col1" >房地产</td>
                        <td id="T_13f52_row3_col2" class="data row3 col2" >19.65</td>
                        <td id="T_13f52_row3_col3" class="data row3 col3" >81.28</td>
                        <td id="T_13f52_row3_col4" class="data row3 col4" >56.58</td>
                        <td id="T_13f52_row3_col5" class="data row3 col5" >0.09</td>
                        <td id="T_13f52_row3_col6" class="data row3 col6" >20.50</td>
                        <td id="T_13f52_row3_col7" class="data row3 col7" >10.84</td>
                        <td id="T_13f52_row3_col8" class="data row3 col8" >331,895.50</td>
                        <td id="T_13f52_row3_col9" class="data row3 col9" >20.02</td>
                        <td id="T_13f52_row3_col10" class="data row3 col10" >5.31</td>
                        <td id="T_13f52_row3_col11" class="data row3 col11" >35,553.02</td>
                        <td id="T_13f52_row3_col12" class="data row3 col12" >14.10</td>
                        <td id="T_13f52_row3_col13" class="data row3 col13" >6.85</td>
                        <td id="T_13f52_row3_col14" class="data row3 col14" >45,227.06</td>
                        <td id="T_13f52_row3_col15" class="data row3 col15" >25.80</td>
                        <td id="T_13f52_row3_col16" class="data row3 col16" >109.64</td>
                        <td id="T_13f52_row3_col17" class="data row3 col17" >7.32</td>
                        <td id="T_13f52_row3_col18" class="data row3 col18" >8.33</td>
                        <td id="T_13f52_row3_col19" class="data row3 col19" >0.59</td>
                        <td id="T_13f52_row3_col20" class="data row3 col20" >-</td>
                        <td id="T_13f52_row3_col21" class="data row3 col21" >296,175.63</td>
                        <td id="T_13f52_row3_col22" class="data row3 col22" >1,093,741.95</td>
                        <td id="T_13f52_row3_col23" class="data row3 col23" >652,715.81</td>
                        <td id="T_13f52_row3_col24" class="data row3 col24" >72.92</td>
            </tr>
            <tr>
                        <th id="T_13f52_level0_row4" class="row_heading level0 row4" >600886.SS</th>
                        <td id="T_13f52_row4_col0" class="data row4 col0" >国投电力</td>
                        <td id="T_13f52_row4_col1" class="data row4 col1" >公用事业</td>
                        <td id="T_13f52_row4_col2" class="data row4 col2" >2.87</td>
                        <td id="T_13f52_row4_col3" class="data row4 col3" >63.92</td>
                        <td id="T_13f52_row4_col4" class="data row4 col4" >20.36</td>
                        <td id="T_13f52_row4_col5" class="data row4 col5" >1.07</td>
                        <td id="T_13f52_row4_col6" class="data row4 col6" >11.40</td>
                        <td id="T_13f52_row4_col7" class="data row4 col7" >11.52</td>
                        <td id="T_13f52_row4_col8" class="data row4 col8" >38,602.07</td>
                        <td id="T_13f52_row4_col9" class="data row4 col9" >8.58</td>
                        <td id="T_13f52_row4_col10" class="data row4 col10" >18.99</td>
                        <td id="T_13f52_row4_col11" class="data row4 col11" >4,466.87</td>
                        <td id="T_13f52_row4_col12" class="data row4 col12" >19.99</td>
                        <td id="T_13f52_row4_col13" class="data row4 col13" >13.48</td>
                        <td id="T_13f52_row4_col14" class="data row4 col14" >9,072.54</td>
                        <td id="T_13f52_row4_col15" class="data row4 col15" >18.50</td>
                        <td id="T_13f52_row4_col16" class="data row4 col16" >17.96</td>
                        <td id="T_13f52_row4_col17" class="data row4 col17" >12.38</td>
                        <td id="T_13f52_row4_col18" class="data row4 col18" >15.00</td>
                        <td id="T_13f52_row4_col19" class="data row4 col19" >0.75</td>
                        <td id="T_13f52_row4_col20" class="data row4 col20" >2.90</td>
                        <td id="T_13f52_row4_col21" class="data row4 col21" >67,011.67</td>
                        <td id="T_13f52_row4_col22" class="data row4 col22" >185,308.38</td>
                        <td id="T_13f52_row4_col23" class="data row4 col23" >94,502.51</td>
                        <td id="T_13f52_row4_col24" class="data row4 col24" >63.84</td>
            </tr>
            <tr>
                        <th id="T_13f52_level0_row5" class="row_heading level0 row5" >600036.SS</th>
                        <td id="T_13f52_row5_col0" class="data row5 col0" >招商银行</td>
                        <td id="T_13f52_row5_col1" class="data row5 col1" >银行</td>
                        <td id="T_13f52_row5_col2" class="data row5 col2" >22.26</td>
                        <td id="T_13f52_row5_col3" class="data row5 col3" >91.27</td>
                        <td id="T_13f52_row5_col4" class="data row5 col4" >0.15</td>
                        <td id="T_13f52_row5_col5" class="data row5 col5" >1.44</td>
                        <td id="T_13f52_row5_col6" class="data row5 col6" >15.46</td>
                        <td id="T_13f52_row5_col7" class="data row5 col7" >43.54</td>
                        <td id="T_13f52_row5_col8" class="data row5 col8" >195,736.25</td>
                        <td id="T_13f52_row5_col9" class="data row5 col9" >11.97</td>
                        <td id="T_13f52_row5_col10" class="data row5 col10" >4.30</td>
                        <td id="T_13f52_row5_col11" class="data row5 col11" >85,229.75</td>
                        <td id="T_13f52_row5_col12" class="data row5 col12" >11.65</td>
                        <td id="T_13f52_row5_col13" class="data row5 col13" >5.92</td>
                        <td id="T_13f52_row5_col14" class="data row5 col14" >76,865.50</td>
                        <td id="T_13f52_row5_col15" class="data row5 col15" >-693.52</td>
                        <td id="T_13f52_row5_col16" class="data row5 col16" >1,273.45</td>
                        <td id="T_13f52_row5_col17" class="data row5 col17" >14.53</td>
                        <td id="T_13f52_row5_col18" class="data row5 col18" >17.00</td>
                        <td id="T_13f52_row5_col19" class="data row5 col19" >1.46</td>
                        <td id="T_13f52_row5_col20" class="data row5 col20" >2.93</td>
                        <td id="T_13f52_row5_col21" class="data row5 col21" >1,448,565.15</td>
                        <td id="T_13f52_row5_col22" class="data row5 col22" >-171,200,164.68</td>
                        <td id="T_13f52_row5_col23" class="data row5 col23" >1,472,131.36</td>
                        <td id="T_13f52_row5_col24" class="data row5 col24" >-</td>
            </tr>
            <tr>
                        <th id="T_13f52_level0_row6" class="row_heading level0 row6" >000333.SZ</th>
                        <td id="T_13f52_row6_col0" class="data row6 col0" >美的集团</td>
                        <td id="T_13f52_row6_col1" class="data row6 col1" >家用电器</td>
                        <td id="T_13f52_row6_col2" class="data row6 col2" >38.26</td>
                        <td id="T_13f52_row6_col3" class="data row6 col3" >65.53</td>
                        <td id="T_13f52_row6_col4" class="data row6 col4" >22.82</td>
                        <td id="T_13f52_row6_col5" class="data row6 col5" >25.15</td>
                        <td id="T_13f52_row6_col6" class="data row6 col6" >23.69</td>
                        <td id="T_13f52_row6_col7" class="data row6 col7" >8.31</td>
                        <td id="T_13f52_row6_col8" class="data row6 col8" >265,704.10</td>
                        <td id="T_13f52_row6_col9" class="data row6 col9" >5.73</td>
                        <td id="T_13f52_row6_col10" class="data row6 col10" >3.11</td>
                        <td id="T_13f52_row6_col11" class="data row6 col11" >22,237.16</td>
                        <td id="T_13f52_row6_col12" class="data row6 col12" >16.39</td>
                        <td id="T_13f52_row6_col13" class="data row6 col13" >3.66</td>
                        <td id="T_13f52_row6_col14" class="data row6 col14" >25,878.13</td>
                        <td id="T_13f52_row6_col15" class="data row6 col15" >11.21</td>
                        <td id="T_13f52_row6_col16" class="data row6 col16" >43.88</td>
                        <td id="T_13f52_row6_col17" class="data row6 col17" >18.81</td>
                        <td id="T_13f52_row6_col18" class="data row6 col18" >24.64</td>
                        <td id="T_13f52_row6_col19" class="data row6 col19" >1.50</td>
                        <td id="T_13f52_row6_col20" class="data row6 col20" >2.43</td>
                        <td id="T_13f52_row6_col21" class="data row6 col21" >547,817.00</td>
                        <td id="T_13f52_row6_col22" class="data row6 col22" >442,095.34</td>
                        <td id="T_13f52_row6_col23" class="data row6 col23" >431,728.04</td>
                        <td id="T_13f52_row6_col24" class="data row6 col24" >-23.91</td>
            </tr>
            <tr>
                        <th id="T_13f52_level0_row7" class="row_heading level0 row7" >601012.SS</th>
                        <td id="T_13f52_row7_col0" class="data row7 col0" >隆基股份</td>
                        <td id="T_13f52_row7_col1" class="data row7 col1" >电气设备</td>
                        <td id="T_13f52_row7_col2" class="data row7 col2" >12.14</td>
                        <td id="T_13f52_row7_col3" class="data row7 col3" >59.38</td>
                        <td id="T_13f52_row7_col4" class="data row7 col4" >24.45</td>
                        <td id="T_13f52_row7_col5" class="data row7 col5" >0.50</td>
                        <td id="T_13f52_row7_col6" class="data row7 col6" >21.03</td>
                        <td id="T_13f52_row7_col7" class="data row7 col7" >16.28</td>
                        <td id="T_13f52_row7_col8" class="data row7 col8" >31,457.63</td>
                        <td id="T_13f52_row7_col9" class="data row7 col9" >49.97</td>
                        <td id="T_13f52_row7_col10" class="data row7 col10" >15.77</td>
                        <td id="T_13f52_row7_col11" class="data row7 col11" >4,988.60</td>
                        <td id="T_13f52_row7_col12" class="data row7 col12" >46.72</td>
                        <td id="T_13f52_row7_col13" class="data row7 col13" >68.60</td>
                        <td id="T_13f52_row7_col14" class="data row7 col14" >1,597.33</td>
                        <td id="T_13f52_row7_col15" class="data row7 col15" >-97.28</td>
                        <td id="T_13f52_row7_col16" class="data row7 col16" >181.11</td>
                        <td id="T_13f52_row7_col17" class="data row7 col17" >39.34</td>
                        <td id="T_13f52_row7_col18" class="data row7 col18" >74.12</td>
                        <td id="T_13f52_row7_col19" class="data row7 col19" >1.59</td>
                        <td id="T_13f52_row7_col20" class="data row7 col20" >0.41</td>
                        <td id="T_13f52_row7_col21" class="data row7 col21" >369,742.87</td>
                        <td id="T_13f52_row7_col22" class="data row7 col22" >44.87</td>
                        <td id="T_13f52_row7_col23" class="data row7 col23" >187,102.81</td>
                        <td id="T_13f52_row7_col24" class="data row7 col24" >-823,887.39</td>
            </tr>
            <tr>
                        <th id="T_13f52_level0_row8" class="row_heading level0 row8" >601398.SS</th>
                        <td id="T_13f52_row8_col0" class="data row8 col0" >工商银行</td>
                        <td id="T_13f52_row8_col1" class="data row8 col1" >银行</td>
                        <td id="T_13f52_row8_col2" class="data row8 col2" >4.60</td>
                        <td id="T_13f52_row8_col3" class="data row8 col3" >91.27</td>
                        <td id="T_13f52_row8_col4" class="data row8 col4" >139.76</td>
                        <td id="T_13f52_row8_col5" class="data row8 col5" >0.31</td>
                        <td id="T_13f52_row8_col6" class="data row8 col6" >12.72</td>
                        <td id="T_13f52_row8_col7" class="data row8 col7" >50.13</td>
                        <td id="T_13f52_row8_col8" class="data row8 col8" >604,505.25</td>
                        <td id="T_13f52_row8_col9" class="data row8 col9" >0.07</td>
                        <td id="T_13f52_row8_col10" class="data row8 col10" >2.42</td>
                        <td id="T_13f52_row8_col11" class="data row8 col11" >302,963.75</td>
                        <td id="T_13f52_row8_col12" class="data row8 col12" >3.38</td>
                        <td id="T_13f52_row8_col13" class="data row8 col13" >1.95</td>
                        <td id="T_13f52_row8_col14" class="data row8 col14" >-93,765.75</td>
                        <td id="T_13f52_row8_col15" class="data row8 col15" >-104.59</td>
                        <td id="T_13f52_row8_col16" class="data row8 col16" >139.60</td>
                        <td id="T_13f52_row8_col17" class="data row8 col17" >6.01</td>
                        <td id="T_13f52_row8_col18" class="data row8 col18" >5.82</td>
                        <td id="T_13f52_row8_col19" class="data row8 col19" >1.72</td>
                        <td id="T_13f52_row8_col20" class="data row8 col20" >4.61</td>
                        <td id="T_13f52_row8_col21" class="data row8 col21" >1,762,918.27</td>
                        <td id="T_13f52_row8_col22" class="data row8 col22" >4,215.09</td>
                        <td id="T_13f52_row8_col23" class="data row8 col23" >4,221,192.20</td>
                        <td id="T_13f52_row8_col24" class="data row8 col24" >-41,723.95</td>
            </tr>
            <tr>
                        <th id="T_13f52_level0_row9" class="row_heading level0 row9" >000895.SZ</th>
                        <td id="T_13f52_row9_col0" class="data row9 col0" >双汇发展</td>
                        <td id="T_13f52_row9_col1" class="data row9 col1" >食品饮料</td>
                        <td id="T_13f52_row9_col2" class="data row9 col2" >1.09</td>
                        <td id="T_13f52_row9_col3" class="data row9 col3" >30.46</td>
                        <td id="T_13f52_row9_col4" class="data row9 col4" >1.32</td>
                        <td id="T_13f52_row9_col5" class="data row9 col5" >-</td>
                        <td id="T_13f52_row9_col6" class="data row9 col6" >31.63</td>
                        <td id="T_13f52_row9_col7" class="data row9 col7" >9.01</td>
                        <td id="T_13f52_row9_col8" class="data row9 col8" >58,437.67</td>
                        <td id="T_13f52_row9_col9" class="data row9 col9" >14.21</td>
                        <td id="T_13f52_row9_col10" class="data row9 col10" >15.19</td>
                        <td id="T_13f52_row9_col11" class="data row9 col11" >5,231.08</td>
                        <td id="T_13f52_row9_col12" class="data row9 col12" >13.15</td>
                        <td id="T_13f52_row9_col13" class="data row9 col13" >2.22</td>
                        <td id="T_13f52_row9_col14" class="data row9 col14" >5,225.37</td>
                        <td id="T_13f52_row9_col15" class="data row9 col15" >25.11</td>
                        <td id="T_13f52_row9_col16" class="data row9 col16" >68.40</td>
                        <td id="T_13f52_row9_col17" class="data row9 col17" >19.13</td>
                        <td id="T_13f52_row9_col18" class="data row9 col18" >23.28</td>
                        <td id="T_13f52_row9_col19" class="data row9 col19" >1.77</td>
                        <td id="T_13f52_row9_col20" class="data row9 col20" >5.55</td>
                        <td id="T_13f52_row9_col21" class="data row9 col21" >121,782.80</td>
                        <td id="T_13f52_row9_col22" class="data row9 col22" >124,420.74</td>
                        <td id="T_13f52_row9_col23" class="data row9 col23" >93,823.95</td>
                        <td id="T_13f52_row9_col24" class="data row9 col24" >2.12</td>
            </tr>
            <tr>
                        <th id="T_13f52_level0_row10" class="row_heading level0 row10" >600570.SS</th>
                        <td id="T_13f52_row10_col0" class="data row10 col0" >恒生电子</td>
                        <td id="T_13f52_row10_col1" class="data row10 col1" >计算机</td>
                        <td id="T_13f52_row10_col2" class="data row10 col2" >5.13</td>
                        <td id="T_13f52_row10_col3" class="data row10 col3" >49.48</td>
                        <td id="T_13f52_row10_col4" class="data row10 col4" >14.02</td>
                        <td id="T_13f52_row10_col5" class="data row10 col5" >6.85</td>
                        <td id="T_13f52_row10_col6" class="data row10 col6" >24.06</td>
                        <td id="T_13f52_row10_col7" class="data row10 col7" >26.42</td>
                        <td id="T_13f52_row10_col8" class="data row10 col8" >3,493.37</td>
                        <td id="T_13f52_row10_col9" class="data row10 col9" >16.27</td>
                        <td id="T_13f52_row10_col10" class="data row10 col10" >7.59</td>
                        <td id="T_13f52_row10_col11" class="data row10 col11" >963.54</td>
                        <td id="T_13f52_row10_col12" class="data row10 col12" >49.90</td>
                        <td id="T_13f52_row10_col13" class="data row10 col13" >64.01</td>
                        <td id="T_13f52_row10_col14" class="data row10 col14" >779.22</td>
                        <td id="T_13f52_row10_col15" class="data row10 col15" >10.32</td>
                        <td id="T_13f52_row10_col16" class="data row10 col16" >20.60</td>
                        <td id="T_13f52_row10_col17" class="data row10 col17" >58.78</td>
                        <td id="T_13f52_row10_col18" class="data row10 col18" >95.23</td>
                        <td id="T_13f52_row10_col19" class="data row10 col19" >1.91</td>
                        <td id="T_13f52_row10_col20" class="data row10 col20" >0.40</td>
                        <td id="T_13f52_row10_col21" class="data row10 col21" >91,754.63</td>
                        <td id="T_13f52_row10_col22" class="data row10 col22" >13,015.01</td>
                        <td id="T_13f52_row10_col23" class="data row10 col23" >38,434.90</td>
                        <td id="T_13f52_row10_col24" class="data row10 col24" >-604.99</td>
            </tr>
            <tr>
                        <th id="T_13f52_level0_row11" class="row_heading level0 row11" >600030.SS</th>
                        <td id="T_13f52_row11_col0" class="data row11 col0" >中信证券</td>
                        <td id="T_13f52_row11_col1" class="data row11 col1" >非银金融</td>
                        <td id="T_13f52_row11_col2" class="data row11 col2" >8.35</td>
                        <td id="T_13f52_row11_col3" class="data row11 col3" >82.35</td>
                        <td id="T_13f52_row11_col4" class="data row11 col4" >293.77</td>
                        <td id="T_13f52_row11_col5" class="data row11 col5" >5.93</td>
                        <td id="T_13f52_row11_col6" class="data row11 col6" >7.53</td>
                        <td id="T_13f52_row11_col7" class="data row11 col7" >27.81</td>
                        <td id="T_13f52_row11_col8" class="data row11 col8" >43,833.03</td>
                        <td id="T_13f52_row11_col9" class="data row11 col9" >9.51</td>
                        <td id="T_13f52_row11_col10" class="data row11 col10" >22.12</td>
                        <td id="T_13f52_row11_col11" class="data row11 col11" >12,247.03</td>
                        <td id="T_13f52_row11_col12" class="data row11 col12" >13.17</td>
                        <td id="T_13f52_row11_col13" class="data row11 col13" >27.55</td>
                        <td id="T_13f52_row11_col14" class="data row11 col14" >18,830.60</td>
                        <td id="T_13f52_row11_col15" class="data row11 col15" >50.91</td>
                        <td id="T_13f52_row11_col16" class="data row11 col16" >279.93</td>
                        <td id="T_13f52_row11_col17" class="data row11 col17" >20.60</td>
                        <td id="T_13f52_row11_col18" class="data row11 col18" >25.32</td>
                        <td id="T_13f52_row11_col19" class="data row11 col19" >1.92</td>
                        <td id="T_13f52_row11_col20" class="data row11 col20" >2.05</td>
                        <td id="T_13f52_row11_col21" class="data row11 col21" >310,081.16</td>
                        <td id="T_13f52_row11_col22" class="data row11 col22" >765,842.13</td>
                        <td id="T_13f52_row11_col23" class="data row11 col23" >219,737.24</td>
                        <td id="T_13f52_row11_col24" class="data row11 col24" >59.51</td>
            </tr>
            <tr>
                        <th id="T_13f52_level0_row12" class="row_heading level0 row12" >600000.SS</th>
                        <td id="T_13f52_row12_col0" class="data row12 col0" >浦发银行</td>
                        <td id="T_13f52_row12_col1" class="data row12 col1" >银行</td>
                        <td id="T_13f52_row12_col2" class="data row12 col2" >4.10</td>
                        <td id="T_13f52_row12_col3" class="data row12 col3" >91.88</td>
                        <td id="T_13f52_row12_col4" class="data row12 col4" >6.45</td>
                        <td id="T_13f52_row12_col5" class="data row12 col5" >1.09</td>
                        <td id="T_13f52_row12_col6" class="data row12 col6" >11.54</td>
                        <td id="T_13f52_row12_col7" class="data row12 col7" >50.05</td>
                        <td id="T_13f52_row12_col8" class="data row12 col8" >113,597.75</td>
                        <td id="T_13f52_row12_col9" class="data row12 col9" >1.01</td>
                        <td id="T_13f52_row12_col10" class="data row12 col10" >3.84</td>
                        <td id="T_13f52_row12_col11" class="data row12 col11" >56,852.00</td>
                        <td id="T_13f52_row12_col12" class="data row12 col12" >2.47</td>
                        <td id="T_13f52_row12_col13" class="data row12 col13" >3.22</td>
                        <td id="T_13f52_row12_col14" class="data row12 col14" >-112,565.25</td>
                        <td id="T_13f52_row12_col15" class="data row12 col15" >-67.43</td>
                        <td id="T_13f52_row12_col16" class="data row12 col16" >193.50</td>
                        <td id="T_13f52_row12_col17" class="data row12 col17" >5.77</td>
                        <td id="T_13f52_row12_col18" class="data row12 col18" >5.28</td>
                        <td id="T_13f52_row12_col19" class="data row12 col19" >2.14</td>
                        <td id="T_13f52_row12_col20" class="data row12 col20" >2.76</td>
                        <td id="T_13f52_row12_col21" class="data row12 col21" >300,271.96</td>
                        <td id="T_13f52_row12_col22" class="data row12 col22" >-89,658.94</td>
                        <td id="T_13f52_row12_col23" class="data row12 col23" >773,004.66</td>
                        <td id="T_13f52_row12_col24" class="data row12 col24" >-</td>
            </tr>
            <tr>
                        <th id="T_13f52_level0_row13" class="row_heading level0 row13" >000725.SZ</th>
                        <td id="T_13f52_row13_col0" class="data row13 col0" >京东方Ａ</td>
                        <td id="T_13f52_row13_col1" class="data row13 col1" >电子</td>
                        <td id="T_13f52_row13_col2" class="data row13 col2" >5.48</td>
                        <td id="T_13f52_row13_col3" class="data row13 col3" >59.13</td>
                        <td id="T_13f52_row13_col4" class="data row13 col4" >17.60</td>
                        <td id="T_13f52_row13_col5" class="data row13 col5" >1.36</td>
                        <td id="T_13f52_row13_col6" class="data row13 col6" >4.95</td>
                        <td id="T_13f52_row13_col7" class="data row13 col7" >4.24</td>
                        <td id="T_13f52_row13_col8" class="data row13 col8" >110,630.38</td>
                        <td id="T_13f52_row13_col9" class="data row13 col9" >13.28</td>
                        <td id="T_13f52_row13_col10" class="data row13 col10" >8.55</td>
                        <td id="T_13f52_row13_col11" class="data row13 col11" >4,489.27</td>
                        <td id="T_13f52_row13_col12" class="data row13 col12" >21.23</td>
                        <td id="T_13f52_row13_col13" class="data row13 col13" >122.41</td>
                        <td id="T_13f52_row13_col14" class="data row13 col14" >-19,536.96</td>
                        <td id="T_13f52_row13_col15" class="data row13 col15" >-20.20</td>
                        <td id="T_13f52_row13_col16" class="data row13 col16" >57.98</td>
                        <td id="T_13f52_row13_col17" class="data row13 col17" >22.27</td>
                        <td id="T_13f52_row13_col18" class="data row13 col18" >46.46</td>
                        <td id="T_13f52_row13_col19" class="data row13 col19" >2.19</td>
                        <td id="T_13f52_row13_col20" class="data row13 col20" >0.75</td>
                        <td id="T_13f52_row13_col21" class="data row13 col21" >208,550.07</td>
                        <td id="T_13f52_row13_col22" class="data row13 col22" >-134,146.21</td>
                        <td id="T_13f52_row13_col23" class="data row13 col23" >97,786.81</td>
                        <td id="T_13f52_row13_col24" class="data row13 col24" >-</td>
            </tr>
            <tr>
                        <th id="T_13f52_level0_row14" class="row_heading level0 row14" >002027.SZ</th>
                        <td id="T_13f52_row14_col0" class="data row14 col0" >分众传媒</td>
                        <td id="T_13f52_row14_col1" class="data row14 col1" >传媒</td>
                        <td id="T_13f52_row14_col2" class="data row14 col2" >13.78</td>
                        <td id="T_13f52_row14_col3" class="data row14 col3" >20.21</td>
                        <td id="T_13f52_row14_col4" class="data row14 col4" >33.41</td>
                        <td id="T_13f52_row14_col5" class="data row14 col5" >0.99</td>
                        <td id="T_13f52_row14_col6" class="data row14 col6" >34.01</td>
                        <td id="T_13f52_row14_col7" class="data row14 col7" >34.64</td>
                        <td id="T_13f52_row14_col8" class="data row14 col8" >12,699.47</td>
                        <td id="T_13f52_row14_col9" class="data row14 col9" >1.40</td>
                        <td id="T_13f52_row14_col10" class="data row14 col10" >18.92</td>
                        <td id="T_13f52_row14_col11" class="data row14 col11" >4,426.70</td>
                        <td id="T_13f52_row14_col12" class="data row14 col12" >14.23</td>
                        <td id="T_13f52_row14_col13" class="data row14 col13" >91.87</td>
                        <td id="T_13f52_row14_col14" class="data row14 col14" >3,554.12</td>
                        <td id="T_13f52_row14_col15" class="data row14 col15" >23.11</td>
                        <td id="T_13f52_row14_col16" class="data row14 col16" >61.17</td>
                        <td id="T_13f52_row14_col17" class="data row14 col17" >26.89</td>
                        <td id="T_13f52_row14_col18" class="data row14 col18" >32.99</td>
                        <td id="T_13f52_row14_col19" class="data row14 col19" >2.32</td>
                        <td id="T_13f52_row14_col20" class="data row14 col20" >-</td>
                        <td id="T_13f52_row14_col21" class="data row14 col21" >146,045.11</td>
                        <td id="T_13f52_row14_col22" class="data row14 col22" >80,860.53</td>
                        <td id="T_13f52_row14_col23" class="data row14 col23" >81,530.75</td>
                        <td id="T_13f52_row14_col24" class="data row14 col24" >-80.61</td>
            </tr>
            <tr>
                        <th id="T_13f52_level0_row15" class="row_heading level0 row15" >601899.SS</th>
                        <td id="T_13f52_row15_col0" class="data row15 col0" >紫金矿业</td>
                        <td id="T_13f52_row15_col1" class="data row15 col1" >有色金属</td>
                        <td id="T_13f52_row15_col2" class="data row15 col2" >11.36</td>
                        <td id="T_13f52_row15_col3" class="data row15 col3" >59.08</td>
                        <td id="T_13f52_row15_col4" class="data row15 col4" >2.95</td>
                        <td id="T_13f52_row15_col5" class="data row15 col5" >0.56</td>
                        <td id="T_13f52_row15_col6" class="data row15 col6" >10.01</td>
                        <td id="T_13f52_row15_col7" class="data row15 col7" >3.63</td>
                        <td id="T_13f52_row15_col8" class="data row15 col8" >127,035.55</td>
                        <td id="T_13f52_row15_col9" class="data row15 col9" >22.17</td>
                        <td id="T_13f52_row15_col10" class="data row15 col10" >8.80</td>
                        <td id="T_13f52_row15_col11" class="data row15 col11" >4,598.50</td>
                        <td id="T_13f52_row15_col12" class="data row15 col12" >24.43</td>
                        <td id="T_13f52_row15_col13" class="data row15 col13" >24.57</td>
                        <td id="T_13f52_row15_col14" class="data row15 col14" >1,575.64</td>
                        <td id="T_13f52_row15_col15" class="data row15 col15" >-110.17</td>
                        <td id="T_13f52_row15_col16" class="data row15 col16" >54.13</td>
                        <td id="T_13f52_row15_col17" class="data row15 col17" >35.54</td>
                        <td id="T_13f52_row15_col18" class="data row15 col18" >57.71</td>
                        <td id="T_13f52_row15_col19" class="data row15 col19" >2.36</td>
                        <td id="T_13f52_row15_col20" class="data row15 col20" >2.00</td>
                        <td id="T_13f52_row15_col21" class="data row15 col21" >265,368.62</td>
                        <td id="T_13f52_row15_col22" class="data row15 col22" >-163.07</td>
                        <td id="T_13f52_row15_col23" class="data row15 col23" >107,811.29</td>
                        <td id="T_13f52_row15_col24" class="data row15 col24" >-</td>
            </tr>
            <tr>
                        <th id="T_13f52_level0_row16" class="row_heading level0 row16" >000858.SZ</th>
                        <td id="T_13f52_row16_col0" class="data row16 col0" >五 粮 液</td>
                        <td id="T_13f52_row16_col1" class="data row16 col1" >食品饮料</td>
                        <td id="T_13f52_row16_col2" class="data row16 col2" >16.09</td>
                        <td id="T_13f52_row16_col3" class="data row16 col3" >22.95</td>
                        <td id="T_13f52_row16_col4" class="data row16 col4" >36.06</td>
                        <td id="T_13f52_row16_col5" class="data row16 col5" >0.00</td>
                        <td id="T_13f52_row16_col6" class="data row16 col6" >21.48</td>
                        <td id="T_13f52_row16_col7" class="data row16 col7" >33.75</td>
                        <td id="T_13f52_row16_col8" class="data row16 col8" >44,414.03</td>
                        <td id="T_13f52_row16_col9" class="data row16 col9" >24.06</td>
                        <td id="T_13f52_row16_col10" class="data row16 col10" >9.17</td>
                        <td id="T_13f52_row16_col11" class="data row16 col11" >15,103.74</td>
                        <td id="T_13f52_row16_col12" class="data row16 col12" >27.68</td>
                        <td id="T_13f52_row16_col13" class="data row16 col13" >12.02</td>
                        <td id="T_13f52_row16_col14" class="data row16 col14" >14,151.02</td>
                        <td id="T_13f52_row16_col15" class="data row16 col15" >22.79</td>
                        <td id="T_13f52_row16_col16" class="data row16 col16" >57.73</td>
                        <td id="T_13f52_row16_col17" class="data row16 col17" >56.73</td>
                        <td id="T_13f52_row16_col18" class="data row16 col18" >81.03</td>
                        <td id="T_13f52_row16_col19" class="data row16 col19" >2.93</td>
                        <td id="T_13f52_row16_col20" class="data row16 col20" >-</td>
                        <td id="T_13f52_row16_col21" class="data row16 col21" >1,223,871.56</td>
                        <td id="T_13f52_row16_col22" class="data row16 col22" >319,594.14</td>
                        <td id="T_13f52_row16_col23" class="data row16 col23" >381,004.97</td>
                        <td id="T_13f52_row16_col24" class="data row16 col24" >-282.95</td>
            </tr>
            <tr>
                        <th id="T_13f52_level0_row17" class="row_heading level0 row17" >600900.SS</th>
                        <td id="T_13f52_row17_col0" class="data row17 col0" >长江电力</td>
                        <td id="T_13f52_row17_col1" class="data row17 col1" >公用事业</td>
                        <td id="T_13f52_row17_col2" class="data row17 col2" >17.24</td>
                        <td id="T_13f52_row17_col3" class="data row17 col3" >46.10</td>
                        <td id="T_13f52_row17_col4" class="data row17 col4" >8.85</td>
                        <td id="T_13f52_row17_col5" class="data row17 col5" >0.59</td>
                        <td id="T_13f52_row17_col6" class="data row17 col6" >15.52</td>
                        <td id="T_13f52_row17_col7" class="data row17 col7" >44.31</td>
                        <td id="T_13f52_row17_col8" class="data row17 col8" >52,254.23</td>
                        <td id="T_13f52_row17_col9" class="data row17 col9" >5.12</td>
                        <td id="T_13f52_row17_col10" class="data row17 col10" >9.59</td>
                        <td id="T_13f52_row17_col11" class="data row17 col11" >23,178.31</td>
                        <td id="T_13f52_row17_col12" class="data row17 col12" >6.31</td>
                        <td id="T_13f52_row17_col13" class="data row17 col13" >14.01</td>
                        <td id="T_13f52_row17_col14" class="data row17 col14" >36,227.81</td>
                        <td id="T_13f52_row17_col15" class="data row17 col15" >0.54</td>
                        <td id="T_13f52_row17_col16" class="data row17 col16" >9.49</td>
                        <td id="T_13f52_row17_col17" class="data row17 col17" >16.54</td>
                        <td id="T_13f52_row17_col18" class="data row17 col18" >19.50</td>
                        <td id="T_13f52_row17_col19" class="data row17 col19" >3.09</td>
                        <td id="T_13f52_row17_col20" class="data row17 col20" >3.97</td>
                        <td id="T_13f52_row17_col21" class="data row17 col21" >451,881.57</td>
                        <td id="T_13f52_row17_col22" class="data row17 col22" >467,208.09</td>
                        <td id="T_13f52_row17_col23" class="data row17 col23" >349,081.62</td>
                        <td id="T_13f52_row17_col24" class="data row17 col24" >3.28</td>
            </tr>
            <tr>
                        <th id="T_13f52_level0_row18" class="row_heading level0 row18" >600276.SS</th>
                        <td id="T_13f52_row18_col0" class="data row18 col0" >恒瑞医药</td>
                        <td id="T_13f52_row18_col1" class="data row18 col1" >医药生物</td>
                        <td id="T_13f52_row18_col2" class="data row18 col2" >6.58</td>
                        <td id="T_13f52_row18_col3" class="data row18 col3" >11.35</td>
                        <td id="T_13f52_row18_col4" class="data row18 col4" >31.83</td>
                        <td id="T_13f52_row18_col5" class="data row18 col5" >-</td>
                        <td id="T_13f52_row18_col6" class="data row18 col6" >20.95</td>
                        <td id="T_13f52_row18_col7" class="data row18 col7" >23.07</td>
                        <td id="T_13f52_row18_col8" class="data row18 col8" >20,569.18</td>
                        <td id="T_13f52_row18_col9" class="data row18 col9" >26.23</td>
                        <td id="T_13f52_row18_col10" class="data row18 col10" >7.31</td>
                        <td id="T_13f52_row18_col11" class="data row18 col11" >4,734.67</td>
                        <td id="T_13f52_row18_col12" class="data row18 col12" >25.41</td>
                        <td id="T_13f52_row18_col13" class="data row18 col13" >6.20</td>
                        <td id="T_13f52_row18_col14" class="data row18 col14" >2,636.32</td>
                        <td id="T_13f52_row18_col15" class="data row18 col15" >12.33</td>
                        <td id="T_13f52_row18_col16" class="data row18 col16" >29.30</td>
                        <td id="T_13f52_row18_col17" class="data row18 col17" >67.09</td>
                        <td id="T_13f52_row18_col18" class="data row18 col18" >93.07</td>
                        <td id="T_13f52_row18_col19" class="data row18 col19" >3.66</td>
                        <td id="T_13f52_row18_col20" class="data row18 col20" >-</td>
                        <td id="T_13f52_row18_col21" class="data row18 col21" >440,666.69</td>
                        <td id="T_13f52_row18_col22" class="data row18 col22" >46,326.24</td>
                        <td id="T_13f52_row18_col23" class="data row18 col23" >113,496.80</td>
                        <td id="T_13f52_row18_col24" class="data row18 col24" >-851.22</td>
            </tr>
            <tr>
                        <th id="T_13f52_level0_row19" class="row_heading level0 row19" >600519.SS</th>
                        <td id="T_13f52_row19_col0" class="data row19 col0" >贵州茅台</td>
                        <td id="T_13f52_row19_col1" class="data row19 col1" >食品饮料</td>
                        <td id="T_13f52_row19_col2" class="data row19 col2" >30.99</td>
                        <td id="T_13f52_row19_col3" class="data row19 col3" >21.40</td>
                        <td id="T_13f52_row19_col4" class="data row19 col4" >1.65</td>
                        <td id="T_13f52_row19_col5" class="data row19 col5" >-</td>
                        <td id="T_13f52_row19_col6" class="data row19 col6" >30.01</td>
                        <td id="T_13f52_row19_col7" class="data row19 col7" >47.94</td>
                        <td id="T_13f52_row19_col8" class="data row19 col8" >78,050.86</td>
                        <td id="T_13f52_row19_col9" class="data row19 col9" >17.87</td>
                        <td id="T_13f52_row19_col10" class="data row19 col10" >7.86</td>
                        <td id="T_13f52_row19_col11" class="data row19 col11" >37,546.69</td>
                        <td id="T_13f52_row19_col12" class="data row19 col12" >20.13</td>
                        <td id="T_13f52_row19_col13" class="data row19 col13" >8.75</td>
                        <td id="T_13f52_row19_col14" class="data row19 col14" >38,111.89</td>
                        <td id="T_13f52_row19_col15" class="data row19 col15" >37.59</td>
                        <td id="T_13f52_row19_col16" class="data row19 col16" >45.08</td>
                        <td id="T_13f52_row19_col17" class="data row19 col17" >59.47</td>
                        <td id="T_13f52_row19_col18" class="data row19 col18" >75.33</td>
                        <td id="T_13f52_row19_col19" class="data row19 col19" >3.74</td>
                        <td id="T_13f52_row19_col20" class="data row19 col20" >1.33</td>
                        <td id="T_13f52_row19_col21" class="data row19 col21" >2,828,334.27</td>
                        <td id="T_13f52_row19_col22" class="data row19 col22" >1,189,500.62</td>
                        <td id="T_13f52_row19_col23" class="data row19 col23" >796,909.35</td>
                        <td id="T_13f52_row19_col24" class="data row19 col24" >-137.77</td>
            </tr>
            <tr>
                        <th id="T_13f52_level0_row20" class="row_heading level0 row20" >002415.SZ</th>
                        <td id="T_13f52_row20_col0" class="data row20 col0" >海康威视</td>
                        <td id="T_13f52_row20_col1" class="data row20 col1" >电子</td>
                        <td id="T_13f52_row20_col2" class="data row20 col2" >8.74</td>
                        <td id="T_13f52_row20_col3" class="data row20 col3" >38.58</td>
                        <td id="T_13f52_row20_col4" class="data row20 col4" >42.53</td>
                        <td id="T_13f52_row20_col5" class="data row20 col5" >0.51</td>
                        <td id="T_13f52_row20_col6" class="data row20 col6" >28.43</td>
                        <td id="T_13f52_row20_col7" class="data row20 col7" >21.96</td>
                        <td id="T_13f52_row20_col8" class="data row20 col8" >53,226.04</td>
                        <td id="T_13f52_row20_col9" class="data row20 col9" >14.92</td>
                        <td id="T_13f52_row20_col10" class="data row20 col10" >4.45</td>
                        <td id="T_13f52_row20_col11" class="data row20 col11" >11,640.78</td>
                        <td id="T_13f52_row20_col12" class="data row20 col12" >12.60</td>
                        <td id="T_13f52_row20_col13" class="data row20 col13" >6.99</td>
                        <td id="T_13f52_row20_col14" class="data row20 col14" >8,165.84</td>
                        <td id="T_13f52_row20_col15" class="data row20 col15" >49.38</td>
                        <td id="T_13f52_row20_col16" class="data row20 col16" >82.14</td>
                        <td id="T_13f52_row20_col17" class="data row20 col17" >40.45</td>
                        <td id="T_13f52_row20_col18" class="data row20 col18" >49.06</td>
                        <td id="T_13f52_row20_col19" class="data row20 col19" >3.89</td>
                        <td id="T_13f52_row20_col20" class="data row20 col20" >1.63</td>
                        <td id="T_13f52_row20_col21" class="data row20 col21" >571,069.83</td>
                        <td id="T_13f52_row20_col22" class="data row20 col22" >322,502.50</td>
                        <td id="T_13f52_row20_col23" class="data row20 col23" >205,940.78</td>
                        <td id="T_13f52_row20_col24" class="data row20 col24" >-77.07</td>
            </tr>
            <tr>
                        <th id="T_13f52_level0_row21" class="row_heading level0 row21" >603288.SS</th>
                        <td id="T_13f52_row21_col0" class="data row21 col0" >海天味业</td>
                        <td id="T_13f52_row21_col1" class="data row21 col1" >食品饮料</td>
                        <td id="T_13f52_row21_col2" class="data row21 col2" >5.03</td>
                        <td id="T_13f52_row21_col3" class="data row21 col3" >31.72</td>
                        <td id="T_13f52_row21_col4" class="data row21 col4" >0.21</td>
                        <td id="T_13f52_row21_col5" class="data row21 col5" >0.15</td>
                        <td id="T_13f52_row21_col6" class="data row21 col6" >31.42</td>
                        <td id="T_13f52_row21_col7" class="data row21 col7" >26.24</td>
                        <td id="T_13f52_row21_col8" class="data row21 col8" >18,551.89</td>
                        <td id="T_13f52_row21_col9" class="data row21 col9" >16.05</td>
                        <td id="T_13f52_row21_col10" class="data row21 col10" >0.85</td>
                        <td id="T_13f52_row21_col11" class="data row21 col11" >4,913.07</td>
                        <td id="T_13f52_row21_col12" class="data row21 col12" >21.95</td>
                        <td id="T_13f52_row21_col13" class="data row21 col13" >2.08</td>
                        <td id="T_13f52_row21_col14" class="data row21 col14" >5,564.91</td>
                        <td id="T_13f52_row21_col15" class="data row21 col15" >11.37</td>
                        <td id="T_13f52_row21_col16" class="data row21 col16" >15.72</td>
                        <td id="T_13f52_row21_col17" class="data row21 col17" >66.07</td>
                        <td id="T_13f52_row21_col18" class="data row21 col18" >90.64</td>
                        <td id="T_13f52_row21_col19" class="data row21 col19" >4.13</td>
                        <td id="T_13f52_row21_col20" class="data row21 col20" >1.20</td>
                        <td id="T_13f52_row21_col21" class="data row21 col21" >445,301.26</td>
                        <td id="T_13f52_row21_col22" class="data row21 col22" >95,461.96</td>
                        <td id="T_13f52_row21_col23" class="data row21 col23" >108,814.57</td>
                        <td id="T_13f52_row21_col24" class="data row21 col24" >-366.47</td>
            </tr>
            <tr>
                        <th id="T_13f52_level0_row22" class="row_heading level0 row22" >601888.SS</th>
                        <td id="T_13f52_row22_col0" class="data row22 col0" >中国中免</td>
                        <td id="T_13f52_row22_col1" class="data row22 col1" >休闲服务</td>
                        <td id="T_13f52_row22_col2" class="data row22 col2" >70.49</td>
                        <td id="T_13f52_row22_col3" class="data row22 col3" >37.55</td>
                        <td id="T_13f52_row22_col4" class="data row22 col4" >2.34</td>
                        <td id="T_13f52_row22_col5" class="data row22 col5" >3.69</td>
                        <td id="T_13f52_row22_col6" class="data row22 col6" >21.92</td>
                        <td id="T_13f52_row22_col7" class="data row22 col7" >9.18</td>
                        <td id="T_13f52_row22_col8" class="data row22 col8" >44,124.68</td>
                        <td id="T_13f52_row22_col9" class="data row22 col9" >25.94</td>
                        <td id="T_13f52_row22_col10" class="data row22 col10" >34.96</td>
                        <td id="T_13f52_row22_col11" class="data row22 col11" >4,099.26</td>
                        <td id="T_13f52_row22_col12" class="data row22 col12" >34.84</td>
                        <td id="T_13f52_row22_col13" class="data row22 col13" >13.83</td>
                        <td id="T_13f52_row22_col14" class="data row22 col14" >3,109.37</td>
                        <td id="T_13f52_row22_col15" class="data row22 col15" >105.58</td>
                        <td id="T_13f52_row22_col16" class="data row22 col16" >204.00</td>
                        <td id="T_13f52_row22_col17" class="data row22 col17" >69.24</td>
                        <td id="T_13f52_row22_col18" class="data row22 col18" >152.21</td>
                        <td id="T_13f52_row22_col19" class="data row22 col19" >4.37</td>
                        <td id="T_13f52_row22_col20" class="data row22 col20" >0.80</td>
                        <td id="T_13f52_row22_col21" class="data row22 col21" >623,934.50</td>
                        <td id="T_13f52_row22_col22" class="data row22 col22" >309,807.50</td>
                        <td id="T_13f52_row22_col23" class="data row22 col23" >120,761.56</td>
                        <td id="T_13f52_row22_col24" class="data row22 col24" >-101.39</td>
            </tr>
            <tr>
                        <th id="T_13f52_level0_row23" class="row_heading level0 row23" >002594.SZ</th>
                        <td id="T_13f52_row23_col0" class="data row23 col0" >比亚迪</td>
                        <td id="T_13f52_row23_col1" class="data row23 col1" >汽车</td>
                        <td id="T_13f52_row23_col2" class="data row23 col2" >13.70</td>
                        <td id="T_13f52_row23_col3" class="data row23 col3" >67.94</td>
                        <td id="T_13f52_row23_col4" class="data row23 col4" >36.43</td>
                        <td id="T_13f52_row23_col5" class="data row23 col5" >0.12</td>
                        <td id="T_13f52_row23_col6" class="data row23 col6" >5.68</td>
                        <td id="T_13f52_row23_col7" class="data row23 col7" >2.49</td>
                        <td id="T_13f52_row23_col8" class="data row23 col8" >130,076.41</td>
                        <td id="T_13f52_row23_col9" class="data row23 col9" >14.53</td>
                        <td id="T_13f52_row23_col10" class="data row23 col10" >14.13</td>
                        <td id="T_13f52_row23_col11" class="data row23 col11" >3,173.85</td>
                        <td id="T_13f52_row23_col12" class="data row23 col12" >29.57</td>
                        <td id="T_13f52_row23_col13" class="data row23 col13" >115.04</td>
                        <td id="T_13f52_row23_col14" class="data row23 col14" >3,553.80</td>
                        <td id="T_13f52_row23_col15" class="data row23 col15" >-231.87</td>
                        <td id="T_13f52_row23_col16" class="data row23 col16" >381.11</td>
                        <td id="T_13f52_row23_col17" class="data row23 col17" >124.28</td>
                        <td id="T_13f52_row23_col18" class="data row23 col18" >160.91</td>
                        <td id="T_13f52_row23_col19" class="data row23 col19" >5.44</td>
                        <td id="T_13f52_row23_col20" class="data row23 col20" >-</td>
                        <td id="T_13f52_row23_col21" class="data row23 col21" >510,709.50</td>
                        <td id="T_13f52_row23_col22" class="data row23 col22" >-86,814.19</td>
                        <td id="T_13f52_row23_col23" class="data row23 col23" >83,473.39</td>
                        <td id="T_13f52_row23_col24" class="data row23 col24" >-</td>
            </tr>
            <tr>
                        <th id="T_13f52_level0_row24" class="row_heading level0 row24" >600887.SS</th>
                        <td id="T_13f52_row24_col0" class="data row24 col0" >伊利股份</td>
                        <td id="T_13f52_row24_col1" class="data row24 col1" >食品饮料</td>
                        <td id="T_13f52_row24_col2" class="data row24 col2" >6.53</td>
                        <td id="T_13f52_row24_col3" class="data row24 col3" >57.09</td>
                        <td id="T_13f52_row24_col4" class="data row24 col4" >6.81</td>
                        <td id="T_13f52_row24_col5" class="data row24 col5" >1.19</td>
                        <td id="T_13f52_row24_col6" class="data row24 col6" >24.20</td>
                        <td id="T_13f52_row24_col7" class="data row24 col7" >7.98</td>
                        <td id="T_13f52_row24_col8" class="data row24 col8" >83,680.04</td>
                        <td id="T_13f52_row24_col9" class="data row24 col9" >12.56</td>
                        <td id="T_13f52_row24_col10" class="data row24 col10" >4.81</td>
                        <td id="T_13f52_row24_col11" class="data row24 col11" >6,613.14</td>
                        <td id="T_13f52_row24_col12" class="data row24 col12" >5.69</td>
                        <td id="T_13f52_row24_col13" class="data row24 col13" >3.13</td>
                        <td id="T_13f52_row24_col14" class="data row24 col14" >2,432.79</td>
                        <td id="T_13f52_row24_col15" class="data row24 col15" >-216.14</td>
                        <td id="T_13f52_row24_col16" class="data row24 col16" >272.20</td>
                        <td id="T_13f52_row24_col17" class="data row24 col17" >27.32</td>
                        <td id="T_13f52_row24_col18" class="data row24 col18" >36.40</td>
                        <td id="T_13f52_row24_col19" class="data row24 col19" >6.40</td>
                        <td id="T_13f52_row24_col20" class="data row24 col20" >-</td>
                        <td id="T_13f52_row24_col21" class="data row24 col21" >240,750.51</td>
                        <td id="T_13f52_row24_col22" class="data row24 col22" >-40,876.74</td>
                        <td id="T_13f52_row24_col23" class="data row24 col23" >97,993.42</td>
                        <td id="T_13f52_row24_col24" class="data row24 col24" >-</td>
            </tr>
            <tr>
                        <th id="T_13f52_level0_row25" class="row_heading level0 row25" >300750.SZ</th>
                        <td id="T_13f52_row25_col0" class="data row25 col0" >宁德时代</td>
                        <td id="T_13f52_row25_col1" class="data row25 col1" >电气设备</td>
                        <td id="T_13f52_row25_col2" class="data row25 col2" >20.61</td>
                        <td id="T_13f52_row25_col3" class="data row25 col3" >55.82</td>
                        <td id="T_13f52_row25_col4" class="data row25 col4" >48.95</td>
                        <td id="T_13f52_row25_col5" class="data row25 col5" >0.23</td>
                        <td id="T_13f52_row25_col6" class="data row25 col6" >11.66</td>
                        <td id="T_13f52_row25_col7" class="data row25 col7" >12.97</td>
                        <td id="T_13f52_row25_col8" class="data row25 col8" >36,428.91</td>
                        <td id="T_13f52_row25_col9" class="data row25 col9" >37.54</td>
                        <td id="T_13f52_row25_col10" class="data row25 col10" >24.16</td>
                        <td id="T_13f52_row25_col11" class="data row25 col11" >4,352.16</td>
                        <td id="T_13f52_row25_col12" class="data row25 col12" >14.80</td>
                        <td id="T_13f52_row25_col13" class="data row25 col13" >24.56</td>
                        <td id="T_13f52_row25_col14" class="data row25 col14" >2,232.11</td>
                        <td id="T_13f52_row25_col15" class="data row25 col15" >-61.23</td>
                        <td id="T_13f52_row25_col16" class="data row25 col16" >122.10</td>
                        <td id="T_13f52_row25_col17" class="data row25 col17" >145.04</td>
                        <td id="T_13f52_row25_col18" class="data row25 col18" >231.34</td>
                        <td id="T_13f52_row25_col19" class="data row25 col19" >15.63</td>
                        <td id="T_13f52_row25_col20" class="data row25 col20" >-</td>
                        <td id="T_13f52_row25_col21" class="data row25 col21" >1,006,820.20</td>
                        <td id="T_13f52_row25_col22" class="data row25 col22" >2,579.00</td>
                        <td id="T_13f52_row25_col23" class="data row25 col23" >81,300.34</td>
                        <td id="T_13f52_row25_col24" class="data row25 col24" >-38,939.20</td>
            </tr>
            <tr>
                        <th id="T_13f52_level0_row26" class="row_heading level0 row26" >000651.SZ</th>
                        <td id="T_13f52_row26_col0" class="data row26 col0" >格力电器</td>
                        <td id="T_13f52_row26_col1" class="data row26 col1" >家用电器</td>
                        <td id="T_13f52_row26_col2" class="data row26 col2" >25.71</td>
                        <td id="T_13f52_row26_col3" class="data row26 col3" >58.14</td>
                        <td id="T_13f52_row26_col4" class="data row26 col4" >17.56</td>
                        <td id="T_13f52_row26_col5" class="data row26 col5" >0.18</td>
                        <td id="T_13f52_row26_col6" class="data row26 col6" >26.13</td>
                        <td id="T_13f52_row26_col7" class="data row26 col7" >13.45</td>
                        <td id="T_13f52_row26_col8" class="data row26 col8" >178,766.68</td>
                        <td id="T_13f52_row26_col9" class="data row26 col9" >6.56</td>
                        <td id="T_13f52_row26_col10" class="data row26 col10" >24.45</td>
                        <td id="T_13f52_row26_col11" class="data row26 col11" >23,868.76</td>
                        <td id="T_13f52_row26_col12" class="data row26 col12" >0.34</td>
                        <td id="T_13f52_row26_col13" class="data row26 col13" >14.58</td>
                        <td id="T_13f52_row26_col14" class="data row26 col14" >18,726.76</td>
                        <td id="T_13f52_row26_col15" class="data row26 col15" >9.95</td>
                        <td id="T_13f52_row26_col16" class="data row26 col16" >51.97</td>
                        <td id="T_13f52_row26_col17" class="data row26 col17" >13.87</td>
                        <td id="T_13f52_row26_col18" class="data row26 col18" >14.11</td>
                        <td id="T_13f52_row26_col19" class="data row26 col19" >41.65</td>
                        <td id="T_13f52_row26_col20" class="data row26 col20" >-</td>
                        <td id="T_13f52_row26_col21" class="data row26 col21" >336,760.57</td>
                        <td id="T_13f52_row26_col22" class="data row26 col22" >309,872.64</td>
                        <td id="T_13f52_row26_col23" class="data row26 col23" >306,134.73</td>
                        <td id="T_13f52_row26_col24" class="data row26 col24" >-8.68</td>
            </tr>
            <tr>
                        <th id="T_13f52_level0_row27" class="row_heading level0 row27" >600340.SS</th>
                        <td id="T_13f52_row27_col0" class="data row27 col0" >华夏幸福</td>
                        <td id="T_13f52_row27_col1" class="data row27 col1" >房地产</td>
                        <td id="T_13f52_row27_col2" class="data row27 col2" >0.90</td>
                        <td id="T_13f52_row27_col3" class="data row27 col3" >81.29</td>
                        <td id="T_13f52_row27_col4" class="data row27 col4" >212.96</td>
                        <td id="T_13f52_row27_col5" class="data row27 col5" >0.33</td>
                        <td id="T_13f52_row27_col6" class="data row27 col6" >21.44</td>
                        <td id="T_13f52_row27_col7" class="data row27 col7" >11.59</td>
                        <td id="T_13f52_row27_col8" class="data row27 col8" >87,463.02</td>
                        <td id="T_13f52_row27_col9" class="data row27 col9" >20.76</td>
                        <td id="T_13f52_row27_col10" class="data row27 col10" >22.55</td>
                        <td id="T_13f52_row27_col11" class="data row27 col11" >9,715.66</td>
                        <td id="T_13f52_row27_col12" class="data row27 col12" >-5.88</td>
                        <td id="T_13f52_row27_col13" class="data row27 col13" >59.94</td>
                        <td id="T_13f52_row27_col14" class="data row27 col14" >-23,917.21</td>
                        <td id="T_13f52_row27_col15" class="data row27 col15" >57.88</td>
                        <td id="T_13f52_row27_col16" class="data row27 col16" >164.51</td>
                        <td id="T_13f52_row27_col17" class="data row27 col17" >5.59</td>
                        <td id="T_13f52_row27_col18" class="data row27 col18" >2.16</td>
                        <td id="T_13f52_row27_col19" class="data row27 col19" >-</td>
                        <td id="T_13f52_row27_col20" class="data row27 col20" >5.33</td>
                        <td id="T_13f52_row27_col21" class="data row27 col21" >21,016.68</td>
                        <td id="T_13f52_row27_col22" class="data row27 col22" >-1,107,540.93</td>
                        <td id="T_13f52_row27_col23" class="data row27 col23" >104,443.56</td>
                        <td id="T_13f52_row27_col24" class="data row27 col24" >-</td>
            </tr>
            <tr>
                        <th id="T_13f52_level0_row28" class="row_heading level0 row28" >000625.SZ</th>
                        <td id="T_13f52_row28_col0" class="data row28 col0" >长安汽车</td>
                        <td id="T_13f52_row28_col1" class="data row28 col1" >汽车</td>
                        <td id="T_13f52_row28_col2" class="data row28 col2" >4.81</td>
                        <td id="T_13f52_row28_col3" class="data row28 col3" >55.77</td>
                        <td id="T_13f52_row28_col4" class="data row28 col4" >39.01</td>
                        <td id="T_13f52_row28_col5" class="data row28 col5" >0.09</td>
                        <td id="T_13f52_row28_col6" class="data row28 col6" >4.17</td>
                        <td id="T_13f52_row28_col7" class="data row28 col7" >2.53</td>
                        <td id="T_13f52_row28_col8" class="data row28 col8" >75,367.82</td>
                        <td id="T_13f52_row28_col9" class="data row28 col9" >3.04</td>
                        <td id="T_13f52_row28_col10" class="data row28 col10" >18.70</td>
                        <td id="T_13f52_row28_col11" class="data row28 col11" >2,123.87</td>
                        <td id="T_13f52_row28_col12" class="data row28 col12" >-268.29</td>
                        <td id="T_13f52_row28_col13" class="data row28 col13" >202.57</td>
                        <td id="T_13f52_row28_col14" class="data row28 col14" >-1,998.48</td>
                        <td id="T_13f52_row28_col15" class="data row28 col15" >-304.21</td>
                        <td id="T_13f52_row28_col16" class="data row28 col16" >575.13</td>
                        <td id="T_13f52_row28_col17" class="data row28 col17" >33.40</td>
                        <td id="T_13f52_row28_col18" class="data row28 col18" >53.58</td>
                        <td id="T_13f52_row28_col19" class="data row28 col19" >-</td>
                        <td id="T_13f52_row28_col20" class="data row28 col20" >-</td>
                        <td id="T_13f52_row28_col21" class="data row28 col21" >113,799.68</td>
                        <td id="T_13f52_row28_col22" class="data row28 col22" >179,845.23</td>
                        <td id="T_13f52_row28_col23" class="data row28 col23" >-107,130.52</td>
                        <td id="T_13f52_row28_col24" class="data row28 col24" >36.72</td>
            </tr>
            <tr>
                        <th id="T_13f52_level0_row29" class="row_heading level0 row29" >600066.SS</th>
                        <td id="T_13f52_row29_col0" class="data row29 col0" >宇通客车</td>
                        <td id="T_13f52_row29_col1" class="data row29 col1" >汽车</td>
                        <td id="T_13f52_row29_col2" class="data row29 col2" >1.54</td>
                        <td id="T_13f52_row29_col3" class="data row29 col3" >53.64</td>
                        <td id="T_13f52_row29_col4" class="data row29 col4" >47.74</td>
                        <td id="T_13f52_row29_col5" class="data row29 col5" >0.00</td>
                        <td id="T_13f52_row29_col6" class="data row29 col6" >12.11</td>
                        <td id="T_13f52_row29_col7" class="data row29 col7" >6.35</td>
                        <td id="T_13f52_row29_col8" class="data row29 col8" >29,291.15</td>
                        <td id="T_13f52_row29_col9" class="data row29 col9" >-12.40</td>
                        <td id="T_13f52_row29_col10" class="data row29 col10" >14.22</td>
                        <td id="T_13f52_row29_col11" class="data row29 col11" >1,972.23</td>
                        <td id="T_13f52_row29_col12" class="data row29 col12" >-38.50</td>
                        <td id="T_13f52_row29_col13" class="data row29 col13" >30.74</td>
                        <td id="T_13f52_row29_col14" class="data row29 col14" >1,519.09</td>
                        <td id="T_13f52_row29_col15" class="data row29 col15" >-3.73</td>
                        <td id="T_13f52_row29_col16" class="data row29 col16" >179.13</td>
                        <td id="T_13f52_row29_col17" class="data row29 col17" >58.85</td>
                        <td id="T_13f52_row29_col18" class="data row29 col18" >15.33</td>
                        <td id="T_13f52_row29_col19" class="data row29 col19" >-</td>
                        <td id="T_13f52_row29_col20" class="data row29 col20" >5.21</td>
                        <td id="T_13f52_row29_col21" class="data row29 col21" >30,232.74</td>
                        <td id="T_13f52_row29_col22" class="data row29 col22" >17,379.18</td>
                        <td id="T_13f52_row29_col23" class="data row29 col23" >6,849.78</td>
                        <td id="T_13f52_row29_col24" class="data row29 col24" >-73.96</td>
            </tr>
    </tbody></table>



## 美股

### 指标筛选

1. 负债率 < 50%
2. 应收比 < 30%
3. 商誉比 < 30%
4. ROE >= 15
5. 利润率 >= 20%
6. 收入增长 >= 15% 或 盈利增长 >= 15% 或 FCF增长率 >= 15% 且 (收入增长 > 0 且 盈利增长 > 0 且 FCF增长 > 0)
7. 折价率 > -200%

注: 非美国公司的DCF和盈利折现使用的是所在国货币，市值为美元，未计算折价率




<style  type="text/css" >
#T_1fc85_row0_col0,#T_1fc85_row0_col1,#T_1fc85_row0_col2,#T_1fc85_row0_col3,#T_1fc85_row0_col4,#T_1fc85_row0_col5,#T_1fc85_row0_col6,#T_1fc85_row0_col7,#T_1fc85_row0_col8,#T_1fc85_row0_col9,#T_1fc85_row0_col10,#T_1fc85_row0_col11,#T_1fc85_row0_col12,#T_1fc85_row0_col13,#T_1fc85_row0_col14,#T_1fc85_row0_col15,#T_1fc85_row0_col16,#T_1fc85_row0_col17,#T_1fc85_row0_col18,#T_1fc85_row0_col19,#T_1fc85_row0_col20,#T_1fc85_row0_col21,#T_1fc85_row0_col22,#T_1fc85_row0_col23,#T_1fc85_row1_col0,#T_1fc85_row1_col1,#T_1fc85_row1_col2,#T_1fc85_row1_col3,#T_1fc85_row1_col4,#T_1fc85_row1_col5,#T_1fc85_row1_col6,#T_1fc85_row1_col7,#T_1fc85_row1_col8,#T_1fc85_row1_col9,#T_1fc85_row1_col10,#T_1fc85_row1_col11,#T_1fc85_row1_col12,#T_1fc85_row1_col13,#T_1fc85_row1_col14,#T_1fc85_row1_col15,#T_1fc85_row1_col16,#T_1fc85_row1_col17,#T_1fc85_row1_col18,#T_1fc85_row1_col19,#T_1fc85_row1_col20,#T_1fc85_row1_col21,#T_1fc85_row1_col22,#T_1fc85_row1_col23,#T_1fc85_row2_col0,#T_1fc85_row2_col1,#T_1fc85_row2_col2,#T_1fc85_row2_col3,#T_1fc85_row2_col4,#T_1fc85_row2_col5,#T_1fc85_row2_col6,#T_1fc85_row2_col7,#T_1fc85_row2_col8,#T_1fc85_row2_col9,#T_1fc85_row2_col10,#T_1fc85_row2_col11,#T_1fc85_row2_col12,#T_1fc85_row2_col13,#T_1fc85_row2_col14,#T_1fc85_row2_col15,#T_1fc85_row2_col16,#T_1fc85_row2_col17,#T_1fc85_row2_col18,#T_1fc85_row2_col19,#T_1fc85_row2_col20,#T_1fc85_row2_col21,#T_1fc85_row2_col22,#T_1fc85_row2_col23,#T_1fc85_row3_col0,#T_1fc85_row3_col1,#T_1fc85_row3_col2,#T_1fc85_row3_col3,#T_1fc85_row3_col4,#T_1fc85_row3_col5,#T_1fc85_row3_col6,#T_1fc85_row3_col7,#T_1fc85_row3_col8,#T_1fc85_row3_col9,#T_1fc85_row3_col10,#T_1fc85_row3_col11,#T_1fc85_row3_col12,#T_1fc85_row3_col13,#T_1fc85_row3_col14,#T_1fc85_row3_col15,#T_1fc85_row3_col16,#T_1fc85_row3_col17,#T_1fc85_row3_col18,#T_1fc85_row3_col19,#T_1fc85_row3_col20,#T_1fc85_row3_col21,#T_1fc85_row3_col22,#T_1fc85_row3_col23,#T_1fc85_row4_col0,#T_1fc85_row4_col1,#T_1fc85_row4_col2,#T_1fc85_row4_col3,#T_1fc85_row4_col4,#T_1fc85_row4_col5,#T_1fc85_row4_col6,#T_1fc85_row4_col7,#T_1fc85_row4_col8,#T_1fc85_row4_col9,#T_1fc85_row4_col10,#T_1fc85_row4_col11,#T_1fc85_row4_col12,#T_1fc85_row4_col13,#T_1fc85_row4_col14,#T_1fc85_row4_col15,#T_1fc85_row4_col16,#T_1fc85_row4_col17,#T_1fc85_row4_col18,#T_1fc85_row4_col19,#T_1fc85_row4_col20,#T_1fc85_row4_col21,#T_1fc85_row4_col22,#T_1fc85_row4_col23,#T_1fc85_row5_col0,#T_1fc85_row5_col1,#T_1fc85_row5_col2,#T_1fc85_row5_col3,#T_1fc85_row5_col4,#T_1fc85_row5_col5,#T_1fc85_row5_col6,#T_1fc85_row5_col7,#T_1fc85_row5_col8,#T_1fc85_row5_col9,#T_1fc85_row5_col10,#T_1fc85_row5_col11,#T_1fc85_row5_col12,#T_1fc85_row5_col13,#T_1fc85_row5_col14,#T_1fc85_row5_col15,#T_1fc85_row5_col16,#T_1fc85_row5_col17,#T_1fc85_row5_col18,#T_1fc85_row5_col19,#T_1fc85_row5_col20,#T_1fc85_row5_col21,#T_1fc85_row5_col22,#T_1fc85_row5_col23,#T_1fc85_row6_col0,#T_1fc85_row6_col1,#T_1fc85_row6_col2,#T_1fc85_row6_col3,#T_1fc85_row6_col4,#T_1fc85_row6_col5,#T_1fc85_row6_col6,#T_1fc85_row6_col7,#T_1fc85_row6_col8,#T_1fc85_row6_col9,#T_1fc85_row6_col10,#T_1fc85_row6_col11,#T_1fc85_row6_col12,#T_1fc85_row6_col13,#T_1fc85_row6_col14,#T_1fc85_row6_col15,#T_1fc85_row6_col16,#T_1fc85_row6_col17,#T_1fc85_row6_col18,#T_1fc85_row6_col19,#T_1fc85_row6_col20,#T_1fc85_row6_col21,#T_1fc85_row6_col22,#T_1fc85_row6_col23,#T_1fc85_row7_col0,#T_1fc85_row7_col1,#T_1fc85_row7_col2,#T_1fc85_row7_col3,#T_1fc85_row7_col4,#T_1fc85_row7_col5,#T_1fc85_row7_col6,#T_1fc85_row7_col7,#T_1fc85_row7_col8,#T_1fc85_row7_col9,#T_1fc85_row7_col10,#T_1fc85_row7_col11,#T_1fc85_row7_col12,#T_1fc85_row7_col13,#T_1fc85_row7_col14,#T_1fc85_row7_col15,#T_1fc85_row7_col16,#T_1fc85_row7_col17,#T_1fc85_row7_col18,#T_1fc85_row7_col19,#T_1fc85_row7_col20,#T_1fc85_row7_col21,#T_1fc85_row7_col22,#T_1fc85_row8_col0,#T_1fc85_row8_col1,#T_1fc85_row8_col2,#T_1fc85_row8_col3,#T_1fc85_row8_col4,#T_1fc85_row8_col5,#T_1fc85_row8_col6,#T_1fc85_row8_col7,#T_1fc85_row8_col8,#T_1fc85_row8_col9,#T_1fc85_row8_col10,#T_1fc85_row8_col11,#T_1fc85_row8_col12,#T_1fc85_row8_col13,#T_1fc85_row8_col14,#T_1fc85_row8_col15,#T_1fc85_row8_col16,#T_1fc85_row8_col17,#T_1fc85_row8_col18,#T_1fc85_row8_col19,#T_1fc85_row8_col20,#T_1fc85_row8_col21,#T_1fc85_row8_col22,#T_1fc85_row8_col23,#T_1fc85_row9_col0,#T_1fc85_row9_col1,#T_1fc85_row9_col2,#T_1fc85_row9_col3,#T_1fc85_row9_col4,#T_1fc85_row9_col5,#T_1fc85_row9_col6,#T_1fc85_row9_col7,#T_1fc85_row9_col8,#T_1fc85_row9_col9,#T_1fc85_row9_col10,#T_1fc85_row9_col11,#T_1fc85_row9_col12,#T_1fc85_row9_col14,#T_1fc85_row9_col15,#T_1fc85_row9_col16,#T_1fc85_row9_col17,#T_1fc85_row9_col18,#T_1fc85_row9_col19,#T_1fc85_row9_col20,#T_1fc85_row9_col22,#T_1fc85_row9_col23,#T_1fc85_row10_col0,#T_1fc85_row10_col1,#T_1fc85_row10_col2,#T_1fc85_row10_col3,#T_1fc85_row10_col4,#T_1fc85_row10_col5,#T_1fc85_row10_col6,#T_1fc85_row10_col7,#T_1fc85_row10_col8,#T_1fc85_row10_col9,#T_1fc85_row10_col10,#T_1fc85_row10_col11,#T_1fc85_row10_col12,#T_1fc85_row10_col13,#T_1fc85_row10_col14,#T_1fc85_row10_col15,#T_1fc85_row10_col16,#T_1fc85_row10_col17,#T_1fc85_row10_col18,#T_1fc85_row10_col19,#T_1fc85_row10_col20,#T_1fc85_row10_col21,#T_1fc85_row10_col22,#T_1fc85_row11_col0,#T_1fc85_row11_col1,#T_1fc85_row11_col2,#T_1fc85_row11_col3,#T_1fc85_row11_col4,#T_1fc85_row11_col5,#T_1fc85_row11_col6,#T_1fc85_row11_col7,#T_1fc85_row11_col8,#T_1fc85_row11_col9,#T_1fc85_row11_col10,#T_1fc85_row11_col11,#T_1fc85_row11_col12,#T_1fc85_row11_col13,#T_1fc85_row11_col14,#T_1fc85_row11_col15,#T_1fc85_row11_col16,#T_1fc85_row11_col17,#T_1fc85_row11_col18,#T_1fc85_row11_col19,#T_1fc85_row11_col20,#T_1fc85_row11_col21,#T_1fc85_row11_col22,#T_1fc85_row11_col23,#T_1fc85_row12_col0,#T_1fc85_row12_col1,#T_1fc85_row12_col2,#T_1fc85_row12_col3,#T_1fc85_row12_col4,#T_1fc85_row12_col5,#T_1fc85_row12_col6,#T_1fc85_row12_col7,#T_1fc85_row12_col8,#T_1fc85_row12_col9,#T_1fc85_row12_col10,#T_1fc85_row12_col11,#T_1fc85_row12_col12,#T_1fc85_row12_col13,#T_1fc85_row12_col14,#T_1fc85_row12_col15,#T_1fc85_row12_col16,#T_1fc85_row12_col17,#T_1fc85_row12_col18,#T_1fc85_row12_col19,#T_1fc85_row12_col20,#T_1fc85_row12_col21,#T_1fc85_row12_col22,#T_1fc85_row12_col23,#T_1fc85_row13_col0,#T_1fc85_row13_col1,#T_1fc85_row13_col2,#T_1fc85_row13_col3,#T_1fc85_row13_col4,#T_1fc85_row13_col5,#T_1fc85_row13_col6,#T_1fc85_row13_col7,#T_1fc85_row13_col8,#T_1fc85_row13_col9,#T_1fc85_row13_col10,#T_1fc85_row13_col11,#T_1fc85_row13_col12,#T_1fc85_row13_col13,#T_1fc85_row13_col14,#T_1fc85_row13_col15,#T_1fc85_row13_col16,#T_1fc85_row13_col17,#T_1fc85_row13_col18,#T_1fc85_row13_col19,#T_1fc85_row13_col20,#T_1fc85_row13_col21,#T_1fc85_row13_col22,#T_1fc85_row14_col0,#T_1fc85_row14_col1,#T_1fc85_row14_col2,#T_1fc85_row14_col3,#T_1fc85_row14_col4,#T_1fc85_row14_col5,#T_1fc85_row14_col6,#T_1fc85_row14_col7,#T_1fc85_row14_col8,#T_1fc85_row14_col9,#T_1fc85_row14_col10,#T_1fc85_row14_col11,#T_1fc85_row14_col12,#T_1fc85_row14_col13,#T_1fc85_row14_col14,#T_1fc85_row14_col15,#T_1fc85_row14_col16,#T_1fc85_row14_col17,#T_1fc85_row14_col18,#T_1fc85_row14_col19,#T_1fc85_row14_col20,#T_1fc85_row14_col21,#T_1fc85_row14_col22,#T_1fc85_row14_col23,#T_1fc85_row15_col0,#T_1fc85_row15_col1,#T_1fc85_row15_col2,#T_1fc85_row15_col3,#T_1fc85_row15_col4,#T_1fc85_row15_col5,#T_1fc85_row15_col6,#T_1fc85_row15_col7,#T_1fc85_row15_col8,#T_1fc85_row15_col9,#T_1fc85_row15_col10,#T_1fc85_row15_col11,#T_1fc85_row15_col12,#T_1fc85_row15_col13,#T_1fc85_row15_col14,#T_1fc85_row15_col15,#T_1fc85_row15_col16,#T_1fc85_row15_col17,#T_1fc85_row15_col18,#T_1fc85_row15_col19,#T_1fc85_row15_col20,#T_1fc85_row15_col21,#T_1fc85_row15_col22,#T_1fc85_row16_col0,#T_1fc85_row16_col1,#T_1fc85_row16_col2,#T_1fc85_row16_col3,#T_1fc85_row16_col4,#T_1fc85_row16_col5,#T_1fc85_row16_col6,#T_1fc85_row16_col7,#T_1fc85_row16_col8,#T_1fc85_row16_col9,#T_1fc85_row16_col10,#T_1fc85_row16_col11,#T_1fc85_row16_col12,#T_1fc85_row16_col13,#T_1fc85_row16_col14,#T_1fc85_row16_col15,#T_1fc85_row16_col16,#T_1fc85_row16_col17,#T_1fc85_row16_col18,#T_1fc85_row16_col19,#T_1fc85_row16_col20,#T_1fc85_row16_col21,#T_1fc85_row16_col22,#T_1fc85_row17_col0,#T_1fc85_row17_col1,#T_1fc85_row17_col2,#T_1fc85_row17_col3,#T_1fc85_row17_col4,#T_1fc85_row17_col5,#T_1fc85_row17_col6,#T_1fc85_row17_col7,#T_1fc85_row17_col8,#T_1fc85_row17_col9,#T_1fc85_row17_col10,#T_1fc85_row17_col11,#T_1fc85_row17_col12,#T_1fc85_row17_col13,#T_1fc85_row17_col14,#T_1fc85_row17_col15,#T_1fc85_row17_col16,#T_1fc85_row17_col17,#T_1fc85_row17_col18,#T_1fc85_row17_col19,#T_1fc85_row17_col20,#T_1fc85_row17_col21,#T_1fc85_row17_col22,#T_1fc85_row18_col0,#T_1fc85_row18_col1,#T_1fc85_row18_col2,#T_1fc85_row18_col3,#T_1fc85_row18_col4,#T_1fc85_row18_col5,#T_1fc85_row18_col6,#T_1fc85_row18_col7,#T_1fc85_row18_col8,#T_1fc85_row18_col9,#T_1fc85_row18_col10,#T_1fc85_row18_col11,#T_1fc85_row18_col12,#T_1fc85_row18_col13,#T_1fc85_row18_col14,#T_1fc85_row18_col15,#T_1fc85_row18_col16,#T_1fc85_row18_col17,#T_1fc85_row18_col18,#T_1fc85_row18_col19,#T_1fc85_row18_col20,#T_1fc85_row18_col21,#T_1fc85_row18_col22,#T_1fc85_row19_col0,#T_1fc85_row19_col1,#T_1fc85_row19_col2,#T_1fc85_row19_col3,#T_1fc85_row19_col4,#T_1fc85_row19_col5,#T_1fc85_row19_col6,#T_1fc85_row19_col7,#T_1fc85_row19_col8,#T_1fc85_row19_col9,#T_1fc85_row19_col10,#T_1fc85_row19_col11,#T_1fc85_row19_col12,#T_1fc85_row19_col13,#T_1fc85_row19_col14,#T_1fc85_row19_col15,#T_1fc85_row19_col16,#T_1fc85_row19_col17,#T_1fc85_row19_col18,#T_1fc85_row19_col19,#T_1fc85_row19_col20,#T_1fc85_row19_col21,#T_1fc85_row19_col22,#T_1fc85_row20_col0,#T_1fc85_row20_col1,#T_1fc85_row20_col2,#T_1fc85_row20_col3,#T_1fc85_row20_col4,#T_1fc85_row20_col5,#T_1fc85_row20_col6,#T_1fc85_row20_col7,#T_1fc85_row20_col8,#T_1fc85_row20_col9,#T_1fc85_row20_col10,#T_1fc85_row20_col11,#T_1fc85_row20_col12,#T_1fc85_row20_col13,#T_1fc85_row20_col14,#T_1fc85_row20_col15,#T_1fc85_row20_col16,#T_1fc85_row20_col17,#T_1fc85_row20_col18,#T_1fc85_row20_col19,#T_1fc85_row20_col20,#T_1fc85_row20_col21,#T_1fc85_row20_col22,#T_1fc85_row20_col23,#T_1fc85_row21_col0,#T_1fc85_row21_col1,#T_1fc85_row21_col2,#T_1fc85_row21_col3,#T_1fc85_row21_col4,#T_1fc85_row21_col5,#T_1fc85_row21_col6,#T_1fc85_row21_col7,#T_1fc85_row21_col8,#T_1fc85_row21_col9,#T_1fc85_row21_col10,#T_1fc85_row21_col11,#T_1fc85_row21_col12,#T_1fc85_row21_col13,#T_1fc85_row21_col14,#T_1fc85_row21_col15,#T_1fc85_row21_col16,#T_1fc85_row21_col17,#T_1fc85_row21_col18,#T_1fc85_row21_col19,#T_1fc85_row21_col20,#T_1fc85_row21_col21,#T_1fc85_row21_col22,#T_1fc85_row22_col0,#T_1fc85_row22_col1,#T_1fc85_row22_col2,#T_1fc85_row22_col3,#T_1fc85_row22_col4,#T_1fc85_row22_col5,#T_1fc85_row22_col6,#T_1fc85_row22_col7,#T_1fc85_row22_col8,#T_1fc85_row22_col9,#T_1fc85_row22_col10,#T_1fc85_row22_col11,#T_1fc85_row22_col12,#T_1fc85_row22_col13,#T_1fc85_row22_col14,#T_1fc85_row22_col15,#T_1fc85_row22_col16,#T_1fc85_row22_col17,#T_1fc85_row22_col18,#T_1fc85_row22_col19,#T_1fc85_row22_col20,#T_1fc85_row22_col21,#T_1fc85_row22_col22,#T_1fc85_row23_col0,#T_1fc85_row23_col1,#T_1fc85_row23_col2,#T_1fc85_row23_col3,#T_1fc85_row23_col4,#T_1fc85_row23_col5,#T_1fc85_row23_col6,#T_1fc85_row23_col7,#T_1fc85_row23_col8,#T_1fc85_row23_col9,#T_1fc85_row23_col10,#T_1fc85_row23_col11,#T_1fc85_row23_col12,#T_1fc85_row23_col13,#T_1fc85_row23_col14,#T_1fc85_row23_col15,#T_1fc85_row23_col16,#T_1fc85_row23_col17,#T_1fc85_row23_col18,#T_1fc85_row23_col19,#T_1fc85_row23_col20,#T_1fc85_row23_col21,#T_1fc85_row23_col22,#T_1fc85_row23_col23,#T_1fc85_row24_col0,#T_1fc85_row24_col1,#T_1fc85_row24_col2,#T_1fc85_row24_col3,#T_1fc85_row24_col4,#T_1fc85_row24_col5,#T_1fc85_row24_col6,#T_1fc85_row24_col7,#T_1fc85_row24_col8,#T_1fc85_row24_col9,#T_1fc85_row24_col10,#T_1fc85_row24_col11,#T_1fc85_row24_col12,#T_1fc85_row24_col13,#T_1fc85_row24_col14,#T_1fc85_row24_col15,#T_1fc85_row24_col16,#T_1fc85_row24_col17,#T_1fc85_row24_col18,#T_1fc85_row24_col19,#T_1fc85_row24_col20,#T_1fc85_row24_col21,#T_1fc85_row24_col22,#T_1fc85_row25_col0,#T_1fc85_row25_col1,#T_1fc85_row25_col2,#T_1fc85_row25_col3,#T_1fc85_row25_col4,#T_1fc85_row25_col5,#T_1fc85_row25_col6,#T_1fc85_row25_col7,#T_1fc85_row25_col8,#T_1fc85_row25_col9,#T_1fc85_row25_col10,#T_1fc85_row25_col11,#T_1fc85_row25_col12,#T_1fc85_row25_col13,#T_1fc85_row25_col14,#T_1fc85_row25_col15,#T_1fc85_row25_col16,#T_1fc85_row25_col17,#T_1fc85_row25_col18,#T_1fc85_row25_col19,#T_1fc85_row25_col20,#T_1fc85_row25_col21,#T_1fc85_row25_col22{
            color:  black;
        }#T_1fc85_row7_col23,#T_1fc85_row9_col13,#T_1fc85_row9_col21,#T_1fc85_row10_col23,#T_1fc85_row13_col23,#T_1fc85_row15_col23,#T_1fc85_row16_col23,#T_1fc85_row17_col23,#T_1fc85_row18_col23,#T_1fc85_row19_col23,#T_1fc85_row21_col23,#T_1fc85_row22_col23,#T_1fc85_row24_col23,#T_1fc85_row25_col23{
            color:  red;
        }</style><table id="T_1fc85_" ><thead>    <tr>        <th class="blank level0" ></th>        <th class="col_heading level0 col0" >名称</th>        <th class="col_heading level0 col1" >行业</th>        <th class="col_heading level0 col2" >负债率</th>        <th class="col_heading level0 col3" >应收比</th>        <th class="col_heading level0 col4" >商誉比</th>        <th class="col_heading level0 col5" >ROE</th>        <th class="col_heading level0 col6" >利润率</th>        <th class="col_heading level0 col7" >收入</th>        <th class="col_heading level0 col8" >收入增长</th>        <th class="col_heading level0 col9" >收入波动</th>        <th class="col_heading level0 col10" >盈利</th>        <th class="col_heading level0 col11" >盈利增长</th>        <th class="col_heading level0 col12" >盈利波动</th>        <th class="col_heading level0 col13" >FCF</th>        <th class="col_heading level0 col14" >FCF增长</th>        <th class="col_heading level0 col15" >FCF波动</th>        <th class="col_heading level0 col16" >PE</th>        <th class="col_heading level0 col17" >PE0</th>        <th class="col_heading level0 col18" >PEG</th>        <th class="col_heading level0 col19" >股息率</th>        <th class="col_heading level0 col20" >市值</th>        <th class="col_heading level0 col21" >DCF</th>        <th class="col_heading level0 col22" >盈利折现</th>        <th class="col_heading level0 col23" >折价率</th>    </tr>    <tr>        <th class="index_name level0" >Symbol</th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>    </tr></thead><tbody>
                <tr>
                        <th id="T_1fc85_level0_row0" class="row_heading level0 row0" >TSM</th>
                        <td id="T_1fc85_row0_col0" class="data row0 col0" >Taiwan Semiconductor</td>
                        <td id="T_1fc85_row0_col1" class="data row0 col1" >Technology</td>
                        <td id="T_1fc85_row0_col2" class="data row0 col2" >32.97</td>
                        <td id="T_1fc85_row0_col3" class="data row0 col3" >10.91</td>
                        <td id="T_1fc85_row0_col4" class="data row0 col4" >0.29</td>
                        <td id="T_1fc85_row0_col5" class="data row0 col5" >23.33</td>
                        <td id="T_1fc85_row0_col6" class="data row0 col6" >35.07</td>
                        <td id="T_1fc85_row0_col7" class="data row0 col7" >1,104,540.25</td>
                        <td id="T_1fc85_row0_col8" class="data row0 col8" >11.48</td>
                        <td id="T_1fc85_row0_col9" class="data row0 col9" >11.89</td>
                        <td id="T_1fc85_row0_col10" class="data row0 col10" >389,819.56</td>
                        <td id="T_1fc85_row0_col11" class="data row0 col11" >16.70</td>
                        <td id="T_1fc85_row0_col12" class="data row0 col12" >28.89</td>
                        <td id="T_1fc85_row0_col13" class="data row0 col13" >245,811.63</td>
                        <td id="T_1fc85_row0_col14" class="data row0 col14" >21.73</td>
                        <td id="T_1fc85_row0_col15" class="data row0 col15" >74.11</td>
                        <td id="T_1fc85_row0_col16" class="data row0 col16" >32.04</td>
                        <td id="T_1fc85_row0_col17" class="data row0 col17" >1.46</td>
                        <td id="T_1fc85_row0_col18" class="data row0 col18" >0.09</td>
                        <td id="T_1fc85_row0_col19" class="data row0 col19" >-</td>
                        <td id="T_1fc85_row0_col20" class="data row0 col20" >569,517.74</td>
                        <td id="T_1fc85_row0_col21" class="data row0 col21" >5,416,260.72</td>
                        <td id="T_1fc85_row0_col22" class="data row0 col22" >7,625,607.83</td>
                        <td id="T_1fc85_row0_col23" class="data row0 col23" >89.49</td>
            </tr>
            <tr>
                        <th id="T_1fc85_level0_row1" class="row_heading level0 row1" >INVA</th>
                        <td id="T_1fc85_row1_col0" class="data row1 col0" >Innoviva Inc. Common</td>
                        <td id="T_1fc85_row1_col1" class="data row1 col1" >Health Care</td>
                        <td id="T_1fc85_row1_col2" class="data row1 col2" >39.19</td>
                        <td id="T_1fc85_row1_col3" class="data row1 col3" >27.89</td>
                        <td id="T_1fc85_row1_col4" class="data row1 col4" >-</td>
                        <td id="T_1fc85_row1_col5" class="data row1 col5" >73.43</td>
                        <td id="T_1fc85_row1_col6" class="data row1 col6" >85.00</td>
                        <td id="T_1fc85_row1_col7" class="data row1 col7" >269.01</td>
                        <td id="T_1fc85_row1_col8" class="data row1 col8" >16.40</td>
                        <td id="T_1fc85_row1_col9" class="data row1 col9" >14.87</td>
                        <td id="T_1fc85_row1_col10" class="data row1 col10" >227.72</td>
                        <td id="T_1fc85_row1_col11" class="data row1 col11" >59.00</td>
                        <td id="T_1fc85_row1_col12" class="data row1 col12" >128.13</td>
                        <td id="T_1fc85_row1_col13" class="data row1 col13" >233.95</td>
                        <td id="T_1fc85_row1_col14" class="data row1 col14" >31.50</td>
                        <td id="T_1fc85_row1_col15" class="data row1 col15" >22.92</td>
                        <td id="T_1fc85_row1_col16" class="data row1 col16" >5.72</td>
                        <td id="T_1fc85_row1_col17" class="data row1 col17" >5.78</td>
                        <td id="T_1fc85_row1_col18" class="data row1 col18" >0.10</td>
                        <td id="T_1fc85_row1_col19" class="data row1 col19" >-</td>
                        <td id="T_1fc85_row1_col20" class="data row1 col20" >1,316.28</td>
                        <td id="T_1fc85_row1_col21" class="data row1 col21" >6,417.00</td>
                        <td id="T_1fc85_row1_col22" class="data row1 col22" >10,762.22</td>
                        <td id="T_1fc85_row1_col23" class="data row1 col23" >79.49</td>
            </tr>
            <tr>
                        <th id="T_1fc85_level0_row2" class="row_heading level0 row2" >VRTX</th>
                        <td id="T_1fc85_row2_col0" class="data row2 col0" >Vertex Pharmaceutica</td>
                        <td id="T_1fc85_row2_col1" class="data row2 col1" >Health Care</td>
                        <td id="T_1fc85_row2_col2" class="data row2 col2" >26.08</td>
                        <td id="T_1fc85_row2_col3" class="data row2 col3" >14.27</td>
                        <td id="T_1fc85_row2_col4" class="data row2 col4" >11.54</td>
                        <td id="T_1fc85_row2_col5" class="data row2 col5" >27.71</td>
                        <td id="T_1fc85_row2_col6" class="data row2 col6" >37.84</td>
                        <td id="T_1fc85_row2_col7" class="data row2 col7" >3,976.19</td>
                        <td id="T_1fc85_row2_col8" class="data row2 col8" >36.04</td>
                        <td id="T_1fc85_row2_col9" class="data row2 col9" >13.32</td>
                        <td id="T_1fc85_row2_col10" class="data row2 col10" >1,562.21</td>
                        <td id="T_1fc85_row2_col11" class="data row2 col11" >260.79</td>
                        <td id="T_1fc85_row2_col12" class="data row2 col12" >386.71</td>
                        <td id="T_1fc85_row2_col13" class="data row2 col13" >1,601.99</td>
                        <td id="T_1fc85_row2_col14" class="data row2 col14" >61.71</td>
                        <td id="T_1fc85_row2_col15" class="data row2 col15" >36.80</td>
                        <td id="T_1fc85_row2_col16" class="data row2 col16" >20.01</td>
                        <td id="T_1fc85_row2_col17" class="data row2 col17" >34.79</td>
                        <td id="T_1fc85_row2_col18" class="data row2 col18" >0.13</td>
                        <td id="T_1fc85_row2_col19" class="data row2 col19" >-</td>
                        <td id="T_1fc85_row2_col20" class="data row2 col20" >54,343.74</td>
                        <td id="T_1fc85_row2_col21" class="data row2 col21" >79,503.88</td>
                        <td id="T_1fc85_row2_col22" class="data row2 col22" >815,403.48</td>
                        <td id="T_1fc85_row2_col23" class="data row2 col23" >31.65</td>
            </tr>
            <tr>
                        <th id="T_1fc85_level0_row3" class="row_heading level0 row3" >GMAB</th>
                        <td id="T_1fc85_row3_col0" class="data row3 col0" >Genmab A/S ADS</td>
                        <td id="T_1fc85_row3_col1" class="data row3 col1" >Health Care</td>
                        <td id="T_1fc85_row3_col2" class="data row3 col2" >9.56</td>
                        <td id="T_1fc85_row3_col3" class="data row3 col3" >26.82</td>
                        <td id="T_1fc85_row3_col4" class="data row3 col4" >-</td>
                        <td id="T_1fc85_row3_col5" class="data row3 col5" >19.07</td>
                        <td id="T_1fc85_row3_col6" class="data row3 col6" >45.68</td>
                        <td id="T_1fc85_row3_col7" class="data row3 col7" >5,216.86</td>
                        <td id="T_1fc85_row3_col8" class="data row3 col8" >64.57</td>
                        <td id="T_1fc85_row3_col9" class="data row3 col9" >32.24</td>
                        <td id="T_1fc85_row3_col10" class="data row3 col10" >2,374.89</td>
                        <td id="T_1fc85_row3_col11" class="data row3 col11" >66.73</td>
                        <td id="T_1fc85_row3_col12" class="data row3 col12" >46.36</td>
                        <td id="T_1fc85_row3_col13" class="data row3 col13" >2,454.12</td>
                        <td id="T_1fc85_row3_col14" class="data row3 col14" >128.78</td>
                        <td id="T_1fc85_row3_col15" class="data row3 col15" >229.94</td>
                        <td id="T_1fc85_row3_col16" class="data row3 col16" >-</td>
                        <td id="T_1fc85_row3_col17" class="data row3 col17" >11.42</td>
                        <td id="T_1fc85_row3_col18" class="data row3 col18" >0.17</td>
                        <td id="T_1fc85_row3_col19" class="data row3 col19" >-</td>
                        <td id="T_1fc85_row3_col20" class="data row3 col20" >27,129.13</td>
                        <td id="T_1fc85_row3_col21" class="data row3 col21" >334,308.01</td>
                        <td id="T_1fc85_row3_col22" class="data row3 col22" >128,743.73</td>
                        <td id="T_1fc85_row3_col23" class="data row3 col23" >91.88</td>
            </tr>
            <tr>
                        <th id="T_1fc85_level0_row4" class="row_heading level0 row4" >AFYA</th>
                        <td id="T_1fc85_row4_col0" class="data row4 col0" >Afya Limited Class A</td>
                        <td id="T_1fc85_row4_col1" class="data row4 col1" >Consumer Services</td>
                        <td id="T_1fc85_row4_col2" class="data row4 col2" >40.88</td>
                        <td id="T_1fc85_row4_col3" class="data row4 col3" >26.92</td>
                        <td id="T_1fc85_row4_col4" class="data row4 col4" >29.14</td>
                        <td id="T_1fc85_row4_col5" class="data row4 col5" >33.40</td>
                        <td id="T_1fc85_row4_col6" class="data row4 col6" >22.92</td>
                        <td id="T_1fc85_row4_col7" class="data row4 col7" >625.44</td>
                        <td id="T_1fc85_row4_col8" class="data row4 col8" >79.80</td>
                        <td id="T_1fc85_row4_col9" class="data row4 col9" >39.05</td>
                        <td id="T_1fc85_row4_col10" class="data row4 col10" >144.43</td>
                        <td id="T_1fc85_row4_col11" class="data row4 col11" >86.08</td>
                        <td id="T_1fc85_row4_col12" class="data row4 col12" >6.79</td>
                        <td id="T_1fc85_row4_col13" class="data row4 col13" >152.19</td>
                        <td id="T_1fc85_row4_col14" class="data row4 col14" >158.53</td>
                        <td id="T_1fc85_row4_col15" class="data row4 col15" >138.40</td>
                        <td id="T_1fc85_row4_col16" class="data row4 col16" >-</td>
                        <td id="T_1fc85_row4_col17" class="data row4 col17" >15.96</td>
                        <td id="T_1fc85_row4_col18" class="data row4 col18" >0.19</td>
                        <td id="T_1fc85_row4_col19" class="data row4 col19" >-</td>
                        <td id="T_1fc85_row4_col20" class="data row4 col20" >2,304.95</td>
                        <td id="T_1fc85_row4_col21" class="data row4 col21" >29,683.84</td>
                        <td id="T_1fc85_row4_col22" class="data row4 col22" >10,763.92</td>
                        <td id="T_1fc85_row4_col23" class="data row4 col23" >92.24</td>
            </tr>
            <tr>
                        <th id="T_1fc85_level0_row5" class="row_heading level0 row5" >EXEL</th>
                        <td id="T_1fc85_row5_col0" class="data row5 col0" >Exelixis Inc. Common</td>
                        <td id="T_1fc85_row5_col1" class="data row5 col1" >Health Care</td>
                        <td id="T_1fc85_row5_col2" class="data row5 col2" >12.08</td>
                        <td id="T_1fc85_row5_col3" class="data row5 col3" >16.75</td>
                        <td id="T_1fc85_row5_col4" class="data row5 col4" >3.39</td>
                        <td id="T_1fc85_row5_col5" class="data row5 col5" >33.18</td>
                        <td id="T_1fc85_row5_col6" class="data row5 col6" >39.85</td>
                        <td id="T_1fc85_row5_col7" class="data row5 col7" >815.40</td>
                        <td id="T_1fc85_row5_col8" class="data row5 col8" >34.70</td>
                        <td id="T_1fc85_row5_col9" class="data row5 col9" >47.11</td>
                        <td id="T_1fc85_row5_col10" class="data row5 col10" >319.27</td>
                        <td id="T_1fc85_row5_col11" class="data row5 col11" >76.26</td>
                        <td id="T_1fc85_row5_col12" class="data row5 col12" >234.92</td>
                        <td id="T_1fc85_row5_col13" class="data row5 col13" >304.91</td>
                        <td id="T_1fc85_row5_col14" class="data row5 col14" >44.63</td>
                        <td id="T_1fc85_row5_col15" class="data row5 col15" >115.32</td>
                        <td id="T_1fc85_row5_col16" class="data row5 col16" >63.91</td>
                        <td id="T_1fc85_row5_col17" class="data row5 col17" >21.94</td>
                        <td id="T_1fc85_row5_col18" class="data row5 col18" >0.29</td>
                        <td id="T_1fc85_row5_col19" class="data row5 col19" >-</td>
                        <td id="T_1fc85_row5_col20" class="data row5 col20" >7,004.00</td>
                        <td id="T_1fc85_row5_col21" class="data row5 col21" >10,976.35</td>
                        <td id="T_1fc85_row5_col22" class="data row5 col22" >20,328.36</td>
                        <td id="T_1fc85_row5_col23" class="data row5 col23" >36.19</td>
            </tr>
            <tr>
                        <th id="T_1fc85_level0_row6" class="row_heading level0 row6" >KL</th>
                        <td id="T_1fc85_row6_col0" class="data row6 col0" >Kirkland Lake Gold L</td>
                        <td id="T_1fc85_row6_col1" class="data row6 col1" >-</td>
                        <td id="T_1fc85_row6_col2" class="data row6 col2" >28.18</td>
                        <td id="T_1fc85_row6_col3" class="data row6 col3" >0.94</td>
                        <td id="T_1fc85_row6_col4" class="data row6 col4" >-</td>
                        <td id="T_1fc85_row6_col5" class="data row6 col5" >19.86</td>
                        <td id="T_1fc85_row6_col6" class="data row6 col6" >30.06</td>
                        <td id="T_1fc85_row6_col7" class="data row6 col7" >1,375.87</td>
                        <td id="T_1fc85_row6_col8" class="data row6 col8" >50.49</td>
                        <td id="T_1fc85_row6_col9" class="data row6 col9" >27.87</td>
                        <td id="T_1fc85_row6_col10" class="data row6 col10" >438.54</td>
                        <td id="T_1fc85_row6_col11" class="data row6 col11" >83.99</td>
                        <td id="T_1fc85_row6_col12" class="data row6 col12" >37.56</td>
                        <td id="T_1fc85_row6_col13" class="data row6 col13" >409.60</td>
                        <td id="T_1fc85_row6_col14" class="data row6 col14" >63.22</td>
                        <td id="T_1fc85_row6_col15" class="data row6 col15" >5.53</td>
                        <td id="T_1fc85_row6_col16" class="data row6 col16" >14.71</td>
                        <td id="T_1fc85_row6_col17" class="data row6 col17" >26.13</td>
                        <td id="T_1fc85_row6_col18" class="data row6 col18" >0.31</td>
                        <td id="T_1fc85_row6_col19" class="data row6 col19" >-</td>
                        <td id="T_1fc85_row6_col20" class="data row6 col20" >11,460.34</td>
                        <td id="T_1fc85_row6_col21" class="data row6 col21" >20,878.80</td>
                        <td id="T_1fc85_row6_col22" class="data row6 col22" >31,624.92</td>
                        <td id="T_1fc85_row6_col23" class="data row6 col23" >45.11</td>
            </tr>
            <tr>
                        <th id="T_1fc85_level0_row7" class="row_heading level0 row7" >EA</th>
                        <td id="T_1fc85_row7_col0" class="data row7 col0" >Electronic Arts Inc.</td>
                        <td id="T_1fc85_row7_col1" class="data row7 col1" >Technology</td>
                        <td id="T_1fc85_row7_col2" class="data row7 col2" >32.86</td>
                        <td id="T_1fc85_row7_col3" class="data row7 col3" >8.33</td>
                        <td id="T_1fc85_row7_col4" class="data row7 col4" >25.26</td>
                        <td id="T_1fc85_row7_col5" class="data row7 col5" >26.59</td>
                        <td id="T_1fc85_row7_col6" class="data row7 col6" >28.92</td>
                        <td id="T_1fc85_row7_col7" class="data row7 col7" >5,120.50</td>
                        <td id="T_1fc85_row7_col8" class="data row7 col8" >4.76</td>
                        <td id="T_1fc85_row7_col9" class="data row7 col9" >7.98</td>
                        <td id="T_1fc85_row7_col10" class="data row7 col10" >1,517.00</td>
                        <td id="T_1fc85_row7_col11" class="data row7 col11" >67.93</td>
                        <td id="T_1fc85_row7_col12" class="data row7 col12" >112.96</td>
                        <td id="T_1fc85_row7_col13" class="data row7 col13" >1,531.25</td>
                        <td id="T_1fc85_row7_col14" class="data row7 col14" >5.02</td>
                        <td id="T_1fc85_row7_col15" class="data row7 col15" >13.41</td>
                        <td id="T_1fc85_row7_col16" class="data row7 col16" >35.90</td>
                        <td id="T_1fc85_row7_col17" class="data row7 col17" >27.53</td>
                        <td id="T_1fc85_row7_col18" class="data row7 col18" >0.41</td>
                        <td id="T_1fc85_row7_col19" class="data row7 col19" >-</td>
                        <td id="T_1fc85_row7_col20" class="data row7 col20" >41,766.17</td>
                        <td id="T_1fc85_row7_col21" class="data row7 col21" >22,293.12</td>
                        <td id="T_1fc85_row7_col22" class="data row7 col22" >83,955.51</td>
                        <td id="T_1fc85_row7_col23" class="data row7 col23" >-87.35</td>
            </tr>
            <tr>
                        <th id="T_1fc85_level0_row8" class="row_heading level0 row8" >INMD</th>
                        <td id="T_1fc85_row8_col0" class="data row8 col0" >InMode Ltd. Ordinary</td>
                        <td id="T_1fc85_row8_col1" class="data row8 col1" >Health Care</td>
                        <td id="T_1fc85_row8_col2" class="data row8 col2" >13.62</td>
                        <td id="T_1fc85_row8_col3" class="data row8 col3" >6.83</td>
                        <td id="T_1fc85_row8_col4" class="data row8 col4" >-</td>
                        <td id="T_1fc85_row8_col5" class="data row8 col5" >40.33</td>
                        <td id="T_1fc85_row8_col6" class="data row8 col6" >28.59</td>
                        <td id="T_1fc85_row8_col7" class="data row8 col7" >129.02</td>
                        <td id="T_1fc85_row8_col8" class="data row8 col8" >58.43</td>
                        <td id="T_1fc85_row8_col9" class="data row8 col9" >27.85</td>
                        <td id="T_1fc85_row8_col10" class="data row8 col10" >41.84</td>
                        <td id="T_1fc85_row8_col11" class="data row8 col11" >116.57</td>
                        <td id="T_1fc85_row8_col12" class="data row8 col12" >81.88</td>
                        <td id="T_1fc85_row8_col13" class="data row8 col13" >47.80</td>
                        <td id="T_1fc85_row8_col14" class="data row8 col14" >83.23</td>
                        <td id="T_1fc85_row8_col15" class="data row8 col15" >63.84</td>
                        <td id="T_1fc85_row8_col16" class="data row8 col16" >73.48</td>
                        <td id="T_1fc85_row8_col17" class="data row8 col17" >77.73</td>
                        <td id="T_1fc85_row8_col18" class="data row8 col18" >0.67</td>
                        <td id="T_1fc85_row8_col19" class="data row8 col19" >-</td>
                        <td id="T_1fc85_row8_col20" class="data row8 col20" >3,252.34</td>
                        <td id="T_1fc85_row8_col21" class="data row8 col21" >3,406.30</td>
                        <td id="T_1fc85_row8_col22" class="data row8 col22" >4,853.80</td>
                        <td id="T_1fc85_row8_col23" class="data row8 col23" >4.52</td>
            </tr>
            <tr>
                        <th id="T_1fc85_level0_row9" class="row_heading level0 row9" >KKR</th>
                        <td id="T_1fc85_row9_col0" class="data row9 col0" >KKR & Co. Inc. Commo</td>
                        <td id="T_1fc85_row9_col1" class="data row9 col1" >Finance</td>
                        <td id="T_1fc85_row9_col2" class="data row9 col2" >48.88</td>
                        <td id="T_1fc85_row9_col3" class="data row9 col3" >22.75</td>
                        <td id="T_1fc85_row9_col4" class="data row9 col4" >0.69</td>
                        <td id="T_1fc85_row9_col5" class="data row9 col5" >16.25</td>
                        <td id="T_1fc85_row9_col6" class="data row9 col6" >24.05</td>
                        <td id="T_1fc85_row9_col7" class="data row9 col7" >6,404.02</td>
                        <td id="T_1fc85_row9_col8" class="data row9 col8" >26.64</td>
                        <td id="T_1fc85_row9_col9" class="data row9 col9" >54.69</td>
                        <td id="T_1fc85_row9_col10" class="data row9 col10" >1,539.23</td>
                        <td id="T_1fc85_row9_col11" class="data row9 col11" >29.41</td>
                        <td id="T_1fc85_row9_col12" class="data row9 col12" >41.83</td>
                        <td id="T_1fc85_row9_col13" class="data row9 col13" >-5,834.65</td>
                        <td id="T_1fc85_row9_col14" class="data row9 col14" >30.83</td>
                        <td id="T_1fc85_row9_col15" class="data row9 col15" >71.97</td>
                        <td id="T_1fc85_row9_col16" class="data row9 col16" >16.42</td>
                        <td id="T_1fc85_row9_col17" class="data row9 col17" >20.75</td>
                        <td id="T_1fc85_row9_col18" class="data row9 col18" >0.71</td>
                        <td id="T_1fc85_row9_col19" class="data row9 col19" >2.93</td>
                        <td id="T_1fc85_row9_col20" class="data row9 col20" >31,944.25</td>
                        <td id="T_1fc85_row9_col21" class="data row9 col21" >-157,735.47</td>
                        <td id="T_1fc85_row9_col22" class="data row9 col22" >40,336.41</td>
                        <td id="T_1fc85_row9_col23" class="data row9 col23" >-</td>
            </tr>
            <tr>
                        <th id="T_1fc85_level0_row10" class="row_heading level0 row10" >NTES</th>
                        <td id="T_1fc85_row10_col0" class="data row10 col0" >NetEase Inc. America</td>
                        <td id="T_1fc85_row10_col1" class="data row10 col1" >Miscellaneous</td>
                        <td id="T_1fc85_row10_col2" class="data row10 col2" >33.89</td>
                        <td id="T_1fc85_row10_col3" class="data row10 col3" >8.99</td>
                        <td id="T_1fc85_row10_col4" class="data row10 col4" >0.39</td>
                        <td id="T_1fc85_row10_col5" class="data row10 col5" >21.57</td>
                        <td id="T_1fc85_row10_col6" class="data row10 col6" >22.09</td>
                        <td id="T_1fc85_row10_col7" class="data row10 col7" >57,131.05</td>
                        <td id="T_1fc85_row10_col8" class="data row10 col8" >18.43</td>
                        <td id="T_1fc85_row10_col9" class="data row10 col9" >5.14</td>
                        <td id="T_1fc85_row10_col10" class="data row10 col10" >12,540.15</td>
                        <td id="T_1fc85_row10_col11" class="data row10 col11" >53.15</td>
                        <td id="T_1fc85_row10_col12" class="data row10 col12" >166.31</td>
                        <td id="T_1fc85_row10_col13" class="data row10 col13" >15,330.20</td>
                        <td id="T_1fc85_row10_col14" class="data row10 col14" >33.70</td>
                        <td id="T_1fc85_row10_col15" class="data row10 col15" >20.88</td>
                        <td id="T_1fc85_row10_col16" class="data row10 col16" >41.17</td>
                        <td id="T_1fc85_row10_col17" class="data row10 col17" >39.74</td>
                        <td id="T_1fc85_row10_col18" class="data row10 col18" >0.75</td>
                        <td id="T_1fc85_row10_col19" class="data row10 col19" >1.18</td>
                        <td id="T_1fc85_row10_col20" class="data row10 col20" >498,369.16</td>
                        <td id="T_1fc85_row10_col21" class="data row10 col21" >440,855.12</td>
                        <td id="T_1fc85_row10_col22" class="data row10 col22" >532,030.60</td>
                        <td id="T_1fc85_row10_col23" class="data row10 col23" >-13.05</td>
            </tr>
            <tr>
                        <th id="T_1fc85_level0_row11" class="row_heading level0 row11" >EDTK</th>
                        <td id="T_1fc85_row11_col0" class="data row11 col0" >Skillful Craftsman E</td>
                        <td id="T_1fc85_row11_col1" class="data row11 col1" >Consumer Services</td>
                        <td id="T_1fc85_row11_col2" class="data row11 col2" >38.97</td>
                        <td id="T_1fc85_row11_col3" class="data row11 col3" >0.28</td>
                        <td id="T_1fc85_row11_col4" class="data row11 col4" >-</td>
                        <td id="T_1fc85_row11_col5" class="data row11 col5" >45.21</td>
                        <td id="T_1fc85_row11_col6" class="data row11 col6" >36.78</td>
                        <td id="T_1fc85_row11_col7" class="data row11 col7" >22.73</td>
                        <td id="T_1fc85_row11_col8" class="data row11 col8" >40.69</td>
                        <td id="T_1fc85_row11_col9" class="data row11 col9" >35.01</td>
                        <td id="T_1fc85_row11_col10" class="data row11 col10" >8.22</td>
                        <td id="T_1fc85_row11_col11" class="data row11 col11" >29.67</td>
                        <td id="T_1fc85_row11_col12" class="data row11 col12" >20.76</td>
                        <td id="T_1fc85_row11_col13" class="data row11 col13" >6.38</td>
                        <td id="T_1fc85_row11_col14" class="data row11 col14" >83.37</td>
                        <td id="T_1fc85_row11_col15" class="data row11 col15" >40.18</td>
                        <td id="T_1fc85_row11_col16" class="data row11 col16" >-</td>
                        <td id="T_1fc85_row11_col17" class="data row11 col17" >22.21</td>
                        <td id="T_1fc85_row11_col18" class="data row11 col18" >0.75</td>
                        <td id="T_1fc85_row11_col19" class="data row11 col19" >-</td>
                        <td id="T_1fc85_row11_col20" class="data row11 col20" >182.59</td>
                        <td id="T_1fc85_row11_col21" class="data row11 col21" >455.30</td>
                        <td id="T_1fc85_row11_col22" class="data row11 col22" >216.64</td>
                        <td id="T_1fc85_row11_col23" class="data row11 col23" >59.90</td>
            </tr>
            <tr>
                        <th id="T_1fc85_level0_row12" class="row_heading level0 row12" >HLG</th>
                        <td id="T_1fc85_row12_col0" class="data row12 col0" >Hailiang Education G</td>
                        <td id="T_1fc85_row12_col1" class="data row12 col1" >Consumer Services</td>
                        <td id="T_1fc85_row12_col2" class="data row12 col2" >27.00</td>
                        <td id="T_1fc85_row12_col3" class="data row12 col3" >5.67</td>
                        <td id="T_1fc85_row12_col4" class="data row12 col4" >3.04</td>
                        <td id="T_1fc85_row12_col5" class="data row12 col5" >17.04</td>
                        <td id="T_1fc85_row12_col6" class="data row12 col6" >20.82</td>
                        <td id="T_1fc85_row12_col7" class="data row12 col7" >1,251.07</td>
                        <td id="T_1fc85_row12_col8" class="data row12 col8" >21.38</td>
                        <td id="T_1fc85_row12_col9" class="data row12 col9" >19.96</td>
                        <td id="T_1fc85_row12_col10" class="data row12 col10" >263.65</td>
                        <td id="T_1fc85_row12_col11" class="data row12 col11" >30.30</td>
                        <td id="T_1fc85_row12_col12" class="data row12 col12" >3.42</td>
                        <td id="T_1fc85_row12_col13" class="data row12 col13" >401.58</td>
                        <td id="T_1fc85_row12_col14" class="data row12 col14" >51.62</td>
                        <td id="T_1fc85_row12_col15" class="data row12 col15" >116.64</td>
                        <td id="T_1fc85_row12_col16" class="data row12 col16" >15.41</td>
                        <td id="T_1fc85_row12_col17" class="data row12 col17" >25.01</td>
                        <td id="T_1fc85_row12_col18" class="data row12 col18" >0.83</td>
                        <td id="T_1fc85_row12_col19" class="data row12 col19" >-</td>
                        <td id="T_1fc85_row12_col20" class="data row12 col20" >6,594.53</td>
                        <td id="T_1fc85_row12_col21" class="data row12 col21" >16,553.19</td>
                        <td id="T_1fc85_row12_col22" class="data row12 col22" >7,045.59</td>
                        <td id="T_1fc85_row12_col23" class="data row12 col23" >60.16</td>
            </tr>
            <tr>
                        <th id="T_1fc85_level0_row13" class="row_heading level0 row13" >ANET</th>
                        <td id="T_1fc85_row13_col0" class="data row13 col0" >Arista Networks Inc.</td>
                        <td id="T_1fc85_row13_col1" class="data row13 col1" >Technology</td>
                        <td id="T_1fc85_row13_col2" class="data row13 col2" >29.94</td>
                        <td id="T_1fc85_row13_col3" class="data row13 col3" >16.81</td>
                        <td id="T_1fc85_row13_col4" class="data row13 col4" >5.71</td>
                        <td id="T_1fc85_row13_col5" class="data row13 col5" >22.40</td>
                        <td id="T_1fc85_row13_col6" class="data row13 col6" >26.00</td>
                        <td id="T_1fc85_row13_col7" class="data row13 col7" >2,131.44</td>
                        <td id="T_1fc85_row13_col8" class="data row13 col8" >12.96</td>
                        <td id="T_1fc85_row13_col9" class="data row13 col9" >17.29</td>
                        <td id="T_1fc85_row13_col10" class="data row13 col10" >561.43</td>
                        <td id="T_1fc85_row13_col11" class="data row13 col11" >37.80</td>
                        <td id="T_1fc85_row13_col12" class="data row13 col12" >107.63</td>
                        <td id="T_1fc85_row13_col13" class="data row13 col13" >690.66</td>
                        <td id="T_1fc85_row13_col14" class="data row13 col14" >17.13</td>
                        <td id="T_1fc85_row13_col15" class="data row13 col15" >69.73</td>
                        <td id="T_1fc85_row13_col16" class="data row13 col16" >43.84</td>
                        <td id="T_1fc85_row13_col17" class="data row13 col17" >47.59</td>
                        <td id="T_1fc85_row13_col18" class="data row13 col18" >1.26</td>
                        <td id="T_1fc85_row13_col19" class="data row13 col19" >-</td>
                        <td id="T_1fc85_row13_col20" class="data row13 col20" >26,719.40</td>
                        <td id="T_1fc85_row13_col21" class="data row13 col21" >13,650.35</td>
                        <td id="T_1fc85_row13_col22" class="data row13 col22" >17,596.86</td>
                        <td id="T_1fc85_row13_col23" class="data row13 col23" >-95.74</td>
            </tr>
            <tr>
                        <th id="T_1fc85_level0_row14" class="row_heading level0 row14" >TROW</th>
                        <td id="T_1fc85_row14_col0" class="data row14 col0" >T. Rowe Price Group </td>
                        <td id="T_1fc85_row14_col1" class="data row14 col1" >Finance</td>
                        <td id="T_1fc85_row14_col2" class="data row14 col2" >13.04</td>
                        <td id="T_1fc85_row14_col3" class="data row14 col3" >14.31</td>
                        <td id="T_1fc85_row14_col4" class="data row14 col4" >8.64</td>
                        <td id="T_1fc85_row14_col5" class="data row14 col5" >29.13</td>
                        <td id="T_1fc85_row14_col6" class="data row14 col6" >35.30</td>
                        <td id="T_1fc85_row14_col7" class="data row14 col7" >5,513.02</td>
                        <td id="T_1fc85_row14_col8" class="data row14 col8" >8.57</td>
                        <td id="T_1fc85_row14_col9" class="data row14 col9" >3.47</td>
                        <td id="T_1fc85_row14_col10" class="data row14 col10" >1,959.83</td>
                        <td id="T_1fc85_row14_col11" class="data row14 col11" >16.67</td>
                        <td id="T_1fc85_row14_col12" class="data row14 col12" >5.71</td>
                        <td id="T_1fc85_row14_col13" class="data row14 col13" >1,129.30</td>
                        <td id="T_1fc85_row14_col14" class="data row14 col14" >1,088.12</td>
                        <td id="T_1fc85_row14_col15" class="data row14 col15" >1,867.35</td>
                        <td id="T_1fc85_row14_col16" class="data row14 col16" >16.51</td>
                        <td id="T_1fc85_row14_col17" class="data row14 col17" >22.51</td>
                        <td id="T_1fc85_row14_col18" class="data row14 col18" >1.35</td>
                        <td id="T_1fc85_row14_col19" class="data row14 col19" >2.62</td>
                        <td id="T_1fc85_row14_col20" class="data row14 col20" >44,116.68</td>
                        <td id="T_1fc85_row14_col21" class="data row14 col21" >20,579,201.34</td>
                        <td id="T_1fc85_row14_col22" class="data row14 col22" >38,304.52</td>
                        <td id="T_1fc85_row14_col23" class="data row14 col23" >99.79</td>
            </tr>
            <tr>
                        <th id="T_1fc85_level0_row15" class="row_heading level0 row15" >TPL</th>
                        <td id="T_1fc85_row15_col0" class="data row15 col0" >Texas Pacific Land C</td>
                        <td id="T_1fc85_row15_col1" class="data row15 col1" >Energy</td>
                        <td id="T_1fc85_row15_col2" class="data row15 col2" >15.12</td>
                        <td id="T_1fc85_row15_col3" class="data row15 col3" >15.95</td>
                        <td id="T_1fc85_row15_col4" class="data row15 col4" >-</td>
                        <td id="T_1fc85_row15_col5" class="data row15 col5" >69.19</td>
                        <td id="T_1fc85_row15_col6" class="data row15 col6" >64.09</td>
                        <td id="T_1fc85_row15_col7" class="data row15 col7" >311.54</td>
                        <td id="T_1fc85_row15_col8" class="data row15 col8" >39.88</td>
                        <td id="T_1fc85_row15_col9" class="data row15 col9" >69.48</td>
                        <td id="T_1fc85_row15_col10" class="data row15 col10" >200.44</td>
                        <td id="T_1fc85_row15_col11" class="data row15 col11" >40.97</td>
                        <td id="T_1fc85_row15_col12" class="data row15 col12" >80.80</td>
                        <td id="T_1fc85_row15_col13" class="data row15 col13" >183.80</td>
                        <td id="T_1fc85_row15_col14" class="data row15 col14" >57.34</td>
                        <td id="T_1fc85_row15_col15" class="data row15 col15" >80.25</td>
                        <td id="T_1fc85_row15_col16" class="data row15 col16" >65.48</td>
                        <td id="T_1fc85_row15_col17" class="data row15 col17" >57.52</td>
                        <td id="T_1fc85_row15_col18" class="data row15 col18" >1.40</td>
                        <td id="T_1fc85_row15_col19" class="data row15 col19" >0.48</td>
                        <td id="T_1fc85_row15_col20" class="data row15 col20" >11,528.29</td>
                        <td id="T_1fc85_row15_col21" class="data row15 col21" >8,428.59</td>
                        <td id="T_1fc85_row15_col22" class="data row15 col22" >6,704.56</td>
                        <td id="T_1fc85_row15_col23" class="data row15 col23" >-36.78</td>
            </tr>
            <tr>
                        <th id="T_1fc85_level0_row16" class="row_heading level0 row16" >ABMD</th>
                        <td id="T_1fc85_row16_col0" class="data row16 col0" >ABIOMED Inc. Common </td>
                        <td id="T_1fc85_row16_col1" class="data row16 col1" >Health Care</td>
                        <td id="T_1fc85_row16_col2" class="data row16 col2" >11.02</td>
                        <td id="T_1fc85_row16_col3" class="data row16 col3" >11.47</td>
                        <td id="T_1fc85_row16_col4" class="data row16 col4" >5.91</td>
                        <td id="T_1fc85_row16_col5" class="data row16 col5" >19.98</td>
                        <td id="T_1fc85_row16_col6" class="data row16 col6" >25.83</td>
                        <td id="T_1fc85_row16_col7" class="data row16 col7" >762.90</td>
                        <td id="T_1fc85_row16_col8" class="data row16 col8" >13.22</td>
                        <td id="T_1fc85_row16_col9" class="data row16 col9" >14.80</td>
                        <td id="T_1fc85_row16_col10" class="data row16 col10" >199.93</td>
                        <td id="T_1fc85_row16_col11" class="data row16 col11" >40.13</td>
                        <td id="T_1fc85_row16_col12" class="data row16 col12" >80.31</td>
                        <td id="T_1fc85_row16_col13" class="data row16 col13" >205.26</td>
                        <td id="T_1fc85_row16_col14" class="data row16 col14" >27.48</td>
                        <td id="T_1fc85_row16_col15" class="data row16 col15" >26.26</td>
                        <td id="T_1fc85_row16_col16" class="data row16 col16" >58.61</td>
                        <td id="T_1fc85_row16_col17" class="data row16 col17" >65.55</td>
                        <td id="T_1fc85_row16_col18" class="data row16 col18" >1.63</td>
                        <td id="T_1fc85_row16_col19" class="data row16 col19" >-</td>
                        <td id="T_1fc85_row16_col20" class="data row16 col20" >13,106.38</td>
                        <td id="T_1fc85_row16_col21" class="data row16 col21" >5,154.94</td>
                        <td id="T_1fc85_row16_col22" class="data row16 col22" >6,573.93</td>
                        <td id="T_1fc85_row16_col23" class="data row16 col23" >-154.25</td>
            </tr>
            <tr>
                        <th id="T_1fc85_level0_row17" class="row_heading level0 row17" >FB</th>
                        <td id="T_1fc85_row17_col0" class="data row17 col0" >Facebook Inc. Class </td>
                        <td id="T_1fc85_row17_col1" class="data row17 col1" >Technology</td>
                        <td id="T_1fc85_row17_col2" class="data row17 col2" >19.47</td>
                        <td id="T_1fc85_row17_col3" class="data row17 col3" >13.19</td>
                        <td id="T_1fc85_row17_col4" class="data row17 col4" >14.85</td>
                        <td id="T_1fc85_row17_col5" class="data row17 col5" >22.18</td>
                        <td id="T_1fc85_row17_col6" class="data row17 col6" >34.71</td>
                        <td id="T_1fc85_row17_col7" class="data row17 col7" >63,288.25</td>
                        <td id="T_1fc85_row17_col8" class="data row17 col8" >28.52</td>
                        <td id="T_1fc85_row17_col9" class="data row17 col9" >8.05</td>
                        <td id="T_1fc85_row17_col10" class="data row17 col10" >21,419.25</td>
                        <td id="T_1fc85_row17_col11" class="data row17 col11" >26.68</td>
                        <td id="T_1fc85_row17_col12" class="data row17 col12" >38.49</td>
                        <td id="T_1fc85_row17_col13" class="data row17 col13" >19,421.50</td>
                        <td id="T_1fc85_row17_col14" class="data row17 col14" >12.46</td>
                        <td id="T_1fc85_row17_col15" class="data row17 col15" >25.14</td>
                        <td id="T_1fc85_row17_col16" class="data row17 col16" >28.31</td>
                        <td id="T_1fc85_row17_col17" class="data row17 col17" >43.73</td>
                        <td id="T_1fc85_row17_col18" class="data row17 col18" >1.64</td>
                        <td id="T_1fc85_row17_col19" class="data row17 col19" >-</td>
                        <td id="T_1fc85_row17_col20" class="data row17 col20" >936,694.25</td>
                        <td id="T_1fc85_row17_col21" class="data row17 col21" >342,336.46</td>
                        <td id="T_1fc85_row17_col22" class="data row17 col22" >528,389.22</td>
                        <td id="T_1fc85_row17_col23" class="data row17 col23" >-173.62</td>
            </tr>
            <tr>
                        <th id="T_1fc85_level0_row18" class="row_heading level0 row18" >OCG</th>
                        <td id="T_1fc85_row18_col0" class="data row18 col0" >Oriental Culture Hol</td>
                        <td id="T_1fc85_row18_col1" class="data row18 col1" >Consumer Services</td>
                        <td id="T_1fc85_row18_col2" class="data row18 col2" >18.34</td>
                        <td id="T_1fc85_row18_col3" class="data row18 col3" >3.45</td>
                        <td id="T_1fc85_row18_col4" class="data row18 col4" >-</td>
                        <td id="T_1fc85_row18_col5" class="data row18 col5" >58.19</td>
                        <td id="T_1fc85_row18_col6" class="data row18 col6" >42.78</td>
                        <td id="T_1fc85_row18_col7" class="data row18 col7" >12.08</td>
                        <td id="T_1fc85_row18_col8" class="data row18 col8" >90.46</td>
                        <td id="T_1fc85_row18_col9" class="data row18 col9" >85.99</td>
                        <td id="T_1fc85_row18_col10" class="data row18 col10" >4.59</td>
                        <td id="T_1fc85_row18_col11" class="data row18 col11" >84.43</td>
                        <td id="T_1fc85_row18_col12" class="data row18 col12" >228.95</td>
                        <td id="T_1fc85_row18_col13" class="data row18 col13" >6.88</td>
                        <td id="T_1fc85_row18_col14" class="data row18 col14" >87.97</td>
                        <td id="T_1fc85_row18_col15" class="data row18 col15" >143.00</td>
                        <td id="T_1fc85_row18_col16" class="data row18 col16" >-</td>
                        <td id="T_1fc85_row18_col17" class="data row18 col17" >139.66</td>
                        <td id="T_1fc85_row18_col18" class="data row18 col18" >1.65</td>
                        <td id="T_1fc85_row18_col19" class="data row18 col19" >-</td>
                        <td id="T_1fc85_row18_col20" class="data row18 col20" >640.60</td>
                        <td id="T_1fc85_row18_col21" class="data row18 col21" >527.84</td>
                        <td id="T_1fc85_row18_col22" class="data row18 col22" >333.08</td>
                        <td id="T_1fc85_row18_col23" class="data row18 col23" >-21.36</td>
            </tr>
            <tr>
                        <th id="T_1fc85_level0_row19" class="row_heading level0 row19" >QLYS</th>
                        <td id="T_1fc85_row19_col0" class="data row19 col0" >Qualys Inc. Common S</td>
                        <td id="T_1fc85_row19_col1" class="data row19 col1" >Technology</td>
                        <td id="T_1fc85_row19_col2" class="data row19 col2" >45.10</td>
                        <td id="T_1fc85_row19_col3" class="data row19 col3" >27.60</td>
                        <td id="T_1fc85_row19_col4" class="data row19 col4" >1.84</td>
                        <td id="T_1fc85_row19_col5" class="data row19 col5" >17.09</td>
                        <td id="T_1fc85_row19_col6" class="data row19 col6" >21.21</td>
                        <td id="T_1fc85_row19_col7" class="data row19 col7" >298.57</td>
                        <td id="T_1fc85_row19_col8" class="data row19 col8" >16.33</td>
                        <td id="T_1fc85_row19_col9" class="data row19 col9" >4.08</td>
                        <td id="T_1fc85_row19_col10" class="data row19 col10" >64.66</td>
                        <td id="T_1fc85_row19_col11" class="data row19 col11" >31.59</td>
                        <td id="T_1fc85_row19_col12" class="data row19 col12" >10.36</td>
                        <td id="T_1fc85_row19_col13" class="data row19 col13" >113.90</td>
                        <td id="T_1fc85_row19_col14" class="data row19 col14" >29.80</td>
                        <td id="T_1fc85_row19_col15" class="data row19 col15" >17.14</td>
                        <td id="T_1fc85_row19_col16" class="data row19 col16" >44.66</td>
                        <td id="T_1fc85_row19_col17" class="data row19 col17" >60.63</td>
                        <td id="T_1fc85_row19_col18" class="data row19 col18" >1.92</td>
                        <td id="T_1fc85_row19_col19" class="data row19 col19" >-</td>
                        <td id="T_1fc85_row19_col20" class="data row19 col20" >3,920.76</td>
                        <td id="T_1fc85_row19_col21" class="data row19 col21" >3,010.73</td>
                        <td id="T_1fc85_row19_col22" class="data row19 col22" >1,777.12</td>
                        <td id="T_1fc85_row19_col23" class="data row19 col23" >-30.23</td>
            </tr>
            <tr>
                        <th id="T_1fc85_level0_row20" class="row_heading level0 row20" >ESNT</th>
                        <td id="T_1fc85_row20_col0" class="data row20 col0" >Essent Group Ltd. Co</td>
                        <td id="T_1fc85_row20_col1" class="data row20 col1" >Finance</td>
                        <td id="T_1fc85_row20_col2" class="data row20 col2" >25.76</td>
                        <td id="T_1fc85_row20_col3" class="data row20 col3" >5.25</td>
                        <td id="T_1fc85_row20_col4" class="data row20 col4" >-</td>
                        <td id="T_1fc85_row20_col5" class="data row20 col5" >17.16</td>
                        <td id="T_1fc85_row20_col6" class="data row20 col6" >59.53</td>
                        <td id="T_1fc85_row20_col7" class="data row20 col7" >779.65</td>
                        <td id="T_1fc85_row20_col8" class="data row20 col8" >18.49</td>
                        <td id="T_1fc85_row20_col9" class="data row20 col9" >7.56</td>
                        <td id="T_1fc85_row20_col10" class="data row20 col10" >453.97</td>
                        <td id="T_1fc85_row20_col11" class="data row20 col11" >5.43</td>
                        <td id="T_1fc85_row20_col12" class="data row20 col12" >27.02</td>
                        <td id="T_1fc85_row20_col13" class="data row20 col13" >574.75</td>
                        <td id="T_1fc85_row20_col14" class="data row20 col14" >29.32</td>
                        <td id="T_1fc85_row20_col15" class="data row20 col15" >38.04</td>
                        <td id="T_1fc85_row20_col16" class="data row20 col16" >12.21</td>
                        <td id="T_1fc85_row20_col17" class="data row20 col17" >11.77</td>
                        <td id="T_1fc85_row20_col18" class="data row20 col18" >2.17</td>
                        <td id="T_1fc85_row20_col19" class="data row20 col19" >-</td>
                        <td id="T_1fc85_row20_col20" class="data row20 col20" >5,345.28</td>
                        <td id="T_1fc85_row20_col21" class="data row20 col21" >15,031.67</td>
                        <td id="T_1fc85_row20_col22" class="data row20 col22" >6,681.72</td>
                        <td id="T_1fc85_row20_col23" class="data row20 col23" >64.44</td>
            </tr>
            <tr>
                        <th id="T_1fc85_level0_row21" class="row_heading level0 row21" >PAX</th>
                        <td id="T_1fc85_row21_col0" class="data row21 col0" >Patria Investments L</td>
                        <td id="T_1fc85_row21_col1" class="data row21 col1" >Finance</td>
                        <td id="T_1fc85_row21_col2" class="data row21 col2" >44.90</td>
                        <td id="T_1fc85_row21_col3" class="data row21 col3" >21.53</td>
                        <td id="T_1fc85_row21_col4" class="data row21 col4" >-</td>
                        <td id="T_1fc85_row21_col5" class="data row21 col5" >80.55</td>
                        <td id="T_1fc85_row21_col6" class="data row21 col6" >47.64</td>
                        <td id="T_1fc85_row21_col7" class="data row21 col7" >114.63</td>
                        <td id="T_1fc85_row21_col8" class="data row21 col8" >4.98</td>
                        <td id="T_1fc85_row21_col9" class="data row21 col9" >16.45</td>
                        <td id="T_1fc85_row21_col10" class="data row21 col10" >54.81</td>
                        <td id="T_1fc85_row21_col11" class="data row21 col11" >20.16</td>
                        <td id="T_1fc85_row21_col12" class="data row21 col12" >19.65</td>
                        <td id="T_1fc85_row21_col13" class="data row21 col13" >45.12</td>
                        <td id="T_1fc85_row21_col14" class="data row21 col14" >16.81</td>
                        <td id="T_1fc85_row21_col15" class="data row21 col15" >2.43</td>
                        <td id="T_1fc85_row21_col16" class="data row21 col16" >-</td>
                        <td id="T_1fc85_row21_col17" class="data row21 col17" >43.98</td>
                        <td id="T_1fc85_row21_col18" class="data row21 col18" >2.18</td>
                        <td id="T_1fc85_row21_col19" class="data row21 col19" >-</td>
                        <td id="T_1fc85_row21_col20" class="data row21 col20" >2,410.54</td>
                        <td id="T_1fc85_row21_col21" class="data row21 col21" >884.97</td>
                        <td id="T_1fc85_row21_col22" class="data row21 col22" >1,164.16</td>
                        <td id="T_1fc85_row21_col23" class="data row21 col23" >-172.39</td>
            </tr>
            <tr>
                        <th id="T_1fc85_level0_row22" class="row_heading level0 row22" >MNST</th>
                        <td id="T_1fc85_row22_col0" class="data row22 col0" >Monster Beverage Cor</td>
                        <td id="T_1fc85_row22_col1" class="data row22 col1" >Consumer Non-Durables</td>
                        <td id="T_1fc85_row22_col2" class="data row22 col2" >16.80</td>
                        <td id="T_1fc85_row22_col3" class="data row22 col3" >14.48</td>
                        <td id="T_1fc85_row22_col4" class="data row22 col4" >25.80</td>
                        <td id="T_1fc85_row22_col5" class="data row22 col5" >25.61</td>
                        <td id="T_1fc85_row22_col6" class="data row22 col6" >26.87</td>
                        <td id="T_1fc85_row22_col7" class="data row22 col7" >3,993.92</td>
                        <td id="T_1fc85_row22_col8" class="data row22 col8" >10.94</td>
                        <td id="T_1fc85_row22_col9" class="data row22 col9" >1.84</td>
                        <td id="T_1fc85_row22_col10" class="data row22 col10" >1,082.78</td>
                        <td id="T_1fc85_row22_col11" class="data row22 col11" >19.93</td>
                        <td id="T_1fc85_row22_col12" class="data row22 col12" >7.89</td>
                        <td id="T_1fc85_row22_col13" class="data row22 col13" >1,082.94</td>
                        <td id="T_1fc85_row22_col14" class="data row22 col14" >14.54</td>
                        <td id="T_1fc85_row22_col15" class="data row22 col15" >19.95</td>
                        <td id="T_1fc85_row22_col16" class="data row22 col16" >36.12</td>
                        <td id="T_1fc85_row22_col17" class="data row22 col17" >46.56</td>
                        <td id="T_1fc85_row22_col18" class="data row22 col18" >2.34</td>
                        <td id="T_1fc85_row22_col19" class="data row22 col19" >-</td>
                        <td id="T_1fc85_row22_col20" class="data row22 col20" >50,408.77</td>
                        <td id="T_1fc85_row22_col21" class="data row22 col21" >20,099.10</td>
                        <td id="T_1fc85_row22_col22" class="data row22 col22" >22,877.49</td>
                        <td id="T_1fc85_row22_col23" class="data row22 col23" >-150.80</td>
            </tr>
            <tr>
                        <th id="T_1fc85_level0_row23" class="row_heading level0 row23" >MASI</th>
                        <td id="T_1fc85_row23_col0" class="data row23 col0" >Masimo Corporation C</td>
                        <td id="T_1fc85_row23_col1" class="data row23 col1" >Health Care</td>
                        <td id="T_1fc85_row23_col2" class="data row23 col2" >17.80</td>
                        <td id="T_1fc85_row23_col3" class="data row23 col3" >15.86</td>
                        <td id="T_1fc85_row23_col4" class="data row23 col4" >7.33</td>
                        <td id="T_1fc85_row23_col5" class="data row23 col5" >17.77</td>
                        <td id="T_1fc85_row23_col6" class="data row23 col6" >20.07</td>
                        <td id="T_1fc85_row23_col7" class="data row23 col7" >932.53</td>
                        <td id="T_1fc85_row23_col8" class="data row23 col8" >13.28</td>
                        <td id="T_1fc85_row23_col9" class="data row23 col9" >7.52</td>
                        <td id="T_1fc85_row23_col10" class="data row23 col10" >188.71</td>
                        <td id="T_1fc85_row23_col11" class="data row23 col11" >26.32</td>
                        <td id="T_1fc85_row23_col12" class="data row23 col12" >27.06</td>
                        <td id="T_1fc85_row23_col13" class="data row23 col13" >131.61</td>
                        <td id="T_1fc85_row23_col14" class="data row23 col14" >551.99</td>
                        <td id="T_1fc85_row23_col15" class="data row23 col15" >991.44</td>
                        <td id="T_1fc85_row23_col16" class="data row23 col16" >53.60</td>
                        <td id="T_1fc85_row23_col17" class="data row23 col17" >61.56</td>
                        <td id="T_1fc85_row23_col18" class="data row23 col18" >2.34</td>
                        <td id="T_1fc85_row23_col19" class="data row23 col19" >-</td>
                        <td id="T_1fc85_row23_col20" class="data row23 col20" >11,617.18</td>
                        <td id="T_1fc85_row23_col21" class="data row23 col21" >399,275.06</td>
                        <td id="T_1fc85_row23_col22" class="data row23 col22" >4,617.28</td>
                        <td id="T_1fc85_row23_col23" class="data row23 col23" >97.09</td>
            </tr>
            <tr>
                        <th id="T_1fc85_level0_row24" class="row_heading level0 row24" >GRMN</th>
                        <td id="T_1fc85_row24_col0" class="data row24 col0" >Garmin Ltd. Common S</td>
                        <td id="T_1fc85_row24_col1" class="data row24 col1" >Capital Goods</td>
                        <td id="T_1fc85_row24_col2" class="data row24 col2" >21.55</td>
                        <td id="T_1fc85_row24_col3" class="data row24 col3" >20.53</td>
                        <td id="T_1fc85_row24_col4" class="data row24 col4" >10.59</td>
                        <td id="T_1fc85_row24_col5" class="data row24 col5" >18.23</td>
                        <td id="T_1fc85_row24_col6" class="data row24 col6" >23.12</td>
                        <td id="T_1fc85_row24_col7" class="data row24 col7" >3,603.27</td>
                        <td id="T_1fc85_row24_col8" class="data row24 col8" >10.30</td>
                        <td id="T_1fc85_row24_col9" class="data row24 col9" >2.69</td>
                        <td id="T_1fc85_row24_col10" class="data row24 col10" >836.97</td>
                        <td id="T_1fc85_row24_col11" class="data row24 col11" >13.10</td>
                        <td id="T_1fc85_row24_col12" class="data row24 col12" >21.13</td>
                        <td id="T_1fc85_row24_col13" class="data row24 col13" >703.82</td>
                        <td id="T_1fc85_row24_col14" class="data row24 col14" >28.73</td>
                        <td id="T_1fc85_row24_col15" class="data row24 col15" >46.45</td>
                        <td id="T_1fc85_row24_col16" class="data row24 col16" >26.27</td>
                        <td id="T_1fc85_row24_col17" class="data row24 col17" >32.98</td>
                        <td id="T_1fc85_row24_col18" class="data row24 col18" >2.52</td>
                        <td id="T_1fc85_row24_col19" class="data row24 col19" >3.12</td>
                        <td id="T_1fc85_row24_col20" class="data row24 col20" >27,599.71</td>
                        <td id="T_1fc85_row24_col21" class="data row24 col21" >18,171.17</td>
                        <td id="T_1fc85_row24_col22" class="data row24 col22" >14,992.37</td>
                        <td id="T_1fc85_row24_col23" class="data row24 col23" >-51.89</td>
            </tr>
            <tr>
                        <th id="T_1fc85_level0_row25" class="row_heading level0 row25" >CODA</th>
                        <td id="T_1fc85_row25_col0" class="data row25 col0" >Coda Octopus Group I</td>
                        <td id="T_1fc85_row25_col1" class="data row25 col1" >Capital Goods</td>
                        <td id="T_1fc85_row25_col2" class="data row25 col2" >9.58</td>
                        <td id="T_1fc85_row25_col3" class="data row25 col3" >15.00</td>
                        <td id="T_1fc85_row25_col4" class="data row25 col4" >9.83</td>
                        <td id="T_1fc85_row25_col5" class="data row25 col5" >17.85</td>
                        <td id="T_1fc85_row25_col6" class="data row25 col6" >20.94</td>
                        <td id="T_1fc85_row25_col7" class="data row25 col7" >20.29</td>
                        <td id="T_1fc85_row25_col8" class="data row25 col8" >6.34</td>
                        <td id="T_1fc85_row25_col9" class="data row25 col9" >30.04</td>
                        <td id="T_1fc85_row25_col10" class="data row25 col10" >4.22</td>
                        <td id="T_1fc85_row25_col11" class="data row25 col11" >6.04</td>
                        <td id="T_1fc85_row25_col12" class="data row25 col12" >42.71</td>
                        <td id="T_1fc85_row25_col13" class="data row25 col13" >2.97</td>
                        <td id="T_1fc85_row25_col14" class="data row25 col14" >30.12</td>
                        <td id="T_1fc85_row25_col15" class="data row25 col15" >79.02</td>
                        <td id="T_1fc85_row25_col16" class="data row25 col16" >31.85</td>
                        <td id="T_1fc85_row25_col17" class="data row25 col17" >22.13</td>
                        <td id="T_1fc85_row25_col18" class="data row25 col18" >3.67</td>
                        <td id="T_1fc85_row25_col19" class="data row25 col19" >-</td>
                        <td id="T_1fc85_row25_col20" class="data row25 col20" >93.49</td>
                        <td id="T_1fc85_row25_col21" class="data row25 col21" >79.00</td>
                        <td id="T_1fc85_row25_col22" class="data row25 col22" >63.17</td>
                        <td id="T_1fc85_row25_col23" class="data row25 col23" >-18.34</td>
            </tr>
    </tbody></table>



### 观察列表




<style  type="text/css" >
#T_f0100_row0_col0,#T_f0100_row0_col1,#T_f0100_row0_col2,#T_f0100_row0_col3,#T_f0100_row0_col4,#T_f0100_row0_col5,#T_f0100_row0_col6,#T_f0100_row0_col7,#T_f0100_row0_col8,#T_f0100_row0_col9,#T_f0100_row0_col10,#T_f0100_row0_col11,#T_f0100_row0_col12,#T_f0100_row0_col13,#T_f0100_row0_col15,#T_f0100_row0_col16,#T_f0100_row0_col17,#T_f0100_row0_col18,#T_f0100_row0_col19,#T_f0100_row0_col20,#T_f0100_row0_col21,#T_f0100_row0_col22,#T_f0100_row1_col0,#T_f0100_row1_col1,#T_f0100_row1_col2,#T_f0100_row1_col3,#T_f0100_row1_col4,#T_f0100_row1_col5,#T_f0100_row1_col6,#T_f0100_row1_col7,#T_f0100_row1_col8,#T_f0100_row1_col9,#T_f0100_row1_col10,#T_f0100_row1_col11,#T_f0100_row1_col12,#T_f0100_row1_col13,#T_f0100_row1_col14,#T_f0100_row1_col15,#T_f0100_row1_col16,#T_f0100_row1_col17,#T_f0100_row1_col18,#T_f0100_row1_col19,#T_f0100_row1_col20,#T_f0100_row1_col21,#T_f0100_row1_col22,#T_f0100_row1_col23,#T_f0100_row2_col0,#T_f0100_row2_col1,#T_f0100_row2_col2,#T_f0100_row2_col3,#T_f0100_row2_col4,#T_f0100_row2_col5,#T_f0100_row2_col6,#T_f0100_row2_col7,#T_f0100_row2_col8,#T_f0100_row2_col9,#T_f0100_row2_col10,#T_f0100_row2_col11,#T_f0100_row2_col12,#T_f0100_row2_col13,#T_f0100_row2_col14,#T_f0100_row2_col15,#T_f0100_row2_col16,#T_f0100_row2_col17,#T_f0100_row2_col18,#T_f0100_row2_col19,#T_f0100_row2_col20,#T_f0100_row2_col21,#T_f0100_row2_col22,#T_f0100_row2_col23,#T_f0100_row3_col0,#T_f0100_row3_col1,#T_f0100_row3_col2,#T_f0100_row3_col3,#T_f0100_row3_col4,#T_f0100_row3_col5,#T_f0100_row3_col6,#T_f0100_row3_col7,#T_f0100_row3_col8,#T_f0100_row3_col9,#T_f0100_row3_col10,#T_f0100_row3_col11,#T_f0100_row3_col12,#T_f0100_row3_col13,#T_f0100_row3_col14,#T_f0100_row3_col15,#T_f0100_row3_col16,#T_f0100_row3_col17,#T_f0100_row3_col18,#T_f0100_row3_col19,#T_f0100_row3_col20,#T_f0100_row3_col21,#T_f0100_row3_col22,#T_f0100_row3_col23,#T_f0100_row4_col0,#T_f0100_row4_col1,#T_f0100_row4_col2,#T_f0100_row4_col3,#T_f0100_row4_col4,#T_f0100_row4_col5,#T_f0100_row4_col6,#T_f0100_row4_col7,#T_f0100_row4_col9,#T_f0100_row4_col10,#T_f0100_row4_col11,#T_f0100_row4_col12,#T_f0100_row4_col13,#T_f0100_row4_col14,#T_f0100_row4_col15,#T_f0100_row4_col16,#T_f0100_row4_col17,#T_f0100_row4_col18,#T_f0100_row4_col19,#T_f0100_row4_col20,#T_f0100_row4_col21,#T_f0100_row4_col22,#T_f0100_row5_col0,#T_f0100_row5_col1,#T_f0100_row5_col2,#T_f0100_row5_col3,#T_f0100_row5_col4,#T_f0100_row5_col5,#T_f0100_row5_col6,#T_f0100_row5_col7,#T_f0100_row5_col8,#T_f0100_row5_col9,#T_f0100_row5_col10,#T_f0100_row5_col11,#T_f0100_row5_col12,#T_f0100_row5_col13,#T_f0100_row5_col14,#T_f0100_row5_col15,#T_f0100_row5_col16,#T_f0100_row5_col17,#T_f0100_row5_col18,#T_f0100_row5_col19,#T_f0100_row5_col20,#T_f0100_row5_col21,#T_f0100_row5_col22,#T_f0100_row6_col0,#T_f0100_row6_col1,#T_f0100_row6_col2,#T_f0100_row6_col3,#T_f0100_row6_col4,#T_f0100_row6_col5,#T_f0100_row6_col6,#T_f0100_row6_col7,#T_f0100_row6_col9,#T_f0100_row6_col10,#T_f0100_row6_col11,#T_f0100_row6_col12,#T_f0100_row6_col13,#T_f0100_row6_col15,#T_f0100_row6_col16,#T_f0100_row6_col17,#T_f0100_row6_col18,#T_f0100_row6_col19,#T_f0100_row6_col20,#T_f0100_row6_col21,#T_f0100_row6_col22,#T_f0100_row7_col0,#T_f0100_row7_col1,#T_f0100_row7_col2,#T_f0100_row7_col3,#T_f0100_row7_col4,#T_f0100_row7_col5,#T_f0100_row7_col6,#T_f0100_row7_col7,#T_f0100_row7_col8,#T_f0100_row7_col9,#T_f0100_row7_col10,#T_f0100_row7_col11,#T_f0100_row7_col12,#T_f0100_row7_col13,#T_f0100_row7_col14,#T_f0100_row7_col15,#T_f0100_row7_col16,#T_f0100_row7_col17,#T_f0100_row7_col18,#T_f0100_row7_col19,#T_f0100_row7_col20,#T_f0100_row7_col21,#T_f0100_row7_col22,#T_f0100_row8_col0,#T_f0100_row8_col1,#T_f0100_row8_col2,#T_f0100_row8_col3,#T_f0100_row8_col4,#T_f0100_row8_col5,#T_f0100_row8_col6,#T_f0100_row8_col7,#T_f0100_row8_col8,#T_f0100_row8_col9,#T_f0100_row8_col10,#T_f0100_row8_col11,#T_f0100_row8_col12,#T_f0100_row8_col13,#T_f0100_row8_col14,#T_f0100_row8_col15,#T_f0100_row8_col16,#T_f0100_row8_col17,#T_f0100_row8_col18,#T_f0100_row8_col19,#T_f0100_row8_col20,#T_f0100_row8_col21,#T_f0100_row8_col22,#T_f0100_row9_col0,#T_f0100_row9_col1,#T_f0100_row9_col2,#T_f0100_row9_col3,#T_f0100_row9_col4,#T_f0100_row9_col5,#T_f0100_row9_col6,#T_f0100_row9_col7,#T_f0100_row9_col8,#T_f0100_row9_col9,#T_f0100_row9_col10,#T_f0100_row9_col11,#T_f0100_row9_col12,#T_f0100_row9_col13,#T_f0100_row9_col14,#T_f0100_row9_col15,#T_f0100_row9_col16,#T_f0100_row9_col17,#T_f0100_row9_col18,#T_f0100_row9_col19,#T_f0100_row9_col20,#T_f0100_row9_col21,#T_f0100_row9_col22,#T_f0100_row10_col0,#T_f0100_row10_col1,#T_f0100_row10_col2,#T_f0100_row10_col3,#T_f0100_row10_col4,#T_f0100_row10_col5,#T_f0100_row10_col6,#T_f0100_row10_col7,#T_f0100_row10_col8,#T_f0100_row10_col9,#T_f0100_row10_col10,#T_f0100_row10_col11,#T_f0100_row10_col12,#T_f0100_row10_col13,#T_f0100_row10_col14,#T_f0100_row10_col15,#T_f0100_row10_col16,#T_f0100_row10_col17,#T_f0100_row10_col18,#T_f0100_row10_col19,#T_f0100_row10_col20,#T_f0100_row10_col21,#T_f0100_row10_col22,#T_f0100_row11_col0,#T_f0100_row11_col1,#T_f0100_row11_col2,#T_f0100_row11_col3,#T_f0100_row11_col4,#T_f0100_row11_col5,#T_f0100_row11_col6,#T_f0100_row11_col7,#T_f0100_row11_col8,#T_f0100_row11_col9,#T_f0100_row11_col10,#T_f0100_row11_col11,#T_f0100_row11_col12,#T_f0100_row11_col13,#T_f0100_row11_col14,#T_f0100_row11_col15,#T_f0100_row11_col16,#T_f0100_row11_col17,#T_f0100_row11_col18,#T_f0100_row11_col19,#T_f0100_row11_col20,#T_f0100_row11_col21,#T_f0100_row11_col22,#T_f0100_row12_col0,#T_f0100_row12_col1,#T_f0100_row12_col2,#T_f0100_row12_col3,#T_f0100_row12_col4,#T_f0100_row12_col5,#T_f0100_row12_col6,#T_f0100_row12_col7,#T_f0100_row12_col8,#T_f0100_row12_col9,#T_f0100_row12_col10,#T_f0100_row12_col11,#T_f0100_row12_col12,#T_f0100_row12_col13,#T_f0100_row12_col14,#T_f0100_row12_col15,#T_f0100_row12_col16,#T_f0100_row12_col17,#T_f0100_row12_col18,#T_f0100_row12_col19,#T_f0100_row12_col20,#T_f0100_row12_col21,#T_f0100_row12_col22,#T_f0100_row13_col0,#T_f0100_row13_col1,#T_f0100_row13_col2,#T_f0100_row13_col3,#T_f0100_row13_col4,#T_f0100_row13_col5,#T_f0100_row13_col6,#T_f0100_row13_col7,#T_f0100_row13_col8,#T_f0100_row13_col9,#T_f0100_row13_col10,#T_f0100_row13_col11,#T_f0100_row13_col12,#T_f0100_row13_col15,#T_f0100_row13_col16,#T_f0100_row13_col17,#T_f0100_row13_col18,#T_f0100_row13_col19,#T_f0100_row13_col20,#T_f0100_row13_col22,#T_f0100_row13_col23,#T_f0100_row14_col0,#T_f0100_row14_col1,#T_f0100_row14_col2,#T_f0100_row14_col3,#T_f0100_row14_col4,#T_f0100_row14_col5,#T_f0100_row14_col6,#T_f0100_row14_col7,#T_f0100_row14_col8,#T_f0100_row14_col9,#T_f0100_row14_col10,#T_f0100_row14_col11,#T_f0100_row14_col12,#T_f0100_row14_col13,#T_f0100_row14_col14,#T_f0100_row14_col15,#T_f0100_row14_col16,#T_f0100_row14_col17,#T_f0100_row14_col18,#T_f0100_row14_col19,#T_f0100_row14_col20,#T_f0100_row14_col21,#T_f0100_row14_col22,#T_f0100_row14_col23,#T_f0100_row15_col0,#T_f0100_row15_col1,#T_f0100_row15_col2,#T_f0100_row15_col3,#T_f0100_row15_col4,#T_f0100_row15_col5,#T_f0100_row15_col6,#T_f0100_row15_col7,#T_f0100_row15_col8,#T_f0100_row15_col9,#T_f0100_row15_col10,#T_f0100_row15_col11,#T_f0100_row15_col12,#T_f0100_row15_col13,#T_f0100_row15_col14,#T_f0100_row15_col15,#T_f0100_row15_col16,#T_f0100_row15_col17,#T_f0100_row15_col18,#T_f0100_row15_col19,#T_f0100_row15_col20,#T_f0100_row15_col21,#T_f0100_row15_col22,#T_f0100_row16_col0,#T_f0100_row16_col1,#T_f0100_row16_col2,#T_f0100_row16_col3,#T_f0100_row16_col4,#T_f0100_row16_col5,#T_f0100_row16_col6,#T_f0100_row16_col7,#T_f0100_row16_col8,#T_f0100_row16_col9,#T_f0100_row16_col10,#T_f0100_row16_col11,#T_f0100_row16_col12,#T_f0100_row16_col13,#T_f0100_row16_col14,#T_f0100_row16_col15,#T_f0100_row16_col16,#T_f0100_row16_col17,#T_f0100_row16_col18,#T_f0100_row16_col19,#T_f0100_row16_col20,#T_f0100_row16_col21,#T_f0100_row16_col22,#T_f0100_row17_col0,#T_f0100_row17_col1,#T_f0100_row17_col2,#T_f0100_row17_col3,#T_f0100_row17_col4,#T_f0100_row17_col5,#T_f0100_row17_col6,#T_f0100_row17_col7,#T_f0100_row17_col8,#T_f0100_row17_col9,#T_f0100_row17_col10,#T_f0100_row17_col11,#T_f0100_row17_col12,#T_f0100_row17_col13,#T_f0100_row17_col15,#T_f0100_row17_col16,#T_f0100_row17_col17,#T_f0100_row17_col18,#T_f0100_row17_col19,#T_f0100_row17_col20,#T_f0100_row17_col21,#T_f0100_row17_col22,#T_f0100_row18_col0,#T_f0100_row18_col1,#T_f0100_row18_col2,#T_f0100_row18_col3,#T_f0100_row18_col4,#T_f0100_row18_col5,#T_f0100_row18_col6,#T_f0100_row18_col7,#T_f0100_row18_col8,#T_f0100_row18_col9,#T_f0100_row18_col10,#T_f0100_row18_col11,#T_f0100_row18_col12,#T_f0100_row18_col13,#T_f0100_row18_col14,#T_f0100_row18_col15,#T_f0100_row18_col16,#T_f0100_row18_col17,#T_f0100_row18_col18,#T_f0100_row18_col19,#T_f0100_row18_col20,#T_f0100_row18_col21,#T_f0100_row18_col22,#T_f0100_row19_col0,#T_f0100_row19_col1,#T_f0100_row19_col2,#T_f0100_row19_col3,#T_f0100_row19_col4,#T_f0100_row19_col6,#T_f0100_row19_col7,#T_f0100_row19_col8,#T_f0100_row19_col9,#T_f0100_row19_col11,#T_f0100_row19_col12,#T_f0100_row19_col14,#T_f0100_row19_col15,#T_f0100_row19_col16,#T_f0100_row19_col17,#T_f0100_row19_col18,#T_f0100_row19_col19,#T_f0100_row19_col20,#T_f0100_row19_col23,#T_f0100_row20_col0,#T_f0100_row20_col1,#T_f0100_row20_col2,#T_f0100_row20_col3,#T_f0100_row20_col4,#T_f0100_row20_col5,#T_f0100_row20_col6,#T_f0100_row20_col7,#T_f0100_row20_col8,#T_f0100_row20_col9,#T_f0100_row20_col10,#T_f0100_row20_col12,#T_f0100_row20_col13,#T_f0100_row20_col15,#T_f0100_row20_col16,#T_f0100_row20_col17,#T_f0100_row20_col18,#T_f0100_row20_col19,#T_f0100_row20_col20,#T_f0100_row20_col21,#T_f0100_row20_col22,#T_f0100_row21_col0,#T_f0100_row21_col1,#T_f0100_row21_col2,#T_f0100_row21_col3,#T_f0100_row21_col4,#T_f0100_row21_col7,#T_f0100_row21_col8,#T_f0100_row21_col9,#T_f0100_row21_col11,#T_f0100_row21_col12,#T_f0100_row21_col15,#T_f0100_row21_col16,#T_f0100_row21_col17,#T_f0100_row21_col18,#T_f0100_row21_col19,#T_f0100_row21_col20,#T_f0100_row21_col23,#T_f0100_row22_col0,#T_f0100_row22_col1,#T_f0100_row22_col2,#T_f0100_row22_col3,#T_f0100_row22_col4,#T_f0100_row22_col5,#T_f0100_row22_col7,#T_f0100_row22_col8,#T_f0100_row22_col9,#T_f0100_row22_col12,#T_f0100_row22_col15,#T_f0100_row22_col16,#T_f0100_row22_col17,#T_f0100_row22_col18,#T_f0100_row22_col19,#T_f0100_row22_col20,#T_f0100_row22_col23,#T_f0100_row23_col0,#T_f0100_row23_col1,#T_f0100_row23_col2,#T_f0100_row23_col3,#T_f0100_row23_col4,#T_f0100_row23_col7,#T_f0100_row23_col8,#T_f0100_row23_col9,#T_f0100_row23_col11,#T_f0100_row23_col12,#T_f0100_row23_col13,#T_f0100_row23_col15,#T_f0100_row23_col16,#T_f0100_row23_col17,#T_f0100_row23_col18,#T_f0100_row23_col19,#T_f0100_row23_col20,#T_f0100_row23_col23,#T_f0100_row24_col0,#T_f0100_row24_col1,#T_f0100_row24_col2,#T_f0100_row24_col3,#T_f0100_row24_col4,#T_f0100_row24_col5,#T_f0100_row24_col6,#T_f0100_row24_col7,#T_f0100_row24_col8,#T_f0100_row24_col9,#T_f0100_row24_col10,#T_f0100_row24_col12,#T_f0100_row24_col13,#T_f0100_row24_col15,#T_f0100_row24_col16,#T_f0100_row24_col17,#T_f0100_row24_col18,#T_f0100_row24_col19,#T_f0100_row24_col20,#T_f0100_row24_col21,#T_f0100_row25_col0,#T_f0100_row25_col1,#T_f0100_row25_col2,#T_f0100_row25_col3,#T_f0100_row25_col4,#T_f0100_row25_col5,#T_f0100_row25_col7,#T_f0100_row25_col8,#T_f0100_row25_col9,#T_f0100_row25_col11,#T_f0100_row25_col12,#T_f0100_row25_col14,#T_f0100_row25_col15,#T_f0100_row25_col16,#T_f0100_row25_col17,#T_f0100_row25_col18,#T_f0100_row25_col19,#T_f0100_row25_col20,#T_f0100_row25_col23,#T_f0100_row26_col0,#T_f0100_row26_col1,#T_f0100_row26_col2,#T_f0100_row26_col3,#T_f0100_row26_col4,#T_f0100_row26_col5,#T_f0100_row26_col6,#T_f0100_row26_col7,#T_f0100_row26_col8,#T_f0100_row26_col9,#T_f0100_row26_col10,#T_f0100_row26_col12,#T_f0100_row26_col13,#T_f0100_row26_col14,#T_f0100_row26_col15,#T_f0100_row26_col16,#T_f0100_row26_col17,#T_f0100_row26_col18,#T_f0100_row26_col19,#T_f0100_row26_col20,#T_f0100_row26_col21,#T_f0100_row26_col22,#T_f0100_row26_col23,#T_f0100_row27_col0,#T_f0100_row27_col1,#T_f0100_row27_col2,#T_f0100_row27_col3,#T_f0100_row27_col4,#T_f0100_row27_col7,#T_f0100_row27_col9,#T_f0100_row27_col12,#T_f0100_row27_col14,#T_f0100_row27_col15,#T_f0100_row27_col16,#T_f0100_row27_col17,#T_f0100_row27_col18,#T_f0100_row27_col19,#T_f0100_row27_col20,#T_f0100_row27_col23,#T_f0100_row28_col0,#T_f0100_row28_col1,#T_f0100_row28_col2,#T_f0100_row28_col3,#T_f0100_row28_col4,#T_f0100_row28_col5,#T_f0100_row28_col6,#T_f0100_row28_col7,#T_f0100_row28_col8,#T_f0100_row28_col9,#T_f0100_row28_col10,#T_f0100_row28_col12,#T_f0100_row28_col13,#T_f0100_row28_col14,#T_f0100_row28_col15,#T_f0100_row28_col16,#T_f0100_row28_col17,#T_f0100_row28_col18,#T_f0100_row28_col19,#T_f0100_row28_col20,#T_f0100_row28_col21,#T_f0100_row28_col22,#T_f0100_row29_col0,#T_f0100_row29_col1,#T_f0100_row29_col2,#T_f0100_row29_col3,#T_f0100_row29_col4,#T_f0100_row29_col5,#T_f0100_row29_col6,#T_f0100_row29_col7,#T_f0100_row29_col9,#T_f0100_row29_col10,#T_f0100_row29_col12,#T_f0100_row29_col13,#T_f0100_row29_col15,#T_f0100_row29_col16,#T_f0100_row29_col17,#T_f0100_row29_col18,#T_f0100_row29_col19,#T_f0100_row29_col20,#T_f0100_row29_col21,#T_f0100_row29_col22,#T_f0100_row30_col0,#T_f0100_row30_col1,#T_f0100_row30_col2,#T_f0100_row30_col3,#T_f0100_row30_col4,#T_f0100_row30_col5,#T_f0100_row30_col6,#T_f0100_row30_col7,#T_f0100_row30_col8,#T_f0100_row30_col9,#T_f0100_row30_col10,#T_f0100_row30_col12,#T_f0100_row30_col13,#T_f0100_row30_col15,#T_f0100_row30_col16,#T_f0100_row30_col17,#T_f0100_row30_col18,#T_f0100_row30_col19,#T_f0100_row30_col20,#T_f0100_row30_col21,#T_f0100_row31_col0,#T_f0100_row31_col1,#T_f0100_row31_col2,#T_f0100_row31_col3,#T_f0100_row31_col4,#T_f0100_row31_col5,#T_f0100_row31_col6,#T_f0100_row31_col7,#T_f0100_row31_col9,#T_f0100_row31_col10,#T_f0100_row31_col12,#T_f0100_row31_col13,#T_f0100_row31_col15,#T_f0100_row31_col16,#T_f0100_row31_col17,#T_f0100_row31_col18,#T_f0100_row31_col19,#T_f0100_row31_col20,#T_f0100_row31_col21,#T_f0100_row31_col22,#T_f0100_row32_col0,#T_f0100_row32_col1,#T_f0100_row32_col2,#T_f0100_row32_col3,#T_f0100_row32_col4,#T_f0100_row32_col5,#T_f0100_row32_col6,#T_f0100_row32_col7,#T_f0100_row32_col9,#T_f0100_row32_col10,#T_f0100_row32_col12,#T_f0100_row32_col13,#T_f0100_row32_col14,#T_f0100_row32_col15,#T_f0100_row32_col16,#T_f0100_row32_col17,#T_f0100_row32_col18,#T_f0100_row32_col19,#T_f0100_row32_col20,#T_f0100_row32_col21,#T_f0100_row32_col22,#T_f0100_row32_col23,#T_f0100_row33_col0,#T_f0100_row33_col1,#T_f0100_row33_col2,#T_f0100_row33_col3,#T_f0100_row33_col4,#T_f0100_row33_col6,#T_f0100_row33_col7,#T_f0100_row33_col8,#T_f0100_row33_col9,#T_f0100_row33_col10,#T_f0100_row33_col12,#T_f0100_row33_col13,#T_f0100_row33_col14,#T_f0100_row33_col15,#T_f0100_row33_col16,#T_f0100_row33_col17,#T_f0100_row33_col18,#T_f0100_row33_col19,#T_f0100_row33_col20,#T_f0100_row33_col21,#T_f0100_row33_col23,#T_f0100_row34_col0,#T_f0100_row34_col1,#T_f0100_row34_col2,#T_f0100_row34_col3,#T_f0100_row34_col4,#T_f0100_row34_col5,#T_f0100_row34_col7,#T_f0100_row34_col8,#T_f0100_row34_col9,#T_f0100_row34_col11,#T_f0100_row34_col12,#T_f0100_row34_col13,#T_f0100_row34_col15,#T_f0100_row34_col16,#T_f0100_row34_col17,#T_f0100_row34_col18,#T_f0100_row34_col19,#T_f0100_row34_col20,#T_f0100_row34_col23,#T_f0100_row35_col0,#T_f0100_row35_col1,#T_f0100_row35_col2,#T_f0100_row35_col3,#T_f0100_row35_col4,#T_f0100_row35_col5,#T_f0100_row35_col7,#T_f0100_row35_col8,#T_f0100_row35_col9,#T_f0100_row35_col12,#T_f0100_row35_col13,#T_f0100_row35_col15,#T_f0100_row35_col16,#T_f0100_row35_col17,#T_f0100_row35_col18,#T_f0100_row35_col19,#T_f0100_row35_col20,#T_f0100_row35_col21{
            color:  black;
        }#T_f0100_row0_col14,#T_f0100_row0_col23,#T_f0100_row4_col8,#T_f0100_row4_col23,#T_f0100_row5_col23,#T_f0100_row6_col8,#T_f0100_row6_col14,#T_f0100_row6_col23,#T_f0100_row7_col23,#T_f0100_row8_col23,#T_f0100_row9_col23,#T_f0100_row10_col23,#T_f0100_row11_col23,#T_f0100_row12_col23,#T_f0100_row13_col13,#T_f0100_row13_col14,#T_f0100_row13_col21,#T_f0100_row15_col23,#T_f0100_row16_col23,#T_f0100_row17_col14,#T_f0100_row17_col23,#T_f0100_row18_col23,#T_f0100_row19_col5,#T_f0100_row19_col10,#T_f0100_row19_col13,#T_f0100_row19_col21,#T_f0100_row19_col22,#T_f0100_row20_col11,#T_f0100_row20_col14,#T_f0100_row20_col23,#T_f0100_row21_col5,#T_f0100_row21_col6,#T_f0100_row21_col10,#T_f0100_row21_col13,#T_f0100_row21_col14,#T_f0100_row21_col21,#T_f0100_row21_col22,#T_f0100_row22_col6,#T_f0100_row22_col10,#T_f0100_row22_col11,#T_f0100_row22_col13,#T_f0100_row22_col14,#T_f0100_row22_col21,#T_f0100_row22_col22,#T_f0100_row23_col5,#T_f0100_row23_col6,#T_f0100_row23_col10,#T_f0100_row23_col14,#T_f0100_row23_col21,#T_f0100_row23_col22,#T_f0100_row24_col11,#T_f0100_row24_col14,#T_f0100_row24_col22,#T_f0100_row24_col23,#T_f0100_row25_col6,#T_f0100_row25_col10,#T_f0100_row25_col13,#T_f0100_row25_col21,#T_f0100_row25_col22,#T_f0100_row26_col11,#T_f0100_row27_col5,#T_f0100_row27_col6,#T_f0100_row27_col8,#T_f0100_row27_col10,#T_f0100_row27_col11,#T_f0100_row27_col13,#T_f0100_row27_col21,#T_f0100_row27_col22,#T_f0100_row28_col11,#T_f0100_row28_col23,#T_f0100_row29_col8,#T_f0100_row29_col11,#T_f0100_row29_col14,#T_f0100_row29_col23,#T_f0100_row30_col11,#T_f0100_row30_col14,#T_f0100_row30_col22,#T_f0100_row30_col23,#T_f0100_row31_col8,#T_f0100_row31_col11,#T_f0100_row31_col14,#T_f0100_row31_col23,#T_f0100_row32_col8,#T_f0100_row32_col11,#T_f0100_row33_col5,#T_f0100_row33_col11,#T_f0100_row33_col22,#T_f0100_row34_col6,#T_f0100_row34_col10,#T_f0100_row34_col14,#T_f0100_row34_col21,#T_f0100_row34_col22,#T_f0100_row35_col6,#T_f0100_row35_col10,#T_f0100_row35_col11,#T_f0100_row35_col14,#T_f0100_row35_col22,#T_f0100_row35_col23{
            color:  red;
        }</style><table id="T_f0100_" ><thead>    <tr>        <th class="blank level0" ></th>        <th class="col_heading level0 col0" >名称</th>        <th class="col_heading level0 col1" >行业</th>        <th class="col_heading level0 col2" >负债率</th>        <th class="col_heading level0 col3" >应收比</th>        <th class="col_heading level0 col4" >商誉比</th>        <th class="col_heading level0 col5" >ROE</th>        <th class="col_heading level0 col6" >利润率</th>        <th class="col_heading level0 col7" >收入</th>        <th class="col_heading level0 col8" >收入增长</th>        <th class="col_heading level0 col9" >收入波动</th>        <th class="col_heading level0 col10" >盈利</th>        <th class="col_heading level0 col11" >盈利增长</th>        <th class="col_heading level0 col12" >盈利波动</th>        <th class="col_heading level0 col13" >FCF</th>        <th class="col_heading level0 col14" >FCF增长</th>        <th class="col_heading level0 col15" >FCF波动</th>        <th class="col_heading level0 col16" >PE</th>        <th class="col_heading level0 col17" >PE0</th>        <th class="col_heading level0 col18" >PEG</th>        <th class="col_heading level0 col19" >股息率</th>        <th class="col_heading level0 col20" >市值</th>        <th class="col_heading level0 col21" >DCF</th>        <th class="col_heading level0 col22" >盈利折现</th>        <th class="col_heading level0 col23" >折价率</th>    </tr>    <tr>        <th class="index_name level0" >Symbol</th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>    </tr></thead><tbody>
                <tr>
                        <th id="T_f0100_level0_row0" class="row_heading level0 row0" >BIDU</th>
                        <td id="T_f0100_row0_col0" class="data row0 col0" >Baidu Inc. ADS</td>
                        <td id="T_f0100_row0_col1" class="data row0 col1" >Technology</td>
                        <td id="T_f0100_row0_col2" class="data row0 col2" >42.34</td>
                        <td id="T_f0100_row0_col3" class="data row0 col3" >10.82</td>
                        <td id="T_f0100_row0_col4" class="data row0 col4" >12.18</td>
                        <td id="T_f0100_row0_col5" class="data row0 col5" >11.59</td>
                        <td id="T_f0100_row0_col6" class="data row0 col6" >17.64</td>
                        <td id="T_f0100_row0_col7" class="data row0 col7" >101,268.25</td>
                        <td id="T_f0100_row0_col8" class="data row0 col8" >7.63</td>
                        <td id="T_f0100_row0_col9" class="data row0 col9" >10.70</td>
                        <td id="T_f0100_row0_col10" class="data row0 col10" >17,600.75</td>
                        <td id="T_f0100_row0_col11" class="data row0 col11" >316.86</td>
                        <td id="T_f0100_row0_col12" class="data row0 col12" >589.45</td>
                        <td id="T_f0100_row0_col13" class="data row0 col13" >24,097.50</td>
                        <td id="T_f0100_row0_col14" class="data row0 col14" >-11.75</td>
                        <td id="T_f0100_row0_col15" class="data row0 col15" >8.08</td>
                        <td id="T_f0100_row0_col16" class="data row0 col16" >19.24</td>
                        <td id="T_f0100_row0_col17" class="data row0 col17" >23.40</td>
                        <td id="T_f0100_row0_col18" class="data row0 col18" >0.07</td>
                        <td id="T_f0100_row0_col19" class="data row0 col19" >-</td>
                        <td id="T_f0100_row0_col20" class="data row0 col20" >411,849.15</td>
                        <td id="T_f0100_row0_col21" class="data row0 col21" >217,154.39</td>
                        <td id="T_f0100_row0_col22" class="data row0 col22" >14,101,407.74</td>
                        <td id="T_f0100_row0_col23" class="data row0 col23" >-89.66</td>
            </tr>
            <tr>
                        <th id="T_f0100_level0_row1" class="row_heading level0 row1" >TSM</th>
                        <td id="T_f0100_row1_col0" class="data row1 col0" >Taiwan Semiconductor</td>
                        <td id="T_f0100_row1_col1" class="data row1 col1" >Technology</td>
                        <td id="T_f0100_row1_col2" class="data row1 col2" >32.97</td>
                        <td id="T_f0100_row1_col3" class="data row1 col3" >10.91</td>
                        <td id="T_f0100_row1_col4" class="data row1 col4" >0.29</td>
                        <td id="T_f0100_row1_col5" class="data row1 col5" >23.33</td>
                        <td id="T_f0100_row1_col6" class="data row1 col6" >35.07</td>
                        <td id="T_f0100_row1_col7" class="data row1 col7" >1,104,540.25</td>
                        <td id="T_f0100_row1_col8" class="data row1 col8" >11.48</td>
                        <td id="T_f0100_row1_col9" class="data row1 col9" >11.89</td>
                        <td id="T_f0100_row1_col10" class="data row1 col10" >389,819.56</td>
                        <td id="T_f0100_row1_col11" class="data row1 col11" >16.70</td>
                        <td id="T_f0100_row1_col12" class="data row1 col12" >28.89</td>
                        <td id="T_f0100_row1_col13" class="data row1 col13" >245,811.63</td>
                        <td id="T_f0100_row1_col14" class="data row1 col14" >21.73</td>
                        <td id="T_f0100_row1_col15" class="data row1 col15" >74.11</td>
                        <td id="T_f0100_row1_col16" class="data row1 col16" >32.04</td>
                        <td id="T_f0100_row1_col17" class="data row1 col17" >1.46</td>
                        <td id="T_f0100_row1_col18" class="data row1 col18" >0.09</td>
                        <td id="T_f0100_row1_col19" class="data row1 col19" >-</td>
                        <td id="T_f0100_row1_col20" class="data row1 col20" >569,517.74</td>
                        <td id="T_f0100_row1_col21" class="data row1 col21" >5,416,260.72</td>
                        <td id="T_f0100_row1_col22" class="data row1 col22" >7,625,607.83</td>
                        <td id="T_f0100_row1_col23" class="data row1 col23" >89.49</td>
            </tr>
            <tr>
                        <th id="T_f0100_level0_row2" class="row_heading level0 row2" >YY</th>
                        <td id="T_f0100_row2_col0" class="data row2 col0" >JOYY Inc. American D</td>
                        <td id="T_f0100_row2_col1" class="data row2 col1" >Technology</td>
                        <td id="T_f0100_row2_col2" class="data row2 col2" >22.90</td>
                        <td id="T_f0100_row2_col3" class="data row2 col3" >7.09</td>
                        <td id="T_f0100_row2_col4" class="data row2 col4" >30.02</td>
                        <td id="T_f0100_row2_col5" class="data row2 col5" >16.55</td>
                        <td id="T_f0100_row2_col6" class="data row2 col6" >29.44</td>
                        <td id="T_f0100_row2_col7" class="data row2 col7" >16,541.37</td>
                        <td id="T_f0100_row2_col8" class="data row2 col8" >16.64</td>
                        <td id="T_f0100_row2_col9" class="data row2 col9" >57.73</td>
                        <td id="T_f0100_row2_col10" class="data row2 col10" >4,280.86</td>
                        <td id="T_f0100_row2_col11" class="data row2 col11" >85.34</td>
                        <td id="T_f0100_row2_col12" class="data row2 col12" >110.67</td>
                        <td id="T_f0100_row2_col13" class="data row2 col13" >3,681.99</td>
                        <td id="T_f0100_row2_col14" class="data row2 col14" >3.79</td>
                        <td id="T_f0100_row2_col15" class="data row2 col15" >18.97</td>
                        <td id="T_f0100_row2_col16" class="data row2 col16" >3.82</td>
                        <td id="T_f0100_row2_col17" class="data row2 col17" >8.21</td>
                        <td id="T_f0100_row2_col18" class="data row2 col18" >0.10</td>
                        <td id="T_f0100_row2_col19" class="data row2 col19" >-</td>
                        <td id="T_f0100_row2_col20" class="data row2 col20" >35,143.88</td>
                        <td id="T_f0100_row2_col21" class="data row2 col21" >51,880.00</td>
                        <td id="T_f0100_row2_col22" class="data row2 col22" >315,345.34</td>
                        <td id="T_f0100_row2_col23" class="data row2 col23" >32.26</td>
            </tr>
            <tr>
                        <th id="T_f0100_level0_row3" class="row_heading level0 row3" >JD</th>
                        <td id="T_f0100_row3_col0" class="data row3 col0" >JD.com Inc. American</td>
                        <td id="T_f0100_row3_col1" class="data row3 col1" >Miscellaneous</td>
                        <td id="T_f0100_row3_col2" class="data row3 col2" >47.52</td>
                        <td id="T_f0100_row3_col3" class="data row3 col3" >1.94</td>
                        <td id="T_f0100_row3_col4" class="data row3 col4" >5.81</td>
                        <td id="T_f0100_row3_col5" class="data row3 col5" >9.19</td>
                        <td id="T_f0100_row3_col6" class="data row3 col6" >2.04</td>
                        <td id="T_f0100_row3_col7" class="data row3 col7" >536,760.47</td>
                        <td id="T_f0100_row3_col8" class="data row3 col8" >27.22</td>
                        <td id="T_f0100_row3_col9" class="data row3 col9" >2.22</td>
                        <td id="T_f0100_row3_col10" class="data row3 col10" >14,736.37</td>
                        <td id="T_f0100_row3_col11" class="data row3 col11" >417.65</td>
                        <td id="T_f0100_row3_col12" class="data row3 col12" >1,067.16</td>
                        <td id="T_f0100_row3_col13" class="data row3 col13" >18,140.35</td>
                        <td id="T_f0100_row3_col14" class="data row3 col14" >117.46</td>
                        <td id="T_f0100_row3_col15" class="data row3 col15" >215.36</td>
                        <td id="T_f0100_row3_col16" class="data row3 col16" >15.42</td>
                        <td id="T_f0100_row3_col17" class="data row3 col17" >51.51</td>
                        <td id="T_f0100_row3_col18" class="data row3 col18" >0.12</td>
                        <td id="T_f0100_row3_col19" class="data row3 col19" >-</td>
                        <td id="T_f0100_row3_col20" class="data row3 col20" >759,069.32</td>
                        <td id="T_f0100_row3_col21" class="data row3 col21" >2,129,826.09</td>
                        <td id="T_f0100_row3_col22" class="data row3 col22" >22,477,655.65</td>
                        <td id="T_f0100_row3_col23" class="data row3 col23" >64.36</td>
            </tr>
            <tr>
                        <th id="T_f0100_level0_row4" class="row_heading level0 row4" >KO</th>
                        <td id="T_f0100_row4_col0" class="data row4 col0" >Coca-Cola Company (T</td>
                        <td id="T_f0100_row4_col1" class="data row4 col1" >Consumer Non-Durables</td>
                        <td id="T_f0100_row4_col2" class="data row4 col2" >75.62</td>
                        <td id="T_f0100_row4_col3" class="data row4 col3" >9.52</td>
                        <td id="T_f0100_row4_col4" class="data row4 col4" >90.71</td>
                        <td id="T_f0100_row4_col5" class="data row4 col5" >33.08</td>
                        <td id="T_f0100_row4_col6" class="data row4 col6" >17.40</td>
                        <td id="T_f0100_row4_col7" class="data row4 col7" >35,198.00</td>
                        <td id="T_f0100_row4_col8" class="data row4 col8" >-2.68</td>
                        <td id="T_f0100_row4_col9" class="data row4 col9" >10.28</td>
                        <td id="T_f0100_row4_col10" class="data row4 col10" >6,087.25</td>
                        <td id="T_f0100_row4_col11" class="data row4 col11" >147.01</td>
                        <td id="T_f0100_row4_col12" class="data row4 col12" >233.99</td>
                        <td id="T_f0100_row4_col13" class="data row4 col13" >7,113.50</td>
                        <td id="T_f0100_row4_col14" class="data row4 col14" >18.77</td>
                        <td id="T_f0100_row4_col15" class="data row4 col15" >18.06</td>
                        <td id="T_f0100_row4_col16" class="data row4 col16" >33.68</td>
                        <td id="T_f0100_row4_col17" class="data row4 col17" >39.84</td>
                        <td id="T_f0100_row4_col18" class="data row4 col18" >0.27</td>
                        <td id="T_f0100_row4_col19" class="data row4 col19" >3.23</td>
                        <td id="T_f0100_row4_col20" class="data row4 col20" >242,488.89</td>
                        <td id="T_f0100_row4_col21" class="data row4 col21" >146,234.74</td>
                        <td id="T_f0100_row4_col22" class="data row4 col22" >1,038,431.62</td>
                        <td id="T_f0100_row4_col23" class="data row4 col23" >-65.82</td>
            </tr>
            <tr>
                        <th id="T_f0100_level0_row5" class="row_heading level0 row5" >NTES</th>
                        <td id="T_f0100_row5_col0" class="data row5 col0" >NetEase Inc. America</td>
                        <td id="T_f0100_row5_col1" class="data row5 col1" >Miscellaneous</td>
                        <td id="T_f0100_row5_col2" class="data row5 col2" >33.89</td>
                        <td id="T_f0100_row5_col3" class="data row5 col3" >8.99</td>
                        <td id="T_f0100_row5_col4" class="data row5 col4" >0.39</td>
                        <td id="T_f0100_row5_col5" class="data row5 col5" >21.57</td>
                        <td id="T_f0100_row5_col6" class="data row5 col6" >22.09</td>
                        <td id="T_f0100_row5_col7" class="data row5 col7" >57,131.05</td>
                        <td id="T_f0100_row5_col8" class="data row5 col8" >18.43</td>
                        <td id="T_f0100_row5_col9" class="data row5 col9" >5.14</td>
                        <td id="T_f0100_row5_col10" class="data row5 col10" >12,540.15</td>
                        <td id="T_f0100_row5_col11" class="data row5 col11" >53.15</td>
                        <td id="T_f0100_row5_col12" class="data row5 col12" >166.31</td>
                        <td id="T_f0100_row5_col13" class="data row5 col13" >15,330.20</td>
                        <td id="T_f0100_row5_col14" class="data row5 col14" >33.70</td>
                        <td id="T_f0100_row5_col15" class="data row5 col15" >20.88</td>
                        <td id="T_f0100_row5_col16" class="data row5 col16" >41.17</td>
                        <td id="T_f0100_row5_col17" class="data row5 col17" >39.74</td>
                        <td id="T_f0100_row5_col18" class="data row5 col18" >0.75</td>
                        <td id="T_f0100_row5_col19" class="data row5 col19" >1.18</td>
                        <td id="T_f0100_row5_col20" class="data row5 col20" >498,369.16</td>
                        <td id="T_f0100_row5_col21" class="data row5 col21" >440,855.12</td>
                        <td id="T_f0100_row5_col22" class="data row5 col22" >532,030.60</td>
                        <td id="T_f0100_row5_col23" class="data row5 col23" >-13.05</td>
            </tr>
            <tr>
                        <th id="T_f0100_level0_row6" class="row_heading level0 row6" >TCOM</th>
                        <td id="T_f0100_row6_col0" class="data row6 col0" >Trip.com Group Limit</td>
                        <td id="T_f0100_row6_col1" class="data row6 col1" >Miscellaneous</td>
                        <td id="T_f0100_row6_col2" class="data row6 col2" >45.76</td>
                        <td id="T_f0100_row6_col3" class="data row6 col3" >48.59</td>
                        <td id="T_f0100_row6_col4" class="data row6 col4" >59.14</td>
                        <td id="T_f0100_row6_col5" class="data row6 col5" >1.84</td>
                        <td id="T_f0100_row6_col6" class="data row6 col6" >3.39</td>
                        <td id="T_f0100_row6_col7" class="data row6 col7" >27,935.75</td>
                        <td id="T_f0100_row6_col8" class="data row6 col8" >-5.97</td>
                        <td id="T_f0100_row6_col9" class="data row6 col9" >36.96</td>
                        <td id="T_f0100_row6_col10" class="data row6 col10" >1,757.75</td>
                        <td id="T_f0100_row6_col11" class="data row6 col11" >111.92</td>
                        <td id="T_f0100_row6_col12" class="data row6 col12" >365.78</td>
                        <td id="T_f0100_row6_col13" class="data row6 col13" >3,798.75</td>
                        <td id="T_f0100_row6_col14" class="data row6 col14" >-56.07</td>
                        <td id="T_f0100_row6_col15" class="data row6 col15" >96.00</td>
                        <td id="T_f0100_row6_col16" class="data row6 col16" >-</td>
                        <td id="T_f0100_row6_col17" class="data row6 col17" >85.07</td>
                        <td id="T_f0100_row6_col18" class="data row6 col18" >0.76</td>
                        <td id="T_f0100_row6_col19" class="data row6 col19" >-</td>
                        <td id="T_f0100_row6_col20" class="data row6 col20" >149,536.65</td>
                        <td id="T_f0100_row6_col21" class="data row6 col21" >5,819.79</td>
                        <td id="T_f0100_row6_col22" class="data row6 col22" >191,390.21</td>
                        <td id="T_f0100_row6_col23" class="data row6 col23" >-2,469.45</td>
            </tr>
            <tr>
                        <th id="T_f0100_level0_row7" class="row_heading level0 row7" >BABA</th>
                        <td id="T_f0100_row7_col0" class="data row7 col0" >Alibaba Group Holdin</td>
                        <td id="T_f0100_row7_col1" class="data row7 col1" >Consumer Services</td>
                        <td id="T_f0100_row7_col2" class="data row7 col2" >33.70</td>
                        <td id="T_f0100_row7_col3" class="data row7 col3" >8.56</td>
                        <td id="T_f0100_row7_col4" class="data row7 col4" >36.64</td>
                        <td id="T_f0100_row7_col5" class="data row7 col5" >17.71</td>
                        <td id="T_f0100_row7_col6" class="data row7 col6" >26.46</td>
                        <td id="T_f0100_row7_col7" class="data row7 col7" >323,773.50</td>
                        <td id="T_f0100_row7_col8" class="data row7 col8" >47.99</td>
                        <td id="T_f0100_row7_col9" class="data row7 col9" >11.65</td>
                        <td id="T_f0100_row7_col10" class="data row7 col10" >86,271.75</td>
                        <td id="T_f0100_row7_col11" class="data row7 col11" >51.30</td>
                        <td id="T_f0100_row7_col12" class="data row7 col12" >16.92</td>
                        <td id="T_f0100_row7_col13" class="data row7 col13" >110,393.75</td>
                        <td id="T_f0100_row7_col14" class="data row7 col14" >28.25</td>
                        <td id="T_f0100_row7_col15" class="data row7 col15" >19.50</td>
                        <td id="T_f0100_row7_col16" class="data row7 col16" >24.47</td>
                        <td id="T_f0100_row7_col17" class="data row7 col17" >44.44</td>
                        <td id="T_f0100_row7_col18" class="data row7 col18" >0.87</td>
                        <td id="T_f0100_row7_col19" class="data row7 col19" >-</td>
                        <td id="T_f0100_row7_col20" class="data row7 col20" >3,833,763.20</td>
                        <td id="T_f0100_row7_col21" class="data row7 col21" >2,820,112.85</td>
                        <td id="T_f0100_row7_col22" class="data row7 col22" >3,534,629.16</td>
                        <td id="T_f0100_row7_col23" class="data row7 col23" >-35.94</td>
            </tr>
            <tr>
                        <th id="T_f0100_level0_row8" class="row_heading level0 row8" >GOOGL</th>
                        <td id="T_f0100_row8_col0" class="data row8 col0" >Alphabet Inc. Class </td>
                        <td id="T_f0100_row8_col1" class="data row8 col1" >Technology</td>
                        <td id="T_f0100_row8_col2" class="data row8 col2" >30.37</td>
                        <td id="T_f0100_row8_col3" class="data row8 col3" >17.19</td>
                        <td id="T_f0100_row8_col4" class="data row8 col4" >9.51</td>
                        <td id="T_f0100_row8_col5" class="data row8 col5" >15.19</td>
                        <td id="T_f0100_row8_col6" class="data row8 col6" >19.29</td>
                        <td id="T_f0100_row8_col7" class="data row8 col7" >148,014.50</td>
                        <td id="T_f0100_row8_col8" class="data row8 col8" >18.16</td>
                        <td id="T_f0100_row8_col9" class="data row8 col9" >5.33</td>
                        <td id="T_f0100_row8_col10" class="data row8 col10" >29,502.50</td>
                        <td id="T_f0100_row8_col11" class="data row8 col11" >57.24</td>
                        <td id="T_f0100_row8_col12" class="data row8 col12" >74.09</td>
                        <td id="T_f0100_row8_col13" class="data row8 col13" >30,138.50</td>
                        <td id="T_f0100_row8_col14" class="data row8 col14" >23.16</td>
                        <td id="T_f0100_row8_col15" class="data row8 col15" >23.99</td>
                        <td id="T_f0100_row8_col16" class="data row8 col16" >31.90</td>
                        <td id="T_f0100_row8_col17" class="data row8 col17" >54.91</td>
                        <td id="T_f0100_row8_col18" class="data row8 col18" >0.96</td>
                        <td id="T_f0100_row8_col19" class="data row8 col19" >-</td>
                        <td id="T_f0100_row8_col20" class="data row8 col20" >1,620,004.04</td>
                        <td id="T_f0100_row8_col21" class="data row8 col21" >686,423.57</td>
                        <td id="T_f0100_row8_col22" class="data row8 col22" >1,350,485.14</td>
                        <td id="T_f0100_row8_col23" class="data row8 col23" >-136.01</td>
            </tr>
            <tr>
                        <th id="T_f0100_level0_row9" class="row_heading level0 row9" >GOOG</th>
                        <td id="T_f0100_row9_col0" class="data row9 col0" >Alphabet Inc. Class </td>
                        <td id="T_f0100_row9_col1" class="data row9 col1" >Technology</td>
                        <td id="T_f0100_row9_col2" class="data row9 col2" >30.37</td>
                        <td id="T_f0100_row9_col3" class="data row9 col3" >17.19</td>
                        <td id="T_f0100_row9_col4" class="data row9 col4" >9.51</td>
                        <td id="T_f0100_row9_col5" class="data row9 col5" >15.19</td>
                        <td id="T_f0100_row9_col6" class="data row9 col6" >19.29</td>
                        <td id="T_f0100_row9_col7" class="data row9 col7" >148,014.50</td>
                        <td id="T_f0100_row9_col8" class="data row9 col8" >18.16</td>
                        <td id="T_f0100_row9_col9" class="data row9 col9" >5.33</td>
                        <td id="T_f0100_row9_col10" class="data row9 col10" >29,502.50</td>
                        <td id="T_f0100_row9_col11" class="data row9 col11" >57.24</td>
                        <td id="T_f0100_row9_col12" class="data row9 col12" >74.09</td>
                        <td id="T_f0100_row9_col13" class="data row9 col13" >30,138.50</td>
                        <td id="T_f0100_row9_col14" class="data row9 col14" >23.16</td>
                        <td id="T_f0100_row9_col15" class="data row9 col15" >23.99</td>
                        <td id="T_f0100_row9_col16" class="data row9 col16" >32.67</td>
                        <td id="T_f0100_row9_col17" class="data row9 col17" >55.11</td>
                        <td id="T_f0100_row9_col18" class="data row9 col18" >0.96</td>
                        <td id="T_f0100_row9_col19" class="data row9 col19" >-</td>
                        <td id="T_f0100_row9_col20" class="data row9 col20" >1,625,965.46</td>
                        <td id="T_f0100_row9_col21" class="data row9 col21" >686,423.57</td>
                        <td id="T_f0100_row9_col22" class="data row9 col22" >1,350,485.14</td>
                        <td id="T_f0100_row9_col23" class="data row9 col23" >-136.87</td>
            </tr>
            <tr>
                        <th id="T_f0100_level0_row10" class="row_heading level0 row10" >AMZN</th>
                        <td id="T_f0100_row10_col0" class="data row10 col0" >Amazon.com Inc. Comm</td>
                        <td id="T_f0100_row10_col1" class="data row10 col1" >Consumer Services</td>
                        <td id="T_f0100_row10_col2" class="data row10 col2" >70.92</td>
                        <td id="T_f0100_row10_col3" class="data row10 col3" >6.30</td>
                        <td id="T_f0100_row10_col4" class="data row10 col4" >16.08</td>
                        <td id="T_f0100_row10_col5" class="data row10 col5" >18.90</td>
                        <td id="T_f0100_row10_col6" class="data row10 col6" >3.92</td>
                        <td id="T_f0100_row10_col7" class="data row10 col7" >269,334.75</td>
                        <td id="T_f0100_row10_col8" class="data row10 col8" >29.67</td>
                        <td id="T_f0100_row10_col9" class="data row10 col9" >8.65</td>
                        <td id="T_f0100_row10_col10" class="data row10 col10" >11,506.25</td>
                        <td id="T_f0100_row10_col11" class="data row10 col11" >110.41</td>
                        <td id="T_f0100_row10_col12" class="data row10 col12" >110.91</td>
                        <td id="T_f0100_row10_col13" class="data row10 col13" >17,820.75</td>
                        <td id="T_f0100_row10_col14" class="data row10 col14" >71.58</td>
                        <td id="T_f0100_row10_col15" class="data row10 col15" >85.13</td>
                        <td id="T_f0100_row10_col16" class="data row10 col16" >61.00</td>
                        <td id="T_f0100_row10_col17" class="data row10 col17" >140.53</td>
                        <td id="T_f0100_row10_col18" class="data row10 col18" >1.27</td>
                        <td id="T_f0100_row10_col19" class="data row10 col19" >-</td>
                        <td id="T_f0100_row10_col20" class="data row10 col20" >1,616,973.66</td>
                        <td id="T_f0100_row10_col21" class="data row10 col21" >1,049,585.87</td>
                        <td id="T_f0100_row10_col22" class="data row10 col22" >1,226,866.41</td>
                        <td id="T_f0100_row10_col23" class="data row10 col23" >-54.06</td>
            </tr>
            <tr>
                        <th id="T_f0100_level0_row11" class="row_heading level0 row11" >MSFT</th>
                        <td id="T_f0100_row11_col0" class="data row11 col0" >Microsoft Corporatio</td>
                        <td id="T_f0100_row11_col1" class="data row11 col1" >Technology</td>
                        <td id="T_f0100_row11_col2" class="data row11 col2" >60.74</td>
                        <td id="T_f0100_row11_col3" class="data row11 col3" >22.38</td>
                        <td id="T_f0100_row11_col4" class="data row11 col4" >36.64</td>
                        <td id="T_f0100_row11_col5" class="data row11 col5" >31.22</td>
                        <td id="T_f0100_row11_col6" class="data row11 col6" >25.89</td>
                        <td id="T_f0100_row11_col7" class="data row11 col7" >118,947.25</td>
                        <td id="T_f0100_row11_col8" class="data row11 col8" >13.98</td>
                        <td id="T_f0100_row11_col9" class="data row11 col9" >0.32</td>
                        <td id="T_f0100_row11_col10" class="data row11 col10" >31,395.25</td>
                        <td id="T_f0100_row11_col11" class="data row11 col11" >38.22</td>
                        <td id="T_f0100_row11_col12" class="data row11 col12" >88.66</td>
                        <td id="T_f0100_row11_col13" class="data row11 col13" >36,781.00</td>
                        <td id="T_f0100_row11_col14" class="data row11 col14" >13.21</td>
                        <td id="T_f0100_row11_col15" class="data row11 col15" >9.03</td>
                        <td id="T_f0100_row11_col16" class="data row11 col16" >34.18</td>
                        <td id="T_f0100_row11_col17" class="data row11 col17" >60.16</td>
                        <td id="T_f0100_row11_col18" class="data row11 col18" >1.57</td>
                        <td id="T_f0100_row11_col19" class="data row11 col19" >1.63</td>
                        <td id="T_f0100_row11_col20" class="data row11 col20" >1,888,842.42</td>
                        <td id="T_f0100_row11_col21" class="data row11 col21" >660,667.61</td>
                        <td id="T_f0100_row11_col22" class="data row11 col22" >992,646.44</td>
                        <td id="T_f0100_row11_col23" class="data row11 col23" >-185.90</td>
            </tr>
            <tr>
                        <th id="T_f0100_level0_row12" class="row_heading level0 row12" >FB</th>
                        <td id="T_f0100_row12_col0" class="data row12 col0" >Facebook Inc. Class </td>
                        <td id="T_f0100_row12_col1" class="data row12 col1" >Technology</td>
                        <td id="T_f0100_row12_col2" class="data row12 col2" >19.47</td>
                        <td id="T_f0100_row12_col3" class="data row12 col3" >13.19</td>
                        <td id="T_f0100_row12_col4" class="data row12 col4" >14.85</td>
                        <td id="T_f0100_row12_col5" class="data row12 col5" >22.18</td>
                        <td id="T_f0100_row12_col6" class="data row12 col6" >34.71</td>
                        <td id="T_f0100_row12_col7" class="data row12 col7" >63,288.25</td>
                        <td id="T_f0100_row12_col8" class="data row12 col8" >28.52</td>
                        <td id="T_f0100_row12_col9" class="data row12 col9" >8.05</td>
                        <td id="T_f0100_row12_col10" class="data row12 col10" >21,419.25</td>
                        <td id="T_f0100_row12_col11" class="data row12 col11" >26.68</td>
                        <td id="T_f0100_row12_col12" class="data row12 col12" >38.49</td>
                        <td id="T_f0100_row12_col13" class="data row12 col13" >19,421.50</td>
                        <td id="T_f0100_row12_col14" class="data row12 col14" >12.46</td>
                        <td id="T_f0100_row12_col15" class="data row12 col15" >25.14</td>
                        <td id="T_f0100_row12_col16" class="data row12 col16" >28.31</td>
                        <td id="T_f0100_row12_col17" class="data row12 col17" >43.73</td>
                        <td id="T_f0100_row12_col18" class="data row12 col18" >1.64</td>
                        <td id="T_f0100_row12_col19" class="data row12 col19" >-</td>
                        <td id="T_f0100_row12_col20" class="data row12 col20" >936,694.25</td>
                        <td id="T_f0100_row12_col21" class="data row12 col21" >342,336.46</td>
                        <td id="T_f0100_row12_col22" class="data row12 col22" >528,389.22</td>
                        <td id="T_f0100_row12_col23" class="data row12 col23" >-173.62</td>
            </tr>
            <tr>
                        <th id="T_f0100_level0_row13" class="row_heading level0 row13" >NFLX</th>
                        <td id="T_f0100_row13_col0" class="data row13 col0" >Netflix Inc. Common </td>
                        <td id="T_f0100_row13_col1" class="data row13 col1" >Consumer Services</td>
                        <td id="T_f0100_row13_col2" class="data row13 col2" >71.83</td>
                        <td id="T_f0100_row13_col3" class="data row13 col3" >5.41</td>
                        <td id="T_f0100_row13_col4" class="data row13 col4" >-</td>
                        <td id="T_f0100_row13_col5" class="data row13 col5" >22.08</td>
                        <td id="T_f0100_row13_col6" class="data row13 col6" >8.19</td>
                        <td id="T_f0100_row13_col7" class="data row13 col7" >18,159.89</td>
                        <td id="T_f0100_row13_col8" class="data row13 col8" >28.90</td>
                        <td id="T_f0100_row13_col9" class="data row13 col9" >5.64</td>
                        <td id="T_f0100_row13_col10" class="data row13 col10" >1,599.62</td>
                        <td id="T_f0100_row13_col11" class="data row13 col11" >72.92</td>
                        <td id="T_f0100_row13_col12" class="data row13 col12" >38.05</td>
                        <td id="T_f0100_row13_col13" class="data row13 col13" >-1,506.22</td>
                        <td id="T_f0100_row13_col14" class="data row13 col14" >-35.24</td>
                        <td id="T_f0100_row13_col15" class="data row13 col15" >110.73</td>
                        <td id="T_f0100_row13_col16" class="data row13 col16" >59.87</td>
                        <td id="T_f0100_row13_col17" class="data row13 col17" >137.14</td>
                        <td id="T_f0100_row13_col18" class="data row13 col18" >1.88</td>
                        <td id="T_f0100_row13_col19" class="data row13 col19" >-</td>
                        <td id="T_f0100_row13_col20" class="data row13 col20" >219,369.19</td>
                        <td id="T_f0100_row13_col21" class="data row13 col21" >-5,969.98</td>
                        <td id="T_f0100_row13_col22" class="data row13 col22" >96,352.89</td>
                        <td id="T_f0100_row13_col23" class="data row13 col23" >-</td>
            </tr>
            <tr>
                        <th id="T_f0100_level0_row14" class="row_heading level0 row14" >MOMO</th>
                        <td id="T_f0100_row14_col0" class="data row14 col0" >Momo Inc. American D</td>
                        <td id="T_f0100_row14_col1" class="data row14 col1" >Technology</td>
                        <td id="T_f0100_row14_col2" class="data row14 col2" >36.11</td>
                        <td id="T_f0100_row14_col3" class="data row14 col3" >2.13</td>
                        <td id="T_f0100_row14_col4" class="data row14 col4" >27.93</td>
                        <td id="T_f0100_row14_col5" class="data row14 col5" >23.50</td>
                        <td id="T_f0100_row14_col6" class="data row14 col6" >19.16</td>
                        <td id="T_f0100_row14_col7" class="data row14 col7" >13,583.52</td>
                        <td id="T_f0100_row14_col8" class="data row14 col8" >22.03</td>
                        <td id="T_f0100_row14_col9" class="data row14 col9" >31.58</td>
                        <td id="T_f0100_row14_col10" class="data row14 col10" >2,509.56</td>
                        <td id="T_f0100_row14_col11" class="data row14 col11" >2.46</td>
                        <td id="T_f0100_row14_col12" class="data row14 col12" >30.25</td>
                        <td id="T_f0100_row14_col13" class="data row14 col13" >3,492.87</td>
                        <td id="T_f0100_row14_col14" class="data row14 col14" >14.14</td>
                        <td id="T_f0100_row14_col15" class="data row14 col15" >57.21</td>
                        <td id="T_f0100_row14_col16" class="data row14 col16" >9.32</td>
                        <td id="T_f0100_row14_col17" class="data row14 col17" >7.24</td>
                        <td id="T_f0100_row14_col18" class="data row14 col18" >2.94</td>
                        <td id="T_f0100_row14_col19" class="data row14 col19" >-</td>
                        <td id="T_f0100_row14_col20" class="data row14 col20" >18,165.41</td>
                        <td id="T_f0100_row14_col21" class="data row14 col21" >64,192.01</td>
                        <td id="T_f0100_row14_col22" class="data row14 col22" >34,114.83</td>
                        <td id="T_f0100_row14_col23" class="data row14 col23" >71.70</td>
            </tr>
            <tr>
                        <th id="T_f0100_level0_row15" class="row_heading level0 row15" >AAPL</th>
                        <td id="T_f0100_row15_col0" class="data row15 col0" >Apple Inc. Common St</td>
                        <td id="T_f0100_row15_col1" class="data row15 col1" >Technology</td>
                        <td id="T_f0100_row15_col2" class="data row15 col2" >79.83</td>
                        <td id="T_f0100_row15_col3" class="data row15 col3" >13.64</td>
                        <td id="T_f0100_row15_col4" class="data row15 col4" >-</td>
                        <td id="T_f0100_row15_col5" class="data row15 col5" >60.14</td>
                        <td id="T_f0100_row15_col6" class="data row15 col6" >21.41</td>
                        <td id="T_f0100_row15_col7" class="data row15 col7" >257,379.50</td>
                        <td id="T_f0100_row15_col8" class="data row15 col8" >6.44</td>
                        <td id="T_f0100_row15_col9" class="data row15 col9" >8.99</td>
                        <td id="T_f0100_row15_col10" class="data row15 col10" >55,137.25</td>
                        <td id="T_f0100_row15_col11" class="data row15 col11" >6.61</td>
                        <td id="T_f0100_row15_col12" class="data row15 col12" >15.33</td>
                        <td id="T_f0100_row15_col13" class="data row15 col13" >62,039.00</td>
                        <td id="T_f0100_row15_col14" class="data row15 col14" >13.42</td>
                        <td id="T_f0100_row15_col15" class="data row15 col15" >18.68</td>
                        <td id="T_f0100_row15_col16" class="data row15 col16" >28.30</td>
                        <td id="T_f0100_row15_col17" class="data row15 col17" >38.10</td>
                        <td id="T_f0100_row15_col18" class="data row15 col18" >5.76</td>
                        <td id="T_f0100_row15_col19" class="data row15 col19" >1.37</td>
                        <td id="T_f0100_row15_col20" class="data row15 col20" >2,100,801.96</td>
                        <td id="T_f0100_row15_col21" class="data row15 col21" >1,120,121.51</td>
                        <td id="T_f0100_row15_col22" class="data row15 col22" >837,114.67</td>
                        <td id="T_f0100_row15_col23" class="data row15 col23" >-87.55</td>
            </tr>
            <tr>
                        <th id="T_f0100_level0_row16" class="row_heading level0 row16" >NVDA</th>
                        <td id="T_f0100_row16_col0" class="data row16 col0" >NVIDIA Corporation C</td>
                        <td id="T_f0100_row16_col1" class="data row16 col1" >Technology</td>
                        <td id="T_f0100_row16_col2" class="data row16 col2" >41.33</td>
                        <td id="T_f0100_row16_col3" class="data row16 col3" >14.57</td>
                        <td id="T_f0100_row16_col4" class="data row16 col4" >24.82</td>
                        <td id="T_f0100_row16_col5" class="data row16 col5" >33.42</td>
                        <td id="T_f0100_row16_col6" class="data row16 col6" >29.58</td>
                        <td id="T_f0100_row16_col7" class="data row16 col7" >12,255.75</td>
                        <td id="T_f0100_row16_col8" class="data row16 col8" >22.18</td>
                        <td id="T_f0100_row16_col9" class="data row16 col9" >29.80</td>
                        <td id="T_f0100_row16_col10" class="data row16 col10" >3,579.00</td>
                        <td id="T_f0100_row16_col11" class="data row16 col11" >19.45</td>
                        <td id="T_f0100_row16_col12" class="data row16 col12" >45.97</td>
                        <td id="T_f0100_row16_col13" class="data row16 col13" >3,754.50</td>
                        <td id="T_f0100_row16_col14" class="data row16 col14" >17.95</td>
                        <td id="T_f0100_row16_col15" class="data row16 col15" >15.59</td>
                        <td id="T_f0100_row16_col16" class="data row16 col16" >101.90</td>
                        <td id="T_f0100_row16_col17" class="data row16 col17" >126.41</td>
                        <td id="T_f0100_row16_col18" class="data row16 col18" >6.50</td>
                        <td id="T_f0100_row16_col19" class="data row16 col19" >0.34</td>
                        <td id="T_f0100_row16_col20" class="data row16 col20" >452,421.26</td>
                        <td id="T_f0100_row16_col21" class="data row16 col21" >75,677.12</td>
                        <td id="T_f0100_row16_col22" class="data row16 col22" >74,767.20</td>
                        <td id="T_f0100_row16_col23" class="data row16 col23" >-497.83</td>
            </tr>
            <tr>
                        <th id="T_f0100_level0_row17" class="row_heading level0 row17" >EDU</th>
                        <td id="T_f0100_row17_col0" class="data row17 col0" >New Oriental Educati</td>
                        <td id="T_f0100_row17_col1" class="data row17 col1" >Miscellaneous</td>
                        <td id="T_f0100_row17_col2" class="data row17 col2" >56.23</td>
                        <td id="T_f0100_row17_col3" class="data row17 col3" >1.59</td>
                        <td id="T_f0100_row17_col4" class="data row17 col4" >2.94</td>
                        <td id="T_f0100_row17_col5" class="data row17 col5" >14.10</td>
                        <td id="T_f0100_row17_col6" class="data row17 col6" >11.65</td>
                        <td id="T_f0100_row17_col7" class="data row17 col7" >2,730.53</td>
                        <td id="T_f0100_row17_col8" class="data row17 col8" >26.03</td>
                        <td id="T_f0100_row17_col9" class="data row17 col9" >10.23</td>
                        <td id="T_f0100_row17_col10" class="data row17 col10" >305.50</td>
                        <td id="T_f0100_row17_col11" class="data row17 col11" >20.64</td>
                        <td id="T_f0100_row17_col12" class="data row17 col12" >47.90</td>
                        <td id="T_f0100_row17_col13" class="data row17 col13" >528.81</td>
                        <td id="T_f0100_row17_col14" class="data row17 col14" >-1.15</td>
                        <td id="T_f0100_row17_col15" class="data row17 col15" >9.44</td>
                        <td id="T_f0100_row17_col16" class="data row17 col16" >38.42</td>
                        <td id="T_f0100_row17_col17" class="data row17 col17" >325.60</td>
                        <td id="T_f0100_row17_col18" class="data row17 col18" >15.78</td>
                        <td id="T_f0100_row17_col19" class="data row17 col19" >-</td>
                        <td id="T_f0100_row17_col20" class="data row17 col20" >99,470.20</td>
                        <td id="T_f0100_row17_col21" class="data row17 col21" >6,507.15</td>
                        <td id="T_f0100_row17_col22" class="data row17 col22" >6,562.16</td>
                        <td id="T_f0100_row17_col23" class="data row17 col23" >-1,428.63</td>
            </tr>
            <tr>
                        <th id="T_f0100_level0_row18" class="row_heading level0 row18" >WB</th>
                        <td id="T_f0100_row18_col0" class="data row18 col0" >Weibo Corporation Am</td>
                        <td id="T_f0100_row18_col1" class="data row18 col1" >Technology</td>
                        <td id="T_f0100_row18_col2" class="data row18 col2" >54.44</td>
                        <td id="T_f0100_row18_col3" class="data row18 col3" >73.45</td>
                        <td id="T_f0100_row18_col4" class="data row18 col4" >2.19</td>
                        <td id="T_f0100_row18_col5" class="data row18 col5" >23.78</td>
                        <td id="T_f0100_row18_col6" class="data row18 col6" >27.62</td>
                        <td id="T_f0100_row18_col7" class="data row18 col7" >1,581.35</td>
                        <td id="T_f0100_row18_col8" class="data row18 col8" >15.96</td>
                        <td id="T_f0100_row18_col9" class="data row18 col9" >29.20</td>
                        <td id="T_f0100_row18_col10" class="data row18 col10" >433.11</td>
                        <td id="T_f0100_row18_col11" class="data row18 col11" >4.01</td>
                        <td id="T_f0100_row18_col12" class="data row18 col12" >51.69</td>
                        <td id="T_f0100_row18_col13" class="data row18 col13" >573.77</td>
                        <td id="T_f0100_row18_col14" class="data row18 col14" >12.40</td>
                        <td id="T_f0100_row18_col15" class="data row18 col15" >22.24</td>
                        <td id="T_f0100_row18_col16" class="data row18 col16" >34.59</td>
                        <td id="T_f0100_row18_col17" class="data row18 col17" >159.19</td>
                        <td id="T_f0100_row18_col18" class="data row18 col18" >39.69</td>
                        <td id="T_f0100_row18_col19" class="data row18 col19" >-</td>
                        <td id="T_f0100_row18_col20" class="data row18 col20" >68,948.67</td>
                        <td id="T_f0100_row18_col21" class="data row18 col21" >10,099.10</td>
                        <td id="T_f0100_row18_col22" class="data row18 col22" >6,138.10</td>
                        <td id="T_f0100_row18_col23" class="data row18 col23" >-582.72</td>
            </tr>
            <tr>
                        <th id="T_f0100_level0_row19" class="row_heading level0 row19" >TLSA</th>
                        <td id="T_f0100_row19_col0" class="data row19 col0" >Tiziana Life Science</td>
                        <td id="T_f0100_row19_col1" class="data row19 col1" >Health Care</td>
                        <td id="T_f0100_row19_col2" class="data row19 col2" >331.88</td>
                        <td id="T_f0100_row19_col3" class="data row19 col3" >-</td>
                        <td id="T_f0100_row19_col4" class="data row19 col4" >-</td>
                        <td id="T_f0100_row19_col5" class="data row19 col5" >-299.85</td>
                        <td id="T_f0100_row19_col6" class="data row19 col6" >-</td>
                        <td id="T_f0100_row19_col7" class="data row19 col7" >-</td>
                        <td id="T_f0100_row19_col8" class="data row19 col8" >-</td>
                        <td id="T_f0100_row19_col9" class="data row19 col9" >-</td>
                        <td id="T_f0100_row19_col10" class="data row19 col10" >-8.26</td>
                        <td id="T_f0100_row19_col11" class="data row19 col11" >9.68</td>
                        <td id="T_f0100_row19_col12" class="data row19 col12" >15.05</td>
                        <td id="T_f0100_row19_col13" class="data row19 col13" >-6.02</td>
                        <td id="T_f0100_row19_col14" class="data row19 col14" >18.40</td>
                        <td id="T_f0100_row19_col15" class="data row19 col15" >49.60</td>
                        <td id="T_f0100_row19_col16" class="data row19 col16" >-</td>
                        <td id="T_f0100_row19_col17" class="data row19 col17" >-</td>
                        <td id="T_f0100_row19_col18" class="data row19 col18" >-</td>
                        <td id="T_f0100_row19_col19" class="data row19 col19" >-</td>
                        <td id="T_f0100_row19_col20" class="data row19 col20" >209.44</td>
                        <td id="T_f0100_row19_col21" class="data row19 col21" >-122.69</td>
                        <td id="T_f0100_row19_col22" class="data row19 col22" >-135.84</td>
                        <td id="T_f0100_row19_col23" class="data row19 col23" >-</td>
            </tr>
            <tr>
                        <th id="T_f0100_level0_row20" class="row_heading level0 row20" >SOGO</th>
                        <td id="T_f0100_row20_col0" class="data row20 col0" >Sogou Inc. American </td>
                        <td id="T_f0100_row20_col1" class="data row20 col1" >Technology</td>
                        <td id="T_f0100_row20_col2" class="data row20 col2" >29.89</td>
                        <td id="T_f0100_row20_col3" class="data row20 col3" >8.24</td>
                        <td id="T_f0100_row20_col4" class="data row20 col4" >0.67</td>
                        <td id="T_f0100_row20_col5" class="data row20 col5" >4.04</td>
                        <td id="T_f0100_row20_col6" class="data row20 col6" >3.43</td>
                        <td id="T_f0100_row20_col7" class="data row20 col7" >1,032.36</td>
                        <td id="T_f0100_row20_col8" class="data row20 col8" >2.30</td>
                        <td id="T_f0100_row20_col9" class="data row20 col9" >22.50</td>
                        <td id="T_f0100_row20_col10" class="data row20 col10" >40.47</td>
                        <td id="T_f0100_row20_col11" class="data row20 col11" >-70.36</td>
                        <td id="T_f0100_row20_col12" class="data row20 col12" >131.71</td>
                        <td id="T_f0100_row20_col13" class="data row20 col13" >73.20</td>
                        <td id="T_f0100_row20_col14" class="data row20 col14" >-4.09</td>
                        <td id="T_f0100_row20_col15" class="data row20 col15" >162.33</td>
                        <td id="T_f0100_row20_col16" class="data row20 col16" >-</td>
                        <td id="T_f0100_row20_col17" class="data row20 col17" >79.59</td>
                        <td id="T_f0100_row20_col18" class="data row20 col18" >-</td>
                        <td id="T_f0100_row20_col19" class="data row20 col19" >-</td>
                        <td id="T_f0100_row20_col20" class="data row20 col20" >3,220.53</td>
                        <td id="T_f0100_row20_col21" class="data row20 col21" >828.78</td>
                        <td id="T_f0100_row20_col22" class="data row20 col22" >26.65</td>
                        <td id="T_f0100_row20_col23" class="data row20 col23" >-288.58</td>
            </tr>
            <tr>
                        <th id="T_f0100_level0_row21" class="row_heading level0 row21" >NIO</th>
                        <td id="T_f0100_row21_col0" class="data row21 col0" >NIO Inc. American de</td>
                        <td id="T_f0100_row21_col1" class="data row21 col1" >Finance</td>
                        <td id="T_f0100_row21_col2" class="data row21 col2" >41.69</td>
                        <td id="T_f0100_row21_col3" class="data row21 col3" >10.10</td>
                        <td id="T_f0100_row21_col4" class="data row21 col4" >-</td>
                        <td id="T_f0100_row21_col5" class="data row21 col5" >-28.88</td>
                        <td id="T_f0100_row21_col6" class="data row21 col6" >-217.18</td>
                        <td id="T_f0100_row21_col7" class="data row21 col7" >7,258.50</td>
                        <td id="T_f0100_row21_col8" class="data row21 col8" >inf</td>
                        <td id="T_f0100_row21_col9" class="data row21 col9" >-</td>
                        <td id="T_f0100_row21_col10" class="data row21 col10" >-11,978.36</td>
                        <td id="T_f0100_row21_col11" class="data row21 col11" >35.53</td>
                        <td id="T_f0100_row21_col12" class="data row21 col12" >149.80</td>
                        <td id="T_f0100_row21_col13" class="data row21 col13" >-6,462.41</td>
                        <td id="T_f0100_row21_col14" class="data row21 col14" >-7.85</td>
                        <td id="T_f0100_row21_col15" class="data row21 col15" >96.90</td>
                        <td id="T_f0100_row21_col16" class="data row21 col16" >-</td>
                        <td id="T_f0100_row21_col17" class="data row21 col17" >-</td>
                        <td id="T_f0100_row21_col18" class="data row21 col18" >-</td>
                        <td id="T_f0100_row21_col19" class="data row21 col19" >-</td>
                        <td id="T_f0100_row21_col20" class="data row21 col20" >68,719.53</td>
                        <td id="T_f0100_row21_col21" class="data row21 col21" >-65,556.70</td>
                        <td id="T_f0100_row21_col22" class="data row21 col22" >-358,063.53</td>
                        <td id="T_f0100_row21_col23" class="data row21 col23" >-</td>
            </tr>
            <tr>
                        <th id="T_f0100_level0_row22" class="row_heading level0 row22" >LI</th>
                        <td id="T_f0100_row22_col0" class="data row22 col0" >Li Auto Inc. America</td>
                        <td id="T_f0100_row22_col1" class="data row22 col1" >Capital Goods</td>
                        <td id="T_f0100_row22_col2" class="data row22 col2" >18.06</td>
                        <td id="T_f0100_row22_col3" class="data row22 col3" >1.31</td>
                        <td id="T_f0100_row22_col4" class="data row22 col4" >-</td>
                        <td id="T_f0100_row22_col5" class="data row22 col5" >35.47</td>
                        <td id="T_f0100_row22_col6" class="data row22 col6" >-429.57</td>
                        <td id="T_f0100_row22_col7" class="data row22 col7" >3,246.99</td>
                        <td id="T_f0100_row22_col8" class="data row22 col8" >inf</td>
                        <td id="T_f0100_row22_col9" class="data row22 col9" >-</td>
                        <td id="T_f0100_row22_col10" class="data row22 col10" >-1,374.17</td>
                        <td id="T_f0100_row22_col11" class="data row22 col11" >-17.32</td>
                        <td id="T_f0100_row22_col12" class="data row22 col12" >108.13</td>
                        <td id="T_f0100_row22_col13" class="data row22 col13" >-866.51</td>
                        <td id="T_f0100_row22_col14" class="data row22 col14" >-85.61</td>
                        <td id="T_f0100_row22_col15" class="data row22 col15" >147.25</td>
                        <td id="T_f0100_row22_col16" class="data row22 col16" >-</td>
                        <td id="T_f0100_row22_col17" class="data row22 col17" >-</td>
                        <td id="T_f0100_row22_col18" class="data row22 col18" >-</td>
                        <td id="T_f0100_row22_col19" class="data row22 col19" >-</td>
                        <td id="T_f0100_row22_col20" class="data row22 col20" >147,056.75</td>
                        <td id="T_f0100_row22_col21" class="data row22 col21" >-169.15</td>
                        <td id="T_f0100_row22_col22" class="data row22 col22" >-10,378.67</td>
                        <td id="T_f0100_row22_col23" class="data row22 col23" >-</td>
            </tr>
            <tr>
                        <th id="T_f0100_level0_row23" class="row_heading level0 row23" >BILI</th>
                        <td id="T_f0100_row23_col0" class="data row23 col0" >Bilibili Inc. Americ</td>
                        <td id="T_f0100_row23_col1" class="data row23 col1" >Technology</td>
                        <td id="T_f0100_row23_col2" class="data row23 col2" >67.39</td>
                        <td id="T_f0100_row23_col3" class="data row23 col3" >11.77</td>
                        <td id="T_f0100_row23_col4" class="data row23 col4" >17.05</td>
                        <td id="T_f0100_row23_col5" class="data row23 col5" >-9.33</td>
                        <td id="T_f0100_row23_col6" class="data row23 col6" >-20.55</td>
                        <td id="T_f0100_row23_col7" class="data row23 col7" >6,343.57</td>
                        <td id="T_f0100_row23_col8" class="data row23 col8" >69.49</td>
                        <td id="T_f0100_row23_col9" class="data row23 col9" >6.72</td>
                        <td id="T_f0100_row23_col10" class="data row23 col10" >-1,372.14</td>
                        <td id="T_f0100_row23_col11" class="data row23 col11" >83.54</td>
                        <td id="T_f0100_row23_col12" class="data row23 col12" >66.70</td>
                        <td id="T_f0100_row23_col13" class="data row23 col13" >203.21</td>
                        <td id="T_f0100_row23_col14" class="data row23 col14" >-110.94</td>
                        <td id="T_f0100_row23_col15" class="data row23 col15" >144.16</td>
                        <td id="T_f0100_row23_col16" class="data row23 col16" >-</td>
                        <td id="T_f0100_row23_col17" class="data row23 col17" >-</td>
                        <td id="T_f0100_row23_col18" class="data row23 col18" >-</td>
                        <td id="T_f0100_row23_col19" class="data row23 col19" >-</td>
                        <td id="T_f0100_row23_col20" class="data row23 col20" >260,576.40</td>
                        <td id="T_f0100_row23_col21" class="data row23 col21" >-22.84</td>
                        <td id="T_f0100_row23_col22" class="data row23 col22" >-98,257.86</td>
                        <td id="T_f0100_row23_col23" class="data row23 col23" >-</td>
            </tr>
            <tr>
                        <th id="T_f0100_level0_row24" class="row_heading level0 row24" >AMD</th>
                        <td id="T_f0100_row24_col0" class="data row24 col0" >Advanced Micro Devic</td>
                        <td id="T_f0100_row24_col1" class="data row24 col1" >Technology</td>
                        <td id="T_f0100_row24_col2" class="data row24 col2" >34.87</td>
                        <td id="T_f0100_row24_col3" class="data row24 col3" >21.26</td>
                        <td id="T_f0100_row24_col4" class="data row24 col4" >4.95</td>
                        <td id="T_f0100_row24_col5" class="data row24 col5" >18.95</td>
                        <td id="T_f0100_row24_col6" class="data row24 col6" >8.79</td>
                        <td id="T_f0100_row24_col7" class="data row24 col7" >7,055.50</td>
                        <td id="T_f0100_row24_col8" class="data row24 col8" >24.09</td>
                        <td id="T_f0100_row24_col9" class="data row24 col9" >20.56</td>
                        <td id="T_f0100_row24_col10" class="data row24 col10" >783.75</td>
                        <td id="T_f0100_row24_col11" class="data row24 col11" >-163.27</td>
                        <td id="T_f0100_row24_col12" class="data row24 col12" >887.22</td>
                        <td id="T_f0100_row24_col13" class="data row24 col13" >205.75</td>
                        <td id="T_f0100_row24_col14" class="data row24 col14" >-34.90</td>
                        <td id="T_f0100_row24_col15" class="data row24 col15" >253.60</td>
                        <td id="T_f0100_row24_col16" class="data row24 col16" >34.25</td>
                        <td id="T_f0100_row24_col17" class="data row24 col17" >126.47</td>
                        <td id="T_f0100_row24_col18" class="data row24 col18" >-</td>
                        <td id="T_f0100_row24_col19" class="data row24 col19" >-</td>
                        <td id="T_f0100_row24_col20" class="data row24 col20" >99,121.34</td>
                        <td id="T_f0100_row24_col21" class="data row24 col21" >826.53</td>
                        <td id="T_f0100_row24_col22" class="data row24 col22" >-2,345.64</td>
                        <td id="T_f0100_row24_col23" class="data row24 col23" >-11,892.51</td>
            </tr>
            <tr>
                        <th id="T_f0100_level0_row25" class="row_heading level0 row25" >XPEV</th>
                        <td id="T_f0100_row25_col0" class="data row25 col0" >XPeng Inc. American </td>
                        <td id="T_f0100_row25_col1" class="data row25 col1" >Capital Goods</td>
                        <td id="T_f0100_row25_col2" class="data row25 col2" >22.99</td>
                        <td id="T_f0100_row25_col3" class="data row25 col3" >22.00</td>
                        <td id="T_f0100_row25_col4" class="data row25 col4" >-</td>
                        <td id="T_f0100_row25_col5" class="data row25 col5" >36.71</td>
                        <td id="T_f0100_row25_col6" class="data row25 col6" >-4,872.58</td>
                        <td id="T_f0100_row25_col7" class="data row25 col7" >2,725.08</td>
                        <td id="T_f0100_row25_col8" class="data row25 col8" >11,983.54</td>
                        <td id="T_f0100_row25_col9" class="data row25 col9" >16,732.64</td>
                        <td id="T_f0100_row25_col10" class="data row25 col10" >-2,607.49</td>
                        <td id="T_f0100_row25_col11" class="data row25 col11" >68.96</td>
                        <td id="T_f0100_row25_col12" class="data row25 col12" >134.29</td>
                        <td id="T_f0100_row25_col13" class="data row25 col13" >-2,927.75</td>
                        <td id="T_f0100_row25_col14" class="data row25 col14" >25.86</td>
                        <td id="T_f0100_row25_col15" class="data row25 col15" >153.64</td>
                        <td id="T_f0100_row25_col16" class="data row25 col16" >-</td>
                        <td id="T_f0100_row25_col17" class="data row25 col17" >-</td>
                        <td id="T_f0100_row25_col18" class="data row25 col18" >-</td>
                        <td id="T_f0100_row25_col19" class="data row25 col19" >-</td>
                        <td id="T_f0100_row25_col20" class="data row25 col20" >188,802.11</td>
                        <td id="T_f0100_row25_col21" class="data row25 col21" >-70,896.59</td>
                        <td id="T_f0100_row25_col22" class="data row25 col22" >-146,876.38</td>
                        <td id="T_f0100_row25_col23" class="data row25 col23" >-</td>
            </tr>
            <tr>
                        <th id="T_f0100_level0_row26" class="row_heading level0 row26" >TAL</th>
                        <td id="T_f0100_row26_col0" class="data row26 col0" >TAL Education Group </td>
                        <td id="T_f0100_row26_col1" class="data row26 col1" >Miscellaneous</td>
                        <td id="T_f0100_row26_col2" class="data row26 col2" >57.03</td>
                        <td id="T_f0100_row26_col3" class="data row26 col3" >0.41</td>
                        <td id="T_f0100_row26_col4" class="data row26 col4" >8.74</td>
                        <td id="T_f0100_row26_col5" class="data row26 col5" >5.10</td>
                        <td id="T_f0100_row26_col6" class="data row26 col6" >4.99</td>
                        <td id="T_f0100_row26_col7" class="data row26 col7" >3,011.77</td>
                        <td id="T_f0100_row26_col8" class="data row26 col8" >38.17</td>
                        <td id="T_f0100_row26_col9" class="data row26 col9" >10.89</td>
                        <td id="T_f0100_row26_col10" class="data row26 col10" >84.87</td>
                        <td id="T_f0100_row26_col11" class="data row26 col11" >-13.23</td>
                        <td id="T_f0100_row26_col12" class="data row26 col12" >108.72</td>
                        <td id="T_f0100_row26_col13" class="data row26 col13" >430.89</td>
                        <td id="T_f0100_row26_col14" class="data row26 col14" >340.43</td>
                        <td id="T_f0100_row26_col15" class="data row26 col15" >669.10</td>
                        <td id="T_f0100_row26_col16" class="data row26 col16" >-</td>
                        <td id="T_f0100_row26_col17" class="data row26 col17" >1,345.47</td>
                        <td id="T_f0100_row26_col18" class="data row26 col18" >-</td>
                        <td id="T_f0100_row26_col19" class="data row26 col19" >-</td>
                        <td id="T_f0100_row26_col20" class="data row26 col20" >114,193.61</td>
                        <td id="T_f0100_row26_col21" class="data row26 col21" >406,502.92</td>
                        <td id="T_f0100_row26_col22" class="data row26 col22" >730.57</td>
                        <td id="T_f0100_row26_col23" class="data row26 col23" >71.91</td>
            </tr>
            <tr>
                        <th id="T_f0100_level0_row27" class="row_heading level0 row27" >XNET</th>
                        <td id="T_f0100_row27_col0" class="data row27 col0" >Xunlei Limited Ameri</td>
                        <td id="T_f0100_row27_col1" class="data row27 col1" >Technology</td>
                        <td id="T_f0100_row27_col2" class="data row27 col2" >30.13</td>
                        <td id="T_f0100_row27_col3" class="data row27 col3" >19.31</td>
                        <td id="T_f0100_row27_col4" class="data row27 col4" >7.74</td>
                        <td id="T_f0100_row27_col5" class="data row27 col5" >-10.96</td>
                        <td id="T_f0100_row27_col6" class="data row27 col6" >-18.19</td>
                        <td id="T_f0100_row27_col7" class="data row27 col7" >199.56</td>
                        <td id="T_f0100_row27_col8" class="data row27 col8" >-1.18</td>
                        <td id="T_f0100_row27_col9" class="data row27 col9" >18.69</td>
                        <td id="T_f0100_row27_col10" class="data row27 col10" >-36.03</td>
                        <td id="T_f0100_row27_col11" class="data row27 col11" >-11.58</td>
                        <td id="T_f0100_row27_col12" class="data row27 col12" >56.28</td>
                        <td id="T_f0100_row27_col13" class="data row27 col13" >-37.66</td>
                        <td id="T_f0100_row27_col14" class="data row27 col14" >22.97</td>
                        <td id="T_f0100_row27_col15" class="data row27 col15" >67.75</td>
                        <td id="T_f0100_row27_col16" class="data row27 col16" >-</td>
                        <td id="T_f0100_row27_col17" class="data row27 col17" >-</td>
                        <td id="T_f0100_row27_col18" class="data row27 col18" >-</td>
                        <td id="T_f0100_row27_col19" class="data row27 col19" >-</td>
                        <td id="T_f0100_row27_col20" class="data row27 col20" >2,045.31</td>
                        <td id="T_f0100_row27_col21" class="data row27 col21" >-853.79</td>
                        <td id="T_f0100_row27_col22" class="data row27 col22" >-326.37</td>
                        <td id="T_f0100_row27_col23" class="data row27 col23" >-</td>
            </tr>
            <tr>
                        <th id="T_f0100_level0_row28" class="row_heading level0 row28" >DIS</th>
                        <td id="T_f0100_row28_col0" class="data row28 col0" >Walt Disney Company </td>
                        <td id="T_f0100_row28_col1" class="data row28 col1" >Consumer Services</td>
                        <td id="T_f0100_row28_col2" class="data row28 col2" >51.62</td>
                        <td id="T_f0100_row28_col3" class="data row28 col3" >19.43</td>
                        <td id="T_f0100_row28_col4" class="data row28 col4" >92.95</td>
                        <td id="T_f0100_row28_col5" class="data row28 col5" >14.14</td>
                        <td id="T_f0100_row28_col6" class="data row28 col6" >12.25</td>
                        <td id="T_f0100_row28_col7" class="data row28 col7" >62,391.50</td>
                        <td id="T_f0100_row28_col8" class="data row28 col8" >6.28</td>
                        <td id="T_f0100_row28_col9" class="data row28 col9" >11.66</td>
                        <td id="T_f0100_row28_col10" class="data row28 col10" >7,442.00</td>
                        <td id="T_f0100_row28_col11" class="data row28 col11" >-32.63</td>
                        <td id="T_f0100_row28_col12" class="data row28 col12" >84.95</td>
                        <td id="T_f0100_row28_col13" class="data row28 col13" >5,969.00</td>
                        <td id="T_f0100_row28_col14" class="data row28 col14" >12.73</td>
                        <td id="T_f0100_row28_col15" class="data row28 col15" >95.13</td>
                        <td id="T_f0100_row28_col16" class="data row28 col16" >-</td>
                        <td id="T_f0100_row28_col17" class="data row28 col17" >43.22</td>
                        <td id="T_f0100_row28_col18" class="data row28 col18" >-</td>
                        <td id="T_f0100_row28_col19" class="data row28 col19" >-</td>
                        <td id="T_f0100_row28_col20" class="data row28 col20" >321,627.75</td>
                        <td id="T_f0100_row28_col21" class="data row28 col21" >105,934.77</td>
                        <td id="T_f0100_row28_col22" class="data row28 col22" >32,678.40</td>
                        <td id="T_f0100_row28_col23" class="data row28 col23" >-203.61</td>
            </tr>
            <tr>
                        <th id="T_f0100_level0_row29" class="row_heading level0 row29" >GILD</th>
                        <td id="T_f0100_row29_col0" class="data row29 col0" >Gilead Sciences Inc.</td>
                        <td id="T_f0100_row29_col1" class="data row29 col1" >Health Care</td>
                        <td id="T_f0100_row29_col2" class="data row29 col2" >73.36</td>
                        <td id="T_f0100_row29_col3" class="data row29 col3" >19.85</td>
                        <td id="T_f0100_row29_col4" class="data row29 col4" >44.54</td>
                        <td id="T_f0100_row29_col5" class="data row29 col5" >18.18</td>
                        <td id="T_f0100_row29_col6" class="data row29 col6" >16.72</td>
                        <td id="T_f0100_row29_col7" class="data row29 col7" >23,843.00</td>
                        <td id="T_f0100_row29_col8" class="data row29 col8" >-1.27</td>
                        <td id="T_f0100_row29_col9" class="data row29 col9" >12.83</td>
                        <td id="T_f0100_row29_col10" class="data row29 col10" >3,898.00</td>
                        <td id="T_f0100_row29_col11" class="data row29 col11" >-27.04</td>
                        <td id="T_f0100_row29_col12" class="data row29 col12" >61.95</td>
                        <td id="T_f0100_row29_col13" class="data row29 col13" >8,655.25</td>
                        <td id="T_f0100_row29_col14" class="data row29 col14" >-10.75</td>
                        <td id="T_f0100_row29_col15" class="data row29 col15" >22.60</td>
                        <td id="T_f0100_row29_col16" class="data row29 col16" >280.96</td>
                        <td id="T_f0100_row29_col17" class="data row29 col17" >21.78</td>
                        <td id="T_f0100_row29_col18" class="data row29 col18" >-</td>
                        <td id="T_f0100_row29_col19" class="data row29 col19" >3.23</td>
                        <td id="T_f0100_row29_col20" class="data row29 col20" >84,898.41</td>
                        <td id="T_f0100_row29_col21" class="data row29 col21" >80,450.20</td>
                        <td id="T_f0100_row29_col22" class="data row29 col22" >21,087.53</td>
                        <td id="T_f0100_row29_col23" class="data row29 col23" >-5.53</td>
            </tr>
            <tr>
                        <th id="T_f0100_level0_row30" class="row_heading level0 row30" >TWTR</th>
                        <td id="T_f0100_row30_col0" class="data row30 col0" >Twitter Inc. Common </td>
                        <td id="T_f0100_row30_col1" class="data row30 col1" >Technology</td>
                        <td id="T_f0100_row30_col2" class="data row30 col2" >40.43</td>
                        <td id="T_f0100_row30_col3" class="data row30 col3" >28.03</td>
                        <td id="T_f0100_row30_col4" class="data row30 col4" >16.47</td>
                        <td id="T_f0100_row30_col5" class="data row30 col5" >4.54</td>
                        <td id="T_f0100_row30_col6" class="data row30 col6" >11.75</td>
                        <td id="T_f0100_row30_col7" class="data row30 col7" >3,165.33</td>
                        <td id="T_f0100_row30_col8" class="data row30 col8" >15.22</td>
                        <td id="T_f0100_row30_col9" class="data row30 col9" >8.64</td>
                        <td id="T_f0100_row30_col10" class="data row30 col10" >356.89</td>
                        <td id="T_f0100_row30_col11" class="data row30 col11" >-457.18</td>
                        <td id="T_f0100_row30_col12" class="data row30 col12" >664.34</td>
                        <td id="T_f0100_row30_col13" class="data row30 col13" >602.11</td>
                        <td id="T_f0100_row30_col14" class="data row30 col14" >-22.52</td>
                        <td id="T_f0100_row30_col15" class="data row30 col15" >56.89</td>
                        <td id="T_f0100_row30_col16" class="data row30 col16" >-</td>
                        <td id="T_f0100_row30_col17" class="data row30 col17" >131.94</td>
                        <td id="T_f0100_row30_col18" class="data row30 col18" >-</td>
                        <td id="T_f0100_row30_col19" class="data row30 col19" >-</td>
                        <td id="T_f0100_row30_col20" class="data row30 col20" >47,089.49</td>
                        <td id="T_f0100_row30_col21" class="data row30 col21" >3,819.84</td>
                        <td id="T_f0100_row30_col22" class="data row30 col22" >-172,382.90</td>
                        <td id="T_f0100_row30_col23" class="data row30 col23" >-1,132.76</td>
            </tr>
            <tr>
                        <th id="T_f0100_level0_row31" class="row_heading level0 row31" >PFE</th>
                        <td id="T_f0100_row31_col0" class="data row31 col0" >Pfizer Inc. Common S</td>
                        <td id="T_f0100_row31_col1" class="data row31 col1" >Health Care</td>
                        <td id="T_f0100_row31_col2" class="data row31 col2" >58.84</td>
                        <td id="T_f0100_row31_col3" class="data row31 col3" >26.71</td>
                        <td id="T_f0100_row31_col4" class="data row31 col4" >78.40</td>
                        <td id="T_f0100_row31_col5" class="data row31 col5" >22.12</td>
                        <td id="T_f0100_row31_col6" class="data row31 col6" >32.59</td>
                        <td id="T_f0100_row31_col7" class="data row31 col7" >44,112.75</td>
                        <td id="T_f0100_row31_col8" class="data row31 col8" >-6.56</td>
                        <td id="T_f0100_row31_col9" class="data row31 col9" >13.65</td>
                        <td id="T_f0100_row31_col10" class="data row31 col10" >14,587.50</td>
                        <td id="T_f0100_row31_col11" class="data row31 col11" >-14.22</td>
                        <td id="T_f0100_row31_col12" class="data row31 col12" >52.18</td>
                        <td id="T_f0100_row31_col13" class="data row31 col13" >12,839.00</td>
                        <td id="T_f0100_row31_col14" class="data row31 col14" >-5.08</td>
                        <td id="T_f0100_row31_col15" class="data row31 col15" >19.84</td>
                        <td id="T_f0100_row31_col16" class="data row31 col16" >22.93</td>
                        <td id="T_f0100_row31_col17" class="data row31 col17" >14.97</td>
                        <td id="T_f0100_row31_col18" class="data row31 col18" >-</td>
                        <td id="T_f0100_row31_col19" class="data row31 col19" >3.67</td>
                        <td id="T_f0100_row31_col20" class="data row31 col20" >218,384.97</td>
                        <td id="T_f0100_row31_col21" class="data row31 col21" >141,262.35</td>
                        <td id="T_f0100_row31_col22" class="data row31 col22" >121,710.97</td>
                        <td id="T_f0100_row31_col23" class="data row31 col23" >-54.60</td>
            </tr>
            <tr>
                        <th id="T_f0100_level0_row32" class="row_heading level0 row32" >WFC</th>
                        <td id="T_f0100_row32_col0" class="data row32 col0" >Wells Fargo & Compan</td>
                        <td id="T_f0100_row32_col1" class="data row32 col1" >Finance</td>
                        <td id="T_f0100_row32_col2" class="data row32 col2" >90.49</td>
                        <td id="T_f0100_row32_col3" class="data row32 col3" >65.36</td>
                        <td id="T_f0100_row32_col4" class="data row32 col4" >16.03</td>
                        <td id="T_f0100_row32_col5" class="data row32 col5" >9.67</td>
                        <td id="T_f0100_row32_col6" class="data row32 col6" >20.40</td>
                        <td id="T_f0100_row32_col7" class="data row32 col7" >77,865.50</td>
                        <td id="T_f0100_row32_col8" class="data row32 col8" >-11.14</td>
                        <td id="T_f0100_row32_col9" class="data row32 col9" >15.71</td>
                        <td id="T_f0100_row32_col10" class="data row32 col10" >16,856.50</td>
                        <td id="T_f0100_row32_col11" class="data row32 col11" >-31.62</td>
                        <td id="T_f0100_row32_col12" class="data row32 col12" >45.11</td>
                        <td id="T_f0100_row32_col13" class="data row32 col13" >-</td>
                        <td id="T_f0100_row32_col14" class="data row32 col14" >-</td>
                        <td id="T_f0100_row32_col15" class="data row32 col15" >-</td>
                        <td id="T_f0100_row32_col16" class="data row32 col16" >32.25</td>
                        <td id="T_f0100_row32_col17" class="data row32 col17" >11.54</td>
                        <td id="T_f0100_row32_col18" class="data row32 col18" >-</td>
                        <td id="T_f0100_row32_col19" class="data row32 col19" >3.71</td>
                        <td id="T_f0100_row32_col20" class="data row32 col20" >194,466.99</td>
                        <td id="T_f0100_row32_col21" class="data row32 col21" >-</td>
                        <td id="T_f0100_row32_col22" class="data row32 col22" >76,917.62</td>
                        <td id="T_f0100_row32_col23" class="data row32 col23" >-</td>
            </tr>
            <tr>
                        <th id="T_f0100_level0_row33" class="row_heading level0 row33" >FUTU</th>
                        <td id="T_f0100_row33_col0" class="data row33 col0" >Futu Holdings Limite</td>
                        <td id="T_f0100_row33_col1" class="data row33 col1" >Finance</td>
                        <td id="T_f0100_row33_col2" class="data row33 col2" >88.35</td>
                        <td id="T_f0100_row33_col3" class="data row33 col3" >860.68</td>
                        <td id="T_f0100_row33_col4" class="data row33 col4" >-</td>
                        <td id="T_f0100_row33_col5" class="data row33 col5" >-16.57</td>
                        <td id="T_f0100_row33_col6" class="data row33 col6" >19.01</td>
                        <td id="T_f0100_row33_col7" class="data row33 col7" >1,276.39</td>
                        <td id="T_f0100_row33_col8" class="data row33 col8" >134.20</td>
                        <td id="T_f0100_row33_col9" class="data row33 col9" >93.31</td>
                        <td id="T_f0100_row33_col10" class="data row33 col10" >405.40</td>
                        <td id="T_f0100_row33_col11" class="data row33 col11" >-363.29</td>
                        <td id="T_f0100_row33_col12" class="data row33 col12" >1,297.94</td>
                        <td id="T_f0100_row33_col13" class="data row33 col13" >7,140.61</td>
                        <td id="T_f0100_row33_col14" class="data row33 col14" >361.72</td>
                        <td id="T_f0100_row33_col15" class="data row33 col15" >563.98</td>
                        <td id="T_f0100_row33_col16" class="data row33 col16" >119.18</td>
                        <td id="T_f0100_row33_col17" class="data row33 col17" >55.97</td>
                        <td id="T_f0100_row33_col18" class="data row33 col18" >-</td>
                        <td id="T_f0100_row33_col19" class="data row33 col19" >-</td>
                        <td id="T_f0100_row33_col20" class="data row33 col20" >22,690.16</td>
                        <td id="T_f0100_row33_col21" class="data row33 col21" >7,751,213.57</td>
                        <td id="T_f0100_row33_col22" class="data row33 col22" >-78,231.41</td>
                        <td id="T_f0100_row33_col23" class="data row33 col23" >99.71</td>
            </tr>
            <tr>
                        <th id="T_f0100_level0_row34" class="row_heading level0 row34" >TIGR</th>
                        <td id="T_f0100_row34_col0" class="data row34 col0" >UP Fintech Holding L</td>
                        <td id="T_f0100_row34_col1" class="data row34 col1" >Finance</td>
                        <td id="T_f0100_row34_col2" class="data row34 col2" >89.25</td>
                        <td id="T_f0100_row34_col3" class="data row34 col3" >918.74</td>
                        <td id="T_f0100_row34_col4" class="data row34 col4" >1.03</td>
                        <td id="T_f0100_row34_col5" class="data row34 col5" >38.57</td>
                        <td id="T_f0100_row34_col6" class="data row34 col6" >-43.16</td>
                        <td id="T_f0100_row34_col7" class="data row34 col7" >58.37</td>
                        <td id="T_f0100_row34_col8" class="data row34 col8" >98.63</td>
                        <td id="T_f0100_row34_col9" class="data row34 col9" >36.38</td>
                        <td id="T_f0100_row34_col10" class="data row34 col10" >-10.31</td>
                        <td id="T_f0100_row34_col11" class="data row34 col11" >15.60</td>
                        <td id="T_f0100_row34_col12" class="data row34 col12" >418.68</td>
                        <td id="T_f0100_row34_col13" class="data row34 col13" >186.09</td>
                        <td id="T_f0100_row34_col14" class="data row34 col14" >-295.56</td>
                        <td id="T_f0100_row34_col15" class="data row34 col15" >747.71</td>
                        <td id="T_f0100_row34_col16" class="data row34 col16" >234.21</td>
                        <td id="T_f0100_row34_col17" class="data row34 col17" >-</td>
                        <td id="T_f0100_row34_col18" class="data row34 col18" >-</td>
                        <td id="T_f0100_row34_col19" class="data row34 col19" >-</td>
                        <td id="T_f0100_row34_col20" class="data row34 col20" >24,059.65</td>
                        <td id="T_f0100_row34_col21" class="data row34 col21" >-14,708.75</td>
                        <td id="T_f0100_row34_col22" class="data row34 col22" >-196.36</td>
                        <td id="T_f0100_row34_col23" class="data row34 col23" >-</td>
            </tr>
            <tr>
                        <th id="T_f0100_level0_row35" class="row_heading level0 row35" >NIU</th>
                        <td id="T_f0100_row35_col0" class="data row35 col0" >Niu Technologies Ame</td>
                        <td id="T_f0100_row35_col1" class="data row35 col1" >Capital Goods</td>
                        <td id="T_f0100_row35_col2" class="data row35 col2" >46.21</td>
                        <td id="T_f0100_row35_col3" class="data row35 col3" >4.24</td>
                        <td id="T_f0100_row35_col4" class="data row35 col4" >-</td>
                        <td id="T_f0100_row35_col5" class="data row35 col5" >9.14</td>
                        <td id="T_f0100_row35_col6" class="data row35 col6" >-7.89</td>
                        <td id="T_f0100_row35_col7" class="data row35 col7" >1,691.94</td>
                        <td id="T_f0100_row35_col8" class="data row35 col8" >50.10</td>
                        <td id="T_f0100_row35_col9" class="data row35 col9" >38.09</td>
                        <td id="T_f0100_row35_col10" class="data row35 col10" >-43.74</td>
                        <td id="T_f0100_row35_col11" class="data row35 col11" >-25.58</td>
                        <td id="T_f0100_row35_col12" class="data row35 col12" >122.36</td>
                        <td id="T_f0100_row35_col13" class="data row35 col13" >112.92</td>
                        <td id="T_f0100_row35_col14" class="data row35 col14" >-22.35</td>
                        <td id="T_f0100_row35_col15" class="data row35 col15" >424.63</td>
                        <td id="T_f0100_row35_col16" class="data row35 col16" >101.93</td>
                        <td id="T_f0100_row35_col17" class="data row35 col17" >-</td>
                        <td id="T_f0100_row35_col18" class="data row35 col18" >-</td>
                        <td id="T_f0100_row35_col19" class="data row35 col19" >-</td>
                        <td id="T_f0100_row35_col20" class="data row35 col20" >16,316.11</td>
                        <td id="T_f0100_row35_col21" class="data row35 col21" >720.72</td>
                        <td id="T_f0100_row35_col22" class="data row35 col22" >-249.35</td>
                        <td id="T_f0100_row35_col23" class="data row35 col23" >-2,163.87</td>
            </tr>
    </tbody></table>



## 港股

### 指标选股

1. 负债率 < 50%
2. 应收比 < 30%
3. 商誉比 < 30%
4. ROE >= 15
5. 利润率 >= 20%
6. 收入增长 >= 15% 或 盈利增长 >= 15% 或 FCF增长率 >= 15% 且 (收入增长 > 0 且 盈利增长 > 0 且 FCF增长 > 0)




<style  type="text/css" >
#T_fe9ce_row0_col0,#T_fe9ce_row0_col1,#T_fe9ce_row0_col2,#T_fe9ce_row0_col3,#T_fe9ce_row0_col4,#T_fe9ce_row0_col5,#T_fe9ce_row0_col6,#T_fe9ce_row0_col7,#T_fe9ce_row0_col8,#T_fe9ce_row0_col9,#T_fe9ce_row0_col10,#T_fe9ce_row0_col11,#T_fe9ce_row0_col12,#T_fe9ce_row0_col13,#T_fe9ce_row0_col14,#T_fe9ce_row0_col15,#T_fe9ce_row0_col16,#T_fe9ce_row0_col17,#T_fe9ce_row0_col18,#T_fe9ce_row0_col19,#T_fe9ce_row0_col20,#T_fe9ce_row0_col21,#T_fe9ce_row0_col22,#T_fe9ce_row1_col0,#T_fe9ce_row1_col1,#T_fe9ce_row1_col2,#T_fe9ce_row1_col3,#T_fe9ce_row1_col4,#T_fe9ce_row1_col5,#T_fe9ce_row1_col6,#T_fe9ce_row1_col7,#T_fe9ce_row1_col8,#T_fe9ce_row1_col9,#T_fe9ce_row1_col10,#T_fe9ce_row1_col11,#T_fe9ce_row1_col12,#T_fe9ce_row1_col13,#T_fe9ce_row1_col14,#T_fe9ce_row1_col15,#T_fe9ce_row1_col16,#T_fe9ce_row1_col17,#T_fe9ce_row1_col18,#T_fe9ce_row1_col19,#T_fe9ce_row1_col20,#T_fe9ce_row1_col21,#T_fe9ce_row1_col22,#T_fe9ce_row2_col0,#T_fe9ce_row2_col1,#T_fe9ce_row2_col2,#T_fe9ce_row2_col3,#T_fe9ce_row2_col4,#T_fe9ce_row2_col5,#T_fe9ce_row2_col6,#T_fe9ce_row2_col7,#T_fe9ce_row2_col8,#T_fe9ce_row2_col9,#T_fe9ce_row2_col10,#T_fe9ce_row2_col11,#T_fe9ce_row2_col12,#T_fe9ce_row2_col13,#T_fe9ce_row2_col14,#T_fe9ce_row2_col15,#T_fe9ce_row2_col16,#T_fe9ce_row2_col17,#T_fe9ce_row2_col18,#T_fe9ce_row2_col19,#T_fe9ce_row2_col20,#T_fe9ce_row2_col21,#T_fe9ce_row2_col22,#T_fe9ce_row3_col0,#T_fe9ce_row3_col1,#T_fe9ce_row3_col2,#T_fe9ce_row3_col3,#T_fe9ce_row3_col4,#T_fe9ce_row3_col5,#T_fe9ce_row3_col6,#T_fe9ce_row3_col7,#T_fe9ce_row3_col8,#T_fe9ce_row3_col9,#T_fe9ce_row3_col10,#T_fe9ce_row3_col11,#T_fe9ce_row3_col12,#T_fe9ce_row3_col13,#T_fe9ce_row3_col14,#T_fe9ce_row3_col15,#T_fe9ce_row3_col16,#T_fe9ce_row3_col17,#T_fe9ce_row3_col18,#T_fe9ce_row3_col19,#T_fe9ce_row3_col20,#T_fe9ce_row3_col21,#T_fe9ce_row3_col22,#T_fe9ce_row4_col0,#T_fe9ce_row4_col1,#T_fe9ce_row4_col2,#T_fe9ce_row4_col3,#T_fe9ce_row4_col4,#T_fe9ce_row4_col5,#T_fe9ce_row4_col6,#T_fe9ce_row4_col7,#T_fe9ce_row4_col8,#T_fe9ce_row4_col9,#T_fe9ce_row4_col10,#T_fe9ce_row4_col11,#T_fe9ce_row4_col12,#T_fe9ce_row4_col13,#T_fe9ce_row4_col14,#T_fe9ce_row4_col15,#T_fe9ce_row4_col16,#T_fe9ce_row4_col17,#T_fe9ce_row4_col18,#T_fe9ce_row4_col19,#T_fe9ce_row4_col20,#T_fe9ce_row4_col21,#T_fe9ce_row4_col22,#T_fe9ce_row5_col0,#T_fe9ce_row5_col1,#T_fe9ce_row5_col2,#T_fe9ce_row5_col3,#T_fe9ce_row5_col4,#T_fe9ce_row5_col5,#T_fe9ce_row5_col6,#T_fe9ce_row5_col7,#T_fe9ce_row5_col8,#T_fe9ce_row5_col9,#T_fe9ce_row5_col10,#T_fe9ce_row5_col11,#T_fe9ce_row5_col12,#T_fe9ce_row5_col13,#T_fe9ce_row5_col14,#T_fe9ce_row5_col15,#T_fe9ce_row5_col16,#T_fe9ce_row5_col17,#T_fe9ce_row5_col18,#T_fe9ce_row5_col19,#T_fe9ce_row5_col20,#T_fe9ce_row5_col21,#T_fe9ce_row5_col22,#T_fe9ce_row6_col0,#T_fe9ce_row6_col1,#T_fe9ce_row6_col2,#T_fe9ce_row6_col3,#T_fe9ce_row6_col4,#T_fe9ce_row6_col5,#T_fe9ce_row6_col6,#T_fe9ce_row6_col7,#T_fe9ce_row6_col8,#T_fe9ce_row6_col9,#T_fe9ce_row6_col10,#T_fe9ce_row6_col11,#T_fe9ce_row6_col13,#T_fe9ce_row6_col14,#T_fe9ce_row6_col15,#T_fe9ce_row6_col16,#T_fe9ce_row6_col17,#T_fe9ce_row6_col18,#T_fe9ce_row6_col19,#T_fe9ce_row6_col21,#T_fe9ce_row6_col22,#T_fe9ce_row7_col0,#T_fe9ce_row7_col1,#T_fe9ce_row7_col2,#T_fe9ce_row7_col3,#T_fe9ce_row7_col4,#T_fe9ce_row7_col5,#T_fe9ce_row7_col6,#T_fe9ce_row7_col7,#T_fe9ce_row7_col8,#T_fe9ce_row7_col9,#T_fe9ce_row7_col10,#T_fe9ce_row7_col11,#T_fe9ce_row7_col12,#T_fe9ce_row7_col13,#T_fe9ce_row7_col14,#T_fe9ce_row7_col15,#T_fe9ce_row7_col16,#T_fe9ce_row7_col17,#T_fe9ce_row7_col18,#T_fe9ce_row7_col19,#T_fe9ce_row7_col20,#T_fe9ce_row7_col21,#T_fe9ce_row7_col22,#T_fe9ce_row8_col0,#T_fe9ce_row8_col1,#T_fe9ce_row8_col2,#T_fe9ce_row8_col3,#T_fe9ce_row8_col4,#T_fe9ce_row8_col5,#T_fe9ce_row8_col6,#T_fe9ce_row8_col7,#T_fe9ce_row8_col8,#T_fe9ce_row8_col9,#T_fe9ce_row8_col10,#T_fe9ce_row8_col11,#T_fe9ce_row8_col12,#T_fe9ce_row8_col13,#T_fe9ce_row8_col14,#T_fe9ce_row8_col15,#T_fe9ce_row8_col16,#T_fe9ce_row8_col17,#T_fe9ce_row8_col18,#T_fe9ce_row8_col19,#T_fe9ce_row8_col20,#T_fe9ce_row8_col21,#T_fe9ce_row8_col22,#T_fe9ce_row9_col0,#T_fe9ce_row9_col1,#T_fe9ce_row9_col2,#T_fe9ce_row9_col3,#T_fe9ce_row9_col4,#T_fe9ce_row9_col5,#T_fe9ce_row9_col6,#T_fe9ce_row9_col7,#T_fe9ce_row9_col8,#T_fe9ce_row9_col9,#T_fe9ce_row9_col10,#T_fe9ce_row9_col11,#T_fe9ce_row9_col12,#T_fe9ce_row9_col13,#T_fe9ce_row9_col14,#T_fe9ce_row9_col15,#T_fe9ce_row9_col16,#T_fe9ce_row9_col17,#T_fe9ce_row9_col18,#T_fe9ce_row9_col19,#T_fe9ce_row9_col20,#T_fe9ce_row9_col21,#T_fe9ce_row9_col22,#T_fe9ce_row10_col0,#T_fe9ce_row10_col1,#T_fe9ce_row10_col2,#T_fe9ce_row10_col3,#T_fe9ce_row10_col4,#T_fe9ce_row10_col5,#T_fe9ce_row10_col6,#T_fe9ce_row10_col7,#T_fe9ce_row10_col8,#T_fe9ce_row10_col9,#T_fe9ce_row10_col10,#T_fe9ce_row10_col11,#T_fe9ce_row10_col12,#T_fe9ce_row10_col13,#T_fe9ce_row10_col14,#T_fe9ce_row10_col15,#T_fe9ce_row10_col16,#T_fe9ce_row10_col17,#T_fe9ce_row10_col18,#T_fe9ce_row10_col19,#T_fe9ce_row10_col20,#T_fe9ce_row10_col21,#T_fe9ce_row10_col22,#T_fe9ce_row11_col0,#T_fe9ce_row11_col1,#T_fe9ce_row11_col2,#T_fe9ce_row11_col3,#T_fe9ce_row11_col4,#T_fe9ce_row11_col5,#T_fe9ce_row11_col6,#T_fe9ce_row11_col7,#T_fe9ce_row11_col8,#T_fe9ce_row11_col9,#T_fe9ce_row11_col10,#T_fe9ce_row11_col11,#T_fe9ce_row11_col12,#T_fe9ce_row11_col13,#T_fe9ce_row11_col14,#T_fe9ce_row11_col15,#T_fe9ce_row11_col16,#T_fe9ce_row11_col17,#T_fe9ce_row11_col18,#T_fe9ce_row11_col19,#T_fe9ce_row11_col20,#T_fe9ce_row11_col21,#T_fe9ce_row11_col22,#T_fe9ce_row12_col0,#T_fe9ce_row12_col1,#T_fe9ce_row12_col2,#T_fe9ce_row12_col3,#T_fe9ce_row12_col4,#T_fe9ce_row12_col5,#T_fe9ce_row12_col6,#T_fe9ce_row12_col7,#T_fe9ce_row12_col8,#T_fe9ce_row12_col9,#T_fe9ce_row12_col10,#T_fe9ce_row12_col11,#T_fe9ce_row12_col12,#T_fe9ce_row12_col13,#T_fe9ce_row12_col14,#T_fe9ce_row12_col15,#T_fe9ce_row12_col16,#T_fe9ce_row12_col17,#T_fe9ce_row12_col18,#T_fe9ce_row12_col19,#T_fe9ce_row12_col20,#T_fe9ce_row12_col21,#T_fe9ce_row12_col22,#T_fe9ce_row13_col0,#T_fe9ce_row13_col1,#T_fe9ce_row13_col2,#T_fe9ce_row13_col3,#T_fe9ce_row13_col4,#T_fe9ce_row13_col5,#T_fe9ce_row13_col6,#T_fe9ce_row13_col7,#T_fe9ce_row13_col8,#T_fe9ce_row13_col9,#T_fe9ce_row13_col10,#T_fe9ce_row13_col11,#T_fe9ce_row13_col13,#T_fe9ce_row13_col14,#T_fe9ce_row13_col15,#T_fe9ce_row13_col16,#T_fe9ce_row13_col17,#T_fe9ce_row13_col18,#T_fe9ce_row13_col19,#T_fe9ce_row13_col21,#T_fe9ce_row13_col22,#T_fe9ce_row14_col0,#T_fe9ce_row14_col1,#T_fe9ce_row14_col2,#T_fe9ce_row14_col3,#T_fe9ce_row14_col4,#T_fe9ce_row14_col5,#T_fe9ce_row14_col6,#T_fe9ce_row14_col7,#T_fe9ce_row14_col8,#T_fe9ce_row14_col9,#T_fe9ce_row14_col10,#T_fe9ce_row14_col11,#T_fe9ce_row14_col12,#T_fe9ce_row14_col13,#T_fe9ce_row14_col14,#T_fe9ce_row14_col15,#T_fe9ce_row14_col16,#T_fe9ce_row14_col17,#T_fe9ce_row14_col18,#T_fe9ce_row14_col19,#T_fe9ce_row14_col20,#T_fe9ce_row14_col21,#T_fe9ce_row14_col22,#T_fe9ce_row15_col0,#T_fe9ce_row15_col1,#T_fe9ce_row15_col2,#T_fe9ce_row15_col3,#T_fe9ce_row15_col4,#T_fe9ce_row15_col5,#T_fe9ce_row15_col6,#T_fe9ce_row15_col7,#T_fe9ce_row15_col8,#T_fe9ce_row15_col9,#T_fe9ce_row15_col10,#T_fe9ce_row15_col11,#T_fe9ce_row15_col12,#T_fe9ce_row15_col13,#T_fe9ce_row15_col14,#T_fe9ce_row15_col15,#T_fe9ce_row15_col16,#T_fe9ce_row15_col17,#T_fe9ce_row15_col18,#T_fe9ce_row15_col19,#T_fe9ce_row15_col20,#T_fe9ce_row15_col21,#T_fe9ce_row16_col0,#T_fe9ce_row16_col1,#T_fe9ce_row16_col2,#T_fe9ce_row16_col3,#T_fe9ce_row16_col4,#T_fe9ce_row16_col5,#T_fe9ce_row16_col6,#T_fe9ce_row16_col7,#T_fe9ce_row16_col8,#T_fe9ce_row16_col9,#T_fe9ce_row16_col10,#T_fe9ce_row16_col11,#T_fe9ce_row16_col12,#T_fe9ce_row16_col13,#T_fe9ce_row16_col14,#T_fe9ce_row16_col15,#T_fe9ce_row16_col16,#T_fe9ce_row16_col17,#T_fe9ce_row16_col18,#T_fe9ce_row16_col19,#T_fe9ce_row16_col20,#T_fe9ce_row16_col21,#T_fe9ce_row17_col0,#T_fe9ce_row17_col1,#T_fe9ce_row17_col2,#T_fe9ce_row17_col3,#T_fe9ce_row17_col4,#T_fe9ce_row17_col5,#T_fe9ce_row17_col6,#T_fe9ce_row17_col7,#T_fe9ce_row17_col8,#T_fe9ce_row17_col9,#T_fe9ce_row17_col10,#T_fe9ce_row17_col11,#T_fe9ce_row17_col12,#T_fe9ce_row17_col13,#T_fe9ce_row17_col14,#T_fe9ce_row17_col15,#T_fe9ce_row17_col16,#T_fe9ce_row17_col17,#T_fe9ce_row17_col18,#T_fe9ce_row17_col19,#T_fe9ce_row17_col20,#T_fe9ce_row17_col21,#T_fe9ce_row17_col22,#T_fe9ce_row18_col0,#T_fe9ce_row18_col1,#T_fe9ce_row18_col2,#T_fe9ce_row18_col3,#T_fe9ce_row18_col4,#T_fe9ce_row18_col5,#T_fe9ce_row18_col6,#T_fe9ce_row18_col7,#T_fe9ce_row18_col8,#T_fe9ce_row18_col9,#T_fe9ce_row18_col10,#T_fe9ce_row18_col11,#T_fe9ce_row18_col12,#T_fe9ce_row18_col13,#T_fe9ce_row18_col14,#T_fe9ce_row18_col15,#T_fe9ce_row18_col16,#T_fe9ce_row18_col17,#T_fe9ce_row18_col18,#T_fe9ce_row18_col19,#T_fe9ce_row18_col20,#T_fe9ce_row18_col21,#T_fe9ce_row19_col0,#T_fe9ce_row19_col1,#T_fe9ce_row19_col2,#T_fe9ce_row19_col3,#T_fe9ce_row19_col4,#T_fe9ce_row19_col5,#T_fe9ce_row19_col6,#T_fe9ce_row19_col7,#T_fe9ce_row19_col8,#T_fe9ce_row19_col9,#T_fe9ce_row19_col10,#T_fe9ce_row19_col11,#T_fe9ce_row19_col12,#T_fe9ce_row19_col13,#T_fe9ce_row19_col14,#T_fe9ce_row19_col15,#T_fe9ce_row19_col16,#T_fe9ce_row19_col17,#T_fe9ce_row19_col18,#T_fe9ce_row19_col19,#T_fe9ce_row19_col20,#T_fe9ce_row19_col21,#T_fe9ce_row19_col22,#T_fe9ce_row20_col0,#T_fe9ce_row20_col1,#T_fe9ce_row20_col2,#T_fe9ce_row20_col3,#T_fe9ce_row20_col4,#T_fe9ce_row20_col5,#T_fe9ce_row20_col6,#T_fe9ce_row20_col7,#T_fe9ce_row20_col8,#T_fe9ce_row20_col9,#T_fe9ce_row20_col10,#T_fe9ce_row20_col11,#T_fe9ce_row20_col12,#T_fe9ce_row20_col13,#T_fe9ce_row20_col14,#T_fe9ce_row20_col15,#T_fe9ce_row20_col16,#T_fe9ce_row20_col17,#T_fe9ce_row20_col18,#T_fe9ce_row20_col19,#T_fe9ce_row20_col20,#T_fe9ce_row20_col21,#T_fe9ce_row21_col0,#T_fe9ce_row21_col1,#T_fe9ce_row21_col2,#T_fe9ce_row21_col3,#T_fe9ce_row21_col4,#T_fe9ce_row21_col5,#T_fe9ce_row21_col6,#T_fe9ce_row21_col7,#T_fe9ce_row21_col8,#T_fe9ce_row21_col9,#T_fe9ce_row21_col10,#T_fe9ce_row21_col11,#T_fe9ce_row21_col12,#T_fe9ce_row21_col13,#T_fe9ce_row21_col14,#T_fe9ce_row21_col15,#T_fe9ce_row21_col16,#T_fe9ce_row21_col17,#T_fe9ce_row21_col18,#T_fe9ce_row21_col19,#T_fe9ce_row21_col20,#T_fe9ce_row21_col21,#T_fe9ce_row22_col0,#T_fe9ce_row22_col1,#T_fe9ce_row22_col2,#T_fe9ce_row22_col3,#T_fe9ce_row22_col4,#T_fe9ce_row22_col5,#T_fe9ce_row22_col6,#T_fe9ce_row22_col7,#T_fe9ce_row22_col8,#T_fe9ce_row22_col9,#T_fe9ce_row22_col10,#T_fe9ce_row22_col11,#T_fe9ce_row22_col12,#T_fe9ce_row22_col13,#T_fe9ce_row22_col14,#T_fe9ce_row22_col15,#T_fe9ce_row22_col16,#T_fe9ce_row22_col17,#T_fe9ce_row22_col18,#T_fe9ce_row22_col19,#T_fe9ce_row22_col20,#T_fe9ce_row22_col21,#T_fe9ce_row23_col0,#T_fe9ce_row23_col1,#T_fe9ce_row23_col2,#T_fe9ce_row23_col3,#T_fe9ce_row23_col4,#T_fe9ce_row23_col5,#T_fe9ce_row23_col6,#T_fe9ce_row23_col7,#T_fe9ce_row23_col8,#T_fe9ce_row23_col9,#T_fe9ce_row23_col10,#T_fe9ce_row23_col11,#T_fe9ce_row23_col12,#T_fe9ce_row23_col13,#T_fe9ce_row23_col14,#T_fe9ce_row23_col15,#T_fe9ce_row23_col16,#T_fe9ce_row23_col17,#T_fe9ce_row23_col18,#T_fe9ce_row23_col19,#T_fe9ce_row23_col20,#T_fe9ce_row23_col21,#T_fe9ce_row24_col0,#T_fe9ce_row24_col1,#T_fe9ce_row24_col2,#T_fe9ce_row24_col3,#T_fe9ce_row24_col4,#T_fe9ce_row24_col5,#T_fe9ce_row24_col6,#T_fe9ce_row24_col7,#T_fe9ce_row24_col8,#T_fe9ce_row24_col9,#T_fe9ce_row24_col10,#T_fe9ce_row24_col11,#T_fe9ce_row24_col12,#T_fe9ce_row24_col13,#T_fe9ce_row24_col14,#T_fe9ce_row24_col15,#T_fe9ce_row24_col16,#T_fe9ce_row24_col17,#T_fe9ce_row24_col18,#T_fe9ce_row24_col19,#T_fe9ce_row24_col20,#T_fe9ce_row24_col21,#T_fe9ce_row24_col22,#T_fe9ce_row25_col0,#T_fe9ce_row25_col1,#T_fe9ce_row25_col2,#T_fe9ce_row25_col3,#T_fe9ce_row25_col4,#T_fe9ce_row25_col5,#T_fe9ce_row25_col6,#T_fe9ce_row25_col7,#T_fe9ce_row25_col8,#T_fe9ce_row25_col9,#T_fe9ce_row25_col10,#T_fe9ce_row25_col11,#T_fe9ce_row25_col12,#T_fe9ce_row25_col13,#T_fe9ce_row25_col14,#T_fe9ce_row25_col15,#T_fe9ce_row25_col16,#T_fe9ce_row25_col17,#T_fe9ce_row25_col18,#T_fe9ce_row25_col19,#T_fe9ce_row25_col20,#T_fe9ce_row25_col21,#T_fe9ce_row26_col0,#T_fe9ce_row26_col1,#T_fe9ce_row26_col2,#T_fe9ce_row26_col3,#T_fe9ce_row26_col4,#T_fe9ce_row26_col5,#T_fe9ce_row26_col6,#T_fe9ce_row26_col7,#T_fe9ce_row26_col8,#T_fe9ce_row26_col9,#T_fe9ce_row26_col10,#T_fe9ce_row26_col11,#T_fe9ce_row26_col12,#T_fe9ce_row26_col13,#T_fe9ce_row26_col14,#T_fe9ce_row26_col15,#T_fe9ce_row26_col16,#T_fe9ce_row26_col17,#T_fe9ce_row26_col18,#T_fe9ce_row26_col19,#T_fe9ce_row26_col20,#T_fe9ce_row26_col21,#T_fe9ce_row26_col22{
            color:  black;
        }#T_fe9ce_row6_col12,#T_fe9ce_row6_col20,#T_fe9ce_row13_col12,#T_fe9ce_row13_col20,#T_fe9ce_row15_col22,#T_fe9ce_row16_col22,#T_fe9ce_row18_col22,#T_fe9ce_row20_col22,#T_fe9ce_row21_col22,#T_fe9ce_row22_col22,#T_fe9ce_row23_col22,#T_fe9ce_row25_col22{
            color:  red;
        }</style><table id="T_fe9ce_" ><thead>    <tr>        <th class="blank level0" ></th>        <th class="col_heading level0 col0" >名称</th>        <th class="col_heading level0 col1" >负债率</th>        <th class="col_heading level0 col2" >应收比</th>        <th class="col_heading level0 col3" >商誉比</th>        <th class="col_heading level0 col4" >ROE</th>        <th class="col_heading level0 col5" >利润率</th>        <th class="col_heading level0 col6" >收入</th>        <th class="col_heading level0 col7" >收入增长</th>        <th class="col_heading level0 col8" >收入波动</th>        <th class="col_heading level0 col9" >盈利</th>        <th class="col_heading level0 col10" >盈利增长</th>        <th class="col_heading level0 col11" >盈利波动</th>        <th class="col_heading level0 col12" >FCF</th>        <th class="col_heading level0 col13" >FCF增长</th>        <th class="col_heading level0 col14" >FCF波动</th>        <th class="col_heading level0 col15" >PE</th>        <th class="col_heading level0 col16" >PE0</th>        <th class="col_heading level0 col17" >PEG</th>        <th class="col_heading level0 col18" >股息率</th>        <th class="col_heading level0 col19" >市值</th>        <th class="col_heading level0 col20" >DCF</th>        <th class="col_heading level0 col21" >盈利折现</th>        <th class="col_heading level0 col22" >折价率</th>    </tr>    <tr>        <th class="index_name level0" >Symbol</th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>    </tr></thead><tbody>
                <tr>
                        <th id="T_fe9ce_level0_row0" class="row_heading level0 row0" >1681.HK</th>
                        <td id="T_fe9ce_row0_col0" class="data row0 col0" >康臣药业</td>
                        <td id="T_fe9ce_row0_col1" class="data row0 col1" >36.30</td>
                        <td id="T_fe9ce_row0_col2" class="data row0 col2" >26.15</td>
                        <td id="T_fe9ce_row0_col3" class="data row0 col3" >14.86</td>
                        <td id="T_fe9ce_row0_col4" class="data row0 col4" >17.68</td>
                        <td id="T_fe9ce_row0_col5" class="data row0 col5" >20.54</td>
                        <td id="T_fe9ce_row0_col6" class="data row0 col6" >1,746.32</td>
                        <td id="T_fe9ce_row0_col7" class="data row0 col7" >2.07</td>
                        <td id="T_fe9ce_row0_col8" class="data row0 col8" >8.69</td>
                        <td id="T_fe9ce_row0_col9" class="data row0 col9" >360.05</td>
                        <td id="T_fe9ce_row0_col10" class="data row0 col10" >153.16</td>
                        <td id="T_fe9ce_row0_col11" class="data row0 col11" >325.81</td>
                        <td id="T_fe9ce_row0_col12" class="data row0 col12" >444.99</td>
                        <td id="T_fe9ce_row0_col13" class="data row0 col13" >140.93</td>
                        <td id="T_fe9ce_row0_col14" class="data row0 col14" >186.70</td>
                        <td id="T_fe9ce_row0_col15" class="data row0 col15" >52.07</td>
                        <td id="T_fe9ce_row0_col16" class="data row0 col16" >10.27</td>
                        <td id="T_fe9ce_row0_col17" class="data row0 col17" >0.07</td>
                        <td id="T_fe9ce_row0_col18" class="data row0 col18" >3.81</td>
                        <td id="T_fe9ce_row0_col19" class="data row0 col19" >3,698.31</td>
                        <td id="T_fe9ce_row0_col20" class="data row0 col20" >70,548.78</td>
                        <td id="T_fe9ce_row0_col21" class="data row0 col21" >66,025.81</td>
                        <td id="T_fe9ce_row0_col22" class="data row0 col22" >94.76</td>
            </tr>
            <tr>
                        <th id="T_fe9ce_level0_row1" class="row_heading level0 row1" >2660.HK</th>
                        <td id="T_fe9ce_row1_col0" class="data row1 col0" >禅游科技</td>
                        <td id="T_fe9ce_row1_col1" class="data row1 col1" >6.95</td>
                        <td id="T_fe9ce_row1_col2" class="data row1 col2" >9.60</td>
                        <td id="T_fe9ce_row1_col3" class="data row1 col3" >-</td>
                        <td id="T_fe9ce_row1_col4" class="data row1 col4" >31.91</td>
                        <td id="T_fe9ce_row1_col5" class="data row1 col5" >22.01</td>
                        <td id="T_fe9ce_row1_col6" class="data row1 col6" >604.82</td>
                        <td id="T_fe9ce_row1_col7" class="data row1 col7" >17.39</td>
                        <td id="T_fe9ce_row1_col8" class="data row1 col8" >4.60</td>
                        <td id="T_fe9ce_row1_col9" class="data row1 col9" >139.17</td>
                        <td id="T_fe9ce_row1_col10" class="data row1 col10" >49.69</td>
                        <td id="T_fe9ce_row1_col11" class="data row1 col11" >13.24</td>
                        <td id="T_fe9ce_row1_col12" class="data row1 col12" >135.05</td>
                        <td id="T_fe9ce_row1_col13" class="data row1 col13" >54.05</td>
                        <td id="T_fe9ce_row1_col14" class="data row1 col14" >78.58</td>
                        <td id="T_fe9ce_row1_col15" class="data row1 col15" >-</td>
                        <td id="T_fe9ce_row1_col16" class="data row1 col16" >7.72</td>
                        <td id="T_fe9ce_row1_col17" class="data row1 col17" >0.16</td>
                        <td id="T_fe9ce_row1_col18" class="data row1 col18" >-</td>
                        <td id="T_fe9ce_row1_col19" class="data row1 col19" >1,074.29</td>
                        <td id="T_fe9ce_row1_col20" class="data row1 col20" >5,827.47</td>
                        <td id="T_fe9ce_row1_col21" class="data row1 col21" >5,529.00</td>
                        <td id="T_fe9ce_row1_col22" class="data row1 col22" >81.57</td>
            </tr>
            <tr>
                        <th id="T_fe9ce_level0_row2" class="row_heading level0 row2" >1558.HK</th>
                        <td id="T_fe9ce_row2_col0" class="data row2 col0" >东阳光药</td>
                        <td id="T_fe9ce_row2_col1" class="data row2 col1" >46.62</td>
                        <td id="T_fe9ce_row2_col2" class="data row2 col2" >25.54</td>
                        <td id="T_fe9ce_row2_col3" class="data row2 col3" >1.55</td>
                        <td id="T_fe9ce_row2_col4" class="data row2 col4" >27.79</td>
                        <td id="T_fe9ce_row2_col5" class="data row2 col5" >36.13</td>
                        <td id="T_fe9ce_row2_col6" class="data row2 col6" >3,171.05</td>
                        <td id="T_fe9ce_row2_col7" class="data row2 col7" >47.47</td>
                        <td id="T_fe9ce_row2_col8" class="data row2 col8" >105.40</td>
                        <td id="T_fe9ce_row2_col9" class="data row2 col9" >1,086.95</td>
                        <td id="T_fe9ce_row2_col10" class="data row2 col10" >30.99</td>
                        <td id="T_fe9ce_row2_col11" class="data row2 col11" >80.91</td>
                        <td id="T_fe9ce_row2_col12" class="data row2 col12" >490.63</td>
                        <td id="T_fe9ce_row2_col13" class="data row2 col13" >343.43</td>
                        <td id="T_fe9ce_row2_col14" class="data row2 col14" >722.32</td>
                        <td id="T_fe9ce_row2_col15" class="data row2 col15" >-</td>
                        <td id="T_fe9ce_row2_col16" class="data row2 col16" >4.90</td>
                        <td id="T_fe9ce_row2_col17" class="data row2 col17" >0.16</td>
                        <td id="T_fe9ce_row2_col18" class="data row2 col18" >-</td>
                        <td id="T_fe9ce_row2_col19" class="data row2 col19" >5,328.00</td>
                        <td id="T_fe9ce_row2_col20" class="data row2 col20" >472,292.63</td>
                        <td id="T_fe9ce_row2_col21" class="data row2 col21" >29,487.91</td>
                        <td id="T_fe9ce_row2_col22" class="data row2 col22" >98.87</td>
            </tr>
            <tr>
                        <th id="T_fe9ce_level0_row3" class="row_heading level0 row3" >6820.HK</th>
                        <td id="T_fe9ce_row3_col0" class="data row3 col0" >友谊时光</td>
                        <td id="T_fe9ce_row3_col1" class="data row3 col1" >12.60</td>
                        <td id="T_fe9ce_row3_col2" class="data row3 col2" >7.08</td>
                        <td id="T_fe9ce_row3_col3" class="data row3 col3" >-</td>
                        <td id="T_fe9ce_row3_col4" class="data row3 col4" >38.95</td>
                        <td id="T_fe9ce_row3_col5" class="data row3 col5" >21.88</td>
                        <td id="T_fe9ce_row3_col6" class="data row3 col6" >1,508.96</td>
                        <td id="T_fe9ce_row3_col7" class="data row3 col7" >51.22</td>
                        <td id="T_fe9ce_row3_col8" class="data row3 col8" >50.61</td>
                        <td id="T_fe9ce_row3_col9" class="data row3 col9" >343.42</td>
                        <td id="T_fe9ce_row3_col10" class="data row3 col10" >76.65</td>
                        <td id="T_fe9ce_row3_col11" class="data row3 col11" >94.14</td>
                        <td id="T_fe9ce_row3_col12" class="data row3 col12" >283.25</td>
                        <td id="T_fe9ce_row3_col13" class="data row3 col13" >78.93</td>
                        <td id="T_fe9ce_row3_col14" class="data row3 col14" >83.51</td>
                        <td id="T_fe9ce_row3_col15" class="data row3 col15" >-</td>
                        <td id="T_fe9ce_row3_col16" class="data row3 col16" >12.68</td>
                        <td id="T_fe9ce_row3_col17" class="data row3 col17" >0.17</td>
                        <td id="T_fe9ce_row3_col18" class="data row3 col18" >-</td>
                        <td id="T_fe9ce_row3_col19" class="data row3 col19" >4,353.54</td>
                        <td id="T_fe9ce_row3_col20" class="data row3 col20" >18,838.36</td>
                        <td id="T_fe9ce_row3_col21" class="data row3 col21" >22,007.54</td>
                        <td id="T_fe9ce_row3_col22" class="data row3 col22" >76.89</td>
            </tr>
            <tr>
                        <th id="T_fe9ce_level0_row4" class="row_heading level0 row4" >3686.HK</th>
                        <td id="T_fe9ce_row4_col0" class="data row4 col0" >祈福生活服务</td>
                        <td id="T_fe9ce_row4_col1" class="data row4 col1" >27.40</td>
                        <td id="T_fe9ce_row4_col2" class="data row4 col2" >25.42</td>
                        <td id="T_fe9ce_row4_col3" class="data row4 col3" >-</td>
                        <td id="T_fe9ce_row4_col4" class="data row4 col4" >23.54</td>
                        <td id="T_fe9ce_row4_col5" class="data row4 col5" >22.86</td>
                        <td id="T_fe9ce_row4_col6" class="data row4 col6" >381.13</td>
                        <td id="T_fe9ce_row4_col7" class="data row4 col7" >5.24</td>
                        <td id="T_fe9ce_row4_col8" class="data row4 col8" >11.32</td>
                        <td id="T_fe9ce_row4_col9" class="data row4 col9" >88.39</td>
                        <td id="T_fe9ce_row4_col10" class="data row4 col10" >31.74</td>
                        <td id="T_fe9ce_row4_col11" class="data row4 col11" >2.67</td>
                        <td id="T_fe9ce_row4_col12" class="data row4 col12" >84.32</td>
                        <td id="T_fe9ce_row4_col13" class="data row4 col13" >13.53</td>
                        <td id="T_fe9ce_row4_col14" class="data row4 col14" >17.44</td>
                        <td id="T_fe9ce_row4_col15" class="data row4 col15" >-</td>
                        <td id="T_fe9ce_row4_col16" class="data row4 col16" >5.59</td>
                        <td id="T_fe9ce_row4_col17" class="data row4 col17" >0.18</td>
                        <td id="T_fe9ce_row4_col18" class="data row4 col18" >-</td>
                        <td id="T_fe9ce_row4_col19" class="data row4 col19" >494.11</td>
                        <td id="T_fe9ce_row4_col20" class="data row4 col20" >1,526.36</td>
                        <td id="T_fe9ce_row4_col21" class="data row4 col21" >2,437.24</td>
                        <td id="T_fe9ce_row4_col22" class="data row4 col22" >67.63</td>
            </tr>
            <tr>
                        <th id="T_fe9ce_level0_row5" class="row_heading level0 row5" >0914.HK</th>
                        <td id="T_fe9ce_row5_col0" class="data row5 col0" >海螺水泥</td>
                        <td id="T_fe9ce_row5_col1" class="data row5 col1" >16.30</td>
                        <td id="T_fe9ce_row5_col2" class="data row5 col2" >7.17</td>
                        <td id="T_fe9ce_row5_col3" class="data row5 col3" >0.36</td>
                        <td id="T_fe9ce_row5_col4" class="data row5 col4" >22.59</td>
                        <td id="T_fe9ce_row5_col5" class="data row5 col5" >21.40</td>
                        <td id="T_fe9ce_row5_col6" class="data row5 col6" >134,246.61</td>
                        <td id="T_fe9ce_row5_col7" class="data row5 col7" >35.01</td>
                        <td id="T_fe9ce_row5_col8" class="data row5 col8" >31.14</td>
                        <td id="T_fe9ce_row5_col9" class="data row5 col9" >28,597.85</td>
                        <td id="T_fe9ce_row5_col10" class="data row5 col10" >35.10</td>
                        <td id="T_fe9ce_row5_col11" class="data row5 col11" >46.03</td>
                        <td id="T_fe9ce_row5_col12" class="data row5 col12" >25,427.11</td>
                        <td id="T_fe9ce_row5_col13" class="data row5 col13" >36.04</td>
                        <td id="T_fe9ce_row5_col14" class="data row5 col14" >80.90</td>
                        <td id="T_fe9ce_row5_col15" class="data row5 col15" >6.11</td>
                        <td id="T_fe9ce_row5_col16" class="data row5 col16" >7.83</td>
                        <td id="T_fe9ce_row5_col17" class="data row5 col17" >0.22</td>
                        <td id="T_fe9ce_row5_col18" class="data row5 col18" >3.04</td>
                        <td id="T_fe9ce_row5_col19" class="data row5 col19" >223,935.47</td>
                        <td id="T_fe9ce_row5_col20" class="data row5 col20" >768,241.81</td>
                        <td id="T_fe9ce_row5_col21" class="data row5 col21" >847,141.73</td>
                        <td id="T_fe9ce_row5_col22" class="data row5 col22" >70.85</td>
            </tr>
            <tr>
                        <th id="T_fe9ce_level0_row6" class="row_heading level0 row6" >0586.HK</th>
                        <td id="T_fe9ce_row6_col0" class="data row6 col0" >海螺创业</td>
                        <td id="T_fe9ce_row6_col1" class="data row6 col1" >26.41</td>
                        <td id="T_fe9ce_row6_col2" class="data row6 col2" >29.06</td>
                        <td id="T_fe9ce_row6_col3" class="data row6 col3" >-</td>
                        <td id="T_fe9ce_row6_col4" class="data row6 col4" >20.34</td>
                        <td id="T_fe9ce_row6_col5" class="data row6 col5" >155.65</td>
                        <td id="T_fe9ce_row6_col6" class="data row6 col6" >4,169.85</td>
                        <td id="T_fe9ce_row6_col7" class="data row6 col7" >48.71</td>
                        <td id="T_fe9ce_row6_col8" class="data row6 col8" >25.27</td>
                        <td id="T_fe9ce_row6_col9" class="data row6 col9" >5,990.93</td>
                        <td id="T_fe9ce_row6_col10" class="data row6 col10" >33.76</td>
                        <td id="T_fe9ce_row6_col11" class="data row6 col11" >35.78</td>
                        <td id="T_fe9ce_row6_col12" class="data row6 col12" >-1,754.75</td>
                        <td id="T_fe9ce_row6_col13" class="data row6 col13" >111.47</td>
                        <td id="T_fe9ce_row6_col14" class="data row6 col14" >116.73</td>
                        <td id="T_fe9ce_row6_col15" class="data row6 col15" >-</td>
                        <td id="T_fe9ce_row6_col16" class="data row6 col16" >8.32</td>
                        <td id="T_fe9ce_row6_col17" class="data row6 col17" >0.25</td>
                        <td id="T_fe9ce_row6_col18" class="data row6 col18" >1.81</td>
                        <td id="T_fe9ce_row6_col19" class="data row6 col19" >49,872.73</td>
                        <td id="T_fe9ce_row6_col20" class="data row6 col20" >-189,877.63</td>
                        <td id="T_fe9ce_row6_col21" class="data row6 col21" >172,505.38</td>
                        <td id="T_fe9ce_row6_col22" class="data row6 col22" >-</td>
            </tr>
            <tr>
                        <th id="T_fe9ce_level0_row7" class="row_heading level0 row7" >1277.HK</th>
                        <td id="T_fe9ce_row7_col0" class="data row7 col0" >力量能源</td>
                        <td id="T_fe9ce_row7_col1" class="data row7 col1" >24.86</td>
                        <td id="T_fe9ce_row7_col2" class="data row7 col2" >5.82</td>
                        <td id="T_fe9ce_row7_col3" class="data row7 col3" >-</td>
                        <td id="T_fe9ce_row7_col4" class="data row7 col4" >38.28</td>
                        <td id="T_fe9ce_row7_col5" class="data row7 col5" >30.47</td>
                        <td id="T_fe9ce_row7_col6" class="data row7 col6" >2,472.62</td>
                        <td id="T_fe9ce_row7_col7" class="data row7 col7" >19.96</td>
                        <td id="T_fe9ce_row7_col8" class="data row7 col8" >17.17</td>
                        <td id="T_fe9ce_row7_col9" class="data row7 col9" >748.78</td>
                        <td id="T_fe9ce_row7_col10" class="data row7 col10" >16.82</td>
                        <td id="T_fe9ce_row7_col11" class="data row7 col11" >28.37</td>
                        <td id="T_fe9ce_row7_col12" class="data row7 col12" >884.27</td>
                        <td id="T_fe9ce_row7_col13" class="data row7 col13" >22.58</td>
                        <td id="T_fe9ce_row7_col14" class="data row7 col14" >38.49</td>
                        <td id="T_fe9ce_row7_col15" class="data row7 col15" >4.71</td>
                        <td id="T_fe9ce_row7_col16" class="data row7 col16" >4.83</td>
                        <td id="T_fe9ce_row7_col17" class="data row7 col17" >0.29</td>
                        <td id="T_fe9ce_row7_col18" class="data row7 col18" >-</td>
                        <td id="T_fe9ce_row7_col19" class="data row7 col19" >3,616.03</td>
                        <td id="T_fe9ce_row7_col20" class="data row7 col20" >19,870.79</td>
                        <td id="T_fe9ce_row7_col21" class="data row7 col21" >14,690.50</td>
                        <td id="T_fe9ce_row7_col22" class="data row7 col22" >81.80</td>
            </tr>
            <tr>
                        <th id="T_fe9ce_level0_row8" class="row_heading level0 row8" >1598.HK</th>
                        <td id="T_fe9ce_row8_col0" class="data row8 col0" >21世纪教育</td>
                        <td id="T_fe9ce_row8_col1" class="data row8 col1" >41.39</td>
                        <td id="T_fe9ce_row8_col2" class="data row8 col2" >4.26</td>
                        <td id="T_fe9ce_row8_col3" class="data row8 col3" >10.27</td>
                        <td id="T_fe9ce_row8_col4" class="data row8 col4" >16.13</td>
                        <td id="T_fe9ce_row8_col5" class="data row8 col5" >31.64</td>
                        <td id="T_fe9ce_row8_col6" class="data row8 col6" >214.94</td>
                        <td id="T_fe9ce_row8_col7" class="data row8 col7" >14.44</td>
                        <td id="T_fe9ce_row8_col8" class="data row8 col8" >5.49</td>
                        <td id="T_fe9ce_row8_col9" class="data row8 col9" >68.56</td>
                        <td id="T_fe9ce_row8_col10" class="data row8 col10" >22.19</td>
                        <td id="T_fe9ce_row8_col11" class="data row8 col11" >30.47</td>
                        <td id="T_fe9ce_row8_col12" class="data row8 col12" >65.80</td>
                        <td id="T_fe9ce_row8_col13" class="data row8 col13" >1.92</td>
                        <td id="T_fe9ce_row8_col14" class="data row8 col14" >76.78</td>
                        <td id="T_fe9ce_row8_col15" class="data row8 col15" >-</td>
                        <td id="T_fe9ce_row8_col16" class="data row8 col16" >8.43</td>
                        <td id="T_fe9ce_row8_col17" class="data row8 col17" >0.38</td>
                        <td id="T_fe9ce_row8_col18" class="data row8 col18" >-</td>
                        <td id="T_fe9ce_row8_col19" class="data row8 col19" >577.70</td>
                        <td id="T_fe9ce_row8_col20" class="data row8 col20" >881.27</td>
                        <td id="T_fe9ce_row8_col21" class="data row8 col21" >1,526.74</td>
                        <td id="T_fe9ce_row8_col22" class="data row8 col22" >34.45</td>
            </tr>
            <tr>
                        <th id="T_fe9ce_level0_row9" class="row_heading level0 row9" >3798.HK</th>
                        <td id="T_fe9ce_row9_col0" class="data row9 col0" >家乡互动</td>
                        <td id="T_fe9ce_row9_col1" class="data row9 col1" >14.06</td>
                        <td id="T_fe9ce_row9_col2" class="data row9 col2" >12.79</td>
                        <td id="T_fe9ce_row9_col3" class="data row9 col3" >-</td>
                        <td id="T_fe9ce_row9_col4" class="data row9 col4" >68.29</td>
                        <td id="T_fe9ce_row9_col5" class="data row9 col5" >44.74</td>
                        <td id="T_fe9ce_row9_col6" class="data row9 col6" >509.58</td>
                        <td id="T_fe9ce_row9_col7" class="data row9 col7" >44.37</td>
                        <td id="T_fe9ce_row9_col8" class="data row9 col8" >20.79</td>
                        <td id="T_fe9ce_row9_col9" class="data row9 col9" >230.06</td>
                        <td id="T_fe9ce_row9_col10" class="data row9 col10" >54.15</td>
                        <td id="T_fe9ce_row9_col11" class="data row9 col11" >46.52</td>
                        <td id="T_fe9ce_row9_col12" class="data row9 col12" >257.90</td>
                        <td id="T_fe9ce_row9_col13" class="data row9 col13" >31.66</td>
                        <td id="T_fe9ce_row9_col14" class="data row9 col14" >19.92</td>
                        <td id="T_fe9ce_row9_col15" class="data row9 col15" >-</td>
                        <td id="T_fe9ce_row9_col16" class="data row9 col16" >21.84</td>
                        <td id="T_fe9ce_row9_col17" class="data row9 col17" >0.40</td>
                        <td id="T_fe9ce_row9_col18" class="data row9 col18" >-</td>
                        <td id="T_fe9ce_row9_col19" class="data row9 col19" >5,024.96</td>
                        <td id="T_fe9ce_row9_col20" class="data row9 col20" >7,099.17</td>
                        <td id="T_fe9ce_row9_col21" class="data row9 col21" >9,944.67</td>
                        <td id="T_fe9ce_row9_col22" class="data row9 col22" >29.22</td>
            </tr>
            <tr>
                        <th id="T_fe9ce_level0_row10" class="row_heading level0 row10" >3601.HK</th>
                        <td id="T_fe9ce_row10_col0" class="data row10 col0" >鲁大师</td>
                        <td id="T_fe9ce_row10_col1" class="data row10 col1" >6.89</td>
                        <td id="T_fe9ce_row10_col2" class="data row10 col2" >19.15</td>
                        <td id="T_fe9ce_row10_col3" class="data row10 col3" >-</td>
                        <td id="T_fe9ce_row10_col4" class="data row10 col4" >28.40</td>
                        <td id="T_fe9ce_row10_col5" class="data row10 col5" >28.15</td>
                        <td id="T_fe9ce_row10_col6" class="data row10 col6" >298.81</td>
                        <td id="T_fe9ce_row10_col7" class="data row10 col7" >57.87</td>
                        <td id="T_fe9ce_row10_col8" class="data row10 col8" >91.82</td>
                        <td id="T_fe9ce_row10_col9" class="data row10 col9" >75.61</td>
                        <td id="T_fe9ce_row10_col10" class="data row10 col10" >16.75</td>
                        <td id="T_fe9ce_row10_col11" class="data row10 col11" >41.33</td>
                        <td id="T_fe9ce_row10_col12" class="data row10 col12" >47.16</td>
                        <td id="T_fe9ce_row10_col13" class="data row10 col13" >2.86</td>
                        <td id="T_fe9ce_row10_col14" class="data row10 col14" >32.01</td>
                        <td id="T_fe9ce_row10_col15" class="data row10 col15" >-</td>
                        <td id="T_fe9ce_row10_col16" class="data row10 col16" >7.89</td>
                        <td id="T_fe9ce_row10_col17" class="data row10 col17" >0.47</td>
                        <td id="T_fe9ce_row10_col18" class="data row10 col18" >-</td>
                        <td id="T_fe9ce_row10_col19" class="data row10 col19" >596.91</td>
                        <td id="T_fe9ce_row10_col20" class="data row10 col20" >647.98</td>
                        <td id="T_fe9ce_row10_col21" class="data row10 col21" >1,480.96</td>
                        <td id="T_fe9ce_row10_col22" class="data row10 col22" >7.88</td>
            </tr>
            <tr>
                        <th id="T_fe9ce_level0_row11" class="row_heading level0 row11" >6186.HK</th>
                        <td id="T_fe9ce_row11_col0" class="data row11 col0" >中国飞鹤</td>
                        <td id="T_fe9ce_row11_col1" class="data row11 col1" >32.26</td>
                        <td id="T_fe9ce_row11_col2" class="data row11 col2" >3.19</td>
                        <td id="T_fe9ce_row11_col3" class="data row11 col3" >0.27</td>
                        <td id="T_fe9ce_row11_col4" class="data row11 col4" >35.80</td>
                        <td id="T_fe9ce_row11_col5" class="data row11 col5" >27.49</td>
                        <td id="T_fe9ce_row11_col6" class="data row11 col6" >12,148.29</td>
                        <td id="T_fe9ce_row11_col7" class="data row11 col7" >48.02</td>
                        <td id="T_fe9ce_row11_col8" class="data row11 col8" >24.74</td>
                        <td id="T_fe9ce_row11_col9" class="data row11 col9" >3,693.48</td>
                        <td id="T_fe9ce_row11_col10" class="data row11 col10" >85.92</td>
                        <td id="T_fe9ce_row11_col11" class="data row11 col11" >9.29</td>
                        <td id="T_fe9ce_row11_col12" class="data row11 col12" >3,494.73</td>
                        <td id="T_fe9ce_row11_col13" class="data row11 col13" >66.16</td>
                        <td id="T_fe9ce_row11_col14" class="data row11 col14" >48.49</td>
                        <td id="T_fe9ce_row11_col15" class="data row11 col15" >-</td>
                        <td id="T_fe9ce_row11_col16" class="data row11 col16" >42.60</td>
                        <td id="T_fe9ce_row11_col17" class="data row11 col17" >0.50</td>
                        <td id="T_fe9ce_row11_col18" class="data row11 col18" >-</td>
                        <td id="T_fe9ce_row11_col19" class="data row11 col19" >157,330.55</td>
                        <td id="T_fe9ce_row11_col20" class="data row11 col20" >187,561.87</td>
                        <td id="T_fe9ce_row11_col21" class="data row11 col21" >274,554.27</td>
                        <td id="T_fe9ce_row11_col22" class="data row11 col22" >16.12</td>
            </tr>
            <tr>
                        <th id="T_fe9ce_level0_row12" class="row_heading level0 row12" >1830.HK</th>
                        <td id="T_fe9ce_row12_col0" class="data row12 col0" >必瘦站</td>
                        <td id="T_fe9ce_row12_col1" class="data row12 col1" >47.74</td>
                        <td id="T_fe9ce_row12_col2" class="data row12 col2" >6.14</td>
                        <td id="T_fe9ce_row12_col3" class="data row12 col3" >-</td>
                        <td id="T_fe9ce_row12_col4" class="data row12 col4" >42.84</td>
                        <td id="T_fe9ce_row12_col5" class="data row12 col5" >22.29</td>
                        <td id="T_fe9ce_row12_col6" class="data row12 col6" >1,025.31</td>
                        <td id="T_fe9ce_row12_col7" class="data row12 col7" >18.49</td>
                        <td id="T_fe9ce_row12_col8" class="data row12 col8" >14.25</td>
                        <td id="T_fe9ce_row12_col9" class="data row12 col9" >241.18</td>
                        <td id="T_fe9ce_row12_col10" class="data row12 col10" >63.25</td>
                        <td id="T_fe9ce_row12_col11" class="data row12 col11" >49.84</td>
                        <td id="T_fe9ce_row12_col12" class="data row12 col12" >329.60</td>
                        <td id="T_fe9ce_row12_col13" class="data row12 col13" >52.20</td>
                        <td id="T_fe9ce_row12_col14" class="data row12 col14" >36.98</td>
                        <td id="T_fe9ce_row12_col15" class="data row12 col15" >25.62</td>
                        <td id="T_fe9ce_row12_col16" class="data row12 col16" >34.51</td>
                        <td id="T_fe9ce_row12_col17" class="data row12 col17" >0.55</td>
                        <td id="T_fe9ce_row12_col18" class="data row12 col18" >10.07</td>
                        <td id="T_fe9ce_row12_col19" class="data row12 col19" >8,322.29</td>
                        <td id="T_fe9ce_row12_col20" class="data row12 col20" >13,734.87</td>
                        <td id="T_fe9ce_row12_col21" class="data row12 col21" >12,300.24</td>
                        <td id="T_fe9ce_row12_col22" class="data row12 col22" >39.41</td>
            </tr>
            <tr>
                        <th id="T_fe9ce_level0_row13" class="row_heading level0 row13" >1756.HK</th>
                        <td id="T_fe9ce_row13_col0" class="data row13 col0" >华立大学集团</td>
                        <td id="T_fe9ce_row13_col1" class="data row13 col1" >47.08</td>
                        <td id="T_fe9ce_row13_col2" class="data row13 col2" >2.89</td>
                        <td id="T_fe9ce_row13_col3" class="data row13 col3" >-</td>
                        <td id="T_fe9ce_row13_col4" class="data row13 col4" >15.53</td>
                        <td id="T_fe9ce_row13_col5" class="data row13 col5" >34.63</td>
                        <td id="T_fe9ce_row13_col6" class="data row13 col6" >655.61</td>
                        <td id="T_fe9ce_row13_col7" class="data row13 col7" >9.66</td>
                        <td id="T_fe9ce_row13_col8" class="data row13 col8" >4.01</td>
                        <td id="T_fe9ce_row13_col9" class="data row13 col9" >229.04</td>
                        <td id="T_fe9ce_row13_col10" class="data row13 col10" >17.66</td>
                        <td id="T_fe9ce_row13_col11" class="data row13 col11" >18.78</td>
                        <td id="T_fe9ce_row13_col12" class="data row13 col12" >-144.89</td>
                        <td id="T_fe9ce_row13_col13" class="data row13 col13" >85.28</td>
                        <td id="T_fe9ce_row13_col14" class="data row13 col14" >285.66</td>
                        <td id="T_fe9ce_row13_col15" class="data row13 col15" >-</td>
                        <td id="T_fe9ce_row13_col16" class="data row13 col16" >10.85</td>
                        <td id="T_fe9ce_row13_col17" class="data row13 col17" >0.61</td>
                        <td id="T_fe9ce_row13_col18" class="data row13 col18" >-</td>
                        <td id="T_fe9ce_row13_col19" class="data row13 col19" >2,484.60</td>
                        <td id="T_fe9ce_row13_col20" class="data row13 col20" >-10,662.89</td>
                        <td id="T_fe9ce_row13_col21" class="data row13 col21" >4,585.03</td>
                        <td id="T_fe9ce_row13_col22" class="data row13 col22" >-</td>
            </tr>
            <tr>
                        <th id="T_fe9ce_level0_row14" class="row_heading level0 row14" >1890.HK</th>
                        <td id="T_fe9ce_row14_col0" class="data row14 col0" >中国科培</td>
                        <td id="T_fe9ce_row14_col1" class="data row14 col1" >28.14</td>
                        <td id="T_fe9ce_row14_col2" class="data row14 col2" >22.19</td>
                        <td id="T_fe9ce_row14_col3" class="data row14 col3" >-</td>
                        <td id="T_fe9ce_row14_col4" class="data row14 col4" >19.44</td>
                        <td id="T_fe9ce_row14_col5" class="data row14 col5" >59.78</td>
                        <td id="T_fe9ce_row14_col6" class="data row14 col6" >653.07</td>
                        <td id="T_fe9ce_row14_col7" class="data row14 col7" >23.97</td>
                        <td id="T_fe9ce_row14_col8" class="data row14 col8" >2.47</td>
                        <td id="T_fe9ce_row14_col9" class="data row14 col9" >398.47</td>
                        <td id="T_fe9ce_row14_col10" class="data row14 col10" >35.11</td>
                        <td id="T_fe9ce_row14_col11" class="data row14 col11" >12.25</td>
                        <td id="T_fe9ce_row14_col12" class="data row14 col12" >144.04</td>
                        <td id="T_fe9ce_row14_col13" class="data row14 col13" >158.66</td>
                        <td id="T_fe9ce_row14_col14" class="data row14 col14" >226.57</td>
                        <td id="T_fe9ce_row14_col15" class="data row14 col15" >-</td>
                        <td id="T_fe9ce_row14_col16" class="data row14 col16" >24.24</td>
                        <td id="T_fe9ce_row14_col17" class="data row14 col17" >0.69</td>
                        <td id="T_fe9ce_row14_col18" class="data row14 col18" >-</td>
                        <td id="T_fe9ce_row14_col19" class="data row14 col19" >9,658.43</td>
                        <td id="T_fe9ce_row14_col20" class="data row14 col20" >28,139.16</td>
                        <td id="T_fe9ce_row14_col21" class="data row14 col21" >11,806.33</td>
                        <td id="T_fe9ce_row14_col22" class="data row14 col22" >65.68</td>
            </tr>
            <tr>
                        <th id="T_fe9ce_level0_row15" class="row_heading level0 row15" >9999.HK</th>
                        <td id="T_fe9ce_row15_col0" class="data row15 col0" >网易-S</td>
                        <td id="T_fe9ce_row15_col1" class="data row15 col1" >33.89</td>
                        <td id="T_fe9ce_row15_col2" class="data row15 col2" >8.99</td>
                        <td id="T_fe9ce_row15_col3" class="data row15 col3" >0.39</td>
                        <td id="T_fe9ce_row15_col4" class="data row15 col4" >21.57</td>
                        <td id="T_fe9ce_row15_col5" class="data row15 col5" >22.09</td>
                        <td id="T_fe9ce_row15_col6" class="data row15 col6" >57,131.05</td>
                        <td id="T_fe9ce_row15_col7" class="data row15 col7" >18.43</td>
                        <td id="T_fe9ce_row15_col8" class="data row15 col8" >5.14</td>
                        <td id="T_fe9ce_row15_col9" class="data row15 col9" >12,540.15</td>
                        <td id="T_fe9ce_row15_col10" class="data row15 col10" >53.15</td>
                        <td id="T_fe9ce_row15_col11" class="data row15 col11" >166.31</td>
                        <td id="T_fe9ce_row15_col12" class="data row15 col12" >15,330.20</td>
                        <td id="T_fe9ce_row15_col13" class="data row15 col13" >33.70</td>
                        <td id="T_fe9ce_row15_col14" class="data row15 col14" >20.88</td>
                        <td id="T_fe9ce_row15_col15" class="data row15 col15" >-</td>
                        <td id="T_fe9ce_row15_col16" class="data row15 col16" >39.08</td>
                        <td id="T_fe9ce_row15_col17" class="data row15 col17" >0.74</td>
                        <td id="T_fe9ce_row15_col18" class="data row15 col18" >-</td>
                        <td id="T_fe9ce_row15_col19" class="data row15 col19" >490,116.63</td>
                        <td id="T_fe9ce_row15_col20" class="data row15 col20" >440,855.12</td>
                        <td id="T_fe9ce_row15_col21" class="data row15 col21" >532,030.60</td>
                        <td id="T_fe9ce_row15_col22" class="data row15 col22" >-11.17</td>
            </tr>
            <tr>
                        <th id="T_fe9ce_level0_row16" class="row_heading level0 row16" >6969.HK</th>
                        <td id="T_fe9ce_row16_col0" class="data row16 col0" >思摩尔国际</td>
                        <td id="T_fe9ce_row16_col1" class="data row16 col1" >16.07</td>
                        <td id="T_fe9ce_row16_col2" class="data row16 col2" >23.94</td>
                        <td id="T_fe9ce_row16_col3" class="data row16 col3" >-</td>
                        <td id="T_fe9ce_row16_col4" class="data row16 col4" >109.26</td>
                        <td id="T_fe9ce_row16_col5" class="data row16 col5" >21.50</td>
                        <td id="T_fe9ce_row16_col6" class="data row16 col6" >5,654.86</td>
                        <td id="T_fe9ce_row16_col7" class="data row16 col7" >90.85</td>
                        <td id="T_fe9ce_row16_col8" class="data row16 col8" >51.39</td>
                        <td id="T_fe9ce_row16_col9" class="data row16 col9" >1,374.16</td>
                        <td id="T_fe9ce_row16_col10" class="data row16 col10" >164.98</td>
                        <td id="T_fe9ce_row16_col11" class="data row16 col11" >141.59</td>
                        <td id="T_fe9ce_row16_col12" class="data row16 col12" >1,386.35</td>
                        <td id="T_fe9ce_row16_col13" class="data row16 col13" >99.12</td>
                        <td id="T_fe9ce_row16_col14" class="data row16 col14" >37.70</td>
                        <td id="T_fe9ce_row16_col15" class="data row16 col15" >-</td>
                        <td id="T_fe9ce_row16_col16" class="data row16 col16" >169.88</td>
                        <td id="T_fe9ce_row16_col17" class="data row16 col17" >1.03</td>
                        <td id="T_fe9ce_row16_col18" class="data row16 col18" >-</td>
                        <td id="T_fe9ce_row16_col19" class="data row16 col19" >233,443.98</td>
                        <td id="T_fe9ce_row16_col20" class="data row16 col20" >125,841.15</td>
                        <td id="T_fe9ce_row16_col21" class="data row16 col21" >288,206.66</td>
                        <td id="T_fe9ce_row16_col22" class="data row16 col22" >-85.51</td>
            </tr>
            <tr>
                        <th id="T_fe9ce_level0_row17" class="row_heading level0 row17" >2189.HK</th>
                        <td id="T_fe9ce_row17_col0" class="data row17 col0" >嘉涛(香港)控股</td>
                        <td id="T_fe9ce_row17_col1" class="data row17 col1" >44.77</td>
                        <td id="T_fe9ce_row17_col2" class="data row17 col2" >2.00</td>
                        <td id="T_fe9ce_row17_col3" class="data row17 col3" >-</td>
                        <td id="T_fe9ce_row17_col4" class="data row17 col4" >98.37</td>
                        <td id="T_fe9ce_row17_col5" class="data row17 col5" >22.77</td>
                        <td id="T_fe9ce_row17_col6" class="data row17 col6" >170.41</td>
                        <td id="T_fe9ce_row17_col7" class="data row17 col7" >8.86</td>
                        <td id="T_fe9ce_row17_col8" class="data row17 col8" >4.30</td>
                        <td id="T_fe9ce_row17_col9" class="data row17 col9" >38.92</td>
                        <td id="T_fe9ce_row17_col10" class="data row17 col10" >13.05</td>
                        <td id="T_fe9ce_row17_col11" class="data row17 col11" >11.78</td>
                        <td id="T_fe9ce_row17_col12" class="data row17 col12" >44.22</td>
                        <td id="T_fe9ce_row17_col13" class="data row17 col13" >28.52</td>
                        <td id="T_fe9ce_row17_col14" class="data row17 col14" >18.31</td>
                        <td id="T_fe9ce_row17_col15" class="data row17 col15" >-</td>
                        <td id="T_fe9ce_row17_col16" class="data row17 col16" >14.41</td>
                        <td id="T_fe9ce_row17_col17" class="data row17 col17" >1.10</td>
                        <td id="T_fe9ce_row17_col18" class="data row17 col18" >-</td>
                        <td id="T_fe9ce_row17_col19" class="data row17 col19" >560.93</td>
                        <td id="T_fe9ce_row17_col20" class="data row17 col20" >1,136.39</td>
                        <td id="T_fe9ce_row17_col21" class="data row17 col21" >696.16</td>
                        <td id="T_fe9ce_row17_col22" class="data row17 col22" >50.64</td>
            </tr>
            <tr>
                        <th id="T_fe9ce_level0_row18" class="row_heading level0 row18" >0868.HK</th>
                        <td id="T_fe9ce_row18_col0" class="data row18 col0" >信义玻璃</td>
                        <td id="T_fe9ce_row18_col1" class="data row18 col1" >37.94</td>
                        <td id="T_fe9ce_row18_col2" class="data row18 col2" >17.37</td>
                        <td id="T_fe9ce_row18_col3" class="data row18 col3" >0.20</td>
                        <td id="T_fe9ce_row18_col4" class="data row18 col4" >22.32</td>
                        <td id="T_fe9ce_row18_col5" class="data row18 col5" >28.94</td>
                        <td id="T_fe9ce_row18_col6" class="data row18 col6" >16,404.10</td>
                        <td id="T_fe9ce_row18_col7" class="data row18 col7" >8.25</td>
                        <td id="T_fe9ce_row18_col8" class="data row18 col8" >6.50</td>
                        <td id="T_fe9ce_row18_col9" class="data row18 col9" >4,787.64</td>
                        <td id="T_fe9ce_row18_col10" class="data row18 col10" >18.22</td>
                        <td id="T_fe9ce_row18_col11" class="data row18 col11" >21.82</td>
                        <td id="T_fe9ce_row18_col12" class="data row18 col12" >1,850.63</td>
                        <td id="T_fe9ce_row18_col13" class="data row18 col13" >0.07</td>
                        <td id="T_fe9ce_row18_col14" class="data row18 col14" >60.29</td>
                        <td id="T_fe9ce_row18_col15" class="data row18 col15" >26.07</td>
                        <td id="T_fe9ce_row18_col16" class="data row18 col16" >20.29</td>
                        <td id="T_fe9ce_row18_col17" class="data row18 col17" >1.11</td>
                        <td id="T_fe9ce_row18_col18" class="data row18 col18" >4.84</td>
                        <td id="T_fe9ce_row18_col19" class="data row18 col19" >97,146.37</td>
                        <td id="T_fe9ce_row18_col20" class="data row18 col20" >23,562.26</td>
                        <td id="T_fe9ce_row18_col21" class="data row18 col21" >97,137.36</td>
                        <td id="T_fe9ce_row18_col22" class="data row18 col22" >-312.30</td>
            </tr>
            <tr>
                        <th id="T_fe9ce_level0_row19" class="row_heading level0 row19" >1935.HK</th>
                        <td id="T_fe9ce_row19_col0" class="data row19 col0" >嘉宏教育</td>
                        <td id="T_fe9ce_row19_col1" class="data row19 col1" >17.52</td>
                        <td id="T_fe9ce_row19_col2" class="data row19 col2" >1.35</td>
                        <td id="T_fe9ce_row19_col3" class="data row19 col3" >6.22</td>
                        <td id="T_fe9ce_row19_col4" class="data row19 col4" >15.27</td>
                        <td id="T_fe9ce_row19_col5" class="data row19 col5" >51.56</td>
                        <td id="T_fe9ce_row19_col6" class="data row19 col6" >380.06</td>
                        <td id="T_fe9ce_row19_col7" class="data row19 col7" >50.64</td>
                        <td id="T_fe9ce_row19_col8" class="data row19 col8" >31.14</td>
                        <td id="T_fe9ce_row19_col9" class="data row19 col9" >179.94</td>
                        <td id="T_fe9ce_row19_col10" class="data row19 col10" >30.61</td>
                        <td id="T_fe9ce_row19_col11" class="data row19 col11" >19.47</td>
                        <td id="T_fe9ce_row19_col12" class="data row19 col12" >222.45</td>
                        <td id="T_fe9ce_row19_col13" class="data row19 col13" >45.68</td>
                        <td id="T_fe9ce_row19_col14" class="data row19 col14" >45.18</td>
                        <td id="T_fe9ce_row19_col15" class="data row19 col15" >-</td>
                        <td id="T_fe9ce_row19_col16" class="data row19 col16" >36.84</td>
                        <td id="T_fe9ce_row19_col17" class="data row19 col17" >1.20</td>
                        <td id="T_fe9ce_row19_col18" class="data row19 col18" >-</td>
                        <td id="T_fe9ce_row19_col19" class="data row19 col19" >6,629.03</td>
                        <td id="T_fe9ce_row19_col20" class="data row19 col20" >8,174.89</td>
                        <td id="T_fe9ce_row19_col21" class="data row19 col21" >4,841.43</td>
                        <td id="T_fe9ce_row19_col22" class="data row19 col22" >18.91</td>
            </tr>
            <tr>
                        <th id="T_fe9ce_level0_row20" class="row_heading level0 row20" >0867.HK</th>
                        <td id="T_fe9ce_row20_col0" class="data row20 col0" >康哲药业</td>
                        <td id="T_fe9ce_row20_col1" class="data row20 col1" >12.58</td>
                        <td id="T_fe9ce_row20_col2" class="data row20 col2" >25.74</td>
                        <td id="T_fe9ce_row20_col3" class="data row20 col3" >11.01</td>
                        <td id="T_fe9ce_row20_col4" class="data row20 col4" >22.20</td>
                        <td id="T_fe9ce_row20_col5" class="data row20 col5" >33.52</td>
                        <td id="T_fe9ce_row20_col6" class="data row20 col6" >5,950.47</td>
                        <td id="T_fe9ce_row20_col7" class="data row20 col7" >9.24</td>
                        <td id="T_fe9ce_row20_col8" class="data row20 col8" >6.76</td>
                        <td id="T_fe9ce_row20_col9" class="data row20 col9" >2,003.95</td>
                        <td id="T_fe9ce_row20_col10" class="data row20 col10" >15.17</td>
                        <td id="T_fe9ce_row20_col11" class="data row20 col11" >12.23</td>
                        <td id="T_fe9ce_row20_col12" class="data row20 col12" >2,221.98</td>
                        <td id="T_fe9ce_row20_col13" class="data row20 col13" >12.66</td>
                        <td id="T_fe9ce_row20_col14" class="data row20 col14" >30.68</td>
                        <td id="T_fe9ce_row20_col15" class="data row20 col15" >23.55</td>
                        <td id="T_fe9ce_row20_col16" class="data row20 col16" >21.15</td>
                        <td id="T_fe9ce_row20_col17" class="data row20 col17" >1.39</td>
                        <td id="T_fe9ce_row20_col18" class="data row20 col18" >2.98</td>
                        <td id="T_fe9ce_row20_col19" class="data row20 col19" >42,393.10</td>
                        <td id="T_fe9ce_row20_col20" class="data row20 col20" >39,369.68</td>
                        <td id="T_fe9ce_row20_col21" class="data row20 col21" >37,767.44</td>
                        <td id="T_fe9ce_row20_col22" class="data row20 col22" >-7.68</td>
            </tr>
            <tr>
                        <th id="T_fe9ce_level0_row21" class="row_heading level0 row21" >0700.HK</th>
                        <td id="T_fe9ce_row21_col0" class="data row21 col0" >腾讯控股</td>
                        <td id="T_fe9ce_row21_col1" class="data row21 col1" >41.65</td>
                        <td id="T_fe9ce_row21_col2" class="data row21 col2" >10.98</td>
                        <td id="T_fe9ce_row21_col3" class="data row21 col3" >15.43</td>
                        <td id="T_fe9ce_row21_col4" class="data row21 col4" >24.13</td>
                        <td id="T_fe9ce_row21_col5" class="data row21 col5" >28.29</td>
                        <td id="T_fe9ce_row21_col6" class="data row21 col6" >352,451.75</td>
                        <td id="T_fe9ce_row21_col7" class="data row21 col7" >26.65</td>
                        <td id="T_fe9ce_row21_col8" class="data row21 col8" >5.52</td>
                        <td id="T_fe9ce_row21_col9" class="data row21 col9" >100,846.50</td>
                        <td id="T_fe9ce_row21_col10" class="data row21 col10" >33.31</td>
                        <td id="T_fe9ce_row21_col11" class="data row21 col11" >33.18</td>
                        <td id="T_fe9ce_row21_col12" class="data row21 col12" >117,774.50</td>
                        <td id="T_fe9ce_row21_col13" class="data row21 col13" >20.72</td>
                        <td id="T_fe9ce_row21_col14" class="data row21 col14" >21.25</td>
                        <td id="T_fe9ce_row21_col15" class="data row21 col15" >55.52</td>
                        <td id="T_fe9ce_row21_col16" class="data row21 col16" >47.99</td>
                        <td id="T_fe9ce_row21_col17" class="data row21 col17" >1.44</td>
                        <td id="T_fe9ce_row21_col18" class="data row21 col18" >0.23</td>
                        <td id="T_fe9ce_row21_col19" class="data row21 col19" >4,839,421.27</td>
                        <td id="T_fe9ce_row21_col20" class="data row21 col20" >2,534,702.96</td>
                        <td id="T_fe9ce_row21_col21" class="data row21 col21" >2,875,857.22</td>
                        <td id="T_fe9ce_row21_col22" class="data row21 col22" >-90.93</td>
            </tr>
            <tr>
                        <th id="T_fe9ce_level0_row22" class="row_heading level0 row22" >0799.HK</th>
                        <td id="T_fe9ce_row22_col0" class="data row22 col0" >IGG</td>
                        <td id="T_fe9ce_row22_col1" class="data row22 col1" >20.96</td>
                        <td id="T_fe9ce_row22_col2" class="data row22 col2" >8.47</td>
                        <td id="T_fe9ce_row22_col3" class="data row22 col3" >-</td>
                        <td id="T_fe9ce_row22_col4" class="data row22 col4" >58.33</td>
                        <td id="T_fe9ce_row22_col5" class="data row22 col5" >28.50</td>
                        <td id="T_fe9ce_row22_col6" class="data row22 col6" >681.95</td>
                        <td id="T_fe9ce_row22_col7" class="data row22 col7" >5.98</td>
                        <td id="T_fe9ce_row22_col8" class="data row22 col8" >17.08</td>
                        <td id="T_fe9ce_row22_col9" class="data row22 col9" >195.06</td>
                        <td id="T_fe9ce_row22_col10" class="data row22 col10" >24.11</td>
                        <td id="T_fe9ce_row22_col11" class="data row22 col11" >38.52</td>
                        <td id="T_fe9ce_row22_col12" class="data row22 col12" >172.30</td>
                        <td id="T_fe9ce_row22_col13" class="data row22 col13" >8.01</td>
                        <td id="T_fe9ce_row22_col14" class="data row22 col14" >48.52</td>
                        <td id="T_fe9ce_row22_col15" class="data row22 col15" >-</td>
                        <td id="T_fe9ce_row22_col16" class="data row22 col16" >59.58</td>
                        <td id="T_fe9ce_row22_col17" class="data row22 col17" >2.47</td>
                        <td id="T_fe9ce_row22_col18" class="data row22 col18" >3.28</td>
                        <td id="T_fe9ce_row22_col19" class="data row22 col19" >11,621.01</td>
                        <td id="T_fe9ce_row22_col20" class="data row22 col20" >2,712.39</td>
                        <td id="T_fe9ce_row22_col21" class="data row22 col21" >4,540.53</td>
                        <td id="T_fe9ce_row22_col22" class="data row22 col22" >-328.44</td>
            </tr>
            <tr>
                        <th id="T_fe9ce_level0_row23" class="row_heading level0 row23" >9997.HK</th>
                        <td id="T_fe9ce_row23_col0" class="data row23 col0" >康基医疗</td>
                        <td id="T_fe9ce_row23_col1" class="data row23 col1" >2.77</td>
                        <td id="T_fe9ce_row23_col2" class="data row23 col2" >17.33</td>
                        <td id="T_fe9ce_row23_col3" class="data row23 col3" >-</td>
                        <td id="T_fe9ce_row23_col4" class="data row23 col4" >43.05</td>
                        <td id="T_fe9ce_row23_col5" class="data row23 col5" >44.74</td>
                        <td id="T_fe9ce_row23_col6" class="data row23 col6" >404.03</td>
                        <td id="T_fe9ce_row23_col7" class="data row23 col7" >28.95</td>
                        <td id="T_fe9ce_row23_col8" class="data row23 col8" >23.69</td>
                        <td id="T_fe9ce_row23_col9" class="data row23 col9" >180.29</td>
                        <td id="T_fe9ce_row23_col10" class="data row23 col10" >28.87</td>
                        <td id="T_fe9ce_row23_col11" class="data row23 col11" >10.41</td>
                        <td id="T_fe9ce_row23_col12" class="data row23 col12" >211.14</td>
                        <td id="T_fe9ce_row23_col13" class="data row23 col13" >23.56</td>
                        <td id="T_fe9ce_row23_col14" class="data row23 col14" >53.22</td>
                        <td id="T_fe9ce_row23_col15" class="data row23 col15" >-</td>
                        <td id="T_fe9ce_row23_col16" class="data row23 col16" >76.09</td>
                        <td id="T_fe9ce_row23_col17" class="data row23 col17" >2.64</td>
                        <td id="T_fe9ce_row23_col18" class="data row23 col18" >-</td>
                        <td id="T_fe9ce_row23_col19" class="data row23 col19" >13,717.55</td>
                        <td id="T_fe9ce_row23_col20" class="data row23 col20" >4,853.30</td>
                        <td id="T_fe9ce_row23_col21" class="data row23 col21" >4,668.80</td>
                        <td id="T_fe9ce_row23_col22" class="data row23 col22" >-182.64</td>
            </tr>
            <tr>
                        <th id="T_fe9ce_level0_row24" class="row_heading level0 row24" >6127.HK</th>
                        <td id="T_fe9ce_row24_col0" class="data row24 col0" >昭衍新药</td>
                        <td id="T_fe9ce_row24_col1" class="data row24 col1" >41.92</td>
                        <td id="T_fe9ce_row24_col2" class="data row24 col2" >15.49</td>
                        <td id="T_fe9ce_row24_col3" class="data row24 col3" >10.23</td>
                        <td id="T_fe9ce_row24_col4" class="data row24 col4" >19.51</td>
                        <td id="T_fe9ce_row24_col5" class="data row24 col5" >27.59</td>
                        <td id="T_fe9ce_row24_col6" class="data row24 col6" >606.34</td>
                        <td id="T_fe9ce_row24_col7" class="data row24 col7" >53.46</td>
                        <td id="T_fe9ce_row24_col8" class="data row24 col8" >16.49</td>
                        <td id="T_fe9ce_row24_col9" class="data row24 col9" >171.64</td>
                        <td id="T_fe9ce_row24_col10" class="data row24 col10" >60.93</td>
                        <td id="T_fe9ce_row24_col11" class="data row24 col11" >16.74</td>
                        <td id="T_fe9ce_row24_col12" class="data row24 col12" >111.12</td>
                        <td id="T_fe9ce_row24_col13" class="data row24 col13" >368.09</td>
                        <td id="T_fe9ce_row24_col14" class="data row24 col14" >729.80</td>
                        <td id="T_fe9ce_row24_col15" class="data row24 col15" >-</td>
                        <td id="T_fe9ce_row24_col16" class="data row24 col16" >248.80</td>
                        <td id="T_fe9ce_row24_col17" class="data row24 col17" >4.08</td>
                        <td id="T_fe9ce_row24_col18" class="data row24 col18" >-</td>
                        <td id="T_fe9ce_row24_col19" class="data row24 col19" >42,703.84</td>
                        <td id="T_fe9ce_row24_col20" class="data row24 col20" >125,630.15</td>
                        <td id="T_fe9ce_row24_col21" class="data row24 col21" >8,399.09</td>
                        <td id="T_fe9ce_row24_col22" class="data row24 col22" >66.01</td>
            </tr>
            <tr>
                        <th id="T_fe9ce_level0_row25" class="row_heading level0 row25" >9633.HK</th>
                        <td id="T_fe9ce_row25_col0" class="data row25 col0" >农夫山泉</td>
                        <td id="T_fe9ce_row25_col1" class="data row25 col1" >40.09</td>
                        <td id="T_fe9ce_row25_col2" class="data row25 col2" >4.16</td>
                        <td id="T_fe9ce_row25_col3" class="data row25 col3" >-</td>
                        <td id="T_fe9ce_row25_col4" class="data row25 col4" >34.90</td>
                        <td id="T_fe9ce_row25_col5" class="data row25 col5" >20.15</td>
                        <td id="T_fe9ce_row25_col6" class="data row25 col6" >21,216.15</td>
                        <td id="T_fe9ce_row25_col7" class="data row25 col7" >9.87</td>
                        <td id="T_fe9ce_row25_col8" class="data row25 col8" >12.67</td>
                        <td id="T_fe9ce_row25_col9" class="data row25 col9" >4,303.12</td>
                        <td id="T_fe9ce_row25_col10" class="data row25 col10" >16.85</td>
                        <td id="T_fe9ce_row25_col11" class="data row25 col11" >17.65</td>
                        <td id="T_fe9ce_row25_col12" class="data row25 col12" >3,537.93</td>
                        <td id="T_fe9ce_row25_col13" class="data row25 col13" >75.80</td>
                        <td id="T_fe9ce_row25_col14" class="data row25 col14" >139.77</td>
                        <td id="T_fe9ce_row25_col15" class="data row25 col15" >-</td>
                        <td id="T_fe9ce_row25_col16" class="data row25 col16" >93.24</td>
                        <td id="T_fe9ce_row25_col17" class="data row25 col17" >5.53</td>
                        <td id="T_fe9ce_row25_col18" class="data row25 col18" >-</td>
                        <td id="T_fe9ce_row25_col19" class="data row25 col19" >401,240.52</td>
                        <td id="T_fe9ce_row25_col20" class="data row25 col20" >223,573.12</td>
                        <td id="T_fe9ce_row25_col21" class="data row25 col21" >84,479.65</td>
                        <td id="T_fe9ce_row25_col22" class="data row25 col22" >-79.47</td>
            </tr>
            <tr>
                        <th id="T_fe9ce_level0_row26" class="row_heading level0 row26" >1523.HK</th>
                        <td id="T_fe9ce_row26_col0" class="data row26 col0" >珩湾科技</td>
                        <td id="T_fe9ce_row26_col1" class="data row26 col1" >39.57</td>
                        <td id="T_fe9ce_row26_col2" class="data row26 col2" >13.40</td>
                        <td id="T_fe9ce_row26_col3" class="data row26 col3" >-</td>
                        <td id="T_fe9ce_row26_col4" class="data row26 col4" >34.51</td>
                        <td id="T_fe9ce_row26_col5" class="data row26 col5" >25.56</td>
                        <td id="T_fe9ce_row26_col6" class="data row26 col6" >44.42</td>
                        <td id="T_fe9ce_row26_col7" class="data row26 col7" >12.48</td>
                        <td id="T_fe9ce_row26_col8" class="data row26 col8" >2.62</td>
                        <td id="T_fe9ce_row26_col9" class="data row26 col9" >11.42</td>
                        <td id="T_fe9ce_row26_col10" class="data row26 col10" >17.62</td>
                        <td id="T_fe9ce_row26_col11" class="data row26 col11" >3.74</td>
                        <td id="T_fe9ce_row26_col12" class="data row26 col12" >12.66</td>
                        <td id="T_fe9ce_row26_col13" class="data row26 col13" >474.90</td>
                        <td id="T_fe9ce_row26_col14" class="data row26 col14" >836.60</td>
                        <td id="T_fe9ce_row26_col15" class="data row26 col15" >-</td>
                        <td id="T_fe9ce_row26_col16" class="data row26 col16" >119.96</td>
                        <td id="T_fe9ce_row26_col17" class="data row26 col17" >6.81</td>
                        <td id="T_fe9ce_row26_col18" class="data row26 col18" >-</td>
                        <td id="T_fe9ce_row26_col19" class="data row26 col19" >1,370.31</td>
                        <td id="T_fe9ce_row26_col20" class="data row26 col20" >26,395.44</td>
                        <td id="T_fe9ce_row26_col21" class="data row26 col21" >228.45</td>
                        <td id="T_fe9ce_row26_col22" class="data row26 col22" >94.81</td>
            </tr>
    </tbody></table>



### 观察列表




<style  type="text/css" >
#T_7061b_row0_col0,#T_7061b_row0_col1,#T_7061b_row0_col2,#T_7061b_row0_col3,#T_7061b_row0_col4,#T_7061b_row0_col5,#T_7061b_row0_col6,#T_7061b_row0_col7,#T_7061b_row0_col8,#T_7061b_row0_col9,#T_7061b_row0_col10,#T_7061b_row0_col11,#T_7061b_row0_col12,#T_7061b_row0_col13,#T_7061b_row0_col14,#T_7061b_row0_col15,#T_7061b_row0_col16,#T_7061b_row0_col17,#T_7061b_row0_col18,#T_7061b_row0_col19,#T_7061b_row0_col20,#T_7061b_row0_col21,#T_7061b_row0_col22,#T_7061b_row1_col0,#T_7061b_row1_col1,#T_7061b_row1_col2,#T_7061b_row1_col3,#T_7061b_row1_col4,#T_7061b_row1_col5,#T_7061b_row1_col6,#T_7061b_row1_col7,#T_7061b_row1_col8,#T_7061b_row1_col9,#T_7061b_row1_col10,#T_7061b_row1_col11,#T_7061b_row1_col12,#T_7061b_row1_col14,#T_7061b_row1_col15,#T_7061b_row1_col16,#T_7061b_row1_col17,#T_7061b_row1_col18,#T_7061b_row1_col19,#T_7061b_row1_col21,#T_7061b_row1_col22,#T_7061b_row2_col0,#T_7061b_row2_col1,#T_7061b_row2_col2,#T_7061b_row2_col3,#T_7061b_row2_col4,#T_7061b_row2_col5,#T_7061b_row2_col6,#T_7061b_row2_col7,#T_7061b_row2_col8,#T_7061b_row2_col9,#T_7061b_row2_col10,#T_7061b_row2_col11,#T_7061b_row2_col14,#T_7061b_row2_col15,#T_7061b_row2_col16,#T_7061b_row2_col17,#T_7061b_row2_col18,#T_7061b_row2_col19,#T_7061b_row2_col20,#T_7061b_row2_col21,#T_7061b_row3_col0,#T_7061b_row3_col1,#T_7061b_row3_col2,#T_7061b_row3_col3,#T_7061b_row3_col4,#T_7061b_row3_col5,#T_7061b_row3_col6,#T_7061b_row3_col7,#T_7061b_row3_col8,#T_7061b_row3_col9,#T_7061b_row3_col10,#T_7061b_row3_col11,#T_7061b_row3_col12,#T_7061b_row3_col13,#T_7061b_row3_col14,#T_7061b_row3_col15,#T_7061b_row3_col16,#T_7061b_row3_col17,#T_7061b_row3_col18,#T_7061b_row3_col19,#T_7061b_row3_col20,#T_7061b_row3_col21,#T_7061b_row4_col0,#T_7061b_row4_col1,#T_7061b_row4_col2,#T_7061b_row4_col3,#T_7061b_row4_col4,#T_7061b_row4_col5,#T_7061b_row4_col6,#T_7061b_row4_col7,#T_7061b_row4_col8,#T_7061b_row4_col9,#T_7061b_row4_col10,#T_7061b_row4_col11,#T_7061b_row4_col12,#T_7061b_row4_col14,#T_7061b_row4_col15,#T_7061b_row4_col16,#T_7061b_row4_col17,#T_7061b_row4_col18,#T_7061b_row4_col19,#T_7061b_row4_col20,#T_7061b_row4_col21,#T_7061b_row5_col0,#T_7061b_row5_col1,#T_7061b_row5_col2,#T_7061b_row5_col3,#T_7061b_row5_col4,#T_7061b_row5_col5,#T_7061b_row5_col6,#T_7061b_row5_col7,#T_7061b_row5_col8,#T_7061b_row5_col9,#T_7061b_row5_col10,#T_7061b_row5_col11,#T_7061b_row5_col12,#T_7061b_row5_col13,#T_7061b_row5_col14,#T_7061b_row5_col15,#T_7061b_row5_col16,#T_7061b_row5_col17,#T_7061b_row5_col18,#T_7061b_row5_col19,#T_7061b_row5_col20,#T_7061b_row5_col21,#T_7061b_row6_col0,#T_7061b_row6_col1,#T_7061b_row6_col2,#T_7061b_row6_col3,#T_7061b_row6_col4,#T_7061b_row6_col5,#T_7061b_row6_col6,#T_7061b_row6_col7,#T_7061b_row6_col8,#T_7061b_row6_col9,#T_7061b_row6_col10,#T_7061b_row6_col11,#T_7061b_row6_col12,#T_7061b_row6_col13,#T_7061b_row6_col14,#T_7061b_row6_col15,#T_7061b_row6_col16,#T_7061b_row6_col17,#T_7061b_row6_col18,#T_7061b_row6_col19,#T_7061b_row6_col20,#T_7061b_row6_col21,#T_7061b_row7_col0,#T_7061b_row7_col1,#T_7061b_row7_col2,#T_7061b_row7_col3,#T_7061b_row7_col4,#T_7061b_row7_col5,#T_7061b_row7_col6,#T_7061b_row7_col7,#T_7061b_row7_col8,#T_7061b_row7_col9,#T_7061b_row7_col10,#T_7061b_row7_col11,#T_7061b_row7_col12,#T_7061b_row7_col14,#T_7061b_row7_col15,#T_7061b_row7_col16,#T_7061b_row7_col17,#T_7061b_row7_col18,#T_7061b_row7_col19,#T_7061b_row7_col20,#T_7061b_row7_col21,#T_7061b_row8_col0,#T_7061b_row8_col1,#T_7061b_row8_col2,#T_7061b_row8_col3,#T_7061b_row8_col4,#T_7061b_row8_col5,#T_7061b_row8_col6,#T_7061b_row8_col7,#T_7061b_row8_col8,#T_7061b_row8_col9,#T_7061b_row8_col10,#T_7061b_row8_col11,#T_7061b_row8_col12,#T_7061b_row8_col14,#T_7061b_row8_col15,#T_7061b_row8_col16,#T_7061b_row8_col17,#T_7061b_row8_col18,#T_7061b_row8_col19,#T_7061b_row8_col20,#T_7061b_row8_col21,#T_7061b_row9_col0,#T_7061b_row9_col1,#T_7061b_row9_col2,#T_7061b_row9_col3,#T_7061b_row9_col4,#T_7061b_row9_col5,#T_7061b_row9_col6,#T_7061b_row9_col7,#T_7061b_row9_col8,#T_7061b_row9_col9,#T_7061b_row9_col10,#T_7061b_row9_col11,#T_7061b_row9_col13,#T_7061b_row9_col14,#T_7061b_row9_col15,#T_7061b_row9_col16,#T_7061b_row9_col17,#T_7061b_row9_col18,#T_7061b_row9_col19,#T_7061b_row9_col21,#T_7061b_row9_col22,#T_7061b_row10_col0,#T_7061b_row10_col1,#T_7061b_row10_col2,#T_7061b_row10_col3,#T_7061b_row10_col4,#T_7061b_row10_col5,#T_7061b_row10_col6,#T_7061b_row10_col7,#T_7061b_row10_col8,#T_7061b_row10_col9,#T_7061b_row10_col10,#T_7061b_row10_col11,#T_7061b_row10_col13,#T_7061b_row10_col14,#T_7061b_row10_col15,#T_7061b_row10_col16,#T_7061b_row10_col17,#T_7061b_row10_col18,#T_7061b_row10_col19,#T_7061b_row10_col21,#T_7061b_row10_col22,#T_7061b_row11_col0,#T_7061b_row11_col1,#T_7061b_row11_col2,#T_7061b_row11_col3,#T_7061b_row11_col4,#T_7061b_row11_col6,#T_7061b_row11_col7,#T_7061b_row11_col8,#T_7061b_row11_col9,#T_7061b_row11_col11,#T_7061b_row11_col12,#T_7061b_row11_col14,#T_7061b_row11_col15,#T_7061b_row11_col16,#T_7061b_row11_col17,#T_7061b_row11_col18,#T_7061b_row11_col19,#T_7061b_row11_col21,#T_7061b_row11_col22,#T_7061b_row12_col0,#T_7061b_row12_col1,#T_7061b_row12_col2,#T_7061b_row12_col3,#T_7061b_row12_col4,#T_7061b_row12_col5,#T_7061b_row12_col6,#T_7061b_row12_col7,#T_7061b_row12_col8,#T_7061b_row12_col9,#T_7061b_row12_col11,#T_7061b_row12_col12,#T_7061b_row12_col14,#T_7061b_row12_col15,#T_7061b_row12_col16,#T_7061b_row12_col17,#T_7061b_row12_col18,#T_7061b_row12_col19,#T_7061b_row12_col22,#T_7061b_row13_col0,#T_7061b_row13_col1,#T_7061b_row13_col2,#T_7061b_row13_col3,#T_7061b_row13_col6,#T_7061b_row13_col7,#T_7061b_row13_col8,#T_7061b_row13_col10,#T_7061b_row13_col11,#T_7061b_row13_col13,#T_7061b_row13_col14,#T_7061b_row13_col15,#T_7061b_row13_col16,#T_7061b_row13_col17,#T_7061b_row13_col18,#T_7061b_row13_col19,#T_7061b_row13_col22,#T_7061b_row14_col0,#T_7061b_row14_col1,#T_7061b_row14_col2,#T_7061b_row14_col4,#T_7061b_row14_col6,#T_7061b_row14_col7,#T_7061b_row14_col8,#T_7061b_row14_col10,#T_7061b_row14_col11,#T_7061b_row14_col12,#T_7061b_row14_col14,#T_7061b_row14_col15,#T_7061b_row14_col16,#T_7061b_row14_col17,#T_7061b_row14_col18,#T_7061b_row14_col19,#T_7061b_row14_col22,#T_7061b_row15_col0,#T_7061b_row15_col1,#T_7061b_row15_col2,#T_7061b_row15_col3,#T_7061b_row15_col4,#T_7061b_row15_col6,#T_7061b_row15_col7,#T_7061b_row15_col8,#T_7061b_row15_col10,#T_7061b_row15_col11,#T_7061b_row15_col13,#T_7061b_row15_col14,#T_7061b_row15_col15,#T_7061b_row15_col16,#T_7061b_row15_col17,#T_7061b_row15_col18,#T_7061b_row15_col19,#T_7061b_row15_col22,#T_7061b_row16_col0,#T_7061b_row16_col1,#T_7061b_row16_col2,#T_7061b_row16_col3,#T_7061b_row16_col6,#T_7061b_row16_col7,#T_7061b_row16_col8,#T_7061b_row16_col10,#T_7061b_row16_col11,#T_7061b_row16_col13,#T_7061b_row16_col14,#T_7061b_row16_col15,#T_7061b_row16_col16,#T_7061b_row16_col17,#T_7061b_row16_col18,#T_7061b_row16_col19,#T_7061b_row16_col22,#T_7061b_row17_col0,#T_7061b_row17_col1,#T_7061b_row17_col2,#T_7061b_row17_col3,#T_7061b_row17_col6,#T_7061b_row17_col8,#T_7061b_row17_col11,#T_7061b_row17_col12,#T_7061b_row17_col13,#T_7061b_row17_col14,#T_7061b_row17_col15,#T_7061b_row17_col16,#T_7061b_row17_col17,#T_7061b_row17_col18,#T_7061b_row17_col19,#T_7061b_row17_col20,#T_7061b_row17_col21,#T_7061b_row17_col22,#T_7061b_row18_col0,#T_7061b_row18_col1,#T_7061b_row18_col2,#T_7061b_row18_col3,#T_7061b_row18_col4,#T_7061b_row18_col5,#T_7061b_row18_col6,#T_7061b_row18_col7,#T_7061b_row18_col8,#T_7061b_row18_col9,#T_7061b_row18_col11,#T_7061b_row18_col12,#T_7061b_row18_col14,#T_7061b_row18_col15,#T_7061b_row18_col16,#T_7061b_row18_col17,#T_7061b_row18_col18,#T_7061b_row18_col19,#T_7061b_row18_col20,#T_7061b_row18_col21,#T_7061b_row19_col0,#T_7061b_row19_col1,#T_7061b_row19_col2,#T_7061b_row19_col3,#T_7061b_row19_col4,#T_7061b_row19_col5,#T_7061b_row19_col6,#T_7061b_row19_col7,#T_7061b_row19_col8,#T_7061b_row19_col9,#T_7061b_row19_col11,#T_7061b_row19_col14,#T_7061b_row19_col15,#T_7061b_row19_col16,#T_7061b_row19_col17,#T_7061b_row19_col18,#T_7061b_row19_col19,#T_7061b_row19_col20,#T_7061b_row19_col21,#T_7061b_row19_col22,#T_7061b_row20_col0,#T_7061b_row20_col1,#T_7061b_row20_col2,#T_7061b_row20_col3,#T_7061b_row20_col4,#T_7061b_row20_col5,#T_7061b_row20_col6,#T_7061b_row20_col8,#T_7061b_row20_col9,#T_7061b_row20_col11,#T_7061b_row20_col12,#T_7061b_row20_col14,#T_7061b_row20_col15,#T_7061b_row20_col16,#T_7061b_row20_col17,#T_7061b_row20_col18,#T_7061b_row20_col19,#T_7061b_row20_col20,#T_7061b_row20_col21,#T_7061b_row21_col0,#T_7061b_row21_col1,#T_7061b_row21_col2,#T_7061b_row21_col3,#T_7061b_row21_col6,#T_7061b_row21_col7,#T_7061b_row21_col8,#T_7061b_row21_col10,#T_7061b_row21_col11,#T_7061b_row21_col12,#T_7061b_row21_col14,#T_7061b_row21_col15,#T_7061b_row21_col16,#T_7061b_row21_col17,#T_7061b_row21_col18,#T_7061b_row21_col19,#T_7061b_row21_col22{
            color:  black;
        }#T_7061b_row1_col13,#T_7061b_row1_col20,#T_7061b_row2_col12,#T_7061b_row2_col13,#T_7061b_row2_col22,#T_7061b_row3_col22,#T_7061b_row4_col13,#T_7061b_row4_col22,#T_7061b_row5_col22,#T_7061b_row6_col22,#T_7061b_row7_col13,#T_7061b_row7_col22,#T_7061b_row8_col13,#T_7061b_row8_col22,#T_7061b_row9_col12,#T_7061b_row9_col20,#T_7061b_row10_col12,#T_7061b_row10_col20,#T_7061b_row11_col5,#T_7061b_row11_col10,#T_7061b_row11_col13,#T_7061b_row11_col20,#T_7061b_row12_col10,#T_7061b_row12_col13,#T_7061b_row12_col20,#T_7061b_row12_col21,#T_7061b_row13_col4,#T_7061b_row13_col5,#T_7061b_row13_col9,#T_7061b_row13_col12,#T_7061b_row13_col20,#T_7061b_row13_col21,#T_7061b_row14_col3,#T_7061b_row14_col5,#T_7061b_row14_col9,#T_7061b_row14_col13,#T_7061b_row14_col20,#T_7061b_row14_col21,#T_7061b_row15_col5,#T_7061b_row15_col9,#T_7061b_row15_col12,#T_7061b_row15_col20,#T_7061b_row15_col21,#T_7061b_row16_col4,#T_7061b_row16_col5,#T_7061b_row16_col9,#T_7061b_row16_col12,#T_7061b_row16_col20,#T_7061b_row16_col21,#T_7061b_row17_col4,#T_7061b_row17_col5,#T_7061b_row17_col7,#T_7061b_row17_col9,#T_7061b_row17_col10,#T_7061b_row18_col10,#T_7061b_row18_col13,#T_7061b_row18_col22,#T_7061b_row19_col10,#T_7061b_row19_col12,#T_7061b_row19_col13,#T_7061b_row20_col7,#T_7061b_row20_col10,#T_7061b_row20_col13,#T_7061b_row20_col22,#T_7061b_row21_col4,#T_7061b_row21_col5,#T_7061b_row21_col9,#T_7061b_row21_col13,#T_7061b_row21_col20,#T_7061b_row21_col21{
            color:  red;
        }</style><table id="T_7061b_" ><thead>    <tr>        <th class="blank level0" ></th>        <th class="col_heading level0 col0" >名称</th>        <th class="col_heading level0 col1" >负债率</th>        <th class="col_heading level0 col2" >应收比</th>        <th class="col_heading level0 col3" >商誉比</th>        <th class="col_heading level0 col4" >ROE</th>        <th class="col_heading level0 col5" >利润率</th>        <th class="col_heading level0 col6" >收入</th>        <th class="col_heading level0 col7" >收入增长</th>        <th class="col_heading level0 col8" >收入波动</th>        <th class="col_heading level0 col9" >盈利</th>        <th class="col_heading level0 col10" >盈利增长</th>        <th class="col_heading level0 col11" >盈利波动</th>        <th class="col_heading level0 col12" >FCF</th>        <th class="col_heading level0 col13" >FCF增长</th>        <th class="col_heading level0 col14" >FCF波动</th>        <th class="col_heading level0 col15" >PE</th>        <th class="col_heading level0 col16" >PE0</th>        <th class="col_heading level0 col17" >PEG</th>        <th class="col_heading level0 col18" >股息率</th>        <th class="col_heading level0 col19" >市值</th>        <th class="col_heading level0 col20" >DCF</th>        <th class="col_heading level0 col21" >盈利折现</th>        <th class="col_heading level0 col22" >折价率</th>    </tr>    <tr>        <th class="index_name level0" >Symbol</th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>    </tr></thead><tbody>
                <tr>
                        <th id="T_7061b_level0_row0" class="row_heading level0 row0" >9992.HK</th>
                        <td id="T_7061b_row0_col0" class="data row0 col0" >泡泡玛特</td>
                        <td id="T_7061b_row0_col1" class="data row0 col1" >12.05</td>
                        <td id="T_7061b_row0_col2" class="data row0 col2" >3.40</td>
                        <td id="T_7061b_row0_col3" class="data row0 col3" >0.00</td>
                        <td id="T_7061b_row0_col4" class="data row0 col4" >33.03</td>
                        <td id="T_7061b_row0_col5" class="data row0 col5" >16.99</td>
                        <td id="T_7061b_row0_col6" class="data row0 col6" >1,217.37</td>
                        <td id="T_7061b_row0_col7" class="data row0 col7" >167.33</td>
                        <td id="T_7061b_row0_col8" class="data row0 col8" >102.21</td>
                        <td id="T_7061b_row0_col9" class="data row0 col9" >268.93</td>
                        <td id="T_7061b_row0_col10" class="data row0 col10" >2,204.10</td>
                        <td id="T_7061b_row0_col11" class="data row0 col11" >3,501.82</td>
                        <td id="T_7061b_row0_col12" class="data row0 col12" >267.20</td>
                        <td id="T_7061b_row0_col13" class="data row0 col13" >1,216.11</td>
                        <td id="T_7061b_row0_col14" class="data row0 col14" >1,919.33</td>
                        <td id="T_7061b_row0_col15" class="data row0 col15" >-</td>
                        <td id="T_7061b_row0_col16" class="data row0 col16" >322.52</td>
                        <td id="T_7061b_row0_col17" class="data row0 col17" >0.15</td>
                        <td id="T_7061b_row0_col18" class="data row0 col18" >-</td>
                        <td id="T_7061b_row0_col19" class="data row0 col19" >86,734.52</td>
                        <td id="T_7061b_row0_col20" class="data row0 col20" >6,613,013.61</td>
                        <td id="T_7061b_row0_col21" class="data row0 col21" >35,600,742.07</td>
                        <td id="T_7061b_row0_col22" class="data row0 col22" >98.69</td>
            </tr>
            <tr>
                        <th id="T_7061b_level0_row1" class="row_heading level0 row1" >0285.HK</th>
                        <td id="T_7061b_row1_col0" class="data row1 col0" >比亚迪电子</td>
                        <td id="T_7061b_row1_col1" class="data row1 col1" >41.35</td>
                        <td id="T_7061b_row1_col2" class="data row1 col2" >19.80</td>
                        <td id="T_7061b_row1_col3" class="data row1 col3" >-</td>
                        <td id="T_7061b_row1_col4" class="data row1 col4" >16.47</td>
                        <td id="T_7061b_row1_col5" class="data row1 col5" >5.61</td>
                        <td id="T_7061b_row1_col6" class="data row1 col6" >51,492.75</td>
                        <td id="T_7061b_row1_col7" class="data row1 col7" >24.31</td>
                        <td id="T_7061b_row1_col8" class="data row1 col8" >16.56</td>
                        <td id="T_7061b_row1_col9" class="data row1 col9" >2,953.13</td>
                        <td id="T_7061b_row1_col10" class="data row1 col10" >66.09</td>
                        <td id="T_7061b_row1_col11" class="data row1 col11" >151.24</td>
                        <td id="T_7061b_row1_col12" class="data row1 col12" >30.80</td>
                        <td id="T_7061b_row1_col13" class="data row1 col13" >-353.88</td>
                        <td id="T_7061b_row1_col14" class="data row1 col14" >344.03</td>
                        <td id="T_7061b_row1_col15" class="data row1 col15" >66.55</td>
                        <td id="T_7061b_row1_col16" class="data row1 col16" >33.23</td>
                        <td id="T_7061b_row1_col17" class="data row1 col17" >0.50</td>
                        <td id="T_7061b_row1_col18" class="data row1 col18" >-</td>
                        <td id="T_7061b_row1_col19" class="data row1 col19" >98,137.49</td>
                        <td id="T_7061b_row1_col20" class="data row1 col20" >-5,328.03</td>
                        <td id="T_7061b_row1_col21" class="data row1 col21" >158,295.94</td>
                        <td id="T_7061b_row1_col22" class="data row1 col22" >-</td>
            </tr>
            <tr>
                        <th id="T_7061b_level0_row2" class="row_heading level0 row2" >3908.HK</th>
                        <td id="T_7061b_row2_col0" class="data row2 col0" >中金公司</td>
                        <td id="T_7061b_row2_col1" class="data row2 col1" >86.23</td>
                        <td id="T_7061b_row2_col2" class="data row2 col2" >279.30</td>
                        <td id="T_7061b_row2_col3" class="data row2 col3" >2.21</td>
                        <td id="T_7061b_row2_col4" class="data row2 col4" >8.66</td>
                        <td id="T_7061b_row2_col5" class="data row2 col5" >25.33</td>
                        <td id="T_7061b_row2_col6" class="data row2 col6" >17,345.27</td>
                        <td id="T_7061b_row2_col7" class="data row2 col7" >34.26</td>
                        <td id="T_7061b_row2_col8" class="data row2 col8" >29.68</td>
                        <td id="T_7061b_row2_col9" class="data row2 col9" >4,426.17</td>
                        <td id="T_7061b_row2_col10" class="data row2 col10" >39.22</td>
                        <td id="T_7061b_row2_col11" class="data row2 col11" >26.80</td>
                        <td id="T_7061b_row2_col12" class="data row2 col12" >-20,632.27</td>
                        <td id="T_7061b_row2_col13" class="data row2 col13" >-159.43</td>
                        <td id="T_7061b_row2_col14" class="data row2 col14" >194.62</td>
                        <td id="T_7061b_row2_col15" class="data row2 col15" >-</td>
                        <td id="T_7061b_row2_col16" class="data row2 col16" >44.43</td>
                        <td id="T_7061b_row2_col17" class="data row2 col17" >1.13</td>
                        <td id="T_7061b_row2_col18" class="data row2 col18" >-</td>
                        <td id="T_7061b_row2_col19" class="data row2 col19" >196,634.02</td>
                        <td id="T_7061b_row2_col20" class="data row2 col20" >52,206.02</td>
                        <td id="T_7061b_row2_col21" class="data row2 col21" >142,853.62</td>
                        <td id="T_7061b_row2_col22" class="data row2 col22" >-276.65</td>
            </tr>
            <tr>
                        <th id="T_7061b_level0_row3" class="row_heading level0 row3" >0700.HK</th>
                        <td id="T_7061b_row3_col0" class="data row3 col0" >腾讯控股</td>
                        <td id="T_7061b_row3_col1" class="data row3 col1" >41.65</td>
                        <td id="T_7061b_row3_col2" class="data row3 col2" >10.98</td>
                        <td id="T_7061b_row3_col3" class="data row3 col3" >15.43</td>
                        <td id="T_7061b_row3_col4" class="data row3 col4" >24.13</td>
                        <td id="T_7061b_row3_col5" class="data row3 col5" >28.29</td>
                        <td id="T_7061b_row3_col6" class="data row3 col6" >352,451.75</td>
                        <td id="T_7061b_row3_col7" class="data row3 col7" >26.65</td>
                        <td id="T_7061b_row3_col8" class="data row3 col8" >5.52</td>
                        <td id="T_7061b_row3_col9" class="data row3 col9" >100,846.50</td>
                        <td id="T_7061b_row3_col10" class="data row3 col10" >33.31</td>
                        <td id="T_7061b_row3_col11" class="data row3 col11" >33.18</td>
                        <td id="T_7061b_row3_col12" class="data row3 col12" >117,774.50</td>
                        <td id="T_7061b_row3_col13" class="data row3 col13" >20.72</td>
                        <td id="T_7061b_row3_col14" class="data row3 col14" >21.25</td>
                        <td id="T_7061b_row3_col15" class="data row3 col15" >55.52</td>
                        <td id="T_7061b_row3_col16" class="data row3 col16" >47.99</td>
                        <td id="T_7061b_row3_col17" class="data row3 col17" >1.44</td>
                        <td id="T_7061b_row3_col18" class="data row3 col18" >0.23</td>
                        <td id="T_7061b_row3_col19" class="data row3 col19" >4,839,421.27</td>
                        <td id="T_7061b_row3_col20" class="data row3 col20" >2,534,702.96</td>
                        <td id="T_7061b_row3_col21" class="data row3 col21" >2,875,857.22</td>
                        <td id="T_7061b_row3_col22" class="data row3 col22" >-90.93</td>
            </tr>
            <tr>
                        <th id="T_7061b_level0_row4" class="row_heading level0 row4" >2319.HK</th>
                        <td id="T_7061b_row4_col0" class="data row4 col0" >蒙牛乳业</td>
                        <td id="T_7061b_row4_col1" class="data row4 col1" >53.53</td>
                        <td id="T_7061b_row4_col2" class="data row4 col2" >5.72</td>
                        <td id="T_7061b_row4_col3" class="data row4 col3" >14.81</td>
                        <td id="T_7061b_row4_col4" class="data row4 col4" >11.48</td>
                        <td id="T_7061b_row4_col5" class="data row4 col5" >4.41</td>
                        <td id="T_7061b_row4_col6" class="data row4 col6" >71,049.35</td>
                        <td id="T_7061b_row4_col7" class="data row4 col7" >8.48</td>
                        <td id="T_7061b_row4_col8" class="data row4 col8" >10.63</td>
                        <td id="T_7061b_row4_col9" class="data row4 col9" >3,180.34</td>
                        <td id="T_7061b_row4_col10" class="data row4 col10" >23.12</td>
                        <td id="T_7061b_row4_col11" class="data row4 col11" >32.99</td>
                        <td id="T_7061b_row4_col12" class="data row4 col12" >2,269.85</td>
                        <td id="T_7061b_row4_col13" class="data row4 col13" >-26.64</td>
                        <td id="T_7061b_row4_col14" class="data row4 col14" >17.18</td>
                        <td id="T_7061b_row4_col15" class="data row4 col15" >38.00</td>
                        <td id="T_7061b_row4_col16" class="data row4 col16" >45.62</td>
                        <td id="T_7061b_row4_col17" class="data row4 col17" >1.97</td>
                        <td id="T_7061b_row4_col18" class="data row4 col18" >0.69</td>
                        <td id="T_7061b_row4_col19" class="data row4 col19" >145,090.26</td>
                        <td id="T_7061b_row4_col20" class="data row4 col20" >12,457.44</td>
                        <td id="T_7061b_row4_col21" class="data row4 col21" >72,372.90</td>
                        <td id="T_7061b_row4_col22" class="data row4 col22" >-1,064.69</td>
            </tr>
            <tr>
                        <th id="T_7061b_level0_row5" class="row_heading level0 row5" >2331.HK</th>
                        <td id="T_7061b_row5_col0" class="data row5 col0" >李宁</td>
                        <td id="T_7061b_row5_col1" class="data row5 col1" >40.46</td>
                        <td id="T_7061b_row5_col2" class="data row5 col2" >5.01</td>
                        <td id="T_7061b_row5_col3" class="data row5 col3" >1.19</td>
                        <td id="T_7061b_row5_col4" class="data row5 col4" >15.76</td>
                        <td id="T_7061b_row5_col5" class="data row5 col5" >8.79</td>
                        <td id="T_7061b_row5_col6" class="data row5 col6" >11,927.85</td>
                        <td id="T_7061b_row5_col7" class="data row5 col7" >18.21</td>
                        <td id="T_7061b_row5_col8" class="data row5 col8" >13.86</td>
                        <td id="T_7061b_row5_col9" class="data row5 col9" >1,107.01</td>
                        <td id="T_7061b_row5_col10" class="data row5 col10" >53.91</td>
                        <td id="T_7061b_row5_col11" class="data row5 col11" >49.88</td>
                        <td id="T_7061b_row5_col12" class="data row5 col12" >1,730.47</td>
                        <td id="T_7061b_row5_col13" class="data row5 col13" >59.22</td>
                        <td id="T_7061b_row5_col14" class="data row5 col14" >91.58</td>
                        <td id="T_7061b_row5_col15" class="data row5 col15" >106.62</td>
                        <td id="T_7061b_row5_col16" class="data row5 col16" >137.09</td>
                        <td id="T_7061b_row5_col17" class="data row5 col17" >2.54</td>
                        <td id="T_7061b_row5_col18" class="data row5 col18" >-</td>
                        <td id="T_7061b_row5_col19" class="data row5 col19" >151,764.26</td>
                        <td id="T_7061b_row5_col20" class="data row5 col20" >82,111.24</td>
                        <td id="T_7061b_row5_col21" class="data row5 col21" >47,642.28</td>
                        <td id="T_7061b_row5_col22" class="data row5 col22" >-84.83</td>
            </tr>
            <tr>
                        <th id="T_7061b_level0_row6" class="row_heading level0 row6" >2020.HK</th>
                        <td id="T_7061b_row6_col0" class="data row6 col0" >安踏体育</td>
                        <td id="T_7061b_row6_col1" class="data row6 col1" >50.21</td>
                        <td id="T_7061b_row6_col2" class="data row6 col2" >10.63</td>
                        <td id="T_7061b_row6_col3" class="data row6 col3" >-</td>
                        <td id="T_7061b_row6_col4" class="data row6 col4" >24.16</td>
                        <td id="T_7061b_row6_col5" class="data row6 col5" >16.45</td>
                        <td id="T_7061b_row6_col6" class="data row6 col6" >27,558.13</td>
                        <td id="T_7061b_row6_col7" class="data row6 col7" >29.94</td>
                        <td id="T_7061b_row6_col8" class="data row6 col8" >21.96</td>
                        <td id="T_7061b_row6_col9" class="data row6 col9" >4,424.17</td>
                        <td id="T_7061b_row6_col10" class="data row6 col10" >19.91</td>
                        <td id="T_7061b_row6_col11" class="data row6 col11" >20.23</td>
                        <td id="T_7061b_row6_col12" class="data row6 col12" >5,098.48</td>
                        <td id="T_7061b_row6_col13" class="data row6 col13" >41.31</td>
                        <td id="T_7061b_row6_col14" class="data row6 col14" >39.73</td>
                        <td id="T_7061b_row6_col15" class="data row6 col15" >70.93</td>
                        <td id="T_7061b_row6_col16" class="data row6 col16" >79.39</td>
                        <td id="T_7061b_row6_col17" class="data row6 col17" >3.99</td>
                        <td id="T_7061b_row6_col18" class="data row6 col18" >1.83</td>
                        <td id="T_7061b_row6_col19" class="data row6 col19" >351,221.37</td>
                        <td id="T_7061b_row6_col20" class="data row6 col20" >171,726.14</td>
                        <td id="T_7061b_row6_col21" class="data row6 col21" >93,414.41</td>
                        <td id="T_7061b_row6_col22" class="data row6 col22" >-104.52</td>
            </tr>
            <tr>
                        <th id="T_7061b_level0_row7" class="row_heading level0 row7" >3613.HK</th>
                        <td id="T_7061b_row7_col0" class="data row7 col0" >同仁堂国药</td>
                        <td id="T_7061b_row7_col1" class="data row7 col1" >8.41</td>
                        <td id="T_7061b_row7_col2" class="data row7 col2" >41.62</td>
                        <td id="T_7061b_row7_col3" class="data row7 col3" >1.64</td>
                        <td id="T_7061b_row7_col4" class="data row7 col4" >19.63</td>
                        <td id="T_7061b_row7_col5" class="data row7 col5" >39.28</td>
                        <td id="T_7061b_row7_col6" class="data row7 col6" >1,381.96</td>
                        <td id="T_7061b_row7_col7" class="data row7 col7" >2.01</td>
                        <td id="T_7061b_row7_col8" class="data row7 col8" >15.28</td>
                        <td id="T_7061b_row7_col9" class="data row7 col9" >542.32</td>
                        <td id="T_7061b_row7_col10" class="data row7 col10" >3.94</td>
                        <td id="T_7061b_row7_col11" class="data row7 col11" >12.66</td>
                        <td id="T_7061b_row7_col12" class="data row7 col12" >399.18</td>
                        <td id="T_7061b_row7_col13" class="data row7 col13" >-19.44</td>
                        <td id="T_7061b_row7_col14" class="data row7 col14" >53.86</td>
                        <td id="T_7061b_row7_col15" class="data row7 col15" >-</td>
                        <td id="T_7061b_row7_col16" class="data row7 col16" >16.35</td>
                        <td id="T_7061b_row7_col17" class="data row7 col17" >4.15</td>
                        <td id="T_7061b_row7_col18" class="data row7 col18" >1.67</td>
                        <td id="T_7061b_row7_col19" class="data row7 col19" >8,866.33</td>
                        <td id="T_7061b_row7_col20" class="data row7 col20" >2,811.67</td>
                        <td id="T_7061b_row7_col21" class="data row7 col21" >7,671.70</td>
                        <td id="T_7061b_row7_col22" class="data row7 col22" >-215.34</td>
            </tr>
            <tr>
                        <th id="T_7061b_level0_row8" class="row_heading level0 row8" >2359.HK</th>
                        <td id="T_7061b_row8_col0" class="data row8 col0" >药明康德</td>
                        <td id="T_7061b_row8_col1" class="data row8 col1" >29.32</td>
                        <td id="T_7061b_row8_col2" class="data row8 col2" >25.62</td>
                        <td id="T_7061b_row8_col3" class="data row8 col3" >4.28</td>
                        <td id="T_7061b_row8_col4" class="data row8 col4" >12.99</td>
                        <td id="T_7061b_row8_col5" class="data row8 col5" >17.91</td>
                        <td id="T_7061b_row8_col6" class="data row8 col6" >11,696.65</td>
                        <td id="T_7061b_row8_col7" class="data row8 col7" >28.72</td>
                        <td id="T_7061b_row8_col8" class="data row8 col8" >5.05</td>
                        <td id="T_7061b_row8_col9" class="data row8 col9" >2,075.60</td>
                        <td id="T_7061b_row8_col10" class="data row8 col10" >41.96</td>
                        <td id="T_7061b_row8_col11" class="data row8 col11" >53.33</td>
                        <td id="T_7061b_row8_col12" class="data row8 col12" >287.20</td>
                        <td id="T_7061b_row8_col13" class="data row8 col13" >-86.40</td>
                        <td id="T_7061b_row8_col14" class="data row8 col14" >204.47</td>
                        <td id="T_7061b_row8_col15" class="data row8 col15" >-</td>
                        <td id="T_7061b_row8_col16" class="data row8 col16" >174.09</td>
                        <td id="T_7061b_row8_col17" class="data row8 col17" >4.15</td>
                        <td id="T_7061b_row8_col18" class="data row8 col18" >-</td>
                        <td id="T_7061b_row8_col19" class="data row8 col19" >361,346.79</td>
                        <td id="T_7061b_row8_col20" class="data row8 col20" >51.77</td>
                        <td id="T_7061b_row8_col21" class="data row8 col21" >70,832.18</td>
                        <td id="T_7061b_row8_col22" class="data row8 col22" >-697,943.69</td>
            </tr>
            <tr>
                        <th id="T_7061b_level0_row9" class="row_heading level0 row9" >2269.HK</th>
                        <td id="T_7061b_row9_col0" class="data row9 col0" >药明生物</td>
                        <td id="T_7061b_row9_col1" class="data row9 col1" >27.84</td>
                        <td id="T_7061b_row9_col2" class="data row9 col2" >49.35</td>
                        <td id="T_7061b_row9_col3" class="data row9 col3" >0.90</td>
                        <td id="T_7061b_row9_col4" class="data row9 col4" >7.58</td>
                        <td id="T_7061b_row9_col5" class="data row9 col5" >24.01</td>
                        <td id="T_7061b_row9_col6" class="data row9 col6" >3,437.34</td>
                        <td id="T_7061b_row9_col7" class="data row9 col7" >51.54</td>
                        <td id="T_7061b_row9_col8" class="data row9 col8" >9.24</td>
                        <td id="T_7061b_row9_col9" class="data row9 col9" >896.48</td>
                        <td id="T_7061b_row9_col10" class="data row9 col10" >92.32</td>
                        <td id="T_7061b_row9_col11" class="data row9 col11" >49.70</td>
                        <td id="T_7061b_row9_col12" class="data row9 col12" >-1,758.83</td>
                        <td id="T_7061b_row9_col13" class="data row9 col13" >146.45</td>
                        <td id="T_7061b_row9_col14" class="data row9 col14" >86.69</td>
                        <td id="T_7061b_row9_col15" class="data row9 col15" >-</td>
                        <td id="T_7061b_row9_col16" class="data row9 col16" >469.14</td>
                        <td id="T_7061b_row9_col17" class="data row9 col17" >5.08</td>
                        <td id="T_7061b_row9_col18" class="data row9 col18" >-</td>
                        <td id="T_7061b_row9_col19" class="data row9 col19" >420,574.56</td>
                        <td id="T_7061b_row9_col20" class="data row9 col20" >-298,052.90</td>
                        <td id="T_7061b_row9_col21" class="data row9 col21" >73,543.81</td>
                        <td id="T_7061b_row9_col22" class="data row9 col22" >-</td>
            </tr>
            <tr>
                        <th id="T_7061b_level0_row10" class="row_heading level0 row10" >0981.HK</th>
                        <td id="T_7061b_row10_col0" class="data row10 col0" >中芯国际</td>
                        <td id="T_7061b_row10_col1" class="data row10 col1" >30.77</td>
                        <td id="T_7061b_row10_col2" class="data row10 col2" >14.01</td>
                        <td id="T_7061b_row10_col3" class="data row10 col3" >0.08</td>
                        <td id="T_7061b_row10_col4" class="data row10 col4" >3.54</td>
                        <td id="T_7061b_row10_col5" class="data row10 col5" >8.91</td>
                        <td id="T_7061b_row10_col6" class="data row10 col6" >3,370.95</td>
                        <td id="T_7061b_row10_col7" class="data row10 col7" >8.82</td>
                        <td id="T_7061b_row10_col8" class="data row10 col8" >16.34</td>
                        <td id="T_7061b_row10_col9" class="data row10 col9" >315.99</td>
                        <td id="T_7061b_row10_col10" class="data row10 col10" >84.86</td>
                        <td id="T_7061b_row10_col11" class="data row10 col11" >115.46</td>
                        <td id="T_7061b_row10_col12" class="data row10 col12" >-1,670.03</td>
                        <td id="T_7061b_row10_col13" class="data row10 col13" >97.63</td>
                        <td id="T_7061b_row10_col14" class="data row10 col14" >196.87</td>
                        <td id="T_7061b_row10_col15" class="data row10 col15" >303.19</td>
                        <td id="T_7061b_row10_col16" class="data row10 col16" >674.62</td>
                        <td id="T_7061b_row10_col17" class="data row10 col17" >7.95</td>
                        <td id="T_7061b_row10_col18" class="data row10 col18" >-</td>
                        <td id="T_7061b_row10_col19" class="data row10 col19" >213,174.60</td>
                        <td id="T_7061b_row10_col20" class="data row10 col20" >-148,297.71</td>
                        <td id="T_7061b_row10_col21" class="data row10 col21" >23,102.85</td>
                        <td id="T_7061b_row10_col22" class="data row10 col22" >-</td>
            </tr>
            <tr>
                        <th id="T_7061b_level0_row11" class="row_heading level0 row11" >1810.HK</th>
                        <td id="T_7061b_row11_col0" class="data row11 col0" >小米集团-W</td>
                        <td id="T_7061b_row11_col1" class="data row11 col1" >51.11</td>
                        <td id="T_7061b_row11_col2" class="data row11 col2" >13.70</td>
                        <td id="T_7061b_row11_col3" class="data row11 col3" >0.20</td>
                        <td id="T_7061b_row11_col4" class="data row11 col4" >20.56</td>
                        <td id="T_7061b_row11_col5" class="data row11 col5" >-4.33</td>
                        <td id="T_7061b_row11_col6" class="data row11 col6" >185,311.12</td>
                        <td id="T_7061b_row11_col7" class="data row11 col7" >29.91</td>
                        <td id="T_7061b_row11_col8" class="data row11 col8" >19.67</td>
                        <td id="T_7061b_row11_col9" class="data row11 col9" >31.88</td>
                        <td id="T_7061b_row11_col10" class="data row11 col10" >-18.05</td>
                        <td id="T_7061b_row11_col11" class="data row11 col11" >116.99</td>
                        <td id="T_7061b_row11_col12" class="data row11 col12" >7,961.22</td>
                        <td id="T_7061b_row11_col13" class="data row11 col13" >-121.70</td>
                        <td id="T_7061b_row11_col14" class="data row11 col14" >328.86</td>
                        <td id="T_7061b_row11_col15" class="data row11 col15" >-</td>
                        <td id="T_7061b_row11_col16" class="data row11 col16" >19,122.21</td>
                        <td id="T_7061b_row11_col17" class="data row11 col17" >-</td>
                        <td id="T_7061b_row11_col18" class="data row11 col18" >-</td>
                        <td id="T_7061b_row11_col19" class="data row11 col19" >609,702.02</td>
                        <td id="T_7061b_row11_col20" class="data row11 col20" >-2,258.02</td>
                        <td id="T_7061b_row11_col21" class="data row11 col21" >235.10</td>
                        <td id="T_7061b_row11_col22" class="data row11 col22" >-</td>
            </tr>
            <tr>
                        <th id="T_7061b_level0_row12" class="row_heading level0 row12" >3888.HK</th>
                        <td id="T_7061b_row12_col0" class="data row12 col0" >金山软件</td>
                        <td id="T_7061b_row12_col1" class="data row12 col1" >19.45</td>
                        <td id="T_7061b_row12_col2" class="data row12 col2" >28.51</td>
                        <td id="T_7061b_row12_col3" class="data row12 col3" >0.75</td>
                        <td id="T_7061b_row12_col4" class="data row12 col4" >14.75</td>
                        <td id="T_7061b_row12_col5" class="data row12 col5" >53.14</td>
                        <td id="T_7061b_row12_col6" class="data row12 col6" >5,263.20</td>
                        <td id="T_7061b_row12_col7" class="data row12 col7" >5.33</td>
                        <td id="T_7061b_row12_col8" class="data row12 col8" >28.01</td>
                        <td id="T_7061b_row12_col9" class="data row12 col9" >3,022.43</td>
                        <td id="T_7061b_row12_col10" class="data row12 col10" >-444.91</td>
                        <td id="T_7061b_row12_col11" class="data row12 col11" >333.97</td>
                        <td id="T_7061b_row12_col12" class="data row12 col12" >639.09</td>
                        <td id="T_7061b_row12_col13" class="data row12 col13" >-240.00</td>
                        <td id="T_7061b_row12_col14" class="data row12 col14" >283.31</td>
                        <td id="T_7061b_row12_col15" class="data row12 col15" >-</td>
                        <td id="T_7061b_row12_col16" class="data row12 col16" >19.92</td>
                        <td id="T_7061b_row12_col17" class="data row12 col17" >-</td>
                        <td id="T_7061b_row12_col18" class="data row12 col18" >-</td>
                        <td id="T_7061b_row12_col19" class="data row12 col19" >60,205.27</td>
                        <td id="T_7061b_row12_col20" class="data row12 col20" >-18,641.06</td>
                        <td id="T_7061b_row12_col21" class="data row12 col21" >-1,314,064.02</td>
                        <td id="T_7061b_row12_col22" class="data row12 col22" >-</td>
            </tr>
            <tr>
                        <th id="T_7061b_level0_row13" class="row_heading level0 row13" >3690.HK</th>
                        <td id="T_7061b_row13_col0" class="data row13 col0" >美团-W</td>
                        <td id="T_7061b_row13_col1" class="data row13 col1" >41.39</td>
                        <td id="T_7061b_row13_col2" class="data row13 col2" >8.66</td>
                        <td id="T_7061b_row13_col3" class="data row13 col3" >28.30</td>
                        <td id="T_7061b_row13_col4" class="data row13 col4" >-19.90</td>
                        <td id="T_7061b_row13_col5" class="data row13 col5" >-56.90</td>
                        <td id="T_7061b_row13_col6" class="data row13 col6" >77,337.82</td>
                        <td id="T_7061b_row13_col7" class="data row13 col7" >52.67</td>
                        <td id="T_7061b_row13_col8" class="data row13 col8" >36.69</td>
                        <td id="T_7061b_row13_col9" class="data row13 col9" >-31,861.68</td>
                        <td id="T_7061b_row13_col10" class="data row13 col10" >172.94</td>
                        <td id="T_7061b_row13_col11" class="data row13 col11" >310.96</td>
                        <td id="T_7061b_row13_col12" class="data row13 col12" >-3,149.06</td>
                        <td id="T_7061b_row13_col13" class="data row13 col13" >219.37</td>
                        <td id="T_7061b_row13_col14" class="data row13 col14" >666.06</td>
                        <td id="T_7061b_row13_col15" class="data row13 col15" >-</td>
                        <td id="T_7061b_row13_col16" class="data row13 col16" >-</td>
                        <td id="T_7061b_row13_col17" class="data row13 col17" >-</td>
                        <td id="T_7061b_row13_col18" class="data row13 col18" >-</td>
                        <td id="T_7061b_row13_col19" class="data row13 col19" >1,514,579.61</td>
                        <td id="T_7061b_row13_col20" class="data row13 col20" >-1,145,660.33</td>
                        <td id="T_7061b_row13_col21" class="data row13 col21" >-7,290,728.76</td>
                        <td id="T_7061b_row13_col22" class="data row13 col22" >-</td>
            </tr>
            <tr>
                        <th id="T_7061b_level0_row14" class="row_heading level0 row14" >1024.HK</th>
                        <td id="T_7061b_row14_col0" class="data row14 col0" >快手-W</td>
                        <td id="T_7061b_row14_col1" class="data row14 col1" >406.92</td>
                        <td id="T_7061b_row14_col2" class="data row14 col2" >6.89</td>
                        <td id="T_7061b_row14_col3" class="data row14 col3" >-0.52</td>
                        <td id="T_7061b_row14_col4" class="data row14 col4" >58.33</td>
                        <td id="T_7061b_row14_col5" class="data row14 col5" >-137.56</td>
                        <td id="T_7061b_row14_col6" class="data row14 col6" >31,634.17</td>
                        <td id="T_7061b_row14_col7" class="data row14 col7" >95.46</td>
                        <td id="T_7061b_row14_col8" class="data row14 col8" >46.65</td>
                        <td id="T_7061b_row14_col9" class="data row14 col9" >-42,190.25</td>
                        <td id="T_7061b_row14_col10" class="data row14 col10" >171.21</td>
                        <td id="T_7061b_row14_col11" class="data row14 col11" >283.23</td>
                        <td id="T_7061b_row14_col12" class="data row14 col12" >621.03</td>
                        <td id="T_7061b_row14_col13" class="data row14 col13" >-317.01</td>
                        <td id="T_7061b_row14_col14" class="data row14 col14" >264.59</td>
                        <td id="T_7061b_row14_col15" class="data row14 col15" >-</td>
                        <td id="T_7061b_row14_col16" class="data row14 col16" >-</td>
                        <td id="T_7061b_row14_col17" class="data row14 col17" >-</td>
                        <td id="T_7061b_row14_col18" class="data row14 col18" >-</td>
                        <td id="T_7061b_row14_col19" class="data row14 col19" >708,096.73</td>
                        <td id="T_7061b_row14_col20" class="data row14 col20" >-67,063.72</td>
                        <td id="T_7061b_row14_col21" class="data row14 col21" >-9,474,943.88</td>
                        <td id="T_7061b_row14_col22" class="data row14 col22" >-</td>
            </tr>
            <tr>
                        <th id="T_7061b_level0_row15" class="row_heading level0 row15" >1068.HK</th>
                        <td id="T_7061b_row15_col0" class="data row15 col0" >雨润食品</td>
                        <td id="T_7061b_row15_col1" class="data row15 col1" >135.43</td>
                        <td id="T_7061b_row15_col2" class="data row15 col2" >12.35</td>
                        <td id="T_7061b_row15_col3" class="data row15 col3" >-</td>
                        <td id="T_7061b_row15_col4" class="data row15 col4" >38.19</td>
                        <td id="T_7061b_row15_col5" class="data row15 col5" >-23.16</td>
                        <td id="T_7061b_row15_col6" class="data row15 col6" >13,786.51</td>
                        <td id="T_7061b_row15_col7" class="data row15 col7" >8.40</td>
                        <td id="T_7061b_row15_col8" class="data row15 col8" >10.65</td>
                        <td id="T_7061b_row15_col9" class="data row15 col9" >-3,158.41</td>
                        <td id="T_7061b_row15_col10" class="data row15 col10" >27.51</td>
                        <td id="T_7061b_row15_col11" class="data row15 col11" >105.95</td>
                        <td id="T_7061b_row15_col12" class="data row15 col12" >-147.83</td>
                        <td id="T_7061b_row15_col13" class="data row15 col13" >12.50</td>
                        <td id="T_7061b_row15_col14" class="data row15 col14" >149.90</td>
                        <td id="T_7061b_row15_col15" class="data row15 col15" >-</td>
                        <td id="T_7061b_row15_col16" class="data row15 col16" >-</td>
                        <td id="T_7061b_row15_col17" class="data row15 col17" >-</td>
                        <td id="T_7061b_row15_col18" class="data row15 col18" >-</td>
                        <td id="T_7061b_row15_col19" class="data row15 col19" >1,503.59</td>
                        <td id="T_7061b_row15_col20" class="data row15 col20" >-2,608.77</td>
                        <td id="T_7061b_row15_col21" class="data row15 col21" >-79,373.86</td>
                        <td id="T_7061b_row15_col22" class="data row15 col22" >-</td>
            </tr>
            <tr>
                        <th id="T_7061b_level0_row16" class="row_heading level0 row16" >8083.HK</th>
                        <td id="T_7061b_row16_col0" class="data row16 col0" >中国有赞</td>
                        <td id="T_7061b_row16_col1" class="data row16 col1" >62.09</td>
                        <td id="T_7061b_row16_col2" class="data row16 col2" >3.54</td>
                        <td id="T_7061b_row16_col3" class="data row16 col3" >50.88</td>
                        <td id="T_7061b_row16_col4" class="data row16 col4" >-11.46</td>
                        <td id="T_7061b_row16_col5" class="data row16 col5" >-48.60</td>
                        <td id="T_7061b_row16_col6" class="data row16 col6" >945.93</td>
                        <td id="T_7061b_row16_col7" class="data row16 col7" >112.40</td>
                        <td id="T_7061b_row16_col8" class="data row16 col8" >64.15</td>
                        <td id="T_7061b_row16_col9" class="data row16 col9" >-357.55</td>
                        <td id="T_7061b_row16_col10" class="data row16 col10" >90.51</td>
                        <td id="T_7061b_row16_col11" class="data row16 col11" >173.65</td>
                        <td id="T_7061b_row16_col12" class="data row16 col12" >-447.26</td>
                        <td id="T_7061b_row16_col13" class="data row16 col13" >81.34</td>
                        <td id="T_7061b_row16_col14" class="data row16 col14" >278.29</td>
                        <td id="T_7061b_row16_col15" class="data row16 col15" >-</td>
                        <td id="T_7061b_row16_col16" class="data row16 col16" >-</td>
                        <td id="T_7061b_row16_col17" class="data row16 col17" >-</td>
                        <td id="T_7061b_row16_col18" class="data row16 col18" >-</td>
                        <td id="T_7061b_row16_col19" class="data row16 col19" >22,638.06</td>
                        <td id="T_7061b_row16_col20" class="data row16 col20" >-30,924.16</td>
                        <td id="T_7061b_row16_col21" class="data row16 col21" >-28,535.10</td>
                        <td id="T_7061b_row16_col22" class="data row16 col22" >-</td>
            </tr>
            <tr>
                        <th id="T_7061b_level0_row17" class="row_heading level0 row17" >2298.HK</th>
                        <td id="T_7061b_row17_col0" class="data row17 col0" >都市丽人</td>
                        <td id="T_7061b_row17_col1" class="data row17 col1" >46.44</td>
                        <td id="T_7061b_row17_col2" class="data row17 col2" >9.88</td>
                        <td id="T_7061b_row17_col3" class="data row17 col3" >0.12</td>
                        <td id="T_7061b_row17_col4" class="data row17 col4" >-9.33</td>
                        <td id="T_7061b_row17_col5" class="data row17 col5" >-5.31</td>
                        <td id="T_7061b_row17_col6" class="data row17 col6" >4,194.58</td>
                        <td id="T_7061b_row17_col7" class="data row17 col7" >-10.94</td>
                        <td id="T_7061b_row17_col8" class="data row17 col8" >20.20</td>
                        <td id="T_7061b_row17_col9" class="data row17 col9" >-180.17</td>
                        <td id="T_7061b_row17_col10" class="data row17 col10" >-171.57</td>
                        <td id="T_7061b_row17_col11" class="data row17 col11" >241.55</td>
                        <td id="T_7061b_row17_col12" class="data row17 col12" >43.22</td>
                        <td id="T_7061b_row17_col13" class="data row17 col13" >153.46</td>
                        <td id="T_7061b_row17_col14" class="data row17 col14" >539.55</td>
                        <td id="T_7061b_row17_col15" class="data row17 col15" >-</td>
                        <td id="T_7061b_row17_col16" class="data row17 col16" >-</td>
                        <td id="T_7061b_row17_col17" class="data row17 col17" >-</td>
                        <td id="T_7061b_row17_col18" class="data row17 col18" >-</td>
                        <td id="T_7061b_row17_col19" class="data row17 col19" >2,208.14</td>
                        <td id="T_7061b_row17_col20" class="data row17 col20" >7,953.01</td>
                        <td id="T_7061b_row17_col21" class="data row17 col21" >755.58</td>
                        <td id="T_7061b_row17_col22" class="data row17 col22" >72.24</td>
            </tr>
            <tr>
                        <th id="T_7061b_level0_row18" class="row_heading level0 row18" >0268.HK</th>
                        <td id="T_7061b_row18_col0" class="data row18 col0" >金蝶国际</td>
                        <td id="T_7061b_row18_col1" class="data row18 col1" >25.77</td>
                        <td id="T_7061b_row18_col2" class="data row18 col2" >30.00</td>
                        <td id="T_7061b_row18_col3" class="data row18 col3" >1.63</td>
                        <td id="T_7061b_row18_col4" class="data row18 col4" >4.30</td>
                        <td id="T_7061b_row18_col5" class="data row18 col5" >7.33</td>
                        <td id="T_7061b_row18_col6" class="data row18 col6" >2,948.54</td>
                        <td id="T_7061b_row18_col7" class="data row18 col7" >13.75</td>
                        <td id="T_7061b_row18_col8" class="data row18 col8" >11.25</td>
                        <td id="T_7061b_row18_col9" class="data row18 col9" >189.80</td>
                        <td id="T_7061b_row18_col10" class="data row18 col10" >-55.57</td>
                        <td id="T_7061b_row18_col11" class="data row18 col11" >118.39</td>
                        <td id="T_7061b_row18_col12" class="data row18 col12" >756.61</td>
                        <td id="T_7061b_row18_col13" class="data row18 col13" >-12.84</td>
                        <td id="T_7061b_row18_col14" class="data row18 col14" >35.18</td>
                        <td id="T_7061b_row18_col15" class="data row18 col15" >220.22</td>
                        <td id="T_7061b_row18_col16" class="data row18 col16" >427.39</td>
                        <td id="T_7061b_row18_col17" class="data row18 col17" >-</td>
                        <td id="T_7061b_row18_col18" class="data row18 col18" >-</td>
                        <td id="T_7061b_row18_col19" class="data row18 col19" >81,120.13</td>
                        <td id="T_7061b_row18_col20" class="data row18 col20" >6,591.52</td>
                        <td id="T_7061b_row18_col21" class="data row18 col21" >298.54</td>
                        <td id="T_7061b_row18_col22" class="data row18 col22" >-1,130.67</td>
            </tr>
            <tr>
                        <th id="T_7061b_level0_row19" class="row_heading level0 row19" >1347.HK</th>
                        <td id="T_7061b_row19_col0" class="data row19 col0" >华虹半导体</td>
                        <td id="T_7061b_row19_col1" class="data row19 col1" >26.58</td>
                        <td id="T_7061b_row19_col2" class="data row19 col2" >13.98</td>
                        <td id="T_7061b_row19_col3" class="data row19 col3" >-</td>
                        <td id="T_7061b_row19_col4" class="data row19 col4" >7.06</td>
                        <td id="T_7061b_row19_col5" class="data row19 col5" >16.35</td>
                        <td id="T_7061b_row19_col6" class="data row19 col6" >908.07</td>
                        <td id="T_7061b_row19_col7" class="data row19 col7" >6.15</td>
                        <td id="T_7061b_row19_col8" class="data row19 col8" >7.89</td>
                        <td id="T_7061b_row19_col9" class="data row19 col9" >147.53</td>
                        <td id="T_7061b_row19_col10" class="data row19 col10" >-8.01</td>
                        <td id="T_7061b_row19_col11" class="data row19 col11" >32.53</td>
                        <td id="T_7061b_row19_col12" class="data row19 col12" >-353.18</td>
                        <td id="T_7061b_row19_col13" class="data row19 col13" >-619.72</td>
                        <td id="T_7061b_row19_col14" class="data row19 col14" >1,026.21</td>
                        <td id="T_7061b_row19_col15" class="data row19 col15" >42.30</td>
                        <td id="T_7061b_row19_col16" class="data row19 col16" >301.16</td>
                        <td id="T_7061b_row19_col17" class="data row19 col17" >-</td>
                        <td id="T_7061b_row19_col18" class="data row19 col18" >-</td>
                        <td id="T_7061b_row19_col19" class="data row19 col19" >44,428.73</td>
                        <td id="T_7061b_row19_col20" class="data row19 col20" >527,495.56</td>
                        <td id="T_7061b_row19_col21" class="data row19 col21" >1,489.15</td>
                        <td id="T_7061b_row19_col22" class="data row19 col22" >91.58</td>
            </tr>
            <tr>
                        <th id="T_7061b_level0_row20" class="row_heading level0 row20" >6055.HK</th>
                        <td id="T_7061b_row20_col0" class="data row20 col0" >中烟香港</td>
                        <td id="T_7061b_row20_col1" class="data row20 col1" >56.43</td>
                        <td id="T_7061b_row20_col2" class="data row20 col2" >9.93</td>
                        <td id="T_7061b_row20_col3" class="data row20 col3" >-</td>
                        <td id="T_7061b_row20_col4" class="data row20 col4" >21.51</td>
                        <td id="T_7061b_row20_col5" class="data row20 col5" >3.60</td>
                        <td id="T_7061b_row20_col6" class="data row20 col6" >6,824.37</td>
                        <td id="T_7061b_row20_col7" class="data row20 col7" >-14.50</td>
                        <td id="T_7061b_row20_col8" class="data row20 col8" >44.61</td>
                        <td id="T_7061b_row20_col9" class="data row20 col9" >254.48</td>
                        <td id="T_7061b_row20_col10" class="data row20 col10" >-23.96</td>
                        <td id="T_7061b_row20_col11" class="data row20 col11" >46.53</td>
                        <td id="T_7061b_row20_col12" class="data row20 col12" >358.57</td>
                        <td id="T_7061b_row20_col13" class="data row20 col13" >-17.49</td>
                        <td id="T_7061b_row20_col14" class="data row20 col14" >115.64</td>
                        <td id="T_7061b_row20_col15" class="data row20 col15" >-</td>
                        <td id="T_7061b_row20_col16" class="data row20 col16" >39.91</td>
                        <td id="T_7061b_row20_col17" class="data row20 col17" >-</td>
                        <td id="T_7061b_row20_col18" class="data row20 col18" >-</td>
                        <td id="T_7061b_row20_col19" class="data row20 col19" >10,156.09</td>
                        <td id="T_7061b_row20_col20" class="data row20 col20" >2,692.93</td>
                        <td id="T_7061b_row20_col21" class="data row20 col21" >1,535.84</td>
                        <td id="T_7061b_row20_col22" class="data row20 col22" >-277.14</td>
            </tr>
            <tr>
                        <th id="T_7061b_level0_row21" class="row_heading level0 row21" >9626.HK</th>
                        <td id="T_7061b_row21_col0" class="data row21 col0" >哔哩哔哩-SW</td>
                        <td id="T_7061b_row21_col1" class="data row21 col1" >67.39</td>
                        <td id="T_7061b_row21_col2" class="data row21 col2" >11.77</td>
                        <td id="T_7061b_row21_col3" class="data row21 col3" >17.05</td>
                        <td id="T_7061b_row21_col4" class="data row21 col4" >-9.33</td>
                        <td id="T_7061b_row21_col5" class="data row21 col5" >-20.55</td>
                        <td id="T_7061b_row21_col6" class="data row21 col6" >6,343.57</td>
                        <td id="T_7061b_row21_col7" class="data row21 col7" >69.49</td>
                        <td id="T_7061b_row21_col8" class="data row21 col8" >6.72</td>
                        <td id="T_7061b_row21_col9" class="data row21 col9" >-1,372.14</td>
                        <td id="T_7061b_row21_col10" class="data row21 col10" >83.54</td>
                        <td id="T_7061b_row21_col11" class="data row21 col11" >66.70</td>
                        <td id="T_7061b_row21_col12" class="data row21 col12" >203.21</td>
                        <td id="T_7061b_row21_col13" class="data row21 col13" >-110.94</td>
                        <td id="T_7061b_row21_col14" class="data row21 col14" >144.16</td>
                        <td id="T_7061b_row21_col15" class="data row21 col15" >-</td>
                        <td id="T_7061b_row21_col16" class="data row21 col16" >-</td>
                        <td id="T_7061b_row21_col17" class="data row21 col17" >-</td>
                        <td id="T_7061b_row21_col18" class="data row21 col18" >-</td>
                        <td id="T_7061b_row21_col19" class="data row21 col19" >252,914.54</td>
                        <td id="T_7061b_row21_col20" class="data row21 col20" >-22.84</td>
                        <td id="T_7061b_row21_col21" class="data row21 col21" >-98,257.86</td>
                        <td id="T_7061b_row21_col22" class="data row21 col22" >-</td>
            </tr>
    </tbody></table>




<script>
$('table').addClass('table table-striped table-hover  table-sm ')
$('thead').addClass('thead-dark')
$('.main').css('width', '1800px')
</script>