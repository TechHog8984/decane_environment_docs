# Preface
Important information to know before writing scripts

Decane uses Luau, so all Luau globals are present (see https://lua.org/manual/5.1 and https://luau.org/compatability)

However, the `os` library is NOT.

> [!NOTE]  
> All classes use UpperCamelCase, constants use UPPER_SNAKE_CASE, and all other globals use snake_case.

On top of what Luau provides, there are additional third-party libraries packed into Decane used internally which are left exposed for the user:

* [middleclass](https://github.com/kikito/middleclass) (as `middleclass`)
* [GoodSignal](https://github.com/stravant/goodsignal) (as `Signal`)

<br>

<- [Previous (Welcome)](../README.MD)

[Next (API)](../API/README.MD) ->