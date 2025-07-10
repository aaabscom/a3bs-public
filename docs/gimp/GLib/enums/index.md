---
layout: default
title: GLib.enums
---
# GLib.enums

## BookmarkFileError

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| APP_NOT_REGISTERED | 2 |
| FILE_NOT_FOUND | 7 |
| INVALID_URI | 0 |
| INVALID_VALUE | 1 |
| READ | 4 |
| UNKNOWN_ENCODING | 5 |
| URI_NOT_FOUND | 3 |
| WRITE | 6 |

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


## ChecksumType

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| MD5 | 0 |
| SHA1 | 1 |
| SHA256 | 2 |
| SHA384 | 4 |
| SHA512 | 3 |

### Other runtime attributes ‡


### Runtime functions †

## ConvertError

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| BAD_URI | 4 |
| EMBEDDED_NUL | 7 |
| FAILED | 2 |
| ILLEGAL_SEQUENCE | 1 |
| NOT_ABSOLUTE_PATH | 5 |
| NO_CONVERSION | 0 |
| NO_MEMORY | 6 |
| PARTIAL_INPUT | 3 |

### Other runtime attributes ‡


### Runtime functions †

## DateDMY

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| DAY | 0 |
| MONTH | 1 |
| YEAR | 2 |

### Other runtime attributes ‡


### Runtime functions †

## DateMonth

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| APRIL | 4 |
| AUGUST | 8 |
| BAD_MONTH | 0 |
| DECEMBER | 12 |
| FEBRUARY | 2 |
| JANUARY | 1 |
| JULY | 7 |
| JUNE | 6 |
| MARCH | 3 |
| MAY | 5 |
| NOVEMBER | 11 |
| OCTOBER | 10 |
| SEPTEMBER | 9 |

### Other runtime attributes ‡


### Runtime functions †

## DateWeekday

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| BAD_WEEKDAY | 0 |
| FRIDAY | 5 |
| MONDAY | 1 |
| SATURDAY | 6 |
| SUNDAY | 7 |
| THURSDAY | 4 |
| TUESDAY | 2 |
| WEDNESDAY | 3 |

### Other runtime attributes ‡


### Runtime functions †

## ErrorType

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| DIGIT_RADIX | 5 |
| FLOAT_MALFORMED | 7 |
| FLOAT_RADIX | 6 |
| NON_DIGIT_IN_CONST | 4 |
| UNEXP_EOF | 1 |
| UNEXP_EOF_IN_COMMENT | 3 |
| UNEXP_EOF_IN_STRING | 2 |
| UNKNOWN | 0 |

### Other runtime attributes ‡


### Runtime functions †

## FileError

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| ACCES | 2 |
| AGAIN | 19 |
| BADF | 16 |
| EXIST | 0 |
| FAILED | 24 |
| FAULT | 10 |
| INTR | 20 |
| INVAL | 17 |
| IO | 21 |
| ISDIR | 1 |
| LOOP | 11 |
| MFILE | 14 |
| NAMETOOLONG | 3 |
| NFILE | 15 |
| NODEV | 7 |
| NOENT | 4 |
| NOMEM | 13 |
| NOSPC | 12 |
| NOSYS | 23 |
| NOTDIR | 5 |
| NXIO | 6 |
| PERM | 22 |
| PIPE | 18 |
| ROFS | 8 |
| TXTBSY | 9 |

### Other runtime attributes ‡


### Runtime functions †

## IOChannelError

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| FAILED | 8 |
| FBIG | 0 |
| INVAL | 1 |
| IO | 2 |
| ISDIR | 3 |
| NOSPC | 4 |
| NXIO | 5 |
| OVERFLOW | 6 |
| PIPE | 7 |

### Other runtime attributes ‡


### Runtime functions †

## IOError

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| AGAIN | 1 |
| INVAL | 2 |
| NONE | 0 |
| UNKNOWN | 3 |

### Other runtime attributes ‡


### Runtime functions †

## IOStatus

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| AGAIN | 3 |
| EOF | 2 |
| ERROR | 0 |
| NORMAL | 1 |

### Other runtime attributes ‡


### Runtime functions †

