Provider             |  Level        |  Event ID  |  Version  |  Channel  |  Task  |  Opcode  |  Keyword           |  Message
---------------------|---------------|------------|-----------|-----------|--------|----------|--------------------|----------------------------------------------------------------------------------
DptfAcpiEtwProvider  |               |  0         |  0        |           |        |          |                    |  {stringPtr}
DptfAcpiEtwProvider  |  Information  |  100       |  0        |           |        |  Start   |  ApiTrace Windows  |  INFO: ISR Start;  Interrupt = {Interrupt}; MessageID = {MessageID}
DptfAcpiEtwProvider  |  Information  |  101       |  0        |           |        |  Stop    |  ApiTrace Windows  |  INFO: ISR End;  Status = {Status}
DptfAcpiEtwProvider  |               |  102       |  0        |           |        |          |  Windows           |  DEBUG: {String}
DptfAcpiEtwProvider  |  Error        |  103       |  0        |           |        |          |  Windows           |  ERROR: {String}
DptfAcpiEtwProvider  |  Warning      |  104       |  0        |           |        |          |  Windows           |  WARN: {String}
DptfAcpiEtwProvider  |  Information  |  105       |  0        |           |        |          |  Windows           |  INFO: {String}
DptfAcpiEtwProvider  |  Information  |  106       |  0        |           |        |          |  Windows           |  INFO: {String}; Status = {Status}
DptfAcpiEtwProvider  |  Information  |  107       |  0        |           |        |          |  ApiTrace Windows  |  INFO: DPC Start; Interrupt = {Interrupt}; Associated Object = {AssociatedObject}
DptfAcpiEtwProvider  |  Information  |  108       |  0        |           |        |  Stop    |  ApiTrace Windows  |