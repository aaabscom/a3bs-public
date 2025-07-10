---
layout: default
title: GObject.constants
---
# GObject.constants

## Constants table

| Name | Value | Type | Documentation |
|------------------|-------------------|-------------------|------------------|
| PARAM_MASK | 255 | <class 'int'> | § |
| PARAM_STATIC_STRINGS | 224 | <class 'int'> | § |
| PARAM_USER_SHIFT | 8 | <class 'int'> | § |
| SIGNAL_FLAGS_MASK | 511 | <class 'int'> | § |
| SIGNAL_MATCH_MASK | 63 | <class 'int'> | § |
| TYPE_FLAG_RESERVED_ID_BIT | 1 | <class 'int'> | § |
| TYPE_FUNDAMENTAL_MAX | 1020 | <class 'int'> | § |
| TYPE_FUNDAMENTAL_SHIFT | 2 | <class 'int'> | § |
| TYPE_RESERVED_BSE_FIRST | 32 | <class 'int'> | § |
| TYPE_RESERVED_BSE_LAST | 48 | <class 'int'> | § |
| TYPE_RESERVED_GLIB_FIRST | 22 | <class 'int'> | § |
| TYPE_RESERVED_GLIB_LAST | 31 | <class 'int'> | § |
| TYPE_RESERVED_USER_FIRST | 49 | <class 'int'> | § |
| VALUE_COLLECT_FORMAT_MAX_LENGTH | 8 | <class 'int'> | § |
| VALUE_INTERNED_STRING | 268435456 | <class 'int'> | § |
| VALUE_NOCOPY_CONTENTS | 134217728 | <class 'int'> | § |

## Documentation §
- int([x]) -> integer<br />int(x, base=10) -> integer<br /><br />Convert a number or string to an integer, or return 0 if no arguments<br />are given.  If x is a number, return x.__int__().  For floating-point<br />numbers, this truncates towards zero.<br /><br />If x is not a number or if base is given, then x must be a string,<br />bytes, or bytearray instance representing an integer literal in the<br />given base.  The literal can be preceded by '+' or '-' and be surrounded<br />by whitespace.  The base defaults to 10.  Valid bases are 0 and 2-36.<br />Base 0 means to interpret the base from the string as an integer literal.<br />>>> int('0b100', base=0)<br />4

### Runtime attributes

- **denominator**
- **imag**
- **numerator**
- **real**

### Runtime functions
- **as_integer_ratio**`()`
  - Return a pair of integers, whose ratio is equal to the original int.<br /><br />The ratio is in lowest terms and has a positive denominator.<br /><br />>>> (10).as_integer_ratio()<br />(10, 1)<br />>>> (-10).as_integer_ratio()<br />(-10, 1)<br />>>> (0).as_integer_ratio()<br />(0, 1)

- **bit_count**`()`
  - Number of ones in the binary representation of the absolute value of self.<br /><br />Also known as the population count.<br /><br />>>> bin(13)<br />'0b1101'<br />>>> (13).bit_count()<br />3

- **bit_length**`()`
  - Number of bits necessary to represent self in binary.<br /><br />>>> bin(37)<br />'0b100101'<br />>>> (37).bit_length()<br />6

- **conjugate**`()`
  - Returns self, the complex conjugate of any int.

- **from_bytes**`(bytes, byteorder='big', *, signed=False)`
  - Return the integer represented by the given array of bytes.<br /><br />bytes<br />  Holds the array of bytes to convert.  The argument must either<br />  support the buffer protocol or be an iterable object producing bytes.<br />  Bytes and bytearray are examples of built-in objects that support the<br />  buffer protocol.<br />byteorder<br />  The byte order used to represent the integer.  If byteorder is 'big',<br />  the most significant byte is at the beginning of the byte array.  If<br />  byteorder is 'little', the most significant byte is at the end of the<br />  byte array.  To request the native byte order of the host system, use<br />  sys.byteorder as the byte order value.  Default is to use 'big'.<br />signed<br />  Indicates whether two's complement is used to represent the integer.

- **is_integer**`()`
  - Returns True. Exists for duck type compatibility with float.is_integer.

- **to_bytes**`(length=1, byteorder='big', *, signed=False)`
  - Return an array of bytes representing an integer.<br /><br />length<br />  Length of bytes object to use.  An OverflowError is raised if the<br />  integer is not representable with the given number of bytes.  Default<br />  is length 1.<br />byteorder<br />  The byte order used to represent the integer.  If byteorder is 'big',<br />  the most significant byte is at the beginning of the byte array.  If<br />  byteorder is 'little', the most significant byte is at the end of the<br />  byte array.  To request the native byte order of the host system, use<br />  sys.byteorder as the byte order value.  Default is to use 'big'.<br />signed<br />  Determines whether two's complement is used to represent the integer.<br />  If signed is False and a negative integer is given, an OverflowError<br />  is raised.


