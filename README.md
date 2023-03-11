jimmy and maskedRaider string array variables **point to the same memory location**

`*` in a variable declaration **means the variable is a pointer** and therefore can be modified

`Stack` is the **memory section where all local variables are stored.** Local variables are variables defined in functions.

`Heap` **stores data created when a program is running that have a long life span**

`Globals` is the **memory section where all global variables are stored** Global variables are variables that are defined outside functions. They can be used anywhere in the code and they get created when the program first runs.

`Constants` is the **memory section that stores read-only data (like string literals)** They cannot be changed and also get created when the program first runs

`Code` is also a **read only memory section that stores and loads assembled code** It's mostly located at the lowest location in memory in most operating systems.