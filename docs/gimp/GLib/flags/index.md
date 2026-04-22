---
layout: default
title: GLib.flags
---
# GLib.flags

## AsciiType

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| ALNUM | 1 |
| ALPHA | 2 |
| CNTRL | 4 |
| DIGIT | 8 |
| GRAPH | 16 |
| LOWER | 32 |
| PRINT | 64 |
| PUNCT | 128 |
| SPACE | 256 |
| UPPER | 512 |
| XDIGIT | 1024 |

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


<br>
## FileSetContentsFlags

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| NONE | 0 |
| CONSISTENT | 1 |
| DURABLE | 2 |
| ONLY_EXISTING | 4 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## FileTest

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| IS_REGULAR | 1 |
| IS_SYMLINK | 2 |
| IS_DIR | 4 |
| IS_EXECUTABLE | 8 |
| EXISTS | 16 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## FormatSizeFlags

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| DEFAULT | 0 |
| LONG_FORMAT | 1 |
| IEC_UNITS | 2 |
| BITS | 4 |
| ONLY_VALUE | 8 |
| ONLY_UNIT | 16 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## HookFlagMask

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| ACTIVE | 1 |
| IN_CALL | 2 |
| MASK | 15 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## IOCondition

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| IN | 1 |
| PRI | 2 |
| OUT | 4 |
| ERR | 8 |
| HUP | 16 |
| NVAL | 32 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## IOFlags

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| NONE | 0 |
| APPEND | 1 |
| NONBLOCK | 2 |
| SET_MASK | 3 |
| IS_READABLE | 4 |
| IS_WRITEABLE | 8 |
| IS_SEEKABLE | 16 |
| MASK | 31 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## KeyFileFlags

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| NONE | 0 |
| KEEP_COMMENTS | 1 |
| KEEP_TRANSLATIONS | 2 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## LogLevelFlags

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| FLAG_RECURSION | 1 |
| FLAG_FATAL | 2 |
| LEVEL_ERROR | 4 |
| LEVEL_CRITICAL | 8 |
| LEVEL_WARNING | 16 |
| LEVEL_MESSAGE | 32 |
| LEVEL_INFO | 64 |
| LEVEL_DEBUG | 128 |
| LEVEL_MASK | 18446744073709551612 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## MainContextFlags

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| NONE | 0 |
| OWNERLESS_POLLING | 1 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## MarkupCollectType

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| INVALID | 0 |
| STRING | 1 |
| STRDUP | 2 |
| BOOLEAN | 3 |
| TRISTATE | 4 |
| OPTIONAL | 65536 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## MarkupParseFlags

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| DEFAULT_FLAGS | 0 |
| DO_NOT_USE_THIS_UNSUPPORTED_FLAG | 1 |
| TREAT_CDATA_AS_TEXT | 2 |
| PREFIX_ERROR_POSITION | 4 |
| IGNORE_QUALIFIED | 8 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## OptionFlags

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| NONE | 0 |
| HIDDEN | 1 |
| IN_MAIN | 2 |
| REVERSE | 4 |
| NO_ARG | 8 |
| FILENAME | 16 |
| OPTIONAL_ARG | 32 |
| NOALIAS | 64 |
| DEPRECATED | 128 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## RegexCompileFlags

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| DEFAULT | 0 |
| CASELESS | 1 |
| MULTILINE | 2 |
| DOTALL | 4 |
| EXTENDED | 8 |
| ANCHORED | 16 |
| DOLLAR_ENDONLY | 32 |
| UNGREEDY | 512 |
| RAW | 2048 |
| NO_AUTO_CAPTURE | 4096 |
| OPTIMIZE | 8192 |
| FIRSTLINE | 262144 |
| DUPNAMES | 524288 |
| NEWLINE_CR | 1048576 |
| NEWLINE_LF | 2097152 |
| NEWLINE_CRLF | 3145728 |
| NEWLINE_ANYCRLF | 5242880 |
| BSR_ANYCRLF | 8388608 |
| JAVASCRIPT_COMPAT | 33554432 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## RegexMatchFlags

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| DEFAULT | 0 |
| ANCHORED | 16 |
| NOTBOL | 128 |
| NOTEOL | 256 |
| NOTEMPTY | 1024 |
| PARTIAL_SOFT | 32768 |
| NEWLINE_CR | 1048576 |
| NEWLINE_LF | 2097152 |
| NEWLINE_CRLF | 3145728 |
| NEWLINE_ANY | 4194304 |
| NEWLINE_ANYCRLF | 5242880 |
| BSR_ANYCRLF | 8388608 |
| BSR_ANY | 16777216 |
| PARTIAL_HARD | 134217728 |
| NOTEMPTY_ATSTART | 268435456 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## SpawnFlags

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| DEFAULT | 0 |
| LEAVE_DESCRIPTORS_OPEN | 1 |
| DO_NOT_REAP_CHILD | 2 |
| SEARCH_PATH | 4 |
| STDOUT_TO_DEV_NULL | 8 |
| STDERR_TO_DEV_NULL | 16 |
| CHILD_INHERITS_STDIN | 32 |
| FILE_AND_ARGV_ZERO | 64 |
| SEARCH_PATH_FROM_ENVP | 128 |
| CLOEXEC_PIPES | 256 |
| CHILD_INHERITS_STDOUT | 512 |
| CHILD_INHERITS_STDERR | 1024 |
| STDIN_FROM_DEV_NULL | 2048 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## TestSubprocessFlags

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| DEFAULT | 0 |
| INHERIT_STDIN | 1 |
| INHERIT_STDOUT | 2 |
| INHERIT_STDERR | 4 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## TestTrapFlags

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| DEFAULT | 0 |
| SILENCE_STDOUT | 128 |
| SILENCE_STDERR | 256 |
| INHERIT_STDIN | 512 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## TraverseFlags

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| LEAVES | 1 |
| NON_LEAVES | 2 |
| MASK | 3 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## UriFlags

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| NONE | 0 |
| PARSE_RELAXED | 1 |
| HAS_PASSWORD | 2 |
| HAS_AUTH_PARAMS | 4 |
| ENCODED | 8 |
| NON_DNS | 16 |
| ENCODED_QUERY | 32 |
| ENCODED_PATH | 64 |
| ENCODED_FRAGMENT | 128 |
| SCHEME_NORMALIZE | 256 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## UriHideFlags

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| NONE | 0 |
| USERINFO | 1 |
| PASSWORD | 2 |
| AUTH_PARAMS | 4 |
| QUERY | 8 |
| FRAGMENT | 16 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## UriParamsFlags

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| NONE | 0 |
| CASE_INSENSITIVE | 1 |
| WWW_FORM | 2 |
| PARSE_RELAXED | 4 |

### Other runtime attributes ‡


### Runtime functions †

<br>