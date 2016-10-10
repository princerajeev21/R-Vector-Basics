---
title       : Creating a Vector
description : In this chapter we will learn to create a vector


--- type:NormalExercise lang:r xp:50 skills:1 key:0b8961fe9d
Creating a Vector

In this chapter we will create a vector.
A vector is of mainly 3 types:
  a. Numeric Vector - one that contains only numeric values (integer of float).
  b. Character Vector - one that contains either single character values or strings as values.
  c. Logical Vector - one that contains logical values (TRUE or FALSE).

*** =instructions
- A vector is a simple tool to store data.
- To create a vector in R, we use the c() function aka combine function.
- Check how each of the vectors are created
- code is mentoned in the exercise window

*** =hint
- click Submit to run the code

*** =pre_exercise_code
```{r}
# Create a numeric vector
numeric_vector <- c(1,2,3,4,5)

# Create a float vector
float_vector <- c(10.0,20.0,30.0,40.0,50.0)

# Create a character vector with single characters
scharacter_vector <- c('H','e','l','l','o')

# Create a character vector with single characters
character_vector <- c('Hello','Python','Scala','Java','PHP')

# Create a logical vector
logical_vector <- c(TRUE,FALSE,FALSE,TRUE,FALSE)

# Clean up the environment
rm(Movies)
```

*** =sample_code
```{r}
# create a numeric_vector with values from 21 to 30

# print the numeric_vector

# create a character_vector with values from A to H

# print the character_vector

# create a logical_vector with values from TRUE,FALSE,FALSE,TRUE,TRUE

# print the logical_vector

```

*** =solution
```{r}
# create a numeric_vector with values from 21 to 30
numeric_vector <- c(21:30)
# print the numeric_vector
pri
nt(numeric_vector)
# create a character_vector with values from A to H
character_vector <- c('A','B','C','D','E','F','G','H')
# print the character_vector
print(character_vector)

# create a logical_vector with values from TRUE,FALSE,FALSE,TRUE,TRUE
logical_vector <- c(TRUE,FALSE,FALSE,TRUE,TRUE)
# print the logical_vector
print(logical_vector)
```

*** =sct
```{r}
# SCT written with testwhat: https://github.com/datacamp/testwhat/wiki

test_error()

success_msg("Good work!")
```
