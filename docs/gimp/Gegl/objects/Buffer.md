---
layout: default
title: Gegl.objects
---
# Gegl.objects

## Buffer
- :Constructors:<br /><br />::<br /><br />    Buffer(**properties)<br />    new(format_name:str, x:int, y:int, width:int, height:int) -> Gegl.Buffer<br />    new_for_backend(extent:Gegl.Rectangle, backend:Gegl.TileBackend) -> Gegl.Buffer

### Runtime attributes

- **command**
- **g_type_instance**
- **padding**
- **parent_instance**
- **priv**
- **props**
- **qdata**
- **ref_count**
- **source**

### Runtime functions
- **add_handler**`(*args, **kwargs)`
  - add_handler(self, handler=None)

- **bind_property**`(bound native)`
  - documentation unavailable

- **bind_property_full**`(self, *args, **kargs)`
  - documentation unavailable

- **chain**`(bound native)`
  - documentation unavailable

- **clear**`(*args, **kwargs)`
  - clear(self, roi:Gegl.Rectangle)

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

- **copy**`(*args, **kwargs)`
  - copy(self, src_rect:Gegl.Rectangle, repeat_mode:Gegl.AbyssPolicy, dst:Gegl.Buffer, dst_rect:Gegl.Rectangle)

- **create_sub_buffer**`(*args, **kwargs)`
  - create_sub_buffer(self, extent:Gegl.Rectangle) -> Gegl.Buffer

- **damage_rect**`(*args, **kwargs)`
  - damage_rect(self, rect:Gegl.Rectangle)

- **damage_tile**`(*args, **kwargs)`
  - damage_tile(self, x:int, y:int, z:int, damage:int)

- **disconnect**`(*args, **kwargs)`
  - signal_handler_disconnect(instance:GObject.Object, handler_id:int)

- **disconnect_by_func**`(bound native)`
  - documentation unavailable

- **dup**`(*args, **kwargs)`
  - dup(self) -> Gegl.Buffer

- **emit**`(bound native)`
  - documentation unavailable

- **emit_stop_by_name**`(self, detailed_signal)`
  - Deprecated, please use stop_emission_by_name.

- **find_property**`(*args, **kwargs)`
  - find_property(self, property_name:str) -> GObject.ParamSpec

- **flush**`(*args, **kwargs)`
  - flush(self)

- **flush_ext**`(*args, **kwargs)`
  - flush_ext(self, rect:Gegl.Rectangle)

- **force_floating**`(self, *args, **kargs)`
  - documentation unavailable

- **freeze_changed**`(*args, **kwargs)`
  - freeze_changed(self)

- **freeze_notify**`(self)`
  - Freezes the object's property-changed notification queue.<br /><br />:returns:<br />    A context manager which optionally can be used to<br />    automatically thaw notifications.<br /><br />This will freeze the object so that "notify" signals are blocked until<br />the thaw_notify() method is called.<br /><br />.. code-block:: python<br /><br />    with obj.freeze_notify():<br />        pass

- **get**`(*args, **kwargs)`
  - get(self, rect:Gegl.Rectangle, scale:float, format_name:str=None, repeat_mode:Gegl.AbyssPolicy) -> list

- **get_abyss**`(*args, **kwargs)`
  - get_abyss(self) -> Gegl.Rectangle

- **get_data**`(self, *args, **kargs)`
  - documentation unavailable

- **get_extent**`(*args, **kwargs)`
  - get_extent(self) -> Gegl.Rectangle

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

- **linear_close**`(*args, **kwargs)`
  - linear_close(self, linear=None)

- **list_properties**`(*args, **kwargs)`
  - list_properties(self) -> list

- **load**`(*args, **kwargs)`
  - load(path:str) -> Gegl.Buffer

- **lock**`(*args, **kwargs)`
  - lock(self)

- **new**`(*args, **kwargs)`
  - new(format_name:str, x:int, y:int, width:int, height:int) -> Gegl.Buffer

