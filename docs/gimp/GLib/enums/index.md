---
layout: default
title: GLib.enums
---
# GLib.enums

## BookmarkFileError

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| INVALID_URI | 0 |
| INVALID_VALUE | 1 |
| APP_NOT_REGISTERED | 2 |
| URI_NOT_FOUND | 3 |
| READ | 4 |
| UNKNOWN_ENCODING | 5 |
| WRITE | 6 |
| FILE_NOT_FOUND | 7 |

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
## ChecksumType

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| MD5 | 0 |
| SHA1 | 1 |
| SHA256 | 2 |
| SHA512 | 3 |
| SHA384 | 4 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## ConvertError

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| NO_CONVERSION | 0 |
| ILLEGAL_SEQUENCE | 1 |
| FAILED | 2 |
| PARTIAL_INPUT | 3 |
| BAD_URI | 4 |
| NOT_ABSOLUTE_PATH | 5 |
| NO_MEMORY | 6 |
| EMBEDDED_NUL | 7 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## DateDMY

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| DAY | 0 |
| MONTH | 1 |
| YEAR | 2 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## DateMonth

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| BAD_MONTH | 0 |
| JANUARY | 1 |
| FEBRUARY | 2 |
| MARCH | 3 |
| APRIL | 4 |
| MAY | 5 |
| JUNE | 6 |
| JULY | 7 |
| AUGUST | 8 |
| SEPTEMBER | 9 |
| OCTOBER | 10 |
| NOVEMBER | 11 |
| DECEMBER | 12 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## DateWeekday

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| BAD_WEEKDAY | 0 |
| MONDAY | 1 |
| TUESDAY | 2 |
| WEDNESDAY | 3 |
| THURSDAY | 4 |
| FRIDAY | 5 |
| SATURDAY | 6 |
| SUNDAY | 7 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## ErrorType

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| UNKNOWN | 0 |
| UNEXP_EOF | 1 |
| UNEXP_EOF_IN_STRING | 2 |
| UNEXP_EOF_IN_COMMENT | 3 |
| NON_DIGIT_IN_CONST | 4 |
| DIGIT_RADIX | 5 |
| FLOAT_RADIX | 6 |
| FLOAT_MALFORMED | 7 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## FileError

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| EXIST | 0 |
| ISDIR | 1 |
| ACCES | 2 |
| NAMETOOLONG | 3 |
| NOENT | 4 |
| NOTDIR | 5 |
| NXIO | 6 |
| NODEV | 7 |
| ROFS | 8 |
| TXTBSY | 9 |
| FAULT | 10 |
| LOOP | 11 |
| NOSPC | 12 |
| NOMEM | 13 |
| MFILE | 14 |
| NFILE | 15 |
| BADF | 16 |
| INVAL | 17 |
| PIPE | 18 |
| AGAIN | 19 |
| INTR | 20 |
| IO | 21 |
| PERM | 22 |
| NOSYS | 23 |
| FAILED | 24 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## IOChannelError

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| FBIG | 0 |
| INVAL | 1 |
| IO | 2 |
| ISDIR | 3 |
| NOSPC | 4 |
| NXIO | 5 |
| OVERFLOW | 6 |
| PIPE | 7 |
| FAILED | 8 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## IOError

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| NONE | 0 |
| AGAIN | 1 |
| INVAL | 2 |
| UNKNOWN | 3 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## IOStatus

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| ERROR | 0 |
| NORMAL | 1 |
| EOF | 2 |
| AGAIN | 3 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## KeyFileError

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| UNKNOWN_ENCODING | 0 |
| PARSE | 1 |
| NOT_FOUND | 2 |
| KEY_NOT_FOUND | 3 |
| GROUP_NOT_FOUND | 4 |
| INVALID_VALUE | 5 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## LogWriterOutput

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| UNHANDLED | 0 |
| HANDLED | 1 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## MarkupError

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| BAD_UTF8 | 0 |
| EMPTY | 1 |
| PARSE | 2 |
| UNKNOWN_ELEMENT | 3 |
| UNKNOWN_ATTRIBUTE | 4 |
| INVALID_CONTENT | 5 |
| MISSING_ATTRIBUTE | 6 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## NormalizeMode

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| NFD | 0 |
| NFC | 1 |
| NFKD | 2 |
| NFKC | 3 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## NumberParserError

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| INVALID | 0 |
| OUT_OF_BOUNDS | 1 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## OnceStatus

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| NOTCALLED | 0 |
| PROGRESS | 1 |
| READY | 2 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## OptionArg

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| NONE | 0 |
| STRING | 1 |
| INT | 2 |
| CALLBACK | 3 |
| FILENAME | 4 |
| STRING_ARRAY | 5 |
| FILENAME_ARRAY | 6 |
| DOUBLE | 7 |
| INT64 | 8 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## OptionError

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| UNKNOWN_OPTION | 0 |
| BAD_VALUE | 1 |
| FAILED | 2 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## RegexError

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| COMPILE | 0 |
| OPTIMIZE | 1 |
| REPLACE | 2 |
| MATCH | 3 |
| INTERNAL | 4 |
| STRAY_BACKSLASH | 101 |
| MISSING_CONTROL_CHAR | 102 |
| UNRECOGNIZED_ESCAPE | 103 |
| QUANTIFIERS_OUT_OF_ORDER | 104 |
| QUANTIFIER_TOO_BIG | 105 |
| UNTERMINATED_CHARACTER_CLASS | 106 |
| INVALID_ESCAPE_IN_CHARACTER_CLASS | 107 |
| RANGE_OUT_OF_ORDER | 108 |
| NOTHING_TO_REPEAT | 109 |
| UNRECOGNIZED_CHARACTER | 112 |
| POSIX_NAMED_CLASS_OUTSIDE_CLASS | 113 |
| UNMATCHED_PARENTHESIS | 114 |
| INEXISTENT_SUBPATTERN_REFERENCE | 115 |
| UNTERMINATED_COMMENT | 118 |
| EXPRESSION_TOO_LARGE | 120 |
| MEMORY_ERROR | 121 |
| VARIABLE_LENGTH_LOOKBEHIND | 125 |
| MALFORMED_CONDITION | 126 |
| TOO_MANY_CONDITIONAL_BRANCHES | 127 |
| ASSERTION_EXPECTED | 128 |
| UNKNOWN_POSIX_CLASS_NAME | 130 |
| POSIX_COLLATING_ELEMENTS_NOT_SUPPORTED | 131 |
| HEX_CODE_TOO_LARGE | 134 |
| INVALID_CONDITION | 135 |
| SINGLE_BYTE_MATCH_IN_LOOKBEHIND | 136 |
| INFINITE_LOOP | 140 |
| MISSING_SUBPATTERN_NAME_TERMINATOR | 142 |
| DUPLICATE_SUBPATTERN_NAME | 143 |
| MALFORMED_PROPERTY | 146 |
| UNKNOWN_PROPERTY | 147 |
| SUBPATTERN_NAME_TOO_LONG | 148 |
| TOO_MANY_SUBPATTERNS | 149 |
| INVALID_OCTAL_VALUE | 151 |
| TOO_MANY_BRANCHES_IN_DEFINE | 154 |
| DEFINE_REPETION | 155 |
| INCONSISTENT_NEWLINE_OPTIONS | 156 |
| MISSING_BACK_REFERENCE | 157 |
| INVALID_RELATIVE_REFERENCE | 158 |
| BACKTRACKING_CONTROL_VERB_ARGUMENT_FORBIDDEN | 159 |
| UNKNOWN_BACKTRACKING_CONTROL_VERB | 160 |
| NUMBER_TOO_BIG | 161 |
| MISSING_SUBPATTERN_NAME | 162 |
| MISSING_DIGIT | 163 |
| INVALID_DATA_CHARACTER | 164 |
| EXTRA_SUBPATTERN_NAME | 165 |
| BACKTRACKING_CONTROL_VERB_ARGUMENT_REQUIRED | 166 |
| INVALID_CONTROL_CHAR | 168 |
| MISSING_NAME | 169 |
| NOT_SUPPORTED_IN_CLASS | 171 |
| TOO_MANY_FORWARD_REFERENCES | 172 |
| NAME_TOO_LONG | 175 |
| CHARACTER_VALUE_TOO_LARGE | 176 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## SeekType

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| CUR | 0 |
| SET | 1 |
| END | 2 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## ShellError

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| BAD_QUOTING | 0 |
| EMPTY_STRING | 1 |
| FAILED | 2 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## SliceConfig

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| ALWAYS_MALLOC | 1 |
| BYPASS_MAGAZINES | 2 |
| WORKING_SET_MSECS | 3 |
| COLOR_INCREMENT | 4 |
| CHUNK_SIZES | 5 |
| CONTENTION_COUNTER | 6 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## SpawnError

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| FORK | 0 |
| READ | 1 |
| CHDIR | 2 |
| ACCES | 3 |
| PERM | 4 |
| TOO_BIG | 5 |
| NOEXEC | 6 |
| NAMETOOLONG | 7 |
| NOENT | 8 |
| NOMEM | 9 |
| NOTDIR | 10 |
| LOOP | 11 |
| TXTBUSY | 12 |
| IO | 13 |
| NFILE | 14 |
| MFILE | 15 |
| INVAL | 16 |
| ISDIR | 17 |
| LIBBAD | 18 |
| FAILED | 19 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## TestFileType

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| DIST | 0 |
| BUILT | 1 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## TestLogType

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| NONE | 0 |
| ERROR | 1 |
| START_BINARY | 2 |
| LIST_CASE | 3 |
| SKIP_CASE | 4 |
| START_CASE | 5 |
| STOP_CASE | 6 |
| MIN_RESULT | 7 |
| MAX_RESULT | 8 |
| MESSAGE | 9 |
| START_SUITE | 10 |
| STOP_SUITE | 11 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## TestResult

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| SUCCESS | 0 |
| SKIPPED | 1 |
| FAILURE | 2 |
| INCOMPLETE | 3 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## ThreadError

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| THREAD_ERROR_AGAIN | 0 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## TimeType

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| STANDARD | 0 |
| DAYLIGHT | 1 |
| UNIVERSAL | 2 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## TokenType

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| EOF | 0 |
| LEFT_PAREN | 40 |
| RIGHT_PAREN | 41 |
| COMMA | 44 |
| EQUAL_SIGN | 61 |
| LEFT_BRACE | 91 |
| RIGHT_BRACE | 93 |
| LEFT_CURLY | 123 |
| RIGHT_CURLY | 125 |
| NONE | 256 |
| ERROR | 257 |
| CHAR | 258 |
| BINARY | 259 |
| OCTAL | 260 |
| INT | 261 |
| HEX | 262 |
| FLOAT | 263 |
| STRING | 264 |
| SYMBOL | 265 |
| IDENTIFIER | 266 |
| IDENTIFIER_NULL | 267 |
| COMMENT_SINGLE | 268 |
| COMMENT_MULTI | 269 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## TraverseType

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| IN_ORDER | 0 |
| PRE_ORDER | 1 |
| POST_ORDER | 2 |
| LEVEL_ORDER | 3 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## UnicodeBreakType

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| MANDATORY | 0 |
| CARRIAGE_RETURN | 1 |
| LINE_FEED | 2 |
| COMBINING_MARK | 3 |
| SURROGATE | 4 |
| ZERO_WIDTH_SPACE | 5 |
| INSEPARABLE | 6 |
| NON_BREAKING_GLUE | 7 |
| CONTINGENT | 8 |
| SPACE | 9 |
| AFTER | 10 |
| BEFORE | 11 |
| BEFORE_AND_AFTER | 12 |
| HYPHEN | 13 |
| NON_STARTER | 14 |
| OPEN_PUNCTUATION | 15 |
| CLOSE_PUNCTUATION | 16 |
| QUOTATION | 17 |
| EXCLAMATION | 18 |
| IDEOGRAPHIC | 19 |
| NUMERIC | 20 |
| INFIX_SEPARATOR | 21 |
| SYMBOL | 22 |
| ALPHABETIC | 23 |
| PREFIX | 24 |
| POSTFIX | 25 |
| COMPLEX_CONTEXT | 26 |
| AMBIGUOUS | 27 |
| UNKNOWN | 28 |
| NEXT_LINE | 29 |
| WORD_JOINER | 30 |
| HANGUL_L_JAMO | 31 |
| HANGUL_V_JAMO | 32 |
| HANGUL_T_JAMO | 33 |
| HANGUL_LV_SYLLABLE | 34 |
| HANGUL_LVT_SYLLABLE | 35 |
| CLOSE_PARENTHESIS | 36 |
| CONDITIONAL_JAPANESE_STARTER | 37 |
| HEBREW_LETTER | 38 |
| REGIONAL_INDICATOR | 39 |
| EMOJI_BASE | 40 |
| EMOJI_MODIFIER | 41 |
| ZERO_WIDTH_JOINER | 42 |
| AKSARA | 43 |
| AKSARA_PRE_BASE | 44 |
| AKSARA_START | 45 |
| VIRAMA_FINAL | 46 |
| VIRAMA | 47 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## UnicodeScript

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| INVALID_CODE | -1 |
| COMMON | 0 |
| INHERITED | 1 |
| ARABIC | 2 |
| ARMENIAN | 3 |
| BENGALI | 4 |
| BOPOMOFO | 5 |
| CHEROKEE | 6 |
| COPTIC | 7 |
| CYRILLIC | 8 |
| DESERET | 9 |
| DEVANAGARI | 10 |
| ETHIOPIC | 11 |
| GEORGIAN | 12 |
| GOTHIC | 13 |
| GREEK | 14 |
| GUJARATI | 15 |
| GURMUKHI | 16 |
| HAN | 17 |
| HANGUL | 18 |
| HEBREW | 19 |
| HIRAGANA | 20 |
| KANNADA | 21 |
| KATAKANA | 22 |
| KHMER | 23 |
| LAO | 24 |
| LATIN | 25 |
| MALAYALAM | 26 |
| MONGOLIAN | 27 |
| MYANMAR | 28 |
| OGHAM | 29 |
| OLD_ITALIC | 30 |
| ORIYA | 31 |
| RUNIC | 32 |
| SINHALA | 33 |
| SYRIAC | 34 |
| TAMIL | 35 |
| TELUGU | 36 |
| THAANA | 37 |
| THAI | 38 |
| TIBETAN | 39 |
| CANADIAN_ABORIGINAL | 40 |
| YI | 41 |
| TAGALOG | 42 |
| HANUNOO | 43 |
| BUHID | 44 |
| TAGBANWA | 45 |
| BRAILLE | 46 |
| CYPRIOT | 47 |
| LIMBU | 48 |
| OSMANYA | 49 |
| SHAVIAN | 50 |
| LINEAR_B | 51 |
| TAI_LE | 52 |
| UGARITIC | 53 |
| NEW_TAI_LUE | 54 |
| BUGINESE | 55 |
| GLAGOLITIC | 56 |
| TIFINAGH | 57 |
| SYLOTI_NAGRI | 58 |
| OLD_PERSIAN | 59 |
| KHAROSHTHI | 60 |
| UNKNOWN | 61 |
| BALINESE | 62 |
| CUNEIFORM | 63 |
| PHOENICIAN | 64 |
| PHAGS_PA | 65 |
| NKO | 66 |
| KAYAH_LI | 67 |
| LEPCHA | 68 |
| REJANG | 69 |
| SUNDANESE | 70 |
| SAURASHTRA | 71 |
| CHAM | 72 |
| OL_CHIKI | 73 |
| VAI | 74 |
| CARIAN | 75 |
| LYCIAN | 76 |
| LYDIAN | 77 |
| AVESTAN | 78 |
| BAMUM | 79 |
| EGYPTIAN_HIEROGLYPHS | 80 |
| IMPERIAL_ARAMAIC | 81 |
| INSCRIPTIONAL_PAHLAVI | 82 |
| INSCRIPTIONAL_PARTHIAN | 83 |
| JAVANESE | 84 |
| KAITHI | 85 |
| LISU | 86 |
| MEETEI_MAYEK | 87 |
| OLD_SOUTH_ARABIAN | 88 |
| OLD_TURKIC | 89 |
| SAMARITAN | 90 |
| TAI_THAM | 91 |
| TAI_VIET | 92 |
| BATAK | 93 |
| BRAHMI | 94 |
| MANDAIC | 95 |
| CHAKMA | 96 |
| MEROITIC_CURSIVE | 97 |
| MEROITIC_HIEROGLYPHS | 98 |
| MIAO | 99 |
| SHARADA | 100 |
| SORA_SOMPENG | 101 |
| TAKRI | 102 |
| BASSA_VAH | 103 |
| CAUCASIAN_ALBANIAN | 104 |
| DUPLOYAN | 105 |
| ELBASAN | 106 |
| GRANTHA | 107 |
| KHOJKI | 108 |
| KHUDAWADI | 109 |
| LINEAR_A | 110 |
| MAHAJANI | 111 |
| MANICHAEAN | 112 |
| MENDE_KIKAKUI | 113 |
| MODI | 114 |
| MRO | 115 |
| NABATAEAN | 116 |
| OLD_NORTH_ARABIAN | 117 |
| OLD_PERMIC | 118 |
| PAHAWH_HMONG | 119 |
| PALMYRENE | 120 |
| PAU_CIN_HAU | 121 |
| PSALTER_PAHLAVI | 122 |
| SIDDHAM | 123 |
| TIRHUTA | 124 |
| WARANG_CITI | 125 |
| AHOM | 126 |
| ANATOLIAN_HIEROGLYPHS | 127 |
| HATRAN | 128 |
| MULTANI | 129 |
| OLD_HUNGARIAN | 130 |
| SIGNWRITING | 131 |
| ADLAM | 132 |
| BHAIKSUKI | 133 |
| MARCHEN | 134 |
| NEWA | 135 |
| OSAGE | 136 |
| TANGUT | 137 |
| MASARAM_GONDI | 138 |
| NUSHU | 139 |
| SOYOMBO | 140 |
| ZANABAZAR_SQUARE | 141 |
| DOGRA | 142 |
| GUNJALA_GONDI | 143 |
| HANIFI_ROHINGYA | 144 |
| MAKASAR | 145 |
| MEDEFAIDRIN | 146 |
| OLD_SOGDIAN | 147 |
| SOGDIAN | 148 |
| ELYMAIC | 149 |
| NANDINAGARI | 150 |
| NYIAKENG_PUACHUE_HMONG | 151 |
| WANCHO | 152 |
| CHORASMIAN | 153 |
| DIVES_AKURU | 154 |
| KHITAN_SMALL_SCRIPT | 155 |
| YEZIDI | 156 |
| CYPRO_MINOAN | 157 |
| OLD_UYGHUR | 158 |
| TANGSA | 159 |
| TOTO | 160 |
| VITHKUQI | 161 |
| MATH | 162 |
| KAWI | 163 |
| NAG_MUNDARI | 164 |
| TODHRI | 165 |
| GARAY | 166 |
| TULU_TIGALARI | 167 |
| SUNUWAR | 168 |
| GURUNG_KHEMA | 169 |
| KIRAT_RAI | 170 |
| OL_ONAL | 171 |

