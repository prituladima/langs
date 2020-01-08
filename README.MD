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