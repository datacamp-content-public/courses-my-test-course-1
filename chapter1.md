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

## Insert exercise title here

```yaml
type: NormalExercise
key: ac4cf86e36
xp: 100
```

You can use R to perform simple or complicated arithmetic calculations. Below is a list of some of a number of most-widely used arithmetic operators in R.

- addition ```+```
- subtraction ```-```
- multiplication ```*```
- division ```/```
- exponentiation ```^```


`@instructions`
Use R operators to perform the following operations
- add 2 to 4
- subtract 5 from 15
- multiply 5 by 63
- divide 42 by 6
- raise 5 to the power of 31

`@hint`


`@pre_exercise_code`
```{r}

```

`@sample_code`
```{r}
# add 2 to 4

# subtract 5 from 15

# Multiply 5 by 63

# divide 42 by 6

# raise 5 to the power of 31
```

`@solution`
```{r}
6
10
5*63
42/6
5^31
```

`@sct`
```{r}
ex() %>% check_output(2+4)
ex() %>% check_output(15 -5)
ex() %>% check_output(5*63)
ex() %>% check_output(42/6)
ex() %>% check_output(5^2)
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

---

## Creating Vectors

```yaml
type: NormalExercise
key: 3a5490d847
xp: 100
```

Vectors are one-dimensional arrays that can hold numerical, character or logical values.
In R, you create vectors using the c() function. For example, suppose you want to create a vector by the name ```myvec``` that contains the values 1, 2 and 5, you would do that as follows,
```
myvec <- c(1,2,5)
```
Notice that the order of the elements of the vector is important. Now to print out ```myvec``` we will type it in the console. The result will be,
```
myvec
[1] 1 2 5
```
You can also assign characters to a vector like the following example.
```
mycharvec <- c("apples","oranges")
```


`@instructions`
Create a vector that contains the values 5, 2 and 6 (in that order) and call it x.

`@hint`


`@pre_exercise_code`
```{r}

```

`@sample_code`
```{r}
# Create the vector
x <- 
```

`@solution`
```{r}
x <- c(5, 2, 6)
```

`@sct`
```{r}
ex() %>% check_object("x") %>% check_equal()
success_msg("Well done!")
```

---

## Working with Vectors

```yaml
type: NormalExercise
key: 881475d3b1
xp: 100
```

You can do different types of calculations with vectors. For instance, you can multiply all the elements of a vector by a certain number, divide all the values of a vector by a certain number or add corresponding values of two vectors together. **_Note_** the size of the vectors should be exactly the same for them to be added together. 
For example, the following three expressions are exactly the same,
```
c(1, 2, 3) + c(4, 5, 6)
c(1+4, 2+5, 3+6)
c(5, 7, 9)
```
You can do the calculations using the variables that represent vectors.
```
a <- c(1, 2, 3)
b <- c(4, 5, 6)
a + b
```

`@instructions`
Create the vector ```x``` that contains numbers 5, 8 and 10. Create the vector ```y``` that contains numbers 4, 6, and 10. Create the vector ```z``` that is the sum of ```x``` and ```y```. To add the elements, use the variables representing the vectors.
Notice how each element of ```x``` is added to its corresponding element of ```y``` to make their corresponding element of ```z```.

`@hint`


`@pre_exercise_code`
```{r}

```

`@sample_code`
```{r}
# Create the vector x
x <- 

# Create the vector y
y <- 

# Create the vector z
z <- 


```

`@solution`
```{r}
x <- c(5, 8, 10)
y <- c(4, 6, 10)
z <- c(9, 14, 20)
```

`@sct`
```{r}
ex() %>% check_object("x") %>% check_equal()
ex() %>% check_object("y") %>% check_equal()
ex() %>% check_object("z") %>% check_equal()
success_msg("Well done!")
```

---

## Copy of Working with Vectors

```yaml
type: NormalExercise
key: 6fe1f9a68c
xp: 100
```

You can add the sum of the elements of a vector using the function ```sum()```. For instance, ```sum(a)``` will add the values of the elements stored in the vector.

`@instructions`
Create the vector ```x``` that contains numbers 5, 8 and 10. Defind the variable ```z``` as the sum of the elements of ```x```.

`@hint`


`@pre_exercise_code`
```{r}

```

`@sample_code`
```{r}
# Create the vector x
x <- 

# Create the variable z
z <-

```

`@solution`
```{r}
x <- c(5, 8, 10)
z <- sum(x)
```

`@sct`
```{r}
ex() %>% check_object("x") %>% check_equal()
ex() %>% check_object("z") %>% check_equal()
success_msg("Well done!")
```
