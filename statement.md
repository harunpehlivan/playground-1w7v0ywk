# Welcome!

Peglo

```C# runnable
// { autofold
using System;

class Hello 
{
    static void Main() 
    {
// }
int? a = null;
Console.WriteLine(a ?? 5);
// Equivalent ternary : a != null ? a : 5
// { autofold
    }
}
// }
```

# Description

The ?? operator allows you to assign the variable if it is not null otherwise it assigns the right value.
