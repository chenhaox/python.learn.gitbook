# Class

## Useful build-in functions:

`__dict__`: return the all **properties** of the instance as a **dictionary**.

`__call__`: When the instance of the class is called, execute this function.

`__metaclass__` : Set the metaclass of the class. \(Usually, the metaclass of the class is `type`\)

Using type to make a function:

`type(`className,  fatherObject , memberDict`)`

> | Operator | Method |
> | :--- | :--- |
> | == | `__eq__` |
> | != | `__ne__` |
> | &lt; | `__lt__` |
> | &lt;= | `__le__` |
> | &gt; | `__gt__` |
> | &gt;= | `__ge__` |

## Python inner-built functions



> | Functionality | Name |
> | :--- | :--- |
> | Output the message when is called out in the console | `__repr__` |
> | Output the message when Printing | `__str__` |

