---
layout: default
title: Gegl.objects
---
# Gegl.objects

## MetadataStore
- :Constructors:<br /><br />::<br /><br />    MetadataStore(**properties)

### Runtime attributes

- **g_type_instance**
- **parent_instance**
- **props**
- **qdata**
- **ref_count**

### Runtime functions
- **bind_property**`(bound native)`
  - documentation unavailable

- **bind_property_full**`(self, *args, **kargs)`
  - documentation unavailable

- **chain**`(bound native)`
  - documentation unavailable

- **compat_control**`(self, *args, **kargs)`
  - documentation unavailable

- **connect**`(bound native)`
  - documentation unavailable

- **connect_after**`(bound native)`
  - documentation unavailable

- **connect_data**`(self, detailed_signal, handler, *data, **kwargs)`
  - Connect a callback to the given signal with optional user data.<br /><br />:param str detailed_signal:<br />    A detailed signal to connect to.<br />:param callable handler:<br />    Callback handler to connect to the signal.<br />:param *data:<br />    Variable data which is passed through to the signal handler.<br />:param GObject.ConnectFlags connect_flags:<br />    Flags used for connection options.<br />:returns:<br />    A signal id which can be used with disconnect.

- **connect_object**`(bound native)`
  - documentation unavailable

- **connect_object_after**`(bound native)`
  - documentation unavailable

- **declare**`(*args, **kwargs)`
  - declare(self, pspec:GObject.ParamSpec)

- **disconnect**`(*args, **kwargs)`
  - signal_handler_disconnect(instance:GObject.Object, handler_id:int)

- **disconnect_by_func**`(bound native)`
  - documentation unavailable

- **do__declare**`(bound native)`
  - _declare(self, pspec:GObject.ParamSpec, shadow:bool)

- **do__get_value**`(bound native)`
  - _get_value(self, name:str) -> GObject.Value

- **do_has_value**`(bound native)`
  - has_value(self, name:str) -> bool

- **do_register_hook**`(bound native)`
  - register_hook(self, file_module_name:str, flags:int)

- **do_set_value**`(bound native)`
  - set_value(self, name:str, value:GObject.Value)

- **emit**`(bound native)`
  - documentation unavailable

- **emit_stop_by_name**`(self, detailed_signal)`
  - Deprecated, please use stop_emission_by_name.

- **find_property**`(*args, **kwargs)`
  - find_property(self, property_name:str) -> GObject.ParamSpec

- **force_floating**`(self, *args, **kargs)`
  - documentation unavailable

- **freeze_notify**`(self)`
  - Freezes the object's property-changed notification queue.<br /><br />:returns:<br />    A context manager which optionally can be used to<br />    automatically thaw notifications.<br /><br />This will freeze the object so that "notify" signals are blocked until<br />the thaw_notify() method is called.<br /><br />.. code-block:: python<br /><br />    with obj.freeze_notify():<br />        pass

- **get_artist**`(*args, **kwargs)`
  - get_artist(self) -> str

- **get_comment**`(*args, **kwargs)`
  - get_comment(self) -> str

- **get_copyright**`(*args, **kwargs)`
  - get_copyright(self) -> str

- **get_data**`(self, *args, **kargs)`
  - documentation unavailable

- **get_description**`(*args, **kwargs)`
  - get_description(self) -> str

- **get_disclaimer**`(*args, **kwargs)`
  - get_disclaimer(self) -> str

- **get_file_module_name**`(*args, **kwargs)`
  - get_file_module_name(self) -> str

- **get_properties**`(bound native)`
  - documentation unavailable

- **get_property**`(bound native)`
  - documentation unavailable

- **get_qdata**`(self, *args, **kargs)`
  - documentation unavailable

- **get_resolution**`(*args, **kwargs)`
  - get_resolution(self, unit:Gegl.ResolutionUnit, x:float, y:float) -> bool

- **get_resolution_unit**`(*args, **kwargs)`
  - get_resolution_unit(self) -> Gegl.ResolutionUnit

- **get_resolution_x**`(*args, **kwargs)`
  - get_resolution_x(self) -> float

- **get_resolution_y**`(*args, **kwargs)`
  - get_resolution_y(self) -> float

- **get_software**`(*args, **kwargs)`
  - get_software(self) -> str

- **get_source**`(*args, **kwargs)`
  - get_source(self) -> str

- **get_string**`(*args, **kwargs)`
  - get_string(self, name:str) -> str

- **get_timestamp**`(*args, **kwargs)`
  - get_timestamp(self) -> GLib.DateTime

- **get_title**`(*args, **kwargs)`
  - get_title(self) -> str

- **get_value**`(*args, **kwargs)`
  - get_value(self, name:str, value:GObject.Value) -> value:GObject.Value

- **get_warning**`(*args, **kwargs)`
  - get_warning(self) -> str

- **getv**`(*args, **kwargs)`
  - getv(self, names:list, values:list)

- **handler_block**`(obj, handler_id)`
  - Blocks the signal handler from being invoked until<br />handler_unblock() is called.<br /><br />:param GObject.Object obj:<br />    Object instance to block handlers for.<br />:param int handler_id:<br />    Id of signal to block.<br />:returns:<br />    A context manager which optionally can be used to<br />    automatically unblock the handler:<br /><br />.. code-block:: python<br /><br />    with GObject.signal_handler_block(obj, id):<br />        pass

- **handler_block_by_func**`(bound native)`
  - documentation unavailable

- **handler_disconnect**`(*args, **kwargs)`
  - signal_handler_disconnect(instance:GObject.Object, handler_id:int)

