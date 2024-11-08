java c
Assignment for MATLAB Workshop 
Due date: November 9, 2024 at 11:00 pm 
Q1 Solving function Matlab can be used to solve the numerical result of a function, and its differential and integration. We can first create a “function file” to present this function f(x), which returns the corresponding output for a given input. In this question, your task is to fill the function file.
Please do not modify any code in “Q1.m”. 
1.1 Define the function to be solved.We  have  a  completed  function  f(x) = x * J1 (x) — 2ln[0.7sin(x) + 0.86]   to   be solved, where J1 (x)  is the Bessel function of the first kind. We first need to define this function on Matlab by writing a “m file”, whose input is “x” and output is “f(x)” .
TASK ONE (10%) Your task is to fill the file “f.m” corresponding to above function. After you have finished it, running the “Q1.m”, you are expected to see the followed information on the Command Window.
Exact y list: 



3.0515 
0.3016 
-0.3017 1.1958 

Your result: 



3.0515 
0.3016 
-0.3017 1.1958 
1.2 Plot the figure off(x).
Then we can plot the figure of f(x). We set the x range from -5 to 5, then compute the corresponding f(x). Continue “Q1.m”, you can see

the figure.
1.3 Compute differential value off(x).
We can solve the differential value off(x) on  x0   by first obtaining the form. f ′ (x) then computing f ′ (x0). An alternative method is shown as  which can be used for complicated unknown functions.
TASK TWO (20%) 
Your task is to fill the file “diff_f.m”, which solve the approximate differential value  off(x) on given “x” by above numerical method. After you have finished it, continue the “Q1.m”, you are expected to see the followed information. Here the accuracy   is dependent to that you chose.
Exact differential result: 0.665414
Your differential result: 0.665414
1.4 Compute integral value off(x).
For this function, it is difficult to write the integration form. We can use the numerical method that separate this integration to a discrete summation. To solve the integration off(x) from  xi   to  xf , we can cut the range into lots of pieces    {xi, xi  + △x, xi  + 2△x, … , xf} , and solve the corresponding f(x). Finally, we 代 写Assignment for MATLAB WorkshopMatlab
代做程序编程语言can obtain the approximate integral value by adding them up and multiplying  △x . 
TASK THREE (20%) Your task is to fill the file“integral_f.m”, whose input is“x_i”and“x_f”and output is integral value of f(x) from“x_i”to“x_f”. You are expected to see the followed information. Here the accuracy is dependent to that you chose.
Exact integral result: -0.026055
Your integral result: -0.026055
Q2. Axes rotation
Rotating the x-y axes counterclockwise through into x’-y’axes can be represented as  where  is the original coordinate and  is the new coordinate after rotation. In this equation, we will plot the function  y  = x 2  +
5sin(3x) + cosh(x) − 1  at the original axes and the axes that being rotated counterclockwise through  
2.1 Build the function.
TASK ONE (15%) 
Your task is to finish the file ‘g.m’ , in which the input a vector  x(⃗) =
{x1, x2, … , xn }containing a set of values of x and the output is a vector
= {x1(2), x2(2), … , xn(2)}. After finished it, running Q2, you are expected to see that at the
Command Window.
x         y     exact_y
-2.0000     -7.4724     -7.4724
0     -0.5211     -0.5211
2.0000       3.5515       3.5515
2.2 Plot this function
We set the x range from -5 to 5, and the corresponding y values are obtained from y = 5xsin(3x) − sinh(x + 0.5). In this part, we will plot the function from -5 to 5.
TASK TWO ( 20% )
Your task is to finish the file plot_function.m, which will plot x-y figure with input  x(→) ,  y(→) . The requirements are as followed.
1. line width is 2;
2. line color is black;
3. title is "y = 5xcos(3x)-sinh(x+0.5)";
4. x-label is "x";
5. y-label is “y".
You are expected to see that.

2.3 Rotation axes
In this part, we will rotate the axes counterclockwise through  −4/3π and plot the new
function in the new axes.
TASK THREE (15%) 
Your task is to finish the file rotation.m. The input is the coordinate information at the original axes x, y, and the angle to be rotate θ . The output is the coordinate information at the new axes x’ and y’ . Hint: you can use matrix product to map the coordinate of every point. You are expected to see that. 









         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
