### Name : S Mohamed Ahsan
### Reg No : 212223240089
# Experiment-4 ARMSTRONG NUMBER 
## Aim: 
Write a python program to check the number is Armstrong number or not and inspect for failures. 

## Algorithm
1.	Start the program.
2. Read an integer input number.
3. Initialize the variables current_digit, sum = 0, and num = number.
4. Repeat Steps 5 to 7 until num > 0
5. current_digit = (num % 10).
6. sum = sum + (current_digit * current_digit * current_digit). 7. Stop the program.
7. num = num / 10.
8. Check if sum == number. If true, print "It is an Armstrong Number." Otherwise, print "It is not an Armstrong Number."
9. Stop the program. 

## Program
```python
num=int(input("Ente a anumber :"))
power=len(str(num))
total=sum(int(digit)**power for digit in str(num))
if num==total:
    print(num,"is an Armstrong number")
else:
    print(num,"is not an Armstrong number")
```
## Output
<img width="535" height="219" alt="image" src="https://github.com/user-attachments/assets/51a238e4-8076-49f5-be83-8309828c5392" />

## Result
Thus, the python program to find an Armstrong number has been executed successfully.
