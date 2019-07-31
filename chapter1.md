---
title: 'Chapter Title Here'
description: 'Chapter description goes here.'
free_preview: true
---

## Example coding exercise

```yaml
type: NormalExercise
key: 2bafef99a3
lang: r
xp: 100
skills: 1
```

This is an example exercise.

`@instructions`


`@hint`


`@pre_exercise_code`
```{r}

```

`@sample_code`
```{r}

```

`@solution`
```{r}

```

`@sct`
```{r}

```

---

## Assigning a value to a variabe

```yaml
type: NormalExercise
key: ddc011c0e5
xp: 100
```

A variable is an entity that stores a value or an object (like a vector, etc.). You can assign a value to the variable ```
my_var ``` with the following command.

``` 
my_var <- 4
```

`@instructions`
Complete the code in the script such that it assigns the value 17 to variable x.

`@hint`


`@pre_exercise_code`
```{r}

```

`@sample_code`
```{r}
# Assign the value 17 to x.
x <- 
```

`@solution`
```{r}
x <- 17
```

`@sct`
```{r}
# sct code
ex() %>% check_object("x") %>% check_equal()
success_msg("Well done!")

```

---

## Printing the Results

```yaml
type: NormalExercise
key: f67ec5b842
xp: 100
```

Suppose you have already assigned the value 17 to variable x. Now you want to print the value of x (just to confirm). To do that, you should simply type the name of the variable in the script and run it.

`@instructions`
Print the value of x.

`@hint`


`@pre_exercise_code`
```{r}
x <- 17
```

`@sample_code`
```{r}
# Print the value of x!

```

`@solution`
```{r}
x
```

`@sct`
```{r}
ex() %>% check_object("x") %>% check_equal()
success_msg("Well done!")
```

---

## Variables

```yaml
type: NormalExercise
key: c6b2e31392
xp: 100
```

We would like to try adding two variables here. You have already learned to assign values to a variable. You can easily add, subtract, multiply or divide variables using the operators +, -, * and /. For example, if you want to add the values stored in the two variables ```x``` and ```y```, you woul use the command
```
x+y
```
Or, if you want to multiply the value stored in ```x``` by the value stored in ```y``` you would use
```
x*y
```


`@instructions`
Assign to x the value 17. Assign to y the value 289. Create a new variable ```z``` that is the result of adding the two variables ```x``` and ```y```.

`@hint`


`@pre_exercise_code`
```{r}
x <- 17
y <- 289
z <- x + y
```

`@sample_code`
```{r}
# Assign the value 17 to x
x <- 

# Assign the value 289 to y
y <- 

# create the variable z
z <-
```

`@solution`
```{r}
z <- x + y
```

`@sct`
```{r}
ex() %>% check_object("x") %>% check_equal()
ex() %>% check_object("y") %>% check_equal()
ex() %>% check_object("z") %>% check_equal()
success_msg("Well done!")
```
