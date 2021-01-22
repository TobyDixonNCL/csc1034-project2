When searching for errors in this code, I started with the runtime errors. I would run the program
and play the game until I hit an error. If an error presented itself I would check the error message to see
where the error occurred. If I could identify the issue straight away, I made the fix and repeated the process
Otherwise I set a debugger breakpoint and stepped through the code with the python debugger to investigate the issue
more accurately.

Once this method of finding errors became either too tedious or stopped working, I started using pytest to check
that all the test cases were returning true. After running the tests, I would pick a test and if the issue was not
immediately obvious, I would again use the debugger to step through the code to get a more in depth look at the values
at each point throughout the code.

After these two methods were exhausted and the game was running without hiccups, I then just play tested to see if there 
were any more issues with the code that didn't raise errors. One of the errors I found using this method was that when the
program prints the winning message to the winner, it doesn't use that players name, just which ever player is at the index 
1 of the players array.

After going through and fixing errors with the code, I tried to improve the codebase to the best of my ability. The only
improvements I could come up with were replacing some for loops with list comprehensions - hence making the code more
pythonic. I also removed an if statement that seemed to have no effect.  