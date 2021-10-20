# Style Guide

### Naming
Directory in PascalCase  
Namespaces in PascalCase  
Classes and types in PascalCase  
Interfaces in IPascalCase (I before the name in PascalCase)  
Enum values in SCREAMING_SNAKE_CASE ( ´･ω･)  
Function / Medthods in PascalCase  
Public attributes in PascalCase  
Public properties (getters and setters) in PascalCase  
Private / Local attributes in camelCase  
    
Blank one line between each methods and properties  
Blank one line between the attribute declerations and the methods' and the properties' declearation  
The order of declearations are as follow: attributes, operator overloads, properties, methods  
Put spaces between operators (such as `a + b`) and space after a comma in a list-like structure (`add(1, 2)`)  
Put a space before and after the content with in the `{}` when it's only in 1 line (`{ return 1; }`).
  
Don't change line with `{}`
You can put a space before the `{` if you want, be consistent in the same file.  
Indentation size is 4, using tabs  
**Above styles are not forced, but recommended.**

```c#
namespace Foo {
    class Bar {
        public int Id;
        public String Name;
        private int age;

        public int Age {
            get { return age; }
            set { this.age = value; }
        }

        public void DisplayData() {
            console.out.writeline(
                "ID: " + this.id.toString() + 
                "Name: " + this.Name + 
                "Age: " + this.age.toString()
            );
        }
    }
}
```