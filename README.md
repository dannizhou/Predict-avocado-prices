Dataset and Processing
======================

<table>
<caption>Data summary</caption>
<tbody>
<tr class="odd">
<td style="text-align: left;">Name</td>
<td style="text-align: left;">final</td>
</tr>
<tr class="even">
<td style="text-align: left;">Number of rows</td>
<td style="text-align: left;">16221</td>
</tr>
<tr class="odd">
<td style="text-align: left;">Number of columns</td>
<td style="text-align: left;">24</td>
</tr>
<tr class="even">
<td style="text-align: left;">_______________________</td>
<td style="text-align: left;"></td>
</tr>
<tr class="odd">
<td style="text-align: left;">Column type frequency:</td>
<td style="text-align: left;"></td>
</tr>
<tr class="even">
<td style="text-align: left;">character</td>
<td style="text-align: left;">2</td>
</tr>
<tr class="odd">
<td style="text-align: left;">Date</td>
<td style="text-align: left;">1</td>
</tr>
<tr class="even">
<td style="text-align: left;">numeric</td>
<td style="text-align: left;">21</td>
</tr>
<tr class="odd">
<td style="text-align: left;">________________________</td>
<td style="text-align: left;"></td>
</tr>
<tr class="even">
<td style="text-align: left;">Group variables</td>
<td style="text-align: left;">None</td>
</tr>
</tbody>
</table>

**Variable type: character**

<table>
<thead>
<tr class="header">
<th style="text-align: left;">skim_variable</th>
<th style="text-align: right;">n_missing</th>
<th style="text-align: right;">complete_rate</th>
<th style="text-align: right;">min</th>
<th style="text-align: right;">max</th>
<th style="text-align: right;">empty</th>
<th style="text-align: right;">n_unique</th>
<th style="text-align: right;">whitespace</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: left;">type</td>
<td style="text-align: right;">0</td>
<td style="text-align: right;">1</td>
<td style="text-align: right;">7</td>
<td style="text-align: right;">12</td>
<td style="text-align: right;">0</td>
<td style="text-align: right;">2</td>
<td style="text-align: right;">0</td>
</tr>
<tr class="even">
<td style="text-align: left;">region</td>
<td style="text-align: right;">0</td>
<td style="text-align: right;">1</td>
<td style="text-align: right;">5</td>
<td style="text-align: right;">19</td>
<td style="text-align: right;">0</td>
<td style="text-align: right;">48</td>
<td style="text-align: right;">0</td>
</tr>
</tbody>
</table>

**Variable type: Date**

<table>
<thead>
<tr class="header">
<th style="text-align: left;">skim_variable</th>
<th style="text-align: right;">n_missing</th>
<th style="text-align: right;">complete_rate</th>
<th style="text-align: left;">min</th>
<th style="text-align: left;">max</th>
<th style="text-align: left;">median</th>
<th style="text-align: right;">n_unique</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: left;">ship_date</td>
<td style="text-align: right;">0</td>
<td style="text-align: right;">1</td>
<td style="text-align: left;">2014-12-28</td>
<td style="text-align: left;">2018-03-18</td>
<td style="text-align: left;">2016-08-07</td>
<td style="text-align: right;">169</td>
</tr>
</tbody>
</table>

**Variable type: numeric**

