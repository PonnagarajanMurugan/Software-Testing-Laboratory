# Ex.No: 4 check the given number is Armstrong number or not and inspect for failures.
### DATE:                                                                            
### REGISTER NUMBER : 212222040115
### AIM: 
Write a python program to check the number is Armstrong number or not and inspect for failures.

### Algorithm:
1.  Start the program.
2.	Read an integer input number.
3.	Initialize the variables current_digit, sum = 0, and num = number.
4.	Repeat Steps 5 to 7 until num > 0
5.	current_digit = (num % 10).
6.	sum = sum + (current_digit * current_digit * current_digit). 7. Stop the program.
7.	num = num / 10.
8.	Check if sum == number. If true, print "It is an Armstrong Number." Otherwise, print "It is not an Armstrong Number."
9.	Stop the program.

### Program:
```
x = input("Enter the input: ")

if x.isnumeric(): 
    x = int(x)
    temp = x
    cube = 0

    while temp > 0: 
        digit = temp % 10
        cube = cube + (digit ** 3)
        temp //= 10

    if cube == x: 
        print("Armstrong Number")
    else: 
        print("Not Armstrong Number")
else: 
    print("Enter a Positive Integer.")

```

### Output:

```
PS C:\Users\SEC\Desktop\web\exp2> python -u "c:\Users\SEC\Desktop\web\exp2\exp4.py"
Enter the input: 143
Not Armstrong Number

PS C:\Users\SEC\Desktop\web\exp2> python -u "c:\Users\SEC\Desktop\web\exp2\exp4.py"
Enter the input: 153
Armstrong Number

PS C:\Users\SEC\Desktop\web\exp2> python -u "c:\Users\SEC\Desktop\web\exp2\exp4.py"
Enter the input: -25
Enter a Positive Integer.

PS C:\Users\SEC\Desktop\web\exp2> python -u "c:\Users\SEC\Desktop\web\exp2\exp4.py"
Enter the input: -10
Enter a Positive Integer.

PS C:\Users\SEC\Desktop\web\exp2> python -u "c:\Users\SEC\Desktop\web\exp2\exp4.py"
Enter the input: 1
Armstrong Number

PS C:\Users\SEC\Desktop\web\exp2> python -u "c:\Users\SEC\Desktop\web\exp2\exp4.py"
Enter the input:  
Enter a Positive Integer.

PS C:\Users\SEC\Desktop\web\exp2> python -u "c:\Users\SEC\Desktop\web\exp2\exp4.py"
Enter the input: sh
Enter a Positive Integer.
```




### Result:
Thus, the python program to check the number is Armstrong number or not implemented and the output is verified successfully.


