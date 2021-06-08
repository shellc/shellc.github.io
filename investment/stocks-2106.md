---
layout: default
title: 选股(2106)
---


<style>
table {font-size: 12px;}
</style>
# 选股

Update: 20210609

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

1. 负债率 <= 50%
2. 应收比 < 20%
3. 商誉比 < 20%
4. ROE >= 20%
5. 利润率 >= 20%
6. 收入增长 >= 15% 且 盈利增长 >= 15%




<style  type="text/css" >
#T_8c52d_row0_col0,#T_8c52d_row0_col1,#T_8c52d_row0_col2,#T_8c52d_row0_col3,#T_8c52d_row0_col4,#T_8c52d_row0_col5,#T_8c52d_row0_col6,#T_8c52d_row0_col7,#T_8c52d_row0_col8,#T_8c52d_row0_col9,#T_8c52d_row0_col10,#T_8c52d_row0_col11,#T_8c52d_row0_col12,#T_8c52d_row1_col0,#T_8c52d_row1_col1,#T_8c52d_row1_col2,#T_8c52d_row1_col3,#T_8c52d_row1_col4,#T_8c52d_row1_col5,#T_8c52d_row1_col6,#T_8c52d_row1_col7,#T_8c52d_row1_col9,#T_8c52d_row1_col10,#T_8c52d_row1_col11,#T_8c52d_row1_col12,#T_8c52d_row2_col0,#T_8c52d_row2_col1,#T_8c52d_row2_col2,#T_8c52d_row2_col3,#T_8c52d_row2_col4,#T_8c52d_row2_col5,#T_8c52d_row2_col6,#T_8c52d_row2_col7,#T_8c52d_row2_col8,#T_8c52d_row2_col9,#T_8c52d_row2_col10,#T_8c52d_row2_col11,#T_8c52d_row2_col12,#T_8c52d_row3_col0,#T_8c52d_row3_col1,#T_8c52d_row3_col2,#T_8c52d_row3_col3,#T_8c52d_row3_col4,#T_8c52d_row3_col5,#T_8c52d_row3_col6,#T_8c52d_row3_col8,#T_8c52d_row3_col9,#T_8c52d_row3_col10,#T_8c52d_row3_col11,#T_8c52d_row3_col12,#T_8c52d_row4_col0,#T_8c52d_row4_col1,#T_8c52d_row4_col2,#T_8c52d_row4_col3,#T_8c52d_row4_col4,#T_8c52d_row4_col5,#T_8c52d_row4_col6,#T_8c52d_row4_col8,#T_8c52d_row4_col9,#T_8c52d_row4_col10,#T_8c52d_row4_col11,#T_8c52d_row4_col12,#T_8c52d_row5_col0,#T_8c52d_row5_col1,#T_8c52d_row5_col2,#T_8c52d_row5_col3,#T_8c52d_row5_col4,#T_8c52d_row5_col5,#T_8c52d_row5_col6,#T_8c52d_row5_col8,#T_8c52d_row5_col9,#T_8c52d_row5_col10,#T_8c52d_row5_col11,#T_8c52d_row5_col12,#T_8c52d_row6_col0,#T_8c52d_row6_col1,#T_8c52d_row6_col2,#T_8c52d_row6_col3,#T_8c52d_row6_col4,#T_8c52d_row6_col5,#T_8c52d_row6_col6,#T_8c52d_row6_col7,#T_8c52d_row6_col8,#T_8c52d_row6_col9,#T_8c52d_row6_col10,#T_8c52d_row6_col11,#T_8c52d_row6_col12,#T_8c52d_row7_col0,#T_8c52d_row7_col1,#T_8c52d_row7_col2,#T_8c52d_row7_col3,#T_8c52d_row7_col4,#T_8c52d_row7_col5,#T_8c52d_row7_col6,#T_8c52d_row7_col7,#T_8c52d_row7_col8,#T_8c52d_row7_col9,#T_8c52d_row7_col10,#T_8c52d_row7_col11,#T_8c52d_row7_col12,#T_8c52d_row8_col0,#T_8c52d_row8_col1,#T_8c52d_row8_col2,#T_8c52d_row8_col3,#T_8c52d_row8_col4,#T_8c52d_row8_col5,#T_8c52d_row8_col6,#T_8c52d_row8_col7,#T_8c52d_row8_col8,#T_8c52d_row8_col9,#T_8c52d_row8_col10,#T_8c52d_row8_col11,#T_8c52d_row8_col12,#T_8c52d_row9_col0,#T_8c52d_row9_col1,#T_8c52d_row9_col2,#T_8c52d_row9_col3,#T_8c52d_row9_col4,#T_8c52d_row9_col5,#T_8c52d_row9_col6,#T_8c52d_row9_col7,#T_8c52d_row9_col8,#T_8c52d_row9_col9,#T_8c52d_row9_col10,#T_8c52d_row9_col11,#T_8c52d_row9_col12,#T_8c52d_row10_col0,#T_8c52d_row10_col1,#T_8c52d_row10_col2,#T_8c52d_row10_col3,#T_8c52d_row10_col4,#T_8c52d_row10_col5,#T_8c52d_row10_col6,#T_8c52d_row10_col7,#T_8c52d_row10_col8,#T_8c52d_row10_col9,#T_8c52d_row10_col10,#T_8c52d_row10_col11,#T_8c52d_row10_col12,#T_8c52d_row11_col0,#T_8c52d_row11_col1,#T_8c52d_row11_col2,#T_8c52d_row11_col3,#T_8c52d_row11_col4,#T_8c52d_row11_col5,#T_8c52d_row11_col6,#T_8c52d_row11_col7,#T_8c52d_row11_col8,#T_8c52d_row11_col9,#T_8c52d_row11_col10,#T_8c52d_row11_col11,#T_8c52d_row11_col12,#T_8c52d_row12_col0,#T_8c52d_row12_col1,#T_8c52d_row12_col2,#T_8c52d_row12_col3,#T_8c52d_row12_col4,#T_8c52d_row12_col5,#T_8c52d_row12_col6,#T_8c52d_row12_col7,#T_8c52d_row12_col8,#T_8c52d_row12_col9,#T_8c52d_row12_col10,#T_8c52d_row12_col11,#T_8c52d_row12_col12,#T_8c52d_row13_col0,#T_8c52d_row13_col1,#T_8c52d_row13_col2,#T_8c52d_row13_col3,#T_8c52d_row13_col4,#T_8c52d_row13_col5,#T_8c52d_row13_col6,#T_8c52d_row13_col7,#T_8c52d_row13_col9,#T_8c52d_row13_col10,#T_8c52d_row13_col11,#T_8c52d_row13_col12,#T_8c52d_row14_col0,#T_8c52d_row14_col1,#T_8c52d_row14_col2,#T_8c52d_row14_col3,#T_8c52d_row14_col4,#T_8c52d_row14_col5,#T_8c52d_row14_col6,#T_8c52d_row14_col7,#T_8c52d_row14_col8,#T_8c52d_row14_col9,#T_8c52d_row14_col10,#T_8c52d_row14_col11,#T_8c52d_row14_col12,#T_8c52d_row15_col0,#T_8c52d_row15_col1,#T_8c52d_row15_col2,#T_8c52d_row15_col3,#T_8c52d_row15_col4,#T_8c52d_row15_col5,#T_8c52d_row15_col6,#T_8c52d_row15_col7,#T_8c52d_row15_col9,#T_8c52d_row15_col10,#T_8c52d_row15_col11,#T_8c52d_row15_col12,#T_8c52d_row16_col0,#T_8c52d_row16_col1,#T_8c52d_row16_col2,#T_8c52d_row16_col3,#T_8c52d_row16_col4,#T_8c52d_row16_col5,#T_8c52d_row16_col6,#T_8c52d_row16_col7,#T_8c52d_row16_col8,#T_8c52d_row16_col9,#T_8c52d_row16_col10,#T_8c52d_row16_col11,#T_8c52d_row16_col12,#T_8c52d_row17_col0,#T_8c52d_row17_col1,#T_8c52d_row17_col2,#T_8c52d_row17_col3,#T_8c52d_row17_col4,#T_8c52d_row17_col5,#T_8c52d_row17_col6,#T_8c52d_row17_col7,#T_8c52d_row17_col8,#T_8c52d_row17_col9,#T_8c52d_row17_col10,#T_8c52d_row17_col11,#T_8c52d_row17_col12,#T_8c52d_row18_col0,#T_8c52d_row18_col1,#T_8c52d_row18_col2,#T_8c52d_row18_col3,#T_8c52d_row18_col4,#T_8c52d_row18_col5,#T_8c52d_row18_col6,#T_8c52d_row18_col7,#T_8c52d_row18_col8,#T_8c52d_row18_col9,#T_8c52d_row18_col10,#T_8c52d_row18_col11,#T_8c52d_row18_col12,#T_8c52d_row19_col0,#T_8c52d_row19_col1,#T_8c52d_row19_col2,#T_8c52d_row19_col3,#T_8c52d_row19_col4,#T_8c52d_row19_col5,#T_8c52d_row19_col6,#T_8c52d_row19_col7,#T_8c52d_row19_col8,#T_8c52d_row19_col9,#T_8c52d_row19_col10,#T_8c52d_row19_col11,#T_8c52d_row19_col12,#T_8c52d_row20_col0,#T_8c52d_row20_col1,#T_8c52d_row20_col2,#T_8c52d_row20_col3,#T_8c52d_row20_col4,#T_8c52d_row20_col5,#T_8c52d_row20_col6,#T_8c52d_row20_col7,#T_8c52d_row20_col9,#T_8c52d_row20_col10,#T_8c52d_row20_col11,#T_8c52d_row20_col12,#T_8c52d_row21_col0,#T_8c52d_row21_col1,#T_8c52d_row21_col2,#T_8c52d_row21_col3,#T_8c52d_row21_col4,#T_8c52d_row21_col5,#T_8c52d_row21_col6,#T_8c52d_row21_col7,#T_8c52d_row21_col8,#T_8c52d_row21_col9,#T_8c52d_row21_col10,#T_8c52d_row21_col11,#T_8c52d_row21_col12,#T_8c52d_row22_col0,#T_8c52d_row22_col1,#T_8c52d_row22_col2,#T_8c52d_row22_col3,#T_8c52d_row22_col4,#T_8c52d_row22_col5,#T_8c52d_row22_col6,#T_8c52d_row22_col7,#T_8c52d_row22_col8,#T_8c52d_row22_col9,#T_8c52d_row22_col10,#T_8c52d_row22_col11,#T_8c52d_row22_col12{
            color:  black;
        }#T_8c52d_row1_col8,#T_8c52d_row3_col7,#T_8c52d_row4_col7,#T_8c52d_row5_col7,#T_8c52d_row13_col8,#T_8c52d_row15_col8,#T_8c52d_row20_col8{
            color:  red;
        }</style><table id="T_8c52d_" ><thead>    <tr>        <th class="blank level0" ></th>        <th class="col_heading level0 col0" >名称</th>        <th class="col_heading level0 col1" >负债率</th>        <th class="col_heading level0 col2" >ROE</th>        <th class="col_heading level0 col3" >利润率</th>        <th class="col_heading level0 col4" >收入增长</th>        <th class="col_heading level0 col5" >收入增长TTM</th>        <th class="col_heading level0 col6" >盈利增长</th>        <th class="col_heading level0 col7" >盈利增长TTM</th>        <th class="col_heading level0 col8" >FCF增长</th>        <th class="col_heading level0 col9" >PE</th>        <th class="col_heading level0 col10" >PEm</th>        <th class="col_heading level0 col11" >PEG</th>        <th class="col_heading level0 col12" >季报日期</th>    </tr>    <tr>        <th class="index_name level0" >Symbol</th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>    </tr></thead><tbody>
                <tr>
                        <th id="T_8c52d_level0_row0" class="row_heading level0 row0" >002714.SZ</th>
                        <td id="T_8c52d_row0_col0" class="data row0 col0" >牧原股份</td>
                        <td id="T_8c52d_row0_col1" class="data row0 col1" >46.09</td>
                        <td id="T_8c52d_row0_col2" class="data row0 col2" >28.10</td>
                        <td id="T_8c52d_row0_col3" class="data row0 col3" >26.61</td>
                        <td id="T_8c52d_row0_col4" class="data row0 col4" >87.55</td>
                        <td id="T_8c52d_row0_col5" class="data row0 col5" >21.47</td>
                        <td id="T_8c52d_row0_col6" class="data row0 col6" >448.77</td>
                        <td id="T_8c52d_row0_col7" class="data row0 col7" >10.32</td>
                        <td id="T_8c52d_row0_col8" class="data row0 col8" >199.27</td>
                        <td id="T_8c52d_row0_col9" class="data row0 col9" >8.29</td>
                        <td id="T_8c52d_row0_col10" class="data row0 col10" >27.97</td>
                        <td id="T_8c52d_row0_col11" class="data row0 col11" >0.06</td>
                        <td id="T_8c52d_row0_col12" class="data row0 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_8c52d_level0_row1" class="row_heading level0 row1" >002932.SZ</th>
                        <td id="T_8c52d_row1_col0" class="data row1 col0" >明德生物</td>
                        <td id="T_8c52d_row1_col1" class="data row1 col1" >21.85</td>
                        <td id="T_8c52d_row1_col2" class="data row1 col2" >21.76</td>
                        <td id="T_8c52d_row1_col3" class="data row1 col3" >36.58</td>
                        <td id="T_8c52d_row1_col4" class="data row1 col4" >146.32</td>
                        <td id="T_8c52d_row1_col5" class="data row1 col5" >429.43</td>
                        <td id="T_8c52d_row1_col6" class="data row1 col6" >330.21</td>
                        <td id="T_8c52d_row1_col7" class="data row1 col7" >1,029.24</td>
                        <td id="T_8c52d_row1_col8" class="data row1 col8" >-1,108.82</td>
                        <td id="T_8c52d_row1_col9" class="data row1 col9" >13.56</td>
                        <td id="T_8c52d_row1_col10" class="data row1 col10" >40.98</td>
                        <td id="T_8c52d_row1_col11" class="data row1 col11" >0.12</td>
                        <td id="T_8c52d_row1_col12" class="data row1 col12" >2020-12-31</td>
            </tr>
            <tr>
                        <th id="T_8c52d_level0_row2" class="row_heading level0 row2" >600585.SS</th>
                        <td id="T_8c52d_row2_col0" class="data row2 col0" >海螺水泥</td>
                        <td id="T_8c52d_row2_col1" class="data row2 col1" >16.30</td>
                        <td id="T_8c52d_row2_col2" class="data row2 col2" >22.59</td>
                        <td id="T_8c52d_row2_col3" class="data row2 col3" >21.40</td>
                        <td id="T_8c52d_row2_col4" class="data row2 col4" >35.01</td>
                        <td id="T_8c52d_row2_col5" class="data row2 col5" >6.37</td>
                        <td id="T_8c52d_row2_col6" class="data row2 col6" >35.10</td>
                        <td id="T_8c52d_row2_col7" class="data row2 col7" >2.55</td>
                        <td id="T_8c52d_row2_col8" class="data row2 col8" >36.04</td>
                        <td id="T_8c52d_row2_col9" class="data row2 col9" >7.10</td>
                        <td id="T_8c52d_row2_col10" class="data row2 col10" >8.49</td>
                        <td id="T_8c52d_row2_col11" class="data row2 col11" >0.24</td>
                        <td id="T_8c52d_row2_col12" class="data row2 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_8c52d_level0_row3" class="row_heading level0 row3" >603360.SS</th>
                        <td id="T_8c52d_row3_col0" class="data row3 col0" >百傲化学</td>
                        <td id="T_8c52d_row3_col1" class="data row3 col1" >30.87</td>
                        <td id="T_8c52d_row3_col2" class="data row3 col2" >21.22</td>
                        <td id="T_8c52d_row3_col3" class="data row3 col3" >29.17</td>
                        <td id="T_8c52d_row3_col4" class="data row3 col4" >26.58</td>
                        <td id="T_8c52d_row3_col5" class="data row3 col5" >2.50</td>
                        <td id="T_8c52d_row3_col6" class="data row3 col6" >42.80</td>
                        <td id="T_8c52d_row3_col7" class="data row3 col7" >-17.19</td>
                        <td id="T_8c52d_row3_col8" class="data row3 col8" >73.49</td>
                        <td id="T_8c52d_row3_col9" class="data row3 col9" >19.76</td>
                        <td id="T_8c52d_row3_col10" class="data row3 col10" >18.90</td>
                        <td id="T_8c52d_row3_col11" class="data row3 col11" >0.44</td>
                        <td id="T_8c52d_row3_col12" class="data row3 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_8c52d_level0_row4" class="row_heading level0 row4" >300771.SZ</th>
                        <td id="T_8c52d_row4_col0" class="data row4 col0" >智莱科技</td>
                        <td id="T_8c52d_row4_col1" class="data row4 col1" >12.01</td>
                        <td id="T_8c52d_row4_col2" class="data row4 col2" >23.16</td>
                        <td id="T_8c52d_row4_col3" class="data row4 col3" >23.88</td>
                        <td id="T_8c52d_row4_col4" class="data row4 col4" >26.16</td>
                        <td id="T_8c52d_row4_col5" class="data row4 col5" >3.74</td>
                        <td id="T_8c52d_row4_col6" class="data row4 col6" >34.01</td>
                        <td id="T_8c52d_row4_col7" class="data row4 col7" >-11.21</td>
                        <td id="T_8c52d_row4_col8" class="data row4 col8" >17.60</td>
                        <td id="T_8c52d_row4_col9" class="data row4 col9" >17.25</td>
                        <td id="T_8c52d_row4_col10" class="data row4 col10" >17.37</td>
                        <td id="T_8c52d_row4_col11" class="data row4 col11" >0.51</td>
                        <td id="T_8c52d_row4_col12" class="data row4 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_8c52d_level0_row5" class="row_heading level0 row5" >603160.SS</th>
                        <td id="T_8c52d_row5_col0" class="data row5 col0" >汇顶科技</td>
                        <td id="T_8c52d_row5_col1" class="data row5 col1" >18.72</td>
                        <td id="T_8c52d_row5_col2" class="data row5 col2" >25.04</td>
                        <td id="T_8c52d_row5_col3" class="data row5 col3" >26.16</td>
                        <td id="T_8c52d_row5_col4" class="data row5 col4" >26.11</td>
                        <td id="T_8c52d_row5_col5" class="data row5 col5" >1.02</td>
                        <td id="T_8c52d_row5_col6" class="data row5 col6" >55.80</td>
                        <td id="T_8c52d_row5_col7" class="data row5 col7" >-2.90</td>
                        <td id="T_8c52d_row5_col8" class="data row5 col8" >18.94</td>
                        <td id="T_8c52d_row5_col9" class="data row5 col9" >37.02</td>
                        <td id="T_8c52d_row5_col10" class="data row5 col10" >42.03</td>
                        <td id="T_8c52d_row5_col11" class="data row5 col11" >0.75</td>
                        <td id="T_8c52d_row5_col12" class="data row5 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_8c52d_level0_row6" class="row_heading level0 row6" >002626.SZ</th>
                        <td id="T_8c52d_row6_col0" class="data row6 col0" >金达威</td>
                        <td id="T_8c52d_row6_col1" class="data row6 col1" >32.22</td>
                        <td id="T_8c52d_row6_col2" class="data row6 col2" >21.33</td>
                        <td id="T_8c52d_row6_col3" class="data row6 col3" >22.04</td>
                        <td id="T_8c52d_row6_col4" class="data row6 col4" >19.57</td>
                        <td id="T_8c52d_row6_col5" class="data row6 col5" >2.88</td>
                        <td id="T_8c52d_row6_col6" class="data row6 col6" >41.13</td>
                        <td id="T_8c52d_row6_col7" class="data row6 col7" >8.68</td>
                        <td id="T_8c52d_row6_col8" class="data row6 col8" >29.51</td>
                        <td id="T_8c52d_row6_col9" class="data row6 col9" >27.90</td>
                        <td id="T_8c52d_row6_col10" class="data row6 col10" >45.47</td>
                        <td id="T_8c52d_row6_col11" class="data row6 col11" >1.11</td>
                        <td id="T_8c52d_row6_col12" class="data row6 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_8c52d_level0_row7" class="row_heading level0 row7" >002677.SZ</th>
                        <td id="T_8c52d_row7_col0" class="data row7 col0" >浙江美大</td>
                        <td id="T_8c52d_row7_col1" class="data row7 col1" >21.80</td>
                        <td id="T_8c52d_row7_col2" class="data row7 col2" >28.29</td>
                        <td id="T_8c52d_row7_col3" class="data row7 col3" >28.67</td>
                        <td id="T_8c52d_row7_col4" class="data row7 col4" >20.62</td>
                        <td id="T_8c52d_row7_col5" class="data row7 col5" >14.49</td>
                        <td id="T_8c52d_row7_col6" class="data row7 col6" >21.24</td>
                        <td id="T_8c52d_row7_col7" class="data row7 col7" >14.76</td>
                        <td id="T_8c52d_row7_col8" class="data row7 col8" >44.23</td>
                        <td id="T_8c52d_row7_col9" class="data row7 col9" >19.73</td>
                        <td id="T_8c52d_row7_col10" class="data row7 col10" >29.71</td>
                        <td id="T_8c52d_row7_col11" class="data row7 col11" >1.40</td>
                        <td id="T_8c52d_row7_col12" class="data row7 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_8c52d_level0_row8" class="row_heading level0 row8" >300033.SZ</th>
                        <td id="T_8c52d_row8_col0" class="data row8 col0" >同花顺</td>
                        <td id="T_8c52d_row8_col1" class="data row8 col1" >26.99</td>
                        <td id="T_8c52d_row8_col2" class="data row8 col2" >24.34</td>
                        <td id="T_8c52d_row8_col3" class="data row8 col3" >52.33</td>
                        <td id="T_8c52d_row8_col4" class="data row8 col4" >29.08</td>
                        <td id="T_8c52d_row8_col5" class="data row8 col5" >5.13</td>
                        <td id="T_8c52d_row8_col6" class="data row8 col6" >40.34</td>
                        <td id="T_8c52d_row8_col7" class="data row8 col7" >2.48</td>
                        <td id="T_8c52d_row8_col8" class="data row8 col8" >63.18</td>
                        <td id="T_8c52d_row8_col9" class="data row8 col9" >34.67</td>
                        <td id="T_8c52d_row8_col10" class="data row8 col10" >61.58</td>
                        <td id="T_8c52d_row8_col11" class="data row8 col11" >1.53</td>
                        <td id="T_8c52d_row8_col12" class="data row8 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_8c52d_level0_row9" class="row_heading level0 row9" >300832.SZ</th>
                        <td id="T_8c52d_row9_col0" class="data row9 col0" >新产业</td>
                        <td id="T_8c52d_row9_col1" class="data row9 col1" >9.45</td>
                        <td id="T_8c52d_row9_col2" class="data row9 col2" >25.97</td>
                        <td id="T_8c52d_row9_col3" class="data row9 col3" >46.52</td>
                        <td id="T_8c52d_row9_col4" class="data row9 col4" >24.46</td>
                        <td id="T_8c52d_row9_col5" class="data row9 col5" >11.10</td>
                        <td id="T_8c52d_row9_col6" class="data row9 col6" >20.61</td>
                        <td id="T_8c52d_row9_col7" class="data row9 col7" >6.11</td>
                        <td id="T_8c52d_row9_col8" class="data row9 col8" >27.94</td>
                        <td id="T_8c52d_row9_col9" class="data row9 col9" >25.82</td>
                        <td id="T_8c52d_row9_col10" class="data row9 col10" >35.56</td>
                        <td id="T_8c52d_row9_col11" class="data row9 col11" >1.73</td>
                        <td id="T_8c52d_row9_col12" class="data row9 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_8c52d_level0_row10" class="row_heading level0 row10" >600570.SS</th>
                        <td id="T_8c52d_row10_col0" class="data row10 col0" >恒生电子</td>
                        <td id="T_8c52d_row10_col1" class="data row10 col1" >49.48</td>
                        <td id="T_8c52d_row10_col2" class="data row10 col2" >24.06</td>
                        <td id="T_8c52d_row10_col3" class="data row10 col3" >26.42</td>
                        <td id="T_8c52d_row10_col4" class="data row10 col4" >16.27</td>
                        <td id="T_8c52d_row10_col5" class="data row10 col5" >5.69</td>
                        <td id="T_8c52d_row10_col6" class="data row10 col6" >49.90</td>
                        <td id="T_8c52d_row10_col7" class="data row10 col7" >16.16</td>
                        <td id="T_8c52d_row10_col8" class="data row10 col8" >10.32</td>
                        <td id="T_8c52d_row10_col9" class="data row10 col9" >58.78</td>
                        <td id="T_8c52d_row10_col10" class="data row10 col10" >95.23</td>
                        <td id="T_8c52d_row10_col11" class="data row10 col11" >1.91</td>
                        <td id="T_8c52d_row10_col12" class="data row10 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_8c52d_level0_row11" class="row_heading level0 row11" >300628.SZ</th>
                        <td id="T_8c52d_row11_col0" class="data row11 col0" >亿联网络</td>
                        <td id="T_8c52d_row11_col1" class="data row11 col1" >9.97</td>
                        <td id="T_8c52d_row11_col2" class="data row11 col2" >24.39</td>
                        <td id="T_8c52d_row11_col3" class="data row11 col3" >46.38</td>
                        <td id="T_8c52d_row11_col4" class="data row11 col4" >26.19</td>
                        <td id="T_8c52d_row11_col5" class="data row11 col5" >3.39</td>
                        <td id="T_8c52d_row11_col6" class="data row11 col6" >30.91</td>
                        <td id="T_8c52d_row11_col7" class="data row11 col7" >0.66</td>
                        <td id="T_8c52d_row11_col8" class="data row11 col8" >28.68</td>
                        <td id="T_8c52d_row11_col9" class="data row11 col9" >51.88</td>
                        <td id="T_8c52d_row11_col10" class="data row11 col10" >67.87</td>
                        <td id="T_8c52d_row11_col11" class="data row11 col11" >2.20</td>
                        <td id="T_8c52d_row11_col12" class="data row11 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_8c52d_level0_row12" class="row_heading level0 row12" >603444.SS</th>
                        <td id="T_8c52d_row12_col0" class="data row12 col0" >吉比特</td>
                        <td id="T_8c52d_row12_col1" class="data row12 col1" >21.16</td>
                        <td id="T_8c52d_row12_col2" class="data row12 col2" >26.31</td>
                        <td id="T_8c52d_row12_col3" class="data row12 col3" >40.37</td>
                        <td id="T_8c52d_row12_col4" class="data row12 col4" >24.14</td>
                        <td id="T_8c52d_row12_col5" class="data row12 col5" >13.78</td>
                        <td id="T_8c52d_row12_col6" class="data row12 col6" >19.94</td>
                        <td id="T_8c52d_row12_col7" class="data row12 col7" >4.11</td>
                        <td id="T_8c52d_row12_col8" class="data row12 col8" >66.50</td>
                        <td id="T_8c52d_row12_col9" class="data row12 col9" >38.19</td>
                        <td id="T_8c52d_row12_col10" class="data row12 col10" >52.21</td>
                        <td id="T_8c52d_row12_col11" class="data row12 col11" >2.62</td>
                        <td id="T_8c52d_row12_col12" class="data row12 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_8c52d_level0_row13" class="row_heading level0 row13" >300782.SZ</th>
                        <td id="T_8c52d_row13_col0" class="data row13 col0" >卓胜微</td>
                        <td id="T_8c52d_row13_col1" class="data row13 col1" >14.18</td>
                        <td id="T_8c52d_row13_col2" class="data row13 col2" >39.60</td>
                        <td id="T_8c52d_row13_col3" class="data row13 col3" >32.25</td>
                        <td id="T_8c52d_row13_col4" class="data row13 col4" >83.09</td>
                        <td id="T_8c52d_row13_col5" class="data row13 col5" >26.22</td>
                        <td id="T_8c52d_row13_col6" class="data row13 col6" >105.87</td>
                        <td id="T_8c52d_row13_col7" class="data row13 col7" >31.74</td>
                        <td id="T_8c52d_row13_col8" class="data row13 col8" >-780.68</td>
                        <td id="T_8c52d_row13_col9" class="data row13 col9" >95.49</td>
                        <td id="T_8c52d_row13_col10" class="data row13 col10" >290.75</td>
                        <td id="T_8c52d_row13_col11" class="data row13 col11" >2.75</td>
                        <td id="T_8c52d_row13_col12" class="data row13 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_8c52d_level0_row14" class="row_heading level0 row14" >300529.SZ</th>
                        <td id="T_8c52d_row14_col0" class="data row14 col0" >健帆生物</td>
                        <td id="T_8c52d_row14_col1" class="data row14 col1" >11.91</td>
                        <td id="T_8c52d_row14_col2" class="data row14 col2" >25.48</td>
                        <td id="T_8c52d_row14_col3" class="data row14 col3" >40.97</td>
                        <td id="T_8c52d_row14_col4" class="data row14 col4" >39.53</td>
                        <td id="T_8c52d_row14_col5" class="data row14 col5" >10.25</td>
                        <td id="T_8c52d_row14_col6" class="data row14 col6" >45.56</td>
                        <td id="T_8c52d_row14_col7" class="data row14 col7" >11.30</td>
                        <td id="T_8c52d_row14_col8" class="data row14 col8" >68.14</td>
                        <td id="T_8c52d_row14_col9" class="data row14 col9" >75.31</td>
                        <td id="T_8c52d_row14_col10" class="data row14 col10" >135.26</td>
                        <td id="T_8c52d_row14_col11" class="data row14 col11" >2.97</td>
                        <td id="T_8c52d_row14_col12" class="data row14 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_8c52d_level0_row15" class="row_heading level0 row15" >002901.SZ</th>
                        <td id="T_8c52d_row15_col0" class="data row15 col0" >大博医疗</td>
                        <td id="T_8c52d_row15_col1" class="data row15 col1" >21.68</td>
                        <td id="T_8c52d_row15_col2" class="data row15 col2" >28.78</td>
                        <td id="T_8c52d_row15_col3" class="data row15 col3" >45.57</td>
                        <td id="T_8c52d_row15_col4" class="data row15 col4" >40.40</td>
                        <td id="T_8c52d_row15_col5" class="data row15 col5" >19.06</td>
                        <td id="T_8c52d_row15_col6" class="data row15 col6" >28.58</td>
                        <td id="T_8c52d_row15_col7" class="data row15 col7" >18.26</td>
                        <td id="T_8c52d_row15_col8" class="data row15 col8" >-2.48</td>
                        <td id="T_8c52d_row15_col9" class="data row15 col9" >52.44</td>
                        <td id="T_8c52d_row15_col10" class="data row15 col10" >86.03</td>
                        <td id="T_8c52d_row15_col11" class="data row15 col11" >3.01</td>
                        <td id="T_8c52d_row15_col12" class="data row15 col12" >2020-09-30</td>
            </tr>
            <tr>
                        <th id="T_8c52d_level0_row16" class="row_heading level0 row16" >300760.SZ</th>
                        <td id="T_8c52d_row16_col0" class="data row16 col0" >迈瑞医疗</td>
                        <td id="T_8c52d_row16_col1" class="data row16 col1" >30.07</td>
                        <td id="T_8c52d_row16_col2" class="data row16 col2" >29.36</td>
                        <td id="T_8c52d_row16_col3" class="data row16 col3" >27.54</td>
                        <td id="T_8c52d_row16_col4" class="data row16 col4" >23.49</td>
                        <td id="T_8c52d_row16_col5" class="data row16 col5" >4.95</td>
                        <td id="T_8c52d_row16_col6" class="data row16 col6" >37.24</td>
                        <td id="T_8c52d_row16_col7" class="data row16 col7" >6.03</td>
                        <td id="T_8c52d_row16_col8" class="data row16 col8" >43.62</td>
                        <td id="T_8c52d_row16_col9" class="data row16 col9" >83.38</td>
                        <td id="T_8c52d_row16_col10" class="data row16 col10" >133.43</td>
                        <td id="T_8c52d_row16_col11" class="data row16 col11" >3.58</td>
                        <td id="T_8c52d_row16_col12" class="data row16 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_8c52d_level0_row17" class="row_heading level0 row17" >600519.SS</th>
                        <td id="T_8c52d_row17_col0" class="data row17 col0" >贵州茅台</td>
                        <td id="T_8c52d_row17_col1" class="data row17 col1" >21.40</td>
                        <td id="T_8c52d_row17_col2" class="data row17 col2" >30.01</td>
                        <td id="T_8c52d_row17_col3" class="data row17 col3" >47.94</td>
                        <td id="T_8c52d_row17_col4" class="data row17 col4" >17.87</td>
                        <td id="T_8c52d_row17_col5" class="data row17 col5" >3.02</td>
                        <td id="T_8c52d_row17_col6" class="data row17 col6" >20.13</td>
                        <td id="T_8c52d_row17_col7" class="data row17 col7" >1.84</td>
                        <td id="T_8c52d_row17_col8" class="data row17 col8" >37.59</td>
                        <td id="T_8c52d_row17_col9" class="data row17 col9" >59.47</td>
                        <td id="T_8c52d_row17_col10" class="data row17 col10" >75.33</td>
                        <td id="T_8c52d_row17_col11" class="data row17 col11" >3.74</td>
                        <td id="T_8c52d_row17_col12" class="data row17 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_8c52d_level0_row18" class="row_heading level0 row18" >603288.SS</th>
                        <td id="T_8c52d_row18_col0" class="data row18 col0" >海天味业</td>
                        <td id="T_8c52d_row18_col1" class="data row18 col1" >31.72</td>
                        <td id="T_8c52d_row18_col2" class="data row18 col2" >31.42</td>
                        <td id="T_8c52d_row18_col3" class="data row18 col3" >26.24</td>
                        <td id="T_8c52d_row18_col4" class="data row18 col4" >16.05</td>
                        <td id="T_8c52d_row18_col5" class="data row18 col5" >5.59</td>
                        <td id="T_8c52d_row18_col6" class="data row18 col6" >21.95</td>
                        <td id="T_8c52d_row18_col7" class="data row18 col7" >5.32</td>
                        <td id="T_8c52d_row18_col8" class="data row18 col8" >11.37</td>
                        <td id="T_8c52d_row18_col9" class="data row18 col9" >66.07</td>
                        <td id="T_8c52d_row18_col10" class="data row18 col10" >90.64</td>
                        <td id="T_8c52d_row18_col11" class="data row18 col11" >4.13</td>
                        <td id="T_8c52d_row18_col12" class="data row18 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_8c52d_level0_row19" class="row_heading level0 row19" >300595.SZ</th>
                        <td id="T_8c52d_row19_col0" class="data row19 col0" >欧普康视</td>
                        <td id="T_8c52d_row19_col1" class="data row19 col1" >10.02</td>
                        <td id="T_8c52d_row19_col2" class="data row19 col2" >21.91</td>
                        <td id="T_8c52d_row19_col3" class="data row19 col3" >48.20</td>
                        <td id="T_8c52d_row19_col4" class="data row19 col4" >40.94</td>
                        <td id="T_8c52d_row19_col5" class="data row19 col5" >21.01</td>
                        <td id="T_8c52d_row19_col6" class="data row19 col6" >42.15</td>
                        <td id="T_8c52d_row19_col7" class="data row19 col7" >23.11</td>
                        <td id="T_8c52d_row19_col8" class="data row19 col8" >54.08</td>
                        <td id="T_8c52d_row19_col9" class="data row19 col9" >114.88</td>
                        <td id="T_8c52d_row19_col10" class="data row19 col10" >220.13</td>
                        <td id="T_8c52d_row19_col11" class="data row19 col11" >5.22</td>
                        <td id="T_8c52d_row19_col12" class="data row19 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_8c52d_level0_row20" class="row_heading level0 row20" >600436.SS</th>
                        <td id="T_8c52d_row20_col0" class="data row20 col0" >片仔癀</td>
                        <td id="T_8c52d_row20_col1" class="data row20 col1" >19.10</td>
                        <td id="T_8c52d_row20_col2" class="data row20 col2" >21.07</td>
                        <td id="T_8c52d_row20_col3" class="data row20 col3" >23.85</td>
                        <td id="T_8c52d_row20_col4" class="data row20 col4" >20.72</td>
                        <td id="T_8c52d_row20_col5" class="data row20 col5" >4.41</td>
                        <td id="T_8c52d_row20_col6" class="data row20 col6" >27.83</td>
                        <td id="T_8c52d_row20_col7" class="data row20 col7" >5.83</td>
                        <td id="T_8c52d_row20_col8" class="data row20 col8" >-166.81</td>
                        <td id="T_8c52d_row20_col9" class="data row20 col9" >137.41</td>
                        <td id="T_8c52d_row20_col10" class="data row20 col10" >194.48</td>
                        <td id="T_8c52d_row20_col11" class="data row20 col11" >6.99</td>
                        <td id="T_8c52d_row20_col12" class="data row20 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_8c52d_level0_row21" class="row_heading level0 row21" >300896.SZ</th>
                        <td id="T_8c52d_row21_col0" class="data row21 col0" >爱美客</td>
                        <td id="T_8c52d_row21_col1" class="data row21 col1" >2.19</td>
                        <td id="T_8c52d_row21_col2" class="data row21 col2" >28.05</td>
                        <td id="T_8c52d_row21_col3" class="data row21 col3" >48.00</td>
                        <td id="T_8c52d_row21_col4" class="data row21 col4" >48.40</td>
                        <td id="T_8c52d_row21_col5" class="data row21 col5" >13.63</td>
                        <td id="T_8c52d_row21_col6" class="data row21 col6" >80.70</td>
                        <td id="T_8c52d_row21_col7" class="data row21 col7" >15.13</td>
                        <td id="T_8c52d_row21_col8" class="data row21 col8" >120.48</td>
                        <td id="T_8c52d_row21_col9" class="data row21 col9" >193.55</td>
                        <td id="T_8c52d_row21_col10" class="data row21 col10" >589.77</td>
                        <td id="T_8c52d_row21_col11" class="data row21 col11" >7.31</td>
                        <td id="T_8c52d_row21_col12" class="data row21 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_8c52d_level0_row22" class="row_heading level0 row22" >600763.SS</th>
                        <td id="T_8c52d_row22_col0" class="data row22 col0" >通策医疗</td>
                        <td id="T_8c52d_row22_col1" class="data row22 col1" >23.37</td>
                        <td id="T_8c52d_row22_col2" class="data row22 col2" >23.98</td>
                        <td id="T_8c52d_row22_col3" class="data row22 col3" >21.89</td>
                        <td id="T_8c52d_row22_col4" class="data row22 col4" >21.36</td>
                        <td id="T_8c52d_row22_col5" class="data row22 col5" >20.99</td>
                        <td id="T_8c52d_row22_col6" class="data row22 col6" >33.13</td>
                        <td id="T_8c52d_row22_col7" class="data row22 col7" >37.14</td>
                        <td id="T_8c52d_row22_col8" class="data row22 col8" >38.60</td>
                        <td id="T_8c52d_row22_col9" class="data row22 col9" >176.39</td>
                        <td id="T_8c52d_row22_col10" class="data row22 col10" >315.32</td>
                        <td id="T_8c52d_row22_col11" class="data row22 col11" >9.52</td>
                        <td id="T_8c52d_row22_col12" class="data row22 col12" >2021-03-31</td>
            </tr>
    </tbody></table>



