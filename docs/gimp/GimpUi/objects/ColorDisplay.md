---
layout: default
title: GimpUi.objects
---
# GimpUi.objects

## ColorDisplay
- :Constructors:<br /><br />::<br /><br />    ColorDisplay(**properties)

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

- **build_data_path**`(*args, **kwargs)`
  - build_data_path(name:str) -> str

- **build_plug_in_path**`(*args, **kwargs)`
  - build_plug_in_path(name:str) -> str

- **build_system_path**`(*args, **kwargs)`
  - build_system_path(name:str) -> str

- **build_writable_path**`(*args, **kwargs)`
  - build_writable_path(name:str) -> str

- **chain**`(bound native)`
  - documentation unavailable

- **changed**`(*args, **kwargs)`
  - changed(self)

- **clone**`(*args, **kwargs)`
  - clone(self) -> GimpUi.ColorDisplay

- **compat_control**`(self, *args, **kargs)`
  - documentation unavailable

- **configure**`(*args, **kwargs)`
  - configure(self) -> Gtk.Widget

- **configure_reset**`(*args, **kwargs)`
  - configure_reset(self)

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

- **convert_buffer**`(*args, **kwargs)`
  - convert_buffer(self, buffer:Gegl.Buffer, area:Gegl.Rectangle)

- **deserialize_return**`(*args, **kwargs)`
  - deserialize_return(scanner:GLib.Scanner, expected_token:GLib.TokenType, nest_level:int) -> bool

- **diff**`(*args, **kwargs)`
  - diff(a:GObject.Object, b:GObject.Object, flags:GObject.ParamFlags) -> list

- **disconnect**`(*args, **kwargs)`
  - signal_handler_disconnect(instance:GObject.Object, handler_id:int)

- **disconnect_by_func**`(bound native)`
  - documentation unavailable

- **do_changed**`(bound native)`
  - changed(self)

- **do_configure**`(bound native)`
  - configure(self) -> Gtk.Widget

- **do_convert_buffer**`(bound native)`
  - convert_buffer(self, buffer:Gegl.Buffer, area:Gegl.Rectangle)

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

- **get_config**`(*args, **kwargs)`
  - get_config(self) -> Gimp.ColorConfig

- **get_data**`(self, *args, **kargs)`
  - documentation unavailable

- **get_enabled**`(*args, **kwargs)`
  - get_enabled(self) -> bool

- **get_managed**`(*args, **kwargs)`
  - get_managed(self) -> Gimp.ColorManaged

- **get_properties**`(bound native)`
  - documentation unavailable

- **get_property**`(bound native)`
  - documentation unavailable

- **get_qdata**`(self, *args, **kargs)`
  - documentation unavailable

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

- **list_properties**`(*args, **kwargs)`
  - list_properties(self) -> list

- **load_state**`(*args, **kwargs)`
  - load_state(self, state:Gimp.Parasite)

- **newv**`(*args, **kwargs)`
  - newv(object_type:GType, parameters:list) -> GObject.Object

- **notify**`(*args, **kwargs)`
  - notify(self, property_name:str)

- **notify_by_pspec**`(self, *args, **kargs)`
  - documentation unavailable

- **override_property**`(*args, **kwargs)`
  - override_property(self, property_id:int, name:str)

- **param_spec_duplicate**`(*args, **kwargs)`
  - param_spec_duplicate(pspec:GObject.ParamSpec) -> GObject.ParamSpec

- **ref**`(self, *args, **kargs)`
  - documentation unavailable

- **ref_sink**`(self, *args, **kargs)`
  - documentation unavailable

- **replace_data**`(self, *args, **kargs)`
  - documentation unavailable

- **replace_qdata**`(self, *args, **kargs)`
  - documentation unavailable

- **reset_properties**`(*args, **kwargs)`
  - reset_properties(object:GObject.Object)

- **reset_property**`(*args, **kwargs)`
  - reset_property(object:GObject.Object, property_name:str)

- **run_dispose**`(*args, **kwargs)`
  - run_dispose(self)

- **save_state**`(*args, **kwargs)`
  - save_state(self) -> Gimp.Parasite

- **serialize_value**`(*args, **kwargs)`
  - serialize_value(value:GObject.Value, str:GLib.String, escaped:bool) -> bool

- **set_data**`(self, *args, **kargs)`
  - documentation unavailable

- **set_enabled**`(*args, **kwargs)`
  - set_enabled(self, enabled:bool)

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

- **string_append_escaped**`(*args, **kwargs)`
  - string_append_escaped(string:GLib.String, val:str)

- **sync**`(*args, **kwargs)`
  - sync(src:GObject.Object, dest:GObject.Object, flags:GObject.ParamFlags) -> bool

- **thaw_notify**`(*args, **kwargs)`
  - thaw_notify(self)

- **type_register**`(*args, **kwargs)`
  - type_register(parent_type:GType, type_name:str, pspecs:list) -> GType

- **unref**`(self, *args, **kargs)`
  - documentation unavailable

- **watch_closure**`(self, *args, **kargs)`
  - documentation unavailable

- **weak_ref**`(bound native)`
  - documentation unavailable


