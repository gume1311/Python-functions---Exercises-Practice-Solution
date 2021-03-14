# Functions 1

## 1.-create a function that receives a string and print the inverted string, remember that to print an element i you can use printf("%c",string[i]); 

```python
def reverse(s): 
  str = "" 
  for i in s: 
    str = i + str
  return str
```

## 2.-create a function that returns 0 if both have the same length and 1 if is different.
```python
def no(l1, l2):
    if not l1 and not l2:
        return True

    if len(l1) != len(l2):
        return (0)
 elif (no)

   
    return no(l1, l2)
```
## 4.-create a function where you insert a string and return 1 if is palindromic or not, it means that returns 1 if is palindrome ("ala"), return 0 if is not ("hello")
```python
igual, aux = 0, 0
texto = input("Ingrese la palabra que desea evaluar: ")
for ind in reversed(range(0, len(texto))):
  if texto[ind].lower() == texto[aux].lower():
    igual += 1
  aux += 1
if len(texto) == igual:
  print("El texto es palindromo!")
else:
  print("El texto no es palindromo!")


```

## 6. Write a Python function to check whether a number is in a given range. 
 ```python
 
 def test_range(n):
    if n in range(1,11):
        print( " %s is in the range"(n))
    else :
        print("The number is outside the range.")
 return(0)
 
 ```
## 7. Write a Python function that accepts a string and calculate the number of upper case letters and lower case letters. 
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

## 9. Write a Python function that takes a number as a parameter and check the number is prime or not.

```python

def prime-test(n):
    if (n==1):
        return False
    elif (n==2):
        return True;
             for s in range(2,n):
            if(n % s==0):
                return False
        return True            
print(prime-test(3))

```

