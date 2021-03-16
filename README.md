# Functions 1


## In a folder labeled as "functions1" inside github upload the next scripts (the scripts must run in repl.it ) NOTE: just upload the link to your github folder (2 points each one) 
### 1.-create a function that receives a string and print the inverted string, remember that to print an element i you can use printf("%c",string[i]); 

```python
def reverse(s): 
  str = "" 
  for i in s: 
    str = i + str
  return str
```

### 2.-create a function that returns 0 if both have the same length and 1 if is different.
```python
def no(l1, l2):
    if not l1 and not l2:
        return True

    if len(l1) != len(l2):
        return (0)
 elif (no)

   
    return no(l1, l2)
```
### 4.-create a function where you insert a string and return 1 if is palindromic or not, it means that returns 1 if is palindrome ("ala"), return 0 if is not ("hello")
```python
igual, aux = 0, 0
text = input("Enter the word you want to evaluater: ")
for ind in reversed(range(0, len(text))):
  if text[ind].lower() == text[aux].lower():
    igual += 1
  aux += 1
if len(text) == igual:
  print("ala")
else:
  print("hello")

```

### 5.-create a function where you enter a string of 30 chars and print only the consonants

```python
def countCharacterType(str): 
  
    consonant =0
   
    for i in range(30, len(str)):  
          
        ch = str[i]  
  
        if ( (ch >= 'a' and ch <= 'z') or 
             (ch >= 'A' and ch <= 'Z') ):  
 
            ch = ch.lower() 
  
            if (ch == 'a' or ch == 'e' or ch == 'i' 
                        or ch == 'o' or ch == 'u'): 
                 consonant += 0
            else: 
                consonant += 1
          
    print("Consonant:", consonant)  
```



# The second part is from this week: In another folder "functions2" upload your version of the python and C versions of the first 12 examples in the page https://www.w3resource.com/python-exercises/python-functions-exercises.php labeled as "ex01.c" or "ex01.py", the C versions hold for 1 point and the python versions hold for 1 point each one. 

## ex01.c

```c
#include <stdio.h>
#include <stdlib.h>
biggestNumber(int,int,int);
int main()
{
    int a,b,c;
    printf("Enter the three numbers\n");
    scanf("%d%d%d",&a,&b,&c);

 
int biggestNumber(int a,int b,int c){
if(a>b)
{
    if(a>c)
    return a;
    else
        return c;
}
else
{
    if(b>c)
        return b;
    else
        return c;
}
}

```
## ex01.py

```python
def max_of_two( a, b ):
    if a > b:
        return a
    return b
def max_of_three( a, b, c ):
    return max_of_two( a, max_of_two( b, c ) )
print(max_of_three(1, 2, 3))
```
## ex02.c

```c
#include <stdio.h>
#include <stdlib.h>
 

int sum(int arr[], int n)
{
    int sum = 0; 
 
   
    for (int i = 0; i < n; i++)
    sum += arr[i];
 
    return sum;
}
 
```
## ex02.py

```python
def sum(numbers):
    total = 0
    for x in numbers:
        total += x
    return total
print(sum((numbers)))

```

## ex03.c
```c
#include <stdio.h>

int main()
{
    int i, num;

    do
    {
        printf( "\n  Enter a whole number: ", 163 );
        scanf( "%d", &numero )

        for ( i = 1 ; i <= 10 ; i++ )
            printf( "\n   %d * %d = %d", i, num, i * num );
    return 0;
}
```
## ex03.py
```python
def multiply(numbers):  
    total = 1
    for x in numbers:
        total *= x  
    return total  
print(multiply((1, 2, 3, 4, 5, 6)))
```
## ex04.py
```python
def string_reverse(str1):

    rstr1 = ''
    index = len(str1)
    while index > 0:
        rstr1 += str1[ index - 1 ]
        index = index - 1
    return rstr1
print(string_reverse('1234abcd'))

```
## ex04.c
```c
#include <iostream>
#include <cstring>

using namespace std;

void inv (char cad[], int wide)
{
    int wide2=wide;
    char inv[wide2];

    for (int x=0, y=wide; x<wide && y>=0; x++, y--)
    {
        inv[x]=cadena[y];
    }
    cout<<"> "<<cadena<<endl;
    cout<<endl<<"> "<<inv<<endl<<endl;
    return;
}

int main ()
{

    char opcion;
    string word;
    int long, long2;

    while (opcion!='n')
    {
        system ("cls");
        cout<<"> Ejercicio 6"<<endl<<endl;
        cout<<"> Ingrese una palabra: ";
        cin>>palabra;
        longitud=palabra.length();

        char cadena[palabra.size()+1];
        strcpy(cadena, palabra.c_str());

        longitud2=strlen(cadena);

        invertidor (cadena,long2);

    return 0;
}
```
## ex05.py
```python
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n-1)
n=int(input("Input a number to compute the factiorial : "))
print(factorial(n))
```

## ex05.c
```c

```

## ex06.py
```python
def test_range(n):
    if n in range(1,11):
        print( " %s is in the range"(n))
    else :
        print("The number is outside the range.")
 return(0)
```

## ex06.c
```c

```

## ex07.py
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

```

## ex07.c
```c

```

## ex08.py
```python

```

## ex08.c
```c

```

## ex09.py
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

## ex09.c
```c
#include<stdio.h>  
int main(){    
int n,i,m=0,flag=0;    
printf("Enter the number to check prime:");    
scanf("%d",&n);    
m=n/2;    
for(i=2;i<=m;i++)    
{    
if(n%i==0)    
{    
printf("Number is not prime");    
flag=1;    
break;    
}    
}    
if(flag==0)    
printf("Number is prime");     
return 0;  
 }    
```

## ex10.py
```python

```

## ex10.c
```c

```

## ex11.py
```python
def perfect_number(n):
    sum = 0
    for x in range(1, n):
        if n % x == 0:
            sum += x
    return sum == n
print(perfect_number(6))
```

## ex11.c
```c
# include <stdio.h>   

int main()   
{   
 int i, Number, Sum = 0 ;   
  
 printf("\n Please Enter any number \n") ;   
 scanf("%d", &Number) ;   
 
 for(i = 1 ; i < Number ; i++)   
  {   
   if(Number % i == 0)   
     Sum = Sum + i ;   
  }    

 if (Sum == Number)   
    printf("\n %d is a Perfect Number", Number) ;   
 else   
    printf("\n%d is not the Perfect Number", Number) ;   

return 0 ;   
}

```

## ex12.py
```python
int i;
  int len=strlen(string);
  for(i=len-1; i>=0; i--){
    if(string[len-i-1]!=string[i]){
      return 0;
    }
  }
  return 1;
}

int function1(char string[MAX])
{
  int length1 = strlen()
}


int main(void) {
  char mystring1[MAX] = "This is a string";
  char mystring2[MAX] = "a string";
  printf("the value for string 1 is %lu and len10 result is %d \n",strlen(mystring1),len10(mystring1));
  printf("the value for string 2 is %lu and len10 result is %d \n",strlen(mystring2),len10(mystring2));

  reverse_string(mystring1);
  printf("the value of palindrome is %d\n",palindrome("01210"));

  return 0;
}
```

## ex12.c
```c

```



