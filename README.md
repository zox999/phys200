# BASICS OF SCIENTIFIC COMPUTATION 
#projects I did for the course

2.1.1 C11: (1 point) Read lines and fill array
Write a program that reads a column of numbers from a file and fills in an array with these
numbers until you reach to the end of file.

2.1.3 C13: (2 points) Multiply large numbers
Multiply two 30-digit numbers not using math functions and/or libraries. Hint: The simplest
way of handling the algoritm is as follows: split each digit of these two numbers into two
arrays and cross process each digit from these two arrays (i.e two numbers) accordingly.

3.1.1 S11: (2 points) Simpson’s integration
This project is concerned with implementing a better
approximation to a numerical integral, namely the Simpson’s rule
(https://en.wikipedia.org/wiki/Simpson%27s_rule). This time, however, the code must
take in a series of predefined x and f(x) values from a file.
Instructions:
1. Your program must contain a function whose prototype is:
def simpsons(x,f):
where x is an array that contains the values of x and f is an array that contains the
values of the function. You may use the file S11.dat provided with the function.
2. You may assume that the x values are always evenly spaced.
3. The upper and lower limits of the integral are to be taken as the first and second-to-last
lines in the file (e.g. in S11.dat, x0 = 0.0 and xf = 2.0).
4. In the main body of your function, you should read a file that contains x and f values as
two columns, convert them into two arrays, x and f and call the function simpson.


3.3.2 S32: (3 points) Charged point particles
Calculate the electric field of a collection of point charges at a given point in 3D space.
Instructions:
1. This problem deals with an arbitrary number of point charges distributed in
three-dimensional space, creating a total electric field at a given point, P (see figure
below).
2. Your code should read a file, S32.dat that contains three columns, which are, in order,
the charge of each point particle, and their three coordinates.
3. Your code should ask the user for the coordinates of point P.
4. Your code should contain a function efield(q,r1,r2) that calculates the eletric field
created at point r2 by a point particle of charge q, located at r1.
5. The main body of your code should then call this function many times in a loop to
calculate the total electric field.
6. The length of S32.dat is arbitrary so your code should be able to handle any number of
charges.
7. The charges can be positive and negative.
8. Your code should print on screen the three components of the resultant electric field
vector at point P. NOTE that this is just three numbers.
