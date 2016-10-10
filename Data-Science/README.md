Learn R using SWIRL

Introduced as apart of Coursera's Data Science specialization by Johns Hopkins University.

0. Install R
swirl requires R 3.0.2 or later. If you have an older version of R, please update before going any further. If you're not sure what version of R you have, type R.version.string at the R prompt. You can download the latest version of R from https://www.r-project.org/.
Optional but highly recommended: Install RStudio. You can download the latest version of RStudio at https://www.rstudio.com/products/rstudio/.

1. Install swirl
Since swirl is an R package, you can easily install it by entering a single command from the R console:
  install.packages("swirl")
If you've installed swirl in the past make sure you have version 2.2.21 or later. You can check this with:
  packageVersion("swirl")

2. Load swirl
Every time you want to use swirl, you need to first load the package. From the R console:
  library(swirl)

3. Install the Exploratory Data Analysis course
swirl offers a variety of interactive courses, but for our purposes, you want the one called Exploratory Data Analysis. Type the following from the R prompt to install this course:
  install_from_swirl("Exploratory Data Analysis")

4. Start swirl and complete the lessons
Type the following from the R console to start swirl:
  swirl()
Then, follow the menus and select a course when given the option.

For more information on swirl, visit swirlstats.com
