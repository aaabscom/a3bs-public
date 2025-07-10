---
layout: default
title: Gimp.enums
---
# Gimp.enums

## AddMaskType

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| ALPHA | 2 |
| ALPHA_TRANSFER | 3 |
| BLACK | 1 |
| CHANNEL | 6 |
| COPY | 5 |
| SELECTION | 4 |
| WHITE | 0 |

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


## ArgumentSync

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| NONE | 0 |
| PARASITE | 1 |

### Other runtime attributes ‡


### Runtime functions †

## BrushApplicationMode

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| HARD | 0 |
| SOFT | 1 |

### Other runtime attributes ‡


### Runtime functions †

## BrushGeneratedShape

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| CIRCLE | 0 |
| DIAMOND | 2 |
| SQUARE | 1 |

### Other runtime attributes ‡


### Runtime functions †

## CapStyle

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| BUTT | 0 |
| ROUND | 1 |
| SQUARE | 2 |

### Other runtime attributes ‡


### Runtime functions †

## ChannelOps

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| ADD | 0 |
| INTERSECT | 3 |
| REPLACE | 2 |
| SUBTRACT | 1 |

### Other runtime attributes ‡


### Runtime functions †

## ChannelType

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| ALPHA | 5 |
| BLUE | 2 |
| GRAY | 3 |
| GREEN | 1 |
| INDEXED | 4 |
| RED | 0 |

### Other runtime attributes ‡


### Runtime functions †

## CheckSize

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| LARGE_CHECKS | 2 |
| MEDIUM_CHECKS | 1 |
| SMALL_CHECKS | 0 |

### Other runtime attributes ‡


### Runtime functions †

## CheckType

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| BLACK_ONLY | 5 |
| CUSTOM_CHECKS | 6 |
| DARK_CHECKS | 2 |
| GRAY_CHECKS | 1 |
| GRAY_ONLY | 4 |
| LIGHT_CHECKS | 0 |
| WHITE_ONLY | 3 |

### Other runtime attributes ‡


### Runtime functions †

## CloneType

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| IMAGE | 0 |
| PATTERN | 1 |

### Other runtime attributes ‡


### Runtime functions †

## ColorManagementMode

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| DISPLAY | 1 |
| OFF | 0 |
| SOFTPROOF | 2 |

### Other runtime attributes ‡


### Runtime functions †

## ColorRenderingIntent

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| ABSOLUTE_COLORIMETRIC | 3 |
| PERCEPTUAL | 0 |
| RELATIVE_COLORIMETRIC | 1 |
| SATURATION | 2 |

### Other runtime attributes ‡


### Runtime functions †

## ColorTag

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| BLUE | 1 |
| BROWN | 5 |
| GRAY | 8 |
| GREEN | 2 |
| NONE | 0 |
| ORANGE | 4 |
| RED | 6 |
| VIOLET | 7 |
| YELLOW | 3 |

### Other runtime attributes ‡


### Runtime functions †

## ColorTransformFlags

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| BLACK_POINT_COMPENSATION | 8192 |
| GAMUT_CHECK | 4096 |
| NOOPTIMIZE | 256 |

### Other runtime attributes ‡


### Runtime functions †

## ComponentType

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| DOUBLE | 700 |
| FLOAT | 600 |
| HALF | 500 |
| U16 | 200 |
| U32 | 300 |
| U8 | 100 |

### Other runtime attributes ‡


### Runtime functions †

## ConfigError

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| OPEN | 0 |
| OPEN_ENOENT | 1 |
| PARSE | 3 |
| VERSION | 4 |
| WRITE | 2 |

### Other runtime attributes ‡


### Runtime functions †

## ConfigPathType

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| DIR | 2 |
| DIR_LIST | 3 |
| FILE | 0 |
| FILE_LIST | 1 |

### Other runtime attributes ‡


### Runtime functions †

## ConvertDitherType

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| FIXED | 3 |
| FS | 1 |
| FS_LOWBLEED | 2 |
| NONE | 0 |

