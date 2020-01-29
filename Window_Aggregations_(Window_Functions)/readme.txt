Window aggregate functions (aka window functions or windowed aggregates) are functions that perform a calculation over a group of records called window that are in some relation to the current record (i.e. can be in the same partition or frame as the current row).

In other words, when executed, a window function computes a value for each and every row in a window (per window specification).

Note:
Window functions are also called over functions due to how they are applied using over operator.

Spark SQL supports three kinds of window functions:
 - ranking functions
 - analytic functions
 - aggregate functions
