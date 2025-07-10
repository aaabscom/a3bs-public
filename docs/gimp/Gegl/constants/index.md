---
layout: default
title: Gegl.constants
---
# Gegl.constants

## Constants table

| Name | Value | Type | Documentation |
|------------------|-------------------|-------------------|------------------|
| AUTO_ROWSTRIDE | unavailable | unavailable | unavailable |
| CH_BACK_CENTER | 256 | <class 'int'> | § |
| CH_BACK_LEFT | 16 | <class 'int'> | § |
| CH_BACK_RIGHT | 32 | <class 'int'> | § |
| CH_FRONT_CENTER | 4 | <class 'int'> | § |
| CH_FRONT_LEFT | 1 | <class 'int'> | § |
| CH_FRONT_LEFT_OF_CENTER | 64 | <class 'int'> | § |
| CH_FRONT_RIGHT | 2 | <class 'int'> | § |
| CH_FRONT_RIGHT_OF_CENTER | 128 | <class 'int'> | § |
| CH_LAYOUT_2POINT1 | unavailable | unavailable | unavailable |
| CH_LAYOUT_2_1 | unavailable | unavailable | unavailable |
| CH_LAYOUT_2_2 | unavailable | unavailable | unavailable |
| CH_LAYOUT_3POINT1 | unavailable | unavailable | unavailable |
| CH_LAYOUT_4POINT0 | unavailable | unavailable | unavailable |
| CH_LAYOUT_4POINT1 | unavailable | unavailable | unavailable |
| CH_LAYOUT_5POINT0 | unavailable | unavailable | unavailable |
| CH_LAYOUT_5POINT0_BACK | unavailable | unavailable | unavailable |
| CH_LAYOUT_5POINT1 | unavailable | unavailable | unavailable |
| CH_LAYOUT_5POINT1_BACK | unavailable | unavailable | unavailable |
| CH_LAYOUT_6POINT0 | unavailable | unavailable | unavailable |
| CH_LAYOUT_6POINT0_FRONT | unavailable | unavailable | unavailable |
| CH_LAYOUT_6POINT1 | unavailable | unavailable | unavailable |
| CH_LAYOUT_6POINT1_BACK | unavailable | unavailable | unavailable |
| CH_LAYOUT_6POINT1_FRONT | unavailable | unavailable | unavailable |
| CH_LAYOUT_7POINT0 | unavailable | unavailable | unavailable |
| CH_LAYOUT_7POINT0_FRONT | unavailable | unavailable | unavailable |
| CH_LAYOUT_7POINT1 | unavailable | unavailable | unavailable |
| CH_LAYOUT_7POINT1_WIDE | unavailable | unavailable | unavailable |
| CH_LAYOUT_7POINT1_WIDE_BACK | unavailable | unavailable | unavailable |
| CH_LAYOUT_HEXADECAGONAL | unavailable | unavailable | unavailable |
| CH_LAYOUT_HEXAGONAL | unavailable | unavailable | unavailable |
| CH_LAYOUT_NATIVE | -1 | <class 'int'> | § |
| CH_LAYOUT_OCTAGONAL | unavailable | unavailable | unavailable |
| CH_LAYOUT_QUAD | unavailable | unavailable | unavailable |
| CH_LAYOUT_STEREO | unavailable | unavailable | unavailable |
| CH_LAYOUT_STEREO_DOWNMIX | unavailable | unavailable | unavailable |
| CH_LAYOUT_SURROUND | unavailable | unavailable | unavailable |
| CH_LOW_FREQUENCY | 8 | <class 'int'> | § |
| CH_LOW_FREQUENCY_2 | unavailable | unavailable | unavailable |
| CH_SIDE_LEFT | 512 | <class 'int'> | § |
| CH_SIDE_RIGHT | 1024 | <class 'int'> | § |
| CH_STEREO_LEFT | 536870912 | <class 'int'> | § |
| CH_STEREO_RIGHT | 1073741824 | <class 'int'> | § |
| CH_SURROUND_DIRECT_LEFT | unavailable | unavailable | unavailable |
| CH_SURROUND_DIRECT_RIGHT | unavailable | unavailable | unavailable |
| CH_TOP_BACK_CENTER | 65536 | <class 'int'> | § |
| CH_TOP_BACK_LEFT | 32768 | <class 'int'> | § |
| CH_TOP_BACK_RIGHT | 131072 | <class 'int'> | § |
| CH_TOP_CENTER | 2048 | <class 'int'> | § |
| CH_TOP_FRONT_CENTER | 8192 | <class 'int'> | § |
| CH_TOP_FRONT_LEFT | 4096 | <class 'int'> | § |
| CH_TOP_FRONT_RIGHT | 16384 | <class 'int'> | § |
| CH_WIDE_LEFT | -2147483648 | <class 'int'> | § |
| CH_WIDE_RIGHT | unavailable | unavailable | unavailable |
| FLOAT_EPSILON | 1e-05 | <class 'float'> | §§ |
| LOOKUP_MAX_ENTRIES | 819200 | <class 'int'> | § |
| MAJOR_VERSION | unavailable | unavailable | unavailable |
| MAX_AUDIO_CHANNELS | 8 | <class 'int'> | § |
| MICRO_VERSION | 62 | <class 'int'> | § |
| MINOR_VERSION | 4 | <class 'int'> | § |
| PARAM_NO_VALIDATE | 64 | <class 'int'> | § |

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




## Documentation §§
- Convert a string or number to a floating-point number, if possible.

### Runtime attributes

- **imag**
- **real**

### Runtime functions
- **as_integer_ratio**`()`
  - Return a pair of integers, whose ratio is exactly equal to the original float.<br /><br />The ratio is in lowest terms and has a positive denominator.  Raise<br />OverflowError on infinities and a ValueError on NaNs.<br /><br />>>> (10.0).as_integer_ratio()<br />(10, 1)<br />>>> (0.0).as_integer_ratio()<br />(0, 1)<br />>>> (-.25).as_integer_ratio()<br />(-1, 4)

- **conjugate**`()`
  - Return self, the complex conjugate of any float.

- **fromhex**`(string, /)`
  - Create a floating-point number from a hexadecimal string.<br /><br />>>> float.fromhex('0x1.ffffp10')<br />2047.984375<br />>>> float.fromhex('-0x1p-1074')<br />-5e-324

- **hex**`()`
  - Return a hexadecimal representation of a floating-point number.<br /><br />>>> (-0.1).hex()<br />'-0x1.999999999999ap-4'<br />>>> 3.14159.hex()<br />'0x1.921f9f01b866ep+1'

- **is_integer**`()`
  - Return True if the float is an integer.


