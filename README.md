# wirds-2021-binder-GR

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/GrzegorzR3/wirds-2021-binder-GR/main?urlpath=rstudio)

Aby repozytorium stało się obrazem, który będzie zawierał R wraz z określonymi pakietami należy utworzyć dwa pliki:

+ `runtime.txt` -- plik powinien zawierać wersję R wraz z datą np. `r-3.6-YYYY-MM-DD` lub `r-YYYY-MM-DD` (domyślnie wybrany będzie wersja 3.6)
+ `install.R` -- skrypt w R zawierający listę pakietów do instalacji np. `install.packages("tidyverse")`
