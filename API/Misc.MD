# Misc
Miscellaneous values

### wait
```luau
wait(time_seconds: number)
```
pauses execution of the current thread for the given amount of seconds (can be fractional)

*does NOT affect the game*

### set_global
```luau
set_global(name: string, value: any)
```
sets the global with the given name to the given value. this affects all scripts.

if value is `nil`, the name specified will no longer have a value associated

<- [Previous (User)](./User.MD)

[Next (Table)](./Table.MD) ->