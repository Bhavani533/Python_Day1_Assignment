# Python_Day1_Assignment
# Arithmetic operators
# Addition
a = 2
b = 3
print(a+b)

# Subtraction
a = 3
b = 1
print(a-b)

# Multiplication
a = 3
b = 5
print(a*b)

# Division
a = 10
b = 2
print(a/b)

# Modulus
a = 10
b = 3
print(a%b)

# Exponentiation(power)
a = 2
b = 3
print(a**b)

# Floor division
a = 10
b = 2
print(a//b)

# logical operators
# and
a = 10
b = 20
if(a>5 and b>5):
    print("The nmbers are greater than 5")
else:
    print("the numbers are not greater than 5")

# or
a = 10
b = 3
if(a>=10 or b>=10):
    print("The numbers are greter than 5")
else:
    print("The numbers are not greater than 5")
    
# not
a = 10
b = 5
if not(a==b):
    print("a is not equal to b")
else:
    print("a is equal to b")
    
# Assignment operators
# =(Assign)
a = 2
b = 3
c = a+b
print(c)
# add and assign
a = 2
b = 3
a += b
print(a)
# sub and assign
a = 5
b = 2
a -= b
print(a)
# mul and assign
a = 2
b = 5
a *= b
print(a)
# div and assign
a = 10
b = 5
a /= b
print(a)

# even or odd
# a = 5
a = 52
if(a%2==0):
    print("The number is even")
else:
    print("The number is odd")
    
# leap year
# a =2000
a = 2003
if(a%400==0 or a%100!=0 and a%4==0):
    print("It is a leap year")
else:
    print("It is not a leap year")
    
# creating list
list1 = [1,2,"Teju",2.5,3]
print(list1)
list2 = [4,8,9,"ashu",5]
# compare
print(list1 is list2)
# extend
list1.extend(list2)
print(list1)
# append
list1.append(8)
print(list1)
# pop
list1.pop(-1)
print(list1)
# insert
list2.insert(2,"Vishnu")
print(list2)

# Diff between for and while
# for
a = [1,2,3,4,5]
for i in a:
    print(i)
# while
i = 1
while i<=5:
    print(i)
    i +=1