## KeyFileError

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| GROUP_NOT_FOUND | 4 |
| INVALID_VALUE | 5 |
| KEY_NOT_FOUND | 3 |
| NOT_FOUND | 2 |
| PARSE | 1 |
| UNKNOWN_ENCODING | 0 |

### Other runtime attributes ‡


### Runtime functions †

## LogWriterOutput

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| HANDLED | 1 |
| UNHANDLED | 0 |

### Other runtime attributes ‡


### Runtime functions †

## MarkupError

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| BAD_UTF8 | 0 |
| EMPTY | 1 |
| INVALID_CONTENT | 5 |
| MISSING_ATTRIBUTE | 6 |
| PARSE | 2 |
| UNKNOWN_ATTRIBUTE | 4 |
| UNKNOWN_ELEMENT | 3 |

### Other runtime attributes ‡


### Runtime functions †

## NormalizeMode

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| ALL | 2 |
| ALL_COMPOSE | 3 |
| DEFAULT | 0 |
| DEFAULT_COMPOSE | 1 |
| NFC | 1 |
| NFD | 0 |
| NFKC | 3 |
| NFKD | 2 |

### Other runtime attributes ‡


### Runtime functions †

## NumberParserError

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| INVALID | 0 |
| OUT_OF_BOUNDS | 1 |

### Other runtime attributes ‡


### Runtime functions †

## OnceStatus

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| NOTCALLED | 0 |
| PROGRESS | 1 |
| READY | 2 |

### Other runtime attributes ‡


### Runtime functions †

## OptionArg

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| CALLBACK | 3 |
| DOUBLE | 7 |
| FILENAME | 4 |
| FILENAME_ARRAY | 6 |
| INT | 2 |
| INT64 | 8 |
| NONE | 0 |
| STRING | 1 |
| STRING_ARRAY | 5 |

### Other runtime attributes ‡


### Runtime functions †

## OptionError

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| BAD_VALUE | 1 |
| FAILED | 2 |
| UNKNOWN_OPTION | 0 |

### Other runtime attributes ‡


### Runtime functions †

## RegexError

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| ASSERTION_EXPECTED | 128 |
| BACKTRACKING_CONTROL_VERB_ARGUMENT_FORBIDDEN | 159 |
| BACKTRACKING_CONTROL_VERB_ARGUMENT_REQUIRED | 166 |
| CHARACTER_VALUE_TOO_LARGE | 176 |
| COMPILE | 0 |
| DEFINE_REPETION | 155 |
| DUPLICATE_SUBPATTERN_NAME | 143 |
| EXPRESSION_TOO_LARGE | 120 |
| EXTRA_SUBPATTERN_NAME | 165 |
| HEX_CODE_TOO_LARGE | 134 |
| INCONSISTENT_NEWLINE_OPTIONS | 156 |
| INEXISTENT_SUBPATTERN_REFERENCE | 115 |
| INFINITE_LOOP | 140 |
| INTERNAL | 4 |
| INVALID_CONDITION | 135 |
| INVALID_CONTROL_CHAR | 168 |
| INVALID_DATA_CHARACTER | 164 |
| INVALID_ESCAPE_IN_CHARACTER_CLASS | 107 |
| INVALID_OCTAL_VALUE | 151 |
| INVALID_RELATIVE_REFERENCE | 158 |
| MALFORMED_CONDITION | 126 |
| MALFORMED_PROPERTY | 146 |
| MATCH | 3 |
| MEMORY_ERROR | 121 |
| MISSING_BACK_REFERENCE | 157 |
| MISSING_CONTROL_CHAR | 102 |
| MISSING_DIGIT | 163 |
| MISSING_NAME | 169 |
| MISSING_SUBPATTERN_NAME | 162 |
| MISSING_SUBPATTERN_NAME_TERMINATOR | 142 |
| NAME_TOO_LONG | 175 |
| NOTHING_TO_REPEAT | 109 |
| NOT_SUPPORTED_IN_CLASS | 171 |
| NUMBER_TOO_BIG | 161 |
| OPTIMIZE | 1 |
| POSIX_COLLATING_ELEMENTS_NOT_SUPPORTED | 131 |
| POSIX_NAMED_CLASS_OUTSIDE_CLASS | 113 |
| QUANTIFIERS_OUT_OF_ORDER | 104 |
| QUANTIFIER_TOO_BIG | 105 |
| RANGE_OUT_OF_ORDER | 108 |
| REPLACE | 2 |
| SINGLE_BYTE_MATCH_IN_LOOKBEHIND | 136 |
| STRAY_BACKSLASH | 101 |
| SUBPATTERN_NAME_TOO_LONG | 148 |
| TOO_MANY_BRANCHES_IN_DEFINE | 154 |
| TOO_MANY_CONDITIONAL_BRANCHES | 127 |
| TOO_MANY_FORWARD_REFERENCES | 172 |
| TOO_MANY_SUBPATTERNS | 149 |
| UNKNOWN_BACKTRACKING_CONTROL_VERB | 160 |
| UNKNOWN_POSIX_CLASS_NAME | 130 |
| UNKNOWN_PROPERTY | 147 |
| UNMATCHED_PARENTHESIS | 114 |
| UNRECOGNIZED_CHARACTER | 112 |
| UNRECOGNIZED_ESCAPE | 103 |
| UNTERMINATED_CHARACTER_CLASS | 106 |
| UNTERMINATED_COMMENT | 118 |
| VARIABLE_LENGTH_LOOKBEHIND | 125 |