### Other runtime attributes ‡


### Runtime functions †

## ConvertPaletteType

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| CUSTOM | 3 |
| GENERATE | 0 |
| MONO | 2 |
| WEB | 1 |

### Other runtime attributes ‡


### Runtime functions †

## ConvolveType

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| BLUR | 0 |
| SHARPEN | 1 |

### Other runtime attributes ‡


### Runtime functions †

## CpuAccelFlags

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| NONE | 0 |
| PPC_ALTIVEC | 67108864 |
| X86_3DNOW | 1073741824 |
| X86_AVX | 2097152 |
| X86_MMX | -2147483648 |
| X86_MMXEXT | 536870912 |
| X86_SSE | 268435456 |
| X86_SSE2 | 134217728 |
| X86_SSE3 | 33554432 |
| X86_SSE4_1 | 8388608 |
| X86_SSE4_2 | 4194304 |
| X86_SSSE3 | 16777216 |

### Other runtime attributes ‡


### Runtime functions †

## DesaturateMode

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| AVERAGE | 2 |
| LIGHTNESS | 0 |
| LUMA | 1 |
| LUMINANCE | 3 |
| VALUE | 4 |

### Other runtime attributes ‡


### Runtime functions †

## DodgeBurnType

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| BURN | 1 |
| DODGE | 0 |

### Other runtime attributes ‡


### Runtime functions †

## ExportReturn

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| EXPORT | 1 |
| IGNORE | 0 |

### Other runtime attributes ‡


### Runtime functions †

## FileChooserAction

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| ANY | -1 |
| CREATE_FOLDER | 3 |
| OPEN | 0 |
| SAVE | 1 |
| SELECT_FOLDER | 2 |

### Other runtime attributes ‡


### Runtime functions †

## FillType

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| BACKGROUND | 1 |
| CIELAB_MIDDLE_GRAY | 2 |
| FOREGROUND | 0 |
| PATTERN | 5 |
| TRANSPARENT | 4 |
| WHITE | 3 |

### Other runtime attributes ‡


### Runtime functions †

## ForegroundExtractMode

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| MATTING | 0 |

### Other runtime attributes ‡


### Runtime functions †

## GradientBlendColorSpace

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| CIE_LAB | 2 |
| RGB_LINEAR | 1 |
| RGB_PERCEPTUAL | 0 |

### Other runtime attributes ‡


### Runtime functions †

## GradientSegmentColor

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| HSV_CCW | 1 |
| HSV_CW | 2 |
| RGB | 0 |

### Other runtime attributes ‡


### Runtime functions †

## GradientSegmentType

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| CURVED | 1 |
| LINEAR | 0 |
| SINE | 2 |
| SPHERE_DECREASING | 4 |
| SPHERE_INCREASING | 3 |
| STEP | 5 |

### Other runtime attributes ‡


### Runtime functions †

## GradientType

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| BILINEAR | 1 |
| CONICAL_ASYMMETRIC | 5 |
| CONICAL_SYMMETRIC | 4 |
| LINEAR | 0 |
| RADIAL | 2 |
| SHAPEBURST_ANGULAR | 6 |
| SHAPEBURST_DIMPLED | 8 |
| SHAPEBURST_SPHERICAL | 7 |
| SPIRAL_ANTICLOCKWISE | 10 |
| SPIRAL_CLOCKWISE | 9 |
| SQUARE | 3 |

### Other runtime attributes ‡


### Runtime functions †

## GridStyle

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| DOTS | 0 |
| DOUBLE_DASH | 3 |
| INTERSECTIONS | 1 |
| ON_OFF_DASH | 2 |
| SOLID | 4 |

### Other runtime attributes ‡


### Runtime functions †

## HistogramChannel

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| ALPHA | 4 |
| BLUE | 3 |
| GREEN | 2 |
| LUMINANCE | 5 |
| RED | 1 |
| VALUE | 0 |

