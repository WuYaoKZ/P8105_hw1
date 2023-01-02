P8105_hw1
================
Yang Xie
2023-01-02

\*\* Load Pckages\*\*

``` r
library(tidyverse)
```

    ## Warning: 程辑包'tidyverse'是用R版本4.2.2 来建造的

### Problem 1

Load the penguins data set and give a short description using inline R
code:

``` r
data("penguins", package="palmerpenguins")

penguins
```

    ## # A tibble: 344 × 8
    ##    species island    bill_length_mm bill_depth_mm flipper_…¹ body_…² sex    year
    ##    <fct>   <fct>              <dbl>         <dbl>      <int>   <int> <fct> <int>
    ##  1 Adelie  Torgersen           39.1          18.7        181    3750 male   2007
    ##  2 Adelie  Torgersen           39.5          17.4        186    3800 fema…  2007
    ##  3 Adelie  Torgersen           40.3          18          195    3250 fema…  2007
    ##  4 Adelie  Torgersen           NA            NA           NA      NA <NA>   2007
    ##  5 Adelie  Torgersen           36.7          19.3        193    3450 fema…  2007
    ##  6 Adelie  Torgersen           39.3          20.6        190    3650 male   2007
    ##  7 Adelie  Torgersen           38.9          17.8        181    3625 fema…  2007
    ##  8 Adelie  Torgersen           39.2          19.6        195    4675 male   2007
    ##  9 Adelie  Torgersen           34.1          18.1        193    3475 <NA>   2007
    ## 10 Adelie  Torgersen           42            20.2        190    4250 <NA>   2007
    ## # … with 334 more rows, and abbreviated variable names ¹​flipper_length_mm,
    ## #   ²​body_mass_g

-   The data set penguins has 344 rows and 8 columns.

-   The data set contains variables: species, island, bill_length_mm,
    bill_depth_mm, flipper_length_mm, body_mass_g, sex, year.

-   The mean flipper length is 200.9152047.