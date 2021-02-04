# STA 199: Data wrangling II

**Date**: Friday, February 5<br>

## Learning objectives

- Reinforce core functions from package `dplyr`
- Tidy data and tibbles
- Wrangling multiple datasets with `*_join()`

## Key Resources

- [dplyr cheatsheet](https://rstudio.com/wp-content/uploads/2015/02/data-wrangling-cheatsheet.pdf)

## `dplyr` join functions

Consider `*_join(x, y)`.

|  Join function | Description                                                  |
|----------------|--------------------------------------------------------------|
| `inner_join()` | join all rows from `x` where there are matching values in `y`|
|  `left_join()` | include all rows from `x`                                    |
| `right_join()` | include all rows from `y`                                    |
|  `full_join()` | include all rows in `x` or `y`                               |
|  `semi_join()` | return all rows from `x` with match in `y`                   |
|  `anti_join()` | return all rows from `x` without a match in `y`              |