### Other runtime attributes ‡


### Runtime functions †

## HueRange

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| ALL | 0 |
| BLUE | 5 |
| CYAN | 4 |
| GREEN | 3 |
| MAGENTA | 6 |
| RED | 1 |
| YELLOW | 2 |

### Other runtime attributes ‡


### Runtime functions †

## IconType

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| ICON_NAME | 0 |
| IMAGE_FILE | 2 |
| PIXBUF | 1 |

### Other runtime attributes ‡


### Runtime functions †

## ImageBaseType

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| GRAY | 1 |
| INDEXED | 2 |
| RGB | 0 |

### Other runtime attributes ‡


### Runtime functions †

## ImageType

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| GRAYA_IMAGE | 3 |
| GRAY_IMAGE | 2 |
| INDEXEDA_IMAGE | 5 |
| INDEXED_IMAGE | 4 |
| RGBA_IMAGE | 1 |
| RGB_IMAGE | 0 |

### Other runtime attributes ‡


### Runtime functions †

## InkBlobType

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| CIRCLE | 0 |
| DIAMOND | 2 |
| SQUARE | 1 |

### Other runtime attributes ‡


### Runtime functions †

## InterpolationType

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| CUBIC | 2 |
| LINEAR | 1 |
| LOHALO | 4 |
| NOHALO | 3 |
| NONE | 0 |

### Other runtime attributes ‡


### Runtime functions †

## JoinStyle

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| BEVEL | 2 |
| MITER | 0 |
| ROUND | 1 |

### Other runtime attributes ‡


### Runtime functions †

## LayerColorSpace

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| AUTO | 0 |
| LAB | 3 |
| RGB_LINEAR | 1 |
| RGB_NON_LINEAR | 2 |
| RGB_PERCEPTUAL | 4 |

### Other runtime attributes ‡


### Runtime functions †

## LayerCompositeMode

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| AUTO | 0 |
| CLIP_TO_BACKDROP | 2 |
| CLIP_TO_LAYER | 3 |
| INTERSECTION | 4 |
| UNION | 1 |

### Other runtime attributes ‡


### Runtime functions †

## LayerMode

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| ADDITION | 33 |
| ADDITION_LEGACY | 7 |
| BEHIND | 29 |
| BEHIND_LEGACY | 2 |
| BURN | 43 |
| BURN_LEGACY | 17 |
| COLOR_ERASE | 57 |
| COLOR_ERASE_LEGACY | 22 |
| DARKEN_ONLY | 35 |
| DARKEN_ONLY_LEGACY | 9 |
| DIFFERENCE | 32 |
| DIFFERENCE_LEGACY | 6 |
| DISSOLVE | 1 |
| DIVIDE | 41 |
| DIVIDE_LEGACY | 15 |
| DODGE | 42 |
| DODGE_LEGACY | 16 |
| ERASE | 58 |
| EXCLUSION | 52 |
| GRAIN_EXTRACT | 46 |
| GRAIN_EXTRACT_LEGACY | 20 |
| GRAIN_MERGE | 47 |
| GRAIN_MERGE_LEGACY | 21 |
| HARDLIGHT | 44 |
| HARDLIGHT_LEGACY | 18 |
| HARD_MIX | 51 |
| HSL_COLOR | 39 |
| HSL_COLOR_LEGACY | 13 |
| HSV_HUE | 37 |
| HSV_HUE_LEGACY | 11 |
| HSV_SATURATION | 38 |
| HSV_SATURATION_LEGACY | 12 |
| HSV_VALUE | 40 |
| HSV_VALUE_LEGACY | 14 |
| LCH_CHROMA | 25 |
| LCH_COLOR | 26 |
| LCH_HUE | 24 |
| LCH_LIGHTNESS | 27 |
| LIGHTEN_ONLY | 36 |
| LIGHTEN_ONLY_LEGACY | 10 |
| LINEAR_BURN | 53 |
| LINEAR_LIGHT | 50 |
| LUMA_DARKEN_ONLY | 54 |
| LUMA_LIGHTEN_ONLY | 55 |
| LUMINANCE | 56 |
| MERGE | 59 |
| MULTIPLY | 30 |
| MULTIPLY_LEGACY | 3 |
| NORMAL | 28 |
| NORMAL_LEGACY | 0 |
| OVERLAY | 23 |
| OVERLAY_LEGACY | 5 |
| PASS_THROUGH | 61 |
| PIN_LIGHT | 49 |
| REPLACE | 62 |
| SCREEN | 31 |
| SCREEN_LEGACY | 4 |
| SOFTLIGHT | 45 |
| SOFTLIGHT_LEGACY | 19 |
| SPLIT | 60 |
| SUBTRACT | 34 |
| SUBTRACT_LEGACY | 8 |
| VIVID_LIGHT | 48 |