<table>
<thead>
<tr class="header">
<th style="text-align: left;">skim_variable</th>
<th style="text-align: right;">n_missing</th>
<th style="text-align: right;">complete_rate</th>
<th style="text-align: right;">mean</th>
<th style="text-align: right;">sd</th>
<th style="text-align: right;">p0</th>
<th style="text-align: right;">p25</th>
<th style="text-align: right;">p50</th>
<th style="text-align: right;">p75</th>
<th style="text-align: right;">p100</th>
<th style="text-align: left;">hist</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: left;">average_price</td>
<td style="text-align: right;">0</td>
<td style="text-align: right;">1</td>
<td style="text-align: right;">1.41</td>
<td style="text-align: right;">0.41</td>
<td style="text-align: right;">0.44</td>
<td style="text-align: right;">1.10</td>
<td style="text-align: right;">1.38</td>
<td style="text-align: right;">1.67</td>
<td style="text-align: right;">3.25</td>
<td style="text-align: left;">▂▇▅▁▁</td>
</tr>
<tr class="even">
<td style="text-align: left;">total_volume</td>
<td style="text-align: right;">0</td>
<td style="text-align: right;">1</td>
<td style="text-align: right;">352859.56</td>
<td style="text-align: right;">806556.01</td>
<td style="text-align: right;">84.56</td>
<td style="text-align: right;">9219.97</td>
<td style="text-align: right;">80015.17</td>
<td style="text-align: right;">344490.91</td>
<td style="text-align: right;">11213596.29</td>
<td style="text-align: left;">▇▁▁▁▁</td>
</tr>
<tr class="odd">
<td style="text-align: left;">sku_4046</td>
<td style="text-align: right;">0</td>
<td style="text-align: right;">1</td>
<td style="text-align: right;">115494.34</td>
<td style="text-align: right;">319810.82</td>
<td style="text-align: right;">0.00</td>
<td style="text-align: right;">641.47</td>
<td style="text-align: right;">5403.05</td>
<td style="text-align: right;">85266.60</td>
<td style="text-align: right;">4794142.14</td>
<td style="text-align: left;">▇▁▁▁▁</td>
</tr>
<tr class="even">
<td style="text-align: left;">sku_4225</td>
<td style="text-align: right;">0</td>
<td style="text-align: right;">1</td>
<td style="text-align: right;">127139.95</td>
<td style="text-align: right;">300957.43</td>
<td style="text-align: right;">0.00</td>
<td style="text-align: right;">2449.35</td>
<td style="text-align: right;">22043.38</td>
<td style="text-align: right;">107904.00</td>
<td style="text-align: right;">4097591.67</td>
<td style="text-align: left;">▇▁▁▁▁</td>
</tr>
<tr class="odd">
<td style="text-align: left;">sku_4770</td>
<td style="text-align: right;">0</td>
<td style="text-align: right;">1</td>
<td style="text-align: right;">11643.15</td>
<td style="text-align: right;">42056.32</td>
<td style="text-align: right;">0.00</td>
<td style="text-align: right;">0.00</td>
<td style="text-align: right;">110.87</td>
<td style="text-align: right;">4388.77</td>
<td style="text-align: right;">704466.56</td>
<td style="text-align: left;">▇▁▁▁▁</td>
</tr>
<tr class="even">
<td style="text-align: left;">total_bags</td>
<td style="text-align: right;">0</td>
<td style="text-align: right;">1</td>
<td style="text-align: right;">98580.81</td>
<td style="text-align: right;">230840.17</td>
<td style="text-align: right;">0.00</td>
<td style="text-align: right;">4034.96</td>
<td style="text-align: right;">28391.13</td>
<td style="text-align: right;">88490.93</td>
<td style="text-align: right;">3462625.70</td>
<td style="text-align: left;">▇▁▁▁▁</td>
</tr>
<tr class="odd">
<td style="text-align: left;">small_bags</td>
<td style="text-align: right;">0</td>
<td style="text-align: right;">1</td>
<td style="text-align: right;">77608.91</td>
<td style="text-align: right;">200578.57</td>
<td style="text-align: right;">0.00</td>
<td style="text-align: right;">2110.00</td>
<td style="text-align: right;">19273.80</td>
<td style="text-align: right;">68906.93</td>
<td style="text-align: right;">3403581.49</td>
<td style="text-align: left;">▇▁▁▁▁</td>
</tr>
<tr class="even">
<td style="text-align: left;">large_bags</td>
<td style="text-align: right;">0</td>
<td style="text-align: right;">1</td>
<td style="text-align: right;">19334.71</td>
<td style="text-align: right;">51455.54</td>
<td style="text-align: right;">0.00</td>
<td style="text-align: right;">62.51</td>
<td style="text-align: right;">1850.35</td>
<td style="text-align: right;">13544.68</td>
<td style="text-align: right;">832296.70</td>
<td style="text-align: left;">▇▁▁▁▁</td>
</tr>
<tr class="odd">
<td style="text-align: left;">xlarge_bags</td>
<td style="text-align: right;">0</td>
<td style="text-align: right;">1</td>
<td style="text-align: right;">1637.18</td>
<td style="text-align: right;">7322.26</td>
<td style="text-align: right;">0.00</td>
<td style="text-align: right;">0.00</td>
<td style="text-align: right;">0.00</td>
<td style="text-align: right;">67.00</td>
<td style="text-align: right;">131300.76</td>
<td style="text-align: left;">▇▁▁▁▁</td>
</tr>
<tr class="even">
<td style="text-align: left;">distance_km</td>
<td style="text-align: right;">0</td>
<td style="text-align: right;">1</td>
<td style="text-align: right;">3380.94</td>
<td style="text-align: right;">729.77</td>
<td style="text-align: right;">1590.00</td>
<td style="text-align: right;">2861.00</td>
<td style="text-align: right;">3402.00</td>
<td style="text-align: right;">3950.00</td>
<td style="text-align: right;">4709.00</td>
<td style="text-align: left;">▃▃▇▇▅</td>
</tr>
<tr class="odd">
<td style="text-align: left;">daily_temp_range</td>
<td style="text-align: right;">0</td>
<td style="text-align: right;">1</td>
<td style="text-align: right;">12.54</td>
<td style="text-align: right;">3.50</td>
<td style="text-align: right;">4.27</td>
<td style="text-align: right;">10.04</td>
<td style="text-align: right;">12.27</td>
<td style="text-align: right;">15.30</td>
<td style="text-align: right;">20.92</td>
<td style="text-align: left;">▂▇▇▇▂</td>
</tr>
<tr class="even">
<td style="text-align: left;">daily_dew_point</td>
<td style="text-align: right;">0</td>
<td style="text-align: right;">1</td>
<td style="text-align: right;">12.09</td>
<td style="text-align: right;">4.71</td>
<td style="text-align: right;">-1.33</td>
<td style="text-align: right;">9.22</td>
<td style="text-align: right;">12.70</td>
<td style="text-align: right;">16.16</td>
<td style="text-align: right;">18.68</td>
<td style="text-align: left;">▁▂▃▅▇</td>
</tr>
<tr class="odd">
<td style="text-align: left;">daily_wet_bulb</td>
<td style="text-align: right;">0</td>
<td style="text-align: right;">1</td>
<td style="text-align: right;">12.07</td>
<td style="text-align: right;">4.73</td>
<td style="text-align: right;">-1.20</td>
<td style="text-align: right;">9.22</td>
<td style="text-align: right;">12.70</td>
<td style="text-align: right;">16.16</td>
<td style="text-align: right;">18.68</td>
<td style="text-align: left;">▁▂▃▅▇</td>
</tr>
<tr class="even">
<td style="text-align: left;">daily_max_temp</td>
<td style="text-align: right;">0</td>
<td style="text-align: right;">1</td>
<td style="text-align: right;">28.32</td>
<td style="text-align: right;">3.52</td>
<td style="text-align: right;">1.67</td>
<td style="text-align: right;">26.77</td>
<td style="text-align: right;">28.13</td>
<td style="text-align: right;">30.13</td>
<td style="text-align: right;">36.62</td>
<td style="text-align: left;">▁▁▁▇▃</td>
</tr>
<tr class="odd">
<td style="text-align: left;">daily_min_temp</td>
<td style="text-align: right;">0</td>
<td style="text-align: right;">1</td>
<td style="text-align: right;">15.81</td>
<td style="text-align: right;">2.61</td>
<td style="text-align: right;">0.92</td>
<td style="text-align: right;">14.32</td>
<td style="text-align: right;">16.24</td>
<td style="text-align: right;">17.70</td>
<td style="text-align: right;">19.76</td>
<td style="text-align: left;">▁▁▁▆▇</td>
</tr>
<tr class="even">
<td style="text-align: left;">daily_avg_temp</td>
<td style="text-align: right;">0</td>
<td style="text-align: right;">1</td>
<td style="text-align: right;">21.34</td>
<td style="text-align: right;">2.18</td>
<td style="text-align: right;">11.16</td>
<td style="text-align: right;">20.03</td>
<td style="text-align: right;">21.44</td>
<td style="text-align: right;">22.71</td>
<td style="text-align: right;">27.07</td>
<td style="text-align: left;">▁▁▃▇▂</td>
</tr>
<tr class="odd">
<td style="text-align: left;">daily_precip_mm</td>
<td style="text-align: right;">0</td>
<td style="text-align: right;">1</td>
<td style="text-align: right;">1.76</td>
<td style="text-align: right;">3.42</td>
<td style="text-align: right;">0.00</td>
<td style="text-align: right;">0.00</td>
<td style="text-align: right;">0.07</td>
<td style="text-align: right;">2.10</td>
<td style="text-align: right;">22.57</td>
<td style="text-align: left;">▇▁▁▁▁</td>
</tr>
<tr class="even">
<td style="text-align: left;">daily_relative_humidity</td>
<td style="text-align: right;">0</td>
<td style="text-align: right;">1</td>
<td style="text-align: right;">58.13</td>
<td style="text-align: right;">16.17</td>
<td style="text-align: right;">8.04</td>
<td style="text-align: right;">46.77</td>
<td style="text-align: right;">57.16</td>
<td style="text-align: right;">71.43</td>
<td style="text-align: right;">90.71</td>
<td style="text-align: left;">▁▃▇▇▅</td>
</tr>
<tr class="odd">
<td style="text-align: left;">daily_surface_pressure</td>
<td style="text-align: right;">0</td>
<td style="text-align: right;">1</td>
<td style="text-align: right;">85.99</td>
<td style="text-align: right;">4.71</td>
<td style="text-align: right;">24.92</td>
<td style="text-align: right;">86.27</td>
<td style="text-align: right;">86.36</td>
<td style="text-align: right;">86.44</td>
<td style="text-align: right;">86.80</td>
<td style="text-align: left;">▁▁▁▁▇</td>
</tr>
<tr class="even">
<td style="text-align: left;">daily_wind_speed</td>
<td style="text-align: right;">0</td>
<td style="text-align: right;">1</td>
<td style="text-align: right;">1.44</td>
<td style="text-align: right;">1.02</td>
<td style="text-align: right;">0.74</td>
<td style="text-align: right;">1.09</td>
<td style="text-align: right;">1.32</td>
<td style="text-align: right;">1.62</td>
<td style="text-align: right;">13.76</td>
<td style="text-align: left;">▇▁▁▁▁</td>
</tr>
<tr class="odd">
<td style="text-align: left;">daily_sky_insolation</td>
<td style="text-align: right;">0</td>
<td style="text-align: right;">1</td>
<td style="text-align: right;">17.45</td>
<td style="text-align: right;">13.48</td>
<td style="text-align: right;">-99.00</td>
<td style="text-align: right;">16.18</td>
<td style="text-align: right;">18.94</td>
<td style="text-align: right;">21.44</td>
<td style="text-align: right;">28.90</td>
<td style="text-align: left;">▁▁▁▁▇</td>
</tr>
</tbody>
</table>

