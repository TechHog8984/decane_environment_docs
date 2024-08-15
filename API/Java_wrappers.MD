# Java wrappers

### java_println
```luau
java_println(...: any)
```
`tostring`s all arguments, adds four spaces after each, and then calls `System.out.println` in java with the resulting string

### java_print
```luau
java_print(...: any)
```
same as above, but calls `System.out.print` instead

### java_log
```luau
java_log(level: "INFO" | "WARN" | "ERROR" | "FATAL", ...: any)
```
same as above, but calls the Minecraft logger's respective log method for the given level instead

<- [Previous (API)](./README.MD)

[Next (User)](./User.MD) ->