# setting up

you'll need to add `-g` and `-O0` to your `make`

# Using

We want to:
- detect all leaks
- write output to logfile

`valgrind --leak-check=yes --show-leak-kinds=all -v -logfile="logfile.txt"  ./np -r 2 -X 100 -Y 100`








# references

1. [quick start](https://valgrind.org/docs/manual/quick-start.html)
