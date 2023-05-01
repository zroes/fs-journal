# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
it allows us to group related types together and to specify a unique name for each type within the namespace
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
class is a reference type and struct is a value type
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
void
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
public
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
the return type
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
the abstract keyword is preventing the Car class from being instantiated directly. It indicates that the class is incomplete and requires further implementation by any derived classes
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
It allows derived classes to override the start function
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
public, private, protected, internal
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
only other methods within that same class
```