---
layout: default
title: Gimp.constants
---
# Gimp.constants

## Constants table

| Name | Value | Type | Documentation |
|------------------|-------------------|-------------------|------------------|
| API_VERSION | 3.0 | <class 'str'> | § |
| CHECK_DARK | 0.4 | <class 'float'> | §§ |
| CHECK_LIGHT | 0.6 | <class 'float'> | §§ |
| CHECK_SIZE | 8 | <class 'int'> | §§§ |
| CHECK_SIZE_SM | 4 | <class 'int'> | §§§ |
| CONFIG_PARAM_AGGREGATE | 2 | <class 'int'> | §§§ |
| CONFIG_PARAM_CONFIRM | 8 | <class 'int'> | §§§ |
| CONFIG_PARAM_DEFAULTS | 16 | <class 'int'> | §§§ |
| CONFIG_PARAM_DONT_COMPARE | 64 | <class 'int'> | §§§ |
| CONFIG_PARAM_FLAGS | 7 | <class 'int'> | §§§ |
| CONFIG_PARAM_FLAG_SHIFT | 7 | <class 'int'> | §§§ |
| CONFIG_PARAM_IGNORE | 32 | <class 'int'> | §§§ |
| CONFIG_PARAM_RESTART | 4 | <class 'int'> | §§§ |
| CONFIG_PARAM_SERIALIZE | 1 | <class 'int'> | §§§ |
| MAJOR_VERSION | 3 | <class 'int'> | §§§ |
| MAX_IMAGE_SIZE | 524288 | <class 'int'> | §§§ |
| MAX_MEMSIZE | unavailable | unavailable | unavailable |
| MAX_RESOLUTION | 1048576.0 | <class 'float'> | §§ |
| MICRO_VERSION | 4 | <class 'int'> | §§§ |
| MINOR_VERSION | unavailable | unavailable | unavailable |
| MIN_IMAGE_SIZE | 1 | <class 'int'> | §§§ |
| MIN_RESOLUTION | 0.005 | <class 'float'> | §§ |
| MODULE_ABI_VERSION | 5 | <class 'int'> | §§§ |
| PARAM_DONT_SERIALIZE | 2 | <class 'int'> | §§§ |
| PARAM_FLAG_SHIFT | 2 | <class 'int'> | §§§ |
| PARAM_NO_VALIDATE | 1 | <class 'int'> | §§§ |
| PARAM_READABLE | 1 | <class 'int'> | §§§ |
| PARAM_READWRITE | 3 | <class 'int'> | §§§ |
| PARAM_STATIC_STRINGS | 224 | <class 'int'> | §§§ |
| PARAM_WRITABLE | 2 | <class 'int'> | §§§ |
| PARASITE_ATTACH_GRANDPARENT | 8388608 | <class 'int'> | §§§ |
| PARASITE_ATTACH_PARENT | 32768 | <class 'int'> | §§§ |
| PARASITE_GRANDPARENT_PERSISTENT | unavailable | unavailable | unavailable |
| PARASITE_GRANDPARENT_UNDOABLE | unavailable | unavailable | unavailable |
| PARASITE_PARENT_PERSISTENT | unavailable | unavailable | unavailable |
| PARASITE_PARENT_UNDOABLE | unavailable | unavailable | unavailable |
| PARASITE_PERSISTENT | 1 | <class 'int'> | §§§ |
| PARASITE_UNDOABLE | 2 | <class 'int'> | §§§ |
| PIXPIPE_MAXDIM | 4 | <class 'int'> | §§§ |
| VERSION | 3.0.4 | <class 'str'> | § |

## Documentation §
- str(object='') -> str<br />str(bytes_or_buffer[, encoding[, errors]]) -> str<br /><br />Create a new string object from the given object. If encoding or<br />errors is specified, then the object must expose a data buffer<br />that will be decoded using the given encoding and error handler.<br />Otherwise, returns the result of object.__str__() (if defined)<br />or repr(object).<br />encoding defaults to 'utf-8'.<br />errors defaults to 'strict'.


### Runtime functions
- **capitalize**`()`
  - Return a capitalized version of the string.<br /><br />More specifically, make the first character have upper case and the rest lower<br />case.

- **casefold**`()`
  - Return a version of the string suitable for caseless comparisons.

- **center**`(width, fillchar=' ', /)`
  - Return a centered string of length width.<br /><br />Padding is done using the specified fill character (default is a space).

- **count**`(bound native)`
  - Return the number of non-overlapping occurrences of substring sub in string S[start:end].<br /><br />Optional arguments start and end are interpreted as in slice notation.

- **encode**`(encoding='utf-8', errors='strict')`
  - Encode the string using the codec registered for encoding.<br /><br />encoding<br />  The encoding in which to encode the string.<br />errors<br />  The error handling scheme to use for encoding errors.<br />  The default is 'strict' meaning that encoding errors raise a<br />  UnicodeEncodeError.  Other possible values are 'ignore', 'replace' and<br />  'xmlcharrefreplace' as well as any other name registered with<br />  codecs.register_error that can handle UnicodeEncodeErrors.

