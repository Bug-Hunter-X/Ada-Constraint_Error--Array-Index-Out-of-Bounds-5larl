# Ada Constraint_Error: Array Index Out of Bounds

This repository demonstrates a common error in Ada programming: the `Constraint_Error` that occurs when trying to access an array element using an index that is outside the defined bounds of the array.

The `bug.ada` file contains code that attempts to access an array element with an out-of-bounds index, resulting in the `Constraint_Error` exception being raised.  The `bugSolution.ada` file provides a corrected version of the code that prevents this error.

This example highlights the importance of robust input validation and bounds checking in Ada to prevent runtime exceptions.