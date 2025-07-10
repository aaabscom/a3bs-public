---
layout: default
title: GObject.flags
---
# GObject.flags

## BindingFlags

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| BIDIRECTIONAL | 1 |
| DEFAULT | 0 |
| INVERT_BOOLEAN | 4 |
| SYNC_CREATE | 2 |

### Other runtime attributes ‡
- **denominator**
- **first_value_name**
- **first_value_nick**
- **imag**
- **numerator**
- **real**
- **value_names**
- **value_nicks**


### Runtime functions †
- **as_integer_ratio**`(self, /)`
  - Return a pair of integers, whose ratio is equal to the original int.<br /><br />The ratio is in lowest terms and has a positive denominator.<br /><br />>>> (10).as_integer_ratio()<br />(10, 1)<br />>>> (-10).as_integer_ratio()<br />(-10, 1)<br />>>> (0).as_integer_ratio()<br />(0, 1)

- **bit_count**`(self, /)`
  - Number of ones in the binary representation of the absolute value of self.<br /><br />Also known as the population count.<br /><br />>>> bin(13)<br />'0b1101'<br />>>> (13).bit_count()<br />3

- **bit_length**`(self, /)`
  - Number of bits necessary to represent self in binary.<br /><br />>>> bin(37)<br />'0b100101'<br />>>> (37).bit_length()<br />6

- **conjugate**`(self, /)`
  - Returns self, the complex conjugate of any int.

- **from_bytes**`(bytes, byteorder='big', *, signed=False)`
  - Return the integer represented by the given array of bytes.<br /><br />bytes<br />  Holds the array of bytes to convert.  The argument must either<br />  support the buffer protocol or be an iterable object producing bytes.<br />  Bytes and bytearray are examples of built-in objects that support the<br />  buffer protocol.<br />byteorder<br />  The byte order used to represent the integer.  If byteorder is 'big',<br />  the most significant byte is at the beginning of the byte array.  If<br />  byteorder is 'little', the most significant byte is at the end of the<br />  byte array.  To request the native byte order of the host system, use<br />  sys.byteorder as the byte order value.  Default is to use 'big'.<br />signed<br />  Indicates whether two's complement is used to represent the integer.

- **is_integer**`(self, /)`
  - Returns True. Exists for duck type compatibility with float.is_integer.

- **to_bytes**`(self, /, length=1, byteorder='big', *, signed=False)`
  - Return an array of bytes representing an integer.<br /><br />length<br />  Length of bytes object to use.  An OverflowError is raised if the<br />  integer is not representable with the given number of bytes.  Default<br />  is length 1.<br />byteorder<br />  The byte order used to represent the integer.  If byteorder is 'big',<br />  the most significant byte is at the beginning of the byte array.  If<br />  byteorder is 'little', the most significant byte is at the end of the<br />  byte array.  To request the native byte order of the host system, use<br />  sys.byteorder as the byte order value.  Default is to use 'big'.<br />signed<br />  Determines whether two's complement is used to represent the integer.<br />  If signed is False and a negative integer is given, an OverflowError<br />  is raised.


## ConnectFlags

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| AFTER | 1 |
| DEFAULT | 0 |
| SWAPPED | 2 |

### Other runtime attributes ‡


### Runtime functions †

## IOCondition

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| ERR | 8 |
| HUP | 16 |
| IN | 1 |
| NVAL | 32 |
| OUT | 4 |
| PRI | 2 |

### Other runtime attributes ‡


### Runtime functions †

## ParamFlags

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| CONSTRUCT | 4 |
| CONSTRUCT_ONLY | 8 |
| DEPRECATED | 2147483648 |
| EXPLICIT_NOTIFY | 1073741824 |
| LAX_VALIDATION | 16 |
| PRIVATE | 32 |
| READABLE | 1 |
| READWRITE | 3 |
| STATIC_BLURB | 128 |
| STATIC_NAME | 32 |
| STATIC_NICK | 64 |
| WRITABLE | 2 |

### Other runtime attributes ‡


### Runtime functions †

## SignalFlags

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| ACCUMULATOR_FIRST_RUN | 131072 |
| ACTION | 32 |
| DEPRECATED | 256 |
| DETAILED | 16 |
| MUST_COLLECT | 128 |
| NO_HOOKS | 64 |
| NO_RECURSE | 8 |
| RUN_CLEANUP | 4 |
| RUN_FIRST | 1 |
| RUN_LAST | 2 |

### Other runtime attributes ‡


### Runtime functions †

## SignalMatchType

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| CLOSURE | 4 |
| DATA | 16 |
| DETAIL | 2 |
| FUNC | 8 |
| ID | 1 |
| UNBLOCKED | 32 |

### Other runtime attributes ‡


### Runtime functions †

## TypeDebugFlags

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| INSTANCE_COUNT | 4 |
| MASK | 7 |
| NONE | 0 |
| OBJECTS | 1 |
| SIGNALS | 2 |

### Other runtime attributes ‡


### Runtime functions †

## TypeFlags

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| ABSTRACT | 16 |
| DEPRECATED | 128 |
| FINAL | 64 |
| NONE | 0 |
| VALUE_ABSTRACT | 32 |

### Other runtime attributes ‡


### Runtime functions †

## TypeFundamentalFlags

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| CLASSED | 1 |
| DEEP_DERIVABLE | 8 |
| DERIVABLE | 4 |
| INSTANTIATABLE | 2 |

### Other runtime attributes ‡


### Runtime functions †
