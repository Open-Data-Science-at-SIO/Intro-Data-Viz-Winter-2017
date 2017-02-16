Join our chatroom to keep appraised of updates, info, and general Q&A:

[![Join the chat at https://gitter.im/Open-Data-Science-at-SIO/Intro-Data-Viz-Winter-2017](https://badges.gitter.im/Open-Data-Science-at-SIO/Intro-Data-Viz-Winter-2017.svg)](https://gitter.im/Open-Data-Science-at-SIO/Intro-Data-Viz-Winter-2017?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

# Introduction to Data Visualization and Data Wrangling for R Users Group (Winter 2017)

## Course Objectives

The goal of the course is to get students familiar with the process of reading, manipulating, and visualizing data. The course will be taught primarily in R, but will touch on related topics such as R markdown, the "grammar of graphics", Shiny, and Git. 

Github Repo for the course: https://github.com/Open-Data-Science-at-SIO/Intro-Data-Viz-Winter-2017

## Code of Conduct

All participants will be expected to follow the SIO Open Data Science Code of Conduct: https://open-data-science-at-sio.github.io/mission.html

Note that this applies both to the physical space for classes, as well as online interactions in the chatroom, mailing list, and Github repository.

## Target Audience

Students should have some familiarity with programming and/or R (e.g. past experience programming in R for an introductory stats course). A short introductory course in R (e.g. https://www.datacamp.com/courses/free-introduction-to-r) will also suffice.

### Pre-requisites

Students who plan to attend should install R (https://cran.r-project.org/), RStudio (https://www.rstudio.com/products/rstudio/download/), and Git (https://git-scm.com/). While RStudio is not strictly necessary for this course, it will ensure a standard user interface for students to follow along.

Students should also create a GitHub account (https://github.com/).

## Logistics

Class meets every Thursday 1pm - 2:30pm in Hubbs Hall 4500 (unless otherwise noted).

Each class will be ~~30-45~~ 60 min. of guided code demos, followed by ~~30-45~~ 30 min of Q&A / interactive lab sessions.

Students are **highly encouraged** to bring laptops to class to follow along.

## Schedule

* January 12 (Week 1)
    * Course Logistics
    * Basic Git and Github
    * Overview of R data types (numeric, factor, string, date & time, binary, etc.)
    * Overview of R data structures (array, list, matrix, data frames, etc.)
* January 19 (Week 2)
    * RStudio interface setup
    * Installing R packages
    * Basic R markdown (`rmarkdown` and `knitr`)
    * Reading and writing data from files & databases
    * Basic data wrangling
        * Conversion between wide and long formats
        * Data validation
* January 26 (Week 3)
    * The "grammar of graphics" (`ggplot2`) & layer system
    * Basic ggplot geoms and plots (scatterplot, histogram, bars, lines)
* February 2 (Week 4)
    * Changing colors in ggplot
    * The theme layer in ggplot
    * Custom color palettes (`viridis`, `RColorBrewer`, `spaceMovie`)
    * Adding summary statistics in plots
* February 9 (Week 5)
    * Advanced ggplot geoms and plots
    * Various plot tweaks (coordinate transformations)
    * Multi-panel plots
* February 16 (Week 6)
    * Advanced data wrangling (`dplyr` and `tidyr`)
    * subsetting, summarizing, transformations, merging datasets
    * `lapply` (base R) and `map` (`purrr`) functions
* February 23 (Week 7)
    * Advanced R markdown and different output formats
* March 2 (Week 8)
    * 3d plots (`rgl`)
    * Animation (`gganimate`)
* March 9 (Week 9)
    * Interactive web apps (`shiny`)
* March 16 (Week 10)
    * TBD (unassigned - catch-up week / guest speaker / advanced topic)

# Links

## Week 1
* [Simple introduction to Git that explains the jargon and various use cases -- https://speakerdeck.com/alicebartlett/git-for-humans](https://speakerdeck.com/alicebartlett/git-for-humans)
* [A quick guide to making new repositories on Github and associating them with a new RStudio project -- http://happygitwithr.com/rstudio-git-github.html](http://happygitwithr.com/rstudio-git-github.html)
* [RStudio tips and tricks -- https://rawgit.com/kevinushey/2017-rstudio-conf/master/slides.html#1](https://rawgit.com/kevinushey/2017-rstudio-conf/master/slides.html#1)

## Week 2
* [R Markdown basics -- http://rmarkdown.rstudio.com/](http://rmarkdown.rstudio.com/)
* [Bibliographies and citations in R Markdown -- http://rmarkdown.rstudio.com/authoring_bibliographies_and_citations.html](http://rmarkdown.rstudio.com/authoring_bibliographies_and_citations.html)
* [Advanced R Markdown -- https://slides.yihui.name/2017-rstudio-conf-rmarkdown-Yihui-Xie.html#1](https://slides.yihui.name/2017-rstudio-conf-rmarkdown-Yihui-Xie.html#1)
* [Sample code for various tasks in R -- http://www.cookbook-r.com/](http://www.cookbook-r.com/)
* [RStudio cheatsheets - https://www.rstudio.com/resources/cheatsheets/](https://www.rstudio.com/resources/cheatsheets/)

## Week 3
* Basis for week 3 notes: [Harvard tutorial -- http://tutorials.iq.harvard.edu/R/Rgraphics/Rgraphics.html](http://tutorials.iq.harvard.edu/R/Rgraphics/Rgraphics.html)
* Basis for week 3 notes: [Hadley slides -- http://ggplot2.org/resources/2007-vanderbilt.pdf](http://ggplot2.org/resources/2007-vanderbilt.pdf)
* [ggplot2 book -- http://roger.ucsd.edu/record=b6914994~S9](http://roger.ucsd.edu/record=b6914994~S9)
* [Hadley slides on ggplot2 motivation and examples -- http://ggplot2.org/resources/2007-past-present-future.pdf](http://ggplot2.org/resources/2007-past-present-future.pdf)
* [Argument against ggplot -- http://simplystatistics.org/2016/02/11/why-i-dont-use-ggplot2/](http://simplystatistics.org/2016/02/11/why-i-dont-use-ggplot2/)
* [Response to above, pro-ggplot -- http://varianceexplained.org/r/why-I-use-ggplot2/](http://varianceexplained.org/r/why-I-use-ggplot2/)
* [Reasons to use ggplot system -- https://mandymejia.wordpress.com/2013/11/13/10-reasons-to-switch-to-ggplot-7/](https://mandymejia.wordpress.com/2013/11/13/10-reasons-to-switch-to-ggplot-7/)

## Week 4
* [theme layer documentation in ggplot -- http://docs.ggplot2.org/dev/vignettes/themes.html](http://docs.ggplot2.org/dev/vignettes/themes.html)
* [`spaceMovie` package for Star Wars palettes -- https://github.com/butterflyology/spaceMovie](https://github.com/butterflyology/spaceMovie)
* [`viridis` package for color palettes -- https://cran.r-project.org/web/packages/viridis/vignettes/intro-to-viridis.html](https://cran.r-project.org/web/packages/viridis/vignettes/intro-to-viridis.html)
* [Info about different color scales in ggplot -- http://www.cookbook-r.com/Graphs/Colors_(ggplot2)/](http://www.cookbook-r.com/Graphs/Colors_(ggplot2)/)
* [Cheatsheet about color palettes -- https://www.nceas.ucsb.edu/~frazier/RSpatialGuides/colorPaletteCheatsheet.pdf](https://www.nceas.ucsb.edu/~frazier/RSpatialGuides/colorPaletteCheatsheet.pdf)

## Week 5
* [ggplot gallery -- http://www.r-graph-gallery.com/portfolio/ggplot2-package/](http://www.r-graph-gallery.com/portfolio/ggplot2-package/)
* [extensions to ggplot (other packages) -- http://www.ggplot2-exts.org/gallery/](http://www.ggplot2-exts.org/gallery/)
* [various tweaks to prettify a ggplot figure -- http://zevross.com/blog/2014/08/04/beautiful-plotting-in-r-a-ggplot2-cheatsheet-3/](http://zevross.com/blog/2014/08/04/beautiful-plotting-in-r-a-ggplot2-cheatsheet-3/)

## Week 6
* [Tidy Data -- http://vita.had.co.nz/papers/tidy-data.pdf](http://vita.had.co.nz/papers/tidy-data.pdf)
* [Data Wrangling cheatsheet -- https://github.com/rstudio/cheatsheets/raw/master/source/pdfs/data-transformation-cheatsheet.pdf](https://github.com/rstudio/cheatsheets/raw/master/source/pdfs/data-transformation-cheatsheet.pdf)
* [dplyr vignette -- https://cran.rstudio.com/web/packages/dplyr/vignettes/introduction.html](https://cran.rstudio.com/web/packages/dplyr/vignettes/introduction.html)