### 金融行业

1. ROE >= 10%
2. 商誉比 < 10%
3. 利润率 >= 20%
3. 盈利增长 >= 10% 且 收入增长 >= 10%




<style  type="text/css" >
#T_f6a3c_row0_col0,#T_f6a3c_row0_col1,#T_f6a3c_row0_col2,#T_f6a3c_row0_col3,#T_f6a3c_row0_col4,#T_f6a3c_row0_col5,#T_f6a3c_row0_col6,#T_f6a3c_row0_col7,#T_f6a3c_row0_col9,#T_f6a3c_row0_col10,#T_f6a3c_row0_col11,#T_f6a3c_row0_col12,#T_f6a3c_row1_col0,#T_f6a3c_row1_col1,#T_f6a3c_row1_col2,#T_f6a3c_row1_col3,#T_f6a3c_row1_col4,#T_f6a3c_row1_col5,#T_f6a3c_row1_col6,#T_f6a3c_row1_col7,#T_f6a3c_row1_col9,#T_f6a3c_row1_col10,#T_f6a3c_row1_col11,#T_f6a3c_row1_col12,#T_f6a3c_row2_col0,#T_f6a3c_row2_col1,#T_f6a3c_row2_col2,#T_f6a3c_row2_col3,#T_f6a3c_row2_col4,#T_f6a3c_row2_col5,#T_f6a3c_row2_col6,#T_f6a3c_row2_col7,#T_f6a3c_row2_col9,#T_f6a3c_row2_col10,#T_f6a3c_row2_col11,#T_f6a3c_row2_col12,#T_f6a3c_row3_col0,#T_f6a3c_row3_col1,#T_f6a3c_row3_col2,#T_f6a3c_row3_col3,#T_f6a3c_row3_col4,#T_f6a3c_row3_col5,#T_f6a3c_row3_col6,#T_f6a3c_row3_col7,#T_f6a3c_row3_col8,#T_f6a3c_row3_col9,#T_f6a3c_row3_col10,#T_f6a3c_row3_col11,#T_f6a3c_row3_col12,#T_f6a3c_row4_col0,#T_f6a3c_row4_col1,#T_f6a3c_row4_col2,#T_f6a3c_row4_col3,#T_f6a3c_row4_col4,#T_f6a3c_row4_col5,#T_f6a3c_row4_col6,#T_f6a3c_row4_col7,#T_f6a3c_row4_col8,#T_f6a3c_row4_col9,#T_f6a3c_row4_col10,#T_f6a3c_row4_col11,#T_f6a3c_row4_col12,#T_f6a3c_row5_col0,#T_f6a3c_row5_col1,#T_f6a3c_row5_col2,#T_f6a3c_row5_col3,#T_f6a3c_row5_col4,#T_f6a3c_row5_col5,#T_f6a3c_row5_col6,#T_f6a3c_row5_col7,#T_f6a3c_row5_col9,#T_f6a3c_row5_col10,#T_f6a3c_row5_col11,#T_f6a3c_row5_col12,#T_f6a3c_row6_col0,#T_f6a3c_row6_col1,#T_f6a3c_row6_col2,#T_f6a3c_row6_col3,#T_f6a3c_row6_col4,#T_f6a3c_row6_col5,#T_f6a3c_row6_col6,#T_f6a3c_row6_col7,#T_f6a3c_row6_col9,#T_f6a3c_row6_col10,#T_f6a3c_row6_col11,#T_f6a3c_row6_col12,#T_f6a3c_row7_col0,#T_f6a3c_row7_col1,#T_f6a3c_row7_col2,#T_f6a3c_row7_col3,#T_f6a3c_row7_col4,#T_f6a3c_row7_col5,#T_f6a3c_row7_col6,#T_f6a3c_row7_col7,#T_f6a3c_row7_col9,#T_f6a3c_row7_col10,#T_f6a3c_row7_col11,#T_f6a3c_row7_col12{
            color:  black;
        }#T_f6a3c_row0_col8,#T_f6a3c_row1_col8,#T_f6a3c_row2_col8,#T_f6a3c_row5_col8,#T_f6a3c_row6_col8,#T_f6a3c_row7_col8{
            color:  red;
        }</style><table id="T_f6a3c_" ><thead>    <tr>        <th class="blank level0" ></th>        <th class="col_heading level0 col0" >名称</th>        <th class="col_heading level0 col1" >负债率</th>        <th class="col_heading level0 col2" >ROE</th>        <th class="col_heading level0 col3" >利润率</th>        <th class="col_heading level0 col4" >收入增长</th>        <th class="col_heading level0 col5" >收入增长TTM</th>        <th class="col_heading level0 col6" >盈利增长</th>        <th class="col_heading level0 col7" >盈利增长TTM</th>        <th class="col_heading level0 col8" >FCF增长</th>        <th class="col_heading level0 col9" >PE</th>        <th class="col_heading level0 col10" >PEm</th>        <th class="col_heading level0 col11" >PEG</th>        <th class="col_heading level0 col12" >季报日期</th>    </tr>    <tr>        <th class="index_name level0" >Symbol</th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>    </tr></thead><tbody>
                <tr>
                        <th id="T_f6a3c_level0_row0" class="row_heading level0 row0" >601229.SS</th>
                        <td id="T_f6a3c_row0_col0" class="data row0 col0" >上海银行</td>
                        <td id="T_f6a3c_row0_col1" class="data row0 col1" >92.25</td>
                        <td id="T_f6a3c_row0_col2" class="data row0 col2" >12.51</td>
                        <td id="T_f6a3c_row0_col3" class="data row0 col3" >63.20</td>
                        <td id="T_f6a3c_row0_col4" class="data row0 col4" >10.14</td>
                        <td id="T_f6a3c_row0_col5" class="data row0 col5" >2.40</td>
                        <td id="T_f6a3c_row0_col6" class="data row0 col6" >11.03</td>
                        <td id="T_f6a3c_row0_col7" class="data row0 col7" >1.52</td>
                        <td id="T_f6a3c_row0_col8" class="data row0 col8" >-118.51</td>
                        <td id="T_f6a3c_row0_col9" class="data row0 col9" >6.15</td>
                        <td id="T_f6a3c_row0_col10" class="data row0 col10" >6.55</td>
                        <td id="T_f6a3c_row0_col11" class="data row0 col11" >0.59</td>
                        <td id="T_f6a3c_row0_col12" class="data row0 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_f6a3c_level0_row1" class="row_heading level0 row1" >601838.SS</th>
                        <td id="T_f6a3c_row1_col0" class="data row1 col0" >成都银行</td>
                        <td id="T_f6a3c_row1_col1" class="data row1 col1" >92.93</td>
                        <td id="T_f6a3c_row1_col2" class="data row1 col2" >14.82</td>
                        <td id="T_f6a3c_row1_col3" class="data row1 col3" >56.23</td>
                        <td id="T_f6a3c_row1_col4" class="data row1 col4" >12.32</td>
                        <td id="T_f6a3c_row1_col5" class="data row1 col5" >4.49</td>
                        <td id="T_f6a3c_row1_col6" class="data row1 col6" >15.63</td>
                        <td id="T_f6a3c_row1_col7" class="data row1 col7" >4.25</td>
                        <td id="T_f6a3c_row1_col8" class="data row1 col8" >-176.43</td>
                        <td id="T_f6a3c_row1_col9" class="data row1 col9" >8.41</td>
                        <td id="T_f6a3c_row1_col10" class="data row1 col10" >10.08</td>
                        <td id="T_f6a3c_row1_col11" class="data row1 col11" >0.65</td>
                        <td id="T_f6a3c_row1_col12" class="data row1 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_f6a3c_level0_row2" class="row_heading level0 row2" >601577.SS</th>
                        <td id="T_f6a3c_row2_col0" class="data row2 col0" >长沙银行</td>
                        <td id="T_f6a3c_row2_col1" class="data row2 col1" >93.51</td>
                        <td id="T_f6a3c_row2_col2" class="data row2 col2" >14.98</td>
                        <td id="T_f6a3c_row2_col3" class="data row2 col3" >43.03</td>
                        <td id="T_f6a3c_row2_col4" class="data row2 col4" >10.42</td>
                        <td id="T_f6a3c_row2_col5" class="data row2 col5" >1.91</td>
                        <td id="T_f6a3c_row2_col6" class="data row2 col6" >10.82</td>
                        <td id="T_f6a3c_row2_col7" class="data row2 col7" >1.46</td>
                        <td id="T_f6a3c_row2_col8" class="data row2 col8" >-149.80</td>
                        <td id="T_f6a3c_row2_col9" class="data row2 col9" >6.50</td>
                        <td id="T_f6a3c_row2_col10" class="data row2 col10" >8.16</td>
                        <td id="T_f6a3c_row2_col11" class="data row2 col11" >0.75</td>
                        <td id="T_f6a3c_row2_col12" class="data row2 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_f6a3c_level0_row3" class="row_heading level0 row3" >601128.SS</th>
                        <td id="T_f6a3c_row3_col0" class="data row3 col0" >常熟银行</td>
                        <td id="T_f6a3c_row3_col1" class="data row3 col1" >90.84</td>
                        <td id="T_f6a3c_row3_col2" class="data row3 col2" >11.06</td>
                        <td id="T_f6a3c_row3_col3" class="data row3 col3" >36.04</td>
                        <td id="T_f6a3c_row3_col4" class="data row3 col4" >12.82</td>
                        <td id="T_f6a3c_row3_col5" class="data row3 col5" >1.38</td>
                        <td id="T_f6a3c_row3_col6" class="data row3 col6" >12.89</td>
                        <td id="T_f6a3c_row3_col7" class="data row3 col7" >1.37</td>
                        <td id="T_f6a3c_row3_col8" class="data row3 col8" >170.81</td>
                        <td id="T_f6a3c_row3_col9" class="data row3 col9" >10.40</td>
                        <td id="T_f6a3c_row3_col10" class="data row3 col10" >11.83</td>
                        <td id="T_f6a3c_row3_col11" class="data row3 col11" >0.92</td>
                        <td id="T_f6a3c_row3_col12" class="data row3 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_f6a3c_level0_row4" class="row_heading level0 row4" >600926.SS</th>
                        <td id="T_f6a3c_row4_col0" class="data row4 col0" >杭州银行</td>
                        <td id="T_f6a3c_row4_col1" class="data row4 col1" >93.08</td>
                        <td id="T_f6a3c_row4_col2" class="data row4 col2" >11.24</td>
                        <td id="T_f6a3c_row4_col3" class="data row4 col3" >48.22</td>
                        <td id="T_f6a3c_row4_col4" class="data row4 col4" >15.82</td>
                        <td id="T_f6a3c_row4_col5" class="data row4 col5" >4.07</td>
                        <td id="T_f6a3c_row4_col6" class="data row4 col6" >16.34</td>
                        <td id="T_f6a3c_row4_col7" class="data row4 col7" >4.95</td>
                        <td id="T_f6a3c_row4_col8" class="data row4 col8" >41.76</td>
                        <td id="T_f6a3c_row4_col9" class="data row4 col9" >14.15</td>
                        <td id="T_f6a3c_row4_col10" class="data row4 col10" >16.37</td>
                        <td id="T_f6a3c_row4_col11" class="data row4 col11" >1.00</td>
                        <td id="T_f6a3c_row4_col12" class="data row4 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_f6a3c_level0_row5" class="row_heading level0 row5" >002142.SZ</th>
                        <td id="T_f6a3c_row5_col0" class="data row5 col0" >宁波银行</td>
                        <td id="T_f6a3c_row5_col1" class="data row5 col1" >92.69</td>
                        <td id="T_f6a3c_row5_col2" class="data row5 col2" >16.34</td>
                        <td id="T_f6a3c_row5_col3" class="data row5 col3" >49.03</td>
                        <td id="T_f6a3c_row5_col4" class="data row5 col4" >19.23</td>
                        <td id="T_f6a3c_row5_col5" class="data row5 col5" >5.54</td>
                        <td id="T_f6a3c_row5_col6" class="data row5 col6" >17.40</td>
                        <td id="T_f6a3c_row5_col7" class="data row5 col7" >4.87</td>
                        <td id="T_f6a3c_row5_col8" class="data row5 col8" >-174.45</td>
                        <td id="T_f6a3c_row5_col9" class="data row5 col9" >17.03</td>
                        <td id="T_f6a3c_row5_col10" class="data row5 col10" >20.90</td>
                        <td id="T_f6a3c_row5_col11" class="data row5 col11" >1.20</td>
                        <td id="T_f6a3c_row5_col12" class="data row5 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_f6a3c_level0_row6" class="row_heading level0 row6" >600036.SS</th>
                        <td id="T_f6a3c_row6_col0" class="data row6 col0" >招商银行</td>
                        <td id="T_f6a3c_row6_col1" class="data row6 col1" >91.27</td>
                        <td id="T_f6a3c_row6_col2" class="data row6 col2" >15.46</td>
                        <td id="T_f6a3c_row6_col3" class="data row6 col3" >43.54</td>
                        <td id="T_f6a3c_row6_col4" class="data row6 col4" >11.97</td>
                        <td id="T_f6a3c_row6_col5" class="data row6 col5" >3.28</td>
                        <td id="T_f6a3c_row6_col6" class="data row6 col6" >11.65</td>
                        <td id="T_f6a3c_row6_col7" class="data row6 col7" >4.34</td>
                        <td id="T_f6a3c_row6_col8" class="data row6 col8" >-693.52</td>
                        <td id="T_f6a3c_row6_col9" class="data row6 col9" >14.53</td>
                        <td id="T_f6a3c_row6_col10" class="data row6 col10" >17.00</td>
                        <td id="T_f6a3c_row6_col11" class="data row6 col11" >1.46</td>
                        <td id="T_f6a3c_row6_col12" class="data row6 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_f6a3c_level0_row7" class="row_heading level0 row7" >002961.SZ</th>
                        <td id="T_f6a3c_row7_col0" class="data row7 col0" >瑞达期货</td>
                        <td id="T_f6a3c_row7_col1" class="data row7 col1" >82.51</td>
                        <td id="T_f6a3c_row7_col2" class="data row7 col2" >10.05</td>
                        <td id="T_f6a3c_row7_col3" class="data row7 col3" >21.88</td>
                        <td id="T_f6a3c_row7_col4" class="data row7 col4" >45.82</td>
                        <td id="T_f6a3c_row7_col5" class="data row7 col5" >40.61</td>
                        <td id="T_f6a3c_row7_col6" class="data row7 col6" >27.83</td>
                        <td id="T_f6a3c_row7_col7" class="data row7 col7" >105.98</td>
                        <td id="T_f6a3c_row7_col8" class="data row7 col8" >-19.07</td>
                        <td id="T_f6a3c_row7_col9" class="data row7 col9" >37.04</td>
                        <td id="T_f6a3c_row7_col10" class="data row7 col10" >57.39</td>
                        <td id="T_f6a3c_row7_col11" class="data row7 col11" >2.06</td>
                        <td id="T_f6a3c_row7_col12" class="data row7 col12" >2020-12-31</td>
            </tr>
    </tbody></table>



### 观察列表






