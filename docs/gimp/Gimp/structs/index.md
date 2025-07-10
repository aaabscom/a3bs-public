---
layout: default
title: Gimp.structs
---
# Gimp.structs

## Array
- :Constructors:<br /><br />::<br /><br />    Array()<br />    new(data:list, static_data:bool) -> Gimp.Array

### Runtime functions †
- **copy**`(*args, **kwargs)`
  - copy(self) -> Gimp.Array

- **free**`(*args, **kwargs)`
  - free(self)

- **new**`(*args, **kwargs)`
  - new(data:list, static_data:bool) -> Gimp.Array



## BatchProcedureClass
- :Constructors:<br /><br />::<br /><br />    BatchProcedureClass()

## BrushClass
- :Constructors:<br /><br />::<br /><br />    BrushClass()

## ChannelClass
- :Constructors:<br /><br />::<br /><br />    ChannelClass()

## ChoiceClass
- :Constructors:<br /><br />::<br /><br />    ChoiceClass()

## ColorConfigClass
- :Constructors:<br /><br />::<br /><br />    ColorConfigClass()

## ColorManagedInterface
- :Constructors:<br /><br />::<br /><br />    ColorManagedInterface()

## ColorProfileClass
- :Constructors:<br /><br />::<br /><br />    ColorProfileClass()

## ColorTransformClass
- :Constructors:<br /><br />::<br /><br />    ColorTransformClass()

## Config

### Runtime functions ††
- **copy**`(*args, **kwargs)`
  - copy(self, dest:Gimp.Config, flags:GObject.ParamFlags) -> bool

- **deserialize**`(*args, **kwargs)`
  - deserialize(self, scanner:GLib.Scanner, nest_level:int, data=None) -> bool

- **deserialize_file**`(*args, **kwargs)`
  - deserialize_file(self, file:Gio.File, data=None) -> bool

- **deserialize_parasite**`(*args, **kwargs)`
  - deserialize_parasite(self, parasite:Gimp.Parasite, data=None) -> bool

- **deserialize_properties**`(*args, **kwargs)`
  - deserialize_properties(self, scanner:GLib.Scanner, nest_level:int) -> bool

- **deserialize_property**`(*args, **kwargs)`
  - deserialize_property(self, scanner:GLib.Scanner, nest_level:int) -> GLib.TokenType

- **deserialize_stream**`(*args, **kwargs)`
  - deserialize_stream(self, input:Gio.InputStream, data=None) -> bool

- **deserialize_string**`(*args, **kwargs)`
  - deserialize_string(self, text:list, data=None) -> bool

- **duplicate**`(*args, **kwargs)`
  - duplicate(self)

- **is_equal_to**`(*args, **kwargs)`
  - is_equal_to(self, b:Gimp.Config) -> bool

- **reset**`(*args, **kwargs)`
  - reset(self)

- **serialize**`(*args, **kwargs)`
  - serialize(self, writer:Gimp.ConfigWriter, data=None) -> bool

- **serialize_changed_properties**`(*args, **kwargs)`
  - serialize_changed_properties(self, writer:Gimp.ConfigWriter) -> bool

- **serialize_properties**`(*args, **kwargs)`
  - serialize_properties(self, writer:Gimp.ConfigWriter) -> bool

- **serialize_property**`(*args, **kwargs)`
  - serialize_property(self, param_spec:GObject.ParamSpec, writer:Gimp.ConfigWriter) -> bool

- **serialize_property_by_name**`(*args, **kwargs)`
  - serialize_property_by_name(self, prop_name:str, writer:Gimp.ConfigWriter) -> bool

- **serialize_to_fd**`(*args, **kwargs)`
  - serialize_to_fd(self, fd:int, data=None) -> bool

- **serialize_to_file**`(*args, **kwargs)`
  - serialize_to_file(self, file:Gio.File, header:str=None, footer:str=None, data=None) -> bool

- **serialize_to_parasite**`(*args, **kwargs)`
  - serialize_to_parasite(self, parasite_name:str, parasite_flags:int, data=None) -> Gimp.Parasite

