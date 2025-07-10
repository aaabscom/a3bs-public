---
layout: default
title: GObject.structs
---
# GObject.structs

## CClosure
- :Constructors:<br /><br />::<br /><br />    CClosure()

### Runtime functions †
- **marshal_BOOLEAN__BOXED_BOXED**`(*args, **kwargs)`
  - marshal_BOOLEAN__BOXED_BOXED(closure:GObject.Closure, return_value:GObject.Value, n_param_values:int, param_values:GObject.Value, invocation_hint=None, marshal_data=None)

- **marshal_BOOLEAN__FLAGS**`(*args, **kwargs)`
  - marshal_BOOLEAN__FLAGS(closure:GObject.Closure, return_value:GObject.Value, n_param_values:int, param_values:GObject.Value, invocation_hint=None, marshal_data=None)

- **marshal_STRING__OBJECT_POINTER**`(*args, **kwargs)`
  - marshal_STRING__OBJECT_POINTER(closure:GObject.Closure, return_value:GObject.Value, n_param_values:int, param_values:GObject.Value, invocation_hint=None, marshal_data=None)

- **marshal_VOID__BOOLEAN**`(*args, **kwargs)`
  - marshal_VOID__BOOLEAN(closure:GObject.Closure, return_value:GObject.Value, n_param_values:int, param_values:GObject.Value, invocation_hint=None, marshal_data=None)

- **marshal_VOID__BOXED**`(*args, **kwargs)`
  - marshal_VOID__BOXED(closure:GObject.Closure, return_value:GObject.Value, n_param_values:int, param_values:GObject.Value, invocation_hint=None, marshal_data=None)

- **marshal_VOID__CHAR**`(*args, **kwargs)`
  - marshal_VOID__CHAR(closure:GObject.Closure, return_value:GObject.Value, n_param_values:int, param_values:GObject.Value, invocation_hint=None, marshal_data=None)

- **marshal_VOID__DOUBLE**`(*args, **kwargs)`
  - marshal_VOID__DOUBLE(closure:GObject.Closure, return_value:GObject.Value, n_param_values:int, param_values:GObject.Value, invocation_hint=None, marshal_data=None)

- **marshal_VOID__ENUM**`(*args, **kwargs)`
  - marshal_VOID__ENUM(closure:GObject.Closure, return_value:GObject.Value, n_param_values:int, param_values:GObject.Value, invocation_hint=None, marshal_data=None)

- **marshal_VOID__FLAGS**`(*args, **kwargs)`
  - marshal_VOID__FLAGS(closure:GObject.Closure, return_value:GObject.Value, n_param_values:int, param_values:GObject.Value, invocation_hint=None, marshal_data=None)

- **marshal_VOID__FLOAT**`(*args, **kwargs)`
  - marshal_VOID__FLOAT(closure:GObject.Closure, return_value:GObject.Value, n_param_values:int, param_values:GObject.Value, invocation_hint=None, marshal_data=None)

- **marshal_VOID__INT**`(*args, **kwargs)`
  - marshal_VOID__INT(closure:GObject.Closure, return_value:GObject.Value, n_param_values:int, param_values:GObject.Value, invocation_hint=None, marshal_data=None)

- **marshal_VOID__LONG**`(*args, **kwargs)`
  - marshal_VOID__LONG(closure:GObject.Closure, return_value:GObject.Value, n_param_values:int, param_values:GObject.Value, invocation_hint=None, marshal_data=None)

- **marshal_VOID__OBJECT**`(*args, **kwargs)`
  - marshal_VOID__OBJECT(closure:GObject.Closure, return_value:GObject.Value, n_param_values:int, param_values:GObject.Value, invocation_hint=None, marshal_data=None)

- **marshal_VOID__PARAM**`(*args, **kwargs)`
  - marshal_VOID__PARAM(closure:GObject.Closure, return_value:GObject.Value, n_param_values:int, param_values:GObject.Value, invocation_hint=None, marshal_data=None)