Model Development
=================

1.  Preparation

<!-- -->

    ## 'data.frame':    16221 obs. of  24 variables:
    ##  $ ship_date              : num  16432 16432 16432 16432 16432 ...
    ##  $ average_price          : num  1.22 1 1.08 1.01 1.02 1.4 0.93 1.19 1.11 0.88 ...
    ##  $ total_volume           : num  40873 435021 788025 80034 491738 ...
    ##  $ sku_4046               : num  2820 364302 53987 44562 7194 ...
    ##  $ sku_4225               : num  28287 23821 552906 24964 396752 ...
    ##  $ sku_4770               : num  49.9 82.2 39995 2752.3 128.8 ...
    ##  $ total_bags             : num  9716 46816 141137 7756 87663 ...
    ##  $ small_bags             : num  9187 16707 137146 6064 87407 ...
    ##  $ large_bags             : num  530 30109 3991 1691 256 ...
    ##  $ xlarge_bags            : num  0 0 0 0 0 ...
    ##  $ type                   : Factor w/ 2 levels "conventional",..: 1 1 1 1 1 1 1 1 1 1 ...
    ##  $ region                 : Factor w/ 48 levels "Albany","Atlanta",..: 1 2 3 4 5 6 7 8 9 10 ...
    ##  $ distance_km            : num  4400 2860 3900 3641 4547 ...
    ##  $ daily_temp_range       : num  4.27 4.27 4.27 4.27 4.27 4.27 4.27 4.27 4.27 4.27 ...
    ##  $ daily_dew_point        : num  2.59 2.59 2.59 2.59 2.59 2.59 2.59 2.59 2.59 2.59 ...
    ##  $ daily_wet_bulb         : num  1.78 1.78 1.78 1.78 1.78 1.78 1.78 1.78 1.78 1.78 ...
    ##  $ daily_max_temp         : num  1.67 1.67 1.67 1.67 1.67 1.67 1.67 1.67 1.67 1.67 ...
    ##  $ daily_min_temp         : num  0.92 0.92 0.92 0.92 0.92 0.92 0.92 0.92 0.92 0.92 ...
    ##  $ daily_avg_temp         : num  11.2 11.2 11.2 11.2 11.2 ...
    ##  $ daily_precip_mm        : num  8.03 8.03 8.03 8.03 8.03 8.03 8.03 8.03 8.03 8.03 ...
    ##  $ daily_relative_humidity: num  8.04 8.04 8.04 8.04 8.04 8.04 8.04 8.04 8.04 8.04 ...
    ##  $ daily_surface_pressure : num  24.9 24.9 24.9 24.9 24.9 ...
    ##  $ daily_wind_speed       : num  13.8 13.8 13.8 13.8 13.8 ...
    ##  $ daily_sky_insolation   : num  18.7 18.7 18.7 18.7 18.7 ...

