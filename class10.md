# JavaScript book, Ch. 10, “Error Handling & Debugging”:

If you understand execution contexts (which have two
stages) and stacks, you are more likely to find the error
in your code.
Debugging is the process of finding errors. It involves a
process of deduction.
The console helps narrow down the area in which the
error is located, so you can try to find the exact error.
JavaScript has 7 different types of errors. Each creates
its own error object, which can tell you its line number
and gives a description of the error.
If you know that you may get an error, you can handle
it gracefully using the try, catch, finally statements.
Use them to give your users helpful feedback.


## error objects types:


**Syntax Error**
DESCRIPTION
Generic error - the other errors
are all based upon this error.


**Syntax error**
  syntax has not been followed.


**ReferenceError**
 Tried to reference a variable that is
not declared/within scope.


**Type error**
An unexpected data type that
cannot be coerced.

**Range Error**
Numbers not in acceptable range.

**URI Error**
encodeURI ().decodeURI(),and
similar methods used incorrectly.

**EvalError**
eva l () function used incorrectly.