- **serialize_to_stream**`(*args, **kwargs)`
  - serialize_to_stream(self, output:Gio.OutputStream, header:str=None, footer:str=None, data=None) -> bool

- **serialize_to_string**`(*args, **kwargs)`
  - serialize_to_string(self, data=None) -> str



## ConfigWriter
- :Constructors:<br /><br />::<br /><br />    new_from_fd(fd:int) -> Gimp.ConfigWriter or None<br />    new_from_file(file:Gio.File, atomic:bool, header:str) -> Gimp.ConfigWriter or None<br />    new_from_stream(output:Gio.OutputStream, header:str) -> Gimp.ConfigWriter or None<br />    new_from_string(string:GLib.String) -> Gimp.ConfigWriter or None

### Runtime functions †††
- **close**`(*args, **kwargs)`
  - close(self)

- **comment**`(*args, **kwargs)`
  - comment(self, comment:str)

- **comment_mode**`(*args, **kwargs)`
  - comment_mode(self, enable:bool)

- **copy**`(self, /)`
  - documentation unavailable

- **data**`(*args, **kwargs)`
  - data(self, data:list)

- **finish**`(*args, **kwargs)`
  - finish(self, footer:str) -> bool

- **identifier**`(*args, **kwargs)`
  - identifier(self, identifier:str)

- **linefeed**`(*args, **kwargs)`
  - linefeed(self)

- **new_from_fd**`(*args, **kwargs)`
  - new_from_fd(fd:int) -> Gimp.ConfigWriter or None

- **new_from_file**`(*args, **kwargs)`
  - new_from_file(file:Gio.File, atomic:bool, header:str) -> Gimp.ConfigWriter or None

- **new_from_stream**`(*args, **kwargs)`
  - new_from_stream(output:Gio.OutputStream, header:str) -> Gimp.ConfigWriter or None

- **new_from_string**`(*args, **kwargs)`
  - new_from_string(string:GLib.String) -> Gimp.ConfigWriter or None

- **open**`(*args, **kwargs)`
  - open(self, name:str)

- **print_**`(*args, **kwargs)`
  - print_(self, string:str, len:int)

- **ref**`(*args, **kwargs)`
  - ref(self) -> Gimp.ConfigWriter

- **revert**`(*args, **kwargs)`
  - revert(self)

- **string**`(*args, **kwargs)`
  - string(self, string:str)

- **unref**`(*args, **kwargs)`
  - unref(self)



## DisplayClass
- :Constructors:<br /><br />::<br /><br />    DisplayClass()

## DrawableClass
- :Constructors:<br /><br />::<br /><br />    DrawableClass()

## DrawableFilterClass
- :Constructors:<br /><br />::<br /><br />    DrawableFilterClass()

## DrawableFilterConfigClass
- :Constructors:<br /><br />::<br /><br />    DrawableFilterConfigClass()

## EnumDesc
- :Constructors:<br /><br />::<br /><br />    EnumDesc()

## ExportOptionsClass
- :Constructors:<br /><br />::<br /><br />    ExportOptionsClass()

## ExportProcedureClass
- :Constructors:<br /><br />::<br /><br />    ExportProcedureClass()

## FileProcedureClass
- :Constructors:<br /><br />::<br /><br />    FileProcedureClass()

## FlagsDesc
- :Constructors:<br /><br />::<br /><br />    FlagsDesc()

## FontClass
- :Constructors:<br /><br />::<br /><br />    FontClass()

## GradientClass
- :Constructors:<br /><br />::<br /><br />    GradientClass()

## GroupLayerClass
- :Constructors:<br /><br />::<br /><br />    GroupLayerClass()

## ImageClass
- :Constructors:<br /><br />::<br /><br />    ImageClass()

## ImageProcedureClass
- :Constructors:<br /><br />::<br /><br />    ImageProcedureClass()

## ItemClass
- :Constructors:<br /><br />::<br /><br />    ItemClass()

