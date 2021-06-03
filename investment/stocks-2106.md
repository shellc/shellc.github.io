---
layout: default
title: 选股(2106)
---


<style>
table {font-size: 11px;}
</style>

# 选股

Update: 20210603


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
#T_9ce81_row0_col0,#T_9ce81_row0_col1,#T_9ce81_row0_col2,#T_9ce81_row0_col3,#T_9ce81_row0_col4,#T_9ce81_row0_col5,#T_9ce81_row0_col6,#T_9ce81_row0_col7,#T_9ce81_row0_col8,#T_9ce81_row0_col9,#T_9ce81_row0_col10,#T_9ce81_row0_col12,#T_9ce81_row0_col14,#T_9ce81_row0_col15,#T_9ce81_row0_col16,#T_9ce81_row0_col17,#T_9ce81_row0_col18,#T_9ce81_row1_col0,#T_9ce81_row1_col1,#T_9ce81_row1_col2,#T_9ce81_row1_col3,#T_9ce81_row1_col4,#T_9ce81_row1_col5,#T_9ce81_row1_col6,#T_9ce81_row1_col7,#T_9ce81_row1_col8,#T_9ce81_row1_col9,#T_9ce81_row1_col10,#T_9ce81_row1_col11,#T_9ce81_row1_col12,#T_9ce81_row1_col14,#T_9ce81_row1_col15,#T_9ce81_row1_col16,#T_9ce81_row1_col17,#T_9ce81_row1_col18,#T_9ce81_row2_col0,#T_9ce81_row2_col1,#T_9ce81_row2_col2,#T_9ce81_row2_col3,#T_9ce81_row2_col4,#T_9ce81_row2_col5,#T_9ce81_row2_col6,#T_9ce81_row2_col8,#T_9ce81_row2_col9,#T_9ce81_row2_col10,#T_9ce81_row2_col12,#T_9ce81_row2_col13,#T_9ce81_row2_col14,#T_9ce81_row2_col15,#T_9ce81_row2_col16,#T_9ce81_row2_col17,#T_9ce81_row3_col0,#T_9ce81_row3_col1,#T_9ce81_row3_col2,#T_9ce81_row3_col3,#T_9ce81_row3_col4,#T_9ce81_row3_col5,#T_9ce81_row3_col6,#T_9ce81_row3_col7,#T_9ce81_row3_col8,#T_9ce81_row3_col9,#T_9ce81_row3_col10,#T_9ce81_row3_col11,#T_9ce81_row3_col12,#T_9ce81_row3_col13,#T_9ce81_row3_col14,#T_9ce81_row3_col15,#T_9ce81_row3_col16,#T_9ce81_row3_col17,#T_9ce81_row3_col18,#T_9ce81_row4_col0,#T_9ce81_row4_col1,#T_9ce81_row4_col2,#T_9ce81_row4_col3,#T_9ce81_row4_col4,#T_9ce81_row4_col5,#T_9ce81_row4_col6,#T_9ce81_row4_col7,#T_9ce81_row4_col8,#T_9ce81_row4_col9,#T_9ce81_row4_col10,#T_9ce81_row4_col11,#T_9ce81_row4_col12,#T_9ce81_row4_col13,#T_9ce81_row4_col14,#T_9ce81_row4_col15,#T_9ce81_row4_col16,#T_9ce81_row4_col17,#T_9ce81_row4_col18,#T_9ce81_row5_col0,#T_9ce81_row5_col1,#T_9ce81_row5_col2,#T_9ce81_row5_col3,#T_9ce81_row5_col4,#T_9ce81_row5_col5,#T_9ce81_row5_col6,#T_9ce81_row5_col8,#T_9ce81_row5_col9,#T_9ce81_row5_col10,#T_9ce81_row5_col12,#T_9ce81_row5_col13,#T_9ce81_row5_col14,#T_9ce81_row5_col15,#T_9ce81_row5_col16,#T_9ce81_row5_col17,#T_9ce81_row6_col0,#T_9ce81_row6_col1,#T_9ce81_row6_col2,#T_9ce81_row6_col3,#T_9ce81_row6_col4,#T_9ce81_row6_col5,#T_9ce81_row6_col6,#T_9ce81_row6_col7,#T_9ce81_row6_col8,#T_9ce81_row6_col9,#T_9ce81_row6_col10,#T_9ce81_row6_col11,#T_9ce81_row6_col12,#T_9ce81_row6_col13,#T_9ce81_row6_col14,#T_9ce81_row6_col15,#T_9ce81_row6_col16,#T_9ce81_row6_col17,#T_9ce81_row6_col18,#T_9ce81_row7_col0,#T_9ce81_row7_col1,#T_9ce81_row7_col2,#T_9ce81_row7_col3,#T_9ce81_row7_col4,#T_9ce81_row7_col5,#T_9ce81_row7_col6,#T_9ce81_row7_col7,#T_9ce81_row7_col8,#T_9ce81_row7_col9,#T_9ce81_row7_col10,#T_9ce81_row7_col11,#T_9ce81_row7_col12,#T_9ce81_row7_col13,#T_9ce81_row7_col14,#T_9ce81_row7_col15,#T_9ce81_row7_col16,#T_9ce81_row7_col17,#T_9ce81_row8_col0,#T_9ce81_row8_col1,#T_9ce81_row8_col2,#T_9ce81_row8_col3,#T_9ce81_row8_col4,#T_9ce81_row8_col5,#T_9ce81_row8_col6,#T_9ce81_row8_col7,#T_9ce81_row8_col8,#T_9ce81_row8_col9,#T_9ce81_row8_col10,#T_9ce81_row8_col11,#T_9ce81_row8_col12,#T_9ce81_row8_col13,#T_9ce81_row8_col14,#T_9ce81_row8_col15,#T_9ce81_row8_col16,#T_9ce81_row8_col17,#T_9ce81_row9_col0,#T_9ce81_row9_col1,#T_9ce81_row9_col2,#T_9ce81_row9_col3,#T_9ce81_row9_col4,#T_9ce81_row9_col5,#T_9ce81_row9_col6,#T_9ce81_row9_col7,#T_9ce81_row9_col8,#T_9ce81_row9_col9,#T_9ce81_row9_col10,#T_9ce81_row9_col11,#T_9ce81_row9_col12,#T_9ce81_row9_col13,#T_9ce81_row9_col14,#T_9ce81_row9_col15,#T_9ce81_row9_col16,#T_9ce81_row9_col17,#T_9ce81_row10_col0,#T_9ce81_row10_col1,#T_9ce81_row10_col2,#T_9ce81_row10_col3,#T_9ce81_row10_col4,#T_9ce81_row10_col5,#T_9ce81_row10_col6,#T_9ce81_row10_col7,#T_9ce81_row10_col8,#T_9ce81_row10_col9,#T_9ce81_row10_col10,#T_9ce81_row10_col12,#T_9ce81_row10_col14,#T_9ce81_row10_col15,#T_9ce81_row10_col16,#T_9ce81_row10_col17,#T_9ce81_row10_col18,#T_9ce81_row11_col0,#T_9ce81_row11_col1,#T_9ce81_row11_col2,#T_9ce81_row11_col3,#T_9ce81_row11_col4,#T_9ce81_row11_col5,#T_9ce81_row11_col6,#T_9ce81_row11_col7,#T_9ce81_row11_col8,#T_9ce81_row11_col9,#T_9ce81_row11_col10,#T_9ce81_row11_col11,#T_9ce81_row11_col12,#T_9ce81_row11_col13,#T_9ce81_row11_col14,#T_9ce81_row11_col15,#T_9ce81_row11_col16,#T_9ce81_row11_col17,#T_9ce81_row12_col0,#T_9ce81_row12_col1,#T_9ce81_row12_col2,#T_9ce81_row12_col3,#T_9ce81_row12_col4,#T_9ce81_row12_col5,#T_9ce81_row12_col6,#T_9ce81_row12_col7,#T_9ce81_row12_col8,#T_9ce81_row12_col9,#T_9ce81_row12_col10,#T_9ce81_row12_col12,#T_9ce81_row12_col14,#T_9ce81_row12_col15,#T_9ce81_row12_col16,#T_9ce81_row12_col17,#T_9ce81_row12_col18,#T_9ce81_row13_col0,#T_9ce81_row13_col1,#T_9ce81_row13_col2,#T_9ce81_row13_col3,#T_9ce81_row13_col4,#T_9ce81_row13_col5,#T_9ce81_row13_col6,#T_9ce81_row13_col7,#T_9ce81_row13_col8,#T_9ce81_row13_col9,#T_9ce81_row13_col10,#T_9ce81_row13_col11,#T_9ce81_row13_col12,#T_9ce81_row13_col13,#T_9ce81_row13_col14,#T_9ce81_row13_col15,#T_9ce81_row13_col16,#T_9ce81_row13_col17,#T_9ce81_row14_col0,#T_9ce81_row14_col1,#T_9ce81_row14_col2,#T_9ce81_row14_col3,#T_9ce81_row14_col4,#T_9ce81_row14_col5,#T_9ce81_row14_col6,#T_9ce81_row14_col7,#T_9ce81_row14_col8,#T_9ce81_row14_col9,#T_9ce81_row14_col10,#T_9ce81_row14_col12,#T_9ce81_row14_col13,#T_9ce81_row14_col14,#T_9ce81_row14_col15,#T_9ce81_row14_col16,#T_9ce81_row14_col17,#T_9ce81_row15_col0,#T_9ce81_row15_col1,#T_9ce81_row15_col2,#T_9ce81_row15_col3,#T_9ce81_row15_col4,#T_9ce81_row15_col5,#T_9ce81_row15_col6,#T_9ce81_row15_col7,#T_9ce81_row15_col8,#T_9ce81_row15_col9,#T_9ce81_row15_col10,#T_9ce81_row15_col12,#T_9ce81_row15_col14,#T_9ce81_row15_col15,#T_9ce81_row15_col16,#T_9ce81_row15_col17,#T_9ce81_row15_col18,#T_9ce81_row16_col0,#T_9ce81_row16_col1,#T_9ce81_row16_col2,#T_9ce81_row16_col3,#T_9ce81_row16_col4,#T_9ce81_row16_col5,#T_9ce81_row16_col6,#T_9ce81_row16_col7,#T_9ce81_row16_col8,#T_9ce81_row16_col9,#T_9ce81_row16_col10,#T_9ce81_row16_col11,#T_9ce81_row16_col12,#T_9ce81_row16_col13,#T_9ce81_row16_col14,#T_9ce81_row16_col15,#T_9ce81_row16_col16,#T_9ce81_row16_col17,#T_9ce81_row17_col0,#T_9ce81_row17_col1,#T_9ce81_row17_col2,#T_9ce81_row17_col3,#T_9ce81_row17_col4,#T_9ce81_row17_col5,#T_9ce81_row17_col6,#T_9ce81_row17_col7,#T_9ce81_row17_col8,#T_9ce81_row17_col9,#T_9ce81_row17_col10,#T_9ce81_row17_col11,#T_9ce81_row17_col12,#T_9ce81_row17_col13,#T_9ce81_row17_col14,#T_9ce81_row17_col15,#T_9ce81_row17_col16,#T_9ce81_row17_col17,#T_9ce81_row18_col0,#T_9ce81_row18_col1,#T_9ce81_row18_col2,#T_9ce81_row18_col3,#T_9ce81_row18_col4,#T_9ce81_row18_col5,#T_9ce81_row18_col6,#T_9ce81_row18_col7,#T_9ce81_row18_col8,#T_9ce81_row18_col9,#T_9ce81_row18_col10,#T_9ce81_row18_col11,#T_9ce81_row18_col12,#T_9ce81_row18_col13,#T_9ce81_row18_col14,#T_9ce81_row18_col15,#T_9ce81_row18_col16,#T_9ce81_row18_col17,#T_9ce81_row18_col18,#T_9ce81_row19_col0,#T_9ce81_row19_col1,#T_9ce81_row19_col2,#T_9ce81_row19_col3,#T_9ce81_row19_col4,#T_9ce81_row19_col5,#T_9ce81_row19_col6,#T_9ce81_row19_col7,#T_9ce81_row19_col8,#T_9ce81_row19_col9,#T_9ce81_row19_col10,#T_9ce81_row19_col11,#T_9ce81_row19_col12,#T_9ce81_row19_col13,#T_9ce81_row19_col14,#T_9ce81_row19_col15,#T_9ce81_row19_col16,#T_9ce81_row19_col17,#T_9ce81_row20_col0,#T_9ce81_row20_col1,#T_9ce81_row20_col2,#T_9ce81_row20_col3,#T_9ce81_row20_col4,#T_9ce81_row20_col5,#T_9ce81_row20_col6,#T_9ce81_row20_col7,#T_9ce81_row20_col8,#T_9ce81_row20_col9,#T_9ce81_row20_col10,#T_9ce81_row20_col11,#T_9ce81_row20_col12,#T_9ce81_row20_col13,#T_9ce81_row20_col14,#T_9ce81_row20_col15,#T_9ce81_row20_col16,#T_9ce81_row20_col17,#T_9ce81_row21_col0,#T_9ce81_row21_col1,#T_9ce81_row21_col2,#T_9ce81_row21_col3,#T_9ce81_row21_col4,#T_9ce81_row21_col5,#T_9ce81_row21_col6,#T_9ce81_row21_col7,#T_9ce81_row21_col8,#T_9ce81_row21_col9,#T_9ce81_row21_col10,#T_9ce81_row21_col11,#T_9ce81_row21_col12,#T_9ce81_row21_col13,#T_9ce81_row21_col14,#T_9ce81_row21_col15,#T_9ce81_row21_col16,#T_9ce81_row21_col17,#T_9ce81_row22_col0,#T_9ce81_row22_col1,#T_9ce81_row22_col2,#T_9ce81_row22_col3,#T_9ce81_row22_col4,#T_9ce81_row22_col5,#T_9ce81_row22_col6,#T_9ce81_row22_col7,#T_9ce81_row22_col8,#T_9ce81_row22_col9,#T_9ce81_row22_col10,#T_9ce81_row22_col11,#T_9ce81_row22_col12,#T_9ce81_row22_col13,#T_9ce81_row22_col14,#T_9ce81_row22_col15,#T_9ce81_row22_col16,#T_9ce81_row22_col17,#T_9ce81_row23_col0,#T_9ce81_row23_col1,#T_9ce81_row23_col2,#T_9ce81_row23_col3,#T_9ce81_row23_col4,#T_9ce81_row23_col5,#T_9ce81_row23_col6,#T_9ce81_row23_col7,#T_9ce81_row23_col8,#T_9ce81_row23_col9,#T_9ce81_row23_col10,#T_9ce81_row23_col11,#T_9ce81_row23_col12,#T_9ce81_row23_col13,#T_9ce81_row23_col14,#T_9ce81_row23_col15,#T_9ce81_row23_col16,#T_9ce81_row23_col17,#T_9ce81_row24_col0,#T_9ce81_row24_col1,#T_9ce81_row24_col2,#T_9ce81_row24_col3,#T_9ce81_row24_col4,#T_9ce81_row24_col5,#T_9ce81_row24_col6,#T_9ce81_row24_col7,#T_9ce81_row24_col8,#T_9ce81_row24_col9,#T_9ce81_row24_col10,#T_9ce81_row24_col11,#T_9ce81_row24_col12,#T_9ce81_row24_col13,#T_9ce81_row24_col14,#T_9ce81_row24_col15,#T_9ce81_row24_col16,#T_9ce81_row24_col17,#T_9ce81_row25_col0,#T_9ce81_row25_col1,#T_9ce81_row25_col2,#T_9ce81_row25_col3,#T_9ce81_row25_col4,#T_9ce81_row25_col5,#T_9ce81_row25_col6,#T_9ce81_row25_col7,#T_9ce81_row25_col8,#T_9ce81_row25_col9,#T_9ce81_row25_col10,#T_9ce81_row25_col11,#T_9ce81_row25_col12,#T_9ce81_row25_col13,#T_9ce81_row25_col14,#T_9ce81_row25_col15,#T_9ce81_row25_col16,#T_9ce81_row25_col17,#T_9ce81_row26_col0,#T_9ce81_row26_col1,#T_9ce81_row26_col2,#T_9ce81_row26_col3,#T_9ce81_row26_col4,#T_9ce81_row26_col5,#T_9ce81_row26_col6,#T_9ce81_row26_col7,#T_9ce81_row26_col8,#T_9ce81_row26_col9,#T_9ce81_row26_col10,#T_9ce81_row26_col12,#T_9ce81_row26_col13,#T_9ce81_row26_col14,#T_9ce81_row26_col15,#T_9ce81_row26_col16,#T_9ce81_row26_col17,#T_9ce81_row27_col0,#T_9ce81_row27_col1,#T_9ce81_row27_col2,#T_9ce81_row27_col3,#T_9ce81_row27_col4,#T_9ce81_row27_col5,#T_9ce81_row27_col6,#T_9ce81_row27_col7,#T_9ce81_row27_col8,#T_9ce81_row27_col9,#T_9ce81_row27_col10,#T_9ce81_row27_col11,#T_9ce81_row27_col12,#T_9ce81_row27_col13,#T_9ce81_row27_col14,#T_9ce81_row27_col15,#T_9ce81_row27_col16,#T_9ce81_row27_col17,#T_9ce81_row28_col0,#T_9ce81_row28_col1,#T_9ce81_row28_col2,#T_9ce81_row28_col3,#T_9ce81_row28_col4,#T_9ce81_row28_col5,#T_9ce81_row28_col6,#T_9ce81_row28_col7,#T_9ce81_row28_col8,#T_9ce81_row28_col9,#T_9ce81_row28_col10,#T_9ce81_row28_col11,#T_9ce81_row28_col12,#T_9ce81_row28_col13,#T_9ce81_row28_col14,#T_9ce81_row28_col15,#T_9ce81_row28_col16,#T_9ce81_row28_col17,#T_9ce81_row29_col0,#T_9ce81_row29_col1,#T_9ce81_row29_col2,#T_9ce81_row29_col3,#T_9ce81_row29_col4,#T_9ce81_row29_col5,#T_9ce81_row29_col6,#T_9ce81_row29_col7,#T_9ce81_row29_col8,#T_9ce81_row29_col9,#T_9ce81_row29_col10,#T_9ce81_row29_col12,#T_9ce81_row29_col14,#T_9ce81_row29_col15,#T_9ce81_row29_col16,#T_9ce81_row29_col17,#T_9ce81_row29_col18,#T_9ce81_row30_col0,#T_9ce81_row30_col1,#T_9ce81_row30_col2,#T_9ce81_row30_col3,#T_9ce81_row30_col4,#T_9ce81_row30_col5,#T_9ce81_row30_col6,#T_9ce81_row30_col7,#T_9ce81_row30_col8,#T_9ce81_row30_col9,#T_9ce81_row30_col10,#T_9ce81_row30_col11,#T_9ce81_row30_col12,#T_9ce81_row30_col13,#T_9ce81_row30_col14,#T_9ce81_row30_col15,#T_9ce81_row30_col16,#T_9ce81_row30_col17,#T_9ce81_row31_col0,#T_9ce81_row31_col1,#T_9ce81_row31_col2,#T_9ce81_row31_col3,#T_9ce81_row31_col4,#T_9ce81_row31_col5,#T_9ce81_row31_col6,#T_9ce81_row31_col7,#T_9ce81_row31_col8,#T_9ce81_row31_col9,#T_9ce81_row31_col10,#T_9ce81_row31_col12,#T_9ce81_row31_col14,#T_9ce81_row31_col15,#T_9ce81_row31_col16,#T_9ce81_row31_col17,#T_9ce81_row31_col18{
            color:  black;
        }#T_9ce81_row0_col11,#T_9ce81_row0_col13,#T_9ce81_row1_col13,#T_9ce81_row2_col7,#T_9ce81_row2_col11,#T_9ce81_row2_col18,#T_9ce81_row5_col7,#T_9ce81_row5_col11,#T_9ce81_row5_col18,#T_9ce81_row7_col18,#T_9ce81_row8_col18,#T_9ce81_row9_col18,#T_9ce81_row10_col11,#T_9ce81_row10_col13,#T_9ce81_row11_col18,#T_9ce81_row12_col11,#T_9ce81_row12_col13,#T_9ce81_row13_col18,#T_9ce81_row14_col11,#T_9ce81_row14_col18,#T_9ce81_row15_col11,#T_9ce81_row15_col13,#T_9ce81_row16_col18,#T_9ce81_row17_col18,#T_9ce81_row19_col18,#T_9ce81_row20_col18,#T_9ce81_row21_col18,#T_9ce81_row22_col18,#T_9ce81_row23_col18,#T_9ce81_row24_col18,#T_9ce81_row25_col18,#T_9ce81_row26_col11,#T_9ce81_row26_col18,#T_9ce81_row27_col18,#T_9ce81_row28_col18,#T_9ce81_row29_col11,#T_9ce81_row29_col13,#T_9ce81_row30_col18,#T_9ce81_row31_col11,#T_9ce81_row31_col13{
            color:  red;
        }</style><table id="T_9ce81_" ><thead>    <tr>        <th class="blank level0" ></th>        <th class="col_heading level0 col0" >名称</th>        <th class="col_heading level0 col1" >行业</th>        <th class="col_heading level0 col2" >权重</th>        <th class="col_heading level0 col3" >负债率</th>        <th class="col_heading level0 col4" >应收比</th>        <th class="col_heading level0 col5" >ROE</th>        <th class="col_heading level0 col6" >利润率</th>        <th class="col_heading level0 col7" >收入增长</th>        <th class="col_heading level0 col8" >收入波动</th>        <th class="col_heading level0 col9" >盈利增长</th>        <th class="col_heading level0 col10" >盈利波动</th>        <th class="col_heading level0 col11" >FCF增长</th>        <th class="col_heading level0 col12" >FCF波动</th>        <th class="col_heading level0 col13" >DCF</th>        <th class="col_heading level0 col14" >盈利折现</th>        <th class="col_heading level0 col15" >PE</th>        <th class="col_heading level0 col16" >PEG</th>        <th class="col_heading level0 col17" >市值</th>        <th class="col_heading level0 col18" >折价率</th>    </tr>    <tr>        <th class="index_name level0" >Symbol</th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>    </tr></thead><tbody>
                <tr>
                        <th id="T_9ce81_level0_row0" class="row_heading level0 row0" >002932.SZ</th>
                        <td id="T_9ce81_row0_col0" class="data row0 col0" >明德生物</td>
                        <td id="T_9ce81_row0_col1" class="data row0 col1" >医药生物</td>
                        <td id="T_9ce81_row0_col2" class="data row0 col2" >0.07</td>
                        <td id="T_9ce81_row0_col3" class="data row0 col3" >21.85</td>
                        <td id="T_9ce81_row0_col4" class="data row0 col4" >19.76</td>
                        <td id="T_9ce81_row0_col5" class="data row0 col5" >21.76</td>
                        <td id="T_9ce81_row0_col6" class="data row0 col6" >36.58</td>
                        <td id="T_9ce81_row0_col7" class="data row0 col7" >146.32</td>
                        <td id="T_9ce81_row0_col8" class="data row0 col8" >245.19</td>
                        <td id="T_9ce81_row0_col9" class="data row0 col9" >330.21</td>
                        <td id="T_9ce81_row0_col10" class="data row0 col10" >605.52</td>
                        <td id="T_9ce81_row0_col11" class="data row0 col11" >-1108.82</td>
                        <td id="T_9ce81_row0_col12" class="data row0 col12" >2198.15</td>
                        <td id="T_9ce81_row0_col13" class="data row0 col13" >-903.76</td>
                        <td id="T_9ce81_row0_col14" class="data row0 col14" >140.19</td>
                        <td id="T_9ce81_row0_col15" class="data row0 col15" >8.11</td>
                        <td id="T_9ce81_row0_col16" class="data row0 col16" >0.02</td>
                        <td id="T_9ce81_row0_col17" class="data row0 col17" >6.56</td>
                        <td id="T_9ce81_row0_col18" class="data row0 col18" >0.00</td>
            </tr>
            <tr>
                        <th id="T_9ce81_level0_row1" class="row_heading level0 row1" >002714.SZ</th>
                        <td id="T_9ce81_row1_col0" class="data row1 col0" >牧原股份</td>
                        <td id="T_9ce81_row1_col1" class="data row1 col1" >农林牧渔</td>
                        <td id="T_9ce81_row1_col2" class="data row1 col2" >21.46</td>
                        <td id="T_9ce81_row1_col3" class="data row1 col3" >46.09</td>
                        <td id="T_9ce81_row1_col4" class="data row1 col4" >0.13</td>
                        <td id="T_9ce81_row1_col5" class="data row1 col5" >28.10</td>
                        <td id="T_9ce81_row1_col6" class="data row1 col6" >26.61</td>
                        <td id="T_9ce81_row1_col7" class="data row1 col7" >87.55</td>
                        <td id="T_9ce81_row1_col8" class="data row1 col8" >79.09</td>
                        <td id="T_9ce81_row1_col9" class="data row1 col9" >448.77</td>
                        <td id="T_9ce81_row1_col10" class="data row1 col10" >583.13</td>
                        <td id="T_9ce81_row1_col11" class="data row1 col11" >199.27</td>
                        <td id="T_9ce81_row1_col12" class="data row1 col12" >373.67</td>
                        <td id="T_9ce81_row1_col13" class="data row1 col13" >-2566.75</td>
                        <td id="T_9ce81_row1_col14" class="data row1 col14" >16539.66</td>
                        <td id="T_9ce81_row1_col15" class="data row1 col15" >11.56</td>
                        <td id="T_9ce81_row1_col16" class="data row1 col16" >0.03</td>
                        <td id="T_9ce81_row1_col17" class="data row1 col17" >350.03</td>
                        <td id="T_9ce81_row1_col18" class="data row1 col18" >0.00</td>
            </tr>
            <tr>
                        <th id="T_9ce81_level0_row2" class="row_heading level0 row2" >300418.SZ</th>
                        <td id="T_9ce81_row2_col0" class="data row2 col0" >昆仑万维</td>
                        <td id="T_9ce81_row2_col1" class="data row2 col1" >传媒</td>
                        <td id="T_9ce81_row2_col2" class="data row2 col2" >1.14</td>
                        <td id="T_9ce81_row2_col3" class="data row2 col3" >26.89</td>
                        <td id="T_9ce81_row2_col4" class="data row2 col4" >13.41</td>
                        <td id="T_9ce81_row2_col5" class="data row2 col5" >27.55</td>
                        <td id="T_9ce81_row2_col6" class="data row2 col6" >68.64</td>
                        <td id="T_9ce81_row2_col7" class="data row2 col7" >-6.17</td>
                        <td id="T_9ce81_row2_col8" class="data row2 col8" >16.93</td>
                        <td id="T_9ce81_row2_col9" class="data row2 col9" >105.00</td>
                        <td id="T_9ce81_row2_col10" class="data row2 col10" >156.97</td>
                        <td id="T_9ce81_row2_col11" class="data row2 col11" >-5.39</td>
                        <td id="T_9ce81_row2_col12" class="data row2 col12" >42.73</td>
                        <td id="T_9ce81_row2_col13" class="data row2 col13" >11.90</td>
                        <td id="T_9ce81_row2_col14" class="data row2 col14" >204.88</td>
                        <td id="T_9ce81_row2_col15" class="data row2 col15" >4.53</td>
                        <td id="T_9ce81_row2_col16" class="data row2 col16" >0.04</td>
                        <td id="T_9ce81_row2_col17" class="data row2 col17" >21.79</td>
                        <td id="T_9ce81_row2_col18" class="data row2 col18" >-83.12</td>
            </tr>
            <tr>
                        <th id="T_9ce81_level0_row3" class="row_heading level0 row3" >000672.SZ</th>
                        <td id="T_9ce81_row3_col0" class="data row3 col0" >上峰水泥</td>
                        <td id="T_9ce81_row3_col1" class="data row3 col1" >建筑材料</td>
                        <td id="T_9ce81_row3_col2" class="data row3 col2" >1.18</td>
                        <td id="T_9ce81_row3_col3" class="data row3 col3" >36.62</td>
                        <td id="T_9ce81_row3_col4" class="data row3 col4" >8.81</td>
                        <td id="T_9ce81_row3_col5" class="data row3 col5" >37.68</td>
                        <td id="T_9ce81_row3_col6" class="data row3 col6" >26.99</td>
                        <td id="T_9ce81_row3_col7" class="data row3 col7" >14.05</td>
                        <td id="T_9ce81_row3_col8" class="data row3 col8" >26.51</td>
                        <td id="T_9ce81_row3_col9" class="data row3 col9" >43.73</td>
                        <td id="T_9ce81_row3_col10" class="data row3 col10" >51.12</td>
                        <td id="T_9ce81_row3_col11" class="data row3 col11" >34.90</td>
                        <td id="T_9ce81_row3_col12" class="data row3 col12" >81.40</td>
                        <td id="T_9ce81_row3_col13" class="data row3 col13" >47.11</td>
                        <td id="T_9ce81_row3_col14" class="data row3 col14" >58.53</td>
                        <td id="T_9ce81_row3_col15" class="data row3 col15" >7.83</td>
                        <td id="T_9ce81_row3_col16" class="data row3 col16" >0.18</td>
                        <td id="T_9ce81_row3_col17" class="data row3 col17" >16.01</td>
                        <td id="T_9ce81_row3_col18" class="data row3 col18" >66.01</td>
            </tr>
            <tr>
                        <th id="T_9ce81_level0_row4" class="row_heading level0 row4" >600585.SS</th>
                        <td id="T_9ce81_row4_col0" class="data row4 col0" >海螺水泥</td>
                        <td id="T_9ce81_row4_col1" class="data row4 col1" >建筑材料</td>
                        <td id="T_9ce81_row4_col2" class="data row4 col2" >19.83</td>
                        <td id="T_9ce81_row4_col3" class="data row4 col3" >16.30</td>
                        <td id="T_9ce81_row4_col4" class="data row4 col4" >7.17</td>
                        <td id="T_9ce81_row4_col5" class="data row4 col5" >22.59</td>
                        <td id="T_9ce81_row4_col6" class="data row4 col6" >21.40</td>
                        <td id="T_9ce81_row4_col7" class="data row4 col7" >35.01</td>
                        <td id="T_9ce81_row4_col8" class="data row4 col8" >31.14</td>
                        <td id="T_9ce81_row4_col9" class="data row4 col9" >35.10</td>
                        <td id="T_9ce81_row4_col10" class="data row4 col10" >46.03</td>
                        <td id="T_9ce81_row4_col11" class="data row4 col11" >36.04</td>
                        <td id="T_9ce81_row4_col12" class="data row4 col12" >80.90</td>
                        <td id="T_9ce81_row4_col13" class="data row4 col13" >768.24</td>
                        <td id="T_9ce81_row4_col14" class="data row4 col14" >847.14</td>
                        <td id="T_9ce81_row4_col15" class="data row4 col15" >7.11</td>
                        <td id="T_9ce81_row4_col16" class="data row4 col16" >0.20</td>
                        <td id="T_9ce81_row4_col17" class="data row4 col17" >256.22</td>
                        <td id="T_9ce81_row4_col18" class="data row4 col18" >66.65</td>
            </tr>
            <tr>
                        <th id="T_9ce81_level0_row5" class="row_heading level0 row5" >600738.SS</th>
                        <td id="T_9ce81_row5_col0" class="data row5 col0" >丽尚国潮</td>
                        <td id="T_9ce81_row5_col1" class="data row5 col1" >商业贸易</td>
                        <td id="T_9ce81_row5_col2" class="data row5 col2" >0.80</td>
                        <td id="T_9ce81_row5_col3" class="data row5 col3" >49.64</td>
                        <td id="T_9ce81_row5_col4" class="data row5 col4" >1.56</td>
                        <td id="T_9ce81_row5_col5" class="data row5 col5" >20.19</td>
                        <td id="T_9ce81_row5_col6" class="data row5 col6" >40.48</td>
                        <td id="T_9ce81_row5_col7" class="data row5 col7" >-5.90</td>
                        <td id="T_9ce81_row5_col8" class="data row5 col8" >57.73</td>
                        <td id="T_9ce81_row5_col9" class="data row5 col9" >285.05</td>
                        <td id="T_9ce81_row5_col10" class="data row5 col10" >623.06</td>
                        <td id="T_9ce81_row5_col11" class="data row5 col11" >-147.69</td>
                        <td id="T_9ce81_row5_col12" class="data row5 col12" >206.14</td>
                        <td id="T_9ce81_row5_col13" class="data row5 col13" >0.00</td>
                        <td id="T_9ce81_row5_col14" class="data row5 col14" >326.09</td>
                        <td id="T_9ce81_row5_col15" class="data row5 col15" >69.37</td>
                        <td id="T_9ce81_row5_col16" class="data row5 col16" >0.24</td>
                        <td id="T_9ce81_row5_col17" class="data row5 col17" >6.79</td>
                        <td id="T_9ce81_row5_col18" class="data row5 col18" >-262396.07</td>
            </tr>
            <tr>
                        <th id="T_9ce81_level0_row6" class="row_heading level0 row6" >603360.SS</th>
                        <td id="T_9ce81_row6_col0" class="data row6 col0" >百傲化学</td>
                        <td id="T_9ce81_row6_col1" class="data row6 col1" >化工</td>
                        <td id="T_9ce81_row6_col2" class="data row6 col2" >0.07</td>
                        <td id="T_9ce81_row6_col3" class="data row6 col3" >30.87</td>
                        <td id="T_9ce81_row6_col4" class="data row6 col4" >18.07</td>
                        <td id="T_9ce81_row6_col5" class="data row6 col5" >21.22</td>
                        <td id="T_9ce81_row6_col6" class="data row6 col6" >29.17</td>
                        <td id="T_9ce81_row6_col7" class="data row6 col7" >26.58</td>
                        <td id="T_9ce81_row6_col8" class="data row6 col8" >39.60</td>
                        <td id="T_9ce81_row6_col9" class="data row6 col9" >42.80</td>
                        <td id="T_9ce81_row6_col10" class="data row6 col10" >69.54</td>
                        <td id="T_9ce81_row6_col11" class="data row6 col11" >73.49</td>
                        <td id="T_9ce81_row6_col12" class="data row6 col12" >178.99</td>
                        <td id="T_9ce81_row6_col13" class="data row6 col13" >5.79</td>
                        <td id="T_9ce81_row6_col14" class="data row6 col14" >6.72</td>
                        <td id="T_9ce81_row6_col15" class="data row6 col15" >20.04</td>
                        <td id="T_9ce81_row6_col16" class="data row6 col16" >0.47</td>
                        <td id="T_9ce81_row6_col17" class="data row6 col17" >3.68</td>
                        <td id="T_9ce81_row6_col18" class="data row6 col18" >36.47</td>
            </tr>
            <tr>
                        <th id="T_9ce81_level0_row7" class="row_heading level0 row7" >300771.SZ</th>
                        <td id="T_9ce81_row7_col0" class="data row7 col0" >智莱科技</td>
                        <td id="T_9ce81_row7_col1" class="data row7 col1" >计算机</td>
                        <td id="T_9ce81_row7_col2" class="data row7 col2" >0.12</td>
                        <td id="T_9ce81_row7_col3" class="data row7 col3" >12.01</td>
                        <td id="T_9ce81_row7_col4" class="data row7 col4" >8.40</td>
                        <td id="T_9ce81_row7_col5" class="data row7 col5" >23.16</td>
                        <td id="T_9ce81_row7_col6" class="data row7 col6" >23.88</td>
                        <td id="T_9ce81_row7_col7" class="data row7 col7" >26.16</td>
                        <td id="T_9ce81_row7_col8" class="data row7 col8" >32.91</td>
                        <td id="T_9ce81_row7_col9" class="data row7 col9" >34.01</td>
                        <td id="T_9ce81_row7_col10" class="data row7 col10" >49.62</td>
                        <td id="T_9ce81_row7_col11" class="data row7 col11" >17.60</td>
                        <td id="T_9ce81_row7_col12" class="data row7 col12" >38.43</td>
                        <td id="T_9ce81_row7_col13" class="data row7 col13" >2.65</td>
                        <td id="T_9ce81_row7_col14" class="data row7 col14" >6.17</td>
                        <td id="T_9ce81_row7_col15" class="data row7 col15" >17.55</td>
                        <td id="T_9ce81_row7_col16" class="data row7 col16" >0.52</td>
                        <td id="T_9ce81_row7_col17" class="data row7 col17" >3.73</td>
                        <td id="T_9ce81_row7_col18" class="data row7 col18" >-40.60</td>
            </tr>
            <tr>
                        <th id="T_9ce81_level0_row8" class="row_heading level0 row8" >603160.SS</th>
                        <td id="T_9ce81_row8_col0" class="data row8 col0" >汇顶科技</td>
                        <td id="T_9ce81_row8_col1" class="data row8 col1" >电子</td>
                        <td id="T_9ce81_row8_col2" class="data row8 col2" >0.88</td>
                        <td id="T_9ce81_row8_col3" class="data row8 col3" >18.72</td>
                        <td id="T_9ce81_row8_col4" class="data row8 col4" >11.10</td>
                        <td id="T_9ce81_row8_col5" class="data row8 col5" >25.04</td>
                        <td id="T_9ce81_row8_col6" class="data row8 col6" >26.16</td>
                        <td id="T_9ce81_row8_col7" class="data row8 col7" >26.11</td>
                        <td id="T_9ce81_row8_col8" class="data row8 col8" >41.45</td>
                        <td id="T_9ce81_row8_col9" class="data row8 col9" >55.80</td>
                        <td id="T_9ce81_row8_col10" class="data row8 col10" >135.49</td>
                        <td id="T_9ce81_row8_col11" class="data row8 col11" >18.94</td>
                        <td id="T_9ce81_row8_col12" class="data row8 col12" >140.73</td>
                        <td id="T_9ce81_row8_col13" class="data row8 col13" >21.96</td>
                        <td id="T_9ce81_row8_col14" class="data row8 col14" >62.48</td>
                        <td id="T_9ce81_row8_col15" class="data row8 col15" >36.88</td>
                        <td id="T_9ce81_row8_col16" class="data row8 col16" >0.66</td>
                        <td id="T_9ce81_row8_col17" class="data row8 col17" >59.42</td>
                        <td id="T_9ce81_row8_col18" class="data row8 col18" >-170.64</td>
            </tr>
            <tr>
                        <th id="T_9ce81_level0_row9" class="row_heading level0 row9" >300033.SZ</th>
                        <td id="T_9ce81_row9_col0" class="data row9 col0" >同花顺</td>
                        <td id="T_9ce81_row9_col1" class="data row9 col1" >计算机</td>
                        <td id="T_9ce81_row9_col2" class="data row9 col2" >1.48</td>
                        <td id="T_9ce81_row9_col3" class="data row9 col3" >26.99</td>
                        <td id="T_9ce81_row9_col4" class="data row9 col4" >2.59</td>
                        <td id="T_9ce81_row9_col5" class="data row9 col5" >24.34</td>
                        <td id="T_9ce81_row9_col6" class="data row9 col6" >52.33</td>
                        <td id="T_9ce81_row9_col7" class="data row9 col7" >29.08</td>
                        <td id="T_9ce81_row9_col8" class="data row9 col8" >32.56</td>
                        <td id="T_9ce81_row9_col9" class="data row9 col9" >40.34</td>
                        <td id="T_9ce81_row9_col10" class="data row9 col10" >52.36</td>
                        <td id="T_9ce81_row9_col11" class="data row9 col11" >63.18</td>
                        <td id="T_9ce81_row9_col12" class="data row9 col12" >90.96</td>
                        <td id="T_9ce81_row9_col13" class="data row9 col13" >47.92</td>
                        <td id="T_9ce81_row9_col14" class="data row9 col14" >32.87</td>
                        <td id="T_9ce81_row9_col15" class="data row9 col15" >35.06</td>
                        <td id="T_9ce81_row9_col16" class="data row9 col16" >0.87</td>
                        <td id="T_9ce81_row9_col17" class="data row9 col17" >61.94</td>
                        <td id="T_9ce81_row9_col18" class="data row9 col18" >-29.26</td>
            </tr>
            <tr>
                        <th id="T_9ce81_level0_row10" class="row_heading level0 row10" >300782.SZ</th>
                        <td id="T_9ce81_row10_col0" class="data row10 col0" >卓胜微</td>
                        <td id="T_9ce81_row10_col1" class="data row10 col1" >电子</td>
                        <td id="T_9ce81_row10_col2" class="data row10 col2" >2.74</td>
                        <td id="T_9ce81_row10_col3" class="data row10 col3" >14.18</td>
                        <td id="T_9ce81_row10_col4" class="data row10 col4" >13.48</td>
                        <td id="T_9ce81_row10_col5" class="data row10 col5" >39.60</td>
                        <td id="T_9ce81_row10_col6" class="data row10 col6" >32.25</td>
                        <td id="T_9ce81_row10_col7" class="data row10 col7" >83.09</td>
                        <td id="T_9ce81_row10_col8" class="data row10 col8" >87.66</td>
                        <td id="T_9ce81_row10_col9" class="data row10 col9" >105.87</td>
                        <td id="T_9ce81_row10_col10" class="data row10 col10" >105.71</td>
                        <td id="T_9ce81_row10_col11" class="data row10 col11" >-780.68</td>
                        <td id="T_9ce81_row10_col12" class="data row10 col12" >1228.39</td>
                        <td id="T_9ce81_row10_col13" class="data row10 col13" >-865.91</td>
                        <td id="T_9ce81_row10_col14" class="data row10 col14" >47.57</td>
                        <td id="T_9ce81_row10_col15" class="data row10 col15" >97.95</td>
                        <td id="T_9ce81_row10_col16" class="data row10 col16" >0.93</td>
                        <td id="T_9ce81_row10_col17" class="data row10 col17" >138.43</td>
                        <td id="T_9ce81_row10_col18" class="data row10 col18" >0.00</td>
            </tr>
            <tr>
                        <th id="T_9ce81_level0_row11" class="row_heading level0 row11" >002677.SZ</th>
                        <td id="T_9ce81_row11_col0" class="data row11 col0" >浙江美大</td>
                        <td id="T_9ce81_row11_col1" class="data row11 col1" >家用电器</td>
                        <td id="T_9ce81_row11_col2" class="data row11 col2" >0.46</td>
                        <td id="T_9ce81_row11_col3" class="data row11 col3" >21.80</td>
                        <td id="T_9ce81_row11_col4" class="data row11 col4" >1.94</td>
                        <td id="T_9ce81_row11_col5" class="data row11 col5" >28.29</td>
                        <td id="T_9ce81_row11_col6" class="data row11 col6" >28.67</td>
                        <td id="T_9ce81_row11_col7" class="data row11 col7" >20.62</td>
                        <td id="T_9ce81_row11_col8" class="data row11 col8" >15.69</td>
                        <td id="T_9ce81_row11_col9" class="data row11 col9" >21.24</td>
                        <td id="T_9ce81_row11_col10" class="data row11 col10" >2.82</td>
                        <td id="T_9ce81_row11_col11" class="data row11 col11" >44.23</td>
                        <td id="T_9ce81_row11_col12" class="data row11 col12" >89.38</td>
                        <td id="T_9ce81_row11_col13" class="data row11 col13" >11.82</td>
                        <td id="T_9ce81_row11_col14" class="data row11 col14" >9.18</td>
                        <td id="T_9ce81_row11_col15" class="data row11 col15" >20.12</td>
                        <td id="T_9ce81_row11_col16" class="data row11 col16" >0.95</td>
                        <td id="T_9ce81_row11_col17" class="data row11 col17" >12.55</td>
                        <td id="T_9ce81_row11_col18" class="data row11 col18" >-6.23</td>
            </tr>
            <tr>
                        <th id="T_9ce81_level0_row12" class="row_heading level0 row12" >600989.SS</th>
                        <td id="T_9ce81_row12_col0" class="data row12 col0" >宝丰能源</td>
                        <td id="T_9ce81_row12_col1" class="data row12 col1" >化工</td>
                        <td id="T_9ce81_row12_col2" class="data row12 col2" >1.30</td>
                        <td id="T_9ce81_row12_col3" class="data row12 col3" >32.03</td>
                        <td id="T_9ce81_row12_col4" class="data row12 col4" >3.64</td>
                        <td id="T_9ce81_row12_col5" class="data row12 col5" >21.66</td>
                        <td id="T_9ce81_row12_col6" class="data row12 col6" >27.28</td>
                        <td id="T_9ce81_row12_col7" class="data row12 col7" >9.15</td>
                        <td id="T_9ce81_row12_col8" class="data row12 col8" >7.22</td>
                        <td id="T_9ce81_row12_col9" class="data row12 col9" >16.96</td>
                        <td id="T_9ce81_row12_col10" class="data row12 col10" >12.43</td>
                        <td id="T_9ce81_row12_col11" class="data row12 col11" >-184.25</td>
                        <td id="T_9ce81_row12_col12" class="data row12 col12" >173.78</td>
                        <td id="T_9ce81_row12_col13" class="data row12 col13" >-9.17</td>
                        <td id="T_9ce81_row12_col14" class="data row12 col14" >74.03</td>
                        <td id="T_9ce81_row12_col15" class="data row12 col15" >19.01</td>
                        <td id="T_9ce81_row12_col16" class="data row12 col16" >1.12</td>
                        <td id="T_9ce81_row12_col17" class="data row12 col17" >105.09</td>
                        <td id="T_9ce81_row12_col18" class="data row12 col18" >0.00</td>
            </tr>
            <tr>
                        <th id="T_9ce81_level0_row13" class="row_heading level0 row13" >600570.SS</th>
                        <td id="T_9ce81_row13_col0" class="data row13 col0" >恒生电子</td>
                        <td id="T_9ce81_row13_col1" class="data row13 col1" >计算机</td>
                        <td id="T_9ce81_row13_col2" class="data row13 col2" >5.11</td>
                        <td id="T_9ce81_row13_col3" class="data row13 col3" >49.48</td>
                        <td id="T_9ce81_row13_col4" class="data row13 col4" >14.02</td>
                        <td id="T_9ce81_row13_col5" class="data row13 col5" >24.06</td>
                        <td id="T_9ce81_row13_col6" class="data row13 col6" >26.42</td>
                        <td id="T_9ce81_row13_col7" class="data row13 col7" >16.27</td>
                        <td id="T_9ce81_row13_col8" class="data row13 col8" >7.59</td>
                        <td id="T_9ce81_row13_col9" class="data row13 col9" >49.90</td>
                        <td id="T_9ce81_row13_col10" class="data row13 col10" >64.01</td>
                        <td id="T_9ce81_row13_col11" class="data row13 col11" >10.32</td>
                        <td id="T_9ce81_row13_col12" class="data row13 col12" >20.60</td>
                        <td id="T_9ce81_row13_col13" class="data row13 col13" >13.02</td>
                        <td id="T_9ce81_row13_col14" class="data row13 col14" >38.43</td>
                        <td id="T_9ce81_row13_col15" class="data row13 col15" >60.65</td>
                        <td id="T_9ce81_row13_col16" class="data row13 col16" >1.22</td>
                        <td id="T_9ce81_row13_col17" class="data row13 col17" >93.11</td>
                        <td id="T_9ce81_row13_col18" class="data row13 col18" >-615.42</td>
            </tr>
            <tr>
                        <th id="T_9ce81_level0_row14" class="row_heading level0 row14" >002901.SZ</th>
                        <td id="T_9ce81_row14_col0" class="data row14 col0" >大博医疗</td>
                        <td id="T_9ce81_row14_col1" class="data row14 col1" >医药生物</td>
                        <td id="T_9ce81_row14_col2" class="data row14 col2" >0.08</td>
                        <td id="T_9ce81_row14_col3" class="data row14 col3" >21.68</td>
                        <td id="T_9ce81_row14_col4" class="data row14 col4" >19.30</td>
                        <td id="T_9ce81_row14_col5" class="data row14 col5" >28.78</td>
                        <td id="T_9ce81_row14_col6" class="data row14 col6" >45.57</td>
                        <td id="T_9ce81_row14_col7" class="data row14 col7" >40.40</td>
                        <td id="T_9ce81_row14_col8" class="data row14 col8" >19.39</td>
                        <td id="T_9ce81_row14_col9" class="data row14 col9" >28.58</td>
                        <td id="T_9ce81_row14_col10" class="data row14 col10" >5.35</td>
                        <td id="T_9ce81_row14_col11" class="data row14 col11" >-2.48</td>
                        <td id="T_9ce81_row14_col12" class="data row14 col12" >56.39</td>
                        <td id="T_9ce81_row14_col13" class="data row14 col13" >2.36</td>
                        <td id="T_9ce81_row14_col14" class="data row14 col14" >8.70</td>
                        <td id="T_9ce81_row14_col15" class="data row14 col15" >46.60</td>
                        <td id="T_9ce81_row14_col16" class="data row14 col16" >1.63</td>
                        <td id="T_9ce81_row14_col17" class="data row14 col17" >30.15</td>
                        <td id="T_9ce81_row14_col18" class="data row14 col18" >-1176.12</td>
            </tr>
            <tr>
                        <th id="T_9ce81_level0_row15" class="row_heading level0 row15" >002507.SZ</th>
                        <td id="T_9ce81_row15_col0" class="data row15 col0" >涪陵榨菜</td>
                        <td id="T_9ce81_row15_col1" class="data row15 col1" >食品饮料</td>
                        <td id="T_9ce81_row15_col2" class="data row15 col2" >0.59</td>
                        <td id="T_9ce81_row15_col3" class="data row15 col3" >14.06</td>
                        <td id="T_9ce81_row15_col4" class="data row15 col4" >0.49</td>
                        <td id="T_9ce81_row15_col5" class="data row15 col5" >23.03</td>
                        <td id="T_9ce81_row15_col6" class="data row15 col6" >31.60</td>
                        <td id="T_9ce81_row15_col7" class="data row15 col7" >14.70</td>
                        <td id="T_9ce81_row15_col8" class="data row15 col8" >11.00</td>
                        <td id="T_9ce81_row15_col9" class="data row15 col9" >26.55</td>
                        <td id="T_9ce81_row15_col10" class="data row15 col10" >34.20</td>
                        <td id="T_9ce81_row15_col11" class="data row15 col11" >-290.57</td>
                        <td id="T_9ce81_row15_col12" class="data row15 col12" >344.89</td>
                        <td id="T_9ce81_row15_col13" class="data row15 col13" >-24.51</td>
                        <td id="T_9ce81_row15_col14" class="data row15 col14" >15.11</td>
                        <td id="T_9ce81_row15_col15" class="data row15 col15" >43.71</td>
                        <td id="T_9ce81_row15_col16" class="data row15 col16" >1.65</td>
                        <td id="T_9ce81_row15_col17" class="data row15 col17" >35.61</td>
                        <td id="T_9ce81_row15_col18" class="data row15 col18" >0.00</td>
            </tr>
            <tr>
                        <th id="T_9ce81_level0_row16" class="row_heading level0 row16" >300529.SZ</th>
                        <td id="T_9ce81_row16_col0" class="data row16 col0" >健帆生物</td>
                        <td id="T_9ce81_row16_col1" class="data row16 col1" >医药生物</td>
                        <td id="T_9ce81_row16_col2" class="data row16 col2" >0.97</td>
                        <td id="T_9ce81_row16_col3" class="data row16 col3" >11.91</td>
                        <td id="T_9ce81_row16_col4" class="data row16 col4" >11.56</td>
                        <td id="T_9ce81_row16_col5" class="data row16 col5" >25.48</td>
                        <td id="T_9ce81_row16_col6" class="data row16 col6" >40.97</td>
                        <td id="T_9ce81_row16_col7" class="data row16 col7" >39.53</td>
                        <td id="T_9ce81_row16_col8" class="data row16 col8" >2.86</td>
                        <td id="T_9ce81_row16_col9" class="data row16 col9" >45.56</td>
                        <td id="T_9ce81_row16_col10" class="data row16 col10" >6.74</td>
                        <td id="T_9ce81_row16_col11" class="data row16 col11" >68.14</td>
                        <td id="T_9ce81_row16_col12" class="data row16 col12" >3.67</td>
                        <td id="T_9ce81_row16_col13" class="data row16 col13" >18.05</td>
                        <td id="T_9ce81_row16_col14" class="data row16 col14" >19.54</td>
                        <td id="T_9ce81_row16_col15" class="data row16 col15" >75.24</td>
                        <td id="T_9ce81_row16_col16" class="data row16 col16" >1.65</td>
                        <td id="T_9ce81_row16_col17" class="data row16 col17" >73.29</td>
                        <td id="T_9ce81_row16_col18" class="data row16 col18" >-305.98</td>
            </tr>
            <tr>
                        <th id="T_9ce81_level0_row17" class="row_heading level0 row17" >300628.SZ</th>
                        <td id="T_9ce81_row17_col0" class="data row17 col0" >亿联网络</td>
                        <td id="T_9ce81_row17_col1" class="data row17 col1" >通信</td>
                        <td id="T_9ce81_row17_col2" class="data row17 col2" >3.61</td>
                        <td id="T_9ce81_row17_col3" class="data row17 col3" >9.97</td>
                        <td id="T_9ce81_row17_col4" class="data row17 col4" >18.77</td>
                        <td id="T_9ce81_row17_col5" class="data row17 col5" >24.39</td>
                        <td id="T_9ce81_row17_col6" class="data row17 col6" >46.38</td>
                        <td id="T_9ce81_row17_col7" class="data row17 col7" >26.19</td>
                        <td id="T_9ce81_row17_col8" class="data row17 col8" >13.83</td>
                        <td id="T_9ce81_row17_col9" class="data row17 col9" >30.91</td>
                        <td id="T_9ce81_row17_col10" class="data row17 col10" >23.73</td>
                        <td id="T_9ce81_row17_col11" class="data row17 col11" >28.68</td>
                        <td id="T_9ce81_row17_col12" class="data row17 col12" >12.49</td>
                        <td id="T_9ce81_row17_col13" class="data row17 col13" >18.85</td>
                        <td id="T_9ce81_row17_col14" class="data row17 col14" >26.78</td>
                        <td id="T_9ce81_row17_col15" class="data row17 col15" >53.24</td>
                        <td id="T_9ce81_row17_col16" class="data row17 col16" >1.72</td>
                        <td id="T_9ce81_row17_col17" class="data row17 col17" >68.53</td>
                        <td id="T_9ce81_row17_col18" class="data row17 col18" >-263.46</td>
            </tr>
            <tr>
                        <th id="T_9ce81_level0_row18" class="row_heading level0 row18" >603444.SS</th>
                        <td id="T_9ce81_row18_col0" class="data row18 col0" >吉比特</td>
                        <td id="T_9ce81_row18_col1" class="data row18 col1" >传媒</td>
                        <td id="T_9ce81_row18_col2" class="data row18 col2" >2.83</td>
                        <td id="T_9ce81_row18_col3" class="data row18 col3" >21.16</td>
                        <td id="T_9ce81_row18_col4" class="data row18 col4" >10.85</td>
                        <td id="T_9ce81_row18_col5" class="data row18 col5" >26.31</td>
                        <td id="T_9ce81_row18_col6" class="data row18 col6" >40.37</td>
                        <td id="T_9ce81_row18_col7" class="data row18 col7" >24.14</td>
                        <td id="T_9ce81_row18_col8" class="data row18 col8" >8.35</td>
                        <td id="T_9ce81_row18_col9" class="data row18 col9" >19.94</td>
                        <td id="T_9ce81_row18_col10" class="data row18 col10" >8.77</td>
                        <td id="T_9ce81_row18_col11" class="data row18 col11" >66.50</td>
                        <td id="T_9ce81_row18_col12" class="data row18 col12" >112.96</td>
                        <td id="T_9ce81_row18_col13" class="data row18 col13" >48.73</td>
                        <td id="T_9ce81_row18_col14" class="data row18 col14" >16.84</td>
                        <td id="T_9ce81_row18_col15" class="data row18 col15" >34.59</td>
                        <td id="T_9ce81_row18_col16" class="data row18 col16" >1.73</td>
                        <td id="T_9ce81_row18_col17" class="data row18 col17" >37.69</td>
                        <td id="T_9ce81_row18_col18" class="data row18 col18" >22.66</td>
            </tr>
            <tr>
                        <th id="T_9ce81_level0_row19" class="row_heading level0 row19" >600779.SS</th>
                        <td id="T_9ce81_row19_col0" class="data row19 col0" >水井坊</td>
                        <td id="T_9ce81_row19_col1" class="data row19 col1" >食品饮料</td>
                        <td id="T_9ce81_row19_col2" class="data row19 col2" >1.22</td>
                        <td id="T_9ce81_row19_col3" class="data row19 col3" >51.09</td>
                        <td id="T_9ce81_row19_col4" class="data row19 col4" >0.40</td>
                        <td id="T_9ce81_row19_col5" class="data row19 col5" >31.45</td>
                        <td id="T_9ce81_row19_col6" class="data row19 col6" >21.15</td>
                        <td id="T_9ce81_row19_col7" class="data row19 col7" >16.03</td>
                        <td id="T_9ce81_row19_col8" class="data row19 col8" >27.60</td>
                        <td id="T_9ce81_row19_col9" class="data row19 col9" >34.61</td>
                        <td id="T_9ce81_row19_col10" class="data row19 col10" >42.67</td>
                        <td id="T_9ce81_row19_col11" class="data row19 col11" >23.72</td>
                        <td id="T_9ce81_row19_col12" class="data row19 col12" >83.94</td>
                        <td id="T_9ce81_row19_col13" class="data row19 col13" >12.13</td>
                        <td id="T_9ce81_row19_col14" class="data row19 col14" >18.12</td>
                        <td id="T_9ce81_row19_col15" class="data row19 col15" >64.50</td>
                        <td id="T_9ce81_row19_col16" class="data row19 col16" >1.86</td>
                        <td id="T_9ce81_row19_col17" class="data row19 col17" >61.91</td>
                        <td id="T_9ce81_row19_col18" class="data row19 col18" >-410.18</td>
            </tr>
            <tr>
                        <th id="T_9ce81_level0_row20" class="row_heading level0 row20" >002833.SZ</th>
                        <td id="T_9ce81_row20_col0" class="data row20 col0" >弘亚数控</td>
                        <td id="T_9ce81_row20_col1" class="data row20 col1" >机械设备</td>
                        <td id="T_9ce81_row20_col2" class="data row20 col2" >0.38</td>
                        <td id="T_9ce81_row20_col3" class="data row20 col3" >26.31</td>
                        <td id="T_9ce81_row20_col4" class="data row20 col4" >7.33</td>
                        <td id="T_9ce81_row20_col5" class="data row20 col5" >22.78</td>
                        <td id="T_9ce81_row20_col6" class="data row20 col6" >23.79</td>
                        <td id="T_9ce81_row20_col7" class="data row20 col7" >28.09</td>
                        <td id="T_9ce81_row20_col8" class="data row20 col8" >17.93</td>
                        <td id="T_9ce81_row20_col9" class="data row20 col9" >14.35</td>
                        <td id="T_9ce81_row20_col10" class="data row20 col10" >1.54</td>
                        <td id="T_9ce81_row20_col11" class="data row20 col11" >6.66</td>
                        <td id="T_9ce81_row20_col12" class="data row20 col12" >10.44</td>
                        <td id="T_9ce81_row20_col13" class="data row20 col13" >3.53</td>
                        <td id="T_9ce81_row20_col14" class="data row20 col14" >5.36</td>
                        <td id="T_9ce81_row20_col15" class="data row20 col15" >26.98</td>
                        <td id="T_9ce81_row20_col16" class="data row20 col16" >1.88</td>
                        <td id="T_9ce81_row20_col17" class="data row20 col17" >11.24</td>
                        <td id="T_9ce81_row20_col18" class="data row20 col18" >-218.13</td>
            </tr>
            <tr>
                        <th id="T_9ce81_level0_row21" class="row_heading level0 row21" >603195.SS</th>
                        <td id="T_9ce81_row21_col0" class="data row21 col0" >公牛集团</td>
                        <td id="T_9ce81_row21_col1" class="data row21 col1" >轻工制造</td>
                        <td id="T_9ce81_row21_col2" class="data row21 col2" >3.04</td>
                        <td id="T_9ce81_row21_col3" class="data row21 col3" >26.53</td>
                        <td id="T_9ce81_row21_col4" class="data row21 col4" >3.09</td>
                        <td id="T_9ce81_row21_col5" class="data row21 col5" >50.07</td>
                        <td id="T_9ce81_row21_col6" class="data row21 col6" >20.55</td>
                        <td id="T_9ce81_row21_col7" class="data row21 col7" >12.02</td>
                        <td id="T_9ce81_row21_col8" class="data row21 col8" >12.60</td>
                        <td id="T_9ce81_row21_col9" class="data row21 col9" >22.75</td>
                        <td id="T_9ce81_row21_col10" class="data row21 col10" >19.65</td>
                        <td id="T_9ce81_row21_col11" class="data row21 col11" >61.00</td>
                        <td id="T_9ce81_row21_col12" class="data row21 col12" >30.19</td>
                        <td id="T_9ce81_row21_col13" class="data row21 col13" >86.27</td>
                        <td id="T_9ce81_row21_col14" class="data row21 col14" >42.75</td>
                        <td id="T_9ce81_row21_col15" class="data row21 col15" >43.67</td>
                        <td id="T_9ce81_row21_col16" class="data row21 col16" >1.92</td>
                        <td id="T_9ce81_row21_col17" class="data row21 col17" >120.10</td>
                        <td id="T_9ce81_row21_col18" class="data row21 col18" >-39.22</td>
            </tr>
            <tr>
                        <th id="T_9ce81_level0_row22" class="row_heading level0 row22" >300760.SZ</th>
                        <td id="T_9ce81_row22_col0" class="data row22 col0" >迈瑞医疗</td>
                        <td id="T_9ce81_row22_col1" class="data row22 col1" >医药生物</td>
                        <td id="T_9ce81_row22_col2" class="data row22 col2" >3.25</td>
                        <td id="T_9ce81_row22_col3" class="data row22 col3" >30.07</td>
                        <td id="T_9ce81_row22_col4" class="data row22 col4" >8.72</td>
                        <td id="T_9ce81_row22_col5" class="data row22 col5" >29.36</td>
                        <td id="T_9ce81_row22_col6" class="data row22 col6" >27.54</td>
                        <td id="T_9ce81_row22_col7" class="data row22 col7" >23.49</td>
                        <td id="T_9ce81_row22_col8" class="data row22 col8" >3.33</td>
                        <td id="T_9ce81_row22_col9" class="data row22 col9" >37.24</td>
                        <td id="T_9ce81_row22_col10" class="data row22 col10" >9.89</td>
                        <td id="T_9ce81_row22_col11" class="data row22 col11" >43.62</td>
                        <td id="T_9ce81_row22_col12" class="data row22 col12" >44.39</td>
                        <td id="T_9ce81_row22_col13" class="data row22 col13" >157.19</td>
                        <td id="T_9ce81_row22_col14" class="data row22 col14" >136.70</td>
                        <td id="T_9ce81_row22_col15" class="data row22 col15" >83.18</td>
                        <td id="T_9ce81_row22_col16" class="data row22 col16" >2.23</td>
                        <td id="T_9ce81_row22_col17" class="data row22 col17" >587.18</td>
                        <td id="T_9ce81_row22_col18" class="data row22 col18" >-273.55</td>
            </tr>
            <tr>
                        <th id="T_9ce81_level0_row23" class="row_heading level0 row23" >300832.SZ</th>
                        <td id="T_9ce81_row23_col0" class="data row23 col0" >新产业</td>
                        <td id="T_9ce81_row23_col1" class="data row23 col1" >医药生物</td>
                        <td id="T_9ce81_row23_col2" class="data row23 col2" >0.47</td>
                        <td id="T_9ce81_row23_col3" class="data row23 col3" >9.45</td>
                        <td id="T_9ce81_row23_col4" class="data row23 col4" >10.07</td>
                        <td id="T_9ce81_row23_col5" class="data row23 col5" >25.97</td>
                        <td id="T_9ce81_row23_col6" class="data row23 col6" >46.52</td>
                        <td id="T_9ce81_row23_col7" class="data row23 col7" >24.46</td>
                        <td id="T_9ce81_row23_col8" class="data row23 col8" >5.26</td>
                        <td id="T_9ce81_row23_col9" class="data row23 col9" >20.61</td>
                        <td id="T_9ce81_row23_col10" class="data row23 col10" >8.85</td>
                        <td id="T_9ce81_row23_col11" class="data row23 col11" >27.94</td>
                        <td id="T_9ce81_row23_col12" class="data row23 col12" >13.10</td>
                        <td id="T_9ce81_row23_col13" class="data row23 col13" >12.63</td>
                        <td id="T_9ce81_row23_col14" class="data row23 col14" >15.80</td>
                        <td id="T_9ce81_row23_col15" class="data row23 col15" >52.44</td>
                        <td id="T_9ce81_row23_col16" class="data row23 col16" >2.54</td>
                        <td id="T_9ce81_row23_col17" class="data row23 col17" >52.26</td>
                        <td id="T_9ce81_row23_col18" class="data row23 col18" >-313.68</td>
            </tr>
            <tr>
                        <th id="T_9ce81_level0_row24" class="row_heading level0 row24" >600519.SS</th>
                        <td id="T_9ce81_row24_col0" class="data row24 col0" >贵州茅台</td>
                        <td id="T_9ce81_row24_col1" class="data row24 col1" >食品饮料</td>
                        <td id="T_9ce81_row24_col2" class="data row24 col2" >30.99</td>
                        <td id="T_9ce81_row24_col3" class="data row24 col3" >21.40</td>
                        <td id="T_9ce81_row24_col4" class="data row24 col4" >1.65</td>
                        <td id="T_9ce81_row24_col5" class="data row24 col5" >30.01</td>
                        <td id="T_9ce81_row24_col6" class="data row24 col6" >47.94</td>
                        <td id="T_9ce81_row24_col7" class="data row24 col7" >17.87</td>
                        <td id="T_9ce81_row24_col8" class="data row24 col8" >7.86</td>
                        <td id="T_9ce81_row24_col9" class="data row24 col9" >20.13</td>
                        <td id="T_9ce81_row24_col10" class="data row24 col10" >8.75</td>
                        <td id="T_9ce81_row24_col11" class="data row24 col11" >37.59</td>
                        <td id="T_9ce81_row24_col12" class="data row24 col12" >45.08</td>
                        <td id="T_9ce81_row24_col13" class="data row24 col13" >1189.50</td>
                        <td id="T_9ce81_row24_col14" class="data row24 col14" >796.91</td>
                        <td id="T_9ce81_row24_col15" class="data row24 col15" >58.69</td>
                        <td id="T_9ce81_row24_col16" class="data row24 col16" >2.92</td>
                        <td id="T_9ce81_row24_col17" class="data row24 col17" >2791.27</td>
                        <td id="T_9ce81_row24_col18" class="data row24 col18" >-134.66</td>
            </tr>
            <tr>
                        <th id="T_9ce81_level0_row25" class="row_heading level0 row25" >300896.SZ</th>
                        <td id="T_9ce81_row25_col0" class="data row25 col0" >爱美客</td>
                        <td id="T_9ce81_row25_col1" class="data row25 col1" >医药生物</td>
                        <td id="T_9ce81_row25_col2" class="data row25 col2" >0.87</td>
                        <td id="T_9ce81_row25_col3" class="data row25 col3" >2.19</td>
                        <td id="T_9ce81_row25_col4" class="data row25 col4" >6.39</td>
                        <td id="T_9ce81_row25_col5" class="data row25 col5" >28.05</td>
                        <td id="T_9ce81_row25_col6" class="data row25 col6" >48.00</td>
                        <td id="T_9ce81_row25_col7" class="data row25 col7" >48.40</td>
                        <td id="T_9ce81_row25_col8" class="data row25 col8" >23.55</td>
                        <td id="T_9ce81_row25_col9" class="data row25 col9" >80.70</td>
                        <td id="T_9ce81_row25_col10" class="data row25 col10" >58.94</td>
                        <td id="T_9ce81_row25_col11" class="data row25 col11" >120.48</td>
                        <td id="T_9ce81_row25_col12" class="data row25 col12" >73.47</td>
                        <td id="T_9ce81_row25_col13" class="data row25 col13" >24.71</td>
                        <td id="T_9ce81_row25_col14" class="data row25 col14" >16.26</td>
                        <td id="T_9ce81_row25_col15" class="data row25 col15" >236.42</td>
                        <td id="T_9ce81_row25_col16" class="data row25 col16" >2.93</td>
                        <td id="T_9ce81_row25_col17" class="data row25 col17" >134.15</td>
                        <td id="T_9ce81_row25_col18" class="data row25 col18" >-442.86</td>
            </tr>
            <tr>
                        <th id="T_9ce81_level0_row26" class="row_heading level0 row26" >603983.SS</th>
                        <td id="T_9ce81_row26_col0" class="data row26 col0" >丸美股份</td>
                        <td id="T_9ce81_row26_col1" class="data row26 col1" >化工</td>
                        <td id="T_9ce81_row26_col2" class="data row26 col2" >0.14</td>
                        <td id="T_9ce81_row26_col3" class="data row26 col3" >20.93</td>
                        <td id="T_9ce81_row26_col4" class="data row26 col4" >0.50</td>
                        <td id="T_9ce81_row26_col5" class="data row26 col5" >24.39</td>
                        <td id="T_9ce81_row26_col6" class="data row26 col6" >26.16</td>
                        <td id="T_9ce81_row26_col7" class="data row26 col7" >9.24</td>
                        <td id="T_9ce81_row26_col8" class="data row26 col8" >10.74</td>
                        <td id="T_9ce81_row26_col9" class="data row26 col9" >15.77</td>
                        <td id="T_9ce81_row26_col10" class="data row26 col10" >22.62</td>
                        <td id="T_9ce81_row26_col11" class="data row26 col11" >-49.63</td>
                        <td id="T_9ce81_row26_col12" class="data row26 col12" >119.58</td>
                        <td id="T_9ce81_row26_col13" class="data row26 col13" >0.49</td>
                        <td id="T_9ce81_row26_col14" class="data row26 col14" >8.16</td>
                        <td id="T_9ce81_row26_col15" class="data row26 col15" >52.45</td>
                        <td id="T_9ce81_row26_col16" class="data row26 col16" >3.33</td>
                        <td id="T_9ce81_row26_col17" class="data row26 col17" >23.37</td>
                        <td id="T_9ce81_row26_col18" class="data row26 col18" >-4661.90</td>
            </tr>
            <tr>
                        <th id="T_9ce81_level0_row27" class="row_heading level0 row27" >300595.SZ</th>
                        <td id="T_9ce81_row27_col0" class="data row27 col0" >欧普康视</td>
                        <td id="T_9ce81_row27_col1" class="data row27 col1" >医药生物</td>
                        <td id="T_9ce81_row27_col2" class="data row27 col2" >1.21</td>
                        <td id="T_9ce81_row27_col3" class="data row27 col3" >10.02</td>
                        <td id="T_9ce81_row27_col4" class="data row27 col4" >18.19</td>
                        <td id="T_9ce81_row27_col5" class="data row27 col5" >21.91</td>
                        <td id="T_9ce81_row27_col6" class="data row27 col6" >48.20</td>
                        <td id="T_9ce81_row27_col7" class="data row27 col7" >40.94</td>
                        <td id="T_9ce81_row27_col8" class="data row27 col8" >6.26</td>
                        <td id="T_9ce81_row27_col9" class="data row27 col9" >42.15</td>
                        <td id="T_9ce81_row27_col10" class="data row27 col10" >1.09</td>
                        <td id="T_9ce81_row27_col11" class="data row27 col11" >54.08</td>
                        <td id="T_9ce81_row27_col12" class="data row27 col12" >33.61</td>
                        <td id="T_9ce81_row27_col13" class="data row27 col13" >7.55</td>
                        <td id="T_9ce81_row27_col14" class="data row27 col14" >9.48</td>
                        <td id="T_9ce81_row27_col15" class="data row27 col15" >156.31</td>
                        <td id="T_9ce81_row27_col16" class="data row27 col16" >3.71</td>
                        <td id="T_9ce81_row27_col17" class="data row27 col17" >83.38</td>
                        <td id="T_9ce81_row27_col18" class="data row27 col18" >-1003.72</td>
            </tr>
            <tr>
                        <th id="T_9ce81_level0_row28" class="row_heading level0 row28" >603288.SS</th>
                        <td id="T_9ce81_row28_col0" class="data row28 col0" >海天味业</td>
                        <td id="T_9ce81_row28_col1" class="data row28 col1" >食品饮料</td>
                        <td id="T_9ce81_row28_col2" class="data row28 col2" >5.08</td>
                        <td id="T_9ce81_row28_col3" class="data row28 col3" >31.72</td>
                        <td id="T_9ce81_row28_col4" class="data row28 col4" >0.21</td>
                        <td id="T_9ce81_row28_col5" class="data row28 col5" >31.42</td>
                        <td id="T_9ce81_row28_col6" class="data row28 col6" >26.24</td>
                        <td id="T_9ce81_row28_col7" class="data row28 col7" >16.05</td>
                        <td id="T_9ce81_row28_col8" class="data row28 col8" >0.85</td>
                        <td id="T_9ce81_row28_col9" class="data row28 col9" >21.95</td>
                        <td id="T_9ce81_row28_col10" class="data row28 col10" >2.08</td>
                        <td id="T_9ce81_row28_col11" class="data row28 col11" >11.37</td>
                        <td id="T_9ce81_row28_col12" class="data row28 col12" >15.72</td>
                        <td id="T_9ce81_row28_col13" class="data row28 col13" >95.46</td>
                        <td id="T_9ce81_row28_col14" class="data row28 col14" >108.81</td>
                        <td id="T_9ce81_row28_col15" class="data row28 col15" >86.22</td>
                        <td id="T_9ce81_row28_col16" class="data row28 col16" >3.93</td>
                        <td id="T_9ce81_row28_col17" class="data row28 col17" >581.42</td>
                        <td id="T_9ce81_row28_col18" class="data row28 col18" >-509.06</td>
            </tr>
            <tr>
                        <th id="T_9ce81_level0_row29" class="row_heading level0 row29" >600436.SS</th>
                        <td id="T_9ce81_row29_col0" class="data row29 col0" >片仔癀</td>
                        <td id="T_9ce81_row29_col1" class="data row29 col1" >医药生物</td>
                        <td id="T_9ce81_row29_col2" class="data row29 col2" >2.72</td>
                        <td id="T_9ce81_row29_col3" class="data row29 col3" >19.10</td>
                        <td id="T_9ce81_row29_col4" class="data row29 col4" >10.00</td>
                        <td id="T_9ce81_row29_col5" class="data row29 col5" >21.07</td>
                        <td id="T_9ce81_row29_col6" class="data row29 col6" >23.85</td>
                        <td id="T_9ce81_row29_col7" class="data row29 col7" >20.72</td>
                        <td id="T_9ce81_row29_col8" class="data row29 col8" >7.30</td>
                        <td id="T_9ce81_row29_col9" class="data row29 col9" >27.83</td>
                        <td id="T_9ce81_row29_col10" class="data row29 col10" >11.96</td>
                        <td id="T_9ce81_row29_col11" class="data row29 col11" >-166.81</td>
                        <td id="T_9ce81_row29_col12" class="data row29 col12" >136.30</td>
                        <td id="T_9ce81_row29_col13" class="data row29 col13" >-1.10</td>
                        <td id="T_9ce81_row29_col14" class="data row29 col14" >31.61</td>
                        <td id="T_9ce81_row29_col15" class="data row29 col15" >130.91</td>
                        <td id="T_9ce81_row29_col16" class="data row29 col16" >4.70</td>
                        <td id="T_9ce81_row29_col17" class="data row29 col17" >231.59</td>
                        <td id="T_9ce81_row29_col18" class="data row29 col18" >0.00</td>
            </tr>
            <tr>
                        <th id="T_9ce81_level0_row30" class="row_heading level0 row30" >600763.SS</th>
                        <td id="T_9ce81_row30_col0" class="data row30 col0" >通策医疗</td>
                        <td id="T_9ce81_row30_col1" class="data row30 col1" >医药生物</td>
                        <td id="T_9ce81_row30_col2" class="data row30 col2" >2.18</td>
                        <td id="T_9ce81_row30_col3" class="data row30 col3" >23.37</td>
                        <td id="T_9ce81_row30_col4" class="data row30 col4" >4.92</td>
                        <td id="T_9ce81_row30_col5" class="data row30 col5" >23.98</td>
                        <td id="T_9ce81_row30_col6" class="data row30 col6" >21.89</td>
                        <td id="T_9ce81_row30_col7" class="data row30 col7" >21.36</td>
                        <td id="T_9ce81_row30_col8" class="data row30 col8" >11.87</td>
                        <td id="T_9ce81_row30_col9" class="data row30 col9" >33.13</td>
                        <td id="T_9ce81_row30_col10" class="data row30 col10" >24.64</td>
                        <td id="T_9ce81_row30_col11" class="data row30 col11" >38.60</td>
                        <td id="T_9ce81_row30_col12" class="data row30 col12" >81.59</td>
                        <td id="T_9ce81_row30_col13" class="data row30 col13" >12.56</td>
                        <td id="T_9ce81_row30_col14" class="data row30 col14" >10.71</td>
                        <td id="T_9ce81_row30_col15" class="data row30 col15" >172.58</td>
                        <td id="T_9ce81_row30_col16" class="data row30 col16" >5.21</td>
                        <td id="T_9ce81_row30_col17" class="data row30 col17" >116.68</td>
                        <td id="T_9ce81_row30_col18" class="data row30 col18" >-829.29</td>
            </tr>
            <tr>
                        <th id="T_9ce81_level0_row31" class="row_heading level0 row31" >000885.SZ</th>
                        <td id="T_9ce81_row31_col0" class="data row31 col0" >城发环境</td>
                        <td id="T_9ce81_row31_col1" class="data row31 col1" >交通运输</td>
                        <td id="T_9ce81_row31_col2" class="data row31 col2" >0.26</td>
                        <td id="T_9ce81_row31_col3" class="data row31 col3" >60.46</td>
                        <td id="T_9ce81_row31_col4" class="data row31 col4" >15.69</td>
                        <td id="T_9ce81_row31_col5" class="data row31 col5" >22.03</td>
                        <td id="T_9ce81_row31_col6" class="data row31 col6" >25.54</td>
                        <td id="T_9ce81_row31_col7" class="data row31 col7" >18.36</td>
                        <td id="T_9ce81_row31_col8" class="data row31 col8" >28.79</td>
                        <td id="T_9ce81_row31_col9" class="data row31 col9" >0.73</td>
                        <td id="T_9ce81_row31_col10" class="data row31 col10" >5.86</td>
                        <td id="T_9ce81_row31_col11" class="data row31 col11" >-328.78</td>
                        <td id="T_9ce81_row31_col12" class="data row31 col12" >483.06</td>
                        <td id="T_9ce81_row31_col13" class="data row31 col13" >-17.76</td>
                        <td id="T_9ce81_row31_col14" class="data row31 col14" >7.85</td>
                        <td id="T_9ce81_row31_col15" class="data row31 col15" >7.00</td>
                        <td id="T_9ce81_row31_col16" class="data row31 col16" >9.55</td>
                        <td id="T_9ce81_row31_col17" class="data row31 col17" >6.36</td>
                        <td id="T_9ce81_row31_col18" class="data row31 col18" >0.00</td>
            </tr>
    </tbody></table>



### 金融行业

1. ROE > 10%
2. 商誉比 < 10%
3. 盈利增长 >= 10% 或 收入增长 >= 10%




<style  type="text/css" >
#T_8167a_row0_col0,#T_8167a_row0_col1,#T_8167a_row0_col2,#T_8167a_row0_col3,#T_8167a_row0_col4,#T_8167a_row0_col5,#T_8167a_row0_col6,#T_8167a_row0_col7,#T_8167a_row0_col8,#T_8167a_row0_col9,#T_8167a_row0_col10,#T_8167a_row0_col12,#T_8167a_row0_col14,#T_8167a_row0_col15,#T_8167a_row0_col16,#T_8167a_row0_col17,#T_8167a_row0_col18,#T_8167a_row1_col0,#T_8167a_row1_col1,#T_8167a_row1_col2,#T_8167a_row1_col3,#T_8167a_row1_col4,#T_8167a_row1_col5,#T_8167a_row1_col6,#T_8167a_row1_col7,#T_8167a_row1_col8,#T_8167a_row1_col9,#T_8167a_row1_col10,#T_8167a_row1_col12,#T_8167a_row1_col14,#T_8167a_row1_col15,#T_8167a_row1_col16,#T_8167a_row1_col17,#T_8167a_row1_col18,#T_8167a_row2_col0,#T_8167a_row2_col1,#T_8167a_row2_col2,#T_8167a_row2_col3,#T_8167a_row2_col4,#T_8167a_row2_col5,#T_8167a_row2_col6,#T_8167a_row2_col7,#T_8167a_row2_col8,#T_8167a_row2_col9,#T_8167a_row2_col10,#T_8167a_row2_col12,#T_8167a_row2_col13,#T_8167a_row2_col14,#T_8167a_row2_col15,#T_8167a_row2_col16,#T_8167a_row2_col17,#T_8167a_row3_col0,#T_8167a_row3_col1,#T_8167a_row3_col2,#T_8167a_row3_col3,#T_8167a_row3_col4,#T_8167a_row3_col5,#T_8167a_row3_col6,#T_8167a_row3_col7,#T_8167a_row3_col8,#T_8167a_row3_col9,#T_8167a_row3_col10,#T_8167a_row3_col12,#T_8167a_row3_col14,#T_8167a_row3_col15,#T_8167a_row3_col16,#T_8167a_row3_col17,#T_8167a_row3_col18,#T_8167a_row4_col0,#T_8167a_row4_col1,#T_8167a_row4_col2,#T_8167a_row4_col3,#T_8167a_row4_col4,#T_8167a_row4_col5,#T_8167a_row4_col6,#T_8167a_row4_col7,#T_8167a_row4_col8,#T_8167a_row4_col9,#T_8167a_row4_col10,#T_8167a_row4_col12,#T_8167a_row4_col13,#T_8167a_row4_col14,#T_8167a_row4_col15,#T_8167a_row4_col16,#T_8167a_row4_col17,#T_8167a_row5_col0,#T_8167a_row5_col1,#T_8167a_row5_col2,#T_8167a_row5_col3,#T_8167a_row5_col4,#T_8167a_row5_col5,#T_8167a_row5_col6,#T_8167a_row5_col7,#T_8167a_row5_col8,#T_8167a_row5_col9,#T_8167a_row5_col10,#T_8167a_row5_col12,#T_8167a_row5_col13,#T_8167a_row5_col14,#T_8167a_row5_col15,#T_8167a_row5_col16,#T_8167a_row5_col17,#T_8167a_row6_col0,#T_8167a_row6_col1,#T_8167a_row6_col2,#T_8167a_row6_col3,#T_8167a_row6_col4,#T_8167a_row6_col5,#T_8167a_row6_col6,#T_8167a_row6_col7,#T_8167a_row6_col8,#T_8167a_row6_col9,#T_8167a_row6_col10,#T_8167a_row6_col12,#T_8167a_row6_col13,#T_8167a_row6_col14,#T_8167a_row6_col15,#T_8167a_row6_col16,#T_8167a_row6_col17,#T_8167a_row6_col18,#T_8167a_row7_col0,#T_8167a_row7_col1,#T_8167a_row7_col2,#T_8167a_row7_col3,#T_8167a_row7_col4,#T_8167a_row7_col5,#T_8167a_row7_col6,#T_8167a_row7_col7,#T_8167a_row7_col8,#T_8167a_row7_col9,#T_8167a_row7_col10,#T_8167a_row7_col11,#T_8167a_row7_col12,#T_8167a_row7_col13,#T_8167a_row7_col14,#T_8167a_row7_col15,#T_8167a_row7_col16,#T_8167a_row7_col17,#T_8167a_row7_col18,#T_8167a_row8_col0,#T_8167a_row8_col1,#T_8167a_row8_col2,#T_8167a_row8_col3,#T_8167a_row8_col4,#T_8167a_row8_col5,#T_8167a_row8_col6,#T_8167a_row8_col7,#T_8167a_row8_col8,#T_8167a_row8_col9,#T_8167a_row8_col10,#T_8167a_row8_col11,#T_8167a_row8_col12,#T_8167a_row8_col13,#T_8167a_row8_col14,#T_8167a_row8_col15,#T_8167a_row8_col16,#T_8167a_row8_col17,#T_8167a_row8_col18,#T_8167a_row9_col0,#T_8167a_row9_col1,#T_8167a_row9_col2,#T_8167a_row9_col3,#T_8167a_row9_col4,#T_8167a_row9_col5,#T_8167a_row9_col6,#T_8167a_row9_col7,#T_8167a_row9_col8,#T_8167a_row9_col9,#T_8167a_row9_col10,#T_8167a_row9_col12,#T_8167a_row9_col14,#T_8167a_row9_col15,#T_8167a_row9_col16,#T_8167a_row9_col17,#T_8167a_row9_col18,#T_8167a_row10_col0,#T_8167a_row10_col1,#T_8167a_row10_col2,#T_8167a_row10_col3,#T_8167a_row10_col4,#T_8167a_row10_col5,#T_8167a_row10_col6,#T_8167a_row10_col7,#T_8167a_row10_col8,#T_8167a_row10_col9,#T_8167a_row10_col10,#T_8167a_row10_col12,#T_8167a_row10_col13,#T_8167a_row10_col14,#T_8167a_row10_col15,#T_8167a_row10_col16,#T_8167a_row10_col17,#T_8167a_row11_col0,#T_8167a_row11_col1,#T_8167a_row11_col2,#T_8167a_row11_col3,#T_8167a_row11_col4,#T_8167a_row11_col5,#T_8167a_row11_col6,#T_8167a_row11_col7,#T_8167a_row11_col8,#T_8167a_row11_col9,#T_8167a_row11_col10,#T_8167a_row11_col12,#T_8167a_row11_col14,#T_8167a_row11_col15,#T_8167a_row11_col16,#T_8167a_row11_col17,#T_8167a_row11_col18,#T_8167a_row12_col0,#T_8167a_row12_col1,#T_8167a_row12_col2,#T_8167a_row12_col3,#T_8167a_row12_col4,#T_8167a_row12_col5,#T_8167a_row12_col6,#T_8167a_row12_col7,#T_8167a_row12_col8,#T_8167a_row12_col9,#T_8167a_row12_col10,#T_8167a_row12_col12,#T_8167a_row12_col14,#T_8167a_row12_col15,#T_8167a_row12_col16,#T_8167a_row12_col17,#T_8167a_row12_col18,#T_8167a_row13_col0,#T_8167a_row13_col1,#T_8167a_row13_col2,#T_8167a_row13_col3,#T_8167a_row13_col4,#T_8167a_row13_col5,#T_8167a_row13_col6,#T_8167a_row13_col7,#T_8167a_row13_col8,#T_8167a_row13_col9,#T_8167a_row13_col10,#T_8167a_row13_col11,#T_8167a_row13_col12,#T_8167a_row13_col14,#T_8167a_row13_col15,#T_8167a_row13_col16,#T_8167a_row13_col17,#T_8167a_row13_col18,#T_8167a_row14_col0,#T_8167a_row14_col1,#T_8167a_row14_col2,#T_8167a_row14_col3,#T_8167a_row14_col4,#T_8167a_row14_col5,#T_8167a_row14_col6,#T_8167a_row14_col7,#T_8167a_row14_col8,#T_8167a_row14_col9,#T_8167a_row14_col10,#T_8167a_row14_col12,#T_8167a_row14_col14,#T_8167a_row14_col15,#T_8167a_row14_col16,#T_8167a_row14_col17,#T_8167a_row14_col18,#T_8167a_row15_col0,#T_8167a_row15_col1,#T_8167a_row15_col2,#T_8167a_row15_col3,#T_8167a_row15_col4,#T_8167a_row15_col5,#T_8167a_row15_col6,#T_8167a_row15_col7,#T_8167a_row15_col8,#T_8167a_row15_col9,#T_8167a_row15_col10,#T_8167a_row15_col12,#T_8167a_row15_col14,#T_8167a_row15_col15,#T_8167a_row15_col16,#T_8167a_row15_col17,#T_8167a_row15_col18,#T_8167a_row16_col0,#T_8167a_row16_col1,#T_8167a_row16_col2,#T_8167a_row16_col3,#T_8167a_row16_col4,#T_8167a_row16_col5,#T_8167a_row16_col6,#T_8167a_row16_col7,#T_8167a_row16_col8,#T_8167a_row16_col9,#T_8167a_row16_col10,#T_8167a_row16_col12,#T_8167a_row16_col14,#T_8167a_row16_col15,#T_8167a_row16_col16,#T_8167a_row16_col17,#T_8167a_row16_col18{
            color:  black;
        }#T_8167a_row0_col11,#T_8167a_row0_col13,#T_8167a_row1_col11,#T_8167a_row1_col13,#T_8167a_row2_col11,#T_8167a_row2_col18,#T_8167a_row3_col11,#T_8167a_row3_col13,#T_8167a_row4_col11,#T_8167a_row4_col18,#T_8167a_row5_col11,#T_8167a_row5_col18,#T_8167a_row6_col11,#T_8167a_row9_col11,#T_8167a_row9_col13,#T_8167a_row10_col11,#T_8167a_row10_col18,#T_8167a_row11_col11,#T_8167a_row11_col13,#T_8167a_row12_col11,#T_8167a_row12_col13,#T_8167a_row13_col13,#T_8167a_row14_col11,#T_8167a_row14_col13,#T_8167a_row15_col11,#T_8167a_row15_col13,#T_8167a_row16_col11,#T_8167a_row16_col13{
            color:  red;
        }</style><table id="T_8167a_" ><thead>    <tr>        <th class="blank level0" ></th>        <th class="col_heading level0 col0" >名称</th>        <th class="col_heading level0 col1" >行业</th>        <th class="col_heading level0 col2" >权重</th>        <th class="col_heading level0 col3" >负债率</th>        <th class="col_heading level0 col4" >应收比</th>        <th class="col_heading level0 col5" >ROE</th>        <th class="col_heading level0 col6" >利润率</th>        <th class="col_heading level0 col7" >收入增长</th>        <th class="col_heading level0 col8" >收入波动</th>        <th class="col_heading level0 col9" >盈利增长</th>        <th class="col_heading level0 col10" >盈利波动</th>        <th class="col_heading level0 col11" >FCF增长</th>        <th class="col_heading level0 col12" >FCF波动</th>        <th class="col_heading level0 col13" >DCF</th>        <th class="col_heading level0 col14" >盈利折现</th>        <th class="col_heading level0 col15" >PE</th>        <th class="col_heading level0 col16" >PEG</th>        <th class="col_heading level0 col17" >市值</th>        <th class="col_heading level0 col18" >折价率</th>    </tr>    <tr>        <th class="index_name level0" >Symbol</th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>    </tr></thead><tbody>
                <tr>
                        <th id="T_8167a_level0_row0" class="row_heading level0 row0" >601997.SS</th>
                        <td id="T_8167a_row0_col0" class="data row0 col0" >贵阳银行</td>
                        <td id="T_8167a_row0_col1" class="data row0 col1" >银行</td>
                        <td id="T_8167a_row0_col2" class="data row0 col2" >0.65</td>
                        <td id="T_8167a_row0_col3" class="data row0 col3" >92.80</td>
                        <td id="T_8167a_row0_col4" class="data row0 col4" >1.28</td>
                        <td id="T_8167a_row0_col5" class="data row0 col5" >17.47</td>
                        <td id="T_8167a_row0_col6" class="data row0 col6" >54.49</td>
                        <td id="T_8167a_row0_col7" class="data row0 col7" >13.83</td>
                        <td id="T_8167a_row0_col8" class="data row0 col8" >9.08</td>
                        <td id="T_8167a_row0_col9" class="data row0 col9" >16.76</td>
                        <td id="T_8167a_row0_col10" class="data row0 col10" >6.26</td>
                        <td id="T_8167a_row0_col11" class="data row0 col11" >-159.52</td>
                        <td id="T_8167a_row0_col12" class="data row0 col12" >117.14</td>
                        <td id="T_8167a_row0_col13" class="data row0 col13" >-35.89</td>
                        <td id="T_8167a_row0_col14" class="data row0 col14" >93.65</td>
                        <td id="T_8167a_row0_col15" class="data row0 col15" >4.73</td>
                        <td id="T_8167a_row0_col16" class="data row0 col16" >0.28</td>
                        <td id="T_8167a_row0_col17" class="data row0 col17" >28.30</td>
                        <td id="T_8167a_row0_col18" class="data row0 col18" >nan</td>
            </tr>
            <tr>
                        <th id="T_8167a_level0_row1" class="row_heading level0 row1" >601838.SS</th>
                        <td id="T_8167a_row1_col0" class="data row1 col0" >成都银行</td>
                        <td id="T_8167a_row1_col1" class="data row1 col1" >银行</td>
                        <td id="T_8167a_row1_col2" class="data row1 col2" >0.81</td>
                        <td id="T_8167a_row1_col3" class="data row1 col3" >93.62</td>
                        <td id="T_8167a_row1_col4" class="data row1 col4" >2.64</td>
                        <td id="T_8167a_row1_col5" class="data row1 col5" >15.50</td>
                        <td id="T_8167a_row1_col6" class="data row1 col6" >52.11</td>
                        <td id="T_8167a_row1_col7" class="data row1 col7" >26.62</td>
                        <td id="T_8167a_row1_col8" class="data row1 col8" >21.12</td>
                        <td id="T_8167a_row1_col9" class="data row1 col9" >15.63</td>
                        <td id="T_8167a_row1_col10" class="data row1 col10" >6.14</td>
                        <td id="T_8167a_row1_col11" class="data row1 col11" >-141.63</td>
                        <td id="T_8167a_row1_col12" class="data row1 col12" >148.74</td>
                        <td id="T_8167a_row1_col13" class="data row1 col13" >-18.66</td>
                        <td id="T_8167a_row1_col14" class="data row1 col14" >95.94</td>
                        <td id="T_8167a_row1_col15" class="data row1 col15" >7.93</td>
                        <td id="T_8167a_row1_col16" class="data row1 col16" >0.51</td>
                        <td id="T_8167a_row1_col17" class="data row1 col17" >49.78</td>
                        <td id="T_8167a_row1_col18" class="data row1 col18" >nan</td>
            </tr>
            <tr>
                        <th id="T_8167a_level0_row2" class="row_heading level0 row2" >601229.SS</th>
                        <td id="T_8167a_row2_col0" class="data row2 col0" >上海银行</td>
                        <td id="T_8167a_row2_col1" class="data row2 col1" >银行</td>
                        <td id="T_8167a_row2_col2" class="data row2 col2" >2.61</td>
                        <td id="T_8167a_row2_col3" class="data row2 col3" >92.25</td>
                        <td id="T_8167a_row2_col4" class="data row2 col4" >7.05</td>
                        <td id="T_8167a_row2_col5" class="data row2 col5" >12.51</td>
                        <td id="T_8167a_row2_col6" class="data row2 col6" >63.20</td>
                        <td id="T_8167a_row2_col7" class="data row2 col7" >10.14</td>
                        <td id="T_8167a_row2_col8" class="data row2 col8" >9.39</td>
                        <td id="T_8167a_row2_col9" class="data row2 col9" >11.03</td>
                        <td id="T_8167a_row2_col10" class="data row2 col10" >7.49</td>
                        <td id="T_8167a_row2_col11" class="data row2 col11" >-118.51</td>
                        <td id="T_8167a_row2_col12" class="data row2 col12" >97.23</td>
                        <td id="T_8167a_row2_col13" class="data row2 col13" >4.53</td>
                        <td id="T_8167a_row2_col14" class="data row2 col14" >316.97</td>
                        <td id="T_8167a_row2_col15" class="data row2 col15" >5.71</td>
                        <td id="T_8167a_row2_col16" class="data row2 col16" >0.52</td>
                        <td id="T_8167a_row2_col17" class="data row2 col17" >121.04</td>
                        <td id="T_8167a_row2_col18" class="data row2 col18" >-2571.08</td>
            </tr>
            <tr>
                        <th id="T_8167a_level0_row3" class="row_heading level0 row3" >601009.SS</th>
                        <td id="T_8167a_row3_col0" class="data row3 col0" >南京银行</td>
                        <td id="T_8167a_row3_col1" class="data row3 col1" >银行</td>
                        <td id="T_8167a_row3_col2" class="data row3 col2" >2.12</td>
                        <td id="T_8167a_row3_col3" class="data row3 col3" >93.45</td>
                        <td id="T_8167a_row3_col4" class="data row3 col4" >9.80</td>
                        <td id="T_8167a_row3_col5" class="data row3 col5" >16.29</td>
                        <td id="T_8167a_row3_col6" class="data row3 col6" >49.90</td>
                        <td id="T_8167a_row3_col7" class="data row3 col7" >10.15</td>
                        <td id="T_8167a_row3_col8" class="data row3 col8" >5.23</td>
                        <td id="T_8167a_row3_col9" class="data row3 col9" >14.67</td>
                        <td id="T_8167a_row3_col10" class="data row3 col10" >2.28</td>
                        <td id="T_8167a_row3_col11" class="data row3 col11" >-1417.97</td>
                        <td id="T_8167a_row3_col12" class="data row3 col12" >2342.24</td>
                        <td id="T_8167a_row3_col13" class="data row3 col13" >-697759.98</td>
                        <td id="T_8167a_row3_col14" class="data row3 col14" >192.99</td>
                        <td id="T_8167a_row3_col15" class="data row3 col15" >7.82</td>
                        <td id="T_8167a_row3_col16" class="data row3 col16" >0.53</td>
                        <td id="T_8167a_row3_col17" class="data row3 col17" >105.17</td>
                        <td id="T_8167a_row3_col18" class="data row3 col18" >nan</td>
            </tr>
            <tr>
                        <th id="T_8167a_level0_row4" class="row_heading level0 row4" >601577.SS</th>
                        <td id="T_8167a_row4_col0" class="data row4 col0" >长沙银行</td>
                        <td id="T_8167a_row4_col1" class="data row4 col1" >银行</td>
                        <td id="T_8167a_row4_col2" class="data row4 col2" >0.40</td>
                        <td id="T_8167a_row4_col3" class="data row4 col3" >93.51</td>
                        <td id="T_8167a_row4_col4" class="data row4 col4" >2.67</td>
                        <td id="T_8167a_row4_col5" class="data row4 col5" >14.98</td>
                        <td id="T_8167a_row4_col6" class="data row4 col6" >43.03</td>
                        <td id="T_8167a_row4_col7" class="data row4 col7" >10.42</td>
                        <td id="T_8167a_row4_col8" class="data row4 col8" >5.63</td>
                        <td id="T_8167a_row4_col9" class="data row4 col9" >10.82</td>
                        <td id="T_8167a_row4_col10" class="data row4 col10" >4.97</td>
                        <td id="T_8167a_row4_col11" class="data row4 col11" >-149.80</td>
                        <td id="T_8167a_row4_col12" class="data row4 col12" >106.99</td>
                        <td id="T_8167a_row4_col13" class="data row4 col13" >6.96</td>
                        <td id="T_8167a_row4_col14" class="data row4 col14" >79.62</td>
                        <td id="T_8167a_row4_col15" class="data row4 col15" >7.14</td>
                        <td id="T_8167a_row4_col16" class="data row4 col16" >0.66</td>
                        <td id="T_8167a_row4_col17" class="data row4 col17" >38.69</td>
                        <td id="T_8167a_row4_col18" class="data row4 col18" >-456.17</td>
            </tr>
            <tr>
                        <th id="T_8167a_level0_row5" class="row_heading level0 row5" >002958.SZ</th>
                        <td id="T_8167a_row5_col0" class="data row5 col0" >青农商行</td>
                        <td id="T_8167a_row5_col1" class="data row5 col1" >银行</td>
                        <td id="T_8167a_row5_col2" class="data row5 col2" >0.50</td>
                        <td id="T_8167a_row5_col3" class="data row5 col3" >92.70</td>
                        <td id="T_8167a_row5_col4" class="data row5 col4" >1.41</td>
                        <td id="T_8167a_row5_col5" class="data row5 col5" >11.53</td>
                        <td id="T_8167a_row5_col6" class="data row5 col6" >43.16</td>
                        <td id="T_8167a_row5_col7" class="data row5 col7" >9.77</td>
                        <td id="T_8167a_row5_col8" class="data row5 col8" >35.49</td>
                        <td id="T_8167a_row5_col9" class="data row5 col9" >11.59</td>
                        <td id="T_8167a_row5_col10" class="data row5 col10" >6.17</td>
                        <td id="T_8167a_row5_col11" class="data row5 col11" >-138.47</td>
                        <td id="T_8167a_row5_col12" class="data row5 col12" >207.69</td>
                        <td id="T_8167a_row5_col13" class="data row5 col13" >0.11</td>
                        <td id="T_8167a_row5_col14" class="data row5 col14" >44.59</td>
                        <td id="T_8167a_row5_col15" class="data row5 col15" >8.12</td>
                        <td id="T_8167a_row5_col16" class="data row5 col16" >0.70</td>
                        <td id="T_8167a_row5_col17" class="data row5 col17" >24.50</td>
                        <td id="T_8167a_row5_col18" class="data row5 col18" >-21825.66</td>
            </tr>
            <tr>
                        <th id="T_8167a_level0_row6" class="row_heading level0 row6" >601658.SS</th>
                        <td id="T_8167a_row6_col0" class="data row6 col0" >邮储银行</td>
                        <td id="T_8167a_row6_col1" class="data row6 col1" >银行</td>
                        <td id="T_8167a_row6_col2" class="data row6 col2" >1.20</td>
                        <td id="T_8167a_row6_col3" class="data row6 col3" >94.07</td>
                        <td id="T_8167a_row6_col4" class="data row6 col4" >2.27</td>
                        <td id="T_8167a_row6_col5" class="data row6 col5" >11.82</td>
                        <td id="T_8167a_row6_col6" class="data row6 col6" >26.06</td>
                        <td id="T_8167a_row6_col7" class="data row6 col7" >6.04</td>
                        <td id="T_8167a_row6_col8" class="data row6 col8" >2.30</td>
                        <td id="T_8167a_row6_col9" class="data row6 col9" >10.52</td>
                        <td id="T_8167a_row6_col10" class="data row6 col10" >5.61</td>
                        <td id="T_8167a_row6_col11" class="data row6 col11" >-173.49</td>
                        <td id="T_8167a_row6_col12" class="data row6 col12" >250.48</td>
                        <td id="T_8167a_row6_col13" class="data row6 col13" >2581.41</td>
                        <td id="T_8167a_row6_col14" class="data row6 col14" >944.82</td>
                        <td id="T_8167a_row6_col15" class="data row6 col15" >7.75</td>
                        <td id="T_8167a_row6_col16" class="data row6 col16" >0.74</td>
                        <td id="T_8167a_row6_col17" class="data row6 col17" >506.26</td>
                        <td id="T_8167a_row6_col18" class="data row6 col18" >80.39</td>
            </tr>
            <tr>
                        <th id="T_8167a_level0_row7" class="row_heading level0 row7" >600926.SS</th>
                        <td id="T_8167a_row7_col0" class="data row7 col0" >杭州银行</td>
                        <td id="T_8167a_row7_col1" class="data row7 col1" >银行</td>
                        <td id="T_8167a_row7_col2" class="data row7 col2" >1.36</td>
                        <td id="T_8167a_row7_col3" class="data row7 col3" >93.08</td>
                        <td id="T_8167a_row7_col4" class="data row7 col4" >1.08</td>
                        <td id="T_8167a_row7_col5" class="data row7 col5" >11.24</td>
                        <td id="T_8167a_row7_col6" class="data row7 col6" >48.22</td>
                        <td id="T_8167a_row7_col7" class="data row7 col7" >15.82</td>
                        <td id="T_8167a_row7_col8" class="data row7 col8" >7.40</td>
                        <td id="T_8167a_row7_col9" class="data row7 col9" >16.34</td>
                        <td id="T_8167a_row7_col10" class="data row7 col10" >7.30</td>
                        <td id="T_8167a_row7_col11" class="data row7 col11" >41.76</td>
                        <td id="T_8167a_row7_col12" class="data row7 col12" >194.69</td>
                        <td id="T_8167a_row7_col13" class="data row7 col13" >1178.05</td>
                        <td id="T_8167a_row7_col14" class="data row7 col14" >114.90</td>
                        <td id="T_8167a_row7_col15" class="data row7 col15" >12.95</td>
                        <td id="T_8167a_row7_col16" class="data row7 col16" >0.79</td>
                        <td id="T_8167a_row7_col17" class="data row7 col17" >97.02</td>
                        <td id="T_8167a_row7_col18" class="data row7 col18" >91.76</td>
            </tr>
            <tr>
                        <th id="T_8167a_level0_row8" class="row_heading level0 row8" >601128.SS</th>
                        <td id="T_8167a_row8_col0" class="data row8 col0" >常熟银行</td>
                        <td id="T_8167a_row8_col1" class="data row8 col1" >银行</td>
                        <td id="T_8167a_row8_col2" class="data row8 col2" >0.64</td>
                        <td id="T_8167a_row8_col3" class="data row8 col3" >90.84</td>
                        <td id="T_8167a_row8_col4" class="data row8 col4" >0.65</td>
                        <td id="T_8167a_row8_col5" class="data row8 col5" >11.06</td>
                        <td id="T_8167a_row8_col6" class="data row8 col6" >36.04</td>
                        <td id="T_8167a_row8_col7" class="data row8 col7" >12.82</td>
                        <td id="T_8167a_row8_col8" class="data row8 col8" >5.59</td>
                        <td id="T_8167a_row8_col9" class="data row8 col9" >12.89</td>
                        <td id="T_8167a_row8_col10" class="data row8 col10" >10.37</td>
                        <td id="T_8167a_row8_col11" class="data row8 col11" >170.81</td>
                        <td id="T_8167a_row8_col12" class="data row8 col12" >457.78</td>
                        <td id="T_8167a_row8_col13" class="data row8 col13" >505.12</td>
                        <td id="T_8167a_row8_col14" class="data row8 col14" >28.24</td>
                        <td id="T_8167a_row8_col15" class="data row8 col15" >10.27</td>
                        <td id="T_8167a_row8_col16" class="data row8 col16" >0.80</td>
                        <td id="T_8167a_row8_col17" class="data row8 col17" >18.77</td>
                        <td id="T_8167a_row8_col18" class="data row8 col18" >96.28</td>
            </tr>
            <tr>
                        <th id="T_8167a_level0_row9" class="row_heading level0 row9" >600919.SS</th>
                        <td id="T_8167a_row9_col0" class="data row9 col0" >江苏银行</td>
                        <td id="T_8167a_row9_col1" class="data row9 col1" >银行</td>
                        <td id="T_8167a_row9_col2" class="data row9 col2" >3.09</td>
                        <td id="T_8167a_row9_col3" class="data row9 col3" >93.39</td>
                        <td id="T_8167a_row9_col4" class="data row9 col4" >0.84</td>
                        <td id="T_8167a_row9_col5" class="data row9 col5" >12.02</td>
                        <td id="T_8167a_row9_col6" class="data row9 col6" >46.07</td>
                        <td id="T_8167a_row9_col7" class="data row9 col7" >34.52</td>
                        <td id="T_8167a_row9_col8" class="data row9 col8" >46.74</td>
                        <td id="T_8167a_row9_col9" class="data row9 col9" >8.32</td>
                        <td id="T_8167a_row9_col10" class="data row9 col10" >4.65</td>
                        <td id="T_8167a_row9_col11" class="data row9 col11" >-16.35</td>
                        <td id="T_8167a_row9_col12" class="data row9 col12" >18.66</td>
                        <td id="T_8167a_row9_col13" class="data row9 col13" >-667.81</td>
                        <td id="T_8167a_row9_col14" class="data row9 col14" >216.76</td>
                        <td id="T_8167a_row9_col15" class="data row9 col15" >7.17</td>
                        <td id="T_8167a_row9_col16" class="data row9 col16" >0.86</td>
                        <td id="T_8167a_row9_col17" class="data row9 col17" >114.91</td>
                        <td id="T_8167a_row9_col18" class="data row9 col18" >nan</td>
            </tr>
            <tr>
                        <th id="T_8167a_level0_row10" class="row_heading level0 row10" >600928.SS</th>
                        <td id="T_8167a_row10_col0" class="data row10 col0" >西安银行</td>
                        <td id="T_8167a_row10_col1" class="data row10 col1" >银行</td>
                        <td id="T_8167a_row10_col2" class="data row10 col2" >0.22</td>
                        <td id="T_8167a_row10_col3" class="data row10 col3" >91.50</td>
                        <td id="T_8167a_row10_col4" class="data row10 col4" >3.28</td>
                        <td id="T_8167a_row10_col5" class="data row10 col5" >11.59</td>
                        <td id="T_8167a_row10_col6" class="data row10 col6" >48.65</td>
                        <td id="T_8167a_row10_col7" class="data row10 col7" >20.98</td>
                        <td id="T_8167a_row10_col8" class="data row10 col8" >18.60</td>
                        <td id="T_8167a_row10_col9" class="data row10 col9" >9.04</td>
                        <td id="T_8167a_row10_col10" class="data row10 col10" >5.35</td>
                        <td id="T_8167a_row10_col11" class="data row10 col11" >-117.52</td>
                        <td id="T_8167a_row10_col12" class="data row10 col12" >121.09</td>
                        <td id="T_8167a_row10_col13" class="data row10 col13" >0.23</td>
                        <td id="T_8167a_row10_col14" class="data row10 col14" >40.11</td>
                        <td id="T_8167a_row10_col15" class="data row10 col15" >8.20</td>
                        <td id="T_8167a_row10_col16" class="data row10 col16" >0.91</td>
                        <td id="T_8167a_row10_col17" class="data row10 col17" >22.09</td>
                        <td id="T_8167a_row10_col18" class="data row10 col18" >-9526.44</td>
            </tr>
            <tr>
                        <th id="T_8167a_level0_row11" class="row_heading level0 row11" >002142.SZ</th>
                        <td id="T_8167a_row11_col0" class="data row11 col0" >宁波银行</td>
                        <td id="T_8167a_row11_col1" class="data row11 col1" >银行</td>
                        <td id="T_8167a_row11_col2" class="data row11 col2" >5.55</td>
                        <td id="T_8167a_row11_col3" class="data row11 col3" >92.69</td>
                        <td id="T_8167a_row11_col4" class="data row11 col4" >4.58</td>
                        <td id="T_8167a_row11_col5" class="data row11 col5" >16.34</td>
                        <td id="T_8167a_row11_col6" class="data row11 col6" >49.03</td>
                        <td id="T_8167a_row11_col7" class="data row11 col7" >19.23</td>
                        <td id="T_8167a_row11_col8" class="data row11 col8" >7.17</td>
                        <td id="T_8167a_row11_col9" class="data row11 col9" >17.40</td>
                        <td id="T_8167a_row11_col10" class="data row11 col10" >6.78</td>
                        <td id="T_8167a_row11_col11" class="data row11 col11" >-174.45</td>
                        <td id="T_8167a_row11_col12" class="data row11 col12" >231.84</td>
                        <td id="T_8167a_row11_col13" class="data row11 col13" >-71.86</td>
                        <td id="T_8167a_row11_col14" class="data row11 col14" >245.09</td>
                        <td id="T_8167a_row11_col15" class="data row11 col15" >16.08</td>
                        <td id="T_8167a_row11_col16" class="data row11 col16" >0.92</td>
                        <td id="T_8167a_row11_col17" class="data row11 col17" >253.84</td>
                        <td id="T_8167a_row11_col18" class="data row11 col18" >nan</td>
            </tr>
            <tr>
                        <th id="T_8167a_level0_row12" class="row_heading level0 row12" >002961.SZ</th>
                        <td id="T_8167a_row12_col0" class="data row12 col0" >瑞达期货</td>
                        <td id="T_8167a_row12_col1" class="data row12 col1" >非银金融</td>
                        <td id="T_8167a_row12_col2" class="data row12 col2" >0.08</td>
                        <td id="T_8167a_row12_col3" class="data row12 col3" >82.51</td>
                        <td id="T_8167a_row12_col4" class="data row12 col4" >1.21</td>
                        <td id="T_8167a_row12_col5" class="data row12 col5" >10.05</td>
                        <td id="T_8167a_row12_col6" class="data row12 col6" >21.88</td>
                        <td id="T_8167a_row12_col7" class="data row12 col7" >45.82</td>
                        <td id="T_8167a_row12_col8" class="data row12 col8" >57.73</td>
                        <td id="T_8167a_row12_col9" class="data row12 col9" >27.83</td>
                        <td id="T_8167a_row12_col10" class="data row12 col10" >69.67</td>
                        <td id="T_8167a_row12_col11" class="data row12 col11" >-19.07</td>
                        <td id="T_8167a_row12_col12" class="data row12 col12" >106.19</td>
                        <td id="T_8167a_row12_col13" class="data row12 col13" >-4.63</td>
                        <td id="T_8167a_row12_col14" class="data row12 col14" >4.07</td>
                        <td id="T_8167a_row12_col15" class="data row12 col15" >29.08</td>
                        <td id="T_8167a_row12_col16" class="data row12 col16" >1.04</td>
                        <td id="T_8167a_row12_col17" class="data row12 col17" >9.19</td>
                        <td id="T_8167a_row12_col18" class="data row12 col18" >nan</td>
            </tr>
            <tr>
                        <th id="T_8167a_level0_row13" class="row_heading level0 row13" >002948.SZ</th>
                        <td id="T_8167a_row13_col0" class="data row13 col0" >青岛银行</td>
                        <td id="T_8167a_row13_col1" class="data row13 col1" >银行</td>
                        <td id="T_8167a_row13_col2" class="data row13 col2" >0.13</td>
                        <td id="T_8167a_row13_col3" class="data row13 col3" >93.28</td>
                        <td id="T_8167a_row13_col4" class="data row13 col4" >0.00</td>
                        <td id="T_8167a_row13_col5" class="data row13 col5" >10.57</td>
                        <td id="T_8167a_row13_col6" class="data row13 col6" >40.35</td>
                        <td id="T_8167a_row13_col7" class="data row13 col7" >15.37</td>
                        <td id="T_8167a_row13_col8" class="data row13 col8" >7.42</td>
                        <td id="T_8167a_row13_col9" class="data row13 col9" >8.06</td>
                        <td id="T_8167a_row13_col10" class="data row13 col10" >4.29</td>
                        <td id="T_8167a_row13_col11" class="data row13 col11" >16.72</td>
                        <td id="T_8167a_row13_col12" class="data row13 col12" >104.19</td>
                        <td id="T_8167a_row13_col13" class="data row13 col13" >-540.26</td>
                        <td id="T_8167a_row13_col14" class="data row13 col14" >33.90</td>
                        <td id="T_8167a_row13_col15" class="data row13 col15" >9.13</td>
                        <td id="T_8167a_row13_col16" class="data row13 col16" >1.13</td>
                        <td id="T_8167a_row13_col17" class="data row13 col17" >22.68</td>
                        <td id="T_8167a_row13_col18" class="data row13 col18" >nan</td>
            </tr>
            <tr>
                        <th id="T_8167a_level0_row14" class="row_heading level0 row14" >600036.SS</th>
                        <td id="T_8167a_row14_col0" class="data row14 col0" >招商银行</td>
                        <td id="T_8167a_row14_col1" class="data row14 col1" >银行</td>
                        <td id="T_8167a_row14_col2" class="data row14 col2" >22.00</td>
                        <td id="T_8167a_row14_col3" class="data row14 col3" >91.27</td>
                        <td id="T_8167a_row14_col4" class="data row14 col4" >0.15</td>
                        <td id="T_8167a_row14_col5" class="data row14 col5" >15.46</td>
                        <td id="T_8167a_row14_col6" class="data row14 col6" >43.54</td>
                        <td id="T_8167a_row14_col7" class="data row14 col7" >11.97</td>
                        <td id="T_8167a_row14_col8" class="data row14 col8" >4.30</td>
                        <td id="T_8167a_row14_col9" class="data row14 col9" >11.65</td>
                        <td id="T_8167a_row14_col10" class="data row14 col10" >5.92</td>
                        <td id="T_8167a_row14_col11" class="data row14 col11" >-693.52</td>
                        <td id="T_8167a_row14_col12" class="data row14 col12" >1273.45</td>
                        <td id="T_8167a_row14_col13" class="data row14 col13" >-171200.16</td>
                        <td id="T_8167a_row14_col14" class="data row14 col14" >1472.13</td>
                        <td id="T_8167a_row14_col15" class="data row14 col15" >14.30</td>
                        <td id="T_8167a_row14_col16" class="data row14 col16" >1.23</td>
                        <td id="T_8167a_row14_col17" class="data row14 col17" >1452.16</td>
                        <td id="T_8167a_row14_col18" class="data row14 col18" >nan</td>
            </tr>
            <tr>
                        <th id="T_8167a_level0_row15" class="row_heading level0 row15" >600015.SS</th>
                        <td id="T_8167a_row15_col0" class="data row15 col0" >华夏银行</td>
                        <td id="T_8167a_row15_col1" class="data row15 col1" >银行</td>
                        <td id="T_8167a_row15_col2" class="data row15 col2" >1.26</td>
                        <td id="T_8167a_row15_col3" class="data row15 col3" >91.08</td>
                        <td id="T_8167a_row15_col4" class="data row15 col4" >11.77</td>
                        <td id="T_8167a_row15_col5" class="data row15 col5" >10.30</td>
                        <td id="T_8167a_row15_col6" class="data row15 col6" >35.99</td>
                        <td id="T_8167a_row15_col7" class="data row15 col7" >28.76</td>
                        <td id="T_8167a_row15_col8" class="data row15 col8" >40.00</td>
                        <td id="T_8167a_row15_col9" class="data row15 col9" >2.46</td>
                        <td id="T_8167a_row15_col10" class="data row15 col10" >4.62</td>
                        <td id="T_8167a_row15_col11" class="data row15 col11" >-54.10</td>
                        <td id="T_8167a_row15_col12" class="data row15 col12" >105.75</td>
                        <td id="T_8167a_row15_col13" class="data row15 col13" >-65.10</td>
                        <td id="T_8167a_row15_col14" class="data row15 col14" >284.95</td>
                        <td id="T_8167a_row15_col15" class="data row15 col15" >4.51</td>
                        <td id="T_8167a_row15_col16" class="data row15 col16" >1.83</td>
                        <td id="T_8167a_row15_col17" class="data row15 col17" >98.32</td>
                        <td id="T_8167a_row15_col18" class="data row15 col18" >nan</td>
            </tr>
            <tr>
                        <th id="T_8167a_level0_row16" class="row_heading level0 row16" >000001.SZ</th>
                        <td id="T_8167a_row16_col0" class="data row16 col0" >平安银行</td>
                        <td id="T_8167a_row16_col1" class="data row16 col1" >银行</td>
                        <td id="T_8167a_row16_col2" class="data row16 col2" >8.24</td>
                        <td id="T_8167a_row16_col3" class="data row16 col3" >91.85</td>
                        <td id="T_8167a_row16_col4" class="data row16 col4" >2.89</td>
                        <td id="T_8167a_row16_col5" class="data row16 col5" >10.19</td>
                        <td id="T_8167a_row16_col6" class="data row16 col6" >35.71</td>
                        <td id="T_8167a_row16_col7" class="data row16 col7" >10.19</td>
                        <td id="T_8167a_row16_col8" class="data row16 col8" >4.91</td>
                        <td id="T_8167a_row16_col9" class="data row16 col9" >7.74</td>
                        <td id="T_8167a_row16_col10" class="data row16 col10" >5.54</td>
                        <td id="T_8167a_row16_col11" class="data row16 col11" >-44.54</td>
                        <td id="T_8167a_row16_col12" class="data row16 col12" >13.22</td>
                        <td id="T_8167a_row16_col13" class="data row16 col13" >-165.25</td>
                        <td id="T_8167a_row16_col14" class="data row16 col14" >410.95</td>
                        <td id="T_8167a_row16_col15" class="data row16 col15" >15.19</td>
                        <td id="T_8167a_row16_col16" class="data row16 col16" >1.96</td>
                        <td id="T_8167a_row16_col17" class="data row16 col17" >463.61</td>
                        <td id="T_8167a_row16_col18" class="data row16 col18" >nan</td>
            </tr>
    </tbody></table>



### 观察列表






<style  type="text/css" >
#T_46a48_row0_col0,#T_46a48_row0_col1,#T_46a48_row0_col2,#T_46a48_row0_col3,#T_46a48_row0_col4,#T_46a48_row0_col5,#T_46a48_row0_col6,#T_46a48_row0_col7,#T_46a48_row0_col8,#T_46a48_row0_col9,#T_46a48_row0_col10,#T_46a48_row0_col12,#T_46a48_row0_col13,#T_46a48_row0_col14,#T_46a48_row0_col15,#T_46a48_row0_col16,#T_46a48_row0_col17,#T_46a48_row1_col0,#T_46a48_row1_col1,#T_46a48_row1_col2,#T_46a48_row1_col3,#T_46a48_row1_col4,#T_46a48_row1_col5,#T_46a48_row1_col6,#T_46a48_row1_col7,#T_46a48_row1_col8,#T_46a48_row1_col9,#T_46a48_row1_col10,#T_46a48_row1_col12,#T_46a48_row1_col14,#T_46a48_row1_col15,#T_46a48_row1_col16,#T_46a48_row1_col17,#T_46a48_row1_col18,#T_46a48_row2_col0,#T_46a48_row2_col1,#T_46a48_row2_col2,#T_46a48_row2_col3,#T_46a48_row2_col4,#T_46a48_row2_col5,#T_46a48_row2_col6,#T_46a48_row2_col7,#T_46a48_row2_col8,#T_46a48_row2_col9,#T_46a48_row2_col10,#T_46a48_row2_col12,#T_46a48_row2_col14,#T_46a48_row2_col15,#T_46a48_row2_col16,#T_46a48_row2_col17,#T_46a48_row2_col18,#T_46a48_row3_col0,#T_46a48_row3_col1,#T_46a48_row3_col2,#T_46a48_row3_col3,#T_46a48_row3_col4,#T_46a48_row3_col5,#T_46a48_row3_col6,#T_46a48_row3_col7,#T_46a48_row3_col8,#T_46a48_row3_col9,#T_46a48_row3_col10,#T_46a48_row3_col11,#T_46a48_row3_col12,#T_46a48_row3_col13,#T_46a48_row3_col14,#T_46a48_row3_col15,#T_46a48_row3_col16,#T_46a48_row3_col17,#T_46a48_row4_col0,#T_46a48_row4_col1,#T_46a48_row4_col2,#T_46a48_row4_col3,#T_46a48_row4_col4,#T_46a48_row4_col5,#T_46a48_row4_col6,#T_46a48_row4_col7,#T_46a48_row4_col8,#T_46a48_row4_col9,#T_46a48_row4_col10,#T_46a48_row4_col12,#T_46a48_row4_col14,#T_46a48_row4_col15,#T_46a48_row4_col16,#T_46a48_row4_col17,#T_46a48_row4_col18,#T_46a48_row5_col0,#T_46a48_row5_col1,#T_46a48_row5_col2,#T_46a48_row5_col3,#T_46a48_row5_col4,#T_46a48_row5_col5,#T_46a48_row5_col6,#T_46a48_row5_col7,#T_46a48_row5_col8,#T_46a48_row5_col9,#T_46a48_row5_col10,#T_46a48_row5_col11,#T_46a48_row5_col12,#T_46a48_row5_col13,#T_46a48_row5_col14,#T_46a48_row5_col15,#T_46a48_row5_col16,#T_46a48_row5_col17,#T_46a48_row5_col18,#T_46a48_row6_col0,#T_46a48_row6_col1,#T_46a48_row6_col2,#T_46a48_row6_col3,#T_46a48_row6_col4,#T_46a48_row6_col5,#T_46a48_row6_col6,#T_46a48_row6_col7,#T_46a48_row6_col8,#T_46a48_row6_col9,#T_46a48_row6_col10,#T_46a48_row6_col11,#T_46a48_row6_col12,#T_46a48_row6_col13,#T_46a48_row6_col14,#T_46a48_row6_col15,#T_46a48_row6_col16,#T_46a48_row6_col17,#T_46a48_row6_col18,#T_46a48_row7_col0,#T_46a48_row7_col1,#T_46a48_row7_col2,#T_46a48_row7_col3,#T_46a48_row7_col4,#T_46a48_row7_col5,#T_46a48_row7_col6,#T_46a48_row7_col7,#T_46a48_row7_col8,#T_46a48_row7_col9,#T_46a48_row7_col10,#T_46a48_row7_col11,#T_46a48_row7_col12,#T_46a48_row7_col13,#T_46a48_row7_col14,#T_46a48_row7_col15,#T_46a48_row7_col16,#T_46a48_row7_col17,#T_46a48_row8_col0,#T_46a48_row8_col1,#T_46a48_row8_col2,#T_46a48_row8_col3,#T_46a48_row8_col4,#T_46a48_row8_col5,#T_46a48_row8_col6,#T_46a48_row8_col7,#T_46a48_row8_col8,#T_46a48_row8_col9,#T_46a48_row8_col10,#T_46a48_row8_col11,#T_46a48_row8_col12,#T_46a48_row8_col13,#T_46a48_row8_col14,#T_46a48_row8_col15,#T_46a48_row8_col16,#T_46a48_row8_col17,#T_46a48_row8_col18,#T_46a48_row9_col0,#T_46a48_row9_col1,#T_46a48_row9_col2,#T_46a48_row9_col3,#T_46a48_row9_col4,#T_46a48_row9_col5,#T_46a48_row9_col6,#T_46a48_row9_col7,#T_46a48_row9_col8,#T_46a48_row9_col9,#T_46a48_row9_col10,#T_46a48_row9_col11,#T_46a48_row9_col12,#T_46a48_row9_col13,#T_46a48_row9_col14,#T_46a48_row9_col15,#T_46a48_row9_col16,#T_46a48_row9_col17,#T_46a48_row10_col0,#T_46a48_row10_col1,#T_46a48_row10_col2,#T_46a48_row10_col3,#T_46a48_row10_col4,#T_46a48_row10_col5,#T_46a48_row10_col6,#T_46a48_row10_col7,#T_46a48_row10_col8,#T_46a48_row10_col9,#T_46a48_row10_col10,#T_46a48_row10_col11,#T_46a48_row10_col12,#T_46a48_row10_col13,#T_46a48_row10_col14,#T_46a48_row10_col15,#T_46a48_row10_col16,#T_46a48_row10_col17,#T_46a48_row11_col0,#T_46a48_row11_col1,#T_46a48_row11_col2,#T_46a48_row11_col3,#T_46a48_row11_col4,#T_46a48_row11_col5,#T_46a48_row11_col6,#T_46a48_row11_col7,#T_46a48_row11_col8,#T_46a48_row11_col9,#T_46a48_row11_col10,#T_46a48_row11_col12,#T_46a48_row11_col13,#T_46a48_row11_col14,#T_46a48_row11_col15,#T_46a48_row11_col16,#T_46a48_row11_col17,#T_46a48_row12_col0,#T_46a48_row12_col1,#T_46a48_row12_col2,#T_46a48_row12_col3,#T_46a48_row12_col4,#T_46a48_row12_col5,#T_46a48_row12_col6,#T_46a48_row12_col7,#T_46a48_row12_col8,#T_46a48_row12_col9,#T_46a48_row12_col10,#T_46a48_row12_col11,#T_46a48_row12_col12,#T_46a48_row12_col13,#T_46a48_row12_col14,#T_46a48_row12_col15,#T_46a48_row12_col16,#T_46a48_row12_col17,#T_46a48_row12_col18,#T_46a48_row13_col0,#T_46a48_row13_col1,#T_46a48_row13_col2,#T_46a48_row13_col3,#T_46a48_row13_col4,#T_46a48_row13_col5,#T_46a48_row13_col6,#T_46a48_row13_col7,#T_46a48_row13_col8,#T_46a48_row13_col10,#T_46a48_row13_col11,#T_46a48_row13_col12,#T_46a48_row13_col14,#T_46a48_row13_col16,#T_46a48_row13_col17,#T_46a48_row13_col18,#T_46a48_row14_col0,#T_46a48_row14_col1,#T_46a48_row14_col2,#T_46a48_row14_col3,#T_46a48_row14_col4,#T_46a48_row14_col5,#T_46a48_row14_col6,#T_46a48_row14_col7,#T_46a48_row14_col8,#T_46a48_row14_col9,#T_46a48_row14_col10,#T_46a48_row14_col12,#T_46a48_row14_col14,#T_46a48_row14_col15,#T_46a48_row14_col16,#T_46a48_row14_col17,#T_46a48_row14_col18,#T_46a48_row15_col0,#T_46a48_row15_col1,#T_46a48_row15_col2,#T_46a48_row15_col3,#T_46a48_row15_col4,#T_46a48_row15_col5,#T_46a48_row15_col6,#T_46a48_row15_col7,#T_46a48_row15_col8,#T_46a48_row15_col9,#T_46a48_row15_col10,#T_46a48_row15_col11,#T_46a48_row15_col12,#T_46a48_row15_col13,#T_46a48_row15_col14,#T_46a48_row15_col15,#T_46a48_row15_col16,#T_46a48_row15_col17,#T_46a48_row16_col0,#T_46a48_row16_col1,#T_46a48_row16_col2,#T_46a48_row16_col3,#T_46a48_row16_col4,#T_46a48_row16_col5,#T_46a48_row16_col6,#T_46a48_row16_col7,#T_46a48_row16_col8,#T_46a48_row16_col9,#T_46a48_row16_col10,#T_46a48_row16_col12,#T_46a48_row16_col14,#T_46a48_row16_col15,#T_46a48_row16_col16,#T_46a48_row16_col17,#T_46a48_row16_col18,#T_46a48_row17_col0,#T_46a48_row17_col1,#T_46a48_row17_col2,#T_46a48_row17_col3,#T_46a48_row17_col4,#T_46a48_row17_col5,#T_46a48_row17_col6,#T_46a48_row17_col7,#T_46a48_row17_col8,#T_46a48_row17_col9,#T_46a48_row17_col10,#T_46a48_row17_col11,#T_46a48_row17_col12,#T_46a48_row17_col13,#T_46a48_row17_col14,#T_46a48_row17_col15,#T_46a48_row17_col16,#T_46a48_row17_col17,#T_46a48_row17_col18,#T_46a48_row18_col0,#T_46a48_row18_col1,#T_46a48_row18_col2,#T_46a48_row18_col3,#T_46a48_row18_col4,#T_46a48_row18_col5,#T_46a48_row18_col6,#T_46a48_row18_col7,#T_46a48_row18_col8,#T_46a48_row18_col9,#T_46a48_row18_col10,#T_46a48_row18_col11,#T_46a48_row18_col12,#T_46a48_row18_col13,#T_46a48_row18_col14,#T_46a48_row18_col15,#T_46a48_row18_col16,#T_46a48_row18_col17,#T_46a48_row19_col0,#T_46a48_row19_col1,#T_46a48_row19_col2,#T_46a48_row19_col3,#T_46a48_row19_col4,#T_46a48_row19_col5,#T_46a48_row19_col6,#T_46a48_row19_col7,#T_46a48_row19_col8,#T_46a48_row19_col9,#T_46a48_row19_col10,#T_46a48_row19_col11,#T_46a48_row19_col12,#T_46a48_row19_col13,#T_46a48_row19_col14,#T_46a48_row19_col15,#T_46a48_row19_col16,#T_46a48_row19_col17,#T_46a48_row19_col18,#T_46a48_row20_col0,#T_46a48_row20_col1,#T_46a48_row20_col2,#T_46a48_row20_col3,#T_46a48_row20_col4,#T_46a48_row20_col5,#T_46a48_row20_col6,#T_46a48_row20_col7,#T_46a48_row20_col8,#T_46a48_row20_col9,#T_46a48_row20_col10,#T_46a48_row20_col12,#T_46a48_row20_col14,#T_46a48_row20_col15,#T_46a48_row20_col16,#T_46a48_row20_col17,#T_46a48_row20_col18,#T_46a48_row21_col0,#T_46a48_row21_col1,#T_46a48_row21_col2,#T_46a48_row21_col3,#T_46a48_row21_col4,#T_46a48_row21_col5,#T_46a48_row21_col6,#T_46a48_row21_col7,#T_46a48_row21_col8,#T_46a48_row21_col9,#T_46a48_row21_col10,#T_46a48_row21_col11,#T_46a48_row21_col12,#T_46a48_row21_col13,#T_46a48_row21_col14,#T_46a48_row21_col15,#T_46a48_row21_col16,#T_46a48_row21_col17,#T_46a48_row22_col0,#T_46a48_row22_col1,#T_46a48_row22_col2,#T_46a48_row22_col3,#T_46a48_row22_col4,#T_46a48_row22_col5,#T_46a48_row22_col6,#T_46a48_row22_col7,#T_46a48_row22_col8,#T_46a48_row22_col9,#T_46a48_row22_col10,#T_46a48_row22_col11,#T_46a48_row22_col12,#T_46a48_row22_col13,#T_46a48_row22_col14,#T_46a48_row22_col15,#T_46a48_row22_col16,#T_46a48_row22_col17,#T_46a48_row23_col0,#T_46a48_row23_col1,#T_46a48_row23_col2,#T_46a48_row23_col3,#T_46a48_row23_col4,#T_46a48_row23_col5,#T_46a48_row23_col6,#T_46a48_row23_col7,#T_46a48_row23_col8,#T_46a48_row23_col9,#T_46a48_row23_col10,#T_46a48_row23_col11,#T_46a48_row23_col12,#T_46a48_row23_col13,#T_46a48_row23_col14,#T_46a48_row23_col15,#T_46a48_row23_col16,#T_46a48_row23_col17,#T_46a48_row24_col0,#T_46a48_row24_col1,#T_46a48_row24_col2,#T_46a48_row24_col3,#T_46a48_row24_col4,#T_46a48_row24_col5,#T_46a48_row24_col6,#T_46a48_row24_col7,#T_46a48_row24_col8,#T_46a48_row24_col9,#T_46a48_row24_col10,#T_46a48_row24_col12,#T_46a48_row24_col13,#T_46a48_row24_col14,#T_46a48_row24_col15,#T_46a48_row24_col16,#T_46a48_row24_col17,#T_46a48_row25_col0,#T_46a48_row25_col1,#T_46a48_row25_col2,#T_46a48_row25_col3,#T_46a48_row25_col4,#T_46a48_row25_col5,#T_46a48_row25_col6,#T_46a48_row25_col7,#T_46a48_row25_col8,#T_46a48_row25_col9,#T_46a48_row25_col10,#T_46a48_row25_col11,#T_46a48_row25_col12,#T_46a48_row25_col13,#T_46a48_row25_col14,#T_46a48_row25_col15,#T_46a48_row25_col16,#T_46a48_row25_col17,#T_46a48_row26_col0,#T_46a48_row26_col1,#T_46a48_row26_col2,#T_46a48_row26_col3,#T_46a48_row26_col4,#T_46a48_row26_col5,#T_46a48_row26_col6,#T_46a48_row26_col7,#T_46a48_row26_col8,#T_46a48_row26_col10,#T_46a48_row26_col12,#T_46a48_row26_col13,#T_46a48_row26_col15,#T_46a48_row26_col17,#T_46a48_row26_col18,#T_46a48_row27_col0,#T_46a48_row27_col1,#T_46a48_row27_col2,#T_46a48_row27_col3,#T_46a48_row27_col4,#T_46a48_row27_col5,#T_46a48_row27_col6,#T_46a48_row27_col7,#T_46a48_row27_col8,#T_46a48_row27_col9,#T_46a48_row27_col10,#T_46a48_row27_col11,#T_46a48_row27_col12,#T_46a48_row27_col13,#T_46a48_row27_col14,#T_46a48_row27_col15,#T_46a48_row27_col16,#T_46a48_row27_col17,#T_46a48_row27_col18,#T_46a48_row28_col0,#T_46a48_row28_col1,#T_46a48_row28_col2,#T_46a48_row28_col3,#T_46a48_row28_col4,#T_46a48_row28_col5,#T_46a48_row28_col6,#T_46a48_row28_col7,#T_46a48_row28_col8,#T_46a48_row28_col9,#T_46a48_row28_col10,#T_46a48_row28_col11,#T_46a48_row28_col12,#T_46a48_row28_col13,#T_46a48_row28_col14,#T_46a48_row28_col15,#T_46a48_row28_col16,#T_46a48_row28_col17,#T_46a48_row29_col0,#T_46a48_row29_col1,#T_46a48_row29_col2,#T_46a48_row29_col3,#T_46a48_row29_col4,#T_46a48_row29_col5,#T_46a48_row29_col6,#T_46a48_row29_col8,#T_46a48_row29_col10,#T_46a48_row29_col12,#T_46a48_row29_col13,#T_46a48_row29_col14,#T_46a48_row29_col15,#T_46a48_row29_col17{
            color:  black;
        }#T_46a48_row0_col11,#T_46a48_row0_col18,#T_46a48_row1_col11,#T_46a48_row1_col13,#T_46a48_row2_col11,#T_46a48_row2_col13,#T_46a48_row3_col18,#T_46a48_row4_col11,#T_46a48_row4_col13,#T_46a48_row7_col18,#T_46a48_row9_col18,#T_46a48_row10_col18,#T_46a48_row11_col11,#T_46a48_row11_col18,#T_46a48_row13_col9,#T_46a48_row13_col13,#T_46a48_row13_col15,#T_46a48_row14_col11,#T_46a48_row14_col13,#T_46a48_row15_col18,#T_46a48_row16_col11,#T_46a48_row16_col13,#T_46a48_row18_col18,#T_46a48_row20_col11,#T_46a48_row20_col13,#T_46a48_row21_col18,#T_46a48_row22_col18,#T_46a48_row23_col18,#T_46a48_row24_col11,#T_46a48_row24_col18,#T_46a48_row25_col18,#T_46a48_row26_col9,#T_46a48_row26_col11,#T_46a48_row26_col14,#T_46a48_row26_col16,#T_46a48_row28_col18,#T_46a48_row29_col7,#T_46a48_row29_col9,#T_46a48_row29_col11,#T_46a48_row29_col16,#T_46a48_row29_col18{
            color:  red;
        }</style><table id="T_46a48_" ><thead>    <tr>        <th class="blank level0" ></th>        <th class="col_heading level0 col0" >名称</th>        <th class="col_heading level0 col1" >行业</th>        <th class="col_heading level0 col2" >权重</th>        <th class="col_heading level0 col3" >负债率</th>        <th class="col_heading level0 col4" >应收比</th>        <th class="col_heading level0 col5" >ROE</th>        <th class="col_heading level0 col6" >利润率</th>        <th class="col_heading level0 col7" >收入增长</th>        <th class="col_heading level0 col8" >收入波动</th>        <th class="col_heading level0 col9" >盈利增长</th>        <th class="col_heading level0 col10" >盈利波动</th>        <th class="col_heading level0 col11" >FCF增长</th>        <th class="col_heading level0 col12" >FCF波动</th>        <th class="col_heading level0 col13" >DCF</th>        <th class="col_heading level0 col14" >盈利折现</th>        <th class="col_heading level0 col15" >PE</th>        <th class="col_heading level0 col16" >PEG</th>        <th class="col_heading level0 col17" >市值</th>        <th class="col_heading level0 col18" >折价率</th>    </tr>    <tr>        <th class="index_name level0" >Symbol</th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>    </tr></thead><tbody>
                <tr>
                        <th id="T_46a48_level0_row0" class="row_heading level0 row0" >300750.SZ</th>
                        <td id="T_46a48_row0_col0" class="data row0 col0" >宁德时代</td>
                        <td id="T_46a48_row0_col1" class="data row0 col1" >电气设备</td>
                        <td id="T_46a48_row0_col2" class="data row0 col2" >19.96</td>
                        <td id="T_46a48_row0_col3" class="data row0 col3" >55.82</td>
                        <td id="T_46a48_row0_col4" class="data row0 col4" >48.95</td>
                        <td id="T_46a48_row0_col5" class="data row0 col5" >11.66</td>
                        <td id="T_46a48_row0_col6" class="data row0 col6" >12.97</td>
                        <td id="T_46a48_row0_col7" class="data row0 col7" >37.54</td>
                        <td id="T_46a48_row0_col8" class="data row0 col8" >24.16</td>
                        <td id="T_46a48_row0_col9" class="data row0 col9" >14.80</td>
                        <td id="T_46a48_row0_col10" class="data row0 col10" >24.56</td>
                        <td id="T_46a48_row0_col11" class="data row0 col11" >-61.23</td>
                        <td id="T_46a48_row0_col12" class="data row0 col12" >122.10</td>
                        <td id="T_46a48_row0_col13" class="data row0 col13" >2.58</td>
                        <td id="T_46a48_row0_col14" class="data row0 col14" >81.30</td>
                        <td id="T_46a48_row0_col15" class="data row0 col15" >145.51</td>
                        <td id="T_46a48_row0_col16" class="data row0 col16" >9.83</td>
                        <td id="T_46a48_row0_col17" class="data row0 col17" >988.86</td>
                        <td id="T_46a48_row0_col18" class="data row0 col18" >-38242.87</td>
            </tr>
            <tr>
                        <th id="T_46a48_level0_row1" class="row_heading level0 row1" >600036.SS</th>
                        <td id="T_46a48_row1_col0" class="data row1 col0" >招商银行</td>
                        <td id="T_46a48_row1_col1" class="data row1 col1" >银行</td>
                        <td id="T_46a48_row1_col2" class="data row1 col2" >22.00</td>
                        <td id="T_46a48_row1_col3" class="data row1 col3" >91.27</td>
                        <td id="T_46a48_row1_col4" class="data row1 col4" >0.15</td>
                        <td id="T_46a48_row1_col5" class="data row1 col5" >15.46</td>
                        <td id="T_46a48_row1_col6" class="data row1 col6" >43.54</td>
                        <td id="T_46a48_row1_col7" class="data row1 col7" >11.97</td>
                        <td id="T_46a48_row1_col8" class="data row1 col8" >4.30</td>
                        <td id="T_46a48_row1_col9" class="data row1 col9" >11.65</td>
                        <td id="T_46a48_row1_col10" class="data row1 col10" >5.92</td>
                        <td id="T_46a48_row1_col11" class="data row1 col11" >-693.52</td>
                        <td id="T_46a48_row1_col12" class="data row1 col12" >1273.45</td>
                        <td id="T_46a48_row1_col13" class="data row1 col13" >-171200.16</td>
                        <td id="T_46a48_row1_col14" class="data row1 col14" >1472.13</td>
                        <td id="T_46a48_row1_col15" class="data row1 col15" >14.30</td>
                        <td id="T_46a48_row1_col16" class="data row1 col16" >1.23</td>
                        <td id="T_46a48_row1_col17" class="data row1 col17" >1452.16</td>
                        <td id="T_46a48_row1_col18" class="data row1 col18" >nan</td>
            </tr>
            <tr>
                        <th id="T_46a48_level0_row2" class="row_heading level0 row2" >601899.SS</th>
                        <td id="T_46a48_row2_col0" class="data row2 col0" >紫金矿业</td>
                        <td id="T_46a48_row2_col1" class="data row2 col1" >有色金属</td>
                        <td id="T_46a48_row2_col2" class="data row2 col2" >11.50</td>
                        <td id="T_46a48_row2_col3" class="data row2 col3" >59.08</td>
                        <td id="T_46a48_row2_col4" class="data row2 col4" >2.95</td>
                        <td id="T_46a48_row2_col5" class="data row2 col5" >10.01</td>
                        <td id="T_46a48_row2_col6" class="data row2 col6" >3.63</td>
                        <td id="T_46a48_row2_col7" class="data row2 col7" >22.17</td>
                        <td id="T_46a48_row2_col8" class="data row2 col8" >8.80</td>
                        <td id="T_46a48_row2_col9" class="data row2 col9" >24.43</td>
                        <td id="T_46a48_row2_col10" class="data row2 col10" >24.57</td>
                        <td id="T_46a48_row2_col11" class="data row2 col11" >-110.17</td>
                        <td id="T_46a48_row2_col12" class="data row2 col12" >54.13</td>
                        <td id="T_46a48_row2_col13" class="data row2 col13" >-0.16</td>
                        <td id="T_46a48_row2_col14" class="data row2 col14" >107.81</td>
                        <td id="T_46a48_row2_col15" class="data row2 col15" >35.81</td>
                        <td id="T_46a48_row2_col16" class="data row2 col16" >1.47</td>
                        <td id="T_46a48_row2_col17" class="data row2 col17" >285.72</td>
                        <td id="T_46a48_row2_col18" class="data row2 col18" >nan</td>
            </tr>
            <tr>
                        <th id="T_46a48_level0_row3" class="row_heading level0 row3" >600489.SS</th>
                        <td id="T_46a48_row3_col0" class="data row3 col0" >中金黄金</td>
                        <td id="T_46a48_row3_col1" class="data row3 col1" >有色金属</td>
                        <td id="T_46a48_row3_col2" class="data row3 col2" >1.73</td>
                        <td id="T_46a48_row3_col3" class="data row3 col3" >44.27</td>
                        <td id="T_46a48_row3_col4" class="data row3 col4" >1.66</td>
                        <td id="T_46a48_row3_col5" class="data row3 col5" >2.88</td>
                        <td id="T_46a48_row3_col6" class="data row3 col6" >1.29</td>
                        <td id="T_46a48_row3_col7" class="data row3 col7" >13.63</td>
                        <td id="T_46a48_row3_col8" class="data row3 col8" >9.29</td>
                        <td id="T_46a48_row3_col9" class="data row3 col9" >242.86</td>
                        <td id="T_46a48_row3_col10" class="data row3 col10" >456.40</td>
                        <td id="T_46a48_row3_col11" class="data row3 col11" >33.70</td>
                        <td id="T_46a48_row3_col12" class="data row3 col12" >333.14</td>
                        <td id="T_46a48_row3_col13" class="data row3 col13" >28.07</td>
                        <td id="T_46a48_row3_col14" class="data row3 col14" >248.78</td>
                        <td id="T_46a48_row3_col15" class="data row3 col15" >24.64</td>
                        <td id="T_46a48_row3_col16" class="data row3 col16" >0.10</td>
                        <td id="T_46a48_row3_col17" class="data row3 col17" >46.24</td>
                        <td id="T_46a48_row3_col18" class="data row3 col18" >-64.76</td>
            </tr>
            <tr>
                        <th id="T_46a48_level0_row4" class="row_heading level0 row4" >000725.SZ</th>
                        <td id="T_46a48_row4_col0" class="data row4 col0" >京东方Ａ</td>
                        <td id="T_46a48_row4_col1" class="data row4 col1" >电子</td>
                        <td id="T_46a48_row4_col2" class="data row4 col2" >5.71</td>
                        <td id="T_46a48_row4_col3" class="data row4 col3" >59.13</td>
                        <td id="T_46a48_row4_col4" class="data row4 col4" >17.60</td>
                        <td id="T_46a48_row4_col5" class="data row4 col5" >4.95</td>
                        <td id="T_46a48_row4_col6" class="data row4 col6" >4.24</td>
                        <td id="T_46a48_row4_col7" class="data row4 col7" >13.28</td>
                        <td id="T_46a48_row4_col8" class="data row4 col8" >8.55</td>
                        <td id="T_46a48_row4_col9" class="data row4 col9" >21.23</td>
                        <td id="T_46a48_row4_col10" class="data row4 col10" >122.41</td>
                        <td id="T_46a48_row4_col11" class="data row4 col11" >-20.20</td>
                        <td id="T_46a48_row4_col12" class="data row4 col12" >57.98</td>
                        <td id="T_46a48_row4_col13" class="data row4 col13" >-134.15</td>
                        <td id="T_46a48_row4_col14" class="data row4 col14" >97.79</td>
                        <td id="T_46a48_row4_col15" class="data row4 col15" >22.61</td>
                        <td id="T_46a48_row4_col16" class="data row4 col16" >1.06</td>
                        <td id="T_46a48_row4_col17" class="data row4 col17" >218.19</td>
                        <td id="T_46a48_row4_col18" class="data row4 col18" >nan</td>
            </tr>
            <tr>
                        <th id="T_46a48_level0_row5" class="row_heading level0 row5" >600585.SS</th>
                        <td id="T_46a48_row5_col0" class="data row5 col0" >海螺水泥</td>
                        <td id="T_46a48_row5_col1" class="data row5 col1" >建筑材料</td>
                        <td id="T_46a48_row5_col2" class="data row5 col2" >19.83</td>
                        <td id="T_46a48_row5_col3" class="data row5 col3" >16.30</td>
                        <td id="T_46a48_row5_col4" class="data row5 col4" >7.17</td>
                        <td id="T_46a48_row5_col5" class="data row5 col5" >22.59</td>
                        <td id="T_46a48_row5_col6" class="data row5 col6" >21.40</td>
                        <td id="T_46a48_row5_col7" class="data row5 col7" >35.01</td>
                        <td id="T_46a48_row5_col8" class="data row5 col8" >31.14</td>
                        <td id="T_46a48_row5_col9" class="data row5 col9" >35.10</td>
                        <td id="T_46a48_row5_col10" class="data row5 col10" >46.03</td>
                        <td id="T_46a48_row5_col11" class="data row5 col11" >36.04</td>
                        <td id="T_46a48_row5_col12" class="data row5 col12" >80.90</td>
                        <td id="T_46a48_row5_col13" class="data row5 col13" >768.24</td>
                        <td id="T_46a48_row5_col14" class="data row5 col14" >847.14</td>
                        <td id="T_46a48_row5_col15" class="data row5 col15" >7.11</td>
                        <td id="T_46a48_row5_col16" class="data row5 col16" >0.20</td>
                        <td id="T_46a48_row5_col17" class="data row5 col17" >256.22</td>
                        <td id="T_46a48_row5_col18" class="data row5 col18" >66.65</td>
            </tr>
            <tr>
                        <th id="T_46a48_level0_row6" class="row_heading level0 row6" >600900.SS</th>
                        <td id="T_46a48_row6_col0" class="data row6 col0" >长江电力</td>
                        <td id="T_46a48_row6_col1" class="data row6 col1" >公用事业</td>
                        <td id="T_46a48_row6_col2" class="data row6 col2" >17.13</td>
                        <td id="T_46a48_row6_col3" class="data row6 col3" >46.10</td>
                        <td id="T_46a48_row6_col4" class="data row6 col4" >8.85</td>
                        <td id="T_46a48_row6_col5" class="data row6 col5" >15.52</td>
                        <td id="T_46a48_row6_col6" class="data row6 col6" >44.31</td>
                        <td id="T_46a48_row6_col7" class="data row6 col7" >5.12</td>
                        <td id="T_46a48_row6_col8" class="data row6 col8" >9.59</td>
                        <td id="T_46a48_row6_col9" class="data row6 col9" >6.31</td>
                        <td id="T_46a48_row6_col10" class="data row6 col10" >14.01</td>
                        <td id="T_46a48_row6_col11" class="data row6 col11" >0.54</td>
                        <td id="T_46a48_row6_col12" class="data row6 col12" >9.49</td>
                        <td id="T_46a48_row6_col13" class="data row6 col13" >467.21</td>
                        <td id="T_46a48_row6_col14" class="data row6 col14" >349.08</td>
                        <td id="T_46a48_row6_col15" class="data row6 col15" >16.77</td>
                        <td id="T_46a48_row6_col16" class="data row6 col16" >2.66</td>
                        <td id="T_46a48_row6_col17" class="data row6 col17" >450.74</td>
                        <td id="T_46a48_row6_col18" class="data row6 col18" >3.52</td>
            </tr>
            <tr>
                        <th id="T_46a48_level0_row7" class="row_heading level0 row7" >603288.SS</th>
                        <td id="T_46a48_row7_col0" class="data row7 col0" >海天味业</td>
                        <td id="T_46a48_row7_col1" class="data row7 col1" >食品饮料</td>
                        <td id="T_46a48_row7_col2" class="data row7 col2" >5.08</td>
                        <td id="T_46a48_row7_col3" class="data row7 col3" >31.72</td>
                        <td id="T_46a48_row7_col4" class="data row7 col4" >0.21</td>
                        <td id="T_46a48_row7_col5" class="data row7 col5" >31.42</td>
                        <td id="T_46a48_row7_col6" class="data row7 col6" >26.24</td>
                        <td id="T_46a48_row7_col7" class="data row7 col7" >16.05</td>
                        <td id="T_46a48_row7_col8" class="data row7 col8" >0.85</td>
                        <td id="T_46a48_row7_col9" class="data row7 col9" >21.95</td>
                        <td id="T_46a48_row7_col10" class="data row7 col10" >2.08</td>
                        <td id="T_46a48_row7_col11" class="data row7 col11" >11.37</td>
                        <td id="T_46a48_row7_col12" class="data row7 col12" >15.72</td>
                        <td id="T_46a48_row7_col13" class="data row7 col13" >95.46</td>
                        <td id="T_46a48_row7_col14" class="data row7 col14" >108.81</td>
                        <td id="T_46a48_row7_col15" class="data row7 col15" >86.22</td>
                        <td id="T_46a48_row7_col16" class="data row7 col16" >3.93</td>
                        <td id="T_46a48_row7_col17" class="data row7 col17" >581.42</td>
                        <td id="T_46a48_row7_col18" class="data row7 col18" >-509.06</td>
            </tr>
            <tr>
                        <th id="T_46a48_level0_row8" class="row_heading level0 row8" >600030.SS</th>
                        <td id="T_46a48_row8_col0" class="data row8 col0" >中信证券</td>
                        <td id="T_46a48_row8_col1" class="data row8 col1" >非银金融</td>
                        <td id="T_46a48_row8_col2" class="data row8 col2" >8.29</td>
                        <td id="T_46a48_row8_col3" class="data row8 col3" >82.35</td>
                        <td id="T_46a48_row8_col4" class="data row8 col4" >293.77</td>
                        <td id="T_46a48_row8_col5" class="data row8 col5" >7.53</td>
                        <td id="T_46a48_row8_col6" class="data row8 col6" >27.81</td>
                        <td id="T_46a48_row8_col7" class="data row8 col7" >9.51</td>
                        <td id="T_46a48_row8_col8" class="data row8 col8" >22.12</td>
                        <td id="T_46a48_row8_col9" class="data row8 col9" >13.17</td>
                        <td id="T_46a48_row8_col10" class="data row8 col10" >27.55</td>
                        <td id="T_46a48_row8_col11" class="data row8 col11" >50.91</td>
                        <td id="T_46a48_row8_col12" class="data row8 col12" >279.93</td>
                        <td id="T_46a48_row8_col13" class="data row8 col13" >765.84</td>
                        <td id="T_46a48_row8_col14" class="data row8 col14" >219.74</td>
                        <td id="T_46a48_row8_col15" class="data row8 col15" >20.37</td>
                        <td id="T_46a48_row8_col16" class="data row8 col16" >1.55</td>
                        <td id="T_46a48_row8_col17" class="data row8 col17" >325.75</td>
                        <td id="T_46a48_row8_col18" class="data row8 col18" >57.46</td>
            </tr>
            <tr>
                        <th id="T_46a48_level0_row9" class="row_heading level0 row9" >601888.SS</th>
                        <td id="T_46a48_row9_col0" class="data row9 col0" >中国中免</td>
                        <td id="T_46a48_row9_col1" class="data row9 col1" >休闲服务</td>
                        <td id="T_46a48_row9_col2" class="data row9 col2" >70.74</td>
                        <td id="T_46a48_row9_col3" class="data row9 col3" >37.55</td>
                        <td id="T_46a48_row9_col4" class="data row9 col4" >2.34</td>
                        <td id="T_46a48_row9_col5" class="data row9 col5" >21.92</td>
                        <td id="T_46a48_row9_col6" class="data row9 col6" >9.18</td>
                        <td id="T_46a48_row9_col7" class="data row9 col7" >25.94</td>
                        <td id="T_46a48_row9_col8" class="data row9 col8" >34.96</td>
                        <td id="T_46a48_row9_col9" class="data row9 col9" >34.84</td>
                        <td id="T_46a48_row9_col10" class="data row9 col10" >13.83</td>
                        <td id="T_46a48_row9_col11" class="data row9 col11" >105.58</td>
                        <td id="T_46a48_row9_col12" class="data row9 col12" >204.00</td>
                        <td id="T_46a48_row9_col13" class="data row9 col13" >309.81</td>
                        <td id="T_46a48_row9_col14" class="data row9 col14" >120.76</td>
                        <td id="T_46a48_row9_col15" class="data row9 col15" >70.49</td>
                        <td id="T_46a48_row9_col16" class="data row9 col16" >2.02</td>
                        <td id="T_46a48_row9_col17" class="data row9 col17" >635.14</td>
                        <td id="T_46a48_row9_col18" class="data row9 col18" >-105.01</td>
            </tr>
            <tr>
                        <th id="T_46a48_level0_row10" class="row_heading level0 row10" >000333.SZ</th>
                        <td id="T_46a48_row10_col0" class="data row10 col0" >美的集团</td>
                        <td id="T_46a48_row10_col1" class="data row10 col1" >家用电器</td>
                        <td id="T_46a48_row10_col2" class="data row10 col2" >38.36</td>
                        <td id="T_46a48_row10_col3" class="data row10 col3" >65.53</td>
                        <td id="T_46a48_row10_col4" class="data row10 col4" >22.82</td>
                        <td id="T_46a48_row10_col5" class="data row10 col5" >23.69</td>
                        <td id="T_46a48_row10_col6" class="data row10 col6" >8.31</td>
                        <td id="T_46a48_row10_col7" class="data row10 col7" >5.73</td>
                        <td id="T_46a48_row10_col8" class="data row10 col8" >3.11</td>
                        <td id="T_46a48_row10_col9" class="data row10 col9" >16.39</td>
                        <td id="T_46a48_row10_col10" class="data row10 col10" >3.66</td>
                        <td id="T_46a48_row10_col11" class="data row10 col11" >11.21</td>
                        <td id="T_46a48_row10_col12" class="data row10 col12" >43.88</td>
                        <td id="T_46a48_row10_col13" class="data row10 col13" >442.10</td>
                        <td id="T_46a48_row10_col14" class="data row10 col14" >431.73</td>
                        <td id="T_46a48_row10_col15" class="data row10 col15" >19.39</td>
                        <td id="T_46a48_row10_col16" class="data row10 col16" >1.18</td>
                        <td id="T_46a48_row10_col17" class="data row10 col17" >560.09</td>
                        <td id="T_46a48_row10_col18" class="data row10 col18" >-26.69</td>
            </tr>
            <tr>
                        <th id="T_46a48_level0_row11" class="row_heading level0 row11" >601398.SS</th>
                        <td id="T_46a48_row11_col0" class="data row11 col0" >工商银行</td>
                        <td id="T_46a48_row11_col1" class="data row11 col1" >银行</td>
                        <td id="T_46a48_row11_col2" class="data row11 col2" >4.63</td>
                        <td id="T_46a48_row11_col3" class="data row11 col3" >91.27</td>
                        <td id="T_46a48_row11_col4" class="data row11 col4" >139.76</td>
                        <td id="T_46a48_row11_col5" class="data row11 col5" >12.72</td>
                        <td id="T_46a48_row11_col6" class="data row11 col6" >50.13</td>
                        <td id="T_46a48_row11_col7" class="data row11 col7" >0.07</td>
                        <td id="T_46a48_row11_col8" class="data row11 col8" >2.42</td>
                        <td id="T_46a48_row11_col9" class="data row11 col9" >3.38</td>
                        <td id="T_46a48_row11_col10" class="data row11 col10" >1.95</td>
                        <td id="T_46a48_row11_col11" class="data row11 col11" >-104.59</td>
                        <td id="T_46a48_row11_col12" class="data row11 col12" >139.60</td>
                        <td id="T_46a48_row11_col13" class="data row11 col13" >4.22</td>
                        <td id="T_46a48_row11_col14" class="data row11 col14" >4221.19</td>
                        <td id="T_46a48_row11_col15" class="data row11 col15" >5.83</td>
                        <td id="T_46a48_row11_col16" class="data row11 col16" >1.73</td>
                        <td id="T_46a48_row11_col17" class="data row11 col17" >1849.75</td>
                        <td id="T_46a48_row11_col18" class="data row11 col18" >-43783.93</td>
            </tr>
            <tr>
                        <th id="T_46a48_level0_row12" class="row_heading level0 row12" >000895.SZ</th>
                        <td id="T_46a48_row12_col0" class="data row12 col0" >双汇发展</td>
                        <td id="T_46a48_row12_col1" class="data row12 col1" >食品饮料</td>
                        <td id="T_46a48_row12_col2" class="data row12 col2" >1.11</td>
                        <td id="T_46a48_row12_col3" class="data row12 col3" >30.46</td>
                        <td id="T_46a48_row12_col4" class="data row12 col4" >1.32</td>
                        <td id="T_46a48_row12_col5" class="data row12 col5" >31.63</td>
                        <td id="T_46a48_row12_col6" class="data row12 col6" >9.01</td>
                        <td id="T_46a48_row12_col7" class="data row12 col7" >14.21</td>
                        <td id="T_46a48_row12_col8" class="data row12 col8" >15.19</td>
                        <td id="T_46a48_row12_col9" class="data row12 col9" >13.15</td>
                        <td id="T_46a48_row12_col10" class="data row12 col10" >2.22</td>
                        <td id="T_46a48_row12_col11" class="data row12 col11" >25.11</td>
                        <td id="T_46a48_row12_col12" class="data row12 col12" >68.40</td>
                        <td id="T_46a48_row12_col13" class="data row12 col13" >124.42</td>
                        <td id="T_46a48_row12_col14" class="data row12 col14" >93.82</td>
                        <td id="T_46a48_row12_col15" class="data row12 col15" >19.53</td>
                        <td id="T_46a48_row12_col16" class="data row12 col16" >1.48</td>
                        <td id="T_46a48_row12_col17" class="data row12 col17" >121.68</td>
                        <td id="T_46a48_row12_col18" class="data row12 col18" >2.20</td>
            </tr>
            <tr>
                        <th id="T_46a48_level0_row13" class="row_heading level0 row13" >600340.SS</th>
                        <td id="T_46a48_row13_col0" class="data row13 col0" >华夏幸福</td>
                        <td id="T_46a48_row13_col1" class="data row13 col1" >房地产</td>
                        <td id="T_46a48_row13_col2" class="data row13 col2" >0.90</td>
                        <td id="T_46a48_row13_col3" class="data row13 col3" >81.29</td>
                        <td id="T_46a48_row13_col4" class="data row13 col4" >212.96</td>
                        <td id="T_46a48_row13_col5" class="data row13 col5" >21.44</td>
                        <td id="T_46a48_row13_col6" class="data row13 col6" >11.59</td>
                        <td id="T_46a48_row13_col7" class="data row13 col7" >20.76</td>
                        <td id="T_46a48_row13_col8" class="data row13 col8" >22.55</td>
                        <td id="T_46a48_row13_col9" class="data row13 col9" >-5.88</td>
                        <td id="T_46a48_row13_col10" class="data row13 col10" >59.94</td>
                        <td id="T_46a48_row13_col11" class="data row13 col11" >57.88</td>
                        <td id="T_46a48_row13_col12" class="data row13 col12" >164.51</td>
                        <td id="T_46a48_row13_col13" class="data row13 col13" >-1107.54</td>
                        <td id="T_46a48_row13_col14" class="data row13 col14" >104.44</td>
                        <td id="T_46a48_row13_col15" class="data row13 col15" >-7.52</td>
                        <td id="T_46a48_row13_col16" class="data row13 col16" >1.28</td>
                        <td id="T_46a48_row13_col17" class="data row13 col17" >21.84</td>
                        <td id="T_46a48_row13_col18" class="data row13 col18" >nan</td>
            </tr>
            <tr>
                        <th id="T_46a48_level0_row14" class="row_heading level0 row14" >600887.SS</th>
                        <td id="T_46a48_row14_col0" class="data row14 col0" >伊利股份</td>
                        <td id="T_46a48_row14_col1" class="data row14 col1" >食品饮料</td>
                        <td id="T_46a48_row14_col2" class="data row14 col2" >6.61</td>
                        <td id="T_46a48_row14_col3" class="data row14 col3" >57.09</td>
                        <td id="T_46a48_row14_col4" class="data row14 col4" >6.81</td>
                        <td id="T_46a48_row14_col5" class="data row14 col5" >24.20</td>
                        <td id="T_46a48_row14_col6" class="data row14 col6" >7.98</td>
                        <td id="T_46a48_row14_col7" class="data row14 col7" >12.56</td>
                        <td id="T_46a48_row14_col8" class="data row14 col8" >4.81</td>
                        <td id="T_46a48_row14_col9" class="data row14 col9" >5.69</td>
                        <td id="T_46a48_row14_col10" class="data row14 col10" >3.13</td>
                        <td id="T_46a48_row14_col11" class="data row14 col11" >-216.14</td>
                        <td id="T_46a48_row14_col12" class="data row14 col12" >272.20</td>
                        <td id="T_46a48_row14_col13" class="data row14 col13" >-40.88</td>
                        <td id="T_46a48_row14_col14" class="data row14 col14" >97.99</td>
                        <td id="T_46a48_row14_col15" class="data row14 col15" >27.38</td>
                        <td id="T_46a48_row14_col16" class="data row14 col16" >4.81</td>
                        <td id="T_46a48_row14_col17" class="data row14 col17" >240.02</td>
                        <td id="T_46a48_row14_col18" class="data row14 col18" >nan</td>
            </tr>
            <tr>
                        <th id="T_46a48_level0_row15" class="row_heading level0 row15" >000651.SZ</th>
                        <td id="T_46a48_row15_col0" class="data row15 col0" >格力电器</td>
                        <td id="T_46a48_row15_col1" class="data row15 col1" >家用电器</td>
                        <td id="T_46a48_row15_col2" class="data row15 col2" >25.72</td>
                        <td id="T_46a48_row15_col3" class="data row15 col3" >58.14</td>
                        <td id="T_46a48_row15_col4" class="data row15 col4" >17.56</td>
                        <td id="T_46a48_row15_col5" class="data row15 col5" >26.13</td>
                        <td id="T_46a48_row15_col6" class="data row15 col6" >13.45</td>
                        <td id="T_46a48_row15_col7" class="data row15 col7" >6.56</td>
                        <td id="T_46a48_row15_col8" class="data row15 col8" >24.45</td>
                        <td id="T_46a48_row15_col9" class="data row15 col9" >0.34</td>
                        <td id="T_46a48_row15_col10" class="data row15 col10" >14.58</td>
                        <td id="T_46a48_row15_col11" class="data row15 col11" >9.95</td>
                        <td id="T_46a48_row15_col12" class="data row15 col12" >51.97</td>
                        <td id="T_46a48_row15_col13" class="data row15 col13" >309.87</td>
                        <td id="T_46a48_row15_col14" class="data row15 col14" >306.13</td>
                        <td id="T_46a48_row15_col15" class="data row15 col15" >14.01</td>
                        <td id="T_46a48_row15_col16" class="data row15 col16" >41.37</td>
                        <td id="T_46a48_row15_col17" class="data row15 col17" >337.18</td>
                        <td id="T_46a48_row15_col18" class="data row15 col18" >-8.81</td>
            </tr>
            <tr>
                        <th id="T_46a48_level0_row16" class="row_heading level0 row16" >600000.SS</th>
                        <td id="T_46a48_row16_col0" class="data row16 col0" >浦发银行</td>
                        <td id="T_46a48_row16_col1" class="data row16 col1" >银行</td>
                        <td id="T_46a48_row16_col2" class="data row16 col2" >4.14</td>
                        <td id="T_46a48_row16_col3" class="data row16 col3" >91.88</td>
                        <td id="T_46a48_row16_col4" class="data row16 col4" >6.45</td>
                        <td id="T_46a48_row16_col5" class="data row16 col5" >11.54</td>
                        <td id="T_46a48_row16_col6" class="data row16 col6" >50.05</td>
                        <td id="T_46a48_row16_col7" class="data row16 col7" >1.01</td>
                        <td id="T_46a48_row16_col8" class="data row16 col8" >3.84</td>
                        <td id="T_46a48_row16_col9" class="data row16 col9" >2.47</td>
                        <td id="T_46a48_row16_col10" class="data row16 col10" >3.22</td>
                        <td id="T_46a48_row16_col11" class="data row16 col11" >-67.43</td>
                        <td id="T_46a48_row16_col12" class="data row16 col12" >193.50</td>
                        <td id="T_46a48_row16_col13" class="data row16 col13" >-89.66</td>
                        <td id="T_46a48_row16_col14" class="data row16 col14" >773.00</td>
                        <td id="T_46a48_row16_col15" class="data row16 col15" >5.03</td>
                        <td id="T_46a48_row16_col16" class="data row16 col16" >2.03</td>
                        <td id="T_46a48_row16_col17" class="data row16 col17" >299.98</td>
                        <td id="T_46a48_row16_col18" class="data row16 col18" >nan</td>
            </tr>
            <tr>
                        <th id="T_46a48_level0_row17" class="row_heading level0 row17" >601318.SS</th>
                        <td id="T_46a48_row17_col0" class="data row17 col0" >中国平安</td>
                        <td id="T_46a48_row17_col1" class="data row17 col1" >非银金融</td>
                        <td id="T_46a48_row17_col2" class="data row17 col2" >28.63</td>
                        <td id="T_46a48_row17_col3" class="data row17 col3" >89.63</td>
                        <td id="T_46a48_row17_col4" class="data row17 col4" >36.19</td>
                        <td id="T_46a48_row17_col5" class="data row17 col5" >19.77</td>
                        <td id="T_46a48_row17_col6" class="data row17 col6" >10.76</td>
                        <td id="T_46a48_row17_col7" class="data row17 col7" >8.44</td>
                        <td id="T_46a48_row17_col8" class="data row17 col8" >5.08</td>
                        <td id="T_46a48_row17_col9" class="data row17 col9" >18.48</td>
                        <td id="T_46a48_row17_col10" class="data row17 col10" >21.74</td>
                        <td id="T_46a48_row17_col11" class="data row17 col11" >30.57</td>
                        <td id="T_46a48_row17_col12" class="data row17 col12" >52.95</td>
                        <td id="T_46a48_row17_col13" class="data row17 col13" >4000.34</td>
                        <td id="T_46a48_row17_col14" class="data row17 col14" >2495.68</td>
                        <td id="T_46a48_row17_col15" class="data row17 col15" >8.98</td>
                        <td id="T_46a48_row17_col16" class="data row17 col16" >0.49</td>
                        <td id="T_46a48_row17_col17" class="data row17 col17" >1295.52</td>
                        <td id="T_46a48_row17_col18" class="data row17 col18" >67.61</td>
            </tr>
            <tr>
                        <th id="T_46a48_level0_row18" class="row_heading level0 row18" >002415.SZ</th>
                        <td id="T_46a48_row18_col0" class="data row18 col0" >海康威视</td>
                        <td id="T_46a48_row18_col1" class="data row18 col1" >电子</td>
                        <td id="T_46a48_row18_col2" class="data row18 col2" >8.75</td>
                        <td id="T_46a48_row18_col3" class="data row18 col3" >38.58</td>
                        <td id="T_46a48_row18_col4" class="data row18 col4" >42.53</td>
                        <td id="T_46a48_row18_col5" class="data row18 col5" >28.43</td>
                        <td id="T_46a48_row18_col6" class="data row18 col6" >21.96</td>
                        <td id="T_46a48_row18_col7" class="data row18 col7" >14.92</td>
                        <td id="T_46a48_row18_col8" class="data row18 col8" >4.45</td>
                        <td id="T_46a48_row18_col9" class="data row18 col9" >12.60</td>
                        <td id="T_46a48_row18_col10" class="data row18 col10" >6.99</td>
                        <td id="T_46a48_row18_col11" class="data row18 col11" >49.38</td>
                        <td id="T_46a48_row18_col12" class="data row18 col12" >82.14</td>
                        <td id="T_46a48_row18_col13" class="data row18 col13" >322.50</td>
                        <td id="T_46a48_row18_col14" class="data row18 col14" >205.94</td>
                        <td id="T_46a48_row18_col15" class="data row18 col15" >40.95</td>
                        <td id="T_46a48_row18_col16" class="data row18 col16" >3.25</td>
                        <td id="T_46a48_row18_col17" class="data row18 col17" >575.74</td>
                        <td id="T_46a48_row18_col18" class="data row18 col18" >-78.52</td>
            </tr>
            <tr>
                        <th id="T_46a48_level0_row19" class="row_heading level0 row19" >000002.SZ</th>
                        <td id="T_46a48_row19_col0" class="data row19 col0" >万  科Ａ</td>
                        <td id="T_46a48_row19_col1" class="data row19 col1" >房地产</td>
                        <td id="T_46a48_row19_col2" class="data row19 col2" >19.70</td>
                        <td id="T_46a48_row19_col3" class="data row19 col3" >81.28</td>
                        <td id="T_46a48_row19_col4" class="data row19 col4" >56.58</td>
                        <td id="T_46a48_row19_col5" class="data row19 col5" >20.50</td>
                        <td id="T_46a48_row19_col6" class="data row19 col6" >10.84</td>
                        <td id="T_46a48_row19_col7" class="data row19 col7" >20.02</td>
                        <td id="T_46a48_row19_col8" class="data row19 col8" >5.31</td>
                        <td id="T_46a48_row19_col9" class="data row19 col9" >14.10</td>
                        <td id="T_46a48_row19_col10" class="data row19 col10" >6.85</td>
                        <td id="T_46a48_row19_col11" class="data row19 col11" >25.80</td>
                        <td id="T_46a48_row19_col12" class="data row19 col12" >109.64</td>
                        <td id="T_46a48_row19_col13" class="data row19 col13" >1093.74</td>
                        <td id="T_46a48_row19_col14" class="data row19 col14" >652.72</td>
                        <td id="T_46a48_row19_col15" class="data row19 col15" >7.48</td>
                        <td id="T_46a48_row19_col16" class="data row19 col16" >0.53</td>
                        <td id="T_46a48_row19_col17" class="data row19 col17" >310.89</td>
                        <td id="T_46a48_row19_col18" class="data row19 col18" >71.58</td>
            </tr>
            <tr>
                        <th id="T_46a48_level0_row20" class="row_heading level0 row20" >002594.SZ</th>
                        <td id="T_46a48_row20_col0" class="data row20 col0" >比亚迪</td>
                        <td id="T_46a48_row20_col1" class="data row20 col1" >汽车</td>
                        <td id="T_46a48_row20_col2" class="data row20 col2" >13.45</td>
                        <td id="T_46a48_row20_col3" class="data row20 col3" >67.94</td>
                        <td id="T_46a48_row20_col4" class="data row20 col4" >36.43</td>
                        <td id="T_46a48_row20_col5" class="data row20 col5" >5.68</td>
                        <td id="T_46a48_row20_col6" class="data row20 col6" >2.49</td>
                        <td id="T_46a48_row20_col7" class="data row20 col7" >14.53</td>
                        <td id="T_46a48_row20_col8" class="data row20 col8" >14.13</td>
                        <td id="T_46a48_row20_col9" class="data row20 col9" >29.57</td>
                        <td id="T_46a48_row20_col10" class="data row20 col10" >115.04</td>
                        <td id="T_46a48_row20_col11" class="data row20 col11" >-231.87</td>
                        <td id="T_46a48_row20_col12" class="data row20 col12" >381.11</td>
                        <td id="T_46a48_row20_col13" class="data row20 col13" >-86.81</td>
                        <td id="T_46a48_row20_col14" class="data row20 col14" >83.47</td>
                        <td id="T_46a48_row20_col15" class="data row20 col15" >122.41</td>
                        <td id="T_46a48_row20_col16" class="data row20 col16" >4.14</td>
                        <td id="T_46a48_row20_col17" class="data row20 col17" >533.60</td>
                        <td id="T_46a48_row20_col18" class="data row20 col18" >nan</td>
            </tr>
            <tr>
                        <th id="T_46a48_level0_row21" class="row_heading level0 row21" >600519.SS</th>
                        <td id="T_46a48_row21_col0" class="data row21 col0" >贵州茅台</td>
                        <td id="T_46a48_row21_col1" class="data row21 col1" >食品饮料</td>
                        <td id="T_46a48_row21_col2" class="data row21 col2" >30.99</td>
                        <td id="T_46a48_row21_col3" class="data row21 col3" >21.40</td>
                        <td id="T_46a48_row21_col4" class="data row21 col4" >1.65</td>
                        <td id="T_46a48_row21_col5" class="data row21 col5" >30.01</td>
                        <td id="T_46a48_row21_col6" class="data row21 col6" >47.94</td>
                        <td id="T_46a48_row21_col7" class="data row21 col7" >17.87</td>
                        <td id="T_46a48_row21_col8" class="data row21 col8" >7.86</td>
                        <td id="T_46a48_row21_col9" class="data row21 col9" >20.13</td>
                        <td id="T_46a48_row21_col10" class="data row21 col10" >8.75</td>
                        <td id="T_46a48_row21_col11" class="data row21 col11" >37.59</td>
                        <td id="T_46a48_row21_col12" class="data row21 col12" >45.08</td>
                        <td id="T_46a48_row21_col13" class="data row21 col13" >1189.50</td>
                        <td id="T_46a48_row21_col14" class="data row21 col14" >796.91</td>
                        <td id="T_46a48_row21_col15" class="data row21 col15" >58.69</td>
                        <td id="T_46a48_row21_col16" class="data row21 col16" >2.92</td>
                        <td id="T_46a48_row21_col17" class="data row21 col17" >2791.27</td>
                        <td id="T_46a48_row21_col18" class="data row21 col18" >-134.66</td>
            </tr>
            <tr>
                        <th id="T_46a48_level0_row22" class="row_heading level0 row22" >000858.SZ</th>
                        <td id="T_46a48_row22_col0" class="data row22 col0" >五 粮 液</td>
                        <td id="T_46a48_row22_col1" class="data row22 col1" >食品饮料</td>
                        <td id="T_46a48_row22_col2" class="data row22 col2" >16.22</td>
                        <td id="T_46a48_row22_col3" class="data row22 col3" >22.95</td>
                        <td id="T_46a48_row22_col4" class="data row22 col4" >36.06</td>
                        <td id="T_46a48_row22_col5" class="data row22 col5" >21.48</td>
                        <td id="T_46a48_row22_col6" class="data row22 col6" >33.75</td>
                        <td id="T_46a48_row22_col7" class="data row22 col7" >24.06</td>
                        <td id="T_46a48_row22_col8" class="data row22 col8" >9.17</td>
                        <td id="T_46a48_row22_col9" class="data row22 col9" >27.68</td>
                        <td id="T_46a48_row22_col10" class="data row22 col10" >12.02</td>
                        <td id="T_46a48_row22_col11" class="data row22 col11" >22.79</td>
                        <td id="T_46a48_row22_col12" class="data row22 col12" >57.73</td>
                        <td id="T_46a48_row22_col13" class="data row22 col13" >319.59</td>
                        <td id="T_46a48_row22_col14" class="data row22 col14" >381.00</td>
                        <td id="T_46a48_row22_col15" class="data row22 col15" >56.11</td>
                        <td id="T_46a48_row22_col16" class="data row22 col16" >2.03</td>
                        <td id="T_46a48_row22_col17" class="data row22 col17" >1210.44</td>
                        <td id="T_46a48_row22_col18" class="data row22 col18" >-278.74</td>
            </tr>
            <tr>
                        <th id="T_46a48_level0_row23" class="row_heading level0 row23" >600276.SS</th>
                        <td id="T_46a48_row23_col0" class="data row23 col0" >恒瑞医药</td>
                        <td id="T_46a48_row23_col1" class="data row23 col1" >医药生物</td>
                        <td id="T_46a48_row23_col2" class="data row23 col2" >6.63</td>
                        <td id="T_46a48_row23_col3" class="data row23 col3" >11.35</td>
                        <td id="T_46a48_row23_col4" class="data row23 col4" >31.83</td>
                        <td id="T_46a48_row23_col5" class="data row23 col5" >20.95</td>
                        <td id="T_46a48_row23_col6" class="data row23 col6" >23.07</td>
                        <td id="T_46a48_row23_col7" class="data row23 col7" >26.23</td>
                        <td id="T_46a48_row23_col8" class="data row23 col8" >7.31</td>
                        <td id="T_46a48_row23_col9" class="data row23 col9" >25.41</td>
                        <td id="T_46a48_row23_col10" class="data row23 col10" >6.20</td>
                        <td id="T_46a48_row23_col11" class="data row23 col11" >12.33</td>
                        <td id="T_46a48_row23_col12" class="data row23 col12" >29.30</td>
                        <td id="T_46a48_row23_col13" class="data row23 col13" >46.33</td>
                        <td id="T_46a48_row23_col14" class="data row23 col14" >113.50</td>
                        <td id="T_46a48_row23_col15" class="data row23 col15" >69.09</td>
                        <td id="T_46a48_row23_col16" class="data row23 col16" >2.72</td>
                        <td id="T_46a48_row23_col17" class="data row23 col17" >449.74</td>
                        <td id="T_46a48_row23_col18" class="data row23 col18" >-870.82</td>
            </tr>
            <tr>
                        <th id="T_46a48_level0_row24" class="row_heading level0 row24" >601012.SS</th>
                        <td id="T_46a48_row24_col0" class="data row24 col0" >隆基股份</td>
                        <td id="T_46a48_row24_col1" class="data row24 col1" >电气设备</td>
                        <td id="T_46a48_row24_col2" class="data row24 col2" >12.39</td>
                        <td id="T_46a48_row24_col3" class="data row24 col3" >59.38</td>
                        <td id="T_46a48_row24_col4" class="data row24 col4" >24.45</td>
                        <td id="T_46a48_row24_col5" class="data row24 col5" >21.03</td>
                        <td id="T_46a48_row24_col6" class="data row24 col6" >16.28</td>
                        <td id="T_46a48_row24_col7" class="data row24 col7" >49.97</td>
                        <td id="T_46a48_row24_col8" class="data row24 col8" >15.77</td>
                        <td id="T_46a48_row24_col9" class="data row24 col9" >46.72</td>
                        <td id="T_46a48_row24_col10" class="data row24 col10" >68.60</td>
                        <td id="T_46a48_row24_col11" class="data row24 col11" >-97.28</td>
                        <td id="T_46a48_row24_col12" class="data row24 col12" >181.11</td>
                        <td id="T_46a48_row24_col13" class="data row24 col13" >0.04</td>
                        <td id="T_46a48_row24_col14" class="data row24 col14" >187.10</td>
                        <td id="T_46a48_row24_col15" class="data row24 col15" >42.61</td>
                        <td id="T_46a48_row24_col16" class="data row24 col16" >0.91</td>
                        <td id="T_46a48_row24_col17" class="data row24 col17" >391.63</td>
                        <td id="T_46a48_row24_col18" class="data row24 col18" >-872657.34</td>
            </tr>
            <tr>
                        <th id="T_46a48_level0_row25" class="row_heading level0 row25" >600570.SS</th>
                        <td id="T_46a48_row25_col0" class="data row25 col0" >恒生电子</td>
                        <td id="T_46a48_row25_col1" class="data row25 col1" >计算机</td>
                        <td id="T_46a48_row25_col2" class="data row25 col2" >5.11</td>
                        <td id="T_46a48_row25_col3" class="data row25 col3" >49.48</td>
                        <td id="T_46a48_row25_col4" class="data row25 col4" >14.02</td>
                        <td id="T_46a48_row25_col5" class="data row25 col5" >24.06</td>
                        <td id="T_46a48_row25_col6" class="data row25 col6" >26.42</td>
                        <td id="T_46a48_row25_col7" class="data row25 col7" >16.27</td>
                        <td id="T_46a48_row25_col8" class="data row25 col8" >7.59</td>
                        <td id="T_46a48_row25_col9" class="data row25 col9" >49.90</td>
                        <td id="T_46a48_row25_col10" class="data row25 col10" >64.01</td>
                        <td id="T_46a48_row25_col11" class="data row25 col11" >10.32</td>
                        <td id="T_46a48_row25_col12" class="data row25 col12" >20.60</td>
                        <td id="T_46a48_row25_col13" class="data row25 col13" >13.02</td>
                        <td id="T_46a48_row25_col14" class="data row25 col14" >38.43</td>
                        <td id="T_46a48_row25_col15" class="data row25 col15" >60.65</td>
                        <td id="T_46a48_row25_col16" class="data row25 col16" >1.22</td>
                        <td id="T_46a48_row25_col17" class="data row25 col17" >93.11</td>
                        <td id="T_46a48_row25_col18" class="data row25 col18" >-615.42</td>
            </tr>
            <tr>
                        <th id="T_46a48_level0_row26" class="row_heading level0 row26" >000625.SZ</th>
                        <td id="T_46a48_row26_col0" class="data row26 col0" >长安汽车</td>
                        <td id="T_46a48_row26_col1" class="data row26 col1" >汽车</td>
                        <td id="T_46a48_row26_col2" class="data row26 col2" >4.82</td>
                        <td id="T_46a48_row26_col3" class="data row26 col3" >55.77</td>
                        <td id="T_46a48_row26_col4" class="data row26 col4" >39.01</td>
                        <td id="T_46a48_row26_col5" class="data row26 col5" >4.17</td>
                        <td id="T_46a48_row26_col6" class="data row26 col6" >2.53</td>
                        <td id="T_46a48_row26_col7" class="data row26 col7" >3.04</td>
                        <td id="T_46a48_row26_col8" class="data row26 col8" >18.70</td>
                        <td id="T_46a48_row26_col9" class="data row26 col9" >-268.29</td>
                        <td id="T_46a48_row26_col10" class="data row26 col10" >202.57</td>
                        <td id="T_46a48_row26_col11" class="data row26 col11" >-304.21</td>
                        <td id="T_46a48_row26_col12" class="data row26 col12" >575.13</td>
                        <td id="T_46a48_row26_col13" class="data row26 col13" >179.85</td>
                        <td id="T_46a48_row26_col14" class="data row26 col14" >-107.13</td>
                        <td id="T_46a48_row26_col15" class="data row26 col15" >35.21</td>
                        <td id="T_46a48_row26_col16" class="data row26 col16" >-0.13</td>
                        <td id="T_46a48_row26_col17" class="data row26 col17" >124.89</td>
                        <td id="T_46a48_row26_col18" class="data row26 col18" >30.56</td>
            </tr>
            <tr>
                        <th id="T_46a48_level0_row27" class="row_heading level0 row27" >600886.SS</th>
                        <td id="T_46a48_row27_col0" class="data row27 col0" >国投电力</td>
                        <td id="T_46a48_row27_col1" class="data row27 col1" >公用事业</td>
                        <td id="T_46a48_row27_col2" class="data row27 col2" >2.86</td>
                        <td id="T_46a48_row27_col3" class="data row27 col3" >63.92</td>
                        <td id="T_46a48_row27_col4" class="data row27 col4" >20.36</td>
                        <td id="T_46a48_row27_col5" class="data row27 col5" >11.40</td>
                        <td id="T_46a48_row27_col6" class="data row27 col6" >11.52</td>
                        <td id="T_46a48_row27_col7" class="data row27 col7" >8.58</td>
                        <td id="T_46a48_row27_col8" class="data row27 col8" >18.99</td>
                        <td id="T_46a48_row27_col9" class="data row27 col9" >19.99</td>
                        <td id="T_46a48_row27_col10" class="data row27 col10" >13.48</td>
                        <td id="T_46a48_row27_col11" class="data row27 col11" >18.50</td>
                        <td id="T_46a48_row27_col12" class="data row27 col12" >17.96</td>
                        <td id="T_46a48_row27_col13" class="data row27 col13" >185.31</td>
                        <td id="T_46a48_row27_col14" class="data row27 col14" >94.50</td>
                        <td id="T_46a48_row27_col15" class="data row27 col15" >12.88</td>
                        <td id="T_46a48_row27_col16" class="data row27 col16" >0.64</td>
                        <td id="T_46a48_row27_col17" class="data row27 col17" >67.71</td>
                        <td id="T_46a48_row27_col18" class="data row27 col18" >63.46</td>
            </tr>
            <tr>
                        <th id="T_46a48_level0_row28" class="row_heading level0 row28" >002027.SZ</th>
                        <td id="T_46a48_row28_col0" class="data row28 col0" >分众传媒</td>
                        <td id="T_46a48_row28_col1" class="data row28 col1" >传媒</td>
                        <td id="T_46a48_row28_col2" class="data row28 col2" >13.62</td>
                        <td id="T_46a48_row28_col3" class="data row28 col3" >20.21</td>
                        <td id="T_46a48_row28_col4" class="data row28 col4" >33.41</td>
                        <td id="T_46a48_row28_col5" class="data row28 col5" >34.01</td>
                        <td id="T_46a48_row28_col6" class="data row28 col6" >34.64</td>
                        <td id="T_46a48_row28_col7" class="data row28 col7" >1.40</td>
                        <td id="T_46a48_row28_col8" class="data row28 col8" >18.92</td>
                        <td id="T_46a48_row28_col9" class="data row28 col9" >14.23</td>
                        <td id="T_46a48_row28_col10" class="data row28 col10" >91.87</td>
                        <td id="T_46a48_row28_col11" class="data row28 col11" >23.11</td>
                        <td id="T_46a48_row28_col12" class="data row28 col12" >61.17</td>
                        <td id="T_46a48_row28_col13" class="data row28 col13" >80.86</td>
                        <td id="T_46a48_row28_col14" class="data row28 col14" >81.53</td>
                        <td id="T_46a48_row28_col15" class="data row28 col15" >27.05</td>
                        <td id="T_46a48_row28_col16" class="data row28 col16" >1.90</td>
                        <td id="T_46a48_row28_col17" class="data row28 col17" >144.28</td>
                        <td id="T_46a48_row28_col18" class="data row28 col18" >-78.44</td>
            </tr>
            <tr>
                        <th id="T_46a48_level0_row29" class="row_heading level0 row29" >600066.SS</th>
                        <td id="T_46a48_row29_col0" class="data row29 col0" >宇通客车</td>
                        <td id="T_46a48_row29_col1" class="data row29 col1" >汽车</td>
                        <td id="T_46a48_row29_col2" class="data row29 col2" >1.51</td>
                        <td id="T_46a48_row29_col3" class="data row29 col3" >53.64</td>
                        <td id="T_46a48_row29_col4" class="data row29 col4" >47.74</td>
                        <td id="T_46a48_row29_col5" class="data row29 col5" >12.11</td>
                        <td id="T_46a48_row29_col6" class="data row29 col6" >6.35</td>
                        <td id="T_46a48_row29_col7" class="data row29 col7" >-12.40</td>
                        <td id="T_46a48_row29_col8" class="data row29 col8" >14.22</td>
                        <td id="T_46a48_row29_col9" class="data row29 col9" >-38.50</td>
                        <td id="T_46a48_row29_col10" class="data row29 col10" >30.74</td>
                        <td id="T_46a48_row29_col11" class="data row29 col11" >-3.73</td>
                        <td id="T_46a48_row29_col12" class="data row29 col12" >179.13</td>
                        <td id="T_46a48_row29_col13" class="data row29 col13" >17.38</td>
                        <td id="T_46a48_row29_col14" class="data row29 col14" >6.85</td>
                        <td id="T_46a48_row29_col15" class="data row29 col15" >53.83</td>
                        <td id="T_46a48_row29_col16" class="data row29 col16" >-1.40</td>
                        <td id="T_46a48_row29_col17" class="data row29 col17" >29.51</td>
                        <td id="T_46a48_row29_col18" class="data row29 col18" >-69.79</td>
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
#T_f5318_row0_col0,#T_f5318_row0_col1,#T_f5318_row0_col2,#T_f5318_row0_col3,#T_f5318_row0_col4,#T_f5318_row0_col5,#T_f5318_row0_col6,#T_f5318_row0_col7,#T_f5318_row0_col8,#T_f5318_row0_col9,#T_f5318_row0_col10,#T_f5318_row0_col11,#T_f5318_row0_col12,#T_f5318_row0_col13,#T_f5318_row0_col14,#T_f5318_row1_col0,#T_f5318_row1_col1,#T_f5318_row1_col2,#T_f5318_row1_col3,#T_f5318_row1_col4,#T_f5318_row1_col5,#T_f5318_row1_col6,#T_f5318_row1_col7,#T_f5318_row1_col8,#T_f5318_row1_col9,#T_f5318_row1_col10,#T_f5318_row1_col11,#T_f5318_row1_col12,#T_f5318_row1_col13,#T_f5318_row1_col14,#T_f5318_row2_col0,#T_f5318_row2_col1,#T_f5318_row2_col2,#T_f5318_row2_col3,#T_f5318_row2_col4,#T_f5318_row2_col5,#T_f5318_row2_col6,#T_f5318_row2_col7,#T_f5318_row2_col8,#T_f5318_row2_col9,#T_f5318_row2_col10,#T_f5318_row2_col11,#T_f5318_row2_col12,#T_f5318_row2_col13,#T_f5318_row2_col14,#T_f5318_row3_col0,#T_f5318_row3_col1,#T_f5318_row3_col2,#T_f5318_row3_col3,#T_f5318_row3_col4,#T_f5318_row3_col5,#T_f5318_row3_col6,#T_f5318_row3_col7,#T_f5318_row3_col8,#T_f5318_row3_col9,#T_f5318_row3_col10,#T_f5318_row3_col11,#T_f5318_row3_col12,#T_f5318_row3_col13,#T_f5318_row3_col14,#T_f5318_row4_col0,#T_f5318_row4_col1,#T_f5318_row4_col2,#T_f5318_row4_col3,#T_f5318_row4_col4,#T_f5318_row4_col5,#T_f5318_row4_col6,#T_f5318_row4_col7,#T_f5318_row4_col8,#T_f5318_row4_col9,#T_f5318_row4_col10,#T_f5318_row4_col11,#T_f5318_row4_col12,#T_f5318_row4_col13,#T_f5318_row4_col14,#T_f5318_row5_col0,#T_f5318_row5_col1,#T_f5318_row5_col2,#T_f5318_row5_col3,#T_f5318_row5_col4,#T_f5318_row5_col5,#T_f5318_row5_col6,#T_f5318_row5_col7,#T_f5318_row5_col8,#T_f5318_row5_col9,#T_f5318_row5_col10,#T_f5318_row5_col11,#T_f5318_row5_col12,#T_f5318_row5_col13,#T_f5318_row5_col14,#T_f5318_row6_col0,#T_f5318_row6_col1,#T_f5318_row6_col2,#T_f5318_row6_col3,#T_f5318_row6_col4,#T_f5318_row6_col5,#T_f5318_row6_col6,#T_f5318_row6_col7,#T_f5318_row6_col8,#T_f5318_row6_col9,#T_f5318_row6_col10,#T_f5318_row6_col11,#T_f5318_row6_col12,#T_f5318_row6_col13,#T_f5318_row6_col14,#T_f5318_row7_col0,#T_f5318_row7_col1,#T_f5318_row7_col2,#T_f5318_row7_col3,#T_f5318_row7_col4,#T_f5318_row7_col5,#T_f5318_row7_col6,#T_f5318_row7_col7,#T_f5318_row7_col8,#T_f5318_row7_col9,#T_f5318_row7_col10,#T_f5318_row7_col11,#T_f5318_row7_col12,#T_f5318_row7_col13,#T_f5318_row7_col14,#T_f5318_row7_col15,#T_f5318_row8_col0,#T_f5318_row8_col1,#T_f5318_row8_col2,#T_f5318_row8_col3,#T_f5318_row8_col4,#T_f5318_row8_col5,#T_f5318_row8_col6,#T_f5318_row8_col7,#T_f5318_row8_col8,#T_f5318_row8_col9,#T_f5318_row8_col10,#T_f5318_row8_col11,#T_f5318_row8_col12,#T_f5318_row8_col13,#T_f5318_row8_col14,#T_f5318_row8_col15,#T_f5318_row9_col0,#T_f5318_row9_col1,#T_f5318_row9_col2,#T_f5318_row9_col3,#T_f5318_row9_col4,#T_f5318_row9_col5,#T_f5318_row9_col6,#T_f5318_row9_col7,#T_f5318_row9_col8,#T_f5318_row9_col9,#T_f5318_row9_col10,#T_f5318_row9_col11,#T_f5318_row9_col12,#T_f5318_row9_col13,#T_f5318_row9_col14,#T_f5318_row9_col15,#T_f5318_row10_col0,#T_f5318_row10_col1,#T_f5318_row10_col2,#T_f5318_row10_col3,#T_f5318_row10_col4,#T_f5318_row10_col5,#T_f5318_row10_col6,#T_f5318_row10_col7,#T_f5318_row10_col8,#T_f5318_row10_col9,#T_f5318_row10_col10,#T_f5318_row10_col11,#T_f5318_row10_col12,#T_f5318_row10_col13,#T_f5318_row10_col14,#T_f5318_row10_col15,#T_f5318_row11_col0,#T_f5318_row11_col1,#T_f5318_row11_col2,#T_f5318_row11_col3,#T_f5318_row11_col4,#T_f5318_row11_col5,#T_f5318_row11_col6,#T_f5318_row11_col7,#T_f5318_row11_col8,#T_f5318_row11_col9,#T_f5318_row11_col10,#T_f5318_row11_col11,#T_f5318_row11_col12,#T_f5318_row11_col13,#T_f5318_row11_col14,#T_f5318_row11_col15,#T_f5318_row12_col0,#T_f5318_row12_col1,#T_f5318_row12_col2,#T_f5318_row12_col3,#T_f5318_row12_col4,#T_f5318_row12_col5,#T_f5318_row12_col6,#T_f5318_row12_col7,#T_f5318_row12_col8,#T_f5318_row12_col9,#T_f5318_row12_col10,#T_f5318_row12_col11,#T_f5318_row12_col12,#T_f5318_row12_col13,#T_f5318_row12_col14,#T_f5318_row12_col15,#T_f5318_row13_col0,#T_f5318_row13_col1,#T_f5318_row13_col2,#T_f5318_row13_col3,#T_f5318_row13_col4,#T_f5318_row13_col5,#T_f5318_row13_col6,#T_f5318_row13_col7,#T_f5318_row13_col8,#T_f5318_row13_col9,#T_f5318_row13_col10,#T_f5318_row13_col11,#T_f5318_row13_col12,#T_f5318_row13_col13,#T_f5318_row13_col14,#T_f5318_row13_col15,#T_f5318_row14_col0,#T_f5318_row14_col1,#T_f5318_row14_col2,#T_f5318_row14_col3,#T_f5318_row14_col4,#T_f5318_row14_col5,#T_f5318_row14_col6,#T_f5318_row14_col7,#T_f5318_row14_col8,#T_f5318_row14_col9,#T_f5318_row14_col10,#T_f5318_row14_col11,#T_f5318_row14_col12,#T_f5318_row14_col13,#T_f5318_row14_col14,#T_f5318_row14_col15,#T_f5318_row15_col0,#T_f5318_row15_col1,#T_f5318_row15_col2,#T_f5318_row15_col3,#T_f5318_row15_col4,#T_f5318_row15_col5,#T_f5318_row15_col6,#T_f5318_row15_col7,#T_f5318_row15_col8,#T_f5318_row15_col9,#T_f5318_row15_col10,#T_f5318_row15_col11,#T_f5318_row15_col12,#T_f5318_row15_col13,#T_f5318_row15_col14,#T_f5318_row15_col15,#T_f5318_row16_col0,#T_f5318_row16_col1,#T_f5318_row16_col2,#T_f5318_row16_col3,#T_f5318_row16_col4,#T_f5318_row16_col5,#T_f5318_row16_col6,#T_f5318_row16_col7,#T_f5318_row16_col8,#T_f5318_row16_col9,#T_f5318_row16_col10,#T_f5318_row16_col11,#T_f5318_row16_col12,#T_f5318_row16_col13,#T_f5318_row16_col14,#T_f5318_row16_col15,#T_f5318_row17_col0,#T_f5318_row17_col1,#T_f5318_row17_col2,#T_f5318_row17_col3,#T_f5318_row17_col4,#T_f5318_row17_col5,#T_f5318_row17_col6,#T_f5318_row17_col7,#T_f5318_row17_col8,#T_f5318_row17_col9,#T_f5318_row17_col10,#T_f5318_row17_col11,#T_f5318_row17_col12,#T_f5318_row17_col13,#T_f5318_row17_col14,#T_f5318_row17_col15,#T_f5318_row18_col0,#T_f5318_row18_col1,#T_f5318_row18_col2,#T_f5318_row18_col3,#T_f5318_row18_col4,#T_f5318_row18_col5,#T_f5318_row18_col6,#T_f5318_row18_col7,#T_f5318_row18_col8,#T_f5318_row18_col9,#T_f5318_row18_col10,#T_f5318_row18_col11,#T_f5318_row18_col12,#T_f5318_row18_col13,#T_f5318_row18_col14,#T_f5318_row18_col15,#T_f5318_row19_col0,#T_f5318_row19_col1,#T_f5318_row19_col2,#T_f5318_row19_col3,#T_f5318_row19_col4,#T_f5318_row19_col5,#T_f5318_row19_col6,#T_f5318_row19_col7,#T_f5318_row19_col8,#T_f5318_row19_col9,#T_f5318_row19_col10,#T_f5318_row19_col11,#T_f5318_row19_col12,#T_f5318_row19_col13,#T_f5318_row19_col14,#T_f5318_row19_col15,#T_f5318_row20_col0,#T_f5318_row20_col1,#T_f5318_row20_col2,#T_f5318_row20_col3,#T_f5318_row20_col4,#T_f5318_row20_col5,#T_f5318_row20_col6,#T_f5318_row20_col7,#T_f5318_row20_col8,#T_f5318_row20_col9,#T_f5318_row20_col10,#T_f5318_row20_col12,#T_f5318_row20_col13,#T_f5318_row20_col14,#T_f5318_row20_col15,#T_f5318_row21_col0,#T_f5318_row21_col1,#T_f5318_row21_col2,#T_f5318_row21_col3,#T_f5318_row21_col4,#T_f5318_row21_col5,#T_f5318_row21_col6,#T_f5318_row21_col7,#T_f5318_row21_col8,#T_f5318_row21_col9,#T_f5318_row21_col10,#T_f5318_row21_col11,#T_f5318_row21_col12,#T_f5318_row21_col13,#T_f5318_row21_col14,#T_f5318_row21_col15,#T_f5318_row22_col0,#T_f5318_row22_col1,#T_f5318_row22_col2,#T_f5318_row22_col3,#T_f5318_row22_col4,#T_f5318_row22_col5,#T_f5318_row22_col6,#T_f5318_row22_col7,#T_f5318_row22_col8,#T_f5318_row22_col9,#T_f5318_row22_col10,#T_f5318_row22_col11,#T_f5318_row22_col12,#T_f5318_row22_col13,#T_f5318_row22_col14,#T_f5318_row22_col15,#T_f5318_row23_col0,#T_f5318_row23_col1,#T_f5318_row23_col2,#T_f5318_row23_col3,#T_f5318_row23_col4,#T_f5318_row23_col5,#T_f5318_row23_col6,#T_f5318_row23_col7,#T_f5318_row23_col8,#T_f5318_row23_col9,#T_f5318_row23_col10,#T_f5318_row23_col11,#T_f5318_row23_col12,#T_f5318_row23_col13,#T_f5318_row23_col14,#T_f5318_row23_col15,#T_f5318_row24_col0,#T_f5318_row24_col1,#T_f5318_row24_col2,#T_f5318_row24_col3,#T_f5318_row24_col4,#T_f5318_row24_col5,#T_f5318_row24_col6,#T_f5318_row24_col7,#T_f5318_row24_col8,#T_f5318_row24_col9,#T_f5318_row24_col10,#T_f5318_row24_col11,#T_f5318_row24_col12,#T_f5318_row24_col13,#T_f5318_row24_col14,#T_f5318_row24_col15,#T_f5318_row25_col0,#T_f5318_row25_col1,#T_f5318_row25_col2,#T_f5318_row25_col3,#T_f5318_row25_col4,#T_f5318_row25_col5,#T_f5318_row25_col6,#T_f5318_row25_col7,#T_f5318_row25_col8,#T_f5318_row25_col9,#T_f5318_row25_col10,#T_f5318_row25_col11,#T_f5318_row25_col12,#T_f5318_row25_col13,#T_f5318_row25_col14,#T_f5318_row25_col15{
            color:  black;
        }#T_f5318_row0_col15,#T_f5318_row1_col15,#T_f5318_row2_col15,#T_f5318_row3_col15,#T_f5318_row4_col15,#T_f5318_row5_col15,#T_f5318_row6_col15,#T_f5318_row20_col11{
            color:  red;
        }</style><table id="T_f5318_" ><thead>    <tr>        <th class="blank level0" ></th>        <th class="col_heading level0 col0" >负债率</th>        <th class="col_heading level0 col1" >应收比</th>        <th class="col_heading level0 col2" >商誉比</th>        <th class="col_heading level0 col3" >ROE</th>        <th class="col_heading level0 col4" >利润率</th>        <th class="col_heading level0 col5" >收入增长</th>        <th class="col_heading level0 col6" >收入波动</th>        <th class="col_heading level0 col7" >盈利增长</th>        <th class="col_heading level0 col8" >盈利波动</th>        <th class="col_heading level0 col9" >FCF增长</th>        <th class="col_heading level0 col10" >FCF波动</th>        <th class="col_heading level0 col11" >DCF</th>        <th class="col_heading level0 col12" >盈利折现</th>        <th class="col_heading level0 col13" >国家</th>        <th class="col_heading level0 col14" >市值</th>        <th class="col_heading level0 col15" >折价率</th>    </tr>    <tr>        <th class="index_name level0" >Symbol</th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>    </tr></thead><tbody>
                <tr>
                        <th id="T_f5318_level0_row0" class="row_heading level0 row0" >FB</th>
                        <td id="T_f5318_row0_col0" class="data row0 col0" >19.47</td>
                        <td id="T_f5318_row0_col1" class="data row0 col1" >13.19</td>
                        <td id="T_f5318_row0_col2" class="data row0 col2" >14.85</td>
                        <td id="T_f5318_row0_col3" class="data row0 col3" >22.18</td>
                        <td id="T_f5318_row0_col4" class="data row0 col4" >34.71</td>
                        <td id="T_f5318_row0_col5" class="data row0 col5" >28.52</td>
                        <td id="T_f5318_row0_col6" class="data row0 col6" >8.05</td>
                        <td id="T_f5318_row0_col7" class="data row0 col7" >26.68</td>
                        <td id="T_f5318_row0_col8" class="data row0 col8" >38.49</td>
                        <td id="T_f5318_row0_col9" class="data row0 col9" >12.46</td>
                        <td id="T_f5318_row0_col10" class="data row0 col10" >25.14</td>
                        <td id="T_f5318_row0_col11" class="data row0 col11" >342.34</td>
                        <td id="T_f5318_row0_col12" class="data row0 col12" >528.39</td>
                        <td id="T_f5318_row0_col13" class="data row0 col13" >United States</td>
                        <td id="T_f5318_row0_col14" class="data row0 col14" >933.29</td>
                        <td id="T_f5318_row0_col15" class="data row0 col15" >-172.62</td>
            </tr>
            <tr>
                        <th id="T_f5318_level0_row1" class="row_heading level0 row1" >MNST</th>
                        <td id="T_f5318_row1_col0" class="data row1 col0" >16.80</td>
                        <td id="T_f5318_row1_col1" class="data row1 col1" >14.48</td>
                        <td id="T_f5318_row1_col2" class="data row1 col2" >25.80</td>
                        <td id="T_f5318_row1_col3" class="data row1 col3" >25.61</td>
                        <td id="T_f5318_row1_col4" class="data row1 col4" >26.87</td>
                        <td id="T_f5318_row1_col5" class="data row1 col5" >10.94</td>
                        <td id="T_f5318_row1_col6" class="data row1 col6" >1.84</td>
                        <td id="T_f5318_row1_col7" class="data row1 col7" >19.93</td>
                        <td id="T_f5318_row1_col8" class="data row1 col8" >7.89</td>
                        <td id="T_f5318_row1_col9" class="data row1 col9" >14.54</td>
                        <td id="T_f5318_row1_col10" class="data row1 col10" >19.95</td>
                        <td id="T_f5318_row1_col11" class="data row1 col11" >20.10</td>
                        <td id="T_f5318_row1_col12" class="data row1 col12" >22.88</td>
                        <td id="T_f5318_row1_col13" class="data row1 col13" >United States</td>
                        <td id="T_f5318_row1_col14" class="data row1 col14" >50.12</td>
                        <td id="T_f5318_row1_col15" class="data row1 col15" >-149.38</td>
            </tr>
            <tr>
                        <th id="T_f5318_level0_row2" class="row_heading level0 row2" >ABMD</th>
                        <td id="T_f5318_row2_col0" class="data row2 col0" >11.02</td>
                        <td id="T_f5318_row2_col1" class="data row2 col1" >11.47</td>
                        <td id="T_f5318_row2_col2" class="data row2 col2" >5.91</td>
                        <td id="T_f5318_row2_col3" class="data row2 col3" >19.98</td>
                        <td id="T_f5318_row2_col4" class="data row2 col4" >25.83</td>
                        <td id="T_f5318_row2_col5" class="data row2 col5" >13.22</td>
                        <td id="T_f5318_row2_col6" class="data row2 col6" >14.80</td>
                        <td id="T_f5318_row2_col7" class="data row2 col7" >40.13</td>
                        <td id="T_f5318_row2_col8" class="data row2 col8" >80.31</td>
                        <td id="T_f5318_row2_col9" class="data row2 col9" >27.48</td>
                        <td id="T_f5318_row2_col10" class="data row2 col10" >26.26</td>
                        <td id="T_f5318_row2_col11" class="data row2 col11" >5.15</td>
                        <td id="T_f5318_row2_col12" class="data row2 col12" >6.57</td>
                        <td id="T_f5318_row2_col13" class="data row2 col13" >United States</td>
                        <td id="T_f5318_row2_col14" class="data row2 col14" >12.70</td>
                        <td id="T_f5318_row2_col15" class="data row2 col15" >-146.28</td>
            </tr>
            <tr>
                        <th id="T_f5318_level0_row3" class="row_heading level0 row3" >EA</th>
                        <td id="T_f5318_row3_col0" class="data row3 col0" >32.86</td>
                        <td id="T_f5318_row3_col1" class="data row3 col1" >8.33</td>
                        <td id="T_f5318_row3_col2" class="data row3 col2" >25.26</td>
                        <td id="T_f5318_row3_col3" class="data row3 col3" >26.59</td>
                        <td id="T_f5318_row3_col4" class="data row3 col4" >28.92</td>
                        <td id="T_f5318_row3_col5" class="data row3 col5" >4.76</td>
                        <td id="T_f5318_row3_col6" class="data row3 col6" >7.98</td>
                        <td id="T_f5318_row3_col7" class="data row3 col7" >67.93</td>
                        <td id="T_f5318_row3_col8" class="data row3 col8" >112.96</td>
                        <td id="T_f5318_row3_col9" class="data row3 col9" >5.02</td>
                        <td id="T_f5318_row3_col10" class="data row3 col10" >13.41</td>
                        <td id="T_f5318_row3_col11" class="data row3 col11" >22.29</td>
                        <td id="T_f5318_row3_col12" class="data row3 col12" >83.96</td>
                        <td id="T_f5318_row3_col13" class="data row3 col13" >United States</td>
                        <td id="T_f5318_row3_col14" class="data row3 col14" >40.47</td>
                        <td id="T_f5318_row3_col15" class="data row3 col15" >-81.52</td>
            </tr>
            <tr>
                        <th id="T_f5318_level0_row4" class="row_heading level0 row4" >TPL</th>
                        <td id="T_f5318_row4_col0" class="data row4 col0" >15.12</td>
                        <td id="T_f5318_row4_col1" class="data row4 col1" >15.95</td>
                        <td id="T_f5318_row4_col2" class="data row4 col2" >0.00</td>
                        <td id="T_f5318_row4_col3" class="data row4 col3" >69.19</td>
                        <td id="T_f5318_row4_col4" class="data row4 col4" >64.09</td>
                        <td id="T_f5318_row4_col5" class="data row4 col5" >39.88</td>
                        <td id="T_f5318_row4_col6" class="data row4 col6" >69.48</td>
                        <td id="T_f5318_row4_col7" class="data row4 col7" >40.97</td>
                        <td id="T_f5318_row4_col8" class="data row4 col8" >80.80</td>
                        <td id="T_f5318_row4_col9" class="data row4 col9" >57.34</td>
                        <td id="T_f5318_row4_col10" class="data row4 col10" >80.25</td>
                        <td id="T_f5318_row4_col11" class="data row4 col11" >8.43</td>
                        <td id="T_f5318_row4_col12" class="data row4 col12" >6.70</td>
                        <td id="T_f5318_row4_col13" class="data row4 col13" >United States</td>
                        <td id="T_f5318_row4_col14" class="data row4 col14" >11.56</td>
                        <td id="T_f5318_row4_col15" class="data row4 col15" >-37.17</td>
            </tr>
            <tr>
                        <th id="T_f5318_level0_row5" class="row_heading level0 row5" >QLYS</th>
                        <td id="T_f5318_row5_col0" class="data row5 col0" >45.10</td>
                        <td id="T_f5318_row5_col1" class="data row5 col1" >27.60</td>
                        <td id="T_f5318_row5_col2" class="data row5 col2" >1.84</td>
                        <td id="T_f5318_row5_col3" class="data row5 col3" >17.09</td>
                        <td id="T_f5318_row5_col4" class="data row5 col4" >21.21</td>
                        <td id="T_f5318_row5_col5" class="data row5 col5" >16.33</td>
                        <td id="T_f5318_row5_col6" class="data row5 col6" >4.08</td>
                        <td id="T_f5318_row5_col7" class="data row5 col7" >31.59</td>
                        <td id="T_f5318_row5_col8" class="data row5 col8" >10.36</td>
                        <td id="T_f5318_row5_col9" class="data row5 col9" >29.80</td>
                        <td id="T_f5318_row5_col10" class="data row5 col10" >17.14</td>
                        <td id="T_f5318_row5_col11" class="data row5 col11" >3.01</td>
                        <td id="T_f5318_row5_col12" class="data row5 col12" >1.78</td>
                        <td id="T_f5318_row5_col13" class="data row5 col13" >United States</td>
                        <td id="T_f5318_row5_col14" class="data row5 col14" >3.87</td>
                        <td id="T_f5318_row5_col15" class="data row5 col15" >-28.40</td>
            </tr>
            <tr>
                        <th id="T_f5318_level0_row6" class="row_heading level0 row6" >CODA</th>
                        <td id="T_f5318_row6_col0" class="data row6 col0" >9.58</td>
                        <td id="T_f5318_row6_col1" class="data row6 col1" >15.00</td>
                        <td id="T_f5318_row6_col2" class="data row6 col2" >9.83</td>
                        <td id="T_f5318_row6_col3" class="data row6 col3" >17.85</td>
                        <td id="T_f5318_row6_col4" class="data row6 col4" >20.94</td>
                        <td id="T_f5318_row6_col5" class="data row6 col5" >6.34</td>
                        <td id="T_f5318_row6_col6" class="data row6 col6" >30.04</td>
                        <td id="T_f5318_row6_col7" class="data row6 col7" >6.04</td>
                        <td id="T_f5318_row6_col8" class="data row6 col8" >42.71</td>
                        <td id="T_f5318_row6_col9" class="data row6 col9" >30.12</td>
                        <td id="T_f5318_row6_col10" class="data row6 col10" >79.02</td>
                        <td id="T_f5318_row6_col11" class="data row6 col11" >0.08</td>
                        <td id="T_f5318_row6_col12" class="data row6 col12" >0.06</td>
                        <td id="T_f5318_row6_col13" class="data row6 col13" >United States</td>
                        <td id="T_f5318_row6_col14" class="data row6 col14" >0.10</td>
                        <td id="T_f5318_row6_col15" class="data row6 col15" >-23.58</td>
            </tr>
            <tr>
                        <th id="T_f5318_level0_row7" class="row_heading level0 row7" >VRTX</th>
                        <td id="T_f5318_row7_col0" class="data row7 col0" >26.08</td>
                        <td id="T_f5318_row7_col1" class="data row7 col1" >14.27</td>
                        <td id="T_f5318_row7_col2" class="data row7 col2" >11.54</td>
                        <td id="T_f5318_row7_col3" class="data row7 col3" >27.71</td>
                        <td id="T_f5318_row7_col4" class="data row7 col4" >37.84</td>
                        <td id="T_f5318_row7_col5" class="data row7 col5" >36.04</td>
                        <td id="T_f5318_row7_col6" class="data row7 col6" >13.32</td>
                        <td id="T_f5318_row7_col7" class="data row7 col7" >260.79</td>
                        <td id="T_f5318_row7_col8" class="data row7 col8" >386.71</td>
                        <td id="T_f5318_row7_col9" class="data row7 col9" >61.71</td>
                        <td id="T_f5318_row7_col10" class="data row7 col10" >36.80</td>
                        <td id="T_f5318_row7_col11" class="data row7 col11" >79.50</td>
                        <td id="T_f5318_row7_col12" class="data row7 col12" >815.40</td>
                        <td id="T_f5318_row7_col13" class="data row7 col13" >United States</td>
                        <td id="T_f5318_row7_col14" class="data row7 col14" >54.46</td>
                        <td id="T_f5318_row7_col15" class="data row7 col15" >31.50</td>
            </tr>
            <tr>
                        <th id="T_f5318_level0_row8" class="row_heading level0 row8" >EXEL</th>
                        <td id="T_f5318_row8_col0" class="data row8 col0" >12.08</td>
                        <td id="T_f5318_row8_col1" class="data row8 col1" >16.75</td>
                        <td id="T_f5318_row8_col2" class="data row8 col2" >3.39</td>
                        <td id="T_f5318_row8_col3" class="data row8 col3" >33.18</td>
                        <td id="T_f5318_row8_col4" class="data row8 col4" >39.85</td>
                        <td id="T_f5318_row8_col5" class="data row8 col5" >34.70</td>
                        <td id="T_f5318_row8_col6" class="data row8 col6" >47.11</td>
                        <td id="T_f5318_row8_col7" class="data row8 col7" >76.26</td>
                        <td id="T_f5318_row8_col8" class="data row8 col8" >234.92</td>
                        <td id="T_f5318_row8_col9" class="data row8 col9" >44.63</td>
                        <td id="T_f5318_row8_col10" class="data row8 col10" >115.32</td>
                        <td id="T_f5318_row8_col11" class="data row8 col11" >10.98</td>
                        <td id="T_f5318_row8_col12" class="data row8 col12" >20.33</td>
                        <td id="T_f5318_row8_col13" class="data row8 col13" >United States</td>
                        <td id="T_f5318_row8_col14" class="data row8 col14" >7.00</td>
                        <td id="T_f5318_row8_col15" class="data row8 col15" >36.25</td>
            </tr>
            <tr>
                        <th id="T_f5318_level0_row9" class="row_heading level0 row9" >INVA</th>
                        <td id="T_f5318_row9_col0" class="data row9 col0" >39.19</td>
                        <td id="T_f5318_row9_col1" class="data row9 col1" >27.89</td>
                        <td id="T_f5318_row9_col2" class="data row9 col2" >0.00</td>
                        <td id="T_f5318_row9_col3" class="data row9 col3" >73.43</td>
                        <td id="T_f5318_row9_col4" class="data row9 col4" >85.00</td>
                        <td id="T_f5318_row9_col5" class="data row9 col5" >16.40</td>
                        <td id="T_f5318_row9_col6" class="data row9 col6" >14.87</td>
                        <td id="T_f5318_row9_col7" class="data row9 col7" >59.00</td>
                        <td id="T_f5318_row9_col8" class="data row9 col8" >128.13</td>
                        <td id="T_f5318_row9_col9" class="data row9 col9" >31.50</td>
                        <td id="T_f5318_row9_col10" class="data row9 col10" >22.92</td>
                        <td id="T_f5318_row9_col11" class="data row9 col11" >6.42</td>
                        <td id="T_f5318_row9_col12" class="data row9 col12" >10.76</td>
                        <td id="T_f5318_row9_col13" class="data row9 col13" >United States</td>
                        <td id="T_f5318_row9_col14" class="data row9 col14" >0.92</td>
                        <td id="T_f5318_row9_col15" class="data row9 col15" >85.60</td>
            </tr>
            <tr>
                        <th id="T_f5318_level0_row10" class="row_heading level0 row10" >MASI</th>
                        <td id="T_f5318_row10_col0" class="data row10 col0" >17.80</td>
                        <td id="T_f5318_row10_col1" class="data row10 col1" >15.86</td>
                        <td id="T_f5318_row10_col2" class="data row10 col2" >7.33</td>
                        <td id="T_f5318_row10_col3" class="data row10 col3" >17.77</td>
                        <td id="T_f5318_row10_col4" class="data row10 col4" >20.07</td>
                        <td id="T_f5318_row10_col5" class="data row10 col5" >13.28</td>
                        <td id="T_f5318_row10_col6" class="data row10 col6" >7.52</td>
                        <td id="T_f5318_row10_col7" class="data row10 col7" >26.32</td>
                        <td id="T_f5318_row10_col8" class="data row10 col8" >27.06</td>
                        <td id="T_f5318_row10_col9" class="data row10 col9" >551.99</td>
                        <td id="T_f5318_row10_col10" class="data row10 col10" >991.44</td>
                        <td id="T_f5318_row10_col11" class="data row10 col11" >399.28</td>
                        <td id="T_f5318_row10_col12" class="data row10 col12" >4.62</td>
                        <td id="T_f5318_row10_col13" class="data row10 col13" >United States</td>
                        <td id="T_f5318_row10_col14" class="data row10 col14" >11.57</td>
                        <td id="T_f5318_row10_col15" class="data row10 col15" >97.10</td>
            </tr>
            <tr>
                        <th id="T_f5318_level0_row11" class="row_heading level0 row11" >TROW</th>
                        <td id="T_f5318_row11_col0" class="data row11 col0" >13.04</td>
                        <td id="T_f5318_row11_col1" class="data row11 col1" >14.31</td>
                        <td id="T_f5318_row11_col2" class="data row11 col2" >8.64</td>
                        <td id="T_f5318_row11_col3" class="data row11 col3" >29.13</td>
                        <td id="T_f5318_row11_col4" class="data row11 col4" >35.30</td>
                        <td id="T_f5318_row11_col5" class="data row11 col5" >8.57</td>
                        <td id="T_f5318_row11_col6" class="data row11 col6" >3.47</td>
                        <td id="T_f5318_row11_col7" class="data row11 col7" >16.67</td>
                        <td id="T_f5318_row11_col8" class="data row11 col8" >5.71</td>
                        <td id="T_f5318_row11_col9" class="data row11 col9" >1088.12</td>
                        <td id="T_f5318_row11_col10" class="data row11 col10" >1867.35</td>
                        <td id="T_f5318_row11_col11" class="data row11 col11" >20579.20</td>
                        <td id="T_f5318_row11_col12" class="data row11 col12" >38.30</td>
                        <td id="T_f5318_row11_col13" class="data row11 col13" >United States</td>
                        <td id="T_f5318_row11_col14" class="data row11 col14" >43.75</td>
                        <td id="T_f5318_row11_col15" class="data row11 col15" >99.79</td>
            </tr>
            <tr>
                        <th id="T_f5318_level0_row12" class="row_heading level0 row12" >AFYA</th>
                        <td id="T_f5318_row12_col0" class="data row12 col0" >40.88</td>
                        <td id="T_f5318_row12_col1" class="data row12 col1" >26.92</td>
                        <td id="T_f5318_row12_col2" class="data row12 col2" >29.14</td>
                        <td id="T_f5318_row12_col3" class="data row12 col3" >33.40</td>
                        <td id="T_f5318_row12_col4" class="data row12 col4" >22.92</td>
                        <td id="T_f5318_row12_col5" class="data row12 col5" >79.80</td>
                        <td id="T_f5318_row12_col6" class="data row12 col6" >39.05</td>
                        <td id="T_f5318_row12_col7" class="data row12 col7" >86.08</td>
                        <td id="T_f5318_row12_col8" class="data row12 col8" >6.79</td>
                        <td id="T_f5318_row12_col9" class="data row12 col9" >158.53</td>
                        <td id="T_f5318_row12_col10" class="data row12 col10" >138.40</td>
                        <td id="T_f5318_row12_col11" class="data row12 col11" >29.68</td>
                        <td id="T_f5318_row12_col12" class="data row12 col12" >10.76</td>
                        <td id="T_f5318_row12_col13" class="data row12 col13" >Brazil</td>
                        <td id="T_f5318_row12_col14" class="data row12 col14" >2.35</td>
                        <td id="T_f5318_row12_col15" class="data row12 col15" >0.00</td>
            </tr>
            <tr>
                        <th id="T_f5318_level0_row13" class="row_heading level0 row13" >ANET</th>
                        <td id="T_f5318_row13_col0" class="data row13 col0" >29.94</td>
                        <td id="T_f5318_row13_col1" class="data row13 col1" >16.81</td>
                        <td id="T_f5318_row13_col2" class="data row13 col2" >5.71</td>
                        <td id="T_f5318_row13_col3" class="data row13 col3" >22.40</td>
                        <td id="T_f5318_row13_col4" class="data row13 col4" >26.00</td>
                        <td id="T_f5318_row13_col5" class="data row13 col5" >12.96</td>
                        <td id="T_f5318_row13_col6" class="data row13 col6" >17.29</td>
                        <td id="T_f5318_row13_col7" class="data row13 col7" >37.80</td>
                        <td id="T_f5318_row13_col8" class="data row13 col8" >107.63</td>
                        <td id="T_f5318_row13_col9" class="data row13 col9" >17.13</td>
                        <td id="T_f5318_row13_col10" class="data row13 col10" >69.73</td>
                        <td id="T_f5318_row13_col11" class="data row13 col11" >13.65</td>
                        <td id="T_f5318_row13_col12" class="data row13 col12" >17.60</td>
                        <td id="T_f5318_row13_col13" class="data row13 col13" >0</td>
                        <td id="T_f5318_row13_col14" class="data row13 col14" >25.50</td>
                        <td id="T_f5318_row13_col15" class="data row13 col15" >0.00</td>
            </tr>
            <tr>
                        <th id="T_f5318_level0_row14" class="row_heading level0 row14" >EDTK</th>
                        <td id="T_f5318_row14_col0" class="data row14 col0" >38.97</td>
                        <td id="T_f5318_row14_col1" class="data row14 col1" >0.28</td>
                        <td id="T_f5318_row14_col2" class="data row14 col2" >0.00</td>
                        <td id="T_f5318_row14_col3" class="data row14 col3" >45.21</td>
                        <td id="T_f5318_row14_col4" class="data row14 col4" >36.78</td>
                        <td id="T_f5318_row14_col5" class="data row14 col5" >40.69</td>
                        <td id="T_f5318_row14_col6" class="data row14 col6" >35.01</td>
                        <td id="T_f5318_row14_col7" class="data row14 col7" >29.67</td>
                        <td id="T_f5318_row14_col8" class="data row14 col8" >20.76</td>
                        <td id="T_f5318_row14_col9" class="data row14 col9" >83.37</td>
                        <td id="T_f5318_row14_col10" class="data row14 col10" >40.18</td>
                        <td id="T_f5318_row14_col11" class="data row14 col11" >0.46</td>
                        <td id="T_f5318_row14_col12" class="data row14 col12" >0.22</td>
                        <td id="T_f5318_row14_col13" class="data row14 col13" >China</td>
                        <td id="T_f5318_row14_col14" class="data row14 col14" >0.03</td>
                        <td id="T_f5318_row14_col15" class="data row14 col15" >0.00</td>
            </tr>
            <tr>
                        <th id="T_f5318_level0_row15" class="row_heading level0 row15" >ESNT</th>
                        <td id="T_f5318_row15_col0" class="data row15 col0" >25.76</td>
                        <td id="T_f5318_row15_col1" class="data row15 col1" >5.25</td>
                        <td id="T_f5318_row15_col2" class="data row15 col2" >0.00</td>
                        <td id="T_f5318_row15_col3" class="data row15 col3" >17.16</td>
                        <td id="T_f5318_row15_col4" class="data row15 col4" >59.53</td>
                        <td id="T_f5318_row15_col5" class="data row15 col5" >18.49</td>
                        <td id="T_f5318_row15_col6" class="data row15 col6" >7.56</td>
                        <td id="T_f5318_row15_col7" class="data row15 col7" >5.43</td>
                        <td id="T_f5318_row15_col8" class="data row15 col8" >27.02</td>
                        <td id="T_f5318_row15_col9" class="data row15 col9" >29.32</td>
                        <td id="T_f5318_row15_col10" class="data row15 col10" >38.04</td>
                        <td id="T_f5318_row15_col11" class="data row15 col11" >15.03</td>
                        <td id="T_f5318_row15_col12" class="data row15 col12" >6.68</td>
                        <td id="T_f5318_row15_col13" class="data row15 col13" >0</td>
                        <td id="T_f5318_row15_col14" class="data row15 col14" >5.36</td>
                        <td id="T_f5318_row15_col15" class="data row15 col15" >0.00</td>
            </tr>
            <tr>
                        <th id="T_f5318_level0_row16" class="row_heading level0 row16" >GMAB</th>
                        <td id="T_f5318_row16_col0" class="data row16 col0" >9.56</td>
                        <td id="T_f5318_row16_col1" class="data row16 col1" >26.82</td>
                        <td id="T_f5318_row16_col2" class="data row16 col2" >0.00</td>
                        <td id="T_f5318_row16_col3" class="data row16 col3" >19.07</td>
                        <td id="T_f5318_row16_col4" class="data row16 col4" >45.68</td>
                        <td id="T_f5318_row16_col5" class="data row16 col5" >64.57</td>
                        <td id="T_f5318_row16_col6" class="data row16 col6" >32.24</td>
                        <td id="T_f5318_row16_col7" class="data row16 col7" >66.73</td>
                        <td id="T_f5318_row16_col8" class="data row16 col8" >46.36</td>
                        <td id="T_f5318_row16_col9" class="data row16 col9" >128.78</td>
                        <td id="T_f5318_row16_col10" class="data row16 col10" >229.94</td>
                        <td id="T_f5318_row16_col11" class="data row16 col11" >334.31</td>
                        <td id="T_f5318_row16_col12" class="data row16 col12" >128.74</td>
                        <td id="T_f5318_row16_col13" class="data row16 col13" >Denmark</td>
                        <td id="T_f5318_row16_col14" class="data row16 col14" >26.53</td>
                        <td id="T_f5318_row16_col15" class="data row16 col15" >0.00</td>
            </tr>
            <tr>
                        <th id="T_f5318_level0_row17" class="row_heading level0 row17" >GRMN</th>
                        <td id="T_f5318_row17_col0" class="data row17 col0" >21.55</td>
                        <td id="T_f5318_row17_col1" class="data row17 col1" >20.53</td>
                        <td id="T_f5318_row17_col2" class="data row17 col2" >10.59</td>
                        <td id="T_f5318_row17_col3" class="data row17 col3" >18.23</td>
                        <td id="T_f5318_row17_col4" class="data row17 col4" >23.12</td>
                        <td id="T_f5318_row17_col5" class="data row17 col5" >10.30</td>
                        <td id="T_f5318_row17_col6" class="data row17 col6" >2.69</td>
                        <td id="T_f5318_row17_col7" class="data row17 col7" >13.10</td>
                        <td id="T_f5318_row17_col8" class="data row17 col8" >21.13</td>
                        <td id="T_f5318_row17_col9" class="data row17 col9" >28.73</td>
                        <td id="T_f5318_row17_col10" class="data row17 col10" >46.45</td>
                        <td id="T_f5318_row17_col11" class="data row17 col11" >18.17</td>
                        <td id="T_f5318_row17_col12" class="data row17 col12" >14.99</td>
                        <td id="T_f5318_row17_col13" class="data row17 col13" >Switzerland</td>
                        <td id="T_f5318_row17_col14" class="data row17 col14" >27.26</td>
                        <td id="T_f5318_row17_col15" class="data row17 col15" >0.00</td>
            </tr>
            <tr>
                        <th id="T_f5318_level0_row18" class="row_heading level0 row18" >HLG</th>
                        <td id="T_f5318_row18_col0" class="data row18 col0" >27.00</td>
                        <td id="T_f5318_row18_col1" class="data row18 col1" >5.67</td>
                        <td id="T_f5318_row18_col2" class="data row18 col2" >3.04</td>
                        <td id="T_f5318_row18_col3" class="data row18 col3" >17.04</td>
                        <td id="T_f5318_row18_col4" class="data row18 col4" >20.82</td>
                        <td id="T_f5318_row18_col5" class="data row18 col5" >21.38</td>
                        <td id="T_f5318_row18_col6" class="data row18 col6" >19.96</td>
                        <td id="T_f5318_row18_col7" class="data row18 col7" >30.30</td>
                        <td id="T_f5318_row18_col8" class="data row18 col8" >3.42</td>
                        <td id="T_f5318_row18_col9" class="data row18 col9" >51.62</td>
                        <td id="T_f5318_row18_col10" class="data row18 col10" >116.64</td>
                        <td id="T_f5318_row18_col11" class="data row18 col11" >16.55</td>
                        <td id="T_f5318_row18_col12" class="data row18 col12" >7.05</td>
                        <td id="T_f5318_row18_col13" class="data row18 col13" >China</td>
                        <td id="T_f5318_row18_col14" class="data row18 col14" >1.05</td>
                        <td id="T_f5318_row18_col15" class="data row18 col15" >0.00</td>
            </tr>
            <tr>
                        <th id="T_f5318_level0_row19" class="row_heading level0 row19" >INMD</th>
                        <td id="T_f5318_row19_col0" class="data row19 col0" >13.62</td>
                        <td id="T_f5318_row19_col1" class="data row19 col1" >6.83</td>
                        <td id="T_f5318_row19_col2" class="data row19 col2" >0.00</td>
                        <td id="T_f5318_row19_col3" class="data row19 col3" >40.33</td>
                        <td id="T_f5318_row19_col4" class="data row19 col4" >28.59</td>
                        <td id="T_f5318_row19_col5" class="data row19 col5" >58.43</td>
                        <td id="T_f5318_row19_col6" class="data row19 col6" >27.85</td>
                        <td id="T_f5318_row19_col7" class="data row19 col7" >116.57</td>
                        <td id="T_f5318_row19_col8" class="data row19 col8" >81.88</td>
                        <td id="T_f5318_row19_col9" class="data row19 col9" >83.23</td>
                        <td id="T_f5318_row19_col10" class="data row19 col10" >63.84</td>
                        <td id="T_f5318_row19_col11" class="data row19 col11" >3.41</td>
                        <td id="T_f5318_row19_col12" class="data row19 col12" >4.85</td>
                        <td id="T_f5318_row19_col13" class="data row19 col13" >Israel</td>
                        <td id="T_f5318_row19_col14" class="data row19 col14" >3.20</td>
                        <td id="T_f5318_row19_col15" class="data row19 col15" >0.00</td>
            </tr>
            <tr>
                        <th id="T_f5318_level0_row20" class="row_heading level0 row20" >KKR</th>
                        <td id="T_f5318_row20_col0" class="data row20 col0" >48.88</td>
                        <td id="T_f5318_row20_col1" class="data row20 col1" >22.75</td>
                        <td id="T_f5318_row20_col2" class="data row20 col2" >0.69</td>
                        <td id="T_f5318_row20_col3" class="data row20 col3" >16.25</td>
                        <td id="T_f5318_row20_col4" class="data row20 col4" >24.05</td>
                        <td id="T_f5318_row20_col5" class="data row20 col5" >26.64</td>
                        <td id="T_f5318_row20_col6" class="data row20 col6" >54.69</td>
                        <td id="T_f5318_row20_col7" class="data row20 col7" >29.41</td>
                        <td id="T_f5318_row20_col8" class="data row20 col8" >41.83</td>
                        <td id="T_f5318_row20_col9" class="data row20 col9" >30.83</td>
                        <td id="T_f5318_row20_col10" class="data row20 col10" >71.97</td>
                        <td id="T_f5318_row20_col11" class="data row20 col11" >-157.74</td>
                        <td id="T_f5318_row20_col12" class="data row20 col12" >40.34</td>
                        <td id="T_f5318_row20_col13" class="data row20 col13" >United States</td>
                        <td id="T_f5318_row20_col14" class="data row20 col14" >32.00</td>
                        <td id="T_f5318_row20_col15" class="data row20 col15" >0.00</td>
            </tr>
            <tr>
                        <th id="T_f5318_level0_row21" class="row_heading level0 row21" >KL</th>
                        <td id="T_f5318_row21_col0" class="data row21 col0" >28.18</td>
                        <td id="T_f5318_row21_col1" class="data row21 col1" >0.94</td>
                        <td id="T_f5318_row21_col2" class="data row21 col2" >0.00</td>
                        <td id="T_f5318_row21_col3" class="data row21 col3" >19.86</td>
                        <td id="T_f5318_row21_col4" class="data row21 col4" >30.06</td>
                        <td id="T_f5318_row21_col5" class="data row21 col5" >50.49</td>
                        <td id="T_f5318_row21_col6" class="data row21 col6" >27.87</td>
                        <td id="T_f5318_row21_col7" class="data row21 col7" >83.99</td>
                        <td id="T_f5318_row21_col8" class="data row21 col8" >37.56</td>
                        <td id="T_f5318_row21_col9" class="data row21 col9" >63.22</td>
                        <td id="T_f5318_row21_col10" class="data row21 col10" >5.53</td>
                        <td id="T_f5318_row21_col11" class="data row21 col11" >20.88</td>
                        <td id="T_f5318_row21_col12" class="data row21 col12" >31.62</td>
                        <td id="T_f5318_row21_col13" class="data row21 col13" >0</td>
                        <td id="T_f5318_row21_col14" class="data row21 col14" >11.67</td>
                        <td id="T_f5318_row21_col15" class="data row21 col15" >0.00</td>
            </tr>
            <tr>
                        <th id="T_f5318_level0_row22" class="row_heading level0 row22" >NTES</th>
                        <td id="T_f5318_row22_col0" class="data row22 col0" >33.89</td>
                        <td id="T_f5318_row22_col1" class="data row22 col1" >8.99</td>
                        <td id="T_f5318_row22_col2" class="data row22 col2" >0.39</td>
                        <td id="T_f5318_row22_col3" class="data row22 col3" >21.57</td>
                        <td id="T_f5318_row22_col4" class="data row22 col4" >22.09</td>
                        <td id="T_f5318_row22_col5" class="data row22 col5" >18.43</td>
                        <td id="T_f5318_row22_col6" class="data row22 col6" >5.14</td>
                        <td id="T_f5318_row22_col7" class="data row22 col7" >53.15</td>
                        <td id="T_f5318_row22_col8" class="data row22 col8" >166.31</td>
                        <td id="T_f5318_row22_col9" class="data row22 col9" >33.70</td>
                        <td id="T_f5318_row22_col10" class="data row22 col10" >20.88</td>
                        <td id="T_f5318_row22_col11" class="data row22 col11" >440.86</td>
                        <td id="T_f5318_row22_col12" class="data row22 col12" >532.03</td>
                        <td id="T_f5318_row22_col13" class="data row22 col13" >China</td>
                        <td id="T_f5318_row22_col14" class="data row22 col14" >77.44</td>
                        <td id="T_f5318_row22_col15" class="data row22 col15" >0.00</td>
            </tr>
            <tr>
                        <th id="T_f5318_level0_row23" class="row_heading level0 row23" >OCG</th>
                        <td id="T_f5318_row23_col0" class="data row23 col0" >18.34</td>
                        <td id="T_f5318_row23_col1" class="data row23 col1" >3.45</td>
                        <td id="T_f5318_row23_col2" class="data row23 col2" >0.00</td>
                        <td id="T_f5318_row23_col3" class="data row23 col3" >58.19</td>
                        <td id="T_f5318_row23_col4" class="data row23 col4" >42.78</td>
                        <td id="T_f5318_row23_col5" class="data row23 col5" >90.46</td>
                        <td id="T_f5318_row23_col6" class="data row23 col6" >85.99</td>
                        <td id="T_f5318_row23_col7" class="data row23 col7" >84.43</td>
                        <td id="T_f5318_row23_col8" class="data row23 col8" >228.95</td>
                        <td id="T_f5318_row23_col9" class="data row23 col9" >87.97</td>
                        <td id="T_f5318_row23_col10" class="data row23 col10" >143.00</td>
                        <td id="T_f5318_row23_col11" class="data row23 col11" >0.53</td>
                        <td id="T_f5318_row23_col12" class="data row23 col12" >0.33</td>
                        <td id="T_f5318_row23_col13" class="data row23 col13" >China</td>
                        <td id="T_f5318_row23_col14" class="data row23 col14" >0.10</td>
                        <td id="T_f5318_row23_col15" class="data row23 col15" >0.00</td>
            </tr>
            <tr>
                        <th id="T_f5318_level0_row24" class="row_heading level0 row24" >PAX</th>
                        <td id="T_f5318_row24_col0" class="data row24 col0" >44.90</td>
                        <td id="T_f5318_row24_col1" class="data row24 col1" >21.53</td>
                        <td id="T_f5318_row24_col2" class="data row24 col2" >0.00</td>
                        <td id="T_f5318_row24_col3" class="data row24 col3" >80.55</td>
                        <td id="T_f5318_row24_col4" class="data row24 col4" >47.64</td>
                        <td id="T_f5318_row24_col5" class="data row24 col5" >4.98</td>
                        <td id="T_f5318_row24_col6" class="data row24 col6" >16.45</td>
                        <td id="T_f5318_row24_col7" class="data row24 col7" >20.16</td>
                        <td id="T_f5318_row24_col8" class="data row24 col8" >19.65</td>
                        <td id="T_f5318_row24_col9" class="data row24 col9" >16.81</td>
                        <td id="T_f5318_row24_col10" class="data row24 col10" >2.43</td>
                        <td id="T_f5318_row24_col11" class="data row24 col11" >0.88</td>
                        <td id="T_f5318_row24_col12" class="data row24 col12" >1.16</td>
                        <td id="T_f5318_row24_col13" class="data row24 col13" >Cayman Islands</td>
                        <td id="T_f5318_row24_col14" class="data row24 col14" >2.30</td>
                        <td id="T_f5318_row24_col15" class="data row24 col15" >0.00</td>
            </tr>
            <tr>
                        <th id="T_f5318_level0_row25" class="row_heading level0 row25" >TSM</th>
                        <td id="T_f5318_row25_col0" class="data row25 col0" >32.97</td>
                        <td id="T_f5318_row25_col1" class="data row25 col1" >10.91</td>
                        <td id="T_f5318_row25_col2" class="data row25 col2" >0.29</td>
                        <td id="T_f5318_row25_col3" class="data row25 col3" >23.33</td>
                        <td id="T_f5318_row25_col4" class="data row25 col4" >35.07</td>
                        <td id="T_f5318_row25_col5" class="data row25 col5" >11.48</td>
                        <td id="T_f5318_row25_col6" class="data row25 col6" >11.89</td>
                        <td id="T_f5318_row25_col7" class="data row25 col7" >16.70</td>
                        <td id="T_f5318_row25_col8" class="data row25 col8" >28.89</td>
                        <td id="T_f5318_row25_col9" class="data row25 col9" >21.73</td>
                        <td id="T_f5318_row25_col10" class="data row25 col10" >74.11</td>
                        <td id="T_f5318_row25_col11" class="data row25 col11" >5416.26</td>
                        <td id="T_f5318_row25_col12" class="data row25 col12" >7625.61</td>
                        <td id="T_f5318_row25_col13" class="data row25 col13" >Taiwan</td>
                        <td id="T_f5318_row25_col14" class="data row25 col14" >616.88</td>
                        <td id="T_f5318_row25_col15" class="data row25 col15" >0.00</td>
            </tr>
    </tbody></table>



### 观察列表




<style  type="text/css" >
#T_089c9_row0_col0,#T_089c9_row0_col1,#T_089c9_row0_col2,#T_089c9_row0_col3,#T_089c9_row0_col4,#T_089c9_row0_col5,#T_089c9_row0_col6,#T_089c9_row0_col7,#T_089c9_row0_col8,#T_089c9_row0_col9,#T_089c9_row0_col10,#T_089c9_row0_col11,#T_089c9_row0_col12,#T_089c9_row0_col13,#T_089c9_row0_col14,#T_089c9_row0_col15,#T_089c9_row1_col0,#T_089c9_row1_col1,#T_089c9_row1_col2,#T_089c9_row1_col3,#T_089c9_row1_col4,#T_089c9_row1_col5,#T_089c9_row1_col6,#T_089c9_row1_col7,#T_089c9_row1_col8,#T_089c9_row1_col9,#T_089c9_row1_col10,#T_089c9_row1_col11,#T_089c9_row1_col12,#T_089c9_row1_col13,#T_089c9_row1_col14,#T_089c9_row2_col0,#T_089c9_row2_col1,#T_089c9_row2_col2,#T_089c9_row2_col3,#T_089c9_row2_col4,#T_089c9_row2_col5,#T_089c9_row2_col6,#T_089c9_row2_col7,#T_089c9_row2_col8,#T_089c9_row2_col9,#T_089c9_row2_col10,#T_089c9_row2_col11,#T_089c9_row2_col12,#T_089c9_row2_col13,#T_089c9_row2_col14,#T_089c9_row3_col0,#T_089c9_row3_col1,#T_089c9_row3_col2,#T_089c9_row3_col4,#T_089c9_row3_col5,#T_089c9_row3_col6,#T_089c9_row3_col7,#T_089c9_row3_col8,#T_089c9_row3_col9,#T_089c9_row3_col10,#T_089c9_row3_col13,#T_089c9_row3_col14,#T_089c9_row3_col15,#T_089c9_row4_col0,#T_089c9_row4_col1,#T_089c9_row4_col2,#T_089c9_row4_col3,#T_089c9_row4_col4,#T_089c9_row4_col5,#T_089c9_row4_col6,#T_089c9_row4_col7,#T_089c9_row4_col8,#T_089c9_row4_col9,#T_089c9_row4_col10,#T_089c9_row4_col11,#T_089c9_row4_col12,#T_089c9_row4_col13,#T_089c9_row4_col14,#T_089c9_row4_col15,#T_089c9_row5_col0,#T_089c9_row5_col1,#T_089c9_row5_col2,#T_089c9_row5_col3,#T_089c9_row5_col4,#T_089c9_row5_col5,#T_089c9_row5_col6,#T_089c9_row5_col7,#T_089c9_row5_col8,#T_089c9_row5_col9,#T_089c9_row5_col10,#T_089c9_row5_col11,#T_089c9_row5_col12,#T_089c9_row5_col13,#T_089c9_row5_col14,#T_089c9_row6_col0,#T_089c9_row6_col1,#T_089c9_row6_col2,#T_089c9_row6_col3,#T_089c9_row6_col4,#T_089c9_row6_col5,#T_089c9_row6_col6,#T_089c9_row6_col8,#T_089c9_row6_col10,#T_089c9_row6_col11,#T_089c9_row6_col12,#T_089c9_row6_col13,#T_089c9_row6_col14,#T_089c9_row7_col0,#T_089c9_row7_col1,#T_089c9_row7_col2,#T_089c9_row7_col3,#T_089c9_row7_col4,#T_089c9_row7_col6,#T_089c9_row7_col7,#T_089c9_row7_col8,#T_089c9_row7_col10,#T_089c9_row7_col11,#T_089c9_row7_col12,#T_089c9_row7_col13,#T_089c9_row7_col14,#T_089c9_row7_col15,#T_089c9_row8_col0,#T_089c9_row8_col1,#T_089c9_row8_col2,#T_089c9_row8_col5,#T_089c9_row8_col6,#T_089c9_row8_col7,#T_089c9_row8_col8,#T_089c9_row8_col10,#T_089c9_row8_col13,#T_089c9_row8_col14,#T_089c9_row8_col15,#T_089c9_row9_col0,#T_089c9_row9_col1,#T_089c9_row9_col2,#T_089c9_row9_col3,#T_089c9_row9_col4,#T_089c9_row9_col5,#T_089c9_row9_col6,#T_089c9_row9_col7,#T_089c9_row9_col8,#T_089c9_row9_col10,#T_089c9_row9_col11,#T_089c9_row9_col12,#T_089c9_row9_col13,#T_089c9_row9_col14,#T_089c9_row9_col15,#T_089c9_row10_col0,#T_089c9_row10_col1,#T_089c9_row10_col2,#T_089c9_row10_col3,#T_089c9_row10_col4,#T_089c9_row10_col5,#T_089c9_row10_col6,#T_089c9_row10_col7,#T_089c9_row10_col8,#T_089c9_row10_col9,#T_089c9_row10_col10,#T_089c9_row10_col11,#T_089c9_row10_col12,#T_089c9_row10_col13,#T_089c9_row10_col14,#T_089c9_row10_col15,#T_089c9_row11_col0,#T_089c9_row11_col1,#T_089c9_row11_col2,#T_089c9_row11_col3,#T_089c9_row11_col5,#T_089c9_row11_col6,#T_089c9_row11_col8,#T_089c9_row11_col10,#T_089c9_row11_col13,#T_089c9_row11_col14,#T_089c9_row11_col15,#T_089c9_row12_col0,#T_089c9_row12_col1,#T_089c9_row12_col2,#T_089c9_row12_col3,#T_089c9_row12_col4,#T_089c9_row12_col5,#T_089c9_row12_col6,#T_089c9_row12_col7,#T_089c9_row12_col8,#T_089c9_row12_col9,#T_089c9_row12_col10,#T_089c9_row12_col11,#T_089c9_row12_col12,#T_089c9_row12_col13,#T_089c9_row12_col14,#T_089c9_row12_col15,#T_089c9_row13_col0,#T_089c9_row13_col1,#T_089c9_row13_col2,#T_089c9_row13_col3,#T_089c9_row13_col4,#T_089c9_row13_col5,#T_089c9_row13_col6,#T_089c9_row13_col7,#T_089c9_row13_col8,#T_089c9_row13_col9,#T_089c9_row13_col10,#T_089c9_row13_col11,#T_089c9_row13_col12,#T_089c9_row13_col13,#T_089c9_row13_col14,#T_089c9_row14_col0,#T_089c9_row14_col1,#T_089c9_row14_col2,#T_089c9_row14_col5,#T_089c9_row14_col6,#T_089c9_row14_col7,#T_089c9_row14_col8,#T_089c9_row14_col10,#T_089c9_row14_col13,#T_089c9_row14_col14,#T_089c9_row14_col15,#T_089c9_row15_col0,#T_089c9_row15_col1,#T_089c9_row15_col2,#T_089c9_row15_col3,#T_089c9_row15_col4,#T_089c9_row15_col5,#T_089c9_row15_col6,#T_089c9_row15_col7,#T_089c9_row15_col8,#T_089c9_row15_col9,#T_089c9_row15_col10,#T_089c9_row15_col11,#T_089c9_row15_col12,#T_089c9_row15_col13,#T_089c9_row15_col14,#T_089c9_row15_col15,#T_089c9_row16_col0,#T_089c9_row16_col1,#T_089c9_row16_col2,#T_089c9_row16_col3,#T_089c9_row16_col4,#T_089c9_row16_col5,#T_089c9_row16_col6,#T_089c9_row16_col7,#T_089c9_row16_col8,#T_089c9_row16_col9,#T_089c9_row16_col10,#T_089c9_row16_col11,#T_089c9_row16_col12,#T_089c9_row16_col13,#T_089c9_row16_col14,#T_089c9_row17_col0,#T_089c9_row17_col1,#T_089c9_row17_col2,#T_089c9_row17_col3,#T_089c9_row17_col4,#T_089c9_row17_col5,#T_089c9_row17_col6,#T_089c9_row17_col7,#T_089c9_row17_col8,#T_089c9_row17_col9,#T_089c9_row17_col10,#T_089c9_row17_col11,#T_089c9_row17_col12,#T_089c9_row17_col13,#T_089c9_row17_col14,#T_089c9_row18_col0,#T_089c9_row18_col1,#T_089c9_row18_col2,#T_089c9_row18_col3,#T_089c9_row18_col4,#T_089c9_row18_col5,#T_089c9_row18_col6,#T_089c9_row18_col7,#T_089c9_row18_col8,#T_089c9_row18_col9,#T_089c9_row18_col10,#T_089c9_row18_col11,#T_089c9_row18_col12,#T_089c9_row18_col13,#T_089c9_row18_col14,#T_089c9_row18_col15,#T_089c9_row19_col0,#T_089c9_row19_col1,#T_089c9_row19_col2,#T_089c9_row19_col3,#T_089c9_row19_col4,#T_089c9_row19_col5,#T_089c9_row19_col6,#T_089c9_row19_col8,#T_089c9_row19_col10,#T_089c9_row19_col11,#T_089c9_row19_col13,#T_089c9_row19_col14,#T_089c9_row20_col0,#T_089c9_row20_col1,#T_089c9_row20_col2,#T_089c9_row20_col3,#T_089c9_row20_col5,#T_089c9_row20_col6,#T_089c9_row20_col7,#T_089c9_row20_col8,#T_089c9_row20_col9,#T_089c9_row20_col10,#T_089c9_row20_col13,#T_089c9_row20_col14,#T_089c9_row20_col15,#T_089c9_row21_col0,#T_089c9_row21_col1,#T_089c9_row21_col2,#T_089c9_row21_col3,#T_089c9_row21_col4,#T_089c9_row21_col5,#T_089c9_row21_col6,#T_089c9_row21_col7,#T_089c9_row21_col8,#T_089c9_row21_col10,#T_089c9_row21_col11,#T_089c9_row21_col12,#T_089c9_row21_col13,#T_089c9_row21_col14,#T_089c9_row21_col15,#T_089c9_row22_col0,#T_089c9_row22_col1,#T_089c9_row22_col2,#T_089c9_row22_col3,#T_089c9_row22_col4,#T_089c9_row22_col5,#T_089c9_row22_col6,#T_089c9_row22_col8,#T_089c9_row22_col9,#T_089c9_row22_col10,#T_089c9_row22_col11,#T_089c9_row22_col12,#T_089c9_row22_col13,#T_089c9_row22_col14,#T_089c9_row22_col15,#T_089c9_row23_col0,#T_089c9_row23_col1,#T_089c9_row23_col2,#T_089c9_row23_col6,#T_089c9_row23_col8,#T_089c9_row23_col9,#T_089c9_row23_col10,#T_089c9_row23_col13,#T_089c9_row23_col14,#T_089c9_row23_col15,#T_089c9_row24_col0,#T_089c9_row24_col1,#T_089c9_row24_col2,#T_089c9_row24_col3,#T_089c9_row24_col4,#T_089c9_row24_col5,#T_089c9_row24_col6,#T_089c9_row24_col7,#T_089c9_row24_col8,#T_089c9_row24_col9,#T_089c9_row24_col10,#T_089c9_row24_col11,#T_089c9_row24_col12,#T_089c9_row24_col13,#T_089c9_row24_col14,#T_089c9_row25_col0,#T_089c9_row25_col1,#T_089c9_row25_col2,#T_089c9_row25_col3,#T_089c9_row25_col4,#T_089c9_row25_col5,#T_089c9_row25_col6,#T_089c9_row25_col7,#T_089c9_row25_col8,#T_089c9_row25_col9,#T_089c9_row25_col10,#T_089c9_row25_col11,#T_089c9_row25_col12,#T_089c9_row25_col13,#T_089c9_row25_col14,#T_089c9_row25_col15,#T_089c9_row26_col0,#T_089c9_row26_col1,#T_089c9_row26_col2,#T_089c9_row26_col3,#T_089c9_row26_col4,#T_089c9_row26_col5,#T_089c9_row26_col6,#T_089c9_row26_col7,#T_089c9_row26_col8,#T_089c9_row26_col10,#T_089c9_row26_col12,#T_089c9_row26_col13,#T_089c9_row26_col14,#T_089c9_row26_col15,#T_089c9_row27_col0,#T_089c9_row27_col1,#T_089c9_row27_col2,#T_089c9_row27_col3,#T_089c9_row27_col4,#T_089c9_row27_col5,#T_089c9_row27_col6,#T_089c9_row27_col8,#T_089c9_row27_col9,#T_089c9_row27_col10,#T_089c9_row27_col11,#T_089c9_row27_col12,#T_089c9_row27_col13,#T_089c9_row27_col14,#T_089c9_row28_col0,#T_089c9_row28_col1,#T_089c9_row28_col2,#T_089c9_row28_col3,#T_089c9_row28_col4,#T_089c9_row28_col6,#T_089c9_row28_col7,#T_089c9_row28_col8,#T_089c9_row28_col9,#T_089c9_row28_col10,#T_089c9_row28_col11,#T_089c9_row28_col12,#T_089c9_row28_col13,#T_089c9_row28_col14,#T_089c9_row29_col0,#T_089c9_row29_col1,#T_089c9_row29_col2,#T_089c9_row29_col3,#T_089c9_row29_col4,#T_089c9_row29_col6,#T_089c9_row29_col8,#T_089c9_row29_col10,#T_089c9_row29_col11,#T_089c9_row29_col12,#T_089c9_row29_col13,#T_089c9_row29_col14,#T_089c9_row30_col0,#T_089c9_row30_col1,#T_089c9_row30_col2,#T_089c9_row30_col3,#T_089c9_row30_col4,#T_089c9_row30_col5,#T_089c9_row30_col6,#T_089c9_row30_col8,#T_089c9_row30_col10,#T_089c9_row30_col11,#T_089c9_row30_col13,#T_089c9_row30_col14,#T_089c9_row30_col15,#T_089c9_row31_col0,#T_089c9_row31_col1,#T_089c9_row31_col2,#T_089c9_row31_col3,#T_089c9_row31_col4,#T_089c9_row31_col6,#T_089c9_row31_col8,#T_089c9_row31_col10,#T_089c9_row31_col11,#T_089c9_row31_col12,#T_089c9_row31_col13,#T_089c9_row31_col14,#T_089c9_row32_col0,#T_089c9_row32_col1,#T_089c9_row32_col2,#T_089c9_row32_col3,#T_089c9_row32_col4,#T_089c9_row32_col6,#T_089c9_row32_col8,#T_089c9_row32_col9,#T_089c9_row32_col10,#T_089c9_row32_col11,#T_089c9_row32_col12,#T_089c9_row32_col13,#T_089c9_row32_col14,#T_089c9_row32_col15,#T_089c9_row33_col0,#T_089c9_row33_col1,#T_089c9_row33_col2,#T_089c9_row33_col4,#T_089c9_row33_col5,#T_089c9_row33_col6,#T_089c9_row33_col8,#T_089c9_row33_col9,#T_089c9_row33_col10,#T_089c9_row33_col11,#T_089c9_row33_col13,#T_089c9_row33_col14,#T_089c9_row33_col15,#T_089c9_row34_col0,#T_089c9_row34_col1,#T_089c9_row34_col2,#T_089c9_row34_col3,#T_089c9_row34_col5,#T_089c9_row34_col6,#T_089c9_row34_col7,#T_089c9_row34_col8,#T_089c9_row34_col10,#T_089c9_row34_col13,#T_089c9_row34_col14,#T_089c9_row34_col15,#T_089c9_row35_col0,#T_089c9_row35_col1,#T_089c9_row35_col2,#T_089c9_row35_col3,#T_089c9_row35_col5,#T_089c9_row35_col6,#T_089c9_row35_col8,#T_089c9_row35_col10,#T_089c9_row35_col11,#T_089c9_row35_col13,#T_089c9_row35_col14,#T_089c9_row35_col15{
            color:  black;
        }#T_089c9_row1_col15,#T_089c9_row2_col15,#T_089c9_row3_col3,#T_089c9_row3_col11,#T_089c9_row3_col12,#T_089c9_row5_col15,#T_089c9_row6_col7,#T_089c9_row6_col9,#T_089c9_row6_col15,#T_089c9_row7_col5,#T_089c9_row7_col9,#T_089c9_row8_col3,#T_089c9_row8_col4,#T_089c9_row8_col9,#T_089c9_row8_col11,#T_089c9_row8_col12,#T_089c9_row9_col9,#T_089c9_row11_col4,#T_089c9_row11_col7,#T_089c9_row11_col9,#T_089c9_row11_col11,#T_089c9_row11_col12,#T_089c9_row13_col15,#T_089c9_row14_col3,#T_089c9_row14_col4,#T_089c9_row14_col9,#T_089c9_row14_col11,#T_089c9_row14_col12,#T_089c9_row16_col15,#T_089c9_row17_col15,#T_089c9_row19_col7,#T_089c9_row19_col9,#T_089c9_row19_col12,#T_089c9_row19_col15,#T_089c9_row20_col4,#T_089c9_row20_col11,#T_089c9_row20_col12,#T_089c9_row21_col9,#T_089c9_row22_col7,#T_089c9_row23_col3,#T_089c9_row23_col4,#T_089c9_row23_col5,#T_089c9_row23_col7,#T_089c9_row23_col11,#T_089c9_row23_col12,#T_089c9_row24_col15,#T_089c9_row26_col9,#T_089c9_row26_col11,#T_089c9_row27_col7,#T_089c9_row27_col15,#T_089c9_row28_col5,#T_089c9_row28_col15,#T_089c9_row29_col5,#T_089c9_row29_col7,#T_089c9_row29_col9,#T_089c9_row29_col15,#T_089c9_row30_col7,#T_089c9_row30_col9,#T_089c9_row30_col12,#T_089c9_row31_col5,#T_089c9_row31_col7,#T_089c9_row31_col9,#T_089c9_row31_col15,#T_089c9_row32_col5,#T_089c9_row32_col7,#T_089c9_row33_col3,#T_089c9_row33_col7,#T_089c9_row33_col12,#T_089c9_row34_col4,#T_089c9_row34_col9,#T_089c9_row34_col11,#T_089c9_row34_col12,#T_089c9_row35_col4,#T_089c9_row35_col7,#T_089c9_row35_col9,#T_089c9_row35_col12{
            color:  red;
        }</style><table id="T_089c9_" ><thead>    <tr>        <th class="blank level0" ></th>        <th class="col_heading level0 col0" >负债率</th>        <th class="col_heading level0 col1" >应收比</th>        <th class="col_heading level0 col2" >商誉比</th>        <th class="col_heading level0 col3" >ROE</th>        <th class="col_heading level0 col4" >利润率</th>        <th class="col_heading level0 col5" >收入增长</th>        <th class="col_heading level0 col6" >收入波动</th>        <th class="col_heading level0 col7" >盈利增长</th>        <th class="col_heading level0 col8" >盈利波动</th>        <th class="col_heading level0 col9" >FCF增长</th>        <th class="col_heading level0 col10" >FCF波动</th>        <th class="col_heading level0 col11" >DCF</th>        <th class="col_heading level0 col12" >盈利折现</th>        <th class="col_heading level0 col13" >国家</th>        <th class="col_heading level0 col14" >市值</th>        <th class="col_heading level0 col15" >折价率</th>    </tr>    <tr>        <th class="index_name level0" >Symbol</th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>    </tr></thead><tbody>
                <tr>
                        <th id="T_089c9_level0_row0" class="row_heading level0 row0" >BABA</th>
                        <td id="T_089c9_row0_col0" class="data row0 col0" >33.70</td>
                        <td id="T_089c9_row0_col1" class="data row0 col1" >8.56</td>
                        <td id="T_089c9_row0_col2" class="data row0 col2" >36.64</td>
                        <td id="T_089c9_row0_col3" class="data row0 col3" >17.71</td>
                        <td id="T_089c9_row0_col4" class="data row0 col4" >26.46</td>
                        <td id="T_089c9_row0_col5" class="data row0 col5" >47.99</td>
                        <td id="T_089c9_row0_col6" class="data row0 col6" >11.65</td>
                        <td id="T_089c9_row0_col7" class="data row0 col7" >51.30</td>
                        <td id="T_089c9_row0_col8" class="data row0 col8" >16.92</td>
                        <td id="T_089c9_row0_col9" class="data row0 col9" >28.25</td>
                        <td id="T_089c9_row0_col10" class="data row0 col10" >19.50</td>
                        <td id="T_089c9_row0_col11" class="data row0 col11" >2820.11</td>
                        <td id="T_089c9_row0_col12" class="data row0 col12" >3534.63</td>
                        <td id="T_089c9_row0_col13" class="data row0 col13" >China</td>
                        <td id="T_089c9_row0_col14" class="data row0 col14" >595.64</td>
                        <td id="T_089c9_row0_col15" class="data row0 col15" >nan</td>
            </tr>
            <tr>
                        <th id="T_089c9_level0_row1" class="row_heading level0 row1" >AAPL</th>
                        <td id="T_089c9_row1_col0" class="data row1 col0" >79.83</td>
                        <td id="T_089c9_row1_col1" class="data row1 col1" >13.64</td>
                        <td id="T_089c9_row1_col2" class="data row1 col2" >0.00</td>
                        <td id="T_089c9_row1_col3" class="data row1 col3" >60.14</td>
                        <td id="T_089c9_row1_col4" class="data row1 col4" >21.41</td>
                        <td id="T_089c9_row1_col5" class="data row1 col5" >6.44</td>
                        <td id="T_089c9_row1_col6" class="data row1 col6" >8.99</td>
                        <td id="T_089c9_row1_col7" class="data row1 col7" >6.61</td>
                        <td id="T_089c9_row1_col8" class="data row1 col8" >15.33</td>
                        <td id="T_089c9_row1_col9" class="data row1 col9" >13.42</td>
                        <td id="T_089c9_row1_col10" class="data row1 col10" >18.68</td>
                        <td id="T_089c9_row1_col11" class="data row1 col11" >1120.12</td>
                        <td id="T_089c9_row1_col12" class="data row1 col12" >837.11</td>
                        <td id="T_089c9_row1_col13" class="data row1 col13" >United States</td>
                        <td id="T_089c9_row1_col14" class="data row1 col14" >2168.21</td>
                        <td id="T_089c9_row1_col15" class="data row1 col15" >-93.57</td>
            </tr>
            <tr>
                        <th id="T_089c9_level0_row2" class="row_heading level0 row2" >FB</th>
                        <td id="T_089c9_row2_col0" class="data row2 col0" >19.47</td>
                        <td id="T_089c9_row2_col1" class="data row2 col1" >13.19</td>
                        <td id="T_089c9_row2_col2" class="data row2 col2" >14.85</td>
                        <td id="T_089c9_row2_col3" class="data row2 col3" >22.18</td>
                        <td id="T_089c9_row2_col4" class="data row2 col4" >34.71</td>
                        <td id="T_089c9_row2_col5" class="data row2 col5" >28.52</td>
                        <td id="T_089c9_row2_col6" class="data row2 col6" >8.05</td>
                        <td id="T_089c9_row2_col7" class="data row2 col7" >26.68</td>
                        <td id="T_089c9_row2_col8" class="data row2 col8" >38.49</td>
                        <td id="T_089c9_row2_col9" class="data row2 col9" >12.46</td>
                        <td id="T_089c9_row2_col10" class="data row2 col10" >25.14</td>
                        <td id="T_089c9_row2_col11" class="data row2 col11" >342.34</td>
                        <td id="T_089c9_row2_col12" class="data row2 col12" >528.39</td>
                        <td id="T_089c9_row2_col13" class="data row2 col13" >United States</td>
                        <td id="T_089c9_row2_col14" class="data row2 col14" >933.29</td>
                        <td id="T_089c9_row2_col15" class="data row2 col15" >-172.62</td>
            </tr>
            <tr>
                        <th id="T_089c9_level0_row3" class="row_heading level0 row3" >TLSA</th>
                        <td id="T_089c9_row3_col0" class="data row3 col0" >331.88</td>
                        <td id="T_089c9_row3_col1" class="data row3 col1" >0.00</td>
                        <td id="T_089c9_row3_col2" class="data row3 col2" >0.00</td>
                        <td id="T_089c9_row3_col3" class="data row3 col3" >-299.85</td>
                        <td id="T_089c9_row3_col4" class="data row3 col4" >0.00</td>
                        <td id="T_089c9_row3_col5" class="data row3 col5" >0.00</td>
                        <td id="T_089c9_row3_col6" class="data row3 col6" >0.00</td>
                        <td id="T_089c9_row3_col7" class="data row3 col7" >9.68</td>
                        <td id="T_089c9_row3_col8" class="data row3 col8" >15.05</td>
                        <td id="T_089c9_row3_col9" class="data row3 col9" >18.40</td>
                        <td id="T_089c9_row3_col10" class="data row3 col10" >49.60</td>
                        <td id="T_089c9_row3_col11" class="data row3 col11" >-0.12</td>
                        <td id="T_089c9_row3_col12" class="data row3 col12" >-0.14</td>
                        <td id="T_089c9_row3_col13" class="data row3 col13" >United Kingdom</td>
                        <td id="T_089c9_row3_col14" class="data row3 col14" >0.22</td>
                        <td id="T_089c9_row3_col15" class="data row3 col15" >nan</td>
            </tr>
            <tr>
                        <th id="T_089c9_level0_row4" class="row_heading level0 row4" >JD</th>
                        <td id="T_089c9_row4_col0" class="data row4 col0" >47.52</td>
                        <td id="T_089c9_row4_col1" class="data row4 col1" >1.94</td>
                        <td id="T_089c9_row4_col2" class="data row4 col2" >5.81</td>
                        <td id="T_089c9_row4_col3" class="data row4 col3" >9.19</td>
                        <td id="T_089c9_row4_col4" class="data row4 col4" >2.04</td>
                        <td id="T_089c9_row4_col5" class="data row4 col5" >27.22</td>
                        <td id="T_089c9_row4_col6" class="data row4 col6" >2.22</td>
                        <td id="T_089c9_row4_col7" class="data row4 col7" >417.65</td>
                        <td id="T_089c9_row4_col8" class="data row4 col8" >1067.16</td>
                        <td id="T_089c9_row4_col9" class="data row4 col9" >117.46</td>
                        <td id="T_089c9_row4_col10" class="data row4 col10" >215.36</td>
                        <td id="T_089c9_row4_col11" class="data row4 col11" >2129.83</td>
                        <td id="T_089c9_row4_col12" class="data row4 col12" >22477.66</td>
                        <td id="T_089c9_row4_col13" class="data row4 col13" >China</td>
                        <td id="T_089c9_row4_col14" class="data row4 col14" >119.32</td>
                        <td id="T_089c9_row4_col15" class="data row4 col15" >nan</td>
            </tr>
            <tr>
                        <th id="T_089c9_level0_row5" class="row_heading level0 row5" >NVDA</th>
                        <td id="T_089c9_row5_col0" class="data row5 col0" >41.33</td>
                        <td id="T_089c9_row5_col1" class="data row5 col1" >14.57</td>
                        <td id="T_089c9_row5_col2" class="data row5 col2" >24.82</td>
                        <td id="T_089c9_row5_col3" class="data row5 col3" >33.42</td>
                        <td id="T_089c9_row5_col4" class="data row5 col4" >29.58</td>
                        <td id="T_089c9_row5_col5" class="data row5 col5" >22.18</td>
                        <td id="T_089c9_row5_col6" class="data row5 col6" >29.80</td>
                        <td id="T_089c9_row5_col7" class="data row5 col7" >19.45</td>
                        <td id="T_089c9_row5_col8" class="data row5 col8" >45.97</td>
                        <td id="T_089c9_row5_col9" class="data row5 col9" >17.95</td>
                        <td id="T_089c9_row5_col10" class="data row5 col10" >15.59</td>
                        <td id="T_089c9_row5_col11" class="data row5 col11" >75.68</td>
                        <td id="T_089c9_row5_col12" class="data row5 col12" >74.77</td>
                        <td id="T_089c9_row5_col13" class="data row5 col13" >United States</td>
                        <td id="T_089c9_row5_col14" class="data row5 col14" >418.11</td>
                        <td id="T_089c9_row5_col15" class="data row5 col15" >-452.50</td>
            </tr>
            <tr>
                        <th id="T_089c9_level0_row6" class="row_heading level0 row6" >SOGO</th>
                        <td id="T_089c9_row6_col0" class="data row6 col0" >29.89</td>
                        <td id="T_089c9_row6_col1" class="data row6 col1" >8.24</td>
                        <td id="T_089c9_row6_col2" class="data row6 col2" >0.67</td>
                        <td id="T_089c9_row6_col3" class="data row6 col3" >4.04</td>
                        <td id="T_089c9_row6_col4" class="data row6 col4" >3.43</td>
                        <td id="T_089c9_row6_col5" class="data row6 col5" >2.30</td>
                        <td id="T_089c9_row6_col6" class="data row6 col6" >22.50</td>
                        <td id="T_089c9_row6_col7" class="data row6 col7" >-70.36</td>
                        <td id="T_089c9_row6_col8" class="data row6 col8" >131.71</td>
                        <td id="T_089c9_row6_col9" class="data row6 col9" >-4.09</td>
                        <td id="T_089c9_row6_col10" class="data row6 col10" >162.33</td>
                        <td id="T_089c9_row6_col11" class="data row6 col11" >0.83</td>
                        <td id="T_089c9_row6_col12" class="data row6 col12" >0.03</td>
                        <td id="T_089c9_row6_col13" class="data row6 col13" >United States</td>
                        <td id="T_089c9_row6_col14" class="data row6 col14" >3.24</td>
                        <td id="T_089c9_row6_col15" class="data row6 col15" >-290.50</td>
            </tr>
            <tr>
                        <th id="T_089c9_level0_row7" class="row_heading level0 row7" >TCOM</th>
                        <td id="T_089c9_row7_col0" class="data row7 col0" >45.76</td>
                        <td id="T_089c9_row7_col1" class="data row7 col1" >48.59</td>
                        <td id="T_089c9_row7_col2" class="data row7 col2" >59.14</td>
                        <td id="T_089c9_row7_col3" class="data row7 col3" >1.84</td>
                        <td id="T_089c9_row7_col4" class="data row7 col4" >3.39</td>
                        <td id="T_089c9_row7_col5" class="data row7 col5" >-5.97</td>
                        <td id="T_089c9_row7_col6" class="data row7 col6" >36.96</td>
                        <td id="T_089c9_row7_col7" class="data row7 col7" >111.92</td>
                        <td id="T_089c9_row7_col8" class="data row7 col8" >365.78</td>
                        <td id="T_089c9_row7_col9" class="data row7 col9" >-56.07</td>
                        <td id="T_089c9_row7_col10" class="data row7 col10" >96.00</td>
                        <td id="T_089c9_row7_col11" class="data row7 col11" >5.82</td>
                        <td id="T_089c9_row7_col12" class="data row7 col12" >191.39</td>
                        <td id="T_089c9_row7_col13" class="data row7 col13" >China</td>
                        <td id="T_089c9_row7_col14" class="data row7 col14" >25.29</td>
                        <td id="T_089c9_row7_col15" class="data row7 col15" >nan</td>
            </tr>
            <tr>
                        <th id="T_089c9_level0_row8" class="row_heading level0 row8" >NIO</th>
                        <td id="T_089c9_row8_col0" class="data row8 col0" >41.69</td>
                        <td id="T_089c9_row8_col1" class="data row8 col1" >10.10</td>
                        <td id="T_089c9_row8_col2" class="data row8 col2" >0.00</td>
                        <td id="T_089c9_row8_col3" class="data row8 col3" >-28.88</td>
                        <td id="T_089c9_row8_col4" class="data row8 col4" >-217.18</td>
                        <td id="T_089c9_row8_col5" class="data row8 col5" >inf</td>
                        <td id="T_089c9_row8_col6" class="data row8 col6" >0.00</td>
                        <td id="T_089c9_row8_col7" class="data row8 col7" >35.53</td>
                        <td id="T_089c9_row8_col8" class="data row8 col8" >149.80</td>
                        <td id="T_089c9_row8_col9" class="data row8 col9" >-7.85</td>
                        <td id="T_089c9_row8_col10" class="data row8 col10" >96.90</td>
                        <td id="T_089c9_row8_col11" class="data row8 col11" >-65.56</td>
                        <td id="T_089c9_row8_col12" class="data row8 col12" >-358.06</td>
                        <td id="T_089c9_row8_col13" class="data row8 col13" >nan</td>
                        <td id="T_089c9_row8_col14" class="data row8 col14" >67.44</td>
                        <td id="T_089c9_row8_col15" class="data row8 col15" >nan</td>
            </tr>
            <tr>
                        <th id="T_089c9_level0_row9" class="row_heading level0 row9" >BIDU</th>
                        <td id="T_089c9_row9_col0" class="data row9 col0" >42.34</td>
                        <td id="T_089c9_row9_col1" class="data row9 col1" >10.82</td>
                        <td id="T_089c9_row9_col2" class="data row9 col2" >12.18</td>
                        <td id="T_089c9_row9_col3" class="data row9 col3" >11.59</td>
                        <td id="T_089c9_row9_col4" class="data row9 col4" >17.64</td>
                        <td id="T_089c9_row9_col5" class="data row9 col5" >7.63</td>
                        <td id="T_089c9_row9_col6" class="data row9 col6" >10.70</td>
                        <td id="T_089c9_row9_col7" class="data row9 col7" >316.86</td>
                        <td id="T_089c9_row9_col8" class="data row9 col8" >589.45</td>
                        <td id="T_089c9_row9_col9" class="data row9 col9" >-11.75</td>
                        <td id="T_089c9_row9_col10" class="data row9 col10" >8.08</td>
                        <td id="T_089c9_row9_col11" class="data row9 col11" >217.15</td>
                        <td id="T_089c9_row9_col12" class="data row9 col12" >14101.41</td>
                        <td id="T_089c9_row9_col13" class="data row9 col13" >China</td>
                        <td id="T_089c9_row9_col14" class="data row9 col14" >68.75</td>
                        <td id="T_089c9_row9_col15" class="data row9 col15" >nan</td>
            </tr>
            <tr>
                        <th id="T_089c9_level0_row10" class="row_heading level0 row10" >NTES</th>
                        <td id="T_089c9_row10_col0" class="data row10 col0" >33.89</td>
                        <td id="T_089c9_row10_col1" class="data row10 col1" >8.99</td>
                        <td id="T_089c9_row10_col2" class="data row10 col2" >0.39</td>
                        <td id="T_089c9_row10_col3" class="data row10 col3" >21.57</td>
                        <td id="T_089c9_row10_col4" class="data row10 col4" >22.09</td>
                        <td id="T_089c9_row10_col5" class="data row10 col5" >18.43</td>
                        <td id="T_089c9_row10_col6" class="data row10 col6" >5.14</td>
                        <td id="T_089c9_row10_col7" class="data row10 col7" >53.15</td>
                        <td id="T_089c9_row10_col8" class="data row10 col8" >166.31</td>
                        <td id="T_089c9_row10_col9" class="data row10 col9" >33.70</td>
                        <td id="T_089c9_row10_col10" class="data row10 col10" >20.88</td>
                        <td id="T_089c9_row10_col11" class="data row10 col11" >440.86</td>
                        <td id="T_089c9_row10_col12" class="data row10 col12" >532.03</td>
                        <td id="T_089c9_row10_col13" class="data row10 col13" >China</td>
                        <td id="T_089c9_row10_col14" class="data row10 col14" >77.44</td>
                        <td id="T_089c9_row10_col15" class="data row10 col15" >nan</td>
            </tr>
            <tr>
                        <th id="T_089c9_level0_row11" class="row_heading level0 row11" >LI</th>
                        <td id="T_089c9_row11_col0" class="data row11 col0" >18.06</td>
                        <td id="T_089c9_row11_col1" class="data row11 col1" >1.31</td>
                        <td id="T_089c9_row11_col2" class="data row11 col2" >0.00</td>
                        <td id="T_089c9_row11_col3" class="data row11 col3" >35.47</td>
                        <td id="T_089c9_row11_col4" class="data row11 col4" >-429.57</td>
                        <td id="T_089c9_row11_col5" class="data row11 col5" >inf</td>
                        <td id="T_089c9_row11_col6" class="data row11 col6" >0.00</td>
                        <td id="T_089c9_row11_col7" class="data row11 col7" >-17.32</td>
                        <td id="T_089c9_row11_col8" class="data row11 col8" >108.13</td>
                        <td id="T_089c9_row11_col9" class="data row11 col9" >-85.61</td>
                        <td id="T_089c9_row11_col10" class="data row11 col10" >147.25</td>
                        <td id="T_089c9_row11_col11" class="data row11 col11" >-0.17</td>
                        <td id="T_089c9_row11_col12" class="data row11 col12" >-10.38</td>
                        <td id="T_089c9_row11_col13" class="data row11 col13" >China</td>
                        <td id="T_089c9_row11_col14" class="data row11 col14" >22.02</td>
                        <td id="T_089c9_row11_col15" class="data row11 col15" >nan</td>
            </tr>
            <tr>
                        <th id="T_089c9_level0_row12" class="row_heading level0 row12" >YY</th>
                        <td id="T_089c9_row12_col0" class="data row12 col0" >22.90</td>
                        <td id="T_089c9_row12_col1" class="data row12 col1" >7.09</td>
                        <td id="T_089c9_row12_col2" class="data row12 col2" >30.02</td>
                        <td id="T_089c9_row12_col3" class="data row12 col3" >16.55</td>
                        <td id="T_089c9_row12_col4" class="data row12 col4" >29.44</td>
                        <td id="T_089c9_row12_col5" class="data row12 col5" >16.64</td>
                        <td id="T_089c9_row12_col6" class="data row12 col6" >57.73</td>
                        <td id="T_089c9_row12_col7" class="data row12 col7" >85.34</td>
                        <td id="T_089c9_row12_col8" class="data row12 col8" >110.67</td>
                        <td id="T_089c9_row12_col9" class="data row12 col9" >3.79</td>
                        <td id="T_089c9_row12_col10" class="data row12 col10" >18.97</td>
                        <td id="T_089c9_row12_col11" class="data row12 col11" >51.88</td>
                        <td id="T_089c9_row12_col12" class="data row12 col12" >315.35</td>
                        <td id="T_089c9_row12_col13" class="data row12 col13" >China</td>
                        <td id="T_089c9_row12_col14" class="data row12 col14" >5.86</td>
                        <td id="T_089c9_row12_col15" class="data row12 col15" >nan</td>
            </tr>
            <tr>
                        <th id="T_089c9_level0_row13" class="row_heading level0 row13" >AMZN</th>
                        <td id="T_089c9_row13_col0" class="data row13 col0" >70.92</td>
                        <td id="T_089c9_row13_col1" class="data row13 col1" >6.30</td>
                        <td id="T_089c9_row13_col2" class="data row13 col2" >16.08</td>
                        <td id="T_089c9_row13_col3" class="data row13 col3" >18.90</td>
                        <td id="T_089c9_row13_col4" class="data row13 col4" >3.92</td>
                        <td id="T_089c9_row13_col5" class="data row13 col5" >29.67</td>
                        <td id="T_089c9_row13_col6" class="data row13 col6" >8.65</td>
                        <td id="T_089c9_row13_col7" class="data row13 col7" >110.41</td>
                        <td id="T_089c9_row13_col8" class="data row13 col8" >110.91</td>
                        <td id="T_089c9_row13_col9" class="data row13 col9" >71.58</td>
                        <td id="T_089c9_row13_col10" class="data row13 col10" >85.13</td>
                        <td id="T_089c9_row13_col11" class="data row13 col11" >1049.59</td>
                        <td id="T_089c9_row13_col12" class="data row13 col12" >1226.87</td>
                        <td id="T_089c9_row13_col13" class="data row13 col13" >United States</td>
                        <td id="T_089c9_row13_col14" class="data row13 col14" >1630.98</td>
                        <td id="T_089c9_row13_col15" class="data row13 col15" >-55.39</td>
            </tr>
            <tr>
                        <th id="T_089c9_level0_row14" class="row_heading level0 row14" >BILI</th>
                        <td id="T_089c9_row14_col0" class="data row14 col0" >67.39</td>
                        <td id="T_089c9_row14_col1" class="data row14 col1" >11.77</td>
                        <td id="T_089c9_row14_col2" class="data row14 col2" >17.05</td>
                        <td id="T_089c9_row14_col3" class="data row14 col3" >-9.33</td>
                        <td id="T_089c9_row14_col4" class="data row14 col4" >-20.55</td>
                        <td id="T_089c9_row14_col5" class="data row14 col5" >69.49</td>
                        <td id="T_089c9_row14_col6" class="data row14 col6" >6.72</td>
                        <td id="T_089c9_row14_col7" class="data row14 col7" >83.54</td>
                        <td id="T_089c9_row14_col8" class="data row14 col8" >66.70</td>
                        <td id="T_089c9_row14_col9" class="data row14 col9" >-110.94</td>
                        <td id="T_089c9_row14_col10" class="data row14 col10" >144.16</td>
                        <td id="T_089c9_row14_col11" class="data row14 col11" >-0.02</td>
                        <td id="T_089c9_row14_col12" class="data row14 col12" >-98.26</td>
                        <td id="T_089c9_row14_col13" class="data row14 col13" >China</td>
                        <td id="T_089c9_row14_col14" class="data row14 col14" >42.44</td>
                        <td id="T_089c9_row14_col15" class="data row14 col15" >nan</td>
            </tr>
            <tr>
                        <th id="T_089c9_level0_row15" class="row_heading level0 row15" >WB</th>
                        <td id="T_089c9_row15_col0" class="data row15 col0" >54.44</td>
                        <td id="T_089c9_row15_col1" class="data row15 col1" >73.45</td>
                        <td id="T_089c9_row15_col2" class="data row15 col2" >2.19</td>
                        <td id="T_089c9_row15_col3" class="data row15 col3" >23.78</td>
                        <td id="T_089c9_row15_col4" class="data row15 col4" >27.62</td>
                        <td id="T_089c9_row15_col5" class="data row15 col5" >15.96</td>
                        <td id="T_089c9_row15_col6" class="data row15 col6" >29.20</td>
                        <td id="T_089c9_row15_col7" class="data row15 col7" >4.01</td>
                        <td id="T_089c9_row15_col8" class="data row15 col8" >51.69</td>
                        <td id="T_089c9_row15_col9" class="data row15 col9" >12.40</td>
                        <td id="T_089c9_row15_col10" class="data row15 col10" >22.24</td>
                        <td id="T_089c9_row15_col11" class="data row15 col11" >10.10</td>
                        <td id="T_089c9_row15_col12" class="data row15 col12" >6.14</td>
                        <td id="T_089c9_row15_col13" class="data row15 col13" >China</td>
                        <td id="T_089c9_row15_col14" class="data row15 col14" >11.52</td>
                        <td id="T_089c9_row15_col15" class="data row15 col15" >nan</td>
            </tr>
            <tr>
                        <th id="T_089c9_level0_row16" class="row_heading level0 row16" >GOOG</th>
                        <td id="T_089c9_row16_col0" class="data row16 col0" >30.37</td>
                        <td id="T_089c9_row16_col1" class="data row16 col1" >17.19</td>
                        <td id="T_089c9_row16_col2" class="data row16 col2" >9.51</td>
                        <td id="T_089c9_row16_col3" class="data row16 col3" >15.19</td>
                        <td id="T_089c9_row16_col4" class="data row16 col4" >19.29</td>
                        <td id="T_089c9_row16_col5" class="data row16 col5" >18.16</td>
                        <td id="T_089c9_row16_col6" class="data row16 col6" >5.33</td>
                        <td id="T_089c9_row16_col7" class="data row16 col7" >57.24</td>
                        <td id="T_089c9_row16_col8" class="data row16 col8" >74.09</td>
                        <td id="T_089c9_row16_col9" class="data row16 col9" >23.16</td>
                        <td id="T_089c9_row16_col10" class="data row16 col10" >23.99</td>
                        <td id="T_089c9_row16_col11" class="data row16 col11" >686.42</td>
                        <td id="T_089c9_row16_col12" class="data row16 col12" >1350.49</td>
                        <td id="T_089c9_row16_col13" class="data row16 col13" >United States</td>
                        <td id="T_089c9_row16_col14" class="data row16 col14" >1622.65</td>
                        <td id="T_089c9_row16_col15" class="data row16 col15" >-136.39</td>
            </tr>
            <tr>
                        <th id="T_089c9_level0_row17" class="row_heading level0 row17" >MSFT</th>
                        <td id="T_089c9_row17_col0" class="data row17 col0" >60.74</td>
                        <td id="T_089c9_row17_col1" class="data row17 col1" >22.38</td>
                        <td id="T_089c9_row17_col2" class="data row17 col2" >36.64</td>
                        <td id="T_089c9_row17_col3" class="data row17 col3" >31.22</td>
                        <td id="T_089c9_row17_col4" class="data row17 col4" >25.89</td>
                        <td id="T_089c9_row17_col5" class="data row17 col5" >13.98</td>
                        <td id="T_089c9_row17_col6" class="data row17 col6" >0.32</td>
                        <td id="T_089c9_row17_col7" class="data row17 col7" >38.22</td>
                        <td id="T_089c9_row17_col8" class="data row17 col8" >88.66</td>
                        <td id="T_089c9_row17_col9" class="data row17 col9" >13.21</td>
                        <td id="T_089c9_row17_col10" class="data row17 col10" >9.03</td>
                        <td id="T_089c9_row17_col11" class="data row17 col11" >660.67</td>
                        <td id="T_089c9_row17_col12" class="data row17 col12" >992.65</td>
                        <td id="T_089c9_row17_col13" class="data row17 col13" >United States</td>
                        <td id="T_089c9_row17_col14" class="data row17 col14" >1862.56</td>
                        <td id="T_089c9_row17_col15" class="data row17 col15" >-181.92</td>
            </tr>
            <tr>
                        <th id="T_089c9_level0_row18" class="row_heading level0 row18" >TSM</th>
                        <td id="T_089c9_row18_col0" class="data row18 col0" >32.97</td>
                        <td id="T_089c9_row18_col1" class="data row18 col1" >10.91</td>
                        <td id="T_089c9_row18_col2" class="data row18 col2" >0.29</td>
                        <td id="T_089c9_row18_col3" class="data row18 col3" >23.33</td>
                        <td id="T_089c9_row18_col4" class="data row18 col4" >35.07</td>
                        <td id="T_089c9_row18_col5" class="data row18 col5" >11.48</td>
                        <td id="T_089c9_row18_col6" class="data row18 col6" >11.89</td>
                        <td id="T_089c9_row18_col7" class="data row18 col7" >16.70</td>
                        <td id="T_089c9_row18_col8" class="data row18 col8" >28.89</td>
                        <td id="T_089c9_row18_col9" class="data row18 col9" >21.73</td>
                        <td id="T_089c9_row18_col10" class="data row18 col10" >74.11</td>
                        <td id="T_089c9_row18_col11" class="data row18 col11" >5416.26</td>
                        <td id="T_089c9_row18_col12" class="data row18 col12" >7625.61</td>
                        <td id="T_089c9_row18_col13" class="data row18 col13" >Taiwan</td>
                        <td id="T_089c9_row18_col14" class="data row18 col14" >616.88</td>
                        <td id="T_089c9_row18_col15" class="data row18 col15" >nan</td>
            </tr>
            <tr>
                        <th id="T_089c9_level0_row19" class="row_heading level0 row19" >AMD</th>
                        <td id="T_089c9_row19_col0" class="data row19 col0" >34.87</td>
                        <td id="T_089c9_row19_col1" class="data row19 col1" >21.26</td>
                        <td id="T_089c9_row19_col2" class="data row19 col2" >4.95</td>
                        <td id="T_089c9_row19_col3" class="data row19 col3" >18.95</td>
                        <td id="T_089c9_row19_col4" class="data row19 col4" >8.79</td>
                        <td id="T_089c9_row19_col5" class="data row19 col5" >24.09</td>
                        <td id="T_089c9_row19_col6" class="data row19 col6" >20.56</td>
                        <td id="T_089c9_row19_col7" class="data row19 col7" >-163.27</td>
                        <td id="T_089c9_row19_col8" class="data row19 col8" >887.22</td>
                        <td id="T_089c9_row19_col9" class="data row19 col9" >-34.90</td>
                        <td id="T_089c9_row19_col10" class="data row19 col10" >253.60</td>
                        <td id="T_089c9_row19_col11" class="data row19 col11" >0.83</td>
                        <td id="T_089c9_row19_col12" class="data row19 col12" >-2.35</td>
                        <td id="T_089c9_row19_col13" class="data row19 col13" >United States</td>
                        <td id="T_089c9_row19_col14" class="data row19 col14" >99.60</td>
                        <td id="T_089c9_row19_col15" class="data row19 col15" >-11949.85</td>
            </tr>
            <tr>
                        <th id="T_089c9_level0_row20" class="row_heading level0 row20" >XPEV</th>
                        <td id="T_089c9_row20_col0" class="data row20 col0" >22.99</td>
                        <td id="T_089c9_row20_col1" class="data row20 col1" >22.00</td>
                        <td id="T_089c9_row20_col2" class="data row20 col2" >0.00</td>
                        <td id="T_089c9_row20_col3" class="data row20 col3" >36.71</td>
                        <td id="T_089c9_row20_col4" class="data row20 col4" >-4872.58</td>
                        <td id="T_089c9_row20_col5" class="data row20 col5" >11983.54</td>
                        <td id="T_089c9_row20_col6" class="data row20 col6" >16732.64</td>
                        <td id="T_089c9_row20_col7" class="data row20 col7" >68.96</td>
                        <td id="T_089c9_row20_col8" class="data row20 col8" >134.29</td>
                        <td id="T_089c9_row20_col9" class="data row20 col9" >25.86</td>
                        <td id="T_089c9_row20_col10" class="data row20 col10" >153.64</td>
                        <td id="T_089c9_row20_col11" class="data row20 col11" >-70.90</td>
                        <td id="T_089c9_row20_col12" class="data row20 col12" >-146.88</td>
                        <td id="T_089c9_row20_col13" class="data row20 col13" >China</td>
                        <td id="T_089c9_row20_col14" class="data row20 col14" >27.39</td>
                        <td id="T_089c9_row20_col15" class="data row20 col15" >nan</td>
            </tr>
            <tr>
                        <th id="T_089c9_level0_row21" class="row_heading level0 row21" >EDU</th>
                        <td id="T_089c9_row21_col0" class="data row21 col0" >56.23</td>
                        <td id="T_089c9_row21_col1" class="data row21 col1" >1.59</td>
                        <td id="T_089c9_row21_col2" class="data row21 col2" >2.94</td>
                        <td id="T_089c9_row21_col3" class="data row21 col3" >14.10</td>
                        <td id="T_089c9_row21_col4" class="data row21 col4" >11.65</td>
                        <td id="T_089c9_row21_col5" class="data row21 col5" >26.03</td>
                        <td id="T_089c9_row21_col6" class="data row21 col6" >10.23</td>
                        <td id="T_089c9_row21_col7" class="data row21 col7" >20.64</td>
                        <td id="T_089c9_row21_col8" class="data row21 col8" >47.90</td>
                        <td id="T_089c9_row21_col9" class="data row21 col9" >-1.15</td>
                        <td id="T_089c9_row21_col10" class="data row21 col10" >9.44</td>
                        <td id="T_089c9_row21_col11" class="data row21 col11" >6.51</td>
                        <td id="T_089c9_row21_col12" class="data row21 col12" >6.56</td>
                        <td id="T_089c9_row21_col13" class="data row21 col13" >China</td>
                        <td id="T_089c9_row21_col14" class="data row21 col14" >180.38</td>
                        <td id="T_089c9_row21_col15" class="data row21 col15" >nan</td>
            </tr>
            <tr>
                        <th id="T_089c9_level0_row22" class="row_heading level0 row22" >TAL</th>
                        <td id="T_089c9_row22_col0" class="data row22 col0" >57.03</td>
                        <td id="T_089c9_row22_col1" class="data row22 col1" >0.41</td>
                        <td id="T_089c9_row22_col2" class="data row22 col2" >8.74</td>
                        <td id="T_089c9_row22_col3" class="data row22 col3" >5.10</td>
                        <td id="T_089c9_row22_col4" class="data row22 col4" >4.99</td>
                        <td id="T_089c9_row22_col5" class="data row22 col5" >38.17</td>
                        <td id="T_089c9_row22_col6" class="data row22 col6" >10.89</td>
                        <td id="T_089c9_row22_col7" class="data row22 col7" >-13.23</td>
                        <td id="T_089c9_row22_col8" class="data row22 col8" >108.72</td>
                        <td id="T_089c9_row22_col9" class="data row22 col9" >340.43</td>
                        <td id="T_089c9_row22_col10" class="data row22 col10" >669.10</td>
                        <td id="T_089c9_row22_col11" class="data row22 col11" >406.50</td>
                        <td id="T_089c9_row22_col12" class="data row22 col12" >0.73</td>
                        <td id="T_089c9_row22_col13" class="data row22 col13" >China</td>
                        <td id="T_089c9_row22_col14" class="data row22 col14" >24.70</td>
                        <td id="T_089c9_row22_col15" class="data row22 col15" >nan</td>
            </tr>
            <tr>
                        <th id="T_089c9_level0_row23" class="row_heading level0 row23" >XNET</th>
                        <td id="T_089c9_row23_col0" class="data row23 col0" >30.13</td>
                        <td id="T_089c9_row23_col1" class="data row23 col1" >19.31</td>
                        <td id="T_089c9_row23_col2" class="data row23 col2" >7.74</td>
                        <td id="T_089c9_row23_col3" class="data row23 col3" >-10.96</td>
                        <td id="T_089c9_row23_col4" class="data row23 col4" >-18.19</td>
                        <td id="T_089c9_row23_col5" class="data row23 col5" >-1.18</td>
                        <td id="T_089c9_row23_col6" class="data row23 col6" >18.69</td>
                        <td id="T_089c9_row23_col7" class="data row23 col7" >-11.58</td>
                        <td id="T_089c9_row23_col8" class="data row23 col8" >56.28</td>
                        <td id="T_089c9_row23_col9" class="data row23 col9" >22.97</td>
                        <td id="T_089c9_row23_col10" class="data row23 col10" >67.75</td>
                        <td id="T_089c9_row23_col11" class="data row23 col11" >-0.85</td>
                        <td id="T_089c9_row23_col12" class="data row23 col12" >-0.33</td>
                        <td id="T_089c9_row23_col13" class="data row23 col13" >China</td>
                        <td id="T_089c9_row23_col14" class="data row23 col14" >0.34</td>
                        <td id="T_089c9_row23_col15" class="data row23 col15" >nan</td>
            </tr>
            <tr>
                        <th id="T_089c9_level0_row24" class="row_heading level0 row24" >GOOGL</th>
                        <td id="T_089c9_row24_col0" class="data row24 col0" >30.37</td>
                        <td id="T_089c9_row24_col1" class="data row24 col1" >17.19</td>
                        <td id="T_089c9_row24_col2" class="data row24 col2" >9.51</td>
                        <td id="T_089c9_row24_col3" class="data row24 col3" >15.19</td>
                        <td id="T_089c9_row24_col4" class="data row24 col4" >19.29</td>
                        <td id="T_089c9_row24_col5" class="data row24 col5" >18.16</td>
                        <td id="T_089c9_row24_col6" class="data row24 col6" >5.33</td>
                        <td id="T_089c9_row24_col7" class="data row24 col7" >57.24</td>
                        <td id="T_089c9_row24_col8" class="data row24 col8" >74.09</td>
                        <td id="T_089c9_row24_col9" class="data row24 col9" >23.16</td>
                        <td id="T_089c9_row24_col10" class="data row24 col10" >23.99</td>
                        <td id="T_089c9_row24_col11" class="data row24 col11" >686.42</td>
                        <td id="T_089c9_row24_col12" class="data row24 col12" >1350.49</td>
                        <td id="T_089c9_row24_col13" class="data row24 col13" >United States</td>
                        <td id="T_089c9_row24_col14" class="data row24 col14" >1588.68</td>
                        <td id="T_089c9_row24_col15" class="data row24 col15" >-131.44</td>
            </tr>
            <tr>
                        <th id="T_089c9_level0_row25" class="row_heading level0 row25" >MOMO</th>
                        <td id="T_089c9_row25_col0" class="data row25 col0" >36.11</td>
                        <td id="T_089c9_row25_col1" class="data row25 col1" >2.13</td>
                        <td id="T_089c9_row25_col2" class="data row25 col2" >27.93</td>
                        <td id="T_089c9_row25_col3" class="data row25 col3" >23.50</td>
                        <td id="T_089c9_row25_col4" class="data row25 col4" >19.16</td>
                        <td id="T_089c9_row25_col5" class="data row25 col5" >22.03</td>
                        <td id="T_089c9_row25_col6" class="data row25 col6" >31.58</td>
                        <td id="T_089c9_row25_col7" class="data row25 col7" >2.46</td>
                        <td id="T_089c9_row25_col8" class="data row25 col8" >30.25</td>
                        <td id="T_089c9_row25_col9" class="data row25 col9" >14.14</td>
                        <td id="T_089c9_row25_col10" class="data row25 col10" >57.21</td>
                        <td id="T_089c9_row25_col11" class="data row25 col11" >64.19</td>
                        <td id="T_089c9_row25_col12" class="data row25 col12" >34.11</td>
                        <td id="T_089c9_row25_col13" class="data row25 col13" >China</td>
                        <td id="T_089c9_row25_col14" class="data row25 col14" >2.95</td>
                        <td id="T_089c9_row25_col15" class="data row25 col15" >nan</td>
            </tr>
            <tr>
                        <th id="T_089c9_level0_row26" class="row_heading level0 row26" >NFLX</th>
                        <td id="T_089c9_row26_col0" class="data row26 col0" >71.83</td>
                        <td id="T_089c9_row26_col1" class="data row26 col1" >5.41</td>
                        <td id="T_089c9_row26_col2" class="data row26 col2" >0.00</td>
                        <td id="T_089c9_row26_col3" class="data row26 col3" >22.08</td>
                        <td id="T_089c9_row26_col4" class="data row26 col4" >8.19</td>
                        <td id="T_089c9_row26_col5" class="data row26 col5" >28.90</td>
                        <td id="T_089c9_row26_col6" class="data row26 col6" >5.64</td>
                        <td id="T_089c9_row26_col7" class="data row26 col7" >72.92</td>
                        <td id="T_089c9_row26_col8" class="data row26 col8" >38.05</td>
                        <td id="T_089c9_row26_col9" class="data row26 col9" >-35.24</td>
                        <td id="T_089c9_row26_col10" class="data row26 col10" >110.73</td>
                        <td id="T_089c9_row26_col11" class="data row26 col11" >-5.97</td>
                        <td id="T_089c9_row26_col12" class="data row26 col12" >96.35</td>
                        <td id="T_089c9_row26_col13" class="data row26 col13" >United States</td>
                        <td id="T_089c9_row26_col14" class="data row26 col14" >221.36</td>
                        <td id="T_089c9_row26_col15" class="data row26 col15" >nan</td>
            </tr>
            <tr>
                        <th id="T_089c9_level0_row27" class="row_heading level0 row27" >DIS</th>
                        <td id="T_089c9_row27_col0" class="data row27 col0" >51.62</td>
                        <td id="T_089c9_row27_col1" class="data row27 col1" >19.43</td>
                        <td id="T_089c9_row27_col2" class="data row27 col2" >92.95</td>
                        <td id="T_089c9_row27_col3" class="data row27 col3" >14.14</td>
                        <td id="T_089c9_row27_col4" class="data row27 col4" >12.25</td>
                        <td id="T_089c9_row27_col5" class="data row27 col5" >6.28</td>
                        <td id="T_089c9_row27_col6" class="data row27 col6" >11.66</td>
                        <td id="T_089c9_row27_col7" class="data row27 col7" >-32.63</td>
                        <td id="T_089c9_row27_col8" class="data row27 col8" >84.95</td>
                        <td id="T_089c9_row27_col9" class="data row27 col9" >12.73</td>
                        <td id="T_089c9_row27_col10" class="data row27 col10" >95.13</td>
                        <td id="T_089c9_row27_col11" class="data row27 col11" >105.93</td>
                        <td id="T_089c9_row27_col12" class="data row27 col12" >32.68</td>
                        <td id="T_089c9_row27_col13" class="data row27 col13" >United States</td>
                        <td id="T_089c9_row27_col14" class="data row27 col14" >321.60</td>
                        <td id="T_089c9_row27_col15" class="data row27 col15" >-203.58</td>
            </tr>
            <tr>
                        <th id="T_089c9_level0_row28" class="row_heading level0 row28" >KO</th>
                        <td id="T_089c9_row28_col0" class="data row28 col0" >75.62</td>
                        <td id="T_089c9_row28_col1" class="data row28 col1" >9.52</td>
                        <td id="T_089c9_row28_col2" class="data row28 col2" >90.71</td>
                        <td id="T_089c9_row28_col3" class="data row28 col3" >33.08</td>
                        <td id="T_089c9_row28_col4" class="data row28 col4" >17.40</td>
                        <td id="T_089c9_row28_col5" class="data row28 col5" >-2.68</td>
                        <td id="T_089c9_row28_col6" class="data row28 col6" >10.28</td>
                        <td id="T_089c9_row28_col7" class="data row28 col7" >147.01</td>
                        <td id="T_089c9_row28_col8" class="data row28 col8" >233.99</td>
                        <td id="T_089c9_row28_col9" class="data row28 col9" >18.77</td>
                        <td id="T_089c9_row28_col10" class="data row28 col10" >18.06</td>
                        <td id="T_089c9_row28_col11" class="data row28 col11" >146.23</td>
                        <td id="T_089c9_row28_col12" class="data row28 col12" >1038.43</td>
                        <td id="T_089c9_row28_col13" class="data row28 col13" >United States</td>
                        <td id="T_089c9_row28_col14" class="data row28 col14" >239.27</td>
                        <td id="T_089c9_row28_col15" class="data row28 col15" >-63.62</td>
            </tr>
            <tr>
                        <th id="T_089c9_level0_row29" class="row_heading level0 row29" >GILD</th>
                        <td id="T_089c9_row29_col0" class="data row29 col0" >73.36</td>
                        <td id="T_089c9_row29_col1" class="data row29 col1" >19.85</td>
                        <td id="T_089c9_row29_col2" class="data row29 col2" >44.54</td>
                        <td id="T_089c9_row29_col3" class="data row29 col3" >18.18</td>
                        <td id="T_089c9_row29_col4" class="data row29 col4" >16.72</td>
                        <td id="T_089c9_row29_col5" class="data row29 col5" >-1.27</td>
                        <td id="T_089c9_row29_col6" class="data row29 col6" >12.83</td>
                        <td id="T_089c9_row29_col7" class="data row29 col7" >-27.04</td>
                        <td id="T_089c9_row29_col8" class="data row29 col8" >61.95</td>
                        <td id="T_089c9_row29_col9" class="data row29 col9" >-10.75</td>
                        <td id="T_089c9_row29_col10" class="data row29 col10" >22.60</td>
                        <td id="T_089c9_row29_col11" class="data row29 col11" >80.45</td>
                        <td id="T_089c9_row29_col12" class="data row29 col12" >21.09</td>
                        <td id="T_089c9_row29_col13" class="data row29 col13" >United States</td>
                        <td id="T_089c9_row29_col14" class="data row29 col14" >82.81</td>
                        <td id="T_089c9_row29_col15" class="data row29 col15" >-2.94</td>
            </tr>
            <tr>
                        <th id="T_089c9_level0_row30" class="row_heading level0 row30" >TWTR</th>
                        <td id="T_089c9_row30_col0" class="data row30 col0" >40.43</td>
                        <td id="T_089c9_row30_col1" class="data row30 col1" >28.03</td>
                        <td id="T_089c9_row30_col2" class="data row30 col2" >16.47</td>
                        <td id="T_089c9_row30_col3" class="data row30 col3" >4.54</td>
                        <td id="T_089c9_row30_col4" class="data row30 col4" >11.75</td>
                        <td id="T_089c9_row30_col5" class="data row30 col5" >15.22</td>
                        <td id="T_089c9_row30_col6" class="data row30 col6" >8.64</td>
                        <td id="T_089c9_row30_col7" class="data row30 col7" >-457.18</td>
                        <td id="T_089c9_row30_col8" class="data row30 col8" >664.34</td>
                        <td id="T_089c9_row30_col9" class="data row30 col9" >-22.52</td>
                        <td id="T_089c9_row30_col10" class="data row30 col10" >56.89</td>
                        <td id="T_089c9_row30_col11" class="data row30 col11" >3.82</td>
                        <td id="T_089c9_row30_col12" class="data row30 col12" >-172.38</td>
                        <td id="T_089c9_row30_col13" class="data row30 col13" >nan</td>
                        <td id="T_089c9_row30_col14" class="data row30 col14" >45.62</td>
                        <td id="T_089c9_row30_col15" class="data row30 col15" >nan</td>
            </tr>
            <tr>
                        <th id="T_089c9_level0_row31" class="row_heading level0 row31" >PFE</th>
                        <td id="T_089c9_row31_col0" class="data row31 col0" >58.84</td>
                        <td id="T_089c9_row31_col1" class="data row31 col1" >26.71</td>
                        <td id="T_089c9_row31_col2" class="data row31 col2" >78.40</td>
                        <td id="T_089c9_row31_col3" class="data row31 col3" >22.12</td>
                        <td id="T_089c9_row31_col4" class="data row31 col4" >32.59</td>
                        <td id="T_089c9_row31_col5" class="data row31 col5" >-6.56</td>
                        <td id="T_089c9_row31_col6" class="data row31 col6" >13.65</td>
                        <td id="T_089c9_row31_col7" class="data row31 col7" >-14.22</td>
                        <td id="T_089c9_row31_col8" class="data row31 col8" >52.18</td>
                        <td id="T_089c9_row31_col9" class="data row31 col9" >-5.08</td>
                        <td id="T_089c9_row31_col10" class="data row31 col10" >19.84</td>
                        <td id="T_089c9_row31_col11" class="data row31 col11" >141.26</td>
                        <td id="T_089c9_row31_col12" class="data row31 col12" >121.71</td>
                        <td id="T_089c9_row31_col13" class="data row31 col13" >United States</td>
                        <td id="T_089c9_row31_col14" class="data row31 col14" >217.13</td>
                        <td id="T_089c9_row31_col15" class="data row31 col15" >-53.71</td>
            </tr>
            <tr>
                        <th id="T_089c9_level0_row32" class="row_heading level0 row32" >WFC</th>
                        <td id="T_089c9_row32_col0" class="data row32 col0" >90.49</td>
                        <td id="T_089c9_row32_col1" class="data row32 col1" >65.36</td>
                        <td id="T_089c9_row32_col2" class="data row32 col2" >16.03</td>
                        <td id="T_089c9_row32_col3" class="data row32 col3" >9.67</td>
                        <td id="T_089c9_row32_col4" class="data row32 col4" >20.40</td>
                        <td id="T_089c9_row32_col5" class="data row32 col5" >-11.14</td>
                        <td id="T_089c9_row32_col6" class="data row32 col6" >15.71</td>
                        <td id="T_089c9_row32_col7" class="data row32 col7" >-31.62</td>
                        <td id="T_089c9_row32_col8" class="data row32 col8" >45.11</td>
                        <td id="T_089c9_row32_col9" class="data row32 col9" >0.00</td>
                        <td id="T_089c9_row32_col10" class="data row32 col10" >0.00</td>
                        <td id="T_089c9_row32_col11" class="data row32 col11" >0.00</td>
                        <td id="T_089c9_row32_col12" class="data row32 col12" >76.92</td>
                        <td id="T_089c9_row32_col13" class="data row32 col13" >United States</td>
                        <td id="T_089c9_row32_col14" class="data row32 col14" >193.49</td>
                        <td id="T_089c9_row32_col15" class="data row32 col15" >nan</td>
            </tr>
            <tr>
                        <th id="T_089c9_level0_row33" class="row_heading level0 row33" >FUTU</th>
                        <td id="T_089c9_row33_col0" class="data row33 col0" >88.35</td>
                        <td id="T_089c9_row33_col1" class="data row33 col1" >860.68</td>
                        <td id="T_089c9_row33_col2" class="data row33 col2" >0.00</td>
                        <td id="T_089c9_row33_col3" class="data row33 col3" >-16.57</td>
                        <td id="T_089c9_row33_col4" class="data row33 col4" >19.01</td>
                        <td id="T_089c9_row33_col5" class="data row33 col5" >134.20</td>
                        <td id="T_089c9_row33_col6" class="data row33 col6" >93.31</td>
                        <td id="T_089c9_row33_col7" class="data row33 col7" >-363.29</td>
                        <td id="T_089c9_row33_col8" class="data row33 col8" >1297.94</td>
                        <td id="T_089c9_row33_col9" class="data row33 col9" >361.72</td>
                        <td id="T_089c9_row33_col10" class="data row33 col10" >563.98</td>
                        <td id="T_089c9_row33_col11" class="data row33 col11" >7751.21</td>
                        <td id="T_089c9_row33_col12" class="data row33 col12" >-78.23</td>
                        <td id="T_089c9_row33_col13" class="data row33 col13" >Hong Kong</td>
                        <td id="T_089c9_row33_col14" class="data row33 col14" >21.17</td>
                        <td id="T_089c9_row33_col15" class="data row33 col15" >nan</td>
            </tr>
            <tr>
                        <th id="T_089c9_level0_row34" class="row_heading level0 row34" >TIGR</th>
                        <td id="T_089c9_row34_col0" class="data row34 col0" >89.25</td>
                        <td id="T_089c9_row34_col1" class="data row34 col1" >918.74</td>
                        <td id="T_089c9_row34_col2" class="data row34 col2" >1.03</td>
                        <td id="T_089c9_row34_col3" class="data row34 col3" >38.57</td>
                        <td id="T_089c9_row34_col4" class="data row34 col4" >-43.16</td>
                        <td id="T_089c9_row34_col5" class="data row34 col5" >98.63</td>
                        <td id="T_089c9_row34_col6" class="data row34 col6" >36.38</td>
                        <td id="T_089c9_row34_col7" class="data row34 col7" >15.60</td>
                        <td id="T_089c9_row34_col8" class="data row34 col8" >418.68</td>
                        <td id="T_089c9_row34_col9" class="data row34 col9" >-295.56</td>
                        <td id="T_089c9_row34_col10" class="data row34 col10" >747.71</td>
                        <td id="T_089c9_row34_col11" class="data row34 col11" >-14.71</td>
                        <td id="T_089c9_row34_col12" class="data row34 col12" >-0.20</td>
                        <td id="T_089c9_row34_col13" class="data row34 col13" >China</td>
                        <td id="T_089c9_row34_col14" class="data row34 col14" >3.30</td>
                        <td id="T_089c9_row34_col15" class="data row34 col15" >nan</td>
            </tr>
            <tr>
                        <th id="T_089c9_level0_row35" class="row_heading level0 row35" >NIU</th>
                        <td id="T_089c9_row35_col0" class="data row35 col0" >46.21</td>
                        <td id="T_089c9_row35_col1" class="data row35 col1" >4.24</td>
                        <td id="T_089c9_row35_col2" class="data row35 col2" >0.00</td>
                        <td id="T_089c9_row35_col3" class="data row35 col3" >9.14</td>
                        <td id="T_089c9_row35_col4" class="data row35 col4" >-7.89</td>
                        <td id="T_089c9_row35_col5" class="data row35 col5" >50.10</td>
                        <td id="T_089c9_row35_col6" class="data row35 col6" >38.09</td>
                        <td id="T_089c9_row35_col7" class="data row35 col7" >-25.58</td>
                        <td id="T_089c9_row35_col8" class="data row35 col8" >122.36</td>
                        <td id="T_089c9_row35_col9" class="data row35 col9" >-22.35</td>
                        <td id="T_089c9_row35_col10" class="data row35 col10" >424.63</td>
                        <td id="T_089c9_row35_col11" class="data row35 col11" >0.72</td>
                        <td id="T_089c9_row35_col12" class="data row35 col12" >-0.25</td>
                        <td id="T_089c9_row35_col13" class="data row35 col13" >China</td>
                        <td id="T_089c9_row35_col14" class="data row35 col14" >2.62</td>
                        <td id="T_089c9_row35_col15" class="data row35 col15" >nan</td>
            </tr>
    </tbody></table>



## 港股

### 指标选股




<style  type="text/css" >
#T_43e8e_row0_col0,#T_43e8e_row0_col1,#T_43e8e_row0_col2,#T_43e8e_row0_col3,#T_43e8e_row0_col4,#T_43e8e_row0_col5,#T_43e8e_row0_col6,#T_43e8e_row0_col7,#T_43e8e_row0_col8,#T_43e8e_row0_col9,#T_43e8e_row0_col10,#T_43e8e_row0_col11,#T_43e8e_row0_col13,#T_43e8e_row1_col0,#T_43e8e_row1_col1,#T_43e8e_row1_col2,#T_43e8e_row1_col3,#T_43e8e_row1_col4,#T_43e8e_row1_col5,#T_43e8e_row1_col6,#T_43e8e_row1_col7,#T_43e8e_row1_col8,#T_43e8e_row1_col9,#T_43e8e_row1_col10,#T_43e8e_row1_col11,#T_43e8e_row1_col12,#T_43e8e_row1_col13,#T_43e8e_row2_col0,#T_43e8e_row2_col1,#T_43e8e_row2_col2,#T_43e8e_row2_col3,#T_43e8e_row2_col4,#T_43e8e_row2_col5,#T_43e8e_row2_col6,#T_43e8e_row2_col7,#T_43e8e_row2_col8,#T_43e8e_row2_col9,#T_43e8e_row2_col10,#T_43e8e_row2_col11,#T_43e8e_row2_col12,#T_43e8e_row2_col13,#T_43e8e_row3_col0,#T_43e8e_row3_col1,#T_43e8e_row3_col2,#T_43e8e_row3_col3,#T_43e8e_row3_col4,#T_43e8e_row3_col5,#T_43e8e_row3_col6,#T_43e8e_row3_col7,#T_43e8e_row3_col8,#T_43e8e_row3_col9,#T_43e8e_row3_col10,#T_43e8e_row3_col11,#T_43e8e_row3_col12,#T_43e8e_row3_col13,#T_43e8e_row4_col0,#T_43e8e_row4_col1,#T_43e8e_row4_col2,#T_43e8e_row4_col3,#T_43e8e_row4_col4,#T_43e8e_row4_col5,#T_43e8e_row4_col6,#T_43e8e_row4_col7,#T_43e8e_row4_col8,#T_43e8e_row4_col9,#T_43e8e_row4_col10,#T_43e8e_row4_col11,#T_43e8e_row4_col12,#T_43e8e_row4_col13,#T_43e8e_row5_col0,#T_43e8e_row5_col1,#T_43e8e_row5_col2,#T_43e8e_row5_col3,#T_43e8e_row5_col4,#T_43e8e_row5_col5,#T_43e8e_row5_col6,#T_43e8e_row5_col7,#T_43e8e_row5_col8,#T_43e8e_row5_col9,#T_43e8e_row5_col10,#T_43e8e_row5_col11,#T_43e8e_row5_col12,#T_43e8e_row5_col13,#T_43e8e_row6_col0,#T_43e8e_row6_col1,#T_43e8e_row6_col2,#T_43e8e_row6_col3,#T_43e8e_row6_col4,#T_43e8e_row6_col5,#T_43e8e_row6_col6,#T_43e8e_row6_col7,#T_43e8e_row6_col8,#T_43e8e_row6_col9,#T_43e8e_row6_col10,#T_43e8e_row6_col11,#T_43e8e_row6_col12,#T_43e8e_row6_col13,#T_43e8e_row7_col0,#T_43e8e_row7_col1,#T_43e8e_row7_col2,#T_43e8e_row7_col3,#T_43e8e_row7_col4,#T_43e8e_row7_col5,#T_43e8e_row7_col6,#T_43e8e_row7_col7,#T_43e8e_row7_col8,#T_43e8e_row7_col9,#T_43e8e_row7_col10,#T_43e8e_row7_col11,#T_43e8e_row7_col12,#T_43e8e_row7_col13,#T_43e8e_row8_col0,#T_43e8e_row8_col1,#T_43e8e_row8_col2,#T_43e8e_row8_col3,#T_43e8e_row8_col4,#T_43e8e_row8_col5,#T_43e8e_row8_col6,#T_43e8e_row8_col7,#T_43e8e_row8_col8,#T_43e8e_row8_col9,#T_43e8e_row8_col10,#T_43e8e_row8_col11,#T_43e8e_row8_col12,#T_43e8e_row8_col13,#T_43e8e_row9_col0,#T_43e8e_row9_col1,#T_43e8e_row9_col2,#T_43e8e_row9_col3,#T_43e8e_row9_col4,#T_43e8e_row9_col5,#T_43e8e_row9_col6,#T_43e8e_row9_col7,#T_43e8e_row9_col8,#T_43e8e_row9_col9,#T_43e8e_row9_col10,#T_43e8e_row9_col11,#T_43e8e_row9_col12,#T_43e8e_row9_col13,#T_43e8e_row10_col0,#T_43e8e_row10_col1,#T_43e8e_row10_col2,#T_43e8e_row10_col3,#T_43e8e_row10_col4,#T_43e8e_row10_col5,#T_43e8e_row10_col6,#T_43e8e_row10_col7,#T_43e8e_row10_col8,#T_43e8e_row10_col9,#T_43e8e_row10_col10,#T_43e8e_row10_col11,#T_43e8e_row10_col12,#T_43e8e_row10_col13,#T_43e8e_row11_col0,#T_43e8e_row11_col1,#T_43e8e_row11_col2,#T_43e8e_row11_col3,#T_43e8e_row11_col4,#T_43e8e_row11_col5,#T_43e8e_row11_col6,#T_43e8e_row11_col7,#T_43e8e_row11_col8,#T_43e8e_row11_col9,#T_43e8e_row11_col10,#T_43e8e_row11_col11,#T_43e8e_row11_col13,#T_43e8e_row12_col0,#T_43e8e_row12_col1,#T_43e8e_row12_col2,#T_43e8e_row12_col3,#T_43e8e_row12_col4,#T_43e8e_row12_col5,#T_43e8e_row12_col6,#T_43e8e_row12_col7,#T_43e8e_row12_col8,#T_43e8e_row12_col9,#T_43e8e_row12_col10,#T_43e8e_row12_col11,#T_43e8e_row12_col12,#T_43e8e_row12_col13,#T_43e8e_row13_col0,#T_43e8e_row13_col1,#T_43e8e_row13_col2,#T_43e8e_row13_col3,#T_43e8e_row13_col4,#T_43e8e_row13_col5,#T_43e8e_row13_col6,#T_43e8e_row13_col7,#T_43e8e_row13_col8,#T_43e8e_row13_col9,#T_43e8e_row13_col10,#T_43e8e_row13_col11,#T_43e8e_row13_col12,#T_43e8e_row13_col13,#T_43e8e_row14_col0,#T_43e8e_row14_col1,#T_43e8e_row14_col2,#T_43e8e_row14_col3,#T_43e8e_row14_col4,#T_43e8e_row14_col5,#T_43e8e_row14_col6,#T_43e8e_row14_col7,#T_43e8e_row14_col8,#T_43e8e_row14_col9,#T_43e8e_row14_col10,#T_43e8e_row14_col11,#T_43e8e_row14_col12,#T_43e8e_row14_col13,#T_43e8e_row15_col0,#T_43e8e_row15_col1,#T_43e8e_row15_col2,#T_43e8e_row15_col3,#T_43e8e_row15_col4,#T_43e8e_row15_col5,#T_43e8e_row15_col6,#T_43e8e_row15_col7,#T_43e8e_row15_col8,#T_43e8e_row15_col9,#T_43e8e_row15_col10,#T_43e8e_row15_col11,#T_43e8e_row15_col12,#T_43e8e_row15_col13,#T_43e8e_row16_col0,#T_43e8e_row16_col1,#T_43e8e_row16_col2,#T_43e8e_row16_col3,#T_43e8e_row16_col4,#T_43e8e_row16_col5,#T_43e8e_row16_col6,#T_43e8e_row16_col7,#T_43e8e_row16_col8,#T_43e8e_row16_col9,#T_43e8e_row16_col10,#T_43e8e_row16_col11,#T_43e8e_row16_col12,#T_43e8e_row16_col13,#T_43e8e_row17_col0,#T_43e8e_row17_col1,#T_43e8e_row17_col2,#T_43e8e_row17_col3,#T_43e8e_row17_col4,#T_43e8e_row17_col5,#T_43e8e_row17_col6,#T_43e8e_row17_col7,#T_43e8e_row17_col8,#T_43e8e_row17_col9,#T_43e8e_row17_col10,#T_43e8e_row17_col11,#T_43e8e_row17_col12,#T_43e8e_row17_col13,#T_43e8e_row18_col0,#T_43e8e_row18_col1,#T_43e8e_row18_col2,#T_43e8e_row18_col3,#T_43e8e_row18_col4,#T_43e8e_row18_col5,#T_43e8e_row18_col6,#T_43e8e_row18_col7,#T_43e8e_row18_col8,#T_43e8e_row18_col9,#T_43e8e_row18_col10,#T_43e8e_row18_col11,#T_43e8e_row18_col12,#T_43e8e_row18_col13,#T_43e8e_row19_col0,#T_43e8e_row19_col1,#T_43e8e_row19_col2,#T_43e8e_row19_col3,#T_43e8e_row19_col4,#T_43e8e_row19_col5,#T_43e8e_row19_col6,#T_43e8e_row19_col7,#T_43e8e_row19_col8,#T_43e8e_row19_col9,#T_43e8e_row19_col10,#T_43e8e_row19_col11,#T_43e8e_row19_col12,#T_43e8e_row19_col13,#T_43e8e_row20_col0,#T_43e8e_row20_col1,#T_43e8e_row20_col2,#T_43e8e_row20_col3,#T_43e8e_row20_col4,#T_43e8e_row20_col5,#T_43e8e_row20_col6,#T_43e8e_row20_col7,#T_43e8e_row20_col8,#T_43e8e_row20_col9,#T_43e8e_row20_col10,#T_43e8e_row20_col11,#T_43e8e_row20_col12,#T_43e8e_row20_col13,#T_43e8e_row21_col0,#T_43e8e_row21_col1,#T_43e8e_row21_col2,#T_43e8e_row21_col3,#T_43e8e_row21_col4,#T_43e8e_row21_col5,#T_43e8e_row21_col6,#T_43e8e_row21_col7,#T_43e8e_row21_col8,#T_43e8e_row21_col9,#T_43e8e_row21_col10,#T_43e8e_row21_col11,#T_43e8e_row21_col12,#T_43e8e_row21_col13,#T_43e8e_row22_col0,#T_43e8e_row22_col1,#T_43e8e_row22_col2,#T_43e8e_row22_col3,#T_43e8e_row22_col4,#T_43e8e_row22_col5,#T_43e8e_row22_col6,#T_43e8e_row22_col7,#T_43e8e_row22_col8,#T_43e8e_row22_col9,#T_43e8e_row22_col10,#T_43e8e_row22_col11,#T_43e8e_row22_col12,#T_43e8e_row22_col13,#T_43e8e_row23_col0,#T_43e8e_row23_col1,#T_43e8e_row23_col2,#T_43e8e_row23_col3,#T_43e8e_row23_col4,#T_43e8e_row23_col5,#T_43e8e_row23_col6,#T_43e8e_row23_col7,#T_43e8e_row23_col8,#T_43e8e_row23_col9,#T_43e8e_row23_col10,#T_43e8e_row23_col11,#T_43e8e_row23_col12,#T_43e8e_row23_col13,#T_43e8e_row24_col0,#T_43e8e_row24_col1,#T_43e8e_row24_col2,#T_43e8e_row24_col3,#T_43e8e_row24_col4,#T_43e8e_row24_col5,#T_43e8e_row24_col6,#T_43e8e_row24_col7,#T_43e8e_row24_col8,#T_43e8e_row24_col9,#T_43e8e_row24_col10,#T_43e8e_row24_col11,#T_43e8e_row24_col12,#T_43e8e_row24_col13,#T_43e8e_row25_col0,#T_43e8e_row25_col1,#T_43e8e_row25_col2,#T_43e8e_row25_col3,#T_43e8e_row25_col4,#T_43e8e_row25_col5,#T_43e8e_row25_col6,#T_43e8e_row25_col7,#T_43e8e_row25_col8,#T_43e8e_row25_col9,#T_43e8e_row25_col10,#T_43e8e_row25_col11,#T_43e8e_row25_col12,#T_43e8e_row25_col13,#T_43e8e_row26_col0,#T_43e8e_row26_col1,#T_43e8e_row26_col2,#T_43e8e_row26_col3,#T_43e8e_row26_col4,#T_43e8e_row26_col5,#T_43e8e_row26_col6,#T_43e8e_row26_col7,#T_43e8e_row26_col8,#T_43e8e_row26_col9,#T_43e8e_row26_col10,#T_43e8e_row26_col11,#T_43e8e_row26_col12,#T_43e8e_row26_col13{
            color:  black;
        }#T_43e8e_row0_col12,#T_43e8e_row11_col12{
            color:  red;
        }</style><table id="T_43e8e_" ><thead>    <tr>        <th class="blank level0" ></th>        <th class="col_heading level0 col0" >名称</th>        <th class="col_heading level0 col1" >负债率</th>        <th class="col_heading level0 col2" >应收比</th>        <th class="col_heading level0 col3" >商誉比</th>        <th class="col_heading level0 col4" >ROE</th>        <th class="col_heading level0 col5" >利润率</th>        <th class="col_heading level0 col6" >收入增长</th>        <th class="col_heading level0 col7" >收入波动</th>        <th class="col_heading level0 col8" >盈利增长</th>        <th class="col_heading level0 col9" >盈利波动</th>        <th class="col_heading level0 col10" >FCF增长</th>        <th class="col_heading level0 col11" >FCF波动</th>        <th class="col_heading level0 col12" >DCF</th>        <th class="col_heading level0 col13" >盈利折现</th>    </tr>    <tr>        <th class="index_name level0" >Symbol</th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>    </tr></thead><tbody>
                <tr>
                        <th id="T_43e8e_level0_row0" class="row_heading level0 row0" >0586.HK</th>
                        <td id="T_43e8e_row0_col0" class="data row0 col0" >海螺创业</td>
                        <td id="T_43e8e_row0_col1" class="data row0 col1" >26.41</td>
                        <td id="T_43e8e_row0_col2" class="data row0 col2" >29.06</td>
                        <td id="T_43e8e_row0_col3" class="data row0 col3" >0.00</td>
                        <td id="T_43e8e_row0_col4" class="data row0 col4" >20.34</td>
                        <td id="T_43e8e_row0_col5" class="data row0 col5" >155.65</td>
                        <td id="T_43e8e_row0_col6" class="data row0 col6" >48.71</td>
                        <td id="T_43e8e_row0_col7" class="data row0 col7" >25.27</td>
                        <td id="T_43e8e_row0_col8" class="data row0 col8" >33.76</td>
                        <td id="T_43e8e_row0_col9" class="data row0 col9" >35.78</td>
                        <td id="T_43e8e_row0_col10" class="data row0 col10" >111.47</td>
                        <td id="T_43e8e_row0_col11" class="data row0 col11" >116.73</td>
                        <td id="T_43e8e_row0_col12" class="data row0 col12" >-189.88</td>
                        <td id="T_43e8e_row0_col13" class="data row0 col13" >172.51</td>
            </tr>
            <tr>
                        <th id="T_43e8e_level0_row1" class="row_heading level0 row1" >0700.HK</th>
                        <td id="T_43e8e_row1_col0" class="data row1 col0" >腾讯控股</td>
                        <td id="T_43e8e_row1_col1" class="data row1 col1" >41.65</td>
                        <td id="T_43e8e_row1_col2" class="data row1 col2" >10.98</td>
                        <td id="T_43e8e_row1_col3" class="data row1 col3" >15.43</td>
                        <td id="T_43e8e_row1_col4" class="data row1 col4" >24.13</td>
                        <td id="T_43e8e_row1_col5" class="data row1 col5" >28.29</td>
                        <td id="T_43e8e_row1_col6" class="data row1 col6" >26.65</td>
                        <td id="T_43e8e_row1_col7" class="data row1 col7" >5.52</td>
                        <td id="T_43e8e_row1_col8" class="data row1 col8" >33.31</td>
                        <td id="T_43e8e_row1_col9" class="data row1 col9" >33.18</td>
                        <td id="T_43e8e_row1_col10" class="data row1 col10" >20.72</td>
                        <td id="T_43e8e_row1_col11" class="data row1 col11" >21.25</td>
                        <td id="T_43e8e_row1_col12" class="data row1 col12" >2534.70</td>
                        <td id="T_43e8e_row1_col13" class="data row1 col13" >2875.86</td>
            </tr>
            <tr>
                        <th id="T_43e8e_level0_row2" class="row_heading level0 row2" >0799.HK</th>
                        <td id="T_43e8e_row2_col0" class="data row2 col0" >IGG</td>
                        <td id="T_43e8e_row2_col1" class="data row2 col1" >20.96</td>
                        <td id="T_43e8e_row2_col2" class="data row2 col2" >8.47</td>
                        <td id="T_43e8e_row2_col3" class="data row2 col3" >0.00</td>
                        <td id="T_43e8e_row2_col4" class="data row2 col4" >58.33</td>
                        <td id="T_43e8e_row2_col5" class="data row2 col5" >28.50</td>
                        <td id="T_43e8e_row2_col6" class="data row2 col6" >5.98</td>
                        <td id="T_43e8e_row2_col7" class="data row2 col7" >17.08</td>
                        <td id="T_43e8e_row2_col8" class="data row2 col8" >24.11</td>
                        <td id="T_43e8e_row2_col9" class="data row2 col9" >38.52</td>
                        <td id="T_43e8e_row2_col10" class="data row2 col10" >8.01</td>
                        <td id="T_43e8e_row2_col11" class="data row2 col11" >48.52</td>
                        <td id="T_43e8e_row2_col12" class="data row2 col12" >2.71</td>
                        <td id="T_43e8e_row2_col13" class="data row2 col13" >4.54</td>
            </tr>
            <tr>
                        <th id="T_43e8e_level0_row3" class="row_heading level0 row3" >0867.HK</th>
                        <td id="T_43e8e_row3_col0" class="data row3 col0" >康哲药业</td>
                        <td id="T_43e8e_row3_col1" class="data row3 col1" >12.58</td>
                        <td id="T_43e8e_row3_col2" class="data row3 col2" >25.74</td>
                        <td id="T_43e8e_row3_col3" class="data row3 col3" >11.01</td>
                        <td id="T_43e8e_row3_col4" class="data row3 col4" >22.20</td>
                        <td id="T_43e8e_row3_col5" class="data row3 col5" >33.52</td>
                        <td id="T_43e8e_row3_col6" class="data row3 col6" >9.24</td>
                        <td id="T_43e8e_row3_col7" class="data row3 col7" >6.76</td>
                        <td id="T_43e8e_row3_col8" class="data row3 col8" >15.17</td>
                        <td id="T_43e8e_row3_col9" class="data row3 col9" >12.23</td>
                        <td id="T_43e8e_row3_col10" class="data row3 col10" >12.66</td>
                        <td id="T_43e8e_row3_col11" class="data row3 col11" >30.68</td>
                        <td id="T_43e8e_row3_col12" class="data row3 col12" >39.37</td>
                        <td id="T_43e8e_row3_col13" class="data row3 col13" >37.77</td>
            </tr>
            <tr>
                        <th id="T_43e8e_level0_row4" class="row_heading level0 row4" >0868.HK</th>
                        <td id="T_43e8e_row4_col0" class="data row4 col0" >信义玻璃</td>
                        <td id="T_43e8e_row4_col1" class="data row4 col1" >37.94</td>
                        <td id="T_43e8e_row4_col2" class="data row4 col2" >17.37</td>
                        <td id="T_43e8e_row4_col3" class="data row4 col3" >0.20</td>
                        <td id="T_43e8e_row4_col4" class="data row4 col4" >22.32</td>
                        <td id="T_43e8e_row4_col5" class="data row4 col5" >28.94</td>
                        <td id="T_43e8e_row4_col6" class="data row4 col6" >8.25</td>
                        <td id="T_43e8e_row4_col7" class="data row4 col7" >6.50</td>
                        <td id="T_43e8e_row4_col8" class="data row4 col8" >18.22</td>
                        <td id="T_43e8e_row4_col9" class="data row4 col9" >21.82</td>
                        <td id="T_43e8e_row4_col10" class="data row4 col10" >0.07</td>
                        <td id="T_43e8e_row4_col11" class="data row4 col11" >60.29</td>
                        <td id="T_43e8e_row4_col12" class="data row4 col12" >23.56</td>
                        <td id="T_43e8e_row4_col13" class="data row4 col13" >97.14</td>
            </tr>
            <tr>
                        <th id="T_43e8e_level0_row5" class="row_heading level0 row5" >0914.HK</th>
                        <td id="T_43e8e_row5_col0" class="data row5 col0" >海螺水泥</td>
                        <td id="T_43e8e_row5_col1" class="data row5 col1" >16.30</td>
                        <td id="T_43e8e_row5_col2" class="data row5 col2" >7.17</td>
                        <td id="T_43e8e_row5_col3" class="data row5 col3" >0.36</td>
                        <td id="T_43e8e_row5_col4" class="data row5 col4" >22.59</td>
                        <td id="T_43e8e_row5_col5" class="data row5 col5" >21.40</td>
                        <td id="T_43e8e_row5_col6" class="data row5 col6" >35.01</td>
                        <td id="T_43e8e_row5_col7" class="data row5 col7" >31.14</td>
                        <td id="T_43e8e_row5_col8" class="data row5 col8" >35.10</td>
                        <td id="T_43e8e_row5_col9" class="data row5 col9" >46.03</td>
                        <td id="T_43e8e_row5_col10" class="data row5 col10" >36.04</td>
                        <td id="T_43e8e_row5_col11" class="data row5 col11" >80.90</td>
                        <td id="T_43e8e_row5_col12" class="data row5 col12" >768.24</td>
                        <td id="T_43e8e_row5_col13" class="data row5 col13" >847.14</td>
            </tr>
            <tr>
                        <th id="T_43e8e_level0_row6" class="row_heading level0 row6" >1277.HK</th>
                        <td id="T_43e8e_row6_col0" class="data row6 col0" >力量能源</td>
                        <td id="T_43e8e_row6_col1" class="data row6 col1" >24.86</td>
                        <td id="T_43e8e_row6_col2" class="data row6 col2" >5.82</td>
                        <td id="T_43e8e_row6_col3" class="data row6 col3" >0.00</td>
                        <td id="T_43e8e_row6_col4" class="data row6 col4" >38.28</td>
                        <td id="T_43e8e_row6_col5" class="data row6 col5" >30.47</td>
                        <td id="T_43e8e_row6_col6" class="data row6 col6" >19.96</td>
                        <td id="T_43e8e_row6_col7" class="data row6 col7" >17.17</td>
                        <td id="T_43e8e_row6_col8" class="data row6 col8" >16.82</td>
                        <td id="T_43e8e_row6_col9" class="data row6 col9" >28.37</td>
                        <td id="T_43e8e_row6_col10" class="data row6 col10" >22.58</td>
                        <td id="T_43e8e_row6_col11" class="data row6 col11" >38.49</td>
                        <td id="T_43e8e_row6_col12" class="data row6 col12" >19.87</td>
                        <td id="T_43e8e_row6_col13" class="data row6 col13" >14.69</td>
            </tr>
            <tr>
                        <th id="T_43e8e_level0_row7" class="row_heading level0 row7" >1523.HK</th>
                        <td id="T_43e8e_row7_col0" class="data row7 col0" >珩湾科技</td>
                        <td id="T_43e8e_row7_col1" class="data row7 col1" >39.57</td>
                        <td id="T_43e8e_row7_col2" class="data row7 col2" >13.40</td>
                        <td id="T_43e8e_row7_col3" class="data row7 col3" >0.00</td>
                        <td id="T_43e8e_row7_col4" class="data row7 col4" >34.51</td>
                        <td id="T_43e8e_row7_col5" class="data row7 col5" >25.56</td>
                        <td id="T_43e8e_row7_col6" class="data row7 col6" >12.48</td>
                        <td id="T_43e8e_row7_col7" class="data row7 col7" >2.62</td>
                        <td id="T_43e8e_row7_col8" class="data row7 col8" >17.62</td>
                        <td id="T_43e8e_row7_col9" class="data row7 col9" >3.74</td>
                        <td id="T_43e8e_row7_col10" class="data row7 col10" >474.90</td>
                        <td id="T_43e8e_row7_col11" class="data row7 col11" >836.60</td>
                        <td id="T_43e8e_row7_col12" class="data row7 col12" >26.40</td>
                        <td id="T_43e8e_row7_col13" class="data row7 col13" >0.23</td>
            </tr>
            <tr>
                        <th id="T_43e8e_level0_row8" class="row_heading level0 row8" >1558.HK</th>
                        <td id="T_43e8e_row8_col0" class="data row8 col0" >东阳光药</td>
                        <td id="T_43e8e_row8_col1" class="data row8 col1" >46.62</td>
                        <td id="T_43e8e_row8_col2" class="data row8 col2" >25.54</td>
                        <td id="T_43e8e_row8_col3" class="data row8 col3" >1.55</td>
                        <td id="T_43e8e_row8_col4" class="data row8 col4" >27.79</td>
                        <td id="T_43e8e_row8_col5" class="data row8 col5" >36.13</td>
                        <td id="T_43e8e_row8_col6" class="data row8 col6" >47.47</td>
                        <td id="T_43e8e_row8_col7" class="data row8 col7" >105.40</td>
                        <td id="T_43e8e_row8_col8" class="data row8 col8" >30.99</td>
                        <td id="T_43e8e_row8_col9" class="data row8 col9" >80.91</td>
                        <td id="T_43e8e_row8_col10" class="data row8 col10" >343.43</td>
                        <td id="T_43e8e_row8_col11" class="data row8 col11" >722.32</td>
                        <td id="T_43e8e_row8_col12" class="data row8 col12" >472.29</td>
                        <td id="T_43e8e_row8_col13" class="data row8 col13" >29.49</td>
            </tr>
            <tr>
                        <th id="T_43e8e_level0_row9" class="row_heading level0 row9" >1598.HK</th>
                        <td id="T_43e8e_row9_col0" class="data row9 col0" >21世纪教育</td>
                        <td id="T_43e8e_row9_col1" class="data row9 col1" >41.39</td>
                        <td id="T_43e8e_row9_col2" class="data row9 col2" >4.26</td>
                        <td id="T_43e8e_row9_col3" class="data row9 col3" >10.27</td>
                        <td id="T_43e8e_row9_col4" class="data row9 col4" >16.13</td>
                        <td id="T_43e8e_row9_col5" class="data row9 col5" >31.64</td>
                        <td id="T_43e8e_row9_col6" class="data row9 col6" >14.44</td>
                        <td id="T_43e8e_row9_col7" class="data row9 col7" >5.49</td>
                        <td id="T_43e8e_row9_col8" class="data row9 col8" >22.19</td>
                        <td id="T_43e8e_row9_col9" class="data row9 col9" >30.47</td>
                        <td id="T_43e8e_row9_col10" class="data row9 col10" >1.92</td>
                        <td id="T_43e8e_row9_col11" class="data row9 col11" >76.78</td>
                        <td id="T_43e8e_row9_col12" class="data row9 col12" >0.88</td>
                        <td id="T_43e8e_row9_col13" class="data row9 col13" >1.53</td>
            </tr>
            <tr>
                        <th id="T_43e8e_level0_row10" class="row_heading level0 row10" >1681.HK</th>
                        <td id="T_43e8e_row10_col0" class="data row10 col0" >康臣药业</td>
                        <td id="T_43e8e_row10_col1" class="data row10 col1" >36.30</td>
                        <td id="T_43e8e_row10_col2" class="data row10 col2" >26.15</td>
                        <td id="T_43e8e_row10_col3" class="data row10 col3" >14.86</td>
                        <td id="T_43e8e_row10_col4" class="data row10 col4" >17.68</td>
                        <td id="T_43e8e_row10_col5" class="data row10 col5" >20.54</td>
                        <td id="T_43e8e_row10_col6" class="data row10 col6" >2.07</td>
                        <td id="T_43e8e_row10_col7" class="data row10 col7" >8.69</td>
                        <td id="T_43e8e_row10_col8" class="data row10 col8" >153.16</td>
                        <td id="T_43e8e_row10_col9" class="data row10 col9" >325.81</td>
                        <td id="T_43e8e_row10_col10" class="data row10 col10" >140.93</td>
                        <td id="T_43e8e_row10_col11" class="data row10 col11" >186.70</td>
                        <td id="T_43e8e_row10_col12" class="data row10 col12" >70.55</td>
                        <td id="T_43e8e_row10_col13" class="data row10 col13" >66.03</td>
            </tr>
            <tr>
                        <th id="T_43e8e_level0_row11" class="row_heading level0 row11" >1756.HK</th>
                        <td id="T_43e8e_row11_col0" class="data row11 col0" >华立大学集团</td>
                        <td id="T_43e8e_row11_col1" class="data row11 col1" >47.08</td>
                        <td id="T_43e8e_row11_col2" class="data row11 col2" >2.89</td>
                        <td id="T_43e8e_row11_col3" class="data row11 col3" >0.00</td>
                        <td id="T_43e8e_row11_col4" class="data row11 col4" >15.53</td>
                        <td id="T_43e8e_row11_col5" class="data row11 col5" >34.63</td>
                        <td id="T_43e8e_row11_col6" class="data row11 col6" >9.66</td>
                        <td id="T_43e8e_row11_col7" class="data row11 col7" >4.01</td>
                        <td id="T_43e8e_row11_col8" class="data row11 col8" >17.66</td>
                        <td id="T_43e8e_row11_col9" class="data row11 col9" >18.78</td>
                        <td id="T_43e8e_row11_col10" class="data row11 col10" >85.28</td>
                        <td id="T_43e8e_row11_col11" class="data row11 col11" >285.66</td>
                        <td id="T_43e8e_row11_col12" class="data row11 col12" >-10.66</td>
                        <td id="T_43e8e_row11_col13" class="data row11 col13" >4.59</td>
            </tr>
            <tr>
                        <th id="T_43e8e_level0_row12" class="row_heading level0 row12" >1830.HK</th>
                        <td id="T_43e8e_row12_col0" class="data row12 col0" >必瘦站</td>
                        <td id="T_43e8e_row12_col1" class="data row12 col1" >47.74</td>
                        <td id="T_43e8e_row12_col2" class="data row12 col2" >6.14</td>
                        <td id="T_43e8e_row12_col3" class="data row12 col3" >0.00</td>
                        <td id="T_43e8e_row12_col4" class="data row12 col4" >42.84</td>
                        <td id="T_43e8e_row12_col5" class="data row12 col5" >22.29</td>
                        <td id="T_43e8e_row12_col6" class="data row12 col6" >18.49</td>
                        <td id="T_43e8e_row12_col7" class="data row12 col7" >14.25</td>
                        <td id="T_43e8e_row12_col8" class="data row12 col8" >63.25</td>
                        <td id="T_43e8e_row12_col9" class="data row12 col9" >49.84</td>
                        <td id="T_43e8e_row12_col10" class="data row12 col10" >52.20</td>
                        <td id="T_43e8e_row12_col11" class="data row12 col11" >36.98</td>
                        <td id="T_43e8e_row12_col12" class="data row12 col12" >13.73</td>
                        <td id="T_43e8e_row12_col13" class="data row12 col13" >12.30</td>
            </tr>
            <tr>
                        <th id="T_43e8e_level0_row13" class="row_heading level0 row13" >1890.HK</th>
                        <td id="T_43e8e_row13_col0" class="data row13 col0" >中国科培</td>
                        <td id="T_43e8e_row13_col1" class="data row13 col1" >28.14</td>
                        <td id="T_43e8e_row13_col2" class="data row13 col2" >22.19</td>
                        <td id="T_43e8e_row13_col3" class="data row13 col3" >0.00</td>
                        <td id="T_43e8e_row13_col4" class="data row13 col4" >19.44</td>
                        <td id="T_43e8e_row13_col5" class="data row13 col5" >59.78</td>
                        <td id="T_43e8e_row13_col6" class="data row13 col6" >23.97</td>
                        <td id="T_43e8e_row13_col7" class="data row13 col7" >2.47</td>
                        <td id="T_43e8e_row13_col8" class="data row13 col8" >35.11</td>
                        <td id="T_43e8e_row13_col9" class="data row13 col9" >12.25</td>
                        <td id="T_43e8e_row13_col10" class="data row13 col10" >158.66</td>
                        <td id="T_43e8e_row13_col11" class="data row13 col11" >226.57</td>
                        <td id="T_43e8e_row13_col12" class="data row13 col12" >28.14</td>
                        <td id="T_43e8e_row13_col13" class="data row13 col13" >11.81</td>
            </tr>
            <tr>
                        <th id="T_43e8e_level0_row14" class="row_heading level0 row14" >1935.HK</th>
                        <td id="T_43e8e_row14_col0" class="data row14 col0" >嘉宏教育</td>
                        <td id="T_43e8e_row14_col1" class="data row14 col1" >17.52</td>
                        <td id="T_43e8e_row14_col2" class="data row14 col2" >1.35</td>
                        <td id="T_43e8e_row14_col3" class="data row14 col3" >6.22</td>
                        <td id="T_43e8e_row14_col4" class="data row14 col4" >15.27</td>
                        <td id="T_43e8e_row14_col5" class="data row14 col5" >51.56</td>
                        <td id="T_43e8e_row14_col6" class="data row14 col6" >50.64</td>
                        <td id="T_43e8e_row14_col7" class="data row14 col7" >31.14</td>
                        <td id="T_43e8e_row14_col8" class="data row14 col8" >30.61</td>
                        <td id="T_43e8e_row14_col9" class="data row14 col9" >19.47</td>
                        <td id="T_43e8e_row14_col10" class="data row14 col10" >45.68</td>
                        <td id="T_43e8e_row14_col11" class="data row14 col11" >45.18</td>
                        <td id="T_43e8e_row14_col12" class="data row14 col12" >8.17</td>
                        <td id="T_43e8e_row14_col13" class="data row14 col13" >4.84</td>
            </tr>
            <tr>
                        <th id="T_43e8e_level0_row15" class="row_heading level0 row15" >2189.HK</th>
                        <td id="T_43e8e_row15_col0" class="data row15 col0" >嘉涛(香港)控股</td>
                        <td id="T_43e8e_row15_col1" class="data row15 col1" >44.77</td>
                        <td id="T_43e8e_row15_col2" class="data row15 col2" >2.00</td>
                        <td id="T_43e8e_row15_col3" class="data row15 col3" >0.00</td>
                        <td id="T_43e8e_row15_col4" class="data row15 col4" >98.37</td>
                        <td id="T_43e8e_row15_col5" class="data row15 col5" >22.77</td>
                        <td id="T_43e8e_row15_col6" class="data row15 col6" >8.86</td>
                        <td id="T_43e8e_row15_col7" class="data row15 col7" >4.30</td>
                        <td id="T_43e8e_row15_col8" class="data row15 col8" >13.05</td>
                        <td id="T_43e8e_row15_col9" class="data row15 col9" >11.78</td>
                        <td id="T_43e8e_row15_col10" class="data row15 col10" >28.52</td>
                        <td id="T_43e8e_row15_col11" class="data row15 col11" >18.31</td>
                        <td id="T_43e8e_row15_col12" class="data row15 col12" >1.14</td>
                        <td id="T_43e8e_row15_col13" class="data row15 col13" >0.70</td>
            </tr>
            <tr>
                        <th id="T_43e8e_level0_row16" class="row_heading level0 row16" >2660.HK</th>
                        <td id="T_43e8e_row16_col0" class="data row16 col0" >禅游科技</td>
                        <td id="T_43e8e_row16_col1" class="data row16 col1" >6.95</td>
                        <td id="T_43e8e_row16_col2" class="data row16 col2" >9.60</td>
                        <td id="T_43e8e_row16_col3" class="data row16 col3" >0.00</td>
                        <td id="T_43e8e_row16_col4" class="data row16 col4" >31.91</td>
                        <td id="T_43e8e_row16_col5" class="data row16 col5" >22.01</td>
                        <td id="T_43e8e_row16_col6" class="data row16 col6" >17.39</td>
                        <td id="T_43e8e_row16_col7" class="data row16 col7" >4.60</td>
                        <td id="T_43e8e_row16_col8" class="data row16 col8" >49.69</td>
                        <td id="T_43e8e_row16_col9" class="data row16 col9" >13.24</td>
                        <td id="T_43e8e_row16_col10" class="data row16 col10" >54.05</td>
                        <td id="T_43e8e_row16_col11" class="data row16 col11" >78.58</td>
                        <td id="T_43e8e_row16_col12" class="data row16 col12" >5.83</td>
                        <td id="T_43e8e_row16_col13" class="data row16 col13" >5.53</td>
            </tr>
            <tr>
                        <th id="T_43e8e_level0_row17" class="row_heading level0 row17" >3601.HK</th>
                        <td id="T_43e8e_row17_col0" class="data row17 col0" >鲁大师</td>
                        <td id="T_43e8e_row17_col1" class="data row17 col1" >6.89</td>
                        <td id="T_43e8e_row17_col2" class="data row17 col2" >19.15</td>
                        <td id="T_43e8e_row17_col3" class="data row17 col3" >0.00</td>
                        <td id="T_43e8e_row17_col4" class="data row17 col4" >28.40</td>
                        <td id="T_43e8e_row17_col5" class="data row17 col5" >28.15</td>
                        <td id="T_43e8e_row17_col6" class="data row17 col6" >57.87</td>
                        <td id="T_43e8e_row17_col7" class="data row17 col7" >91.82</td>
                        <td id="T_43e8e_row17_col8" class="data row17 col8" >16.75</td>
                        <td id="T_43e8e_row17_col9" class="data row17 col9" >41.33</td>
                        <td id="T_43e8e_row17_col10" class="data row17 col10" >2.86</td>
                        <td id="T_43e8e_row17_col11" class="data row17 col11" >32.01</td>
                        <td id="T_43e8e_row17_col12" class="data row17 col12" >0.65</td>
                        <td id="T_43e8e_row17_col13" class="data row17 col13" >1.48</td>
            </tr>
            <tr>
                        <th id="T_43e8e_level0_row18" class="row_heading level0 row18" >3686.HK</th>
                        <td id="T_43e8e_row18_col0" class="data row18 col0" >祈福生活服务</td>
                        <td id="T_43e8e_row18_col1" class="data row18 col1" >27.40</td>
                        <td id="T_43e8e_row18_col2" class="data row18 col2" >25.42</td>
                        <td id="T_43e8e_row18_col3" class="data row18 col3" >0.00</td>
                        <td id="T_43e8e_row18_col4" class="data row18 col4" >23.54</td>
                        <td id="T_43e8e_row18_col5" class="data row18 col5" >22.86</td>
                        <td id="T_43e8e_row18_col6" class="data row18 col6" >5.24</td>
                        <td id="T_43e8e_row18_col7" class="data row18 col7" >11.32</td>
                        <td id="T_43e8e_row18_col8" class="data row18 col8" >31.74</td>
                        <td id="T_43e8e_row18_col9" class="data row18 col9" >2.67</td>
                        <td id="T_43e8e_row18_col10" class="data row18 col10" >13.53</td>
                        <td id="T_43e8e_row18_col11" class="data row18 col11" >17.44</td>
                        <td id="T_43e8e_row18_col12" class="data row18 col12" >1.53</td>
                        <td id="T_43e8e_row18_col13" class="data row18 col13" >2.44</td>
            </tr>
            <tr>
                        <th id="T_43e8e_level0_row19" class="row_heading level0 row19" >3798.HK</th>
                        <td id="T_43e8e_row19_col0" class="data row19 col0" >家乡互动</td>
                        <td id="T_43e8e_row19_col1" class="data row19 col1" >14.06</td>
                        <td id="T_43e8e_row19_col2" class="data row19 col2" >12.79</td>
                        <td id="T_43e8e_row19_col3" class="data row19 col3" >0.00</td>
                        <td id="T_43e8e_row19_col4" class="data row19 col4" >68.29</td>
                        <td id="T_43e8e_row19_col5" class="data row19 col5" >44.74</td>
                        <td id="T_43e8e_row19_col6" class="data row19 col6" >44.37</td>
                        <td id="T_43e8e_row19_col7" class="data row19 col7" >20.79</td>
                        <td id="T_43e8e_row19_col8" class="data row19 col8" >54.15</td>
                        <td id="T_43e8e_row19_col9" class="data row19 col9" >46.52</td>
                        <td id="T_43e8e_row19_col10" class="data row19 col10" >31.66</td>
                        <td id="T_43e8e_row19_col11" class="data row19 col11" >19.92</td>
                        <td id="T_43e8e_row19_col12" class="data row19 col12" >7.10</td>
                        <td id="T_43e8e_row19_col13" class="data row19 col13" >9.94</td>
            </tr>
            <tr>
                        <th id="T_43e8e_level0_row20" class="row_heading level0 row20" >6127.HK</th>
                        <td id="T_43e8e_row20_col0" class="data row20 col0" >昭衍新药</td>
                        <td id="T_43e8e_row20_col1" class="data row20 col1" >41.92</td>
                        <td id="T_43e8e_row20_col2" class="data row20 col2" >15.49</td>
                        <td id="T_43e8e_row20_col3" class="data row20 col3" >10.23</td>
                        <td id="T_43e8e_row20_col4" class="data row20 col4" >19.51</td>
                        <td id="T_43e8e_row20_col5" class="data row20 col5" >27.59</td>
                        <td id="T_43e8e_row20_col6" class="data row20 col6" >53.46</td>
                        <td id="T_43e8e_row20_col7" class="data row20 col7" >16.49</td>
                        <td id="T_43e8e_row20_col8" class="data row20 col8" >60.93</td>
                        <td id="T_43e8e_row20_col9" class="data row20 col9" >16.74</td>
                        <td id="T_43e8e_row20_col10" class="data row20 col10" >368.09</td>
                        <td id="T_43e8e_row20_col11" class="data row20 col11" >729.80</td>
                        <td id="T_43e8e_row20_col12" class="data row20 col12" >125.63</td>
                        <td id="T_43e8e_row20_col13" class="data row20 col13" >8.40</td>
            </tr>
            <tr>
                        <th id="T_43e8e_level0_row21" class="row_heading level0 row21" >6186.HK</th>
                        <td id="T_43e8e_row21_col0" class="data row21 col0" >中国飞鹤</td>
                        <td id="T_43e8e_row21_col1" class="data row21 col1" >32.26</td>
                        <td id="T_43e8e_row21_col2" class="data row21 col2" >3.19</td>
                        <td id="T_43e8e_row21_col3" class="data row21 col3" >0.27</td>
                        <td id="T_43e8e_row21_col4" class="data row21 col4" >35.80</td>
                        <td id="T_43e8e_row21_col5" class="data row21 col5" >27.49</td>
                        <td id="T_43e8e_row21_col6" class="data row21 col6" >48.02</td>
                        <td id="T_43e8e_row21_col7" class="data row21 col7" >24.74</td>
                        <td id="T_43e8e_row21_col8" class="data row21 col8" >85.92</td>
                        <td id="T_43e8e_row21_col9" class="data row21 col9" >9.29</td>
                        <td id="T_43e8e_row21_col10" class="data row21 col10" >66.16</td>
                        <td id="T_43e8e_row21_col11" class="data row21 col11" >48.49</td>
                        <td id="T_43e8e_row21_col12" class="data row21 col12" >187.56</td>
                        <td id="T_43e8e_row21_col13" class="data row21 col13" >274.55</td>
            </tr>
            <tr>
                        <th id="T_43e8e_level0_row22" class="row_heading level0 row22" >6820.HK</th>
                        <td id="T_43e8e_row22_col0" class="data row22 col0" >友谊时光</td>
                        <td id="T_43e8e_row22_col1" class="data row22 col1" >12.60</td>
                        <td id="T_43e8e_row22_col2" class="data row22 col2" >7.08</td>
                        <td id="T_43e8e_row22_col3" class="data row22 col3" >0.00</td>
                        <td id="T_43e8e_row22_col4" class="data row22 col4" >38.95</td>
                        <td id="T_43e8e_row22_col5" class="data row22 col5" >21.88</td>
                        <td id="T_43e8e_row22_col6" class="data row22 col6" >51.22</td>
                        <td id="T_43e8e_row22_col7" class="data row22 col7" >50.61</td>
                        <td id="T_43e8e_row22_col8" class="data row22 col8" >76.65</td>
                        <td id="T_43e8e_row22_col9" class="data row22 col9" >94.14</td>
                        <td id="T_43e8e_row22_col10" class="data row22 col10" >78.93</td>
                        <td id="T_43e8e_row22_col11" class="data row22 col11" >83.51</td>
                        <td id="T_43e8e_row22_col12" class="data row22 col12" >18.84</td>
                        <td id="T_43e8e_row22_col13" class="data row22 col13" >22.01</td>
            </tr>
            <tr>
                        <th id="T_43e8e_level0_row23" class="row_heading level0 row23" >6969.HK</th>
                        <td id="T_43e8e_row23_col0" class="data row23 col0" >思摩尔国际</td>
                        <td id="T_43e8e_row23_col1" class="data row23 col1" >16.07</td>
                        <td id="T_43e8e_row23_col2" class="data row23 col2" >23.94</td>
                        <td id="T_43e8e_row23_col3" class="data row23 col3" >0.00</td>
                        <td id="T_43e8e_row23_col4" class="data row23 col4" >109.26</td>
                        <td id="T_43e8e_row23_col5" class="data row23 col5" >21.50</td>
                        <td id="T_43e8e_row23_col6" class="data row23 col6" >90.85</td>
                        <td id="T_43e8e_row23_col7" class="data row23 col7" >51.39</td>
                        <td id="T_43e8e_row23_col8" class="data row23 col8" >164.98</td>
                        <td id="T_43e8e_row23_col9" class="data row23 col9" >141.59</td>
                        <td id="T_43e8e_row23_col10" class="data row23 col10" >99.12</td>
                        <td id="T_43e8e_row23_col11" class="data row23 col11" >37.70</td>
                        <td id="T_43e8e_row23_col12" class="data row23 col12" >125.84</td>
                        <td id="T_43e8e_row23_col13" class="data row23 col13" >288.21</td>
            </tr>
            <tr>
                        <th id="T_43e8e_level0_row24" class="row_heading level0 row24" >9633.HK</th>
                        <td id="T_43e8e_row24_col0" class="data row24 col0" >农夫山泉</td>
                        <td id="T_43e8e_row24_col1" class="data row24 col1" >40.09</td>
                        <td id="T_43e8e_row24_col2" class="data row24 col2" >4.16</td>
                        <td id="T_43e8e_row24_col3" class="data row24 col3" >0.00</td>
                        <td id="T_43e8e_row24_col4" class="data row24 col4" >34.90</td>
                        <td id="T_43e8e_row24_col5" class="data row24 col5" >20.15</td>
                        <td id="T_43e8e_row24_col6" class="data row24 col6" >9.87</td>
                        <td id="T_43e8e_row24_col7" class="data row24 col7" >12.67</td>
                        <td id="T_43e8e_row24_col8" class="data row24 col8" >16.85</td>
                        <td id="T_43e8e_row24_col9" class="data row24 col9" >17.65</td>
                        <td id="T_43e8e_row24_col10" class="data row24 col10" >75.80</td>
                        <td id="T_43e8e_row24_col11" class="data row24 col11" >139.77</td>
                        <td id="T_43e8e_row24_col12" class="data row24 col12" >223.57</td>
                        <td id="T_43e8e_row24_col13" class="data row24 col13" >84.48</td>
            </tr>
            <tr>
                        <th id="T_43e8e_level0_row25" class="row_heading level0 row25" >9997.HK</th>
                        <td id="T_43e8e_row25_col0" class="data row25 col0" >康基医疗</td>
                        <td id="T_43e8e_row25_col1" class="data row25 col1" >2.77</td>
                        <td id="T_43e8e_row25_col2" class="data row25 col2" >17.33</td>
                        <td id="T_43e8e_row25_col3" class="data row25 col3" >0.00</td>
                        <td id="T_43e8e_row25_col4" class="data row25 col4" >43.05</td>
                        <td id="T_43e8e_row25_col5" class="data row25 col5" >44.74</td>
                        <td id="T_43e8e_row25_col6" class="data row25 col6" >28.95</td>
                        <td id="T_43e8e_row25_col7" class="data row25 col7" >23.69</td>
                        <td id="T_43e8e_row25_col8" class="data row25 col8" >28.87</td>
                        <td id="T_43e8e_row25_col9" class="data row25 col9" >10.41</td>
                        <td id="T_43e8e_row25_col10" class="data row25 col10" >23.56</td>
                        <td id="T_43e8e_row25_col11" class="data row25 col11" >53.22</td>
                        <td id="T_43e8e_row25_col12" class="data row25 col12" >4.85</td>
                        <td id="T_43e8e_row25_col13" class="data row25 col13" >4.67</td>
            </tr>
            <tr>
                        <th id="T_43e8e_level0_row26" class="row_heading level0 row26" >9999.HK</th>
                        <td id="T_43e8e_row26_col0" class="data row26 col0" >网易-S</td>
                        <td id="T_43e8e_row26_col1" class="data row26 col1" >33.89</td>
                        <td id="T_43e8e_row26_col2" class="data row26 col2" >8.99</td>
                        <td id="T_43e8e_row26_col3" class="data row26 col3" >0.39</td>
                        <td id="T_43e8e_row26_col4" class="data row26 col4" >21.57</td>
                        <td id="T_43e8e_row26_col5" class="data row26 col5" >22.09</td>
                        <td id="T_43e8e_row26_col6" class="data row26 col6" >18.43</td>
                        <td id="T_43e8e_row26_col7" class="data row26 col7" >5.14</td>
                        <td id="T_43e8e_row26_col8" class="data row26 col8" >53.15</td>
                        <td id="T_43e8e_row26_col9" class="data row26 col9" >166.31</td>
                        <td id="T_43e8e_row26_col10" class="data row26 col10" >33.70</td>
                        <td id="T_43e8e_row26_col11" class="data row26 col11" >20.88</td>
                        <td id="T_43e8e_row26_col12" class="data row26 col12" >440.86</td>
                        <td id="T_43e8e_row26_col13" class="data row26 col13" >532.03</td>
            </tr>
    </tbody></table>



### 观察列表




<style  type="text/css" >
#T_04932_row0_col0,#T_04932_row0_col1,#T_04932_row0_col2,#T_04932_row0_col3,#T_04932_row0_col4,#T_04932_row0_col5,#T_04932_row0_col6,#T_04932_row0_col7,#T_04932_row0_col8,#T_04932_row0_col9,#T_04932_row0_col10,#T_04932_row0_col11,#T_04932_row0_col12,#T_04932_row0_col13,#T_04932_row1_col0,#T_04932_row1_col1,#T_04932_row1_col2,#T_04932_row1_col3,#T_04932_row1_col4,#T_04932_row1_col6,#T_04932_row1_col7,#T_04932_row1_col9,#T_04932_row1_col11,#T_04932_row1_col13,#T_04932_row2_col0,#T_04932_row2_col1,#T_04932_row2_col2,#T_04932_row2_col3,#T_04932_row2_col4,#T_04932_row2_col5,#T_04932_row2_col6,#T_04932_row2_col7,#T_04932_row2_col8,#T_04932_row2_col9,#T_04932_row2_col10,#T_04932_row2_col11,#T_04932_row2_col13,#T_04932_row3_col0,#T_04932_row3_col1,#T_04932_row3_col2,#T_04932_row3_col3,#T_04932_row3_col4,#T_04932_row3_col5,#T_04932_row3_col6,#T_04932_row3_col7,#T_04932_row3_col9,#T_04932_row3_col11,#T_04932_row4_col0,#T_04932_row4_col1,#T_04932_row4_col2,#T_04932_row4_col3,#T_04932_row4_col6,#T_04932_row4_col7,#T_04932_row4_col8,#T_04932_row4_col9,#T_04932_row4_col10,#T_04932_row4_col11,#T_04932_row5_col0,#T_04932_row5_col1,#T_04932_row5_col2,#T_04932_row5_col3,#T_04932_row5_col4,#T_04932_row5_col5,#T_04932_row5_col6,#T_04932_row5_col7,#T_04932_row5_col8,#T_04932_row5_col9,#T_04932_row5_col10,#T_04932_row5_col11,#T_04932_row5_col12,#T_04932_row5_col13,#T_04932_row6_col0,#T_04932_row6_col1,#T_04932_row6_col2,#T_04932_row6_col3,#T_04932_row6_col4,#T_04932_row6_col5,#T_04932_row6_col6,#T_04932_row6_col7,#T_04932_row6_col8,#T_04932_row6_col9,#T_04932_row6_col11,#T_04932_row6_col12,#T_04932_row6_col13,#T_04932_row7_col0,#T_04932_row7_col1,#T_04932_row7_col2,#T_04932_row7_col4,#T_04932_row7_col6,#T_04932_row7_col7,#T_04932_row7_col8,#T_04932_row7_col9,#T_04932_row7_col11,#T_04932_row8_col0,#T_04932_row8_col1,#T_04932_row8_col2,#T_04932_row8_col3,#T_04932_row8_col4,#T_04932_row8_col5,#T_04932_row8_col6,#T_04932_row8_col7,#T_04932_row8_col8,#T_04932_row8_col9,#T_04932_row8_col11,#T_04932_row8_col12,#T_04932_row8_col13,#T_04932_row9_col0,#T_04932_row9_col1,#T_04932_row9_col2,#T_04932_row9_col3,#T_04932_row9_col4,#T_04932_row9_col5,#T_04932_row9_col6,#T_04932_row9_col7,#T_04932_row9_col8,#T_04932_row9_col9,#T_04932_row9_col10,#T_04932_row9_col11,#T_04932_row9_col12,#T_04932_row9_col13,#T_04932_row10_col0,#T_04932_row10_col1,#T_04932_row10_col2,#T_04932_row10_col3,#T_04932_row10_col4,#T_04932_row10_col5,#T_04932_row10_col6,#T_04932_row10_col7,#T_04932_row10_col8,#T_04932_row10_col9,#T_04932_row10_col10,#T_04932_row10_col11,#T_04932_row10_col13,#T_04932_row11_col0,#T_04932_row11_col1,#T_04932_row11_col2,#T_04932_row11_col3,#T_04932_row11_col4,#T_04932_row11_col5,#T_04932_row11_col6,#T_04932_row11_col7,#T_04932_row11_col8,#T_04932_row11_col9,#T_04932_row11_col11,#T_04932_row11_col13,#T_04932_row12_col0,#T_04932_row12_col1,#T_04932_row12_col2,#T_04932_row12_col3,#T_04932_row12_col4,#T_04932_row12_col6,#T_04932_row12_col7,#T_04932_row12_col8,#T_04932_row12_col9,#T_04932_row12_col10,#T_04932_row12_col11,#T_04932_row13_col0,#T_04932_row13_col1,#T_04932_row13_col2,#T_04932_row13_col3,#T_04932_row13_col6,#T_04932_row13_col7,#T_04932_row13_col8,#T_04932_row13_col9,#T_04932_row13_col10,#T_04932_row13_col11,#T_04932_row14_col0,#T_04932_row14_col1,#T_04932_row14_col2,#T_04932_row14_col3,#T_04932_row14_col4,#T_04932_row14_col5,#T_04932_row14_col6,#T_04932_row14_col7,#T_04932_row14_col8,#T_04932_row14_col9,#T_04932_row14_col10,#T_04932_row14_col11,#T_04932_row14_col12,#T_04932_row14_col13,#T_04932_row15_col0,#T_04932_row15_col1,#T_04932_row15_col2,#T_04932_row15_col3,#T_04932_row15_col7,#T_04932_row15_col9,#T_04932_row15_col10,#T_04932_row15_col11,#T_04932_row15_col12,#T_04932_row15_col13,#T_04932_row16_col0,#T_04932_row16_col1,#T_04932_row16_col2,#T_04932_row16_col3,#T_04932_row16_col4,#T_04932_row16_col5,#T_04932_row16_col6,#T_04932_row16_col7,#T_04932_row16_col9,#T_04932_row16_col11,#T_04932_row16_col12,#T_04932_row16_col13,#T_04932_row17_col0,#T_04932_row17_col1,#T_04932_row17_col2,#T_04932_row17_col3,#T_04932_row17_col4,#T_04932_row17_col5,#T_04932_row17_col6,#T_04932_row17_col7,#T_04932_row17_col9,#T_04932_row17_col11,#T_04932_row17_col12,#T_04932_row17_col13,#T_04932_row18_col0,#T_04932_row18_col1,#T_04932_row18_col2,#T_04932_row18_col3,#T_04932_row18_col4,#T_04932_row18_col5,#T_04932_row18_col7,#T_04932_row18_col9,#T_04932_row18_col11,#T_04932_row18_col12,#T_04932_row18_col13,#T_04932_row19_col0,#T_04932_row19_col1,#T_04932_row19_col2,#T_04932_row19_col3,#T_04932_row19_col4,#T_04932_row19_col5,#T_04932_row19_col6,#T_04932_row19_col7,#T_04932_row19_col8,#T_04932_row19_col9,#T_04932_row19_col11,#T_04932_row19_col12,#T_04932_row19_col13,#T_04932_row20_col0,#T_04932_row20_col1,#T_04932_row20_col2,#T_04932_row20_col3,#T_04932_row20_col6,#T_04932_row20_col7,#T_04932_row20_col8,#T_04932_row20_col9,#T_04932_row20_col11,#T_04932_row21_col0,#T_04932_row21_col1,#T_04932_row21_col2,#T_04932_row21_col3,#T_04932_row21_col4,#T_04932_row21_col5,#T_04932_row21_col6,#T_04932_row21_col7,#T_04932_row21_col8,#T_04932_row21_col9,#T_04932_row21_col11,#T_04932_row21_col12,#T_04932_row21_col13{
            color:  black;
        }#T_04932_row1_col5,#T_04932_row1_col8,#T_04932_row1_col10,#T_04932_row1_col12,#T_04932_row2_col12,#T_04932_row3_col8,#T_04932_row3_col10,#T_04932_row3_col12,#T_04932_row3_col13,#T_04932_row4_col4,#T_04932_row4_col5,#T_04932_row4_col12,#T_04932_row4_col13,#T_04932_row6_col10,#T_04932_row7_col3,#T_04932_row7_col5,#T_04932_row7_col10,#T_04932_row7_col12,#T_04932_row7_col13,#T_04932_row8_col10,#T_04932_row10_col12,#T_04932_row11_col10,#T_04932_row11_col12,#T_04932_row12_col5,#T_04932_row12_col12,#T_04932_row12_col13,#T_04932_row13_col4,#T_04932_row13_col5,#T_04932_row13_col12,#T_04932_row13_col13,#T_04932_row15_col4,#T_04932_row15_col5,#T_04932_row15_col6,#T_04932_row15_col8,#T_04932_row16_col8,#T_04932_row16_col10,#T_04932_row17_col8,#T_04932_row17_col10,#T_04932_row18_col6,#T_04932_row18_col8,#T_04932_row18_col10,#T_04932_row19_col10,#T_04932_row20_col4,#T_04932_row20_col5,#T_04932_row20_col10,#T_04932_row20_col12,#T_04932_row20_col13,#T_04932_row21_col10{
            color:  red;
        }</style><table id="T_04932_" ><thead>    <tr>        <th class="blank level0" ></th>        <th class="col_heading level0 col0" >名称</th>        <th class="col_heading level0 col1" >负债率</th>        <th class="col_heading level0 col2" >应收比</th>        <th class="col_heading level0 col3" >商誉比</th>        <th class="col_heading level0 col4" >ROE</th>        <th class="col_heading level0 col5" >利润率</th>        <th class="col_heading level0 col6" >收入增长</th>        <th class="col_heading level0 col7" >收入波动</th>        <th class="col_heading level0 col8" >盈利增长</th>        <th class="col_heading level0 col9" >盈利波动</th>        <th class="col_heading level0 col10" >FCF增长</th>        <th class="col_heading level0 col11" >FCF波动</th>        <th class="col_heading level0 col12" >DCF</th>        <th class="col_heading level0 col13" >盈利折现</th>    </tr>    <tr>        <th class="index_name level0" >Symbol</th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>    </tr></thead><tbody>
                <tr>
                        <th id="T_04932_level0_row0" class="row_heading level0 row0" >0700.HK</th>
                        <td id="T_04932_row0_col0" class="data row0 col0" >腾讯控股</td>
                        <td id="T_04932_row0_col1" class="data row0 col1" >41.65</td>
                        <td id="T_04932_row0_col2" class="data row0 col2" >10.98</td>
                        <td id="T_04932_row0_col3" class="data row0 col3" >15.43</td>
                        <td id="T_04932_row0_col4" class="data row0 col4" >24.13</td>
                        <td id="T_04932_row0_col5" class="data row0 col5" >28.29</td>
                        <td id="T_04932_row0_col6" class="data row0 col6" >26.65</td>
                        <td id="T_04932_row0_col7" class="data row0 col7" >5.52</td>
                        <td id="T_04932_row0_col8" class="data row0 col8" >33.31</td>
                        <td id="T_04932_row0_col9" class="data row0 col9" >33.18</td>
                        <td id="T_04932_row0_col10" class="data row0 col10" >20.72</td>
                        <td id="T_04932_row0_col11" class="data row0 col11" >21.25</td>
                        <td id="T_04932_row0_col12" class="data row0 col12" >2534.70</td>
                        <td id="T_04932_row0_col13" class="data row0 col13" >2875.86</td>
            </tr>
            <tr>
                        <th id="T_04932_level0_row1" class="row_heading level0 row1" >1810.HK</th>
                        <td id="T_04932_row1_col0" class="data row1 col0" >小米集团-W</td>
                        <td id="T_04932_row1_col1" class="data row1 col1" >51.11</td>
                        <td id="T_04932_row1_col2" class="data row1 col2" >13.70</td>
                        <td id="T_04932_row1_col3" class="data row1 col3" >0.20</td>
                        <td id="T_04932_row1_col4" class="data row1 col4" >20.56</td>
                        <td id="T_04932_row1_col5" class="data row1 col5" >-4.33</td>
                        <td id="T_04932_row1_col6" class="data row1 col6" >29.91</td>
                        <td id="T_04932_row1_col7" class="data row1 col7" >19.67</td>
                        <td id="T_04932_row1_col8" class="data row1 col8" >-18.05</td>
                        <td id="T_04932_row1_col9" class="data row1 col9" >116.99</td>
                        <td id="T_04932_row1_col10" class="data row1 col10" >-121.70</td>
                        <td id="T_04932_row1_col11" class="data row1 col11" >328.86</td>
                        <td id="T_04932_row1_col12" class="data row1 col12" >-2.26</td>
                        <td id="T_04932_row1_col13" class="data row1 col13" >0.24</td>
            </tr>
            <tr>
                        <th id="T_04932_level0_row2" class="row_heading level0 row2" >0981.HK</th>
                        <td id="T_04932_row2_col0" class="data row2 col0" >中芯国际</td>
                        <td id="T_04932_row2_col1" class="data row2 col1" >30.77</td>
                        <td id="T_04932_row2_col2" class="data row2 col2" >14.01</td>
                        <td id="T_04932_row2_col3" class="data row2 col3" >0.08</td>
                        <td id="T_04932_row2_col4" class="data row2 col4" >3.54</td>
                        <td id="T_04932_row2_col5" class="data row2 col5" >8.91</td>
                        <td id="T_04932_row2_col6" class="data row2 col6" >8.82</td>
                        <td id="T_04932_row2_col7" class="data row2 col7" >16.34</td>
                        <td id="T_04932_row2_col8" class="data row2 col8" >84.86</td>
                        <td id="T_04932_row2_col9" class="data row2 col9" >115.46</td>
                        <td id="T_04932_row2_col10" class="data row2 col10" >97.63</td>
                        <td id="T_04932_row2_col11" class="data row2 col11" >196.87</td>
                        <td id="T_04932_row2_col12" class="data row2 col12" >-148.30</td>
                        <td id="T_04932_row2_col13" class="data row2 col13" >23.10</td>
            </tr>
            <tr>
                        <th id="T_04932_level0_row3" class="row_heading level0 row3" >3888.HK</th>
                        <td id="T_04932_row3_col0" class="data row3 col0" >金山软件</td>
                        <td id="T_04932_row3_col1" class="data row3 col1" >19.45</td>
                        <td id="T_04932_row3_col2" class="data row3 col2" >28.51</td>
                        <td id="T_04932_row3_col3" class="data row3 col3" >0.75</td>
                        <td id="T_04932_row3_col4" class="data row3 col4" >14.75</td>
                        <td id="T_04932_row3_col5" class="data row3 col5" >53.14</td>
                        <td id="T_04932_row3_col6" class="data row3 col6" >5.33</td>
                        <td id="T_04932_row3_col7" class="data row3 col7" >28.01</td>
                        <td id="T_04932_row3_col8" class="data row3 col8" >-444.91</td>
                        <td id="T_04932_row3_col9" class="data row3 col9" >333.97</td>
                        <td id="T_04932_row3_col10" class="data row3 col10" >-240.00</td>
                        <td id="T_04932_row3_col11" class="data row3 col11" >283.31</td>
                        <td id="T_04932_row3_col12" class="data row3 col12" >-18.64</td>
                        <td id="T_04932_row3_col13" class="data row3 col13" >-1314.06</td>
            </tr>
            <tr>
                        <th id="T_04932_level0_row4" class="row_heading level0 row4" >3690.HK</th>
                        <td id="T_04932_row4_col0" class="data row4 col0" >美团-W</td>
                        <td id="T_04932_row4_col1" class="data row4 col1" >41.39</td>
                        <td id="T_04932_row4_col2" class="data row4 col2" >8.66</td>
                        <td id="T_04932_row4_col3" class="data row4 col3" >28.30</td>
                        <td id="T_04932_row4_col4" class="data row4 col4" >-19.90</td>
                        <td id="T_04932_row4_col5" class="data row4 col5" >-56.90</td>
                        <td id="T_04932_row4_col6" class="data row4 col6" >52.67</td>
                        <td id="T_04932_row4_col7" class="data row4 col7" >36.69</td>
                        <td id="T_04932_row4_col8" class="data row4 col8" >172.94</td>
                        <td id="T_04932_row4_col9" class="data row4 col9" >310.96</td>
                        <td id="T_04932_row4_col10" class="data row4 col10" >219.37</td>
                        <td id="T_04932_row4_col11" class="data row4 col11" >666.06</td>
                        <td id="T_04932_row4_col12" class="data row4 col12" >-1145.66</td>
                        <td id="T_04932_row4_col13" class="data row4 col13" >-7290.73</td>
            </tr>
            <tr>
                        <th id="T_04932_level0_row5" class="row_heading level0 row5" >2020.HK</th>
                        <td id="T_04932_row5_col0" class="data row5 col0" >安踏体育</td>
                        <td id="T_04932_row5_col1" class="data row5 col1" >50.21</td>
                        <td id="T_04932_row5_col2" class="data row5 col2" >10.63</td>
                        <td id="T_04932_row5_col3" class="data row5 col3" >0.00</td>
                        <td id="T_04932_row5_col4" class="data row5 col4" >24.16</td>
                        <td id="T_04932_row5_col5" class="data row5 col5" >16.45</td>
                        <td id="T_04932_row5_col6" class="data row5 col6" >29.94</td>
                        <td id="T_04932_row5_col7" class="data row5 col7" >21.96</td>
                        <td id="T_04932_row5_col8" class="data row5 col8" >19.91</td>
                        <td id="T_04932_row5_col9" class="data row5 col9" >20.23</td>
                        <td id="T_04932_row5_col10" class="data row5 col10" >41.31</td>
                        <td id="T_04932_row5_col11" class="data row5 col11" >39.73</td>
                        <td id="T_04932_row5_col12" class="data row5 col12" >171.73</td>
                        <td id="T_04932_row5_col13" class="data row5 col13" >93.41</td>
            </tr>
            <tr>
                        <th id="T_04932_level0_row6" class="row_heading level0 row6" >3613.HK</th>
                        <td id="T_04932_row6_col0" class="data row6 col0" >同仁堂国药</td>
                        <td id="T_04932_row6_col1" class="data row6 col1" >8.41</td>
                        <td id="T_04932_row6_col2" class="data row6 col2" >41.62</td>
                        <td id="T_04932_row6_col3" class="data row6 col3" >1.64</td>
                        <td id="T_04932_row6_col4" class="data row6 col4" >19.63</td>
                        <td id="T_04932_row6_col5" class="data row6 col5" >39.28</td>
                        <td id="T_04932_row6_col6" class="data row6 col6" >2.01</td>
                        <td id="T_04932_row6_col7" class="data row6 col7" >15.28</td>
                        <td id="T_04932_row6_col8" class="data row6 col8" >3.94</td>
                        <td id="T_04932_row6_col9" class="data row6 col9" >12.66</td>
                        <td id="T_04932_row6_col10" class="data row6 col10" >-19.44</td>
                        <td id="T_04932_row6_col11" class="data row6 col11" >53.86</td>
                        <td id="T_04932_row6_col12" class="data row6 col12" >2.81</td>
                        <td id="T_04932_row6_col13" class="data row6 col13" >7.67</td>
            </tr>
            <tr>
                        <th id="T_04932_level0_row7" class="row_heading level0 row7" >1024.HK</th>
                        <td id="T_04932_row7_col0" class="data row7 col0" >快手-W</td>
                        <td id="T_04932_row7_col1" class="data row7 col1" >406.92</td>
                        <td id="T_04932_row7_col2" class="data row7 col2" >6.89</td>
                        <td id="T_04932_row7_col3" class="data row7 col3" >-0.52</td>
                        <td id="T_04932_row7_col4" class="data row7 col4" >58.33</td>
                        <td id="T_04932_row7_col5" class="data row7 col5" >-137.56</td>
                        <td id="T_04932_row7_col6" class="data row7 col6" >95.46</td>
                        <td id="T_04932_row7_col7" class="data row7 col7" >46.65</td>
                        <td id="T_04932_row7_col8" class="data row7 col8" >171.21</td>
                        <td id="T_04932_row7_col9" class="data row7 col9" >283.23</td>
                        <td id="T_04932_row7_col10" class="data row7 col10" >-317.01</td>
                        <td id="T_04932_row7_col11" class="data row7 col11" >264.59</td>
                        <td id="T_04932_row7_col12" class="data row7 col12" >-67.06</td>
                        <td id="T_04932_row7_col13" class="data row7 col13" >-9474.94</td>
            </tr>
            <tr>
                        <th id="T_04932_level0_row8" class="row_heading level0 row8" >2319.HK</th>
                        <td id="T_04932_row8_col0" class="data row8 col0" >蒙牛乳业</td>
                        <td id="T_04932_row8_col1" class="data row8 col1" >53.53</td>
                        <td id="T_04932_row8_col2" class="data row8 col2" >5.72</td>
                        <td id="T_04932_row8_col3" class="data row8 col3" >14.81</td>
                        <td id="T_04932_row8_col4" class="data row8 col4" >11.48</td>
                        <td id="T_04932_row8_col5" class="data row8 col5" >4.41</td>
                        <td id="T_04932_row8_col6" class="data row8 col6" >8.48</td>
                        <td id="T_04932_row8_col7" class="data row8 col7" >10.63</td>
                        <td id="T_04932_row8_col8" class="data row8 col8" >23.12</td>
                        <td id="T_04932_row8_col9" class="data row8 col9" >32.99</td>
                        <td id="T_04932_row8_col10" class="data row8 col10" >-26.64</td>
                        <td id="T_04932_row8_col11" class="data row8 col11" >17.18</td>
                        <td id="T_04932_row8_col12" class="data row8 col12" >12.46</td>
                        <td id="T_04932_row8_col13" class="data row8 col13" >72.37</td>
            </tr>
            <tr>
                        <th id="T_04932_level0_row9" class="row_heading level0 row9" >2331.HK</th>
                        <td id="T_04932_row9_col0" class="data row9 col0" >李宁</td>
                        <td id="T_04932_row9_col1" class="data row9 col1" >40.46</td>
                        <td id="T_04932_row9_col2" class="data row9 col2" >5.01</td>
                        <td id="T_04932_row9_col3" class="data row9 col3" >1.19</td>
                        <td id="T_04932_row9_col4" class="data row9 col4" >15.76</td>
                        <td id="T_04932_row9_col5" class="data row9 col5" >8.79</td>
                        <td id="T_04932_row9_col6" class="data row9 col6" >18.21</td>
                        <td id="T_04932_row9_col7" class="data row9 col7" >13.86</td>
                        <td id="T_04932_row9_col8" class="data row9 col8" >53.91</td>
                        <td id="T_04932_row9_col9" class="data row9 col9" >49.88</td>
                        <td id="T_04932_row9_col10" class="data row9 col10" >59.22</td>
                        <td id="T_04932_row9_col11" class="data row9 col11" >91.58</td>
                        <td id="T_04932_row9_col12" class="data row9 col12" >82.11</td>
                        <td id="T_04932_row9_col13" class="data row9 col13" >47.64</td>
            </tr>
            <tr>
                        <th id="T_04932_level0_row10" class="row_heading level0 row10" >2269.HK</th>
                        <td id="T_04932_row10_col0" class="data row10 col0" >药明生物</td>
                        <td id="T_04932_row10_col1" class="data row10 col1" >27.84</td>
                        <td id="T_04932_row10_col2" class="data row10 col2" >49.35</td>
                        <td id="T_04932_row10_col3" class="data row10 col3" >0.90</td>
                        <td id="T_04932_row10_col4" class="data row10 col4" >7.58</td>
                        <td id="T_04932_row10_col5" class="data row10 col5" >24.01</td>
                        <td id="T_04932_row10_col6" class="data row10 col6" >51.54</td>
                        <td id="T_04932_row10_col7" class="data row10 col7" >9.24</td>
                        <td id="T_04932_row10_col8" class="data row10 col8" >92.32</td>
                        <td id="T_04932_row10_col9" class="data row10 col9" >49.70</td>
                        <td id="T_04932_row10_col10" class="data row10 col10" >146.45</td>
                        <td id="T_04932_row10_col11" class="data row10 col11" >86.69</td>
                        <td id="T_04932_row10_col12" class="data row10 col12" >-298.05</td>
                        <td id="T_04932_row10_col13" class="data row10 col13" >73.54</td>
            </tr>
            <tr>
                        <th id="T_04932_level0_row11" class="row_heading level0 row11" >0285.HK</th>
                        <td id="T_04932_row11_col0" class="data row11 col0" >比亚迪电子</td>
                        <td id="T_04932_row11_col1" class="data row11 col1" >41.35</td>
                        <td id="T_04932_row11_col2" class="data row11 col2" >19.80</td>
                        <td id="T_04932_row11_col3" class="data row11 col3" >0.00</td>
                        <td id="T_04932_row11_col4" class="data row11 col4" >16.47</td>
                        <td id="T_04932_row11_col5" class="data row11 col5" >5.61</td>
                        <td id="T_04932_row11_col6" class="data row11 col6" >24.31</td>
                        <td id="T_04932_row11_col7" class="data row11 col7" >16.56</td>
                        <td id="T_04932_row11_col8" class="data row11 col8" >66.09</td>
                        <td id="T_04932_row11_col9" class="data row11 col9" >151.24</td>
                        <td id="T_04932_row11_col10" class="data row11 col10" >-353.88</td>
                        <td id="T_04932_row11_col11" class="data row11 col11" >344.03</td>
                        <td id="T_04932_row11_col12" class="data row11 col12" >-5.33</td>
                        <td id="T_04932_row11_col13" class="data row11 col13" >158.30</td>
            </tr>
            <tr>
                        <th id="T_04932_level0_row12" class="row_heading level0 row12" >1068.HK</th>
                        <td id="T_04932_row12_col0" class="data row12 col0" >雨润食品</td>
                        <td id="T_04932_row12_col1" class="data row12 col1" >135.43</td>
                        <td id="T_04932_row12_col2" class="data row12 col2" >12.35</td>
                        <td id="T_04932_row12_col3" class="data row12 col3" >0.00</td>
                        <td id="T_04932_row12_col4" class="data row12 col4" >38.19</td>
                        <td id="T_04932_row12_col5" class="data row12 col5" >-23.16</td>
                        <td id="T_04932_row12_col6" class="data row12 col6" >8.40</td>
                        <td id="T_04932_row12_col7" class="data row12 col7" >10.65</td>
                        <td id="T_04932_row12_col8" class="data row12 col8" >27.51</td>
                        <td id="T_04932_row12_col9" class="data row12 col9" >105.95</td>
                        <td id="T_04932_row12_col10" class="data row12 col10" >12.50</td>
                        <td id="T_04932_row12_col11" class="data row12 col11" >149.90</td>
                        <td id="T_04932_row12_col12" class="data row12 col12" >-2.61</td>
                        <td id="T_04932_row12_col13" class="data row12 col13" >-79.37</td>
            </tr>
            <tr>
                        <th id="T_04932_level0_row13" class="row_heading level0 row13" >8083.HK</th>
                        <td id="T_04932_row13_col0" class="data row13 col0" >中国有赞</td>
                        <td id="T_04932_row13_col1" class="data row13 col1" >62.09</td>
                        <td id="T_04932_row13_col2" class="data row13 col2" >3.54</td>
                        <td id="T_04932_row13_col3" class="data row13 col3" >50.88</td>
                        <td id="T_04932_row13_col4" class="data row13 col4" >-11.46</td>
                        <td id="T_04932_row13_col5" class="data row13 col5" >-48.60</td>
                        <td id="T_04932_row13_col6" class="data row13 col6" >112.40</td>
                        <td id="T_04932_row13_col7" class="data row13 col7" >64.15</td>
                        <td id="T_04932_row13_col8" class="data row13 col8" >90.51</td>
                        <td id="T_04932_row13_col9" class="data row13 col9" >173.65</td>
                        <td id="T_04932_row13_col10" class="data row13 col10" >81.34</td>
                        <td id="T_04932_row13_col11" class="data row13 col11" >278.29</td>
                        <td id="T_04932_row13_col12" class="data row13 col12" >-30.92</td>
                        <td id="T_04932_row13_col13" class="data row13 col13" >-28.54</td>
            </tr>
            <tr>
                        <th id="T_04932_level0_row14" class="row_heading level0 row14" >9992.HK</th>
                        <td id="T_04932_row14_col0" class="data row14 col0" >泡泡玛特</td>
                        <td id="T_04932_row14_col1" class="data row14 col1" >12.05</td>
                        <td id="T_04932_row14_col2" class="data row14 col2" >3.40</td>
                        <td id="T_04932_row14_col3" class="data row14 col3" >0.00</td>
                        <td id="T_04932_row14_col4" class="data row14 col4" >33.03</td>
                        <td id="T_04932_row14_col5" class="data row14 col5" >16.99</td>
                        <td id="T_04932_row14_col6" class="data row14 col6" >167.33</td>
                        <td id="T_04932_row14_col7" class="data row14 col7" >102.21</td>
                        <td id="T_04932_row14_col8" class="data row14 col8" >2204.10</td>
                        <td id="T_04932_row14_col9" class="data row14 col9" >3501.82</td>
                        <td id="T_04932_row14_col10" class="data row14 col10" >1216.11</td>
                        <td id="T_04932_row14_col11" class="data row14 col11" >1919.33</td>
                        <td id="T_04932_row14_col12" class="data row14 col12" >6613.01</td>
                        <td id="T_04932_row14_col13" class="data row14 col13" >35600.74</td>
            </tr>
            <tr>
                        <th id="T_04932_level0_row15" class="row_heading level0 row15" >2298.HK</th>
                        <td id="T_04932_row15_col0" class="data row15 col0" >都市丽人</td>
                        <td id="T_04932_row15_col1" class="data row15 col1" >46.44</td>
                        <td id="T_04932_row15_col2" class="data row15 col2" >9.88</td>
                        <td id="T_04932_row15_col3" class="data row15 col3" >0.12</td>
                        <td id="T_04932_row15_col4" class="data row15 col4" >-9.33</td>
                        <td id="T_04932_row15_col5" class="data row15 col5" >-5.31</td>
                        <td id="T_04932_row15_col6" class="data row15 col6" >-10.94</td>
                        <td id="T_04932_row15_col7" class="data row15 col7" >20.20</td>
                        <td id="T_04932_row15_col8" class="data row15 col8" >-171.57</td>
                        <td id="T_04932_row15_col9" class="data row15 col9" >241.55</td>
                        <td id="T_04932_row15_col10" class="data row15 col10" >153.46</td>
                        <td id="T_04932_row15_col11" class="data row15 col11" >539.55</td>
                        <td id="T_04932_row15_col12" class="data row15 col12" >7.95</td>
                        <td id="T_04932_row15_col13" class="data row15 col13" >0.76</td>
            </tr>
            <tr>
                        <th id="T_04932_level0_row16" class="row_heading level0 row16" >0268.HK</th>
                        <td id="T_04932_row16_col0" class="data row16 col0" >金蝶国际</td>
                        <td id="T_04932_row16_col1" class="data row16 col1" >25.77</td>
                        <td id="T_04932_row16_col2" class="data row16 col2" >30.00</td>
                        <td id="T_04932_row16_col3" class="data row16 col3" >1.63</td>
                        <td id="T_04932_row16_col4" class="data row16 col4" >4.30</td>
                        <td id="T_04932_row16_col5" class="data row16 col5" >7.33</td>
                        <td id="T_04932_row16_col6" class="data row16 col6" >13.75</td>
                        <td id="T_04932_row16_col7" class="data row16 col7" >11.25</td>
                        <td id="T_04932_row16_col8" class="data row16 col8" >-55.57</td>
                        <td id="T_04932_row16_col9" class="data row16 col9" >118.39</td>
                        <td id="T_04932_row16_col10" class="data row16 col10" >-12.84</td>
                        <td id="T_04932_row16_col11" class="data row16 col11" >35.18</td>
                        <td id="T_04932_row16_col12" class="data row16 col12" >6.59</td>
                        <td id="T_04932_row16_col13" class="data row16 col13" >0.30</td>
            </tr>
            <tr>
                        <th id="T_04932_level0_row17" class="row_heading level0 row17" >1347.HK</th>
                        <td id="T_04932_row17_col0" class="data row17 col0" >华虹半导体</td>
                        <td id="T_04932_row17_col1" class="data row17 col1" >26.58</td>
                        <td id="T_04932_row17_col2" class="data row17 col2" >13.98</td>
                        <td id="T_04932_row17_col3" class="data row17 col3" >0.00</td>
                        <td id="T_04932_row17_col4" class="data row17 col4" >7.06</td>
                        <td id="T_04932_row17_col5" class="data row17 col5" >16.35</td>
                        <td id="T_04932_row17_col6" class="data row17 col6" >6.15</td>
                        <td id="T_04932_row17_col7" class="data row17 col7" >7.89</td>
                        <td id="T_04932_row17_col8" class="data row17 col8" >-8.01</td>
                        <td id="T_04932_row17_col9" class="data row17 col9" >32.53</td>
                        <td id="T_04932_row17_col10" class="data row17 col10" >-619.72</td>
                        <td id="T_04932_row17_col11" class="data row17 col11" >1026.21</td>
                        <td id="T_04932_row17_col12" class="data row17 col12" >527.50</td>
                        <td id="T_04932_row17_col13" class="data row17 col13" >1.49</td>
            </tr>
            <tr>
                        <th id="T_04932_level0_row18" class="row_heading level0 row18" >6055.HK</th>
                        <td id="T_04932_row18_col0" class="data row18 col0" >中烟香港</td>
                        <td id="T_04932_row18_col1" class="data row18 col1" >56.43</td>
                        <td id="T_04932_row18_col2" class="data row18 col2" >9.93</td>
                        <td id="T_04932_row18_col3" class="data row18 col3" >0.00</td>
                        <td id="T_04932_row18_col4" class="data row18 col4" >21.51</td>
                        <td id="T_04932_row18_col5" class="data row18 col5" >3.60</td>
                        <td id="T_04932_row18_col6" class="data row18 col6" >-14.50</td>
                        <td id="T_04932_row18_col7" class="data row18 col7" >44.61</td>
                        <td id="T_04932_row18_col8" class="data row18 col8" >-23.96</td>
                        <td id="T_04932_row18_col9" class="data row18 col9" >46.53</td>
                        <td id="T_04932_row18_col10" class="data row18 col10" >-17.49</td>
                        <td id="T_04932_row18_col11" class="data row18 col11" >115.64</td>
                        <td id="T_04932_row18_col12" class="data row18 col12" >2.69</td>
                        <td id="T_04932_row18_col13" class="data row18 col13" >1.54</td>
            </tr>
            <tr>
                        <th id="T_04932_level0_row19" class="row_heading level0 row19" >2359.HK</th>
                        <td id="T_04932_row19_col0" class="data row19 col0" >药明康德</td>
                        <td id="T_04932_row19_col1" class="data row19 col1" >29.32</td>
                        <td id="T_04932_row19_col2" class="data row19 col2" >25.62</td>
                        <td id="T_04932_row19_col3" class="data row19 col3" >4.28</td>
                        <td id="T_04932_row19_col4" class="data row19 col4" >12.99</td>
                        <td id="T_04932_row19_col5" class="data row19 col5" >17.91</td>
                        <td id="T_04932_row19_col6" class="data row19 col6" >28.72</td>
                        <td id="T_04932_row19_col7" class="data row19 col7" >5.05</td>
                        <td id="T_04932_row19_col8" class="data row19 col8" >41.96</td>
                        <td id="T_04932_row19_col9" class="data row19 col9" >53.33</td>
                        <td id="T_04932_row19_col10" class="data row19 col10" >-86.40</td>
                        <td id="T_04932_row19_col11" class="data row19 col11" >204.47</td>
                        <td id="T_04932_row19_col12" class="data row19 col12" >0.05</td>
                        <td id="T_04932_row19_col13" class="data row19 col13" >70.83</td>
            </tr>
            <tr>
                        <th id="T_04932_level0_row20" class="row_heading level0 row20" >9626.HK</th>
                        <td id="T_04932_row20_col0" class="data row20 col0" >哔哩哔哩-SW</td>
                        <td id="T_04932_row20_col1" class="data row20 col1" >67.39</td>
                        <td id="T_04932_row20_col2" class="data row20 col2" >11.77</td>
                        <td id="T_04932_row20_col3" class="data row20 col3" >17.05</td>
                        <td id="T_04932_row20_col4" class="data row20 col4" >-9.33</td>
                        <td id="T_04932_row20_col5" class="data row20 col5" >-20.55</td>
                        <td id="T_04932_row20_col6" class="data row20 col6" >69.49</td>
                        <td id="T_04932_row20_col7" class="data row20 col7" >6.72</td>
                        <td id="T_04932_row20_col8" class="data row20 col8" >83.54</td>
                        <td id="T_04932_row20_col9" class="data row20 col9" >66.70</td>
                        <td id="T_04932_row20_col10" class="data row20 col10" >-110.94</td>
                        <td id="T_04932_row20_col11" class="data row20 col11" >144.16</td>
                        <td id="T_04932_row20_col12" class="data row20 col12" >-0.02</td>
                        <td id="T_04932_row20_col13" class="data row20 col13" >-98.26</td>
            </tr>
            <tr>
                        <th id="T_04932_level0_row21" class="row_heading level0 row21" >3908.HK</th>
                        <td id="T_04932_row21_col0" class="data row21 col0" >中金公司</td>
                        <td id="T_04932_row21_col1" class="data row21 col1" >86.23</td>
                        <td id="T_04932_row21_col2" class="data row21 col2" >279.30</td>
                        <td id="T_04932_row21_col3" class="data row21 col3" >2.21</td>
                        <td id="T_04932_row21_col4" class="data row21 col4" >8.66</td>
                        <td id="T_04932_row21_col5" class="data row21 col5" >25.33</td>
                        <td id="T_04932_row21_col6" class="data row21 col6" >34.26</td>
                        <td id="T_04932_row21_col7" class="data row21 col7" >29.68</td>
                        <td id="T_04932_row21_col8" class="data row21 col8" >39.22</td>
                        <td id="T_04932_row21_col9" class="data row21 col9" >26.80</td>
                        <td id="T_04932_row21_col10" class="data row21 col10" >-159.43</td>
                        <td id="T_04932_row21_col11" class="data row21 col11" >194.62</td>
                        <td id="T_04932_row21_col12" class="data row21 col12" >52.21</td>
                        <td id="T_04932_row21_col13" class="data row21 col13" >142.85</td>
            </tr>
    </tbody></table>




<script>
$('table').addClass('table table-striped table-hover  table-sm ')
$('thead').addClass('thead-dark')
</script>