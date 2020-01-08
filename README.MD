--- Understanding the Java Class Structure

```cpp
class Animal
{
    public:
        string getName() {
            return name;
        }
 
        setName(string newName)
        {
            name = newName;
        }
 
    private:
        string name;
};

```

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

```python
class Animal: 
    def __init__(self, name): 
         self._name = name 
     
    def get_name(self): 
        return self._name 
     
    def set_name(self, name): 
        self._name = name 
```