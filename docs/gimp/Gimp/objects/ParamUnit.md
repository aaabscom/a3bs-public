---
layout: default
title: Gimp.objects
---
# Gimp.objects

## ParamUnit
- :Constructors:<br /><br />::<br /><br />    ParamUnit(**properties)

### Runtime attributes

- **flags**
- **g_type_instance**
- **name**
- **owner_type**
- **param_id**
- **parent_instance**
- **qdata**
- **ref_count**
- **value_type**

### Runtime functions
- **blurb**`(fget)`
  - documentation unavailable

- **do_finalize**`(bound native)`
  - finalize(self)

- **do_get_property**`(self, pspec)`
  - documentation unavailable

- **do_set_property**`(self, pspec, value)`
  - documentation unavailable

- **do_value_is_valid**`(bound native)`
  - value_is_valid(self, value:GObject.Value) -> bool

- **do_value_set_default**`(bound native)`
  - value_set_default(self, value:GObject.Value)

- **do_value_validate**`(bound native)`
  - value_validate(self, value:GObject.Value) -> bool

- **do_values_cmp**`(bound native)`
  - values_cmp(self, value1:GObject.Value, value2:GObject.Value) -> int

- **get_blurb**`(*args, **kwargs)`
  - get_blurb(self) -> str or None

- **get_default_value**`(*args, **kwargs)`
  - get_default_value(self) -> GObject.Value

- **get_name**`(*args, **kwargs)`
  - get_name(self) -> str

- **get_name_quark**`(*args, **kwargs)`
  - get_name_quark(self) -> int

- **get_nick**`(*args, **kwargs)`
  - get_nick(self) -> str

- **get_qdata**`(*args, **kwargs)`
  - get_qdata(self, quark:int)

- **get_redirect_target**`(*args, **kwargs)`
  - get_redirect_target(self) -> GObject.ParamSpec or None

- **is_valid_name**`(*args, **kwargs)`
  - is_valid_name(name:str) -> bool

- **nick**`(fget)`
  - documentation unavailable

- **set_qdata**`(*args, **kwargs)`
  - set_qdata(self, quark:int, data=None)

- **sink**`(*args, **kwargs)`
  - sink(self)

- **steal_qdata**`(*args, **kwargs)`
  - steal_qdata(self, quark:int)


