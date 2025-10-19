This project is intrest in Data mining that focused on Smoothing data using Smoothing techniques .
First we add arrays of number to smooth it and we import numpy lib to use mathematical functions .
I had been use section in comment if you want to add number as you want , if you not cares about it you can view the rest of the details in the code.
Second thing that we sorted the array ascending by default then we create an array to divide data in it then we store the size of bin in variable named by size .
So if you want to change the size of group modify it this variable 
Create for loop to divide array in to group and each group contain size then create another for loop to print the groups as bins .
Create fuction to divide array .. 
Later on you understand why we create this fuction .
Now we will found mean and median using functions mean(),median() and we will find boundaries using spetial equation . We use array for each function to store data in it then create for loop and use method 'extend()' to store the value in the array that had been created ,we use method 'ceil()' to near the number for the up ,create variable named bu min_value to store the minimum value in it by using method 'min()',create variable named bu max_value to store the maximum value in it by using method 'max()',substract minimum value from bin(elements of bins) and substract maximum value from ,bin(elements of bins)to know the difference between number if the  deference of minimum value ,less than maximum value return min_value else return maximum value.
Create count because when i print the statement show number of bin ,use for loop print element from i to the size that have been defined above and recurrent it for 3 methods that we have covered .

We using Jupyter Notebook to run and test the code .
