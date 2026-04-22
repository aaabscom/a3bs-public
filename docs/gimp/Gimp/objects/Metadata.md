---
layout: default
title: Gimp.objects
---
# Gimp.objects

## Metadata
- :Constructors:<br /><br />::<br /><br />    Metadata(**properties)<br />    new() -> Gimp.Metadata

### Runtime attributes

- **g_type_instance**
- **parent_instance**
- **priv**
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

- **clear**`(*args, **kwargs)`
  - clear(self)

- **clear_comment**`(*args, **kwargs)`
  - clear_comment(self)

- **clear_exif**`(*args, **kwargs)`
  - clear_exif(self)

- **clear_iptc**`(*args, **kwargs)`
  - clear_iptc(self)

- **clear_tag**`(*args, **kwargs)`
  - clear_tag(self, tag:str) -> bool

- **clear_xmp**`(*args, **kwargs)`
  - clear_xmp(self)

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

- **delete_gps_info**`(*args, **kwargs)`
  - delete_gps_info(self)

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

- **erase_exif_thumbnail**`(*args, **kwargs)`
  - erase_exif_thumbnail(self)

- **find_property**`(*args, **kwargs)`
  - find_property(self, property_name:str) -> GObject.ParamSpec

- **force_floating**`(self, *args, **kargs)`
  - documentation unavailable

- **free**`(*args, **kwargs)`
  - free(self)

- **freeze_notify**`(self)`
  - Freezes the object's property-changed notification queue.<br /><br />:returns:<br />    A context manager which optionally can be used to<br />    automatically thaw notifications.<br /><br />This will freeze the object so that "notify" signals are blocked until<br />the thaw_notify() method is called.<br /><br />.. code-block:: python<br /><br />    with obj.freeze_notify():<br />        pass

- **from_app1_segment**`(*args, **kwargs)`
  - from_app1_segment(self, data:list) -> bool

- **from_stream**`(*args, **kwargs)`
  - from_stream(self, stream:Gio.InputStream) -> bool

- **generate_xmp_packet**`(*args, **kwargs)`
  - generate_xmp_packet(self, xmp_format_flags:GExiv2.XmpFormatFlags, padding:int) -> str or None

- **get**`(self, key, default=None)`
  - documentation unavailable

- **get_colorspace**`(*args, **kwargs)`
  - get_colorspace(self) -> Gimp.MetadataColorspace

- **get_comment**`(*args, **kwargs)`
  - get_comment(self) -> str or None

- **get_data**`(self, *args, **kargs)`
  - documentation unavailable

- **get_date_time**`(self)`
  - documentation unavailable

- **get_exif_data**`(*args, **kwargs)`
  - get_exif_data(self, byte_order:GExiv2.ByteOrder) -> GLib.Bytes or None

- **get_exif_tag_rational**`(self, key)`
  - get_exif_tag_rational(self, tag:str) -> nom:int, den:int

- **get_exif_tags**`(*args, **kwargs)`
  - get_exif_tags(self) -> list

- **get_exif_thumbnail**`(*args, **kwargs)`
  - get_exif_thumbnail(self) -> buffer:list

- **get_exposure_time**`(self)`
  - get_exposure_time(self) -> nom:int, den:int

- **get_fnumber**`(*args, **kwargs)`
  - get_fnumber(self) -> float

- **get_focal_length**`(*args, **kwargs)`
  - get_focal_length(self) -> float

- **get_gps_altitude**`(*args, **kwargs)`
  - get_gps_altitude(self) -> altitude:float

- **get_gps_info**`(*args, **kwargs)`
  - get_gps_info(self) -> longitude:float, latitude:float, altitude:float

- **get_gps_latitude**`(*args, **kwargs)`
  - get_gps_latitude(self) -> latitude:float

- **get_gps_longitude**`(*args, **kwargs)`
  - get_gps_longitude(self) -> longitude:float

- **get_guid**`(*args, **kwargs)`
  - get_guid() -> str

- **get_iptc_tags**`(*args, **kwargs)`
  - get_iptc_tags(self) -> list

- **get_iso_speed**`(*args, **kwargs)`
  - get_iso_speed(self) -> int

- **get_metadata_pixel_height**`(*args, **kwargs)`
  - get_metadata_pixel_height(self) -> int

- **get_metadata_pixel_width**`(*args, **kwargs)`
  - get_metadata_pixel_width(self) -> int

- **get_mime_type**`(*args, **kwargs)`
  - get_mime_type(self) -> str

- **get_orientation**`(*args, **kwargs)`
  - get_orientation(self) -> GExiv2.Orientation

