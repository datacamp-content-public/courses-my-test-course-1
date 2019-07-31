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

We learn to assign values to variables.

`@instructions`
A variable is an entity that stores a value or an object (like a vector, etc.). You can assign a value to the variable ```
my_var ``` with the following command.

``` 
my_var <- 4
```

`@hint`
Complete the code in the script such that it assigns the value 17 to variable x.

`@pre_exercise_code`
```{r}
x <- 42
```

`@sample_code`
```{r}
# Assign the value 17 to x.
x <- 
```

`@solution`
```{r}

```

`@sct`
```{r}
# sct code
ex() %>% check_object("x") %>% check_equal()
success_msg("Well done!")

```

---

## creating a vector

```yaml
type: NormalExercise
key: f67ec5b842
xp: 100
```



`@instructions`
Create a vector called "myvec" that contains the numbers 1, 2 and 3.

`@hint`


`@pre_exercise_code`
```{r}

```

`@sample_code`
```{r}
myvec <- 
```

`@solution`
```{r}
myvec <- c(1,2,3)
```

`@sct`
```{r}
ex() %>% check_object("myvec") %>% check_equal()
success_msg("Well done!")
```
