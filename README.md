# SIMULATION-OF-MEAN-AND-VARIANCE-USING-SCILAB

## AIM:
To write a program for mean, variance and cross correlation in SCILAB and verify the output.

## EQUIPMENTS Needed

•	Computer with i3 Processor
•	SCI LAB


## Algorithm
1.	Define	the	Function:	Specify the	function	you	want	to	simulate.	For	example, f(x)=sin⁡(x)f(x) = \sin(x)f(x)=sin(x) or any other function.
2.	Generate Sample Points: Decide on the range and the number of sample points. Generate these sample points within the desired range.
3.	Evaluate the Function: Compute the function values at each of these sample points.
4.	Compute Mean, Variance and Cross Correlation: Use Scilab's functions to calculate the mean and variance of the computed function values.
5.	Display Results: Output the computed mean variance and Cross Correlation PROCEDURE
•	Refer Algorithms and write code for the experiment.
•	Open SCILAB in System
•	Type your code in New Editor
•	Save the file
•	Execute the code
•	If any Error, correct it in code and execute again
•	Verify the generated results


## PROGRAM
```ASM
a = 0;
b = 1;
k = 2;
function X = f(x)
    z = k*(1 - x)^2;
    X = x * z;        
endfunction

EX = intg(a, b, f);
disp("Mean : " + string(EX));

function X = g(x)
    z = k*(1 - x)^2;   
    X = (x^2) * z;     
endfunction

EX2 = intg(a, b, g);

var = EX2 - (EX^2);
disp("Variance : " + string(var));
```

## CALCULATION
<img width="1200" height="1600" alt="image" src="https://github.com/user-attachments/assets/63729a73-14f9-4476-97b2-de129f6baed6" />

<img width="1200" height="1600" alt="image" src="https://github.com/user-attachments/assets/9fdbe251-d1c8-4ecb-a577-34d185f8f2ef" />

## OUTPUT

<img width="876" height="100" alt="image" src="https://github.com/user-attachments/assets/3973ccee-8db1-4f74-968b-68a76b27fa0b" />

## RESULT:
Thus the mean , variance and cross correlation are executed in Scilab and output is verified.
