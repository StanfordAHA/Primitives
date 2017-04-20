This repo is for defining primtiives associated with AHA.

This includes:
Rigel Higher order primitives
CoreIR stdlib primtives
CGRA primitives


Note on notation:

Base types:
  Clk
  Rst
  BitIn
  Bit

For Arrays, use 
  T[len]
    where T is the type of the element of the array
    where len is the length of the array

For Records/bundles/structs/labeled tuples use:
  {
    label1: T1,
    label2: T2,
    ...
    labelN: TN
  }

For Named Types, just use the name
