## My project
 This Project will work with RStudio, mtcar from base R is chosen for this project.

 To better analyze the data you will need to install some R packages. The required packages can be installed using R commands.

```{r}
install.packages(dplyr)
install.packages(cars)
library(dplyr)
library(cars)
```

## Execute the analysis

To execute the analysis, from the project folder you can run
```{r}
Rscript -e "rmarkdown::render('HW2.Rmd')"
```

This will create a file called report.html output in your directory that contains the results.
