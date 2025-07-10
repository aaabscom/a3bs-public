---
layout: default
title: Gimp.objects
---
# Gimp.objects

## Module
- :Constructors:<br /><br />::<br /><br />    Module(**properties)<br />    new(file:Gio.File, auto_load:bool, verbose:bool) -> Gimp.Module

### Runtime attributes

- **g_type_instance**
- **interface_infos**
- **name**
- **parent_instance**
- **props**
- **qdata**
- **ref_count**
- **type_infos**
- **use_count**

### Runtime functions
- **add_interface**`(*args, **kwargs)`
  - add_interface(self, instance_type:GType, interface_type:GType, interface_info:GObject.InterfaceInfo)

- **bind_property**`(bound native)`
  - documentation unavailable

- **bind_property_full**`(self, *args, **kargs)`
  - documentation unavailable

- **chain**`(bound native)`
  - documentation unavailable

- **compat_control**`(self, *args, **kargs)`
  - documentation unavailable

- **complete_interface_info**`(*args, **kwargs)`
  - complete_interface_info(self, instance_type:GType, interface_type:GType, info:GObject.InterfaceInfo)

- **complete_type_info**`(*args, **kwargs)`
  - complete_type_info(self, g_type:GType, info:GObject.TypeInfo, value_table:GObject.TypeValueTable)

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

- **disconnect**`(*args, **kwargs)`
  - signal_handler_disconnect(instance:GObject.Object, handler_id:int)

- **disconnect_by_func**`(bound native)`
  - documentation unavailable

- **do_load**`(bound native)`
  - load(self) -> bool

- **do_modified**`(bound native)`
  - modified(self)

- **do_unload**`(bound native)`
  - unload(self)

- **emit**`(bound native)`
  - documentation unavailable

- **emit_stop_by_name**`(self, detailed_signal)`
  - Deprecated, please use stop_emission_by_name.

- **error_quark**`(*args, **kwargs)`
  - error_quark() -> int

- **find_property**`(*args, **kwargs)`
  - find_property(self, property_name:str) -> GObject.ParamSpec

- **force_floating**`(self, *args, **kargs)`
  - documentation unavailable

- **freeze_notify**`(self)`
  - Freezes the object's property-changed notification queue.<br /><br />:returns:<br />    A context manager which optionally can be used to<br />    automatically thaw notifications.<br /><br />This will freeze the object so that "notify" signals are blocked until<br />the thaw_notify() method is called.<br /><br />.. code-block:: python<br /><br />    with obj.freeze_notify():<br />        pass

- **get_auto_load**`(*args, **kwargs)`
  - get_auto_load(self) -> bool

- **get_data**`(self, *args, **kargs)`
  - documentation unavailable

- **get_file**`(*args, **kwargs)`
  - get_file(self) -> Gio.File

- **get_info**`(*args, **kwargs)`
  - get_info(self) -> Gimp.ModuleInfo

- **get_last_error**`(*args, **kwargs)`
  - get_last_error(self) -> str

- **get_properties**`(bound native)`
  - documentation unavailable

- **get_property**`(bound native)`
  - documentation unavailable

- **get_qdata**`(self, *args, **kargs)`
  - documentation unavailable

- **get_state**`(*args, **kwargs)`
  - get_state(self) -> Gimp.ModuleState

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

- **is_loaded**`(*args, **kwargs)`
  - is_loaded(self) -> bool

- **is_on_disk**`(*args, **kwargs)`
  - is_on_disk(self) -> bool

- **list_properties**`(*args, **kwargs)`
  - list_properties(self) -> list

- **new**`(*args, **kwargs)`
  - new(file:Gio.File, auto_load:bool, verbose:bool) -> Gimp.Module

- **newv**`(*args, **kwargs)`
  - newv(object_type:GType, parameters:list) -> GObject.Object

- **notify**`(*args, **kwargs)`
  - notify(self, property_name:str)

- **notify_by_pspec**`(self, *args, **kargs)`
  - documentation unavailable

- **override_property**`(*args, **kwargs)`
  - override_property(self, property_id:int, name:str)

- **query**`(*args, **kwargs)`
  - query(module:GObject.TypeModule) -> Gimp.ModuleInfo

- **query_module**`(*args, **kwargs)`
  - query_module(self) -> bool

- **ref**`(self, *args, **kargs)`
  - documentation unavailable

- **ref_sink**`(self, *args, **kargs)`
  - documentation unavailable

- **register**`(*args, **kwargs)`
  - register(module:GObject.TypeModule) -> bool

- **register_enum**`(*args, **kwargs)`
  - register_enum(self, name:str, const_static_values:GObject.EnumValue) -> GType

- **register_flags**`(*args, **kwargs)`
  - register_flags(self, name:str, const_static_values:GObject.FlagsValue) -> GType

- **register_type**`(*args, **kwargs)`
  - register_type(self, parent_type:GType, type_name:str, type_info:GObject.TypeInfo, flags:GObject.TypeFlags) -> GType

- **replace_data**`(self, *args, **kargs)`
  - documentation unavailable

- **replace_qdata**`(self, *args, **kargs)`
  - documentation unavailable

- **run_dispose**`(*args, **kwargs)`
  - run_dispose(self)

- **set_auto_load**`(*args, **kwargs)`
  - set_auto_load(self, auto_load:bool)

- **set_data**`(self, *args, **kargs)`
  - documentation unavailable

- **set_name**`(*args, **kwargs)`
  - set_name(self, name:str)

- **set_properties**`(bound native)`
  - documentation unavailable

- **set_property**`(bound native)`
  - documentation unavailable

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

- **unref**`(self, *args, **kargs)`
  - documentation unavailable

- **unuse**`(*args, **kwargs)`
  - unuse(self)

- **use**`(*args, **kwargs)`
  - use(self) -> bool

- **watch_closure**`(self, *args, **kargs)`
  - documentation unavailable

- **weak_ref**`(bound native)`
  - documentation unavailable


