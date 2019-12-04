Untitled
================

``` r
### R session 1

x <- 3*4
x
## [1] 12 :D  all R statements where you create objects - "assignments- have this form:
### objectName <- value
##make antoher asisgnemtn 
this_is_a_really_long_name <- 2.5
r_rocks <- 2^3
rrocks
##trying to run rrocks gets an error! now try R_rocks
R_rocks
#that fails too! because R is case sensative
r_rocks
#calling functions! 
#r has a lot of amazing built in functions accessed like so:
# functionName (arg1= val1, arg2=val2, and so on)
#lets try using the seq() function with seq(1,10) to give us numbers 1 to 10
seq(1,10)
#you can have it go by a different stepsize
seq(1,10, by=2)
#you can get help with examples
example(seq)
#not all functions have or require argument
date()
#getting help! 
help(log)
?log
#lets look at vectors! and indexing! a vector contains contiguous data. you gotta define them.
#so lets make a vector v_x
v_x <- c(56, 95.3, 0.4)
v_x
#now make a vector v_y
v_y <- c(3.2, 1.1, 0.2)
v_y
#now for some vectorization
#vectorizations allows us to loop over vectors element wise! add the two vectors we already assigned
v_x + v_y
v_x/v_y
#all operators +,-, *, sqrt(), round(), log(), all vectorized!
sqrt(v_x)
#INDEXING! GETTING INTO THE DATA TO PULL OUT WHAT YOU WANT! you can use [] to pull out what you want!
v_x[2] #will pull the second input of the vector!trying to access a element that doesn't exst will be error NA
```
