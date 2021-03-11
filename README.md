# Python-functions---Exercises-Practice-Solution
##6. Write a Python function to check whether a number is in a given range. 
 ```python
 
 def test_range(n):
    if n in range(1,11):
        print( " %s is in the range"(n))
    else :
        print("The number is outside the range.")
 return(0)
 
 ```
##7. Write a Python function that accepts a string and calculate the number of upper case letters and lower case letters. 
```python

def string_test(s):
    d={"upper":0, "lower":0}
    for l in s:
        if l.isupper():
           d["upper"]+=1
        elif c.islower():
           d["lower"]+=1
        else:
           pass
    print ("Original String is  : ", s)
    print ("No. of Upper characters : ", d["upper"])
    print ("No. of Lower Characters : ", d["lower"])

```

##9. Write a Python function that takes a number as a parameter and check the number is prime or not.

```python

def prime-test(n):
    if (n==1):
        return False
    elif (n==2):
        return True;
             for n in range(2,n):
            if(n % n==0):
                return False
        return True            
print(prime-test(3))

```

