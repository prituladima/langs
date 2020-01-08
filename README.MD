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