- **endswith**`(bound native)`
  - Return True if the string ends with the specified suffix, False otherwise.<br /><br />suffix<br />  A string or a tuple of strings to try.<br />start<br />  Optional start position. Default: start of the string.<br />end<br />  Optional stop position. Default: end of the string.

- **expandtabs**`(tabsize=8)`
  - Return a copy where all tab characters are expanded using spaces.<br /><br />If tabsize is not given, a tab size of 8 characters is assumed.

- **find**`(bound native)`
  - Return the lowest index in S where substring sub is found, such that sub is contained within S[start:end].<br /><br />Optional arguments start and end are interpreted as in slice notation.<br />Return -1 on failure.

- **format**`(*args, **kwargs)`
  - Return a formatted version of the string, using substitutions from args and kwargs.<br />The substitutions are identified by braces ('{' and '}').

- **format_map**`(mapping, /)`
  - Return a formatted version of the string, using substitutions from mapping.<br />The substitutions are identified by braces ('{' and '}').

- **index**`(bound native)`
  - Return the lowest index in S where substring sub is found, such that sub is contained within S[start:end].<br /><br />Optional arguments start and end are interpreted as in slice notation.<br />Raises ValueError when the substring is not found.

- **isalnum**`()`
  - Return True if the string is an alpha-numeric string, False otherwise.<br /><br />A string is alpha-numeric if all characters in the string are alpha-numeric and<br />there is at least one character in the string.

- **isalpha**`()`
  - Return True if the string is an alphabetic string, False otherwise.<br /><br />A string is alphabetic if all characters in the string are alphabetic and there<br />is at least one character in the string.

- **isascii**`()`
  - Return True if all characters in the string are ASCII, False otherwise.<br /><br />ASCII characters have code points in the range U+0000-U+007F.<br />Empty string is ASCII too.

- **isdecimal**`()`
  - Return True if the string is a decimal string, False otherwise.<br /><br />A string is a decimal string if all characters in the string are decimal and<br />there is at least one character in the string.

- **isdigit**`()`
  - Return True if the string is a digit string, False otherwise.<br /><br />A string is a digit string if all characters in the string are digits and there<br />is at least one character in the string.

- **isidentifier**`()`
  - Return True if the string is a valid Python identifier, False otherwise.<br /><br />Call keyword.iskeyword(s) to test whether string s is a reserved identifier,<br />such as "def" or "class".

- **islower**`()`
  - Return True if the string is a lowercase string, False otherwise.<br /><br />A string is lowercase if all cased characters in the string are lowercase and<br />there is at least one cased character in the string.

- **isnumeric**`()`
  - Return True if the string is a numeric string, False otherwise.<br /><br />A string is numeric if all characters in the string are numeric and there is at<br />least one character in the string.

- **isprintable**`()`
  - Return True if all characters in the string are printable, False otherwise.<br /><br />A character is printable if repr() may use it in its output.

- **isspace**`()`
  - Return True if the string is a whitespace string, False otherwise.<br /><br />A string is whitespace if all characters in the string are whitespace and there<br />is at least one character in the string.

- **istitle**`()`
  - Return True if the string is a title-cased string, False otherwise.<br /><br />In a title-cased string, upper- and title-case characters may only<br />follow uncased characters and lowercase characters only cased ones.

- **isupper**`()`
  - Return True if the string is an uppercase string, False otherwise.<br /><br />A string is uppercase if all cased characters in the string are uppercase and<br />there is at least one cased character in the string.

- **join**`(iterable, /)`
  - Concatenate any number of strings.<br /><br />The string whose method is called is inserted in between each given string.<br />The result is returned as a new string.<br /><br />Example: '.'.join(['ab', 'pq', 'rs']) -> 'ab.pq.rs'

- **ljust**`(width, fillchar=' ', /)`
  - Return a left-justified string of length width.<br /><br />Padding is done using the specified fill character (default is a space).

- **lower**`()`
  - Return a copy of the string converted to lowercase.

- **lstrip**`(chars=None, /)`
  - Return a copy of the string with leading whitespace removed.<br /><br />If chars is given and not None, remove characters in chars instead.

- **maketrans**`(bound native)`
  - Return a translation table usable for str.translate().<br /><br />If there is only one argument, it must be a dictionary mapping Unicode<br />ordinals (integers) or characters to Unicode ordinals, strings or None.<br />Character keys will be then converted to ordinals.<br />If there are two arguments, they must be strings of equal length, and<br />in the resulting dictionary, each character in x will be mapped to the<br />character at the same position in y. If there is a third argument, it<br />must be a string, whose characters will be mapped to None in the result.

