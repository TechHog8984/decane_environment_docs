# Function
function manipulation

> [!NOTE]
> generic_function represents `(...any) -> ...any`

### new_cclosure
```luau
new_cclosure(func: generic_function): generic_function
```
returns a C closure that wraps the given function

### is_lclosure
```luau
is_lclosure(func: generic_function): boolean
```
returns true if the given function is a lua closure

<- [Previous (Table)](./Table.MD)

<!-- [Next (Function)](./Function.MD) -> -->