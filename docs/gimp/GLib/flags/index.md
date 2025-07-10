---
layout: default
title: GLib.flags
---
# GLib.flags

## AsciiType

### Runtime attributes

| Name | Value |
|------------------------|---------------|
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


## FileSetContentsFlags

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| CONSISTENT | 1 |
| DURABLE | 2 |
| NONE | 0 |
| ONLY_EXISTING | 4 |

### Other runtime attributes ‡


### Runtime functions †

## FileTest

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| EXISTS | 16 |
| IS_DIR | 4 |
| IS_EXECUTABLE | 8 |
| IS_REGULAR | 1 |
| IS_SYMLINK | 2 |

### Other runtime attributes ‡


### Runtime functions †

## FormatSizeFlags

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| BITS | 4 |
| DEFAULT | 0 |
| IEC_UNITS | 2 |
| LONG_FORMAT | 1 |
| ONLY_UNIT | 16 |
| ONLY_VALUE | 8 |

### Other runtime attributes ‡


### Runtime functions †

## HookFlagMask

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| ACTIVE | 1 |
| IN_CALL | 2 |
| MASK | 15 |

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

## IOFlags

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| APPEND | 1 |
| GET_MASK | 31 |
| IS_READABLE | 4 |
| IS_SEEKABLE | 16 |
| IS_WRITABLE | 8 |
| IS_WRITEABLE | 8 |
| MASK | 31 |
| NONBLOCK | 2 |
| NONE | 0 |
| SET_MASK | 3 |

### Other runtime attributes ‡


### Runtime functions †

## KeyFileFlags

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| KEEP_COMMENTS | 1 |
| KEEP_TRANSLATIONS | 2 |
| NONE | 0 |

### Other runtime attributes ‡


### Runtime functions †

## LogLevelFlags

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| FLAG_FATAL | 2 |
| FLAG_RECURSION | 1 |
| LEVEL_CRITICAL | 8 |
| LEVEL_DEBUG | 128 |
| LEVEL_ERROR | 4 |
| LEVEL_INFO | 64 |
| LEVEL_MASK | 18446744073709551612 |
| LEVEL_MESSAGE | 32 |
| LEVEL_WARNING | 16 |

### Other runtime attributes ‡


### Runtime functions †

## MainContextFlags

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| NONE | 0 |
| OWNERLESS_POLLING | 1 |

### Other runtime attributes ‡


### Runtime functions †

## MarkupCollectType

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| BOOLEAN | 3 |
| INVALID | 0 |
| OPTIONAL | 65536 |
| STRDUP | 2 |
| STRING | 1 |
| TRISTATE | 4 |

### Other runtime attributes ‡


### Runtime functions †

## MarkupParseFlags

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| DEFAULT_FLAGS | 0 |
| DO_NOT_USE_THIS_UNSUPPORTED_FLAG | 1 |
| IGNORE_QUALIFIED | 8 |
| PREFIX_ERROR_POSITION | 4 |
| TREAT_CDATA_AS_TEXT | 2 |

### Other runtime attributes ‡


### Runtime functions †

## OptionFlags

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| DEPRECATED | 128 |
| FILENAME | 16 |
| HIDDEN | 1 |
| IN_MAIN | 2 |
| NOALIAS | 64 |
| NONE | 0 |
| NO_ARG | 8 |
| OPTIONAL_ARG | 32 |
| REVERSE | 4 |

### Other runtime attributes ‡


### Runtime functions †

## RegexCompileFlags

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| ANCHORED | 16 |
| BSR_ANYCRLF | 8388608 |
| CASELESS | 1 |
| DEFAULT | 0 |
| DOLLAR_ENDONLY | 32 |
| DOTALL | 4 |
| DUPNAMES | 524288 |
| EXTENDED | 8 |
| FIRSTLINE | 262144 |
| JAVASCRIPT_COMPAT | 33554432 |
| MULTILINE | 2 |
| NEWLINE_ANYCRLF | 5242880 |
| NEWLINE_CR | 1048576 |
| NEWLINE_CRLF | 3145728 |
| NEWLINE_LF | 2097152 |
| NO_AUTO_CAPTURE | 4096 |
| OPTIMIZE | 8192 |
| RAW | 2048 |
| UNGREEDY | 512 |

### Other runtime attributes ‡


### Runtime functions †

## RegexMatchFlags

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| ANCHORED | 16 |
| BSR_ANY | 16777216 |
| BSR_ANYCRLF | 8388608 |
| DEFAULT | 0 |
| NEWLINE_ANY | 4194304 |
| NEWLINE_ANYCRLF | 5242880 |
| NEWLINE_CR | 1048576 |
| NEWLINE_CRLF | 3145728 |
| NEWLINE_LF | 2097152 |
| NOTBOL | 128 |
| NOTEMPTY | 1024 |
| NOTEMPTY_ATSTART | 268435456 |
| NOTEOL | 256 |
| PARTIAL | 32768 |
| PARTIAL_HARD | 134217728 |
| PARTIAL_SOFT | 32768 |

### Other runtime attributes ‡


### Runtime functions †

## SpawnFlags

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| CHILD_INHERITS_STDERR | 1024 |
| CHILD_INHERITS_STDIN | 32 |
| CHILD_INHERITS_STDOUT | 512 |
| CLOEXEC_PIPES | 256 |
| DEFAULT | 0 |
| DO_NOT_REAP_CHILD | 2 |
| FILE_AND_ARGV_ZERO | 64 |
| LEAVE_DESCRIPTORS_OPEN | 1 |
| SEARCH_PATH | 4 |
| SEARCH_PATH_FROM_ENVP | 128 |
| STDERR_TO_DEV_NULL | 16 |
| STDIN_FROM_DEV_NULL | 2048 |
| STDOUT_TO_DEV_NULL | 8 |

### Other runtime attributes ‡


### Runtime functions †

## TestSubprocessFlags

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| DEFAULT | 0 |
| INHERIT_STDERR | 4 |
| INHERIT_STDIN | 1 |
| INHERIT_STDOUT | 2 |

### Other runtime attributes ‡


### Runtime functions †

## TestTrapFlags

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| DEFAULT | 0 |
| INHERIT_STDIN | 512 |
| SILENCE_STDERR | 256 |
| SILENCE_STDOUT | 128 |

### Other runtime attributes ‡


### Runtime functions †

## TraverseFlags

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| ALL | 3 |
| LEAFS | 1 |
| LEAVES | 1 |
| MASK | 3 |
| NON_LEAFS | 2 |
| NON_LEAVES | 2 |

### Other runtime attributes ‡


### Runtime functions †

## UriFlags

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| ENCODED | 8 |
| ENCODED_FRAGMENT | 128 |
| ENCODED_PATH | 64 |
| ENCODED_QUERY | 32 |
| HAS_AUTH_PARAMS | 4 |
| HAS_PASSWORD | 2 |
| NONE | 0 |
| NON_DNS | 16 |
| PARSE_RELAXED | 1 |
| SCHEME_NORMALIZE | 256 |

### Other runtime attributes ‡


### Runtime functions †

## UriHideFlags

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| AUTH_PARAMS | 4 |
| FRAGMENT | 16 |
| NONE | 0 |
| PASSWORD | 2 |
| QUERY | 8 |
| USERINFO | 1 |

### Other runtime attributes ‡


### Runtime functions †

## UriParamsFlags

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| CASE_INSENSITIVE | 1 |
| NONE | 0 |
| PARSE_RELAXED | 4 |
| WWW_FORM | 2 |

### Other runtime attributes ‡


### Runtime functions †
