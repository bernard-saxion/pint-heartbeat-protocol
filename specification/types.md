#Data types
All data sent over the network is TODO-endian,
which means the most-significant bit is sent TODO.
Therefore it may be necessary to change the endianness
before sending data over the network

Name | size (bytes) | Encodes | Notes
---- | ------------ | ------- | -----
boolean | TODO | Either false or true | TODO
byte | 1 | An integer between -128 and 127 | two's complement
unsigned byte | 1 | An integer between 0 and 255 |
short | 2 | An integer between -32768 and 32767 | two's complement
etcetera | TODO | TODO | TODO

