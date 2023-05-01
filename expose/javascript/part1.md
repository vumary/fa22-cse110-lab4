1. 20
2. 20
3. 20
4. The code returns an error saying that "result is not defined" and this is 
because ```result``` has variable type ```let``` which is has a blocked scope,
so it's only accessible in the block it's declared and since line 13 outside
that block, an error occurs.
5. The code returns an error because line 7 is attempting to reassign a const
variable which has already been declared as 0. This is not allowed so thus the
error.
6. Line 13 is not reached because of the error on line 9, so nothing is printed.