- **marshal_VOID__POINTER**`(*args, **kwargs)`
  - marshal_VOID__POINTER(closure:GObject.Closure, return_value:GObject.Value, n_param_values:int, param_values:GObject.Value, invocation_hint=None, marshal_data=None)

- **marshal_VOID__STRING**`(*args, **kwargs)`
  - marshal_VOID__STRING(closure:GObject.Closure, return_value:GObject.Value, n_param_values:int, param_values:GObject.Value, invocation_hint=None, marshal_data=None)

- **marshal_VOID__UCHAR**`(*args, **kwargs)`
  - marshal_VOID__UCHAR(closure:GObject.Closure, return_value:GObject.Value, n_param_values:int, param_values:GObject.Value, invocation_hint=None, marshal_data=None)

- **marshal_VOID__UINT**`(*args, **kwargs)`
  - marshal_VOID__UINT(closure:GObject.Closure, return_value:GObject.Value, n_param_values:int, param_values:GObject.Value, invocation_hint=None, marshal_data=None)

- **marshal_VOID__UINT_POINTER**`(*args, **kwargs)`
  - marshal_VOID__UINT_POINTER(closure:GObject.Closure, return_value:GObject.Value, n_param_values:int, param_values:GObject.Value, invocation_hint=None, marshal_data=None)

- **marshal_VOID__ULONG**`(*args, **kwargs)`
  - marshal_VOID__ULONG(closure:GObject.Closure, return_value:GObject.Value, n_param_values:int, param_values:GObject.Value, invocation_hint=None, marshal_data=None)

- **marshal_VOID__VARIANT**`(*args, **kwargs)`
  - marshal_VOID__VARIANT(closure:GObject.Closure, return_value:GObject.Value, n_param_values:int, param_values:GObject.Value, invocation_hint=None, marshal_data=None)

- **marshal_VOID__VOID**`(*args, **kwargs)`
  - marshal_VOID__VOID(closure:GObject.Closure, return_value:GObject.Value, n_param_values:int, param_values:GObject.Value, invocation_hint=None, marshal_data=None)

- **marshal_generic**`(*args, **kwargs)`
  - marshal_generic(closure:GObject.Closure, return_gvalue:GObject.Value, n_param_values:int, param_values:GObject.Value, invocation_hint=None, marshal_data=None)



## Closure
- :Constructors:<br /><br />::<br /><br />    Closure()<br />    new_object(sizeof_closure:int, object:GObject.Object) -> GObject.Closure<br />    new_simple(sizeof_closure:int, data=None) -> GObject.Closure

### Runtime functions ††
- **copy**`(self, /)`
  - documentation unavailable

- **invalidate**`(*args, **kwargs)`
  - invalidate(self)

- **invoke**`(*args, **kwargs)`
  - invoke(self, param_values:list, invocation_hint=None) -> return_value:GObject.Value

- **new_object**`(*args, **kwargs)`
  - new_object(sizeof_closure:int, object:GObject.Object) -> GObject.Closure

- **new_simple**`(*args, **kwargs)`
  - new_simple(sizeof_closure:int, data=None) -> GObject.Closure

- **ref**`(*args, **kwargs)`
  - ref(self) -> GObject.Closure

- **sink**`(*args, **kwargs)`
  - sink(self)

- **unref**`(*args, **kwargs)`
  - unref(self)



## ClosureNotifyData
- :Constructors:<br /><br />::<br /><br />    ClosureNotifyData()

## EnumClass
- :Constructors:<br /><br />::<br /><br />    EnumClass()

## EnumValue
- :Constructors:<br /><br />::<br /><br />    EnumValue()

## FlagsClass
- :Constructors:<br /><br />::<br /><br />    FlagsClass()

## FlagsValue
- :Constructors:<br /><br />::<br /><br />    FlagsValue()

## InitiallyUnownedClass
- :Constructors:<br /><br />::<br /><br />    InitiallyUnownedClass()

## InterfaceInfo
- :Constructors:<br /><br />::<br /><br />    InterfaceInfo()

## ObjectClass
- :Constructors:<br /><br />::<br /><br />    ObjectClass()

