---
layout: default
title: Gimp.objects
---
# Gimp.objects

## Gradient
- :Constructors:<br /><br />::<br /><br />    Gradient(**properties)<br />    new(name:str) -> Gimp.Gradient

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

- **delete**`(*args, **kwargs)`
  - delete(self) -> bool

- **deserialize_return**`(*args, **kwargs)`
  - deserialize_return(scanner:GLib.Scanner, expected_token:GLib.TokenType, nest_level:int) -> bool

- **diff**`(*args, **kwargs)`
  - diff(a:GObject.Object, b:GObject.Object, flags:GObject.ParamFlags) -> list

- **disconnect**`(*args, **kwargs)`
  - signal_handler_disconnect(instance:GObject.Object, handler_id:int)

- **disconnect_by_func**`(bound native)`
  - documentation unavailable

- **duplicate**`(*args, **kwargs)`
  - duplicate(self) -> Gimp.Resource

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

- **get_by_id**`(*args, **kwargs)`
  - get_by_id(resource_id:int) -> Gimp.Resource or None

- **get_by_name**`(*args, **kwargs)`
  - get_by_name(name:str) -> Gimp.Gradient or None

- **get_custom_samples**`(*args, **kwargs)`
  - get_custom_samples(self, positions:list, reverse:bool) -> list

- **get_data**`(self, *args, **kargs)`
  - documentation unavailable

- **get_id**`(*args, **kwargs)`
  - get_id(self) -> int

- **get_name**`(*args, **kwargs)`
  - get_name(self) -> str

- **get_number_of_segments**`(*args, **kwargs)`
  - get_number_of_segments(self) -> int

- **get_properties**`(bound native)`
  - documentation unavailable

- **get_property**`(bound native)`
  - documentation unavailable

- **get_qdata**`(self, *args, **kargs)`
  - documentation unavailable

- **get_uniform_samples**`(*args, **kwargs)`
  - get_uniform_samples(self, num_samples:int, reverse:bool) -> list

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

- **id_is_brush**`(*args, **kwargs)`
  - id_is_brush(resource_id:int) -> bool

- **id_is_font**`(*args, **kwargs)`
  - id_is_font(resource_id:int) -> bool

- **id_is_gradient**`(*args, **kwargs)`
  - id_is_gradient(resource_id:int) -> bool

- **id_is_palette**`(*args, **kwargs)`
  - id_is_palette(resource_id:int) -> bool

- **id_is_pattern**`(*args, **kwargs)`
  - id_is_pattern(resource_id:int) -> bool

- **id_is_valid**`(*args, **kwargs)`
  - id_is_valid(resource_id:int) -> bool

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

- **is_brush**`(*args, **kwargs)`
  - is_brush(self) -> bool

- **is_editable**`(*args, **kwargs)`
  - is_editable(self) -> bool

- **is_floating**`(*args, **kwargs)`
  - is_floating(self) -> bool

- **is_font**`(*args, **kwargs)`
  - is_font(self) -> bool

- **is_gradient**`(*args, **kwargs)`
  - is_gradient(self) -> bool

- **is_palette**`(*args, **kwargs)`
  - is_palette(self) -> bool

- **is_pattern**`(*args, **kwargs)`
  - is_pattern(self) -> bool

- **is_valid**`(*args, **kwargs)`
  - is_valid(self) -> bool

- **list_properties**`(*args, **kwargs)`
  - list_properties(self) -> list

- **new**`(*args, **kwargs)`
  - new(name:str) -> Gimp.Gradient

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

- **rename**`(*args, **kwargs)`
  - rename(self, new_name:str) -> bool

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

- **segment_get_blending_function**`(*args, **kwargs)`
  - segment_get_blending_function(self, segment:int) -> bool, blend_func:Gimp.GradientSegmentType

- **segment_get_coloring_type**`(*args, **kwargs)`
  - segment_get_coloring_type(self, segment:int) -> bool, coloring_type:Gimp.GradientSegmentColor

- **segment_get_left_color**`(*args, **kwargs)`
  - segment_get_left_color(self, segment:int) -> Gegl.Color

- **segment_get_left_pos**`(*args, **kwargs)`
  - segment_get_left_pos(self, segment:int) -> bool, pos:float

- **segment_get_middle_pos**`(*args, **kwargs)`
  - segment_get_middle_pos(self, segment:int) -> bool, pos:float

- **segment_get_right_color**`(*args, **kwargs)`
  - segment_get_right_color(self, segment:int) -> Gegl.Color

- **segment_get_right_pos**`(*args, **kwargs)`
  - segment_get_right_pos(self, segment:int) -> bool, pos:float

- **segment_range_blend_colors**`(*args, **kwargs)`
  - segment_range_blend_colors(self, start_segment:int, end_segment:int) -> bool

- **segment_range_blend_opacity**`(*args, **kwargs)`
  - segment_range_blend_opacity(self, start_segment:int, end_segment:int) -> bool

- **segment_range_delete**`(*args, **kwargs)`
  - segment_range_delete(self, start_segment:int, end_segment:int) -> bool

- **segment_range_flip**`(*args, **kwargs)`
  - segment_range_flip(self, start_segment:int, end_segment:int) -> bool

- **segment_range_move**`(*args, **kwargs)`
  - segment_range_move(self, start_segment:int, end_segment:int, delta:float, control_compress:bool) -> float

- **segment_range_redistribute_handles**`(*args, **kwargs)`
  - segment_range_redistribute_handles(self, start_segment:int, end_segment:int) -> bool

- **segment_range_replicate**`(*args, **kwargs)`
  - segment_range_replicate(self, start_segment:int, end_segment:int, replicate_times:int) -> bool

- **segment_range_set_blending_function**`(*args, **kwargs)`
  - segment_range_set_blending_function(self, start_segment:int, end_segment:int, blending_function:Gimp.GradientSegmentType) -> bool

- **segment_range_set_coloring_type**`(*args, **kwargs)`
  - segment_range_set_coloring_type(self, start_segment:int, end_segment:int, coloring_type:Gimp.GradientSegmentColor) -> bool

- **segment_range_split_midpoint**`(*args, **kwargs)`
  - segment_range_split_midpoint(self, start_segment:int, end_segment:int) -> bool

- **segment_range_split_uniform**`(*args, **kwargs)`
  - segment_range_split_uniform(self, start_segment:int, end_segment:int, split_parts:int) -> bool

- **segment_set_left_color**`(*args, **kwargs)`
  - segment_set_left_color(self, segment:int, color:Gegl.Color) -> bool

- **segment_set_left_pos**`(*args, **kwargs)`
  - segment_set_left_pos(self, segment:int, pos:float) -> bool, final_pos:float

- **segment_set_middle_pos**`(*args, **kwargs)`
  - segment_set_middle_pos(self, segment:int, pos:float) -> bool, final_pos:float

- **segment_set_right_color**`(*args, **kwargs)`
  - segment_set_right_color(self, segment:int, color:Gegl.Color) -> bool

- **segment_set_right_pos**`(*args, **kwargs)`
  - segment_set_right_pos(self, segment:int, pos:float) -> bool, final_pos:float

- **serialize_value**`(*args, **kwargs)`
  - serialize_value(value:GObject.Value, str:GLib.String, escaped:bool) -> bool

- **set_data**`(self, *args, **kargs)`
  - documentation unavailable

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


