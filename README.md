# python-question
Question 1:- factorial


num = int(input("Enter a number: "))
factorial =1

if num < 0:
    print("numbere should be more than zero.")
elif num ==0 or num ==1:
    print(f"The factorial of {num} is 1")
else:
    i =1
    while i <=num:
        factorial *=i
        i+=1
    print(f"The factorial of {num} is {factorial}")

    

Question 2:- average number

total =0
count =10  

for i in range(count):
    num = int(input("Enter number " + str(i + 1) + ": "))
    total +=num

average =total / count
print("The average of the 10 numbers is: " + str(average))


Question 3:- Fibonacci Series

n = 10  
a = 0
b = 1

print("Fibonacci Series:")

for i in range(n):
    print(a)  
    next_no = a + b
    a = b
    b = next_no
