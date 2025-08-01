---
layout: default
title: Gimp.objects
---
# Gimp.objects

## Metadata
- :Constructors:<br /><br />::<br /><br />    Metadata(**properties)<br />    new() -> Gimp.Metadata

### Runtime attributes

- **g_type_instance**
- **props**
- **qdata**
- **ref_count**

### Runtime functions
- **add_xmp_history**`(*args, **kwargs)`
  - add_xmp_history(self, state_status:str)

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

- **deserialize**`(*args, **kwargs)`
  - deserialize(metadata_xml:str) -> Gimp.Metadata

- **disconnect**`(*args, **kwargs)`
  - signal_handler_disconnect(instance:GObject.Object, handler_id:int)

- **disconnect_by_func**`(bound native)`
  - documentation unavailable

- **duplicate**`(*args, **kwargs)`
  - duplicate(self) -> Gimp.Metadata

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

- **get_colorspace**`(*args, **kwargs)`
  - get_colorspace(self) -> Gimp.MetadataColorspace

- **get_data**`(self, *args, **kargs)`
  - documentation unavailable

- **get_guid**`(*args, **kwargs)`
  - get_guid() -> str

- **get_properties**`(bound native)`
  - documentation unavailable

- **get_property**`(bound native)`
  - documentation unavailable

- **get_qdata**`(self, *args, **kargs)`
  - documentation unavailable

- **get_resolution**`(*args, **kwargs)`
  - get_resolution(self) -> bool, xres:float, yres:float, unit:Gimp.Unit

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

- **is_tag_supported**`(*args, **kwargs)`
  - is_tag_supported(tag:str, mime_type:str) -> bool

- **list_properties**`(*args, **kwargs)`
  - list_properties(self) -> list

- **load_from_file**`(*args, **kwargs)`
  - load_from_file(file:Gio.File) -> Gimp.Metadata

- **new**`(*args, **kwargs)`
  - new() -> Gimp.Metadata

- **newv**`(*args, **kwargs)`
  - newv(object_type:GType, parameters:list) -> GObject.Object

- **notify**`(*args, **kwargs)`
  - notify(self, property_name:str)

- **notify_by_pspec**`(self, *args, **kargs)`
  - documentation unavailable

- **override_property**`(*args, **kwargs)`
  - override_property(self, property_id:int, name:str)

- **ref**`(self, *args, **kargs)`
  - documentation unavailable

- **ref_sink**`(self, *args, **kargs)`
  - documentation unavailable

- **replace_data**`(self, *args, **kargs)`
  - documentation unavailable

- **replace_qdata**`(self, *args, **kargs)`
  - documentation unavailable

- **run_dispose**`(*args, **kwargs)`
  - run_dispose(self)

- **save_to_file**`(*args, **kwargs)`
  - save_to_file(self, file:Gio.File) -> bool

- **serialize**`(*args, **kwargs)`
  - serialize(self) -> str

- **set_bits_per_sample**`(*args, **kwargs)`
  - set_bits_per_sample(self, bits_per_sample:int)

- **set_colorspace**`(*args, **kwargs)`
  - set_colorspace(self, colorspace:Gimp.MetadataColorspace)

- **set_creation_date**`(*args, **kwargs)`
  - set_creation_date(self, datetime:GLib.DateTime)

- **set_data**`(self, *args, **kargs)`
  - documentation unavailable

- **set_from_exif**`(*args, **kwargs)`
  - set_from_exif(self, exif_data:list) -> bool

- **set_from_iptc**`(*args, **kwargs)`
  - set_from_iptc(self, iptc_data:list) -> bool

- **set_from_xmp**`(*args, **kwargs)`
  - set_from_xmp(self, xmp_data:list) -> bool

- **set_pixel_size**`(*args, **kwargs)`
  - set_pixel_size(self, width:int, height:int)

- **set_properties**`(bound native)`
  - documentation unavailable

- **set_property**`(bound native)`
  - documentation unavailable

- **set_resolution**`(*args, **kwargs)`
  - set_resolution(self, xres:float, yres:float, unit:Gimp.Unit)

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

- **watch_closure**`(self, *args, **kargs)`
  - documentation unavailable

- **weak_ref**`(bound native)`
  - documentation unavailable