<style  type="text/css" >
#T_666e1_row0_col0,#T_666e1_row0_col1,#T_666e1_row0_col2,#T_666e1_row0_col3,#T_666e1_row0_col4,#T_666e1_row0_col5,#T_666e1_row0_col6,#T_666e1_row0_col7,#T_666e1_row0_col8,#T_666e1_row0_col9,#T_666e1_row0_col10,#T_666e1_row0_col11,#T_666e1_row0_col12,#T_666e1_row1_col0,#T_666e1_row1_col1,#T_666e1_row1_col2,#T_666e1_row1_col3,#T_666e1_row1_col4,#T_666e1_row1_col5,#T_666e1_row1_col6,#T_666e1_row1_col7,#T_666e1_row1_col9,#T_666e1_row1_col10,#T_666e1_row1_col11,#T_666e1_row1_col12,#T_666e1_row2_col0,#T_666e1_row2_col1,#T_666e1_row2_col2,#T_666e1_row2_col3,#T_666e1_row2_col4,#T_666e1_row2_col5,#T_666e1_row2_col6,#T_666e1_row2_col7,#T_666e1_row2_col8,#T_666e1_row2_col9,#T_666e1_row2_col10,#T_666e1_row2_col11,#T_666e1_row2_col12,#T_666e1_row3_col0,#T_666e1_row3_col1,#T_666e1_row3_col2,#T_666e1_row3_col3,#T_666e1_row3_col4,#T_666e1_row3_col5,#T_666e1_row3_col6,#T_666e1_row3_col7,#T_666e1_row3_col8,#T_666e1_row3_col9,#T_666e1_row3_col10,#T_666e1_row3_col11,#T_666e1_row3_col12,#T_666e1_row4_col0,#T_666e1_row4_col1,#T_666e1_row4_col2,#T_666e1_row4_col3,#T_666e1_row4_col4,#T_666e1_row4_col5,#T_666e1_row4_col6,#T_666e1_row4_col8,#T_666e1_row4_col9,#T_666e1_row4_col10,#T_666e1_row4_col11,#T_666e1_row4_col12,#T_666e1_row5_col0,#T_666e1_row5_col1,#T_666e1_row5_col2,#T_666e1_row5_col3,#T_666e1_row5_col4,#T_666e1_row5_col5,#T_666e1_row5_col6,#T_666e1_row5_col7,#T_666e1_row5_col9,#T_666e1_row5_col10,#T_666e1_row5_col11,#T_666e1_row5_col12,#T_666e1_row6_col0,#T_666e1_row6_col1,#T_666e1_row6_col2,#T_666e1_row6_col3,#T_666e1_row6_col4,#T_666e1_row6_col5,#T_666e1_row6_col6,#T_666e1_row6_col7,#T_666e1_row6_col8,#T_666e1_row6_col9,#T_666e1_row6_col10,#T_666e1_row6_col11,#T_666e1_row6_col12,#T_666e1_row7_col0,#T_666e1_row7_col1,#T_666e1_row7_col2,#T_666e1_row7_col3,#T_666e1_row7_col4,#T_666e1_row7_col5,#T_666e1_row7_col6,#T_666e1_row7_col7,#T_666e1_row7_col9,#T_666e1_row7_col10,#T_666e1_row7_col11,#T_666e1_row7_col12,#T_666e1_row8_col0,#T_666e1_row8_col1,#T_666e1_row8_col2,#T_666e1_row8_col3,#T_666e1_row8_col4,#T_666e1_row8_col5,#T_666e1_row8_col6,#T_666e1_row8_col7,#T_666e1_row8_col9,#T_666e1_row8_col10,#T_666e1_row8_col11,#T_666e1_row8_col12,#T_666e1_row9_col0,#T_666e1_row9_col1,#T_666e1_row9_col2,#T_666e1_row9_col3,#T_666e1_row9_col4,#T_666e1_row9_col5,#T_666e1_row9_col6,#T_666e1_row9_col8,#T_666e1_row9_col9,#T_666e1_row9_col10,#T_666e1_row9_col11,#T_666e1_row9_col12,#T_666e1_row10_col0,#T_666e1_row10_col1,#T_666e1_row10_col2,#T_666e1_row10_col3,#T_666e1_row10_col4,#T_666e1_row10_col5,#T_666e1_row10_col6,#T_666e1_row10_col7,#T_666e1_row10_col8,#T_666e1_row10_col9,#T_666e1_row10_col10,#T_666e1_row10_col11,#T_666e1_row10_col12,#T_666e1_row11_col0,#T_666e1_row11_col1,#T_666e1_row11_col2,#T_666e1_row11_col3,#T_666e1_row11_col4,#T_666e1_row11_col5,#T_666e1_row11_col6,#T_666e1_row11_col7,#T_666e1_row11_col8,#T_666e1_row11_col9,#T_666e1_row11_col10,#T_666e1_row11_col11,#T_666e1_row11_col12,#T_666e1_row12_col0,#T_666e1_row12_col1,#T_666e1_row12_col2,#T_666e1_row12_col3,#T_666e1_row12_col4,#T_666e1_row12_col5,#T_666e1_row12_col6,#T_666e1_row12_col7,#T_666e1_row12_col9,#T_666e1_row12_col10,#T_666e1_row12_col11,#T_666e1_row12_col12,#T_666e1_row13_col0,#T_666e1_row13_col1,#T_666e1_row13_col2,#T_666e1_row13_col3,#T_666e1_row13_col4,#T_666e1_row13_col5,#T_666e1_row13_col6,#T_666e1_row13_col7,#T_666e1_row13_col9,#T_666e1_row13_col10,#T_666e1_row13_col11,#T_666e1_row13_col12,#T_666e1_row14_col0,#T_666e1_row14_col1,#T_666e1_row14_col2,#T_666e1_row14_col3,#T_666e1_row14_col4,#T_666e1_row14_col5,#T_666e1_row14_col6,#T_666e1_row14_col7,#T_666e1_row14_col8,#T_666e1_row14_col9,#T_666e1_row14_col10,#T_666e1_row14_col11,#T_666e1_row14_col12,#T_666e1_row15_col0,#T_666e1_row15_col1,#T_666e1_row15_col2,#T_666e1_row15_col3,#T_666e1_row15_col4,#T_666e1_row15_col5,#T_666e1_row15_col6,#T_666e1_row15_col7,#T_666e1_row15_col9,#T_666e1_row15_col10,#T_666e1_row15_col11,#T_666e1_row15_col12,#T_666e1_row16_col0,#T_666e1_row16_col1,#T_666e1_row16_col2,#T_666e1_row16_col3,#T_666e1_row16_col4,#T_666e1_row16_col5,#T_666e1_row16_col6,#T_666e1_row16_col7,#T_666e1_row16_col8,#T_666e1_row16_col9,#T_666e1_row16_col10,#T_666e1_row16_col11,#T_666e1_row16_col12,#T_666e1_row17_col0,#T_666e1_row17_col1,#T_666e1_row17_col2,#T_666e1_row17_col3,#T_666e1_row17_col4,#T_666e1_row17_col5,#T_666e1_row17_col6,#T_666e1_row17_col7,#T_666e1_row17_col8,#T_666e1_row17_col9,#T_666e1_row17_col10,#T_666e1_row17_col11,#T_666e1_row17_col12,#T_666e1_row18_col0,#T_666e1_row18_col1,#T_666e1_row18_col2,#T_666e1_row18_col3,#T_666e1_row18_col4,#T_666e1_row18_col5,#T_666e1_row18_col6,#T_666e1_row18_col7,#T_666e1_row18_col8,#T_666e1_row18_col9,#T_666e1_row18_col10,#T_666e1_row18_col11,#T_666e1_row18_col12,#T_666e1_row19_col0,#T_666e1_row19_col1,#T_666e1_row19_col2,#T_666e1_row19_col3,#T_666e1_row19_col4,#T_666e1_row19_col5,#T_666e1_row19_col6,#T_666e1_row19_col7,#T_666e1_row19_col8,#T_666e1_row19_col9,#T_666e1_row19_col10,#T_666e1_row19_col11,#T_666e1_row19_col12,#T_666e1_row20_col0,#T_666e1_row20_col1,#T_666e1_row20_col2,#T_666e1_row20_col3,#T_666e1_row20_col4,#T_666e1_row20_col5,#T_666e1_row20_col6,#T_666e1_row20_col7,#T_666e1_row20_col8,#T_666e1_row20_col9,#T_666e1_row20_col10,#T_666e1_row20_col11,#T_666e1_row20_col12,#T_666e1_row21_col0,#T_666e1_row21_col1,#T_666e1_row21_col2,#T_666e1_row21_col3,#T_666e1_row21_col4,#T_666e1_row21_col5,#T_666e1_row21_col6,#T_666e1_row21_col7,#T_666e1_row21_col8,#T_666e1_row21_col9,#T_666e1_row21_col10,#T_666e1_row21_col11,#T_666e1_row21_col12,#T_666e1_row22_col0,#T_666e1_row22_col1,#T_666e1_row22_col2,#T_666e1_row22_col3,#T_666e1_row22_col4,#T_666e1_row22_col5,#T_666e1_row22_col6,#T_666e1_row22_col7,#T_666e1_row22_col8,#T_666e1_row22_col9,#T_666e1_row22_col10,#T_666e1_row22_col11,#T_666e1_row22_col12,#T_666e1_row23_col0,#T_666e1_row23_col1,#T_666e1_row23_col2,#T_666e1_row23_col3,#T_666e1_row23_col4,#T_666e1_row23_col5,#T_666e1_row23_col6,#T_666e1_row23_col7,#T_666e1_row23_col9,#T_666e1_row23_col10,#T_666e1_row23_col11,#T_666e1_row23_col12,#T_666e1_row24_col0,#T_666e1_row24_col1,#T_666e1_row24_col2,#T_666e1_row24_col3,#T_666e1_row24_col4,#T_666e1_row24_col5,#T_666e1_row24_col6,#T_666e1_row24_col7,#T_666e1_row24_col9,#T_666e1_row24_col10,#T_666e1_row24_col11,#T_666e1_row24_col12,#T_666e1_row25_col0,#T_666e1_row25_col1,#T_666e1_row25_col2,#T_666e1_row25_col3,#T_666e1_row25_col4,#T_666e1_row25_col5,#T_666e1_row25_col6,#T_666e1_row25_col7,#T_666e1_row25_col9,#T_666e1_row25_col10,#T_666e1_row25_col11,#T_666e1_row25_col12,#T_666e1_row26_col0,#T_666e1_row26_col1,#T_666e1_row26_col2,#T_666e1_row26_col3,#T_666e1_row26_col4,#T_666e1_row26_col6,#T_666e1_row26_col8,#T_666e1_row26_col9,#T_666e1_row26_col10,#T_666e1_row26_col11,#T_666e1_row26_col12,#T_666e1_row27_col0,#T_666e1_row27_col1,#T_666e1_row27_col2,#T_666e1_row27_col3,#T_666e1_row27_col4,#T_666e1_row27_col8,#T_666e1_row27_col9,#T_666e1_row27_col10,#T_666e1_row27_col11,#T_666e1_row27_col12,#T_666e1_row28_col0,#T_666e1_row28_col1,#T_666e1_row28_col2,#T_666e1_row28_col3,#T_666e1_row28_col4,#T_666e1_row28_col5,#T_666e1_row28_col7,#T_666e1_row28_col9,#T_666e1_row28_col10,#T_666e1_row28_col11,#T_666e1_row28_col12,#T_666e1_row29_col0,#T_666e1_row29_col1,#T_666e1_row29_col2,#T_666e1_row29_col3,#T_666e1_row29_col5,#T_666e1_row29_col7,#T_666e1_row29_col9,#T_666e1_row29_col10,#T_666e1_row29_col11,#T_666e1_row29_col12{
            color:  black;
        }#T_666e1_row1_col8,#T_666e1_row4_col7,#T_666e1_row5_col8,#T_666e1_row7_col8,#T_666e1_row8_col8,#T_666e1_row9_col7,#T_666e1_row12_col8,#T_666e1_row13_col8,#T_666e1_row15_col8,#T_666e1_row23_col8,#T_666e1_row24_col8,#T_666e1_row25_col8,#T_666e1_row26_col5,#T_666e1_row26_col7,#T_666e1_row27_col5,#T_666e1_row27_col6,#T_666e1_row27_col7,#T_666e1_row28_col6,#T_666e1_row28_col8,#T_666e1_row29_col4,#T_666e1_row29_col6,#T_666e1_row29_col8{
            color:  red;
        }</style><table id="T_666e1_" ><thead>    <tr>        <th class="blank level0" ></th>        <th class="col_heading level0 col0" >名称</th>        <th class="col_heading level0 col1" >负债率</th>        <th class="col_heading level0 col2" >ROE</th>        <th class="col_heading level0 col3" >利润率</th>        <th class="col_heading level0 col4" >收入增长</th>        <th class="col_heading level0 col5" >收入增长TTM</th>        <th class="col_heading level0 col6" >盈利增长</th>        <th class="col_heading level0 col7" >盈利增长TTM</th>        <th class="col_heading level0 col8" >FCF增长</th>        <th class="col_heading level0 col9" >PE</th>        <th class="col_heading level0 col10" >PEm</th>        <th class="col_heading level0 col11" >PEG</th>        <th class="col_heading level0 col12" >季报日期</th>    </tr>    <tr>        <th class="index_name level0" >Symbol</th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>    </tr></thead><tbody>
                <tr>
                        <th id="T_666e1_level0_row0" class="row_heading level0 row0" >600585.SS</th>
                        <td id="T_666e1_row0_col0" class="data row0 col0" >海螺水泥</td>
                        <td id="T_666e1_row0_col1" class="data row0 col1" >16.30</td>
                        <td id="T_666e1_row0_col2" class="data row0 col2" >22.59</td>
                        <td id="T_666e1_row0_col3" class="data row0 col3" >21.40</td>
                        <td id="T_666e1_row0_col4" class="data row0 col4" >35.01</td>
                        <td id="T_666e1_row0_col5" class="data row0 col5" >6.37</td>
                        <td id="T_666e1_row0_col6" class="data row0 col6" >35.10</td>
                        <td id="T_666e1_row0_col7" class="data row0 col7" >2.55</td>
                        <td id="T_666e1_row0_col8" class="data row0 col8" >36.04</td>
                        <td id="T_666e1_row0_col9" class="data row0 col9" >7.10</td>
                        <td id="T_666e1_row0_col10" class="data row0 col10" >8.49</td>
                        <td id="T_666e1_row0_col11" class="data row0 col11" >0.24</td>
                        <td id="T_666e1_row0_col12" class="data row0 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_666e1_level0_row1" class="row_heading level0 row1" >600489.SS</th>
                        <td id="T_666e1_row1_col0" class="data row1 col0" >中金黄金</td>
                        <td id="T_666e1_row1_col1" class="data row1 col1" >44.27</td>
                        <td id="T_666e1_row1_col2" class="data row1 col2" >3.80</td>
                        <td id="T_666e1_row1_col3" class="data row1 col3" >1.64</td>
                        <td id="T_666e1_row1_col4" class="data row1 col4" >13.64</td>
                        <td id="T_666e1_row1_col5" class="data row1 col5" >8.12</td>
                        <td id="T_666e1_row1_col6" class="data row1 col6" >124.57</td>
                        <td id="T_666e1_row1_col7" class="data row1 col7" >20.74</td>
                        <td id="T_666e1_row1_col8" class="data row1 col8" >-40.46</td>
                        <td id="T_666e1_row1_col9" class="data row1 col9" >27.32</td>
                        <td id="T_666e1_row1_col10" class="data row1 col10" >63.62</td>
                        <td id="T_666e1_row1_col11" class="data row1 col11" >0.51</td>
                        <td id="T_666e1_row1_col12" class="data row1 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_666e1_level0_row2" class="row_heading level0 row2" >601318.SS</th>
                        <td id="T_666e1_row2_col0" class="data row2 col0" >中国平安</td>
                        <td id="T_666e1_row2_col1" class="data row2 col1" >89.63</td>
                        <td id="T_666e1_row2_col2" class="data row2 col2" >19.77</td>
                        <td id="T_666e1_row2_col3" class="data row2 col3" >10.76</td>
                        <td id="T_666e1_row2_col4" class="data row2 col4" >8.44</td>
                        <td id="T_666e1_row2_col5" class="data row2 col5" >2.13</td>
                        <td id="T_666e1_row2_col6" class="data row2 col6" >18.48</td>
                        <td id="T_666e1_row2_col7" class="data row2 col7" >0.81</td>
                        <td id="T_666e1_row2_col8" class="data row2 col8" >30.57</td>
                        <td id="T_666e1_row2_col9" class="data row2 col9" >8.73</td>
                        <td id="T_666e1_row2_col10" class="data row2 col10" >10.49</td>
                        <td id="T_666e1_row2_col11" class="data row2 col11" >0.57</td>
                        <td id="T_666e1_row2_col12" class="data row2 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_666e1_level0_row3" class="row_heading level0 row3" >000002.SZ</th>
                        <td id="T_666e1_row3_col0" class="data row3 col0" >万  科Ａ</td>
                        <td id="T_666e1_row3_col1" class="data row3 col1" >81.28</td>
                        <td id="T_666e1_row3_col2" class="data row3 col2" >20.50</td>
                        <td id="T_666e1_row3_col3" class="data row3 col3" >10.84</td>
                        <td id="T_666e1_row3_col4" class="data row3 col4" >20.02</td>
                        <td id="T_666e1_row3_col5" class="data row3 col5" >3.46</td>
                        <td id="T_666e1_row3_col6" class="data row3 col6" >14.10</td>
                        <td id="T_666e1_row3_col7" class="data row3 col7" >0.10</td>
                        <td id="T_666e1_row3_col8" class="data row3 col8" >25.80</td>
                        <td id="T_666e1_row3_col9" class="data row3 col9" >7.32</td>
                        <td id="T_666e1_row3_col10" class="data row3 col10" >8.33</td>
                        <td id="T_666e1_row3_col11" class="data row3 col11" >0.59</td>
                        <td id="T_666e1_row3_col12" class="data row3 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_666e1_level0_row4" class="row_heading level0 row4" >600886.SS</th>
                        <td id="T_666e1_row4_col0" class="data row4 col0" >国投电力</td>
                        <td id="T_666e1_row4_col1" class="data row4 col1" >63.92</td>
                        <td id="T_666e1_row4_col2" class="data row4 col2" >11.40</td>
                        <td id="T_666e1_row4_col3" class="data row4 col3" >11.52</td>
                        <td id="T_666e1_row4_col4" class="data row4 col4" >8.58</td>
                        <td id="T_666e1_row4_col5" class="data row4 col5" >4.09</td>
                        <td id="T_666e1_row4_col6" class="data row4 col6" >19.99</td>
                        <td id="T_666e1_row4_col7" class="data row4 col7" >-4.68</td>
                        <td id="T_666e1_row4_col8" class="data row4 col8" >18.50</td>
                        <td id="T_666e1_row4_col9" class="data row4 col9" >12.38</td>
                        <td id="T_666e1_row4_col10" class="data row4 col10" >15.00</td>
                        <td id="T_666e1_row4_col11" class="data row4 col11" >0.75</td>
                        <td id="T_666e1_row4_col12" class="data row4 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_666e1_level0_row5" class="row_heading level0 row5" >600036.SS</th>
                        <td id="T_666e1_row5_col0" class="data row5 col0" >招商银行</td>
                        <td id="T_666e1_row5_col1" class="data row5 col1" >91.27</td>
                        <td id="T_666e1_row5_col2" class="data row5 col2" >15.46</td>
                        <td id="T_666e1_row5_col3" class="data row5 col3" >43.54</td>
                        <td id="T_666e1_row5_col4" class="data row5 col4" >11.97</td>
                        <td id="T_666e1_row5_col5" class="data row5 col5" >3.28</td>
                        <td id="T_666e1_row5_col6" class="data row5 col6" >11.65</td>
                        <td id="T_666e1_row5_col7" class="data row5 col7" >4.34</td>
                        <td id="T_666e1_row5_col8" class="data row5 col8" >-693.52</td>
                        <td id="T_666e1_row5_col9" class="data row5 col9" >14.53</td>
                        <td id="T_666e1_row5_col10" class="data row5 col10" >17.00</td>
                        <td id="T_666e1_row5_col11" class="data row5 col11" >1.46</td>
                        <td id="T_666e1_row5_col12" class="data row5 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_666e1_level0_row6" class="row_heading level0 row6" >000333.SZ</th>
                        <td id="T_666e1_row6_col0" class="data row6 col0" >美的集团</td>
                        <td id="T_666e1_row6_col1" class="data row6 col1" >65.53</td>
                        <td id="T_666e1_row6_col2" class="data row6 col2" >23.69</td>
                        <td id="T_666e1_row6_col3" class="data row6 col3" >8.31</td>
                        <td id="T_666e1_row6_col4" class="data row6 col4" >5.73</td>
                        <td id="T_666e1_row6_col5" class="data row6 col5" >8.62</td>
                        <td id="T_666e1_row6_col6" class="data row6 col6" >16.39</td>
                        <td id="T_666e1_row6_col7" class="data row6 col7" >6.09</td>
                        <td id="T_666e1_row6_col8" class="data row6 col8" >11.21</td>
                        <td id="T_666e1_row6_col9" class="data row6 col9" >18.81</td>
                        <td id="T_666e1_row6_col10" class="data row6 col10" >24.64</td>
                        <td id="T_666e1_row6_col11" class="data row6 col11" >1.50</td>
                        <td id="T_666e1_row6_col12" class="data row6 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_666e1_level0_row7" class="row_heading level0 row7" >601012.SS</th>
                        <td id="T_666e1_row7_col0" class="data row7 col0" >隆基股份</td>
                        <td id="T_666e1_row7_col1" class="data row7 col1" >59.38</td>
                        <td id="T_666e1_row7_col2" class="data row7 col2" >21.03</td>
                        <td id="T_666e1_row7_col3" class="data row7 col3" >16.28</td>
                        <td id="T_666e1_row7_col4" class="data row7 col4" >49.97</td>
                        <td id="T_666e1_row7_col5" class="data row7 col5" >13.29</td>
                        <td id="T_666e1_row7_col6" class="data row7 col6" >46.72</td>
                        <td id="T_666e1_row7_col7" class="data row7 col7" >7.46</td>
                        <td id="T_666e1_row7_col8" class="data row7 col8" >-97.28</td>
                        <td id="T_666e1_row7_col9" class="data row7 col9" >39.34</td>
                        <td id="T_666e1_row7_col10" class="data row7 col10" >74.12</td>
                        <td id="T_666e1_row7_col11" class="data row7 col11" >1.59</td>
                        <td id="T_666e1_row7_col12" class="data row7 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_666e1_level0_row8" class="row_heading level0 row8" >601398.SS</th>
                        <td id="T_666e1_row8_col0" class="data row8 col0" >工商银行</td>
                        <td id="T_666e1_row8_col1" class="data row8 col1" >91.27</td>
                        <td id="T_666e1_row8_col2" class="data row8 col2" >12.72</td>
                        <td id="T_666e1_row8_col3" class="data row8 col3" >50.13</td>
                        <td id="T_666e1_row8_col4" class="data row8 col4" >0.07</td>
                        <td id="T_666e1_row8_col5" class="data row8 col5" >0.76</td>
                        <td id="T_666e1_row8_col6" class="data row8 col6" >3.38</td>
                        <td id="T_666e1_row8_col7" class="data row8 col7" >0.39</td>
                        <td id="T_666e1_row8_col8" class="data row8 col8" >-104.59</td>
                        <td id="T_666e1_row8_col9" class="data row8 col9" >6.01</td>
                        <td id="T_666e1_row8_col10" class="data row8 col10" >5.82</td>
                        <td id="T_666e1_row8_col11" class="data row8 col11" >1.72</td>
                        <td id="T_666e1_row8_col12" class="data row8 col12" >2021-03-30</td>
            </tr>
            <tr>
                        <th id="T_666e1_level0_row9" class="row_heading level0 row9" >000895.SZ</th>
                        <td id="T_666e1_row9_col0" class="data row9 col0" >双汇发展</td>
                        <td id="T_666e1_row9_col1" class="data row9 col1" >30.46</td>
                        <td id="T_666e1_row9_col2" class="data row9 col2" >31.63</td>
                        <td id="T_666e1_row9_col3" class="data row9 col3" >9.01</td>
                        <td id="T_666e1_row9_col4" class="data row9 col4" >14.21</td>
                        <td id="T_666e1_row9_col5" class="data row9 col5" >0.98</td>
                        <td id="T_666e1_row9_col6" class="data row9 col6" >13.15</td>
                        <td id="T_666e1_row9_col7" class="data row9 col7" >-0.38</td>
                        <td id="T_666e1_row9_col8" class="data row9 col8" >25.11</td>
                        <td id="T_666e1_row9_col9" class="data row9 col9" >19.13</td>
                        <td id="T_666e1_row9_col10" class="data row9 col10" >23.28</td>
                        <td id="T_666e1_row9_col11" class="data row9 col11" >1.77</td>
                        <td id="T_666e1_row9_col12" class="data row9 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_666e1_level0_row10" class="row_heading level0 row10" >600570.SS</th>
                        <td id="T_666e1_row10_col0" class="data row10 col0" >恒生电子</td>
                        <td id="T_666e1_row10_col1" class="data row10 col1" >49.48</td>
                        <td id="T_666e1_row10_col2" class="data row10 col2" >24.06</td>
                        <td id="T_666e1_row10_col3" class="data row10 col3" >26.42</td>
                        <td id="T_666e1_row10_col4" class="data row10 col4" >16.27</td>
                        <td id="T_666e1_row10_col5" class="data row10 col5" >5.69</td>
                        <td id="T_666e1_row10_col6" class="data row10 col6" >49.90</td>
                        <td id="T_666e1_row10_col7" class="data row10 col7" >16.16</td>
                        <td id="T_666e1_row10_col8" class="data row10 col8" >10.32</td>
                        <td id="T_666e1_row10_col9" class="data row10 col9" >58.78</td>
                        <td id="T_666e1_row10_col10" class="data row10 col10" >95.23</td>
                        <td id="T_666e1_row10_col11" class="data row10 col11" >1.91</td>
                        <td id="T_666e1_row10_col12" class="data row10 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_666e1_level0_row11" class="row_heading level0 row11" >600030.SS</th>
                        <td id="T_666e1_row11_col0" class="data row11 col0" >中信证券</td>
                        <td id="T_666e1_row11_col1" class="data row11 col1" >82.35</td>
                        <td id="T_666e1_row11_col2" class="data row11 col2" >7.53</td>
                        <td id="T_666e1_row11_col3" class="data row11 col3" >27.81</td>
                        <td id="T_666e1_row11_col4" class="data row11 col4" >9.51</td>
                        <td id="T_666e1_row11_col5" class="data row11 col5" >8.70</td>
                        <td id="T_666e1_row11_col6" class="data row11 col6" >13.17</td>
                        <td id="T_666e1_row11_col7" class="data row11 col7" >7.02</td>
                        <td id="T_666e1_row11_col8" class="data row11 col8" >50.91</td>
                        <td id="T_666e1_row11_col9" class="data row11 col9" >20.60</td>
                        <td id="T_666e1_row11_col10" class="data row11 col10" >25.32</td>
                        <td id="T_666e1_row11_col11" class="data row11 col11" >1.92</td>
                        <td id="T_666e1_row11_col12" class="data row11 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_666e1_level0_row12" class="row_heading level0 row12" >600000.SS</th>
                        <td id="T_666e1_row12_col0" class="data row12 col0" >浦发银行</td>
                        <td id="T_666e1_row12_col1" class="data row12 col1" >91.88</td>
                        <td id="T_666e1_row12_col2" class="data row12 col2" >11.54</td>
                        <td id="T_666e1_row12_col3" class="data row12 col3" >50.05</td>
                        <td id="T_666e1_row12_col4" class="data row12 col4" >1.01</td>
                        <td id="T_666e1_row12_col5" class="data row12 col5" >2.01</td>
                        <td id="T_666e1_row12_col6" class="data row12 col6" >2.47</td>
                        <td id="T_666e1_row12_col7" class="data row12 col7" >2.29</td>
                        <td id="T_666e1_row12_col8" class="data row12 col8" >-67.43</td>
                        <td id="T_666e1_row12_col9" class="data row12 col9" >5.77</td>
                        <td id="T_666e1_row12_col10" class="data row12 col10" >5.28</td>
                        <td id="T_666e1_row12_col11" class="data row12 col11" >2.14</td>
                        <td id="T_666e1_row12_col12" class="data row12 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_666e1_level0_row13" class="row_heading level0 row13" >000725.SZ</th>
                        <td id="T_666e1_row13_col0" class="data row13 col0" >京东方Ａ</td>
                        <td id="T_666e1_row13_col1" class="data row13 col1" >59.13</td>
                        <td id="T_666e1_row13_col2" class="data row13 col2" >4.95</td>
                        <td id="T_666e1_row13_col3" class="data row13 col3" >4.24</td>
                        <td id="T_666e1_row13_col4" class="data row13 col4" >13.28</td>
                        <td id="T_666e1_row13_col5" class="data row13 col5" >17.54</td>
                        <td id="T_666e1_row13_col6" class="data row13 col6" >21.23</td>
                        <td id="T_666e1_row13_col7" class="data row13 col7" >91.65</td>
                        <td id="T_666e1_row13_col8" class="data row13 col8" >-20.20</td>
                        <td id="T_666e1_row13_col9" class="data row13 col9" >22.27</td>
                        <td id="T_666e1_row13_col10" class="data row13 col10" >46.46</td>
                        <td id="T_666e1_row13_col11" class="data row13 col11" >2.19</td>
                        <td id="T_666e1_row13_col12" class="data row13 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_666e1_level0_row14" class="row_heading level0 row14" >002027.SZ</th>
                        <td id="T_666e1_row14_col0" class="data row14 col0" >分众传媒</td>
                        <td id="T_666e1_row14_col1" class="data row14 col1" >20.21</td>
                        <td id="T_666e1_row14_col2" class="data row14 col2" >34.01</td>
                        <td id="T_666e1_row14_col3" class="data row14 col3" >34.64</td>
                        <td id="T_666e1_row14_col4" class="data row14 col4" >1.40</td>
                        <td id="T_666e1_row14_col5" class="data row14 col5" >13.68</td>
                        <td id="T_666e1_row14_col6" class="data row14 col6" >14.23</td>
                        <td id="T_666e1_row14_col7" class="data row14 col7" >33.23</td>
                        <td id="T_666e1_row14_col8" class="data row14 col8" >23.11</td>
                        <td id="T_666e1_row14_col9" class="data row14 col9" >26.89</td>
                        <td id="T_666e1_row14_col10" class="data row14 col10" >32.99</td>
                        <td id="T_666e1_row14_col11" class="data row14 col11" >2.32</td>
                        <td id="T_666e1_row14_col12" class="data row14 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_666e1_level0_row15" class="row_heading level0 row15" >601899.SS</th>
                        <td id="T_666e1_row15_col0" class="data row15 col0" >紫金矿业</td>
                        <td id="T_666e1_row15_col1" class="data row15 col1" >59.08</td>
                        <td id="T_666e1_row15_col2" class="data row15 col2" >10.01</td>
                        <td id="T_666e1_row15_col3" class="data row15 col3" >3.63</td>
                        <td id="T_666e1_row15_col4" class="data row15 col4" >22.17</td>
                        <td id="T_666e1_row15_col5" class="data row15 col5" >6.61</td>
                        <td id="T_666e1_row15_col6" class="data row15 col6" >24.43</td>
                        <td id="T_666e1_row15_col7" class="data row15 col7" >22.60</td>
                        <td id="T_666e1_row15_col8" class="data row15 col8" >-110.17</td>
                        <td id="T_666e1_row15_col9" class="data row15 col9" >35.54</td>
                        <td id="T_666e1_row15_col10" class="data row15 col10" >57.71</td>
                        <td id="T_666e1_row15_col11" class="data row15 col11" >2.36</td>
                        <td id="T_666e1_row15_col12" class="data row15 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_666e1_level0_row16" class="row_heading level0 row16" >000858.SZ</th>
                        <td id="T_666e1_row16_col0" class="data row16 col0" >五 粮 液</td>
                        <td id="T_666e1_row16_col1" class="data row16 col1" >22.95</td>
                        <td id="T_666e1_row16_col2" class="data row16 col2" >21.48</td>
                        <td id="T_666e1_row16_col3" class="data row16 col3" >33.75</td>
                        <td id="T_666e1_row16_col4" class="data row16 col4" >24.06</td>
                        <td id="T_666e1_row16_col5" class="data row16 col5" >7.13</td>
                        <td id="T_666e1_row16_col6" class="data row16 col6" >27.68</td>
                        <td id="T_666e1_row16_col7" class="data row16 col7" >8.11</td>
                        <td id="T_666e1_row16_col8" class="data row16 col8" >22.79</td>
                        <td id="T_666e1_row16_col9" class="data row16 col9" >56.73</td>
                        <td id="T_666e1_row16_col10" class="data row16 col10" >81.03</td>
                        <td id="T_666e1_row16_col11" class="data row16 col11" >2.93</td>
                        <td id="T_666e1_row16_col12" class="data row16 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_666e1_level0_row17" class="row_heading level0 row17" >600900.SS</th>
                        <td id="T_666e1_row17_col0" class="data row17 col0" >长江电力</td>
                        <td id="T_666e1_row17_col1" class="data row17 col1" >46.10</td>
                        <td id="T_666e1_row17_col2" class="data row17 col2" >15.52</td>
                        <td id="T_666e1_row17_col3" class="data row17 col3" >44.31</td>
                        <td id="T_666e1_row17_col4" class="data row17 col4" >5.12</td>
                        <td id="T_666e1_row17_col5" class="data row17 col5" >0.84</td>
                        <td id="T_666e1_row17_col6" class="data row17 col6" >6.31</td>
                        <td id="T_666e1_row17_col7" class="data row17 col7" >2.20</td>
                        <td id="T_666e1_row17_col8" class="data row17 col8" >0.54</td>
                        <td id="T_666e1_row17_col9" class="data row17 col9" >16.54</td>
                        <td id="T_666e1_row17_col10" class="data row17 col10" >19.50</td>
                        <td id="T_666e1_row17_col11" class="data row17 col11" >3.09</td>
                        <td id="T_666e1_row17_col12" class="data row17 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_666e1_level0_row18" class="row_heading level0 row18" >600276.SS</th>
                        <td id="T_666e1_row18_col0" class="data row18 col0" >恒瑞医药</td>
                        <td id="T_666e1_row18_col1" class="data row18 col1" >11.35</td>
                        <td id="T_666e1_row18_col2" class="data row18 col2" >20.95</td>
                        <td id="T_666e1_row18_col3" class="data row18 col3" >23.07</td>
                        <td id="T_666e1_row18_col4" class="data row18 col4" >26.23</td>
                        <td id="T_666e1_row18_col5" class="data row18 col5" >5.06</td>
                        <td id="T_666e1_row18_col6" class="data row18 col6" >25.41</td>
                        <td id="T_666e1_row18_col7" class="data row18 col7" >2.86</td>
                        <td id="T_666e1_row18_col8" class="data row18 col8" >12.33</td>
                        <td id="T_666e1_row18_col9" class="data row18 col9" >67.09</td>
                        <td id="T_666e1_row18_col10" class="data row18 col10" >93.07</td>
                        <td id="T_666e1_row18_col11" class="data row18 col11" >3.66</td>
                        <td id="T_666e1_row18_col12" class="data row18 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_666e1_level0_row19" class="row_heading level0 row19" >600519.SS</th>
                        <td id="T_666e1_row19_col0" class="data row19 col0" >贵州茅台</td>
                        <td id="T_666e1_row19_col1" class="data row19 col1" >21.40</td>
                        <td id="T_666e1_row19_col2" class="data row19 col2" >30.01</td>
                        <td id="T_666e1_row19_col3" class="data row19 col3" >47.94</td>
                        <td id="T_666e1_row19_col4" class="data row19 col4" >17.87</td>
                        <td id="T_666e1_row19_col5" class="data row19 col5" >3.02</td>
                        <td id="T_666e1_row19_col6" class="data row19 col6" >20.13</td>
                        <td id="T_666e1_row19_col7" class="data row19 col7" >1.84</td>
                        <td id="T_666e1_row19_col8" class="data row19 col8" >37.59</td>
                        <td id="T_666e1_row19_col9" class="data row19 col9" >59.47</td>
                        <td id="T_666e1_row19_col10" class="data row19 col10" >75.33</td>
                        <td id="T_666e1_row19_col11" class="data row19 col11" >3.74</td>
                        <td id="T_666e1_row19_col12" class="data row19 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_666e1_level0_row20" class="row_heading level0 row20" >002415.SZ</th>
                        <td id="T_666e1_row20_col0" class="data row20 col0" >海康威视</td>
                        <td id="T_666e1_row20_col1" class="data row20 col1" >38.58</td>
                        <td id="T_666e1_row20_col2" class="data row20 col2" >28.43</td>
                        <td id="T_666e1_row20_col3" class="data row20 col3" >21.96</td>
                        <td id="T_666e1_row20_col4" class="data row20 col4" >14.92</td>
                        <td id="T_666e1_row20_col5" class="data row20 col5" >7.18</td>
                        <td id="T_666e1_row20_col6" class="data row20 col6" >12.60</td>
                        <td id="T_666e1_row20_col7" class="data row20 col7" >5.03</td>
                        <td id="T_666e1_row20_col8" class="data row20 col8" >49.38</td>
                        <td id="T_666e1_row20_col9" class="data row20 col9" >40.45</td>
                        <td id="T_666e1_row20_col10" class="data row20 col10" >49.06</td>
                        <td id="T_666e1_row20_col11" class="data row20 col11" >3.89</td>
                        <td id="T_666e1_row20_col12" class="data row20 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_666e1_level0_row21" class="row_heading level0 row21" >603288.SS</th>
                        <td id="T_666e1_row21_col0" class="data row21 col0" >海天味业</td>
                        <td id="T_666e1_row21_col1" class="data row21 col1" >31.72</td>
                        <td id="T_666e1_row21_col2" class="data row21 col2" >31.42</td>
                        <td id="T_666e1_row21_col3" class="data row21 col3" >26.24</td>
                        <td id="T_666e1_row21_col4" class="data row21 col4" >16.05</td>
                        <td id="T_666e1_row21_col5" class="data row21 col5" >5.59</td>
                        <td id="T_666e1_row21_col6" class="data row21 col6" >21.95</td>
                        <td id="T_666e1_row21_col7" class="data row21 col7" >5.32</td>
                        <td id="T_666e1_row21_col8" class="data row21 col8" >11.37</td>
                        <td id="T_666e1_row21_col9" class="data row21 col9" >66.07</td>
                        <td id="T_666e1_row21_col10" class="data row21 col10" >90.64</td>
                        <td id="T_666e1_row21_col11" class="data row21 col11" >4.13</td>
                        <td id="T_666e1_row21_col12" class="data row21 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_666e1_level0_row22" class="row_heading level0 row22" >601888.SS</th>
                        <td id="T_666e1_row22_col0" class="data row22 col0" >中国中免</td>
                        <td id="T_666e1_row22_col1" class="data row22 col1" >37.55</td>
                        <td id="T_666e1_row22_col2" class="data row22 col2" >21.92</td>
                        <td id="T_666e1_row22_col3" class="data row22 col3" >9.18</td>
                        <td id="T_666e1_row22_col4" class="data row22 col4" >25.94</td>
                        <td id="T_666e1_row22_col5" class="data row22 col5" >19.96</td>
                        <td id="T_666e1_row22_col6" class="data row22 col6" >34.84</td>
                        <td id="T_666e1_row22_col7" class="data row22 col7" >48.36</td>
                        <td id="T_666e1_row22_col8" class="data row22 col8" >105.58</td>
                        <td id="T_666e1_row22_col9" class="data row22 col9" >69.24</td>
                        <td id="T_666e1_row22_col10" class="data row22 col10" >152.21</td>
                        <td id="T_666e1_row22_col11" class="data row22 col11" >4.37</td>
                        <td id="T_666e1_row22_col12" class="data row22 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_666e1_level0_row23" class="row_heading level0 row23" >002594.SZ</th>
                        <td id="T_666e1_row23_col0" class="data row23 col0" >比亚迪</td>
                        <td id="T_666e1_row23_col1" class="data row23 col1" >67.94</td>
                        <td id="T_666e1_row23_col2" class="data row23 col2" >5.68</td>
                        <td id="T_666e1_row23_col3" class="data row23 col3" >2.49</td>
                        <td id="T_666e1_row23_col4" class="data row23 col4" >14.53</td>
                        <td id="T_666e1_row23_col5" class="data row23 col5" >13.61</td>
                        <td id="T_666e1_row23_col6" class="data row23 col6" >29.57</td>
                        <td id="T_666e1_row23_col7" class="data row23 col7" >2.95</td>
                        <td id="T_666e1_row23_col8" class="data row23 col8" >-231.87</td>
                        <td id="T_666e1_row23_col9" class="data row23 col9" >124.28</td>
                        <td id="T_666e1_row23_col10" class="data row23 col10" >160.91</td>
                        <td id="T_666e1_row23_col11" class="data row23 col11" >5.44</td>
                        <td id="T_666e1_row23_col12" class="data row23 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_666e1_level0_row24" class="row_heading level0 row24" >600887.SS</th>
                        <td id="T_666e1_row24_col0" class="data row24 col0" >伊利股份</td>
                        <td id="T_666e1_row24_col1" class="data row24 col1" >57.09</td>
                        <td id="T_666e1_row24_col2" class="data row24 col2" >24.20</td>
                        <td id="T_666e1_row24_col3" class="data row24 col3" >7.98</td>
                        <td id="T_666e1_row24_col4" class="data row24 col4" >12.56</td>
                        <td id="T_666e1_row24_col5" class="data row24 col5" >6.93</td>
                        <td id="T_666e1_row24_col6" class="data row24 col6" >5.69</td>
                        <td id="T_666e1_row24_col7" class="data row24 col7" >23.85</td>
                        <td id="T_666e1_row24_col8" class="data row24 col8" >-216.14</td>
                        <td id="T_666e1_row24_col9" class="data row24 col9" >27.32</td>
                        <td id="T_666e1_row24_col10" class="data row24 col10" >36.40</td>
                        <td id="T_666e1_row24_col11" class="data row24 col11" >6.40</td>
                        <td id="T_666e1_row24_col12" class="data row24 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_666e1_level0_row25" class="row_heading level0 row25" >300750.SZ</th>
                        <td id="T_666e1_row25_col0" class="data row25 col0" >宁德时代</td>
                        <td id="T_666e1_row25_col1" class="data row25 col1" >55.82</td>
                        <td id="T_666e1_row25_col2" class="data row25 col2" >11.66</td>
                        <td id="T_666e1_row25_col3" class="data row25 col3" >12.97</td>
                        <td id="T_666e1_row25_col4" class="data row25 col4" >37.54</td>
                        <td id="T_666e1_row25_col5" class="data row25 col5" >20.14</td>
                        <td id="T_666e1_row25_col6" class="data row25 col6" >14.80</td>
                        <td id="T_666e1_row25_col7" class="data row25 col7" >21.71</td>
                        <td id="T_666e1_row25_col8" class="data row25 col8" >-61.23</td>
                        <td id="T_666e1_row25_col9" class="data row25 col9" >145.04</td>
                        <td id="T_666e1_row25_col10" class="data row25 col10" >231.34</td>
                        <td id="T_666e1_row25_col11" class="data row25 col11" >15.63</td>
                        <td id="T_666e1_row25_col12" class="data row25 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_666e1_level0_row26" class="row_heading level0 row26" >000651.SZ</th>
                        <td id="T_666e1_row26_col0" class="data row26 col0" >格力电器</td>
                        <td id="T_666e1_row26_col1" class="data row26 col1" >58.14</td>
                        <td id="T_666e1_row26_col2" class="data row26 col2" >26.13</td>
                        <td id="T_666e1_row26_col3" class="data row26 col3" >13.45</td>
                        <td id="T_666e1_row26_col4" class="data row26 col4" >6.56</td>
                        <td id="T_666e1_row26_col5" class="data row26 col5" >-21.30</td>
                        <td id="T_666e1_row26_col6" class="data row26 col6" >0.34</td>
                        <td id="T_666e1_row26_col7" class="data row26 col7" >-13.16</td>
                        <td id="T_666e1_row26_col8" class="data row26 col8" >9.95</td>
                        <td id="T_666e1_row26_col9" class="data row26 col9" >13.87</td>
                        <td id="T_666e1_row26_col10" class="data row26 col10" >14.11</td>
                        <td id="T_666e1_row26_col11" class="data row26 col11" >41.65</td>
                        <td id="T_666e1_row26_col12" class="data row26 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_666e1_level0_row27" class="row_heading level0 row27" >600340.SS</th>
                        <td id="T_666e1_row27_col0" class="data row27 col0" >华夏幸福</td>
                        <td id="T_666e1_row27_col1" class="data row27 col1" >81.29</td>
                        <td id="T_666e1_row27_col2" class="data row27 col2" >21.44</td>
                        <td id="T_666e1_row27_col3" class="data row27 col3" >11.59</td>
                        <td id="T_666e1_row27_col4" class="data row27 col4" >20.76</td>
                        <td id="T_666e1_row27_col5" class="data row27 col5" >-11.43</td>
                        <td id="T_666e1_row27_col6" class="data row27 col6" >-5.88</td>
                        <td id="T_666e1_row27_col7" class="data row27 col7" >-179.20</td>
                        <td id="T_666e1_row27_col8" class="data row27 col8" >57.88</td>
                        <td id="T_666e1_row27_col9" class="data row27 col9" >5.59</td>
                        <td id="T_666e1_row27_col10" class="data row27 col10" >2.16</td>
                        <td id="T_666e1_row27_col11" class="data row27 col11" >-</td>
                        <td id="T_666e1_row27_col12" class="data row27 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_666e1_level0_row28" class="row_heading level0 row28" >000625.SZ</th>
                        <td id="T_666e1_row28_col0" class="data row28 col0" >长安汽车</td>
                        <td id="T_666e1_row28_col1" class="data row28 col1" >55.77</td>
                        <td id="T_666e1_row28_col2" class="data row28 col2" >4.17</td>
                        <td id="T_666e1_row28_col3" class="data row28 col3" >2.53</td>
                        <td id="T_666e1_row28_col4" class="data row28 col4" >3.04</td>
                        <td id="T_666e1_row28_col5" class="data row28 col5" >24.20</td>
                        <td id="T_666e1_row28_col6" class="data row28 col6" >-268.29</td>
                        <td id="T_666e1_row28_col7" class="data row28 col7" >6.69</td>
                        <td id="T_666e1_row28_col8" class="data row28 col8" >-304.21</td>
                        <td id="T_666e1_row28_col9" class="data row28 col9" >33.40</td>
                        <td id="T_666e1_row28_col10" class="data row28 col10" >53.58</td>
                        <td id="T_666e1_row28_col11" class="data row28 col11" >-</td>
                        <td id="T_666e1_row28_col12" class="data row28 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_666e1_level0_row29" class="row_heading level0 row29" >600066.SS</th>
                        <td id="T_666e1_row29_col0" class="data row29 col0" >宇通客车</td>
                        <td id="T_666e1_row29_col1" class="data row29 col1" >53.64</td>
                        <td id="T_666e1_row29_col2" class="data row29 col2" >12.11</td>
                        <td id="T_666e1_row29_col3" class="data row29 col3" >6.35</td>
                        <td id="T_666e1_row29_col4" class="data row29 col4" >-12.40</td>
                        <td id="T_666e1_row29_col5" class="data row29 col5" >3.78</td>
                        <td id="T_666e1_row29_col6" class="data row29 col6" >-38.50</td>
                        <td id="T_666e1_row29_col7" class="data row29 col7" >6.31</td>
                        <td id="T_666e1_row29_col8" class="data row29 col8" >-3.73</td>
                        <td id="T_666e1_row29_col9" class="data row29 col9" >58.85</td>
                        <td id="T_666e1_row29_col10" class="data row29 col10" >15.33</td>
                        <td id="T_666e1_row29_col11" class="data row29 col11" >-</td>
                        <td id="T_666e1_row29_col12" class="data row29 col12" >2021-03-31</td>
            </tr>
    </tbody></table>



