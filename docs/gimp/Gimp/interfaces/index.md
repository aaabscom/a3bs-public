---
layout: default
title: Gimp.interfaces
---
# Gimp.interfaces

## ColorManaged

### Runtime functions †
- **get_color_profile**`(*args, **kwargs)`
  - get_color_profile(self) -> Gimp.ColorProfile

- **get_icc_profile**`(*args, **kwargs)`
  - get_icc_profile(self) -> list

- **get_simulation_bpc**`(*args, **kwargs)`
  - get_simulation_bpc(self) -> bool

- **get_simulation_intent**`(*args, **kwargs)`
  - get_simulation_intent(self) -> Gimp.ColorRenderingIntent

- **get_simulation_profile**`(*args, **kwargs)`
  - get_simulation_profile(self) -> Gimp.ColorProfile

- **profile_changed**`(*args, **kwargs)`
  - profile_changed(self)

- **simulation_bpc_changed**`(*args, **kwargs)`
  - simulation_bpc_changed(self)

- **simulation_intent_changed**`(*args, **kwargs)`
  - simulation_intent_changed(self)

- **simulation_profile_changed**`(*args, **kwargs)`
  - simulation_profile_changed(self)



## ConfigInterface

### Runtime functions ††
- **build_data_path**`(*args, **kwargs)`
  - build_data_path(name:str) -> str

- **build_plug_in_path**`(*args, **kwargs)`
  - build_plug_in_path(name:str) -> str

- **build_system_path**`(*args, **kwargs)`
  - build_system_path(name:str) -> str

- **build_writable_path**`(*args, **kwargs)`
  - build_writable_path(name:str) -> str

- **deserialize_return**`(*args, **kwargs)`
  - deserialize_return(scanner:GLib.Scanner, expected_token:GLib.TokenType, nest_level:int) -> bool

- **diff**`(*args, **kwargs)`
  - diff(a:GObject.Object, b:GObject.Object, flags:GObject.ParamFlags) -> list

- **error_quark**`(*args, **kwargs)`
  - error_quark() -> int

- **param_spec_duplicate**`(*args, **kwargs)`
  - param_spec_duplicate(pspec:GObject.ParamSpec) -> GObject.ParamSpec

- **reset_properties**`(*args, **kwargs)`
  - reset_properties(object:GObject.Object)

- **reset_property**`(*args, **kwargs)`
  - reset_property(object:GObject.Object, property_name:str)

- **serialize_value**`(*args, **kwargs)`
  - serialize_value(value:GObject.Value, str:GLib.String, escaped:bool) -> bool

- **string_append_escaped**`(*args, **kwargs)`
  - string_append_escaped(string:GLib.String, val:str)

- **sync**`(*args, **kwargs)`
  - sync(src:GObject.Object, dest:GObject.Object, flags:GObject.ParamFlags) -> bool

- **type_register**`(*args, **kwargs)`
  - type_register(parent_type:GType, type_name:str, pspecs:list) -> GType


