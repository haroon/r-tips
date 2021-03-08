## How to Get Help in R
1. To get help on a specific topic, use the [help.search](https://rdrr.io/r/utils/help.search.html) function, e.g. `help.search('help')`.
2. To read documentation of a function, use a question mark before the function name, e.g. `?help.search`.
3. To lookup which package a function belongs to, use [find](https://rdrr.io/r/utils/apropos.html), e.g. `find('help.search')`.
4. To find all objects matching a (partial) query, use [apropos](https://rdrr.io/r/utils/apropos.html), e.g. `apropos('sear')`.
5. To see working example of a function, use [example](https://rdrr.io/r/utils/example.html), e.g. `example(read.table)`.
6. To see working demos of some working `R` scripts, use [demo](https://rdrr.io/r/utils/demo.html), e.g. `demo('plotmath')`. To list the demos in all *available* packages., use `demo(package = .packages(all.available = TRUE))`
