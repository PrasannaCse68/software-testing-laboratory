# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE:                                                                           
### REGISTER NUMBER : 212222040013

### AIM:  
To write python programs for do…while, while, for, switch and if…else and test with possible test 
Cases 

### Algorithm:
1. Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4.  the program with possible test cases.
5. Stop the program.
### Program:

### i.)do…while: 

```
def display():
     start=input("Enter a positive value for START: ")
      end=input("Enter a positive value for END: ")
      if start.isnumeric() and end.isnumeric():
        while True:
            start=int(start)
            end=int(end)
            print(start,end=‘ ‘)
            if start<end:
                start+=1
            else:
                break
      else:
        print("Enter a valid positive number.") 
  display() 
```

### ii.) while…do 

```
start=input("Enter a positive value for START: ") 
end=input("Enter a positive value for END: ")
if start.isnumeric() and end.isnumeric():
     start=int(start)
     end=int(end)
     while start<end:
          print(start)
          start+=1
else:
   print("Enter a valid positive number.")

```

### iii.) switch 

```
def switch():
    switcher={
 0:"even",
  1:"odd"
}
n=input('Enter a value for N: ') try:
  n=int(n)
  print(switcher[n%2])
except ValueError:
   print("Enter a valid number.")
switch() 

```

### iv.) if else

```
def compare():
  a=input("Enter a value for A: ")
  b=input("Enter a value for B: ")
  try:
     a=int(a)
     b=int(b)
     if a>b:
        print("A is greater than")
     elif a<b:
        print("B is greater than")
     else:
        print("A is equal to B")
  except ValueError:
        print(“Enter a valid number.”) 

```

### v.) for

```
def iterate():
    string=input("Enter a string: ") for
    i in string:
       print(ord(i),end=" ")
iterate() 
```





### Output:

### i.)do…while: 
![image](https://github.com/user-attachments/assets/3e2f05cf-21ea-4da6-92bd-50e87b81c080)



### ii.) while…do 
![image](https://github.com/user-attachments/assets/97e5d742-8bb4-48fc-bf90-e4faba76265f)



### iii.) switch 
![image](https://github.com/user-attachments/assets/c10589a1-0ac1-4afd-9d5a-ca00b43e5959)


### iv.) if else
![image](https://github.com/user-attachments/assets/322feb67-b8ab-443b-b343-67c023301877)



### v.) for 
![image](https://github.com/user-attachments/assets/29c5278c-2377-489e-96e3-33542f51da09)






### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.
