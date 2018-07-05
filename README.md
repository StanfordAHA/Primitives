## This repo is for defining primitives/interfaces associated with AHA.

This includes:  
Rigel Higher order primitives  
CoreIR stdlib primtives  
CGRA primitives  




## Notation Guide:

```
Base types: (out direction, in direction)
  Clk, ClkIn
  Rst, RstIn
  Bit, BitIn

For Arrays
  T[len]
    where T is the type of the element of the array
    where len is the length of the array

For Records/bundles/structs/labeled tuples:
  label1 : T1,
  label2 : T2,
  labelN : TN

For Named Types:
  Named Types wrap another type in a name


Short hand for a record of array of Types:
  label[2] : T == label : T[2]

Common type operations:
  (T[len]).elemtype returns T
  (T[len]).len returns len
  T.isa(Kind) returns true if T is of kind 'Kind'
  T.rawtype returns the stripped version of the Named Type T
```
