---
layout: default
title: Gimp.flags
---
# Gimp.flags

## ExportCapabilities

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| CAN_HANDLE_ALPHA | 16 |
| CAN_HANDLE_BITMAP | 8 |
| CAN_HANDLE_GRAY | 2 |
| CAN_HANDLE_INDEXED | 4 |
| CAN_HANDLE_LAYERS | 32 |
| CAN_HANDLE_LAYERS_AS_ANIMATION | 64 |
| CAN_HANDLE_LAYER_EFFECTS | 256 |
| CAN_HANDLE_LAYER_MASKS | 128 |
| CAN_HANDLE_RGB | 1 |
| NEEDS_ALPHA | 512 |
| NEEDS_CROP | 1024 |

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


## MetadataLoadFlags

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| ALL | 4294967295 |
| COLORSPACE | 8 |
| COMMENT | 1 |
| NONE | 0 |
| ORIENTATION | 4 |
| RESOLUTION | 2 |

### Other runtime attributes ‡


### Runtime functions †

## MetadataSaveFlags

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| ALL | 4294967295 |
| COLOR_PROFILE | 16 |
| COMMENT | 32 |
| EXIF | 1 |
| IPTC | 4 |
| THUMBNAIL | 8 |
| XMP | 2 |

### Other runtime attributes ‡


### Runtime functions †

## ProcedureSensitivityMask

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| ALWAYS | 2147483647 |
| DRAWABLE | 1 |
| DRAWABLES | 4 |
| NO_DRAWABLES | 8 |
| NO_IMAGE | 16 |

### Other runtime attributes ‡


### Runtime functions †
