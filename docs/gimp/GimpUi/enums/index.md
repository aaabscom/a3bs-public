---
layout: default
title: GimpUi.enums
---
# GimpUi.enums

## AspectType

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| LANDSCAPE | 2 |
| PORTRAIT | 1 |
| SQUARE | 0 |

### Other runtime attributes ‡
- **denominator**
- **imag**
- **numerator**
- **real**
- **value_name**
- **value_nick**


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


## ChainPosition

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| BOTTOM | 2 |
| LEFT | 1 |
| RIGHT | 3 |
| TOP | 0 |

### Other runtime attributes ‡


### Runtime functions †

## ColorAreaType

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| FLAT | 0 |
| LARGE_CHECKS | 2 |
| SMALL_CHECKS | 1 |

### Other runtime attributes ‡


### Runtime functions †

## ColorSelectorChannel

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| ALPHA | 6 |
| BLUE | 5 |
| GREEN | 4 |
| HUE | 0 |
| LCH_CHROMA | 8 |
| LCH_HUE | 9 |
| LCH_LIGHTNESS | 7 |
| RED | 3 |
| SATURATION | 1 |
| VALUE | 2 |

### Other runtime attributes ‡


### Runtime functions †

## ColorSelectorModel

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| HSV | 2 |
| LCH | 1 |
| RGB | 0 |

### Other runtime attributes ‡


### Runtime functions †

## IntComboBoxLayout

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| ABBREVIATED | 1 |
| FULL | 2 |
| ICON_ONLY | 0 |

### Other runtime attributes ‡


### Runtime functions †

## IntStoreColumns

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| ABBREV | 2 |
| ICON_NAME | 3 |
| LABEL | 1 |
| NUM_COLUMNS | 6 |
| PIXBUF | 4 |
| USER_DATA | 5 |
| VALUE | 0 |

### Other runtime attributes ‡


### Runtime functions †

## PageSelectorTarget

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| IMAGES | 1 |
| LAYERS | 0 |

### Other runtime attributes ‡


### Runtime functions †

## SizeEntryUpdatePolicy

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| NONE | 0 |
| RESOLUTION | 2 |
| SIZE | 1 |

### Other runtime attributes ‡


### Runtime functions †

## WidgetsError

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| WIDGETS_PARSE_ERROR | 0 |

### Other runtime attributes ‡


### Runtime functions †

## ZoomType

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| IN | 0 |
| OUT | 1 |

### Other runtime attributes ‡


### Runtime functions †