- **get_pixel_height**`(*args, **kwargs)`
  - get_pixel_height(self) -> int

- **get_pixel_width**`(*args, **kwargs)`
  - get_pixel_width(self) -> int

- **get_preview_image**`(*args, **kwargs)`
  - get_preview_image(self, props:GExiv2.PreviewProperties) -> GExiv2.PreviewImage

- **get_preview_properties**`(*args, **kwargs)`
  - get_preview_properties(self) -> list or None

- **get_properties**`(bound native)`
  - documentation unavailable

- **get_property**`(bound native)`
  - documentation unavailable

- **get_qdata**`(self, *args, **kargs)`
  - documentation unavailable

- **get_raw**`(self, key)`
  - documentation unavailable

- **get_resolution**`(*args, **kwargs)`
  - get_resolution(self) -> bool, xres:float, yres:float, unit:Gimp.Unit

- **get_supports_exif**`(*args, **kwargs)`
  - get_supports_exif(self) -> bool

- **get_supports_iptc**`(*args, **kwargs)`
  - get_supports_iptc(self) -> bool

- **get_supports_xmp**`(*args, **kwargs)`
  - get_supports_xmp(self) -> bool

- **get_tag_description**`(*args, **kwargs)`
  - get_tag_description(tag:str) -> str or None

- **get_tag_interpreted_string**`(*args, **kwargs)`
  - get_tag_interpreted_string(self, tag:str) -> str or None

- **get_tag_label**`(*args, **kwargs)`
  - get_tag_label(tag:str) -> str or None

- **get_tag_long**`(*args, **kwargs)`
  - get_tag_long(self, tag:str) -> int

- **get_tag_multiple**`(*args, **kwargs)`
  - get_tag_multiple(self, tag:str) -> list or None

- **get_tag_raw**`(*args, **kwargs)`
  - get_tag_raw(self, tag:str) -> GLib.Bytes or None

- **get_tag_string**`(*args, **kwargs)`
  - get_tag_string(self, tag:str) -> str or None

- **get_tag_type**`(*args, **kwargs)`
  - get_tag_type(tag:str) -> str or None

- **get_tags**`(self)`
  - documentation unavailable

- **get_xmp_namespace_for_tag**`(*args, **kwargs)`
  - get_xmp_namespace_for_tag(tag:str) -> str

- **get_xmp_packet**`(*args, **kwargs)`
  - get_xmp_packet(self) -> str or None

- **get_xmp_tags**`(*args, **kwargs)`
  - get_xmp_tags(self) -> list

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

- **has_exif**`(*args, **kwargs)`
  - has_exif(self) -> bool

- **has_iptc**`(*args, **kwargs)`
  - has_iptc(self) -> bool

- **has_tag**`(*args, **kwargs)`
  - has_tag(self, tag:str) -> bool

- **has_xmp**`(*args, **kwargs)`
  - has_xmp(self) -> bool

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

- **is_exif_tag**`(*args, **kwargs)`
  - is_exif_tag(tag:str) -> bool

- **is_floating**`(*args, **kwargs)`
  - is_floating(self) -> bool

- **is_iptc_tag**`(*args, **kwargs)`
  - is_iptc_tag(tag:str) -> bool

- **is_tag_supported**`(*args, **kwargs)`
  - is_tag_supported(tag:str, mime_type:str) -> bool

- **is_xmp_tag**`(*args, **kwargs)`
  - is_xmp_tag(tag:str) -> bool

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

- **open_buf**`(*args, **kwargs)`
  - open_buf(self, data:list) -> bool

- **open_path**`(self, path)`
  - open_path(self, path:str) -> bool

- **override_property**`(*args, **kwargs)`
  - override_property(self, property_id:int, name:str)

- **ref**`(self, *args, **kargs)`
  - documentation unavailable

- **ref_sink**`(self, *args, **kargs)`
  - documentation unavailable

- **register_xmp_namespace**`(*args, **kwargs)`
  - register_xmp_namespace(name:str, prefix:str)

- **replace_data**`(self, *args, **kargs)`
  - documentation unavailable

- **replace_qdata**`(self, *args, **kargs)`
  - documentation unavailable

- **run_dispose**`(*args, **kwargs)`
  - run_dispose(self)

- **save_external**`(*args, **kwargs)`
  - save_external(self, path:str) -> bool

- **save_file**`(self, path=None)`
  - save_file(self, path:str) -> bool

- **save_to_file**`(*args, **kwargs)`
  - save_to_file(self, file:Gio.File) -> bool

- **serialize**`(*args, **kwargs)`
  - serialize(self) -> str

