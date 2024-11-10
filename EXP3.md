# Ex.No: 3 To check the number is prime or not and inspect for failures.
 -
### DATE: 27-08-2024                                                                           
### REGISTER NUMBER : 212222040115

### AIM: 
Write a python program to check the number is prime or not and inspect for failures.
 
### Algorithm:
1. Start the program.
2. Get the number to be checked from the user.
3. If the number is less than or equal to 1, return "Not Prime".
4. If the number is 2, return "Prime".
5. Start the iteration from 3, For each iteration:
6. If the number is divisible by the current iteration value, return "Not Prime".
7. If the number is not divisible by any value from 2 to the square root, return "Prime".
8. Stop the program.

### Program:
```
num = input()

flag = 0

# Check if the input is numeric
if num.isnumeric():
    z = int(num)

    # Special case for number 2
    if z == 2:
        flag = 1

    # For numbers greater than 2
    elif z > 2:
        for i in range(2, z // 2 + 1):  # Loop from 2 to z//2
            if z % i == 0:  # If divisible, it's not prime
                flag = 0
                break
        else:  # If no factors were found, it's prime
            flag = 1

    # Check the flag to determine if it's prime
    if flag == 1:
        print("Prime Number")
    else:
        print("Not a Prime Number")
else:
    print("Enter a Positive Number")

```




### Output:

![STL EX03 OUTPUT](https://github.com/user-attachments/assets/857283d8-57fe-4321-8e96-c9387ef6e6d0)


### Result:
Thus, the python program to check the number is prime or not is implemented and the output is verified successfully.
