
<!-- README is generated from README.Rmd, edit ONLY this file if needed. But, after you edit it, you NEED TO KNIT IT BY HAND in order to create the new README.md, which is the thing which is actually used. -->

# Tutorials for *R for Data Science (2e)*

<!-- badges: start -->

[![R build
status](https://github.com/PPBDS/r4ds.tutorials/workflows/R-CMD-check/badge.svg)](https://github.com/PPBDS/r4ds.tutorials/actions)
<!-- badges: end -->

## About this package

**r4ds.tutorials** provides tutorials for [*R for Data Science
(2e)*](https://r4ds.hadley.nz/) by Hadley Wickham, Mine
Çetinkaya-Rundel, and Garrett Grolemund. These tutorials assume that you
have some experience working with the tools provided by the
**[tutorial.helpers](https://ppbds.github.io/tutorial.helpers/)**
package. As long as you have completed the “Getting Started” tutorial
from that package, you should be fine.

## Installation

You can install the development version from
[GitHub](https://github.com/) with:

``` r
remotes::install_github("PPBDS/r4ds.tutorials")
```

If R offers you the option to update some packages, you should do so.
For packages that need compilation, feel free to answer “no”.

Then **restart your R session** or **restart RStudio**.

## Accessing tutorials

In order to access the tutorials, start by loading the package.

``` r
library(r4ds.tutorials)
```

You can access the tutorials via the Tutorial tab in the top right
(Environment) pane in RStudio.

If either of the following is happening to you

<ul>
<li>
Cannot find the Tutorial pane
</li>
<li>
Cannot find any r4ds tutorials
</li>
</ul>

Then **remember to restart your R session** after installing the
package.

Because tutorials within the Tutorial pane are sorted in alphabetical
order by the name of the package, the **r4ds.tutorials** will be toward
the bottom. If you don’t see any tutorials, try clicking the “Home”
button – the little house symbol with the thin red roof in the upper
right.

In order to expand the window, you can drag and enlarge the tutorial
pane inside RStudio. In order to open a pop-up window, click the “Show
in New Window” icon next to the home icon.

You may notice that the Jobs tab in the lower left will create output as
the tutorial is starting up. This is because RStudio is running the code
to create the tutorial. If you accidentally clicked “Start Tutorial” and
would like to stop the job from running, you can click the back arrow in
the Jobs tab, and then press the red stop sign icon. Your work will be
saved between RStudio sessions, meaning that you can complete a tutorial
in multiple sittings. Once you have completed a tutorial, follow the
instructions on the tutorial `Submit` page and, if you’re a student,
submit your answers as instructed.
