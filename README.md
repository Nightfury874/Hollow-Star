# Hollow-Star
Printing the Hollow star in C, C++ and Python
## In C 
Input number of rows to print from user.<p/>Store it in a variable say rows.
To iterate through rows run an outer loop from 1 to rows. The loop structure should look like for(i=1; i<=rows; i++).
To print spaces, run an inner loop from i to rows - 1. The loop structure should look like for(j=i; j<rows; j++). Inside this loop print single space.
To print star, run another inner loop from 1 to i * 2 - 1. The loop structure should look like for(j=1; j<=(i*2-1); j++). Inside this loop print star for ith or last column or for last row.
After printing all columns of a row, move to next line i.e. print new line.