## 美股

### 指标筛选

1. 负债率 < 50%
2. 应收比 < 20%
3. 商誉比 < 20%
4. ROE >= 20%
5. 利润率 >= 20%
6. 收入增长 >= 15% 且 盈利增长 >= 15%

注: 非美国公司的DCF和盈利折现使用的是所在国货币，市值为美元，未计算折价率




<style  type="text/css" >
#T_c9ae1_row0_col0,#T_c9ae1_row0_col1,#T_c9ae1_row0_col2,#T_c9ae1_row0_col3,#T_c9ae1_row0_col4,#T_c9ae1_row0_col6,#T_c9ae1_row0_col9,#T_c9ae1_row0_col10,#T_c9ae1_row0_col11,#T_c9ae1_row0_col12,#T_c9ae1_row1_col0,#T_c9ae1_row1_col1,#T_c9ae1_row1_col2,#T_c9ae1_row1_col3,#T_c9ae1_row1_col4,#T_c9ae1_row1_col6,#T_c9ae1_row1_col8,#T_c9ae1_row1_col9,#T_c9ae1_row1_col10,#T_c9ae1_row1_col11,#T_c9ae1_row1_col12,#T_c9ae1_row2_col0,#T_c9ae1_row2_col1,#T_c9ae1_row2_col2,#T_c9ae1_row2_col3,#T_c9ae1_row2_col4,#T_c9ae1_row2_col5,#T_c9ae1_row2_col6,#T_c9ae1_row2_col7,#T_c9ae1_row2_col8,#T_c9ae1_row2_col9,#T_c9ae1_row2_col10,#T_c9ae1_row2_col11,#T_c9ae1_row2_col12,#T_c9ae1_row3_col0,#T_c9ae1_row3_col1,#T_c9ae1_row3_col2,#T_c9ae1_row3_col3,#T_c9ae1_row3_col4,#T_c9ae1_row3_col5,#T_c9ae1_row3_col6,#T_c9ae1_row3_col8,#T_c9ae1_row3_col9,#T_c9ae1_row3_col10,#T_c9ae1_row3_col11,#T_c9ae1_row3_col12,#T_c9ae1_row4_col0,#T_c9ae1_row4_col1,#T_c9ae1_row4_col2,#T_c9ae1_row4_col3,#T_c9ae1_row4_col4,#T_c9ae1_row4_col5,#T_c9ae1_row4_col6,#T_c9ae1_row4_col7,#T_c9ae1_row4_col8,#T_c9ae1_row4_col9,#T_c9ae1_row4_col10,#T_c9ae1_row4_col11,#T_c9ae1_row4_col12,#T_c9ae1_row5_col0,#T_c9ae1_row5_col1,#T_c9ae1_row5_col2,#T_c9ae1_row5_col3,#T_c9ae1_row5_col4,#T_c9ae1_row5_col5,#T_c9ae1_row5_col6,#T_c9ae1_row5_col7,#T_c9ae1_row5_col8,#T_c9ae1_row5_col9,#T_c9ae1_row5_col10,#T_c9ae1_row5_col11,#T_c9ae1_row5_col12,#T_c9ae1_row6_col0,#T_c9ae1_row6_col1,#T_c9ae1_row6_col2,#T_c9ae1_row6_col3,#T_c9ae1_row6_col4,#T_c9ae1_row6_col5,#T_c9ae1_row6_col6,#T_c9ae1_row6_col8,#T_c9ae1_row6_col9,#T_c9ae1_row6_col10,#T_c9ae1_row6_col11,#T_c9ae1_row6_col12,#T_c9ae1_row7_col0,#T_c9ae1_row7_col1,#T_c9ae1_row7_col2,#T_c9ae1_row7_col3,#T_c9ae1_row7_col4,#T_c9ae1_row7_col5,#T_c9ae1_row7_col6,#T_c9ae1_row7_col8,#T_c9ae1_row7_col9,#T_c9ae1_row7_col10,#T_c9ae1_row7_col11,#T_c9ae1_row7_col12,#T_c9ae1_row8_col0,#T_c9ae1_row8_col1,#T_c9ae1_row8_col2,#T_c9ae1_row8_col3,#T_c9ae1_row8_col4,#T_c9ae1_row8_col6,#T_c9ae1_row8_col8,#T_c9ae1_row8_col9,#T_c9ae1_row8_col10,#T_c9ae1_row8_col11,#T_c9ae1_row8_col12,#T_c9ae1_row9_col0,#T_c9ae1_row9_col1,#T_c9ae1_row9_col2,#T_c9ae1_row9_col3,#T_c9ae1_row9_col4,#T_c9ae1_row9_col5,#T_c9ae1_row9_col6,#T_c9ae1_row9_col7,#T_c9ae1_row9_col8,#T_c9ae1_row9_col9,#T_c9ae1_row9_col10,#T_c9ae1_row9_col11,#T_c9ae1_row9_col12,#T_c9ae1_row10_col0,#T_c9ae1_row10_col1,#T_c9ae1_row10_col2,#T_c9ae1_row10_col3,#T_c9ae1_row10_col4,#T_c9ae1_row10_col5,#T_c9ae1_row10_col6,#T_c9ae1_row10_col8,#T_c9ae1_row10_col9,#T_c9ae1_row10_col10,#T_c9ae1_row10_col11,#T_c9ae1_row10_col12,#T_c9ae1_row11_col0,#T_c9ae1_row11_col1,#T_c9ae1_row11_col2,#T_c9ae1_row11_col3,#T_c9ae1_row11_col4,#T_c9ae1_row11_col5,#T_c9ae1_row11_col6,#T_c9ae1_row11_col7,#T_c9ae1_row11_col8,#T_c9ae1_row11_col9,#T_c9ae1_row11_col10,#T_c9ae1_row11_col11,#T_c9ae1_row11_col12{
            color:  black;
        }#T_c9ae1_row0_col5,#T_c9ae1_row0_col7,#T_c9ae1_row0_col8,#T_c9ae1_row1_col5,#T_c9ae1_row1_col7,#T_c9ae1_row3_col7,#T_c9ae1_row6_col7,#T_c9ae1_row7_col7,#T_c9ae1_row8_col5,#T_c9ae1_row8_col7,#T_c9ae1_row10_col7{
            color:  red;
        }</style><table id="T_c9ae1_" ><thead>    <tr>        <th class="blank level0" ></th>        <th class="col_heading level0 col0" >名称</th>        <th class="col_heading level0 col1" >负债率</th>        <th class="col_heading level0 col2" >ROE</th>        <th class="col_heading level0 col3" >利润率</th>        <th class="col_heading level0 col4" >收入增长</th>        <th class="col_heading level0 col5" >收入增长TTM</th>        <th class="col_heading level0 col6" >盈利增长</th>        <th class="col_heading level0 col7" >盈利增长TTM</th>        <th class="col_heading level0 col8" >FCF增长</th>        <th class="col_heading level0 col9" >PE</th>        <th class="col_heading level0 col10" >PEm</th>        <th class="col_heading level0 col11" >PEG</th>        <th class="col_heading level0 col12" >季报日期</th>    </tr>    <tr>        <th class="index_name level0" >Symbol</th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>    </tr></thead><tbody>
                <tr>
                        <th id="T_c9ae1_level0_row0" class="row_heading level0 row0" >PKE</th>
                        <td id="T_c9ae1_row0_col0" class="data row0 col0" >Park Aerospace Corp.</td>
                        <td id="T_c9ae1_row0_col1" class="data row0 col1" >17.53</td>
                        <td id="T_c9ae1_row0_col2" class="data row0 col2" >24.61</td>
                        <td id="T_c9ae1_row0_col3" class="data row0 col3" >79.60</td>
                        <td id="T_c9ae1_row0_col4" class="data row0 col4" >23.61</td>
                        <td id="T_c9ae1_row0_col5" class="data row0 col5" >-21.14</td>
                        <td id="T_c9ae1_row0_col6" class="data row0 col6" >160.53</td>
                        <td id="T_c9ae1_row0_col7" class="data row0 col7" >-34.92</td>
                        <td id="T_c9ae1_row0_col8" class="data row0 col8" >-46.80</td>
                        <td id="T_c9ae1_row0_col9" class="data row0 col9" >50.43</td>
                        <td id="T_c9ae1_row0_col10" class="data row0 col10" >8.12</td>
                        <td id="T_c9ae1_row0_col11" class="data row0 col11" >0.05</td>
                        <td id="T_c9ae1_row0_col12" class="data row0 col12" >2020-11-29</td>
            </tr>
            <tr>
                        <th id="T_c9ae1_level0_row1" class="row_heading level0 row1" >MMAC</th>
                        <td id="T_c9ae1_row1_col0" class="data row1 col0" >MMA Capital Holdings</td>
                        <td id="T_c9ae1_row1_col1" class="data row1 col1" >45.62</td>
                        <td id="T_c9ae1_row1_col2" class="data row1 col2" >20.39</td>
                        <td id="T_c9ae1_row1_col3" class="data row1 col3" >126.92</td>
                        <td id="T_c9ae1_row1_col4" class="data row1 col4" >131.63</td>
                        <td id="T_c9ae1_row1_col5" class="data row1 col5" >-27.47</td>
                        <td id="T_c9ae1_row1_col6" class="data row1 col6" >62.74</td>
                        <td id="T_c9ae1_row1_col7" class="data row1 col7" >-91.71</td>
                        <td id="T_c9ae1_row1_col8" class="data row1 col8" >-</td>
                        <td id="T_c9ae1_row1_col9" class="data row1 col9" >18.73</td>
                        <td id="T_c9ae1_row1_col10" class="data row1 col10" >3.27</td>
                        <td id="T_c9ae1_row1_col11" class="data row1 col11" >0.05</td>
                        <td id="T_c9ae1_row1_col12" class="data row1 col12" >2020-12-31</td>
            </tr>
            <tr>
                        <th id="T_c9ae1_level0_row2" class="row_heading level0 row2" >VRTX</th>
                        <td id="T_c9ae1_row2_col0" class="data row2 col0" >Vertex Pharmaceutica</td>
                        <td id="T_c9ae1_row2_col1" class="data row2 col1" >26.08</td>
                        <td id="T_c9ae1_row2_col2" class="data row2 col2" >27.71</td>
                        <td id="T_c9ae1_row2_col3" class="data row2 col3" >37.84</td>
                        <td id="T_c9ae1_row2_col4" class="data row2 col4" >36.04</td>
                        <td id="T_c9ae1_row2_col5" class="data row2 col5" >3.37</td>
                        <td id="T_c9ae1_row2_col6" class="data row2 col6" >260.79</td>
                        <td id="T_c9ae1_row2_col7" class="data row2 col7" >1.86</td>
                        <td id="T_c9ae1_row2_col8" class="data row2 col8" >61.71</td>
                        <td id="T_c9ae1_row2_col9" class="data row2 col9" >20.01</td>
                        <td id="T_c9ae1_row2_col10" class="data row2 col10" >34.79</td>
                        <td id="T_c9ae1_row2_col11" class="data row2 col11" >0.13</td>
                        <td id="T_c9ae1_row2_col12" class="data row2 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_c9ae1_level0_row3" class="row_heading level0 row3" >EXEL</th>
                        <td id="T_c9ae1_row3_col0" class="data row3 col0" >Exelixis Inc. Common</td>
                        <td id="T_c9ae1_row3_col1" class="data row3 col1" >12.08</td>
                        <td id="T_c9ae1_row3_col2" class="data row3 col2" >33.18</td>
                        <td id="T_c9ae1_row3_col3" class="data row3 col3" >39.85</td>
                        <td id="T_c9ae1_row3_col4" class="data row3 col4" >34.70</td>
                        <td id="T_c9ae1_row3_col5" class="data row3 col5" >2.04</td>
                        <td id="T_c9ae1_row3_col6" class="data row3 col6" >76.26</td>
                        <td id="T_c9ae1_row3_col7" class="data row3 col7" >-65.18</td>
                        <td id="T_c9ae1_row3_col8" class="data row3 col8" >44.63</td>
                        <td id="T_c9ae1_row3_col9" class="data row3 col9" >63.91</td>
                        <td id="T_c9ae1_row3_col10" class="data row3 col10" >21.94</td>
                        <td id="T_c9ae1_row3_col11" class="data row3 col11" >0.29</td>
                        <td id="T_c9ae1_row3_col12" class="data row3 col12" >2020-12-31</td>
            </tr>
            <tr>
                        <th id="T_c9ae1_level0_row4" class="row_heading level0 row4" >APPF</th>
                        <td id="T_c9ae1_row4_col0" class="data row4 col0" >AppFolio Inc. Class </td>
                        <td id="T_c9ae1_row4_col1" class="data row4 col1" >26.59</td>
                        <td id="T_c9ae1_row4_col2" class="data row4 col2" >29.01</td>
                        <td id="T_c9ae1_row4_col3" class="data row4 col3" >20.63</td>
                        <td id="T_c9ae1_row4_col4" class="data row4 col4" >29.33</td>
                        <td id="T_c9ae1_row4_col5" class="data row4 col5" >21.11</td>
                        <td id="T_c9ae1_row4_col6" class="data row4 col6" >174.60</td>
                        <td id="T_c9ae1_row4_col7" class="data row4 col7" >336.59</td>
                        <td id="T_c9ae1_row4_col8" class="data row4 col8" >3.65</td>
                        <td id="T_c9ae1_row4_col9" class="data row4 col9" >30.21</td>
                        <td id="T_c9ae1_row4_col10" class="data row4 col10" >82.38</td>
                        <td id="T_c9ae1_row4_col11" class="data row4 col11" >0.47</td>
                        <td id="T_c9ae1_row4_col12" class="data row4 col12" >2020-12-31</td>
            </tr>
            <tr>
                        <th id="T_c9ae1_level0_row5" class="row_heading level0 row5" >INMD</th>
                        <td id="T_c9ae1_row5_col0" class="data row5 col0" >InMode Ltd. Ordinary</td>
                        <td id="T_c9ae1_row5_col1" class="data row5 col1" >13.62</td>
                        <td id="T_c9ae1_row5_col2" class="data row5 col2" >40.33</td>
                        <td id="T_c9ae1_row5_col3" class="data row5 col3" >28.59</td>
                        <td id="T_c9ae1_row5_col4" class="data row5 col4" >58.43</td>
                        <td id="T_c9ae1_row5_col5" class="data row5 col5" >12.17</td>
                        <td id="T_c9ae1_row5_col6" class="data row5 col6" >116.57</td>
                        <td id="T_c9ae1_row5_col7" class="data row5 col7" >26.94</td>
                        <td id="T_c9ae1_row5_col8" class="data row5 col8" >83.23</td>
                        <td id="T_c9ae1_row5_col9" class="data row5 col9" >73.48</td>
                        <td id="T_c9ae1_row5_col10" class="data row5 col10" >77.73</td>
                        <td id="T_c9ae1_row5_col11" class="data row5 col11" >0.67</td>
                        <td id="T_c9ae1_row5_col12" class="data row5 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_c9ae1_level0_row6" class="row_heading level0 row6" >NTES</th>
                        <td id="T_c9ae1_row6_col0" class="data row6 col0" >NetEase Inc. America</td>
                        <td id="T_c9ae1_row6_col1" class="data row6 col1" >33.89</td>
                        <td id="T_c9ae1_row6_col2" class="data row6 col2" >21.57</td>
                        <td id="T_c9ae1_row6_col3" class="data row6 col3" >22.09</td>
                        <td id="T_c9ae1_row6_col4" class="data row6 col4" >18.43</td>
                        <td id="T_c9ae1_row6_col5" class="data row6 col5" >24.35</td>
                        <td id="T_c9ae1_row6_col6" class="data row6 col6" >53.15</td>
                        <td id="T_c9ae1_row6_col7" class="data row6 col7" >-43.20</td>
                        <td id="T_c9ae1_row6_col8" class="data row6 col8" >33.70</td>
                        <td id="T_c9ae1_row6_col9" class="data row6 col9" >41.17</td>
                        <td id="T_c9ae1_row6_col10" class="data row6 col10" >39.74</td>
                        <td id="T_c9ae1_row6_col11" class="data row6 col11" >0.75</td>
                        <td id="T_c9ae1_row6_col12" class="data row6 col12" >2020-12-31</td>
            </tr>
            <tr>
                        <th id="T_c9ae1_level0_row7" class="row_heading level0 row7" >EDTK</th>
                        <td id="T_c9ae1_row7_col0" class="data row7 col0" >Skillful Craftsman E</td>
                        <td id="T_c9ae1_row7_col1" class="data row7 col1" >38.97</td>
                        <td id="T_c9ae1_row7_col2" class="data row7 col2" >45.21</td>
                        <td id="T_c9ae1_row7_col3" class="data row7 col3" >36.78</td>
                        <td id="T_c9ae1_row7_col4" class="data row7 col4" >40.69</td>
                        <td id="T_c9ae1_row7_col5" class="data row7 col5" >6.62</td>
                        <td id="T_c9ae1_row7_col6" class="data row7 col6" >29.67</td>
                        <td id="T_c9ae1_row7_col7" class="data row7 col7" >-7.43</td>
                        <td id="T_c9ae1_row7_col8" class="data row7 col8" >83.37</td>
                        <td id="T_c9ae1_row7_col9" class="data row7 col9" >-</td>
                        <td id="T_c9ae1_row7_col10" class="data row7 col10" >22.21</td>
                        <td id="T_c9ae1_row7_col11" class="data row7 col11" >0.75</td>
                        <td id="T_c9ae1_row7_col12" class="data row7 col12" >2020-09-30</td>
            </tr>
            <tr>
                        <th id="T_c9ae1_level0_row8" class="row_heading level0 row8" >TPL</th>
                        <td id="T_c9ae1_row8_col0" class="data row8 col0" >Texas Pacific Land C</td>
                        <td id="T_c9ae1_row8_col1" class="data row8 col1" >15.12</td>
                        <td id="T_c9ae1_row8_col2" class="data row8 col2" >69.19</td>
                        <td id="T_c9ae1_row8_col3" class="data row8 col3" >64.09</td>
                        <td id="T_c9ae1_row8_col4" class="data row8 col4" >39.88</td>
                        <td id="T_c9ae1_row8_col5" class="data row8 col5" >-38.33</td>
                        <td id="T_c9ae1_row8_col6" class="data row8 col6" >40.97</td>
                        <td id="T_c9ae1_row8_col7" class="data row8 col7" >-44.77</td>
                        <td id="T_c9ae1_row8_col8" class="data row8 col8" >57.34</td>
                        <td id="T_c9ae1_row8_col9" class="data row8 col9" >65.48</td>
                        <td id="T_c9ae1_row8_col10" class="data row8 col10" >57.52</td>
                        <td id="T_c9ae1_row8_col11" class="data row8 col11" >1.40</td>
                        <td id="T_c9ae1_row8_col12" class="data row8 col12" >2020-12-31</td>
            </tr>
            <tr>
                        <th id="T_c9ae1_level0_row9" class="row_heading level0 row9" >FB</th>
                        <td id="T_c9ae1_row9_col0" class="data row9 col0" >Facebook Inc. Class </td>
                        <td id="T_c9ae1_row9_col1" class="data row9 col1" >19.47</td>
                        <td id="T_c9ae1_row9_col2" class="data row9 col2" >22.18</td>
                        <td id="T_c9ae1_row9_col3" class="data row9 col3" >34.71</td>
                        <td id="T_c9ae1_row9_col4" class="data row9 col4" >28.52</td>
                        <td id="T_c9ae1_row9_col5" class="data row9 col5" >9.81</td>
                        <td id="T_c9ae1_row9_col6" class="data row9 col6" >26.68</td>
                        <td id="T_c9ae1_row9_col7" class="data row9 col7" >15.76</td>
                        <td id="T_c9ae1_row9_col8" class="data row9 col8" >12.46</td>
                        <td id="T_c9ae1_row9_col9" class="data row9 col9" >28.31</td>
                        <td id="T_c9ae1_row9_col10" class="data row9 col10" >43.73</td>
                        <td id="T_c9ae1_row9_col11" class="data row9 col11" >1.64</td>
                        <td id="T_c9ae1_row9_col12" class="data row9 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_c9ae1_level0_row10" class="row_heading level0 row10" >OCG</th>
                        <td id="T_c9ae1_row10_col0" class="data row10 col0" >Oriental Culture Hol</td>
                        <td id="T_c9ae1_row10_col1" class="data row10 col1" >18.34</td>
                        <td id="T_c9ae1_row10_col2" class="data row10 col2" >58.19</td>
                        <td id="T_c9ae1_row10_col3" class="data row10 col3" >42.78</td>
                        <td id="T_c9ae1_row10_col4" class="data row10 col4" >90.46</td>
                        <td id="T_c9ae1_row10_col5" class="data row10 col5" >29.66</td>
                        <td id="T_c9ae1_row10_col6" class="data row10 col6" >84.43</td>
                        <td id="T_c9ae1_row10_col7" class="data row10 col7" >-77.46</td>
                        <td id="T_c9ae1_row10_col8" class="data row10 col8" >87.97</td>
                        <td id="T_c9ae1_row10_col9" class="data row10 col9" >-</td>
                        <td id="T_c9ae1_row10_col10" class="data row10 col10" >139.66</td>
                        <td id="T_c9ae1_row10_col11" class="data row10 col11" >1.65</td>
                        <td id="T_c9ae1_row10_col12" class="data row10 col12" >2020-12-31</td>
            </tr>
            <tr>
                        <th id="T_c9ae1_level0_row11" class="row_heading level0 row11" >CPRT</th>
                        <td id="T_c9ae1_row11_col0" class="data row11 col0" >Copart Inc. (DE) Com</td>
                        <td id="T_c9ae1_row11_col1" class="data row11 col1" >27.95</td>
                        <td id="T_c9ae1_row11_col2" class="data row11 col2" >30.93</td>
                        <td id="T_c9ae1_row11_col3" class="data row11 col3" >27.77</td>
                        <td id="T_c9ae1_row11_col4" class="data row11 col4" >15.27</td>
                        <td id="T_c9ae1_row11_col5" class="data row11 col5" >11.97</td>
                        <td id="T_c9ae1_row11_col6" class="data row11 col6" >21.96</td>
                        <td id="T_c9ae1_row11_col7" class="data row11 col7" >20.88</td>
                        <td id="T_c9ae1_row11_col8" class="data row11 col8" >2.37</td>
                        <td id="T_c9ae1_row11_col9" class="data row11 col9" >42.37</td>
                        <td id="T_c9ae1_row11_col10" class="data row11 col10" >56.18</td>
                        <td id="T_c9ae1_row11_col11" class="data row11 col11" >2.56</td>
                        <td id="T_c9ae1_row11_col12" class="data row11 col12" >2021-04-30</td>
            </tr>
    </tbody></table>