- **new_for_backend**`(*args, **kwargs)`
  - new_for_backend(extent:Gegl.Rectangle, backend:Gegl.TileBackend) -> Gegl.Buffer

- **newv**`(*args, **kwargs)`
  - newv(object_type:GType, parameters:list) -> GObject.Object

- **notify**`(*args, **kwargs)`
  - notify(self, property_name:str)

- **notify_by_pspec**`(self, *args, **kargs)`
  - documentation unavailable

- **open**`(*args, **kwargs)`
  - open(path:str) -> Gegl.Buffer

- **override_property**`(*args, **kwargs)`
  - override_property(self, property_id:int, name:str)

- **ref**`(self, *args, **kargs)`
  - documentation unavailable

- **ref_sink**`(self, *args, **kargs)`
  - documentation unavailable

- **remove_handler**`(*args, **kwargs)`
  - remove_handler(self, handler=None)

- **replace_data**`(self, *args, **kargs)`
  - documentation unavailable

- **replace_qdata**`(self, *args, **kargs)`
  - documentation unavailable

- **run_dispose**`(*args, **kwargs)`
  - run_dispose(self)

- **sample_cleanup**`(*args, **kwargs)`
  - sample_cleanup(self)

- **save**`(*args, **kwargs)`
  - save(self, path:str, roi:Gegl.Rectangle)

- **set**`(*args, **kwargs)`
  - set(self, rect:Gegl.Rectangle, format_name:str, src:list)

- **set_abyss**`(*args, **kwargs)`
  - set_abyss(self, abyss:Gegl.Rectangle) -> bool

- **set_color**`(*args, **kwargs)`
  - set_color(self, rect:Gegl.Rectangle, color:Gegl.Color)

- **set_color_from_pixel**`(*args, **kwargs)`
  - set_color_from_pixel(self, rect:Gegl.Rectangle, pixel=None, pixel_format:Babl.Object)

- **set_data**`(self, *args, **kargs)`
  - documentation unavailable

- **set_extent**`(*args, **kwargs)`
  - set_extent(self, extent:Gegl.Rectangle) -> bool

- **set_pattern**`(*args, **kwargs)`
  - set_pattern(self, rect:Gegl.Rectangle, pattern:Gegl.Buffer, x_offset:int, y_offset:int)

- **set_properties**`(bound native)`
  - documentation unavailable

- **set_property**`(bound native)`
  - documentation unavailable

- **set_source**`(*args, **kwargs)`
  - set_source(self, source:Gegl.TileSource)

- **share_storage**`(*args, **kwargs)`
  - share_storage(self, buffer2:Gegl.Buffer) -> bool

- **signal_connect**`(*args, **kwargs)`
  - signal_connect(self, detailed_signal:str, c_handler:GObject.Callback, data=None) -> int

- **steal_data**`(self, *args, **kargs)`
  - documentation unavailable

- **steal_qdata**`(self, *args, **kargs)`
  - documentation unavailable

- **stop_emission**`(self, detailed_signal)`
  - Deprecated, please use stop_emission_by_name.

- **stop_emission_by_name**`(*args, **kwargs)`
  - signal_stop_emission_by_name(instance:GObject.Object, detailed_signal:str)

- **swap_create_file**`(*args, **kwargs)`
  - swap_create_file(suffix:str=None) -> str or None

- **swap_has_file**`(*args, **kwargs)`
  - swap_has_file(path:str) -> bool

- **swap_remove_file**`(*args, **kwargs)`
  - swap_remove_file(path:str)

- **thaw_changed**`(*args, **kwargs)`
  - thaw_changed(self)

- **thaw_notify**`(*args, **kwargs)`
  - thaw_notify(self)

- **unlock**`(*args, **kwargs)`
  - unlock(self)

- **unref**`(self, *args, **kargs)`
  - documentation unavailable

- **watch_closure**`(self, *args, **kargs)`
  - documentation unavailable

- **weak_ref**`(bound native)`
  - documentation unavailable