## LayerClass
- :Constructors:<br /><br />::<br /><br />    LayerClass()

## LayerMaskClass
- :Constructors:<br /><br />::<br /><br />    LayerMaskClass()

## LoadProcedureClass
- :Constructors:<br /><br />::<br /><br />    LoadProcedureClass()

## Matrix2
- :Constructors:<br /><br />::<br /><br />    Matrix2()

### Runtime functions ††††
- **copy**`(self, /)`
  - documentation unavailable

- **determinant**`(*args, **kwargs)`
  - determinant(self) -> float

- **identity**`(*args, **kwargs)`
  - identity(self)

- **invert**`(*args, **kwargs)`
  - invert(self)

- **mult**`(*args, **kwargs)`
  - mult(self, right:Gimp.Matrix2)

- **transform_point**`(*args, **kwargs)`
  - transform_point(self, x:float, y:float) -> newx:float, newy:float



## Matrix3
- :Constructors:<br /><br />::<br /><br />    Matrix3()

### Runtime functions †††††
- **affine**`(*args, **kwargs)`
  - affine(self, a:float, b:float, c:float, d:float, e:float, f:float)

- **copy**`(self, /)`
  - documentation unavailable

- **determinant**`(*args, **kwargs)`
  - determinant(self) -> float

- **equal**`(*args, **kwargs)`
  - equal(self, matrix2:Gimp.Matrix3) -> bool

- **identity**`(*args, **kwargs)`
  - identity(self)

- **invert**`(*args, **kwargs)`
  - invert(self)

- **is_affine**`(*args, **kwargs)`
  - is_affine(self) -> bool

- **is_diagonal**`(*args, **kwargs)`
  - is_diagonal(self) -> bool

- **is_identity**`(*args, **kwargs)`
  - is_identity(self) -> bool

- **is_simple**`(*args, **kwargs)`
  - is_simple(self) -> bool

- **mult**`(*args, **kwargs)`
  - mult(self, right:Gimp.Matrix3)

- **rotate**`(*args, **kwargs)`
  - rotate(self, theta:float)

- **scale**`(*args, **kwargs)`
  - scale(self, x:float, y:float)

- **transform_point**`(*args, **kwargs)`
  - transform_point(self, x:float, y:float, newx:float, newy:float)

- **translate**`(*args, **kwargs)`
  - translate(self, x:float, y:float)

- **xshear**`(*args, **kwargs)`
  - xshear(self, amount:float)

- **yshear**`(*args, **kwargs)`
  - yshear(self, amount:float)



## Matrix4
- :Constructors:<br /><br />::<br /><br />    Matrix4()

### Runtime functions ††††††
- **identity**`(*args, **kwargs)`
  - identity(self)

- **mult**`(*args, **kwargs)`
  - mult(self, right:Gimp.Matrix4)

- **to_deg**`(*args, **kwargs)`
  - to_deg(self) -> a:float, b:float, c:float

- **transform_point**`(*args, **kwargs)`
  - transform_point(self, x:float, y:float, z:float) -> float, newx:float, newy:float, newz:float



## MetadataClass
- :Constructors:<br /><br />::<br /><br />    MetadataClass()

## ModuleClass
- :Constructors:<br /><br />::<br /><br />    ModuleClass()

## ModuleDBClass
- :Constructors:<br /><br />::<br /><br />    ModuleDBClass()

## ModuleInfo
- :Constructors:<br /><br />::<br /><br />    ModuleInfo()

## PDBClass
- :Constructors:<br /><br />::<br /><br />    PDBClass()

## PaletteClass
- :Constructors:<br /><br />::<br /><br />    PaletteClass()

## ParamSpecObject
- :Constructors:<br /><br />::<br /><br />    ParamSpecObject()

### Runtime functions †††††††
- **duplicate**`(*args, **kwargs)`
  - duplicate(pspec:GObject.ParamSpec) -> GObject.ParamSpec

- **get_default**`(*args, **kwargs)`
  - get_default(pspec:GObject.ParamSpec) -> GObject.Object

