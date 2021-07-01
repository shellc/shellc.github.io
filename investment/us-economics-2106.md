---
layout: default
title: 美国宏观经济(2106)
---
# 美国经济

## 就业和物价

### 就业人口

#### 总就业人口


    
![png](US%20Economy_files/US%20Economy_8_0.png)
    


#### 就业人口变化与失业率


    
![png](US%20Economy_files/US%20Economy_10_0.png)
    


### 物价


    
![png](US%20Economy_files/US%20Economy_13_0.png)
    


* [Measuring inflation trends: Why use different inflation measures for policy analysis?](https://fredblog.stlouisfed.org/2018/05/measuring-inflation-trends/)
Congress has instructed the Federal Reserve to pursue monetary policies that promote maximum employment and price stability. The Federal Open Market Committee (FOMC) has determined that “inflation at the rate of 2 percent, as measured by the annual change in the price index for personal consumption expenditures [PCE], is most consistent over the longer run with the Federal Reserve’s statutory mandate” for price stability.

## GDP

### GDP总量


    
![png](US%20Economy_files/US%20Economy_19_0.png)
    


**M2 Money Stock**

The non-seasonally adjusted version of this weekly series:
https://fred.stlouisfed.org/series/WM2NS


https://fred.stlouisfed.org/series/M2SL

**Gross Domestic Product**

Gross domestic product (GDP), the featured measure of U.S. output, is the market value of the goods and services produced by labor and property located in the United States. https://fred.stlouisfed.org/series/GDP

**Real Gross Domestic Product**

Real gross domestic product is the inflation adjusted value of the goods and services produced by labor and property located in the United States.

[Is nominal GDP always higher than real GDP?](https://www.enotes.com/homework-help/nominal-gdp-always-higher-than-real-gdp-646666)

#### GDP增长(TTM)


    
![png](US%20Economy_files/US%20Economy_22_0.png)
    


## 利率

### 长期趋势


    
![png](US%20Economy_files/US%20Economy_27_0.png)
    


#### 相关性




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Interest Rates, Discount Rate</th>
      <th>Inflation, Consumer Prices</th>
      <th>10-Year Treasury Constant Maturity Rate</th>
      <th>10-Year Breakeven Inflation Rate</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>Interest Rates, Discount Rate</th>
      <td>1.00</td>
      <td>0.75</td>
      <td>0.91</td>
      <td>0.48</td>
    </tr>
    <tr>
      <th>Inflation, Consumer Prices</th>
      <td>0.75</td>
      <td>1.00</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>10-Year Treasury Constant Maturity Rate</th>
      <td>0.91</td>
      <td>NaN</td>
      <td>1.00</td>
      <td>0.54</td>
    </tr>
    <tr>
      <th>10-Year Breakeven Inflation Rate</th>
      <td>0.48</td>
      <td>NaN</td>
      <td>0.54</td>
      <td>1.00</td>
    </tr>
  </tbody>
</table>
</div>



### 短期趋势


    
![png](US%20Economy_files/US%20Economy_31_0.png)
    


**Inflation, consumer prices for the United States**

Inflation as measured by the consumer price index reflects the annual percentage change in the cost to the average consumer of acquiring a basket of goods and services that may be fixed or changed at specified intervals, such as yearly. The Laspeyres formula is generally used.

International Monetary Fund, International Financial Statistics and data files.


**10-Year Breakeven Inflation Rate**

The breakeven inflation rate represents a measure of **expected inflation** derived from 10-Year Treasury Constant Maturity Securities (BC_10YEAR) and 10-Year Treasury Inflation-Indexed Constant Maturity Securities (TC_10YEAR). The latest value implies what market participants expect inflation to be in the next 10 years, on average.
Starting with the update on June 21, 2019, the Treasury bond data used in calculating interest rate spreads is obtained directly from the U.S. Treasury Department.



### M2增速与通胀预期


    
![png](US%20Economy_files/US%20Economy_35_0.png)
    





<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>M2</th>
      <th>10-Year Breakeven Inflation Rate</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>M2</th>
      <td>1.00</td>
      <td>-0.26</td>
    </tr>
    <tr>
      <th>10-Year Breakeven Inflation Rate</th>
      <td>-0.26</td>
      <td>1.00</td>
    </tr>
  </tbody>
</table>
</div>



## 资产价格


    
![png](US%20Economy_files/US%20Economy_38_0.png)
    





<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th>Symbol</th>
      <th>CSI 300</th>
      <th>BND</th>
      <th>DBC</th>
      <th>TIP</th>
      <th>VNQ</th>
      <th>S&amp;P 500</th>
      <th>HANG SENG INDEX</th>
      <th>Treasury Yield 10 Years</th>
    </tr>
    <tr>
      <th>Symbol</th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>CSI 300</th>
      <td>1.00</td>
      <td>0.74</td>
      <td>-0.52</td>
      <td>0.73</td>
      <td>0.70</td>
      <td>0.78</td>
      <td>0.56</td>
      <td>-0.52</td>
    </tr>
    <tr>
      <th>BND</th>
      <td>0.74</td>
      <td>1.00</td>
      <td>-0.50</td>
      <td>0.97</td>
      <td>0.83</td>
      <td>0.89</td>
      <td>0.37</td>
      <td>-0.76</td>
    </tr>
    <tr>
      <th>DBC</th>
      <td>-0.52</td>
      <td>-0.50</td>
      <td>1.00</td>
      <td>-0.32</td>
      <td>-0.43</td>
      <td>-0.29</td>
      <td>-0.01</td>
      <td>0.49</td>
    </tr>
    <tr>
      <th>TIP</th>
      <td>0.73</td>
      <td>0.97</td>
      <td>-0.32</td>
      <td>1.00</td>
      <td>0.81</td>
      <td>0.92</td>
      <td>0.38</td>
      <td>-0.73</td>
    </tr>
    <tr>
      <th>VNQ</th>
      <td>0.70</td>
      <td>0.83</td>
      <td>-0.43</td>
      <td>0.81</td>
      <td>1.00</td>
      <td>0.89</td>
      <td>0.52</td>
      <td>-0.44</td>
    </tr>
    <tr>
      <th>S&amp;P 500</th>
      <td>0.78</td>
      <td>0.89</td>
      <td>-0.29</td>
      <td>0.92</td>
      <td>0.89</td>
      <td>1.00</td>
      <td>0.62</td>
      <td>-0.44</td>
    </tr>
    <tr>
      <th>HANG SENG INDEX</th>
      <td>0.56</td>
      <td>0.37</td>
      <td>-0.01</td>
      <td>0.38</td>
      <td>0.52</td>
      <td>0.62</td>
      <td>1.00</td>
      <td>0.18</td>
    </tr>
    <tr>
      <th>Treasury Yield 10 Years</th>
      <td>-0.52</td>
      <td>-0.76</td>
      <td>0.49</td>
      <td>-0.73</td>
      <td>-0.44</td>
      <td>-0.44</td>
      <td>0.18</td>
      <td>1.00</td>
    </tr>
  </tbody>
</table>
</div>



### S&P 500

#### S&P 500与GDP


    
![png](US%20Economy_files/US%20Economy_43_0.png)
    





<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>S&amp;P 500</th>
      <th>US Nominal GDP</th>
      <th>US Real GDP</th>
      <th>Global GDP</th>
      <th>Global GDP(DEF)</th>
      <th>US M2</th>
      <th>US Employees</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>S&amp;P 500</th>
      <td>1.00</td>
      <td>0.95</td>
      <td>0.93</td>
      <td>0.92</td>
      <td>0.90</td>
      <td>0.97</td>
      <td>0.85</td>
    </tr>
    <tr>
      <th>US Nominal GDP</th>
      <td>0.95</td>
      <td>1.00</td>
      <td>0.99</td>
      <td>0.99</td>
      <td>0.98</td>
      <td>0.97</td>
      <td>0.94</td>
    </tr>
    <tr>
      <th>US Real GDP</th>
      <td>0.93</td>
      <td>0.99</td>
      <td>1.00</td>
      <td>0.97</td>
      <td>0.97</td>
      <td>0.94</td>
      <td>0.97</td>
    </tr>
    <tr>
      <th>Global GDP</th>
      <td>0.92</td>
      <td>0.99</td>
      <td>0.97</td>
      <td>1.00</td>
      <td>0.99</td>
      <td>0.98</td>
      <td>0.91</td>
    </tr>
    <tr>
      <th>Global GDP(DEF)</th>
      <td>0.90</td>
      <td>0.98</td>
      <td>0.97</td>
      <td>0.99</td>
      <td>1.00</td>
      <td>0.96</td>
      <td>0.92</td>
    </tr>
    <tr>
      <th>US M2</th>
      <td>0.97</td>
      <td>0.97</td>
      <td>0.94</td>
      <td>0.98</td>
      <td>0.96</td>
      <td>1.00</td>
      <td>0.85</td>
    </tr>
    <tr>
      <th>US Employees</th>
      <td>0.85</td>
      <td>0.94</td>
      <td>0.97</td>
      <td>0.91</td>
      <td>0.92</td>
      <td>0.85</td>
      <td>1.00</td>
    </tr>
  </tbody>
</table>
</div>



#### S&P 500 PE




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>2021-06-30</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>S&amp;P 500 PE</th>
      <td>45.65</td>
    </tr>
  </tbody>
</table>
</div>




    
![png](US%20Economy_files/US%20Economy_46_1.png)
    


#### Dividend Yield




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>2021-06-30</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>S&amp;P 500 Dividend</th>
      <td>1.34</td>
    </tr>
  </tbody>
</table>
</div>




    
![png](US%20Economy_files/US%20Economy_48_1.png)
    


### Shiller's CAPE




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>2021-06-30</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>CAPE</th>
      <td>38.11</td>
    </tr>
    <tr>
      <th>MA 10Y</th>
      <td>27.63</td>
    </tr>
    <tr>
      <th>CAPE 3Y</th>
      <td>36.88</td>
    </tr>
    <tr>
      <th>50%</th>
      <td>20.54</td>
    </tr>
    <tr>
      <th>75%</th>
      <td>26.69</td>
    </tr>
    <tr>
      <th>90%</th>
      <td>32.20</td>
    </tr>
  </tbody>
</table>
</div>




    
![png](US%20Economy_files/US%20Economy_51_0.png)
    


#### Earnings


    
![png](US%20Economy_files/US%20Economy_53_0.png)
    


### Buffett Indicator




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>2021-06-29</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>Buffett_Indicator</th>
      <td>202.95</td>
    </tr>
    <tr>
      <th>MA10Y</th>
      <td>123.43</td>
    </tr>
    <tr>
      <th>50%</th>
      <td>83.30</td>
    </tr>
    <tr>
      <th>75%</th>
      <td>107.96</td>
    </tr>
    <tr>
      <th>90%</th>
      <td>131.69</td>
    </tr>
  </tbody>
</table>
</div>




    
![png](US%20Economy_files/US%20Economy_56_0.png)
    


### TIPS




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>2021-06-29</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>TIPS</th>
      <td>-0.83</td>
    </tr>
    <tr>
      <th>10-Year Treasury Constant Maturity Rate</th>
      <td>1.49</td>
    </tr>
    <tr>
      <th>10-Year Breakeven Inflation Rate</th>
      <td>2.32</td>
    </tr>
  </tbody>
</table>
</div>




    
![png](US%20Economy_files/US%20Economy_58_1.png)
    



    
![png](US%20Economy_files/US%20Economy_59_0.png)
    

   


<script>
$('table').addClass('table table-striped table-hover  table-sm ')
$('thead').addClass('thead-light')
$('.main img').css('width', '90%')
</script>
