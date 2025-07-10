---
layout: default
title: Gegl.structs
---
# Gegl.structs

## AudioFragmentClass
- :Constructors:<br /><br />::<br /><br />    AudioFragmentClass()

## AudioFragmentPrivate

## BufferIterator
- :Constructors:<br /><br />::<br /><br />    BufferIterator()

## BufferIteratorItem
- :Constructors:<br /><br />::<br /><br />    BufferIteratorItem()

## BufferIteratorPriv

## BufferMatrix2
- :Constructors:<br /><br />::<br /><br />    BufferMatrix2()

### Runtime functions †
- **determinant**`(*args, **kwargs)`
  - determinant(self) -> float

- **is_identity**`(*args, **kwargs)`
  - is_identity(self) -> bool

- **is_scale**`(*args, **kwargs)`
  - is_scale(self) -> bool



## ColorClass
- :Constructors:<br /><br />::<br /><br />    ColorClass()

## ColorPrivate

## CurveClass
- :Constructors:<br /><br />::<br /><br />    CurveClass()

## Lookup
- :Constructors:<br /><br />::<br /><br />    Lookup()

## Matrix3
- :Constructors:<br /><br />::<br /><br />    Matrix3()<br />    new() -> Gegl.Matrix3

### Runtime functions ††
- **copy**`(*args, **kwargs)`
  - copy(self) -> Gegl.Matrix3

- **copy_into**`(*args, **kwargs)`
  - copy_into(self, src:Gegl.Matrix3)

- **determinant**`(*args, **kwargs)`
  - determinant(self) -> float

- **equal**`(*args, **kwargs)`
  - equal(self, matrix2:Gegl.Matrix3) -> bool

- **identity**`(*args, **kwargs)`
  - identity(self)

- **invert**`(*args, **kwargs)`
  - invert(self)

- **is_affine**`(*args, **kwargs)`
  - is_affine(self) -> bool

- **is_identity**`(*args, **kwargs)`
  - is_identity(self) -> bool

- **is_scale**`(*args, **kwargs)`
  - is_scale(self) -> bool

- **is_translate**`(*args, **kwargs)`
  - is_translate(self) -> bool

- **multiply**`(*args, **kwargs)`
  - multiply(self, right:Gegl.Matrix3, product:Gegl.Matrix3)

- **new**`(*args, **kwargs)`
  - new() -> Gegl.Matrix3

- **originate**`(*args, **kwargs)`
  - originate(self, x:float, y:float)

- **parse_string**`(*args, **kwargs)`
  - parse_string(self, string:str)

- **round_error**`(*args, **kwargs)`
  - round_error(self)

- **to_string**`(*args, **kwargs)`
  - to_string(self) -> str

- **transform_point**`(*args, **kwargs)`
  - transform_point(self, x:float, y:float)



## MetadataHashClass
- :Constructors:<br /><br />::<br /><br />    MetadataHashClass()

## MetadataInterface
- :Constructors:<br /><br />::<br /><br />    MetadataInterface()

## MetadataIter
- :Constructors:<br /><br />::<br /><br />    MetadataIter()

## MetadataMap
- :Constructors:<br /><br />::<br /><br />    MetadataMap()

## MetadataStoreClass
- :Constructors:<br /><br />::<br /><br />    MetadataStoreClass()

## OperationContext

## ParamSpecDouble
- :Constructors:<br /><br />::<br /><br />    ParamSpecDouble()

### Runtime functions †††
- **set_digits**`(*args, **kwargs)`
  - set_digits(self, digits:int)

- **set_steps**`(*args, **kwargs)`
  - set_steps(self, small_step:float, big_step:float)



## ParamSpecEnum
- :Constructors:<br /><br />::<br /><br />    ParamSpecEnum()

### Runtime functions ††††
- **exclude_value**`(*args, **kwargs)`
  - exclude_value(self, value:int)



## ParamSpecFilePath
- :Constructors:<br /><br />::<br /><br />    ParamSpecFilePath()

## ParamSpecFormat
- :Constructors:<br /><br />::<br /><br />    ParamSpecFormat()

## ParamSpecInt
- :Constructors:<br /><br />::<br /><br />    ParamSpecInt()

### Runtime functions †††††
- **set_steps**`(*args, **kwargs)`
  - set_steps(self, small_step:int, big_step:int)



## ParamSpecSeed
- :Constructors:<br /><br />::<br /><br />    ParamSpecSeed()

## ParamSpecString
- :Constructors:<br /><br />::<br /><br />    ParamSpecString()

## ParamSpecUri
- :Constructors:<br /><br />::<br /><br />    ParamSpecUri()

## PathClass

## PathItem
- :Constructors:<br /><br />::<br /><br />    PathItem()

