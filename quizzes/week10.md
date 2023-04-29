# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
The namespace keyword is used to declare a scope that contains a set of related objects. This allows us to have different namespaces where we can use the same naming conventions without overlap. If no namespace is declared, global namespace is the default.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
Structs are value type and classes are reference type. If a struct is copied into another variable, the entire value of that struct is passed. However, if a class is copied into another variable, it's simply the reference to the class that is passed. This means that if we alter that secondary variable, we are also altering the value of the class itself. Additionally, classes support inheritance while structs do not.
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
A constructor returns an instance of a class with no declared return type.
```
## Example 1
```c#
abstract class Car
{
  ...
  public virtual string Start()
  {
    return "Vroooom";
  }
}
```
**5.** In the example what is the access modifier of the `Start()` method?
<!-- enter you answer in the space below -->
```
"public"
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
It's an indication of the data type of the return for the Start() function.
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
An abstract class cannot be used to create objects, it can only be inherited from another class to be utilized.
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
The virtual is essentially a default function, but it can be overridden in a child class if that keyword is used. So the Start() function could be accessed by a class that has inherited the Car class. If the Start() method is called on that sub-class, it would return "Vroooom". However, we could write a new method called Start() in the sub-class that would then override the Start() in the car-class.
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
Private - These methods can only be accessed from within the same class or struct.
Public - These methods can be accessed from anywhere.
Internal - These methods can only be accessed from within the same assembly.
Protected - These methods can only be accessed from within the same class or a derived class.
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
If a method is set to private, it can only be accessed by functions of the same class. Even an instance of a class cannot access its private members.
```