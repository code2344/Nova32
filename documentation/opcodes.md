# Opcodes
## Data Movement
Data movement uses the prefix 0x0*
|Opcode|Name|Register|Input|Example|
|---|---|---|---|---|
|0x01|MOV|register|immediate|MOV a, 10|
|0x02|MOV|register|register|MOV a, b|
|0x03|LOAD|register|address|LOAD a, [0x1000]|
|0x04|LOAD|address|register|STORE [0x1000], a|
|0x05|LOAD|register|register-address|LOAD a, [b]|
|0x06|LOAD|register-address|register|STORE [a], b|
|0x07|||||
|0x08|||||
|0x09|||||
|0x0A|||||
|0x0B|||||
|0x0C|||||
|0x0D|||||
|0x0E|||||
|0x0F|||||

## Arithmetic
Arithmetic uses the prefix 0x1*
|Opcode|Name|Register|Input|Example|
|---|---|---|---|---|
|0x10|ADD|register|register|ADD a, b|
|0x11|ADD|register|immediate|ADD a, 10|
|0x12|
|0x13|
|0x14|
|0x15|
|0x16|
|0x17|
|0x18|
|0x19|
|0x1A|
|0x1B|
|0x1C|
|0x1D|
|0x1E|
|0x1F|

