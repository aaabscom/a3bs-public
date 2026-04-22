---
layout: default
title: Gimp.enums
---
# Gimp.enums

## AddMaskType

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| WHITE | 0 |
| BLACK | 1 |
| ALPHA | 2 |
| ALPHA_TRANSFER | 3 |
| SELECTION | 4 |
| COPY | 5 |
| CHANNEL | 6 |

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
## ArgumentSync

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| NONE | 0 |
| PARASITE | 1 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## BrushApplicationMode

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| HARD | 0 |
| SOFT | 1 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## BrushGeneratedShape

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| CIRCLE | 0 |
| SQUARE | 1 |
| DIAMOND | 2 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## CapStyle

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| BUTT | 0 |
| ROUND | 1 |
| SQUARE | 2 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## ChannelOps

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| ADD | 0 |
| SUBTRACT | 1 |
| REPLACE | 2 |
| INTERSECT | 3 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## ChannelType

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| RED | 0 |
| GREEN | 1 |
| BLUE | 2 |
| GRAY | 3 |
| INDEXED | 4 |
| ALPHA | 5 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## CheckSize

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| SMALL_CHECKS | 0 |
| MEDIUM_CHECKS | 1 |
| LARGE_CHECKS | 2 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## CheckType

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| LIGHT_CHECKS | 0 |
| GRAY_CHECKS | 1 |
| DARK_CHECKS | 2 |
| WHITE_ONLY | 3 |
| GRAY_ONLY | 4 |
| BLACK_ONLY | 5 |
| CUSTOM_CHECKS | 6 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## CloneType

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| IMAGE | 0 |
| PATTERN | 1 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## ColorManagementMode

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| OFF | 0 |
| DISPLAY | 1 |
| SOFTPROOF | 2 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## ColorRenderingIntent

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| PERCEPTUAL | 0 |
| RELATIVE_COLORIMETRIC | 1 |
| SATURATION | 2 |
| ABSOLUTE_COLORIMETRIC | 3 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## ColorTag

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| NONE | 0 |
| BLUE | 1 |
| GREEN | 2 |
| YELLOW | 3 |
| ORANGE | 4 |
| BROWN | 5 |
| RED | 6 |
| VIOLET | 7 |
| GRAY | 8 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## ColorTransformFlags

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| NOOPTIMIZE | 256 |
| GAMUT_CHECK | 4096 |
| BLACK_POINT_COMPENSATION | 8192 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## ComponentType

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| U8 | 100 |
| U16 | 200 |
| U32 | 300 |
| HALF | 500 |
| FLOAT | 600 |
| DOUBLE | 700 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## ConfigError

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| OPEN | 0 |
| OPEN_ENOENT | 1 |
| WRITE | 2 |
| PARSE | 3 |
| VERSION | 4 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## ConfigPathType

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| FILE | 0 |
| FILE_LIST | 1 |
| DIR | 2 |
| DIR_LIST | 3 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## ConvertDitherType

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| NONE | 0 |
| FS | 1 |
| FS_LOWBLEED | 2 |
| FIXED | 3 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## ConvertPaletteType

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| GENERATE | 0 |
| WEB | 1 |
| MONO | 2 |
| CUSTOM | 3 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## ConvolveType

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| BLUR | 0 |
| SHARPEN | 1 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## CpuAccelFlags

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| X86_MMX | -2147483648 |
| NONE | 0 |
| X86_AVX | 2097152 |
| X86_SSE4_2 | 4194304 |
| X86_SSE4_1 | 8388608 |
| X86_SSSE3 | 16777216 |
| X86_SSE3 | 33554432 |
| PPC_ALTIVEC | 67108864 |
| X86_SSE2 | 134217728 |
| X86_SSE | 268435456 |
| X86_MMXEXT | 536870912 |
| X86_3DNOW | 1073741824 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## CurvePointType

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| SMOOTH | 0 |
| CORNER | 1 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## CurveType

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| SMOOTH | 0 |
| FREE | 1 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## DesaturateMode

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| LIGHTNESS | 0 |
| LUMA | 1 |
| AVERAGE | 2 |
| LUMINANCE | 3 |
| VALUE | 4 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## DodgeBurnType

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| DODGE | 0 |
| BURN | 1 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## ExportReturn

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| IGNORE | 0 |
| EXPORT | 1 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## FileChooserAction

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| ANY | -1 |
| OPEN | 0 |
| SAVE | 1 |
| SELECT_FOLDER | 2 |
| CREATE_FOLDER | 3 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## FillType

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| FOREGROUND | 0 |
| BACKGROUND | 1 |
| CIELAB_MIDDLE_GRAY | 2 |
| WHITE | 3 |
| TRANSPARENT | 4 |
| PATTERN | 5 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## ForegroundExtractMode

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| MATTING | 0 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## GradientBlendColorSpace

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| RGB_PERCEPTUAL | 0 |
| RGB_LINEAR | 1 |
| CIE_LAB | 2 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## GradientSegmentColor

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| RGB | 0 |
| HSV_CCW | 1 |
| HSV_CW | 2 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## GradientSegmentType

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| LINEAR | 0 |
| CURVED | 1 |
| SINE | 2 |
| SPHERE_INCREASING | 3 |
| SPHERE_DECREASING | 4 |
| STEP | 5 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## GradientType

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| LINEAR | 0 |
| BILINEAR | 1 |
| RADIAL | 2 |
| SQUARE | 3 |
| CONICAL_SYMMETRIC | 4 |
| CONICAL_ASYMMETRIC | 5 |
| SHAPEBURST_ANGULAR | 6 |
| SHAPEBURST_SPHERICAL | 7 |
| SHAPEBURST_DIMPLED | 8 |
| SPIRAL_CLOCKWISE | 9 |
| SPIRAL_ANTICLOCKWISE | 10 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## GridStyle

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| DOTS | 0 |
| INTERSECTIONS | 1 |
| ON_OFF_DASH | 2 |
| DOUBLE_DASH | 3 |
| SOLID | 4 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## HistogramChannel

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| VALUE | 0 |
| RED | 1 |
| GREEN | 2 |
| BLUE | 3 |
| ALPHA | 4 |
| LUMINANCE | 5 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## HueRange

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| ALL | 0 |
| RED | 1 |
| YELLOW | 2 |
| GREEN | 3 |
| CYAN | 4 |
| BLUE | 5 |
| MAGENTA | 6 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## IconType

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| ICON_NAME | 0 |
| PIXBUF | 1 |
| IMAGE_FILE | 2 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## ImageBaseType

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| RGB | 0 |
| GRAY | 1 |
| INDEXED | 2 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## ImageType

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| RGB_IMAGE | 0 |
| RGBA_IMAGE | 1 |
| GRAY_IMAGE | 2 |
| GRAYA_IMAGE | 3 |
| INDEXED_IMAGE | 4 |
| INDEXEDA_IMAGE | 5 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## InkBlobType

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| CIRCLE | 0 |
| SQUARE | 1 |
| DIAMOND | 2 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## InterpolationType

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| NONE | 0 |
| LINEAR | 1 |
| CUBIC | 2 |
| NOHALO | 3 |
| LOHALO | 4 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## JoinStyle

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| MITER | 0 |
| ROUND | 1 |
| BEVEL | 2 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## LayerColorSpace

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| AUTO | 0 |
| RGB_LINEAR | 1 |
| RGB_NON_LINEAR | 2 |
| LAB | 3 |
| RGB_PERCEPTUAL | 4 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## LayerCompositeMode

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| AUTO | 0 |
| UNION | 1 |
| CLIP_TO_BACKDROP | 2 |
| CLIP_TO_LAYER | 3 |
| INTERSECTION | 4 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## LayerMode

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| NORMAL_LEGACY | 0 |
| DISSOLVE | 1 |
| BEHIND_LEGACY | 2 |
| MULTIPLY_LEGACY | 3 |
| SCREEN_LEGACY | 4 |
| OVERLAY_LEGACY | 5 |
| DIFFERENCE_LEGACY | 6 |
| ADDITION_LEGACY | 7 |
| SUBTRACT_LEGACY | 8 |
| DARKEN_ONLY_LEGACY | 9 |
| LIGHTEN_ONLY_LEGACY | 10 |
| HSV_HUE_LEGACY | 11 |
| HSV_SATURATION_LEGACY | 12 |
| HSL_COLOR_LEGACY | 13 |
| HSV_VALUE_LEGACY | 14 |
| DIVIDE_LEGACY | 15 |
| DODGE_LEGACY | 16 |
| BURN_LEGACY | 17 |
| HARDLIGHT_LEGACY | 18 |
| SOFTLIGHT_LEGACY | 19 |
| GRAIN_EXTRACT_LEGACY | 20 |
| GRAIN_MERGE_LEGACY | 21 |
| COLOR_ERASE_LEGACY | 22 |
| OVERLAY | 23 |
| LCH_HUE | 24 |
| LCH_CHROMA | 25 |
| LCH_COLOR | 26 |
| LCH_LIGHTNESS | 27 |
| NORMAL | 28 |
| BEHIND | 29 |
| MULTIPLY | 30 |
| SCREEN | 31 |
| DIFFERENCE | 32 |
| ADDITION | 33 |
| SUBTRACT | 34 |
| DARKEN_ONLY | 35 |
| LIGHTEN_ONLY | 36 |
| HSV_HUE | 37 |
| HSV_SATURATION | 38 |
| HSL_COLOR | 39 |
| HSV_VALUE | 40 |
| DIVIDE | 41 |
| DODGE | 42 |
| BURN | 43 |
| HARDLIGHT | 44 |
| SOFTLIGHT | 45 |
| GRAIN_EXTRACT | 46 |
| GRAIN_MERGE | 47 |
| VIVID_LIGHT | 48 |
| PIN_LIGHT | 49 |
| LINEAR_LIGHT | 50 |
| HARD_MIX | 51 |
| EXCLUSION | 52 |
| LINEAR_BURN | 53 |
| LUMA_DARKEN_ONLY | 54 |
| LUMA_LIGHTEN_ONLY | 55 |
| LUMINANCE | 56 |
| COLOR_ERASE | 57 |
| ERASE | 58 |
| MERGE | 59 |
| SPLIT | 60 |
| PASS_THROUGH | 61 |
| REPLACE | 62 |
| OVERWRITE | 63 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## MaskApplyMode

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| APPLY | 0 |
| DISCARD | 1 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## MergeType

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| EXPAND_AS_NECESSARY | 0 |
| CLIP_TO_IMAGE | 1 |
| CLIP_TO_BOTTOM_LAYER | 2 |
| FLATTEN_IMAGE | 3 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## MessageHandlerType

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| MESSAGE_BOX | 0 |
| CONSOLE | 1 |
| ERROR_CONSOLE | 2 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## MetadataColorspace

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| UNSPECIFIED | 0 |
| UNCALIBRATED | 1 |
| SRGB | 2 |
| ADOBERGB | 3 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## ModuleError

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| MODULE_FAILED | 0 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## ModuleState

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| ERROR | 0 |
| LOADED | 1 |
| LOAD_FAILED | 2 |
| NOT_LOADED | 3 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## OffsetType

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| COLOR | 0 |
| TRANSPARENT | 1 |
| WRAP_AROUND | 2 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## OrientationType

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| HORIZONTAL | 0 |
| VERTICAL | 1 |
| UNKNOWN | 2 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## PDBErrorHandler

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| INTERNAL | 0 |
| PLUGIN | 1 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## PDBProcType

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| INTERNAL | 0 |
| PLUGIN | 1 |
| PERSISTENT | 2 |
| TEMPORARY | 3 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## PDBStatusType

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| EXECUTION_ERROR | 0 |
| CALLING_ERROR | 1 |
| PASS_THROUGH | 2 |
| SUCCESS | 3 |
| CANCEL | 4 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## PaintApplicationMode

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| CONSTANT | 0 |
| INCREMENTAL | 1 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## PathStrokeType

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| BEZIER | 0 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## PixbufTransparency

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| KEEP_ALPHA | 0 |
| SMALL_CHECKS | 1 |
| LARGE_CHECKS | 2 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## Precision

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| U8_LINEAR | 100 |
| U8_NON_LINEAR | 150 |
| U8_PERCEPTUAL | 175 |
| U16_LINEAR | 200 |
| U16_NON_LINEAR | 250 |
| U16_PERCEPTUAL | 275 |
| U32_LINEAR | 300 |
| U32_NON_LINEAR | 350 |
| U32_PERCEPTUAL | 375 |
| HALF_LINEAR | 500 |
| HALF_NON_LINEAR | 550 |
| HALF_PERCEPTUAL | 575 |
| FLOAT_LINEAR | 600 |
| FLOAT_NON_LINEAR | 650 |
| FLOAT_PERCEPTUAL | 675 |
| DOUBLE_LINEAR | 700 |
| DOUBLE_NON_LINEAR | 750 |
| DOUBLE_PERCEPTUAL | 775 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## ProgressCommand

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| START | 0 |
| END | 1 |
| SET_TEXT | 2 |
| SET_VALUE | 3 |
| PULSE | 4 |
| GET_WINDOW | 5 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## RepeatMode

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| NONE | 0 |
| TRUNCATE | 1 |
| SAWTOOTH | 2 |
| TRIANGULAR | 3 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## RotationType

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| DEGREES90 | 0 |
| DEGREES180 | 1 |
| DEGREES270 | 2 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## RunMode

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| INTERACTIVE | 0 |
| NONINTERACTIVE | 1 |
| WITH_LAST_VALS | 2 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## SelectCriterion

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| COMPOSITE | 0 |
| RGB_RED | 1 |
| RGB_GREEN | 2 |
| RGB_BLUE | 3 |
| HSV_HUE | 4 |
| HSV_SATURATION | 5 |
| HSV_VALUE | 6 |
| LCH_LIGHTNESS | 7 |
| LCH_CHROMA | 8 |
| LCH_HUE | 9 |
| ALPHA | 10 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## SizeType

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| PIXELS | 0 |
| POINTS | 1 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## StackTraceMode

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| NEVER | 0 |
| QUERY | 1 |
| ALWAYS | 2 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## StrokeMethod

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| LINE | 0 |
| PAINT_METHOD | 1 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## TRCType

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| LINEAR | 0 |
| NON_LINEAR | 1 |
| PERCEPTUAL | 2 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## TextDirection

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| LTR | 0 |
| RTL | 1 |
| TTB_RTL | 2 |
| TTB_RTL_UPRIGHT | 3 |
| TTB_LTR | 4 |
| TTB_LTR_UPRIGHT | 5 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## TextHintStyle

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| NONE | 0 |
| SLIGHT | 1 |
| MEDIUM | 2 |
| FULL | 3 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## TextJustification

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| LEFT | 0 |
| RIGHT | 1 |
| CENTER | 2 |
| FILL | 3 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## TextOutline

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| NONE | 0 |
| STROKE_ONLY | 1 |
| STROKE_FILL | 2 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## TextOutlineDirection

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| OUTER | 0 |
| INNER | 1 |
| CENTERED | 2 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## TransferMode

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| SHADOWS | 0 |
| MIDTONES | 1 |
| HIGHLIGHTS | 2 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## TransformDirection

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| FORWARD | 0 |
| BACKWARD | 1 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## TransformResize

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| ADJUST | 0 |
| CLIP | 1 |
| CROP | 2 |
| CROP_WITH_ASPECT | 3 |

### Other runtime attributes ‡


### Runtime functions †

<br>
## UnitID

### Runtime attributes

|:----------------------------------------|:---------------|
| Name | Value |
| PIXEL | 0 |
| INCH | 1 |
| MM | 2 |
| POINT | 3 |
| PICA | 4 |
| END | 5 |
| PERCENT | 65536 |

### Other runtime attributes ‡


### Runtime functions †

<br>