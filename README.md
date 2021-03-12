# binary_hex_calculator

'pc' is a command-line reverse-polish calculator.
It's aim is to easily convert decimal / binary / hexadecimal numbers.

To use it :
`
  $ pc
  Type '?' or 'h' for help
  > h
  [0-9]* : number
  [?h]elp
  [c]lear
  [d]elete
  [q]uit
  [s]wap
  [r]otate
  convert base: he[x]adecimal <-> decimal
  convert base: [b]inary <-> decimal
  operators: + - * / % ^ sq(rt)
  binary: and or xor not
  others: >>number <<number
  d[0-9]+ : set digits (default 8)
  [ENTER]: duplicate last entry

  > 1
   1: 00000001
  > 2
   2: 00000001
   1: 00000002
  > +
   1: 00000003
  > 
`

To enter and display hexadecimal numbers, type `x` :
`
   2: 00000010
   1: 00000100
  > x
  BASE: 16
   2: 0000 000a  (10)
   1: 0000 0064  (100)
  > 10
  BASE: 16
   3: 0000 000a  (10)
   2: 0000 0064  (100)
   1: 0000 0010  (16)
  > 
`

For binary numbers, type `b` :

To come back to decimal (default) base, enter `x` or `b` a second time.
Note that `0x` (hexadecimal) and `0b` (binary) prefix might always be used.