- **has_default**`(*args, **kwargs)`
  - has_default(pspec:GObject.ParamSpec) -> bool

- **set_default**`(*args, **kwargs)`
  - set_default(pspec:GObject.ParamSpec, default_value:GObject.Object=None)



## ParamSpecObjectClass
- :Constructors:<br /><br />::<br /><br />    ParamSpecObjectClass()

## Parasite
- :Constructors:<br /><br />::<br /><br />    Parasite()<br />    new(name:str, flags:int, data:list=None) -> Gimp.Parasite

### Runtime functions ††††††††
- **compare**`(*args, **kwargs)`
  - compare(self, b:Gimp.Parasite) -> bool

- **copy**`(*args, **kwargs)`
  - copy(self) -> Gimp.Parasite

- **free**`(*args, **kwargs)`
  - free(self)

- **get_data**`(*args, **kwargs)`
  - get_data(self) -> list

- **get_flags**`(*args, **kwargs)`
  - get_flags(self) -> int

- **get_name**`(*args, **kwargs)`
  - get_name(self) -> str

- **has_flag**`(*args, **kwargs)`
  - has_flag(self, flag:int) -> bool

- **is_persistent**`(*args, **kwargs)`
  - is_persistent(self) -> bool

- **is_type**`(*args, **kwargs)`
  - is_type(self, name:str) -> bool

- **is_undoable**`(*args, **kwargs)`
  - is_undoable(self) -> bool

- **new**`(*args, **kwargs)`
  - new(name:str, flags:int, data:list=None) -> Gimp.Parasite



## PathClass
- :Constructors:<br /><br />::<br /><br />    PathClass()

## PatternClass
- :Constructors:<br /><br />::<br /><br />    PatternClass()

## PixPipeParams
- :Constructors:<br /><br />::<br /><br />    PixPipeParams()

## PlugInClass
- :Constructors:<br /><br />::<br /><br />    PlugInClass()

## ProcedureClass
- :Constructors:<br /><br />::<br /><br />    ProcedureClass()

## ProcedureConfigClass
- :Constructors:<br /><br />::<br /><br />    ProcedureConfigClass()

## ProgressVtable
- :Constructors:<br /><br />::<br /><br />    ProgressVtable()

## ResourceClass
- :Constructors:<br /><br />::<br /><br />    ResourceClass()

## Scanner
- :Constructors:<br /><br />::<br /><br />    new_file(file:Gio.File) -> Gimp.Scanner<br />    new_stream(input:Gio.InputStream) -> Gimp.Scanner<br />    new_string(text:list) -> Gimp.Scanner

### Runtime functions †††††††††
- **copy**`(self, /)`
  - documentation unavailable

- **new_file**`(*args, **kwargs)`
  - new_file(file:Gio.File) -> Gimp.Scanner

- **new_stream**`(*args, **kwargs)`
  - new_stream(input:Gio.InputStream) -> Gimp.Scanner

- **new_string**`(*args, **kwargs)`
  - new_string(text:list) -> Gimp.Scanner

- **parse_boolean**`(*args, **kwargs)`
  - parse_boolean(self) -> bool, dest:bool

- **parse_color**`(*args, **kwargs)`
  - parse_color(self) -> bool, color:Gegl.Color

- **parse_data**`(*args, **kwargs)`
  - parse_data(self) -> bool, dest:list

- **parse_double**`(*args, **kwargs)`
  - parse_double(self) -> bool, dest:float

- **parse_identifier**`(*args, **kwargs)`
  - parse_identifier(self) -> bool, identifier:str

- **parse_int**`(*args, **kwargs)`
  - parse_int(self) -> bool, dest:int

- **parse_int64**`(*args, **kwargs)`
  - parse_int64(self) -> bool, dest:int

- **parse_matrix2**`(*args, **kwargs)`
  - parse_matrix2(self) -> bool, dest:Gimp.Matrix2

- **parse_string**`(*args, **kwargs)`
  - parse_string(self) -> bool, dest:str