### Runtime functions †††
- **find_property**`(*args, **kwargs)`
  - find_property(self, property_name:str) -> GObject.ParamSpec

- **install_properties**`(*args, **kwargs)`
  - install_properties(self, pspecs:list)

- **install_property**`(*args, **kwargs)`
  - install_property(self, property_id:int, pspec:GObject.ParamSpec)

- **list_properties**`(*args, **kwargs)`
  - list_properties(self) -> list

- **override_property**`(*args, **kwargs)`
  - override_property(self, property_id:int, name:str)



## ObjectConstructParam
- :Constructors:<br /><br />::<br /><br />    ObjectConstructParam()

## ParamSpecClass
- :Constructors:<br /><br />::<br /><br />    ParamSpecClass()

## ParamSpecPool

### Runtime functions ††††
- **free**`(*args, **kwargs)`
  - free(self)

- **insert**`(*args, **kwargs)`
  - insert(self, pspec:GObject.ParamSpec, owner_type:GType)

- **list**`(*args, **kwargs)`
  - list(self, owner_type:GType) -> list

- **list_owned**`(*args, **kwargs)`
  - list_owned(self, owner_type:GType) -> list

- **lookup**`(*args, **kwargs)`
  - lookup(self, param_name:str, owner_type:GType, walk_ancestors:bool) -> GObject.ParamSpec or None

- **remove**`(*args, **kwargs)`
  - remove(self, pspec:GObject.ParamSpec)



## ParamSpecTypeInfo
- :Constructors:<br /><br />::<br /><br />    ParamSpecTypeInfo()

## Parameter
- :Constructors:<br /><br />::<br /><br />    Parameter()

## SignalInvocationHint
- :Constructors:<br /><br />::<br /><br />    SignalInvocationHint()

## SignalQuery
- :Constructors:<br /><br />::<br /><br />    SignalQuery()

## TypeClass
- :Constructors:<br /><br />::<br /><br />    TypeClass()

### Runtime functions †††††
- **add_private**`(*args, **kwargs)`
  - add_private(self, private_size:int)

- **adjust_private_offset**`(*args, **kwargs)`
  - adjust_private_offset(g_class=None, private_size_or_offset:int)

- **get**`(*args, **kwargs)`
  - get(type:GType) -> GObject.TypeClass

- **get_private**`(*args, **kwargs)`
  - get_private(self, private_type:GType)

- **peek**`(*args, **kwargs)`
  - peek(type:GType) -> GObject.TypeClass or None

- **peek_parent**`(*args, **kwargs)`
  - peek_parent(self) -> GObject.TypeClass

- **peek_static**`(*args, **kwargs)`
  - peek_static(type:GType) -> GObject.TypeClass or None

- **ref**`(*args, **kwargs)`
  - ref(type:GType) -> GObject.TypeClass

- **unref**`(*args, **kwargs)`
  - unref(self)



## TypeFundamentalInfo
- :Constructors:<br /><br />::<br /><br />    TypeFundamentalInfo()

## TypeInfo
- :Constructors:<br /><br />::<br /><br />    TypeInfo()

## TypeInstance
- :Constructors:<br /><br />::<br /><br />    TypeInstance()

### Runtime functions ††††††
- **get_private**`(*args, **kwargs)`
  - get_private(self, private_type:GType)



## TypeInterface
- :Constructors:<br /><br />::<br /><br />    TypeInterface()

### Runtime functions †††††††
- **add_prerequisite**`(*args, **kwargs)`
  - add_prerequisite(interface_type:GType, prerequisite_type:GType)

- **get_plugin**`(*args, **kwargs)`
  - get_plugin(instance_type:GType, interface_type:GType) -> GObject.TypePlugin

- **instantiatable_prerequisite**`(*args, **kwargs)`
  - instantiatable_prerequisite(interface_type:GType) -> GType

- **peek**`(*args, **kwargs)`
  - peek(instance_class:GObject.TypeClass, iface_type:GType) -> GObject.TypeInterface or None