- **partition**`(sep, /)`
  - Partition the string into three parts using the given separator.<br /><br />This will search for the separator in the string.  If the separator is found,<br />returns a 3-tuple containing the part before the separator, the separator<br />itself, and the part after it.<br /><br />If the separator is not found, returns a 3-tuple containing the original string<br />and two empty strings.

- **removeprefix**`(prefix, /)`
  - Return a str with the given prefix string removed if present.<br /><br />If the string starts with the prefix string, return string[len(prefix):].<br />Otherwise, return a copy of the original string.

- **removesuffix**`(suffix, /)`
  - Return a str with the given suffix string removed if present.<br /><br />If the string ends with the suffix string and that suffix is not empty,<br />return string[:-len(suffix)]. Otherwise, return a copy of the original<br />string.

- **replace**`(old, new, /, count=-1)`
  - Return a copy with all occurrences of substring old replaced by new.<br /><br />  count<br />    Maximum number of occurrences to replace.<br />    -1 (the default value) means replace all occurrences.<br /><br />If the optional argument count is given, only the first count occurrences are<br />replaced.

- **rfind**`(bound native)`
  - Return the highest index in S where substring sub is found, such that sub is contained within S[start:end].<br /><br />Optional arguments start and end are interpreted as in slice notation.<br />Return -1 on failure.

- **rindex**`(bound native)`
  - Return the highest index in S where substring sub is found, such that sub is contained within S[start:end].<br /><br />Optional arguments start and end are interpreted as in slice notation.<br />Raises ValueError when the substring is not found.

- **rjust**`(width, fillchar=' ', /)`
  - Return a right-justified string of length width.<br /><br />Padding is done using the specified fill character (default is a space).

- **rpartition**`(sep, /)`
  - Partition the string into three parts using the given separator.<br /><br />This will search for the separator in the string, starting at the end. If<br />the separator is found, returns a 3-tuple containing the part before the<br />separator, the separator itself, and the part after it.<br /><br />If the separator is not found, returns a 3-tuple containing two empty strings<br />and the original string.

- **rsplit**`(sep=None, maxsplit=-1)`
  - Return a list of the substrings in the string, using sep as the separator string.<br /><br />  sep<br />    The separator used to split the string.<br /><br />    When set to None (the default value), will split on any whitespace<br />    character (including \n \r \t \f and spaces) and will discard<br />    empty strings from the result.<br />  maxsplit<br />    Maximum number of splits.<br />    -1 (the default value) means no limit.<br /><br />Splitting starts at the end of the string and works to the front.

- **rstrip**`(chars=None, /)`
  - Return a copy of the string with trailing whitespace removed.<br /><br />If chars is given and not None, remove characters in chars instead.

- **split**`(sep=None, maxsplit=-1)`
  - Return a list of the substrings in the string, using sep as the separator string.<br /><br />  sep<br />    The separator used to split the string.<br /><br />    When set to None (the default value), will split on any whitespace<br />    character (including \n \r \t \f and spaces) and will discard<br />    empty strings from the result.<br />  maxsplit<br />    Maximum number of splits.<br />    -1 (the default value) means no limit.<br /><br />Splitting starts at the front of the string and works to the end.<br /><br />Note, str.split() is mainly useful for data that has been intentionally<br />delimited.  With natural text that includes punctuation, consider using<br />the regular expression module.

- **splitlines**`(keepends=False)`
  - Return a list of the lines in the string, breaking at line boundaries.<br /><br />Line breaks are not included in the resulting list unless keepends is given and<br />true.

- **startswith**`(bound native)`
  - Return True if the string starts with the specified prefix, False otherwise.<br /><br />prefix<br />  A string or a tuple of strings to try.<br />start<br />  Optional start position. Default: start of the string.<br />end<br />  Optional stop position. Default: end of the string.

- **strip**`(chars=None, /)`
  - Return a copy of the string with leading and trailing whitespace removed.<br /><br />If chars is given and not None, remove characters in chars instead.

- **swapcase**`()`
  - Convert uppercase characters to lowercase and lowercase characters to uppercase.

- **title**`()`
  - Return a version of the string where each word is titlecased.<br /><br />More specifically, words start with uppercased characters and all remaining<br />cased characters have lower case.

- **translate**`(table, /)`
  - Replace each character in the string using the given translation table.<br /><br />  table<br />    Translation table, which must be a mapping of Unicode ordinals to<br />    Unicode ordinals, strings, or None.<br /><br />The table must implement lookup/indexing via __getitem__, for instance a<br />dictionary or list.  If this operation raises LookupError, the character is<br />left untouched.  Characters mapped to None are deleted.

- **upper**`()`
  - Return a copy of the string converted to uppercase.

- **zfill**`(width, /)`
  - Pad a numeric string with zeros on the left, to fill a field of the given width.<br /><br />The string is never truncated.




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




## Documentation §§§
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