- **handler_is_connected**`(*args, **kwargs)`
  - signal_handler_is_connected(instance:GObject.Object, handler_id:int) -> bool

- **handler_unblock**`(*args, **kwargs)`
  - signal_handler_unblock(instance:GObject.Object, handler_id:int)

- **handler_unblock_by_func**`(bound native)`
  - documentation unavailable

- **has_value**`(*args, **kwargs)`
  - has_value(self, name:str) -> bool

- **install_properties**`(*args, **kwargs)`
  - install_properties(self, pspecs:list)

- **install_property**`(*args, **kwargs)`
  - install_property(self, property_id:int, pspec:GObject.ParamSpec)

- **interface_find_property**`(self, *args, **kargs)`
  - documentation unavailable

- **interface_install_property**`(self, *args, **kargs)`
  - documentation unavailable

- **interface_list_properties**`(self, *args, **kargs)`
  - documentation unavailable

- **is_floating**`(*args, **kwargs)`
  - is_floating(self) -> bool

- **iter_get_value**`(*args, **kwargs)`
  - iter_get_value(self, iter:Gegl.MetadataIter, value:GObject.Value) -> bool

- **iter_init**`(*args, **kwargs)`
  - iter_init(self, iter:Gegl.MetadataIter)

- **iter_lookup**`(*args, **kwargs)`
  - iter_lookup(self, iter:Gegl.MetadataIter, key:str) -> bool

- **iter_next**`(*args, **kwargs)`
  - iter_next(self, iter:Gegl.MetadataIter) -> str

- **iter_set_value**`(*args, **kwargs)`
  - iter_set_value(self, iter:Gegl.MetadataIter, value:GObject.Value) -> bool

- **list_properties**`(*args, **kwargs)`
  - list_properties(self) -> list

- **newv**`(*args, **kwargs)`
  - newv(object_type:GType, parameters:list) -> GObject.Object

- **notify**`(*args, **kwargs)`
  - notify(self, pspec:GObject.ParamSpec, shadow:bool)

- **notify_by_pspec**`(self, *args, **kargs)`
  - documentation unavailable

- **override_property**`(*args, **kwargs)`
  - override_property(self, property_id:int, name:str)

- **ref**`(self, *args, **kargs)`
  - documentation unavailable

- **ref_sink**`(self, *args, **kargs)`
  - documentation unavailable

- **register**`(*args, **kwargs)`
  - register(self, local_name:str, name:str, transform:GObject.ValueTransform)

- **register_map**`(*args, **kwargs)`
  - register_map(self, file_module:str, flags:int, map:list)

- **replace_data**`(self, *args, **kargs)`
  - documentation unavailable

- **replace_qdata**`(self, *args, **kargs)`
  - documentation unavailable

- **run_dispose**`(*args, **kwargs)`
  - run_dispose(self)

- **set_artist**`(*args, **kwargs)`
  - set_artist(self, artist:str)

- **set_comment**`(*args, **kwargs)`
  - set_comment(self, comment:str)

- **set_copyright**`(*args, **kwargs)`
  - set_copyright(self, copyright:str)

- **set_data**`(self, *args, **kargs)`
  - documentation unavailable

- **set_description**`(*args, **kwargs)`
  - set_description(self, description:str)

- **set_disclaimer**`(*args, **kwargs)`
  - set_disclaimer(self, disclaimer:str)

- **set_properties**`(bound native)`
  - documentation unavailable

- **set_property**`(bound native)`
  - documentation unavailable

- **set_resolution**`(*args, **kwargs)`
  - set_resolution(self, unit:Gegl.ResolutionUnit, x:float, y:float) -> bool

- **set_resolution_unit**`(*args, **kwargs)`
  - set_resolution_unit(self, unit:Gegl.ResolutionUnit)

- **set_resolution_x**`(*args, **kwargs)`
  - set_resolution_x(self, resolution_x:float)

- **set_resolution_y**`(*args, **kwargs)`
  - set_resolution_y(self, resolution_y:float)

- **set_software**`(*args, **kwargs)`
  - set_software(self, software:str)

- **set_source**`(*args, **kwargs)`
  - set_source(self, source:str)

- **set_string**`(*args, **kwargs)`
  - set_string(self, name:str, string:str)

- **set_timestamp**`(*args, **kwargs)`
  - set_timestamp(self, timestamp:GLib.DateTime)

- **set_title**`(*args, **kwargs)`
  - set_title(self, title:str)

- **set_value**`(*args, **kwargs)`
  - set_value(self, name:str, value:GObject.Value)

- **set_warning**`(*args, **kwargs)`
  - set_warning(self, warning:str)

- **steal_data**`(self, *args, **kargs)`
  - documentation unavailable

- **steal_qdata**`(self, *args, **kargs)`
  - documentation unavailable

- **stop_emission**`(self, detailed_signal)`
  - Deprecated, please use stop_emission_by_name.

- **stop_emission_by_name**`(*args, **kwargs)`
  - signal_stop_emission_by_name(instance:GObject.Object, detailed_signal:str)

- **thaw_notify**`(*args, **kwargs)`
  - thaw_notify(self)

- **typeof_value**`(*args, **kwargs)`
  - typeof_value(self, name:str) -> GType

- **unref**`(self, *args, **kargs)`
  - documentation unavailable

- **unregister_map**`(*args, **kwargs)`
  - unregister_map(self)

- **watch_closure**`(self, *args, **kargs)`
  - documentation unavailable

- **weak_ref**`(bound native)`
  - documentation unavailable


