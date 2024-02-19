README
================
Hunter Metz
2024-02-19

# Praat Values

``` r
# 'hablo' and 'habló' duration values

dur_hablo_stressed <- 0.471
dur_hablo_unstressed <- 0.382

# 'o' and 'ó' duration values

dur_o_stressed <- 0.129
dur_o_unstressed <- 0.093

# 'o' and 'ó' intensity values

int_o_stressed <- 4.042
int_o_unstressed <- 1.307

# 'o' and 'ó' pitch values

f0_o_stressed <- 120.549
f0_o_unstressed <- 123.418
```

``` r
# Calculation of the difference in (ms) between dur_hablo_stressed and dur_hablo_unstressed

dur_hablo_difference <- (dur_hablo_stressed - dur_hablo_unstressed) * 1000
print("Difference in duration between stressed and unstressed 'hablo' (ms):")
```

    ## [1] "Difference in duration between stressed and unstressed 'hablo' (ms):"

``` r
print(dur_hablo_difference)
```

    ## [1] 89

``` r
# Calculation of the difference in (ms) between dur_o_stressed and dur_o_unstressed

dur_o_difference <- (dur_o_stressed - dur_o_unstressed) * 1000
print("Difference in duration between stressed and unstressed 'o' (ms):")
```

    ## [1] "Difference in duration between stressed and unstressed 'o' (ms):"

``` r
print(dur_o_difference)
```

    ## [1] 36

``` r
# Calculation of the difference in intensity between dur_o_unstressed and int_o_unstressed

intensity_difference <- int_o_stressed - int_o_unstressed
print("Difference in intensity between stressed and unstressed 'o':")
```

    ## [1] "Difference in intensity between stressed and unstressed 'o':"

``` r
print(intensity_difference)
```

    ## [1] 2.735

``` r
# Calculation of the difference in (ms) in F0 between f0_o_stressed and f0_o_unstressed

f0_difference <- f0_o_stressed - f0_o_unstressed
print("Difference in fundamental frequency (F0) between stressed and unstressed 'o':")
```

    ## [1] "Difference in fundamental frequency (F0) between stressed and unstressed 'o':"

``` r
print(f0_difference)
```

    ## [1] -2.869

# Summary of observations

# The ‘hablo’ and ‘habló’ duration has a difference of 89 (ms), as well as an \[o\] duration difference of 36 (ms). The intensity difference in dB is 2.735 between \[o\] and \[ó\], which makes sense considering the accented syllable. There is also a difference in frequency in Hz of -2.869 for the accented syllable.
