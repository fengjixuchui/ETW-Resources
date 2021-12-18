Provider                    |  Level        |  Event ID  |  Version  |  Channel  |  Task           |  Opcode  |  Keyword       |  Message
----------------------------|---------------|------------|-----------|-----------|-----------------|----------|----------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------
Microsoft-WindowsPhone-Ufx  |  Error        |  100       |  0        |           |  Error          |          |  Error         |  Error in file {Str} on line {Int}
Microsoft-WindowsPhone-Ufx  |  Error        |  101       |  0        |           |  FailedCall     |          |  Error         |  Failed with status 0x{Status} in file {File} on line {Line}
Microsoft-WindowsPhone-Ufx  |  Verbose      |  102       |  0        |           |  FunctionEntry  |          |  Function      |  {Function} ++++
Microsoft-WindowsPhone-Ufx  |  Verbose      |  103       |  0        |           |  FunctionExit   |          |  Function      |  {Function} ----
Microsoft-WindowsPhone-Ufx  |  Error        |  104       |  0        |           |  FailedCall     |          |  Error         |  {Function}: {Message} ({IntParam})
Microsoft-WindowsPhone-Ufx  |  Verbose      |  105       |  0        |           |  IoctlRequest   |          |  UfxBus        |  {Index}: Handling IOCTL {IOCTL}
Microsoft-WindowsPhone-Ufx  |  Information  |  106       |  0        |           |  Debug          |          |  Debug         |  {Function}: {Message}
Microsoft-WindowsPhone-Ufx  |  Information  |  107       |  0        |           |  Setup          |          |  Setup         |  Description: {Description}; Direction: {Direction}; Type: {Type}; Recipient: {Recipient}; Request: {Request}; wValue: {wValue}; wIndex: {wIndex}; wLength: {wLength}
Microsoft-WindowsPhone-Ufx  |  Information  |  108       |  0        |           |  StateMachine   |          |  StateMachine  |  Created Machine {Machine}
Microsoft-WindowsPhone-Ufx  |  Information  |  109       |  0        |           |  StateMachine   |          |  StateMachine  |  {Type} {State} on Machine {Machine}
Microsoft-WindowsPhone-Ufx  |  Information  |  110       |  0        |           |  StateMachine   |          |  StateMachine  |  Enqueue ({Type}; {Event}; {Payload}) to Machine {Machine}
Microsoft-WindowsPhone-Ufx  |  Information  |  111       |  0        |           |  StateMachine   |          |  StateMachine  |  Dequeue ({Event}; {Payload}) on Machine {Machine}
Microsoft-WindowsPhone-Ufx  |  Information  |  112       |  0        |           |  StateMachine   |          |  StateMachine  |  Action {ActionName} on Machine {Machine}
Microsoft-WindowsPhone-Ufx  |  Information  |  113       |  0        |           |  StateMachine   |          |  StateMachine  |  Unhandled ({Event}) on Machine {Machine}. Pop to {ToState}
Microsoft-WindowsPhone-Ufx  |  Information  |  114       |  0        |           |  StateMachine   |          |  StateMachine  |  Exception Machine {Machine}: {Exception}
Microsoft-WindowsPhone-Ufx  |  Information  |  115       |  0        |           |  StateMachine   |          |  StateMachine  |  Queue Resize to {NewQueueSize} on MAchine {Machine}
Microsoft-WindowsPhone-Ufx  |  Information  |  116       |  0        |           |  StateMachine   |          |  StateMachine  |  Exit {FromState} on Machine {Machine}
Microsoft-WindowsPhone-Ufx  |  Information  |  117       |  0        |           |  Debug          |          |  Debug         |  {Function}: {Message} {IntParam}
Microsoft-WindowsPhone-Ufx  |  Information  |  118       |  0        |           |  Notification   |          |  Notification  |  Notification: {Str}
Microsoft-WindowsPhone-Ufx  |  Information  |  119       |  0        |           |  Notification   |          |  Notification  |  Notification: {Str} ({Int})