### 观察列表




<style  type="text/css" >
#T_9e8c7_row0_col0,#T_9e8c7_row0_col1,#T_9e8c7_row0_col2,#T_9e8c7_row0_col3,#T_9e8c7_row0_col4,#T_9e8c7_row0_col6,#T_9e8c7_row0_col7,#T_9e8c7_row0_col9,#T_9e8c7_row0_col10,#T_9e8c7_row0_col11,#T_9e8c7_row0_col12,#T_9e8c7_row1_col0,#T_9e8c7_row1_col1,#T_9e8c7_row1_col2,#T_9e8c7_row1_col3,#T_9e8c7_row1_col4,#T_9e8c7_row1_col5,#T_9e8c7_row1_col6,#T_9e8c7_row1_col7,#T_9e8c7_row1_col8,#T_9e8c7_row1_col9,#T_9e8c7_row1_col10,#T_9e8c7_row1_col11,#T_9e8c7_row1_col12,#T_9e8c7_row2_col0,#T_9e8c7_row2_col1,#T_9e8c7_row2_col2,#T_9e8c7_row2_col3,#T_9e8c7_row2_col4,#T_9e8c7_row2_col6,#T_9e8c7_row2_col7,#T_9e8c7_row2_col8,#T_9e8c7_row2_col9,#T_9e8c7_row2_col10,#T_9e8c7_row2_col11,#T_9e8c7_row2_col12,#T_9e8c7_row3_col0,#T_9e8c7_row3_col1,#T_9e8c7_row3_col2,#T_9e8c7_row3_col3,#T_9e8c7_row3_col4,#T_9e8c7_row3_col5,#T_9e8c7_row3_col6,#T_9e8c7_row3_col7,#T_9e8c7_row3_col8,#T_9e8c7_row3_col9,#T_9e8c7_row3_col10,#T_9e8c7_row3_col11,#T_9e8c7_row3_col12,#T_9e8c7_row4_col0,#T_9e8c7_row4_col1,#T_9e8c7_row4_col2,#T_9e8c7_row4_col3,#T_9e8c7_row4_col5,#T_9e8c7_row4_col6,#T_9e8c7_row4_col8,#T_9e8c7_row4_col9,#T_9e8c7_row4_col10,#T_9e8c7_row4_col11,#T_9e8c7_row4_col12,#T_9e8c7_row5_col0,#T_9e8c7_row5_col1,#T_9e8c7_row5_col2,#T_9e8c7_row5_col3,#T_9e8c7_row5_col4,#T_9e8c7_row5_col5,#T_9e8c7_row5_col6,#T_9e8c7_row5_col8,#T_9e8c7_row5_col9,#T_9e8c7_row5_col10,#T_9e8c7_row5_col11,#T_9e8c7_row5_col12,#T_9e8c7_row6_col0,#T_9e8c7_row6_col1,#T_9e8c7_row6_col2,#T_9e8c7_row6_col3,#T_9e8c7_row6_col6,#T_9e8c7_row6_col9,#T_9e8c7_row6_col10,#T_9e8c7_row6_col11,#T_9e8c7_row6_col12,#T_9e8c7_row7_col0,#T_9e8c7_row7_col1,#T_9e8c7_row7_col2,#T_9e8c7_row7_col3,#T_9e8c7_row7_col4,#T_9e8c7_row7_col5,#T_9e8c7_row7_col6,#T_9e8c7_row7_col7,#T_9e8c7_row7_col8,#T_9e8c7_row7_col9,#T_9e8c7_row7_col10,#T_9e8c7_row7_col11,#T_9e8c7_row7_col12,#T_9e8c7_row8_col0,#T_9e8c7_row8_col1,#T_9e8c7_row8_col2,#T_9e8c7_row8_col3,#T_9e8c7_row8_col4,#T_9e8c7_row8_col5,#T_9e8c7_row8_col6,#T_9e8c7_row8_col7,#T_9e8c7_row8_col8,#T_9e8c7_row8_col9,#T_9e8c7_row8_col10,#T_9e8c7_row8_col11,#T_9e8c7_row8_col12,#T_9e8c7_row9_col0,#T_9e8c7_row9_col1,#T_9e8c7_row9_col2,#T_9e8c7_row9_col3,#T_9e8c7_row9_col4,#T_9e8c7_row9_col5,#T_9e8c7_row9_col6,#T_9e8c7_row9_col7,#T_9e8c7_row9_col8,#T_9e8c7_row9_col9,#T_9e8c7_row9_col10,#T_9e8c7_row9_col11,#T_9e8c7_row9_col12,#T_9e8c7_row10_col0,#T_9e8c7_row10_col1,#T_9e8c7_row10_col2,#T_9e8c7_row10_col3,#T_9e8c7_row10_col4,#T_9e8c7_row10_col5,#T_9e8c7_row10_col6,#T_9e8c7_row10_col7,#T_9e8c7_row10_col8,#T_9e8c7_row10_col9,#T_9e8c7_row10_col10,#T_9e8c7_row10_col11,#T_9e8c7_row10_col12,#T_9e8c7_row11_col0,#T_9e8c7_row11_col1,#T_9e8c7_row11_col2,#T_9e8c7_row11_col3,#T_9e8c7_row11_col4,#T_9e8c7_row11_col5,#T_9e8c7_row11_col6,#T_9e8c7_row11_col7,#T_9e8c7_row11_col8,#T_9e8c7_row11_col9,#T_9e8c7_row11_col10,#T_9e8c7_row11_col11,#T_9e8c7_row11_col12,#T_9e8c7_row12_col0,#T_9e8c7_row12_col1,#T_9e8c7_row12_col2,#T_9e8c7_row12_col3,#T_9e8c7_row12_col4,#T_9e8c7_row12_col5,#T_9e8c7_row12_col6,#T_9e8c7_row12_col7,#T_9e8c7_row12_col8,#T_9e8c7_row12_col9,#T_9e8c7_row12_col10,#T_9e8c7_row12_col11,#T_9e8c7_row12_col12,#T_9e8c7_row13_col0,#T_9e8c7_row13_col1,#T_9e8c7_row13_col2,#T_9e8c7_row13_col3,#T_9e8c7_row13_col4,#T_9e8c7_row13_col5,#T_9e8c7_row13_col6,#T_9e8c7_row13_col7,#T_9e8c7_row13_col9,#T_9e8c7_row13_col10,#T_9e8c7_row13_col11,#T_9e8c7_row13_col12,#T_9e8c7_row14_col0,#T_9e8c7_row14_col1,#T_9e8c7_row14_col2,#T_9e8c7_row14_col3,#T_9e8c7_row14_col4,#T_9e8c7_row14_col6,#T_9e8c7_row14_col8,#T_9e8c7_row14_col9,#T_9e8c7_row14_col10,#T_9e8c7_row14_col11,#T_9e8c7_row14_col12,#T_9e8c7_row15_col0,#T_9e8c7_row15_col1,#T_9e8c7_row15_col2,#T_9e8c7_row15_col3,#T_9e8c7_row15_col4,#T_9e8c7_row15_col5,#T_9e8c7_row15_col6,#T_9e8c7_row15_col7,#T_9e8c7_row15_col8,#T_9e8c7_row15_col9,#T_9e8c7_row15_col10,#T_9e8c7_row15_col11,#T_9e8c7_row15_col12,#T_9e8c7_row16_col0,#T_9e8c7_row16_col1,#T_9e8c7_row16_col2,#T_9e8c7_row16_col3,#T_9e8c7_row16_col4,#T_9e8c7_row16_col5,#T_9e8c7_row16_col6,#T_9e8c7_row16_col7,#T_9e8c7_row16_col8,#T_9e8c7_row16_col9,#T_9e8c7_row16_col10,#T_9e8c7_row16_col11,#T_9e8c7_row16_col12,#T_9e8c7_row17_col0,#T_9e8c7_row17_col1,#T_9e8c7_row17_col2,#T_9e8c7_row17_col3,#T_9e8c7_row17_col4,#T_9e8c7_row17_col5,#T_9e8c7_row17_col6,#T_9e8c7_row17_col9,#T_9e8c7_row17_col10,#T_9e8c7_row17_col11,#T_9e8c7_row17_col12,#T_9e8c7_row18_col0,#T_9e8c7_row18_col1,#T_9e8c7_row18_col2,#T_9e8c7_row18_col3,#T_9e8c7_row18_col4,#T_9e8c7_row18_col6,#T_9e8c7_row18_col8,#T_9e8c7_row18_col9,#T_9e8c7_row18_col10,#T_9e8c7_row18_col11,#T_9e8c7_row18_col12,#T_9e8c7_row19_col0,#T_9e8c7_row19_col1,#T_9e8c7_row19_col3,#T_9e8c7_row19_col4,#T_9e8c7_row19_col5,#T_9e8c7_row19_col6,#T_9e8c7_row19_col7,#T_9e8c7_row19_col8,#T_9e8c7_row19_col9,#T_9e8c7_row19_col10,#T_9e8c7_row19_col11,#T_9e8c7_row19_col12,#T_9e8c7_row20_col0,#T_9e8c7_row20_col1,#T_9e8c7_row20_col2,#T_9e8c7_row20_col3,#T_9e8c7_row20_col4,#T_9e8c7_row20_col9,#T_9e8c7_row20_col10,#T_9e8c7_row20_col11,#T_9e8c7_row20_col12,#T_9e8c7_row21_col0,#T_9e8c7_row21_col1,#T_9e8c7_row21_col4,#T_9e8c7_row21_col5,#T_9e8c7_row21_col6,#T_9e8c7_row21_col7,#T_9e8c7_row21_col9,#T_9e8c7_row21_col10,#T_9e8c7_row21_col11,#T_9e8c7_row21_col12,#T_9e8c7_row22_col0,#T_9e8c7_row22_col1,#T_9e8c7_row22_col2,#T_9e8c7_row22_col4,#T_9e8c7_row22_col5,#T_9e8c7_row22_col9,#T_9e8c7_row22_col10,#T_9e8c7_row22_col11,#T_9e8c7_row22_col12,#T_9e8c7_row23_col0,#T_9e8c7_row23_col1,#T_9e8c7_row23_col4,#T_9e8c7_row23_col5,#T_9e8c7_row23_col6,#T_9e8c7_row23_col7,#T_9e8c7_row23_col9,#T_9e8c7_row23_col10,#T_9e8c7_row23_col11,#T_9e8c7_row23_col12,#T_9e8c7_row24_col0,#T_9e8c7_row24_col1,#T_9e8c7_row24_col2,#T_9e8c7_row24_col3,#T_9e8c7_row24_col4,#T_9e8c7_row24_col5,#T_9e8c7_row24_col7,#T_9e8c7_row24_col9,#T_9e8c7_row24_col10,#T_9e8c7_row24_col11,#T_9e8c7_row24_col12,#T_9e8c7_row25_col0,#T_9e8c7_row25_col1,#T_9e8c7_row25_col2,#T_9e8c7_row25_col4,#T_9e8c7_row25_col5,#T_9e8c7_row25_col6,#T_9e8c7_row25_col8,#T_9e8c7_row25_col9,#T_9e8c7_row25_col10,#T_9e8c7_row25_col11,#T_9e8c7_row25_col12,#T_9e8c7_row26_col0,#T_9e8c7_row26_col1,#T_9e8c7_row26_col2,#T_9e8c7_row26_col3,#T_9e8c7_row26_col4,#T_9e8c7_row26_col5,#T_9e8c7_row26_col7,#T_9e8c7_row26_col8,#T_9e8c7_row26_col9,#T_9e8c7_row26_col10,#T_9e8c7_row26_col11,#T_9e8c7_row26_col12,#T_9e8c7_row27_col0,#T_9e8c7_row27_col1,#T_9e8c7_row27_col5,#T_9e8c7_row27_col8,#T_9e8c7_row27_col9,#T_9e8c7_row27_col10,#T_9e8c7_row27_col11,#T_9e8c7_row27_col12,#T_9e8c7_row28_col0,#T_9e8c7_row28_col1,#T_9e8c7_row28_col2,#T_9e8c7_row28_col3,#T_9e8c7_row28_col4,#T_9e8c7_row28_col7,#T_9e8c7_row28_col8,#T_9e8c7_row28_col9,#T_9e8c7_row28_col10,#T_9e8c7_row28_col11,#T_9e8c7_row28_col12,#T_9e8c7_row29_col0,#T_9e8c7_row29_col1,#T_9e8c7_row29_col2,#T_9e8c7_row29_col3,#T_9e8c7_row29_col5,#T_9e8c7_row29_col7,#T_9e8c7_row29_col9,#T_9e8c7_row29_col10,#T_9e8c7_row29_col11,#T_9e8c7_row29_col12,#T_9e8c7_row30_col0,#T_9e8c7_row30_col1,#T_9e8c7_row30_col2,#T_9e8c7_row30_col3,#T_9e8c7_row30_col4,#T_9e8c7_row30_col5,#T_9e8c7_row30_col9,#T_9e8c7_row30_col10,#T_9e8c7_row30_col11,#T_9e8c7_row30_col12,#T_9e8c7_row31_col0,#T_9e8c7_row31_col1,#T_9e8c7_row31_col2,#T_9e8c7_row31_col3,#T_9e8c7_row31_col5,#T_9e8c7_row31_col9,#T_9e8c7_row31_col10,#T_9e8c7_row31_col11,#T_9e8c7_row31_col12,#T_9e8c7_row32_col0,#T_9e8c7_row32_col1,#T_9e8c7_row32_col2,#T_9e8c7_row32_col3,#T_9e8c7_row32_col5,#T_9e8c7_row32_col7,#T_9e8c7_row32_col8,#T_9e8c7_row32_col9,#T_9e8c7_row32_col10,#T_9e8c7_row32_col11,#T_9e8c7_row32_col12,#T_9e8c7_row33_col0,#T_9e8c7_row33_col1,#T_9e8c7_row33_col3,#T_9e8c7_row33_col4,#T_9e8c7_row33_col5,#T_9e8c7_row33_col7,#T_9e8c7_row33_col8,#T_9e8c7_row33_col9,#T_9e8c7_row33_col10,#T_9e8c7_row33_col11,#T_9e8c7_row33_col12,#T_9e8c7_row34_col0,#T_9e8c7_row34_col1,#T_9e8c7_row34_col2,#T_9e8c7_row34_col4,#T_9e8c7_row34_col5,#T_9e8c7_row34_col6,#T_9e8c7_row34_col9,#T_9e8c7_row34_col10,#T_9e8c7_row34_col11,#T_9e8c7_row34_col12,#T_9e8c7_row35_col0,#T_9e8c7_row35_col1,#T_9e8c7_row35_col2,#T_9e8c7_row35_col4,#T_9e8c7_row35_col5,#T_9e8c7_row35_col9,#T_9e8c7_row35_col10,#T_9e8c7_row35_col11,#T_9e8c7_row35_col12{
            color:  black;
        }#T_9e8c7_row0_col5,#T_9e8c7_row0_col8,#T_9e8c7_row2_col5,#T_9e8c7_row4_col4,#T_9e8c7_row4_col7,#T_9e8c7_row5_col7,#T_9e8c7_row6_col4,#T_9e8c7_row6_col5,#T_9e8c7_row6_col7,#T_9e8c7_row6_col8,#T_9e8c7_row13_col8,#T_9e8c7_row14_col5,#T_9e8c7_row14_col7,#T_9e8c7_row17_col7,#T_9e8c7_row17_col8,#T_9e8c7_row18_col5,#T_9e8c7_row18_col7,#T_9e8c7_row19_col2,#T_9e8c7_row20_col5,#T_9e8c7_row20_col6,#T_9e8c7_row20_col7,#T_9e8c7_row20_col8,#T_9e8c7_row21_col2,#T_9e8c7_row21_col3,#T_9e8c7_row21_col8,#T_9e8c7_row22_col3,#T_9e8c7_row22_col6,#T_9e8c7_row22_col7,#T_9e8c7_row22_col8,#T_9e8c7_row23_col2,#T_9e8c7_row23_col3,#T_9e8c7_row23_col8,#T_9e8c7_row24_col6,#T_9e8c7_row24_col8,#T_9e8c7_row25_col3,#T_9e8c7_row25_col7,#T_9e8c7_row26_col6,#T_9e8c7_row27_col2,#T_9e8c7_row27_col3,#T_9e8c7_row27_col4,#T_9e8c7_row27_col6,#T_9e8c7_row27_col7,#T_9e8c7_row28_col5,#T_9e8c7_row28_col6,#T_9e8c7_row29_col4,#T_9e8c7_row29_col6,#T_9e8c7_row29_col8,#T_9e8c7_row30_col6,#T_9e8c7_row30_col7,#T_9e8c7_row30_col8,#T_9e8c7_row31_col4,#T_9e8c7_row31_col6,#T_9e8c7_row31_col7,#T_9e8c7_row31_col8,#T_9e8c7_row32_col4,#T_9e8c7_row32_col6,#T_9e8c7_row33_col2,#T_9e8c7_row33_col6,#T_9e8c7_row34_col3,#T_9e8c7_row34_col7,#T_9e8c7_row34_col8,#T_9e8c7_row35_col3,#T_9e8c7_row35_col6,#T_9e8c7_row35_col7,#T_9e8c7_row35_col8{
            color:  red;
        }</style><table id="T_9e8c7_" ><thead>    <tr>        <th class="blank level0" ></th>        <th class="col_heading level0 col0" >名称</th>        <th class="col_heading level0 col1" >负债率</th>        <th class="col_heading level0 col2" >ROE</th>        <th class="col_heading level0 col3" >利润率</th>        <th class="col_heading level0 col4" >收入增长</th>        <th class="col_heading level0 col5" >收入增长TTM</th>        <th class="col_heading level0 col6" >盈利增长</th>        <th class="col_heading level0 col7" >盈利增长TTM</th>        <th class="col_heading level0 col8" >FCF增长</th>        <th class="col_heading level0 col9" >PE</th>        <th class="col_heading level0 col10" >PEm</th>        <th class="col_heading level0 col11" >PEG</th>        <th class="col_heading level0 col12" >季报日期</th>    </tr>    <tr>        <th class="index_name level0" >Symbol</th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>    </tr></thead><tbody>
                <tr>
                        <th id="T_9e8c7_level0_row0" class="row_heading level0 row0" >BIDU</th>
                        <td id="T_9e8c7_row0_col0" class="data row0 col0" >Baidu Inc. ADS</td>
                        <td id="T_9e8c7_row0_col1" class="data row0 col1" >42.34</td>
                        <td id="T_9e8c7_row0_col2" class="data row0 col2" >11.59</td>
                        <td id="T_9e8c7_row0_col3" class="data row0 col3" >17.64</td>
                        <td id="T_9e8c7_row0_col4" class="data row0 col4" >7.63</td>
                        <td id="T_9e8c7_row0_col5" class="data row0 col5" >-0.32</td>
                        <td id="T_9e8c7_row0_col6" class="data row0 col6" >316.86</td>
                        <td id="T_9e8c7_row0_col7" class="data row0 col7" >992.46</td>
                        <td id="T_9e8c7_row0_col8" class="data row0 col8" >-11.75</td>
                        <td id="T_9e8c7_row0_col9" class="data row0 col9" >19.24</td>
                        <td id="T_9e8c7_row0_col10" class="data row0 col10" >23.40</td>
                        <td id="T_9e8c7_row0_col11" class="data row0 col11" >0.07</td>
                        <td id="T_9e8c7_row0_col12" class="data row0 col12" >2020-12-31</td>
            </tr>
            <tr>
                        <th id="T_9e8c7_level0_row1" class="row_heading level0 row1" >TSM</th>
                        <td id="T_9e8c7_row1_col0" class="data row1 col0" >Taiwan Semiconductor</td>
                        <td id="T_9e8c7_row1_col1" class="data row1 col1" >32.97</td>
                        <td id="T_9e8c7_row1_col2" class="data row1 col2" >23.33</td>
                        <td id="T_9e8c7_row1_col3" class="data row1 col3" >35.07</td>
                        <td id="T_9e8c7_row1_col4" class="data row1 col4" >11.48</td>
                        <td id="T_9e8c7_row1_col5" class="data row1 col5" >3.87</td>
                        <td id="T_9e8c7_row1_col6" class="data row1 col6" >16.70</td>
                        <td id="T_9e8c7_row1_col7" class="data row1 col7" >4.38</td>
                        <td id="T_9e8c7_row1_col8" class="data row1 col8" >21.73</td>
                        <td id="T_9e8c7_row1_col9" class="data row1 col9" >32.04</td>
                        <td id="T_9e8c7_row1_col10" class="data row1 col10" >1.46</td>
                        <td id="T_9e8c7_row1_col11" class="data row1 col11" >0.09</td>
                        <td id="T_9e8c7_row1_col12" class="data row1 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_9e8c7_level0_row2" class="row_heading level0 row2" >YY</th>
                        <td id="T_9e8c7_row2_col0" class="data row2 col0" >JOYY Inc. American D</td>
                        <td id="T_9e8c7_row2_col1" class="data row2 col1" >22.90</td>
                        <td id="T_9e8c7_row2_col2" class="data row2 col2" >16.55</td>
                        <td id="T_9e8c7_row2_col3" class="data row2 col3" >29.44</td>
                        <td id="T_9e8c7_row2_col4" class="data row2 col4" >16.64</td>
                        <td id="T_9e8c7_row2_col5" class="data row2 col5" >-48.27</td>
                        <td id="T_9e8c7_row2_col6" class="data row2 col6" >85.34</td>
                        <td id="T_9e8c7_row2_col7" class="data row2 col7" >184.34</td>
                        <td id="T_9e8c7_row2_col8" class="data row2 col8" >3.79</td>
                        <td id="T_9e8c7_row2_col9" class="data row2 col9" >3.82</td>
                        <td id="T_9e8c7_row2_col10" class="data row2 col10" >8.21</td>
                        <td id="T_9e8c7_row2_col11" class="data row2 col11" >0.10</td>
                        <td id="T_9e8c7_row2_col12" class="data row2 col12" >2020-12-31</td>
            </tr>
            <tr>
                        <th id="T_9e8c7_level0_row3" class="row_heading level0 row3" >JD</th>
                        <td id="T_9e8c7_row3_col0" class="data row3 col0" >JD.com Inc. American</td>
                        <td id="T_9e8c7_row3_col1" class="data row3 col1" >47.52</td>
                        <td id="T_9e8c7_row3_col2" class="data row3 col2" >9.19</td>
                        <td id="T_9e8c7_row3_col3" class="data row3 col3" >2.04</td>
                        <td id="T_9e8c7_row3_col4" class="data row3 col4" >27.22</td>
                        <td id="T_9e8c7_row3_col5" class="data row3 col5" >29.28</td>
                        <td id="T_9e8c7_row3_col6" class="data row3 col6" >417.65</td>
                        <td id="T_9e8c7_row3_col7" class="data row3 col7" >305.49</td>
                        <td id="T_9e8c7_row3_col8" class="data row3 col8" >117.46</td>
                        <td id="T_9e8c7_row3_col9" class="data row3 col9" >15.42</td>
                        <td id="T_9e8c7_row3_col10" class="data row3 col10" >51.51</td>
                        <td id="T_9e8c7_row3_col11" class="data row3 col11" >0.12</td>
                        <td id="T_9e8c7_row3_col12" class="data row3 col12" >2020-12-31</td>
            </tr>
            <tr>
                        <th id="T_9e8c7_level0_row4" class="row_heading level0 row4" >KO</th>
                        <td id="T_9e8c7_row4_col0" class="data row4 col0" >Coca-Cola Company (T</td>
                        <td id="T_9e8c7_row4_col1" class="data row4 col1" >75.62</td>
                        <td id="T_9e8c7_row4_col2" class="data row4 col2" >33.08</td>
                        <td id="T_9e8c7_row4_col3" class="data row4 col3" >17.40</td>
                        <td id="T_9e8c7_row4_col4" class="data row4 col4" >-2.68</td>
                        <td id="T_9e8c7_row4_col5" class="data row4 col5" >1.27</td>
                        <td id="T_9e8c7_row4_col6" class="data row4 col6" >147.01</td>
                        <td id="T_9e8c7_row4_col7" class="data row4 col7" >-6.84</td>
                        <td id="T_9e8c7_row4_col8" class="data row4 col8" >18.77</td>
                        <td id="T_9e8c7_row4_col9" class="data row4 col9" >33.68</td>
                        <td id="T_9e8c7_row4_col10" class="data row4 col10" >39.84</td>
                        <td id="T_9e8c7_row4_col11" class="data row4 col11" >0.27</td>
                        <td id="T_9e8c7_row4_col12" class="data row4 col12" >2021-04-02</td>
            </tr>
            <tr>
                        <th id="T_9e8c7_level0_row5" class="row_heading level0 row5" >NTES</th>
                        <td id="T_9e8c7_row5_col0" class="data row5 col0" >NetEase Inc. America</td>
                        <td id="T_9e8c7_row5_col1" class="data row5 col1" >33.89</td>
                        <td id="T_9e8c7_row5_col2" class="data row5 col2" >21.57</td>
                        <td id="T_9e8c7_row5_col3" class="data row5 col3" >22.09</td>
                        <td id="T_9e8c7_row5_col4" class="data row5 col4" >18.43</td>
                        <td id="T_9e8c7_row5_col5" class="data row5 col5" >24.35</td>
                        <td id="T_9e8c7_row5_col6" class="data row5 col6" >53.15</td>
                        <td id="T_9e8c7_row5_col7" class="data row5 col7" >-43.20</td>
                        <td id="T_9e8c7_row5_col8" class="data row5 col8" >33.70</td>
                        <td id="T_9e8c7_row5_col9" class="data row5 col9" >41.17</td>
                        <td id="T_9e8c7_row5_col10" class="data row5 col10" >39.74</td>
                        <td id="T_9e8c7_row5_col11" class="data row5 col11" >0.75</td>
                        <td id="T_9e8c7_row5_col12" class="data row5 col12" >2020-12-31</td>
            </tr>
            <tr>
                        <th id="T_9e8c7_level0_row6" class="row_heading level0 row6" >TCOM</th>
                        <td id="T_9e8c7_row6_col0" class="data row6 col0" >Trip.com Group Limit</td>
                        <td id="T_9e8c7_row6_col1" class="data row6 col1" >45.76</td>
                        <td id="T_9e8c7_row6_col2" class="data row6 col2" >1.84</td>
                        <td id="T_9e8c7_row6_col3" class="data row6 col3" >3.39</td>
                        <td id="T_9e8c7_row6_col4" class="data row6 col4" >-5.97</td>
                        <td id="T_9e8c7_row6_col5" class="data row6 col5" >-48.65</td>
                        <td id="T_9e8c7_row6_col6" class="data row6 col6" >111.92</td>
                        <td id="T_9e8c7_row6_col7" class="data row6 col7" >-146.31</td>
                        <td id="T_9e8c7_row6_col8" class="data row6 col8" >-56.07</td>
                        <td id="T_9e8c7_row6_col9" class="data row6 col9" >-</td>
                        <td id="T_9e8c7_row6_col10" class="data row6 col10" >85.07</td>
                        <td id="T_9e8c7_row6_col11" class="data row6 col11" >0.76</td>
                        <td id="T_9e8c7_row6_col12" class="data row6 col12" >2020-12-31</td>
            </tr>
            <tr>
                        <th id="T_9e8c7_level0_row7" class="row_heading level0 row7" >BABA</th>
                        <td id="T_9e8c7_row7_col0" class="data row7 col0" >Alibaba Group Holdin</td>
                        <td id="T_9e8c7_row7_col1" class="data row7 col1" >33.70</td>
                        <td id="T_9e8c7_row7_col2" class="data row7 col2" >17.71</td>
                        <td id="T_9e8c7_row7_col3" class="data row7 col3" >26.46</td>
                        <td id="T_9e8c7_row7_col4" class="data row7 col4" >47.99</td>
                        <td id="T_9e8c7_row7_col5" class="data row7 col5" >26.39</td>
                        <td id="T_9e8c7_row7_col6" class="data row7 col6" >51.30</td>
                        <td id="T_9e8c7_row7_col7" class="data row7 col7" >6.51</td>
                        <td id="T_9e8c7_row7_col8" class="data row7 col8" >28.25</td>
                        <td id="T_9e8c7_row7_col9" class="data row7 col9" >24.47</td>
                        <td id="T_9e8c7_row7_col10" class="data row7 col10" >44.44</td>
                        <td id="T_9e8c7_row7_col11" class="data row7 col11" >0.87</td>
                        <td id="T_9e8c7_row7_col12" class="data row7 col12" >2020-12-31</td>
            </tr>
            <tr>
                        <th id="T_9e8c7_level0_row8" class="row_heading level0 row8" >GOOGL</th>
                        <td id="T_9e8c7_row8_col0" class="data row8 col0" >Alphabet Inc. Class </td>
                        <td id="T_9e8c7_row8_col1" class="data row8 col1" >30.37</td>
                        <td id="T_9e8c7_row8_col2" class="data row8 col2" >15.19</td>
                        <td id="T_9e8c7_row8_col3" class="data row8 col3" >19.29</td>
                        <td id="T_9e8c7_row8_col4" class="data row8 col4" >18.16</td>
                        <td id="T_9e8c7_row8_col5" class="data row8 col5" >7.76</td>
                        <td id="T_9e8c7_row8_col6" class="data row8 col6" >57.24</td>
                        <td id="T_9e8c7_row8_col7" class="data row8 col7" >27.55</td>
                        <td id="T_9e8c7_row8_col8" class="data row8 col8" >23.16</td>
                        <td id="T_9e8c7_row8_col9" class="data row8 col9" >31.90</td>
                        <td id="T_9e8c7_row8_col10" class="data row8 col10" >54.91</td>
                        <td id="T_9e8c7_row8_col11" class="data row8 col11" >0.96</td>
                        <td id="T_9e8c7_row8_col12" class="data row8 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_9e8c7_level0_row9" class="row_heading level0 row9" >GOOG</th>
                        <td id="T_9e8c7_row9_col0" class="data row9 col0" >Alphabet Inc. Class </td>
                        <td id="T_9e8c7_row9_col1" class="data row9 col1" >30.37</td>
                        <td id="T_9e8c7_row9_col2" class="data row9 col2" >15.19</td>
                        <td id="T_9e8c7_row9_col3" class="data row9 col3" >19.29</td>
                        <td id="T_9e8c7_row9_col4" class="data row9 col4" >18.16</td>
                        <td id="T_9e8c7_row9_col5" class="data row9 col5" >7.76</td>
                        <td id="T_9e8c7_row9_col6" class="data row9 col6" >57.24</td>
                        <td id="T_9e8c7_row9_col7" class="data row9 col7" >27.55</td>
                        <td id="T_9e8c7_row9_col8" class="data row9 col8" >23.16</td>
                        <td id="T_9e8c7_row9_col9" class="data row9 col9" >32.67</td>
                        <td id="T_9e8c7_row9_col10" class="data row9 col10" >55.11</td>
                        <td id="T_9e8c7_row9_col11" class="data row9 col11" >0.96</td>
                        <td id="T_9e8c7_row9_col12" class="data row9 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_9e8c7_level0_row10" class="row_heading level0 row10" >AMZN</th>
                        <td id="T_9e8c7_row10_col0" class="data row10 col0" >Amazon.com Inc. Comm</td>
                        <td id="T_9e8c7_row10_col1" class="data row10 col1" >70.92</td>
                        <td id="T_9e8c7_row10_col2" class="data row10 col2" >18.90</td>
                        <td id="T_9e8c7_row10_col3" class="data row10 col3" >3.92</td>
                        <td id="T_9e8c7_row10_col4" class="data row10 col4" >29.67</td>
                        <td id="T_9e8c7_row10_col5" class="data row10 col5" >8.56</td>
                        <td id="T_9e8c7_row10_col6" class="data row10 col6" >110.41</td>
                        <td id="T_9e8c7_row10_col7" class="data row10 col7" >26.12</td>
                        <td id="T_9e8c7_row10_col8" class="data row10 col8" >71.58</td>
                        <td id="T_9e8c7_row10_col9" class="data row10 col9" >61.00</td>
                        <td id="T_9e8c7_row10_col10" class="data row10 col10" >140.53</td>
                        <td id="T_9e8c7_row10_col11" class="data row10 col11" >1.27</td>
                        <td id="T_9e8c7_row10_col12" class="data row10 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_9e8c7_level0_row11" class="row_heading level0 row11" >MSFT</th>
                        <td id="T_9e8c7_row11_col0" class="data row11 col0" >Microsoft Corporatio</td>
                        <td id="T_9e8c7_row11_col1" class="data row11 col1" >60.74</td>
                        <td id="T_9e8c7_row11_col2" class="data row11 col2" >31.22</td>
                        <td id="T_9e8c7_row11_col3" class="data row11 col3" >25.89</td>
                        <td id="T_9e8c7_row11_col4" class="data row11 col4" >13.98</td>
                        <td id="T_9e8c7_row11_col5" class="data row11 col5" >11.85</td>
                        <td id="T_9e8c7_row11_col6" class="data row11 col6" >38.22</td>
                        <td id="T_9e8c7_row11_col7" class="data row11 col7" >26.50</td>
                        <td id="T_9e8c7_row11_col8" class="data row11 col8" >13.21</td>
                        <td id="T_9e8c7_row11_col9" class="data row11 col9" >34.18</td>
                        <td id="T_9e8c7_row11_col10" class="data row11 col10" >60.16</td>
                        <td id="T_9e8c7_row11_col11" class="data row11 col11" >1.57</td>
                        <td id="T_9e8c7_row11_col12" class="data row11 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_9e8c7_level0_row12" class="row_heading level0 row12" >FB</th>
                        <td id="T_9e8c7_row12_col0" class="data row12 col0" >Facebook Inc. Class </td>
                        <td id="T_9e8c7_row12_col1" class="data row12 col1" >19.47</td>
                        <td id="T_9e8c7_row12_col2" class="data row12 col2" >22.18</td>
                        <td id="T_9e8c7_row12_col3" class="data row12 col3" >34.71</td>
                        <td id="T_9e8c7_row12_col4" class="data row12 col4" >28.52</td>
                        <td id="T_9e8c7_row12_col5" class="data row12 col5" >9.81</td>
                        <td id="T_9e8c7_row12_col6" class="data row12 col6" >26.68</td>
                        <td id="T_9e8c7_row12_col7" class="data row12 col7" >15.76</td>
                        <td id="T_9e8c7_row12_col8" class="data row12 col8" >12.46</td>
                        <td id="T_9e8c7_row12_col9" class="data row12 col9" >28.31</td>
                        <td id="T_9e8c7_row12_col10" class="data row12 col10" >43.73</td>
                        <td id="T_9e8c7_row12_col11" class="data row12 col11" >1.64</td>
                        <td id="T_9e8c7_row12_col12" class="data row12 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_9e8c7_level0_row13" class="row_heading level0 row13" >NFLX</th>
                        <td id="T_9e8c7_row13_col0" class="data row13 col0" >Netflix Inc. Common </td>
                        <td id="T_9e8c7_row13_col1" class="data row13 col1" >71.83</td>
                        <td id="T_9e8c7_row13_col2" class="data row13 col2" >22.08</td>
                        <td id="T_9e8c7_row13_col3" class="data row13 col3" >8.19</td>
                        <td id="T_9e8c7_row13_col4" class="data row13 col4" >28.90</td>
                        <td id="T_9e8c7_row13_col5" class="data row13 col5" >5.58</td>
                        <td id="T_9e8c7_row13_col6" class="data row13 col6" >72.92</td>
                        <td id="T_9e8c7_row13_col7" class="data row13 col7" >36.13</td>
                        <td id="T_9e8c7_row13_col8" class="data row13 col8" >-35.24</td>
                        <td id="T_9e8c7_row13_col9" class="data row13 col9" >59.87</td>
                        <td id="T_9e8c7_row13_col10" class="data row13 col10" >137.14</td>
                        <td id="T_9e8c7_row13_col11" class="data row13 col11" >1.88</td>
                        <td id="T_9e8c7_row13_col12" class="data row13 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_9e8c7_level0_row14" class="row_heading level0 row14" >MOMO</th>
                        <td id="T_9e8c7_row14_col0" class="data row14 col0" >Momo Inc. American D</td>
                        <td id="T_9e8c7_row14_col1" class="data row14 col1" >36.11</td>
                        <td id="T_9e8c7_row14_col2" class="data row14 col2" >23.50</td>
                        <td id="T_9e8c7_row14_col3" class="data row14 col3" >19.16</td>
                        <td id="T_9e8c7_row14_col4" class="data row14 col4" >22.03</td>
                        <td id="T_9e8c7_row14_col5" class="data row14 col5" >-11.70</td>
                        <td id="T_9e8c7_row14_col6" class="data row14 col6" >2.46</td>
                        <td id="T_9e8c7_row14_col7" class="data row14 col7" >-29.20</td>
                        <td id="T_9e8c7_row14_col8" class="data row14 col8" >14.14</td>
                        <td id="T_9e8c7_row14_col9" class="data row14 col9" >9.32</td>
                        <td id="T_9e8c7_row14_col10" class="data row14 col10" >7.24</td>
                        <td id="T_9e8c7_row14_col11" class="data row14 col11" >2.94</td>
                        <td id="T_9e8c7_row14_col12" class="data row14 col12" >2020-12-31</td>
            </tr>
            <tr>
                        <th id="T_9e8c7_level0_row15" class="row_heading level0 row15" >AAPL</th>
                        <td id="T_9e8c7_row15_col0" class="data row15 col0" >Apple Inc. Common St</td>
                        <td id="T_9e8c7_row15_col1" class="data row15 col1" >79.83</td>
                        <td id="T_9e8c7_row15_col2" class="data row15 col2" >60.14</td>
                        <td id="T_9e8c7_row15_col3" class="data row15 col3" >21.41</td>
                        <td id="T_9e8c7_row15_col4" class="data row15 col4" >6.44</td>
                        <td id="T_9e8c7_row15_col5" class="data row15 col5" >18.54</td>
                        <td id="T_9e8c7_row15_col6" class="data row15 col6" >6.61</td>
                        <td id="T_9e8c7_row15_col7" class="data row15 col7" >32.92</td>
                        <td id="T_9e8c7_row15_col8" class="data row15 col8" >13.42</td>
                        <td id="T_9e8c7_row15_col9" class="data row15 col9" >28.30</td>
                        <td id="T_9e8c7_row15_col10" class="data row15 col10" >38.10</td>
                        <td id="T_9e8c7_row15_col11" class="data row15 col11" >5.76</td>
                        <td id="T_9e8c7_row15_col12" class="data row15 col12" >2021-03-27</td>
            </tr>
            <tr>
                        <th id="T_9e8c7_level0_row16" class="row_heading level0 row16" >NVDA</th>
                        <td id="T_9e8c7_row16_col0" class="data row16 col0" >NVIDIA Corporation C</td>
                        <td id="T_9e8c7_row16_col1" class="data row16 col1" >41.33</td>
                        <td id="T_9e8c7_row16_col2" class="data row16 col2" >33.42</td>
                        <td id="T_9e8c7_row16_col3" class="data row16 col3" >29.58</td>
                        <td id="T_9e8c7_row16_col4" class="data row16 col4" >22.18</td>
                        <td id="T_9e8c7_row16_col5" class="data row16 col5" >52.73</td>
                        <td id="T_9e8c7_row16_col6" class="data row16 col6" >19.45</td>
                        <td id="T_9e8c7_row16_col7" class="data row16 col7" >54.94</td>
                        <td id="T_9e8c7_row16_col8" class="data row16 col8" >17.95</td>
                        <td id="T_9e8c7_row16_col9" class="data row16 col9" >101.90</td>
                        <td id="T_9e8c7_row16_col10" class="data row16 col10" >126.41</td>
                        <td id="T_9e8c7_row16_col11" class="data row16 col11" >6.50</td>
                        <td id="T_9e8c7_row16_col12" class="data row16 col12" >2021-01-31</td>
            </tr>
            <tr>
                        <th id="T_9e8c7_level0_row17" class="row_heading level0 row17" >EDU</th>
                        <td id="T_9e8c7_row17_col0" class="data row17 col0" >New Oriental Educati</td>
                        <td id="T_9e8c7_row17_col1" class="data row17 col1" >56.23</td>
                        <td id="T_9e8c7_row17_col2" class="data row17 col2" >14.10</td>
                        <td id="T_9e8c7_row17_col3" class="data row17 col3" >11.65</td>
                        <td id="T_9e8c7_row17_col4" class="data row17 col4" >26.03</td>
                        <td id="T_9e8c7_row17_col5" class="data row17 col5" >7.95</td>
                        <td id="T_9e8c7_row17_col6" class="data row17 col6" >20.64</td>
                        <td id="T_9e8c7_row17_col7" class="data row17 col7" >-4.90</td>
                        <td id="T_9e8c7_row17_col8" class="data row17 col8" >-1.15</td>
                        <td id="T_9e8c7_row17_col9" class="data row17 col9" >38.42</td>
                        <td id="T_9e8c7_row17_col10" class="data row17 col10" >325.60</td>
                        <td id="T_9e8c7_row17_col11" class="data row17 col11" >15.78</td>
                        <td id="T_9e8c7_row17_col12" class="data row17 col12" >2021-02-28</td>
            </tr>
            <tr>
                        <th id="T_9e8c7_level0_row18" class="row_heading level0 row18" >WB</th>
                        <td id="T_9e8c7_row18_col0" class="data row18 col0" >Weibo Corporation Am</td>
                        <td id="T_9e8c7_row18_col1" class="data row18 col1" >54.44</td>
                        <td id="T_9e8c7_row18_col2" class="data row18 col2" >23.78</td>
                        <td id="T_9e8c7_row18_col3" class="data row18 col3" >27.62</td>
                        <td id="T_9e8c7_row18_col4" class="data row18 col4" >15.96</td>
                        <td id="T_9e8c7_row18_col5" class="data row18 col5" >-4.36</td>
                        <td id="T_9e8c7_row18_col6" class="data row18 col6" >4.01</td>
                        <td id="T_9e8c7_row18_col7" class="data row18 col7" >-36.65</td>
                        <td id="T_9e8c7_row18_col8" class="data row18 col8" >12.40</td>
                        <td id="T_9e8c7_row18_col9" class="data row18 col9" >34.59</td>
                        <td id="T_9e8c7_row18_col10" class="data row18 col10" >159.19</td>
                        <td id="T_9e8c7_row18_col11" class="data row18 col11" >39.69</td>
                        <td id="T_9e8c7_row18_col12" class="data row18 col12" >2020-12-31</td>
            </tr>
            <tr>
                        <th id="T_9e8c7_level0_row19" class="row_heading level0 row19" >TLSA</th>
                        <td id="T_9e8c7_row19_col0" class="data row19 col0" >Tiziana Life Science</td>
                        <td id="T_9e8c7_row19_col1" class="data row19 col1" >11.70</td>
                        <td id="T_9e8c7_row19_col2" class="data row19 col2" >-255.94</td>
                        <td id="T_9e8c7_row19_col3" class="data row19 col3" >-</td>
                        <td id="T_9e8c7_row19_col4" class="data row19 col4" >-</td>
                        <td id="T_9e8c7_row19_col5" class="data row19 col5" >-</td>
                        <td id="T_9e8c7_row19_col6" class="data row19 col6" >63.37</td>
                        <td id="T_9e8c7_row19_col7" class="data row19 col7" >180.29</td>
                        <td id="T_9e8c7_row19_col8" class="data row19 col8" >25.17</td>
                        <td id="T_9e8c7_row19_col9" class="data row19 col9" >-</td>
                        <td id="T_9e8c7_row19_col10" class="data row19 col10" >-</td>
                        <td id="T_9e8c7_row19_col11" class="data row19 col11" >-</td>
                        <td id="T_9e8c7_row19_col12" class="data row19 col12" >2020-12-31</td>
            </tr>
            <tr>
                        <th id="T_9e8c7_level0_row20" class="row_heading level0 row20" >SOGO</th>
                        <td id="T_9e8c7_row20_col0" class="data row20 col0" >Sogou Inc. American </td>
                        <td id="T_9e8c7_row20_col1" class="data row20 col1" >29.89</td>
                        <td id="T_9e8c7_row20_col2" class="data row20 col2" >4.04</td>
                        <td id="T_9e8c7_row20_col3" class="data row20 col3" >3.43</td>
                        <td id="T_9e8c7_row20_col4" class="data row20 col4" >2.30</td>
                        <td id="T_9e8c7_row20_col5" class="data row20 col5" >-21.12</td>
                        <td id="T_9e8c7_row20_col6" class="data row20 col6" >-70.36</td>
                        <td id="T_9e8c7_row20_col7" class="data row20 col7" >-221.45</td>
                        <td id="T_9e8c7_row20_col8" class="data row20 col8" >-4.09</td>
                        <td id="T_9e8c7_row20_col9" class="data row20 col9" >-</td>
                        <td id="T_9e8c7_row20_col10" class="data row20 col10" >79.59</td>
                        <td id="T_9e8c7_row20_col11" class="data row20 col11" >-</td>
                        <td id="T_9e8c7_row20_col12" class="data row20 col12" >2020-12-31</td>
            </tr>
            <tr>
                        <th id="T_9e8c7_level0_row21" class="row_heading level0 row21" >NIO</th>
                        <td id="T_9e8c7_row21_col0" class="data row21 col0" >NIO Inc. American de</td>
                        <td id="T_9e8c7_row21_col1" class="data row21 col1" >41.69</td>
                        <td id="T_9e8c7_row21_col2" class="data row21 col2" >-28.88</td>
                        <td id="T_9e8c7_row21_col3" class="data row21 col3" >-217.18</td>
                        <td id="T_9e8c7_row21_col4" class="data row21 col4" >inf</td>
                        <td id="T_9e8c7_row21_col5" class="data row21 col5" >40.66</td>
                        <td id="T_9e8c7_row21_col6" class="data row21 col6" >35.53</td>
                        <td id="T_9e8c7_row21_col7" class="data row21 col7" >56.18</td>
                        <td id="T_9e8c7_row21_col8" class="data row21 col8" >-7.85</td>
                        <td id="T_9e8c7_row21_col9" class="data row21 col9" >-</td>
                        <td id="T_9e8c7_row21_col10" class="data row21 col10" >-</td>
                        <td id="T_9e8c7_row21_col11" class="data row21 col11" >-</td>
                        <td id="T_9e8c7_row21_col12" class="data row21 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_9e8c7_level0_row22" class="row_heading level0 row22" >LI</th>
                        <td id="T_9e8c7_row22_col0" class="data row22 col0" >Li Auto Inc. America</td>
                        <td id="T_9e8c7_row22_col1" class="data row22 col1" >18.06</td>
                        <td id="T_9e8c7_row22_col2" class="data row22 col2" >35.47</td>
                        <td id="T_9e8c7_row22_col3" class="data row22 col3" >-429.57</td>
                        <td id="T_9e8c7_row22_col4" class="data row22 col4" >inf</td>
                        <td id="T_9e8c7_row22_col5" class="data row22 col5" >3,225.49</td>
                        <td id="T_9e8c7_row22_col6" class="data row22 col6" >-17.32</td>
                        <td id="T_9e8c7_row22_col7" class="data row22 col7" >-93.78</td>
                        <td id="T_9e8c7_row22_col8" class="data row22 col8" >-85.61</td>
                        <td id="T_9e8c7_row22_col9" class="data row22 col9" >-</td>
                        <td id="T_9e8c7_row22_col10" class="data row22 col10" >-</td>
                        <td id="T_9e8c7_row22_col11" class="data row22 col11" >-</td>
                        <td id="T_9e8c7_row22_col12" class="data row22 col12" >2020-12-31</td>
            </tr>
            <tr>
                        <th id="T_9e8c7_level0_row23" class="row_heading level0 row23" >BILI</th>
                        <td id="T_9e8c7_row23_col0" class="data row23 col0" >Bilibili Inc. Americ</td>
                        <td id="T_9e8c7_row23_col1" class="data row23 col1" >67.39</td>
                        <td id="T_9e8c7_row23_col2" class="data row23 col2" >-9.33</td>
                        <td id="T_9e8c7_row23_col3" class="data row23 col3" >-20.55</td>
                        <td id="T_9e8c7_row23_col4" class="data row23 col4" >69.49</td>
                        <td id="T_9e8c7_row23_col5" class="data row23 col5" >77.03</td>
                        <td id="T_9e8c7_row23_col6" class="data row23 col6" >83.54</td>
                        <td id="T_9e8c7_row23_col7" class="data row23 col7" >133.65</td>
                        <td id="T_9e8c7_row23_col8" class="data row23 col8" >-110.94</td>
                        <td id="T_9e8c7_row23_col9" class="data row23 col9" >-</td>
                        <td id="T_9e8c7_row23_col10" class="data row23 col10" >-</td>
                        <td id="T_9e8c7_row23_col11" class="data row23 col11" >-</td>
                        <td id="T_9e8c7_row23_col12" class="data row23 col12" >2020-12-31</td>
            </tr>
            <tr>
                        <th id="T_9e8c7_level0_row24" class="row_heading level0 row24" >AMD</th>
                        <td id="T_9e8c7_row24_col0" class="data row24 col0" >Advanced Micro Devic</td>
                        <td id="T_9e8c7_row24_col1" class="data row24 col1" >34.87</td>
                        <td id="T_9e8c7_row24_col2" class="data row24 col2" >18.95</td>
                        <td id="T_9e8c7_row24_col3" class="data row24 col3" >8.79</td>
                        <td id="T_9e8c7_row24_col4" class="data row24 col4" >24.09</td>
                        <td id="T_9e8c7_row24_col5" class="data row24 col5" >16.99</td>
                        <td id="T_9e8c7_row24_col6" class="data row24 col6" >-163.27</td>
                        <td id="T_9e8c7_row24_col7" class="data row24 col7" >15.78</td>
                        <td id="T_9e8c7_row24_col8" class="data row24 col8" >-34.90</td>
                        <td id="T_9e8c7_row24_col9" class="data row24 col9" >34.25</td>
                        <td id="T_9e8c7_row24_col10" class="data row24 col10" >126.47</td>
                        <td id="T_9e8c7_row24_col11" class="data row24 col11" >-</td>
                        <td id="T_9e8c7_row24_col12" class="data row24 col12" >2021-03-27</td>
            </tr>
            <tr>
                        <th id="T_9e8c7_level0_row25" class="row_heading level0 row25" >XPEV</th>
                        <td id="T_9e8c7_row25_col0" class="data row25 col0" >XPeng Inc. American </td>
                        <td id="T_9e8c7_row25_col1" class="data row25 col1" >22.99</td>
                        <td id="T_9e8c7_row25_col2" class="data row25 col2" >36.71</td>
                        <td id="T_9e8c7_row25_col3" class="data row25 col3" >-4,872.58</td>
                        <td id="T_9e8c7_row25_col4" class="data row25 col4" >11,983.54</td>
                        <td id="T_9e8c7_row25_col5" class="data row25 col5" >151.78</td>
                        <td id="T_9e8c7_row25_col6" class="data row25 col6" >68.96</td>
                        <td id="T_9e8c7_row25_col7" class="data row25 col7" >-26.00</td>
                        <td id="T_9e8c7_row25_col8" class="data row25 col8" >25.86</td>
                        <td id="T_9e8c7_row25_col9" class="data row25 col9" >-</td>
                        <td id="T_9e8c7_row25_col10" class="data row25 col10" >-</td>
                        <td id="T_9e8c7_row25_col11" class="data row25 col11" >-</td>
                        <td id="T_9e8c7_row25_col12" class="data row25 col12" >2020-12-31</td>
            </tr>
            <tr>
                        <th id="T_9e8c7_level0_row26" class="row_heading level0 row26" >TAL</th>
                        <td id="T_9e8c7_row26_col0" class="data row26 col0" >TAL Education Group </td>
                        <td id="T_9e8c7_row26_col1" class="data row26 col1" >57.03</td>
                        <td id="T_9e8c7_row26_col2" class="data row26 col2" >5.10</td>
                        <td id="T_9e8c7_row26_col3" class="data row26 col3" >4.99</td>
                        <td id="T_9e8c7_row26_col4" class="data row26 col4" >38.17</td>
                        <td id="T_9e8c7_row26_col5" class="data row26 col5" >37.35</td>
                        <td id="T_9e8c7_row26_col6" class="data row26 col6" >-13.23</td>
                        <td id="T_9e8c7_row26_col7" class="data row26 col7" >5.26</td>
                        <td id="T_9e8c7_row26_col8" class="data row26 col8" >340.43</td>
                        <td id="T_9e8c7_row26_col9" class="data row26 col9" >-</td>
                        <td id="T_9e8c7_row26_col10" class="data row26 col10" >1,345.47</td>
                        <td id="T_9e8c7_row26_col11" class="data row26 col11" >-</td>
                        <td id="T_9e8c7_row26_col12" class="data row26 col12" >2021-02-28</td>
            </tr>
            <tr>
                        <th id="T_9e8c7_level0_row27" class="row_heading level0 row27" >XNET</th>
                        <td id="T_9e8c7_row27_col0" class="data row27 col0" >Xunlei Limited Ameri</td>
                        <td id="T_9e8c7_row27_col1" class="data row27 col1" >30.13</td>
                        <td id="T_9e8c7_row27_col2" class="data row27 col2" >-10.96</td>
                        <td id="T_9e8c7_row27_col3" class="data row27 col3" >-18.19</td>
                        <td id="T_9e8c7_row27_col4" class="data row27 col4" >-1.18</td>
                        <td id="T_9e8c7_row27_col5" class="data row27 col5" >3.16</td>
                        <td id="T_9e8c7_row27_col6" class="data row27 col6" >-11.58</td>
                        <td id="T_9e8c7_row27_col7" class="data row27 col7" >-73.97</td>
                        <td id="T_9e8c7_row27_col8" class="data row27 col8" >22.97</td>
                        <td id="T_9e8c7_row27_col9" class="data row27 col9" >-</td>
                        <td id="T_9e8c7_row27_col10" class="data row27 col10" >-</td>
                        <td id="T_9e8c7_row27_col11" class="data row27 col11" >-</td>
                        <td id="T_9e8c7_row27_col12" class="data row27 col12" >2020-12-31</td>
            </tr>
            <tr>
                        <th id="T_9e8c7_level0_row28" class="row_heading level0 row28" >DIS</th>
                        <td id="T_9e8c7_row28_col0" class="data row28 col0" >Walt Disney Company </td>
                        <td id="T_9e8c7_row28_col1" class="data row28 col1" >51.62</td>
                        <td id="T_9e8c7_row28_col2" class="data row28 col2" >14.14</td>
                        <td id="T_9e8c7_row28_col3" class="data row28 col3" >12.25</td>
                        <td id="T_9e8c7_row28_col4" class="data row28 col4" >6.28</td>
                        <td id="T_9e8c7_row28_col5" class="data row28 col5" >-7.05</td>
                        <td id="T_9e8c7_row28_col6" class="data row28 col6" >-32.63</td>
                        <td id="T_9e8c7_row28_col7" class="data row28 col7" >72.97</td>
                        <td id="T_9e8c7_row28_col8" class="data row28 col8" >12.73</td>
                        <td id="T_9e8c7_row28_col9" class="data row28 col9" >-</td>
                        <td id="T_9e8c7_row28_col10" class="data row28 col10" >43.22</td>
                        <td id="T_9e8c7_row28_col11" class="data row28 col11" >-</td>
                        <td id="T_9e8c7_row28_col12" class="data row28 col12" >2021-01-02</td>
            </tr>
            <tr>
                        <th id="T_9e8c7_level0_row29" class="row_heading level0 row29" >GILD</th>
                        <td id="T_9e8c7_row29_col0" class="data row29 col0" >Gilead Sciences Inc.</td>
                        <td id="T_9e8c7_row29_col1" class="data row29 col1" >73.36</td>
                        <td id="T_9e8c7_row29_col2" class="data row29 col2" >18.18</td>
                        <td id="T_9e8c7_row29_col3" class="data row29 col3" >16.72</td>
                        <td id="T_9e8c7_row29_col4" class="data row29 col4" >-1.27</td>
                        <td id="T_9e8c7_row29_col5" class="data row29 col5" >3.54</td>
                        <td id="T_9e8c7_row29_col6" class="data row29 col6" >-27.04</td>
                        <td id="T_9e8c7_row29_col7" class="data row29 col7" >144.72</td>
                        <td id="T_9e8c7_row29_col8" class="data row29 col8" >-10.75</td>
                        <td id="T_9e8c7_row29_col9" class="data row29 col9" >280.96</td>
                        <td id="T_9e8c7_row29_col10" class="data row29 col10" >21.78</td>
                        <td id="T_9e8c7_row29_col11" class="data row29 col11" >-</td>
                        <td id="T_9e8c7_row29_col12" class="data row29 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_9e8c7_level0_row30" class="row_heading level0 row30" >TWTR</th>
                        <td id="T_9e8c7_row30_col0" class="data row30 col0" >Twitter Inc. Common </td>
                        <td id="T_9e8c7_row30_col1" class="data row30 col1" >40.43</td>
                        <td id="T_9e8c7_row30_col2" class="data row30 col2" >4.54</td>
                        <td id="T_9e8c7_row30_col3" class="data row30 col3" >11.75</td>
                        <td id="T_9e8c7_row30_col4" class="data row30 col4" >15.22</td>
                        <td id="T_9e8c7_row30_col5" class="data row30 col5" >6.15</td>
                        <td id="T_9e8c7_row30_col6" class="data row30 col6" >-457.18</td>
                        <td id="T_9e8c7_row30_col7" class="data row30 col7" >-6.73</td>
                        <td id="T_9e8c7_row30_col8" class="data row30 col8" >-22.52</td>
                        <td id="T_9e8c7_row30_col9" class="data row30 col9" >-</td>
                        <td id="T_9e8c7_row30_col10" class="data row30 col10" >131.94</td>
                        <td id="T_9e8c7_row30_col11" class="data row30 col11" >-</td>
                        <td id="T_9e8c7_row30_col12" class="data row30 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_9e8c7_level0_row31" class="row_heading level0 row31" >PFE</th>
                        <td id="T_9e8c7_row31_col0" class="data row31 col0" >Pfizer Inc. Common S</td>
                        <td id="T_9e8c7_row31_col1" class="data row31 col1" >58.84</td>
                        <td id="T_9e8c7_row31_col2" class="data row31 col2" >22.12</td>
                        <td id="T_9e8c7_row31_col3" class="data row31 col3" >32.59</td>
                        <td id="T_9e8c7_row31_col4" class="data row31 col4" >-6.56</td>
                        <td id="T_9e8c7_row31_col5" class="data row31 col5" >1.79</td>
                        <td id="T_9e8c7_row31_col6" class="data row31 col6" >-14.22</td>
                        <td id="T_9e8c7_row31_col7" class="data row31 col7" >-40.91</td>
                        <td id="T_9e8c7_row31_col8" class="data row31 col8" >-5.08</td>
                        <td id="T_9e8c7_row31_col9" class="data row31 col9" >22.93</td>
                        <td id="T_9e8c7_row31_col10" class="data row31 col10" >14.97</td>
                        <td id="T_9e8c7_row31_col11" class="data row31 col11" >-</td>
                        <td id="T_9e8c7_row31_col12" class="data row31 col12" >2020-12-31</td>
            </tr>
            <tr>
                        <th id="T_9e8c7_level0_row32" class="row_heading level0 row32" >WFC</th>
                        <td id="T_9e8c7_row32_col0" class="data row32 col0" >Wells Fargo & Compan</td>
                        <td id="T_9e8c7_row32_col1" class="data row32 col1" >90.49</td>
                        <td id="T_9e8c7_row32_col2" class="data row32 col2" >9.67</td>
                        <td id="T_9e8c7_row32_col3" class="data row32 col3" >20.40</td>
                        <td id="T_9e8c7_row32_col4" class="data row32 col4" >-11.14</td>
                        <td id="T_9e8c7_row32_col5" class="data row32 col5" >9.26</td>
                        <td id="T_9e8c7_row32_col6" class="data row32 col6" >-31.62</td>
                        <td id="T_9e8c7_row32_col7" class="data row32 col7" >123.87</td>
                        <td id="T_9e8c7_row32_col8" class="data row32 col8" >-</td>
                        <td id="T_9e8c7_row32_col9" class="data row32 col9" >32.25</td>
                        <td id="T_9e8c7_row32_col10" class="data row32 col10" >11.54</td>
                        <td id="T_9e8c7_row32_col11" class="data row32 col11" >-</td>
                        <td id="T_9e8c7_row32_col12" class="data row32 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_9e8c7_level0_row33" class="row_heading level0 row33" >FUTU</th>
                        <td id="T_9e8c7_row33_col0" class="data row33 col0" >Futu Holdings Limite</td>
                        <td id="T_9e8c7_row33_col1" class="data row33 col1" >88.35</td>
                        <td id="T_9e8c7_row33_col2" class="data row33 col2" >-16.57</td>
                        <td id="T_9e8c7_row33_col3" class="data row33 col3" >19.01</td>
                        <td id="T_9e8c7_row33_col4" class="data row33 col4" >134.20</td>
                        <td id="T_9e8c7_row33_col5" class="data row33 col5" >221.47</td>
                        <td id="T_9e8c7_row33_col6" class="data row33 col6" >-363.29</td>
                        <td id="T_9e8c7_row33_col7" class="data row33 col7" >700.13</td>
                        <td id="T_9e8c7_row33_col8" class="data row33 col8" >361.72</td>
                        <td id="T_9e8c7_row33_col9" class="data row33 col9" >119.18</td>
                        <td id="T_9e8c7_row33_col10" class="data row33 col10" >55.97</td>
                        <td id="T_9e8c7_row33_col11" class="data row33 col11" >-</td>
                        <td id="T_9e8c7_row33_col12" class="data row33 col12" >2020-12-31</td>
            </tr>
            <tr>
                        <th id="T_9e8c7_level0_row34" class="row_heading level0 row34" >TIGR</th>
                        <td id="T_9e8c7_row34_col0" class="data row34 col0" >UP Fintech Holding L</td>
                        <td id="T_9e8c7_row34_col1" class="data row34 col1" >89.25</td>
                        <td id="T_9e8c7_row34_col2" class="data row34 col2" >38.57</td>
                        <td id="T_9e8c7_row34_col3" class="data row34 col3" >-43.16</td>
                        <td id="T_9e8c7_row34_col4" class="data row34 col4" >98.63</td>
                        <td id="T_9e8c7_row34_col5" class="data row34 col5" >135.32</td>
                        <td id="T_9e8c7_row34_col6" class="data row34 col6" >15.60</td>
                        <td id="T_9e8c7_row34_col7" class="data row34 col7" >-343.80</td>
                        <td id="T_9e8c7_row34_col8" class="data row34 col8" >-295.56</td>
                        <td id="T_9e8c7_row34_col9" class="data row34 col9" >234.21</td>
                        <td id="T_9e8c7_row34_col10" class="data row34 col10" >-</td>
                        <td id="T_9e8c7_row34_col11" class="data row34 col11" >-</td>
                        <td id="T_9e8c7_row34_col12" class="data row34 col12" >2020-12-31</td>
            </tr>
            <tr>
                        <th id="T_9e8c7_level0_row35" class="row_heading level0 row35" >NIU</th>
                        <td id="T_9e8c7_row35_col0" class="data row35 col0" >Niu Technologies Ame</td>
                        <td id="T_9e8c7_row35_col1" class="data row35 col1" >46.21</td>
                        <td id="T_9e8c7_row35_col2" class="data row35 col2" >9.14</td>
                        <td id="T_9e8c7_row35_col3" class="data row35 col3" >-7.89</td>
                        <td id="T_9e8c7_row35_col4" class="data row35 col4" >50.10</td>
                        <td id="T_9e8c7_row35_col5" class="data row35 col5" >17.73</td>
                        <td id="T_9e8c7_row35_col6" class="data row35 col6" >-25.58</td>
                        <td id="T_9e8c7_row35_col7" class="data row35 col7" >-11.28</td>
                        <td id="T_9e8c7_row35_col8" class="data row35 col8" >-22.35</td>
                        <td id="T_9e8c7_row35_col9" class="data row35 col9" >101.93</td>
                        <td id="T_9e8c7_row35_col10" class="data row35 col10" >-</td>
                        <td id="T_9e8c7_row35_col11" class="data row35 col11" >-</td>
                        <td id="T_9e8c7_row35_col12" class="data row35 col12" >2020-12-31</td>
            </tr>
    </tbody></table>



## 港股

### 指标选股

1. 负债率 < 50%
2. 应收比 < 20%
3. 商誉比 < 20%
4. ROE >= 20%
5. 利润率 >= 20%
6. 收入增长 >= 15% 且 盈利增长 >= 15%




<style  type="text/css" >
#T_d1671_row0_col0,#T_d1671_row0_col1,#T_d1671_row0_col2,#T_d1671_row0_col3,#T_d1671_row0_col4,#T_d1671_row0_col5,#T_d1671_row0_col6,#T_d1671_row0_col7,#T_d1671_row0_col8,#T_d1671_row0_col9,#T_d1671_row0_col10,#T_d1671_row0_col11,#T_d1671_row0_col12,#T_d1671_row1_col0,#T_d1671_row1_col1,#T_d1671_row1_col2,#T_d1671_row1_col3,#T_d1671_row1_col4,#T_d1671_row1_col5,#T_d1671_row1_col6,#T_d1671_row1_col7,#T_d1671_row1_col8,#T_d1671_row1_col9,#T_d1671_row1_col10,#T_d1671_row1_col11,#T_d1671_row1_col12,#T_d1671_row2_col0,#T_d1671_row2_col1,#T_d1671_row2_col2,#T_d1671_row2_col3,#T_d1671_row2_col4,#T_d1671_row2_col5,#T_d1671_row2_col6,#T_d1671_row2_col7,#T_d1671_row2_col8,#T_d1671_row2_col9,#T_d1671_row2_col10,#T_d1671_row2_col11,#T_d1671_row2_col12,#T_d1671_row3_col0,#T_d1671_row3_col1,#T_d1671_row3_col2,#T_d1671_row3_col3,#T_d1671_row3_col4,#T_d1671_row3_col5,#T_d1671_row3_col6,#T_d1671_row3_col8,#T_d1671_row3_col9,#T_d1671_row3_col10,#T_d1671_row3_col11,#T_d1671_row3_col12,#T_d1671_row4_col0,#T_d1671_row4_col1,#T_d1671_row4_col2,#T_d1671_row4_col3,#T_d1671_row4_col4,#T_d1671_row4_col5,#T_d1671_row4_col6,#T_d1671_row4_col7,#T_d1671_row4_col8,#T_d1671_row4_col9,#T_d1671_row4_col10,#T_d1671_row4_col11,#T_d1671_row4_col12,#T_d1671_row5_col0,#T_d1671_row5_col1,#T_d1671_row5_col2,#T_d1671_row5_col3,#T_d1671_row5_col4,#T_d1671_row5_col6,#T_d1671_row5_col8,#T_d1671_row5_col9,#T_d1671_row5_col10,#T_d1671_row5_col11,#T_d1671_row5_col12,#T_d1671_row6_col0,#T_d1671_row6_col1,#T_d1671_row6_col2,#T_d1671_row6_col3,#T_d1671_row6_col4,#T_d1671_row6_col5,#T_d1671_row6_col6,#T_d1671_row6_col7,#T_d1671_row6_col8,#T_d1671_row6_col9,#T_d1671_row6_col10,#T_d1671_row6_col11,#T_d1671_row6_col12,#T_d1671_row7_col0,#T_d1671_row7_col1,#T_d1671_row7_col2,#T_d1671_row7_col3,#T_d1671_row7_col4,#T_d1671_row7_col6,#T_d1671_row7_col8,#T_d1671_row7_col9,#T_d1671_row7_col10,#T_d1671_row7_col11,#T_d1671_row7_col12,#T_d1671_row8_col0,#T_d1671_row8_col1,#T_d1671_row8_col2,#T_d1671_row8_col3,#T_d1671_row8_col4,#T_d1671_row8_col5,#T_d1671_row8_col6,#T_d1671_row8_col8,#T_d1671_row8_col9,#T_d1671_row8_col10,#T_d1671_row8_col11,#T_d1671_row8_col12,#T_d1671_row9_col0,#T_d1671_row9_col1,#T_d1671_row9_col2,#T_d1671_row9_col3,#T_d1671_row9_col4,#T_d1671_row9_col5,#T_d1671_row9_col6,#T_d1671_row9_col7,#T_d1671_row9_col8,#T_d1671_row9_col9,#T_d1671_row9_col10,#T_d1671_row9_col11,#T_d1671_row9_col12,#T_d1671_row10_col0,#T_d1671_row10_col1,#T_d1671_row10_col2,#T_d1671_row10_col3,#T_d1671_row10_col4,#T_d1671_row10_col5,#T_d1671_row10_col6,#T_d1671_row10_col7,#T_d1671_row10_col8,#T_d1671_row10_col9,#T_d1671_row10_col10,#T_d1671_row10_col11,#T_d1671_row10_col12{
            color:  black;
        }#T_d1671_row3_col7,#T_d1671_row5_col5,#T_d1671_row5_col7,#T_d1671_row7_col5,#T_d1671_row7_col7,#T_d1671_row8_col7{
            color:  red;
        }</style><table id="T_d1671_" ><thead>    <tr>        <th class="blank level0" ></th>        <th class="col_heading level0 col0" >名称</th>        <th class="col_heading level0 col1" >负债率</th>        <th class="col_heading level0 col2" >ROE</th>        <th class="col_heading level0 col3" >利润率</th>        <th class="col_heading level0 col4" >收入增长</th>        <th class="col_heading level0 col5" >收入增长TTM</th>        <th class="col_heading level0 col6" >盈利增长</th>        <th class="col_heading level0 col7" >盈利增长TTM</th>        <th class="col_heading level0 col8" >FCF增长</th>        <th class="col_heading level0 col9" >PE</th>        <th class="col_heading level0 col10" >PEm</th>        <th class="col_heading level0 col11" >PEG</th>        <th class="col_heading level0 col12" >季报日期</th>    </tr>    <tr>        <th class="index_name level0" >Symbol</th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>    </tr></thead><tbody>
                <tr>
                        <th id="T_d1671_level0_row0" class="row_heading level0 row0" >2660.HK</th>
                        <td id="T_d1671_row0_col0" class="data row0 col0" >禅游科技</td>
                        <td id="T_d1671_row0_col1" class="data row0 col1" >6.95</td>
                        <td id="T_d1671_row0_col2" class="data row0 col2" >31.91</td>
                        <td id="T_d1671_row0_col3" class="data row0 col3" >22.01</td>
                        <td id="T_d1671_row0_col4" class="data row0 col4" >17.39</td>
                        <td id="T_d1671_row0_col5" class="data row0 col5" >12.14</td>
                        <td id="T_d1671_row0_col6" class="data row0 col6" >49.69</td>
                        <td id="T_d1671_row0_col7" class="data row0 col7" >37.66</td>
                        <td id="T_d1671_row0_col8" class="data row0 col8" >54.05</td>
                        <td id="T_d1671_row0_col9" class="data row0 col9" >-</td>
                        <td id="T_d1671_row0_col10" class="data row0 col10" >7.72</td>
                        <td id="T_d1671_row0_col11" class="data row0 col11" >0.16</td>
                        <td id="T_d1671_row0_col12" class="data row0 col12" >2020-12-31</td>
            </tr>
            <tr>
                        <th id="T_d1671_level0_row1" class="row_heading level0 row1" >6820.HK</th>
                        <td id="T_d1671_row1_col0" class="data row1 col0" >友谊时光</td>
                        <td id="T_d1671_row1_col1" class="data row1 col1" >12.60</td>
                        <td id="T_d1671_row1_col2" class="data row1 col2" >38.95</td>
                        <td id="T_d1671_row1_col3" class="data row1 col3" >21.88</td>
                        <td id="T_d1671_row1_col4" class="data row1 col4" >51.22</td>
                        <td id="T_d1671_row1_col5" class="data row1 col5" >29.20</td>
                        <td id="T_d1671_row1_col6" class="data row1 col6" >76.65</td>
                        <td id="T_d1671_row1_col7" class="data row1 col7" >21.18</td>
                        <td id="T_d1671_row1_col8" class="data row1 col8" >78.93</td>
                        <td id="T_d1671_row1_col9" class="data row1 col9" >-</td>
                        <td id="T_d1671_row1_col10" class="data row1 col10" >12.68</td>
                        <td id="T_d1671_row1_col11" class="data row1 col11" >0.17</td>
                        <td id="T_d1671_row1_col12" class="data row1 col12" >2020-12-31</td>
            </tr>
            <tr>
                        <th id="T_d1671_level0_row2" class="row_heading level0 row2" >0914.HK</th>
                        <td id="T_d1671_row2_col0" class="data row2 col0" >海螺水泥</td>
                        <td id="T_d1671_row2_col1" class="data row2 col1" >16.30</td>
                        <td id="T_d1671_row2_col2" class="data row2 col2" >22.59</td>
                        <td id="T_d1671_row2_col3" class="data row2 col3" >21.40</td>
                        <td id="T_d1671_row2_col4" class="data row2 col4" >35.01</td>
                        <td id="T_d1671_row2_col5" class="data row2 col5" >6.37</td>
                        <td id="T_d1671_row2_col6" class="data row2 col6" >35.10</td>
                        <td id="T_d1671_row2_col7" class="data row2 col7" >2.55</td>
                        <td id="T_d1671_row2_col8" class="data row2 col8" >36.04</td>
                        <td id="T_d1671_row2_col9" class="data row2 col9" >6.11</td>
                        <td id="T_d1671_row2_col10" class="data row2 col10" >7.83</td>
                        <td id="T_d1671_row2_col11" class="data row2 col11" >0.22</td>
                        <td id="T_d1671_row2_col12" class="data row2 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_d1671_level0_row3" class="row_heading level0 row3" >1277.HK</th>
                        <td id="T_d1671_row3_col0" class="data row3 col0" >力量能源</td>
                        <td id="T_d1671_row3_col1" class="data row3 col1" >24.86</td>
                        <td id="T_d1671_row3_col2" class="data row3 col2" >38.28</td>
                        <td id="T_d1671_row3_col3" class="data row3 col3" >30.47</td>
                        <td id="T_d1671_row3_col4" class="data row3 col4" >19.96</td>
                        <td id="T_d1671_row3_col5" class="data row3 col5" >8.23</td>
                        <td id="T_d1671_row3_col6" class="data row3 col6" >16.82</td>
                        <td id="T_d1671_row3_col7" class="data row3 col7" >-2.22</td>
                        <td id="T_d1671_row3_col8" class="data row3 col8" >22.58</td>
                        <td id="T_d1671_row3_col9" class="data row3 col9" >4.71</td>
                        <td id="T_d1671_row3_col10" class="data row3 col10" >4.83</td>
                        <td id="T_d1671_row3_col11" class="data row3 col11" >0.29</td>
                        <td id="T_d1671_row3_col12" class="data row3 col12" >2020-12-31</td>
            </tr>
            <tr>
                        <th id="T_d1671_level0_row4" class="row_heading level0 row4" >3798.HK</th>
                        <td id="T_d1671_row4_col0" class="data row4 col0" >家乡互动</td>
                        <td id="T_d1671_row4_col1" class="data row4 col1" >14.06</td>
                        <td id="T_d1671_row4_col2" class="data row4 col2" >68.29</td>
                        <td id="T_d1671_row4_col3" class="data row4 col3" >44.74</td>
                        <td id="T_d1671_row4_col4" class="data row4 col4" >44.37</td>
                        <td id="T_d1671_row4_col5" class="data row4 col5" >36.65</td>
                        <td id="T_d1671_row4_col6" class="data row4 col6" >54.15</td>
                        <td id="T_d1671_row4_col7" class="data row4 col7" >88.99</td>
                        <td id="T_d1671_row4_col8" class="data row4 col8" >31.66</td>
                        <td id="T_d1671_row4_col9" class="data row4 col9" >-</td>
                        <td id="T_d1671_row4_col10" class="data row4 col10" >21.84</td>
                        <td id="T_d1671_row4_col11" class="data row4 col11" >0.40</td>
                        <td id="T_d1671_row4_col12" class="data row4 col12" >2020-12-31</td>
            </tr>
            <tr>
                        <th id="T_d1671_level0_row5" class="row_heading level0 row5" >3601.HK</th>
                        <td id="T_d1671_row5_col0" class="data row5 col0" >鲁大师</td>
                        <td id="T_d1671_row5_col1" class="data row5 col1" >6.89</td>
                        <td id="T_d1671_row5_col2" class="data row5 col2" >28.40</td>
                        <td id="T_d1671_row5_col3" class="data row5 col3" >28.15</td>
                        <td id="T_d1671_row5_col4" class="data row5 col4" >57.87</td>
                        <td id="T_d1671_row5_col5" class="data row5 col5" >-13.99</td>
                        <td id="T_d1671_row5_col6" class="data row5 col6" >16.75</td>
                        <td id="T_d1671_row5_col7" class="data row5 col7" >-30.59</td>
                        <td id="T_d1671_row5_col8" class="data row5 col8" >2.86</td>
                        <td id="T_d1671_row5_col9" class="data row5 col9" >-</td>
                        <td id="T_d1671_row5_col10" class="data row5 col10" >7.89</td>
                        <td id="T_d1671_row5_col11" class="data row5 col11" >0.47</td>
                        <td id="T_d1671_row5_col12" class="data row5 col12" >2020-12-31</td>
            </tr>
            <tr>
                        <th id="T_d1671_level0_row6" class="row_heading level0 row6" >6186.HK</th>
                        <td id="T_d1671_row6_col0" class="data row6 col0" >中国飞鹤</td>
                        <td id="T_d1671_row6_col1" class="data row6 col1" >32.26</td>
                        <td id="T_d1671_row6_col2" class="data row6 col2" >35.80</td>
                        <td id="T_d1671_row6_col3" class="data row6 col3" >27.49</td>
                        <td id="T_d1671_row6_col4" class="data row6 col4" >48.02</td>
                        <td id="T_d1671_row6_col5" class="data row6 col5" >35.50</td>
                        <td id="T_d1671_row6_col6" class="data row6 col6" >85.92</td>
                        <td id="T_d1671_row6_col7" class="data row6 col7" >89.01</td>
                        <td id="T_d1671_row6_col8" class="data row6 col8" >66.16</td>
                        <td id="T_d1671_row6_col9" class="data row6 col9" >-</td>
                        <td id="T_d1671_row6_col10" class="data row6 col10" >42.60</td>
                        <td id="T_d1671_row6_col11" class="data row6 col11" >0.50</td>
                        <td id="T_d1671_row6_col12" class="data row6 col12" >2020-12-31</td>
            </tr>
            <tr>
                        <th id="T_d1671_level0_row7" class="row_heading level0 row7" >1830.HK</th>
                        <td id="T_d1671_row7_col0" class="data row7 col0" >必瘦站</td>
                        <td id="T_d1671_row7_col1" class="data row7 col1" >47.74</td>
                        <td id="T_d1671_row7_col2" class="data row7 col2" >42.84</td>
                        <td id="T_d1671_row7_col3" class="data row7 col3" >22.29</td>
                        <td id="T_d1671_row7_col4" class="data row7 col4" >18.49</td>
                        <td id="T_d1671_row7_col5" class="data row7 col5" >-15.98</td>
                        <td id="T_d1671_row7_col6" class="data row7 col6" >63.25</td>
                        <td id="T_d1671_row7_col7" class="data row7 col7" >-29.78</td>
                        <td id="T_d1671_row7_col8" class="data row7 col8" >52.20</td>
                        <td id="T_d1671_row7_col9" class="data row7 col9" >25.62</td>
                        <td id="T_d1671_row7_col10" class="data row7 col10" >34.51</td>
                        <td id="T_d1671_row7_col11" class="data row7 col11" >0.55</td>
                        <td id="T_d1671_row7_col12" class="data row7 col12" >2020-09-30</td>
            </tr>
            <tr>
                        <th id="T_d1671_level0_row8" class="row_heading level0 row8" >9999.HK</th>
                        <td id="T_d1671_row8_col0" class="data row8 col0" >网易-S</td>
                        <td id="T_d1671_row8_col1" class="data row8 col1" >33.89</td>
                        <td id="T_d1671_row8_col2" class="data row8 col2" >21.57</td>
                        <td id="T_d1671_row8_col3" class="data row8 col3" >22.09</td>
                        <td id="T_d1671_row8_col4" class="data row8 col4" >18.43</td>
                        <td id="T_d1671_row8_col5" class="data row8 col5" >24.35</td>
                        <td id="T_d1671_row8_col6" class="data row8 col6" >53.15</td>
                        <td id="T_d1671_row8_col7" class="data row8 col7" >-43.20</td>
                        <td id="T_d1671_row8_col8" class="data row8 col8" >33.70</td>
                        <td id="T_d1671_row8_col9" class="data row8 col9" >-</td>
                        <td id="T_d1671_row8_col10" class="data row8 col10" >39.08</td>
                        <td id="T_d1671_row8_col11" class="data row8 col11" >0.74</td>
                        <td id="T_d1671_row8_col12" class="data row8 col12" >2020-12-31</td>
            </tr>
            <tr>
                        <th id="T_d1671_level0_row9" class="row_heading level0 row9" >0700.HK</th>
                        <td id="T_d1671_row9_col0" class="data row9 col0" >腾讯控股</td>
                        <td id="T_d1671_row9_col1" class="data row9 col1" >41.65</td>
                        <td id="T_d1671_row9_col2" class="data row9 col2" >24.13</td>
                        <td id="T_d1671_row9_col3" class="data row9 col3" >28.29</td>
                        <td id="T_d1671_row9_col4" class="data row9 col4" >26.65</td>
                        <td id="T_d1671_row9_col5" class="data row9 col5" >27.77</td>
                        <td id="T_d1671_row9_col6" class="data row9 col6" >33.31</td>
                        <td id="T_d1671_row9_col7" class="data row9 col7" >71.31</td>
                        <td id="T_d1671_row9_col8" class="data row9 col8" >20.72</td>
                        <td id="T_d1671_row9_col9" class="data row9 col9" >55.52</td>
                        <td id="T_d1671_row9_col10" class="data row9 col10" >47.99</td>
                        <td id="T_d1671_row9_col11" class="data row9 col11" >1.44</td>
                        <td id="T_d1671_row9_col12" class="data row9 col12" >2020-12-31</td>
            </tr>
            <tr>
                        <th id="T_d1671_level0_row10" class="row_heading level0 row10" >9997.HK</th>
                        <td id="T_d1671_row10_col0" class="data row10 col0" >康基医疗</td>
                        <td id="T_d1671_row10_col1" class="data row10 col1" >2.77</td>
                        <td id="T_d1671_row10_col2" class="data row10 col2" >43.05</td>
                        <td id="T_d1671_row10_col3" class="data row10 col3" >44.74</td>
                        <td id="T_d1671_row10_col4" class="data row10 col4" >28.95</td>
                        <td id="T_d1671_row10_col5" class="data row10 col5" >1.59</td>
                        <td id="T_d1671_row10_col6" class="data row10 col6" >28.87</td>
                        <td id="T_d1671_row10_col7" class="data row10 col7" >21.24</td>
                        <td id="T_d1671_row10_col8" class="data row10 col8" >23.56</td>
                        <td id="T_d1671_row10_col9" class="data row10 col9" >-</td>
                        <td id="T_d1671_row10_col10" class="data row10 col10" >76.09</td>
                        <td id="T_d1671_row10_col11" class="data row10 col11" >2.64</td>
                        <td id="T_d1671_row10_col12" class="data row10 col12" >2020-12-31</td>
            </tr>
    </tbody></table>



