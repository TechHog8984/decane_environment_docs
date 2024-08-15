# decane
a library for interacting with minecraft

### DecaneSignal
A bare-bones signal implementation using GoodSignal's syntax. All events in `decane.events` (see below) are `DecaneSignal`s

> [!NOTE]
> generic_function represents `(...any) -> ...any`

### DecaneSignal:Connect
```luau
signal:Connect(generic_function): DecaneConnection
```
connects and returns a new `DecaneConnection` on signal

### DecaneSignal:DisconnectAll
```luau
signal:DisconnectAll()
```
disconnects all connections on signal

### DecaneConnection:Disconnect
```luau
connection:Disconnect()
```
disconnects the connection

<br>

### decane.events
* `on_chat(content: string, message_id: number): boolean?`<br>
example:
    ```luau
    -- block all messages starting with a period
    decane.events.on_chat:Connect(function(content, message_id)
        if content:sub(1,1) == '.' then
            return true
        end
    end)
    ```


<- [Previous (API)](./README.MD)

[Next (Java wrappers)](./Java_wrappers.MD) ->