### Other runtime attributes ‡


### Runtime functions †

## MaskApplyMode

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| APPLY | 0 |
| DISCARD | 1 |

### Other runtime attributes ‡


### Runtime functions †

## MergeType

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| CLIP_TO_BOTTOM_LAYER | 2 |
| CLIP_TO_IMAGE | 1 |
| EXPAND_AS_NECESSARY | 0 |
| FLATTEN_IMAGE | 3 |

### Other runtime attributes ‡


### Runtime functions †

## MessageHandlerType

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| CONSOLE | 1 |
| ERROR_CONSOLE | 2 |
| MESSAGE_BOX | 0 |

### Other runtime attributes ‡


### Runtime functions †

## MetadataColorspace

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| ADOBERGB | 3 |
| SRGB | 2 |
| UNCALIBRATED | 1 |
| UNSPECIFIED | 0 |

### Other runtime attributes ‡


### Runtime functions †

## ModuleError

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| MODULE_FAILED | 0 |

### Other runtime attributes ‡


### Runtime functions †

## ModuleState

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| ERROR | 0 |
| LOADED | 1 |
| LOAD_FAILED | 2 |
| NOT_LOADED | 3 |

### Other runtime attributes ‡


### Runtime functions †

## OffsetType

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| COLOR | 0 |
| TRANSPARENT | 1 |
| WRAP_AROUND | 2 |

### Other runtime attributes ‡


### Runtime functions †

## OrientationType

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| HORIZONTAL | 0 |
| UNKNOWN | 2 |
| VERTICAL | 1 |

### Other runtime attributes ‡


### Runtime functions †

## PDBErrorHandler

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| INTERNAL | 0 |
| PLUGIN | 1 |

### Other runtime attributes ‡


### Runtime functions †

## PDBProcType

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| INTERNAL | 0 |
| PERSISTENT | 2 |
| PLUGIN | 1 |
| TEMPORARY | 3 |

### Other runtime attributes ‡


### Runtime functions †

## PDBStatusType

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| CALLING_ERROR | 1 |
| CANCEL | 4 |
| EXECUTION_ERROR | 0 |
| PASS_THROUGH | 2 |
| SUCCESS | 3 |

### Other runtime attributes ‡


### Runtime functions †

## PaintApplicationMode

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| CONSTANT | 0 |
| INCREMENTAL | 1 |

### Other runtime attributes ‡


### Runtime functions †

## PathStrokeType

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| BEZIER | 0 |

### Other runtime attributes ‡


### Runtime functions †

## PixbufTransparency

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| KEEP_ALPHA | 0 |
| LARGE_CHECKS | 2 |
| SMALL_CHECKS | 1 |

### Other runtime attributes ‡


### Runtime functions †