- **peek_parent**`(*args, **kwargs)`
  - peek_parent(self) -> GObject.TypeInterface or None

- **prerequisites**`(*args, **kwargs)`
  - prerequisites(interface_type:GType) -> list



## TypeModuleClass
- :Constructors:<br /><br />::<br /><br />    TypeModuleClass()

## TypePluginClass
- :Constructors:<br /><br />::<br /><br />    TypePluginClass()

## TypeQuery
- :Constructors:<br /><br />::<br /><br />    TypeQuery()

## TypeValueTable
- :Constructors:<br /><br />::<br /><br />    TypeValueTable()

## Value
- :Constructors:<br /><br />::<br /><br />    Value()

### Runtime functions ††††††††
- **copy**`(*args, **kwargs)`
  - copy(self, dest_value:GObject.Value)

- **dup_object**`(*args, **kwargs)`
  - dup_object(self) -> GObject.Object or None

- **dup_string**`(*args, **kwargs)`
  - dup_string(self) -> str or None

- **dup_variant**`(*args, **kwargs)`
  - dup_variant(self) -> GLib.Variant or None

- **fits_pointer**`(*args, **kwargs)`
  - fits_pointer(self) -> bool

- **get_boolean**`(*args, **kwargs)`
  - get_boolean(self) -> bool

- **get_boxed**`(self)`
  - get_boxed(self)

- **get_char**`(*args, **kwargs)`
  - get_char(self) -> int

- **get_double**`(*args, **kwargs)`
  - get_double(self) -> float

- **get_enum**`(*args, **kwargs)`
  - get_enum(self) -> int

- **get_flags**`(*args, **kwargs)`
  - get_flags(self) -> int

- **get_float**`(*args, **kwargs)`
  - get_float(self) -> float

- **get_gtype**`(*args, **kwargs)`
  - get_gtype(self) -> GType

- **get_int**`(*args, **kwargs)`
  - get_int(self) -> int

- **get_int64**`(*args, **kwargs)`
  - get_int64(self) -> int

- **get_long**`(*args, **kwargs)`
  - get_long(self) -> int

- **get_object**`(*args, **kwargs)`
  - get_object(self) -> GObject.Object or None

- **get_param**`(*args, **kwargs)`
  - get_param(self) -> GObject.ParamSpec

- **get_pointer**`(*args, **kwargs)`
  - get_pointer(self)

- **get_schar**`(*args, **kwargs)`
  - get_schar(self) -> int

- **get_string**`(*args, **kwargs)`
  - get_string(self) -> str or None

- **get_uchar**`(*args, **kwargs)`
  - get_uchar(self) -> int

- **get_uint**`(*args, **kwargs)`
  - get_uint(self) -> int

- **get_uint64**`(*args, **kwargs)`
  - get_uint64(self) -> int

- **get_ulong**`(*args, **kwargs)`
  - get_ulong(self) -> int

- **get_value**`(self)`
  - documentation unavailable

- **get_variant**`(*args, **kwargs)`
  - get_variant(self) -> GLib.Variant or None

- **init**`(*args, **kwargs)`
  - init(self, g_type:GType) -> GObject.Value

- **init_from_instance**`(*args, **kwargs)`
  - init_from_instance(self, instance:GObject.TypeInstance)

- **peek_pointer**`(*args, **kwargs)`
  - peek_pointer(self)

- **reset**`(*args, **kwargs)`
  - reset(self) -> GObject.Value

- **set_boolean**`(*args, **kwargs)`
  - set_boolean(self, v_boolean:bool)

- **set_boxed**`(self, boxed)`
  - set_boxed(self, v_boxed=None)

- **set_boxed_take_ownership**`(*args, **kwargs)`
  - set_boxed_take_ownership(self, v_boxed=None)

- **set_char**`(*args, **kwargs)`
  - set_char(self, v_char:int)

- **set_double**`(*args, **kwargs)`
  - set_double(self, v_double:float)

- **set_enum**`(*args, **kwargs)`
  - set_enum(self, v_enum:int)

- **set_flags**`(*args, **kwargs)`
  - set_flags(self, v_flags:int)

