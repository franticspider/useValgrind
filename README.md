# setting up

you'll need to add `-g` and `-O0` to your `make`

# Using

We want to:
- detect all leaks
- write output to logfile

if you have an executable that runs like this:

`./np -r 2 -X 100 -Y 100`

check it with valgrind like this:

`valgrind --leak-check=yes --show-leak-kinds=all -v --log-file="logfile.txt"  ./np -r 2 -X 100 -Y 100`

# References

1. [quick start](https://valgrind.org/docs/manual/quick-start.html)
