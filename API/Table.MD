# Table
table manipulation

> [!NOTE]
> `{}` represents a generic table

### set_read_only
```luau
set_read_only(table: {}, value: boolean): {}
```
sets the given table's read-only state to value

returns the given table

### is_read_only
```luau
is_read_only(table: {}): boolean
```
returns whether or not the given table is read-only

### get_read_only
alias to is_read_only

### toggle_read_only
```luau
toggle_read_only(table: {}): boolean
```
flips the given table's read-only state and returns the new state

<- [Previous (Misc)](./Misc.MD)

[Next (Function)](./Function.MD) ->