- **set_float**`(*args, **kwargs)`
  - set_float(self, v_float:float)

- **set_gtype**`(*args, **kwargs)`
  - set_gtype(self, v_gtype:GType)

- **set_instance**`(*args, **kwargs)`
  - set_instance(self, instance=None)

- **set_int**`(*args, **kwargs)`
  - set_int(self, v_int:int)

- **set_int64**`(*args, **kwargs)`
  - set_int64(self, v_int64:int)

- **set_interned_string**`(*args, **kwargs)`
  - set_interned_string(self, v_string:str=None)

- **set_long**`(*args, **kwargs)`
  - set_long(self, v_long:int)

- **set_object**`(*args, **kwargs)`
  - set_object(self, v_object:GObject.Object=None)

- **set_param**`(*args, **kwargs)`
  - set_param(self, param:GObject.ParamSpec=None)

- **set_pointer**`(*args, **kwargs)`
  - set_pointer(self, v_pointer=None)

- **set_schar**`(*args, **kwargs)`
  - set_schar(self, v_char:int)

- **set_static_boxed**`(*args, **kwargs)`
  - set_static_boxed(self, v_boxed=None)

- **set_static_string**`(*args, **kwargs)`
  - set_static_string(self, v_string:str=None)

- **set_string**`(*args, **kwargs)`
  - set_string(self, v_string:str=None)

- **set_string_take_ownership**`(*args, **kwargs)`
  - set_string_take_ownership(self, v_string:str=None)

- **set_uchar**`(*args, **kwargs)`
  - set_uchar(self, v_uchar:int)

- **set_uint**`(*args, **kwargs)`
  - set_uint(self, v_uint:int)

- **set_uint64**`(*args, **kwargs)`
  - set_uint64(self, v_uint64:int)

- **set_ulong**`(*args, **kwargs)`
  - set_ulong(self, v_ulong:int)

- **set_value**`(self, py_value)`
  - documentation unavailable

- **set_variant**`(*args, **kwargs)`
  - set_variant(self, variant:GLib.Variant=None)

- **steal_string**`(*args, **kwargs)`
  - steal_string(self) -> str or None

- **take_boxed**`(*args, **kwargs)`
  - take_boxed(self, v_boxed=None)

- **take_string**`(*args, **kwargs)`
  - take_string(self, v_string:str=None)

- **take_variant**`(*args, **kwargs)`
  - take_variant(self, variant:GLib.Variant=None)

- **transform**`(*args, **kwargs)`
  - transform(self, dest_value:GObject.Value) -> bool

- **type_compatible**`(*args, **kwargs)`
  - type_compatible(src_type:GType, dest_type:GType) -> bool

- **type_transformable**`(*args, **kwargs)`
  - type_transformable(src_type:GType, dest_type:GType) -> bool

- **unset**`(*args, **kwargs)`
  - unset(self)



## ValueArray
- :Constructors:<br /><br />::<br /><br />    ValueArray()<br />    new(n_prealloced:int) -> GObject.ValueArray

### Runtime functions †††††††††
- **append**`(*args, **kwargs)`
  - append(self, value:GObject.Value=None) -> GObject.ValueArray

- **copy**`(*args, **kwargs)`
  - copy(self) -> GObject.ValueArray

- **get_nth**`(*args, **kwargs)`
  - get_nth(self, index_:int) -> GObject.Value

- **insert**`(*args, **kwargs)`
  - insert(self, index_:int, value:GObject.Value=None) -> GObject.ValueArray

- **new**`(*args, **kwargs)`
  - new(n_prealloced:int) -> GObject.ValueArray

- **prepend**`(*args, **kwargs)`
  - prepend(self, value:GObject.Value=None) -> GObject.ValueArray

- **remove**`(*args, **kwargs)`
  - remove(self, index_:int) -> GObject.ValueArray

- **sort**`(*args, **kwargs)`
  - sort(self, compare_func:GLib.CompareDataFunc, user_data=None) -> GObject.ValueArray



## WeakRef
