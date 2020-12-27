# Hollow-Star
Printing the Hollow star in C, C++ and Python
## In C 
Input number of rows to print from user.<p/>Store it in a variable say rows.<p/>
To iterate through rows run an outer loop from 1 to rows.<p/> The loop structure should look like for(i=1; i<=rows; i++).<p/>
To print spaces, run an inner loop from i to rows - 1.<p/> The loop structure should look like for(j=i; j<rows; j++).<p/> Inside this loop print single space.<p/>
To print star, run another inner loop from 1 to i * 2 - 1.<p/> The loop structure should look like for(j=1; j<=(i*2-1); j++).<p/> Inside this loop print star for ith or last column or for last row.<p/>
After printing all columns of a row, move to next line i.e. print new line.
<p/>
![01](01.PNG)
## In C++
The pattern is similar to pyramid pattern.<p/> The only difference is, we will replace all internal ‘#’ characters by space character and we will 2*N-1 (N = number of rows in pattern) ‘*’ characters in last row.
