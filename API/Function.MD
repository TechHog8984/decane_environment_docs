# Function
function manipulation

> [!NOTE]
> `(...any) -> ...any` represents a generic function

### new_cclosure
```luau
new_cclosure(func: (...any) -> ...any): (...any) -> ...any
```
returns a C closure that wraps the given function

### is_lclosure
```luau
is_lclosure(func: (...any) -> ...any): boolean
```
returns true if the given function is a lua closure

<- [Previous (Table)](./Table.MD)

<!-- [Next (Function)](./Function.MD) -> -->