# Dyanmic-x64FastCall

Simple C function that can dynamically invoke a function that 
uses the standard windows x64 four-register fast-call calling convention.

Structs larger then 64 bytes are not suported 
(although pointers do)

Floats work provided they are not one of the first 4 arguments
