---
layout: default
title: 选股(2106)
---


<style>
table {font-size: 11px;}
</style>


# 选股

**Update: 20210603**

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
#T_79e1b_row0_col0,#T_79e1b_row0_col1,#T_79e1b_row0_col2,#T_79e1b_row0_col3,#T_79e1b_row0_col4,#T_79e1b_row0_col5,#T_79e1b_row0_col6,#T_79e1b_row0_col7,#T_79e1b_row0_col8,#T_79e1b_row0_col9,#T_79e1b_row0_col10,#T_79e1b_row0_col12,#T_79e1b_row0_col14,#T_79e1b_row0_col15,#T_79e1b_row0_col16,#T_79e1b_row0_col17,#T_79e1b_row0_col18,#T_79e1b_row1_col0,#T_79e1b_row1_col1,#T_79e1b_row1_col2,#T_79e1b_row1_col3,#T_79e1b_row1_col4,#T_79e1b_row1_col5,#T_79e1b_row1_col6,#T_79e1b_row1_col7,#T_79e1b_row1_col8,#T_79e1b_row1_col9,#T_79e1b_row1_col10,#T_79e1b_row1_col11,#T_79e1b_row1_col12,#T_79e1b_row1_col14,#T_79e1b_row1_col15,#T_79e1b_row1_col16,#T_79e1b_row1_col17,#T_79e1b_row1_col18,#T_79e1b_row2_col0,#T_79e1b_row2_col1,#T_79e1b_row2_col2,#T_79e1b_row2_col3,#T_79e1b_row2_col4,#T_79e1b_row2_col5,#T_79e1b_row2_col6,#T_79e1b_row2_col8,#T_79e1b_row2_col9,#T_79e1b_row2_col10,#T_79e1b_row2_col12,#T_79e1b_row2_col13,#T_79e1b_row2_col14,#T_79e1b_row2_col15,#T_79e1b_row2_col16,#T_79e1b_row2_col17,#T_79e1b_row3_col0,#T_79e1b_row3_col1,#T_79e1b_row3_col2,#T_79e1b_row3_col3,#T_79e1b_row3_col4,#T_79e1b_row3_col5,#T_79e1b_row3_col6,#T_79e1b_row3_col7,#T_79e1b_row3_col8,#T_79e1b_row3_col9,#T_79e1b_row3_col10,#T_79e1b_row3_col11,#T_79e1b_row3_col12,#T_79e1b_row3_col13,#T_79e1b_row3_col14,#T_79e1b_row3_col15,#T_79e1b_row3_col16,#T_79e1b_row3_col17,#T_79e1b_row3_col18,#T_79e1b_row4_col0,#T_79e1b_row4_col1,#T_79e1b_row4_col2,#T_79e1b_row4_col3,#T_79e1b_row4_col4,#T_79e1b_row4_col5,#T_79e1b_row4_col6,#T_79e1b_row4_col7,#T_79e1b_row4_col8,#T_79e1b_row4_col9,#T_79e1b_row4_col10,#T_79e1b_row4_col11,#T_79e1b_row4_col12,#T_79e1b_row4_col13,#T_79e1b_row4_col14,#T_79e1b_row4_col15,#T_79e1b_row4_col16,#T_79e1b_row4_col17,#T_79e1b_row4_col18,#T_79e1b_row5_col0,#T_79e1b_row5_col1,#T_79e1b_row5_col2,#T_79e1b_row5_col3,#T_79e1b_row5_col4,#T_79e1b_row5_col5,#T_79e1b_row5_col6,#T_79e1b_row5_col8,#T_79e1b_row5_col9,#T_79e1b_row5_col10,#T_79e1b_row5_col12,#T_79e1b_row5_col13,#T_79e1b_row5_col14,#T_79e1b_row5_col15,#T_79e1b_row5_col16,#T_79e1b_row5_col17,#T_79e1b_row6_col0,#T_79e1b_row6_col1,#T_79e1b_row6_col2,#T_79e1b_row6_col3,#T_79e1b_row6_col4,#T_79e1b_row6_col5,#T_79e1b_row6_col6,#T_79e1b_row6_col7,#T_79e1b_row6_col8,#T_79e1b_row6_col9,#T_79e1b_row6_col10,#T_79e1b_row6_col11,#T_79e1b_row6_col12,#T_79e1b_row6_col13,#T_79e1b_row6_col14,#T_79e1b_row6_col15,#T_79e1b_row6_col16,#T_79e1b_row6_col17,#T_79e1b_row6_col18,#T_79e1b_row7_col0,#T_79e1b_row7_col1,#T_79e1b_row7_col2,#T_79e1b_row7_col3,#T_79e1b_row7_col4,#T_79e1b_row7_col5,#T_79e1b_row7_col6,#T_79e1b_row7_col7,#T_79e1b_row7_col8,#T_79e1b_row7_col9,#T_79e1b_row7_col10,#T_79e1b_row7_col11,#T_79e1b_row7_col12,#T_79e1b_row7_col13,#T_79e1b_row7_col14,#T_79e1b_row7_col15,#T_79e1b_row7_col16,#T_79e1b_row7_col17,#T_79e1b_row8_col0,#T_79e1b_row8_col1,#T_79e1b_row8_col2,#T_79e1b_row8_col3,#T_79e1b_row8_col4,#T_79e1b_row8_col5,#T_79e1b_row8_col6,#T_79e1b_row8_col7,#T_79e1b_row8_col8,#T_79e1b_row8_col9,#T_79e1b_row8_col10,#T_79e1b_row8_col11,#T_79e1b_row8_col12,#T_79e1b_row8_col13,#T_79e1b_row8_col14,#T_79e1b_row8_col15,#T_79e1b_row8_col16,#T_79e1b_row8_col17,#T_79e1b_row9_col0,#T_79e1b_row9_col1,#T_79e1b_row9_col2,#T_79e1b_row9_col3,#T_79e1b_row9_col4,#T_79e1b_row9_col5,#T_79e1b_row9_col6,#T_79e1b_row9_col7,#T_79e1b_row9_col8,#T_79e1b_row9_col9,#T_79e1b_row9_col10,#T_79e1b_row9_col11,#T_79e1b_row9_col12,#T_79e1b_row9_col13,#T_79e1b_row9_col14,#T_79e1b_row9_col15,#T_79e1b_row9_col16,#T_79e1b_row9_col17,#T_79e1b_row10_col0,#T_79e1b_row10_col1,#T_79e1b_row10_col2,#T_79e1b_row10_col3,#T_79e1b_row10_col4,#T_79e1b_row10_col5,#T_79e1b_row10_col6,#T_79e1b_row10_col7,#T_79e1b_row10_col8,#T_79e1b_row10_col9,#T_79e1b_row10_col10,#T_79e1b_row10_col12,#T_79e1b_row10_col14,#T_79e1b_row10_col15,#T_79e1b_row10_col16,#T_79e1b_row10_col17,#T_79e1b_row10_col18,#T_79e1b_row11_col0,#T_79e1b_row11_col1,#T_79e1b_row11_col2,#T_79e1b_row11_col3,#T_79e1b_row11_col4,#T_79e1b_row11_col5,#T_79e1b_row11_col6,#T_79e1b_row11_col7,#T_79e1b_row11_col8,#T_79e1b_row11_col9,#T_79e1b_row11_col10,#T_79e1b_row11_col11,#T_79e1b_row11_col12,#T_79e1b_row11_col13,#T_79e1b_row11_col14,#T_79e1b_row11_col15,#T_79e1b_row11_col16,#T_79e1b_row11_col17,#T_79e1b_row12_col0,#T_79e1b_row12_col1,#T_79e1b_row12_col2,#T_79e1b_row12_col3,#T_79e1b_row12_col4,#T_79e1b_row12_col5,#T_79e1b_row12_col6,#T_79e1b_row12_col7,#T_79e1b_row12_col8,#T_79e1b_row12_col9,#T_79e1b_row12_col10,#T_79e1b_row12_col12,#T_79e1b_row12_col14,#T_79e1b_row12_col15,#T_79e1b_row12_col16,#T_79e1b_row12_col17,#T_79e1b_row12_col18,#T_79e1b_row13_col0,#T_79e1b_row13_col1,#T_79e1b_row13_col2,#T_79e1b_row13_col3,#T_79e1b_row13_col4,#T_79e1b_row13_col5,#T_79e1b_row13_col6,#T_79e1b_row13_col7,#T_79e1b_row13_col8,#T_79e1b_row13_col9,#T_79e1b_row13_col10,#T_79e1b_row13_col11,#T_79e1b_row13_col12,#T_79e1b_row13_col13,#T_79e1b_row13_col14,#T_79e1b_row13_col15,#T_79e1b_row13_col16,#T_79e1b_row13_col17,#T_79e1b_row14_col0,#T_79e1b_row14_col1,#T_79e1b_row14_col2,#T_79e1b_row14_col3,#T_79e1b_row14_col4,#T_79e1b_row14_col5,#T_79e1b_row14_col6,#T_79e1b_row14_col7,#T_79e1b_row14_col8,#T_79e1b_row14_col9,#T_79e1b_row14_col10,#T_79e1b_row14_col12,#T_79e1b_row14_col13,#T_79e1b_row14_col14,#T_79e1b_row14_col15,#T_79e1b_row14_col16,#T_79e1b_row14_col17,#T_79e1b_row15_col0,#T_79e1b_row15_col1,#T_79e1b_row15_col2,#T_79e1b_row15_col3,#T_79e1b_row15_col4,#T_79e1b_row15_col5,#T_79e1b_row15_col6,#T_79e1b_row15_col7,#T_79e1b_row15_col8,#T_79e1b_row15_col9,#T_79e1b_row15_col10,#T_79e1b_row15_col12,#T_79e1b_row15_col14,#T_79e1b_row15_col15,#T_79e1b_row15_col16,#T_79e1b_row15_col17,#T_79e1b_row15_col18,#T_79e1b_row16_col0,#T_79e1b_row16_col1,#T_79e1b_row16_col2,#T_79e1b_row16_col3,#T_79e1b_row16_col4,#T_79e1b_row16_col5,#T_79e1b_row16_col6,#T_79e1b_row16_col7,#T_79e1b_row16_col8,#T_79e1b_row16_col9,#T_79e1b_row16_col10,#T_79e1b_row16_col11,#T_79e1b_row16_col12,#T_79e1b_row16_col13,#T_79e1b_row16_col14,#T_79e1b_row16_col15,#T_79e1b_row16_col16,#T_79e1b_row16_col17,#T_79e1b_row17_col0,#T_79e1b_row17_col1,#T_79e1b_row17_col2,#T_79e1b_row17_col3,#T_79e1b_row17_col4,#T_79e1b_row17_col5,#T_79e1b_row17_col6,#T_79e1b_row17_col7,#T_79e1b_row17_col8,#T_79e1b_row17_col9,#T_79e1b_row17_col10,#T_79e1b_row17_col11,#T_79e1b_row17_col12,#T_79e1b_row17_col13,#T_79e1b_row17_col14,#T_79e1b_row17_col15,#T_79e1b_row17_col16,#T_79e1b_row17_col17,#T_79e1b_row18_col0,#T_79e1b_row18_col1,#T_79e1b_row18_col2,#T_79e1b_row18_col3,#T_79e1b_row18_col4,#T_79e1b_row18_col5,#T_79e1b_row18_col6,#T_79e1b_row18_col7,#T_79e1b_row18_col8,#T_79e1b_row18_col9,#T_79e1b_row18_col10,#T_79e1b_row18_col11,#T_79e1b_row18_col12,#T_79e1b_row18_col13,#T_79e1b_row18_col14,#T_79e1b_row18_col15,#T_79e1b_row18_col16,#T_79e1b_row18_col17,#T_79e1b_row18_col18,#T_79e1b_row19_col0,#T_79e1b_row19_col1,#T_79e1b_row19_col2,#T_79e1b_row19_col3,#T_79e1b_row19_col4,#T_79e1b_row19_col5,#T_79e1b_row19_col6,#T_79e1b_row19_col7,#T_79e1b_row19_col8,#T_79e1b_row19_col9,#T_79e1b_row19_col10,#T_79e1b_row19_col11,#T_79e1b_row19_col12,#T_79e1b_row19_col13,#T_79e1b_row19_col14,#T_79e1b_row19_col15,#T_79e1b_row19_col16,#T_79e1b_row19_col17,#T_79e1b_row20_col0,#T_79e1b_row20_col1,#T_79e1b_row20_col2,#T_79e1b_row20_col3,#T_79e1b_row20_col4,#T_79e1b_row20_col5,#T_79e1b_row20_col6,#T_79e1b_row20_col7,#T_79e1b_row20_col8,#T_79e1b_row20_col9,#T_79e1b_row20_col10,#T_79e1b_row20_col11,#T_79e1b_row20_col12,#T_79e1b_row20_col13,#T_79e1b_row20_col14,#T_79e1b_row20_col15,#T_79e1b_row20_col16,#T_79e1b_row20_col17,#T_79e1b_row21_col0,#T_79e1b_row21_col1,#T_79e1b_row21_col2,#T_79e1b_row21_col3,#T_79e1b_row21_col4,#T_79e1b_row21_col5,#T_79e1b_row21_col6,#T_79e1b_row21_col7,#T_79e1b_row21_col8,#T_79e1b_row21_col9,#T_79e1b_row21_col10,#T_79e1b_row21_col11,#T_79e1b_row21_col12,#T_79e1b_row21_col13,#T_79e1b_row21_col14,#T_79e1b_row21_col15,#T_79e1b_row21_col16,#T_79e1b_row21_col17,#T_79e1b_row22_col0,#T_79e1b_row22_col1,#T_79e1b_row22_col2,#T_79e1b_row22_col3,#T_79e1b_row22_col4,#T_79e1b_row22_col5,#T_79e1b_row22_col6,#T_79e1b_row22_col7,#T_79e1b_row22_col8,#T_79e1b_row22_col9,#T_79e1b_row22_col10,#T_79e1b_row22_col11,#T_79e1b_row22_col12,#T_79e1b_row22_col13,#T_79e1b_row22_col14,#T_79e1b_row22_col15,#T_79e1b_row22_col16,#T_79e1b_row22_col17,#T_79e1b_row23_col0,#T_79e1b_row23_col1,#T_79e1b_row23_col2,#T_79e1b_row23_col3,#T_79e1b_row23_col4,#T_79e1b_row23_col5,#T_79e1b_row23_col6,#T_79e1b_row23_col7,#T_79e1b_row23_col8,#T_79e1b_row23_col9,#T_79e1b_row23_col10,#T_79e1b_row23_col11,#T_79e1b_row23_col12,#T_79e1b_row23_col13,#T_79e1b_row23_col14,#T_79e1b_row23_col15,#T_79e1b_row23_col16,#T_79e1b_row23_col17,#T_79e1b_row24_col0,#T_79e1b_row24_col1,#T_79e1b_row24_col2,#T_79e1b_row24_col3,#T_79e1b_row24_col4,#T_79e1b_row24_col5,#T_79e1b_row24_col6,#T_79e1b_row24_col7,#T_79e1b_row24_col8,#T_79e1b_row24_col9,#T_79e1b_row24_col10,#T_79e1b_row24_col11,#T_79e1b_row24_col12,#T_79e1b_row24_col13,#T_79e1b_row24_col14,#T_79e1b_row24_col15,#T_79e1b_row24_col16,#T_79e1b_row24_col17,#T_79e1b_row25_col0,#T_79e1b_row25_col1,#T_79e1b_row25_col2,#T_79e1b_row25_col3,#T_79e1b_row25_col4,#T_79e1b_row25_col5,#T_79e1b_row25_col6,#T_79e1b_row25_col7,#T_79e1b_row25_col8,#T_79e1b_row25_col9,#T_79e1b_row25_col10,#T_79e1b_row25_col11,#T_79e1b_row25_col12,#T_79e1b_row25_col13,#T_79e1b_row25_col14,#T_79e1b_row25_col15,#T_79e1b_row25_col16,#T_79e1b_row25_col17,#T_79e1b_row26_col0,#T_79e1b_row26_col1,#T_79e1b_row26_col2,#T_79e1b_row26_col3,#T_79e1b_row26_col4,#T_79e1b_row26_col5,#T_79e1b_row26_col6,#T_79e1b_row26_col7,#T_79e1b_row26_col8,#T_79e1b_row26_col9,#T_79e1b_row26_col10,#T_79e1b_row26_col12,#T_79e1b_row26_col13,#T_79e1b_row26_col14,#T_79e1b_row26_col15,#T_79e1b_row26_col16,#T_79e1b_row26_col17,#T_79e1b_row27_col0,#T_79e1b_row27_col1,#T_79e1b_row27_col2,#T_79e1b_row27_col3,#T_79e1b_row27_col4,#T_79e1b_row27_col5,#T_79e1b_row27_col6,#T_79e1b_row27_col7,#T_79e1b_row27_col8,#T_79e1b_row27_col9,#T_79e1b_row27_col10,#T_79e1b_row27_col11,#T_79e1b_row27_col12,#T_79e1b_row27_col13,#T_79e1b_row27_col14,#T_79e1b_row27_col15,#T_79e1b_row27_col16,#T_79e1b_row27_col17,#T_79e1b_row28_col0,#T_79e1b_row28_col1,#T_79e1b_row28_col2,#T_79e1b_row28_col3,#T_79e1b_row28_col4,#T_79e1b_row28_col5,#T_79e1b_row28_col6,#T_79e1b_row28_col7,#T_79e1b_row28_col8,#T_79e1b_row28_col9,#T_79e1b_row28_col10,#T_79e1b_row28_col11,#T_79e1b_row28_col12,#T_79e1b_row28_col13,#T_79e1b_row28_col14,#T_79e1b_row28_col15,#T_79e1b_row28_col16,#T_79e1b_row28_col17,#T_79e1b_row29_col0,#T_79e1b_row29_col1,#T_79e1b_row29_col2,#T_79e1b_row29_col3,#T_79e1b_row29_col4,#T_79e1b_row29_col5,#T_79e1b_row29_col6,#T_79e1b_row29_col7,#T_79e1b_row29_col8,#T_79e1b_row29_col9,#T_79e1b_row29_col10,#T_79e1b_row29_col12,#T_79e1b_row29_col14,#T_79e1b_row29_col15,#T_79e1b_row29_col16,#T_79e1b_row29_col17,#T_79e1b_row29_col18,#T_79e1b_row30_col0,#T_79e1b_row30_col1,#T_79e1b_row30_col2,#T_79e1b_row30_col3,#T_79e1b_row30_col4,#T_79e1b_row30_col5,#T_79e1b_row30_col6,#T_79e1b_row30_col7,#T_79e1b_row30_col8,#T_79e1b_row30_col9,#T_79e1b_row30_col10,#T_79e1b_row30_col11,#T_79e1b_row30_col12,#T_79e1b_row30_col13,#T_79e1b_row30_col14,#T_79e1b_row30_col15,#T_79e1b_row30_col16,#T_79e1b_row30_col17,#T_79e1b_row31_col0,#T_79e1b_row31_col1,#T_79e1b_row31_col2,#T_79e1b_row31_col3,#T_79e1b_row31_col4,#T_79e1b_row31_col5,#T_79e1b_row31_col6,#T_79e1b_row31_col7,#T_79e1b_row31_col8,#T_79e1b_row31_col9,#T_79e1b_row31_col10,#T_79e1b_row31_col12,#T_79e1b_row31_col14,#T_79e1b_row31_col15,#T_79e1b_row31_col16,#T_79e1b_row31_col17,#T_79e1b_row31_col18{
            color:  black;
        }#T_79e1b_row0_col11,#T_79e1b_row0_col13,#T_79e1b_row1_col13,#T_79e1b_row2_col7,#T_79e1b_row2_col11,#T_79e1b_row2_col18,#T_79e1b_row5_col7,#T_79e1b_row5_col11,#T_79e1b_row5_col18,#T_79e1b_row7_col18,#T_79e1b_row8_col18,#T_79e1b_row9_col18,#T_79e1b_row10_col11,#T_79e1b_row10_col13,#T_79e1b_row11_col18,#T_79e1b_row12_col11,#T_79e1b_row12_col13,#T_79e1b_row13_col18,#T_79e1b_row14_col11,#T_79e1b_row14_col18,#T_79e1b_row15_col11,#T_79e1b_row15_col13,#T_79e1b_row16_col18,#T_79e1b_row17_col18,#T_79e1b_row19_col18,#T_79e1b_row20_col18,#T_79e1b_row21_col18,#T_79e1b_row22_col18,#T_79e1b_row23_col18,#T_79e1b_row24_col18,#T_79e1b_row25_col18,#T_79e1b_row26_col11,#T_79e1b_row26_col18,#T_79e1b_row27_col18,#T_79e1b_row28_col18,#T_79e1b_row29_col11,#T_79e1b_row29_col13,#T_79e1b_row30_col18,#T_79e1b_row31_col11,#T_79e1b_row31_col13{
            color:  red;
        }</style><table id="T_79e1b_" ><thead>    <tr>        <th class="blank level0" ></th>        <th class="col_heading level0 col0" >名称</th>        <th class="col_heading level0 col1" >行业</th>        <th class="col_heading level0 col2" >权重</th>        <th class="col_heading level0 col3" >负债率</th>        <th class="col_heading level0 col4" >应收比</th>        <th class="col_heading level0 col5" >ROE</th>        <th class="col_heading level0 col6" >利润率</th>        <th class="col_heading level0 col7" >收入增长</th>        <th class="col_heading level0 col8" >收入波动</th>        <th class="col_heading level0 col9" >盈利增长</th>        <th class="col_heading level0 col10" >盈利波动</th>        <th class="col_heading level0 col11" >FCF增长</th>        <th class="col_heading level0 col12" >FCF波动</th>        <th class="col_heading level0 col13" >DCF</th>        <th class="col_heading level0 col14" >盈利折现</th>        <th class="col_heading level0 col15" >PE</th>        <th class="col_heading level0 col16" >PEG</th>        <th class="col_heading level0 col17" >市值</th>        <th class="col_heading level0 col18" >折价率</th>    </tr>    <tr>        <th class="index_name level0" >Symbol</th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>    </tr></thead><tbody>
                <tr>
                        <th id="T_79e1b_level0_row0" class="row_heading level0 row0" >002932.SZ</th>
                        <td id="T_79e1b_row0_col0" class="data row0 col0" >明德生物</td>
                        <td id="T_79e1b_row0_col1" class="data row0 col1" >医药生物</td>
                        <td id="T_79e1b_row0_col2" class="data row0 col2" >0.08</td>
                        <td id="T_79e1b_row0_col3" class="data row0 col3" >21.85</td>
                        <td id="T_79e1b_row0_col4" class="data row0 col4" >19.76</td>
                        <td id="T_79e1b_row0_col5" class="data row0 col5" >21.76</td>
                        <td id="T_79e1b_row0_col6" class="data row0 col6" >36.58</td>
                        <td id="T_79e1b_row0_col7" class="data row0 col7" >146.32</td>
                        <td id="T_79e1b_row0_col8" class="data row0 col8" >245.19</td>
                        <td id="T_79e1b_row0_col9" class="data row0 col9" >330.21</td>
                        <td id="T_79e1b_row0_col10" class="data row0 col10" >605.52</td>
                        <td id="T_79e1b_row0_col11" class="data row0 col11" >-1108.82</td>
                        <td id="T_79e1b_row0_col12" class="data row0 col12" >2198.15</td>
                        <td id="T_79e1b_row0_col13" class="data row0 col13" >-903.76</td>
                        <td id="T_79e1b_row0_col14" class="data row0 col14" >140.19</td>
                        <td id="T_79e1b_row0_col15" class="data row0 col15" >8.11</td>
                        <td id="T_79e1b_row0_col16" class="data row0 col16" >0.02</td>
                        <td id="T_79e1b_row0_col17" class="data row0 col17" >6.56</td>
                        <td id="T_79e1b_row0_col18" class="data row0 col18" >0.00</td>
            </tr>
            <tr>
                        <th id="T_79e1b_level0_row1" class="row_heading level0 row1" >002714.SZ</th>
                        <td id="T_79e1b_row1_col0" class="data row1 col0" >牧原股份</td>
                        <td id="T_79e1b_row1_col1" class="data row1 col1" >农林牧渔</td>
                        <td id="T_79e1b_row1_col2" class="data row1 col2" >21.46</td>
                        <td id="T_79e1b_row1_col3" class="data row1 col3" >46.09</td>
                        <td id="T_79e1b_row1_col4" class="data row1 col4" >0.13</td>
                        <td id="T_79e1b_row1_col5" class="data row1 col5" >28.10</td>
                        <td id="T_79e1b_row1_col6" class="data row1 col6" >26.61</td>
                        <td id="T_79e1b_row1_col7" class="data row1 col7" >87.55</td>
                        <td id="T_79e1b_row1_col8" class="data row1 col8" >79.09</td>
                        <td id="T_79e1b_row1_col9" class="data row1 col9" >448.77</td>
                        <td id="T_79e1b_row1_col10" class="data row1 col10" >583.13</td>
                        <td id="T_79e1b_row1_col11" class="data row1 col11" >199.27</td>
                        <td id="T_79e1b_row1_col12" class="data row1 col12" >373.67</td>
                        <td id="T_79e1b_row1_col13" class="data row1 col13" >-2566.75</td>
                        <td id="T_79e1b_row1_col14" class="data row1 col14" >16539.66</td>
                        <td id="T_79e1b_row1_col15" class="data row1 col15" >11.56</td>
                        <td id="T_79e1b_row1_col16" class="data row1 col16" >0.03</td>
                        <td id="T_79e1b_row1_col17" class="data row1 col17" >350.03</td>
                        <td id="T_79e1b_row1_col18" class="data row1 col18" >0.00</td>
            </tr>
            <tr>
                        <th id="T_79e1b_level0_row2" class="row_heading level0 row2" >300418.SZ</th>
                        <td id="T_79e1b_row2_col0" class="data row2 col0" >昆仑万维</td>
                        <td id="T_79e1b_row2_col1" class="data row2 col1" >传媒</td>
                        <td id="T_79e1b_row2_col2" class="data row2 col2" >1.15</td>
                        <td id="T_79e1b_row2_col3" class="data row2 col3" >26.89</td>
                        <td id="T_79e1b_row2_col4" class="data row2 col4" >13.41</td>
                        <td id="T_79e1b_row2_col5" class="data row2 col5" >27.55</td>
                        <td id="T_79e1b_row2_col6" class="data row2 col6" >68.64</td>
                        <td id="T_79e1b_row2_col7" class="data row2 col7" >-6.17</td>
                        <td id="T_79e1b_row2_col8" class="data row2 col8" >16.93</td>
                        <td id="T_79e1b_row2_col9" class="data row2 col9" >105.00</td>
                        <td id="T_79e1b_row2_col10" class="data row2 col10" >156.97</td>
                        <td id="T_79e1b_row2_col11" class="data row2 col11" >-5.39</td>
                        <td id="T_79e1b_row2_col12" class="data row2 col12" >42.73</td>
                        <td id="T_79e1b_row2_col13" class="data row2 col13" >11.90</td>
                        <td id="T_79e1b_row2_col14" class="data row2 col14" >204.88</td>
                        <td id="T_79e1b_row2_col15" class="data row2 col15" >4.53</td>
                        <td id="T_79e1b_row2_col16" class="data row2 col16" >0.04</td>
                        <td id="T_79e1b_row2_col17" class="data row2 col17" >21.79</td>
                        <td id="T_79e1b_row2_col18" class="data row2 col18" >-83.12</td>
            </tr>
            <tr>
                        <th id="T_79e1b_level0_row3" class="row_heading level0 row3" >000672.SZ</th>
                        <td id="T_79e1b_row3_col0" class="data row3 col0" >上峰水泥</td>
                        <td id="T_79e1b_row3_col1" class="data row3 col1" >建筑材料</td>
                        <td id="T_79e1b_row3_col2" class="data row3 col2" >1.17</td>
                        <td id="T_79e1b_row3_col3" class="data row3 col3" >36.62</td>
                        <td id="T_79e1b_row3_col4" class="data row3 col4" >8.81</td>
                        <td id="T_79e1b_row3_col5" class="data row3 col5" >37.68</td>
                        <td id="T_79e1b_row3_col6" class="data row3 col6" >26.99</td>
                        <td id="T_79e1b_row3_col7" class="data row3 col7" >14.05</td>
                        <td id="T_79e1b_row3_col8" class="data row3 col8" >26.51</td>
                        <td id="T_79e1b_row3_col9" class="data row3 col9" >43.73</td>
                        <td id="T_79e1b_row3_col10" class="data row3 col10" >51.12</td>
                        <td id="T_79e1b_row3_col11" class="data row3 col11" >34.90</td>
                        <td id="T_79e1b_row3_col12" class="data row3 col12" >81.40</td>
                        <td id="T_79e1b_row3_col13" class="data row3 col13" >47.11</td>
                        <td id="T_79e1b_row3_col14" class="data row3 col14" >58.53</td>
                        <td id="T_79e1b_row3_col15" class="data row3 col15" >7.83</td>
                        <td id="T_79e1b_row3_col16" class="data row3 col16" >0.18</td>
                        <td id="T_79e1b_row3_col17" class="data row3 col17" >16.01</td>
                        <td id="T_79e1b_row3_col18" class="data row3 col18" >66.01</td>
            </tr>
            <tr>
                        <th id="T_79e1b_level0_row4" class="row_heading level0 row4" >600585.SS</th>
                        <td id="T_79e1b_row4_col0" class="data row4 col0" >海螺水泥</td>
                        <td id="T_79e1b_row4_col1" class="data row4 col1" >建筑材料</td>
                        <td id="T_79e1b_row4_col2" class="data row4 col2" >19.68</td>
                        <td id="T_79e1b_row4_col3" class="data row4 col3" >16.30</td>
                        <td id="T_79e1b_row4_col4" class="data row4 col4" >7.17</td>
                        <td id="T_79e1b_row4_col5" class="data row4 col5" >22.59</td>
                        <td id="T_79e1b_row4_col6" class="data row4 col6" >21.40</td>
                        <td id="T_79e1b_row4_col7" class="data row4 col7" >35.01</td>
                        <td id="T_79e1b_row4_col8" class="data row4 col8" >31.14</td>
                        <td id="T_79e1b_row4_col9" class="data row4 col9" >35.10</td>
                        <td id="T_79e1b_row4_col10" class="data row4 col10" >46.03</td>
                        <td id="T_79e1b_row4_col11" class="data row4 col11" >36.04</td>
                        <td id="T_79e1b_row4_col12" class="data row4 col12" >80.90</td>
                        <td id="T_79e1b_row4_col13" class="data row4 col13" >768.24</td>
                        <td id="T_79e1b_row4_col14" class="data row4 col14" >847.14</td>
                        <td id="T_79e1b_row4_col15" class="data row4 col15" >7.11</td>
                        <td id="T_79e1b_row4_col16" class="data row4 col16" >0.20</td>
                        <td id="T_79e1b_row4_col17" class="data row4 col17" >256.22</td>
                        <td id="T_79e1b_row4_col18" class="data row4 col18" >66.65</td>
            </tr>
            <tr>
                        <th id="T_79e1b_level0_row5" class="row_heading level0 row5" >600738.SS</th>
                        <td id="T_79e1b_row5_col0" class="data row5 col0" >丽尚国潮</td>
                        <td id="T_79e1b_row5_col1" class="data row5 col1" >商业贸易</td>
                        <td id="T_79e1b_row5_col2" class="data row5 col2" >0.82</td>
                        <td id="T_79e1b_row5_col3" class="data row5 col3" >49.64</td>
                        <td id="T_79e1b_row5_col4" class="data row5 col4" >1.56</td>
                        <td id="T_79e1b_row5_col5" class="data row5 col5" >20.19</td>
                        <td id="T_79e1b_row5_col6" class="data row5 col6" >40.48</td>
                        <td id="T_79e1b_row5_col7" class="data row5 col7" >-5.90</td>
                        <td id="T_79e1b_row5_col8" class="data row5 col8" >57.73</td>
                        <td id="T_79e1b_row5_col9" class="data row5 col9" >285.05</td>
                        <td id="T_79e1b_row5_col10" class="data row5 col10" >623.06</td>
                        <td id="T_79e1b_row5_col11" class="data row5 col11" >-147.69</td>
                        <td id="T_79e1b_row5_col12" class="data row5 col12" >206.14</td>
                        <td id="T_79e1b_row5_col13" class="data row5 col13" >0.00</td>
                        <td id="T_79e1b_row5_col14" class="data row5 col14" >326.09</td>
                        <td id="T_79e1b_row5_col15" class="data row5 col15" >69.37</td>
                        <td id="T_79e1b_row5_col16" class="data row5 col16" >0.24</td>
                        <td id="T_79e1b_row5_col17" class="data row5 col17" >6.79</td>
                        <td id="T_79e1b_row5_col18" class="data row5 col18" >-262396.07</td>
            </tr>
            <tr>
                        <th id="T_79e1b_level0_row6" class="row_heading level0 row6" >603360.SS</th>
                        <td id="T_79e1b_row6_col0" class="data row6 col0" >百傲化学</td>
                        <td id="T_79e1b_row6_col1" class="data row6 col1" >化工</td>
                        <td id="T_79e1b_row6_col2" class="data row6 col2" >0.07</td>
                        <td id="T_79e1b_row6_col3" class="data row6 col3" >30.87</td>
                        <td id="T_79e1b_row6_col4" class="data row6 col4" >18.07</td>
                        <td id="T_79e1b_row6_col5" class="data row6 col5" >21.22</td>
                        <td id="T_79e1b_row6_col6" class="data row6 col6" >29.17</td>
                        <td id="T_79e1b_row6_col7" class="data row6 col7" >26.58</td>
                        <td id="T_79e1b_row6_col8" class="data row6 col8" >39.60</td>
                        <td id="T_79e1b_row6_col9" class="data row6 col9" >42.80</td>
                        <td id="T_79e1b_row6_col10" class="data row6 col10" >69.54</td>
                        <td id="T_79e1b_row6_col11" class="data row6 col11" >73.49</td>
                        <td id="T_79e1b_row6_col12" class="data row6 col12" >178.99</td>
                        <td id="T_79e1b_row6_col13" class="data row6 col13" >5.79</td>
                        <td id="T_79e1b_row6_col14" class="data row6 col14" >6.72</td>
                        <td id="T_79e1b_row6_col15" class="data row6 col15" >20.04</td>
                        <td id="T_79e1b_row6_col16" class="data row6 col16" >0.47</td>
                        <td id="T_79e1b_row6_col17" class="data row6 col17" >3.68</td>
                        <td id="T_79e1b_row6_col18" class="data row6 col18" >36.47</td>
            </tr>
            <tr>
                        <th id="T_79e1b_level0_row7" class="row_heading level0 row7" >300771.SZ</th>
                        <td id="T_79e1b_row7_col0" class="data row7 col0" >智莱科技</td>
                        <td id="T_79e1b_row7_col1" class="data row7 col1" >计算机</td>
                        <td id="T_79e1b_row7_col2" class="data row7 col2" >0.12</td>
                        <td id="T_79e1b_row7_col3" class="data row7 col3" >12.01</td>
                        <td id="T_79e1b_row7_col4" class="data row7 col4" >8.40</td>
                        <td id="T_79e1b_row7_col5" class="data row7 col5" >23.16</td>
                        <td id="T_79e1b_row7_col6" class="data row7 col6" >23.88</td>
                        <td id="T_79e1b_row7_col7" class="data row7 col7" >26.16</td>
                        <td id="T_79e1b_row7_col8" class="data row7 col8" >32.91</td>
                        <td id="T_79e1b_row7_col9" class="data row7 col9" >34.01</td>
                        <td id="T_79e1b_row7_col10" class="data row7 col10" >49.62</td>
                        <td id="T_79e1b_row7_col11" class="data row7 col11" >17.60</td>
                        <td id="T_79e1b_row7_col12" class="data row7 col12" >38.43</td>
                        <td id="T_79e1b_row7_col13" class="data row7 col13" >2.65</td>
                        <td id="T_79e1b_row7_col14" class="data row7 col14" >6.17</td>
                        <td id="T_79e1b_row7_col15" class="data row7 col15" >17.55</td>
                        <td id="T_79e1b_row7_col16" class="data row7 col16" >0.52</td>
                        <td id="T_79e1b_row7_col17" class="data row7 col17" >3.73</td>
                        <td id="T_79e1b_row7_col18" class="data row7 col18" >-40.60</td>
            </tr>
            <tr>
                        <th id="T_79e1b_level0_row8" class="row_heading level0 row8" >603160.SS</th>
                        <td id="T_79e1b_row8_col0" class="data row8 col0" >汇顶科技</td>
                        <td id="T_79e1b_row8_col1" class="data row8 col1" >电子</td>
                        <td id="T_79e1b_row8_col2" class="data row8 col2" >0.90</td>
                        <td id="T_79e1b_row8_col3" class="data row8 col3" >18.72</td>
                        <td id="T_79e1b_row8_col4" class="data row8 col4" >11.10</td>
                        <td id="T_79e1b_row8_col5" class="data row8 col5" >25.04</td>
                        <td id="T_79e1b_row8_col6" class="data row8 col6" >26.16</td>
                        <td id="T_79e1b_row8_col7" class="data row8 col7" >26.11</td>
                        <td id="T_79e1b_row8_col8" class="data row8 col8" >41.45</td>
                        <td id="T_79e1b_row8_col9" class="data row8 col9" >55.80</td>
                        <td id="T_79e1b_row8_col10" class="data row8 col10" >135.49</td>
                        <td id="T_79e1b_row8_col11" class="data row8 col11" >18.94</td>
                        <td id="T_79e1b_row8_col12" class="data row8 col12" >140.73</td>
                        <td id="T_79e1b_row8_col13" class="data row8 col13" >21.96</td>
                        <td id="T_79e1b_row8_col14" class="data row8 col14" >62.48</td>
                        <td id="T_79e1b_row8_col15" class="data row8 col15" >36.88</td>
                        <td id="T_79e1b_row8_col16" class="data row8 col16" >0.66</td>
                        <td id="T_79e1b_row8_col17" class="data row8 col17" >59.42</td>
                        <td id="T_79e1b_row8_col18" class="data row8 col18" >-170.64</td>
            </tr>
            <tr>
                        <th id="T_79e1b_level0_row9" class="row_heading level0 row9" >300033.SZ</th>
                        <td id="T_79e1b_row9_col0" class="data row9 col0" >同花顺</td>
                        <td id="T_79e1b_row9_col1" class="data row9 col1" >计算机</td>
                        <td id="T_79e1b_row9_col2" class="data row9 col2" >1.48</td>
                        <td id="T_79e1b_row9_col3" class="data row9 col3" >26.99</td>
                        <td id="T_79e1b_row9_col4" class="data row9 col4" >2.59</td>
                        <td id="T_79e1b_row9_col5" class="data row9 col5" >24.34</td>
                        <td id="T_79e1b_row9_col6" class="data row9 col6" >52.33</td>
                        <td id="T_79e1b_row9_col7" class="data row9 col7" >29.08</td>
                        <td id="T_79e1b_row9_col8" class="data row9 col8" >32.56</td>
                        <td id="T_79e1b_row9_col9" class="data row9 col9" >40.34</td>
                        <td id="T_79e1b_row9_col10" class="data row9 col10" >52.36</td>
                        <td id="T_79e1b_row9_col11" class="data row9 col11" >63.18</td>
                        <td id="T_79e1b_row9_col12" class="data row9 col12" >90.96</td>
                        <td id="T_79e1b_row9_col13" class="data row9 col13" >47.92</td>
                        <td id="T_79e1b_row9_col14" class="data row9 col14" >32.87</td>
                        <td id="T_79e1b_row9_col15" class="data row9 col15" >35.06</td>
                        <td id="T_79e1b_row9_col16" class="data row9 col16" >0.87</td>
                        <td id="T_79e1b_row9_col17" class="data row9 col17" >61.94</td>
                        <td id="T_79e1b_row9_col18" class="data row9 col18" >-29.26</td>
            </tr>
            <tr>
                        <th id="T_79e1b_level0_row10" class="row_heading level0 row10" >300782.SZ</th>
                        <td id="T_79e1b_row10_col0" class="data row10 col0" >卓胜微</td>
                        <td id="T_79e1b_row10_col1" class="data row10 col1" >电子</td>
                        <td id="T_79e1b_row10_col2" class="data row10 col2" >2.77</td>
                        <td id="T_79e1b_row10_col3" class="data row10 col3" >14.18</td>
                        <td id="T_79e1b_row10_col4" class="data row10 col4" >13.48</td>
                        <td id="T_79e1b_row10_col5" class="data row10 col5" >39.60</td>
                        <td id="T_79e1b_row10_col6" class="data row10 col6" >32.25</td>
                        <td id="T_79e1b_row10_col7" class="data row10 col7" >83.09</td>
                        <td id="T_79e1b_row10_col8" class="data row10 col8" >87.66</td>
                        <td id="T_79e1b_row10_col9" class="data row10 col9" >105.87</td>
                        <td id="T_79e1b_row10_col10" class="data row10 col10" >105.71</td>
                        <td id="T_79e1b_row10_col11" class="data row10 col11" >-780.68</td>
                        <td id="T_79e1b_row10_col12" class="data row10 col12" >1228.39</td>
                        <td id="T_79e1b_row10_col13" class="data row10 col13" >-865.91</td>
                        <td id="T_79e1b_row10_col14" class="data row10 col14" >47.57</td>
                        <td id="T_79e1b_row10_col15" class="data row10 col15" >97.95</td>
                        <td id="T_79e1b_row10_col16" class="data row10 col16" >0.93</td>
                        <td id="T_79e1b_row10_col17" class="data row10 col17" >138.43</td>
                        <td id="T_79e1b_row10_col18" class="data row10 col18" >0.00</td>
            </tr>
            <tr>
                        <th id="T_79e1b_level0_row11" class="row_heading level0 row11" >002677.SZ</th>
                        <td id="T_79e1b_row11_col0" class="data row11 col0" >浙江美大</td>
                        <td id="T_79e1b_row11_col1" class="data row11 col1" >家用电器</td>
                        <td id="T_79e1b_row11_col2" class="data row11 col2" >0.45</td>
                        <td id="T_79e1b_row11_col3" class="data row11 col3" >21.80</td>
                        <td id="T_79e1b_row11_col4" class="data row11 col4" >1.94</td>
                        <td id="T_79e1b_row11_col5" class="data row11 col5" >28.29</td>
                        <td id="T_79e1b_row11_col6" class="data row11 col6" >28.67</td>
                        <td id="T_79e1b_row11_col7" class="data row11 col7" >20.62</td>
                        <td id="T_79e1b_row11_col8" class="data row11 col8" >15.69</td>
                        <td id="T_79e1b_row11_col9" class="data row11 col9" >21.24</td>
                        <td id="T_79e1b_row11_col10" class="data row11 col10" >2.82</td>
                        <td id="T_79e1b_row11_col11" class="data row11 col11" >44.23</td>
                        <td id="T_79e1b_row11_col12" class="data row11 col12" >89.38</td>
                        <td id="T_79e1b_row11_col13" class="data row11 col13" >11.82</td>
                        <td id="T_79e1b_row11_col14" class="data row11 col14" >9.18</td>
                        <td id="T_79e1b_row11_col15" class="data row11 col15" >20.12</td>
                        <td id="T_79e1b_row11_col16" class="data row11 col16" >0.95</td>
                        <td id="T_79e1b_row11_col17" class="data row11 col17" >12.55</td>
                        <td id="T_79e1b_row11_col18" class="data row11 col18" >-6.23</td>
            </tr>
            <tr>
                        <th id="T_79e1b_level0_row12" class="row_heading level0 row12" >600989.SS</th>
                        <td id="T_79e1b_row12_col0" class="data row12 col0" >宝丰能源</td>
                        <td id="T_79e1b_row12_col1" class="data row12 col1" >化工</td>
                        <td id="T_79e1b_row12_col2" class="data row12 col2" >1.31</td>
                        <td id="T_79e1b_row12_col3" class="data row12 col3" >32.03</td>
                        <td id="T_79e1b_row12_col4" class="data row12 col4" >3.64</td>
                        <td id="T_79e1b_row12_col5" class="data row12 col5" >21.66</td>
                        <td id="T_79e1b_row12_col6" class="data row12 col6" >27.28</td>
                        <td id="T_79e1b_row12_col7" class="data row12 col7" >9.15</td>
                        <td id="T_79e1b_row12_col8" class="data row12 col8" >7.22</td>
                        <td id="T_79e1b_row12_col9" class="data row12 col9" >16.96</td>
                        <td id="T_79e1b_row12_col10" class="data row12 col10" >12.43</td>
                        <td id="T_79e1b_row12_col11" class="data row12 col11" >-184.25</td>
                        <td id="T_79e1b_row12_col12" class="data row12 col12" >173.78</td>
                        <td id="T_79e1b_row12_col13" class="data row12 col13" >-9.17</td>
                        <td id="T_79e1b_row12_col14" class="data row12 col14" >74.03</td>
                        <td id="T_79e1b_row12_col15" class="data row12 col15" >19.01</td>
                        <td id="T_79e1b_row12_col16" class="data row12 col16" >1.12</td>
                        <td id="T_79e1b_row12_col17" class="data row12 col17" >105.09</td>
                        <td id="T_79e1b_row12_col18" class="data row12 col18" >0.00</td>
            </tr>
            <tr>
                        <th id="T_79e1b_level0_row13" class="row_heading level0 row13" >600570.SS</th>
                        <td id="T_79e1b_row13_col0" class="data row13 col0" >恒生电子</td>
                        <td id="T_79e1b_row13_col1" class="data row13 col1" >计算机</td>
                        <td id="T_79e1b_row13_col2" class="data row13 col2" >5.16</td>
                        <td id="T_79e1b_row13_col3" class="data row13 col3" >49.48</td>
                        <td id="T_79e1b_row13_col4" class="data row13 col4" >14.02</td>
                        <td id="T_79e1b_row13_col5" class="data row13 col5" >24.06</td>
                        <td id="T_79e1b_row13_col6" class="data row13 col6" >26.42</td>
                        <td id="T_79e1b_row13_col7" class="data row13 col7" >16.27</td>
                        <td id="T_79e1b_row13_col8" class="data row13 col8" >7.59</td>
                        <td id="T_79e1b_row13_col9" class="data row13 col9" >49.90</td>
                        <td id="T_79e1b_row13_col10" class="data row13 col10" >64.01</td>
                        <td id="T_79e1b_row13_col11" class="data row13 col11" >10.32</td>
                        <td id="T_79e1b_row13_col12" class="data row13 col12" >20.60</td>
                        <td id="T_79e1b_row13_col13" class="data row13 col13" >13.02</td>
                        <td id="T_79e1b_row13_col14" class="data row13 col14" >38.43</td>
                        <td id="T_79e1b_row13_col15" class="data row13 col15" >60.65</td>
                        <td id="T_79e1b_row13_col16" class="data row13 col16" >1.22</td>
                        <td id="T_79e1b_row13_col17" class="data row13 col17" >93.11</td>
                        <td id="T_79e1b_row13_col18" class="data row13 col18" >-615.42</td>
            </tr>
            <tr>
                        <th id="T_79e1b_level0_row14" class="row_heading level0 row14" >002901.SZ</th>
                        <td id="T_79e1b_row14_col0" class="data row14 col0" >大博医疗</td>
                        <td id="T_79e1b_row14_col1" class="data row14 col1" >医药生物</td>
                        <td id="T_79e1b_row14_col2" class="data row14 col2" >0.08</td>
                        <td id="T_79e1b_row14_col3" class="data row14 col3" >21.68</td>
                        <td id="T_79e1b_row14_col4" class="data row14 col4" >19.30</td>
                        <td id="T_79e1b_row14_col5" class="data row14 col5" >28.78</td>
                        <td id="T_79e1b_row14_col6" class="data row14 col6" >45.57</td>
                        <td id="T_79e1b_row14_col7" class="data row14 col7" >40.40</td>
                        <td id="T_79e1b_row14_col8" class="data row14 col8" >19.39</td>
                        <td id="T_79e1b_row14_col9" class="data row14 col9" >28.58</td>
                        <td id="T_79e1b_row14_col10" class="data row14 col10" >5.35</td>
                        <td id="T_79e1b_row14_col11" class="data row14 col11" >-2.48</td>
                        <td id="T_79e1b_row14_col12" class="data row14 col12" >56.39</td>
                        <td id="T_79e1b_row14_col13" class="data row14 col13" >2.36</td>
                        <td id="T_79e1b_row14_col14" class="data row14 col14" >8.70</td>
                        <td id="T_79e1b_row14_col15" class="data row14 col15" >46.60</td>
                        <td id="T_79e1b_row14_col16" class="data row14 col16" >1.63</td>
                        <td id="T_79e1b_row14_col17" class="data row14 col17" >30.15</td>
                        <td id="T_79e1b_row14_col18" class="data row14 col18" >-1176.12</td>
            </tr>
            <tr>
                        <th id="T_79e1b_level0_row15" class="row_heading level0 row15" >002507.SZ</th>
                        <td id="T_79e1b_row15_col0" class="data row15 col0" >涪陵榨菜</td>
                        <td id="T_79e1b_row15_col1" class="data row15 col1" >食品饮料</td>
                        <td id="T_79e1b_row15_col2" class="data row15 col2" >0.58</td>
                        <td id="T_79e1b_row15_col3" class="data row15 col3" >14.06</td>
                        <td id="T_79e1b_row15_col4" class="data row15 col4" >0.49</td>
                        <td id="T_79e1b_row15_col5" class="data row15 col5" >23.03</td>
                        <td id="T_79e1b_row15_col6" class="data row15 col6" >31.60</td>
                        <td id="T_79e1b_row15_col7" class="data row15 col7" >14.70</td>
                        <td id="T_79e1b_row15_col8" class="data row15 col8" >11.00</td>
                        <td id="T_79e1b_row15_col9" class="data row15 col9" >26.55</td>
                        <td id="T_79e1b_row15_col10" class="data row15 col10" >34.20</td>
                        <td id="T_79e1b_row15_col11" class="data row15 col11" >-290.57</td>
                        <td id="T_79e1b_row15_col12" class="data row15 col12" >344.89</td>
                        <td id="T_79e1b_row15_col13" class="data row15 col13" >-24.51</td>
                        <td id="T_79e1b_row15_col14" class="data row15 col14" >15.11</td>
                        <td id="T_79e1b_row15_col15" class="data row15 col15" >43.71</td>
                        <td id="T_79e1b_row15_col16" class="data row15 col16" >1.65</td>
                        <td id="T_79e1b_row15_col17" class="data row15 col17" >35.61</td>
                        <td id="T_79e1b_row15_col18" class="data row15 col18" >0.00</td>
            </tr>
            <tr>
                        <th id="T_79e1b_level0_row16" class="row_heading level0 row16" >300529.SZ</th>
                        <td id="T_79e1b_row16_col0" class="data row16 col0" >健帆生物</td>
                        <td id="T_79e1b_row16_col1" class="data row16 col1" >医药生物</td>
                        <td id="T_79e1b_row16_col2" class="data row16 col2" >0.96</td>
                        <td id="T_79e1b_row16_col3" class="data row16 col3" >11.91</td>
                        <td id="T_79e1b_row16_col4" class="data row16 col4" >11.56</td>
                        <td id="T_79e1b_row16_col5" class="data row16 col5" >25.48</td>
                        <td id="T_79e1b_row16_col6" class="data row16 col6" >40.97</td>
                        <td id="T_79e1b_row16_col7" class="data row16 col7" >39.53</td>
                        <td id="T_79e1b_row16_col8" class="data row16 col8" >2.86</td>
                        <td id="T_79e1b_row16_col9" class="data row16 col9" >45.56</td>
                        <td id="T_79e1b_row16_col10" class="data row16 col10" >6.74</td>
                        <td id="T_79e1b_row16_col11" class="data row16 col11" >68.14</td>
                        <td id="T_79e1b_row16_col12" class="data row16 col12" >3.67</td>
                        <td id="T_79e1b_row16_col13" class="data row16 col13" >18.05</td>
                        <td id="T_79e1b_row16_col14" class="data row16 col14" >19.54</td>
                        <td id="T_79e1b_row16_col15" class="data row16 col15" >75.24</td>
                        <td id="T_79e1b_row16_col16" class="data row16 col16" >1.65</td>
                        <td id="T_79e1b_row16_col17" class="data row16 col17" >73.29</td>
                        <td id="T_79e1b_row16_col18" class="data row16 col18" >-305.98</td>
            </tr>
            <tr>
                        <th id="T_79e1b_level0_row17" class="row_heading level0 row17" >300628.SZ</th>
                        <td id="T_79e1b_row17_col0" class="data row17 col0" >亿联网络</td>
                        <td id="T_79e1b_row17_col1" class="data row17 col1" >通信</td>
                        <td id="T_79e1b_row17_col2" class="data row17 col2" >3.77</td>
                        <td id="T_79e1b_row17_col3" class="data row17 col3" >9.97</td>
                        <td id="T_79e1b_row17_col4" class="data row17 col4" >18.77</td>
                        <td id="T_79e1b_row17_col5" class="data row17 col5" >24.39</td>
                        <td id="T_79e1b_row17_col6" class="data row17 col6" >46.38</td>
                        <td id="T_79e1b_row17_col7" class="data row17 col7" >26.19</td>
                        <td id="T_79e1b_row17_col8" class="data row17 col8" >13.83</td>
                        <td id="T_79e1b_row17_col9" class="data row17 col9" >30.91</td>
                        <td id="T_79e1b_row17_col10" class="data row17 col10" >23.73</td>
                        <td id="T_79e1b_row17_col11" class="data row17 col11" >28.68</td>
                        <td id="T_79e1b_row17_col12" class="data row17 col12" >12.49</td>
                        <td id="T_79e1b_row17_col13" class="data row17 col13" >18.85</td>
                        <td id="T_79e1b_row17_col14" class="data row17 col14" >26.78</td>
                        <td id="T_79e1b_row17_col15" class="data row17 col15" >53.24</td>
                        <td id="T_79e1b_row17_col16" class="data row17 col16" >1.72</td>
                        <td id="T_79e1b_row17_col17" class="data row17 col17" >68.53</td>
                        <td id="T_79e1b_row17_col18" class="data row17 col18" >-263.46</td>
            </tr>
            <tr>
                        <th id="T_79e1b_level0_row18" class="row_heading level0 row18" >603444.SS</th>
                        <td id="T_79e1b_row18_col0" class="data row18 col0" >吉比特</td>
                        <td id="T_79e1b_row18_col1" class="data row18 col1" >传媒</td>
                        <td id="T_79e1b_row18_col2" class="data row18 col2" >2.74</td>
                        <td id="T_79e1b_row18_col3" class="data row18 col3" >21.16</td>
                        <td id="T_79e1b_row18_col4" class="data row18 col4" >10.85</td>
                        <td id="T_79e1b_row18_col5" class="data row18 col5" >26.31</td>
                        <td id="T_79e1b_row18_col6" class="data row18 col6" >40.37</td>
                        <td id="T_79e1b_row18_col7" class="data row18 col7" >24.14</td>
                        <td id="T_79e1b_row18_col8" class="data row18 col8" >8.35</td>
                        <td id="T_79e1b_row18_col9" class="data row18 col9" >19.94</td>
                        <td id="T_79e1b_row18_col10" class="data row18 col10" >8.77</td>
                        <td id="T_79e1b_row18_col11" class="data row18 col11" >66.50</td>
                        <td id="T_79e1b_row18_col12" class="data row18 col12" >112.96</td>
                        <td id="T_79e1b_row18_col13" class="data row18 col13" >48.73</td>
                        <td id="T_79e1b_row18_col14" class="data row18 col14" >16.84</td>
                        <td id="T_79e1b_row18_col15" class="data row18 col15" >34.59</td>
                        <td id="T_79e1b_row18_col16" class="data row18 col16" >1.73</td>
                        <td id="T_79e1b_row18_col17" class="data row18 col17" >37.69</td>
                        <td id="T_79e1b_row18_col18" class="data row18 col18" >22.66</td>
            </tr>
            <tr>
                        <th id="T_79e1b_level0_row19" class="row_heading level0 row19" >600779.SS</th>
                        <td id="T_79e1b_row19_col0" class="data row19 col0" >水井坊</td>
                        <td id="T_79e1b_row19_col1" class="data row19 col1" >食品饮料</td>
                        <td id="T_79e1b_row19_col2" class="data row19 col2" >1.17</td>
                        <td id="T_79e1b_row19_col3" class="data row19 col3" >51.09</td>
                        <td id="T_79e1b_row19_col4" class="data row19 col4" >0.40</td>
                        <td id="T_79e1b_row19_col5" class="data row19 col5" >31.45</td>
                        <td id="T_79e1b_row19_col6" class="data row19 col6" >21.15</td>
                        <td id="T_79e1b_row19_col7" class="data row19 col7" >16.03</td>
                        <td id="T_79e1b_row19_col8" class="data row19 col8" >27.60</td>
                        <td id="T_79e1b_row19_col9" class="data row19 col9" >34.61</td>
                        <td id="T_79e1b_row19_col10" class="data row19 col10" >42.67</td>
                        <td id="T_79e1b_row19_col11" class="data row19 col11" >23.72</td>
                        <td id="T_79e1b_row19_col12" class="data row19 col12" >83.94</td>
                        <td id="T_79e1b_row19_col13" class="data row19 col13" >12.13</td>
                        <td id="T_79e1b_row19_col14" class="data row19 col14" >18.12</td>
                        <td id="T_79e1b_row19_col15" class="data row19 col15" >64.50</td>
                        <td id="T_79e1b_row19_col16" class="data row19 col16" >1.86</td>
                        <td id="T_79e1b_row19_col17" class="data row19 col17" >61.91</td>
                        <td id="T_79e1b_row19_col18" class="data row19 col18" >-410.18</td>
            </tr>
            <tr>
                        <th id="T_79e1b_level0_row20" class="row_heading level0 row20" >002833.SZ</th>
                        <td id="T_79e1b_row20_col0" class="data row20 col0" >弘亚数控</td>
                        <td id="T_79e1b_row20_col1" class="data row20 col1" >机械设备</td>
                        <td id="T_79e1b_row20_col2" class="data row20 col2" >0.40</td>
                        <td id="T_79e1b_row20_col3" class="data row20 col3" >26.31</td>
                        <td id="T_79e1b_row20_col4" class="data row20 col4" >7.33</td>
                        <td id="T_79e1b_row20_col5" class="data row20 col5" >22.78</td>
                        <td id="T_79e1b_row20_col6" class="data row20 col6" >23.79</td>
                        <td id="T_79e1b_row20_col7" class="data row20 col7" >28.09</td>
                        <td id="T_79e1b_row20_col8" class="data row20 col8" >17.93</td>
                        <td id="T_79e1b_row20_col9" class="data row20 col9" >14.35</td>
                        <td id="T_79e1b_row20_col10" class="data row20 col10" >1.54</td>
                        <td id="T_79e1b_row20_col11" class="data row20 col11" >6.66</td>
                        <td id="T_79e1b_row20_col12" class="data row20 col12" >10.44</td>
                        <td id="T_79e1b_row20_col13" class="data row20 col13" >3.53</td>
                        <td id="T_79e1b_row20_col14" class="data row20 col14" >5.36</td>
                        <td id="T_79e1b_row20_col15" class="data row20 col15" >26.98</td>
                        <td id="T_79e1b_row20_col16" class="data row20 col16" >1.88</td>
                        <td id="T_79e1b_row20_col17" class="data row20 col17" >11.24</td>
                        <td id="T_79e1b_row20_col18" class="data row20 col18" >-218.13</td>
            </tr>
            <tr>
                        <th id="T_79e1b_level0_row21" class="row_heading level0 row21" >603195.SS</th>
                        <td id="T_79e1b_row21_col0" class="data row21 col0" >公牛集团</td>
                        <td id="T_79e1b_row21_col1" class="data row21 col1" >轻工制造</td>
                        <td id="T_79e1b_row21_col2" class="data row21 col2" >3.06</td>
                        <td id="T_79e1b_row21_col3" class="data row21 col3" >26.53</td>
                        <td id="T_79e1b_row21_col4" class="data row21 col4" >3.09</td>
                        <td id="T_79e1b_row21_col5" class="data row21 col5" >50.07</td>
                        <td id="T_79e1b_row21_col6" class="data row21 col6" >20.55</td>
                        <td id="T_79e1b_row21_col7" class="data row21 col7" >12.02</td>
                        <td id="T_79e1b_row21_col8" class="data row21 col8" >12.60</td>
                        <td id="T_79e1b_row21_col9" class="data row21 col9" >22.75</td>
                        <td id="T_79e1b_row21_col10" class="data row21 col10" >19.65</td>
                        <td id="T_79e1b_row21_col11" class="data row21 col11" >61.00</td>
                        <td id="T_79e1b_row21_col12" class="data row21 col12" >30.19</td>
                        <td id="T_79e1b_row21_col13" class="data row21 col13" >86.27</td>
                        <td id="T_79e1b_row21_col14" class="data row21 col14" >42.75</td>
                        <td id="T_79e1b_row21_col15" class="data row21 col15" >43.67</td>
                        <td id="T_79e1b_row21_col16" class="data row21 col16" >1.92</td>
                        <td id="T_79e1b_row21_col17" class="data row21 col17" >120.10</td>
                        <td id="T_79e1b_row21_col18" class="data row21 col18" >-39.22</td>
            </tr>
            <tr>
                        <th id="T_79e1b_level0_row22" class="row_heading level0 row22" >300760.SZ</th>
                        <td id="T_79e1b_row22_col0" class="data row22 col0" >迈瑞医疗</td>
                        <td id="T_79e1b_row22_col1" class="data row22 col1" >医药生物</td>
                        <td id="T_79e1b_row22_col2" class="data row22 col2" >3.26</td>
                        <td id="T_79e1b_row22_col3" class="data row22 col3" >30.07</td>
                        <td id="T_79e1b_row22_col4" class="data row22 col4" >8.72</td>
                        <td id="T_79e1b_row22_col5" class="data row22 col5" >29.36</td>
                        <td id="T_79e1b_row22_col6" class="data row22 col6" >27.54</td>
                        <td id="T_79e1b_row22_col7" class="data row22 col7" >23.49</td>
                        <td id="T_79e1b_row22_col8" class="data row22 col8" >3.33</td>
                        <td id="T_79e1b_row22_col9" class="data row22 col9" >37.24</td>
                        <td id="T_79e1b_row22_col10" class="data row22 col10" >9.89</td>
                        <td id="T_79e1b_row22_col11" class="data row22 col11" >43.62</td>
                        <td id="T_79e1b_row22_col12" class="data row22 col12" >44.39</td>
                        <td id="T_79e1b_row22_col13" class="data row22 col13" >157.19</td>
                        <td id="T_79e1b_row22_col14" class="data row22 col14" >136.70</td>
                        <td id="T_79e1b_row22_col15" class="data row22 col15" >83.18</td>
                        <td id="T_79e1b_row22_col16" class="data row22 col16" >2.23</td>
                        <td id="T_79e1b_row22_col17" class="data row22 col17" >587.18</td>
                        <td id="T_79e1b_row22_col18" class="data row22 col18" >-273.55</td>
            </tr>
            <tr>
                        <th id="T_79e1b_level0_row23" class="row_heading level0 row23" >300832.SZ</th>
                        <td id="T_79e1b_row23_col0" class="data row23 col0" >新产业</td>
                        <td id="T_79e1b_row23_col1" class="data row23 col1" >医药生物</td>
                        <td id="T_79e1b_row23_col2" class="data row23 col2" >0.49</td>
                        <td id="T_79e1b_row23_col3" class="data row23 col3" >9.45</td>
                        <td id="T_79e1b_row23_col4" class="data row23 col4" >10.07</td>
                        <td id="T_79e1b_row23_col5" class="data row23 col5" >25.97</td>
                        <td id="T_79e1b_row23_col6" class="data row23 col6" >46.52</td>
                        <td id="T_79e1b_row23_col7" class="data row23 col7" >24.46</td>
                        <td id="T_79e1b_row23_col8" class="data row23 col8" >5.26</td>
                        <td id="T_79e1b_row23_col9" class="data row23 col9" >20.61</td>
                        <td id="T_79e1b_row23_col10" class="data row23 col10" >8.85</td>
                        <td id="T_79e1b_row23_col11" class="data row23 col11" >27.94</td>
                        <td id="T_79e1b_row23_col12" class="data row23 col12" >13.10</td>
                        <td id="T_79e1b_row23_col13" class="data row23 col13" >12.63</td>
                        <td id="T_79e1b_row23_col14" class="data row23 col14" >15.80</td>
                        <td id="T_79e1b_row23_col15" class="data row23 col15" >52.44</td>
                        <td id="T_79e1b_row23_col16" class="data row23 col16" >2.54</td>
                        <td id="T_79e1b_row23_col17" class="data row23 col17" >52.26</td>
                        <td id="T_79e1b_row23_col18" class="data row23 col18" >-313.68</td>
            </tr>
            <tr>
                        <th id="T_79e1b_level0_row24" class="row_heading level0 row24" >600519.SS</th>
                        <td id="T_79e1b_row24_col0" class="data row24 col0" >贵州茅台</td>
                        <td id="T_79e1b_row24_col1" class="data row24 col1" >食品饮料</td>
                        <td id="T_79e1b_row24_col2" class="data row24 col2" >31.22</td>
                        <td id="T_79e1b_row24_col3" class="data row24 col3" >21.40</td>
                        <td id="T_79e1b_row24_col4" class="data row24 col4" >1.65</td>
                        <td id="T_79e1b_row24_col5" class="data row24 col5" >30.01</td>
                        <td id="T_79e1b_row24_col6" class="data row24 col6" >47.94</td>
                        <td id="T_79e1b_row24_col7" class="data row24 col7" >17.87</td>
                        <td id="T_79e1b_row24_col8" class="data row24 col8" >7.86</td>
                        <td id="T_79e1b_row24_col9" class="data row24 col9" >20.13</td>
                        <td id="T_79e1b_row24_col10" class="data row24 col10" >8.75</td>
                        <td id="T_79e1b_row24_col11" class="data row24 col11" >37.59</td>
                        <td id="T_79e1b_row24_col12" class="data row24 col12" >45.08</td>
                        <td id="T_79e1b_row24_col13" class="data row24 col13" >1189.50</td>
                        <td id="T_79e1b_row24_col14" class="data row24 col14" >796.91</td>
                        <td id="T_79e1b_row24_col15" class="data row24 col15" >58.69</td>
                        <td id="T_79e1b_row24_col16" class="data row24 col16" >2.92</td>
                        <td id="T_79e1b_row24_col17" class="data row24 col17" >2791.27</td>
                        <td id="T_79e1b_row24_col18" class="data row24 col18" >-134.66</td>
            </tr>
            <tr>
                        <th id="T_79e1b_level0_row25" class="row_heading level0 row25" >300896.SZ</th>
                        <td id="T_79e1b_row25_col0" class="data row25 col0" >爱美客</td>
                        <td id="T_79e1b_row25_col1" class="data row25 col1" >医药生物</td>
                        <td id="T_79e1b_row25_col2" class="data row25 col2" >0.84</td>
                        <td id="T_79e1b_row25_col3" class="data row25 col3" >2.19</td>
                        <td id="T_79e1b_row25_col4" class="data row25 col4" >6.39</td>
                        <td id="T_79e1b_row25_col5" class="data row25 col5" >28.05</td>
                        <td id="T_79e1b_row25_col6" class="data row25 col6" >48.00</td>
                        <td id="T_79e1b_row25_col7" class="data row25 col7" >48.40</td>
                        <td id="T_79e1b_row25_col8" class="data row25 col8" >23.55</td>
                        <td id="T_79e1b_row25_col9" class="data row25 col9" >80.70</td>
                        <td id="T_79e1b_row25_col10" class="data row25 col10" >58.94</td>
                        <td id="T_79e1b_row25_col11" class="data row25 col11" >120.48</td>
                        <td id="T_79e1b_row25_col12" class="data row25 col12" >73.47</td>
                        <td id="T_79e1b_row25_col13" class="data row25 col13" >24.71</td>
                        <td id="T_79e1b_row25_col14" class="data row25 col14" >16.26</td>
                        <td id="T_79e1b_row25_col15" class="data row25 col15" >236.42</td>
                        <td id="T_79e1b_row25_col16" class="data row25 col16" >2.93</td>
                        <td id="T_79e1b_row25_col17" class="data row25 col17" >134.15</td>
                        <td id="T_79e1b_row25_col18" class="data row25 col18" >-442.86</td>
            </tr>
            <tr>
                        <th id="T_79e1b_level0_row26" class="row_heading level0 row26" >603983.SS</th>
                        <td id="T_79e1b_row26_col0" class="data row26 col0" >丸美股份</td>
                        <td id="T_79e1b_row26_col1" class="data row26 col1" >化工</td>
                        <td id="T_79e1b_row26_col2" class="data row26 col2" >0.14</td>
                        <td id="T_79e1b_row26_col3" class="data row26 col3" >20.93</td>
                        <td id="T_79e1b_row26_col4" class="data row26 col4" >0.50</td>
                        <td id="T_79e1b_row26_col5" class="data row26 col5" >24.39</td>
                        <td id="T_79e1b_row26_col6" class="data row26 col6" >26.16</td>
                        <td id="T_79e1b_row26_col7" class="data row26 col7" >9.24</td>
                        <td id="T_79e1b_row26_col8" class="data row26 col8" >10.74</td>
                        <td id="T_79e1b_row26_col9" class="data row26 col9" >15.77</td>
                        <td id="T_79e1b_row26_col10" class="data row26 col10" >22.62</td>
                        <td id="T_79e1b_row26_col11" class="data row26 col11" >-49.63</td>
                        <td id="T_79e1b_row26_col12" class="data row26 col12" >119.58</td>
                        <td id="T_79e1b_row26_col13" class="data row26 col13" >0.49</td>
                        <td id="T_79e1b_row26_col14" class="data row26 col14" >8.16</td>
                        <td id="T_79e1b_row26_col15" class="data row26 col15" >52.45</td>
                        <td id="T_79e1b_row26_col16" class="data row26 col16" >3.33</td>
                        <td id="T_79e1b_row26_col17" class="data row26 col17" >23.37</td>
                        <td id="T_79e1b_row26_col18" class="data row26 col18" >-4661.90</td>
            </tr>
            <tr>
                        <th id="T_79e1b_level0_row27" class="row_heading level0 row27" >300595.SZ</th>
                        <td id="T_79e1b_row27_col0" class="data row27 col0" >欧普康视</td>
                        <td id="T_79e1b_row27_col1" class="data row27 col1" >医药生物</td>
                        <td id="T_79e1b_row27_col2" class="data row27 col2" >1.17</td>
                        <td id="T_79e1b_row27_col3" class="data row27 col3" >10.02</td>
                        <td id="T_79e1b_row27_col4" class="data row27 col4" >18.19</td>
                        <td id="T_79e1b_row27_col5" class="data row27 col5" >21.91</td>
                        <td id="T_79e1b_row27_col6" class="data row27 col6" >48.20</td>
                        <td id="T_79e1b_row27_col7" class="data row27 col7" >40.94</td>
                        <td id="T_79e1b_row27_col8" class="data row27 col8" >6.26</td>
                        <td id="T_79e1b_row27_col9" class="data row27 col9" >42.15</td>
                        <td id="T_79e1b_row27_col10" class="data row27 col10" >1.09</td>
                        <td id="T_79e1b_row27_col11" class="data row27 col11" >54.08</td>
                        <td id="T_79e1b_row27_col12" class="data row27 col12" >33.61</td>
                        <td id="T_79e1b_row27_col13" class="data row27 col13" >7.55</td>
                        <td id="T_79e1b_row27_col14" class="data row27 col14" >9.48</td>
                        <td id="T_79e1b_row27_col15" class="data row27 col15" >156.31</td>
                        <td id="T_79e1b_row27_col16" class="data row27 col16" >3.71</td>
                        <td id="T_79e1b_row27_col17" class="data row27 col17" >83.38</td>
                        <td id="T_79e1b_row27_col18" class="data row27 col18" >-1003.72</td>
            </tr>
            <tr>
                        <th id="T_79e1b_level0_row28" class="row_heading level0 row28" >603288.SS</th>
                        <td id="T_79e1b_row28_col0" class="data row28 col0" >海天味业</td>
                        <td id="T_79e1b_row28_col1" class="data row28 col1" >食品饮料</td>
                        <td id="T_79e1b_row28_col2" class="data row28 col2" >5.16</td>
                        <td id="T_79e1b_row28_col3" class="data row28 col3" >31.72</td>
                        <td id="T_79e1b_row28_col4" class="data row28 col4" >0.21</td>
                        <td id="T_79e1b_row28_col5" class="data row28 col5" >31.42</td>
                        <td id="T_79e1b_row28_col6" class="data row28 col6" >26.24</td>
                        <td id="T_79e1b_row28_col7" class="data row28 col7" >16.05</td>
                        <td id="T_79e1b_row28_col8" class="data row28 col8" >0.85</td>
                        <td id="T_79e1b_row28_col9" class="data row28 col9" >21.95</td>
                        <td id="T_79e1b_row28_col10" class="data row28 col10" >2.08</td>
                        <td id="T_79e1b_row28_col11" class="data row28 col11" >11.37</td>
                        <td id="T_79e1b_row28_col12" class="data row28 col12" >15.72</td>
                        <td id="T_79e1b_row28_col13" class="data row28 col13" >95.46</td>
                        <td id="T_79e1b_row28_col14" class="data row28 col14" >108.81</td>
                        <td id="T_79e1b_row28_col15" class="data row28 col15" >86.22</td>
                        <td id="T_79e1b_row28_col16" class="data row28 col16" >3.93</td>
                        <td id="T_79e1b_row28_col17" class="data row28 col17" >581.42</td>
                        <td id="T_79e1b_row28_col18" class="data row28 col18" >-509.06</td>
            </tr>
            <tr>
                        <th id="T_79e1b_level0_row29" class="row_heading level0 row29" >600436.SS</th>
                        <td id="T_79e1b_row29_col0" class="data row29 col0" >片仔癀</td>
                        <td id="T_79e1b_row29_col1" class="data row29 col1" >医药生物</td>
                        <td id="T_79e1b_row29_col2" class="data row29 col2" >2.58</td>
                        <td id="T_79e1b_row29_col3" class="data row29 col3" >19.10</td>
                        <td id="T_79e1b_row29_col4" class="data row29 col4" >10.00</td>
                        <td id="T_79e1b_row29_col5" class="data row29 col5" >21.07</td>
                        <td id="T_79e1b_row29_col6" class="data row29 col6" >23.85</td>
                        <td id="T_79e1b_row29_col7" class="data row29 col7" >20.72</td>
                        <td id="T_79e1b_row29_col8" class="data row29 col8" >7.30</td>
                        <td id="T_79e1b_row29_col9" class="data row29 col9" >27.83</td>
                        <td id="T_79e1b_row29_col10" class="data row29 col10" >11.96</td>
                        <td id="T_79e1b_row29_col11" class="data row29 col11" >-166.81</td>
                        <td id="T_79e1b_row29_col12" class="data row29 col12" >136.30</td>
                        <td id="T_79e1b_row29_col13" class="data row29 col13" >-1.10</td>
                        <td id="T_79e1b_row29_col14" class="data row29 col14" >31.61</td>
                        <td id="T_79e1b_row29_col15" class="data row29 col15" >130.91</td>
                        <td id="T_79e1b_row29_col16" class="data row29 col16" >4.70</td>
                        <td id="T_79e1b_row29_col17" class="data row29 col17" >231.59</td>
                        <td id="T_79e1b_row29_col18" class="data row29 col18" >0.00</td>
            </tr>
            <tr>
                        <th id="T_79e1b_level0_row30" class="row_heading level0 row30" >600763.SS</th>
                        <td id="T_79e1b_row30_col0" class="data row30 col0" >通策医疗</td>
                        <td id="T_79e1b_row30_col1" class="data row30 col1" >医药生物</td>
                        <td id="T_79e1b_row30_col2" class="data row30 col2" >2.12</td>
                        <td id="T_79e1b_row30_col3" class="data row30 col3" >23.37</td>
                        <td id="T_79e1b_row30_col4" class="data row30 col4" >4.92</td>
                        <td id="T_79e1b_row30_col5" class="data row30 col5" >23.98</td>
                        <td id="T_79e1b_row30_col6" class="data row30 col6" >21.89</td>
                        <td id="T_79e1b_row30_col7" class="data row30 col7" >21.36</td>
                        <td id="T_79e1b_row30_col8" class="data row30 col8" >11.87</td>
                        <td id="T_79e1b_row30_col9" class="data row30 col9" >33.13</td>
                        <td id="T_79e1b_row30_col10" class="data row30 col10" >24.64</td>
                        <td id="T_79e1b_row30_col11" class="data row30 col11" >38.60</td>
                        <td id="T_79e1b_row30_col12" class="data row30 col12" >81.59</td>
                        <td id="T_79e1b_row30_col13" class="data row30 col13" >12.56</td>
                        <td id="T_79e1b_row30_col14" class="data row30 col14" >10.71</td>
                        <td id="T_79e1b_row30_col15" class="data row30 col15" >172.58</td>
                        <td id="T_79e1b_row30_col16" class="data row30 col16" >5.21</td>
                        <td id="T_79e1b_row30_col17" class="data row30 col17" >116.68</td>
                        <td id="T_79e1b_row30_col18" class="data row30 col18" >-829.29</td>
            </tr>
            <tr>
                        <th id="T_79e1b_level0_row31" class="row_heading level0 row31" >000885.SZ</th>
                        <td id="T_79e1b_row31_col0" class="data row31 col0" >城发环境</td>
                        <td id="T_79e1b_row31_col1" class="data row31 col1" >交通运输</td>
                        <td id="T_79e1b_row31_col2" class="data row31 col2" >0.26</td>
                        <td id="T_79e1b_row31_col3" class="data row31 col3" >60.46</td>
                        <td id="T_79e1b_row31_col4" class="data row31 col4" >15.69</td>
                        <td id="T_79e1b_row31_col5" class="data row31 col5" >22.03</td>
                        <td id="T_79e1b_row31_col6" class="data row31 col6" >25.54</td>
                        <td id="T_79e1b_row31_col7" class="data row31 col7" >18.36</td>
                        <td id="T_79e1b_row31_col8" class="data row31 col8" >28.79</td>
                        <td id="T_79e1b_row31_col9" class="data row31 col9" >0.73</td>
                        <td id="T_79e1b_row31_col10" class="data row31 col10" >5.86</td>
                        <td id="T_79e1b_row31_col11" class="data row31 col11" >-328.78</td>
                        <td id="T_79e1b_row31_col12" class="data row31 col12" >483.06</td>
                        <td id="T_79e1b_row31_col13" class="data row31 col13" >-17.76</td>
                        <td id="T_79e1b_row31_col14" class="data row31 col14" >7.85</td>
                        <td id="T_79e1b_row31_col15" class="data row31 col15" >7.00</td>
                        <td id="T_79e1b_row31_col16" class="data row31 col16" >9.55</td>
                        <td id="T_79e1b_row31_col17" class="data row31 col17" >6.36</td>
                        <td id="T_79e1b_row31_col18" class="data row31 col18" >0.00</td>
            </tr>
    </tbody></table>



### 金融行业

1. ROE > 10%
2. 商誉比 < 10%
3. 盈利增长 >= 10% 或 收入增长 >= 10%




<style  type="text/css" >
#T_f2bc7_row0_col0,#T_f2bc7_row0_col1,#T_f2bc7_row0_col2,#T_f2bc7_row0_col3,#T_f2bc7_row0_col4,#T_f2bc7_row0_col5,#T_f2bc7_row0_col6,#T_f2bc7_row0_col7,#T_f2bc7_row0_col8,#T_f2bc7_row0_col9,#T_f2bc7_row0_col10,#T_f2bc7_row0_col12,#T_f2bc7_row0_col14,#T_f2bc7_row0_col15,#T_f2bc7_row0_col16,#T_f2bc7_row0_col17,#T_f2bc7_row0_col18,#T_f2bc7_row1_col0,#T_f2bc7_row1_col1,#T_f2bc7_row1_col2,#T_f2bc7_row1_col3,#T_f2bc7_row1_col4,#T_f2bc7_row1_col5,#T_f2bc7_row1_col6,#T_f2bc7_row1_col7,#T_f2bc7_row1_col8,#T_f2bc7_row1_col9,#T_f2bc7_row1_col10,#T_f2bc7_row1_col12,#T_f2bc7_row1_col14,#T_f2bc7_row1_col15,#T_f2bc7_row1_col16,#T_f2bc7_row1_col17,#T_f2bc7_row1_col18,#T_f2bc7_row2_col0,#T_f2bc7_row2_col1,#T_f2bc7_row2_col2,#T_f2bc7_row2_col3,#T_f2bc7_row2_col4,#T_f2bc7_row2_col5,#T_f2bc7_row2_col6,#T_f2bc7_row2_col7,#T_f2bc7_row2_col8,#T_f2bc7_row2_col9,#T_f2bc7_row2_col10,#T_f2bc7_row2_col12,#T_f2bc7_row2_col13,#T_f2bc7_row2_col14,#T_f2bc7_row2_col15,#T_f2bc7_row2_col16,#T_f2bc7_row2_col17,#T_f2bc7_row3_col0,#T_f2bc7_row3_col1,#T_f2bc7_row3_col2,#T_f2bc7_row3_col3,#T_f2bc7_row3_col4,#T_f2bc7_row3_col5,#T_f2bc7_row3_col6,#T_f2bc7_row3_col7,#T_f2bc7_row3_col8,#T_f2bc7_row3_col9,#T_f2bc7_row3_col10,#T_f2bc7_row3_col12,#T_f2bc7_row3_col14,#T_f2bc7_row3_col15,#T_f2bc7_row3_col16,#T_f2bc7_row3_col17,#T_f2bc7_row3_col18,#T_f2bc7_row4_col0,#T_f2bc7_row4_col1,#T_f2bc7_row4_col2,#T_f2bc7_row4_col3,#T_f2bc7_row4_col4,#T_f2bc7_row4_col5,#T_f2bc7_row4_col6,#T_f2bc7_row4_col7,#T_f2bc7_row4_col8,#T_f2bc7_row4_col9,#T_f2bc7_row4_col10,#T_f2bc7_row4_col12,#T_f2bc7_row4_col13,#T_f2bc7_row4_col14,#T_f2bc7_row4_col15,#T_f2bc7_row4_col16,#T_f2bc7_row4_col17,#T_f2bc7_row5_col0,#T_f2bc7_row5_col1,#T_f2bc7_row5_col2,#T_f2bc7_row5_col3,#T_f2bc7_row5_col4,#T_f2bc7_row5_col5,#T_f2bc7_row5_col6,#T_f2bc7_row5_col7,#T_f2bc7_row5_col8,#T_f2bc7_row5_col9,#T_f2bc7_row5_col10,#T_f2bc7_row5_col12,#T_f2bc7_row5_col13,#T_f2bc7_row5_col14,#T_f2bc7_row5_col15,#T_f2bc7_row5_col16,#T_f2bc7_row5_col17,#T_f2bc7_row6_col0,#T_f2bc7_row6_col1,#T_f2bc7_row6_col2,#T_f2bc7_row6_col3,#T_f2bc7_row6_col4,#T_f2bc7_row6_col5,#T_f2bc7_row6_col6,#T_f2bc7_row6_col7,#T_f2bc7_row6_col8,#T_f2bc7_row6_col9,#T_f2bc7_row6_col10,#T_f2bc7_row6_col12,#T_f2bc7_row6_col13,#T_f2bc7_row6_col14,#T_f2bc7_row6_col15,#T_f2bc7_row6_col16,#T_f2bc7_row6_col17,#T_f2bc7_row6_col18,#T_f2bc7_row7_col0,#T_f2bc7_row7_col1,#T_f2bc7_row7_col2,#T_f2bc7_row7_col3,#T_f2bc7_row7_col4,#T_f2bc7_row7_col5,#T_f2bc7_row7_col6,#T_f2bc7_row7_col7,#T_f2bc7_row7_col8,#T_f2bc7_row7_col9,#T_f2bc7_row7_col10,#T_f2bc7_row7_col11,#T_f2bc7_row7_col12,#T_f2bc7_row7_col13,#T_f2bc7_row7_col14,#T_f2bc7_row7_col15,#T_f2bc7_row7_col16,#T_f2bc7_row7_col17,#T_f2bc7_row7_col18,#T_f2bc7_row8_col0,#T_f2bc7_row8_col1,#T_f2bc7_row8_col2,#T_f2bc7_row8_col3,#T_f2bc7_row8_col4,#T_f2bc7_row8_col5,#T_f2bc7_row8_col6,#T_f2bc7_row8_col7,#T_f2bc7_row8_col8,#T_f2bc7_row8_col9,#T_f2bc7_row8_col10,#T_f2bc7_row8_col11,#T_f2bc7_row8_col12,#T_f2bc7_row8_col13,#T_f2bc7_row8_col14,#T_f2bc7_row8_col15,#T_f2bc7_row8_col16,#T_f2bc7_row8_col17,#T_f2bc7_row8_col18,#T_f2bc7_row9_col0,#T_f2bc7_row9_col1,#T_f2bc7_row9_col2,#T_f2bc7_row9_col3,#T_f2bc7_row9_col4,#T_f2bc7_row9_col5,#T_f2bc7_row9_col6,#T_f2bc7_row9_col7,#T_f2bc7_row9_col8,#T_f2bc7_row9_col9,#T_f2bc7_row9_col10,#T_f2bc7_row9_col12,#T_f2bc7_row9_col14,#T_f2bc7_row9_col15,#T_f2bc7_row9_col16,#T_f2bc7_row9_col17,#T_f2bc7_row9_col18,#T_f2bc7_row10_col0,#T_f2bc7_row10_col1,#T_f2bc7_row10_col2,#T_f2bc7_row10_col3,#T_f2bc7_row10_col4,#T_f2bc7_row10_col5,#T_f2bc7_row10_col6,#T_f2bc7_row10_col7,#T_f2bc7_row10_col8,#T_f2bc7_row10_col9,#T_f2bc7_row10_col10,#T_f2bc7_row10_col12,#T_f2bc7_row10_col13,#T_f2bc7_row10_col14,#T_f2bc7_row10_col15,#T_f2bc7_row10_col16,#T_f2bc7_row10_col17,#T_f2bc7_row11_col0,#T_f2bc7_row11_col1,#T_f2bc7_row11_col2,#T_f2bc7_row11_col3,#T_f2bc7_row11_col4,#T_f2bc7_row11_col5,#T_f2bc7_row11_col6,#T_f2bc7_row11_col7,#T_f2bc7_row11_col8,#T_f2bc7_row11_col9,#T_f2bc7_row11_col10,#T_f2bc7_row11_col12,#T_f2bc7_row11_col14,#T_f2bc7_row11_col15,#T_f2bc7_row11_col16,#T_f2bc7_row11_col17,#T_f2bc7_row11_col18,#T_f2bc7_row12_col0,#T_f2bc7_row12_col1,#T_f2bc7_row12_col2,#T_f2bc7_row12_col3,#T_f2bc7_row12_col4,#T_f2bc7_row12_col5,#T_f2bc7_row12_col6,#T_f2bc7_row12_col7,#T_f2bc7_row12_col8,#T_f2bc7_row12_col9,#T_f2bc7_row12_col10,#T_f2bc7_row12_col12,#T_f2bc7_row12_col14,#T_f2bc7_row12_col15,#T_f2bc7_row12_col16,#T_f2bc7_row12_col17,#T_f2bc7_row12_col18,#T_f2bc7_row13_col0,#T_f2bc7_row13_col1,#T_f2bc7_row13_col2,#T_f2bc7_row13_col3,#T_f2bc7_row13_col4,#T_f2bc7_row13_col5,#T_f2bc7_row13_col6,#T_f2bc7_row13_col7,#T_f2bc7_row13_col8,#T_f2bc7_row13_col9,#T_f2bc7_row13_col10,#T_f2bc7_row13_col11,#T_f2bc7_row13_col12,#T_f2bc7_row13_col14,#T_f2bc7_row13_col15,#T_f2bc7_row13_col16,#T_f2bc7_row13_col17,#T_f2bc7_row13_col18,#T_f2bc7_row14_col0,#T_f2bc7_row14_col1,#T_f2bc7_row14_col2,#T_f2bc7_row14_col3,#T_f2bc7_row14_col4,#T_f2bc7_row14_col5,#T_f2bc7_row14_col6,#T_f2bc7_row14_col7,#T_f2bc7_row14_col8,#T_f2bc7_row14_col9,#T_f2bc7_row14_col10,#T_f2bc7_row14_col12,#T_f2bc7_row14_col14,#T_f2bc7_row14_col15,#T_f2bc7_row14_col16,#T_f2bc7_row14_col17,#T_f2bc7_row14_col18,#T_f2bc7_row15_col0,#T_f2bc7_row15_col1,#T_f2bc7_row15_col2,#T_f2bc7_row15_col3,#T_f2bc7_row15_col4,#T_f2bc7_row15_col5,#T_f2bc7_row15_col6,#T_f2bc7_row15_col7,#T_f2bc7_row15_col8,#T_f2bc7_row15_col9,#T_f2bc7_row15_col10,#T_f2bc7_row15_col12,#T_f2bc7_row15_col14,#T_f2bc7_row15_col15,#T_f2bc7_row15_col16,#T_f2bc7_row15_col17,#T_f2bc7_row15_col18,#T_f2bc7_row16_col0,#T_f2bc7_row16_col1,#T_f2bc7_row16_col2,#T_f2bc7_row16_col3,#T_f2bc7_row16_col4,#T_f2bc7_row16_col5,#T_f2bc7_row16_col6,#T_f2bc7_row16_col7,#T_f2bc7_row16_col8,#T_f2bc7_row16_col9,#T_f2bc7_row16_col10,#T_f2bc7_row16_col12,#T_f2bc7_row16_col14,#T_f2bc7_row16_col15,#T_f2bc7_row16_col16,#T_f2bc7_row16_col17,#T_f2bc7_row16_col18{
            color:  black;
        }#T_f2bc7_row0_col11,#T_f2bc7_row0_col13,#T_f2bc7_row1_col11,#T_f2bc7_row1_col13,#T_f2bc7_row2_col11,#T_f2bc7_row2_col18,#T_f2bc7_row3_col11,#T_f2bc7_row3_col13,#T_f2bc7_row4_col11,#T_f2bc7_row4_col18,#T_f2bc7_row5_col11,#T_f2bc7_row5_col18,#T_f2bc7_row6_col11,#T_f2bc7_row9_col11,#T_f2bc7_row9_col13,#T_f2bc7_row10_col11,#T_f2bc7_row10_col18,#T_f2bc7_row11_col11,#T_f2bc7_row11_col13,#T_f2bc7_row12_col11,#T_f2bc7_row12_col13,#T_f2bc7_row13_col13,#T_f2bc7_row14_col11,#T_f2bc7_row14_col13,#T_f2bc7_row15_col11,#T_f2bc7_row15_col13,#T_f2bc7_row16_col11,#T_f2bc7_row16_col13{
            color:  red;
        }</style><table id="T_f2bc7_" ><thead>    <tr>        <th class="blank level0" ></th>        <th class="col_heading level0 col0" >名称</th>        <th class="col_heading level0 col1" >行业</th>        <th class="col_heading level0 col2" >权重</th>        <th class="col_heading level0 col3" >负债率</th>        <th class="col_heading level0 col4" >应收比</th>        <th class="col_heading level0 col5" >ROE</th>        <th class="col_heading level0 col6" >利润率</th>        <th class="col_heading level0 col7" >收入增长</th>        <th class="col_heading level0 col8" >收入波动</th>        <th class="col_heading level0 col9" >盈利增长</th>        <th class="col_heading level0 col10" >盈利波动</th>        <th class="col_heading level0 col11" >FCF增长</th>        <th class="col_heading level0 col12" >FCF波动</th>        <th class="col_heading level0 col13" >DCF</th>        <th class="col_heading level0 col14" >盈利折现</th>        <th class="col_heading level0 col15" >PE</th>        <th class="col_heading level0 col16" >PEG</th>        <th class="col_heading level0 col17" >市值</th>        <th class="col_heading level0 col18" >折价率</th>    </tr>    <tr>        <th class="index_name level0" >Symbol</th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>    </tr></thead><tbody>
                <tr>
                        <th id="T_f2bc7_level0_row0" class="row_heading level0 row0" >601997.SS</th>
                        <td id="T_f2bc7_row0_col0" class="data row0 col0" >贵阳银行</td>
                        <td id="T_f2bc7_row0_col1" class="data row0 col1" >银行</td>
                        <td id="T_f2bc7_row0_col2" class="data row0 col2" >0.64</td>
                        <td id="T_f2bc7_row0_col3" class="data row0 col3" >92.80</td>
                        <td id="T_f2bc7_row0_col4" class="data row0 col4" >1.28</td>
                        <td id="T_f2bc7_row0_col5" class="data row0 col5" >17.47</td>
                        <td id="T_f2bc7_row0_col6" class="data row0 col6" >54.49</td>
                        <td id="T_f2bc7_row0_col7" class="data row0 col7" >13.83</td>
                        <td id="T_f2bc7_row0_col8" class="data row0 col8" >9.08</td>
                        <td id="T_f2bc7_row0_col9" class="data row0 col9" >16.76</td>
                        <td id="T_f2bc7_row0_col10" class="data row0 col10" >6.26</td>
                        <td id="T_f2bc7_row0_col11" class="data row0 col11" >-159.52</td>
                        <td id="T_f2bc7_row0_col12" class="data row0 col12" >117.14</td>
                        <td id="T_f2bc7_row0_col13" class="data row0 col13" >-35.89</td>
                        <td id="T_f2bc7_row0_col14" class="data row0 col14" >93.65</td>
                        <td id="T_f2bc7_row0_col15" class="data row0 col15" >4.73</td>
                        <td id="T_f2bc7_row0_col16" class="data row0 col16" >0.28</td>
                        <td id="T_f2bc7_row0_col17" class="data row0 col17" >28.30</td>
                        <td id="T_f2bc7_row0_col18" class="data row0 col18" >nan</td>
            </tr>
            <tr>
                        <th id="T_f2bc7_level0_row1" class="row_heading level0 row1" >601838.SS</th>
                        <td id="T_f2bc7_row1_col0" class="data row1 col0" >成都银行</td>
                        <td id="T_f2bc7_row1_col1" class="data row1 col1" >银行</td>
                        <td id="T_f2bc7_row1_col2" class="data row1 col2" >0.81</td>
                        <td id="T_f2bc7_row1_col3" class="data row1 col3" >93.62</td>
                        <td id="T_f2bc7_row1_col4" class="data row1 col4" >2.64</td>
                        <td id="T_f2bc7_row1_col5" class="data row1 col5" >15.50</td>
                        <td id="T_f2bc7_row1_col6" class="data row1 col6" >52.11</td>
                        <td id="T_f2bc7_row1_col7" class="data row1 col7" >26.62</td>
                        <td id="T_f2bc7_row1_col8" class="data row1 col8" >21.12</td>
                        <td id="T_f2bc7_row1_col9" class="data row1 col9" >15.63</td>
                        <td id="T_f2bc7_row1_col10" class="data row1 col10" >6.14</td>
                        <td id="T_f2bc7_row1_col11" class="data row1 col11" >-141.63</td>
                        <td id="T_f2bc7_row1_col12" class="data row1 col12" >148.74</td>
                        <td id="T_f2bc7_row1_col13" class="data row1 col13" >-18.66</td>
                        <td id="T_f2bc7_row1_col14" class="data row1 col14" >95.94</td>
                        <td id="T_f2bc7_row1_col15" class="data row1 col15" >7.93</td>
                        <td id="T_f2bc7_row1_col16" class="data row1 col16" >0.51</td>
                        <td id="T_f2bc7_row1_col17" class="data row1 col17" >49.78</td>
                        <td id="T_f2bc7_row1_col18" class="data row1 col18" >nan</td>
            </tr>
            <tr>
                        <th id="T_f2bc7_level0_row2" class="row_heading level0 row2" >601229.SS</th>
                        <td id="T_f2bc7_row2_col0" class="data row2 col0" >上海银行</td>
                        <td id="T_f2bc7_row2_col1" class="data row2 col1" >银行</td>
                        <td id="T_f2bc7_row2_col2" class="data row2 col2" >2.57</td>
                        <td id="T_f2bc7_row2_col3" class="data row2 col3" >92.25</td>
                        <td id="T_f2bc7_row2_col4" class="data row2 col4" >7.05</td>
                        <td id="T_f2bc7_row2_col5" class="data row2 col5" >12.51</td>
                        <td id="T_f2bc7_row2_col6" class="data row2 col6" >63.20</td>
                        <td id="T_f2bc7_row2_col7" class="data row2 col7" >10.14</td>
                        <td id="T_f2bc7_row2_col8" class="data row2 col8" >9.39</td>
                        <td id="T_f2bc7_row2_col9" class="data row2 col9" >11.03</td>
                        <td id="T_f2bc7_row2_col10" class="data row2 col10" >7.49</td>
                        <td id="T_f2bc7_row2_col11" class="data row2 col11" >-118.51</td>
                        <td id="T_f2bc7_row2_col12" class="data row2 col12" >97.23</td>
                        <td id="T_f2bc7_row2_col13" class="data row2 col13" >4.53</td>
                        <td id="T_f2bc7_row2_col14" class="data row2 col14" >316.97</td>
                        <td id="T_f2bc7_row2_col15" class="data row2 col15" >5.71</td>
                        <td id="T_f2bc7_row2_col16" class="data row2 col16" >0.52</td>
                        <td id="T_f2bc7_row2_col17" class="data row2 col17" >121.04</td>
                        <td id="T_f2bc7_row2_col18" class="data row2 col18" >-2571.08</td>
            </tr>
            <tr>
                        <th id="T_f2bc7_level0_row3" class="row_heading level0 row3" >601009.SS</th>
                        <td id="T_f2bc7_row3_col0" class="data row3 col0" >南京银行</td>
                        <td id="T_f2bc7_row3_col1" class="data row3 col1" >银行</td>
                        <td id="T_f2bc7_row3_col2" class="data row3 col2" >2.11</td>
                        <td id="T_f2bc7_row3_col3" class="data row3 col3" >93.45</td>
                        <td id="T_f2bc7_row3_col4" class="data row3 col4" >9.80</td>
                        <td id="T_f2bc7_row3_col5" class="data row3 col5" >16.29</td>
                        <td id="T_f2bc7_row3_col6" class="data row3 col6" >49.90</td>
                        <td id="T_f2bc7_row3_col7" class="data row3 col7" >10.15</td>
                        <td id="T_f2bc7_row3_col8" class="data row3 col8" >5.23</td>
                        <td id="T_f2bc7_row3_col9" class="data row3 col9" >14.67</td>
                        <td id="T_f2bc7_row3_col10" class="data row3 col10" >2.28</td>
                        <td id="T_f2bc7_row3_col11" class="data row3 col11" >-1417.97</td>
                        <td id="T_f2bc7_row3_col12" class="data row3 col12" >2342.24</td>
                        <td id="T_f2bc7_row3_col13" class="data row3 col13" >-697759.98</td>
                        <td id="T_f2bc7_row3_col14" class="data row3 col14" >192.99</td>
                        <td id="T_f2bc7_row3_col15" class="data row3 col15" >7.82</td>
                        <td id="T_f2bc7_row3_col16" class="data row3 col16" >0.53</td>
                        <td id="T_f2bc7_row3_col17" class="data row3 col17" >105.17</td>
                        <td id="T_f2bc7_row3_col18" class="data row3 col18" >nan</td>
            </tr>
            <tr>
                        <th id="T_f2bc7_level0_row4" class="row_heading level0 row4" >601577.SS</th>
                        <td id="T_f2bc7_row4_col0" class="data row4 col0" >长沙银行</td>
                        <td id="T_f2bc7_row4_col1" class="data row4 col1" >银行</td>
                        <td id="T_f2bc7_row4_col2" class="data row4 col2" >0.40</td>
                        <td id="T_f2bc7_row4_col3" class="data row4 col3" >93.51</td>
                        <td id="T_f2bc7_row4_col4" class="data row4 col4" >2.67</td>
                        <td id="T_f2bc7_row4_col5" class="data row4 col5" >14.98</td>
                        <td id="T_f2bc7_row4_col6" class="data row4 col6" >43.03</td>
                        <td id="T_f2bc7_row4_col7" class="data row4 col7" >10.42</td>
                        <td id="T_f2bc7_row4_col8" class="data row4 col8" >5.63</td>
                        <td id="T_f2bc7_row4_col9" class="data row4 col9" >10.82</td>
                        <td id="T_f2bc7_row4_col10" class="data row4 col10" >4.97</td>
                        <td id="T_f2bc7_row4_col11" class="data row4 col11" >-149.80</td>
                        <td id="T_f2bc7_row4_col12" class="data row4 col12" >106.99</td>
                        <td id="T_f2bc7_row4_col13" class="data row4 col13" >6.96</td>
                        <td id="T_f2bc7_row4_col14" class="data row4 col14" >79.62</td>
                        <td id="T_f2bc7_row4_col15" class="data row4 col15" >7.14</td>
                        <td id="T_f2bc7_row4_col16" class="data row4 col16" >0.66</td>
                        <td id="T_f2bc7_row4_col17" class="data row4 col17" >38.69</td>
                        <td id="T_f2bc7_row4_col18" class="data row4 col18" >-456.17</td>
            </tr>
            <tr>
                        <th id="T_f2bc7_level0_row5" class="row_heading level0 row5" >002958.SZ</th>
                        <td id="T_f2bc7_row5_col0" class="data row5 col0" >青农商行</td>
                        <td id="T_f2bc7_row5_col1" class="data row5 col1" >银行</td>
                        <td id="T_f2bc7_row5_col2" class="data row5 col2" >0.50</td>
                        <td id="T_f2bc7_row5_col3" class="data row5 col3" >92.70</td>
                        <td id="T_f2bc7_row5_col4" class="data row5 col4" >1.41</td>
                        <td id="T_f2bc7_row5_col5" class="data row5 col5" >11.53</td>
                        <td id="T_f2bc7_row5_col6" class="data row5 col6" >43.16</td>
                        <td id="T_f2bc7_row5_col7" class="data row5 col7" >9.77</td>
                        <td id="T_f2bc7_row5_col8" class="data row5 col8" >35.49</td>
                        <td id="T_f2bc7_row5_col9" class="data row5 col9" >11.59</td>
                        <td id="T_f2bc7_row5_col10" class="data row5 col10" >6.17</td>
                        <td id="T_f2bc7_row5_col11" class="data row5 col11" >-138.47</td>
                        <td id="T_f2bc7_row5_col12" class="data row5 col12" >207.69</td>
                        <td id="T_f2bc7_row5_col13" class="data row5 col13" >0.11</td>
                        <td id="T_f2bc7_row5_col14" class="data row5 col14" >44.59</td>
                        <td id="T_f2bc7_row5_col15" class="data row5 col15" >8.12</td>
                        <td id="T_f2bc7_row5_col16" class="data row5 col16" >0.70</td>
                        <td id="T_f2bc7_row5_col17" class="data row5 col17" >24.50</td>
                        <td id="T_f2bc7_row5_col18" class="data row5 col18" >-21825.66</td>
            </tr>
            <tr>
                        <th id="T_f2bc7_level0_row6" class="row_heading level0 row6" >601658.SS</th>
                        <td id="T_f2bc7_row6_col0" class="data row6 col0" >邮储银行</td>
                        <td id="T_f2bc7_row6_col1" class="data row6 col1" >银行</td>
                        <td id="T_f2bc7_row6_col2" class="data row6 col2" >1.20</td>
                        <td id="T_f2bc7_row6_col3" class="data row6 col3" >94.07</td>
                        <td id="T_f2bc7_row6_col4" class="data row6 col4" >2.27</td>
                        <td id="T_f2bc7_row6_col5" class="data row6 col5" >11.82</td>
                        <td id="T_f2bc7_row6_col6" class="data row6 col6" >26.06</td>
                        <td id="T_f2bc7_row6_col7" class="data row6 col7" >6.04</td>
                        <td id="T_f2bc7_row6_col8" class="data row6 col8" >2.30</td>
                        <td id="T_f2bc7_row6_col9" class="data row6 col9" >10.52</td>
                        <td id="T_f2bc7_row6_col10" class="data row6 col10" >5.61</td>
                        <td id="T_f2bc7_row6_col11" class="data row6 col11" >-173.49</td>
                        <td id="T_f2bc7_row6_col12" class="data row6 col12" >250.48</td>
                        <td id="T_f2bc7_row6_col13" class="data row6 col13" >2581.41</td>
                        <td id="T_f2bc7_row6_col14" class="data row6 col14" >944.82</td>
                        <td id="T_f2bc7_row6_col15" class="data row6 col15" >7.75</td>
                        <td id="T_f2bc7_row6_col16" class="data row6 col16" >0.74</td>
                        <td id="T_f2bc7_row6_col17" class="data row6 col17" >506.26</td>
                        <td id="T_f2bc7_row6_col18" class="data row6 col18" >80.39</td>
            </tr>
            <tr>
                        <th id="T_f2bc7_level0_row7" class="row_heading level0 row7" >600926.SS</th>
                        <td id="T_f2bc7_row7_col0" class="data row7 col0" >杭州银行</td>
                        <td id="T_f2bc7_row7_col1" class="data row7 col1" >银行</td>
                        <td id="T_f2bc7_row7_col2" class="data row7 col2" >1.37</td>
                        <td id="T_f2bc7_row7_col3" class="data row7 col3" >93.08</td>
                        <td id="T_f2bc7_row7_col4" class="data row7 col4" >1.08</td>
                        <td id="T_f2bc7_row7_col5" class="data row7 col5" >11.24</td>
                        <td id="T_f2bc7_row7_col6" class="data row7 col6" >48.22</td>
                        <td id="T_f2bc7_row7_col7" class="data row7 col7" >15.82</td>
                        <td id="T_f2bc7_row7_col8" class="data row7 col8" >7.40</td>
                        <td id="T_f2bc7_row7_col9" class="data row7 col9" >16.34</td>
                        <td id="T_f2bc7_row7_col10" class="data row7 col10" >7.30</td>
                        <td id="T_f2bc7_row7_col11" class="data row7 col11" >41.76</td>
                        <td id="T_f2bc7_row7_col12" class="data row7 col12" >194.69</td>
                        <td id="T_f2bc7_row7_col13" class="data row7 col13" >1178.05</td>
                        <td id="T_f2bc7_row7_col14" class="data row7 col14" >114.90</td>
                        <td id="T_f2bc7_row7_col15" class="data row7 col15" >12.95</td>
                        <td id="T_f2bc7_row7_col16" class="data row7 col16" >0.79</td>
                        <td id="T_f2bc7_row7_col17" class="data row7 col17" >97.02</td>
                        <td id="T_f2bc7_row7_col18" class="data row7 col18" >91.76</td>
            </tr>
            <tr>
                        <th id="T_f2bc7_level0_row8" class="row_heading level0 row8" >601128.SS</th>
                        <td id="T_f2bc7_row8_col0" class="data row8 col0" >常熟银行</td>
                        <td id="T_f2bc7_row8_col1" class="data row8 col1" >银行</td>
                        <td id="T_f2bc7_row8_col2" class="data row8 col2" >0.63</td>
                        <td id="T_f2bc7_row8_col3" class="data row8 col3" >90.84</td>
                        <td id="T_f2bc7_row8_col4" class="data row8 col4" >0.65</td>
                        <td id="T_f2bc7_row8_col5" class="data row8 col5" >11.06</td>
                        <td id="T_f2bc7_row8_col6" class="data row8 col6" >36.04</td>
                        <td id="T_f2bc7_row8_col7" class="data row8 col7" >12.82</td>
                        <td id="T_f2bc7_row8_col8" class="data row8 col8" >5.59</td>
                        <td id="T_f2bc7_row8_col9" class="data row8 col9" >12.89</td>
                        <td id="T_f2bc7_row8_col10" class="data row8 col10" >10.37</td>
                        <td id="T_f2bc7_row8_col11" class="data row8 col11" >170.81</td>
                        <td id="T_f2bc7_row8_col12" class="data row8 col12" >457.78</td>
                        <td id="T_f2bc7_row8_col13" class="data row8 col13" >505.12</td>
                        <td id="T_f2bc7_row8_col14" class="data row8 col14" >28.24</td>
                        <td id="T_f2bc7_row8_col15" class="data row8 col15" >10.27</td>
                        <td id="T_f2bc7_row8_col16" class="data row8 col16" >0.80</td>
                        <td id="T_f2bc7_row8_col17" class="data row8 col17" >18.77</td>
                        <td id="T_f2bc7_row8_col18" class="data row8 col18" >96.28</td>
            </tr>
            <tr>
                        <th id="T_f2bc7_level0_row9" class="row_heading level0 row9" >600919.SS</th>
                        <td id="T_f2bc7_row9_col0" class="data row9 col0" >江苏银行</td>
                        <td id="T_f2bc7_row9_col1" class="data row9 col1" >银行</td>
                        <td id="T_f2bc7_row9_col2" class="data row9 col2" >3.03</td>
                        <td id="T_f2bc7_row9_col3" class="data row9 col3" >93.39</td>
                        <td id="T_f2bc7_row9_col4" class="data row9 col4" >0.84</td>
                        <td id="T_f2bc7_row9_col5" class="data row9 col5" >12.02</td>
                        <td id="T_f2bc7_row9_col6" class="data row9 col6" >46.07</td>
                        <td id="T_f2bc7_row9_col7" class="data row9 col7" >34.52</td>
                        <td id="T_f2bc7_row9_col8" class="data row9 col8" >46.74</td>
                        <td id="T_f2bc7_row9_col9" class="data row9 col9" >8.32</td>
                        <td id="T_f2bc7_row9_col10" class="data row9 col10" >4.65</td>
                        <td id="T_f2bc7_row9_col11" class="data row9 col11" >-16.35</td>
                        <td id="T_f2bc7_row9_col12" class="data row9 col12" >18.66</td>
                        <td id="T_f2bc7_row9_col13" class="data row9 col13" >-667.81</td>
                        <td id="T_f2bc7_row9_col14" class="data row9 col14" >216.76</td>
                        <td id="T_f2bc7_row9_col15" class="data row9 col15" >7.17</td>
                        <td id="T_f2bc7_row9_col16" class="data row9 col16" >0.86</td>
                        <td id="T_f2bc7_row9_col17" class="data row9 col17" >114.91</td>
                        <td id="T_f2bc7_row9_col18" class="data row9 col18" >nan</td>
            </tr>
            <tr>
                        <th id="T_f2bc7_level0_row10" class="row_heading level0 row10" >600928.SS</th>
                        <td id="T_f2bc7_row10_col0" class="data row10 col0" >西安银行</td>
                        <td id="T_f2bc7_row10_col1" class="data row10 col1" >银行</td>
                        <td id="T_f2bc7_row10_col2" class="data row10 col2" >0.22</td>
                        <td id="T_f2bc7_row10_col3" class="data row10 col3" >91.50</td>
                        <td id="T_f2bc7_row10_col4" class="data row10 col4" >3.28</td>
                        <td id="T_f2bc7_row10_col5" class="data row10 col5" >11.59</td>
                        <td id="T_f2bc7_row10_col6" class="data row10 col6" >48.65</td>
                        <td id="T_f2bc7_row10_col7" class="data row10 col7" >20.98</td>
                        <td id="T_f2bc7_row10_col8" class="data row10 col8" >18.60</td>
                        <td id="T_f2bc7_row10_col9" class="data row10 col9" >9.04</td>
                        <td id="T_f2bc7_row10_col10" class="data row10 col10" >5.35</td>
                        <td id="T_f2bc7_row10_col11" class="data row10 col11" >-117.52</td>
                        <td id="T_f2bc7_row10_col12" class="data row10 col12" >121.09</td>
                        <td id="T_f2bc7_row10_col13" class="data row10 col13" >0.23</td>
                        <td id="T_f2bc7_row10_col14" class="data row10 col14" >40.11</td>
                        <td id="T_f2bc7_row10_col15" class="data row10 col15" >8.20</td>
                        <td id="T_f2bc7_row10_col16" class="data row10 col16" >0.91</td>
                        <td id="T_f2bc7_row10_col17" class="data row10 col17" >22.09</td>
                        <td id="T_f2bc7_row10_col18" class="data row10 col18" >-9526.44</td>
            </tr>
            <tr>
                        <th id="T_f2bc7_level0_row11" class="row_heading level0 row11" >002142.SZ</th>
                        <td id="T_f2bc7_row11_col0" class="data row11 col0" >宁波银行</td>
                        <td id="T_f2bc7_row11_col1" class="data row11 col1" >银行</td>
                        <td id="T_f2bc7_row11_col2" class="data row11 col2" >5.54</td>
                        <td id="T_f2bc7_row11_col3" class="data row11 col3" >92.69</td>
                        <td id="T_f2bc7_row11_col4" class="data row11 col4" >4.58</td>
                        <td id="T_f2bc7_row11_col5" class="data row11 col5" >16.34</td>
                        <td id="T_f2bc7_row11_col6" class="data row11 col6" >49.03</td>
                        <td id="T_f2bc7_row11_col7" class="data row11 col7" >19.23</td>
                        <td id="T_f2bc7_row11_col8" class="data row11 col8" >7.17</td>
                        <td id="T_f2bc7_row11_col9" class="data row11 col9" >17.40</td>
                        <td id="T_f2bc7_row11_col10" class="data row11 col10" >6.78</td>
                        <td id="T_f2bc7_row11_col11" class="data row11 col11" >-174.45</td>
                        <td id="T_f2bc7_row11_col12" class="data row11 col12" >231.84</td>
                        <td id="T_f2bc7_row11_col13" class="data row11 col13" >-71.86</td>
                        <td id="T_f2bc7_row11_col14" class="data row11 col14" >245.09</td>
                        <td id="T_f2bc7_row11_col15" class="data row11 col15" >16.08</td>
                        <td id="T_f2bc7_row11_col16" class="data row11 col16" >0.92</td>
                        <td id="T_f2bc7_row11_col17" class="data row11 col17" >253.84</td>
                        <td id="T_f2bc7_row11_col18" class="data row11 col18" >nan</td>
            </tr>
            <tr>
                        <th id="T_f2bc7_level0_row12" class="row_heading level0 row12" >002961.SZ</th>
                        <td id="T_f2bc7_row12_col0" class="data row12 col0" >瑞达期货</td>
                        <td id="T_f2bc7_row12_col1" class="data row12 col1" >非银金融</td>
                        <td id="T_f2bc7_row12_col2" class="data row12 col2" >0.08</td>
                        <td id="T_f2bc7_row12_col3" class="data row12 col3" >82.51</td>
                        <td id="T_f2bc7_row12_col4" class="data row12 col4" >1.21</td>
                        <td id="T_f2bc7_row12_col5" class="data row12 col5" >10.05</td>
                        <td id="T_f2bc7_row12_col6" class="data row12 col6" >21.88</td>
                        <td id="T_f2bc7_row12_col7" class="data row12 col7" >45.82</td>
                        <td id="T_f2bc7_row12_col8" class="data row12 col8" >57.73</td>
                        <td id="T_f2bc7_row12_col9" class="data row12 col9" >27.83</td>
                        <td id="T_f2bc7_row12_col10" class="data row12 col10" >69.67</td>
                        <td id="T_f2bc7_row12_col11" class="data row12 col11" >-19.07</td>
                        <td id="T_f2bc7_row12_col12" class="data row12 col12" >106.19</td>
                        <td id="T_f2bc7_row12_col13" class="data row12 col13" >-4.63</td>
                        <td id="T_f2bc7_row12_col14" class="data row12 col14" >4.07</td>
                        <td id="T_f2bc7_row12_col15" class="data row12 col15" >29.08</td>
                        <td id="T_f2bc7_row12_col16" class="data row12 col16" >1.04</td>
                        <td id="T_f2bc7_row12_col17" class="data row12 col17" >9.19</td>
                        <td id="T_f2bc7_row12_col18" class="data row12 col18" >nan</td>
            </tr>
            <tr>
                        <th id="T_f2bc7_level0_row13" class="row_heading level0 row13" >002948.SZ</th>
                        <td id="T_f2bc7_row13_col0" class="data row13 col0" >青岛银行</td>
                        <td id="T_f2bc7_row13_col1" class="data row13 col1" >银行</td>
                        <td id="T_f2bc7_row13_col2" class="data row13 col2" >0.13</td>
                        <td id="T_f2bc7_row13_col3" class="data row13 col3" >93.28</td>
                        <td id="T_f2bc7_row13_col4" class="data row13 col4" >0.00</td>
                        <td id="T_f2bc7_row13_col5" class="data row13 col5" >10.57</td>
                        <td id="T_f2bc7_row13_col6" class="data row13 col6" >40.35</td>
                        <td id="T_f2bc7_row13_col7" class="data row13 col7" >15.37</td>
                        <td id="T_f2bc7_row13_col8" class="data row13 col8" >7.42</td>
                        <td id="T_f2bc7_row13_col9" class="data row13 col9" >8.06</td>
                        <td id="T_f2bc7_row13_col10" class="data row13 col10" >4.29</td>
                        <td id="T_f2bc7_row13_col11" class="data row13 col11" >16.72</td>
                        <td id="T_f2bc7_row13_col12" class="data row13 col12" >104.19</td>
                        <td id="T_f2bc7_row13_col13" class="data row13 col13" >-540.26</td>
                        <td id="T_f2bc7_row13_col14" class="data row13 col14" >33.90</td>
                        <td id="T_f2bc7_row13_col15" class="data row13 col15" >9.13</td>
                        <td id="T_f2bc7_row13_col16" class="data row13 col16" >1.13</td>
                        <td id="T_f2bc7_row13_col17" class="data row13 col17" >22.68</td>
                        <td id="T_f2bc7_row13_col18" class="data row13 col18" >nan</td>
            </tr>
            <tr>
                        <th id="T_f2bc7_level0_row14" class="row_heading level0 row14" >600036.SS</th>
                        <td id="T_f2bc7_row14_col0" class="data row14 col0" >招商银行</td>
                        <td id="T_f2bc7_row14_col1" class="data row14 col1" >银行</td>
                        <td id="T_f2bc7_row14_col2" class="data row14 col2" >22.33</td>
                        <td id="T_f2bc7_row14_col3" class="data row14 col3" >91.27</td>
                        <td id="T_f2bc7_row14_col4" class="data row14 col4" >0.15</td>
                        <td id="T_f2bc7_row14_col5" class="data row14 col5" >15.46</td>
                        <td id="T_f2bc7_row14_col6" class="data row14 col6" >43.54</td>
                        <td id="T_f2bc7_row14_col7" class="data row14 col7" >11.97</td>
                        <td id="T_f2bc7_row14_col8" class="data row14 col8" >4.30</td>
                        <td id="T_f2bc7_row14_col9" class="data row14 col9" >11.65</td>
                        <td id="T_f2bc7_row14_col10" class="data row14 col10" >5.92</td>
                        <td id="T_f2bc7_row14_col11" class="data row14 col11" >-693.52</td>
                        <td id="T_f2bc7_row14_col12" class="data row14 col12" >1273.45</td>
                        <td id="T_f2bc7_row14_col13" class="data row14 col13" >-171200.16</td>
                        <td id="T_f2bc7_row14_col14" class="data row14 col14" >1472.13</td>
                        <td id="T_f2bc7_row14_col15" class="data row14 col15" >14.30</td>
                        <td id="T_f2bc7_row14_col16" class="data row14 col16" >1.23</td>
                        <td id="T_f2bc7_row14_col17" class="data row14 col17" >1452.16</td>
                        <td id="T_f2bc7_row14_col18" class="data row14 col18" >nan</td>
            </tr>
            <tr>
                        <th id="T_f2bc7_level0_row15" class="row_heading level0 row15" >600015.SS</th>
                        <td id="T_f2bc7_row15_col0" class="data row15 col0" >华夏银行</td>
                        <td id="T_f2bc7_row15_col1" class="data row15 col1" >银行</td>
                        <td id="T_f2bc7_row15_col2" class="data row15 col2" >1.25</td>
                        <td id="T_f2bc7_row15_col3" class="data row15 col3" >91.08</td>
                        <td id="T_f2bc7_row15_col4" class="data row15 col4" >11.77</td>
                        <td id="T_f2bc7_row15_col5" class="data row15 col5" >10.30</td>
                        <td id="T_f2bc7_row15_col6" class="data row15 col6" >35.99</td>
                        <td id="T_f2bc7_row15_col7" class="data row15 col7" >28.76</td>
                        <td id="T_f2bc7_row15_col8" class="data row15 col8" >40.00</td>
                        <td id="T_f2bc7_row15_col9" class="data row15 col9" >2.46</td>
                        <td id="T_f2bc7_row15_col10" class="data row15 col10" >4.62</td>
                        <td id="T_f2bc7_row15_col11" class="data row15 col11" >-54.10</td>
                        <td id="T_f2bc7_row15_col12" class="data row15 col12" >105.75</td>
                        <td id="T_f2bc7_row15_col13" class="data row15 col13" >-65.10</td>
                        <td id="T_f2bc7_row15_col14" class="data row15 col14" >284.95</td>
                        <td id="T_f2bc7_row15_col15" class="data row15 col15" >4.51</td>
                        <td id="T_f2bc7_row15_col16" class="data row15 col16" >1.83</td>
                        <td id="T_f2bc7_row15_col17" class="data row15 col17" >98.32</td>
                        <td id="T_f2bc7_row15_col18" class="data row15 col18" >nan</td>
            </tr>
            <tr>
                        <th id="T_f2bc7_level0_row16" class="row_heading level0 row16" >000001.SZ</th>
                        <td id="T_f2bc7_row16_col0" class="data row16 col0" >平安银行</td>
                        <td id="T_f2bc7_row16_col1" class="data row16 col1" >银行</td>
                        <td id="T_f2bc7_row16_col2" class="data row16 col2" >8.22</td>
                        <td id="T_f2bc7_row16_col3" class="data row16 col3" >91.85</td>
                        <td id="T_f2bc7_row16_col4" class="data row16 col4" >2.89</td>
                        <td id="T_f2bc7_row16_col5" class="data row16 col5" >10.19</td>
                        <td id="T_f2bc7_row16_col6" class="data row16 col6" >35.71</td>
                        <td id="T_f2bc7_row16_col7" class="data row16 col7" >10.19</td>
                        <td id="T_f2bc7_row16_col8" class="data row16 col8" >4.91</td>
                        <td id="T_f2bc7_row16_col9" class="data row16 col9" >7.74</td>
                        <td id="T_f2bc7_row16_col10" class="data row16 col10" >5.54</td>
                        <td id="T_f2bc7_row16_col11" class="data row16 col11" >-44.54</td>
                        <td id="T_f2bc7_row16_col12" class="data row16 col12" >13.22</td>
                        <td id="T_f2bc7_row16_col13" class="data row16 col13" >-165.25</td>
                        <td id="T_f2bc7_row16_col14" class="data row16 col14" >410.95</td>
                        <td id="T_f2bc7_row16_col15" class="data row16 col15" >15.19</td>
                        <td id="T_f2bc7_row16_col16" class="data row16 col16" >1.96</td>
                        <td id="T_f2bc7_row16_col17" class="data row16 col17" >463.61</td>
                        <td id="T_f2bc7_row16_col18" class="data row16 col18" >nan</td>
            </tr>
    </tbody></table>



### 观察列表






<style  type="text/css" >
#T_203d4_row0_col0,#T_203d4_row0_col1,#T_203d4_row0_col2,#T_203d4_row0_col3,#T_203d4_row0_col4,#T_203d4_row0_col5,#T_203d4_row0_col6,#T_203d4_row0_col7,#T_203d4_row0_col8,#T_203d4_row0_col9,#T_203d4_row0_col10,#T_203d4_row0_col12,#T_203d4_row0_col13,#T_203d4_row0_col14,#T_203d4_row0_col15,#T_203d4_row0_col16,#T_203d4_row0_col17,#T_203d4_row1_col0,#T_203d4_row1_col1,#T_203d4_row1_col2,#T_203d4_row1_col3,#T_203d4_row1_col4,#T_203d4_row1_col5,#T_203d4_row1_col6,#T_203d4_row1_col7,#T_203d4_row1_col8,#T_203d4_row1_col9,#T_203d4_row1_col10,#T_203d4_row1_col12,#T_203d4_row1_col14,#T_203d4_row1_col15,#T_203d4_row1_col16,#T_203d4_row1_col17,#T_203d4_row1_col18,#T_203d4_row2_col0,#T_203d4_row2_col1,#T_203d4_row2_col2,#T_203d4_row2_col3,#T_203d4_row2_col4,#T_203d4_row2_col5,#T_203d4_row2_col6,#T_203d4_row2_col7,#T_203d4_row2_col8,#T_203d4_row2_col9,#T_203d4_row2_col10,#T_203d4_row2_col12,#T_203d4_row2_col14,#T_203d4_row2_col15,#T_203d4_row2_col16,#T_203d4_row2_col17,#T_203d4_row2_col18,#T_203d4_row3_col0,#T_203d4_row3_col1,#T_203d4_row3_col2,#T_203d4_row3_col3,#T_203d4_row3_col4,#T_203d4_row3_col5,#T_203d4_row3_col6,#T_203d4_row3_col7,#T_203d4_row3_col8,#T_203d4_row3_col9,#T_203d4_row3_col10,#T_203d4_row3_col11,#T_203d4_row3_col12,#T_203d4_row3_col13,#T_203d4_row3_col14,#T_203d4_row3_col15,#T_203d4_row3_col16,#T_203d4_row3_col17,#T_203d4_row4_col0,#T_203d4_row4_col1,#T_203d4_row4_col2,#T_203d4_row4_col3,#T_203d4_row4_col4,#T_203d4_row4_col5,#T_203d4_row4_col6,#T_203d4_row4_col7,#T_203d4_row4_col8,#T_203d4_row4_col9,#T_203d4_row4_col10,#T_203d4_row4_col12,#T_203d4_row4_col14,#T_203d4_row4_col15,#T_203d4_row4_col16,#T_203d4_row4_col17,#T_203d4_row4_col18,#T_203d4_row5_col0,#T_203d4_row5_col1,#T_203d4_row5_col2,#T_203d4_row5_col3,#T_203d4_row5_col4,#T_203d4_row5_col5,#T_203d4_row5_col6,#T_203d4_row5_col7,#T_203d4_row5_col8,#T_203d4_row5_col9,#T_203d4_row5_col10,#T_203d4_row5_col11,#T_203d4_row5_col12,#T_203d4_row5_col13,#T_203d4_row5_col14,#T_203d4_row5_col15,#T_203d4_row5_col16,#T_203d4_row5_col17,#T_203d4_row5_col18,#T_203d4_row6_col0,#T_203d4_row6_col1,#T_203d4_row6_col2,#T_203d4_row6_col3,#T_203d4_row6_col4,#T_203d4_row6_col5,#T_203d4_row6_col6,#T_203d4_row6_col7,#T_203d4_row6_col8,#T_203d4_row6_col9,#T_203d4_row6_col10,#T_203d4_row6_col11,#T_203d4_row6_col12,#T_203d4_row6_col13,#T_203d4_row6_col14,#T_203d4_row6_col15,#T_203d4_row6_col16,#T_203d4_row6_col17,#T_203d4_row6_col18,#T_203d4_row7_col0,#T_203d4_row7_col1,#T_203d4_row7_col2,#T_203d4_row7_col3,#T_203d4_row7_col4,#T_203d4_row7_col5,#T_203d4_row7_col6,#T_203d4_row7_col7,#T_203d4_row7_col8,#T_203d4_row7_col9,#T_203d4_row7_col10,#T_203d4_row7_col11,#T_203d4_row7_col12,#T_203d4_row7_col13,#T_203d4_row7_col14,#T_203d4_row7_col15,#T_203d4_row7_col16,#T_203d4_row7_col17,#T_203d4_row8_col0,#T_203d4_row8_col1,#T_203d4_row8_col2,#T_203d4_row8_col3,#T_203d4_row8_col4,#T_203d4_row8_col5,#T_203d4_row8_col6,#T_203d4_row8_col7,#T_203d4_row8_col8,#T_203d4_row8_col9,#T_203d4_row8_col10,#T_203d4_row8_col11,#T_203d4_row8_col12,#T_203d4_row8_col13,#T_203d4_row8_col14,#T_203d4_row8_col15,#T_203d4_row8_col16,#T_203d4_row8_col17,#T_203d4_row8_col18,#T_203d4_row9_col0,#T_203d4_row9_col1,#T_203d4_row9_col2,#T_203d4_row9_col3,#T_203d4_row9_col4,#T_203d4_row9_col5,#T_203d4_row9_col6,#T_203d4_row9_col7,#T_203d4_row9_col8,#T_203d4_row9_col9,#T_203d4_row9_col10,#T_203d4_row9_col11,#T_203d4_row9_col12,#T_203d4_row9_col13,#T_203d4_row9_col14,#T_203d4_row9_col15,#T_203d4_row9_col16,#T_203d4_row9_col17,#T_203d4_row10_col0,#T_203d4_row10_col1,#T_203d4_row10_col2,#T_203d4_row10_col3,#T_203d4_row10_col4,#T_203d4_row10_col5,#T_203d4_row10_col6,#T_203d4_row10_col7,#T_203d4_row10_col8,#T_203d4_row10_col9,#T_203d4_row10_col10,#T_203d4_row10_col11,#T_203d4_row10_col12,#T_203d4_row10_col13,#T_203d4_row10_col14,#T_203d4_row10_col15,#T_203d4_row10_col16,#T_203d4_row10_col17,#T_203d4_row11_col0,#T_203d4_row11_col1,#T_203d4_row11_col2,#T_203d4_row11_col3,#T_203d4_row11_col4,#T_203d4_row11_col5,#T_203d4_row11_col6,#T_203d4_row11_col7,#T_203d4_row11_col8,#T_203d4_row11_col9,#T_203d4_row11_col10,#T_203d4_row11_col12,#T_203d4_row11_col13,#T_203d4_row11_col14,#T_203d4_row11_col15,#T_203d4_row11_col16,#T_203d4_row11_col17,#T_203d4_row12_col0,#T_203d4_row12_col1,#T_203d4_row12_col2,#T_203d4_row12_col3,#T_203d4_row12_col4,#T_203d4_row12_col5,#T_203d4_row12_col6,#T_203d4_row12_col7,#T_203d4_row12_col8,#T_203d4_row12_col9,#T_203d4_row12_col10,#T_203d4_row12_col11,#T_203d4_row12_col12,#T_203d4_row12_col13,#T_203d4_row12_col14,#T_203d4_row12_col15,#T_203d4_row12_col16,#T_203d4_row12_col17,#T_203d4_row12_col18,#T_203d4_row13_col0,#T_203d4_row13_col1,#T_203d4_row13_col2,#T_203d4_row13_col3,#T_203d4_row13_col4,#T_203d4_row13_col5,#T_203d4_row13_col6,#T_203d4_row13_col7,#T_203d4_row13_col8,#T_203d4_row13_col10,#T_203d4_row13_col11,#T_203d4_row13_col12,#T_203d4_row13_col14,#T_203d4_row13_col16,#T_203d4_row13_col17,#T_203d4_row13_col18,#T_203d4_row14_col0,#T_203d4_row14_col1,#T_203d4_row14_col2,#T_203d4_row14_col3,#T_203d4_row14_col4,#T_203d4_row14_col5,#T_203d4_row14_col6,#T_203d4_row14_col7,#T_203d4_row14_col8,#T_203d4_row14_col9,#T_203d4_row14_col10,#T_203d4_row14_col12,#T_203d4_row14_col14,#T_203d4_row14_col15,#T_203d4_row14_col16,#T_203d4_row14_col17,#T_203d4_row14_col18,#T_203d4_row15_col0,#T_203d4_row15_col1,#T_203d4_row15_col2,#T_203d4_row15_col3,#T_203d4_row15_col4,#T_203d4_row15_col5,#T_203d4_row15_col6,#T_203d4_row15_col7,#T_203d4_row15_col8,#T_203d4_row15_col9,#T_203d4_row15_col10,#T_203d4_row15_col11,#T_203d4_row15_col12,#T_203d4_row15_col13,#T_203d4_row15_col14,#T_203d4_row15_col15,#T_203d4_row15_col16,#T_203d4_row15_col17,#T_203d4_row16_col0,#T_203d4_row16_col1,#T_203d4_row16_col2,#T_203d4_row16_col3,#T_203d4_row16_col4,#T_203d4_row16_col5,#T_203d4_row16_col6,#T_203d4_row16_col7,#T_203d4_row16_col8,#T_203d4_row16_col9,#T_203d4_row16_col10,#T_203d4_row16_col12,#T_203d4_row16_col14,#T_203d4_row16_col15,#T_203d4_row16_col16,#T_203d4_row16_col17,#T_203d4_row16_col18,#T_203d4_row17_col0,#T_203d4_row17_col1,#T_203d4_row17_col2,#T_203d4_row17_col3,#T_203d4_row17_col4,#T_203d4_row17_col5,#T_203d4_row17_col6,#T_203d4_row17_col7,#T_203d4_row17_col8,#T_203d4_row17_col9,#T_203d4_row17_col10,#T_203d4_row17_col11,#T_203d4_row17_col12,#T_203d4_row17_col13,#T_203d4_row17_col14,#T_203d4_row17_col15,#T_203d4_row17_col16,#T_203d4_row17_col17,#T_203d4_row17_col18,#T_203d4_row18_col0,#T_203d4_row18_col1,#T_203d4_row18_col2,#T_203d4_row18_col3,#T_203d4_row18_col4,#T_203d4_row18_col5,#T_203d4_row18_col6,#T_203d4_row18_col7,#T_203d4_row18_col8,#T_203d4_row18_col9,#T_203d4_row18_col10,#T_203d4_row18_col11,#T_203d4_row18_col12,#T_203d4_row18_col13,#T_203d4_row18_col14,#T_203d4_row18_col15,#T_203d4_row18_col16,#T_203d4_row18_col17,#T_203d4_row19_col0,#T_203d4_row19_col1,#T_203d4_row19_col2,#T_203d4_row19_col3,#T_203d4_row19_col4,#T_203d4_row19_col5,#T_203d4_row19_col6,#T_203d4_row19_col7,#T_203d4_row19_col8,#T_203d4_row19_col9,#T_203d4_row19_col10,#T_203d4_row19_col11,#T_203d4_row19_col12,#T_203d4_row19_col13,#T_203d4_row19_col14,#T_203d4_row19_col15,#T_203d4_row19_col16,#T_203d4_row19_col17,#T_203d4_row19_col18,#T_203d4_row20_col0,#T_203d4_row20_col1,#T_203d4_row20_col2,#T_203d4_row20_col3,#T_203d4_row20_col4,#T_203d4_row20_col5,#T_203d4_row20_col6,#T_203d4_row20_col7,#T_203d4_row20_col8,#T_203d4_row20_col9,#T_203d4_row20_col10,#T_203d4_row20_col12,#T_203d4_row20_col14,#T_203d4_row20_col15,#T_203d4_row20_col16,#T_203d4_row20_col17,#T_203d4_row20_col18{
            color:  black;
        }#T_203d4_row0_col11,#T_203d4_row0_col18,#T_203d4_row1_col11,#T_203d4_row1_col13,#T_203d4_row2_col11,#T_203d4_row2_col13,#T_203d4_row3_col18,#T_203d4_row4_col11,#T_203d4_row4_col13,#T_203d4_row7_col18,#T_203d4_row9_col18,#T_203d4_row10_col18,#T_203d4_row11_col11,#T_203d4_row11_col18,#T_203d4_row13_col9,#T_203d4_row13_col13,#T_203d4_row13_col15,#T_203d4_row14_col11,#T_203d4_row14_col13,#T_203d4_row15_col18,#T_203d4_row16_col11,#T_203d4_row16_col13,#T_203d4_row18_col18,#T_203d4_row20_col11,#T_203d4_row20_col13{
            color:  red;
        }</style><table id="T_203d4_" ><thead>    <tr>        <th class="blank level0" ></th>        <th class="col_heading level0 col0" >名称</th>        <th class="col_heading level0 col1" >行业</th>        <th class="col_heading level0 col2" >权重</th>        <th class="col_heading level0 col3" >负债率</th>        <th class="col_heading level0 col4" >应收比</th>        <th class="col_heading level0 col5" >ROE</th>        <th class="col_heading level0 col6" >利润率</th>        <th class="col_heading level0 col7" >收入增长</th>        <th class="col_heading level0 col8" >收入波动</th>        <th class="col_heading level0 col9" >盈利增长</th>        <th class="col_heading level0 col10" >盈利波动</th>        <th class="col_heading level0 col11" >FCF增长</th>        <th class="col_heading level0 col12" >FCF波动</th>        <th class="col_heading level0 col13" >DCF</th>        <th class="col_heading level0 col14" >盈利折现</th>        <th class="col_heading level0 col15" >PE</th>        <th class="col_heading level0 col16" >PEG</th>        <th class="col_heading level0 col17" >市值</th>        <th class="col_heading level0 col18" >折价率</th>    </tr>    <tr>        <th class="index_name level0" >Symbol</th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>    </tr></thead><tbody>
                <tr>
                        <th id="T_203d4_level0_row0" class="row_heading level0 row0" >300750.SZ</th>
                        <td id="T_203d4_row0_col0" class="data row0 col0" >宁德时代</td>
                        <td id="T_203d4_row0_col1" class="data row0 col1" >电气设备</td>
                        <td id="T_203d4_row0_col2" class="data row0 col2" >19.98</td>
                        <td id="T_203d4_row0_col3" class="data row0 col3" >55.82</td>
                        <td id="T_203d4_row0_col4" class="data row0 col4" >48.95</td>
                        <td id="T_203d4_row0_col5" class="data row0 col5" >11.66</td>
                        <td id="T_203d4_row0_col6" class="data row0 col6" >12.97</td>
                        <td id="T_203d4_row0_col7" class="data row0 col7" >37.54</td>
                        <td id="T_203d4_row0_col8" class="data row0 col8" >24.16</td>
                        <td id="T_203d4_row0_col9" class="data row0 col9" >14.80</td>
                        <td id="T_203d4_row0_col10" class="data row0 col10" >24.56</td>
                        <td id="T_203d4_row0_col11" class="data row0 col11" >-61.23</td>
                        <td id="T_203d4_row0_col12" class="data row0 col12" >122.10</td>
                        <td id="T_203d4_row0_col13" class="data row0 col13" >2.58</td>
                        <td id="T_203d4_row0_col14" class="data row0 col14" >81.30</td>
                        <td id="T_203d4_row0_col15" class="data row0 col15" >145.51</td>
                        <td id="T_203d4_row0_col16" class="data row0 col16" >9.83</td>
                        <td id="T_203d4_row0_col17" class="data row0 col17" >988.86</td>
                        <td id="T_203d4_row0_col18" class="data row0 col18" >-38242.87</td>
            </tr>
            <tr>
                        <th id="T_203d4_level0_row1" class="row_heading level0 row1" >600036.SS</th>
                        <td id="T_203d4_row1_col0" class="data row1 col0" >招商银行</td>
                        <td id="T_203d4_row1_col1" class="data row1 col1" >银行</td>
                        <td id="T_203d4_row1_col2" class="data row1 col2" >22.33</td>
                        <td id="T_203d4_row1_col3" class="data row1 col3" >91.27</td>
                        <td id="T_203d4_row1_col4" class="data row1 col4" >0.15</td>
                        <td id="T_203d4_row1_col5" class="data row1 col5" >15.46</td>
                        <td id="T_203d4_row1_col6" class="data row1 col6" >43.54</td>
                        <td id="T_203d4_row1_col7" class="data row1 col7" >11.97</td>
                        <td id="T_203d4_row1_col8" class="data row1 col8" >4.30</td>
                        <td id="T_203d4_row1_col9" class="data row1 col9" >11.65</td>
                        <td id="T_203d4_row1_col10" class="data row1 col10" >5.92</td>
                        <td id="T_203d4_row1_col11" class="data row1 col11" >-693.52</td>
                        <td id="T_203d4_row1_col12" class="data row1 col12" >1273.45</td>
                        <td id="T_203d4_row1_col13" class="data row1 col13" >-171200.16</td>
                        <td id="T_203d4_row1_col14" class="data row1 col14" >1472.13</td>
                        <td id="T_203d4_row1_col15" class="data row1 col15" >14.30</td>
                        <td id="T_203d4_row1_col16" class="data row1 col16" >1.23</td>
                        <td id="T_203d4_row1_col17" class="data row1 col17" >1452.16</td>
                        <td id="T_203d4_row1_col18" class="data row1 col18" >nan</td>
            </tr>
            <tr>
                        <th id="T_203d4_level0_row2" class="row_heading level0 row2" >601899.SS</th>
                        <td id="T_203d4_row2_col0" class="data row2 col0" >紫金矿业</td>
                        <td id="T_203d4_row2_col1" class="data row2 col1" >有色金属</td>
                        <td id="T_203d4_row2_col2" class="data row2 col2" >11.69</td>
                        <td id="T_203d4_row2_col3" class="data row2 col3" >59.08</td>
                        <td id="T_203d4_row2_col4" class="data row2 col4" >2.95</td>
                        <td id="T_203d4_row2_col5" class="data row2 col5" >10.01</td>
                        <td id="T_203d4_row2_col6" class="data row2 col6" >3.63</td>
                        <td id="T_203d4_row2_col7" class="data row2 col7" >22.17</td>
                        <td id="T_203d4_row2_col8" class="data row2 col8" >8.80</td>
                        <td id="T_203d4_row2_col9" class="data row2 col9" >24.43</td>
                        <td id="T_203d4_row2_col10" class="data row2 col10" >24.57</td>
                        <td id="T_203d4_row2_col11" class="data row2 col11" >-110.17</td>
                        <td id="T_203d4_row2_col12" class="data row2 col12" >54.13</td>
                        <td id="T_203d4_row2_col13" class="data row2 col13" >-0.16</td>
                        <td id="T_203d4_row2_col14" class="data row2 col14" >107.81</td>
                        <td id="T_203d4_row2_col15" class="data row2 col15" >35.81</td>
                        <td id="T_203d4_row2_col16" class="data row2 col16" >1.47</td>
                        <td id="T_203d4_row2_col17" class="data row2 col17" >285.72</td>
                        <td id="T_203d4_row2_col18" class="data row2 col18" >nan</td>
            </tr>
            <tr>
                        <th id="T_203d4_level0_row3" class="row_heading level0 row3" >600489.SS</th>
                        <td id="T_203d4_row3_col0" class="data row3 col0" >中金黄金</td>
                        <td id="T_203d4_row3_col1" class="data row3 col1" >有色金属</td>
                        <td id="T_203d4_row3_col2" class="data row3 col2" >1.74</td>
                        <td id="T_203d4_row3_col3" class="data row3 col3" >44.27</td>
                        <td id="T_203d4_row3_col4" class="data row3 col4" >1.66</td>
                        <td id="T_203d4_row3_col5" class="data row3 col5" >2.88</td>
                        <td id="T_203d4_row3_col6" class="data row3 col6" >1.29</td>
                        <td id="T_203d4_row3_col7" class="data row3 col7" >13.63</td>
                        <td id="T_203d4_row3_col8" class="data row3 col8" >9.29</td>
                        <td id="T_203d4_row3_col9" class="data row3 col9" >242.86</td>
                        <td id="T_203d4_row3_col10" class="data row3 col10" >456.40</td>
                        <td id="T_203d4_row3_col11" class="data row3 col11" >33.70</td>
                        <td id="T_203d4_row3_col12" class="data row3 col12" >333.14</td>
                        <td id="T_203d4_row3_col13" class="data row3 col13" >28.07</td>
                        <td id="T_203d4_row3_col14" class="data row3 col14" >248.78</td>
                        <td id="T_203d4_row3_col15" class="data row3 col15" >24.64</td>
                        <td id="T_203d4_row3_col16" class="data row3 col16" >0.10</td>
                        <td id="T_203d4_row3_col17" class="data row3 col17" >46.24</td>
                        <td id="T_203d4_row3_col18" class="data row3 col18" >-64.76</td>
            </tr>
            <tr>
                        <th id="T_203d4_level0_row4" class="row_heading level0 row4" >000725.SZ</th>
                        <td id="T_203d4_row4_col0" class="data row4 col0" >京东方Ａ</td>
                        <td id="T_203d4_row4_col1" class="data row4 col1" >电子</td>
                        <td id="T_203d4_row4_col2" class="data row4 col2" >5.69</td>
                        <td id="T_203d4_row4_col3" class="data row4 col3" >59.13</td>
                        <td id="T_203d4_row4_col4" class="data row4 col4" >17.60</td>
                        <td id="T_203d4_row4_col5" class="data row4 col5" >4.95</td>
                        <td id="T_203d4_row4_col6" class="data row4 col6" >4.24</td>
                        <td id="T_203d4_row4_col7" class="data row4 col7" >13.28</td>
                        <td id="T_203d4_row4_col8" class="data row4 col8" >8.55</td>
                        <td id="T_203d4_row4_col9" class="data row4 col9" >21.23</td>
                        <td id="T_203d4_row4_col10" class="data row4 col10" >122.41</td>
                        <td id="T_203d4_row4_col11" class="data row4 col11" >-20.20</td>
                        <td id="T_203d4_row4_col12" class="data row4 col12" >57.98</td>
                        <td id="T_203d4_row4_col13" class="data row4 col13" >-134.15</td>
                        <td id="T_203d4_row4_col14" class="data row4 col14" >97.79</td>
                        <td id="T_203d4_row4_col15" class="data row4 col15" >22.61</td>
                        <td id="T_203d4_row4_col16" class="data row4 col16" >1.06</td>
                        <td id="T_203d4_row4_col17" class="data row4 col17" >218.19</td>
                        <td id="T_203d4_row4_col18" class="data row4 col18" >nan</td>
            </tr>
            <tr>
                        <th id="T_203d4_level0_row5" class="row_heading level0 row5" >600585.SS</th>
                        <td id="T_203d4_row5_col0" class="data row5 col0" >海螺水泥</td>
                        <td id="T_203d4_row5_col1" class="data row5 col1" >建筑材料</td>
                        <td id="T_203d4_row5_col2" class="data row5 col2" >19.68</td>
                        <td id="T_203d4_row5_col3" class="data row5 col3" >16.30</td>
                        <td id="T_203d4_row5_col4" class="data row5 col4" >7.17</td>
                        <td id="T_203d4_row5_col5" class="data row5 col5" >22.59</td>
                        <td id="T_203d4_row5_col6" class="data row5 col6" >21.40</td>
                        <td id="T_203d4_row5_col7" class="data row5 col7" >35.01</td>
                        <td id="T_203d4_row5_col8" class="data row5 col8" >31.14</td>
                        <td id="T_203d4_row5_col9" class="data row5 col9" >35.10</td>
                        <td id="T_203d4_row5_col10" class="data row5 col10" >46.03</td>
                        <td id="T_203d4_row5_col11" class="data row5 col11" >36.04</td>
                        <td id="T_203d4_row5_col12" class="data row5 col12" >80.90</td>
                        <td id="T_203d4_row5_col13" class="data row5 col13" >768.24</td>
                        <td id="T_203d4_row5_col14" class="data row5 col14" >847.14</td>
                        <td id="T_203d4_row5_col15" class="data row5 col15" >7.11</td>
                        <td id="T_203d4_row5_col16" class="data row5 col16" >0.20</td>
                        <td id="T_203d4_row5_col17" class="data row5 col17" >256.22</td>
                        <td id="T_203d4_row5_col18" class="data row5 col18" >66.65</td>
            </tr>
            <tr>
                        <th id="T_203d4_level0_row6" class="row_heading level0 row6" >600900.SS</th>
                        <td id="T_203d4_row6_col0" class="data row6 col0" >长江电力</td>
                        <td id="T_203d4_row6_col1" class="data row6 col1" >公用事业</td>
                        <td id="T_203d4_row6_col2" class="data row6 col2" >17.05</td>
                        <td id="T_203d4_row6_col3" class="data row6 col3" >46.10</td>
                        <td id="T_203d4_row6_col4" class="data row6 col4" >8.85</td>
                        <td id="T_203d4_row6_col5" class="data row6 col5" >15.52</td>
                        <td id="T_203d4_row6_col6" class="data row6 col6" >44.31</td>
                        <td id="T_203d4_row6_col7" class="data row6 col7" >5.12</td>
                        <td id="T_203d4_row6_col8" class="data row6 col8" >9.59</td>
                        <td id="T_203d4_row6_col9" class="data row6 col9" >6.31</td>
                        <td id="T_203d4_row6_col10" class="data row6 col10" >14.01</td>
                        <td id="T_203d4_row6_col11" class="data row6 col11" >0.54</td>
                        <td id="T_203d4_row6_col12" class="data row6 col12" >9.49</td>
                        <td id="T_203d4_row6_col13" class="data row6 col13" >467.21</td>
                        <td id="T_203d4_row6_col14" class="data row6 col14" >349.08</td>
                        <td id="T_203d4_row6_col15" class="data row6 col15" >16.77</td>
                        <td id="T_203d4_row6_col16" class="data row6 col16" >2.66</td>
                        <td id="T_203d4_row6_col17" class="data row6 col17" >450.74</td>
                        <td id="T_203d4_row6_col18" class="data row6 col18" >3.52</td>
            </tr>
            <tr>
                        <th id="T_203d4_level0_row7" class="row_heading level0 row7" >603288.SS</th>
                        <td id="T_203d4_row7_col0" class="data row7 col0" >海天味业</td>
                        <td id="T_203d4_row7_col1" class="data row7 col1" >食品饮料</td>
                        <td id="T_203d4_row7_col2" class="data row7 col2" >5.16</td>
                        <td id="T_203d4_row7_col3" class="data row7 col3" >31.72</td>
                        <td id="T_203d4_row7_col4" class="data row7 col4" >0.21</td>
                        <td id="T_203d4_row7_col5" class="data row7 col5" >31.42</td>
                        <td id="T_203d4_row7_col6" class="data row7 col6" >26.24</td>
                        <td id="T_203d4_row7_col7" class="data row7 col7" >16.05</td>
                        <td id="T_203d4_row7_col8" class="data row7 col8" >0.85</td>
                        <td id="T_203d4_row7_col9" class="data row7 col9" >21.95</td>
                        <td id="T_203d4_row7_col10" class="data row7 col10" >2.08</td>
                        <td id="T_203d4_row7_col11" class="data row7 col11" >11.37</td>
                        <td id="T_203d4_row7_col12" class="data row7 col12" >15.72</td>
                        <td id="T_203d4_row7_col13" class="data row7 col13" >95.46</td>
                        <td id="T_203d4_row7_col14" class="data row7 col14" >108.81</td>
                        <td id="T_203d4_row7_col15" class="data row7 col15" >86.22</td>
                        <td id="T_203d4_row7_col16" class="data row7 col16" >3.93</td>
                        <td id="T_203d4_row7_col17" class="data row7 col17" >581.42</td>
                        <td id="T_203d4_row7_col18" class="data row7 col18" >-509.06</td>
            </tr>
            <tr>
                        <th id="T_203d4_level0_row8" class="row_heading level0 row8" >600030.SS</th>
                        <td id="T_203d4_row8_col0" class="data row8 col0" >中信证券</td>
                        <td id="T_203d4_row8_col1" class="data row8 col1" >非银金融</td>
                        <td id="T_203d4_row8_col2" class="data row8 col2" >8.34</td>
                        <td id="T_203d4_row8_col3" class="data row8 col3" >82.35</td>
                        <td id="T_203d4_row8_col4" class="data row8 col4" >293.77</td>
                        <td id="T_203d4_row8_col5" class="data row8 col5" >7.53</td>
                        <td id="T_203d4_row8_col6" class="data row8 col6" >27.81</td>
                        <td id="T_203d4_row8_col7" class="data row8 col7" >9.51</td>
                        <td id="T_203d4_row8_col8" class="data row8 col8" >22.12</td>
                        <td id="T_203d4_row8_col9" class="data row8 col9" >13.17</td>
                        <td id="T_203d4_row8_col10" class="data row8 col10" >27.55</td>
                        <td id="T_203d4_row8_col11" class="data row8 col11" >50.91</td>
                        <td id="T_203d4_row8_col12" class="data row8 col12" >279.93</td>
                        <td id="T_203d4_row8_col13" class="data row8 col13" >765.84</td>
                        <td id="T_203d4_row8_col14" class="data row8 col14" >219.74</td>
                        <td id="T_203d4_row8_col15" class="data row8 col15" >20.37</td>
                        <td id="T_203d4_row8_col16" class="data row8 col16" >1.55</td>
                        <td id="T_203d4_row8_col17" class="data row8 col17" >325.75</td>
                        <td id="T_203d4_row8_col18" class="data row8 col18" >57.46</td>
            </tr>
            <tr>
                        <th id="T_203d4_level0_row9" class="row_heading level0 row9" >601888.SS</th>
                        <td id="T_203d4_row9_col0" class="data row9 col0" >中国中免</td>
                        <td id="T_203d4_row9_col1" class="data row9 col1" >休闲服务</td>
                        <td id="T_203d4_row9_col2" class="data row9 col2" >70.74</td>
                        <td id="T_203d4_row9_col3" class="data row9 col3" >37.55</td>
                        <td id="T_203d4_row9_col4" class="data row9 col4" >2.34</td>
                        <td id="T_203d4_row9_col5" class="data row9 col5" >21.92</td>
                        <td id="T_203d4_row9_col6" class="data row9 col6" >9.18</td>
                        <td id="T_203d4_row9_col7" class="data row9 col7" >25.94</td>
                        <td id="T_203d4_row9_col8" class="data row9 col8" >34.96</td>
                        <td id="T_203d4_row9_col9" class="data row9 col9" >34.84</td>
                        <td id="T_203d4_row9_col10" class="data row9 col10" >13.83</td>
                        <td id="T_203d4_row9_col11" class="data row9 col11" >105.58</td>
                        <td id="T_203d4_row9_col12" class="data row9 col12" >204.00</td>
                        <td id="T_203d4_row9_col13" class="data row9 col13" >309.81</td>
                        <td id="T_203d4_row9_col14" class="data row9 col14" >120.76</td>
                        <td id="T_203d4_row9_col15" class="data row9 col15" >70.49</td>
                        <td id="T_203d4_row9_col16" class="data row9 col16" >2.02</td>
                        <td id="T_203d4_row9_col17" class="data row9 col17" >635.14</td>
                        <td id="T_203d4_row9_col18" class="data row9 col18" >-105.01</td>
            </tr>
            <tr>
                        <th id="T_203d4_level0_row10" class="row_heading level0 row10" >000333.SZ</th>
                        <td id="T_203d4_row10_col0" class="data row10 col0" >美的集团</td>
                        <td id="T_203d4_row10_col1" class="data row10 col1" >家用电器</td>
                        <td id="T_203d4_row10_col2" class="data row10 col2" >38.73</td>
                        <td id="T_203d4_row10_col3" class="data row10 col3" >65.53</td>
                        <td id="T_203d4_row10_col4" class="data row10 col4" >22.82</td>
                        <td id="T_203d4_row10_col5" class="data row10 col5" >23.69</td>
                        <td id="T_203d4_row10_col6" class="data row10 col6" >8.31</td>
                        <td id="T_203d4_row10_col7" class="data row10 col7" >5.73</td>
                        <td id="T_203d4_row10_col8" class="data row10 col8" >3.11</td>
                        <td id="T_203d4_row10_col9" class="data row10 col9" >16.39</td>
                        <td id="T_203d4_row10_col10" class="data row10 col10" >3.66</td>
                        <td id="T_203d4_row10_col11" class="data row10 col11" >11.21</td>
                        <td id="T_203d4_row10_col12" class="data row10 col12" >43.88</td>
                        <td id="T_203d4_row10_col13" class="data row10 col13" >442.10</td>
                        <td id="T_203d4_row10_col14" class="data row10 col14" >431.73</td>
                        <td id="T_203d4_row10_col15" class="data row10 col15" >19.39</td>
                        <td id="T_203d4_row10_col16" class="data row10 col16" >1.18</td>
                        <td id="T_203d4_row10_col17" class="data row10 col17" >560.09</td>
                        <td id="T_203d4_row10_col18" class="data row10 col18" >-26.69</td>
            </tr>
            <tr>
                        <th id="T_203d4_level0_row11" class="row_heading level0 row11" >601398.SS</th>
                        <td id="T_203d4_row11_col0" class="data row11 col0" >工商银行</td>
                        <td id="T_203d4_row11_col1" class="data row11 col1" >银行</td>
                        <td id="T_203d4_row11_col2" class="data row11 col2" >4.63</td>
                        <td id="T_203d4_row11_col3" class="data row11 col3" >91.27</td>
                        <td id="T_203d4_row11_col4" class="data row11 col4" >139.76</td>
                        <td id="T_203d4_row11_col5" class="data row11 col5" >12.72</td>
                        <td id="T_203d4_row11_col6" class="data row11 col6" >50.13</td>
                        <td id="T_203d4_row11_col7" class="data row11 col7" >0.07</td>
                        <td id="T_203d4_row11_col8" class="data row11 col8" >2.42</td>
                        <td id="T_203d4_row11_col9" class="data row11 col9" >3.38</td>
                        <td id="T_203d4_row11_col10" class="data row11 col10" >1.95</td>
                        <td id="T_203d4_row11_col11" class="data row11 col11" >-104.59</td>
                        <td id="T_203d4_row11_col12" class="data row11 col12" >139.60</td>
                        <td id="T_203d4_row11_col13" class="data row11 col13" >4.22</td>
                        <td id="T_203d4_row11_col14" class="data row11 col14" >4221.19</td>
                        <td id="T_203d4_row11_col15" class="data row11 col15" >5.83</td>
                        <td id="T_203d4_row11_col16" class="data row11 col16" >1.73</td>
                        <td id="T_203d4_row11_col17" class="data row11 col17" >1849.75</td>
                        <td id="T_203d4_row11_col18" class="data row11 col18" >-43783.93</td>
            </tr>
            <tr>
                        <th id="T_203d4_level0_row12" class="row_heading level0 row12" >000895.SZ</th>
                        <td id="T_203d4_row12_col0" class="data row12 col0" >双汇发展</td>
                        <td id="T_203d4_row12_col1" class="data row12 col1" >食品饮料</td>
                        <td id="T_203d4_row12_col2" class="data row12 col2" >1.11</td>
                        <td id="T_203d4_row12_col3" class="data row12 col3" >30.46</td>
                        <td id="T_203d4_row12_col4" class="data row12 col4" >1.32</td>
                        <td id="T_203d4_row12_col5" class="data row12 col5" >31.63</td>
                        <td id="T_203d4_row12_col6" class="data row12 col6" >9.01</td>
                        <td id="T_203d4_row12_col7" class="data row12 col7" >14.21</td>
                        <td id="T_203d4_row12_col8" class="data row12 col8" >15.19</td>
                        <td id="T_203d4_row12_col9" class="data row12 col9" >13.15</td>
                        <td id="T_203d4_row12_col10" class="data row12 col10" >2.22</td>
                        <td id="T_203d4_row12_col11" class="data row12 col11" >25.11</td>
                        <td id="T_203d4_row12_col12" class="data row12 col12" >68.40</td>
                        <td id="T_203d4_row12_col13" class="data row12 col13" >124.42</td>
                        <td id="T_203d4_row12_col14" class="data row12 col14" >93.82</td>
                        <td id="T_203d4_row12_col15" class="data row12 col15" >19.53</td>
                        <td id="T_203d4_row12_col16" class="data row12 col16" >1.48</td>
                        <td id="T_203d4_row12_col17" class="data row12 col17" >121.68</td>
                        <td id="T_203d4_row12_col18" class="data row12 col18" >2.20</td>
            </tr>
            <tr>
                        <th id="T_203d4_level0_row13" class="row_heading level0 row13" >600340.SS</th>
                        <td id="T_203d4_row13_col0" class="data row13 col0" >华夏幸福</td>
                        <td id="T_203d4_row13_col1" class="data row13 col1" >房地产</td>
                        <td id="T_203d4_row13_col2" class="data row13 col2" >0.93</td>
                        <td id="T_203d4_row13_col3" class="data row13 col3" >81.29</td>
                        <td id="T_203d4_row13_col4" class="data row13 col4" >212.96</td>
                        <td id="T_203d4_row13_col5" class="data row13 col5" >21.44</td>
                        <td id="T_203d4_row13_col6" class="data row13 col6" >11.59</td>
                        <td id="T_203d4_row13_col7" class="data row13 col7" >20.76</td>
                        <td id="T_203d4_row13_col8" class="data row13 col8" >22.55</td>
                        <td id="T_203d4_row13_col9" class="data row13 col9" >-5.88</td>
                        <td id="T_203d4_row13_col10" class="data row13 col10" >59.94</td>
                        <td id="T_203d4_row13_col11" class="data row13 col11" >57.88</td>
                        <td id="T_203d4_row13_col12" class="data row13 col12" >164.51</td>
                        <td id="T_203d4_row13_col13" class="data row13 col13" >-1107.54</td>
                        <td id="T_203d4_row13_col14" class="data row13 col14" >104.44</td>
                        <td id="T_203d4_row13_col15" class="data row13 col15" >-7.52</td>
                        <td id="T_203d4_row13_col16" class="data row13 col16" >1.28</td>
                        <td id="T_203d4_row13_col17" class="data row13 col17" >21.84</td>
                        <td id="T_203d4_row13_col18" class="data row13 col18" >nan</td>
            </tr>
            <tr>
                        <th id="T_203d4_level0_row14" class="row_heading level0 row14" >600887.SS</th>
                        <td id="T_203d4_row14_col0" class="data row14 col0" >伊利股份</td>
                        <td id="T_203d4_row14_col1" class="data row14 col1" >食品饮料</td>
                        <td id="T_203d4_row14_col2" class="data row14 col2" >6.65</td>
                        <td id="T_203d4_row14_col3" class="data row14 col3" >57.09</td>
                        <td id="T_203d4_row14_col4" class="data row14 col4" >6.81</td>
                        <td id="T_203d4_row14_col5" class="data row14 col5" >24.20</td>
                        <td id="T_203d4_row14_col6" class="data row14 col6" >7.98</td>
                        <td id="T_203d4_row14_col7" class="data row14 col7" >12.56</td>
                        <td id="T_203d4_row14_col8" class="data row14 col8" >4.81</td>
                        <td id="T_203d4_row14_col9" class="data row14 col9" >5.69</td>
                        <td id="T_203d4_row14_col10" class="data row14 col10" >3.13</td>
                        <td id="T_203d4_row14_col11" class="data row14 col11" >-216.14</td>
                        <td id="T_203d4_row14_col12" class="data row14 col12" >272.20</td>
                        <td id="T_203d4_row14_col13" class="data row14 col13" >-40.88</td>
                        <td id="T_203d4_row14_col14" class="data row14 col14" >97.99</td>
                        <td id="T_203d4_row14_col15" class="data row14 col15" >27.38</td>
                        <td id="T_203d4_row14_col16" class="data row14 col16" >4.81</td>
                        <td id="T_203d4_row14_col17" class="data row14 col17" >240.02</td>
                        <td id="T_203d4_row14_col18" class="data row14 col18" >nan</td>
            </tr>
            <tr>
                        <th id="T_203d4_level0_row15" class="row_heading level0 row15" >000651.SZ</th>
                        <td id="T_203d4_row15_col0" class="data row15 col0" >格力电器</td>
                        <td id="T_203d4_row15_col1" class="data row15 col1" >家用电器</td>
                        <td id="T_203d4_row15_col2" class="data row15 col2" >25.48</td>
                        <td id="T_203d4_row15_col3" class="data row15 col3" >58.14</td>
                        <td id="T_203d4_row15_col4" class="data row15 col4" >17.56</td>
                        <td id="T_203d4_row15_col5" class="data row15 col5" >26.13</td>
                        <td id="T_203d4_row15_col6" class="data row15 col6" >13.45</td>
                        <td id="T_203d4_row15_col7" class="data row15 col7" >6.56</td>
                        <td id="T_203d4_row15_col8" class="data row15 col8" >24.45</td>
                        <td id="T_203d4_row15_col9" class="data row15 col9" >0.34</td>
                        <td id="T_203d4_row15_col10" class="data row15 col10" >14.58</td>
                        <td id="T_203d4_row15_col11" class="data row15 col11" >9.95</td>
                        <td id="T_203d4_row15_col12" class="data row15 col12" >51.97</td>
                        <td id="T_203d4_row15_col13" class="data row15 col13" >309.87</td>
                        <td id="T_203d4_row15_col14" class="data row15 col14" >306.13</td>
                        <td id="T_203d4_row15_col15" class="data row15 col15" >14.01</td>
                        <td id="T_203d4_row15_col16" class="data row15 col16" >41.37</td>
                        <td id="T_203d4_row15_col17" class="data row15 col17" >337.18</td>
                        <td id="T_203d4_row15_col18" class="data row15 col18" >-8.81</td>
            </tr>
            <tr>
                        <th id="T_203d4_level0_row16" class="row_heading level0 row16" >600000.SS</th>
                        <td id="T_203d4_row16_col0" class="data row16 col0" >浦发银行</td>
                        <td id="T_203d4_row16_col1" class="data row16 col1" >银行</td>
                        <td id="T_203d4_row16_col2" class="data row16 col2" >4.11</td>
                        <td id="T_203d4_row16_col3" class="data row16 col3" >91.88</td>
                        <td id="T_203d4_row16_col4" class="data row16 col4" >6.45</td>
                        <td id="T_203d4_row16_col5" class="data row16 col5" >11.54</td>
                        <td id="T_203d4_row16_col6" class="data row16 col6" >50.05</td>
                        <td id="T_203d4_row16_col7" class="data row16 col7" >1.01</td>
                        <td id="T_203d4_row16_col8" class="data row16 col8" >3.84</td>
                        <td id="T_203d4_row16_col9" class="data row16 col9" >2.47</td>
                        <td id="T_203d4_row16_col10" class="data row16 col10" >3.22</td>
                        <td id="T_203d4_row16_col11" class="data row16 col11" >-67.43</td>
                        <td id="T_203d4_row16_col12" class="data row16 col12" >193.50</td>
                        <td id="T_203d4_row16_col13" class="data row16 col13" >-89.66</td>
                        <td id="T_203d4_row16_col14" class="data row16 col14" >773.00</td>
                        <td id="T_203d4_row16_col15" class="data row16 col15" >5.03</td>
                        <td id="T_203d4_row16_col16" class="data row16 col16" >2.03</td>
                        <td id="T_203d4_row16_col17" class="data row16 col17" >299.98</td>
                        <td id="T_203d4_row16_col18" class="data row16 col18" >nan</td>
            </tr>
            <tr>
                        <th id="T_203d4_level0_row17" class="row_heading level0 row17" >601318.SS</th>
                        <td id="T_203d4_row17_col0" class="data row17 col0" >中国平安</td>
                        <td id="T_203d4_row17_col1" class="data row17 col1" >非银金融</td>
                        <td id="T_203d4_row17_col2" class="data row17 col2" >28.85</td>
                        <td id="T_203d4_row17_col3" class="data row17 col3" >89.63</td>
                        <td id="T_203d4_row17_col4" class="data row17 col4" >36.19</td>
                        <td id="T_203d4_row17_col5" class="data row17 col5" >19.77</td>
                        <td id="T_203d4_row17_col6" class="data row17 col6" >10.76</td>
                        <td id="T_203d4_row17_col7" class="data row17 col7" >8.44</td>
                        <td id="T_203d4_row17_col8" class="data row17 col8" >5.08</td>
                        <td id="T_203d4_row17_col9" class="data row17 col9" >18.48</td>
                        <td id="T_203d4_row17_col10" class="data row17 col10" >21.74</td>
                        <td id="T_203d4_row17_col11" class="data row17 col11" >30.57</td>
                        <td id="T_203d4_row17_col12" class="data row17 col12" >52.95</td>
                        <td id="T_203d4_row17_col13" class="data row17 col13" >4000.34</td>
                        <td id="T_203d4_row17_col14" class="data row17 col14" >2495.68</td>
                        <td id="T_203d4_row17_col15" class="data row17 col15" >8.98</td>
                        <td id="T_203d4_row17_col16" class="data row17 col16" >0.49</td>
                        <td id="T_203d4_row17_col17" class="data row17 col17" >1295.52</td>
                        <td id="T_203d4_row17_col18" class="data row17 col18" >67.61</td>
            </tr>
            <tr>
                        <th id="T_203d4_level0_row18" class="row_heading level0 row18" >002415.SZ</th>
                        <td id="T_203d4_row18_col0" class="data row18 col0" >海康威视</td>
                        <td id="T_203d4_row18_col1" class="data row18 col1" >电子</td>
                        <td id="T_203d4_row18_col2" class="data row18 col2" >8.87</td>
                        <td id="T_203d4_row18_col3" class="data row18 col3" >38.58</td>
                        <td id="T_203d4_row18_col4" class="data row18 col4" >42.53</td>
                        <td id="T_203d4_row18_col5" class="data row18 col5" >28.43</td>
                        <td id="T_203d4_row18_col6" class="data row18 col6" >21.96</td>
                        <td id="T_203d4_row18_col7" class="data row18 col7" >14.92</td>
                        <td id="T_203d4_row18_col8" class="data row18 col8" >4.45</td>
                        <td id="T_203d4_row18_col9" class="data row18 col9" >12.60</td>
                        <td id="T_203d4_row18_col10" class="data row18 col10" >6.99</td>
                        <td id="T_203d4_row18_col11" class="data row18 col11" >49.38</td>
                        <td id="T_203d4_row18_col12" class="data row18 col12" >82.14</td>
                        <td id="T_203d4_row18_col13" class="data row18 col13" >322.50</td>
                        <td id="T_203d4_row18_col14" class="data row18 col14" >205.94</td>
                        <td id="T_203d4_row18_col15" class="data row18 col15" >40.95</td>
                        <td id="T_203d4_row18_col16" class="data row18 col16" >3.25</td>
                        <td id="T_203d4_row18_col17" class="data row18 col17" >575.74</td>
                        <td id="T_203d4_row18_col18" class="data row18 col18" >-78.52</td>
            </tr>
            <tr>
                        <th id="T_203d4_level0_row19" class="row_heading level0 row19" >000002.SZ</th>
                        <td id="T_203d4_row19_col0" class="data row19 col0" >万  科Ａ</td>
                        <td id="T_203d4_row19_col1" class="data row19 col1" >房地产</td>
                        <td id="T_203d4_row19_col2" class="data row19 col2" >19.82</td>
                        <td id="T_203d4_row19_col3" class="data row19 col3" >81.28</td>
                        <td id="T_203d4_row19_col4" class="data row19 col4" >56.58</td>
                        <td id="T_203d4_row19_col5" class="data row19 col5" >20.50</td>
                        <td id="T_203d4_row19_col6" class="data row19 col6" >10.84</td>
                        <td id="T_203d4_row19_col7" class="data row19 col7" >20.02</td>
                        <td id="T_203d4_row19_col8" class="data row19 col8" >5.31</td>
                        <td id="T_203d4_row19_col9" class="data row19 col9" >14.10</td>
                        <td id="T_203d4_row19_col10" class="data row19 col10" >6.85</td>
                        <td id="T_203d4_row19_col11" class="data row19 col11" >25.80</td>
                        <td id="T_203d4_row19_col12" class="data row19 col12" >109.64</td>
                        <td id="T_203d4_row19_col13" class="data row19 col13" >1093.74</td>
                        <td id="T_203d4_row19_col14" class="data row19 col14" >652.72</td>
                        <td id="T_203d4_row19_col15" class="data row19 col15" >7.48</td>
                        <td id="T_203d4_row19_col16" class="data row19 col16" >0.53</td>
                        <td id="T_203d4_row19_col17" class="data row19 col17" >310.89</td>
                        <td id="T_203d4_row19_col18" class="data row19 col18" >71.58</td>
            </tr>
            <tr>
                        <th id="T_203d4_level0_row20" class="row_heading level0 row20" >002594.SZ</th>
                        <td id="T_203d4_row20_col0" class="data row20 col0" >比亚迪</td>
                        <td id="T_203d4_row20_col1" class="data row20 col1" >汽车</td>
                        <td id="T_203d4_row20_col2" class="data row20 col2" >13.51</td>
                        <td id="T_203d4_row20_col3" class="data row20 col3" >67.94</td>
                        <td id="T_203d4_row20_col4" class="data row20 col4" >36.43</td>
                        <td id="T_203d4_row20_col5" class="data row20 col5" >5.68</td>
                        <td id="T_203d4_row20_col6" class="data row20 col6" >2.49</td>
                        <td id="T_203d4_row20_col7" class="data row20 col7" >14.53</td>
                        <td id="T_203d4_row20_col8" class="data row20 col8" >14.13</td>
                        <td id="T_203d4_row20_col9" class="data row20 col9" >29.57</td>
                        <td id="T_203d4_row20_col10" class="data row20 col10" >115.04</td>
                        <td id="T_203d4_row20_col11" class="data row20 col11" >-231.87</td>
                        <td id="T_203d4_row20_col12" class="data row20 col12" >381.11</td>
                        <td id="T_203d4_row20_col13" class="data row20 col13" >-86.81</td>
                        <td id="T_203d4_row20_col14" class="data row20 col14" >83.47</td>
                        <td id="T_203d4_row20_col15" class="data row20 col15" >122.41</td>
                        <td id="T_203d4_row20_col16" class="data row20 col16" >4.14</td>
                        <td id="T_203d4_row20_col17" class="data row20 col17" >533.60</td>
                        <td id="T_203d4_row20_col18" class="data row20 col18" >nan</td>
            </tr>
    </tbody></table>



## 美股

### 候选列表

1. 负债率 < 100%
2. 应收占比 < 50%
3. ROE >= 15
4. 利润率 >= 20%
5. 收入增长 >= 20% 或 盈利增长 >= 15% 或 FCF增长率 >= 15%




<style  type="text/css" >
#T_e59d7_row0_col0,#T_e59d7_row0_col1,#T_e59d7_row0_col2,#T_e59d7_row0_col3,#T_e59d7_row0_col4,#T_e59d7_row0_col5,#T_e59d7_row0_col6,#T_e59d7_row0_col8,#T_e59d7_row0_col10,#T_e59d7_row0_col11,#T_e59d7_row0_col13,#T_e59d7_row0_col14,#T_e59d7_row1_col0,#T_e59d7_row1_col1,#T_e59d7_row1_col2,#T_e59d7_row1_col3,#T_e59d7_row1_col4,#T_e59d7_row1_col5,#T_e59d7_row1_col6,#T_e59d7_row1_col7,#T_e59d7_row1_col8,#T_e59d7_row1_col9,#T_e59d7_row1_col10,#T_e59d7_row1_col11,#T_e59d7_row1_col12,#T_e59d7_row1_col13,#T_e59d7_row1_col14,#T_e59d7_row2_col0,#T_e59d7_row2_col1,#T_e59d7_row2_col2,#T_e59d7_row2_col3,#T_e59d7_row2_col4,#T_e59d7_row2_col5,#T_e59d7_row2_col6,#T_e59d7_row2_col7,#T_e59d7_row2_col8,#T_e59d7_row2_col9,#T_e59d7_row2_col10,#T_e59d7_row2_col11,#T_e59d7_row2_col12,#T_e59d7_row2_col13,#T_e59d7_row2_col14,#T_e59d7_row3_col0,#T_e59d7_row3_col1,#T_e59d7_row3_col2,#T_e59d7_row3_col3,#T_e59d7_row3_col4,#T_e59d7_row3_col5,#T_e59d7_row3_col6,#T_e59d7_row3_col8,#T_e59d7_row3_col10,#T_e59d7_row3_col12,#T_e59d7_row3_col13,#T_e59d7_row3_col14,#T_e59d7_row4_col0,#T_e59d7_row4_col1,#T_e59d7_row4_col2,#T_e59d7_row4_col3,#T_e59d7_row4_col4,#T_e59d7_row4_col5,#T_e59d7_row4_col6,#T_e59d7_row4_col7,#T_e59d7_row4_col8,#T_e59d7_row4_col9,#T_e59d7_row4_col10,#T_e59d7_row4_col11,#T_e59d7_row4_col12,#T_e59d7_row4_col13,#T_e59d7_row4_col14,#T_e59d7_row5_col0,#T_e59d7_row5_col1,#T_e59d7_row5_col2,#T_e59d7_row5_col3,#T_e59d7_row5_col4,#T_e59d7_row5_col5,#T_e59d7_row5_col6,#T_e59d7_row5_col7,#T_e59d7_row5_col8,#T_e59d7_row5_col9,#T_e59d7_row5_col10,#T_e59d7_row5_col11,#T_e59d7_row5_col12,#T_e59d7_row5_col13,#T_e59d7_row5_col14,#T_e59d7_row6_col0,#T_e59d7_row6_col1,#T_e59d7_row6_col2,#T_e59d7_row6_col3,#T_e59d7_row6_col4,#T_e59d7_row6_col5,#T_e59d7_row6_col6,#T_e59d7_row6_col7,#T_e59d7_row6_col8,#T_e59d7_row6_col10,#T_e59d7_row6_col11,#T_e59d7_row6_col12,#T_e59d7_row6_col13,#T_e59d7_row6_col14,#T_e59d7_row7_col0,#T_e59d7_row7_col1,#T_e59d7_row7_col2,#T_e59d7_row7_col3,#T_e59d7_row7_col4,#T_e59d7_row7_col6,#T_e59d7_row7_col7,#T_e59d7_row7_col8,#T_e59d7_row7_col10,#T_e59d7_row7_col11,#T_e59d7_row7_col12,#T_e59d7_row7_col13,#T_e59d7_row7_col14,#T_e59d7_row8_col0,#T_e59d7_row8_col1,#T_e59d7_row8_col2,#T_e59d7_row8_col3,#T_e59d7_row8_col4,#T_e59d7_row8_col5,#T_e59d7_row8_col6,#T_e59d7_row8_col7,#T_e59d7_row8_col8,#T_e59d7_row8_col9,#T_e59d7_row8_col10,#T_e59d7_row8_col11,#T_e59d7_row8_col12,#T_e59d7_row8_col13,#T_e59d7_row8_col14,#T_e59d7_row9_col0,#T_e59d7_row9_col1,#T_e59d7_row9_col2,#T_e59d7_row9_col3,#T_e59d7_row9_col4,#T_e59d7_row9_col5,#T_e59d7_row9_col6,#T_e59d7_row9_col8,#T_e59d7_row9_col9,#T_e59d7_row9_col10,#T_e59d7_row9_col11,#T_e59d7_row9_col12,#T_e59d7_row9_col13,#T_e59d7_row9_col14,#T_e59d7_row10_col0,#T_e59d7_row10_col1,#T_e59d7_row10_col2,#T_e59d7_row10_col3,#T_e59d7_row10_col4,#T_e59d7_row10_col5,#T_e59d7_row10_col6,#T_e59d7_row10_col7,#T_e59d7_row10_col8,#T_e59d7_row10_col9,#T_e59d7_row10_col10,#T_e59d7_row10_col11,#T_e59d7_row10_col12,#T_e59d7_row10_col13,#T_e59d7_row10_col14,#T_e59d7_row11_col0,#T_e59d7_row11_col1,#T_e59d7_row11_col2,#T_e59d7_row11_col3,#T_e59d7_row11_col4,#T_e59d7_row11_col5,#T_e59d7_row11_col6,#T_e59d7_row11_col7,#T_e59d7_row11_col8,#T_e59d7_row11_col9,#T_e59d7_row11_col10,#T_e59d7_row11_col11,#T_e59d7_row11_col12,#T_e59d7_row11_col13,#T_e59d7_row11_col14,#T_e59d7_row12_col0,#T_e59d7_row12_col1,#T_e59d7_row12_col2,#T_e59d7_row12_col3,#T_e59d7_row12_col4,#T_e59d7_row12_col5,#T_e59d7_row12_col6,#T_e59d7_row12_col7,#T_e59d7_row12_col8,#T_e59d7_row12_col9,#T_e59d7_row12_col10,#T_e59d7_row12_col11,#T_e59d7_row12_col12,#T_e59d7_row12_col13,#T_e59d7_row12_col14,#T_e59d7_row13_col0,#T_e59d7_row13_col1,#T_e59d7_row13_col2,#T_e59d7_row13_col3,#T_e59d7_row13_col4,#T_e59d7_row13_col5,#T_e59d7_row13_col6,#T_e59d7_row13_col7,#T_e59d7_row13_col8,#T_e59d7_row13_col9,#T_e59d7_row13_col10,#T_e59d7_row13_col11,#T_e59d7_row13_col12,#T_e59d7_row13_col13,#T_e59d7_row13_col14,#T_e59d7_row14_col0,#T_e59d7_row14_col1,#T_e59d7_row14_col2,#T_e59d7_row14_col3,#T_e59d7_row14_col4,#T_e59d7_row14_col5,#T_e59d7_row14_col6,#T_e59d7_row14_col7,#T_e59d7_row14_col8,#T_e59d7_row14_col9,#T_e59d7_row14_col10,#T_e59d7_row14_col11,#T_e59d7_row14_col12,#T_e59d7_row14_col13,#T_e59d7_row14_col14,#T_e59d7_row15_col0,#T_e59d7_row15_col1,#T_e59d7_row15_col2,#T_e59d7_row15_col3,#T_e59d7_row15_col4,#T_e59d7_row15_col5,#T_e59d7_row15_col6,#T_e59d7_row15_col7,#T_e59d7_row15_col8,#T_e59d7_row15_col9,#T_e59d7_row15_col10,#T_e59d7_row15_col11,#T_e59d7_row15_col12,#T_e59d7_row15_col13,#T_e59d7_row15_col14,#T_e59d7_row16_col0,#T_e59d7_row16_col1,#T_e59d7_row16_col2,#T_e59d7_row16_col3,#T_e59d7_row16_col4,#T_e59d7_row16_col5,#T_e59d7_row16_col6,#T_e59d7_row16_col7,#T_e59d7_row16_col8,#T_e59d7_row16_col9,#T_e59d7_row16_col10,#T_e59d7_row16_col11,#T_e59d7_row16_col12,#T_e59d7_row16_col13,#T_e59d7_row16_col14,#T_e59d7_row17_col0,#T_e59d7_row17_col1,#T_e59d7_row17_col2,#T_e59d7_row17_col3,#T_e59d7_row17_col4,#T_e59d7_row17_col5,#T_e59d7_row17_col6,#T_e59d7_row17_col7,#T_e59d7_row17_col8,#T_e59d7_row17_col10,#T_e59d7_row17_col12,#T_e59d7_row17_col13,#T_e59d7_row17_col14,#T_e59d7_row18_col0,#T_e59d7_row18_col1,#T_e59d7_row18_col2,#T_e59d7_row18_col3,#T_e59d7_row18_col4,#T_e59d7_row18_col5,#T_e59d7_row18_col6,#T_e59d7_row18_col7,#T_e59d7_row18_col8,#T_e59d7_row18_col10,#T_e59d7_row18_col12,#T_e59d7_row18_col13,#T_e59d7_row18_col14,#T_e59d7_row19_col0,#T_e59d7_row19_col1,#T_e59d7_row19_col2,#T_e59d7_row19_col3,#T_e59d7_row19_col4,#T_e59d7_row19_col5,#T_e59d7_row19_col6,#T_e59d7_row19_col7,#T_e59d7_row19_col8,#T_e59d7_row19_col9,#T_e59d7_row19_col10,#T_e59d7_row19_col11,#T_e59d7_row19_col12,#T_e59d7_row19_col13,#T_e59d7_row19_col14,#T_e59d7_row20_col0,#T_e59d7_row20_col1,#T_e59d7_row20_col2,#T_e59d7_row20_col3,#T_e59d7_row20_col4,#T_e59d7_row20_col6,#T_e59d7_row20_col7,#T_e59d7_row20_col8,#T_e59d7_row20_col9,#T_e59d7_row20_col10,#T_e59d7_row20_col11,#T_e59d7_row20_col12,#T_e59d7_row20_col13,#T_e59d7_row20_col14,#T_e59d7_row21_col0,#T_e59d7_row21_col1,#T_e59d7_row21_col2,#T_e59d7_row21_col3,#T_e59d7_row21_col4,#T_e59d7_row21_col6,#T_e59d7_row21_col7,#T_e59d7_row21_col8,#T_e59d7_row21_col9,#T_e59d7_row21_col10,#T_e59d7_row21_col11,#T_e59d7_row21_col12,#T_e59d7_row21_col13,#T_e59d7_row21_col14,#T_e59d7_row22_col0,#T_e59d7_row22_col1,#T_e59d7_row22_col2,#T_e59d7_row22_col3,#T_e59d7_row22_col4,#T_e59d7_row22_col5,#T_e59d7_row22_col6,#T_e59d7_row22_col7,#T_e59d7_row22_col8,#T_e59d7_row22_col10,#T_e59d7_row22_col11,#T_e59d7_row22_col12,#T_e59d7_row22_col13,#T_e59d7_row22_col14,#T_e59d7_row23_col0,#T_e59d7_row23_col1,#T_e59d7_row23_col2,#T_e59d7_row23_col3,#T_e59d7_row23_col4,#T_e59d7_row23_col6,#T_e59d7_row23_col7,#T_e59d7_row23_col8,#T_e59d7_row23_col10,#T_e59d7_row23_col11,#T_e59d7_row23_col12,#T_e59d7_row23_col13,#T_e59d7_row23_col14,#T_e59d7_row24_col0,#T_e59d7_row24_col1,#T_e59d7_row24_col2,#T_e59d7_row24_col3,#T_e59d7_row24_col4,#T_e59d7_row24_col6,#T_e59d7_row24_col7,#T_e59d7_row24_col8,#T_e59d7_row24_col9,#T_e59d7_row24_col10,#T_e59d7_row24_col11,#T_e59d7_row24_col12,#T_e59d7_row24_col13,#T_e59d7_row24_col14,#T_e59d7_row25_col0,#T_e59d7_row25_col1,#T_e59d7_row25_col2,#T_e59d7_row25_col3,#T_e59d7_row25_col4,#T_e59d7_row25_col5,#T_e59d7_row25_col6,#T_e59d7_row25_col7,#T_e59d7_row25_col8,#T_e59d7_row25_col9,#T_e59d7_row25_col10,#T_e59d7_row25_col11,#T_e59d7_row25_col12,#T_e59d7_row25_col13,#T_e59d7_row25_col14,#T_e59d7_row26_col0,#T_e59d7_row26_col1,#T_e59d7_row26_col2,#T_e59d7_row26_col3,#T_e59d7_row26_col4,#T_e59d7_row26_col5,#T_e59d7_row26_col6,#T_e59d7_row26_col8,#T_e59d7_row26_col9,#T_e59d7_row26_col10,#T_e59d7_row26_col11,#T_e59d7_row26_col12,#T_e59d7_row26_col13,#T_e59d7_row26_col14,#T_e59d7_row27_col0,#T_e59d7_row27_col1,#T_e59d7_row27_col2,#T_e59d7_row27_col3,#T_e59d7_row27_col4,#T_e59d7_row27_col5,#T_e59d7_row27_col6,#T_e59d7_row27_col7,#T_e59d7_row27_col8,#T_e59d7_row27_col9,#T_e59d7_row27_col10,#T_e59d7_row27_col11,#T_e59d7_row27_col12,#T_e59d7_row27_col13,#T_e59d7_row27_col14,#T_e59d7_row28_col0,#T_e59d7_row28_col1,#T_e59d7_row28_col2,#T_e59d7_row28_col3,#T_e59d7_row28_col4,#T_e59d7_row28_col5,#T_e59d7_row28_col6,#T_e59d7_row28_col8,#T_e59d7_row28_col10,#T_e59d7_row28_col12,#T_e59d7_row28_col13,#T_e59d7_row28_col14,#T_e59d7_row29_col0,#T_e59d7_row29_col1,#T_e59d7_row29_col2,#T_e59d7_row29_col3,#T_e59d7_row29_col4,#T_e59d7_row29_col5,#T_e59d7_row29_col6,#T_e59d7_row29_col7,#T_e59d7_row29_col8,#T_e59d7_row29_col9,#T_e59d7_row29_col10,#T_e59d7_row29_col11,#T_e59d7_row29_col12,#T_e59d7_row29_col13,#T_e59d7_row29_col14,#T_e59d7_row30_col0,#T_e59d7_row30_col1,#T_e59d7_row30_col2,#T_e59d7_row30_col3,#T_e59d7_row30_col4,#T_e59d7_row30_col5,#T_e59d7_row30_col6,#T_e59d7_row30_col8,#T_e59d7_row30_col9,#T_e59d7_row30_col10,#T_e59d7_row30_col12,#T_e59d7_row30_col13,#T_e59d7_row30_col14,#T_e59d7_row31_col0,#T_e59d7_row31_col1,#T_e59d7_row31_col2,#T_e59d7_row31_col3,#T_e59d7_row31_col4,#T_e59d7_row31_col5,#T_e59d7_row31_col6,#T_e59d7_row31_col7,#T_e59d7_row31_col8,#T_e59d7_row31_col10,#T_e59d7_row31_col12,#T_e59d7_row31_col13,#T_e59d7_row31_col14,#T_e59d7_row32_col0,#T_e59d7_row32_col1,#T_e59d7_row32_col2,#T_e59d7_row32_col3,#T_e59d7_row32_col4,#T_e59d7_row32_col6,#T_e59d7_row32_col7,#T_e59d7_row32_col8,#T_e59d7_row32_col9,#T_e59d7_row32_col10,#T_e59d7_row32_col12,#T_e59d7_row32_col13,#T_e59d7_row32_col14,#T_e59d7_row33_col0,#T_e59d7_row33_col1,#T_e59d7_row33_col2,#T_e59d7_row33_col3,#T_e59d7_row33_col4,#T_e59d7_row33_col5,#T_e59d7_row33_col6,#T_e59d7_row33_col8,#T_e59d7_row33_col9,#T_e59d7_row33_col10,#T_e59d7_row33_col11,#T_e59d7_row33_col12,#T_e59d7_row33_col13,#T_e59d7_row33_col14,#T_e59d7_row34_col0,#T_e59d7_row34_col1,#T_e59d7_row34_col2,#T_e59d7_row34_col3,#T_e59d7_row34_col4,#T_e59d7_row34_col5,#T_e59d7_row34_col6,#T_e59d7_row34_col7,#T_e59d7_row34_col8,#T_e59d7_row34_col9,#T_e59d7_row34_col10,#T_e59d7_row34_col11,#T_e59d7_row34_col12,#T_e59d7_row34_col13,#T_e59d7_row34_col14,#T_e59d7_row35_col0,#T_e59d7_row35_col1,#T_e59d7_row35_col2,#T_e59d7_row35_col3,#T_e59d7_row35_col4,#T_e59d7_row35_col6,#T_e59d7_row35_col7,#T_e59d7_row35_col8,#T_e59d7_row35_col9,#T_e59d7_row35_col10,#T_e59d7_row35_col11,#T_e59d7_row35_col12,#T_e59d7_row35_col13,#T_e59d7_row35_col14,#T_e59d7_row36_col0,#T_e59d7_row36_col1,#T_e59d7_row36_col2,#T_e59d7_row36_col3,#T_e59d7_row36_col4,#T_e59d7_row36_col5,#T_e59d7_row36_col6,#T_e59d7_row36_col8,#T_e59d7_row36_col9,#T_e59d7_row36_col10,#T_e59d7_row36_col11,#T_e59d7_row36_col12,#T_e59d7_row36_col13,#T_e59d7_row36_col14,#T_e59d7_row37_col0,#T_e59d7_row37_col1,#T_e59d7_row37_col2,#T_e59d7_row37_col3,#T_e59d7_row37_col4,#T_e59d7_row37_col5,#T_e59d7_row37_col6,#T_e59d7_row37_col7,#T_e59d7_row37_col8,#T_e59d7_row37_col9,#T_e59d7_row37_col10,#T_e59d7_row37_col11,#T_e59d7_row37_col12,#T_e59d7_row37_col13,#T_e59d7_row37_col14,#T_e59d7_row38_col0,#T_e59d7_row38_col1,#T_e59d7_row38_col2,#T_e59d7_row38_col3,#T_e59d7_row38_col4,#T_e59d7_row38_col6,#T_e59d7_row38_col8,#T_e59d7_row38_col9,#T_e59d7_row38_col10,#T_e59d7_row38_col11,#T_e59d7_row38_col12,#T_e59d7_row38_col13,#T_e59d7_row38_col14,#T_e59d7_row39_col0,#T_e59d7_row39_col1,#T_e59d7_row39_col2,#T_e59d7_row39_col3,#T_e59d7_row39_col4,#T_e59d7_row39_col5,#T_e59d7_row39_col6,#T_e59d7_row39_col7,#T_e59d7_row39_col8,#T_e59d7_row39_col9,#T_e59d7_row39_col10,#T_e59d7_row39_col11,#T_e59d7_row39_col12,#T_e59d7_row39_col13,#T_e59d7_row39_col14,#T_e59d7_row40_col0,#T_e59d7_row40_col1,#T_e59d7_row40_col2,#T_e59d7_row40_col3,#T_e59d7_row40_col4,#T_e59d7_row40_col6,#T_e59d7_row40_col8,#T_e59d7_row40_col9,#T_e59d7_row40_col10,#T_e59d7_row40_col11,#T_e59d7_row40_col12,#T_e59d7_row40_col13,#T_e59d7_row40_col14,#T_e59d7_row41_col0,#T_e59d7_row41_col1,#T_e59d7_row41_col2,#T_e59d7_row41_col3,#T_e59d7_row41_col4,#T_e59d7_row41_col6,#T_e59d7_row41_col8,#T_e59d7_row41_col9,#T_e59d7_row41_col10,#T_e59d7_row41_col11,#T_e59d7_row41_col12,#T_e59d7_row41_col13,#T_e59d7_row41_col14,#T_e59d7_row42_col0,#T_e59d7_row42_col1,#T_e59d7_row42_col2,#T_e59d7_row42_col3,#T_e59d7_row42_col4,#T_e59d7_row42_col5,#T_e59d7_row42_col6,#T_e59d7_row42_col7,#T_e59d7_row42_col8,#T_e59d7_row42_col9,#T_e59d7_row42_col10,#T_e59d7_row42_col11,#T_e59d7_row42_col12,#T_e59d7_row42_col13,#T_e59d7_row42_col14,#T_e59d7_row43_col0,#T_e59d7_row43_col1,#T_e59d7_row43_col2,#T_e59d7_row43_col3,#T_e59d7_row43_col4,#T_e59d7_row43_col5,#T_e59d7_row43_col6,#T_e59d7_row43_col7,#T_e59d7_row43_col8,#T_e59d7_row43_col9,#T_e59d7_row43_col10,#T_e59d7_row43_col11,#T_e59d7_row43_col12,#T_e59d7_row43_col13,#T_e59d7_row43_col14,#T_e59d7_row44_col0,#T_e59d7_row44_col1,#T_e59d7_row44_col2,#T_e59d7_row44_col3,#T_e59d7_row44_col4,#T_e59d7_row44_col6,#T_e59d7_row44_col7,#T_e59d7_row44_col8,#T_e59d7_row44_col9,#T_e59d7_row44_col10,#T_e59d7_row44_col11,#T_e59d7_row44_col12,#T_e59d7_row44_col13,#T_e59d7_row44_col14,#T_e59d7_row45_col0,#T_e59d7_row45_col1,#T_e59d7_row45_col2,#T_e59d7_row45_col3,#T_e59d7_row45_col4,#T_e59d7_row45_col6,#T_e59d7_row45_col7,#T_e59d7_row45_col8,#T_e59d7_row45_col9,#T_e59d7_row45_col10,#T_e59d7_row45_col11,#T_e59d7_row45_col12,#T_e59d7_row45_col13,#T_e59d7_row45_col14,#T_e59d7_row46_col0,#T_e59d7_row46_col1,#T_e59d7_row46_col2,#T_e59d7_row46_col3,#T_e59d7_row46_col4,#T_e59d7_row46_col5,#T_e59d7_row46_col6,#T_e59d7_row46_col7,#T_e59d7_row46_col8,#T_e59d7_row46_col10,#T_e59d7_row46_col12,#T_e59d7_row46_col13,#T_e59d7_row46_col14,#T_e59d7_row47_col0,#T_e59d7_row47_col1,#T_e59d7_row47_col2,#T_e59d7_row47_col3,#T_e59d7_row47_col4,#T_e59d7_row47_col5,#T_e59d7_row47_col6,#T_e59d7_row47_col7,#T_e59d7_row47_col8,#T_e59d7_row47_col9,#T_e59d7_row47_col10,#T_e59d7_row47_col11,#T_e59d7_row47_col12,#T_e59d7_row47_col13,#T_e59d7_row47_col14,#T_e59d7_row48_col0,#T_e59d7_row48_col1,#T_e59d7_row48_col2,#T_e59d7_row48_col3,#T_e59d7_row48_col4,#T_e59d7_row48_col5,#T_e59d7_row48_col6,#T_e59d7_row48_col7,#T_e59d7_row48_col8,#T_e59d7_row48_col9,#T_e59d7_row48_col10,#T_e59d7_row48_col11,#T_e59d7_row48_col12,#T_e59d7_row48_col13,#T_e59d7_row48_col14,#T_e59d7_row49_col0,#T_e59d7_row49_col1,#T_e59d7_row49_col2,#T_e59d7_row49_col3,#T_e59d7_row49_col4,#T_e59d7_row49_col5,#T_e59d7_row49_col6,#T_e59d7_row49_col7,#T_e59d7_row49_col8,#T_e59d7_row49_col9,#T_e59d7_row49_col10,#T_e59d7_row49_col11,#T_e59d7_row49_col12,#T_e59d7_row49_col13,#T_e59d7_row49_col14,#T_e59d7_row50_col0,#T_e59d7_row50_col1,#T_e59d7_row50_col2,#T_e59d7_row50_col3,#T_e59d7_row50_col4,#T_e59d7_row50_col5,#T_e59d7_row50_col6,#T_e59d7_row50_col7,#T_e59d7_row50_col8,#T_e59d7_row50_col9,#T_e59d7_row50_col10,#T_e59d7_row50_col11,#T_e59d7_row50_col12,#T_e59d7_row50_col13,#T_e59d7_row50_col14,#T_e59d7_row51_col0,#T_e59d7_row51_col1,#T_e59d7_row51_col2,#T_e59d7_row51_col3,#T_e59d7_row51_col4,#T_e59d7_row51_col5,#T_e59d7_row51_col6,#T_e59d7_row51_col7,#T_e59d7_row51_col8,#T_e59d7_row51_col10,#T_e59d7_row51_col12,#T_e59d7_row51_col13,#T_e59d7_row51_col14,#T_e59d7_row52_col0,#T_e59d7_row52_col1,#T_e59d7_row52_col2,#T_e59d7_row52_col3,#T_e59d7_row52_col4,#T_e59d7_row52_col6,#T_e59d7_row52_col7,#T_e59d7_row52_col8,#T_e59d7_row52_col9,#T_e59d7_row52_col10,#T_e59d7_row52_col11,#T_e59d7_row52_col12,#T_e59d7_row52_col13,#T_e59d7_row52_col14,#T_e59d7_row53_col0,#T_e59d7_row53_col1,#T_e59d7_row53_col2,#T_e59d7_row53_col3,#T_e59d7_row53_col4,#T_e59d7_row53_col5,#T_e59d7_row53_col6,#T_e59d7_row53_col7,#T_e59d7_row53_col8,#T_e59d7_row53_col9,#T_e59d7_row53_col10,#T_e59d7_row53_col11,#T_e59d7_row53_col12,#T_e59d7_row53_col13,#T_e59d7_row53_col14,#T_e59d7_row54_col0,#T_e59d7_row54_col1,#T_e59d7_row54_col2,#T_e59d7_row54_col3,#T_e59d7_row54_col4,#T_e59d7_row54_col5,#T_e59d7_row54_col6,#T_e59d7_row54_col7,#T_e59d7_row54_col8,#T_e59d7_row54_col9,#T_e59d7_row54_col10,#T_e59d7_row54_col11,#T_e59d7_row54_col12,#T_e59d7_row54_col13,#T_e59d7_row54_col14,#T_e59d7_row55_col0,#T_e59d7_row55_col1,#T_e59d7_row55_col2,#T_e59d7_row55_col3,#T_e59d7_row55_col4,#T_e59d7_row55_col5,#T_e59d7_row55_col6,#T_e59d7_row55_col7,#T_e59d7_row55_col8,#T_e59d7_row55_col9,#T_e59d7_row55_col10,#T_e59d7_row55_col12,#T_e59d7_row55_col13,#T_e59d7_row55_col14,#T_e59d7_row56_col0,#T_e59d7_row56_col1,#T_e59d7_row56_col2,#T_e59d7_row56_col3,#T_e59d7_row56_col4,#T_e59d7_row56_col5,#T_e59d7_row56_col6,#T_e59d7_row56_col7,#T_e59d7_row56_col8,#T_e59d7_row56_col9,#T_e59d7_row56_col10,#T_e59d7_row56_col11,#T_e59d7_row56_col12,#T_e59d7_row56_col13,#T_e59d7_row56_col14,#T_e59d7_row57_col0,#T_e59d7_row57_col1,#T_e59d7_row57_col2,#T_e59d7_row57_col3,#T_e59d7_row57_col4,#T_e59d7_row57_col5,#T_e59d7_row57_col6,#T_e59d7_row57_col7,#T_e59d7_row57_col8,#T_e59d7_row57_col9,#T_e59d7_row57_col10,#T_e59d7_row57_col11,#T_e59d7_row57_col12,#T_e59d7_row57_col13,#T_e59d7_row57_col14,#T_e59d7_row58_col0,#T_e59d7_row58_col1,#T_e59d7_row58_col2,#T_e59d7_row58_col3,#T_e59d7_row58_col4,#T_e59d7_row58_col6,#T_e59d7_row58_col7,#T_e59d7_row58_col8,#T_e59d7_row58_col9,#T_e59d7_row58_col10,#T_e59d7_row58_col11,#T_e59d7_row58_col12,#T_e59d7_row58_col13,#T_e59d7_row58_col14,#T_e59d7_row59_col0,#T_e59d7_row59_col1,#T_e59d7_row59_col2,#T_e59d7_row59_col3,#T_e59d7_row59_col4,#T_e59d7_row59_col5,#T_e59d7_row59_col6,#T_e59d7_row59_col7,#T_e59d7_row59_col8,#T_e59d7_row59_col9,#T_e59d7_row59_col10,#T_e59d7_row59_col11,#T_e59d7_row59_col12,#T_e59d7_row59_col13,#T_e59d7_row59_col14,#T_e59d7_row60_col0,#T_e59d7_row60_col1,#T_e59d7_row60_col2,#T_e59d7_row60_col3,#T_e59d7_row60_col4,#T_e59d7_row60_col5,#T_e59d7_row60_col6,#T_e59d7_row60_col7,#T_e59d7_row60_col8,#T_e59d7_row60_col9,#T_e59d7_row60_col10,#T_e59d7_row60_col11,#T_e59d7_row60_col12,#T_e59d7_row60_col13,#T_e59d7_row60_col14,#T_e59d7_row61_col0,#T_e59d7_row61_col1,#T_e59d7_row61_col2,#T_e59d7_row61_col3,#T_e59d7_row61_col4,#T_e59d7_row61_col5,#T_e59d7_row61_col6,#T_e59d7_row61_col7,#T_e59d7_row61_col8,#T_e59d7_row61_col10,#T_e59d7_row61_col11,#T_e59d7_row61_col12,#T_e59d7_row61_col13,#T_e59d7_row61_col14,#T_e59d7_row62_col0,#T_e59d7_row62_col1,#T_e59d7_row62_col2,#T_e59d7_row62_col3,#T_e59d7_row62_col4,#T_e59d7_row62_col5,#T_e59d7_row62_col6,#T_e59d7_row62_col7,#T_e59d7_row62_col8,#T_e59d7_row62_col9,#T_e59d7_row62_col10,#T_e59d7_row62_col11,#T_e59d7_row62_col12,#T_e59d7_row62_col13,#T_e59d7_row62_col14,#T_e59d7_row63_col0,#T_e59d7_row63_col1,#T_e59d7_row63_col2,#T_e59d7_row63_col3,#T_e59d7_row63_col4,#T_e59d7_row63_col5,#T_e59d7_row63_col6,#T_e59d7_row63_col7,#T_e59d7_row63_col8,#T_e59d7_row63_col9,#T_e59d7_row63_col10,#T_e59d7_row63_col11,#T_e59d7_row63_col12,#T_e59d7_row63_col13,#T_e59d7_row63_col14,#T_e59d7_row64_col0,#T_e59d7_row64_col1,#T_e59d7_row64_col2,#T_e59d7_row64_col3,#T_e59d7_row64_col4,#T_e59d7_row64_col5,#T_e59d7_row64_col6,#T_e59d7_row64_col7,#T_e59d7_row64_col8,#T_e59d7_row64_col9,#T_e59d7_row64_col10,#T_e59d7_row64_col11,#T_e59d7_row64_col12,#T_e59d7_row64_col13,#T_e59d7_row64_col14,#T_e59d7_row65_col0,#T_e59d7_row65_col1,#T_e59d7_row65_col2,#T_e59d7_row65_col3,#T_e59d7_row65_col4,#T_e59d7_row65_col6,#T_e59d7_row65_col7,#T_e59d7_row65_col8,#T_e59d7_row65_col9,#T_e59d7_row65_col10,#T_e59d7_row65_col11,#T_e59d7_row65_col12,#T_e59d7_row65_col13,#T_e59d7_row65_col14,#T_e59d7_row66_col0,#T_e59d7_row66_col1,#T_e59d7_row66_col2,#T_e59d7_row66_col3,#T_e59d7_row66_col4,#T_e59d7_row66_col6,#T_e59d7_row66_col8,#T_e59d7_row66_col9,#T_e59d7_row66_col10,#T_e59d7_row66_col12,#T_e59d7_row66_col13,#T_e59d7_row66_col14,#T_e59d7_row67_col0,#T_e59d7_row67_col1,#T_e59d7_row67_col2,#T_e59d7_row67_col3,#T_e59d7_row67_col4,#T_e59d7_row67_col5,#T_e59d7_row67_col6,#T_e59d7_row67_col7,#T_e59d7_row67_col8,#T_e59d7_row67_col9,#T_e59d7_row67_col10,#T_e59d7_row67_col12,#T_e59d7_row67_col13,#T_e59d7_row67_col14,#T_e59d7_row68_col0,#T_e59d7_row68_col1,#T_e59d7_row68_col2,#T_e59d7_row68_col3,#T_e59d7_row68_col4,#T_e59d7_row68_col5,#T_e59d7_row68_col6,#T_e59d7_row68_col7,#T_e59d7_row68_col8,#T_e59d7_row68_col9,#T_e59d7_row68_col10,#T_e59d7_row68_col11,#T_e59d7_row68_col12,#T_e59d7_row68_col13,#T_e59d7_row68_col14,#T_e59d7_row69_col0,#T_e59d7_row69_col1,#T_e59d7_row69_col2,#T_e59d7_row69_col3,#T_e59d7_row69_col4,#T_e59d7_row69_col5,#T_e59d7_row69_col6,#T_e59d7_row69_col7,#T_e59d7_row69_col8,#T_e59d7_row69_col9,#T_e59d7_row69_col10,#T_e59d7_row69_col11,#T_e59d7_row69_col12,#T_e59d7_row69_col13,#T_e59d7_row69_col14,#T_e59d7_row70_col0,#T_e59d7_row70_col1,#T_e59d7_row70_col2,#T_e59d7_row70_col3,#T_e59d7_row70_col4,#T_e59d7_row70_col5,#T_e59d7_row70_col6,#T_e59d7_row70_col8,#T_e59d7_row70_col9,#T_e59d7_row70_col10,#T_e59d7_row70_col11,#T_e59d7_row70_col12,#T_e59d7_row70_col13,#T_e59d7_row70_col14,#T_e59d7_row71_col0,#T_e59d7_row71_col1,#T_e59d7_row71_col2,#T_e59d7_row71_col3,#T_e59d7_row71_col4,#T_e59d7_row71_col5,#T_e59d7_row71_col6,#T_e59d7_row71_col7,#T_e59d7_row71_col8,#T_e59d7_row71_col10,#T_e59d7_row71_col11,#T_e59d7_row71_col12,#T_e59d7_row71_col13,#T_e59d7_row71_col14,#T_e59d7_row72_col0,#T_e59d7_row72_col1,#T_e59d7_row72_col2,#T_e59d7_row72_col3,#T_e59d7_row72_col4,#T_e59d7_row72_col5,#T_e59d7_row72_col6,#T_e59d7_row72_col8,#T_e59d7_row72_col9,#T_e59d7_row72_col10,#T_e59d7_row72_col11,#T_e59d7_row72_col12,#T_e59d7_row72_col13,#T_e59d7_row72_col14,#T_e59d7_row73_col0,#T_e59d7_row73_col1,#T_e59d7_row73_col2,#T_e59d7_row73_col3,#T_e59d7_row73_col4,#T_e59d7_row73_col6,#T_e59d7_row73_col7,#T_e59d7_row73_col8,#T_e59d7_row73_col9,#T_e59d7_row73_col10,#T_e59d7_row73_col11,#T_e59d7_row73_col12,#T_e59d7_row73_col13,#T_e59d7_row73_col14,#T_e59d7_row74_col0,#T_e59d7_row74_col1,#T_e59d7_row74_col2,#T_e59d7_row74_col3,#T_e59d7_row74_col4,#T_e59d7_row74_col5,#T_e59d7_row74_col6,#T_e59d7_row74_col7,#T_e59d7_row74_col8,#T_e59d7_row74_col9,#T_e59d7_row74_col10,#T_e59d7_row74_col11,#T_e59d7_row74_col12,#T_e59d7_row74_col13,#T_e59d7_row74_col14,#T_e59d7_row75_col0,#T_e59d7_row75_col1,#T_e59d7_row75_col2,#T_e59d7_row75_col3,#T_e59d7_row75_col4,#T_e59d7_row75_col5,#T_e59d7_row75_col6,#T_e59d7_row75_col7,#T_e59d7_row75_col8,#T_e59d7_row75_col9,#T_e59d7_row75_col10,#T_e59d7_row75_col11,#T_e59d7_row75_col12,#T_e59d7_row75_col13,#T_e59d7_row75_col14,#T_e59d7_row76_col0,#T_e59d7_row76_col1,#T_e59d7_row76_col2,#T_e59d7_row76_col3,#T_e59d7_row76_col4,#T_e59d7_row76_col5,#T_e59d7_row76_col6,#T_e59d7_row76_col7,#T_e59d7_row76_col8,#T_e59d7_row76_col10,#T_e59d7_row76_col11,#T_e59d7_row76_col12,#T_e59d7_row76_col13,#T_e59d7_row76_col14,#T_e59d7_row77_col0,#T_e59d7_row77_col1,#T_e59d7_row77_col2,#T_e59d7_row77_col3,#T_e59d7_row77_col4,#T_e59d7_row77_col5,#T_e59d7_row77_col6,#T_e59d7_row77_col7,#T_e59d7_row77_col8,#T_e59d7_row77_col10,#T_e59d7_row77_col11,#T_e59d7_row77_col12,#T_e59d7_row77_col13,#T_e59d7_row77_col14,#T_e59d7_row78_col0,#T_e59d7_row78_col1,#T_e59d7_row78_col2,#T_e59d7_row78_col3,#T_e59d7_row78_col4,#T_e59d7_row78_col5,#T_e59d7_row78_col6,#T_e59d7_row78_col7,#T_e59d7_row78_col8,#T_e59d7_row78_col10,#T_e59d7_row78_col11,#T_e59d7_row78_col12,#T_e59d7_row78_col13,#T_e59d7_row78_col14,#T_e59d7_row79_col0,#T_e59d7_row79_col1,#T_e59d7_row79_col2,#T_e59d7_row79_col3,#T_e59d7_row79_col4,#T_e59d7_row79_col5,#T_e59d7_row79_col6,#T_e59d7_row79_col7,#T_e59d7_row79_col8,#T_e59d7_row79_col9,#T_e59d7_row79_col10,#T_e59d7_row79_col11,#T_e59d7_row79_col12,#T_e59d7_row79_col13,#T_e59d7_row79_col14,#T_e59d7_row80_col0,#T_e59d7_row80_col1,#T_e59d7_row80_col2,#T_e59d7_row80_col3,#T_e59d7_row80_col4,#T_e59d7_row80_col5,#T_e59d7_row80_col6,#T_e59d7_row80_col8,#T_e59d7_row80_col9,#T_e59d7_row80_col10,#T_e59d7_row80_col11,#T_e59d7_row80_col12,#T_e59d7_row80_col13,#T_e59d7_row80_col14,#T_e59d7_row81_col0,#T_e59d7_row81_col1,#T_e59d7_row81_col2,#T_e59d7_row81_col3,#T_e59d7_row81_col4,#T_e59d7_row81_col5,#T_e59d7_row81_col6,#T_e59d7_row81_col7,#T_e59d7_row81_col8,#T_e59d7_row81_col9,#T_e59d7_row81_col10,#T_e59d7_row81_col11,#T_e59d7_row81_col12,#T_e59d7_row81_col13,#T_e59d7_row81_col14,#T_e59d7_row82_col0,#T_e59d7_row82_col1,#T_e59d7_row82_col2,#T_e59d7_row82_col3,#T_e59d7_row82_col4,#T_e59d7_row82_col5,#T_e59d7_row82_col6,#T_e59d7_row82_col7,#T_e59d7_row82_col8,#T_e59d7_row82_col9,#T_e59d7_row82_col10,#T_e59d7_row82_col11,#T_e59d7_row82_col12,#T_e59d7_row82_col13,#T_e59d7_row82_col14,#T_e59d7_row83_col0,#T_e59d7_row83_col1,#T_e59d7_row83_col2,#T_e59d7_row83_col3,#T_e59d7_row83_col4,#T_e59d7_row83_col6,#T_e59d7_row83_col7,#T_e59d7_row83_col8,#T_e59d7_row83_col9,#T_e59d7_row83_col10,#T_e59d7_row83_col11,#T_e59d7_row83_col12,#T_e59d7_row83_col13,#T_e59d7_row83_col14,#T_e59d7_row84_col0,#T_e59d7_row84_col1,#T_e59d7_row84_col2,#T_e59d7_row84_col3,#T_e59d7_row84_col4,#T_e59d7_row84_col5,#T_e59d7_row84_col6,#T_e59d7_row84_col8,#T_e59d7_row84_col9,#T_e59d7_row84_col10,#T_e59d7_row84_col11,#T_e59d7_row84_col12,#T_e59d7_row84_col13,#T_e59d7_row84_col14,#T_e59d7_row85_col0,#T_e59d7_row85_col1,#T_e59d7_row85_col2,#T_e59d7_row85_col3,#T_e59d7_row85_col4,#T_e59d7_row85_col5,#T_e59d7_row85_col6,#T_e59d7_row85_col7,#T_e59d7_row85_col8,#T_e59d7_row85_col9,#T_e59d7_row85_col10,#T_e59d7_row85_col11,#T_e59d7_row85_col12,#T_e59d7_row85_col13,#T_e59d7_row85_col14,#T_e59d7_row86_col0,#T_e59d7_row86_col1,#T_e59d7_row86_col2,#T_e59d7_row86_col3,#T_e59d7_row86_col4,#T_e59d7_row86_col5,#T_e59d7_row86_col6,#T_e59d7_row86_col8,#T_e59d7_row86_col9,#T_e59d7_row86_col10,#T_e59d7_row86_col11,#T_e59d7_row86_col13,#T_e59d7_row86_col14,#T_e59d7_row87_col0,#T_e59d7_row87_col1,#T_e59d7_row87_col2,#T_e59d7_row87_col3,#T_e59d7_row87_col4,#T_e59d7_row87_col5,#T_e59d7_row87_col6,#T_e59d7_row87_col7,#T_e59d7_row87_col8,#T_e59d7_row87_col9,#T_e59d7_row87_col10,#T_e59d7_row87_col11,#T_e59d7_row87_col12,#T_e59d7_row87_col13,#T_e59d7_row87_col14,#T_e59d7_row88_col0,#T_e59d7_row88_col1,#T_e59d7_row88_col2,#T_e59d7_row88_col3,#T_e59d7_row88_col4,#T_e59d7_row88_col5,#T_e59d7_row88_col6,#T_e59d7_row88_col7,#T_e59d7_row88_col8,#T_e59d7_row88_col10,#T_e59d7_row88_col11,#T_e59d7_row88_col12,#T_e59d7_row88_col13,#T_e59d7_row88_col14,#T_e59d7_row89_col0,#T_e59d7_row89_col1,#T_e59d7_row89_col2,#T_e59d7_row89_col3,#T_e59d7_row89_col4,#T_e59d7_row89_col6,#T_e59d7_row89_col7,#T_e59d7_row89_col8,#T_e59d7_row89_col10,#T_e59d7_row89_col12,#T_e59d7_row89_col13,#T_e59d7_row89_col14,#T_e59d7_row90_col0,#T_e59d7_row90_col1,#T_e59d7_row90_col2,#T_e59d7_row90_col3,#T_e59d7_row90_col4,#T_e59d7_row90_col5,#T_e59d7_row90_col6,#T_e59d7_row90_col7,#T_e59d7_row90_col8,#T_e59d7_row90_col9,#T_e59d7_row90_col10,#T_e59d7_row90_col11,#T_e59d7_row90_col12,#T_e59d7_row90_col13,#T_e59d7_row90_col14,#T_e59d7_row91_col0,#T_e59d7_row91_col1,#T_e59d7_row91_col2,#T_e59d7_row91_col3,#T_e59d7_row91_col4,#T_e59d7_row91_col5,#T_e59d7_row91_col6,#T_e59d7_row91_col7,#T_e59d7_row91_col8,#T_e59d7_row91_col9,#T_e59d7_row91_col10,#T_e59d7_row91_col11,#T_e59d7_row91_col12,#T_e59d7_row91_col13,#T_e59d7_row91_col14,#T_e59d7_row92_col0,#T_e59d7_row92_col1,#T_e59d7_row92_col2,#T_e59d7_row92_col3,#T_e59d7_row92_col4,#T_e59d7_row92_col5,#T_e59d7_row92_col6,#T_e59d7_row92_col7,#T_e59d7_row92_col8,#T_e59d7_row92_col9,#T_e59d7_row92_col10,#T_e59d7_row92_col11,#T_e59d7_row92_col12,#T_e59d7_row92_col13,#T_e59d7_row92_col14,#T_e59d7_row93_col0,#T_e59d7_row93_col1,#T_e59d7_row93_col2,#T_e59d7_row93_col3,#T_e59d7_row93_col4,#T_e59d7_row93_col5,#T_e59d7_row93_col6,#T_e59d7_row93_col7,#T_e59d7_row93_col8,#T_e59d7_row93_col9,#T_e59d7_row93_col10,#T_e59d7_row93_col11,#T_e59d7_row93_col12,#T_e59d7_row93_col13,#T_e59d7_row93_col14,#T_e59d7_row94_col0,#T_e59d7_row94_col1,#T_e59d7_row94_col2,#T_e59d7_row94_col3,#T_e59d7_row94_col4,#T_e59d7_row94_col5,#T_e59d7_row94_col6,#T_e59d7_row94_col7,#T_e59d7_row94_col8,#T_e59d7_row94_col9,#T_e59d7_row94_col10,#T_e59d7_row94_col11,#T_e59d7_row94_col12,#T_e59d7_row94_col13,#T_e59d7_row94_col14,#T_e59d7_row95_col0,#T_e59d7_row95_col1,#T_e59d7_row95_col2,#T_e59d7_row95_col3,#T_e59d7_row95_col4,#T_e59d7_row95_col5,#T_e59d7_row95_col6,#T_e59d7_row95_col7,#T_e59d7_row95_col8,#T_e59d7_row95_col10,#T_e59d7_row95_col11,#T_e59d7_row95_col12,#T_e59d7_row95_col13,#T_e59d7_row95_col14,#T_e59d7_row96_col0,#T_e59d7_row96_col1,#T_e59d7_row96_col2,#T_e59d7_row96_col3,#T_e59d7_row96_col4,#T_e59d7_row96_col5,#T_e59d7_row96_col6,#T_e59d7_row96_col7,#T_e59d7_row96_col8,#T_e59d7_row96_col9,#T_e59d7_row96_col10,#T_e59d7_row96_col11,#T_e59d7_row96_col12,#T_e59d7_row96_col13,#T_e59d7_row96_col14,#T_e59d7_row97_col0,#T_e59d7_row97_col1,#T_e59d7_row97_col2,#T_e59d7_row97_col3,#T_e59d7_row97_col4,#T_e59d7_row97_col5,#T_e59d7_row97_col6,#T_e59d7_row97_col7,#T_e59d7_row97_col8,#T_e59d7_row97_col9,#T_e59d7_row97_col10,#T_e59d7_row97_col11,#T_e59d7_row97_col12,#T_e59d7_row97_col13,#T_e59d7_row97_col14,#T_e59d7_row98_col0,#T_e59d7_row98_col1,#T_e59d7_row98_col2,#T_e59d7_row98_col3,#T_e59d7_row98_col4,#T_e59d7_row98_col5,#T_e59d7_row98_col6,#T_e59d7_row98_col7,#T_e59d7_row98_col8,#T_e59d7_row98_col9,#T_e59d7_row98_col10,#T_e59d7_row98_col11,#T_e59d7_row98_col12,#T_e59d7_row98_col13,#T_e59d7_row98_col14,#T_e59d7_row99_col0,#T_e59d7_row99_col1,#T_e59d7_row99_col2,#T_e59d7_row99_col3,#T_e59d7_row99_col4,#T_e59d7_row99_col5,#T_e59d7_row99_col6,#T_e59d7_row99_col7,#T_e59d7_row99_col8,#T_e59d7_row99_col10,#T_e59d7_row99_col11,#T_e59d7_row99_col12,#T_e59d7_row99_col13,#T_e59d7_row99_col14,#T_e59d7_row100_col0,#T_e59d7_row100_col1,#T_e59d7_row100_col2,#T_e59d7_row100_col3,#T_e59d7_row100_col4,#T_e59d7_row100_col5,#T_e59d7_row100_col6,#T_e59d7_row100_col7,#T_e59d7_row100_col8,#T_e59d7_row100_col9,#T_e59d7_row100_col10,#T_e59d7_row100_col11,#T_e59d7_row100_col12,#T_e59d7_row100_col13,#T_e59d7_row100_col14,#T_e59d7_row101_col0,#T_e59d7_row101_col1,#T_e59d7_row101_col2,#T_e59d7_row101_col3,#T_e59d7_row101_col4,#T_e59d7_row101_col5,#T_e59d7_row101_col6,#T_e59d7_row101_col8,#T_e59d7_row101_col9,#T_e59d7_row101_col10,#T_e59d7_row101_col12,#T_e59d7_row101_col13,#T_e59d7_row101_col14,#T_e59d7_row102_col0,#T_e59d7_row102_col1,#T_e59d7_row102_col2,#T_e59d7_row102_col3,#T_e59d7_row102_col4,#T_e59d7_row102_col5,#T_e59d7_row102_col6,#T_e59d7_row102_col8,#T_e59d7_row102_col9,#T_e59d7_row102_col10,#T_e59d7_row102_col13,#T_e59d7_row102_col14,#T_e59d7_row103_col0,#T_e59d7_row103_col1,#T_e59d7_row103_col2,#T_e59d7_row103_col3,#T_e59d7_row103_col4,#T_e59d7_row103_col5,#T_e59d7_row103_col6,#T_e59d7_row103_col7,#T_e59d7_row103_col8,#T_e59d7_row103_col10,#T_e59d7_row103_col12,#T_e59d7_row103_col13,#T_e59d7_row103_col14,#T_e59d7_row104_col0,#T_e59d7_row104_col1,#T_e59d7_row104_col2,#T_e59d7_row104_col3,#T_e59d7_row104_col4,#T_e59d7_row104_col5,#T_e59d7_row104_col6,#T_e59d7_row104_col7,#T_e59d7_row104_col8,#T_e59d7_row104_col9,#T_e59d7_row104_col10,#T_e59d7_row104_col11,#T_e59d7_row104_col12,#T_e59d7_row104_col13,#T_e59d7_row104_col14,#T_e59d7_row105_col0,#T_e59d7_row105_col1,#T_e59d7_row105_col2,#T_e59d7_row105_col3,#T_e59d7_row105_col4,#T_e59d7_row105_col5,#T_e59d7_row105_col6,#T_e59d7_row105_col7,#T_e59d7_row105_col8,#T_e59d7_row105_col10,#T_e59d7_row105_col11,#T_e59d7_row105_col12,#T_e59d7_row105_col13,#T_e59d7_row105_col14,#T_e59d7_row106_col0,#T_e59d7_row106_col1,#T_e59d7_row106_col2,#T_e59d7_row106_col3,#T_e59d7_row106_col4,#T_e59d7_row106_col5,#T_e59d7_row106_col6,#T_e59d7_row106_col7,#T_e59d7_row106_col8,#T_e59d7_row106_col9,#T_e59d7_row106_col10,#T_e59d7_row106_col11,#T_e59d7_row106_col12,#T_e59d7_row106_col13,#T_e59d7_row106_col14,#T_e59d7_row107_col0,#T_e59d7_row107_col1,#T_e59d7_row107_col2,#T_e59d7_row107_col3,#T_e59d7_row107_col4,#T_e59d7_row107_col5,#T_e59d7_row107_col6,#T_e59d7_row107_col7,#T_e59d7_row107_col8,#T_e59d7_row107_col9,#T_e59d7_row107_col10,#T_e59d7_row107_col11,#T_e59d7_row107_col12,#T_e59d7_row107_col13,#T_e59d7_row107_col14,#T_e59d7_row108_col0,#T_e59d7_row108_col1,#T_e59d7_row108_col2,#T_e59d7_row108_col3,#T_e59d7_row108_col4,#T_e59d7_row108_col6,#T_e59d7_row108_col7,#T_e59d7_row108_col8,#T_e59d7_row108_col9,#T_e59d7_row108_col10,#T_e59d7_row108_col11,#T_e59d7_row108_col12,#T_e59d7_row108_col13,#T_e59d7_row108_col14,#T_e59d7_row109_col0,#T_e59d7_row109_col1,#T_e59d7_row109_col2,#T_e59d7_row109_col3,#T_e59d7_row109_col4,#T_e59d7_row109_col5,#T_e59d7_row109_col6,#T_e59d7_row109_col8,#T_e59d7_row109_col9,#T_e59d7_row109_col10,#T_e59d7_row109_col12,#T_e59d7_row109_col13,#T_e59d7_row109_col14,#T_e59d7_row110_col0,#T_e59d7_row110_col1,#T_e59d7_row110_col2,#T_e59d7_row110_col3,#T_e59d7_row110_col4,#T_e59d7_row110_col5,#T_e59d7_row110_col6,#T_e59d7_row110_col7,#T_e59d7_row110_col8,#T_e59d7_row110_col9,#T_e59d7_row110_col10,#T_e59d7_row110_col11,#T_e59d7_row110_col12,#T_e59d7_row110_col13,#T_e59d7_row110_col14,#T_e59d7_row111_col0,#T_e59d7_row111_col1,#T_e59d7_row111_col2,#T_e59d7_row111_col3,#T_e59d7_row111_col4,#T_e59d7_row111_col5,#T_e59d7_row111_col6,#T_e59d7_row111_col7,#T_e59d7_row111_col8,#T_e59d7_row111_col9,#T_e59d7_row111_col10,#T_e59d7_row111_col11,#T_e59d7_row111_col12,#T_e59d7_row111_col13,#T_e59d7_row111_col14,#T_e59d7_row112_col0,#T_e59d7_row112_col1,#T_e59d7_row112_col2,#T_e59d7_row112_col3,#T_e59d7_row112_col4,#T_e59d7_row112_col5,#T_e59d7_row112_col6,#T_e59d7_row112_col7,#T_e59d7_row112_col8,#T_e59d7_row112_col9,#T_e59d7_row112_col10,#T_e59d7_row112_col11,#T_e59d7_row112_col12,#T_e59d7_row112_col13,#T_e59d7_row112_col14,#T_e59d7_row113_col0,#T_e59d7_row113_col1,#T_e59d7_row113_col2,#T_e59d7_row113_col3,#T_e59d7_row113_col4,#T_e59d7_row113_col5,#T_e59d7_row113_col6,#T_e59d7_row113_col7,#T_e59d7_row113_col8,#T_e59d7_row113_col9,#T_e59d7_row113_col10,#T_e59d7_row113_col11,#T_e59d7_row113_col12,#T_e59d7_row113_col13,#T_e59d7_row113_col14,#T_e59d7_row114_col0,#T_e59d7_row114_col1,#T_e59d7_row114_col2,#T_e59d7_row114_col3,#T_e59d7_row114_col4,#T_e59d7_row114_col5,#T_e59d7_row114_col6,#T_e59d7_row114_col7,#T_e59d7_row114_col8,#T_e59d7_row114_col9,#T_e59d7_row114_col10,#T_e59d7_row114_col11,#T_e59d7_row114_col12,#T_e59d7_row114_col13,#T_e59d7_row114_col14,#T_e59d7_row115_col0,#T_e59d7_row115_col1,#T_e59d7_row115_col2,#T_e59d7_row115_col3,#T_e59d7_row115_col4,#T_e59d7_row115_col5,#T_e59d7_row115_col6,#T_e59d7_row115_col8,#T_e59d7_row115_col9,#T_e59d7_row115_col10,#T_e59d7_row115_col11,#T_e59d7_row115_col13,#T_e59d7_row115_col14,#T_e59d7_row116_col0,#T_e59d7_row116_col1,#T_e59d7_row116_col2,#T_e59d7_row116_col3,#T_e59d7_row116_col4,#T_e59d7_row116_col5,#T_e59d7_row116_col6,#T_e59d7_row116_col7,#T_e59d7_row116_col8,#T_e59d7_row116_col9,#T_e59d7_row116_col10,#T_e59d7_row116_col11,#T_e59d7_row116_col12,#T_e59d7_row116_col13,#T_e59d7_row116_col14,#T_e59d7_row117_col0,#T_e59d7_row117_col1,#T_e59d7_row117_col2,#T_e59d7_row117_col3,#T_e59d7_row117_col4,#T_e59d7_row117_col5,#T_e59d7_row117_col6,#T_e59d7_row117_col7,#T_e59d7_row117_col8,#T_e59d7_row117_col9,#T_e59d7_row117_col10,#T_e59d7_row117_col12,#T_e59d7_row117_col13,#T_e59d7_row117_col14,#T_e59d7_row118_col0,#T_e59d7_row118_col1,#T_e59d7_row118_col2,#T_e59d7_row118_col3,#T_e59d7_row118_col4,#T_e59d7_row118_col5,#T_e59d7_row118_col6,#T_e59d7_row118_col7,#T_e59d7_row118_col8,#T_e59d7_row118_col10,#T_e59d7_row118_col12,#T_e59d7_row118_col13,#T_e59d7_row118_col14,#T_e59d7_row119_col0,#T_e59d7_row119_col1,#T_e59d7_row119_col2,#T_e59d7_row119_col3,#T_e59d7_row119_col4,#T_e59d7_row119_col5,#T_e59d7_row119_col6,#T_e59d7_row119_col7,#T_e59d7_row119_col8,#T_e59d7_row119_col10,#T_e59d7_row119_col11,#T_e59d7_row119_col12,#T_e59d7_row119_col13,#T_e59d7_row119_col14,#T_e59d7_row120_col0,#T_e59d7_row120_col1,#T_e59d7_row120_col2,#T_e59d7_row120_col3,#T_e59d7_row120_col4,#T_e59d7_row120_col5,#T_e59d7_row120_col6,#T_e59d7_row120_col7,#T_e59d7_row120_col8,#T_e59d7_row120_col9,#T_e59d7_row120_col10,#T_e59d7_row120_col11,#T_e59d7_row120_col12,#T_e59d7_row120_col13,#T_e59d7_row120_col14,#T_e59d7_row121_col0,#T_e59d7_row121_col1,#T_e59d7_row121_col2,#T_e59d7_row121_col3,#T_e59d7_row121_col4,#T_e59d7_row121_col5,#T_e59d7_row121_col6,#T_e59d7_row121_col7,#T_e59d7_row121_col8,#T_e59d7_row121_col9,#T_e59d7_row121_col10,#T_e59d7_row121_col11,#T_e59d7_row121_col12,#T_e59d7_row121_col13,#T_e59d7_row121_col14,#T_e59d7_row122_col0,#T_e59d7_row122_col1,#T_e59d7_row122_col2,#T_e59d7_row122_col3,#T_e59d7_row122_col4,#T_e59d7_row122_col5,#T_e59d7_row122_col6,#T_e59d7_row122_col7,#T_e59d7_row122_col8,#T_e59d7_row122_col9,#T_e59d7_row122_col10,#T_e59d7_row122_col11,#T_e59d7_row122_col12,#T_e59d7_row122_col13,#T_e59d7_row122_col14,#T_e59d7_row123_col0,#T_e59d7_row123_col1,#T_e59d7_row123_col2,#T_e59d7_row123_col3,#T_e59d7_row123_col4,#T_e59d7_row123_col5,#T_e59d7_row123_col6,#T_e59d7_row123_col7,#T_e59d7_row123_col8,#T_e59d7_row123_col9,#T_e59d7_row123_col10,#T_e59d7_row123_col11,#T_e59d7_row123_col12,#T_e59d7_row123_col13,#T_e59d7_row123_col14,#T_e59d7_row124_col0,#T_e59d7_row124_col1,#T_e59d7_row124_col2,#T_e59d7_row124_col3,#T_e59d7_row124_col4,#T_e59d7_row124_col6,#T_e59d7_row124_col7,#T_e59d7_row124_col8,#T_e59d7_row124_col9,#T_e59d7_row124_col10,#T_e59d7_row124_col11,#T_e59d7_row124_col12,#T_e59d7_row124_col13,#T_e59d7_row124_col14,#T_e59d7_row125_col0,#T_e59d7_row125_col1,#T_e59d7_row125_col2,#T_e59d7_row125_col3,#T_e59d7_row125_col4,#T_e59d7_row125_col5,#T_e59d7_row125_col6,#T_e59d7_row125_col7,#T_e59d7_row125_col8,#T_e59d7_row125_col9,#T_e59d7_row125_col10,#T_e59d7_row125_col11,#T_e59d7_row125_col12,#T_e59d7_row125_col13,#T_e59d7_row125_col14,#T_e59d7_row126_col0,#T_e59d7_row126_col1,#T_e59d7_row126_col2,#T_e59d7_row126_col3,#T_e59d7_row126_col4,#T_e59d7_row126_col5,#T_e59d7_row126_col6,#T_e59d7_row126_col7,#T_e59d7_row126_col8,#T_e59d7_row126_col9,#T_e59d7_row126_col10,#T_e59d7_row126_col11,#T_e59d7_row126_col12,#T_e59d7_row126_col13,#T_e59d7_row126_col14,#T_e59d7_row127_col0,#T_e59d7_row127_col1,#T_e59d7_row127_col2,#T_e59d7_row127_col3,#T_e59d7_row127_col4,#T_e59d7_row127_col5,#T_e59d7_row127_col6,#T_e59d7_row127_col7,#T_e59d7_row127_col8,#T_e59d7_row127_col9,#T_e59d7_row127_col10,#T_e59d7_row127_col11,#T_e59d7_row127_col12,#T_e59d7_row127_col13,#T_e59d7_row127_col14,#T_e59d7_row128_col0,#T_e59d7_row128_col1,#T_e59d7_row128_col2,#T_e59d7_row128_col3,#T_e59d7_row128_col4,#T_e59d7_row128_col5,#T_e59d7_row128_col6,#T_e59d7_row128_col7,#T_e59d7_row128_col8,#T_e59d7_row128_col9,#T_e59d7_row128_col10,#T_e59d7_row128_col11,#T_e59d7_row128_col12,#T_e59d7_row128_col13,#T_e59d7_row128_col14,#T_e59d7_row129_col0,#T_e59d7_row129_col1,#T_e59d7_row129_col2,#T_e59d7_row129_col3,#T_e59d7_row129_col4,#T_e59d7_row129_col6,#T_e59d7_row129_col7,#T_e59d7_row129_col8,#T_e59d7_row129_col9,#T_e59d7_row129_col10,#T_e59d7_row129_col11,#T_e59d7_row129_col12,#T_e59d7_row129_col13,#T_e59d7_row129_col14,#T_e59d7_row130_col0,#T_e59d7_row130_col1,#T_e59d7_row130_col2,#T_e59d7_row130_col3,#T_e59d7_row130_col4,#T_e59d7_row130_col5,#T_e59d7_row130_col6,#T_e59d7_row130_col7,#T_e59d7_row130_col8,#T_e59d7_row130_col9,#T_e59d7_row130_col10,#T_e59d7_row130_col11,#T_e59d7_row130_col12,#T_e59d7_row130_col13,#T_e59d7_row130_col14,#T_e59d7_row131_col0,#T_e59d7_row131_col1,#T_e59d7_row131_col2,#T_e59d7_row131_col3,#T_e59d7_row131_col4,#T_e59d7_row131_col5,#T_e59d7_row131_col6,#T_e59d7_row131_col7,#T_e59d7_row131_col8,#T_e59d7_row131_col9,#T_e59d7_row131_col10,#T_e59d7_row131_col11,#T_e59d7_row131_col12,#T_e59d7_row131_col13,#T_e59d7_row131_col14,#T_e59d7_row132_col0,#T_e59d7_row132_col1,#T_e59d7_row132_col2,#T_e59d7_row132_col3,#T_e59d7_row132_col4,#T_e59d7_row132_col5,#T_e59d7_row132_col6,#T_e59d7_row132_col7,#T_e59d7_row132_col8,#T_e59d7_row132_col9,#T_e59d7_row132_col10,#T_e59d7_row132_col11,#T_e59d7_row132_col12,#T_e59d7_row132_col13,#T_e59d7_row132_col14,#T_e59d7_row133_col0,#T_e59d7_row133_col1,#T_e59d7_row133_col2,#T_e59d7_row133_col3,#T_e59d7_row133_col4,#T_e59d7_row133_col5,#T_e59d7_row133_col6,#T_e59d7_row133_col8,#T_e59d7_row133_col10,#T_e59d7_row133_col11,#T_e59d7_row133_col12,#T_e59d7_row133_col13,#T_e59d7_row133_col14,#T_e59d7_row134_col0,#T_e59d7_row134_col1,#T_e59d7_row134_col2,#T_e59d7_row134_col3,#T_e59d7_row134_col4,#T_e59d7_row134_col5,#T_e59d7_row134_col6,#T_e59d7_row134_col7,#T_e59d7_row134_col8,#T_e59d7_row134_col9,#T_e59d7_row134_col10,#T_e59d7_row134_col11,#T_e59d7_row134_col12,#T_e59d7_row134_col13,#T_e59d7_row134_col14,#T_e59d7_row135_col0,#T_e59d7_row135_col1,#T_e59d7_row135_col2,#T_e59d7_row135_col3,#T_e59d7_row135_col4,#T_e59d7_row135_col5,#T_e59d7_row135_col6,#T_e59d7_row135_col7,#T_e59d7_row135_col8,#T_e59d7_row135_col9,#T_e59d7_row135_col10,#T_e59d7_row135_col11,#T_e59d7_row135_col12,#T_e59d7_row135_col13,#T_e59d7_row135_col14,#T_e59d7_row136_col0,#T_e59d7_row136_col1,#T_e59d7_row136_col2,#T_e59d7_row136_col3,#T_e59d7_row136_col4,#T_e59d7_row136_col5,#T_e59d7_row136_col6,#T_e59d7_row136_col7,#T_e59d7_row136_col8,#T_e59d7_row136_col9,#T_e59d7_row136_col10,#T_e59d7_row136_col11,#T_e59d7_row136_col12,#T_e59d7_row136_col13,#T_e59d7_row136_col14,#T_e59d7_row137_col0,#T_e59d7_row137_col1,#T_e59d7_row137_col2,#T_e59d7_row137_col3,#T_e59d7_row137_col4,#T_e59d7_row137_col5,#T_e59d7_row137_col6,#T_e59d7_row137_col7,#T_e59d7_row137_col8,#T_e59d7_row137_col10,#T_e59d7_row137_col11,#T_e59d7_row137_col12,#T_e59d7_row137_col13,#T_e59d7_row137_col14{
            color:  black;
        }#T_e59d7_row0_col7,#T_e59d7_row0_col9,#T_e59d7_row0_col12,#T_e59d7_row3_col7,#T_e59d7_row3_col9,#T_e59d7_row3_col11,#T_e59d7_row6_col9,#T_e59d7_row7_col5,#T_e59d7_row7_col9,#T_e59d7_row9_col7,#T_e59d7_row17_col9,#T_e59d7_row17_col11,#T_e59d7_row18_col9,#T_e59d7_row18_col11,#T_e59d7_row20_col5,#T_e59d7_row21_col5,#T_e59d7_row22_col9,#T_e59d7_row23_col5,#T_e59d7_row23_col9,#T_e59d7_row24_col5,#T_e59d7_row26_col7,#T_e59d7_row28_col7,#T_e59d7_row28_col9,#T_e59d7_row28_col11,#T_e59d7_row30_col7,#T_e59d7_row30_col11,#T_e59d7_row31_col9,#T_e59d7_row31_col11,#T_e59d7_row32_col5,#T_e59d7_row32_col11,#T_e59d7_row33_col7,#T_e59d7_row35_col5,#T_e59d7_row36_col7,#T_e59d7_row38_col5,#T_e59d7_row38_col7,#T_e59d7_row40_col5,#T_e59d7_row40_col7,#T_e59d7_row41_col5,#T_e59d7_row41_col7,#T_e59d7_row44_col5,#T_e59d7_row45_col5,#T_e59d7_row46_col9,#T_e59d7_row46_col11,#T_e59d7_row51_col9,#T_e59d7_row51_col11,#T_e59d7_row52_col5,#T_e59d7_row55_col11,#T_e59d7_row58_col5,#T_e59d7_row61_col9,#T_e59d7_row65_col5,#T_e59d7_row66_col5,#T_e59d7_row66_col7,#T_e59d7_row66_col11,#T_e59d7_row67_col11,#T_e59d7_row70_col7,#T_e59d7_row71_col9,#T_e59d7_row72_col7,#T_e59d7_row73_col5,#T_e59d7_row76_col9,#T_e59d7_row77_col9,#T_e59d7_row78_col9,#T_e59d7_row80_col7,#T_e59d7_row83_col5,#T_e59d7_row84_col7,#T_e59d7_row86_col7,#T_e59d7_row86_col12,#T_e59d7_row88_col9,#T_e59d7_row89_col5,#T_e59d7_row89_col9,#T_e59d7_row89_col11,#T_e59d7_row95_col9,#T_e59d7_row99_col9,#T_e59d7_row101_col7,#T_e59d7_row101_col11,#T_e59d7_row102_col7,#T_e59d7_row102_col11,#T_e59d7_row102_col12,#T_e59d7_row103_col9,#T_e59d7_row103_col11,#T_e59d7_row105_col9,#T_e59d7_row108_col5,#T_e59d7_row109_col7,#T_e59d7_row109_col11,#T_e59d7_row115_col7,#T_e59d7_row115_col12,#T_e59d7_row117_col11,#T_e59d7_row118_col9,#T_e59d7_row118_col11,#T_e59d7_row119_col9,#T_e59d7_row124_col5,#T_e59d7_row129_col5,#T_e59d7_row133_col7,#T_e59d7_row133_col9,#T_e59d7_row137_col9{
            color:  red;
        }</style><table id="T_e59d7_" ><thead>    <tr>        <th class="blank level0" ></th>        <th class="col_heading level0 col0" >负债率</th>        <th class="col_heading level0 col1" >应收比</th>        <th class="col_heading level0 col2" >商誉比</th>        <th class="col_heading level0 col3" >ROE</th>        <th class="col_heading level0 col4" >利润率</th>        <th class="col_heading level0 col5" >收入增长</th>        <th class="col_heading level0 col6" >收入波动</th>        <th class="col_heading level0 col7" >盈利增长</th>        <th class="col_heading level0 col8" >盈利波动</th>        <th class="col_heading level0 col9" >FCF增长</th>        <th class="col_heading level0 col10" >FCF波动</th>        <th class="col_heading level0 col11" >DCF</th>        <th class="col_heading level0 col12" >盈利折现</th>        <th class="col_heading level0 col13" >国家</th>        <th class="col_heading level0 col14" >市值</th>    </tr>    <tr>        <th class="index_name level0" >Symbol</th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>    </tr></thead><tbody>
                <tr>
                        <th id="T_e59d7_level0_row0" class="row_heading level0 row0" >AACG</th>
                        <td id="T_e59d7_row0_col0" class="data row0 col0" >56.96</td>
                        <td id="T_e59d7_row0_col1" class="data row0 col1" >1.40</td>
                        <td id="T_e59d7_row0_col2" class="data row0 col2" >98.16</td>
                        <td id="T_e59d7_row0_col3" class="data row0 col3" >54.04</td>
                        <td id="T_e59d7_row0_col4" class="data row0 col4" >15841.14</td>
                        <td id="T_e59d7_row0_col5" class="data row0 col5" >2395.89</td>
                        <td id="T_e59d7_row0_col6" class="data row0 col6" >4164.56</td>
                        <td id="T_e59d7_row0_col7" class="data row0 col7" >-1264.05</td>
                        <td id="T_e59d7_row0_col8" class="data row0 col8" >2069.60</td>
                        <td id="T_e59d7_row0_col9" class="data row0 col9" >-163.54</td>
                        <td id="T_e59d7_row0_col10" class="data row0 col10" >175.05</td>
                        <td id="T_e59d7_row0_col11" class="data row0 col11" >0.22</td>
                        <td id="T_e59d7_row0_col12" class="data row0 col12" >-2602.76</td>
                        <td id="T_e59d7_row0_col13" class="data row0 col13" >China</td>
                        <td id="T_e59d7_row0_col14" class="data row0 col14" >0.10</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row1" class="row_heading level0 row1" >ABMD</th>
                        <td id="T_e59d7_row1_col0" class="data row1 col0" >11.02</td>
                        <td id="T_e59d7_row1_col1" class="data row1 col1" >11.47</td>
                        <td id="T_e59d7_row1_col2" class="data row1 col2" >5.91</td>
                        <td id="T_e59d7_row1_col3" class="data row1 col3" >19.98</td>
                        <td id="T_e59d7_row1_col4" class="data row1 col4" >25.83</td>
                        <td id="T_e59d7_row1_col5" class="data row1 col5" >13.22</td>
                        <td id="T_e59d7_row1_col6" class="data row1 col6" >14.80</td>
                        <td id="T_e59d7_row1_col7" class="data row1 col7" >40.13</td>
                        <td id="T_e59d7_row1_col8" class="data row1 col8" >80.31</td>
                        <td id="T_e59d7_row1_col9" class="data row1 col9" >27.48</td>
                        <td id="T_e59d7_row1_col10" class="data row1 col10" >26.26</td>
                        <td id="T_e59d7_row1_col11" class="data row1 col11" >5.15</td>
                        <td id="T_e59d7_row1_col12" class="data row1 col12" >6.57</td>
                        <td id="T_e59d7_row1_col13" class="data row1 col13" >United States</td>
                        <td id="T_e59d7_row1_col14" class="data row1 col14" >12.70</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row2" class="row_heading level0 row2" >ADBE</th>
                        <td id="T_e59d7_row2_col0" class="data row2 col0" >45.38</td>
                        <td id="T_e59d7_row2_col1" class="data row2 col1" >10.86</td>
                        <td id="T_e59d7_row2_col2" class="data row2 col2" >80.99</td>
                        <td id="T_e59d7_row2_col3" class="data row2 col3" >28.84</td>
                        <td id="T_e59d7_row2_col4" class="data row2 col4" >29.80</td>
                        <td id="T_e59d7_row2_col5" class="data row2 col5" >20.86</td>
                        <td id="T_e59d7_row2_col6" class="data row2 col6" >4.91</td>
                        <td id="T_e59d7_row2_col7" class="data row2 col7" >48.36</td>
                        <td id="T_e59d7_row2_col8" class="data row2 col8" >32.42</td>
                        <td id="T_e59d7_row2_col9" class="data row2 col9" >25.47</td>
                        <td id="T_e59d7_row2_col10" class="data row2 col10" >16.22</td>
                        <td id="T_e59d7_row2_col11" class="data row2 col11" >95.02</td>
                        <td id="T_e59d7_row2_col12" class="data row2 col12" >120.99</td>
                        <td id="T_e59d7_row2_col13" class="data row2 col13" >United States</td>
                        <td id="T_e59d7_row2_col14" class="data row2 col14" >236.98</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row3" class="row_heading level0 row3" >ADES</th>
                        <td id="T_e59d7_row3_col0" class="data row3 col0" >41.90</td>
                        <td id="T_e59d7_row3_col1" class="data row3 col1" >26.92</td>
                        <td id="T_e59d7_row3_col2" class="data row3 col2" >0.00</td>
                        <td id="T_e59d7_row3_col3" class="data row3 col3" >24.78</td>
                        <td id="T_e59d7_row3_col4" class="data row3 col4" >56.81</td>
                        <td id="T_e59d7_row3_col5" class="data row3 col5" >44.45</td>
                        <td id="T_e59d7_row3_col6" class="data row3 col6" >129.58</td>
                        <td id="T_e59d7_row3_col7" class="data row3 col7" >-43.23</td>
                        <td id="T_e59d7_row3_col8" class="data row3 col8" >99.55</td>
                        <td id="T_e59d7_row3_col9" class="data row3 col9" >-200.32</td>
                        <td id="T_e59d7_row3_col10" class="data row3 col10" >328.64</td>
                        <td id="T_e59d7_row3_col11" class="data row3 col11" >-0.20</td>
                        <td id="T_e59d7_row3_col12" class="data row3 col12" >0.06</td>
                        <td id="T_e59d7_row3_col13" class="data row3 col13" >United States</td>
                        <td id="T_e59d7_row3_col14" class="data row3 col14" >0.15</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row4" class="row_heading level0 row4" >AFYA</th>
                        <td id="T_e59d7_row4_col0" class="data row4 col0" >40.88</td>
                        <td id="T_e59d7_row4_col1" class="data row4 col1" >26.92</td>
                        <td id="T_e59d7_row4_col2" class="data row4 col2" >29.14</td>
                        <td id="T_e59d7_row4_col3" class="data row4 col3" >33.40</td>
                        <td id="T_e59d7_row4_col4" class="data row4 col4" >22.92</td>
                        <td id="T_e59d7_row4_col5" class="data row4 col5" >79.80</td>
                        <td id="T_e59d7_row4_col6" class="data row4 col6" >39.05</td>
                        <td id="T_e59d7_row4_col7" class="data row4 col7" >86.08</td>
                        <td id="T_e59d7_row4_col8" class="data row4 col8" >6.79</td>
                        <td id="T_e59d7_row4_col9" class="data row4 col9" >158.53</td>
                        <td id="T_e59d7_row4_col10" class="data row4 col10" >138.40</td>
                        <td id="T_e59d7_row4_col11" class="data row4 col11" >29.68</td>
                        <td id="T_e59d7_row4_col12" class="data row4 col12" >10.76</td>
                        <td id="T_e59d7_row4_col13" class="data row4 col13" >Brazil</td>
                        <td id="T_e59d7_row4_col14" class="data row4 col14" >2.35</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row5" class="row_heading level0 row5" >ALGN</th>
                        <td id="T_e59d7_row5_col0" class="data row5 col0" >33.04</td>
                        <td id="T_e59d7_row5_col1" class="data row5 col1" >28.66</td>
                        <td id="T_e59d7_row5_col2" class="data row5 col2" >13.75</td>
                        <td id="T_e59d7_row5_col3" class="data row5 col3" >34.95</td>
                        <td id="T_e59d7_row5_col4" class="data row5 col4" >31.57</td>
                        <td id="T_e59d7_row5_col5" class="data row5 col5" >19.52</td>
                        <td id="T_e59d7_row5_col6" class="data row5 col6" >15.58</td>
                        <td id="T_e59d7_row5_col7" class="data row5 col7" >128.22</td>
                        <td id="T_e59d7_row5_col8" class="data row5 col8" >152.91</td>
                        <td id="T_e59d7_row5_col9" class="data row5 col9" >33.89</td>
                        <td id="T_e59d7_row5_col10" class="data row5 col10" >47.77</td>
                        <td id="T_e59d7_row5_col11" class="data row5 col11" >12.12</td>
                        <td id="T_e59d7_row5_col12" class="data row5 col12" >96.37</td>
                        <td id="T_e59d7_row5_col13" class="data row5 col13" >United States</td>
                        <td id="T_e59d7_row5_col14" class="data row5 col14" >45.54</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row6" class="row_heading level0 row6" >AMGN</th>
                        <td id="T_e59d7_row6_col0" class="data row6 col0" >85.05</td>
                        <td id="T_e59d7_row6_col1" class="data row6 col1" >20.94</td>
                        <td id="T_e59d7_row6_col2" class="data row6 col2" >156.12</td>
                        <td id="T_e59d7_row6_col3" class="data row6 col3" >58.32</td>
                        <td id="T_e59d7_row6_col4" class="data row6 col4" >26.54</td>
                        <td id="T_e59d7_row6_col5" class="data row6 col5" >3.71</td>
                        <td id="T_e59d7_row6_col6" class="data row6 col6" >5.23</td>
                        <td id="T_e59d7_row6_col7" class="data row6 col7" >103.40</td>
                        <td id="T_e59d7_row6_col8" class="data row6 col8" >191.18</td>
                        <td id="T_e59d7_row6_col9" class="data row6 col9" >-0.95</td>
                        <td id="T_e59d7_row6_col10" class="data row6 col10" >17.59</td>
                        <td id="T_e59d7_row6_col11" class="data row6 col11" >122.17</td>
                        <td id="T_e59d7_row6_col12" class="data row6 col12" >615.21</td>
                        <td id="T_e59d7_row6_col13" class="data row6 col13" >United States</td>
                        <td id="T_e59d7_row6_col14" class="data row6 col14" >135.11</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row7" class="row_heading level0 row7" >AMSF</th>
                        <td id="T_e59d7_row7_col0" class="data row7 col0" >70.17</td>
                        <td id="T_e59d7_row7_col1" class="data row7 col1" >46.17</td>
                        <td id="T_e59d7_row7_col2" class="data row7 col2" >0.00</td>
                        <td id="T_e59d7_row7_col3" class="data row7 col3" >17.41</td>
                        <td id="T_e59d7_row7_col4" class="data row7 col4" >20.45</td>
                        <td id="T_e59d7_row7_col5" class="data row7 col5" >-3.20</td>
                        <td id="T_e59d7_row7_col6" class="data row7 col6" >4.63</td>
                        <td id="T_e59d7_row7_col7" class="data row7 col7" >25.92</td>
                        <td id="T_e59d7_row7_col8" class="data row7 col8" >30.90</td>
                        <td id="T_e59d7_row7_col9" class="data row7 col9" >-21.69</td>
                        <td id="T_e59d7_row7_col10" class="data row7 col10" >3.27</td>
                        <td id="T_e59d7_row7_col11" class="data row7 col11" >0.60</td>
                        <td id="T_e59d7_row7_col12" class="data row7 col12" >1.80</td>
                        <td id="T_e59d7_row7_col13" class="data row7 col13" >United States</td>
                        <td id="T_e59d7_row7_col14" class="data row7 col14" >1.25</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row8" class="row_heading level0 row8" >ANET</th>
                        <td id="T_e59d7_row8_col0" class="data row8 col0" >29.94</td>
                        <td id="T_e59d7_row8_col1" class="data row8 col1" >16.81</td>
                        <td id="T_e59d7_row8_col2" class="data row8 col2" >5.71</td>
                        <td id="T_e59d7_row8_col3" class="data row8 col3" >22.40</td>
                        <td id="T_e59d7_row8_col4" class="data row8 col4" >26.00</td>
                        <td id="T_e59d7_row8_col5" class="data row8 col5" >12.96</td>
                        <td id="T_e59d7_row8_col6" class="data row8 col6" >17.29</td>
                        <td id="T_e59d7_row8_col7" class="data row8 col7" >37.80</td>
                        <td id="T_e59d7_row8_col8" class="data row8 col8" >107.63</td>
                        <td id="T_e59d7_row8_col9" class="data row8 col9" >17.13</td>
                        <td id="T_e59d7_row8_col10" class="data row8 col10" >69.73</td>
                        <td id="T_e59d7_row8_col11" class="data row8 col11" >13.65</td>
                        <td id="T_e59d7_row8_col12" class="data row8 col12" >17.60</td>
                        <td id="T_e59d7_row8_col13" class="data row8 col13" >0</td>
                        <td id="T_e59d7_row8_col14" class="data row8 col14" >25.50</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row9" class="row_heading level0 row9" >APD</th>
                        <td id="T_e59d7_row9_col0" class="data row9 col0" >50.56</td>
                        <td id="T_e59d7_row9_col1" class="data row9 col1" >16.00</td>
                        <td id="T_e59d7_row9_col2" class="data row9 col2" >7.38</td>
                        <td id="T_e59d7_row9_col3" class="data row9 col3" >18.77</td>
                        <td id="T_e59d7_row9_col4" class="data row9 col4" >23.61</td>
                        <td id="T_e59d7_row9_col5" class="data row9 col5" >2.75</td>
                        <td id="T_e59d7_row9_col6" class="data row9 col6" >5.48</td>
                        <td id="T_e59d7_row9_col7" class="data row9 col7" >-8.46</td>
                        <td id="T_e59d7_row9_col8" class="data row9 col8" >36.41</td>
                        <td id="T_e59d7_row9_col9" class="data row9 col9" >21.15</td>
                        <td id="T_e59d7_row9_col10" class="data row9 col10" >56.52</td>
                        <td id="T_e59d7_row9_col11" class="data row9 col11" >17.52</td>
                        <td id="T_e59d7_row9_col12" class="data row9 col12" >20.28</td>
                        <td id="T_e59d7_row9_col13" class="data row9 col13" >United States</td>
                        <td id="T_e59d7_row9_col14" class="data row9 col14" >67.65</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row10" class="row_heading level0 row10" >APPF</th>
                        <td id="T_e59d7_row10_col0" class="data row10 col0" >26.59</td>
                        <td id="T_e59d7_row10_col1" class="data row10 col1" >3.24</td>
                        <td id="T_e59d7_row10_col2" class="data row10 col2" >19.64</td>
                        <td id="T_e59d7_row10_col3" class="data row10 col3" >29.01</td>
                        <td id="T_e59d7_row10_col4" class="data row10 col4" >20.63</td>
                        <td id="T_e59d7_row10_col5" class="data row10 col5" >29.33</td>
                        <td id="T_e59d7_row10_col6" class="data row10 col6" >7.23</td>
                        <td id="T_e59d7_row10_col7" class="data row10 col7" >174.60</td>
                        <td id="T_e59d7_row10_col8" class="data row10 col8" >140.79</td>
                        <td id="T_e59d7_row10_col9" class="data row10 col9" >3.65</td>
                        <td id="T_e59d7_row10_col10" class="data row10 col10" >19.34</td>
                        <td id="T_e59d7_row10_col11" class="data row10 col11" >0.43</td>
                        <td id="T_e59d7_row10_col12" class="data row10 col12" >13.07</td>
                        <td id="T_e59d7_row10_col13" class="data row10 col13" >United States</td>
                        <td id="T_e59d7_row10_col14" class="data row10 col14" >4.66</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row11" class="row_heading level0 row11" >ASML</th>
                        <td id="T_e59d7_row11_col0" class="data row11 col0" >49.15</td>
                        <td id="T_e59d7_row11_col1" class="data row11 col1" >23.84</td>
                        <td id="T_e59d7_row11_col2" class="data row11 col2" >33.39</td>
                        <td id="T_e59d7_row11_col3" class="data row11 col3" >21.91</td>
                        <td id="T_e59d7_row11_col4" class="data row11 col4" >23.52</td>
                        <td id="T_e59d7_row11_col5" class="data row11 col5" >16.12</td>
                        <td id="T_e59d7_row11_col6" class="data row11 col6" >7.29</td>
                        <td id="T_e59d7_row11_col7" class="data row11 col7" >20.84</td>
                        <td id="T_e59d7_row11_col8" class="data row11 col8" >18.95</td>
                        <td id="T_e59d7_row11_col9" class="data row11 col9" >38.47</td>
                        <td id="T_e59d7_row11_col10" class="data row11 col10" >34.85</td>
                        <td id="T_e59d7_row11_col11" class="data row11 col11" >80.67</td>
                        <td id="T_e59d7_row11_col12" class="data row11 col12" >58.29</td>
                        <td id="T_e59d7_row11_col13" class="data row11 col13" >Netherlands</td>
                        <td id="T_e59d7_row11_col14" class="data row11 col14" >280.77</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row12" class="row_heading level0 row12" >ATHM</th>
                        <td id="T_e59d7_row12_col0" class="data row12 col0" >20.74</td>
                        <td id="T_e59d7_row12_col1" class="data row12 col1" >39.53</td>
                        <td id="T_e59d7_row12_col2" class="data row12 col2" >23.10</td>
                        <td id="T_e59d7_row12_col3" class="data row12 col3" >23.04</td>
                        <td id="T_e59d7_row12_col4" class="data row12 col4" >37.31</td>
                        <td id="T_e59d7_row12_col5" class="data row12 col5" >11.91</td>
                        <td id="T_e59d7_row12_col6" class="data row12 col6" >7.86</td>
                        <td id="T_e59d7_row12_col7" class="data row12 col7" >20.44</td>
                        <td id="T_e59d7_row12_col8" class="data row12 col8" >20.08</td>
                        <td id="T_e59d7_row12_col9" class="data row12 col9" >9.90</td>
                        <td id="T_e59d7_row12_col10" class="data row12 col10" >18.60</td>
                        <td id="T_e59d7_row12_col11" class="data row12 col11" >45.95</td>
                        <td id="T_e59d7_row12_col12" class="data row12 col12" >61.35</td>
                        <td id="T_e59d7_row12_col13" class="data row12 col13" >0</td>
                        <td id="T_e59d7_row12_col14" class="data row12 col14" >9.42</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row13" class="row_heading level0 row13" >AVGO</th>
                        <td id="T_e59d7_row13_col0" class="data row13 col0" >68.52</td>
                        <td id="T_e59d7_row13_col1" class="data row13 col1" >9.62</td>
                        <td id="T_e59d7_row13_col2" class="data row13 col2" >181.98</td>
                        <td id="T_e59d7_row13_col3" class="data row13 col3" >19.41</td>
                        <td id="T_e59d7_row13_col4" class="data row13 col4" >23.21</td>
                        <td id="T_e59d7_row13_col5" class="data row13 col5" >10.77</td>
                        <td id="T_e59d7_row13_col6" class="data row13 col6" >6.58</td>
                        <td id="T_e59d7_row13_col7" class="data row13 col7" >185.14</td>
                        <td id="T_e59d7_row13_col8" class="data row13 col8" >382.97</td>
                        <td id="T_e59d7_row13_col9" class="data row13 col9" >29.32</td>
                        <td id="T_e59d7_row13_col10" class="data row13 col10" >19.35</td>
                        <td id="T_e59d7_row13_col11" class="data row13 col11" >226.17</td>
                        <td id="T_e59d7_row13_col12" class="data row13 col12" >1277.71</td>
                        <td id="T_e59d7_row13_col13" class="data row13 col13" >United States</td>
                        <td id="T_e59d7_row13_col14" class="data row13 col14" >193.43</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row14" class="row_heading level0 row14" >AVGOP</th>
                        <td id="T_e59d7_row14_col0" class="data row14 col0" >68.52</td>
                        <td id="T_e59d7_row14_col1" class="data row14 col1" >9.62</td>
                        <td id="T_e59d7_row14_col2" class="data row14 col2" >181.98</td>
                        <td id="T_e59d7_row14_col3" class="data row14 col3" >19.41</td>
                        <td id="T_e59d7_row14_col4" class="data row14 col4" >23.21</td>
                        <td id="T_e59d7_row14_col5" class="data row14 col5" >10.77</td>
                        <td id="T_e59d7_row14_col6" class="data row14 col6" >6.58</td>
                        <td id="T_e59d7_row14_col7" class="data row14 col7" >185.14</td>
                        <td id="T_e59d7_row14_col8" class="data row14 col8" >382.97</td>
                        <td id="T_e59d7_row14_col9" class="data row14 col9" >29.32</td>
                        <td id="T_e59d7_row14_col10" class="data row14 col10" >19.35</td>
                        <td id="T_e59d7_row14_col11" class="data row14 col11" >226.17</td>
                        <td id="T_e59d7_row14_col12" class="data row14 col12" >1277.71</td>
                        <td id="T_e59d7_row14_col13" class="data row14 col13" >United States</td>
                        <td id="T_e59d7_row14_col14" class="data row14 col14" >0.00</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row15" class="row_heading level0 row15" >BABA</th>
                        <td id="T_e59d7_row15_col0" class="data row15 col0" >33.70</td>
                        <td id="T_e59d7_row15_col1" class="data row15 col1" >8.56</td>
                        <td id="T_e59d7_row15_col2" class="data row15 col2" >36.64</td>
                        <td id="T_e59d7_row15_col3" class="data row15 col3" >17.71</td>
                        <td id="T_e59d7_row15_col4" class="data row15 col4" >26.46</td>
                        <td id="T_e59d7_row15_col5" class="data row15 col5" >47.99</td>
                        <td id="T_e59d7_row15_col6" class="data row15 col6" >11.65</td>
                        <td id="T_e59d7_row15_col7" class="data row15 col7" >51.30</td>
                        <td id="T_e59d7_row15_col8" class="data row15 col8" >16.92</td>
                        <td id="T_e59d7_row15_col9" class="data row15 col9" >28.25</td>
                        <td id="T_e59d7_row15_col10" class="data row15 col10" >19.50</td>
                        <td id="T_e59d7_row15_col11" class="data row15 col11" >2820.11</td>
                        <td id="T_e59d7_row15_col12" class="data row15 col12" >3534.63</td>
                        <td id="T_e59d7_row15_col13" class="data row15 col13" >China</td>
                        <td id="T_e59d7_row15_col14" class="data row15 col14" >595.64</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row16" class="row_heading level0 row16" >BIIB</th>
                        <td id="T_e59d7_row16_col0" class="data row16 col0" >56.59</td>
                        <td id="T_e59d7_row16_col1" class="data row16 col1" >17.31</td>
                        <td id="T_e59d7_row16_col2" class="data row16 col2" >53.85</td>
                        <td id="T_e59d7_row16_col3" class="data row16 col3" >33.91</td>
                        <td id="T_e59d7_row16_col4" class="data row16 col4" >31.08</td>
                        <td id="T_e59d7_row16_col5" class="data row16 col5" >3.33</td>
                        <td id="T_e59d7_row16_col6" class="data row16 col6" >8.61</td>
                        <td id="T_e59d7_row16_col7" class="data row16 col7" >25.11</td>
                        <td id="T_e59d7_row16_col8" class="data row16 col8" >53.71</td>
                        <td id="T_e59d7_row16_col9" class="data row16 col9" >8.73</td>
                        <td id="T_e59d7_row16_col10" class="data row16 col10" >45.83</td>
                        <td id="T_e59d7_row16_col11" class="data row16 col11" >78.08</td>
                        <td id="T_e59d7_row16_col12" class="data row16 col12" >100.37</td>
                        <td id="T_e59d7_row16_col13" class="data row16 col13" >United States</td>
                        <td id="T_e59d7_row16_col14" class="data row16 col14" >40.55</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row17" class="row_heading level0 row17" >BIO</th>
                        <td id="T_e59d7_row17_col0" class="data row17 col0" >23.84</td>
                        <td id="T_e59d7_row17_col1" class="data row17 col1" >16.53</td>
                        <td id="T_e59d7_row17_col2" class="data row17 col2" >2.95</td>
                        <td id="T_e59d7_row17_col3" class="data row17 col3" >20.59</td>
                        <td id="T_e59d7_row17_col4" class="data row17 col4" >61.81</td>
                        <td id="T_e59d7_row17_col5" class="data row17 col5" >5.69</td>
                        <td id="T_e59d7_row17_col6" class="data row17 col6" >4.58</td>
                        <td id="T_e59d7_row17_col7" class="data row17 col7" >232.17</td>
                        <td id="T_e59d7_row17_col8" class="data row17 col8" >135.37</td>
                        <td id="T_e59d7_row17_col9" class="data row17 col9" >-700.05</td>
                        <td id="T_e59d7_row17_col10" class="data row17 col10" >1354.94</td>
                        <td id="T_e59d7_row17_col11" class="data row17 col11" >-566.38</td>
                        <td id="T_e59d7_row17_col12" class="data row17 col12" >618.38</td>
                        <td id="T_e59d7_row17_col13" class="data row17 col13" >United States</td>
                        <td id="T_e59d7_row17_col14" class="data row17 col14" >17.30</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row18" class="row_heading level0 row18" >BMA</th>
                        <td id="T_e59d7_row18_col0" class="data row18 col0" >80.77</td>
                        <td id="T_e59d7_row18_col1" class="data row18 col1" >19.34</td>
                        <td id="T_e59d7_row18_col2" class="data row18 col2" >0.00</td>
                        <td id="T_e59d7_row18_col3" class="data row18 col3" >19.02</td>
                        <td id="T_e59d7_row18_col4" class="data row18 col4" >25.00</td>
                        <td id="T_e59d7_row18_col5" class="data row18 col5" >28.94</td>
                        <td id="T_e59d7_row18_col6" class="data row18 col6" >67.72</td>
                        <td id="T_e59d7_row18_col7" class="data row18 col7" >82.50</td>
                        <td id="T_e59d7_row18_col8" class="data row18 col8" >76.26</td>
                        <td id="T_e59d7_row18_col9" class="data row18 col9" >-263.69</td>
                        <td id="T_e59d7_row18_col10" class="data row18 col10" >366.14</td>
                        <td id="T_e59d7_row18_col11" class="data row18 col11" >-1005.66</td>
                        <td id="T_e59d7_row18_col12" class="data row18 col12" >1380.80</td>
                        <td id="T_e59d7_row18_col13" class="data row18 col13" >Argentina</td>
                        <td id="T_e59d7_row18_col14" class="data row18 col14" >1.07</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row19" class="row_heading level0 row19" >BPMP</th>
                        <td id="T_e59d7_row19_col0" class="data row19 col0" >65.62</td>
                        <td id="T_e59d7_row19_col1" class="data row19 col1" >10.63</td>
                        <td id="T_e59d7_row19_col2" class="data row19 col2" >0.00</td>
                        <td id="T_e59d7_row19_col3" class="data row19 col3" >126.01</td>
                        <td id="T_e59d7_row19_col4" class="data row19 col4" >98.95</td>
                        <td id="T_e59d7_row19_col5" class="data row19 col5" >6.11</td>
                        <td id="T_e59d7_row19_col6" class="data row19 col6" >5.21</td>
                        <td id="T_e59d7_row19_col7" class="data row19 col7" >179.23</td>
                        <td id="T_e59d7_row19_col8" class="data row19 col8" >287.83</td>
                        <td id="T_e59d7_row19_col9" class="data row19 col9" >55.23</td>
                        <td id="T_e59d7_row19_col10" class="data row19 col10" >88.35</td>
                        <td id="T_e59d7_row19_col11" class="data row19 col11" >6.77</td>
                        <td id="T_e59d7_row19_col12" class="data row19 col12" >30.05</td>
                        <td id="T_e59d7_row19_col13" class="data row19 col13" >United States</td>
                        <td id="T_e59d7_row19_col14" class="data row19 col14" >1.49</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row20" class="row_heading level0 row20" >BPYU</th>
                        <td id="T_e59d7_row20_col0" class="data row20 col0" >84.87</td>
                        <td id="T_e59d7_row20_col1" class="data row20 col1" >46.91</td>
                        <td id="T_e59d7_row20_col2" class="data row20 col2" >0.00</td>
                        <td id="T_e59d7_row20_col3" class="data row20 col3" >102.31</td>
                        <td id="T_e59d7_row20_col4" class="data row20 col4" >47.42</td>
                        <td id="T_e59d7_row20_col5" class="data row20 col5" >-18.30</td>
                        <td id="T_e59d7_row20_col6" class="data row20 col6" >6.65</td>
                        <td id="T_e59d7_row20_col7" class="data row20 col7" >56.17</td>
                        <td id="T_e59d7_row20_col8" class="data row20 col8" >413.04</td>
                        <td id="T_e59d7_row20_col9" class="data row20 col9" >0.00</td>
                        <td id="T_e59d7_row20_col10" class="data row20 col10" >0.00</td>
                        <td id="T_e59d7_row20_col11" class="data row20 col11" >0.00</td>
                        <td id="T_e59d7_row20_col12" class="data row20 col12" >50.15</td>
                        <td id="T_e59d7_row20_col13" class="data row20 col13" >United States</td>
                        <td id="T_e59d7_row20_col14" class="data row20 col14" >0.72</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row21" class="row_heading level0 row21" >BPYUP</th>
                        <td id="T_e59d7_row21_col0" class="data row21 col0" >84.87</td>
                        <td id="T_e59d7_row21_col1" class="data row21 col1" >46.91</td>
                        <td id="T_e59d7_row21_col2" class="data row21 col2" >0.00</td>
                        <td id="T_e59d7_row21_col3" class="data row21 col3" >102.31</td>
                        <td id="T_e59d7_row21_col4" class="data row21 col4" >47.42</td>
                        <td id="T_e59d7_row21_col5" class="data row21 col5" >-18.30</td>
                        <td id="T_e59d7_row21_col6" class="data row21 col6" >6.65</td>
                        <td id="T_e59d7_row21_col7" class="data row21 col7" >56.17</td>
                        <td id="T_e59d7_row21_col8" class="data row21 col8" >413.04</td>
                        <td id="T_e59d7_row21_col9" class="data row21 col9" >0.00</td>
                        <td id="T_e59d7_row21_col10" class="data row21 col10" >0.00</td>
                        <td id="T_e59d7_row21_col11" class="data row21 col11" >0.00</td>
                        <td id="T_e59d7_row21_col12" class="data row21 col12" >50.15</td>
                        <td id="T_e59d7_row21_col13" class="data row21 col13" >United States</td>
                        <td id="T_e59d7_row21_col14" class="data row21 col14" >0.00</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row22" class="row_heading level0 row22" >BRKS</th>
                        <td id="T_e59d7_row22_col0" class="data row22 col0" >22.16</td>
                        <td id="T_e59d7_row22_col1" class="data row22 col1" >22.86</td>
                        <td id="T_e59d7_row22_col2" class="data row22 col2" >41.33</td>
                        <td id="T_e59d7_row22_col3" class="data row22 col3" >17.57</td>
                        <td id="T_e59d7_row22_col4" class="data row22 col4" >23.39</td>
                        <td id="T_e59d7_row22_col5" class="data row22 col5" >19.43</td>
                        <td id="T_e59d7_row22_col6" class="data row22 col6" >4.37</td>
                        <td id="T_e59d7_row22_col7" class="data row22 col7" >92.08</td>
                        <td id="T_e59d7_row22_col8" class="data row22 col8" >180.27</td>
                        <td id="T_e59d7_row22_col9" class="data row22 col9" >-40.09</td>
                        <td id="T_e59d7_row22_col10" class="data row22 col10" >57.49</td>
                        <td id="T_e59d7_row22_col11" class="data row22 col11" >0.17</td>
                        <td id="T_e59d7_row22_col12" class="data row22 col12" >13.92</td>
                        <td id="T_e59d7_row22_col13" class="data row22 col13" >United States</td>
                        <td id="T_e59d7_row22_col14" class="data row22 col14" >7.47</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row23" class="row_heading level0 row23" >BSIG</th>
                        <td id="T_e59d7_row23_col0" class="data row23 col0" >72.13</td>
                        <td id="T_e59d7_row23_col1" class="data row23 col1" >17.10</td>
                        <td id="T_e59d7_row23_col2" class="data row23 col2" >60.22</td>
                        <td id="T_e59d7_row23_col3" class="data row23 col3" >145.02</td>
                        <td id="T_e59d7_row23_col4" class="data row23 col4" >20.73</td>
                        <td id="T_e59d7_row23_col5" class="data row23 col5" >-6.71</td>
                        <td id="T_e59d7_row23_col6" class="data row23 col6" >9.03</td>
                        <td id="T_e59d7_row23_col7" class="data row23 col7" >1079.94</td>
                        <td id="T_e59d7_row23_col8" class="data row23 col8" >1790.75</td>
                        <td id="T_e59d7_row23_col9" class="data row23 col9" >-99.51</td>
                        <td id="T_e59d7_row23_col10" class="data row23 col10" >122.82</td>
                        <td id="T_e59d7_row23_col11" class="data row23 col11" >0.00</td>
                        <td id="T_e59d7_row23_col12" class="data row23 col12" >2906.02</td>
                        <td id="T_e59d7_row23_col13" class="data row23 col13" >United Kingdom</td>
                        <td id="T_e59d7_row23_col14" class="data row23 col14" >1.77</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row24" class="row_heading level0 row24" >BSM</th>
                        <td id="T_e59d7_row24_col0" class="data row24 col0" >14.87</td>
                        <td id="T_e59d7_row24_col1" class="data row24 col1" >21.53</td>
                        <td id="T_e59d7_row24_col2" class="data row24 col2" >0.00</td>
                        <td id="T_e59d7_row24_col3" class="data row24 col3" >24.01</td>
                        <td id="T_e59d7_row24_col4" class="data row24 col4" >46.29</td>
                        <td id="T_e59d7_row24_col5" class="data row24 col5" >-0.05</td>
                        <td id="T_e59d7_row24_col6" class="data row24 col6" >48.66</td>
                        <td id="T_e59d7_row24_col7" class="data row24 col7" >5.79</td>
                        <td id="T_e59d7_row24_col8" class="data row24 col8" >71.64</td>
                        <td id="T_e59d7_row24_col9" class="data row24 col9" >30.27</td>
                        <td id="T_e59d7_row24_col10" class="data row24 col10" >195.74</td>
                        <td id="T_e59d7_row24_col11" class="data row24 col11" >3.10</td>
                        <td id="T_e59d7_row24_col12" class="data row24 col12" >2.93</td>
                        <td id="T_e59d7_row24_col13" class="data row24 col13" >United States</td>
                        <td id="T_e59d7_row24_col14" class="data row24 col14" >2.12</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row25" class="row_heading level0 row25" >BSVN</th>
                        <td id="T_e59d7_row25_col0" class="data row25 col0" >89.44</td>
                        <td id="T_e59d7_row25_col1" class="data row25 col1" >0.00</td>
                        <td id="T_e59d7_row25_col2" class="data row25 col2" >0.94</td>
                        <td id="T_e59d7_row25_col3" class="data row25 col3" >22.20</td>
                        <td id="T_e59d7_row25_col4" class="data row25 col4" >46.66</td>
                        <td id="T_e59d7_row25_col5" class="data row25 col5" >4.34</td>
                        <td id="T_e59d7_row25_col6" class="data row25 col6" >3.82</td>
                        <td id="T_e59d7_row25_col7" class="data row25 col7" >24.08</td>
                        <td id="T_e59d7_row25_col8" class="data row25 col8" >102.00</td>
                        <td id="T_e59d7_row25_col9" class="data row25 col9" >12.04</td>
                        <td id="T_e59d7_row25_col10" class="data row25 col10" >47.62</td>
                        <td id="T_e59d7_row25_col11" class="data row25 col11" >0.39</td>
                        <td id="T_e59d7_row25_col12" class="data row25 col12" >0.44</td>
                        <td id="T_e59d7_row25_col13" class="data row25 col13" >United States</td>
                        <td id="T_e59d7_row25_col14" class="data row25 col14" >0.17</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row26" class="row_heading level0 row26" >BTI</th>
                        <td id="T_e59d7_row26_col0" class="data row26 col0" >54.28</td>
                        <td id="T_e59d7_row26_col1" class="data row26 col1" >14.74</td>
                        <td id="T_e59d7_row26_col2" class="data row26 col2" >69.22</td>
                        <td id="T_e59d7_row26_col3" class="data row26 col3" >22.55</td>
                        <td id="T_e59d7_row26_col4" class="data row26 col4" >65.78</td>
                        <td id="T_e59d7_row26_col5" class="data row26 col5" >10.15</td>
                        <td id="T_e59d7_row26_col6" class="data row26 col6" >13.37</td>
                        <td id="T_e59d7_row26_col7" class="data row26 col7" >-25.71</td>
                        <td id="T_e59d7_row26_col8" class="data row26 col8" >51.16</td>
                        <td id="T_e59d7_row26_col9" class="data row26 col9" >36.00</td>
                        <td id="T_e59d7_row26_col10" class="data row26 col10" >64.62</td>
                        <td id="T_e59d7_row26_col11" class="data row26 col11" >239.27</td>
                        <td id="T_e59d7_row26_col12" class="data row26 col12" >78.88</td>
                        <td id="T_e59d7_row26_col13" class="data row26 col13" >United Kingdom</td>
                        <td id="T_e59d7_row26_col14" class="data row26 col14" >89.72</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row27" class="row_heading level0 row27" >CDNS</th>
                        <td id="T_e59d7_row27_col0" class="data row27 col0" >36.90</td>
                        <td id="T_e59d7_row27_col1" class="data row27 col1" >12.98</td>
                        <td id="T_e59d7_row27_col2" class="data row27 col2" >31.37</td>
                        <td id="T_e59d7_row27_col3" class="data row27 col3" >29.55</td>
                        <td id="T_e59d7_row27_col4" class="data row27 col4" >22.76</td>
                        <td id="T_e59d7_row27_col5" class="data row27 col5" >11.38</td>
                        <td id="T_e59d7_row27_col6" class="data row27 col6" >3.01</td>
                        <td id="T_e59d7_row27_col7" class="data row27 col7" >71.72</td>
                        <td id="T_e59d7_row27_col8" class="data row27 col8" >113.16</td>
                        <td id="T_e59d7_row27_col9" class="data row27 col9" >25.28</td>
                        <td id="T_e59d7_row27_col10" class="data row27 col10" >5.68</td>
                        <td id="T_e59d7_row27_col11" class="data row27 col11" >14.47</td>
                        <td id="T_e59d7_row27_col12" class="data row27 col12" >31.43</td>
                        <td id="T_e59d7_row27_col13" class="data row27 col13" >United States</td>
                        <td id="T_e59d7_row27_col14" class="data row27 col14" >34.65</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row28" class="row_heading level0 row28" >CHNR</th>
                        <td id="T_e59d7_row28_col0" class="data row28 col0" >28.95</td>
                        <td id="T_e59d7_row28_col1" class="data row28 col1" >0.06</td>
                        <td id="T_e59d7_row28_col2" class="data row28 col2" >0.00</td>
                        <td id="T_e59d7_row28_col3" class="data row28 col3" >66.89</td>
                        <td id="T_e59d7_row28_col4" class="data row28 col4" >164.48</td>
                        <td id="T_e59d7_row28_col5" class="data row28 col5" >inf</td>
                        <td id="T_e59d7_row28_col6" class="data row28 col6" >0.00</td>
                        <td id="T_e59d7_row28_col7" class="data row28 col7" >-213.71</td>
                        <td id="T_e59d7_row28_col8" class="data row28 col8" >296.07</td>
                        <td id="T_e59d7_row28_col9" class="data row28 col9" >-26.90</td>
                        <td id="T_e59d7_row28_col10" class="data row28 col10" >55.34</td>
                        <td id="T_e59d7_row28_col11" class="data row28 col11" >-0.05</td>
                        <td id="T_e59d7_row28_col12" class="data row28 col12" >0.06</td>
                        <td id="T_e59d7_row28_col13" class="data row28 col13" >Hong Kong</td>
                        <td id="T_e59d7_row28_col14" class="data row28 col14" >0.06</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row29" class="row_heading level0 row29" >CIH</th>
                        <td id="T_e59d7_row29_col0" class="data row29 col0" >57.33</td>
                        <td id="T_e59d7_row29_col1" class="data row29 col1" >5.49</td>
                        <td id="T_e59d7_row29_col2" class="data row29 col2" >0.54</td>
                        <td id="T_e59d7_row29_col3" class="data row29 col3" >381.11</td>
                        <td id="T_e59d7_row29_col4" class="data row29 col4" >41.54</td>
                        <td id="T_e59d7_row29_col5" class="data row29 col5" >24.35</td>
                        <td id="T_e59d7_row29_col6" class="data row29 col6" >14.03</td>
                        <td id="T_e59d7_row29_col7" class="data row29 col7" >32.46</td>
                        <td id="T_e59d7_row29_col8" class="data row29 col8" >14.53</td>
                        <td id="T_e59d7_row29_col9" class="data row29 col9" >23.84</td>
                        <td id="T_e59d7_row29_col10" class="data row29 col10" >35.76</td>
                        <td id="T_e59d7_row29_col11" class="data row29 col11" >5.60</td>
                        <td id="T_e59d7_row29_col12" class="data row29 col12" >5.83</td>
                        <td id="T_e59d7_row29_col13" class="data row29 col13" >China</td>
                        <td id="T_e59d7_row29_col14" class="data row29 col14" >0.17</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row30" class="row_heading level0 row30" >CLF</th>
                        <td id="T_e59d7_row30_col0" class="data row30 col0" >81.64</td>
                        <td id="T_e59d7_row30_col1" class="data row30 col1" >22.28</td>
                        <td id="T_e59d7_row30_col2" class="data row30 col2" >69.67</td>
                        <td id="T_e59d7_row30_col3" class="data row30 col3" >64.78</td>
                        <td id="T_e59d7_row30_col4" class="data row30 col4" >20.12</td>
                        <td id="T_e59d7_row30_col5" class="data row30 col5" >59.78</td>
                        <td id="T_e59d7_row30_col6" class="data row30 col6" >96.68</td>
                        <td id="T_e59d7_row30_col7" class="data row30 col7" >-2.77</td>
                        <td id="T_e59d7_row30_col8" class="data row30 col8" >185.09</td>
                        <td id="T_e59d7_row30_col9" class="data row30 col9" >221.70</td>
                        <td id="T_e59d7_row30_col10" class="data row30 col10" >498.70</td>
                        <td id="T_e59d7_row30_col11" class="data row30 col11" >-46.78</td>
                        <td id="T_e59d7_row30_col12" class="data row30 col12" >4.90</td>
                        <td id="T_e59d7_row30_col13" class="data row30 col13" >United States</td>
                        <td id="T_e59d7_row30_col14" class="data row30 col14" >10.05</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row31" class="row_heading level0 row31" >CMCL</th>
                        <td id="T_e59d7_row31_col0" class="data row31 col0" >11.17</td>
                        <td id="T_e59d7_row31_col1" class="data row31 col1" >5.02</td>
                        <td id="T_e59d7_row31_col2" class="data row31 col2" >0.00</td>
                        <td id="T_e59d7_row31_col3" class="data row31 col3" >20.89</td>
                        <td id="T_e59d7_row31_col4" class="data row31 col4" >27.75</td>
                        <td id="T_e59d7_row31_col5" class="data row31 col5" >13.60</td>
                        <td id="T_e59d7_row31_col6" class="data row31 col6" >17.14</td>
                        <td id="T_e59d7_row31_col7" class="data row31 col7" >84.82</td>
                        <td id="T_e59d7_row31_col8" class="data row31 col8" >180.90</td>
                        <td id="T_e59d7_row31_col9" class="data row31 col9" >-156.36</td>
                        <td id="T_e59d7_row31_col10" class="data row31 col10" >121.48</td>
                        <td id="T_e59d7_row31_col11" class="data row31 col11" >-0.00</td>
                        <td id="T_e59d7_row31_col12" class="data row31 col12" >1.52</td>
                        <td id="T_e59d7_row31_col13" class="data row31 col13" >Canada</td>
                        <td id="T_e59d7_row31_col14" class="data row31 col14" >0.18</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row32" class="row_heading level0 row32" >CNNE</th>
                        <td id="T_e59d7_row32_col0" class="data row32 col0" >17.95</td>
                        <td id="T_e59d7_row32_col1" class="data row32 col1" >3.00</td>
                        <td id="T_e59d7_row32_col2" class="data row32 col2" >1.41</td>
                        <td id="T_e59d7_row32_col3" class="data row32 col3" >16.29</td>
                        <td id="T_e59d7_row32_col4" class="data row32 col4" >81.00</td>
                        <td id="T_e59d7_row32_col5" class="data row32 col5" >-17.60</td>
                        <td id="T_e59d7_row32_col6" class="data row32 col6" >24.14</td>
                        <td id="T_e59d7_row32_col7" class="data row32 col7" >772.06</td>
                        <td id="T_e59d7_row32_col8" class="data row32 col8" >1252.42</td>
                        <td id="T_e59d7_row32_col9" class="data row32 col9" >46.89</td>
                        <td id="T_e59d7_row32_col10" class="data row32 col10" >132.05</td>
                        <td id="T_e59d7_row32_col11" class="data row32 col11" >-3.94</td>
                        <td id="T_e59d7_row32_col12" class="data row32 col12" >3614.06</td>
                        <td id="T_e59d7_row32_col13" class="data row32 col13" >0</td>
                        <td id="T_e59d7_row32_col14" class="data row32 col14" >3.22</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row33" class="row_heading level0 row33" >CNS</th>
                        <td id="T_e59d7_row33_col0" class="data row33 col0" >35.46</td>
                        <td id="T_e59d7_row33_col1" class="data row33 col1" >17.50</td>
                        <td id="T_e59d7_row33_col2" class="data row33 col2" >11.05</td>
                        <td id="T_e59d7_row33_col3" class="data row33 col3" >47.87</td>
                        <td id="T_e59d7_row33_col4" class="data row33 col4" >26.21</td>
                        <td id="T_e59d7_row33_col5" class="data row33 col5" >4.17</td>
                        <td id="T_e59d7_row33_col6" class="data row33 col6" >3.58</td>
                        <td id="T_e59d7_row33_col7" class="data row33 col7" >-0.34</td>
                        <td id="T_e59d7_row33_col8" class="data row33 col8" >37.15</td>
                        <td id="T_e59d7_row33_col9" class="data row33 col9" >25.48</td>
                        <td id="T_e59d7_row33_col10" class="data row33 col10" >69.87</td>
                        <td id="T_e59d7_row33_col11" class="data row33 col11" >2.13</td>
                        <td id="T_e59d7_row33_col12" class="data row33 col12" >1.31</td>
                        <td id="T_e59d7_row33_col13" class="data row33 col13" >United States</td>
                        <td id="T_e59d7_row33_col14" class="data row33 col14" >3.58</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row34" class="row_heading level0 row34" >CODA</th>
                        <td id="T_e59d7_row34_col0" class="data row34 col0" >9.58</td>
                        <td id="T_e59d7_row34_col1" class="data row34 col1" >15.00</td>
                        <td id="T_e59d7_row34_col2" class="data row34 col2" >9.83</td>
                        <td id="T_e59d7_row34_col3" class="data row34 col3" >17.85</td>
                        <td id="T_e59d7_row34_col4" class="data row34 col4" >20.94</td>
                        <td id="T_e59d7_row34_col5" class="data row34 col5" >6.34</td>
                        <td id="T_e59d7_row34_col6" class="data row34 col6" >30.04</td>
                        <td id="T_e59d7_row34_col7" class="data row34 col7" >6.04</td>
                        <td id="T_e59d7_row34_col8" class="data row34 col8" >42.71</td>
                        <td id="T_e59d7_row34_col9" class="data row34 col9" >30.12</td>
                        <td id="T_e59d7_row34_col10" class="data row34 col10" >79.02</td>
                        <td id="T_e59d7_row34_col11" class="data row34 col11" >0.08</td>
                        <td id="T_e59d7_row34_col12" class="data row34 col12" >0.06</td>
                        <td id="T_e59d7_row34_col13" class="data row34 col13" >United States</td>
                        <td id="T_e59d7_row34_col14" class="data row34 col14" >0.10</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row35" class="row_heading level0 row35" >COG</th>
                        <td id="T_e59d7_row35_col0" class="data row35 col0" >51.02</td>
                        <td id="T_e59d7_row35_col1" class="data row35 col1" >15.72</td>
                        <td id="T_e59d7_row35_col2" class="data row35 col2" >0.00</td>
                        <td id="T_e59d7_row35_col3" class="data row35 col3" >17.84</td>
                        <td id="T_e59d7_row35_col4" class="data row35 col4" >20.08</td>
                        <td id="T_e59d7_row35_col5" class="data row35 col5" >-4.64</td>
                        <td id="T_e59d7_row35_col6" class="data row35 col6" >26.06</td>
                        <td id="T_e59d7_row35_col7" class="data row35 col7" >135.52</td>
                        <td id="T_e59d7_row35_col8" class="data row35 col8" >280.42</td>
                        <td id="T_e59d7_row35_col9" class="data row35 col9" >66.90</td>
                        <td id="T_e59d7_row35_col10" class="data row35 col10" >141.05</td>
                        <td id="T_e59d7_row35_col11" class="data row35 col11" >16.36</td>
                        <td id="T_e59d7_row35_col12" class="data row35 col12" >57.07</td>
                        <td id="T_e59d7_row35_col13" class="data row35 col13" >United States</td>
                        <td id="T_e59d7_row35_col14" class="data row35 col14" >6.81</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row36" class="row_heading level0 row36" >CORT</th>
                        <td id="T_e59d7_row36_col0" class="data row36 col0" >8.46</td>
                        <td id="T_e59d7_row36_col1" class="data row36 col1" >7.77</td>
                        <td id="T_e59d7_row36_col2" class="data row36 col2" >0.00</td>
                        <td id="T_e59d7_row36_col3" class="data row36 col3" >35.14</td>
                        <td id="T_e59d7_row36_col4" class="data row36 col4" >42.95</td>
                        <td id="T_e59d7_row36_col5" class="data row36 col5" >31.76</td>
                        <td id="T_e59d7_row36_col6" class="data row36 col6" >22.81</td>
                        <td id="T_e59d7_row36_col7" class="data row36 col7" >-1.38</td>
                        <td id="T_e59d7_row36_col8" class="data row36 col8" >35.37</td>
                        <td id="T_e59d7_row36_col9" class="data row36 col9" >39.77</td>
                        <td id="T_e59d7_row36_col10" class="data row36 col10" >44.14</td>
                        <td id="T_e59d7_row36_col11" class="data row36 col11" >3.77</td>
                        <td id="T_e59d7_row36_col12" class="data row36 col12" >1.24</td>
                        <td id="T_e59d7_row36_col13" class="data row36 col13" >United States</td>
                        <td id="T_e59d7_row36_col14" class="data row36 col14" >2.50</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row37" class="row_heading level0 row37" >CPRT</th>
                        <td id="T_e59d7_row37_col0" class="data row37 col0" >27.95</td>
                        <td id="T_e59d7_row37_col1" class="data row37 col1" >5.29</td>
                        <td id="T_e59d7_row37_col2" class="data row37 col2" >13.80</td>
                        <td id="T_e59d7_row37_col3" class="data row37 col3" >30.93</td>
                        <td id="T_e59d7_row37_col4" class="data row37 col4" >27.77</td>
                        <td id="T_e59d7_row37_col5" class="data row37 col5" >15.27</td>
                        <td id="T_e59d7_row37_col6" class="data row37 col6" >8.56</td>
                        <td id="T_e59d7_row37_col7" class="data row37 col7" >21.96</td>
                        <td id="T_e59d7_row37_col8" class="data row37 col8" >18.08</td>
                        <td id="T_e59d7_row37_col9" class="data row37 col9" >2.37</td>
                        <td id="T_e59d7_row37_col10" class="data row37 col10" >22.21</td>
                        <td id="T_e59d7_row37_col11" class="data row37 col11" >3.95</td>
                        <td id="T_e59d7_row37_col12" class="data row37 col12" >11.65</td>
                        <td id="T_e59d7_row37_col13" class="data row37 col13" >United States</td>
                        <td id="T_e59d7_row37_col14" class="data row37 col14" >29.44</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row38" class="row_heading level0 row38" >CSX</th>
                        <td id="T_e59d7_row38_col0" class="data row38 col0" >67.05</td>
                        <td id="T_e59d7_row38_col1" class="data row38 col1" >8.62</td>
                        <td id="T_e59d7_row38_col2" class="data row38 col2" >0.00</td>
                        <td id="T_e59d7_row38_col3" class="data row38 col3" >28.19</td>
                        <td id="T_e59d7_row38_col4" class="data row38 col4" >32.25</td>
                        <td id="T_e59d7_row38_col5" class="data row38 col5" >-2.17</td>
                        <td id="T_e59d7_row38_col6" class="data row38 col6" >9.37</td>
                        <td id="T_e59d7_row38_col7" class="data row38 col7" >-18.61</td>
                        <td id="T_e59d7_row38_col8" class="data row38 col8" >20.14</td>
                        <td id="T_e59d7_row38_col9" class="data row38 col9" >31.69</td>
                        <td id="T_e59d7_row38_col10" class="data row38 col10" >62.64</td>
                        <td id="T_e59d7_row38_col11" class="data row38 col11" >69.95</td>
                        <td id="T_e59d7_row38_col12" class="data row38 col12" >26.92</td>
                        <td id="T_e59d7_row38_col13" class="data row38 col13" >United States</td>
                        <td id="T_e59d7_row38_col14" class="data row38 col14" >75.42</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row39" class="row_heading level0 row39" >CTO</th>
                        <td id="T_e59d7_row39_col0" class="data row39 col0" >47.31</td>
                        <td id="T_e59d7_row39_col1" class="data row39 col1" >20.69</td>
                        <td id="T_e59d7_row39_col2" class="data row39 col2" >0.00</td>
                        <td id="T_e59d7_row39_col3" class="data row39 col3" >25.72</td>
                        <td id="T_e59d7_row39_col4" class="data row39 col4" >147.04</td>
                        <td id="T_e59d7_row39_col5" class="data row39 col5" >13.78</td>
                        <td id="T_e59d7_row39_col6" class="data row39 col6" >11.28</td>
                        <td id="T_e59d7_row39_col7" class="data row39 col7" >55.57</td>
                        <td id="T_e59d7_row39_col8" class="data row39 col8" >133.57</td>
                        <td id="T_e59d7_row39_col9" class="data row39 col9" >0.00</td>
                        <td id="T_e59d7_row39_col10" class="data row39 col10" >0.00</td>
                        <td id="T_e59d7_row39_col11" class="data row39 col11" >0.00</td>
                        <td id="T_e59d7_row39_col12" class="data row39 col12" >3.02</td>
                        <td id="T_e59d7_row39_col13" class="data row39 col13" >United States</td>
                        <td id="T_e59d7_row39_col14" class="data row39 col14" >0.32</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row40" class="row_heading level0 row40" >DHIL</th>
                        <td id="T_e59d7_row40_col0" class="data row40 col0" >26.47</td>
                        <td id="T_e59d7_row40_col1" class="data row40 col1" >14.29</td>
                        <td id="T_e59d7_row40_col2" class="data row40 col2" >0.00</td>
                        <td id="T_e59d7_row40_col3" class="data row40 col3" >25.68</td>
                        <td id="T_e59d7_row40_col4" class="data row40 col4" >34.44</td>
                        <td id="T_e59d7_row40_col5" class="data row40 col5" >-4.46</td>
                        <td id="T_e59d7_row40_col6" class="data row40 col6" >4.17</td>
                        <td id="T_e59d7_row40_col7" class="data row40 col7" >-6.29</td>
                        <td id="T_e59d7_row40_col8" class="data row40 col8" >22.85</td>
                        <td id="T_e59d7_row40_col9" class="data row40 col9" >17.77</td>
                        <td id="T_e59d7_row40_col10" class="data row40 col10" >81.17</td>
                        <td id="T_e59d7_row40_col11" class="data row40 col11" >1.01</td>
                        <td id="T_e59d7_row40_col12" class="data row40 col12" >0.51</td>
                        <td id="T_e59d7_row40_col13" class="data row40 col13" >United States</td>
                        <td id="T_e59d7_row40_col14" class="data row40 col14" >0.56</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row41" class="row_heading level0 row41" >DMLP</th>
                        <td id="T_e59d7_row41_col0" class="data row41 col0" >4.26</td>
                        <td id="T_e59d7_row41_col1" class="data row41 col1" >15.49</td>
                        <td id="T_e59d7_row41_col2" class="data row41 col2" >0.00</td>
                        <td id="T_e59d7_row41_col3" class="data row41 col3" >43.51</td>
                        <td id="T_e59d7_row41_col4" class="data row41 col4" >63.80</td>
                        <td id="T_e59d7_row41_col5" class="data row41 col5" >-1.69</td>
                        <td id="T_e59d7_row41_col6" class="data row41 col6" >35.10</td>
                        <td id="T_e59d7_row41_col7" class="data row41 col7" >-6.74</td>
                        <td id="T_e59d7_row41_col8" class="data row41 col8" >49.49</td>
                        <td id="T_e59d7_row41_col9" class="data row41 col9" >15.13</td>
                        <td id="T_e59d7_row41_col10" class="data row41 col10" >26.21</td>
                        <td id="T_e59d7_row41_col11" class="data row41 col11" >0.99</td>
                        <td id="T_e59d7_row41_col12" class="data row41 col12" >0.42</td>
                        <td id="T_e59d7_row41_col13" class="data row41 col13" >United States</td>
                        <td id="T_e59d7_row41_col14" class="data row41 col14" >0.55</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row42" class="row_heading level0 row42" >EA</th>
                        <td id="T_e59d7_row42_col0" class="data row42 col0" >32.86</td>
                        <td id="T_e59d7_row42_col1" class="data row42 col1" >8.33</td>
                        <td id="T_e59d7_row42_col2" class="data row42 col2" >25.26</td>
                        <td id="T_e59d7_row42_col3" class="data row42 col3" >26.59</td>
                        <td id="T_e59d7_row42_col4" class="data row42 col4" >28.92</td>
                        <td id="T_e59d7_row42_col5" class="data row42 col5" >4.76</td>
                        <td id="T_e59d7_row42_col6" class="data row42 col6" >7.98</td>
                        <td id="T_e59d7_row42_col7" class="data row42 col7" >67.93</td>
                        <td id="T_e59d7_row42_col8" class="data row42 col8" >112.96</td>
                        <td id="T_e59d7_row42_col9" class="data row42 col9" >5.02</td>
                        <td id="T_e59d7_row42_col10" class="data row42 col10" >13.41</td>
                        <td id="T_e59d7_row42_col11" class="data row42 col11" >22.29</td>
                        <td id="T_e59d7_row42_col12" class="data row42 col12" >83.96</td>
                        <td id="T_e59d7_row42_col13" class="data row42 col13" >United States</td>
                        <td id="T_e59d7_row42_col14" class="data row42 col14" >40.47</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row43" class="row_heading level0 row43" >EDTK</th>
                        <td id="T_e59d7_row43_col0" class="data row43 col0" >38.97</td>
                        <td id="T_e59d7_row43_col1" class="data row43 col1" >0.28</td>
                        <td id="T_e59d7_row43_col2" class="data row43 col2" >0.00</td>
                        <td id="T_e59d7_row43_col3" class="data row43 col3" >45.21</td>
                        <td id="T_e59d7_row43_col4" class="data row43 col4" >36.78</td>
                        <td id="T_e59d7_row43_col5" class="data row43 col5" >40.69</td>
                        <td id="T_e59d7_row43_col6" class="data row43 col6" >35.01</td>
                        <td id="T_e59d7_row43_col7" class="data row43 col7" >29.67</td>
                        <td id="T_e59d7_row43_col8" class="data row43 col8" >20.76</td>
                        <td id="T_e59d7_row43_col9" class="data row43 col9" >83.37</td>
                        <td id="T_e59d7_row43_col10" class="data row43 col10" >40.18</td>
                        <td id="T_e59d7_row43_col11" class="data row43 col11" >0.46</td>
                        <td id="T_e59d7_row43_col12" class="data row43 col12" >0.22</td>
                        <td id="T_e59d7_row43_col13" class="data row43 col13" >China</td>
                        <td id="T_e59d7_row43_col14" class="data row43 col14" >0.03</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row44" class="row_heading level0 row44" >EOS</th>
                        <td id="T_e59d7_row44_col0" class="data row44 col0" >1.05</td>
                        <td id="T_e59d7_row44_col1" class="data row44 col1" >9.73</td>
                        <td id="T_e59d7_row44_col2" class="data row44 col2" >0.00</td>
                        <td id="T_e59d7_row44_col3" class="data row44 col3" >16.37</td>
                        <td id="T_e59d7_row44_col4" class="data row44 col4" >2110.25</td>
                        <td id="T_e59d7_row44_col5" class="data row44 col5" >-0.53</td>
                        <td id="T_e59d7_row44_col6" class="data row44 col6" >10.20</td>
                        <td id="T_e59d7_row44_col7" class="data row44 col7" >1385.73</td>
                        <td id="T_e59d7_row44_col8" class="data row44 col8" >2465.34</td>
                        <td id="T_e59d7_row44_col9" class="data row44 col9" >0.00</td>
                        <td id="T_e59d7_row44_col10" class="data row44 col10" >0.00</td>
                        <td id="T_e59d7_row44_col11" class="data row44 col11" >0.00</td>
                        <td id="T_e59d7_row44_col12" class="data row44 col12" >5194.10</td>
                        <td id="T_e59d7_row44_col13" class="data row44 col13" >0</td>
                        <td id="T_e59d7_row44_col14" class="data row44 col14" >1.11</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row45" class="row_heading level0 row45" >EPM</th>
                        <td id="T_e59d7_row45_col0" class="data row45 col0" >19.55</td>
                        <td id="T_e59d7_row45_col1" class="data row45 col1" >17.44</td>
                        <td id="T_e59d7_row45_col2" class="data row45 col2" >0.00</td>
                        <td id="T_e59d7_row45_col3" class="data row45 col3" >16.08</td>
                        <td id="T_e59d7_row45_col4" class="data row45 col4" >31.77</td>
                        <td id="T_e59d7_row45_col5" class="data row45 col5" >-2.42</td>
                        <td id="T_e59d7_row45_col6" class="data row45 col6" >25.94</td>
                        <td id="T_e59d7_row45_col7" class="data row45 col7" >20.29</td>
                        <td id="T_e59d7_row45_col8" class="data row45 col8" >108.86</td>
                        <td id="T_e59d7_row45_col9" class="data row45 col9" >25.91</td>
                        <td id="T_e59d7_row45_col10" class="data row45 col10" >131.33</td>
                        <td id="T_e59d7_row45_col11" class="data row45 col11" >0.25</td>
                        <td id="T_e59d7_row45_col12" class="data row45 col12" >0.26</td>
                        <td id="T_e59d7_row45_col13" class="data row45 col13" >United States</td>
                        <td id="T_e59d7_row45_col14" class="data row45 col14" >0.14</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row46" class="row_heading level0 row46" >ERII</th>
                        <td id="T_e59d7_row46_col0" class="data row46 col0" >16.00</td>
                        <td id="T_e59d7_row46_col1" class="data row46 col1" >11.01</td>
                        <td id="T_e59d7_row46_col2" class="data row46 col2" >7.45</td>
                        <td id="T_e59d7_row46_col3" class="data row46 col3" >15.71</td>
                        <td id="T_e59d7_row46_col4" class="data row46 col4" >22.73</td>
                        <td id="T_e59d7_row46_col5" class="data row46 col5" >20.44</td>
                        <td id="T_e59d7_row46_col6" class="data row46 col6" >14.89</td>
                        <td id="T_e59d7_row46_col7" class="data row46 col7" >37.19</td>
                        <td id="T_e59d7_row46_col8" class="data row46 col8" >97.30</td>
                        <td id="T_e59d7_row46_col9" class="data row46 col9" >-306.59</td>
                        <td id="T_e59d7_row46_col10" class="data row46 col10" >235.03</td>
                        <td id="T_e59d7_row46_col11" class="data row46 col11" >-0.14</td>
                        <td id="T_e59d7_row46_col12" class="data row46 col12" >0.60</td>
                        <td id="T_e59d7_row46_col13" class="data row46 col13" >United States</td>
                        <td id="T_e59d7_row46_col14" class="data row46 col14" >1.13</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row47" class="row_heading level0 row47" >ESNT</th>
                        <td id="T_e59d7_row47_col0" class="data row47 col0" >25.76</td>
                        <td id="T_e59d7_row47_col1" class="data row47 col1" >5.25</td>
                        <td id="T_e59d7_row47_col2" class="data row47 col2" >0.00</td>
                        <td id="T_e59d7_row47_col3" class="data row47 col3" >17.16</td>
                        <td id="T_e59d7_row47_col4" class="data row47 col4" >59.53</td>
                        <td id="T_e59d7_row47_col5" class="data row47 col5" >18.49</td>
                        <td id="T_e59d7_row47_col6" class="data row47 col6" >7.56</td>
                        <td id="T_e59d7_row47_col7" class="data row47 col7" >5.43</td>
                        <td id="T_e59d7_row47_col8" class="data row47 col8" >27.02</td>
                        <td id="T_e59d7_row47_col9" class="data row47 col9" >29.32</td>
                        <td id="T_e59d7_row47_col10" class="data row47 col10" >38.04</td>
                        <td id="T_e59d7_row47_col11" class="data row47 col11" >15.03</td>
                        <td id="T_e59d7_row47_col12" class="data row47 col12" >6.68</td>
                        <td id="T_e59d7_row47_col13" class="data row47 col13" >0</td>
                        <td id="T_e59d7_row47_col14" class="data row47 col14" >5.36</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row48" class="row_heading level0 row48" >EXEL</th>
                        <td id="T_e59d7_row48_col0" class="data row48 col0" >12.08</td>
                        <td id="T_e59d7_row48_col1" class="data row48 col1" >16.75</td>
                        <td id="T_e59d7_row48_col2" class="data row48 col2" >3.39</td>
                        <td id="T_e59d7_row48_col3" class="data row48 col3" >33.18</td>
                        <td id="T_e59d7_row48_col4" class="data row48 col4" >39.85</td>
                        <td id="T_e59d7_row48_col5" class="data row48 col5" >34.70</td>
                        <td id="T_e59d7_row48_col6" class="data row48 col6" >47.11</td>
                        <td id="T_e59d7_row48_col7" class="data row48 col7" >76.26</td>
                        <td id="T_e59d7_row48_col8" class="data row48 col8" >234.92</td>
                        <td id="T_e59d7_row48_col9" class="data row48 col9" >44.63</td>
                        <td id="T_e59d7_row48_col10" class="data row48 col10" >115.32</td>
                        <td id="T_e59d7_row48_col11" class="data row48 col11" >10.98</td>
                        <td id="T_e59d7_row48_col12" class="data row48 col12" >20.33</td>
                        <td id="T_e59d7_row48_col13" class="data row48 col13" >United States</td>
                        <td id="T_e59d7_row48_col14" class="data row48 col14" >7.00</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row49" class="row_heading level0 row49" >FB</th>
                        <td id="T_e59d7_row49_col0" class="data row49 col0" >19.47</td>
                        <td id="T_e59d7_row49_col1" class="data row49 col1" >13.19</td>
                        <td id="T_e59d7_row49_col2" class="data row49 col2" >14.85</td>
                        <td id="T_e59d7_row49_col3" class="data row49 col3" >22.18</td>
                        <td id="T_e59d7_row49_col4" class="data row49 col4" >34.71</td>
                        <td id="T_e59d7_row49_col5" class="data row49 col5" >28.52</td>
                        <td id="T_e59d7_row49_col6" class="data row49 col6" >8.05</td>
                        <td id="T_e59d7_row49_col7" class="data row49 col7" >26.68</td>
                        <td id="T_e59d7_row49_col8" class="data row49 col8" >38.49</td>
                        <td id="T_e59d7_row49_col9" class="data row49 col9" >12.46</td>
                        <td id="T_e59d7_row49_col10" class="data row49 col10" >25.14</td>
                        <td id="T_e59d7_row49_col11" class="data row49 col11" >342.34</td>
                        <td id="T_e59d7_row49_col12" class="data row49 col12" >528.39</td>
                        <td id="T_e59d7_row49_col13" class="data row49 col13" >United States</td>
                        <td id="T_e59d7_row49_col14" class="data row49 col14" >933.29</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row50" class="row_heading level0 row50" >FDS</th>
                        <td id="T_e59d7_row50_col0" class="data row50 col0" >56.98</td>
                        <td id="T_e59d7_row50_col1" class="data row50 col1" >10.37</td>
                        <td id="T_e59d7_row50_col2" class="data row50 col2" >79.17</td>
                        <td id="T_e59d7_row50_col3" class="data row50 col3" >47.75</td>
                        <td id="T_e59d7_row50_col4" class="data row50 col4" >22.62</td>
                        <td id="T_e59d7_row50_col5" class="data row50 col5" >6.99</td>
                        <td id="T_e59d7_row50_col6" class="data row50 col6" >3.29</td>
                        <td id="T_e59d7_row50_col7" class="data row50 col7" >13.74</td>
                        <td id="T_e59d7_row50_col8" class="data row50 col8" >15.93</td>
                        <td id="T_e59d7_row50_col9" class="data row50 col9" >15.00</td>
                        <td id="T_e59d7_row50_col10" class="data row50 col10" >9.93</td>
                        <td id="T_e59d7_row50_col11" class="data row50 col11" >6.72</td>
                        <td id="T_e59d7_row50_col12" class="data row50 col12" >5.69</td>
                        <td id="T_e59d7_row50_col13" class="data row50 col13" >United States</td>
                        <td id="T_e59d7_row50_col14" class="data row50 col14" >12.40</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row51" class="row_heading level0 row51" >FINV</th>
                        <td id="T_e59d7_row51_col0" class="data row51 col0" >43.35</td>
                        <td id="T_e59d7_row51_col1" class="data row51 col1" >41.31</td>
                        <td id="T_e59d7_row51_col2" class="data row51 col2" >0.60</td>
                        <td id="T_e59d7_row51_col3" class="data row51 col3" >31.26</td>
                        <td id="T_e59d7_row51_col4" class="data row51 col4" >36.55</td>
                        <td id="T_e59d7_row51_col5" class="data row51 col5" >25.65</td>
                        <td id="T_e59d7_row51_col6" class="data row51 col6" >7.72</td>
                        <td id="T_e59d7_row51_col7" class="data row51 col7" >35.74</td>
                        <td id="T_e59d7_row51_col8" class="data row51 col8" >80.15</td>
                        <td id="T_e59d7_row51_col9" class="data row51 col9" >-363.86</td>
                        <td id="T_e59d7_row51_col10" class="data row51 col10" >492.54</td>
                        <td id="T_e59d7_row51_col11" class="data row51 col11" >-342.43</td>
                        <td id="T_e59d7_row51_col12" class="data row51 col12" >59.29</td>
                        <td id="T_e59d7_row51_col13" class="data row51 col13" >United States</td>
                        <td id="T_e59d7_row51_col14" class="data row51 col14" >2.39</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row52" class="row_heading level0 row52" >FTV</th>
                        <td id="T_e59d7_row52_col0" class="data row52 col0" >44.10</td>
                        <td id="T_e59d7_row52_col1" class="data row52 col1" >17.48</td>
                        <td id="T_e59d7_row52_col2" class="data row52 col2" >82.10</td>
                        <td id="T_e59d7_row52_col3" class="data row52 col3" >24.93</td>
                        <td id="T_e59d7_row52_col4" class="data row52 col4" >36.45</td>
                        <td id="T_e59d7_row52_col5" class="data row52 col5" >-4.11</td>
                        <td id="T_e59d7_row52_col6" class="data row52 col6" >27.47</td>
                        <td id="T_e59d7_row52_col7" class="data row52 col7" >74.22</td>
                        <td id="T_e59d7_row52_col8" class="data row52 col8" >132.43</td>
                        <td id="T_e59d7_row52_col9" class="data row52 col9" >9.09</td>
                        <td id="T_e59d7_row52_col10" class="data row52 col10" >13.47</td>
                        <td id="T_e59d7_row52_col11" class="data row52 col11" >19.82</td>
                        <td id="T_e59d7_row52_col12" class="data row52 col12" >97.12</td>
                        <td id="T_e59d7_row52_col13" class="data row52 col13" >0</td>
                        <td id="T_e59d7_row52_col14" class="data row52 col14" >24.86</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row53" class="row_heading level0 row53" >GMAB</th>
                        <td id="T_e59d7_row53_col0" class="data row53 col0" >9.56</td>
                        <td id="T_e59d7_row53_col1" class="data row53 col1" >26.82</td>
                        <td id="T_e59d7_row53_col2" class="data row53 col2" >0.00</td>
                        <td id="T_e59d7_row53_col3" class="data row53 col3" >19.07</td>
                        <td id="T_e59d7_row53_col4" class="data row53 col4" >45.68</td>
                        <td id="T_e59d7_row53_col5" class="data row53 col5" >64.57</td>
                        <td id="T_e59d7_row53_col6" class="data row53 col6" >32.24</td>
                        <td id="T_e59d7_row53_col7" class="data row53 col7" >66.73</td>
                        <td id="T_e59d7_row53_col8" class="data row53 col8" >46.36</td>
                        <td id="T_e59d7_row53_col9" class="data row53 col9" >128.78</td>
                        <td id="T_e59d7_row53_col10" class="data row53 col10" >229.94</td>
                        <td id="T_e59d7_row53_col11" class="data row53 col11" >334.31</td>
                        <td id="T_e59d7_row53_col12" class="data row53 col12" >128.74</td>
                        <td id="T_e59d7_row53_col13" class="data row53 col13" >Denmark</td>
                        <td id="T_e59d7_row53_col14" class="data row53 col14" >26.53</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row54" class="row_heading level0 row54" >GRMN</th>
                        <td id="T_e59d7_row54_col0" class="data row54 col0" >21.55</td>
                        <td id="T_e59d7_row54_col1" class="data row54 col1" >20.53</td>
                        <td id="T_e59d7_row54_col2" class="data row54 col2" >10.59</td>
                        <td id="T_e59d7_row54_col3" class="data row54 col3" >18.23</td>
                        <td id="T_e59d7_row54_col4" class="data row54 col4" >23.12</td>
                        <td id="T_e59d7_row54_col5" class="data row54 col5" >10.30</td>
                        <td id="T_e59d7_row54_col6" class="data row54 col6" >2.69</td>
                        <td id="T_e59d7_row54_col7" class="data row54 col7" >13.10</td>
                        <td id="T_e59d7_row54_col8" class="data row54 col8" >21.13</td>
                        <td id="T_e59d7_row54_col9" class="data row54 col9" >28.73</td>
                        <td id="T_e59d7_row54_col10" class="data row54 col10" >46.45</td>
                        <td id="T_e59d7_row54_col11" class="data row54 col11" >18.17</td>
                        <td id="T_e59d7_row54_col12" class="data row54 col12" >14.99</td>
                        <td id="T_e59d7_row54_col13" class="data row54 col13" >Switzerland</td>
                        <td id="T_e59d7_row54_col14" class="data row54 col14" >27.26</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row55" class="row_heading level0 row55" >HDB</th>
                        <td id="T_e59d7_row55_col0" class="data row55 col0" >88.31</td>
                        <td id="T_e59d7_row55_col1" class="data row55 col1" >0.00</td>
                        <td id="T_e59d7_row55_col2" class="data row55 col2" >0.08</td>
                        <td id="T_e59d7_row55_col3" class="data row55 col3" >15.51</td>
                        <td id="T_e59d7_row55_col4" class="data row55 col4" >37.63</td>
                        <td id="T_e59d7_row55_col5" class="data row55 col5" >14.15</td>
                        <td id="T_e59d7_row55_col6" class="data row55 col6" >4.62</td>
                        <td id="T_e59d7_row55_col7" class="data row55 col7" >19.83</td>
                        <td id="T_e59d7_row55_col8" class="data row55 col8" >2.71</td>
                        <td id="T_e59d7_row55_col9" class="data row55 col9" >12.22</td>
                        <td id="T_e59d7_row55_col10" class="data row55 col10" >47.52</td>
                        <td id="T_e59d7_row55_col11" class="data row55 col11" >-31382.02</td>
                        <td id="T_e59d7_row55_col12" class="data row55 col12" >5265.56</td>
                        <td id="T_e59d7_row55_col13" class="data row55 col13" >India</td>
                        <td id="T_e59d7_row55_col14" class="data row55 col14" >140.56</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row56" class="row_heading level0 row56" >HIFS</th>
                        <td id="T_e59d7_row56_col0" class="data row56 col0" >89.75</td>
                        <td id="T_e59d7_row56_col1" class="data row56 col1" >0.00</td>
                        <td id="T_e59d7_row56_col2" class="data row56 col2" >0.00</td>
                        <td id="T_e59d7_row56_col3" class="data row56 col3" >15.30</td>
                        <td id="T_e59d7_row56_col4" class="data row56 col4" >49.12</td>
                        <td id="T_e59d7_row56_col5" class="data row56 col5" >13.63</td>
                        <td id="T_e59d7_row56_col6" class="data row56 col6" >13.40</td>
                        <td id="T_e59d7_row56_col7" class="data row56 col7" >25.50</td>
                        <td id="T_e59d7_row56_col8" class="data row56 col8" >6.58</td>
                        <td id="T_e59d7_row56_col9" class="data row56 col9" >18.97</td>
                        <td id="T_e59d7_row56_col10" class="data row56 col10" >22.30</td>
                        <td id="T_e59d7_row56_col11" class="data row56 col11" >0.72</td>
                        <td id="T_e59d7_row56_col12" class="data row56 col12" >0.88</td>
                        <td id="T_e59d7_row56_col13" class="data row56 col13" >United States</td>
                        <td id="T_e59d7_row56_col14" class="data row56 col14" >0.63</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row57" class="row_heading level0 row57" >HLG</th>
                        <td id="T_e59d7_row57_col0" class="data row57 col0" >27.00</td>
                        <td id="T_e59d7_row57_col1" class="data row57 col1" >5.67</td>
                        <td id="T_e59d7_row57_col2" class="data row57 col2" >3.04</td>
                        <td id="T_e59d7_row57_col3" class="data row57 col3" >17.04</td>
                        <td id="T_e59d7_row57_col4" class="data row57 col4" >20.82</td>
                        <td id="T_e59d7_row57_col5" class="data row57 col5" >21.38</td>
                        <td id="T_e59d7_row57_col6" class="data row57 col6" >19.96</td>
                        <td id="T_e59d7_row57_col7" class="data row57 col7" >30.30</td>
                        <td id="T_e59d7_row57_col8" class="data row57 col8" >3.42</td>
                        <td id="T_e59d7_row57_col9" class="data row57 col9" >51.62</td>
                        <td id="T_e59d7_row57_col10" class="data row57 col10" >116.64</td>
                        <td id="T_e59d7_row57_col11" class="data row57 col11" >16.55</td>
                        <td id="T_e59d7_row57_col12" class="data row57 col12" >7.05</td>
                        <td id="T_e59d7_row57_col13" class="data row57 col13" >China</td>
                        <td id="T_e59d7_row57_col14" class="data row57 col14" >1.05</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row58" class="row_heading level0 row58" >HMLP</th>
                        <td id="T_e59d7_row58_col0" class="data row58 col0" >49.75</td>
                        <td id="T_e59d7_row58_col1" class="data row58 col1" >9.82</td>
                        <td id="T_e59d7_row58_col2" class="data row58 col2" >0.08</td>
                        <td id="T_e59d7_row58_col3" class="data row58 col3" >17.39</td>
                        <td id="T_e59d7_row58_col4" class="data row58 col4" >41.98</td>
                        <td id="T_e59d7_row58_col5" class="data row58 col5" >-0.10</td>
                        <td id="T_e59d7_row58_col6" class="data row58 col6" >1.35</td>
                        <td id="T_e59d7_row58_col7" class="data row58 col7" >15.60</td>
                        <td id="T_e59d7_row58_col8" class="data row58 col8" >45.73</td>
                        <td id="T_e59d7_row58_col9" class="data row58 col9" >2.74</td>
                        <td id="T_e59d7_row58_col10" class="data row58 col10" >10.27</td>
                        <td id="T_e59d7_row58_col11" class="data row58 col11" >1.17</td>
                        <td id="T_e59d7_row58_col12" class="data row58 col12" >1.15</td>
                        <td id="T_e59d7_row58_col13" class="data row58 col13" >Bermuda</td>
                        <td id="T_e59d7_row58_col14" class="data row58 col14" >0.56</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row59" class="row_heading level0 row59" >ILMN</th>
                        <td id="T_e59d7_row59_col0" class="data row59 col0" >38.11</td>
                        <td id="T_e59d7_row59_col1" class="data row59 col1" >15.04</td>
                        <td id="T_e59d7_row59_col2" class="data row59 col2" >19.11</td>
                        <td id="T_e59d7_row59_col3" class="data row59 col3" >21.02</td>
                        <td id="T_e59d7_row59_col4" class="data row59 col4" >24.92</td>
                        <td id="T_e59d7_row59_col5" class="data row59 col5" >6.28</td>
                        <td id="T_e59d7_row59_col6" class="data row59 col6" >14.85</td>
                        <td id="T_e59d7_row59_col7" class="data row59 col7" >0.18</td>
                        <td id="T_e59d7_row59_col8" class="data row59 col8" >30.30</td>
                        <td id="T_e59d7_row59_col9" class="data row59 col9" >18.36</td>
                        <td id="T_e59d7_row59_col10" class="data row59 col10" >27.35</td>
                        <td id="T_e59d7_row59_col11" class="data row59 col11" >16.00</td>
                        <td id="T_e59d7_row59_col12" class="data row59 col12" >10.25</td>
                        <td id="T_e59d7_row59_col13" class="data row59 col13" >United States</td>
                        <td id="T_e59d7_row59_col14" class="data row59 col14" >60.29</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row60" class="row_heading level0 row60" >INMD</th>
                        <td id="T_e59d7_row60_col0" class="data row60 col0" >13.62</td>
                        <td id="T_e59d7_row60_col1" class="data row60 col1" >6.83</td>
                        <td id="T_e59d7_row60_col2" class="data row60 col2" >0.00</td>
                        <td id="T_e59d7_row60_col3" class="data row60 col3" >40.33</td>
                        <td id="T_e59d7_row60_col4" class="data row60 col4" >28.59</td>
                        <td id="T_e59d7_row60_col5" class="data row60 col5" >58.43</td>
                        <td id="T_e59d7_row60_col6" class="data row60 col6" >27.85</td>
                        <td id="T_e59d7_row60_col7" class="data row60 col7" >116.57</td>
                        <td id="T_e59d7_row60_col8" class="data row60 col8" >81.88</td>
                        <td id="T_e59d7_row60_col9" class="data row60 col9" >83.23</td>
                        <td id="T_e59d7_row60_col10" class="data row60 col10" >63.84</td>
                        <td id="T_e59d7_row60_col11" class="data row60 col11" >3.41</td>
                        <td id="T_e59d7_row60_col12" class="data row60 col12" >4.85</td>
                        <td id="T_e59d7_row60_col13" class="data row60 col13" >Israel</td>
                        <td id="T_e59d7_row60_col14" class="data row60 col14" >3.20</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row61" class="row_heading level0 row61" >INS</th>
                        <td id="T_e59d7_row61_col0" class="data row61 col0" >22.58</td>
                        <td id="T_e59d7_row61_col1" class="data row61 col1" >9.12</td>
                        <td id="T_e59d7_row61_col2" class="data row61 col2" >0.00</td>
                        <td id="T_e59d7_row61_col3" class="data row61 col3" >18.48</td>
                        <td id="T_e59d7_row61_col4" class="data row61 col4" >22.47</td>
                        <td id="T_e59d7_row61_col5" class="data row61 col5" >64.74</td>
                        <td id="T_e59d7_row61_col6" class="data row61 col6" >57.43</td>
                        <td id="T_e59d7_row61_col7" class="data row61 col7" >539.86</td>
                        <td id="T_e59d7_row61_col8" class="data row61 col8" >893.14</td>
                        <td id="T_e59d7_row61_col9" class="data row61 col9" >-53.43</td>
                        <td id="T_e59d7_row61_col10" class="data row61 col10" >189.56</td>
                        <td id="T_e59d7_row61_col11" class="data row61 col11" >0.01</td>
                        <td id="T_e59d7_row61_col12" class="data row61 col12" >18.46</td>
                        <td id="T_e59d7_row61_col13" class="data row61 col13" >United States</td>
                        <td id="T_e59d7_row61_col14" class="data row61 col14" >0.28</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row62" class="row_heading level0 row62" >INTC</th>
                        <td id="T_e59d7_row62_col0" class="data row62 col0" >47.07</td>
                        <td id="T_e59d7_row62_col1" class="data row62 col1" >9.44</td>
                        <td id="T_e59d7_row62_col2" class="data row62 col2" >33.28</td>
                        <td id="T_e59d7_row62_col3" class="data row62 col3" >23.77</td>
                        <td id="T_e59d7_row62_col4" class="data row62 col4" >25.28</td>
                        <td id="T_e59d7_row62_col5" class="data row62 col5" >7.55</td>
                        <td id="T_e59d7_row62_col6" class="data row62 col6" >5.68</td>
                        <td id="T_e59d7_row62_col7" class="data row62 col7" >39.52</td>
                        <td id="T_e59d7_row62_col8" class="data row62 col8" >69.08</td>
                        <td id="T_e59d7_row62_col9" class="data row62 col9" >26.79</td>
                        <td id="T_e59d7_row62_col10" class="data row62 col10" >9.95</td>
                        <td id="T_e59d7_row62_col11" class="data row62 col11" >386.03</td>
                        <td id="T_e59d7_row62_col12" class="data row62 col12" >589.39</td>
                        <td id="T_e59d7_row62_col13" class="data row62 col13" >United States</td>
                        <td id="T_e59d7_row62_col14" class="data row62 col14" >232.10</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row63" class="row_heading level0 row63" >INTU</th>
                        <td id="T_e59d7_row63_col0" class="data row63 col0" >53.29</td>
                        <td id="T_e59d7_row63_col1" class="data row63 col1" >2.62</td>
                        <td id="T_e59d7_row63_col2" class="data row63 col2" >32.39</td>
                        <td id="T_e59d7_row63_col3" class="data row63 col3" >49.31</td>
                        <td id="T_e59d7_row63_col4" class="data row63 col4" >21.94</td>
                        <td id="T_e59d7_row63_col5" class="data row63 col5" >13.91</td>
                        <td id="T_e59d7_row63_col6" class="data row63 col6" >1.79</td>
                        <td id="T_e59d7_row63_col7" class="data row63 col7" >23.12</td>
                        <td id="T_e59d7_row63_col8" class="data row63 col8" >10.22</td>
                        <td id="T_e59d7_row63_col9" class="data row63 col9" >17.23</td>
                        <td id="T_e59d7_row63_col10" class="data row63 col10" >18.55</td>
                        <td id="T_e59d7_row63_col11" class="data row63 col11" >40.49</td>
                        <td id="T_e59d7_row63_col12" class="data row63 col12" >32.41</td>
                        <td id="T_e59d7_row63_col13" class="data row63 col13" >United States</td>
                        <td id="T_e59d7_row63_col14" class="data row63 col14" >121.72</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row64" class="row_heading level0 row64" >INVA</th>
                        <td id="T_e59d7_row64_col0" class="data row64 col0" >39.19</td>
                        <td id="T_e59d7_row64_col1" class="data row64 col1" >27.89</td>
                        <td id="T_e59d7_row64_col2" class="data row64 col2" >0.00</td>
                        <td id="T_e59d7_row64_col3" class="data row64 col3" >73.43</td>
                        <td id="T_e59d7_row64_col4" class="data row64 col4" >85.00</td>
                        <td id="T_e59d7_row64_col5" class="data row64 col5" >16.40</td>
                        <td id="T_e59d7_row64_col6" class="data row64 col6" >14.87</td>
                        <td id="T_e59d7_row64_col7" class="data row64 col7" >59.00</td>
                        <td id="T_e59d7_row64_col8" class="data row64 col8" >128.13</td>
                        <td id="T_e59d7_row64_col9" class="data row64 col9" >31.50</td>
                        <td id="T_e59d7_row64_col10" class="data row64 col10" >22.92</td>
                        <td id="T_e59d7_row64_col11" class="data row64 col11" >6.42</td>
                        <td id="T_e59d7_row64_col12" class="data row64 col12" >10.76</td>
                        <td id="T_e59d7_row64_col13" class="data row64 col13" >United States</td>
                        <td id="T_e59d7_row64_col14" class="data row64 col14" >0.92</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row65" class="row_heading level0 row65" >ISNS</th>
                        <td id="T_e59d7_row65_col0" class="data row65 col0" >9.59</td>
                        <td id="T_e59d7_row65_col1" class="data row65 col1" >17.16</td>
                        <td id="T_e59d7_row65_col2" class="data row65 col2" >0.00</td>
                        <td id="T_e59d7_row65_col3" class="data row65 col3" >21.51</td>
                        <td id="T_e59d7_row65_col4" class="data row65 col4" >20.66</td>
                        <td id="T_e59d7_row65_col5" class="data row65 col5" >-3.05</td>
                        <td id="T_e59d7_row65_col6" class="data row65 col6" >6.54</td>
                        <td id="T_e59d7_row65_col7" class="data row65 col7" >60.16</td>
                        <td id="T_e59d7_row65_col8" class="data row65 col8" >190.31</td>
                        <td id="T_e59d7_row65_col9" class="data row65 col9" >4.39</td>
                        <td id="T_e59d7_row65_col10" class="data row65 col10" >43.01</td>
                        <td id="T_e59d7_row65_col11" class="data row65 col11" >0.03</td>
                        <td id="T_e59d7_row65_col12" class="data row65 col12" >0.14</td>
                        <td id="T_e59d7_row65_col13" class="data row65 col13" >United States</td>
                        <td id="T_e59d7_row65_col14" class="data row65 col14" >0.04</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row66" class="row_heading level0 row66" >ITUB</th>
                        <td id="T_e59d7_row66_col0" class="data row66 col0" >92.35</td>
                        <td id="T_e59d7_row66_col1" class="data row66 col1" >12.82</td>
                        <td id="T_e59d7_row66_col2" class="data row66 col2" >8.48</td>
                        <td id="T_e59d7_row66_col3" class="data row66 col3" >17.22</td>
                        <td id="T_e59d7_row66_col4" class="data row66 col4" >26.27</td>
                        <td id="T_e59d7_row66_col5" class="data row66 col5" >-5.35</td>
                        <td id="T_e59d7_row66_col6" class="data row66 col6" >16.73</td>
                        <td id="T_e59d7_row66_col7" class="data row66 col7" >-4.69</td>
                        <td id="T_e59d7_row66_col8" class="data row66 col8" >22.20</td>
                        <td id="T_e59d7_row66_col9" class="data row66 col9" >779.44</td>
                        <td id="T_e59d7_row66_col10" class="data row66 col10" >1443.17</td>
                        <td id="T_e59d7_row66_col11" class="data row66 col11" >-624126.45</td>
                        <td id="T_e59d7_row66_col12" class="data row66 col12" >261.83</td>
                        <td id="T_e59d7_row66_col13" class="data row66 col13" >Brazil</td>
                        <td id="T_e59d7_row66_col14" class="data row66 col14" >60.05</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row67" class="row_heading level0 row67" >KKR</th>
                        <td id="T_e59d7_row67_col0" class="data row67 col0" >48.88</td>
                        <td id="T_e59d7_row67_col1" class="data row67 col1" >22.75</td>
                        <td id="T_e59d7_row67_col2" class="data row67 col2" >0.69</td>
                        <td id="T_e59d7_row67_col3" class="data row67 col3" >16.25</td>
                        <td id="T_e59d7_row67_col4" class="data row67 col4" >24.05</td>
                        <td id="T_e59d7_row67_col5" class="data row67 col5" >26.64</td>
                        <td id="T_e59d7_row67_col6" class="data row67 col6" >54.69</td>
                        <td id="T_e59d7_row67_col7" class="data row67 col7" >29.41</td>
                        <td id="T_e59d7_row67_col8" class="data row67 col8" >41.83</td>
                        <td id="T_e59d7_row67_col9" class="data row67 col9" >30.83</td>
                        <td id="T_e59d7_row67_col10" class="data row67 col10" >71.97</td>
                        <td id="T_e59d7_row67_col11" class="data row67 col11" >-157.74</td>
                        <td id="T_e59d7_row67_col12" class="data row67 col12" >40.34</td>
                        <td id="T_e59d7_row67_col13" class="data row67 col13" >United States</td>
                        <td id="T_e59d7_row67_col14" class="data row67 col14" >32.00</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row68" class="row_heading level0 row68" >KL</th>
                        <td id="T_e59d7_row68_col0" class="data row68 col0" >28.18</td>
                        <td id="T_e59d7_row68_col1" class="data row68 col1" >0.94</td>
                        <td id="T_e59d7_row68_col2" class="data row68 col2" >0.00</td>
                        <td id="T_e59d7_row68_col3" class="data row68 col3" >19.86</td>
                        <td id="T_e59d7_row68_col4" class="data row68 col4" >30.06</td>
                        <td id="T_e59d7_row68_col5" class="data row68 col5" >50.49</td>
                        <td id="T_e59d7_row68_col6" class="data row68 col6" >27.87</td>
                        <td id="T_e59d7_row68_col7" class="data row68 col7" >83.99</td>
                        <td id="T_e59d7_row68_col8" class="data row68 col8" >37.56</td>
                        <td id="T_e59d7_row68_col9" class="data row68 col9" >63.22</td>
                        <td id="T_e59d7_row68_col10" class="data row68 col10" >5.53</td>
                        <td id="T_e59d7_row68_col11" class="data row68 col11" >20.88</td>
                        <td id="T_e59d7_row68_col12" class="data row68 col12" >31.62</td>
                        <td id="T_e59d7_row68_col13" class="data row68 col13" >0</td>
                        <td id="T_e59d7_row68_col14" class="data row68 col14" >11.67</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row69" class="row_heading level0 row69" >KLAC</th>
                        <td id="T_e59d7_row69_col0" class="data row69 col0" >71.11</td>
                        <td id="T_e59d7_row69_col1" class="data row69 col1" >20.79</td>
                        <td id="T_e59d7_row69_col2" class="data row69 col2" >76.74</td>
                        <td id="T_e59d7_row69_col3" class="data row69 col3" >52.30</td>
                        <td id="T_e59d7_row69_col4" class="data row69 col4" >23.29</td>
                        <td id="T_e59d7_row69_col5" class="data row69 col5" >18.76</td>
                        <td id="T_e59d7_row69_col6" class="data row69 col6" >7.35</td>
                        <td id="T_e59d7_row69_col7" class="data row69 col7" >12.22</td>
                        <td id="T_e59d7_row69_col8" class="data row69 col8" >30.89</td>
                        <td id="T_e59d7_row69_col9" class="data row69 col9" >19.56</td>
                        <td id="T_e59d7_row69_col10" class="data row69 col10" >36.23</td>
                        <td id="T_e59d7_row69_col11" class="data row69 col11" >25.40</td>
                        <td id="T_e59d7_row69_col12" class="data row69 col12" >18.05</td>
                        <td id="T_e59d7_row69_col13" class="data row69 col13" >United States</td>
                        <td id="T_e59d7_row69_col14" class="data row69 col14" >48.37</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row70" class="row_heading level0 row70" >KSU</th>
                        <td id="T_e59d7_row70_col0" class="data row70 col0" >56.01</td>
                        <td id="T_e59d7_row70_col1" class="data row70 col1" >9.39</td>
                        <td id="T_e59d7_row70_col2" class="data row70 col2" >0.33</td>
                        <td id="T_e59d7_row70_col3" class="data row70 col3" >15.41</td>
                        <td id="T_e59d7_row70_col4" class="data row70 col4" >25.65</td>
                        <td id="T_e59d7_row70_col5" class="data row70 col5" >0.84</td>
                        <td id="T_e59d7_row70_col6" class="data row70 col6" >7.79</td>
                        <td id="T_e59d7_row70_col7" class="data row70 col7" >-11.47</td>
                        <td id="T_e59d7_row70_col8" class="data row70 col8" >24.74</td>
                        <td id="T_e59d7_row70_col9" class="data row70 col9" >16.85</td>
                        <td id="T_e59d7_row70_col10" class="data row70 col10" >31.47</td>
                        <td id="T_e59d7_row70_col11" class="data row70 col11" >8.83</td>
                        <td id="T_e59d7_row70_col12" class="data row70 col12" >6.24</td>
                        <td id="T_e59d7_row70_col13" class="data row70 col13" >United States</td>
                        <td id="T_e59d7_row70_col14" class="data row70 col14" >27.24</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row71" class="row_heading level0 row71" >LGND</th>
                        <td id="T_e59d7_row71_col0" class="data row71 col0" >47.92</td>
                        <td id="T_e59d7_row71_col1" class="data row71 col1" >31.68</td>
                        <td id="T_e59d7_row71_col2" class="data row71 col2" >26.73</td>
                        <td id="T_e59d7_row71_col3" class="data row71 col3" >27.54</td>
                        <td id="T_e59d7_row71_col4" class="data row71 col4" >146.87</td>
                        <td id="T_e59d7_row71_col5" class="data row71 col5" >27.01</td>
                        <td id="T_e59d7_row71_col6" class="data row71 col6" >69.54</td>
                        <td id="T_e59d7_row71_col7" class="data row71 col7" >426.69</td>
                        <td id="T_e59d7_row71_col8" class="data row71 col8" >575.98</td>
                        <td id="T_e59d7_row71_col9" class="data row71 col9" >-83.39</td>
                        <td id="T_e59d7_row71_col10" class="data row71 col10" >192.52</td>
                        <td id="T_e59d7_row71_col11" class="data row71 col11" >0.02</td>
                        <td id="T_e59d7_row71_col12" class="data row71 col12" >314.05</td>
                        <td id="T_e59d7_row71_col13" class="data row71 col13" >United States</td>
                        <td id="T_e59d7_row71_col14" class="data row71 col14" >1.89</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row72" class="row_heading level0 row72" >LMST</th>
                        <td id="T_e59d7_row72_col0" class="data row72 col0" >91.16</td>
                        <td id="T_e59d7_row72_col1" class="data row72 col1" >0.00</td>
                        <td id="T_e59d7_row72_col2" class="data row72 col2" >5.39</td>
                        <td id="T_e59d7_row72_col3" class="data row72 col3" >20.57</td>
                        <td id="T_e59d7_row72_col4" class="data row72 col4" >42.81</td>
                        <td id="T_e59d7_row72_col5" class="data row72 col5" >4.90</td>
                        <td id="T_e59d7_row72_col6" class="data row72 col6" >2.94</td>
                        <td id="T_e59d7_row72_col7" class="data row72 col7" >-23.97</td>
                        <td id="T_e59d7_row72_col8" class="data row72 col8" >49.07</td>
                        <td id="T_e59d7_row72_col9" class="data row72 col9" >212.85</td>
                        <td id="T_e59d7_row72_col10" class="data row72 col10" >306.94</td>
                        <td id="T_e59d7_row72_col11" class="data row72 col11" >3.87</td>
                        <td id="T_e59d7_row72_col12" class="data row72 col12" >0.10</td>
                        <td id="T_e59d7_row72_col13" class="data row72 col13" >United States</td>
                        <td id="T_e59d7_row72_col14" class="data row72 col14" >0.12</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row73" class="row_heading level0 row73" >LOPE</th>
                        <td id="T_e59d7_row73_col0" class="data row73 col0" >14.65</td>
                        <td id="T_e59d7_row73_col1" class="data row73 col1" >8.11</td>
                        <td id="T_e59d7_row73_col2" class="data row73 col2" >10.21</td>
                        <td id="T_e59d7_row73_col3" class="data row73 col3" >18.45</td>
                        <td id="T_e59d7_row73_col4" class="data row73 col4" >27.93</td>
                        <td id="T_e59d7_row73_col5" class="data row73 col5" >-4.24</td>
                        <td id="T_e59d7_row73_col6" class="data row73 col6" >11.26</td>
                        <td id="T_e59d7_row73_col7" class="data row73 col7" >8.35</td>
                        <td id="T_e59d7_row73_col8" class="data row73 col8" >7.90</td>
                        <td id="T_e59d7_row73_col9" class="data row73 col9" >24.62</td>
                        <td id="T_e59d7_row73_col10" class="data row73 col10" >73.50</td>
                        <td id="T_e59d7_row73_col11" class="data row73 col11" >3.38</td>
                        <td id="T_e59d7_row73_col12" class="data row73 col12" >3.77</td>
                        <td id="T_e59d7_row73_col13" class="data row73 col13" >United States</td>
                        <td id="T_e59d7_row73_col14" class="data row73 col14" >4.18</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row74" class="row_heading level0 row74" >MA</th>
                        <td id="T_e59d7_row74_col0" class="data row74 col0" >80.59</td>
                        <td id="T_e59d7_row74_col1" class="data row74 col1" >28.44</td>
                        <td id="T_e59d7_row74_col2" class="data row74 col2" >77.61</td>
                        <td id="T_e59d7_row74_col3" class="data row74 col3" >104.57</td>
                        <td id="T_e59d7_row74_col4" class="data row74 col4" >40.13</td>
                        <td id="T_e59d7_row74_col5" class="data row74 col5" >7.73</td>
                        <td id="T_e59d7_row74_col6" class="data row74 col6" >15.18</td>
                        <td id="T_e59d7_row74_col7" class="data row74 col7" >22.39</td>
                        <td id="T_e59d7_row74_col8" class="data row74 col8" >38.01</td>
                        <td id="T_e59d7_row74_col9" class="data row74 col9" >10.09</td>
                        <td id="T_e59d7_row74_col10" class="data row74 col10" >21.49</td>
                        <td id="T_e59d7_row74_col11" class="data row74 col11" >107.54</td>
                        <td id="T_e59d7_row74_col12" class="data row74 col12" >135.96</td>
                        <td id="T_e59d7_row74_col13" class="data row74 col13" >United States</td>
                        <td id="T_e59d7_row74_col14" class="data row74 col14" >363.57</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row75" class="row_heading level0 row75" >MASI</th>
                        <td id="T_e59d7_row75_col0" class="data row75 col0" >17.80</td>
                        <td id="T_e59d7_row75_col1" class="data row75 col1" >15.86</td>
                        <td id="T_e59d7_row75_col2" class="data row75 col2" >7.33</td>
                        <td id="T_e59d7_row75_col3" class="data row75 col3" >17.77</td>
                        <td id="T_e59d7_row75_col4" class="data row75 col4" >20.07</td>
                        <td id="T_e59d7_row75_col5" class="data row75 col5" >13.28</td>
                        <td id="T_e59d7_row75_col6" class="data row75 col6" >7.52</td>
                        <td id="T_e59d7_row75_col7" class="data row75 col7" >26.32</td>
                        <td id="T_e59d7_row75_col8" class="data row75 col8" >27.06</td>
                        <td id="T_e59d7_row75_col9" class="data row75 col9" >551.99</td>
                        <td id="T_e59d7_row75_col10" class="data row75 col10" >991.44</td>
                        <td id="T_e59d7_row75_col11" class="data row75 col11" >399.28</td>
                        <td id="T_e59d7_row75_col12" class="data row75 col12" >4.62</td>
                        <td id="T_e59d7_row75_col13" class="data row75 col13" >United States</td>
                        <td id="T_e59d7_row75_col14" class="data row75 col14" >11.57</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row76" class="row_heading level0 row76" >MBIN</th>
                        <td id="T_e59d7_row76_col0" class="data row76 col0" >91.60</td>
                        <td id="T_e59d7_row76_col1" class="data row76 col1" >2.33</td>
                        <td id="T_e59d7_row76_col2" class="data row76 col2" >2.65</td>
                        <td id="T_e59d7_row76_col3" class="data row76 col3" >20.27</td>
                        <td id="T_e59d7_row76_col4" class="data row76 col4" >48.85</td>
                        <td id="T_e59d7_row76_col5" class="data row76 col5" >49.56</td>
                        <td id="T_e59d7_row76_col6" class="data row76 col6" >48.35</td>
                        <td id="T_e59d7_row76_col7" class="data row76 col7" >57.14</td>
                        <td id="T_e59d7_row76_col8" class="data row76 col8" >66.21</td>
                        <td id="T_e59d7_row76_col9" class="data row76 col9" >-330.88</td>
                        <td id="T_e59d7_row76_col10" class="data row76 col10" >375.02</td>
                        <td id="T_e59d7_row76_col11" class="data row76 col11" >69.29</td>
                        <td id="T_e59d7_row76_col12" class="data row76 col12" >4.29</td>
                        <td id="T_e59d7_row76_col13" class="data row76 col13" >United States</td>
                        <td id="T_e59d7_row76_col14" class="data row76 col14" >1.22</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row77" class="row_heading level0 row77" >MBINO</th>
                        <td id="T_e59d7_row77_col0" class="data row77 col0" >91.60</td>
                        <td id="T_e59d7_row77_col1" class="data row77 col1" >2.33</td>
                        <td id="T_e59d7_row77_col2" class="data row77 col2" >2.65</td>
                        <td id="T_e59d7_row77_col3" class="data row77 col3" >20.27</td>
                        <td id="T_e59d7_row77_col4" class="data row77 col4" >48.85</td>
                        <td id="T_e59d7_row77_col5" class="data row77 col5" >49.56</td>
                        <td id="T_e59d7_row77_col6" class="data row77 col6" >48.35</td>
                        <td id="T_e59d7_row77_col7" class="data row77 col7" >57.14</td>
                        <td id="T_e59d7_row77_col8" class="data row77 col8" >66.21</td>
                        <td id="T_e59d7_row77_col9" class="data row77 col9" >-330.88</td>
                        <td id="T_e59d7_row77_col10" class="data row77 col10" >375.02</td>
                        <td id="T_e59d7_row77_col11" class="data row77 col11" >69.29</td>
                        <td id="T_e59d7_row77_col12" class="data row77 col12" >4.29</td>
                        <td id="T_e59d7_row77_col13" class="data row77 col13" >United States</td>
                        <td id="T_e59d7_row77_col14" class="data row77 col14" >0.00</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row78" class="row_heading level0 row78" >MBINP</th>
                        <td id="T_e59d7_row78_col0" class="data row78 col0" >91.60</td>
                        <td id="T_e59d7_row78_col1" class="data row78 col1" >2.33</td>
                        <td id="T_e59d7_row78_col2" class="data row78 col2" >2.65</td>
                        <td id="T_e59d7_row78_col3" class="data row78 col3" >20.27</td>
                        <td id="T_e59d7_row78_col4" class="data row78 col4" >48.85</td>
                        <td id="T_e59d7_row78_col5" class="data row78 col5" >49.56</td>
                        <td id="T_e59d7_row78_col6" class="data row78 col6" >48.35</td>
                        <td id="T_e59d7_row78_col7" class="data row78 col7" >57.14</td>
                        <td id="T_e59d7_row78_col8" class="data row78 col8" >66.21</td>
                        <td id="T_e59d7_row78_col9" class="data row78 col9" >-330.88</td>
                        <td id="T_e59d7_row78_col10" class="data row78 col10" >375.02</td>
                        <td id="T_e59d7_row78_col11" class="data row78 col11" >69.29</td>
                        <td id="T_e59d7_row78_col12" class="data row78 col12" >4.29</td>
                        <td id="T_e59d7_row78_col13" class="data row78 col13" >United States</td>
                        <td id="T_e59d7_row78_col14" class="data row78 col14" >0.00</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row79" class="row_heading level0 row79" >MCO</th>
                        <td id="T_e59d7_row79_col0" class="data row79 col0" >85.79</td>
                        <td id="T_e59d7_row79_col1" class="data row79 col1" >26.62</td>
                        <td id="T_e59d7_row79_col2" class="data row79 col2" >290.38</td>
                        <td id="T_e59d7_row79_col3" class="data row79 col3" >81.40</td>
                        <td id="T_e59d7_row79_col4" class="data row79 col4" >28.96</td>
                        <td id="T_e59d7_row79_col5" class="data row79 col5" >8.53</td>
                        <td id="T_e59d7_row79_col6" class="data row79 col6" >2.77</td>
                        <td id="T_e59d7_row79_col7" class="data row79 col7" >21.48</td>
                        <td id="T_e59d7_row79_col8" class="data row79 col8" >11.58</td>
                        <td id="T_e59d7_row79_col9" class="data row79 col9" >50.25</td>
                        <td id="T_e59d7_row79_col10" class="data row79 col10" >48.82</td>
                        <td id="T_e59d7_row79_col11" class="data row79 col11" >57.06</td>
                        <td id="T_e59d7_row79_col12" class="data row79 col12" >30.19</td>
                        <td id="T_e59d7_row79_col13" class="data row79 col13" >United States</td>
                        <td id="T_e59d7_row79_col14" class="data row79 col14" >62.71</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row80" class="row_heading level0 row80" >MGRC</th>
                        <td id="T_e59d7_row80_col0" class="data row80 col0" >46.49</td>
                        <td id="T_e59d7_row80_col1" class="data row80 col1" >21.54</td>
                        <td id="T_e59d7_row80_col2" class="data row80 col2" >4.13</td>
                        <td id="T_e59d7_row80_col3" class="data row80 col3" >18.37</td>
                        <td id="T_e59d7_row80_col4" class="data row80 col4" >21.01</td>
                        <td id="T_e59d7_row80_col5" class="data row80 col5" >7.56</td>
                        <td id="T_e59d7_row80_col6" class="data row80 col6" >7.01</td>
                        <td id="T_e59d7_row80_col7" class="data row80 col7" >-7.05</td>
                        <td id="T_e59d7_row80_col8" class="data row80 col8" >36.76</td>
                        <td id="T_e59d7_row80_col9" class="data row80 col9" >48.67</td>
                        <td id="T_e59d7_row80_col10" class="data row80 col10" >82.01</td>
                        <td id="T_e59d7_row80_col11" class="data row80 col11" >2.70</td>
                        <td id="T_e59d7_row80_col12" class="data row80 col12" >1.12</td>
                        <td id="T_e59d7_row80_col13" class="data row80 col13" >United States</td>
                        <td id="T_e59d7_row80_col14" class="data row80 col14" >2.06</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row81" class="row_heading level0 row81" >MKTX</th>
                        <td id="T_e59d7_row81_col0" class="data row81 col0" >28.27</td>
                        <td id="T_e59d7_row81_col1" class="data row81 col1" >38.08</td>
                        <td id="T_e59d7_row81_col2" class="data row81 col2" >15.43</td>
                        <td id="T_e59d7_row81_col3" class="data row81 col3" >28.79</td>
                        <td id="T_e59d7_row81_col4" class="data row81 col4" >40.21</td>
                        <td id="T_e59d7_row81_col5" class="data row81 col5" >20.96</td>
                        <td id="T_e59d7_row81_col6" class="data row81 col6" >12.42</td>
                        <td id="T_e59d7_row81_col7" class="data row81 col7" >27.12</td>
                        <td id="T_e59d7_row81_col8" class="data row81 col8" >16.47</td>
                        <td id="T_e59d7_row81_col9" class="data row81 col9" >36.34</td>
                        <td id="T_e59d7_row81_col10" class="data row81 col10" >16.54</td>
                        <td id="T_e59d7_row81_col11" class="data row81 col11" >7.50</td>
                        <td id="T_e59d7_row81_col12" class="data row81 col12" >5.14</td>
                        <td id="T_e59d7_row81_col13" class="data row81 col13" >United States</td>
                        <td id="T_e59d7_row81_col14" class="data row81 col14" >17.49</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row82" class="row_heading level0 row82" >MMAC</th>
                        <td id="T_e59d7_row82_col0" class="data row82 col0" >45.62</td>
                        <td id="T_e59d7_row82_col1" class="data row82 col1" >0.32</td>
                        <td id="T_e59d7_row82_col2" class="data row82 col2" >0.00</td>
                        <td id="T_e59d7_row82_col3" class="data row82 col3" >20.39</td>
                        <td id="T_e59d7_row82_col4" class="data row82 col4" >126.92</td>
                        <td id="T_e59d7_row82_col5" class="data row82 col5" >131.63</td>
                        <td id="T_e59d7_row82_col6" class="data row82 col6" >233.42</td>
                        <td id="T_e59d7_row82_col7" class="data row82 col7" >62.74</td>
                        <td id="T_e59d7_row82_col8" class="data row82 col8" >153.08</td>
                        <td id="T_e59d7_row82_col9" class="data row82 col9" >0.00</td>
                        <td id="T_e59d7_row82_col10" class="data row82 col10" >0.00</td>
                        <td id="T_e59d7_row82_col11" class="data row82 col11" >0.00</td>
                        <td id="T_e59d7_row82_col12" class="data row82 col12" >2.40</td>
                        <td id="T_e59d7_row82_col13" class="data row82 col13" >United States</td>
                        <td id="T_e59d7_row82_col14" class="data row82 col14" >0.16</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row83" class="row_heading level0 row83" >MMP</th>
                        <td id="T_e59d7_row83_col0" class="data row83 col0" >71.89</td>
                        <td id="T_e59d7_row83_col1" class="data row83 col1" >6.53</td>
                        <td id="T_e59d7_row83_col2" class="data row83 col2" >2.29</td>
                        <td id="T_e59d7_row83_col3" class="data row83 col3" >41.09</td>
                        <td id="T_e59d7_row83_col4" class="data row83 col4" >38.24</td>
                        <td id="T_e59d7_row83_col5" class="data row83 col5" >-0.59</td>
                        <td id="T_e59d7_row83_col6" class="data row83 col6" >12.12</td>
                        <td id="T_e59d7_row83_col7" class="data row83 col7" >3.32</td>
                        <td id="T_e59d7_row83_col8" class="data row83 col8" >43.41</td>
                        <td id="T_e59d7_row83_col9" class="data row83 col9" >21.33</td>
                        <td id="T_e59d7_row83_col10" class="data row83 col10" >66.92</td>
                        <td id="T_e59d7_row83_col11" class="data row83 col11" >13.20</td>
                        <td id="T_e59d7_row83_col12" class="data row83 col12" >14.06</td>
                        <td id="T_e59d7_row83_col13" class="data row83 col13" >United States</td>
                        <td id="T_e59d7_row83_col14" class="data row83 col14" >11.42</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row84" class="row_heading level0 row84" >MNDO</th>
                        <td id="T_e59d7_row84_col0" class="data row84 col0" >28.68</td>
                        <td id="T_e59d7_row84_col1" class="data row84 col1" >10.28</td>
                        <td id="T_e59d7_row84_col2" class="data row84 col2" >35.20</td>
                        <td id="T_e59d7_row84_col3" class="data row84 col3" >24.38</td>
                        <td id="T_e59d7_row84_col4" class="data row84 col4" >26.19</td>
                        <td id="T_e59d7_row84_col5" class="data row84 col5" >9.50</td>
                        <td id="T_e59d7_row84_col6" class="data row84 col6" >13.47</td>
                        <td id="T_e59d7_row84_col7" class="data row84 col7" >-1.19</td>
                        <td id="T_e59d7_row84_col8" class="data row84 col8" >7.40</td>
                        <td id="T_e59d7_row84_col9" class="data row84 col9" >37.41</td>
                        <td id="T_e59d7_row84_col10" class="data row84 col10" >35.81</td>
                        <td id="T_e59d7_row84_col11" class="data row84 col11" >0.16</td>
                        <td id="T_e59d7_row84_col12" class="data row84 col12" >0.07</td>
                        <td id="T_e59d7_row84_col13" class="data row84 col13" >Israel</td>
                        <td id="T_e59d7_row84_col14" class="data row84 col14" >0.06</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row85" class="row_heading level0 row85" >MNST</th>
                        <td id="T_e59d7_row85_col0" class="data row85 col0" >16.80</td>
                        <td id="T_e59d7_row85_col1" class="data row85 col1" >14.48</td>
                        <td id="T_e59d7_row85_col2" class="data row85 col2" >25.80</td>
                        <td id="T_e59d7_row85_col3" class="data row85 col3" >25.61</td>
                        <td id="T_e59d7_row85_col4" class="data row85 col4" >26.87</td>
                        <td id="T_e59d7_row85_col5" class="data row85 col5" >10.94</td>
                        <td id="T_e59d7_row85_col6" class="data row85 col6" >1.84</td>
                        <td id="T_e59d7_row85_col7" class="data row85 col7" >19.93</td>
                        <td id="T_e59d7_row85_col8" class="data row85 col8" >7.89</td>
                        <td id="T_e59d7_row85_col9" class="data row85 col9" >14.54</td>
                        <td id="T_e59d7_row85_col10" class="data row85 col10" >19.95</td>
                        <td id="T_e59d7_row85_col11" class="data row85 col11" >20.10</td>
                        <td id="T_e59d7_row85_col12" class="data row85 col12" >22.88</td>
                        <td id="T_e59d7_row85_col13" class="data row85 col13" >United States</td>
                        <td id="T_e59d7_row85_col14" class="data row85 col14" >50.12</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row86" class="row_heading level0 row86" >MO</th>
                        <td id="T_e59d7_row86_col0" class="data row86 col0" >93.75</td>
                        <td id="T_e59d7_row86_col1" class="data row86 col1" >0.66</td>
                        <td id="T_e59d7_row86_col2" class="data row86 col2" >182.35</td>
                        <td id="T_e59d7_row86_col3" class="data row86 col3" >62.53</td>
                        <td id="T_e59d7_row86_col4" class="data row86 col4" >25.70</td>
                        <td id="T_e59d7_row86_col5" class="data row86 col5" >2.27</td>
                        <td id="T_e59d7_row86_col6" class="data row86 col6" >2.60</td>
                        <td id="T_e59d7_row86_col7" class="data row86 col7" >-198.64</td>
                        <td id="T_e59d7_row86_col8" class="data row86 col8" >218.11</td>
                        <td id="T_e59d7_row86_col9" class="data row86 col9" >24.64</td>
                        <td id="T_e59d7_row86_col10" class="data row86 col10" >42.83</td>
                        <td id="T_e59d7_row86_col11" class="data row86 col11" >168.44</td>
                        <td id="T_e59d7_row86_col12" class="data row86 col12" >-53.10</td>
                        <td id="T_e59d7_row86_col13" class="data row86 col13" >United States</td>
                        <td id="T_e59d7_row86_col14" class="data row86 col14" >91.63</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row87" class="row_heading level0 row87" >MSFT</th>
                        <td id="T_e59d7_row87_col0" class="data row87 col0" >60.74</td>
                        <td id="T_e59d7_row87_col1" class="data row87 col1" >22.38</td>
                        <td id="T_e59d7_row87_col2" class="data row87 col2" >36.64</td>
                        <td id="T_e59d7_row87_col3" class="data row87 col3" >31.22</td>
                        <td id="T_e59d7_row87_col4" class="data row87 col4" >25.89</td>
                        <td id="T_e59d7_row87_col5" class="data row87 col5" >13.98</td>
                        <td id="T_e59d7_row87_col6" class="data row87 col6" >0.32</td>
                        <td id="T_e59d7_row87_col7" class="data row87 col7" >38.22</td>
                        <td id="T_e59d7_row87_col8" class="data row87 col8" >88.66</td>
                        <td id="T_e59d7_row87_col9" class="data row87 col9" >13.21</td>
                        <td id="T_e59d7_row87_col10" class="data row87 col10" >9.03</td>
                        <td id="T_e59d7_row87_col11" class="data row87 col11" >660.67</td>
                        <td id="T_e59d7_row87_col12" class="data row87 col12" >992.65</td>
                        <td id="T_e59d7_row87_col13" class="data row87 col13" >United States</td>
                        <td id="T_e59d7_row87_col14" class="data row87 col14" >1862.56</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row88" class="row_heading level0 row88" >MU</th>
                        <td id="T_e59d7_row88_col0" class="data row88 col0" >27.35</td>
                        <td id="T_e59d7_row88_col1" class="data row88 col1" >18.25</td>
                        <td id="T_e59d7_row88_col2" class="data row88 col2" >3.15</td>
                        <td id="T_e59d7_row88_col3" class="data row88 col3" >23.90</td>
                        <td id="T_e59d7_row88_col4" class="data row88 col4" >27.76</td>
                        <td id="T_e59d7_row88_col5" class="data row88 col5" >6.05</td>
                        <td id="T_e59d7_row88_col6" class="data row88 col6" >38.37</td>
                        <td id="T_e59d7_row88_col7" class="data row88 col7" >21.66</td>
                        <td id="T_e59d7_row88_col8" class="data row88 col8" >135.19</td>
                        <td id="T_e59d7_row88_col9" class="data row88 col9" >-2.78</td>
                        <td id="T_e59d7_row88_col10" class="data row88 col10" >132.97</td>
                        <td id="T_e59d7_row88_col11" class="data row88 col11" >45.35</td>
                        <td id="T_e59d7_row88_col12" class="data row88 col12" >155.23</td>
                        <td id="T_e59d7_row88_col13" class="data row88 col13" >United States</td>
                        <td id="T_e59d7_row88_col14" class="data row88 col14" >94.58</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row89" class="row_heading level0 row89" >NLOK</th>
                        <td id="T_e59d7_row89_col0" class="data row89 col0" >99.87</td>
                        <td id="T_e59d7_row89_col1" class="data row89 col1" >14.02</td>
                        <td id="T_e59d7_row89_col2" class="data row89 col2" >25850.00</td>
                        <td id="T_e59d7_row89_col3" class="data row89 col3" >9722.54</td>
                        <td id="T_e59d7_row89_col4" class="data row89 col4" >49.80</td>
                        <td id="T_e59d7_row89_col5" class="data row89 col5" >-12.99</td>
                        <td id="T_e59d7_row89_col6" class="data row89 col6" >20.39</td>
                        <td id="T_e59d7_row89_col7" class="data row89 col7" >3722.62</td>
                        <td id="T_e59d7_row89_col8" class="data row89 col8" >7567.52</td>
                        <td id="T_e59d7_row89_col9" class="data row89 col9" >-167.99</td>
                        <td id="T_e59d7_row89_col10" class="data row89 col10" >224.56</td>
                        <td id="T_e59d7_row89_col11" class="data row89 col11" >-0.79</td>
                        <td id="T_e59d7_row89_col12" class="data row89 col12" >746892.44</td>
                        <td id="T_e59d7_row89_col13" class="data row89 col13" >United States</td>
                        <td id="T_e59d7_row89_col14" class="data row89 col14" >16.52</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row90" class="row_heading level0 row90" >NRC</th>
                        <td id="T_e59d7_row90_col0" class="data row90 col0" >51.80</td>
                        <td id="T_e59d7_row90_col1" class="data row90 col1" >11.61</td>
                        <td id="T_e59d7_row90_col2" class="data row90 col2" >89.02</td>
                        <td id="T_e59d7_row90_col3" class="data row90 col3" >84.85</td>
                        <td id="T_e59d7_row90_col4" class="data row90 col4" >24.47</td>
                        <td id="T_e59d7_row90_col5" class="data row90 col5" >4.29</td>
                        <td id="T_e59d7_row90_col6" class="data row90 col6" >2.56</td>
                        <td id="T_e59d7_row90_col7" class="data row90 col7" >17.93</td>
                        <td id="T_e59d7_row90_col8" class="data row90 col8" >11.84</td>
                        <td id="T_e59d7_row90_col9" class="data row90 col9" >17.38</td>
                        <td id="T_e59d7_row90_col10" class="data row90 col10" >23.26</td>
                        <td id="T_e59d7_row90_col11" class="data row90 col11" >0.65</td>
                        <td id="T_e59d7_row90_col12" class="data row90 col12" >0.62</td>
                        <td id="T_e59d7_row90_col13" class="data row90 col13" >United States</td>
                        <td id="T_e59d7_row90_col14" class="data row90 col14" >1.21</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row91" class="row_heading level0 row91" >NTES</th>
                        <td id="T_e59d7_row91_col0" class="data row91 col0" >33.89</td>
                        <td id="T_e59d7_row91_col1" class="data row91 col1" >8.99</td>
                        <td id="T_e59d7_row91_col2" class="data row91 col2" >0.39</td>
                        <td id="T_e59d7_row91_col3" class="data row91 col3" >21.57</td>
                        <td id="T_e59d7_row91_col4" class="data row91 col4" >22.09</td>
                        <td id="T_e59d7_row91_col5" class="data row91 col5" >18.43</td>
                        <td id="T_e59d7_row91_col6" class="data row91 col6" >5.14</td>
                        <td id="T_e59d7_row91_col7" class="data row91 col7" >53.15</td>
                        <td id="T_e59d7_row91_col8" class="data row91 col8" >166.31</td>
                        <td id="T_e59d7_row91_col9" class="data row91 col9" >33.70</td>
                        <td id="T_e59d7_row91_col10" class="data row91 col10" >20.88</td>
                        <td id="T_e59d7_row91_col11" class="data row91 col11" >440.86</td>
                        <td id="T_e59d7_row91_col12" class="data row91 col12" >532.03</td>
                        <td id="T_e59d7_row91_col13" class="data row91 col13" >China</td>
                        <td id="T_e59d7_row91_col14" class="data row91 col14" >77.44</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row92" class="row_heading level0 row92" >NVDA</th>
                        <td id="T_e59d7_row92_col0" class="data row92 col0" >41.33</td>
                        <td id="T_e59d7_row92_col1" class="data row92 col1" >14.57</td>
                        <td id="T_e59d7_row92_col2" class="data row92 col2" >24.82</td>
                        <td id="T_e59d7_row92_col3" class="data row92 col3" >33.42</td>
                        <td id="T_e59d7_row92_col4" class="data row92 col4" >29.58</td>
                        <td id="T_e59d7_row92_col5" class="data row92 col5" >22.18</td>
                        <td id="T_e59d7_row92_col6" class="data row92 col6" >29.80</td>
                        <td id="T_e59d7_row92_col7" class="data row92 col7" >19.45</td>
                        <td id="T_e59d7_row92_col8" class="data row92 col8" >45.97</td>
                        <td id="T_e59d7_row92_col9" class="data row92 col9" >17.95</td>
                        <td id="T_e59d7_row92_col10" class="data row92 col10" >15.59</td>
                        <td id="T_e59d7_row92_col11" class="data row92 col11" >75.68</td>
                        <td id="T_e59d7_row92_col12" class="data row92 col12" >74.77</td>
                        <td id="T_e59d7_row92_col13" class="data row92 col13" >United States</td>
                        <td id="T_e59d7_row92_col14" class="data row92 col14" >418.11</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row93" class="row_heading level0 row93" >OCG</th>
                        <td id="T_e59d7_row93_col0" class="data row93 col0" >18.34</td>
                        <td id="T_e59d7_row93_col1" class="data row93 col1" >3.45</td>
                        <td id="T_e59d7_row93_col2" class="data row93 col2" >0.00</td>
                        <td id="T_e59d7_row93_col3" class="data row93 col3" >58.19</td>
                        <td id="T_e59d7_row93_col4" class="data row93 col4" >42.78</td>
                        <td id="T_e59d7_row93_col5" class="data row93 col5" >90.46</td>
                        <td id="T_e59d7_row93_col6" class="data row93 col6" >85.99</td>
                        <td id="T_e59d7_row93_col7" class="data row93 col7" >84.43</td>
                        <td id="T_e59d7_row93_col8" class="data row93 col8" >228.95</td>
                        <td id="T_e59d7_row93_col9" class="data row93 col9" >87.97</td>
                        <td id="T_e59d7_row93_col10" class="data row93 col10" >143.00</td>
                        <td id="T_e59d7_row93_col11" class="data row93 col11" >0.53</td>
                        <td id="T_e59d7_row93_col12" class="data row93 col12" >0.33</td>
                        <td id="T_e59d7_row93_col13" class="data row93 col13" >China</td>
                        <td id="T_e59d7_row93_col14" class="data row93 col14" >0.10</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row94" class="row_heading level0 row94" >OMP</th>
                        <td id="T_e59d7_row94_col0" class="data row94 col0" >49.19</td>
                        <td id="T_e59d7_row94_col1" class="data row94 col1" >20.29</td>
                        <td id="T_e59d7_row94_col2" class="data row94 col2" >0.00</td>
                        <td id="T_e59d7_row94_col3" class="data row94 col3" >22.49</td>
                        <td id="T_e59d7_row94_col4" class="data row94 col4" >20.09</td>
                        <td id="T_e59d7_row94_col5" class="data row94 col5" >28.29</td>
                        <td id="T_e59d7_row94_col6" class="data row94 col6" >37.66</td>
                        <td id="T_e59d7_row94_col7" class="data row94 col7" >17.79</td>
                        <td id="T_e59d7_row94_col8" class="data row94 col8" >109.35</td>
                        <td id="T_e59d7_row94_col9" class="data row94 col9" >109.55</td>
                        <td id="T_e59d7_row94_col10" class="data row94 col10" >332.35</td>
                        <td id="T_e59d7_row94_col11" class="data row94 col11" >0.14</td>
                        <td id="T_e59d7_row94_col12" class="data row94 col12" >1.20</td>
                        <td id="T_e59d7_row94_col13" class="data row94 col13" >United States</td>
                        <td id="T_e59d7_row94_col14" class="data row94 col14" >1.28</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row95" class="row_heading level0 row95" >ORCL</th>
                        <td id="T_e59d7_row95_col0" class="data row95 col0" >88.98</td>
                        <td id="T_e59d7_row95_col1" class="data row95 col1" >16.20</td>
                        <td id="T_e59d7_row95_col2" class="data row95 col2" >362.51</td>
                        <td id="T_e59d7_row95_col3" class="data row95 col3" >40.02</td>
                        <td id="T_e59d7_row95_col4" class="data row95 col4" >22.03</td>
                        <td id="T_e59d7_row95_col5" class="data row95 col5" >1.14</td>
                        <td id="T_e59d7_row95_col6" class="data row95 col6" >2.75</td>
                        <td id="T_e59d7_row95_col7" class="data row95 col7" >46.12</td>
                        <td id="T_e59d7_row95_col8" class="data row95 col8" >143.55</td>
                        <td id="T_e59d7_row95_col9" class="data row95 col9" >-1.00</td>
                        <td id="T_e59d7_row95_col10" class="data row95 col10" >12.15</td>
                        <td id="T_e59d7_row95_col11" class="data row95 col11" >155.14</td>
                        <td id="T_e59d7_row95_col12" class="data row95 col12" >317.51</td>
                        <td id="T_e59d7_row95_col13" class="data row95 col13" >United States</td>
                        <td id="T_e59d7_row95_col14" class="data row95 col14" >231.46</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row96" class="row_heading level0 row96" >PAX</th>
                        <td id="T_e59d7_row96_col0" class="data row96 col0" >44.90</td>
                        <td id="T_e59d7_row96_col1" class="data row96 col1" >21.53</td>
                        <td id="T_e59d7_row96_col2" class="data row96 col2" >0.00</td>
                        <td id="T_e59d7_row96_col3" class="data row96 col3" >80.55</td>
                        <td id="T_e59d7_row96_col4" class="data row96 col4" >47.64</td>
                        <td id="T_e59d7_row96_col5" class="data row96 col5" >4.98</td>
                        <td id="T_e59d7_row96_col6" class="data row96 col6" >16.45</td>
                        <td id="T_e59d7_row96_col7" class="data row96 col7" >20.16</td>
                        <td id="T_e59d7_row96_col8" class="data row96 col8" >19.65</td>
                        <td id="T_e59d7_row96_col9" class="data row96 col9" >16.81</td>
                        <td id="T_e59d7_row96_col10" class="data row96 col10" >2.43</td>
                        <td id="T_e59d7_row96_col11" class="data row96 col11" >0.88</td>
                        <td id="T_e59d7_row96_col12" class="data row96 col12" >1.16</td>
                        <td id="T_e59d7_row96_col13" class="data row96 col13" >Cayman Islands</td>
                        <td id="T_e59d7_row96_col14" class="data row96 col14" >2.30</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row97" class="row_heading level0 row97" >PAYC</th>
                        <td id="T_e59d7_row97_col0" class="data row97 col0" >74.86</td>
                        <td id="T_e59d7_row97_col1" class="data row97 col1" >2.33</td>
                        <td id="T_e59d7_row97_col2" class="data row97 col2" >7.91</td>
                        <td id="T_e59d7_row97_col3" class="data row97 col3" >35.26</td>
                        <td id="T_e59d7_row97_col4" class="data row97 col4" >23.56</td>
                        <td id="T_e59d7_row97_col5" class="data row97 col5" >25.03</td>
                        <td id="T_e59d7_row97_col6" class="data row97 col6" >9.50</td>
                        <td id="T_e59d7_row97_col7" class="data row97 col7" >7.39</td>
                        <td id="T_e59d7_row97_col8" class="data row97 col8" >26.34</td>
                        <td id="T_e59d7_row97_col9" class="data row97 col9" >27.67</td>
                        <td id="T_e59d7_row97_col10" class="data row97 col10" >42.35</td>
                        <td id="T_e59d7_row97_col11" class="data row97 col11" >2.90</td>
                        <td id="T_e59d7_row97_col12" class="data row97 col12" >2.26</td>
                        <td id="T_e59d7_row97_col13" class="data row97 col13" >0</td>
                        <td id="T_e59d7_row97_col14" class="data row97 col14" >19.55</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row98" class="row_heading level0 row98" >PAYX</th>
                        <td id="T_e59d7_row98_col0" class="data row98 col0" >67.47</td>
                        <td id="T_e59d7_row98_col1" class="data row98 col1" >19.56</td>
                        <td id="T_e59d7_row98_col2" class="data row98 col2" >64.40</td>
                        <td id="T_e59d7_row98_col3" class="data row98 col3" >40.85</td>
                        <td id="T_e59d7_row98_col4" class="data row98 col4" >27.56</td>
                        <td id="T_e59d7_row98_col5" class="data row98 col5" >8.64</td>
                        <td id="T_e59d7_row98_col6" class="data row98 col6" >2.64</td>
                        <td id="T_e59d7_row98_col7" class="data row98 col7" >10.17</td>
                        <td id="T_e59d7_row98_col8" class="data row98 col8" >8.84</td>
                        <td id="T_e59d7_row98_col9" class="data row98 col9" >15.44</td>
                        <td id="T_e59d7_row98_col10" class="data row98 col10" >13.69</td>
                        <td id="T_e59d7_row98_col11" class="data row98 col11" >21.11</td>
                        <td id="T_e59d7_row98_col12" class="data row98 col12" >16.45</td>
                        <td id="T_e59d7_row98_col13" class="data row98 col13" >United States</td>
                        <td id="T_e59d7_row98_col14" class="data row98 col14" >36.71</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row99" class="row_heading level0 row99" >PKE</th>
                        <td id="T_e59d7_row99_col0" class="data row99 col0" >17.53</td>
                        <td id="T_e59d7_row99_col1" class="data row99 col1" >18.20</td>
                        <td id="T_e59d7_row99_col2" class="data row99 col2" >6.90</td>
                        <td id="T_e59d7_row99_col3" class="data row99 col3" >24.61</td>
                        <td id="T_e59d7_row99_col4" class="data row99 col4" >79.60</td>
                        <td id="T_e59d7_row99_col5" class="data row99 col5" >23.61</td>
                        <td id="T_e59d7_row99_col6" class="data row99 col6" >5.38</td>
                        <td id="T_e59d7_row99_col7" class="data row99 col7" >160.53</td>
                        <td id="T_e59d7_row99_col8" class="data row99 col8" >273.51</td>
                        <td id="T_e59d7_row99_col9" class="data row99 col9" >-46.80</td>
                        <td id="T_e59d7_row99_col10" class="data row99 col10" >106.96</td>
                        <td id="T_e59d7_row99_col11" class="data row99 col11" >0.01</td>
                        <td id="T_e59d7_row99_col12" class="data row99 col12" >7.63</td>
                        <td id="T_e59d7_row99_col13" class="data row99 col13" >United States</td>
                        <td id="T_e59d7_row99_col14" class="data row99 col14" >0.31</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row100" class="row_heading level0 row100" >PLBC</th>
                        <td id="T_e59d7_row100_col0" class="data row100 col0" >90.99</td>
                        <td id="T_e59d7_row100_col1" class="data row100 col1" >0.00</td>
                        <td id="T_e59d7_row100_col2" class="data row100 col2" >0.00</td>
                        <td id="T_e59d7_row100_col3" class="data row100 col3" >17.10</td>
                        <td id="T_e59d7_row100_col4" class="data row100 col4" >31.35</td>
                        <td id="T_e59d7_row100_col5" class="data row100 col5" >7.25</td>
                        <td id="T_e59d7_row100_col6" class="data row100 col6" >8.10</td>
                        <td id="T_e59d7_row100_col7" class="data row100 col7" >25.01</td>
                        <td id="T_e59d7_row100_col8" class="data row100 col8" >40.66</td>
                        <td id="T_e59d7_row100_col9" class="data row100 col9" >30.22</td>
                        <td id="T_e59d7_row100_col10" class="data row100 col10" >29.46</td>
                        <td id="T_e59d7_row100_col11" class="data row100 col11" >0.40</td>
                        <td id="T_e59d7_row100_col12" class="data row100 col12" >0.31</td>
                        <td id="T_e59d7_row100_col13" class="data row100 col13" >United States</td>
                        <td id="T_e59d7_row100_col14" class="data row100 col14" >0.16</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row101" class="row_heading level0 row101" >PRPH</th>
                        <td id="T_e59d7_row101_col0" class="data row101 col0" >66.39</td>
                        <td id="T_e59d7_row101_col1" class="data row101 col1" >21.74</td>
                        <td id="T_e59d7_row101_col2" class="data row101 col2" >8.54</td>
                        <td id="T_e59d7_row101_col3" class="data row101 col3" >17.19</td>
                        <td id="T_e59d7_row101_col4" class="data row101 col4" >87.90</td>
                        <td id="T_e59d7_row101_col5" class="data row101 col5" >18.41</td>
                        <td id="T_e59d7_row101_col6" class="data row101 col6" >38.03</td>
                        <td id="T_e59d7_row101_col7" class="data row101 col7" >-18.65</td>
                        <td id="T_e59d7_row101_col8" class="data row101 col8" >93.32</td>
                        <td id="T_e59d7_row101_col9" class="data row101 col9" >73.98</td>
                        <td id="T_e59d7_row101_col10" class="data row101 col10" >196.60</td>
                        <td id="T_e59d7_row101_col11" class="data row101 col11" >-0.16</td>
                        <td id="T_e59d7_row101_col12" class="data row101 col12" >0.06</td>
                        <td id="T_e59d7_row101_col13" class="data row101 col13" >United States</td>
                        <td id="T_e59d7_row101_col14" class="data row101 col14" >0.08</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row102" class="row_heading level0 row102" >PRTC</th>
                        <td id="T_e59d7_row102_col0" class="data row102 col0" >33.99</td>
                        <td id="T_e59d7_row102_col1" class="data row102 col1" >24.97</td>
                        <td id="T_e59d7_row102_col2" class="data row102 col2" >0.00</td>
                        <td id="T_e59d7_row102_col3" class="data row102 col3" >15.18</td>
                        <td id="T_e59d7_row102_col4" class="data row102 col4" >1294.76</td>
                        <td id="T_e59d7_row102_col5" class="data row102 col5" >228.57</td>
                        <td id="T_e59d7_row102_col6" class="data row102 col6" >425.81</td>
                        <td id="T_e59d7_row102_col7" class="data row102 col7" >-476.07</td>
                        <td id="T_e59d7_row102_col8" class="data row102 col8" >516.53</td>
                        <td id="T_e59d7_row102_col9" class="data row102 col9" >17.38</td>
                        <td id="T_e59d7_row102_col10" class="data row102 col10" >29.57</td>
                        <td id="T_e59d7_row102_col11" class="data row102 col11" >-2.06</td>
                        <td id="T_e59d7_row102_col12" class="data row102 col12" >-57.81</td>
                        <td id="T_e59d7_row102_col13" class="data row102 col13" >United Kingdom</td>
                        <td id="T_e59d7_row102_col14" class="data row102 col14" >1.65</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row103" class="row_heading level0 row103" >PSXP</th>
                        <td id="T_e59d7_row103_col0" class="data row103 col0" >57.41</td>
                        <td id="T_e59d7_row103_col1" class="data row103 col1" >10.19</td>
                        <td id="T_e59d7_row103_col2" class="data row103 col2" >9.03</td>
                        <td id="T_e59d7_row103_col3" class="data row103 col3" >26.27</td>
                        <td id="T_e59d7_row103_col4" class="data row103 col4" >57.70</td>
                        <td id="T_e59d7_row103_col5" class="data row103 col5" >4.01</td>
                        <td id="T_e59d7_row103_col6" class="data row103 col6" >10.50</td>
                        <td id="T_e59d7_row103_col7" class="data row103 col7" >42.19</td>
                        <td id="T_e59d7_row103_col8" class="data row103 col8" >41.86</td>
                        <td id="T_e59d7_row103_col9" class="data row103 col9" >-118.57</td>
                        <td id="T_e59d7_row103_col10" class="data row103 col10" >61.66</td>
                        <td id="T_e59d7_row103_col11" class="data row103 col11" >-0.02</td>
                        <td id="T_e59d7_row103_col12" class="data row103 col12" >20.84</td>
                        <td id="T_e59d7_row103_col13" class="data row103 col13" >United States</td>
                        <td id="T_e59d7_row103_col14" class="data row103 col14" >9.45</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row104" class="row_heading level0 row104" >QLYS</th>
                        <td id="T_e59d7_row104_col0" class="data row104 col0" >45.10</td>
                        <td id="T_e59d7_row104_col1" class="data row104 col1" >27.60</td>
                        <td id="T_e59d7_row104_col2" class="data row104 col2" >1.84</td>
                        <td id="T_e59d7_row104_col3" class="data row104 col3" >17.09</td>
                        <td id="T_e59d7_row104_col4" class="data row104 col4" >21.21</td>
                        <td id="T_e59d7_row104_col5" class="data row104 col5" >16.33</td>
                        <td id="T_e59d7_row104_col6" class="data row104 col6" >4.08</td>
                        <td id="T_e59d7_row104_col7" class="data row104 col7" >31.59</td>
                        <td id="T_e59d7_row104_col8" class="data row104 col8" >10.36</td>
                        <td id="T_e59d7_row104_col9" class="data row104 col9" >29.80</td>
                        <td id="T_e59d7_row104_col10" class="data row104 col10" >17.14</td>
                        <td id="T_e59d7_row104_col11" class="data row104 col11" >3.01</td>
                        <td id="T_e59d7_row104_col12" class="data row104 col12" >1.78</td>
                        <td id="T_e59d7_row104_col13" class="data row104 col13" >United States</td>
                        <td id="T_e59d7_row104_col14" class="data row104 col14" >3.87</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row105" class="row_heading level0 row105" >RAMP</th>
                        <td id="T_e59d7_row105_col0" class="data row105 col0" >16.47</td>
                        <td id="T_e59d7_row105_col1" class="data row105 col1" >34.62</td>
                        <td id="T_e59d7_row105_col2" class="data row105 col2" >27.38</td>
                        <td id="T_e59d7_row105_col3" class="data row105 col3" >17.38</td>
                        <td id="T_e59d7_row105_col4" class="data row105 col4" >85.10</td>
                        <td id="T_e59d7_row105_col5" class="data row105 col5" >29.65</td>
                        <td id="T_e59d7_row105_col6" class="data row105 col6" >3.65</td>
                        <td id="T_e59d7_row105_col7" class="data row105 col7" >1546.66</td>
                        <td id="T_e59d7_row105_col8" class="data row105 col8" >2385.51</td>
                        <td id="T_e59d7_row105_col9" class="data row105 col9" >-212.71</td>
                        <td id="T_e59d7_row105_col10" class="data row105 col10" >303.24</td>
                        <td id="T_e59d7_row105_col11" class="data row105 col11" >1.21</td>
                        <td id="T_e59d7_row105_col12" class="data row105 col12" >11272.75</td>
                        <td id="T_e59d7_row105_col13" class="data row105 col13" >United States</td>
                        <td id="T_e59d7_row105_col14" class="data row105 col14" >3.35</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row106" class="row_heading level0 row106" >REGN</th>
                        <td id="T_e59d7_row106_col0" class="data row106 col0" >35.76</td>
                        <td id="T_e59d7_row106_col1" class="data row106 col1" >49.51</td>
                        <td id="T_e59d7_row106_col2" class="data row106 col2" >0.00</td>
                        <td id="T_e59d7_row106_col3" class="data row106 col3" >24.59</td>
                        <td id="T_e59d7_row106_col4" class="data row106 col4" >35.61</td>
                        <td id="T_e59d7_row106_col5" class="data row106 col5" >13.93</td>
                        <td id="T_e59d7_row106_col6" class="data row106 col6" >22.78</td>
                        <td id="T_e59d7_row106_col7" class="data row106 col7" >52.19</td>
                        <td id="T_e59d7_row106_col8" class="data row106 col8" >59.91</td>
                        <td id="T_e59d7_row106_col9" class="data row106 col9" >28.57</td>
                        <td id="T_e59d7_row106_col10" class="data row106 col10" >40.67</td>
                        <td id="T_e59d7_row106_col11" class="data row106 col11" >44.06</td>
                        <td id="T_e59d7_row106_col12" class="data row106 col12" >96.58</td>
                        <td id="T_e59d7_row106_col13" class="data row106 col13" >United States</td>
                        <td id="T_e59d7_row106_col14" class="data row106 col14" >53.84</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row107" class="row_heading level0 row107" >SFBS</th>
                        <td id="T_e59d7_row107_col0" class="data row107 col0" >91.68</td>
                        <td id="T_e59d7_row107_col1" class="data row107 col1" >0.00</td>
                        <td id="T_e59d7_row107_col2" class="data row107 col2" >1.37</td>
                        <td id="T_e59d7_row107_col3" class="data row107 col3" >17.33</td>
                        <td id="T_e59d7_row107_col4" class="data row107 col4" >49.70</td>
                        <td id="T_e59d7_row107_col5" class="data row107 col5" >13.89</td>
                        <td id="T_e59d7_row107_col6" class="data row107 col6" >3.62</td>
                        <td id="T_e59d7_row107_col7" class="data row107 col7" >23.24</td>
                        <td id="T_e59d7_row107_col8" class="data row107 col8" >20.80</td>
                        <td id="T_e59d7_row107_col9" class="data row107 col9" >28.28</td>
                        <td id="T_e59d7_row107_col10" class="data row107 col10" >37.87</td>
                        <td id="T_e59d7_row107_col11" class="data row107 col11" >3.93</td>
                        <td id="T_e59d7_row107_col12" class="data row107 col12" >3.13</td>
                        <td id="T_e59d7_row107_col13" class="data row107 col13" >United States</td>
                        <td id="T_e59d7_row107_col14" class="data row107 col14" >3.74</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row108" class="row_heading level0 row108" >SHEN</th>
                        <td id="T_e59d7_row108_col0" class="data row108 col0" >71.33</td>
                        <td id="T_e59d7_row108_col1" class="data row108 col1" >31.88</td>
                        <td id="T_e59d7_row108_col2" class="data row108 col2" >0.56</td>
                        <td id="T_e59d7_row108_col3" class="data row108 col3" >15.77</td>
                        <td id="T_e59d7_row108_col4" class="data row108 col4" >29.87</td>
                        <td id="T_e59d7_row108_col5" class="data row108 col5" >-18.14</td>
                        <td id="T_e59d7_row108_col6" class="data row108 col6" >43.62</td>
                        <td id="T_e59d7_row108_col7" class="data row108 col7" >38.91</td>
                        <td id="T_e59d7_row108_col8" class="data row108 col8" >79.83</td>
                        <td id="T_e59d7_row108_col9" class="data row108 col9" >53.43</td>
                        <td id="T_e59d7_row108_col10" class="data row108 col10" >103.94</td>
                        <td id="T_e59d7_row108_col11" class="data row108 col11" >7.04</td>
                        <td id="T_e59d7_row108_col12" class="data row108 col12" >2.37</td>
                        <td id="T_e59d7_row108_col13" class="data row108 col13" >United States</td>
                        <td id="T_e59d7_row108_col14" class="data row108 col14" >2.56</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row109" class="row_heading level0 row109" >SHIPW</th>
                        <td id="T_e59d7_row109_col0" class="data row109 col0" >85.02</td>
                        <td id="T_e59d7_row109_col1" class="data row109 col1" >4.85</td>
                        <td id="T_e59d7_row109_col2" class="data row109 col2" >0.00</td>
                        <td id="T_e59d7_row109_col3" class="data row109 col3" >719.10</td>
                        <td id="T_e59d7_row109_col4" class="data row109 col4" >960.56</td>
                        <td id="T_e59d7_row109_col5" class="data row109 col5" >261.03</td>
                        <td id="T_e59d7_row109_col6" class="data row109 col6" >177.09</td>
                        <td id="T_e59d7_row109_col7" class="data row109 col7" >-7.69</td>
                        <td id="T_e59d7_row109_col8" class="data row109 col8" >158.62</td>
                        <td id="T_e59d7_row109_col9" class="data row109 col9" >388.12</td>
                        <td id="T_e59d7_row109_col10" class="data row109 col10" >775.39</td>
                        <td id="T_e59d7_row109_col11" class="data row109 col11" >-98.51</td>
                        <td id="T_e59d7_row109_col12" class="data row109 col12" >0.11</td>
                        <td id="T_e59d7_row109_col13" class="data row109 col13" >Greece</td>
                        <td id="T_e59d7_row109_col14" class="data row109 col14" >0.00</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row110" class="row_heading level0 row110" >SIVB</th>
                        <td id="T_e59d7_row110_col0" class="data row110 col0" >92.70</td>
                        <td id="T_e59d7_row110_col1" class="data row110 col1" >0.98</td>
                        <td id="T_e59d7_row110_col2" class="data row110 col2" >1.81</td>
                        <td id="T_e59d7_row110_col3" class="data row110 col3" >16.16</td>
                        <td id="T_e59d7_row110_col4" class="data row110 col4" >32.94</td>
                        <td id="T_e59d7_row110_col5" class="data row110 col5" >26.03</td>
                        <td id="T_e59d7_row110_col6" class="data row110 col6" >9.59</td>
                        <td id="T_e59d7_row110_col7" class="data row110 col7" >40.52</td>
                        <td id="T_e59d7_row110_col8" class="data row110 col8" >50.51</td>
                        <td id="T_e59d7_row110_col9" class="data row110 col9" >32.11</td>
                        <td id="T_e59d7_row110_col10" class="data row110 col10" >14.58</td>
                        <td id="T_e59d7_row110_col11" class="data row110 col11" >27.38</td>
                        <td id="T_e59d7_row110_col12" class="data row110 col12" >31.57</td>
                        <td id="T_e59d7_row110_col13" class="data row110 col13" >United States</td>
                        <td id="T_e59d7_row110_col14" class="data row110 col14" >31.93</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row111" class="row_heading level0 row111" >SIVBP</th>
                        <td id="T_e59d7_row111_col0" class="data row111 col0" >92.70</td>
                        <td id="T_e59d7_row111_col1" class="data row111 col1" >0.98</td>
                        <td id="T_e59d7_row111_col2" class="data row111 col2" >1.81</td>
                        <td id="T_e59d7_row111_col3" class="data row111 col3" >16.16</td>
                        <td id="T_e59d7_row111_col4" class="data row111 col4" >32.94</td>
                        <td id="T_e59d7_row111_col5" class="data row111 col5" >26.03</td>
                        <td id="T_e59d7_row111_col6" class="data row111 col6" >9.59</td>
                        <td id="T_e59d7_row111_col7" class="data row111 col7" >40.52</td>
                        <td id="T_e59d7_row111_col8" class="data row111 col8" >50.51</td>
                        <td id="T_e59d7_row111_col9" class="data row111 col9" >32.11</td>
                        <td id="T_e59d7_row111_col10" class="data row111 col10" >14.58</td>
                        <td id="T_e59d7_row111_col11" class="data row111 col11" >27.38</td>
                        <td id="T_e59d7_row111_col12" class="data row111 col12" >31.57</td>
                        <td id="T_e59d7_row111_col13" class="data row111 col13" >United States</td>
                        <td id="T_e59d7_row111_col14" class="data row111 col14" >0.00</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row112" class="row_heading level0 row112" >SLP</th>
                        <td id="T_e59d7_row112_col0" class="data row112 col0" >7.35</td>
                        <td id="T_e59d7_row112_col1" class="data row112 col1" >25.28</td>
                        <td id="T_e59d7_row112_col2" class="data row112 col2" >8.28</td>
                        <td id="T_e59d7_row112_col3" class="data row112 col3" >19.79</td>
                        <td id="T_e59d7_row112_col4" class="data row112 col4" >25.45</td>
                        <td id="T_e59d7_row112_col5" class="data row112 col5" >19.95</td>
                        <td id="T_e59d7_row112_col6" class="data row112 col6" >4.72</td>
                        <td id="T_e59d7_row112_col7" class="data row112 col7" >19.72</td>
                        <td id="T_e59d7_row112_col8" class="data row112 col8" >30.67</td>
                        <td id="T_e59d7_row112_col9" class="data row112 col9" >18.35</td>
                        <td id="T_e59d7_row112_col10" class="data row112 col10" >22.57</td>
                        <td id="T_e59d7_row112_col11" class="data row112 col11" >0.19</td>
                        <td id="T_e59d7_row112_col12" class="data row112 col12" >0.17</td>
                        <td id="T_e59d7_row112_col13" class="data row112 col13" >United States</td>
                        <td id="T_e59d7_row112_col14" class="data row112 col14" >1.03</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row113" class="row_heading level0 row113" >SPGI</th>
                        <td id="T_e59d7_row113_col0" class="data row113 col0" >73.26</td>
                        <td id="T_e59d7_row113_col1" class="data row113 col1" >21.41</td>
                        <td id="T_e59d7_row113_col2" class="data row113 col2" >733.79</td>
                        <td id="T_e59d7_row113_col3" class="data row113 col3" >356.38</td>
                        <td id="T_e59d7_row113_col4" class="data row113 col4" >29.77</td>
                        <td id="T_e59d7_row113_col5" class="data row113 col5" >7.12</td>
                        <td id="T_e59d7_row113_col6" class="data row113 col6" >3.94</td>
                        <td id="T_e59d7_row113_col7" class="data row113 col7" >16.49</td>
                        <td id="T_e59d7_row113_col8" class="data row113 col8" >12.49</td>
                        <td id="T_e59d7_row113_col9" class="data row113 col9" >23.55</td>
                        <td id="T_e59d7_row113_col10" class="data row113 col10" >17.93</td>
                        <td id="T_e59d7_row113_col11" class="data row113 col11" >57.43</td>
                        <td id="T_e59d7_row113_col12" class="data row113 col12" >38.52</td>
                        <td id="T_e59d7_row113_col13" class="data row113 col13" >United States</td>
                        <td id="T_e59d7_row113_col14" class="data row113 col14" >91.50</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row114" class="row_heading level0 row114" >STMP</th>
                        <td id="T_e59d7_row114_col0" class="data row114 col0" >24.91</td>
                        <td id="T_e59d7_row114_col1" class="data row114 col1" >9.41</td>
                        <td id="T_e59d7_row114_col2" class="data row114 col2" >39.91</td>
                        <td id="T_e59d7_row114_col3" class="data row114 col3" >21.24</td>
                        <td id="T_e59d7_row114_col4" class="data row114 col4" >23.70</td>
                        <td id="T_e59d7_row114_col5" class="data row114 col5" >18.40</td>
                        <td id="T_e59d7_row114_col6" class="data row114 col6" >18.53</td>
                        <td id="T_e59d7_row114_col7" class="data row114 col7" >49.58</td>
                        <td id="T_e59d7_row114_col8" class="data row114 col8" >137.19</td>
                        <td id="T_e59d7_row114_col9" class="data row114 col9" >24.37</td>
                        <td id="T_e59d7_row114_col10" class="data row114 col10" >67.62</td>
                        <td id="T_e59d7_row114_col11" class="data row114 col11" >4.93</td>
                        <td id="T_e59d7_row114_col12" class="data row114 col12" >5.52</td>
                        <td id="T_e59d7_row114_col13" class="data row114 col13" >United States</td>
                        <td id="T_e59d7_row114_col14" class="data row114 col14" >3.49</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row115" class="row_heading level0 row115" >STZ</th>
                        <td id="T_e59d7_row115_col0" class="data row115 col0" >48.61</td>
                        <td id="T_e59d7_row115_col1" class="data row115 col1" >12.64</td>
                        <td id="T_e59d7_row115_col2" class="data row115 col2" >57.31</td>
                        <td id="T_e59d7_row115_col3" class="data row115 col3" >17.71</td>
                        <td id="T_e59d7_row115_col4" class="data row115 col4" >23.94</td>
                        <td id="T_e59d7_row115_col5" class="data row115 col5" >4.37</td>
                        <td id="T_e59d7_row115_col6" class="data row115 col6" >2.34</td>
                        <td id="T_e59d7_row115_col7" class="data row115 col7" >-5694.46</td>
                        <td id="T_e59d7_row115_col8" class="data row115 col8" >9819.06</td>
                        <td id="T_e59d7_row115_col9" class="data row115 col9" >32.08</td>
                        <td id="T_e59d7_row115_col10" class="data row115 col10" >24.67</td>
                        <td id="T_e59d7_row115_col11" class="data row115 col11" >41.66</td>
                        <td id="T_e59d7_row115_col12" class="data row115 col12" >-3640116.38</td>
                        <td id="T_e59d7_row115_col13" class="data row115 col13" >United States</td>
                        <td id="T_e59d7_row115_col14" class="data row115 col14" >46.43</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row116" class="row_heading level0 row116" >SUPN</th>
                        <td id="T_e59d7_row116_col0" class="data row116 col0" >50.48</td>
                        <td id="T_e59d7_row116_col1" class="data row116 col1" >27.07</td>
                        <td id="T_e59d7_row116_col2" class="data row116 col2" >10.46</td>
                        <td id="T_e59d7_row116_col3" class="data row116 col3" >20.49</td>
                        <td id="T_e59d7_row116_col4" class="data row116 col4" >24.82</td>
                        <td id="T_e59d7_row116_col5" class="data row116 col5" >21.28</td>
                        <td id="T_e59d7_row116_col6" class="data row116 col6" >21.89</td>
                        <td id="T_e59d7_row116_col7" class="data row116 col7" >35.97</td>
                        <td id="T_e59d7_row116_col8" class="data row116 col8" >50.32</td>
                        <td id="T_e59d7_row116_col9" class="data row116 col9" >6.49</td>
                        <td id="T_e59d7_row116_col10" class="data row116 col10" >9.23</td>
                        <td id="T_e59d7_row116_col11" class="data row116 col11" >1.95</td>
                        <td id="T_e59d7_row116_col12" class="data row116 col12" >3.08</td>
                        <td id="T_e59d7_row116_col13" class="data row116 col13" >United States</td>
                        <td id="T_e59d7_row116_col14" class="data row116 col14" >1.56</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row117" class="row_heading level0 row117" >TECTP</th>
                        <td id="T_e59d7_row117_col0" class="data row117 col0" >88.31</td>
                        <td id="T_e59d7_row117_col1" class="data row117 col1" >0.09</td>
                        <td id="T_e59d7_row117_col2" class="data row117 col2" >17.88</td>
                        <td id="T_e59d7_row117_col3" class="data row117 col3" >17.81</td>
                        <td id="T_e59d7_row117_col4" class="data row117 col4" >21.03</td>
                        <td id="T_e59d7_row117_col5" class="data row117 col5" >34.30</td>
                        <td id="T_e59d7_row117_col6" class="data row117 col6" >31.18</td>
                        <td id="T_e59d7_row117_col7" class="data row117 col7" >82.89</td>
                        <td id="T_e59d7_row117_col8" class="data row117 col8" >128.92</td>
                        <td id="T_e59d7_row117_col9" class="data row117 col9" >19.48</td>
                        <td id="T_e59d7_row117_col10" class="data row117 col10" >25.82</td>
                        <td id="T_e59d7_row117_col11" class="data row117 col11" >-0.33</td>
                        <td id="T_e59d7_row117_col12" class="data row117 col12" >0.56</td>
                        <td id="T_e59d7_row117_col13" class="data row117 col13" >United States</td>
                        <td id="T_e59d7_row117_col14" class="data row117 col14" >0.00</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row118" class="row_heading level0 row118" >TGS</th>
                        <td id="T_e59d7_row118_col0" class="data row118 col0" >48.66</td>
                        <td id="T_e59d7_row118_col1" class="data row118 col1" >12.58</td>
                        <td id="T_e59d7_row118_col2" class="data row118 col2" >0.00</td>
                        <td id="T_e59d7_row118_col3" class="data row118 col3" >25.87</td>
                        <td id="T_e59d7_row118_col4" class="data row118 col4" >23.65</td>
                        <td id="T_e59d7_row118_col5" class="data row118 col5" >27.13</td>
                        <td id="T_e59d7_row118_col6" class="data row118 col6" >43.11</td>
                        <td id="T_e59d7_row118_col7" class="data row118 col7" >5.54</td>
                        <td id="T_e59d7_row118_col8" class="data row118 col8" >89.99</td>
                        <td id="T_e59d7_row118_col9" class="data row118 col9" >-281.03</td>
                        <td id="T_e59d7_row118_col10" class="data row118 col10" >395.43</td>
                        <td id="T_e59d7_row118_col11" class="data row118 col11" >-473.38</td>
                        <td id="T_e59d7_row118_col12" class="data row118 col12" >173.89</td>
                        <td id="T_e59d7_row118_col13" class="data row118 col13" >Argentina</td>
                        <td id="T_e59d7_row118_col14" class="data row118 col14" >0.76</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row119" class="row_heading level0 row119" >TIRX</th>
                        <td id="T_e59d7_row119_col0" class="data row119 col0" >14.13</td>
                        <td id="T_e59d7_row119_col1" class="data row119 col1" >38.38</td>
                        <td id="T_e59d7_row119_col2" class="data row119 col2" >0.00</td>
                        <td id="T_e59d7_row119_col3" class="data row119 col3" >39.69</td>
                        <td id="T_e59d7_row119_col4" class="data row119 col4" >31.88</td>
                        <td id="T_e59d7_row119_col5" class="data row119 col5" >42.93</td>
                        <td id="T_e59d7_row119_col6" class="data row119 col6" >70.43</td>
                        <td id="T_e59d7_row119_col7" class="data row119 col7" >64.27</td>
                        <td id="T_e59d7_row119_col8" class="data row119 col8" >177.43</td>
                        <td id="T_e59d7_row119_col9" class="data row119 col9" >-9.63</td>
                        <td id="T_e59d7_row119_col10" class="data row119 col10" >164.56</td>
                        <td id="T_e59d7_row119_col11" class="data row119 col11" >0.00</td>
                        <td id="T_e59d7_row119_col12" class="data row119 col12" >0.04</td>
                        <td id="T_e59d7_row119_col13" class="data row119 col13" >China</td>
                        <td id="T_e59d7_row119_col14" class="data row119 col14" >0.08</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row120" class="row_heading level0 row120" >TPL</th>
                        <td id="T_e59d7_row120_col0" class="data row120 col0" >15.12</td>
                        <td id="T_e59d7_row120_col1" class="data row120 col1" >15.95</td>
                        <td id="T_e59d7_row120_col2" class="data row120 col2" >0.00</td>
                        <td id="T_e59d7_row120_col3" class="data row120 col3" >69.19</td>
                        <td id="T_e59d7_row120_col4" class="data row120 col4" >64.09</td>
                        <td id="T_e59d7_row120_col5" class="data row120 col5" >39.88</td>
                        <td id="T_e59d7_row120_col6" class="data row120 col6" >69.48</td>
                        <td id="T_e59d7_row120_col7" class="data row120 col7" >40.97</td>
                        <td id="T_e59d7_row120_col8" class="data row120 col8" >80.80</td>
                        <td id="T_e59d7_row120_col9" class="data row120 col9" >57.34</td>
                        <td id="T_e59d7_row120_col10" class="data row120 col10" >80.25</td>
                        <td id="T_e59d7_row120_col11" class="data row120 col11" >8.43</td>
                        <td id="T_e59d7_row120_col12" class="data row120 col12" >6.70</td>
                        <td id="T_e59d7_row120_col13" class="data row120 col13" >United States</td>
                        <td id="T_e59d7_row120_col14" class="data row120 col14" >11.56</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row121" class="row_heading level0 row121" >TRI</th>
                        <td id="T_e59d7_row121_col0" class="data row121 col0" >44.19</td>
                        <td id="T_e59d7_row121_col1" class="data row121 col1" >20.32</td>
                        <td id="T_e59d7_row121_col2" class="data row121 col2" >60.55</td>
                        <td id="T_e59d7_row121_col3" class="data row121 col3" >20.47</td>
                        <td id="T_e59d7_row121_col4" class="data row121 col4" >35.77</td>
                        <td id="T_e59d7_row121_col5" class="data row121 col5" >4.18</td>
                        <td id="T_e59d7_row121_col6" class="data row121 col6" >3.03</td>
                        <td id="T_e59d7_row121_col7" class="data row121 col7" >31.15</td>
                        <td id="T_e59d7_row121_col8" class="data row121 col8" >131.56</td>
                        <td id="T_e59d7_row121_col9" class="data row121 col9" >147.21</td>
                        <td id="T_e59d7_row121_col10" class="data row121 col10" >334.19</td>
                        <td id="T_e59d7_row121_col11" class="data row121 col11" >189.54</td>
                        <td id="T_e59d7_row121_col12" class="data row121 col12" >54.54</td>
                        <td id="T_e59d7_row121_col13" class="data row121 col13" >United States</td>
                        <td id="T_e59d7_row121_col14" class="data row121 col14" >49.00</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row122" class="row_heading level0 row122" >TROW</th>
                        <td id="T_e59d7_row122_col0" class="data row122 col0" >13.04</td>
                        <td id="T_e59d7_row122_col1" class="data row122 col1" >14.31</td>
                        <td id="T_e59d7_row122_col2" class="data row122 col2" >8.64</td>
                        <td id="T_e59d7_row122_col3" class="data row122 col3" >29.13</td>
                        <td id="T_e59d7_row122_col4" class="data row122 col4" >35.30</td>
                        <td id="T_e59d7_row122_col5" class="data row122 col5" >8.57</td>
                        <td id="T_e59d7_row122_col6" class="data row122 col6" >3.47</td>
                        <td id="T_e59d7_row122_col7" class="data row122 col7" >16.67</td>
                        <td id="T_e59d7_row122_col8" class="data row122 col8" >5.71</td>
                        <td id="T_e59d7_row122_col9" class="data row122 col9" >1088.12</td>
                        <td id="T_e59d7_row122_col10" class="data row122 col10" >1867.35</td>
                        <td id="T_e59d7_row122_col11" class="data row122 col11" >20579.20</td>
                        <td id="T_e59d7_row122_col12" class="data row122 col12" >38.30</td>
                        <td id="T_e59d7_row122_col13" class="data row122 col13" >United States</td>
                        <td id="T_e59d7_row122_col14" class="data row122 col14" >43.75</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row123" class="row_heading level0 row123" >TSM</th>
                        <td id="T_e59d7_row123_col0" class="data row123 col0" >32.97</td>
                        <td id="T_e59d7_row123_col1" class="data row123 col1" >10.91</td>
                        <td id="T_e59d7_row123_col2" class="data row123 col2" >0.29</td>
                        <td id="T_e59d7_row123_col3" class="data row123 col3" >23.33</td>
                        <td id="T_e59d7_row123_col4" class="data row123 col4" >35.07</td>
                        <td id="T_e59d7_row123_col5" class="data row123 col5" >11.48</td>
                        <td id="T_e59d7_row123_col6" class="data row123 col6" >11.89</td>
                        <td id="T_e59d7_row123_col7" class="data row123 col7" >16.70</td>
                        <td id="T_e59d7_row123_col8" class="data row123 col8" >28.89</td>
                        <td id="T_e59d7_row123_col9" class="data row123 col9" >21.73</td>
                        <td id="T_e59d7_row123_col10" class="data row123 col10" >74.11</td>
                        <td id="T_e59d7_row123_col11" class="data row123 col11" >5416.26</td>
                        <td id="T_e59d7_row123_col12" class="data row123 col12" >7625.61</td>
                        <td id="T_e59d7_row123_col13" class="data row123 col13" >Taiwan</td>
                        <td id="T_e59d7_row123_col14" class="data row123 col14" >616.88</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row124" class="row_heading level0 row124" >TXN</th>
                        <td id="T_e59d7_row124_col0" class="data row124 col0" >52.52</td>
                        <td id="T_e59d7_row124_col1" class="data row124 col1" >9.78</td>
                        <td id="T_e59d7_row124_col2" class="data row124 col2" >47.48</td>
                        <td id="T_e59d7_row124_col3" class="data row124 col3" >53.72</td>
                        <td id="T_e59d7_row124_col4" class="data row124 col4" >33.38</td>
                        <td id="T_e59d7_row124_col5" class="data row124 col5" >-0.94</td>
                        <td id="T_e59d7_row124_col6" class="data row124 col6" >7.30</td>
                        <td id="T_e59d7_row124_col7" class="data row124 col7" >17.66</td>
                        <td id="T_e59d7_row124_col8" class="data row124 col8" >31.27</td>
                        <td id="T_e59d7_row124_col9" class="data row124 col9" >6.72</td>
                        <td id="T_e59d7_row124_col10" class="data row124 col10" >19.97</td>
                        <td id="T_e59d7_row124_col11" class="data row124 col11" >83.81</td>
                        <td id="T_e59d7_row124_col12" class="data row124 col12" >99.46</td>
                        <td id="T_e59d7_row124_col13" class="data row124 col13" >United States</td>
                        <td id="T_e59d7_row124_col14" class="data row124 col14" >176.16</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row125" class="row_heading level0 row125" >V</th>
                        <td id="T_e59d7_row125_col0" class="data row125 col0" >55.25</td>
                        <td id="T_e59d7_row125_col1" class="data row125 col1" >13.62</td>
                        <td id="T_e59d7_row125_col2" class="data row125 col2" >51.12</td>
                        <td id="T_e59d7_row125_col3" class="data row125 col3" >34.24</td>
                        <td id="T_e59d7_row125_col4" class="data row125 col4" >47.20</td>
                        <td id="T_e59d7_row125_col5" class="data row125 col5" >6.28</td>
                        <td id="T_e59d7_row125_col6" class="data row125 col6" >9.71</td>
                        <td id="T_e59d7_row125_col7" class="data row125 col7" >20.33</td>
                        <td id="T_e59d7_row125_col8" class="data row125 col8" >32.02</td>
                        <td id="T_e59d7_row125_col9" class="data row125 col9" >7.02</td>
                        <td id="T_e59d7_row125_col10" class="data row125 col10" >31.54</td>
                        <td id="T_e59d7_row125_col11" class="data row125 col11" >163.26</td>
                        <td id="T_e59d7_row125_col12" class="data row125 col12" >212.98</td>
                        <td id="T_e59d7_row125_col13" class="data row125 col13" >United States</td>
                        <td id="T_e59d7_row125_col14" class="data row125 col14" >489.82</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row126" class="row_heading level0 row126" >VALU</th>
                        <td id="T_e59d7_row126_col0" class="data row126 col0" >51.21</td>
                        <td id="T_e59d7_row126_col1" class="data row126 col1" >12.52</td>
                        <td id="T_e59d7_row126_col2" class="data row126 col2" >0.00</td>
                        <td id="T_e59d7_row126_col3" class="data row126 col3" >28.49</td>
                        <td id="T_e59d7_row126_col4" class="data row126 col4" >35.17</td>
                        <td id="T_e59d7_row126_col5" class="data row126 col5" >5.33</td>
                        <td id="T_e59d7_row126_col6" class="data row126 col6" >5.22</td>
                        <td id="T_e59d7_row126_col7" class="data row126 col7" >19.43</td>
                        <td id="T_e59d7_row126_col8" class="data row126 col8" >37.92</td>
                        <td id="T_e59d7_row126_col9" class="data row126 col9" >94.91</td>
                        <td id="T_e59d7_row126_col10" class="data row126 col10" >129.26</td>
                        <td id="T_e59d7_row126_col11" class="data row126 col11" >0.80</td>
                        <td id="T_e59d7_row126_col12" class="data row126 col12" >0.27</td>
                        <td id="T_e59d7_row126_col13" class="data row126 col13" >United States</td>
                        <td id="T_e59d7_row126_col14" class="data row126 col14" >0.30</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row127" class="row_heading level0 row127" >VEEV</th>
                        <td id="T_e59d7_row127_col0" class="data row127 col0" >25.60</td>
                        <td id="T_e59d7_row127_col1" class="data row127 col1" >41.74</td>
                        <td id="T_e59d7_row127_col2" class="data row127 col2" >19.24</td>
                        <td id="T_e59d7_row127_col3" class="data row127 col3" >17.52</td>
                        <td id="T_e59d7_row127_col4" class="data row127 col4" >25.44</td>
                        <td id="T_e59d7_row127_col5" class="data row127 col5" >28.54</td>
                        <td id="T_e59d7_row127_col6" class="data row127 col6" >3.94</td>
                        <td id="T_e59d7_row127_col7" class="data row127 col7" >36.41</td>
                        <td id="T_e59d7_row127_col8" class="data row127 col8" >13.74</td>
                        <td id="T_e59d7_row127_col9" class="data row127 col9" >34.55</td>
                        <td id="T_e59d7_row127_col10" class="data row127 col10" >9.29</td>
                        <td id="T_e59d7_row127_col11" class="data row127 col11" >10.98</td>
                        <td id="T_e59d7_row127_col12" class="data row127 col12" >8.09</td>
                        <td id="T_e59d7_row127_col13" class="data row127 col13" >0</td>
                        <td id="T_e59d7_row127_col14" class="data row127 col14" >44.37</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row128" class="row_heading level0 row128" >VMW</th>
                        <td id="T_e59d7_row128_col0" class="data row128 col0" >68.81</td>
                        <td id="T_e59d7_row128_col1" class="data row128 col1" >28.98</td>
                        <td id="T_e59d7_row128_col2" class="data row128 col2" >106.05</td>
                        <td id="T_e59d7_row128_col3" class="data row128 col3" >51.94</td>
                        <td id="T_e59d7_row128_col4" class="data row128 col4" >24.80</td>
                        <td id="T_e59d7_row128_col5" class="data row128 col5" >12.21</td>
                        <td id="T_e59d7_row128_col6" class="data row128 col6" >3.25</td>
                        <td id="T_e59d7_row128_col7" class="data row128 col7" >166.09</td>
                        <td id="T_e59d7_row128_col8" class="data row128 col8" >202.72</td>
                        <td id="T_e59d7_row128_col9" class="data row128 col9" >13.20</td>
                        <td id="T_e59d7_row128_col10" class="data row128 col10" >7.44</td>
                        <td id="T_e59d7_row128_col11" class="data row128 col11" >62.40</td>
                        <td id="T_e59d7_row128_col12" class="data row128 col12" >560.38</td>
                        <td id="T_e59d7_row128_col13" class="data row128 col13" >United States</td>
                        <td id="T_e59d7_row128_col14" class="data row128 col14" >66.89</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row129" class="row_heading level0 row129" >VNO</th>
                        <td id="T_e59d7_row129_col0" class="data row129 col0" >53.43</td>
                        <td id="T_e59d7_row129_col1" class="data row129 col1" >46.63</td>
                        <td id="T_e59d7_row129_col2" class="data row129 col2" >0.00</td>
                        <td id="T_e59d7_row129_col3" class="data row129 col3" >16.88</td>
                        <td id="T_e59d7_row129_col4" class="data row129 col4" >42.56</td>
                        <td id="T_e59d7_row129_col5" class="data row129 col5" >-7.89</td>
                        <td id="T_e59d7_row129_col6" class="data row129 col6" >11.60</td>
                        <td id="T_e59d7_row129_col7" class="data row129 col7" >196.01</td>
                        <td id="T_e59d7_row129_col8" class="data row129 col8" >364.57</td>
                        <td id="T_e59d7_row129_col9" class="data row129 col9" >0.00</td>
                        <td id="T_e59d7_row129_col10" class="data row129 col10" >0.00</td>
                        <td id="T_e59d7_row129_col11" class="data row129 col11" >0.00</td>
                        <td id="T_e59d7_row129_col12" class="data row129 col12" >256.40</td>
                        <td id="T_e59d7_row129_col13" class="data row129 col13" >United States</td>
                        <td id="T_e59d7_row129_col14" class="data row129 col14" >9.48</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row130" class="row_heading level0 row130" >VRTX</th>
                        <td id="T_e59d7_row130_col0" class="data row130 col0" >26.08</td>
                        <td id="T_e59d7_row130_col1" class="data row130 col1" >14.27</td>
                        <td id="T_e59d7_row130_col2" class="data row130 col2" >11.54</td>
                        <td id="T_e59d7_row130_col3" class="data row130 col3" >27.71</td>
                        <td id="T_e59d7_row130_col4" class="data row130 col4" >37.84</td>
                        <td id="T_e59d7_row130_col5" class="data row130 col5" >36.04</td>
                        <td id="T_e59d7_row130_col6" class="data row130 col6" >13.32</td>
                        <td id="T_e59d7_row130_col7" class="data row130 col7" >260.79</td>
                        <td id="T_e59d7_row130_col8" class="data row130 col8" >386.71</td>
                        <td id="T_e59d7_row130_col9" class="data row130 col9" >61.71</td>
                        <td id="T_e59d7_row130_col10" class="data row130 col10" >36.80</td>
                        <td id="T_e59d7_row130_col11" class="data row130 col11" >79.50</td>
                        <td id="T_e59d7_row130_col12" class="data row130 col12" >815.40</td>
                        <td id="T_e59d7_row130_col13" class="data row130 col13" >United States</td>
                        <td id="T_e59d7_row130_col14" class="data row130 col14" >54.46</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row131" class="row_heading level0 row131" >WAL</th>
                        <td id="T_e59d7_row131_col0" class="data row131 col0" >90.64</td>
                        <td id="T_e59d7_row131_col1" class="data row131 col1" >0.14</td>
                        <td id="T_e59d7_row131_col2" class="data row131 col2" >8.49</td>
                        <td id="T_e59d7_row131_col3" class="data row131 col3" >15.67</td>
                        <td id="T_e59d7_row131_col4" class="data row131 col4" >44.53</td>
                        <td id="T_e59d7_row131_col5" class="data row131 col5" >11.26</td>
                        <td id="T_e59d7_row131_col6" class="data row131 col6" >7.56</td>
                        <td id="T_e59d7_row131_col7" class="data row131 col7" >16.64</td>
                        <td id="T_e59d7_row131_col8" class="data row131 col8" >16.30</td>
                        <td id="T_e59d7_row131_col9" class="data row131 col9" >21.57</td>
                        <td id="T_e59d7_row131_col10" class="data row131 col10" >25.28</td>
                        <td id="T_e59d7_row131_col11" class="data row131 col11" >12.30</td>
                        <td id="T_e59d7_row131_col12" class="data row131 col12" >8.63</td>
                        <td id="T_e59d7_row131_col13" class="data row131 col13" >United States</td>
                        <td id="T_e59d7_row131_col14" class="data row131 col14" >10.59</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row132" class="row_heading level0 row132" >WD</th>
                        <td id="T_e59d7_row132_col0" class="data row132 col0" >74.28</td>
                        <td id="T_e59d7_row132_col1" class="data row132 col1" >41.07</td>
                        <td id="T_e59d7_row132_col2" class="data row132 col2" >20.81</td>
                        <td id="T_e59d7_row132_col3" class="data row132 col3" >20.32</td>
                        <td id="T_e59d7_row132_col4" class="data row132 col4" >24.54</td>
                        <td id="T_e59d7_row132_col5" class="data row132 col5" >14.50</td>
                        <td id="T_e59d7_row132_col6" class="data row132 col6" >14.62</td>
                        <td id="T_e59d7_row132_col7" class="data row132 col7" >8.62</td>
                        <td id="T_e59d7_row132_col8" class="data row132 col8" >32.78</td>
                        <td id="T_e59d7_row132_col9" class="data row132 col9" >27.84</td>
                        <td id="T_e59d7_row132_col10" class="data row132 col10" >534.05</td>
                        <td id="T_e59d7_row132_col11" class="data row132 col11" >0.82</td>
                        <td id="T_e59d7_row132_col12" class="data row132 col12" >3.17</td>
                        <td id="T_e59d7_row132_col13" class="data row132 col13" >United States</td>
                        <td id="T_e59d7_row132_col14" class="data row132 col14" >3.17</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row133" class="row_heading level0 row133" >WIMI</th>
                        <td id="T_e59d7_row133_col0" class="data row133 col0" >13.93</td>
                        <td id="T_e59d7_row133_col1" class="data row133 col1" >22.53</td>
                        <td id="T_e59d7_row133_col2" class="data row133 col2" >39.73</td>
                        <td id="T_e59d7_row133_col3" class="data row133 col3" >29.57</td>
                        <td id="T_e59d7_row133_col4" class="data row133 col4" >22.52</td>
                        <td id="T_e59d7_row133_col5" class="data row133 col5" >66.33</td>
                        <td id="T_e59d7_row133_col6" class="data row133 col6" >64.95</td>
                        <td id="T_e59d7_row133_col7" class="data row133 col7" >-70.57</td>
                        <td id="T_e59d7_row133_col8" class="data row133 col8" >153.62</td>
                        <td id="T_e59d7_row133_col9" class="data row133 col9" >-36.20</td>
                        <td id="T_e59d7_row133_col10" class="data row133 col10" >99.21</td>
                        <td id="T_e59d7_row133_col11" class="data row133 col11" >0.27</td>
                        <td id="T_e59d7_row133_col12" class="data row133 col12" >0.02</td>
                        <td id="T_e59d7_row133_col13" class="data row133 col13" >China</td>
                        <td id="T_e59d7_row133_col14" class="data row133 col14" >0.47</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row134" class="row_heading level0 row134" >XLNX</th>
                        <td id="T_e59d7_row134_col0" class="data row134 col0" >50.67</td>
                        <td id="T_e59d7_row134_col1" class="data row134 col1" >8.63</td>
                        <td id="T_e59d7_row134_col2" class="data row134 col2" >26.75</td>
                        <td id="T_e59d7_row134_col3" class="data row134 col3" >27.51</td>
                        <td id="T_e59d7_row134_col4" class="data row134 col4" >24.90</td>
                        <td id="T_e59d7_row134_col5" class="data row134 col5" >10.69</td>
                        <td id="T_e59d7_row134_col6" class="data row134 col6" >11.54</td>
                        <td id="T_e59d7_row134_col7" class="data row134 col7" >18.24</td>
                        <td id="T_e59d7_row134_col8" class="data row134 col8" >64.13</td>
                        <td id="T_e59d7_row134_col9" class="data row134 col9" >8.46</td>
                        <td id="T_e59d7_row134_col10" class="data row134 col10" >20.52</td>
                        <td id="T_e59d7_row134_col11" class="data row134 col11" >14.72</td>
                        <td id="T_e59d7_row134_col12" class="data row134 col12" >14.08</td>
                        <td id="T_e59d7_row134_col13" class="data row134 col13" >United States</td>
                        <td id="T_e59d7_row134_col14" class="data row134 col14" >31.75</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row135" class="row_heading level0 row135" >YY</th>
                        <td id="T_e59d7_row135_col0" class="data row135 col0" >22.90</td>
                        <td id="T_e59d7_row135_col1" class="data row135 col1" >7.09</td>
                        <td id="T_e59d7_row135_col2" class="data row135 col2" >30.02</td>
                        <td id="T_e59d7_row135_col3" class="data row135 col3" >16.55</td>
                        <td id="T_e59d7_row135_col4" class="data row135 col4" >29.44</td>
                        <td id="T_e59d7_row135_col5" class="data row135 col5" >16.64</td>
                        <td id="T_e59d7_row135_col6" class="data row135 col6" >57.73</td>
                        <td id="T_e59d7_row135_col7" class="data row135 col7" >85.34</td>
                        <td id="T_e59d7_row135_col8" class="data row135 col8" >110.67</td>
                        <td id="T_e59d7_row135_col9" class="data row135 col9" >3.79</td>
                        <td id="T_e59d7_row135_col10" class="data row135 col10" >18.97</td>
                        <td id="T_e59d7_row135_col11" class="data row135 col11" >51.88</td>
                        <td id="T_e59d7_row135_col12" class="data row135 col12" >315.35</td>
                        <td id="T_e59d7_row135_col13" class="data row135 col13" >China</td>
                        <td id="T_e59d7_row135_col14" class="data row135 col14" >5.86</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row136" class="row_heading level0 row136" >ZTS</th>
                        <td id="T_e59d7_row136_col0" class="data row136 col0" >72.28</td>
                        <td id="T_e59d7_row136_col1" class="data row136 col1" >15.18</td>
                        <td id="T_e59d7_row136_col2" class="data row136 col2" >71.48</td>
                        <td id="T_e59d7_row136_col3" class="data row136 col3" >53.25</td>
                        <td id="T_e59d7_row136_col4" class="data row136 col4" >22.32</td>
                        <td id="T_e59d7_row136_col5" class="data row136 col5" >7.95</td>
                        <td id="T_e59d7_row136_col6" class="data row136 col6" >1.62</td>
                        <td id="T_e59d7_row136_col7" class="data row136 col7" >26.51</td>
                        <td id="T_e59d7_row136_col8" class="data row136 col8" >33.64</td>
                        <td id="T_e59d7_row136_col9" class="data row136 col9" >15.56</td>
                        <td id="T_e59d7_row136_col10" class="data row136 col10" >20.55</td>
                        <td id="T_e59d7_row136_col11" class="data row136 col11" >26.55</td>
                        <td id="T_e59d7_row136_col12" class="data row136 col12" >33.36</td>
                        <td id="T_e59d7_row136_col13" class="data row136 col13" >United States</td>
                        <td id="T_e59d7_row136_col14" class="data row136 col14" >82.11</td>
            </tr>
            <tr>
                        <th id="T_e59d7_level0_row137" class="row_heading level0 row137" >ZYXI</th>
                        <td id="T_e59d7_row137_col0" class="data row137 col0" >21.23</td>
                        <td id="T_e59d7_row137_col1" class="data row137 col1" >17.27</td>
                        <td id="T_e59d7_row137_col2" class="data row137 col2" >0.00</td>
                        <td id="T_e59d7_row137_col3" class="data row137 col3" >78.36</td>
                        <td id="T_e59d7_row137_col4" class="data row137 col4" >23.39</td>
                        <td id="T_e59d7_row137_col5" class="data row137 col5" >51.63</td>
                        <td id="T_e59d7_row137_col6" class="data row137 col6" >21.51</td>
                        <td id="T_e59d7_row137_col7" class="data row137 col7" >8.22</td>
                        <td id="T_e59d7_row137_col8" class="data row137 col8" >18.69</td>
                        <td id="T_e59d7_row137_col9" class="data row137 col9" >-42.36</td>
                        <td id="T_e59d7_row137_col10" class="data row137 col10" >54.13</td>
                        <td id="T_e59d7_row137_col11" class="data row137 col11" >0.02</td>
                        <td id="T_e59d7_row137_col12" class="data row137 col12" >0.14</td>
                        <td id="T_e59d7_row137_col13" class="data row137 col13" >United States</td>
                        <td id="T_e59d7_row137_col14" class="data row137 col14" >0.53</td>
            </tr>
    </tbody></table>



### 观察列表




<style  type="text/css" >
#T_baa6f_row0_col0,#T_baa6f_row0_col1,#T_baa6f_row0_col2,#T_baa6f_row0_col3,#T_baa6f_row0_col4,#T_baa6f_row0_col5,#T_baa6f_row0_col6,#T_baa6f_row0_col7,#T_baa6f_row0_col8,#T_baa6f_row0_col9,#T_baa6f_row0_col10,#T_baa6f_row0_col11,#T_baa6f_row0_col12,#T_baa6f_row0_col13,#T_baa6f_row0_col14,#T_baa6f_row1_col0,#T_baa6f_row1_col1,#T_baa6f_row1_col2,#T_baa6f_row1_col3,#T_baa6f_row1_col4,#T_baa6f_row1_col5,#T_baa6f_row1_col6,#T_baa6f_row1_col7,#T_baa6f_row1_col8,#T_baa6f_row1_col9,#T_baa6f_row1_col10,#T_baa6f_row1_col11,#T_baa6f_row1_col12,#T_baa6f_row1_col13,#T_baa6f_row1_col14,#T_baa6f_row2_col0,#T_baa6f_row2_col1,#T_baa6f_row2_col2,#T_baa6f_row2_col3,#T_baa6f_row2_col4,#T_baa6f_row2_col5,#T_baa6f_row2_col6,#T_baa6f_row2_col7,#T_baa6f_row2_col8,#T_baa6f_row2_col9,#T_baa6f_row2_col10,#T_baa6f_row2_col11,#T_baa6f_row2_col12,#T_baa6f_row2_col13,#T_baa6f_row2_col14,#T_baa6f_row3_col0,#T_baa6f_row3_col1,#T_baa6f_row3_col2,#T_baa6f_row3_col4,#T_baa6f_row3_col5,#T_baa6f_row3_col6,#T_baa6f_row3_col7,#T_baa6f_row3_col8,#T_baa6f_row3_col9,#T_baa6f_row3_col10,#T_baa6f_row3_col13,#T_baa6f_row3_col14,#T_baa6f_row4_col0,#T_baa6f_row4_col1,#T_baa6f_row4_col2,#T_baa6f_row4_col3,#T_baa6f_row4_col4,#T_baa6f_row4_col5,#T_baa6f_row4_col6,#T_baa6f_row4_col7,#T_baa6f_row4_col8,#T_baa6f_row4_col9,#T_baa6f_row4_col10,#T_baa6f_row4_col11,#T_baa6f_row4_col12,#T_baa6f_row4_col13,#T_baa6f_row4_col14,#T_baa6f_row5_col0,#T_baa6f_row5_col1,#T_baa6f_row5_col2,#T_baa6f_row5_col3,#T_baa6f_row5_col4,#T_baa6f_row5_col5,#T_baa6f_row5_col6,#T_baa6f_row5_col7,#T_baa6f_row5_col8,#T_baa6f_row5_col9,#T_baa6f_row5_col10,#T_baa6f_row5_col11,#T_baa6f_row5_col12,#T_baa6f_row5_col13,#T_baa6f_row5_col14,#T_baa6f_row6_col0,#T_baa6f_row6_col1,#T_baa6f_row6_col2,#T_baa6f_row6_col3,#T_baa6f_row6_col4,#T_baa6f_row6_col5,#T_baa6f_row6_col6,#T_baa6f_row6_col8,#T_baa6f_row6_col10,#T_baa6f_row6_col11,#T_baa6f_row6_col12,#T_baa6f_row6_col13,#T_baa6f_row6_col14,#T_baa6f_row7_col0,#T_baa6f_row7_col1,#T_baa6f_row7_col2,#T_baa6f_row7_col3,#T_baa6f_row7_col4,#T_baa6f_row7_col6,#T_baa6f_row7_col7,#T_baa6f_row7_col8,#T_baa6f_row7_col10,#T_baa6f_row7_col11,#T_baa6f_row7_col12,#T_baa6f_row7_col13,#T_baa6f_row7_col14,#T_baa6f_row8_col0,#T_baa6f_row8_col1,#T_baa6f_row8_col2,#T_baa6f_row8_col5,#T_baa6f_row8_col6,#T_baa6f_row8_col7,#T_baa6f_row8_col8,#T_baa6f_row8_col10,#T_baa6f_row8_col13,#T_baa6f_row8_col14,#T_baa6f_row9_col0,#T_baa6f_row9_col1,#T_baa6f_row9_col2,#T_baa6f_row9_col3,#T_baa6f_row9_col4,#T_baa6f_row9_col5,#T_baa6f_row9_col6,#T_baa6f_row9_col7,#T_baa6f_row9_col8,#T_baa6f_row9_col10,#T_baa6f_row9_col11,#T_baa6f_row9_col12,#T_baa6f_row9_col13,#T_baa6f_row9_col14,#T_baa6f_row10_col0,#T_baa6f_row10_col1,#T_baa6f_row10_col2,#T_baa6f_row10_col3,#T_baa6f_row10_col4,#T_baa6f_row10_col5,#T_baa6f_row10_col6,#T_baa6f_row10_col7,#T_baa6f_row10_col8,#T_baa6f_row10_col9,#T_baa6f_row10_col10,#T_baa6f_row10_col11,#T_baa6f_row10_col12,#T_baa6f_row10_col13,#T_baa6f_row10_col14,#T_baa6f_row11_col0,#T_baa6f_row11_col1,#T_baa6f_row11_col2,#T_baa6f_row11_col3,#T_baa6f_row11_col5,#T_baa6f_row11_col6,#T_baa6f_row11_col8,#T_baa6f_row11_col10,#T_baa6f_row11_col13,#T_baa6f_row11_col14,#T_baa6f_row12_col0,#T_baa6f_row12_col1,#T_baa6f_row12_col2,#T_baa6f_row12_col3,#T_baa6f_row12_col4,#T_baa6f_row12_col5,#T_baa6f_row12_col6,#T_baa6f_row12_col7,#T_baa6f_row12_col8,#T_baa6f_row12_col9,#T_baa6f_row12_col10,#T_baa6f_row12_col11,#T_baa6f_row12_col12,#T_baa6f_row12_col13,#T_baa6f_row12_col14{
            color:  black;
        }#T_baa6f_row3_col3,#T_baa6f_row3_col11,#T_baa6f_row3_col12,#T_baa6f_row6_col7,#T_baa6f_row6_col9,#T_baa6f_row7_col5,#T_baa6f_row7_col9,#T_baa6f_row8_col3,#T_baa6f_row8_col4,#T_baa6f_row8_col9,#T_baa6f_row8_col11,#T_baa6f_row8_col12,#T_baa6f_row9_col9,#T_baa6f_row11_col4,#T_baa6f_row11_col7,#T_baa6f_row11_col9,#T_baa6f_row11_col11,#T_baa6f_row11_col12{
            color:  red;
        }</style><table id="T_baa6f_" ><thead>    <tr>        <th class="blank level0" ></th>        <th class="col_heading level0 col0" >负债率</th>        <th class="col_heading level0 col1" >应收比</th>        <th class="col_heading level0 col2" >商誉比</th>        <th class="col_heading level0 col3" >ROE</th>        <th class="col_heading level0 col4" >利润率</th>        <th class="col_heading level0 col5" >收入增长</th>        <th class="col_heading level0 col6" >收入波动</th>        <th class="col_heading level0 col7" >盈利增长</th>        <th class="col_heading level0 col8" >盈利波动</th>        <th class="col_heading level0 col9" >FCF增长</th>        <th class="col_heading level0 col10" >FCF波动</th>        <th class="col_heading level0 col11" >DCF</th>        <th class="col_heading level0 col12" >盈利折现</th>        <th class="col_heading level0 col13" >国家</th>        <th class="col_heading level0 col14" >市值</th>    </tr>    <tr>        <th class="index_name level0" >Symbol</th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>    </tr></thead><tbody>
                <tr>
                        <th id="T_baa6f_level0_row0" class="row_heading level0 row0" >BABA</th>
                        <td id="T_baa6f_row0_col0" class="data row0 col0" >33.70</td>
                        <td id="T_baa6f_row0_col1" class="data row0 col1" >8.56</td>
                        <td id="T_baa6f_row0_col2" class="data row0 col2" >36.64</td>
                        <td id="T_baa6f_row0_col3" class="data row0 col3" >17.71</td>
                        <td id="T_baa6f_row0_col4" class="data row0 col4" >26.46</td>
                        <td id="T_baa6f_row0_col5" class="data row0 col5" >47.99</td>
                        <td id="T_baa6f_row0_col6" class="data row0 col6" >11.65</td>
                        <td id="T_baa6f_row0_col7" class="data row0 col7" >51.30</td>
                        <td id="T_baa6f_row0_col8" class="data row0 col8" >16.92</td>
                        <td id="T_baa6f_row0_col9" class="data row0 col9" >28.25</td>
                        <td id="T_baa6f_row0_col10" class="data row0 col10" >19.50</td>
                        <td id="T_baa6f_row0_col11" class="data row0 col11" >2820.11</td>
                        <td id="T_baa6f_row0_col12" class="data row0 col12" >3534.63</td>
                        <td id="T_baa6f_row0_col13" class="data row0 col13" >China</td>
                        <td id="T_baa6f_row0_col14" class="data row0 col14" >595.64</td>
            </tr>
            <tr>
                        <th id="T_baa6f_level0_row1" class="row_heading level0 row1" >AAPL</th>
                        <td id="T_baa6f_row1_col0" class="data row1 col0" >79.83</td>
                        <td id="T_baa6f_row1_col1" class="data row1 col1" >13.64</td>
                        <td id="T_baa6f_row1_col2" class="data row1 col2" >0.00</td>
                        <td id="T_baa6f_row1_col3" class="data row1 col3" >60.14</td>
                        <td id="T_baa6f_row1_col4" class="data row1 col4" >21.41</td>
                        <td id="T_baa6f_row1_col5" class="data row1 col5" >6.44</td>
                        <td id="T_baa6f_row1_col6" class="data row1 col6" >8.99</td>
                        <td id="T_baa6f_row1_col7" class="data row1 col7" >6.61</td>
                        <td id="T_baa6f_row1_col8" class="data row1 col8" >15.33</td>
                        <td id="T_baa6f_row1_col9" class="data row1 col9" >13.42</td>
                        <td id="T_baa6f_row1_col10" class="data row1 col10" >18.68</td>
                        <td id="T_baa6f_row1_col11" class="data row1 col11" >1120.12</td>
                        <td id="T_baa6f_row1_col12" class="data row1 col12" >837.11</td>
                        <td id="T_baa6f_row1_col13" class="data row1 col13" >United States</td>
                        <td id="T_baa6f_row1_col14" class="data row1 col14" >2168.21</td>
            </tr>
            <tr>
                        <th id="T_baa6f_level0_row2" class="row_heading level0 row2" >FB</th>
                        <td id="T_baa6f_row2_col0" class="data row2 col0" >19.47</td>
                        <td id="T_baa6f_row2_col1" class="data row2 col1" >13.19</td>
                        <td id="T_baa6f_row2_col2" class="data row2 col2" >14.85</td>
                        <td id="T_baa6f_row2_col3" class="data row2 col3" >22.18</td>
                        <td id="T_baa6f_row2_col4" class="data row2 col4" >34.71</td>
                        <td id="T_baa6f_row2_col5" class="data row2 col5" >28.52</td>
                        <td id="T_baa6f_row2_col6" class="data row2 col6" >8.05</td>
                        <td id="T_baa6f_row2_col7" class="data row2 col7" >26.68</td>
                        <td id="T_baa6f_row2_col8" class="data row2 col8" >38.49</td>
                        <td id="T_baa6f_row2_col9" class="data row2 col9" >12.46</td>
                        <td id="T_baa6f_row2_col10" class="data row2 col10" >25.14</td>
                        <td id="T_baa6f_row2_col11" class="data row2 col11" >342.34</td>
                        <td id="T_baa6f_row2_col12" class="data row2 col12" >528.39</td>
                        <td id="T_baa6f_row2_col13" class="data row2 col13" >United States</td>
                        <td id="T_baa6f_row2_col14" class="data row2 col14" >933.29</td>
            </tr>
            <tr>
                        <th id="T_baa6f_level0_row3" class="row_heading level0 row3" >TLSA</th>
                        <td id="T_baa6f_row3_col0" class="data row3 col0" >331.88</td>
                        <td id="T_baa6f_row3_col1" class="data row3 col1" >0.00</td>
                        <td id="T_baa6f_row3_col2" class="data row3 col2" >0.00</td>
                        <td id="T_baa6f_row3_col3" class="data row3 col3" >-299.85</td>
                        <td id="T_baa6f_row3_col4" class="data row3 col4" >0.00</td>
                        <td id="T_baa6f_row3_col5" class="data row3 col5" >0.00</td>
                        <td id="T_baa6f_row3_col6" class="data row3 col6" >0.00</td>
                        <td id="T_baa6f_row3_col7" class="data row3 col7" >9.68</td>
                        <td id="T_baa6f_row3_col8" class="data row3 col8" >15.05</td>
                        <td id="T_baa6f_row3_col9" class="data row3 col9" >18.40</td>
                        <td id="T_baa6f_row3_col10" class="data row3 col10" >49.60</td>
                        <td id="T_baa6f_row3_col11" class="data row3 col11" >-0.12</td>
                        <td id="T_baa6f_row3_col12" class="data row3 col12" >-0.14</td>
                        <td id="T_baa6f_row3_col13" class="data row3 col13" >United Kingdom</td>
                        <td id="T_baa6f_row3_col14" class="data row3 col14" >0.22</td>
            </tr>
            <tr>
                        <th id="T_baa6f_level0_row4" class="row_heading level0 row4" >JD</th>
                        <td id="T_baa6f_row4_col0" class="data row4 col0" >47.52</td>
                        <td id="T_baa6f_row4_col1" class="data row4 col1" >1.94</td>
                        <td id="T_baa6f_row4_col2" class="data row4 col2" >5.81</td>
                        <td id="T_baa6f_row4_col3" class="data row4 col3" >9.19</td>
                        <td id="T_baa6f_row4_col4" class="data row4 col4" >2.04</td>
                        <td id="T_baa6f_row4_col5" class="data row4 col5" >27.22</td>
                        <td id="T_baa6f_row4_col6" class="data row4 col6" >2.22</td>
                        <td id="T_baa6f_row4_col7" class="data row4 col7" >417.65</td>
                        <td id="T_baa6f_row4_col8" class="data row4 col8" >1067.16</td>
                        <td id="T_baa6f_row4_col9" class="data row4 col9" >117.46</td>
                        <td id="T_baa6f_row4_col10" class="data row4 col10" >215.36</td>
                        <td id="T_baa6f_row4_col11" class="data row4 col11" >2129.83</td>
                        <td id="T_baa6f_row4_col12" class="data row4 col12" >22477.66</td>
                        <td id="T_baa6f_row4_col13" class="data row4 col13" >China</td>
                        <td id="T_baa6f_row4_col14" class="data row4 col14" >119.32</td>
            </tr>
            <tr>
                        <th id="T_baa6f_level0_row5" class="row_heading level0 row5" >NVDA</th>
                        <td id="T_baa6f_row5_col0" class="data row5 col0" >41.33</td>
                        <td id="T_baa6f_row5_col1" class="data row5 col1" >14.57</td>
                        <td id="T_baa6f_row5_col2" class="data row5 col2" >24.82</td>
                        <td id="T_baa6f_row5_col3" class="data row5 col3" >33.42</td>
                        <td id="T_baa6f_row5_col4" class="data row5 col4" >29.58</td>
                        <td id="T_baa6f_row5_col5" class="data row5 col5" >22.18</td>
                        <td id="T_baa6f_row5_col6" class="data row5 col6" >29.80</td>
                        <td id="T_baa6f_row5_col7" class="data row5 col7" >19.45</td>
                        <td id="T_baa6f_row5_col8" class="data row5 col8" >45.97</td>
                        <td id="T_baa6f_row5_col9" class="data row5 col9" >17.95</td>
                        <td id="T_baa6f_row5_col10" class="data row5 col10" >15.59</td>
                        <td id="T_baa6f_row5_col11" class="data row5 col11" >75.68</td>
                        <td id="T_baa6f_row5_col12" class="data row5 col12" >74.77</td>
                        <td id="T_baa6f_row5_col13" class="data row5 col13" >United States</td>
                        <td id="T_baa6f_row5_col14" class="data row5 col14" >418.11</td>
            </tr>
            <tr>
                        <th id="T_baa6f_level0_row6" class="row_heading level0 row6" >SOGO</th>
                        <td id="T_baa6f_row6_col0" class="data row6 col0" >29.89</td>
                        <td id="T_baa6f_row6_col1" class="data row6 col1" >8.24</td>
                        <td id="T_baa6f_row6_col2" class="data row6 col2" >0.67</td>
                        <td id="T_baa6f_row6_col3" class="data row6 col3" >4.04</td>
                        <td id="T_baa6f_row6_col4" class="data row6 col4" >3.43</td>
                        <td id="T_baa6f_row6_col5" class="data row6 col5" >2.30</td>
                        <td id="T_baa6f_row6_col6" class="data row6 col6" >22.50</td>
                        <td id="T_baa6f_row6_col7" class="data row6 col7" >-70.36</td>
                        <td id="T_baa6f_row6_col8" class="data row6 col8" >131.71</td>
                        <td id="T_baa6f_row6_col9" class="data row6 col9" >-4.09</td>
                        <td id="T_baa6f_row6_col10" class="data row6 col10" >162.33</td>
                        <td id="T_baa6f_row6_col11" class="data row6 col11" >0.83</td>
                        <td id="T_baa6f_row6_col12" class="data row6 col12" >0.03</td>
                        <td id="T_baa6f_row6_col13" class="data row6 col13" >United States</td>
                        <td id="T_baa6f_row6_col14" class="data row6 col14" >3.24</td>
            </tr>
            <tr>
                        <th id="T_baa6f_level0_row7" class="row_heading level0 row7" >TCOM</th>
                        <td id="T_baa6f_row7_col0" class="data row7 col0" >45.76</td>
                        <td id="T_baa6f_row7_col1" class="data row7 col1" >48.59</td>
                        <td id="T_baa6f_row7_col2" class="data row7 col2" >59.14</td>
                        <td id="T_baa6f_row7_col3" class="data row7 col3" >1.84</td>
                        <td id="T_baa6f_row7_col4" class="data row7 col4" >3.39</td>
                        <td id="T_baa6f_row7_col5" class="data row7 col5" >-5.97</td>
                        <td id="T_baa6f_row7_col6" class="data row7 col6" >36.96</td>
                        <td id="T_baa6f_row7_col7" class="data row7 col7" >111.92</td>
                        <td id="T_baa6f_row7_col8" class="data row7 col8" >365.78</td>
                        <td id="T_baa6f_row7_col9" class="data row7 col9" >-56.07</td>
                        <td id="T_baa6f_row7_col10" class="data row7 col10" >96.00</td>
                        <td id="T_baa6f_row7_col11" class="data row7 col11" >5.82</td>
                        <td id="T_baa6f_row7_col12" class="data row7 col12" >191.39</td>
                        <td id="T_baa6f_row7_col13" class="data row7 col13" >China</td>
                        <td id="T_baa6f_row7_col14" class="data row7 col14" >25.29</td>
            </tr>
            <tr>
                        <th id="T_baa6f_level0_row8" class="row_heading level0 row8" >NIO</th>
                        <td id="T_baa6f_row8_col0" class="data row8 col0" >41.69</td>
                        <td id="T_baa6f_row8_col1" class="data row8 col1" >10.10</td>
                        <td id="T_baa6f_row8_col2" class="data row8 col2" >0.00</td>
                        <td id="T_baa6f_row8_col3" class="data row8 col3" >-28.88</td>
                        <td id="T_baa6f_row8_col4" class="data row8 col4" >-217.18</td>
                        <td id="T_baa6f_row8_col5" class="data row8 col5" >inf</td>
                        <td id="T_baa6f_row8_col6" class="data row8 col6" >0.00</td>
                        <td id="T_baa6f_row8_col7" class="data row8 col7" >35.53</td>
                        <td id="T_baa6f_row8_col8" class="data row8 col8" >149.80</td>
                        <td id="T_baa6f_row8_col9" class="data row8 col9" >-7.85</td>
                        <td id="T_baa6f_row8_col10" class="data row8 col10" >96.90</td>
                        <td id="T_baa6f_row8_col11" class="data row8 col11" >-65.56</td>
                        <td id="T_baa6f_row8_col12" class="data row8 col12" >-358.06</td>
                        <td id="T_baa6f_row8_col13" class="data row8 col13" >nan</td>
                        <td id="T_baa6f_row8_col14" class="data row8 col14" >67.44</td>
            </tr>
            <tr>
                        <th id="T_baa6f_level0_row9" class="row_heading level0 row9" >BIDU</th>
                        <td id="T_baa6f_row9_col0" class="data row9 col0" >42.34</td>
                        <td id="T_baa6f_row9_col1" class="data row9 col1" >10.82</td>
                        <td id="T_baa6f_row9_col2" class="data row9 col2" >12.18</td>
                        <td id="T_baa6f_row9_col3" class="data row9 col3" >11.59</td>
                        <td id="T_baa6f_row9_col4" class="data row9 col4" >17.64</td>
                        <td id="T_baa6f_row9_col5" class="data row9 col5" >7.63</td>
                        <td id="T_baa6f_row9_col6" class="data row9 col6" >10.70</td>
                        <td id="T_baa6f_row9_col7" class="data row9 col7" >316.86</td>
                        <td id="T_baa6f_row9_col8" class="data row9 col8" >589.45</td>
                        <td id="T_baa6f_row9_col9" class="data row9 col9" >-11.75</td>
                        <td id="T_baa6f_row9_col10" class="data row9 col10" >8.08</td>
                        <td id="T_baa6f_row9_col11" class="data row9 col11" >217.15</td>
                        <td id="T_baa6f_row9_col12" class="data row9 col12" >14101.41</td>
                        <td id="T_baa6f_row9_col13" class="data row9 col13" >China</td>
                        <td id="T_baa6f_row9_col14" class="data row9 col14" >68.75</td>
            </tr>
            <tr>
                        <th id="T_baa6f_level0_row10" class="row_heading level0 row10" >NTES</th>
                        <td id="T_baa6f_row10_col0" class="data row10 col0" >33.89</td>
                        <td id="T_baa6f_row10_col1" class="data row10 col1" >8.99</td>
                        <td id="T_baa6f_row10_col2" class="data row10 col2" >0.39</td>
                        <td id="T_baa6f_row10_col3" class="data row10 col3" >21.57</td>
                        <td id="T_baa6f_row10_col4" class="data row10 col4" >22.09</td>
                        <td id="T_baa6f_row10_col5" class="data row10 col5" >18.43</td>
                        <td id="T_baa6f_row10_col6" class="data row10 col6" >5.14</td>
                        <td id="T_baa6f_row10_col7" class="data row10 col7" >53.15</td>
                        <td id="T_baa6f_row10_col8" class="data row10 col8" >166.31</td>
                        <td id="T_baa6f_row10_col9" class="data row10 col9" >33.70</td>
                        <td id="T_baa6f_row10_col10" class="data row10 col10" >20.88</td>
                        <td id="T_baa6f_row10_col11" class="data row10 col11" >440.86</td>
                        <td id="T_baa6f_row10_col12" class="data row10 col12" >532.03</td>
                        <td id="T_baa6f_row10_col13" class="data row10 col13" >China</td>
                        <td id="T_baa6f_row10_col14" class="data row10 col14" >77.44</td>
            </tr>
            <tr>
                        <th id="T_baa6f_level0_row11" class="row_heading level0 row11" >LI</th>
                        <td id="T_baa6f_row11_col0" class="data row11 col0" >18.06</td>
                        <td id="T_baa6f_row11_col1" class="data row11 col1" >1.31</td>
                        <td id="T_baa6f_row11_col2" class="data row11 col2" >0.00</td>
                        <td id="T_baa6f_row11_col3" class="data row11 col3" >35.47</td>
                        <td id="T_baa6f_row11_col4" class="data row11 col4" >-429.57</td>
                        <td id="T_baa6f_row11_col5" class="data row11 col5" >inf</td>
                        <td id="T_baa6f_row11_col6" class="data row11 col6" >0.00</td>
                        <td id="T_baa6f_row11_col7" class="data row11 col7" >-17.32</td>
                        <td id="T_baa6f_row11_col8" class="data row11 col8" >108.13</td>
                        <td id="T_baa6f_row11_col9" class="data row11 col9" >-85.61</td>
                        <td id="T_baa6f_row11_col10" class="data row11 col10" >147.25</td>
                        <td id="T_baa6f_row11_col11" class="data row11 col11" >-0.17</td>
                        <td id="T_baa6f_row11_col12" class="data row11 col12" >-10.38</td>
                        <td id="T_baa6f_row11_col13" class="data row11 col13" >China</td>
                        <td id="T_baa6f_row11_col14" class="data row11 col14" >22.02</td>
            </tr>
            <tr>
                        <th id="T_baa6f_level0_row12" class="row_heading level0 row12" >YY</th>
                        <td id="T_baa6f_row12_col0" class="data row12 col0" >22.90</td>
                        <td id="T_baa6f_row12_col1" class="data row12 col1" >7.09</td>
                        <td id="T_baa6f_row12_col2" class="data row12 col2" >30.02</td>
                        <td id="T_baa6f_row12_col3" class="data row12 col3" >16.55</td>
                        <td id="T_baa6f_row12_col4" class="data row12 col4" >29.44</td>
                        <td id="T_baa6f_row12_col5" class="data row12 col5" >16.64</td>
                        <td id="T_baa6f_row12_col6" class="data row12 col6" >57.73</td>
                        <td id="T_baa6f_row12_col7" class="data row12 col7" >85.34</td>
                        <td id="T_baa6f_row12_col8" class="data row12 col8" >110.67</td>
                        <td id="T_baa6f_row12_col9" class="data row12 col9" >3.79</td>
                        <td id="T_baa6f_row12_col10" class="data row12 col10" >18.97</td>
                        <td id="T_baa6f_row12_col11" class="data row12 col11" >51.88</td>
                        <td id="T_baa6f_row12_col12" class="data row12 col12" >315.35</td>
                        <td id="T_baa6f_row12_col13" class="data row12 col13" >China</td>
                        <td id="T_baa6f_row12_col14" class="data row12 col14" >5.86</td>
            </tr>
    </tbody></table>



## 港股


<script>
$('table').addClass('table table-striped table-hover  table-sm ')
$('thead').addClass('thead-dark')
</script>