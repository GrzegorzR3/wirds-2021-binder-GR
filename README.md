# wirds-2021-binder-GR

Aby repozytorium stało się obrazem, który będzie zawierał R wraz z określonymi pakietami należy utworzyć dwa pliki:

+ `runtime.txt` -- plik powinien zawierać wersję R wraz z datą np. `r-3.6-YYYY-MM-DD` lub `r-YYYY-MM-DD` (domyślnie wybrany będzie wersja 3.6)
+ `install.R` -- skrypt w R zawierający listę pakietów do instalacji np. `install.packages("tidyverse")`