### Other runtime attributes ‡


### Runtime functions ††
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

- **from_iso15924**`(*args, **kwargs)`
  - from_iso15924(iso15924:int) -> GLib.UnicodeScript

- **is_integer**`(self, /)`
  - Returns True. Exists for duck type compatibility with float.is_integer.

- **to_bytes**`(self, /, length=1, byteorder='big', *, signed=False)`
  - Return an array of bytes representing an integer.<br /><br />length<br />  Length of bytes object to use.  An OverflowError is raised if the<br />  integer is not representable with the given number of bytes.  Default<br />  is length 1.<br />byteorder<br />  The byte order used to represent the integer.  If byteorder is 'big',<br />  the most significant byte is at the beginning of the byte array.  If<br />  byteorder is 'little', the most significant byte is at the end of the<br />  byte array.  To request the native byte order of the host system, use<br />  sys.byteorder as the byte order value.  Default is to use 'big'.<br />signed<br />  Determines whether two's complement is used to represent the integer.<br />  If signed is False and a negative integer is given, an OverflowError<br />  is raised.

- **to_iso15924**`(*args, **kwargs)`
  - to_iso15924(script:GLib.UnicodeScript) -> int


<br>
## UnicodeType

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| CONTROL | 0 |
| FORMAT | 1 |
| UNASSIGNED | 2 |
| PRIVATE_USE | 3 |
| SURROGATE | 4 |
| LOWERCASE_LETTER | 5 |
| MODIFIER_LETTER | 6 |
| OTHER_LETTER | 7 |
| TITLECASE_LETTER | 8 |
| UPPERCASE_LETTER | 9 |
| SPACING_MARK | 10 |
| ENCLOSING_MARK | 11 |
| NON_SPACING_MARK | 12 |
| DECIMAL_NUMBER | 13 |
| LETTER_NUMBER | 14 |
| OTHER_NUMBER | 15 |
| CONNECT_PUNCTUATION | 16 |
| DASH_PUNCTUATION | 17 |
| CLOSE_PUNCTUATION | 18 |
| FINAL_PUNCTUATION | 19 |
| INITIAL_PUNCTUATION | 20 |
| OTHER_PUNCTUATION | 21 |
| OPEN_PUNCTUATION | 22 |
| CURRENCY_SYMBOL | 23 |
| MODIFIER_SYMBOL | 24 |
| MATH_SYMBOL | 25 |
| OTHER_SYMBOL | 26 |
| LINE_SEPARATOR | 27 |
| PARAGRAPH_SEPARATOR | 28 |
| SPACE_SEPARATOR | 29 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## UnixPipeEnd

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| READ | 0 |
| WRITE | 1 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## UriError

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| FAILED | 0 |
| BAD_SCHEME | 1 |
| BAD_USER | 2 |
| BAD_PASSWORD | 3 |
| BAD_AUTH_PARAMS | 4 |
| BAD_HOST | 5 |
| BAD_PORT | 6 |
| BAD_PATH | 7 |
| BAD_QUERY | 8 |
| BAD_FRAGMENT | 9 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## UserDirectory

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| DIRECTORY_DESKTOP | 0 |
| DIRECTORY_DOCUMENTS | 1 |
| DIRECTORY_DOWNLOAD | 2 |
| DIRECTORY_MUSIC | 3 |
| DIRECTORY_PICTURES | 4 |
| DIRECTORY_PUBLIC_SHARE | 5 |
| DIRECTORY_TEMPLATES | 6 |
| DIRECTORY_VIDEOS | 7 |
| N_DIRECTORIES | 8 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## VariantClass

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| TUPLE | 40 |
| ARRAY | 97 |
| BOOLEAN | 98 |
| DOUBLE | 100 |
| SIGNATURE | 103 |
| HANDLE | 104 |
| INT32 | 105 |
| MAYBE | 109 |
| INT16 | 110 |
| OBJECT_PATH | 111 |
| UINT16 | 113 |
| STRING | 115 |
| UINT64 | 116 |
| UINT32 | 117 |
| VARIANT | 118 |
| INT64 | 120 |
| BYTE | 121 |
| DICT_ENTRY | 123 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## VariantParseError

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| FAILED | 0 |
| BASIC_TYPE_EXPECTED | 1 |
| CANNOT_INFER_TYPE | 2 |
| DEFINITE_TYPE_EXPECTED | 3 |
| INPUT_NOT_AT_END | 4 |
| INVALID_CHARACTER | 5 |
| INVALID_FORMAT_STRING | 6 |
| INVALID_OBJECT_PATH | 7 |
| INVALID_SIGNATURE | 8 |
| INVALID_TYPE_STRING | 9 |
| NO_COMMON_TYPE | 10 |
| NUMBER_OUT_OF_RANGE | 11 |
| NUMBER_TOO_BIG | 12 |
| TYPE_ERROR | 13 |
| UNEXPECTED_TOKEN | 14 |
| UNKNOWN_KEYWORD | 15 |
| UNTERMINATED_STRING_CONSTANT | 16 |
| VALUE_EXPECTED | 17 |
| RECURSION | 18 |

### Other runtime attributes ‡


### Runtime functions †

<br>