Feature Selection

    library(leaps)
    subsets<-regsubsets(average_price~.-region,data=n_final, nbest=1,nvmax=10)   
    sub.sum <- summary(subsets)
    as.data.frame(sub.sum$outmat)

    ##           ship_date total_volume sku_4046 sku_4225 sku_4770 total_bags
    ## 1  ( 1 )                                                              
    ## 2  ( 1 )                                                              
    ## 3  ( 1 )                                                              
    ## 4  ( 1 )          *                                                   
    ## 5  ( 1 )          *                                                   
    ## 6  ( 1 )          *                     *                             
    ## 7  ( 1 )          *                                                   
    ## 8  ( 1 )          *                     *                             
    ## 9  ( 1 )          *            *                 *                    
    ## 10  ( 1 )         *            *                 *                    
    ##           small_bags large_bags xlarge_bags typeorganic distance_km
    ## 1  ( 1 )                                              *            
    ## 2  ( 1 )                                              *           *
    ## 3  ( 1 )                                              *           *
    ## 4  ( 1 )                                              *           *
    ## 5  ( 1 )                      *                       *           *
    ## 6  ( 1 )                      *                       *           *
    ## 7  ( 1 )                      *                       *           *
    ## 8  ( 1 )                      *                       *           *
    ## 9  ( 1 )                      *                       *           *
    ## 10  ( 1 )                     *           *           *           *
    ##           daily_temp_range daily_dew_point daily_wet_bulb daily_max_temp
    ## 1  ( 1 )                                                                
    ## 2  ( 1 )                                                                
    ## 3  ( 1 )                                 *                              
    ## 4  ( 1 )                                                *               
    ## 5  ( 1 )                                                *               
    ## 6  ( 1 )                                                *               
    ## 7  ( 1 )                                                               *
    ## 8  ( 1 )                                                               *
    ## 9  ( 1 )                                                               *
    ## 10  ( 1 )                                                              *
    ##           daily_min_temp daily_avg_temp daily_precip_mm daily_relative_humidity
    ## 1  ( 1 )                                                                       
    ## 2  ( 1 )                                                                       
    ## 3  ( 1 )                                                                       
    ## 4  ( 1 )                                                                       
    ## 5  ( 1 )                                                                       
    ## 6  ( 1 )                                                                       
    ## 7  ( 1 )                                                                      *
    ## 8  ( 1 )                                                                      *
    ## 9  ( 1 )                                                                      *
    ## 10  ( 1 )                                                                     *
    ##           daily_surface_pressure daily_wind_speed daily_sky_insolation
    ## 1  ( 1 )                                                              
    ## 2  ( 1 )                                                              
    ## 3  ( 1 )                                                              
    ## 4  ( 1 )                                                              
    ## 5  ( 1 )                                                              
    ## 6  ( 1 )                                                              
    ## 7  ( 1 )                       *                                      
    ## 8  ( 1 )                       *                                      
    ## 9  ( 1 )                       *                                      
    ## 10  ( 1 )                      *

    #I ended up not removing any varibles at this stage, because I wanted to see how many variables will be left after removing the highly correlated.