### Other runtime attributes ‡


### Runtime functions †

## SeekType

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| CUR | 0 |
| END | 2 |
| SET | 1 |

### Other runtime attributes ‡


### Runtime functions †

## ShellError

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| BAD_QUOTING | 0 |
| EMPTY_STRING | 1 |
| FAILED | 2 |

### Other runtime attributes ‡


### Runtime functions †

## SliceConfig

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| ALWAYS_MALLOC | 1 |
| BYPASS_MAGAZINES | 2 |
| CHUNK_SIZES | 5 |
| COLOR_INCREMENT | 4 |
| CONTENTION_COUNTER | 6 |
| WORKING_SET_MSECS | 3 |

### Other runtime attributes ‡


### Runtime functions †

## SpawnError

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| 2BIG | 5 |
| ACCES | 3 |
| CHDIR | 2 |
| FAILED | 19 |
| FORK | 0 |
| INVAL | 16 |
| IO | 13 |
| ISDIR | 17 |
| LIBBAD | 18 |
| LOOP | 11 |
| MFILE | 15 |
| NAMETOOLONG | 7 |
| NFILE | 14 |
| NOENT | 8 |
| NOEXEC | 6 |
| NOMEM | 9 |
| NOTDIR | 10 |
| PERM | 4 |
| READ | 1 |
| TOO_BIG | 5 |
| TXTBUSY | 12 |

### Other runtime attributes ‡


### Runtime functions †

## TestFileType

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| BUILT | 1 |
| DIST | 0 |

### Other runtime attributes ‡


### Runtime functions †

## TestLogType

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| ERROR | 1 |
| LIST_CASE | 3 |
| MAX_RESULT | 8 |
| MESSAGE | 9 |
| MIN_RESULT | 7 |
| NONE | 0 |
| SKIP_CASE | 4 |
| START_BINARY | 2 |
| START_CASE | 5 |
| START_SUITE | 10 |
| STOP_CASE | 6 |
| STOP_SUITE | 11 |

### Other runtime attributes ‡


### Runtime functions †

## TestResult

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| FAILURE | 2 |
| INCOMPLETE | 3 |
| SKIPPED | 1 |
| SUCCESS | 0 |

### Other runtime attributes ‡


### Runtime functions †

## ThreadError

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| THREAD_ERROR_AGAIN | 0 |

### Other runtime attributes ‡


### Runtime functions †

## TimeType

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| DAYLIGHT | 1 |
| STANDARD | 0 |
| UNIVERSAL | 2 |

### Other runtime attributes ‡


### Runtime functions †

## TokenType

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| BINARY | 259 |
| CHAR | 258 |
| COMMA | 44 |
| COMMENT_MULTI | 269 |
| COMMENT_SINGLE | 268 |
| EOF | 0 |
| EQUAL_SIGN | 61 |
| ERROR | 257 |
| FLOAT | 263 |
| HEX | 262 |
| IDENTIFIER | 266 |
| IDENTIFIER_NULL | 267 |
| INT | 261 |
| LEFT_BRACE | 91 |
| LEFT_CURLY | 123 |
| LEFT_PAREN | 40 |
| NONE | 256 |
| OCTAL | 260 |
| RIGHT_BRACE | 93 |
| RIGHT_CURLY | 125 |
| RIGHT_PAREN | 41 |
| STRING | 264 |
| SYMBOL | 265 |

