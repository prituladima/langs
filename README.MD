Language difference in same problems
===================   
# Class Structure #

## Fields and Methods ##

### C++ ###
```cpp
class Animal
{
    private:
        string name;
    public:
        string getName() {
            return name;
        }
 
        setName(string newName)
        {
            name = newName;
        }
};

```

### Java ###
```java
public class Animal {
    String name;
    public String getName() {
        return name;
    }
    public void setName(String newName) {
        name = newName;
    }
}
```

### Python ###
```python
class Animal: 
    def __init__(self, name): 
         self._name = name 
     
    def get_name(self): 
        return self._name 
     
    def set_name(self, name): 
        self._name = name 
```

## End point ##

### C++ ###
```cpp
#include <iostream>
using namespace std;
int main() 
{
    cout << "Hello, World!";
    return 0;
}
```

### Java ###
```java
public class Main {
    public static void main(String[] args) {
        System.out.println("Hello, World");
    }
}
```

### Python ###
```python
print("Hello, World!")
```


## Understanding Package Declarations and Imports ##

### C++ ###
```cpp
#include <stdio.h>      /* printf, scanf, puts, NULL */
#include <stdlib.h>     /* srand, rand */
#include <time.h>       /* time */
#include <iostream>

using namespace std;

int main ()
{
  /* initialize random seed: */
  srand (time(NULL));

  /* generate secret number between 1 and 10: */
  cout <<  rand() % 10 + 1;

  return 0;
}
```

### Java ###
```java
import java.util.Random;
public class ImportExample {
    public static void main(String[] args) {
        Random r = new Random(); 
        System.out.println(r.nextInt(10));
    }
}
```

### Python ###
```python
import mathematics 
print(mathematics.pi) 
randrange(10) # Integer from 0 to 9 inclusive
```

## Creating Objects ##

### C++ ###
```cpp
Animal aninal(); 
```

### Java ###
```java
Animal animal = new Animal();
```

### Python ###
```python
p1 = Animal()
print(p1.get_name())
```

## Null pointer ##

### C++ ###
```cpp
Animal animal;
Animal *animalPointer = &animal;
animalPointer = NULL; 
animalPointer = 0; 
animalPointer = nullptr; 
```

### Java ###
```java
Animal animal = null;
```

### Python ###
```python
animal = None
```

## Operators ##
Google them

## Statements ##

### C++ and Java ###
```cpp
int a = 200
int b = 33
if (b > a)
{
  print("b is greater than a")
}
else if (a == b)
{
  print("a and b are equal")
}
else
{
  print("a is greater than b")
}

```

### Python ###
```python
a = 200
b = 33
if b > a:
  print("b is greater than a")
elif a == b:
  print("a and b are equal")
else:
  print("a is greater than b")

primes = [2, 3, 5, 7]
for prime in primes:
    print(prime)

# Prints out the numbers 0,1,2,3,4
for x in range(5):
    print(x)

# Prints out 3,4,5
for x in range(3, 6):
    print(x)

# Prints out 3,5,7
for x in range(3, 8, 2):
    print(x)

# Prints out 0,1,2,3,4

count = 0
while count < 5:
    print(count)
    count += 1  # This is the same as count = count + 1

# Prints out 0,1,2,3,4

count = 0
while True:
    print(count)
    count += 1
    if count >= 5:
        break

# Prints out only odd numbers - 1,3,5,7,9
for x in range(10):
    # Check if x is even
    if x % 2 == 0:
        continue
    print(x)
```
Info from:
https://www.learnpython.org/en/Loops

## Basic lang API ##