- **set_bits_per_sample**`(*args, **kwargs)`
  - set_bits_per_sample(self, bits_per_sample:int)

- **set_colorspace**`(*args, **kwargs)`
  - set_colorspace(self, colorspace:Gimp.MetadataColorspace)

- **set_comment**`(*args, **kwargs)`
  - set_comment(self, comment:str)

- **set_creation_date**`(*args, **kwargs)`
  - set_creation_date(self, datetime:GLib.DateTime)

- **set_data**`(self, *args, **kargs)`
  - documentation unavailable

- **set_date_time**`(self, value)`
  - documentation unavailable

- **set_exif_tag_rational**`(self, key, fraction)`
  - set_exif_tag_rational(self, tag:str, nom:int, den:int)

- **set_exif_thumbnail_from_buffer**`(*args, **kwargs)`
  - set_exif_thumbnail_from_buffer(self, buffer:list)

- **set_exif_thumbnail_from_file**`(*args, **kwargs)`
  - set_exif_thumbnail_from_file(self, path:str) -> bool

- **set_from_exif**`(*args, **kwargs)`
  - set_from_exif(self, exif_data:list) -> bool

- **set_from_iptc**`(*args, **kwargs)`
  - set_from_iptc(self, iptc_data:list) -> bool

- **set_from_xmp**`(*args, **kwargs)`
  - set_from_xmp(self, xmp_data:list) -> bool

- **set_gps_info**`(*args, **kwargs)`
  - set_gps_info(self, longitude:float, latitude:float, altitude:float)

- **set_metadata_pixel_height**`(*args, **kwargs)`
  - set_metadata_pixel_height(self, height:int)

- **set_metadata_pixel_width**`(*args, **kwargs)`
  - set_metadata_pixel_width(self, width:int)

- **set_orientation**`(*args, **kwargs)`
  - set_orientation(self, orientation:GExiv2.Orientation)

- **set_pixel_size**`(*args, **kwargs)`
  - set_pixel_size(self, width:int, height:int)

- **set_properties**`(bound native)`
  - documentation unavailable

- **set_property**`(bound native)`
  - documentation unavailable

- **set_resolution**`(*args, **kwargs)`
  - set_resolution(self, xres:float, yres:float, unit:Gimp.Unit)

- **set_tag_long**`(*args, **kwargs)`
  - set_tag_long(self, tag:str, value:int) -> bool

- **set_tag_multiple**`(*args, **kwargs)`
  - set_tag_multiple(self, tag:str, values:list) -> bool

- **set_tag_string**`(*args, **kwargs)`
  - set_tag_string(self, tag:str, value:str) -> bool

- **set_xmp_tag_struct**`(*args, **kwargs)`
  - set_xmp_tag_struct(self, tag:str, type:GExiv2.StructureType) -> bool

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

- **try_clear_tag**`(*args, **kwargs)`
  - try_clear_tag(self, tag:str) -> bool

- **try_delete_gps_info**`(*args, **kwargs)`
  - try_delete_gps_info(self)

- **try_erase_exif_thumbnail**`(*args, **kwargs)`
  - try_erase_exif_thumbnail(self)

- **try_generate_xmp_packet**`(*args, **kwargs)`
  - try_generate_xmp_packet(self, xmp_format_flags:GExiv2.XmpFormatFlags, padding:int) -> str or None

- **try_get_comment**`(*args, **kwargs)`
  - try_get_comment(self) -> str or None

- **try_get_exif_tag_rational**`(*args, **kwargs)`
  - try_get_exif_tag_rational(self, tag:str) -> nom:int, den:int

- **try_get_exposure_time**`(*args, **kwargs)`
  - try_get_exposure_time(self) -> nom:int, den:int

- **try_get_fnumber**`(*args, **kwargs)`
  - try_get_fnumber(self) -> float

- **try_get_focal_length**`(*args, **kwargs)`
  - try_get_focal_length(self) -> float

- **try_get_gps_altitude**`(*args, **kwargs)`
  - try_get_gps_altitude(self) -> altitude:float

- **try_get_gps_info**`(*args, **kwargs)`
  - try_get_gps_info(self) -> longitude:float, latitude:float, altitude:float

- **try_get_gps_latitude**`(*args, **kwargs)`
  - try_get_gps_latitude(self) -> latitude:float

- **try_get_gps_longitude**`(*args, **kwargs)`
  - try_get_gps_longitude(self) -> longitude:float

- **try_get_iso_speed**`(*args, **kwargs)`
  - try_get_iso_speed(self) -> int

- **try_get_metadata_pixel_height**`(*args, **kwargs)`
  - try_get_metadata_pixel_height(self) -> int