## PathList
- :Constructors:<br /><br />::<br /><br />    PathList()

## PathPoint
- :Constructors:<br /><br />::<br /><br />    PathPoint()

## Random
- :Constructors:<br /><br />::<br /><br />    new() -> Gegl.Random<br />    new_with_seed(seed:int) -> Gegl.Random

### Runtime functions ††††††
- **copy**`(self, /)`
  - documentation unavailable

- **duplicate**`(*args, **kwargs)`
  - duplicate(self) -> Gegl.Random

- **float**`(*args, **kwargs)`
  - float(self, x:int, y:int, z:int, n:int) -> float

- **float_range**`(*args, **kwargs)`
  - float_range(self, x:int, y:int, z:int, n:int, min:float, max:float) -> float

- **free**`(*args, **kwargs)`
  - free(self)

- **int**`(*args, **kwargs)`
  - int(self, x:int, y:int, z:int, n:int) -> int

- **int_range**`(*args, **kwargs)`
  - int_range(self, x:int, y:int, z:int, n:int, min:int, max:int) -> int

- **new**`(*args, **kwargs)`
  - new() -> Gegl.Random

- **new_with_seed**`(*args, **kwargs)`
  - new_with_seed(seed:int) -> Gegl.Random

- **set_seed**`(*args, **kwargs)`
  - set_seed(self, seed:int)



## Rectangle
- :Constructors:<br /><br />::<br /><br />    Rectangle()<br />    new(x:int, y:int, width:int, height:int) -> Gegl.Rectangle

### Runtime functions †††††††
- **align**`(*args, **kwargs)`
  - align(self, rectangle:Gegl.Rectangle, tile:Gegl.Rectangle, alignment:Gegl.RectangleAlignment) -> bool

- **align_to_buffer**`(*args, **kwargs)`
  - align_to_buffer(self, rectangle:Gegl.Rectangle, buffer:Gegl.Buffer, alignment:Gegl.RectangleAlignment) -> bool

- **bounding_box**`(*args, **kwargs)`
  - bounding_box(self, source1:Gegl.Rectangle, source2:Gegl.Rectangle)

- **contains**`(*args, **kwargs)`
  - contains(self, child:Gegl.Rectangle) -> bool

- **copy**`(*args, **kwargs)`
  - copy(self, source:Gegl.Rectangle)

- **dump**`(*args, **kwargs)`
  - dump(self)

- **dup**`(*args, **kwargs)`
  - dup(self) -> Gegl.Rectangle

- **equal**`(*args, **kwargs)`
  - equal(self, rectangle2:Gegl.Rectangle) -> bool

- **equal_coords**`(*args, **kwargs)`
  - equal_coords(self, x:int, y:int, width:int, height:int) -> bool

- **infinite_plane**`(*args, **kwargs)`
  - infinite_plane() -> Gegl.Rectangle

- **intersect**`(*args, **kwargs)`
  - intersect(self, src1:Gegl.Rectangle, src2:Gegl.Rectangle) -> bool

- **is_empty**`(*args, **kwargs)`
  - is_empty(self) -> bool

- **is_infinite_plane**`(*args, **kwargs)`
  - is_infinite_plane(self) -> bool

- **new**`(*args, **kwargs)`
  - new(x:int, y:int, width:int, height:int) -> Gegl.Rectangle

- **set**`(*args, **kwargs)`
  - set(self, x:int, y:int, width:int, height:int)

- **subtract**`(*args, **kwargs)`
  - subtract(self, minuend:Gegl.Rectangle, subtrahend:Gegl.Rectangle) -> int

- **subtract_bounding_box**`(*args, **kwargs)`
  - subtract_bounding_box(self, minuend:Gegl.Rectangle, subtrahend:Gegl.Rectangle) -> bool

- **xor**`(*args, **kwargs)`
  - xor(self, source1:Gegl.Rectangle, source2:Gegl.Rectangle) -> int



## Sampler

### Runtime functions ††††††††
- **get**`(*args, **kwargs)`
  - get(self, x:float, y:float, scale:Gegl.BufferMatrix2, output=None, repeat_mode:Gegl.AbyssPolicy)

- **get_context_rect**`(*args, **kwargs)`
  - get_context_rect(self) -> Gegl.Rectangle



## Tile

## TileBackendClass
- :Constructors:<br /><br />::<br /><br />    TileBackendClass()

## TileBackendPrivate

## TileCopyParams
- :Constructors:<br /><br />::<br /><br />    TileCopyParams()

## TileHandlerClass
- :Constructors:<br /><br />::<br /><br />    TileHandlerClass()

## TileHandlerPrivate

## TileSourceClass
- :Constructors:<br /><br />::<br /><br />    TileSourceClass()
