# Mod 3 Day 1

**Original author:** Dr. Cassy Dorff

**Original date:** 8/30/2022

> Historical student-facing teaching material. [Editable R Markdown](mod3_day1_student.Rmd). This is a text preview, not executed output. Code blanks are intentional; see the repository data guide for withheld inputs and external dependencies.

# New data: breweries

Today we are going to explore data on our own applying lessons from last week.

1. Try to load the data below. Take some time to 'look' at the data and get familiar with its structure. (Load in "ncbreweries data" using 'load' or the Rstudio GUI.)

2. How would you describe this data?

```r
# library
library(tidyverse)

# load data
load() 

# use the commands from last lecture to check the dimension, set up, and variable names
# "state the basics"



# check out using tidyverse

```

_What do we see?_

Discuss the data with your group. In the columns we see attributes that contain information about each Brewery. This information is easy to "read" but might prove difficult, in this format, for plotting and analysis.

"Long" formatted data (versus wide) is useful for visualization because each **variable** (or attribute) is represented by a column.

3. Using whatever method you prefer, how would we view the different type of breweries available in the data? How many are in each type?

```r
```


4. Now, how can we calculate the mean beer count for each type of brewery? (There are five types) using a tidy approach? Hint, use group_by and summarize

```r
# in tidy (try in groups)


```


5. Next, can you make a simple graphic of this data? Read about ggplot using the help files first!

```r
```