- **try_get_metadata_pixel_width**`(*args, **kwargs)`
  - try_get_metadata_pixel_width(self) -> int

- **try_get_orientation**`(*args, **kwargs)`
  - try_get_orientation(self) -> GExiv2.Orientation

- **try_get_preview_image**`(*args, **kwargs)`
  - try_get_preview_image(self, props:GExiv2.PreviewProperties) -> GExiv2.PreviewImage

- **try_get_tag_description**`(*args, **kwargs)`
  - try_get_tag_description(tag:str) -> str or None

- **try_get_tag_interpreted_string**`(*args, **kwargs)`
  - try_get_tag_interpreted_string(self, tag:str) -> str or None

- **try_get_tag_label**`(*args, **kwargs)`
  - try_get_tag_label(tag:str) -> str or None

- **try_get_tag_long**`(*args, **kwargs)`
  - try_get_tag_long(self, tag:str) -> int

- **try_get_tag_multiple**`(*args, **kwargs)`
  - try_get_tag_multiple(self, tag:str) -> list or None

- **try_get_tag_raw**`(*args, **kwargs)`
  - try_get_tag_raw(self, tag:str) -> GLib.Bytes or None

- **try_get_tag_string**`(*args, **kwargs)`
  - try_get_tag_string(self, tag:str) -> str or None

- **try_get_tag_type**`(*args, **kwargs)`
  - try_get_tag_type(tag:str) -> str or None

- **try_get_xmp_namespace_for_tag**`(*args, **kwargs)`
  - try_get_xmp_namespace_for_tag(tag:str) -> str

- **try_get_xmp_packet**`(*args, **kwargs)`
  - try_get_xmp_packet(self) -> str or None

- **try_has_tag**`(*args, **kwargs)`
  - try_has_tag(self, tag:str) -> bool

- **try_register_xmp_namespace**`(*args, **kwargs)`
  - try_register_xmp_namespace(name:str, prefix:str)

- **try_set_comment**`(*args, **kwargs)`
  - try_set_comment(self, comment:str)

- **try_set_exif_tag_rational**`(*args, **kwargs)`
  - try_set_exif_tag_rational(self, tag:str, nom:int, den:int)

- **try_set_exif_thumbnail_from_buffer**`(*args, **kwargs)`
  - try_set_exif_thumbnail_from_buffer(self, buffer:list)

- **try_set_gps_info**`(*args, **kwargs)`
  - try_set_gps_info(self, longitude:float, latitude:float, altitude:float)

- **try_set_metadata_pixel_height**`(*args, **kwargs)`
  - try_set_metadata_pixel_height(self, height:int)

- **try_set_metadata_pixel_width**`(*args, **kwargs)`
  - try_set_metadata_pixel_width(self, width:int)

- **try_set_orientation**`(*args, **kwargs)`
  - try_set_orientation(self, orientation:GExiv2.Orientation)

- **try_set_tag_long**`(*args, **kwargs)`
  - try_set_tag_long(self, tag:str, value:int) -> bool

- **try_set_tag_multiple**`(*args, **kwargs)`
  - try_set_tag_multiple(self, tag:str, values:list) -> bool

- **try_set_tag_string**`(*args, **kwargs)`
  - try_set_tag_string(self, tag:str, value:str) -> bool

- **try_set_xmp_tag_struct**`(*args, **kwargs)`
  - try_set_xmp_tag_struct(self, tag:str, type:GExiv2.StructureType) -> bool

- **try_tag_supports_multiple_values**`(*args, **kwargs)`
  - try_tag_supports_multiple_values(self, tag:str) -> bool

- **try_unregister_all_xmp_namespaces**`(*args, **kwargs)`
  - try_unregister_all_xmp_namespaces()

- **try_unregister_xmp_namespace**`(*args, **kwargs)`
  - try_unregister_xmp_namespace(name:str)

- **try_update_gps_info**`(*args, **kwargs)`
  - try_update_gps_info(self, longitude:float, latitude:float, altitude:float)

- **unref**`(self, *args, **kargs)`
  - documentation unavailable

- **unregister_all_xmp_namespaces**`(*args, **kwargs)`
  - unregister_all_xmp_namespaces()

- **unregister_xmp_namespace**`(*args, **kwargs)`
  - unregister_xmp_namespace(name:str)

- **update_gps_info**`(*args, **kwargs)`
  - update_gps_info(self, longitude:float, latitude:float, altitude:float)

- **watch_closure**`(self, *args, **kargs)`
  - documentation unavailable

- **weak_ref**`(bound native)`
  - documentation unavailable


