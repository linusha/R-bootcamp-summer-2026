# Hertie School's 2026 R Bootcamp

Taught by [Linus Hagemann](http://linushagemann.de) at the [Hertie School in Berlin](https://www.hertie-school.org/en/) in September 2026.

Before the first day, please install `R` and `RStudio`, as well as `git`. I prepared a guide you can follow [here](IDS_Software_Setup.pdf).


## Recordings 📺

If you missed the bootcamp or want to revisit some of the content, you can find screencasts/recordings below. Please do not share them outside of the course.

> [!IMPORTANT]
> Only people from inside of Hertie can access these, so you'll need to be logged-in.

1. [Introduction to `R`](https://hertieschool-my.sharepoint.com/:v:/g/personal/243854_students_hertie-school_org/IQBkFFvbVdDlSJAfOyJmfGgCAUZ5ak6J3gNwLJcKcjNwPrA?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=49jD1N): Get to know your way around RStudio, execute your first commands, assign variables,...
2. [Visualizations with `ggplot2`](https://hertieschool-my.sharepoint.com/:v:/g/personal/243854_students_hertie-school_org/IQA4z_7JcU9aT7f6HxCR7vnrAUk7MxXSL5Dxp92v8KsRiu0?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=c0mxZq): Basics of visualizing data with `ggplot` and some 🐧.
3. [Manipulating tabular data with `dplyr`](https://hertieschool-my.sharepoint.com/:v:/g/personal/243854_students_hertie-school_org/IQDMNdJfhAIsQKF6S9JaT2pmAUTNpt6osHDmO3xn5-JB5ic?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=wQ9chN): Dataframes, tabular data and how to manipulate it using `dplyr`. We covered the most important verbs such as `mutate`, `relocate`, `arrange`,`rename`, `group_by`, `summarize`,... 

## Slides 💻

> [!NOTE]
> I did not use all of these during the bootcamp. I still left them here, so that you can skim if you want. `Vectors and Matrices` we only partially covered.

1. [Overview](01-overview/bootcamp-overview.pdf): Overview of what we will cover during the bootcamp.
2. [Intro to R](03-R-intro/intro-to-r.pdf): Introduces the basics of base R (objects, vectors, functions, and dataframes).
3. [Intro to Data Visualization](04-intro-to-data-viz/intro-to-data-viz.pdf): Introduces the basics of data visualization with R using ggplot2.
4. [Working with Dataframes with `dplyr`](05-dplyr/working-with-dataframes-with-dplyr.pdf): Covers the main `dplyr` verbs (functions) such as `filter()`, `select()`, `mutate()`, `summarize()`, and `group_by()`.
5. [Vectors and Matrices](06-vectors-matrices/vectors-and-matrices.pdf): Overview of vectors and matrices in R. Unused in the exercises.

## Cheatsheets 🤓

During the bootcamp, I recommended the cheasheets on [`ggplot`](https://rstudio.github.io/cheatsheets/data-visualization.pdf) & [`dplyr`](https://rstudio.github.io/cheatsheets/data-transformation.pdf). More useful cheatsheets [here](https://rstudio.github.io/cheatsheets/).

## Exercises ✍️

> [!TIP]
> We only worked on the third task on the weekend, but the others are great practice material during the first weeks of IDS. Note that the first exercise is easier than the other two.

1. [`dplyr` and `ggplot` with NYC Flights](Exercises/nyc-flights/nyc-flights.qmd): Practice using `dplyr` and `ggplot2` with a dataset of all flights departing NYC in 2013.
2. [Leader Assassination as a Natural Experiment](Exercises/leader-assassination/leader-assassination.qmd): Practice using `dplyr` and `ggplot2` to investigate the effects of leader assassinations on democracy and war. Adapted from [Quantiative Social Science: An Introduction with Tidyverse](https://press.princeton.edu/books/paperback/9780691222288/quantitative-social-science).
3. [UN Votes of Russia and the US](Exercises/un-voting/un-voting.qmd): Practice using `dplyr` and `ggplot2` to investigate how UN votes between Russia, the USA, and the world moved from after WW2, through the cold war until after "the end of history". Adapted from [Quantiative Social Science: An Introduction with Tidyverse](https://press.princeton.edu/books/paperback/9780691222288/quantitative-social-science).


## Sources & Acknowledgements

All of the materials in here were prepared by [Jackson Luckey](https://www.jacksonmluckey.com/), with oly minor edits by me. Credit for the conceptualization of the bootcamp belongs to him.

### Original Sources Section

This course borrows liberally from Simon Munzert's [Introduction to Data Science (IDS) course](https://github.com/intro-to-data-science-25/) as the bootcamp primarily serves as preparation for the course.

I also took inspiration, examples, and exercises from:

- [R Intro in the R Manual](https://cran.r-project.org/doc/manuals/r-release/R-intro.html)
- [R for Data Science](https://r4ds.hadley.nz/)
- [Quantiative Social Science: An Introduction](https://press.princeton.edu/books/paperback/9780691175461/quantitative-social-science)
- [Quantiative Social Science: An Introduction with Tidyverse](https://press.princeton.edu/books/paperback/9780691222288/quantitative-social-science)
- [Data Analysis for Social Science: A Friendly and Practical Introduction](https://press.princeton.edu/books/paperback/9780691199436/data-analysis-for-social-science)