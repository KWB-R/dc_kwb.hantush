---
title       : Getting started
description : How to use the package
attachments :
  slides_link : 


--- type:NormalExercise lang:r xp:100 skills:1 key:ad7f08c581
## Loading the package

Before using the functions provided in the kwb.hantush package you need to load 
it first.


*** =instructions
- Load the R package `kwb.hantush` using the `library()` function with the 
package name as argument

*** =hint
- Use `library(kwb.hantush)` for the first instruction.


*** =sample_code
```{r}
# load the R package kwb.hantush using library()
library(_____)

```

*** =solution
```{r}
#load the R package kwb.hantush using library()
library(kwb.hantush)
```

*** =sct
```{r}
# SCT written with testwhat: https://github.com/datacamp/testwhat/wiki

test_student_typed(c("library(kwb.hantush)","library(package=`kwb.hantush`"),
              not_typed = "You didn't call `library(kwb.hantush)`!")


success_msg("Good work!")
```
