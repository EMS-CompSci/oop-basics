# oop-basics
# Concepts

Relationship between **class**es and **object**s.<br>
How the **constructor** method creates objects.<br>
The use of **method**s to manipulate **attributes**.<br>
Purpose of **access modifiers** **private** and **public** [^1].<br>
The manipulation or interrogation of objects with **methods**.<br>

You learn through practice with the code in this file.
1. Read the code, trying yo figure out what each line achieves.
2. Add comments.
3. Run the file, by pressing Ctrl+Shift+B.
4. Change some of the code, for example location of brakets and size of indents. Find out what your stylistic preference is.
Modify the program:
1. Add more point objects.
2. Change the access modifiers to public and use the 'dot' notation to change the attributes.
2. Add methods to the Point class, for example distanceTo, which should have the following **signature**. Please note that AQA uses the term function interface.
**Point distanceTo(Point otherPoint)**


## Key vocabulary

| Term | Definition |
|------|---------|
| Class | A structure which bundles data and operations on the data. It can be considered a blueprint for creating objects.  |
| Object | A specific instance of a class. |
| Instantiation | The process of creating an object from a class byb invoking the contructor of the class. |
| Attribute | The data which belongs to a class. |
| Method | A function which belongs to a class. |
| Constructor | A special method that is called in when an object is created. |
| Encapsulation | The concept of bundling data and together with operations on the data. |
| Information Hiding | Stronger form of encapsulation, where access to attributes or methods is limited. |
| Getter | A method which returns attributes. |
| Setter | A method which changes attributes. |



## Reflection

1. What is the difference between a class and an object?
     Use Point as your example.

  2. What does 'private' mean? Why is it useful?
     What would go wrong if x and y were public?

  3. Why does the constructor have no return type?

  4. What does 'const' mean on a method?
     Why is it correct for getX() but wrong for a setter?

  5. p1 and p2 are both Points. Do they share the same x
     and y variables, or do they each have their own?
     How can you tell?

## Potentially new oncepts not related to OOP

Working in the terminal.
Namespace.
Building a program.

[^1] The concept of **protected** access modifier is outside the scope of this section on oop, because it necessitates the concept of **inheritance**.