- **parse_string_no_validate**`(*args, **kwargs)`
  - parse_string_no_validate(self) -> bool, dest:str

- **parse_token**`(*args, **kwargs)`
  - parse_token(self, token:GLib.TokenType) -> bool

- **ref**`(*args, **kwargs)`
  - ref(self) -> Gimp.Scanner

- **unref**`(*args, **kwargs)`
  - unref(self)



## SelectionClass
- :Constructors:<br /><br />::<br /><br />    SelectionClass()

## TextLayerClass
- :Constructors:<br /><br />::<br /><br />    TextLayerClass()

## ThumbnailProcedureClass
- :Constructors:<br /><br />::<br /><br />    ThumbnailProcedureClass()

## UnitClass
- :Constructors:<br /><br />::<br /><br />    UnitClass()

## ValueArray
- :Constructors:<br /><br />::<br /><br />    new(n_prealloced:int) -> Gimp.ValueArray<br />    new_from_values(values:list) -> Gimp.ValueArray

### Runtime functions ††††††††††
- **append**`(*args, **kwargs)`
  - append(self, value:GObject.Value=None) -> Gimp.ValueArray

- **copy**`(*args, **kwargs)`
  - copy(self) -> Gimp.ValueArray

- **get_color_array**`(*args, **kwargs)`
  - get_color_array(self, index:int) -> list

- **get_core_object_array**`(*args, **kwargs)`
  - get_core_object_array(self, index:int) -> list

- **index**`(*args, **kwargs)`
  - index(self, index:int) -> GObject.Value

- **insert**`(*args, **kwargs)`
  - insert(self, index:int, value:GObject.Value=None) -> Gimp.ValueArray

- **length**`(*args, **kwargs)`
  - length(self) -> int

- **new**`(*args, **kwargs)`
  - new(n_prealloced:int) -> Gimp.ValueArray

- **new_from_values**`(*args, **kwargs)`
  - new_from_values(values:list) -> Gimp.ValueArray

- **prepend**`(*args, **kwargs)`
  - prepend(self, value:GObject.Value=None) -> Gimp.ValueArray

- **ref**`(*args, **kwargs)`
  - ref(self) -> Gimp.ValueArray

- **remove**`(*args, **kwargs)`
  - remove(self, index:int) -> Gimp.ValueArray

- **truncate**`(*args, **kwargs)`
  - truncate(self, n_values:int)

- **unref**`(*args, **kwargs)`
  - unref(self)



## Vector2
- :Constructors:<br /><br />::<br /><br />    Vector2()<br />    new(x:float, y:float) -> Gimp.Vector2

### Runtime functions †††††††††††
- **add**`(*args, **kwargs)`
  - add(vector1:Gimp.Vector2, vector2:Gimp.Vector2) -> result:Gimp.Vector2

- **add_val**`(*args, **kwargs)`
  - add_val(self, vector2:Gimp.Vector2) -> Gimp.Vector2

- **copy**`(self, /)`
  - documentation unavailable

- **cross_product**`(*args, **kwargs)`
  - cross_product(self, vector2:Gimp.Vector2) -> Gimp.Vector2

- **cross_product_val**`(*args, **kwargs)`
  - cross_product_val(self, vector2:Gimp.Vector2) -> Gimp.Vector2

- **inner_product**`(*args, **kwargs)`
  - inner_product(self, vector2:Gimp.Vector2) -> float

- **inner_product_val**`(*args, **kwargs)`
  - inner_product_val(self, vector2:Gimp.Vector2) -> float

- **length**`(*args, **kwargs)`
  - length(self) -> float

- **length_val**`(*args, **kwargs)`
  - length_val(self) -> float

- **mul**`(*args, **kwargs)`
  - mul(self, factor:float)

- **mul_val**`(*args, **kwargs)`
  - mul_val(self, factor:float) -> Gimp.Vector2

- **neg**`(*args, **kwargs)`
  - neg(self)