### Other runtime attributes ‡


### Runtime functions †

## TraverseType

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| IN_ORDER | 0 |
| LEVEL_ORDER | 3 |
| POST_ORDER | 2 |
| PRE_ORDER | 1 |

### Other runtime attributes ‡


### Runtime functions †

## UnicodeBreakType

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| AFTER | 10 |
| AKSARA | 43 |
| AKSARA_PRE_BASE | 44 |
| AKSARA_START | 45 |
| ALPHABETIC | 23 |
| AMBIGUOUS | 27 |
| BEFORE | 11 |
| BEFORE_AND_AFTER | 12 |
| CARRIAGE_RETURN | 1 |
| CLOSE_PARANTHESIS | 36 |
| CLOSE_PARENTHESIS | 36 |
| CLOSE_PUNCTUATION | 16 |
| COMBINING_MARK | 3 |
| COMPLEX_CONTEXT | 26 |
| CONDITIONAL_JAPANESE_STARTER | 37 |
| CONTINGENT | 8 |
| EMOJI_BASE | 40 |
| EMOJI_MODIFIER | 41 |
| EXCLAMATION | 18 |
| HANGUL_LVT_SYLLABLE | 35 |
| HANGUL_LV_SYLLABLE | 34 |
| HANGUL_L_JAMO | 31 |
| HANGUL_T_JAMO | 33 |
| HANGUL_V_JAMO | 32 |
| HEBREW_LETTER | 38 |
| HYPHEN | 13 |
| IDEOGRAPHIC | 19 |
| INFIX_SEPARATOR | 21 |
| INSEPARABLE | 6 |
| LINE_FEED | 2 |
| MANDATORY | 0 |
| NEXT_LINE | 29 |
| NON_BREAKING_GLUE | 7 |
| NON_STARTER | 14 |
| NUMERIC | 20 |
| OPEN_PUNCTUATION | 15 |
| POSTFIX | 25 |
| PREFIX | 24 |
| QUOTATION | 17 |
| REGIONAL_INDICATOR | 39 |
| SPACE | 9 |
| SURROGATE | 4 |
| SYMBOL | 22 |
| UNKNOWN | 28 |
| VIRAMA | 47 |
| VIRAMA_FINAL | 46 |
| WORD_JOINER | 30 |
| ZERO_WIDTH_JOINER | 42 |
| ZERO_WIDTH_SPACE | 5 |

### Other runtime attributes ‡


### Runtime functions †

