# binary_hex_calculator

'pc' is a command-line reverse-polish calculator.
It's aim is to easily convert decimal / binary / hexadecimal numbers.

To use it :
````
  $ pc
  Type '?' or 'h' for help
  > h
  + - * / % ^ sq(rt)
  and or xor not <<n >>n
  [?h]elp [q]uit [d]elete [c]lear [s]wap [r]otate
  he[x] [b]inary
  pad c: pad with c
  show n: display n digits

  > 1
   1: 00000001
  > 2
   2: 00000001
   1: 00000002
  > +
   1: 00000003
  >
````

To enter and display hexadecimal numbers, type `x` :
````
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
````

For binary numbers, type `b` :

To come back to decimal (default) base, enter `x` or `b` a second time.
Note that `0x` (hexadecimal) and `0b` (binary) prefix might always be used.

