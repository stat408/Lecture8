Week 8: Exercises
================

## Exercise:

``` r
ski_acres <- data.frame( 
  ski.hill = c('Big Sky','Bridger Bowl', 'Jackson', 'Steamboat' ), 
                        skiable.acres = c(5800,2000, "2500+",2965))
```

### Q1.

What type of variable is `skiable.acres` in the `ski_acres` data frame?

### Q2.

Sort the ski resorts by skiable acres in descending fashion.

## Exercise

Now combine the following information into a single table sorted
alphabetically by the name of the ski hill.

    ##       ski.hill skiable.acres
    ## 1      Big Sky          5800
    ## 2 Bridger Bowl          2000
    ## 3      Jackson         2500+
    ## 4    Steamboat          2965

    ##     ski.resort ticket.cost
    ## 1 Bridger Bowl          60
    ## 2      Big Sky     depends
    ## 3    Steamboat         145
    ## 4      Jackson         130

    ## [1] "Discovery" "2200"      "20"

## Exercise

Combine the two data sets using join

    ##       ski.hill skiable.acres
    ## 1      Big Sky          5800
    ## 2 Bridger Bowl          2000
    ## 3      Jackson         2500+
    ## 4    Steamboat          2965

    ##     ski.resort ticket.cost
    ## 1 Bridger Bowl          60
    ## 2      Big Sky     depends
    ## 3    Steamboat         145
    ## 4      Jackson         130

    ## # A tibble: 1 x 3
    ##   ski.hill  skiable.acres ticket.cost
    ##   <chr>     <chr>         <chr>      
    ## 1 Discovery 2200          20

## Exercise

``` r
billboard
```

    ## # A tibble: 317 x 79
    ##    artist track date.entered   wk1   wk2   wk3   wk4   wk5   wk6   wk7   wk8
    ##    <chr>  <chr> <date>       <dbl> <dbl> <dbl> <dbl> <dbl> <dbl> <dbl> <dbl>
    ##  1 2 Pac  Baby… 2000-02-26      87    82    72    77    87    94    99    NA
    ##  2 2Ge+h… The … 2000-09-02      91    87    92    NA    NA    NA    NA    NA
    ##  3 3 Doo… Kryp… 2000-04-08      81    70    68    67    66    57    54    53
    ##  4 3 Doo… Loser 2000-10-21      76    76    72    69    67    65    55    59
    ##  5 504 B… Wobb… 2000-04-15      57    34    25    17    17    31    36    49
    ##  6 98^0   Give… 2000-08-19      51    39    34    26    26    19     2     2
    ##  7 A*Tee… Danc… 2000-07-08      97    97    96    95   100    NA    NA    NA
    ##  8 Aaliy… I Do… 2000-01-29      84    62    51    41    38    35    35    38
    ##  9 Aaliy… Try … 2000-03-18      59    53    38    28    21    18    16    14
    ## 10 Adams… Open… 2000-08-26      76    76    74    69    68    67    61    58
    ## # … with 307 more rows, and 68 more variables: wk9 <dbl>, wk10 <dbl>,
    ## #   wk11 <dbl>, wk12 <dbl>, wk13 <dbl>, wk14 <dbl>, wk15 <dbl>, wk16 <dbl>,
    ## #   wk17 <dbl>, wk18 <dbl>, wk19 <dbl>, wk20 <dbl>, wk21 <dbl>, wk22 <dbl>,
    ## #   wk23 <dbl>, wk24 <dbl>, wk25 <dbl>, wk26 <dbl>, wk27 <dbl>, wk28 <dbl>,
    ## #   wk29 <dbl>, wk30 <dbl>, wk31 <dbl>, wk32 <dbl>, wk33 <dbl>, wk34 <dbl>,
    ## #   wk35 <dbl>, wk36 <dbl>, wk37 <dbl>, wk38 <dbl>, wk39 <dbl>, wk40 <dbl>,
    ## #   wk41 <dbl>, wk42 <dbl>, wk43 <dbl>, wk44 <dbl>, wk45 <dbl>, wk46 <dbl>,
    ## #   wk47 <dbl>, wk48 <dbl>, wk49 <dbl>, wk50 <dbl>, wk51 <dbl>, wk52 <dbl>,
    ## #   wk53 <dbl>, wk54 <dbl>, wk55 <dbl>, wk56 <dbl>, wk57 <dbl>, wk58 <dbl>,
    ## #   wk59 <dbl>, wk60 <dbl>, wk61 <dbl>, wk62 <dbl>, wk63 <dbl>, wk64 <dbl>,
    ## #   wk65 <dbl>, wk66 <lgl>, wk67 <lgl>, wk68 <lgl>, wk69 <lgl>, wk70 <lgl>,
    ## #   wk71 <lgl>, wk72 <lgl>, wk73 <lgl>, wk74 <lgl>, wk75 <lgl>, wk76 <lgl>

Determine which song in this dataset spent the most time at \#1

## Exercise

Using either the Seattle Housing dataset or the billboard data, explore
the packages above.

    ## Parsed with column specification:
    ## cols(
    ##   price = col_double(),
    ##   bedrooms = col_double(),
    ##   bathrooms = col_double(),
    ##   sqft_living = col_double(),
    ##   sqft_lot = col_double(),
    ##   floors = col_double(),
    ##   waterfront = col_double(),
    ##   sqft_above = col_double(),
    ##   sqft_basement = col_double(),
    ##   zipcode = col_double(),
    ##   lat = col_double(),
    ##   long = col_double(),
    ##   yr_sold = col_double(),
    ##   mn_sold = col_double()
    ## )
