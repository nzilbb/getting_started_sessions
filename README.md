# NZILBB Intro R Sessions

This repository contains data and slides for the initial sessions of the 
NZILBB introductory R workshop series.

The intended use case is for participants in the workshops to run the following
code at the start of the session:

```{r}
install.packages('usethis') # Install `usethis` if you don't already have it.
usethis::use_course('nzilbb/getting_started_sessions')
```

This should download all the relevant data files and the code which generates
the slides for the sessions.