- **neg_val**`(*args, **kwargs)`
  - neg_val(self) -> Gimp.Vector2

- **new**`(*args, **kwargs)`
  - new(x:float, y:float) -> Gimp.Vector2

- **normal**`(*args, **kwargs)`
  - normal(self) -> Gimp.Vector2

- **normal_val**`(*args, **kwargs)`
  - normal_val(self) -> Gimp.Vector2

- **normalize**`(*args, **kwargs)`
  - normalize(self)

- **normalize_val**`(*args, **kwargs)`
  - normalize_val(self) -> Gimp.Vector2

- **rotate**`(*args, **kwargs)`
  - rotate(self, alpha:float)

- **rotate_val**`(*args, **kwargs)`
  - rotate_val(self, alpha:float) -> Gimp.Vector2

- **set**`(*args, **kwargs)`
  - set(self, x:float, y:float)

- **sub**`(*args, **kwargs)`
  - sub(vector1:Gimp.Vector2, vector2:Gimp.Vector2) -> result:Gimp.Vector2

- **sub_val**`(*args, **kwargs)`
  - sub_val(self, vector2:Gimp.Vector2) -> Gimp.Vector2



## Vector3
- :Constructors:<br /><br />::<br /><br />    Vector3()<br />    new(x:float, y:float, z:float) -> Gimp.Vector3

### Runtime functions ††††††††††††
- **add**`(*args, **kwargs)`
  - add(vector1:Gimp.Vector3, vector2:Gimp.Vector3) -> result:Gimp.Vector3

- **add_val**`(*args, **kwargs)`
  - add_val(self, vector2:Gimp.Vector3) -> Gimp.Vector3

- **copy**`(self, /)`
  - documentation unavailable

- **cross_product**`(*args, **kwargs)`
  - cross_product(self, vector2:Gimp.Vector3) -> Gimp.Vector3

- **cross_product_val**`(*args, **kwargs)`
  - cross_product_val(self, vector2:Gimp.Vector3) -> Gimp.Vector3

- **inner_product**`(*args, **kwargs)`
  - inner_product(self, vector2:Gimp.Vector3) -> float

- **inner_product_val**`(*args, **kwargs)`
  - inner_product_val(self, vector2:Gimp.Vector3) -> float

- **length**`(*args, **kwargs)`
  - length(self) -> float

- **length_val**`(*args, **kwargs)`
  - length_val(self) -> float

- **mul**`(*args, **kwargs)`
  - mul(self, factor:float)

- **mul_val**`(*args, **kwargs)`
  - mul_val(self, factor:float) -> Gimp.Vector3

- **neg**`(*args, **kwargs)`
  - neg(self)

- **neg_val**`(*args, **kwargs)`
  - neg_val(self) -> Gimp.Vector3

- **new**`(*args, **kwargs)`
  - new(x:float, y:float, z:float) -> Gimp.Vector3

- **normalize**`(*args, **kwargs)`
  - normalize(self)

- **normalize_val**`(*args, **kwargs)`
  - normalize_val(self) -> Gimp.Vector3

- **rotate**`(*args, **kwargs)`
  - rotate(self, alpha:float, beta:float, gamma:float)

- **rotate_val**`(*args, **kwargs)`
  - rotate_val(self, alpha:float, beta:float, gamma:float) -> Gimp.Vector3

- **set**`(*args, **kwargs)`
  - set(self, x:float, y:float, z:float)

- **sub**`(*args, **kwargs)`
  - sub(vector1:Gimp.Vector3, vector2:Gimp.Vector3) -> result:Gimp.Vector3

- **sub_val**`(*args, **kwargs)`
  - sub_val(self, vector2:Gimp.Vector3) -> Gimp.Vector3



## Vector4
- :Constructors:<br /><br />::<br /><br />    Vector4()

## VectorLoadData
- :Constructors:<br /><br />::<br /><br />    VectorLoadData()

## VectorLoadProcedureClass
- :Constructors:<br /><br />::<br /><br />    VectorLoadProcedureClass()