### 观察列表




<style  type="text/css" >
#T_9caad_row0_col0,#T_9caad_row0_col1,#T_9caad_row0_col2,#T_9caad_row0_col3,#T_9caad_row0_col4,#T_9caad_row0_col5,#T_9caad_row0_col6,#T_9caad_row0_col7,#T_9caad_row0_col8,#T_9caad_row0_col9,#T_9caad_row0_col10,#T_9caad_row0_col11,#T_9caad_row0_col12,#T_9caad_row1_col0,#T_9caad_row1_col1,#T_9caad_row1_col2,#T_9caad_row1_col3,#T_9caad_row1_col4,#T_9caad_row1_col5,#T_9caad_row1_col6,#T_9caad_row1_col7,#T_9caad_row1_col9,#T_9caad_row1_col10,#T_9caad_row1_col11,#T_9caad_row1_col12,#T_9caad_row2_col0,#T_9caad_row2_col1,#T_9caad_row2_col2,#T_9caad_row2_col3,#T_9caad_row2_col4,#T_9caad_row2_col5,#T_9caad_row2_col6,#T_9caad_row2_col7,#T_9caad_row2_col9,#T_9caad_row2_col10,#T_9caad_row2_col11,#T_9caad_row2_col12,#T_9caad_row3_col0,#T_9caad_row3_col1,#T_9caad_row3_col2,#T_9caad_row3_col3,#T_9caad_row3_col4,#T_9caad_row3_col5,#T_9caad_row3_col6,#T_9caad_row3_col7,#T_9caad_row3_col8,#T_9caad_row3_col9,#T_9caad_row3_col10,#T_9caad_row3_col11,#T_9caad_row3_col12,#T_9caad_row4_col0,#T_9caad_row4_col1,#T_9caad_row4_col2,#T_9caad_row4_col3,#T_9caad_row4_col4,#T_9caad_row4_col6,#T_9caad_row4_col9,#T_9caad_row4_col10,#T_9caad_row4_col11,#T_9caad_row4_col12,#T_9caad_row5_col0,#T_9caad_row5_col1,#T_9caad_row5_col2,#T_9caad_row5_col3,#T_9caad_row5_col4,#T_9caad_row5_col5,#T_9caad_row5_col6,#T_9caad_row5_col7,#T_9caad_row5_col8,#T_9caad_row5_col9,#T_9caad_row5_col10,#T_9caad_row5_col11,#T_9caad_row5_col12,#T_9caad_row6_col0,#T_9caad_row6_col1,#T_9caad_row6_col2,#T_9caad_row6_col3,#T_9caad_row6_col4,#T_9caad_row6_col5,#T_9caad_row6_col6,#T_9caad_row6_col8,#T_9caad_row6_col9,#T_9caad_row6_col10,#T_9caad_row6_col11,#T_9caad_row6_col12,#T_9caad_row7_col0,#T_9caad_row7_col1,#T_9caad_row7_col2,#T_9caad_row7_col3,#T_9caad_row7_col4,#T_9caad_row7_col6,#T_9caad_row7_col9,#T_9caad_row7_col10,#T_9caad_row7_col11,#T_9caad_row7_col12,#T_9caad_row8_col0,#T_9caad_row8_col1,#T_9caad_row8_col2,#T_9caad_row8_col3,#T_9caad_row8_col4,#T_9caad_row8_col5,#T_9caad_row8_col6,#T_9caad_row8_col7,#T_9caad_row8_col9,#T_9caad_row8_col10,#T_9caad_row8_col11,#T_9caad_row8_col12,#T_9caad_row9_col0,#T_9caad_row9_col1,#T_9caad_row9_col2,#T_9caad_row9_col3,#T_9caad_row9_col4,#T_9caad_row9_col5,#T_9caad_row9_col6,#T_9caad_row9_col7,#T_9caad_row9_col8,#T_9caad_row9_col9,#T_9caad_row9_col10,#T_9caad_row9_col11,#T_9caad_row9_col12,#T_9caad_row10_col0,#T_9caad_row10_col1,#T_9caad_row10_col2,#T_9caad_row10_col3,#T_9caad_row10_col4,#T_9caad_row10_col5,#T_9caad_row10_col6,#T_9caad_row10_col7,#T_9caad_row10_col8,#T_9caad_row10_col9,#T_9caad_row10_col10,#T_9caad_row10_col11,#T_9caad_row10_col12,#T_9caad_row11_col0,#T_9caad_row11_col1,#T_9caad_row11_col2,#T_9caad_row11_col4,#T_9caad_row11_col5,#T_9caad_row11_col7,#T_9caad_row11_col9,#T_9caad_row11_col10,#T_9caad_row11_col11,#T_9caad_row11_col12,#T_9caad_row12_col0,#T_9caad_row12_col1,#T_9caad_row12_col2,#T_9caad_row12_col3,#T_9caad_row12_col4,#T_9caad_row12_col5,#T_9caad_row12_col9,#T_9caad_row12_col10,#T_9caad_row12_col11,#T_9caad_row12_col12,#T_9caad_row13_col0,#T_9caad_row13_col1,#T_9caad_row13_col4,#T_9caad_row13_col5,#T_9caad_row13_col6,#T_9caad_row13_col7,#T_9caad_row13_col8,#T_9caad_row13_col9,#T_9caad_row13_col10,#T_9caad_row13_col11,#T_9caad_row13_col12,#T_9caad_row14_col0,#T_9caad_row14_col1,#T_9caad_row14_col2,#T_9caad_row14_col4,#T_9caad_row14_col5,#T_9caad_row14_col6,#T_9caad_row14_col7,#T_9caad_row14_col9,#T_9caad_row14_col10,#T_9caad_row14_col11,#T_9caad_row14_col12,#T_9caad_row15_col0,#T_9caad_row15_col1,#T_9caad_row15_col2,#T_9caad_row15_col4,#T_9caad_row15_col6,#T_9caad_row15_col8,#T_9caad_row15_col9,#T_9caad_row15_col10,#T_9caad_row15_col11,#T_9caad_row15_col12,#T_9caad_row16_col0,#T_9caad_row16_col1,#T_9caad_row16_col4,#T_9caad_row16_col5,#T_9caad_row16_col6,#T_9caad_row16_col8,#T_9caad_row16_col9,#T_9caad_row16_col10,#T_9caad_row16_col11,#T_9caad_row16_col12,#T_9caad_row17_col0,#T_9caad_row17_col1,#T_9caad_row17_col8,#T_9caad_row17_col9,#T_9caad_row17_col10,#T_9caad_row17_col11,#T_9caad_row17_col12,#T_9caad_row18_col0,#T_9caad_row18_col1,#T_9caad_row18_col2,#T_9caad_row18_col3,#T_9caad_row18_col4,#T_9caad_row18_col5,#T_9caad_row18_col9,#T_9caad_row18_col10,#T_9caad_row18_col11,#T_9caad_row18_col12,#T_9caad_row19_col0,#T_9caad_row19_col1,#T_9caad_row19_col2,#T_9caad_row19_col3,#T_9caad_row19_col4,#T_9caad_row19_col5,#T_9caad_row19_col9,#T_9caad_row19_col10,#T_9caad_row19_col11,#T_9caad_row19_col12,#T_9caad_row20_col0,#T_9caad_row20_col1,#T_9caad_row20_col2,#T_9caad_row20_col3,#T_9caad_row20_col9,#T_9caad_row20_col10,#T_9caad_row20_col11,#T_9caad_row20_col12,#T_9caad_row21_col0,#T_9caad_row21_col1,#T_9caad_row21_col4,#T_9caad_row21_col5,#T_9caad_row21_col6,#T_9caad_row21_col7,#T_9caad_row21_col9,#T_9caad_row21_col10,#T_9caad_row21_col11,#T_9caad_row21_col12{
            color:  black;
        }#T_9caad_row1_col8,#T_9caad_row2_col8,#T_9caad_row4_col5,#T_9caad_row4_col7,#T_9caad_row4_col8,#T_9caad_row6_col7,#T_9caad_row7_col5,#T_9caad_row7_col7,#T_9caad_row7_col8,#T_9caad_row8_col8,#T_9caad_row11_col3,#T_9caad_row11_col6,#T_9caad_row11_col8,#T_9caad_row12_col6,#T_9caad_row12_col7,#T_9caad_row12_col8,#T_9caad_row13_col2,#T_9caad_row13_col3,#T_9caad_row14_col3,#T_9caad_row14_col8,#T_9caad_row15_col3,#T_9caad_row15_col5,#T_9caad_row15_col7,#T_9caad_row16_col2,#T_9caad_row16_col3,#T_9caad_row16_col7,#T_9caad_row17_col2,#T_9caad_row17_col3,#T_9caad_row17_col4,#T_9caad_row17_col5,#T_9caad_row17_col6,#T_9caad_row17_col7,#T_9caad_row18_col6,#T_9caad_row18_col7,#T_9caad_row18_col8,#T_9caad_row19_col6,#T_9caad_row19_col7,#T_9caad_row19_col8,#T_9caad_row20_col4,#T_9caad_row20_col5,#T_9caad_row20_col6,#T_9caad_row20_col7,#T_9caad_row20_col8,#T_9caad_row21_col2,#T_9caad_row21_col3,#T_9caad_row21_col8{
            color:  red;
        }</style><table id="T_9caad_" ><thead>    <tr>        <th class="blank level0" ></th>        <th class="col_heading level0 col0" >名称</th>        <th class="col_heading level0 col1" >负债率</th>        <th class="col_heading level0 col2" >ROE</th>        <th class="col_heading level0 col3" >利润率</th>        <th class="col_heading level0 col4" >收入增长</th>        <th class="col_heading level0 col5" >收入增长TTM</th>        <th class="col_heading level0 col6" >盈利增长</th>        <th class="col_heading level0 col7" >盈利增长TTM</th>        <th class="col_heading level0 col8" >FCF增长</th>        <th class="col_heading level0 col9" >PE</th>        <th class="col_heading level0 col10" >PEm</th>        <th class="col_heading level0 col11" >PEG</th>        <th class="col_heading level0 col12" >季报日期</th>    </tr>    <tr>        <th class="index_name level0" >Symbol</th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>        <th class="blank" ></th>    </tr></thead><tbody>
                <tr>
                        <th id="T_9caad_level0_row0" class="row_heading level0 row0" >9992.HK</th>
                        <td id="T_9caad_row0_col0" class="data row0 col0" >泡泡玛特</td>
                        <td id="T_9caad_row0_col1" class="data row0 col1" >12.05</td>
                        <td id="T_9caad_row0_col2" class="data row0 col2" >33.03</td>
                        <td id="T_9caad_row0_col3" class="data row0 col3" >16.99</td>
                        <td id="T_9caad_row0_col4" class="data row0 col4" >167.33</td>
                        <td id="T_9caad_row0_col5" class="data row0 col5" >49.31</td>
                        <td id="T_9caad_row0_col6" class="data row0 col6" >2,204.10</td>
                        <td id="T_9caad_row0_col7" class="data row0 col7" >16.05</td>
                        <td id="T_9caad_row0_col8" class="data row0 col8" >1,216.11</td>
                        <td id="T_9caad_row0_col9" class="data row0 col9" >-</td>
                        <td id="T_9caad_row0_col10" class="data row0 col10" >322.52</td>
                        <td id="T_9caad_row0_col11" class="data row0 col11" >0.15</td>
                        <td id="T_9caad_row0_col12" class="data row0 col12" >2020-12-31</td>
            </tr>
            <tr>
                        <th id="T_9caad_level0_row1" class="row_heading level0 row1" >0285.HK</th>
                        <td id="T_9caad_row1_col0" class="data row1 col0" >比亚迪电子</td>
                        <td id="T_9caad_row1_col1" class="data row1 col1" >41.35</td>
                        <td id="T_9caad_row1_col2" class="data row1 col2" >16.47</td>
                        <td id="T_9caad_row1_col3" class="data row1 col3" >5.61</td>
                        <td id="T_9caad_row1_col4" class="data row1 col4" >24.31</td>
                        <td id="T_9caad_row1_col5" class="data row1 col5" >37.89</td>
                        <td id="T_9caad_row1_col6" class="data row1 col6" >66.09</td>
                        <td id="T_9caad_row1_col7" class="data row1 col7" >240.59</td>
                        <td id="T_9caad_row1_col8" class="data row1 col8" >-353.88</td>
                        <td id="T_9caad_row1_col9" class="data row1 col9" >66.55</td>
                        <td id="T_9caad_row1_col10" class="data row1 col10" >33.23</td>
                        <td id="T_9caad_row1_col11" class="data row1 col11" >0.50</td>
                        <td id="T_9caad_row1_col12" class="data row1 col12" >2020-12-31</td>
            </tr>
            <tr>
                        <th id="T_9caad_level0_row2" class="row_heading level0 row2" >3908.HK</th>
                        <td id="T_9caad_row2_col0" class="data row2 col0" >中金公司</td>
                        <td id="T_9caad_row2_col1" class="data row2 col1" >86.23</td>
                        <td id="T_9caad_row2_col2" class="data row2 col2" >8.66</td>
                        <td id="T_9caad_row2_col3" class="data row2 col3" >25.33</td>
                        <td id="T_9caad_row2_col4" class="data row2 col4" >34.26</td>
                        <td id="T_9caad_row2_col5" class="data row2 col5" >5.38</td>
                        <td id="T_9caad_row2_col6" class="data row2 col6" >39.22</td>
                        <td id="T_9caad_row2_col7" class="data row2 col7" >8.31</td>
                        <td id="T_9caad_row2_col8" class="data row2 col8" >-159.43</td>
                        <td id="T_9caad_row2_col9" class="data row2 col9" >-</td>
                        <td id="T_9caad_row2_col10" class="data row2 col10" >44.43</td>
                        <td id="T_9caad_row2_col11" class="data row2 col11" >1.13</td>
                        <td id="T_9caad_row2_col12" class="data row2 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_9caad_level0_row3" class="row_heading level0 row3" >0700.HK</th>
                        <td id="T_9caad_row3_col0" class="data row3 col0" >腾讯控股</td>
                        <td id="T_9caad_row3_col1" class="data row3 col1" >41.65</td>
                        <td id="T_9caad_row3_col2" class="data row3 col2" >24.13</td>
                        <td id="T_9caad_row3_col3" class="data row3 col3" >28.29</td>
                        <td id="T_9caad_row3_col4" class="data row3 col4" >26.65</td>
                        <td id="T_9caad_row3_col5" class="data row3 col5" >27.77</td>
                        <td id="T_9caad_row3_col6" class="data row3 col6" >33.31</td>
                        <td id="T_9caad_row3_col7" class="data row3 col7" >71.31</td>
                        <td id="T_9caad_row3_col8" class="data row3 col8" >20.72</td>
                        <td id="T_9caad_row3_col9" class="data row3 col9" >55.52</td>
                        <td id="T_9caad_row3_col10" class="data row3 col10" >47.99</td>
                        <td id="T_9caad_row3_col11" class="data row3 col11" >1.44</td>
                        <td id="T_9caad_row3_col12" class="data row3 col12" >2020-12-31</td>
            </tr>
            <tr>
                        <th id="T_9caad_level0_row4" class="row_heading level0 row4" >2319.HK</th>
                        <td id="T_9caad_row4_col0" class="data row4 col0" >蒙牛乳业</td>
                        <td id="T_9caad_row4_col1" class="data row4 col1" >53.53</td>
                        <td id="T_9caad_row4_col2" class="data row4 col2" >11.48</td>
                        <td id="T_9caad_row4_col3" class="data row4 col3" >4.41</td>
                        <td id="T_9caad_row4_col4" class="data row4 col4" >8.48</td>
                        <td id="T_9caad_row4_col5" class="data row4 col5" >-3.79</td>
                        <td id="T_9caad_row4_col6" class="data row4 col6" >23.12</td>
                        <td id="T_9caad_row4_col7" class="data row4 col7" >-14.14</td>
                        <td id="T_9caad_row4_col8" class="data row4 col8" >-26.64</td>
                        <td id="T_9caad_row4_col9" class="data row4 col9" >38.00</td>
                        <td id="T_9caad_row4_col10" class="data row4 col10" >45.62</td>
                        <td id="T_9caad_row4_col11" class="data row4 col11" >1.97</td>
                        <td id="T_9caad_row4_col12" class="data row4 col12" >2020-12-31</td>
            </tr>
            <tr>
                        <th id="T_9caad_level0_row5" class="row_heading level0 row5" >2331.HK</th>
                        <td id="T_9caad_row5_col0" class="data row5 col0" >李宁</td>
                        <td id="T_9caad_row5_col1" class="data row5 col1" >40.46</td>
                        <td id="T_9caad_row5_col2" class="data row5 col2" >15.76</td>
                        <td id="T_9caad_row5_col3" class="data row5 col3" >8.79</td>
                        <td id="T_9caad_row5_col4" class="data row5 col4" >18.21</td>
                        <td id="T_9caad_row5_col5" class="data row5 col5" >4.23</td>
                        <td id="T_9caad_row5_col6" class="data row5 col6" >53.91</td>
                        <td id="T_9caad_row5_col7" class="data row5 col7" >13.30</td>
                        <td id="T_9caad_row5_col8" class="data row5 col8" >59.22</td>
                        <td id="T_9caad_row5_col9" class="data row5 col9" >106.62</td>
                        <td id="T_9caad_row5_col10" class="data row5 col10" >137.09</td>
                        <td id="T_9caad_row5_col11" class="data row5 col11" >2.54</td>
                        <td id="T_9caad_row5_col12" class="data row5 col12" >2020-12-31</td>
            </tr>
            <tr>
                        <th id="T_9caad_level0_row6" class="row_heading level0 row6" >2020.HK</th>
                        <td id="T_9caad_row6_col0" class="data row6 col0" >安踏体育</td>
                        <td id="T_9caad_row6_col1" class="data row6 col1" >50.21</td>
                        <td id="T_9caad_row6_col2" class="data row6 col2" >24.16</td>
                        <td id="T_9caad_row6_col3" class="data row6 col3" >16.45</td>
                        <td id="T_9caad_row6_col4" class="data row6 col4" >29.94</td>
                        <td id="T_9caad_row6_col5" class="data row6 col5" >4.67</td>
                        <td id="T_9caad_row6_col6" class="data row6 col6" >19.91</td>
                        <td id="T_9caad_row6_col7" class="data row6 col7" >-3.41</td>
                        <td id="T_9caad_row6_col8" class="data row6 col8" >41.31</td>
                        <td id="T_9caad_row6_col9" class="data row6 col9" >70.93</td>
                        <td id="T_9caad_row6_col10" class="data row6 col10" >79.39</td>
                        <td id="T_9caad_row6_col11" class="data row6 col11" >3.99</td>
                        <td id="T_9caad_row6_col12" class="data row6 col12" >2020-12-31</td>
            </tr>
            <tr>
                        <th id="T_9caad_level0_row7" class="row_heading level0 row7" >3613.HK</th>
                        <td id="T_9caad_row7_col0" class="data row7 col0" >同仁堂国药</td>
                        <td id="T_9caad_row7_col1" class="data row7 col1" >8.41</td>
                        <td id="T_9caad_row7_col2" class="data row7 col2" >19.63</td>
                        <td id="T_9caad_row7_col3" class="data row7 col3" >39.28</td>
                        <td id="T_9caad_row7_col4" class="data row7 col4" >2.01</td>
                        <td id="T_9caad_row7_col5" class="data row7 col5" >-8.19</td>
                        <td id="T_9caad_row7_col6" class="data row7 col6" >3.94</td>
                        <td id="T_9caad_row7_col7" class="data row7 col7" >-2.46</td>
                        <td id="T_9caad_row7_col8" class="data row7 col8" >-19.44</td>
                        <td id="T_9caad_row7_col9" class="data row7 col9" >-</td>
                        <td id="T_9caad_row7_col10" class="data row7 col10" >16.35</td>
                        <td id="T_9caad_row7_col11" class="data row7 col11" >4.15</td>
                        <td id="T_9caad_row7_col12" class="data row7 col12" >2020-12-31</td>
            </tr>
            <tr>
                        <th id="T_9caad_level0_row8" class="row_heading level0 row8" >2359.HK</th>
                        <td id="T_9caad_row8_col0" class="data row8 col0" >药明康德</td>
                        <td id="T_9caad_row8_col1" class="data row8 col1" >29.32</td>
                        <td id="T_9caad_row8_col2" class="data row8 col2" >12.99</td>
                        <td id="T_9caad_row8_col3" class="data row8 col3" >17.91</td>
                        <td id="T_9caad_row8_col4" class="data row8 col4" >28.72</td>
                        <td id="T_9caad_row8_col5" class="data row8 col5" >10.66</td>
                        <td id="T_9caad_row8_col6" class="data row8 col6" >41.96</td>
                        <td id="T_9caad_row8_col7" class="data row8 col7" >40.43</td>
                        <td id="T_9caad_row8_col8" class="data row8 col8" >-86.40</td>
                        <td id="T_9caad_row8_col9" class="data row8 col9" >-</td>
                        <td id="T_9caad_row8_col10" class="data row8 col10" >174.09</td>
                        <td id="T_9caad_row8_col11" class="data row8 col11" >4.15</td>
                        <td id="T_9caad_row8_col12" class="data row8 col12" >2021-03-31</td>
            </tr>
            <tr>
                        <th id="T_9caad_level0_row9" class="row_heading level0 row9" >2269.HK</th>
                        <td id="T_9caad_row9_col0" class="data row9 col0" >药明生物</td>
                        <td id="T_9caad_row9_col1" class="data row9 col1" >27.84</td>
                        <td id="T_9caad_row9_col2" class="data row9 col2" >7.58</td>
                        <td id="T_9caad_row9_col3" class="data row9 col3" >24.01</td>
                        <td id="T_9caad_row9_col4" class="data row9 col4" >51.54</td>
                        <td id="T_9caad_row9_col5" class="data row9 col5" >40.88</td>
                        <td id="T_9caad_row9_col6" class="data row9 col6" >92.32</td>
                        <td id="T_9caad_row9_col7" class="data row9 col7" >66.59</td>
                        <td id="T_9caad_row9_col8" class="data row9 col8" >146.45</td>
                        <td id="T_9caad_row9_col9" class="data row9 col9" >-</td>
                        <td id="T_9caad_row9_col10" class="data row9 col10" >469.14</td>
                        <td id="T_9caad_row9_col11" class="data row9 col11" >5.08</td>
                        <td id="T_9caad_row9_col12" class="data row9 col12" >2020-12-31</td>
            </tr>
            <tr>
                        <th id="T_9caad_level0_row10" class="row_heading level0 row10" >0981.HK</th>
                        <td id="T_9caad_row10_col0" class="data row10 col0" >中芯国际</td>
                        <td id="T_9caad_row10_col1" class="data row10 col1" >30.77</td>
                        <td id="T_9caad_row10_col2" class="data row10 col2" >3.54</td>
                        <td id="T_9caad_row10_col3" class="data row10 col3" >8.91</td>
                        <td id="T_9caad_row10_col4" class="data row10 col4" >8.82</td>
                        <td id="T_9caad_row10_col5" class="data row10 col5" >25.40</td>
                        <td id="T_9caad_row10_col6" class="data row10 col6" >84.86</td>
                        <td id="T_9caad_row10_col7" class="data row10 col7" >204.90</td>
                        <td id="T_9caad_row10_col8" class="data row10 col8" >97.63</td>
                        <td id="T_9caad_row10_col9" class="data row10 col9" >303.19</td>
                        <td id="T_9caad_row10_col10" class="data row10 col10" >674.62</td>
                        <td id="T_9caad_row10_col11" class="data row10 col11" >7.95</td>
                        <td id="T_9caad_row10_col12" class="data row10 col12" >2020-12-31</td>
            </tr>
            <tr>
                        <th id="T_9caad_level0_row11" class="row_heading level0 row11" >1810.HK</th>
                        <td id="T_9caad_row11_col0" class="data row11 col0" >小米集团-W</td>
                        <td id="T_9caad_row11_col1" class="data row11 col1" >51.11</td>
                        <td id="T_9caad_row11_col2" class="data row11 col2" >20.56</td>
                        <td id="T_9caad_row11_col3" class="data row11 col3" >-4.33</td>
                        <td id="T_9caad_row11_col4" class="data row11 col4" >29.91</td>
                        <td id="T_9caad_row11_col5" class="data row11 col5" >19.45</td>
                        <td id="T_9caad_row11_col6" class="data row11 col6" >-18.05</td>
                        <td id="T_9caad_row11_col7" class="data row11 col7" >102.66</td>
                        <td id="T_9caad_row11_col8" class="data row11 col8" >-121.70</td>
                        <td id="T_9caad_row11_col9" class="data row11 col9" >-</td>
                        <td id="T_9caad_row11_col10" class="data row11 col10" >19,122.21</td>
                        <td id="T_9caad_row11_col11" class="data row11 col11" >-</td>
                        <td id="T_9caad_row11_col12" class="data row11 col12" >2020-12-31</td>
            </tr>
            <tr>
                        <th id="T_9caad_level0_row12" class="row_heading level0 row12" >3888.HK</th>
                        <td id="T_9caad_row12_col0" class="data row12 col0" >金山软件</td>
                        <td id="T_9caad_row12_col1" class="data row12 col1" >19.45</td>
                        <td id="T_9caad_row12_col2" class="data row12 col2" >14.75</td>
                        <td id="T_9caad_row12_col3" class="data row12 col3" >53.14</td>
                        <td id="T_9caad_row12_col4" class="data row12 col4" >5.33</td>
                        <td id="T_9caad_row12_col5" class="data row12 col5" >27.98</td>
                        <td id="T_9caad_row12_col6" class="data row12 col6" >-444.91</td>
                        <td id="T_9caad_row12_col7" class="data row12 col7" >-749.58</td>
                        <td id="T_9caad_row12_col8" class="data row12 col8" >-240.00</td>
                        <td id="T_9caad_row12_col9" class="data row12 col9" >-</td>
                        <td id="T_9caad_row12_col10" class="data row12 col10" >19.92</td>
                        <td id="T_9caad_row12_col11" class="data row12 col11" >-</td>
                        <td id="T_9caad_row12_col12" class="data row12 col12" >2020-12-31</td>
            </tr>
            <tr>
                        <th id="T_9caad_level0_row13" class="row_heading level0 row13" >3690.HK</th>
                        <td id="T_9caad_row13_col0" class="data row13 col0" >美团-W</td>
                        <td id="T_9caad_row13_col1" class="data row13 col1" >41.39</td>
                        <td id="T_9caad_row13_col2" class="data row13 col2" >-19.90</td>
                        <td id="T_9caad_row13_col3" class="data row13 col3" >-56.90</td>
                        <td id="T_9caad_row13_col4" class="data row13 col4" >52.67</td>
                        <td id="T_9caad_row13_col5" class="data row13 col5" >17.75</td>
                        <td id="T_9caad_row13_col6" class="data row13 col6" >172.94</td>
                        <td id="T_9caad_row13_col7" class="data row13 col7" >110.31</td>
                        <td id="T_9caad_row13_col8" class="data row13 col8" >219.37</td>
                        <td id="T_9caad_row13_col9" class="data row13 col9" >-</td>
                        <td id="T_9caad_row13_col10" class="data row13 col10" >-</td>
                        <td id="T_9caad_row13_col11" class="data row13 col11" >-</td>
                        <td id="T_9caad_row13_col12" class="data row13 col12" >2020-12-31</td>
            </tr>
            <tr>
                        <th id="T_9caad_level0_row14" class="row_heading level0 row14" >1024.HK</th>
                        <td id="T_9caad_row14_col0" class="data row14 col0" >快手-W</td>
                        <td id="T_9caad_row14_col1" class="data row14 col1" >406.92</td>
                        <td id="T_9caad_row14_col2" class="data row14 col2" >58.33</td>
                        <td id="T_9caad_row14_col3" class="data row14 col3" >-137.56</td>
                        <td id="T_9caad_row14_col4" class="data row14 col4" >95.46</td>
                        <td id="T_9caad_row14_col5" class="data row14 col5" >50.24</td>
                        <td id="T_9caad_row14_col6" class="data row14 col6" >171.21</td>
                        <td id="T_9caad_row14_col7" class="data row14 col7" >493.52</td>
                        <td id="T_9caad_row14_col8" class="data row14 col8" >-317.01</td>
                        <td id="T_9caad_row14_col9" class="data row14 col9" >-</td>
                        <td id="T_9caad_row14_col10" class="data row14 col10" >-</td>
                        <td id="T_9caad_row14_col11" class="data row14 col11" >-</td>
                        <td id="T_9caad_row14_col12" class="data row14 col12" >2020-12-31</td>
            </tr>
            <tr>
                        <th id="T_9caad_level0_row15" class="row_heading level0 row15" >1068.HK</th>
                        <td id="T_9caad_row15_col0" class="data row15 col0" >雨润食品</td>
                        <td id="T_9caad_row15_col1" class="data row15 col1" >135.43</td>
                        <td id="T_9caad_row15_col2" class="data row15 col2" >38.19</td>
                        <td id="T_9caad_row15_col3" class="data row15 col3" >-23.16</td>
                        <td id="T_9caad_row15_col4" class="data row15 col4" >8.40</td>
                        <td id="T_9caad_row15_col5" class="data row15 col5" >-0.08</td>
                        <td id="T_9caad_row15_col6" class="data row15 col6" >27.51</td>
                        <td id="T_9caad_row15_col7" class="data row15 col7" >-48.76</td>
                        <td id="T_9caad_row15_col8" class="data row15 col8" >12.50</td>
                        <td id="T_9caad_row15_col9" class="data row15 col9" >-</td>
                        <td id="T_9caad_row15_col10" class="data row15 col10" >-</td>
                        <td id="T_9caad_row15_col11" class="data row15 col11" >-</td>
                        <td id="T_9caad_row15_col12" class="data row15 col12" >2020-12-31</td>
            </tr>
            <tr>
                        <th id="T_9caad_level0_row16" class="row_heading level0 row16" >8083.HK</th>
                        <td id="T_9caad_row16_col0" class="data row16 col0" >中国有赞</td>
                        <td id="T_9caad_row16_col1" class="data row16 col1" >62.09</td>
                        <td id="T_9caad_row16_col2" class="data row16 col2" >-11.46</td>
                        <td id="T_9caad_row16_col3" class="data row16 col3" >-48.60</td>
                        <td id="T_9caad_row16_col4" class="data row16 col4" >112.40</td>
                        <td id="T_9caad_row16_col5" class="data row16 col5" >55.77</td>
                        <td id="T_9caad_row16_col6" class="data row16 col6" >90.51</td>
                        <td id="T_9caad_row16_col7" class="data row16 col7" >-50.21</td>
                        <td id="T_9caad_row16_col8" class="data row16 col8" >81.34</td>
                        <td id="T_9caad_row16_col9" class="data row16 col9" >-</td>
                        <td id="T_9caad_row16_col10" class="data row16 col10" >-</td>
                        <td id="T_9caad_row16_col11" class="data row16 col11" >-</td>
                        <td id="T_9caad_row16_col12" class="data row16 col12" >2020-12-31</td>
            </tr>
            <tr>
                        <th id="T_9caad_level0_row17" class="row_heading level0 row17" >2298.HK</th>
                        <td id="T_9caad_row17_col0" class="data row17 col0" >都市丽人</td>
                        <td id="T_9caad_row17_col1" class="data row17 col1" >46.44</td>
                        <td id="T_9caad_row17_col2" class="data row17 col2" >-9.33</td>
                        <td id="T_9caad_row17_col3" class="data row17 col3" >-5.31</td>
                        <td id="T_9caad_row17_col4" class="data row17 col4" >-10.94</td>
                        <td id="T_9caad_row17_col5" class="data row17 col5" >-25.10</td>
                        <td id="T_9caad_row17_col6" class="data row17 col6" >-171.57</td>
                        <td id="T_9caad_row17_col7" class="data row17 col7" >-90.90</td>
                        <td id="T_9caad_row17_col8" class="data row17 col8" >153.46</td>
                        <td id="T_9caad_row17_col9" class="data row17 col9" >-</td>
                        <td id="T_9caad_row17_col10" class="data row17 col10" >-</td>
                        <td id="T_9caad_row17_col11" class="data row17 col11" >-</td>
                        <td id="T_9caad_row17_col12" class="data row17 col12" >2020-12-31</td>
            </tr>
            <tr>
                        <th id="T_9caad_level0_row18" class="row_heading level0 row18" >0268.HK</th>
                        <td id="T_9caad_row18_col0" class="data row18 col0" >金蝶国际</td>
                        <td id="T_9caad_row18_col1" class="data row18 col1" >25.77</td>
                        <td id="T_9caad_row18_col2" class="data row18 col2" >4.30</td>
                        <td id="T_9caad_row18_col3" class="data row18 col3" >7.33</td>
                        <td id="T_9caad_row18_col4" class="data row18 col4" >13.75</td>
                        <td id="T_9caad_row18_col5" class="data row18 col5" >0.93</td>
                        <td id="T_9caad_row18_col6" class="data row18 col6" >-55.57</td>
                        <td id="T_9caad_row18_col7" class="data row18 col7" >-190.04</td>
                        <td id="T_9caad_row18_col8" class="data row18 col8" >-12.84</td>
                        <td id="T_9caad_row18_col9" class="data row18 col9" >220.22</td>
                        <td id="T_9caad_row18_col10" class="data row18 col10" >427.39</td>
                        <td id="T_9caad_row18_col11" class="data row18 col11" >-</td>
                        <td id="T_9caad_row18_col12" class="data row18 col12" >2020-12-31</td>
            </tr>
            <tr>
                        <th id="T_9caad_level0_row19" class="row_heading level0 row19" >1347.HK</th>
                        <td id="T_9caad_row19_col0" class="data row19 col0" >华虹半导体</td>
                        <td id="T_9caad_row19_col1" class="data row19 col1" >26.58</td>
                        <td id="T_9caad_row19_col2" class="data row19 col2" >7.06</td>
                        <td id="T_9caad_row19_col3" class="data row19 col3" >16.35</td>
                        <td id="T_9caad_row19_col4" class="data row19 col4" >6.15</td>
                        <td id="T_9caad_row19_col5" class="data row19 col5" >3.08</td>
                        <td id="T_9caad_row19_col6" class="data row19 col6" >-8.01</td>
                        <td id="T_9caad_row19_col7" class="data row19 col7" >-38.71</td>
                        <td id="T_9caad_row19_col8" class="data row19 col8" >-619.72</td>
                        <td id="T_9caad_row19_col9" class="data row19 col9" >42.30</td>
                        <td id="T_9caad_row19_col10" class="data row19 col10" >301.16</td>
                        <td id="T_9caad_row19_col11" class="data row19 col11" >-</td>
                        <td id="T_9caad_row19_col12" class="data row19 col12" >2020-12-31</td>
            </tr>
            <tr>
                        <th id="T_9caad_level0_row20" class="row_heading level0 row20" >6055.HK</th>
                        <td id="T_9caad_row20_col0" class="data row20 col0" >中烟香港</td>
                        <td id="T_9caad_row20_col1" class="data row20 col1" >56.43</td>
                        <td id="T_9caad_row20_col2" class="data row20 col2" >21.51</td>
                        <td id="T_9caad_row20_col3" class="data row20 col3" >3.60</td>
                        <td id="T_9caad_row20_col4" class="data row20 col4" >-14.50</td>
                        <td id="T_9caad_row20_col5" class="data row20 col5" >-61.22</td>
                        <td id="T_9caad_row20_col6" class="data row20 col6" >-23.96</td>
                        <td id="T_9caad_row20_col7" class="data row20 col7" >-70.15</td>
                        <td id="T_9caad_row20_col8" class="data row20 col8" >-17.49</td>
                        <td id="T_9caad_row20_col9" class="data row20 col9" >-</td>
                        <td id="T_9caad_row20_col10" class="data row20 col10" >39.91</td>
                        <td id="T_9caad_row20_col11" class="data row20 col11" >-</td>
                        <td id="T_9caad_row20_col12" class="data row20 col12" >2020-12-31</td>
            </tr>
            <tr>
                        <th id="T_9caad_level0_row21" class="row_heading level0 row21" >9626.HK</th>
                        <td id="T_9caad_row21_col0" class="data row21 col0" >哔哩哔哩-SW</td>
                        <td id="T_9caad_row21_col1" class="data row21 col1" >67.39</td>
                        <td id="T_9caad_row21_col2" class="data row21 col2" >-9.33</td>
                        <td id="T_9caad_row21_col3" class="data row21 col3" >-20.55</td>
                        <td id="T_9caad_row21_col4" class="data row21 col4" >69.49</td>
                        <td id="T_9caad_row21_col5" class="data row21 col5" >77.03</td>
                        <td id="T_9caad_row21_col6" class="data row21 col6" >83.54</td>
                        <td id="T_9caad_row21_col7" class="data row21 col7" >133.65</td>
                        <td id="T_9caad_row21_col8" class="data row21 col8" >-110.94</td>
                        <td id="T_9caad_row21_col9" class="data row21 col9" >-</td>
                        <td id="T_9caad_row21_col10" class="data row21 col10" >-</td>
                        <td id="T_9caad_row21_col11" class="data row21 col11" >-</td>
                        <td id="T_9caad_row21_col12" class="data row21 col12" >2020-12-31</td>
            </tr>
    </tbody></table>




<script>
$('table').addClass('table table-striped table-hover  table-sm ')
$('thead').addClass('thead-dark')
</script>