## Precision

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| DOUBLE_LINEAR | 700 |
| DOUBLE_NON_LINEAR | 750 |
| DOUBLE_PERCEPTUAL | 775 |
| FLOAT_LINEAR | 600 |
| FLOAT_NON_LINEAR | 650 |
| FLOAT_PERCEPTUAL | 675 |
| HALF_LINEAR | 500 |
| HALF_NON_LINEAR | 550 |
| HALF_PERCEPTUAL | 575 |
| U16_LINEAR | 200 |
| U16_NON_LINEAR | 250 |
| U16_PERCEPTUAL | 275 |
| U32_LINEAR | 300 |
| U32_NON_LINEAR | 350 |
| U32_PERCEPTUAL | 375 |
| U8_LINEAR | 100 |
| U8_NON_LINEAR | 150 |
| U8_PERCEPTUAL | 175 |

### Other runtime attributes ‡


### Runtime functions †

## ProgressCommand

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| END | 1 |
| GET_WINDOW | 5 |
| PULSE | 4 |
| SET_TEXT | 2 |
| SET_VALUE | 3 |
| START | 0 |

### Other runtime attributes ‡


### Runtime functions †

## RepeatMode

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| NONE | 0 |
| SAWTOOTH | 2 |
| TRIANGULAR | 3 |
| TRUNCATE | 1 |

### Other runtime attributes ‡


### Runtime functions †

## RotationType

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| DEGREES180 | 1 |
| DEGREES270 | 2 |
| DEGREES90 | 0 |

### Other runtime attributes ‡


### Runtime functions †

## RunMode

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| INTERACTIVE | 0 |
| NONINTERACTIVE | 1 |
| WITH_LAST_VALS | 2 |

### Other runtime attributes ‡


### Runtime functions †

## SelectCriterion

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| ALPHA | 10 |
| COMPOSITE | 0 |
| HSV_HUE | 4 |
| HSV_SATURATION | 5 |
| HSV_VALUE | 6 |
| LCH_CHROMA | 8 |
| LCH_HUE | 9 |
| LCH_LIGHTNESS | 7 |
| RGB_BLUE | 3 |
| RGB_GREEN | 2 |
| RGB_RED | 1 |

### Other runtime attributes ‡


### Runtime functions †

## SizeType

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| PIXELS | 0 |
| POINTS | 1 |

### Other runtime attributes ‡


### Runtime functions †

## StackTraceMode

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| ALWAYS | 2 |
| NEVER | 0 |
| QUERY | 1 |

### Other runtime attributes ‡


### Runtime functions †

## StrokeMethod

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| LINE | 0 |
| PAINT_METHOD | 1 |

### Other runtime attributes ‡


### Runtime functions †

## TextDirection

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| LTR | 0 |
| RTL | 1 |
| TTB_LTR | 4 |
| TTB_LTR_UPRIGHT | 5 |
| TTB_RTL | 2 |
| TTB_RTL_UPRIGHT | 3 |

### Other runtime attributes ‡


### Runtime functions †

## TextHintStyle

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| FULL | 3 |
| MEDIUM | 2 |
| NONE | 0 |
| SLIGHT | 1 |

### Other runtime attributes ‡


### Runtime functions †

## TextJustification

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| CENTER | 2 |
| FILL | 3 |
| LEFT | 0 |
| RIGHT | 1 |

### Other runtime attributes ‡


### Runtime functions †

## TransferMode

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| HIGHLIGHTS | 2 |
| MIDTONES | 1 |
| SHADOWS | 0 |

### Other runtime attributes ‡


### Runtime functions †

## TransformDirection

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| BACKWARD | 1 |
| FORWARD | 0 |

### Other runtime attributes ‡


### Runtime functions †

## TransformResize

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| ADJUST | 0 |
| CLIP | 1 |
| CROP | 2 |
| CROP_WITH_ASPECT | 3 |

### Other runtime attributes ‡


### Runtime functions †

## UnitID

### Runtime attributes

| Name | Value |
|------------------------|---------------|
| END | 5 |
| INCH | 1 |
| MM | 2 |
| PERCENT | 65536 |
| PICA | 4 |
| PIXEL | 0 |
| POINT | 3 |

### Other runtime attributes ‡


### Runtime functions †
