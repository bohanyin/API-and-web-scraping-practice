# hw08
Author: Bohan Yin

## Assignment Description
Thanks for reviewing my homework! This assignment contains two parts. Part 1 evaluate the relationship of population density with average life expectancy using the data from `gapminder`.   The API used for this part is GeoNames. There are a few things we need to do to be able to use this package to access the geonames API:

- Go to the [geonames site](http://www.geonames.org/login/) and register an account.
- Enable the free web service on geonames site
- Tell R your geonames username. You could run the line: `options(geonamesUsername = "my_user_name")`


In part 2 I explored the NBA career performance of Yao Ming, a Chinese formal NBA player served in Houston Rockets. The source of NBA data is from [balldontlie API (NBA stats)](http://www.balldontlie.io/#introduction), which offers free API to access NBA related data (No API key required. Amazing isn¡¦t it). But in order to retrieve data from the website,it still requires the user to write API queries to access data, which I included the written API query in part2.

## Packages
The packages required for this assignment are:  

- `library(dplyr)`
- `library(tidyverse)`
- `library(gapminder)`
- `library(geonames)`
- `library(countrycode)`
- `library(magrittr)`
- `library(broom)`
- `library(dplyr)`
- `library(knitr)`
- `library(stringr)`
- `library(curl)`
- `library(jsonlite)`
- `library(data.table)`
- `library(httr)`
- `library(kableExtra)`

## Access
You can find my assignment here:

- [Part1](hw08_Part1.Rmd)
- [Part2](hw08_Part2.Rmd)

## Note
If you have time, please check out the pdf files for both parts, as they have prettier outlooks!