## UnicodeScript

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| ADLAM | 132 |
| AHOM | 126 |
| ANATOLIAN_HIEROGLYPHS | 127 |
| ARABIC | 2 |
| ARMENIAN | 3 |
| AVESTAN | 78 |
| BALINESE | 62 |
| BAMUM | 79 |
| BASSA_VAH | 103 |
| BATAK | 93 |
| BENGALI | 4 |
| BHAIKSUKI | 133 |
| BOPOMOFO | 5 |
| BRAHMI | 94 |
| BRAILLE | 46 |
| BUGINESE | 55 |
| BUHID | 44 |
| CANADIAN_ABORIGINAL | 40 |
| CARIAN | 75 |
| CAUCASIAN_ALBANIAN | 104 |
| CHAKMA | 96 |
| CHAM | 72 |
| CHEROKEE | 6 |
| CHORASMIAN | 153 |
| COMMON | 0 |
| COPTIC | 7 |
| CUNEIFORM | 63 |
| CYPRIOT | 47 |
| CYPRO_MINOAN | 157 |
| CYRILLIC | 8 |
| DESERET | 9 |
| DEVANAGARI | 10 |
| DIVES_AKURU | 154 |
| DOGRA | 142 |
| DUPLOYAN | 105 |
| EGYPTIAN_HIEROGLYPHS | 80 |
| ELBASAN | 106 |
| ELYMAIC | 149 |
| ETHIOPIC | 11 |
| GARAY | 166 |
| GEORGIAN | 12 |
| GLAGOLITIC | 56 |
| GOTHIC | 13 |
| GRANTHA | 107 |
| GREEK | 14 |
| GUJARATI | 15 |
| GUNJALA_GONDI | 143 |
| GURMUKHI | 16 |
| GURUNG_KHEMA | 169 |
| HAN | 17 |
| HANGUL | 18 |
| HANIFI_ROHINGYA | 144 |
| HANUNOO | 43 |
| HATRAN | 128 |
| HEBREW | 19 |
| HIRAGANA | 20 |
| IMPERIAL_ARAMAIC | 81 |
| INHERITED | 1 |
| INSCRIPTIONAL_PAHLAVI | 82 |
| INSCRIPTIONAL_PARTHIAN | 83 |
| INVALID_CODE | -1 |
| JAVANESE | 84 |
| KAITHI | 85 |
| KANNADA | 21 |
| KATAKANA | 22 |
| KAWI | 163 |
| KAYAH_LI | 67 |
| KHAROSHTHI | 60 |
| KHITAN_SMALL_SCRIPT | 155 |
| KHMER | 23 |
| KHOJKI | 108 |
| KHUDAWADI | 109 |
| KIRAT_RAI | 170 |
| LAO | 24 |
| LATIN | 25 |
| LEPCHA | 68 |
| LIMBU | 48 |
| LINEAR_A | 110 |
| LINEAR_B | 51 |
| LISU | 86 |
| LYCIAN | 76 |
| LYDIAN | 77 |
| MAHAJANI | 111 |
| MAKASAR | 145 |
| MALAYALAM | 26 |
| MANDAIC | 95 |
| MANICHAEAN | 112 |
| MARCHEN | 134 |
| MASARAM_GONDI | 138 |
| MATH | 162 |
| MEDEFAIDRIN | 146 |
| MEETEI_MAYEK | 87 |
| MENDE_KIKAKUI | 113 |
| MEROITIC_CURSIVE | 97 |
| MEROITIC_HIEROGLYPHS | 98 |
| MIAO | 99 |
| MODI | 114 |
| MONGOLIAN | 27 |
| MRO | 115 |
| MULTANI | 129 |
| MYANMAR | 28 |
| NABATAEAN | 116 |
| NAG_MUNDARI | 164 |
| NANDINAGARI | 150 |
| NEWA | 135 |
| NEW_TAI_LUE | 54 |
| NKO | 66 |
| NUSHU | 139 |
| NYIAKENG_PUACHUE_HMONG | 151 |
| OGHAM | 29 |
| OLD_HUNGARIAN | 130 |
| OLD_ITALIC | 30 |
| OLD_NORTH_ARABIAN | 117 |
| OLD_PERMIC | 118 |
| OLD_PERSIAN | 59 |
| OLD_SOGDIAN | 147 |
| OLD_SOUTH_ARABIAN | 88 |
| OLD_TURKIC | 89 |
| OLD_UYGHUR | 158 |
| OL_CHIKI | 73 |
| OL_ONAL | 171 |
| ORIYA | 31 |
| OSAGE | 136 |
| OSMANYA | 49 |
| PAHAWH_HMONG | 119 |
| PALMYRENE | 120 |
| PAU_CIN_HAU | 121 |
| PHAGS_PA | 65 |
| PHOENICIAN | 64 |
| PSALTER_PAHLAVI | 122 |
| REJANG | 69 |
| RUNIC | 32 |
| SAMARITAN | 90 |
| SAURASHTRA | 71 |
| SHARADA | 100 |
| SHAVIAN | 50 |
| SIDDHAM | 123 |
| SIGNWRITING | 131 |
| SINHALA | 33 |
| SOGDIAN | 148 |
| SORA_SOMPENG | 101 |
| SOYOMBO | 140 |
| SUNDANESE | 70 |
| SUNUWAR | 168 |
| SYLOTI_NAGRI | 58 |
| SYRIAC | 34 |
| TAGALOG | 42 |
| TAGBANWA | 45 |
| TAI_LE | 52 |
| TAI_THAM | 91 |
| TAI_VIET | 92 |
| TAKRI | 102 |
| TAMIL | 35 |
| TANGSA | 159 |
| TANGUT | 137 |
| TELUGU | 36 |
| THAANA | 37 |
| THAI | 38 |
| TIBETAN | 39 |
| TIFINAGH | 57 |
| TIRHUTA | 124 |
| TODHRI | 165 |
| TOTO | 160 |
| TULU_TIGALARI | 167 |
| UGARITIC | 53 |
| UNKNOWN | 61 |
| VAI | 74 |
| VITHKUQI | 161 |
| WANCHO | 152 |
| WARANG_CITI | 125 |
| YEZIDI | 156 |
| YI | 41 |
| ZANABAZAR_SQUARE | 141 |

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


