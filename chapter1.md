	--- type:NormalExercise lang:r xp:100 skills:1
	## Calculate the mean

	In this exercise, you'll be calculating a mean.

	*** =instructions
	- Create a variable `m`, equal to the mean of the numbers 0 up to 9.
	- Print out `m`.

	*** =hint
	- You can use `mean(0:9)` to calculate `m`.
	- To print out a variable, simply write the variable name on a new line.

	*** =pre_exercise_code
	```{r}
	# no pre exercise code required
	```

	*** =sample_code
	```{r}
	# Calculate the mean of all single digit numbers and assign the result to 'm'


	# print the result to the console

	```

	*** =solution
	```{r}
	# Calculate the mean of all single digit numbers and assign the result to 'm'
	m <- mean(0:9)

	# print the result to the console
	m
	```

	*** =sct
	```{r}
	test_function("mean", args = "x")
	test_object("m")
	test_output_contains("m")
	test_error()
	success_msg("Great job!")
	```
