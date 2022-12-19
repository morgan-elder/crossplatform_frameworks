- strongly typed
- [[built-in types]] and custom types
- variables and constants have a type
- the value of evaluated expressions has a type
- methods use types to define input parameters and return values
- information stored in a type
	- storage space
	- max and min values that can be represented
	- members (methods, fields, etc)
	- inheritance
	- interface
	- permitted operations
- types ensure that the compiler is performing allowed operations

```cs
// int and bool cannot be added with + operator
int a = 5;
int b = a + 2; // ok

bool test = true;

int c = a + test;
```

## Sources
Refers to the [Microsoft Csharp documentation](https://learn.microsoft.com/en-us/dotnet/csharp/fundamentals/types/)