## UnicodeType

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| CLOSE_PUNCTUATION | 18 |
| CONNECT_PUNCTUATION | 16 |
| CONTROL | 0 |
| CURRENCY_SYMBOL | 23 |
| DASH_PUNCTUATION | 17 |
| DECIMAL_NUMBER | 13 |
| ENCLOSING_MARK | 11 |
| FINAL_PUNCTUATION | 19 |
| FORMAT | 1 |
| INITIAL_PUNCTUATION | 20 |
| LETTER_NUMBER | 14 |
| LINE_SEPARATOR | 27 |
| LOWERCASE_LETTER | 5 |
| MATH_SYMBOL | 25 |
| MODIFIER_LETTER | 6 |
| MODIFIER_SYMBOL | 24 |
| NON_SPACING_MARK | 12 |
| OPEN_PUNCTUATION | 22 |
| OTHER_LETTER | 7 |
| OTHER_NUMBER | 15 |
| OTHER_PUNCTUATION | 21 |
| OTHER_SYMBOL | 26 |
| PARAGRAPH_SEPARATOR | 28 |
| PRIVATE_USE | 3 |
| SPACE_SEPARATOR | 29 |
| SPACING_MARK | 10 |
| SURROGATE | 4 |
| TITLECASE_LETTER | 8 |
| UNASSIGNED | 2 |
| UPPERCASE_LETTER | 9 |

### Other runtime attributes ‡


### Runtime functions †

## UnixPipeEnd

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| READ | 0 |
| WRITE | 1 |

### Other runtime attributes ‡


### Runtime functions †

## UriError

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| BAD_AUTH_PARAMS | 4 |
| BAD_FRAGMENT | 9 |
| BAD_HOST | 5 |
| BAD_PASSWORD | 3 |
| BAD_PATH | 7 |
| BAD_PORT | 6 |
| BAD_QUERY | 8 |
| BAD_SCHEME | 1 |
| BAD_USER | 2 |
| FAILED | 0 |

### Other runtime attributes ‡


### Runtime functions †

## UserDirectory

### Runtime attributes

| Name | Value |
|------------------------|---------------|
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

## VariantClass

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| ARRAY | 97 |
| BOOLEAN | 98 |
| BYTE | 121 |
| DICT_ENTRY | 123 |
| DOUBLE | 100 |
| HANDLE | 104 |
| INT16 | 110 |
| INT32 | 105 |
| INT64 | 120 |
| MAYBE | 109 |
| OBJECT_PATH | 111 |
| SIGNATURE | 103 |
| STRING | 115 |
| TUPLE | 40 |
| UINT16 | 113 |
| UINT32 | 117 |
| UINT64 | 116 |
| VARIANT | 118 |

### Other runtime attributes ‡


### Runtime functions †

## VariantParseError

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| BASIC_TYPE_EXPECTED | 1 |
| CANNOT_INFER_TYPE | 2 |
| DEFINITE_TYPE_EXPECTED | 3 |
| FAILED | 0 |
| INPUT_NOT_AT_END | 4 |
| INVALID_CHARACTER | 5 |
| INVALID_FORMAT_STRING | 6 |
| INVALID_OBJECT_PATH | 7 |
| INVALID_SIGNATURE | 8 |
| INVALID_TYPE_STRING | 9 |
| NO_COMMON_TYPE | 10 |
| NUMBER_OUT_OF_RANGE | 11 |
| NUMBER_TOO_BIG | 12 |
| RECURSION | 18 |
| TYPE_ERROR | 13 |
| UNEXPECTED_TOKEN | 14 |
| UNKNOWN_KEYWORD | 15 |
| UNTERMINATED_STRING_CONSTANT | 16 |
| VALUE_EXPECTED | 17 |

### Other runtime attributes ‡


### Runtime functions †
