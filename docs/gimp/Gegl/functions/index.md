---
layout: default
title: Gegl.functions
---
# Gegl.functions

## babl_variant
- babl_variant(format:Babl.Object, variant:Gegl.BablVariant) -> Babl.Object

### Runtime functions †
- **can_throw_gerror**`()`
  - documentation unavailable

- **equal**`(object, /)`
  - documentation unavailable

- **get_arguments**`()`
  - documentation unavailable

- **get_attribute**`(object, /)`
  - documentation unavailable

- **get_caller_owns**`()`
  - documentation unavailable

- **get_container**`()`
  - documentation unavailable

- **get_flags**`()`
  - documentation unavailable

- **get_name**`()`
  - documentation unavailable

- **get_name_unescaped**`()`
  - documentation unavailable

- **get_namespace**`()`
  - documentation unavailable

- **get_property**`()`
  - documentation unavailable

- **get_return_attribute**`(object, /)`
  - documentation unavailable

- **get_return_type**`()`
  - documentation unavailable

- **get_symbol**`()`
  - documentation unavailable

- **get_type**`()`
  - documentation unavailable

- **get_vfunc**`()`
  - documentation unavailable

- **invoke**`(bound native)`
  - documentation unavailable

- **is_constructor**`()`
  - documentation unavailable

- **is_deprecated**`()`
  - documentation unavailable

- **is_method**`()`
  - documentation unavailable

- **may_return_null**`()`
  - documentation unavailable

- **skip_return**`()`
  - documentation unavailable



## cl_disable
- cl_disable()

### Runtime functions †


## cl_init
- cl_init() -> bool

### Runtime functions †


## cl_is_accelerated
- cl_is_accelerated() -> bool

### Runtime functions †


## config
- config() -> Gegl.Config

### Runtime functions †


## create_chain
- create_chain(ops:str, op_start:Gegl.Node, op_end:Gegl.Node, time:float, rel_dim:int, path_root:str)

### Runtime functions †


## create_chain_argv
- create_chain_argv(ops:str, op_start:Gegl.Node, op_end:Gegl.Node, time:float, rel_dim:int, path_root:str)

### Runtime functions †


## exit
- exit()

### Runtime functions †


## format
- format(format_name:str) -> GObject.Value or None

### Runtime functions †


## format_get_name
- format_get_name(format:GObject.Value) -> str or None

### Runtime functions †


## get_version
- get_version() -> major:int, minor:int, micro:int

### Runtime functions †


## graph_dump_outputs
- graph_dump_outputs(node:Gegl.Node)

### Runtime functions †


## graph_dump_request
- graph_dump_request(node:Gegl.Node, roi:Gegl.Rectangle)

### Runtime functions †


## has_operation
- has_operation(operation_type:str) -> bool

### Runtime functions †


## init
- init(argv:list=None) -> argv:list

### Runtime functions †


## is_main_thread
- is_main_thread() -> bool

### Runtime functions †


## list_operations
- list_operations() -> list

### Runtime functions †


## load_module_directory
- load_module_directory(path:str)

### Runtime functions †


## parallel_distribute
- parallel_distribute(max_n:int, func:Gegl.ParallelDistributeFunc, user_data=None)

### Runtime functions †


## parallel_distribute_area
- parallel_distribute_area(area:Gegl.Rectangle, thread_cost:float, split_strategy:Gegl.SplitStrategy, func:Gegl.ParallelDistributeAreaFunc, user_data=None)

### Runtime functions †


## parallel_distribute_range
- parallel_distribute_range(size:int, thread_cost:float, func:Gegl.ParallelDistributeRangeFunc, user_data=None)

### Runtime functions †


## param_spec_audio_fragment
- param_spec_audio_fragment(name:str, nick:str, blurb:str, flags:GObject.ParamFlags) -> GObject.ParamSpec

### Runtime functions †


## param_spec_color
- param_spec_color(name:str, nick:str, blurb:str, default_color:Gegl.Color, flags:GObject.ParamFlags) -> GObject.ParamSpec

### Runtime functions †


## param_spec_color_from_string
- param_spec_color_from_string(name:str, nick:str, blurb:str, default_color_string:str, flags:GObject.ParamFlags) -> GObject.ParamSpec

### Runtime functions †


## param_spec_color_get_default
- param_spec_color_get_default(self:GObject.ParamSpec) -> Gegl.Color

### Runtime functions †


## param_spec_curve
- param_spec_curve(name:str, nick:str, blurb:str, default_curve:Gegl.Curve, flags:GObject.ParamFlags) -> GObject.ParamSpec

### Runtime functions †


## param_spec_double
- param_spec_double(name:str, nick:str, blurb:str, minimum:float, maximum:float, default_value:float, ui_minimum:float, ui_maximum:float, ui_gamma:float, flags:GObject.ParamFlags) -> GObject.ParamSpec

### Runtime functions †


## param_spec_enum
- param_spec_enum(name:str, nick:str, blurb:str, enum_type:GType, default_value:int, flags:GObject.ParamFlags) -> GObject.ParamSpec

### Runtime functions †


## param_spec_file_path
- param_spec_file_path(name:str, nick:str, blurb:str, no_validate:bool, null_ok:bool, default_value:str, flags:GObject.ParamFlags) -> GObject.ParamSpec

### Runtime functions †


## param_spec_format
- param_spec_format(name:str, nick:str, blurb:str, flags:GObject.ParamFlags) -> GObject.ParamSpec

### Runtime functions †


## param_spec_get_property_key
- param_spec_get_property_key(pspec:GObject.ParamSpec, key_name:str) -> str

### Runtime functions †


## param_spec_int
- param_spec_int(name:str, nick:str, blurb:str, minimum:int, maximum:int, default_value:int, ui_minimum:int, ui_maximum:int, ui_gamma:float, flags:GObject.ParamFlags) -> GObject.ParamSpec

### Runtime functions †


## param_spec_path
- param_spec_path(name:str, nick:str, blurb:str, default_path:Gegl.Path, flags:GObject.ParamFlags) -> GObject.ParamSpec

### Runtime functions †


## param_spec_seed
- param_spec_seed(name:str, nick:str, blurb:str, flags:GObject.ParamFlags) -> GObject.ParamSpec

### Runtime functions †


## param_spec_set_property_key
- param_spec_set_property_key(pspec:GObject.ParamSpec, key_name:str, value:str)

### Runtime functions †


## param_spec_string
- param_spec_string(name:str, nick:str, blurb:str, no_validate:bool, null_ok:bool, default_value:str, flags:GObject.ParamFlags) -> GObject.ParamSpec

### Runtime functions †


## param_spec_uri
- param_spec_uri(name:str, nick:str, blurb:str, no_validate:bool, null_ok:bool, default_value:str, flags:GObject.ParamFlags) -> GObject.ParamSpec

### Runtime functions †


## rectangle_infinite_plane
- rectangle_infinite_plane() -> Gegl.Rectangle

### Runtime functions †


## reset_stats
- reset_stats()

### Runtime functions †


## serialize
- serialize(start:Gegl.Node, end:Gegl.Node, basepath:str, serialize_flags:Gegl.SerializeFlag) -> str

### Runtime functions †


## stats
- stats() -> Gegl.Stats

### Runtime functions †

