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
Assign the number 2 to variable a.

`@hint`
remember we use the operator "<-" to assign a number to a variable.

`@pre_exercise_code`
```{r}

```

`@sample_code`
```{r}
a <- 
```

`@solution`
```{r}
a <- 2
```

`@sct`
```{r}
# sct code
test_error()
success_msg("Nice work! Success messages are a great way to keep users engaged even after the exercise is over. Try to encourage them to play around in the console to really grasp the concepts you're trying to teach!")

```
