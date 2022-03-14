![debuggin tool image](https://www.edureka.co/blog/wp-content/uploads/2019/08/hero-snapshot-debugger-300x165.png)

## What is debugging?
-	A process we do using a debugging tool to figure out where exactly we made a programming mistake by running the code step by step.

## What should you do when you find the point that has the error?
-	You should ask yourself the right question in order to understand what correction can you do to solve the problem. You have to think of the assumptions that led to the error


The questions should be like: 
-	What did you expect your code to do?
-	What happened instead?
-	Am I using this API right?
-	Is there any typos?

## Try and Catch
We can use try and catch if we expect an error to occur, so that if it does, we can handle it and continue executing the code. Also, while specifying exceptions, we should begin with the most specific, then move on to the less specific, and so on...

Exceptions not handled by catch blocks are caught by the Common Language Runtime (CLR). Depending on your CLR setting, one of the following outcomes may occur:

-	A dialog box for debugging appears.
-	The application stops and displays an error message in a dialog box.
-	The standard error output stream receives an error.

## Importance of debugging
One of the examples that shows the impact of bad debugging is the Therac-25 machine.

The Therac-25 was a cutting-edge linear accelerator that delivered radiation therapy to cancer patients. The Therac-25 was the most advanced and computerized radiation therapy system available at the time.
Six occurrences involving substantial dosages of radiation to patients have unfortunately resulted in death.
Patients said they were "burned by the equipment," which some technicians claimed but the firm dismissed.

As you read above, debugging is a critical stage every developer should take it seriously because in the case of medical devices and programs it could lead to people death.




