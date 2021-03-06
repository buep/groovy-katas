# Closures (basic)

## Defining and calling closures

Define a closure that prints `Hello, world!` and call it.

- Run `groovy exercise.groovy`
- Assert `Hello, world!` was printed correctly

## Parameterized closures

Define a closure that takes two numbers, multiplies them and returns the result.

Call the closure with parameters `3` and `7`, store the result in a variable and print it.

- Run `groovy exercise.groovy`
- Assert the printed result is corrected

## Closure scope

Define a variable `prefix`, containing a simple string value.
Define a closure that takes a string argument, and prints it prefixed with the `prefix` variable.

Call the closure with value `Hello!`.

- Q: Will the closure be able to access the value of `prefix`? Why (not)?
- Run `groovy exercise.groovy`
- Q: Was the output as expected?

<br>
<br>

_Recommended continuation: *collections/intermediate*_
