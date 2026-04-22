---
layout: default
title: Gegl.enums
---
# Gegl.enums

## AbyssPolicy

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| NONE | 0 |
| CLAMP | 1 |
| LOOP | 2 |
| BLACK | 3 |
| WHITE | 4 |

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


<br>
## BablVariant

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| FLOAT | 0 |
| LINEAR | 1 |
| NON_LINEAR | 2 |
| PERCEPTUAL | 3 |
| LINEAR_PREMULTIPLIED | 4 |
| PERCEPTUAL_PREMULTIPLIED | 5 |
| LINEAR_PREMULTIPLIED_IF_ALPHA | 6 |
| PERCEPTUAL_PREMULTIPLIED_IF_ALPHA | 7 |
| ADD_ALPHA | 8 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## CachePolicy

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| AUTO | 0 |
| NEVER | 1 |
| ALWAYS | 2 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## DistanceMetric

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| EUCLIDEAN | 0 |
| MANHATTAN | 1 |
| CHEBYSHEV | 2 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## DitherMethod

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| NONE | 0 |
| FLOYD_STEINBERG | 1 |
| BAYER | 2 |
| RANDOM | 3 |
| RANDOM_COVARIANT | 4 |
| ADD | 5 |
| ADD_COVARIANT | 6 |
| XOR | 7 |
| XOR_COVARIANT | 8 |
| BLUE_NOISE | 9 |
| BLUE_NOISE_COVARIANT | 10 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## MapFlags

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| MAP_EXCLUDE_UNMAPPED | 1 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## Orientation

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| HORIZONTAL | 0 |
| VERTICAL | 1 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## RectangleAlignment

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| SUBSET | 0 |
| SUPERSET | 1 |
| NEAREST | 2 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## ResolutionUnit

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| NONE | 0 |
| DPI | 1 |
| DPM | 2 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## SamplerType

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| NEAREST | 0 |
| LINEAR | 1 |
| CUBIC | 2 |
| NOHALO | 3 |
| LOHALO | 4 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## SplitStrategy

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| AUTO | 0 |
| HORIZONTAL | 1 |
| VERTICAL | 2 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## TileCommand

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| EGL_TILE_IDLE | 0 |
| EGL_TILE_SET | 1 |
| EGL_TILE_GET | 2 |
| EGL_TILE_IS_CACHED | 3 |
| EGL_TILE_EXIST | 4 |
| EGL_TILE_VOID | 5 |
| EGL_TILE_FLUSH | 6 |
| EGL_TILE_REFETCH | 7 |
| EGL_TILE_REINIT | 8 |
| GEGL_TILE_LAST_0_4_8_COMMAND | 9 |
| EGL_TILE_LAST_COMMAND | 10 |

### Other runtime attributes ‡


### Runtime functions †

<br>