Removing “organic” avocados

    nonorganic <- n_final[n_final$type=="conventional",-11]
    #The group decided to only include "conventional" type of avocados in the project model because:
    #1. The dataset was too large and we wanted to reduce its size.
    #2. It is expected that organic fruits are consistently more expensive than its non-organic counterparts in almost all cases, so we did not consider this as an interesting point to investigate. 
    #3. Our major interests in the dataset are shipping distance and weather in the area that produced avocados, we reckoned that including the "type" variable would be distracting.

Visualization

    hist(nonorganic$average_price,
         main = "Price Distribution",
         xlab="Average price",
         xlim=c(0,2.5),
         breaks = 100,
         col = "grey")

![](Untitled_files/figure-markdown_strict/unnamed-chunk-3-1.png)

    plot(nonorganic$average_price, nonorganic$distance_km, 
         main = " Relationship between average price and distance", 
         xlab = "Average Price", 
         ylab = "Distance",
         pch = 20,
         cex = 0.5,
         col = "black")

![](Untitled_files/figure-markdown_strict/unnamed-chunk-3-2.png)

    boxplot(average_price~distance_km, data = nonorganic,
            col = rainbow(47))

![](Untitled_files/figure-markdown_strict/unnamed-chunk-3-3.png)

    library(ggplot2)
    ggplot(final, aes(x = average_price)) +
      geom_density(aes(group=type, col=type))

![](Untitled_files/figure-markdown_strict/unnamed-chunk-3-4.png)
