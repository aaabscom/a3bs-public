---
layout: default
title: Gimp.objects
---
# Gimp.objects

## Image
- :Constructors:<br /><br />::<br /><br />    Image(**properties)<br />    new(width:int, height:int, type:Gimp.ImageBaseType) -> Gimp.Image<br />    new_with_precision(width:int, height:int, type:Gimp.ImageBaseType, precision:Gimp.Precision) -> Gimp.Image

### Runtime attributes

- **g_type_instance**
- **props**
- **qdata**
- **ref_count**

### Runtime functions
- **add_hguide**`(*args, **kwargs)`
  - add_hguide(self, yposition:int) -> int

- **add_sample_point**`(*args, **kwargs)`
  - add_sample_point(self, position_x:int, position_y:int) -> int

- **add_vguide**`(*args, **kwargs)`
  - add_vguide(self, xposition:int) -> int

- **attach_parasite**`(*args, **kwargs)`
  - attach_parasite(self, parasite:Gimp.Parasite) -> bool

- **autocrop**`(*args, **kwargs)`
  - autocrop(self, drawable:Gimp.Drawable=None) -> bool

- **autocrop_selected_layers**`(*args, **kwargs)`
  - autocrop_selected_layers(self, drawable:Gimp.Drawable=None) -> bool

- **bind_property**`(bound native)`
  - documentation unavailable

- **bind_property_full**`(self, *args, **kargs)`
  - documentation unavailable

- **chain**`(bound native)`
  - documentation unavailable

- **clean_all**`(*args, **kwargs)`
  - clean_all(self) -> bool

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

- **convert_color_profile**`(*args, **kwargs)`
  - convert_color_profile(self, profile:Gimp.ColorProfile, intent:Gimp.ColorRenderingIntent, bpc:bool) -> bool

- **convert_color_profile_from_file**`(*args, **kwargs)`
  - convert_color_profile_from_file(self, file:Gio.File, intent:Gimp.ColorRenderingIntent, bpc:bool) -> bool

- **convert_grayscale**`(*args, **kwargs)`
  - convert_grayscale(self) -> bool

- **convert_indexed**`(*args, **kwargs)`
  - convert_indexed(self, dither_type:Gimp.ConvertDitherType, palette_type:Gimp.ConvertPaletteType, num_cols:int, alpha_dither:bool, remove_unused:bool, palette:str) -> bool

- **convert_precision**`(*args, **kwargs)`
  - convert_precision(self, precision:Gimp.Precision) -> bool

- **convert_rgb**`(*args, **kwargs)`
  - convert_rgb(self) -> bool

- **convert_set_dither_matrix**`(*args, **kwargs)`
  - convert_set_dither_matrix(width:int, height:int, matrix:GLib.Bytes) -> bool

- **crop**`(*args, **kwargs)`
  - crop(self, new_width:int, new_height:int, offx:int, offy:int) -> bool

- **delete**`(*args, **kwargs)`
  - delete(self) -> bool

- **delete_guide**`(*args, **kwargs)`
  - delete_guide(self, guide:int) -> bool

- **delete_sample_point**`(*args, **kwargs)`
  - delete_sample_point(self, sample_point:int) -> bool

- **detach_parasite**`(*args, **kwargs)`
  - detach_parasite(self, name:str) -> bool

- **disconnect**`(*args, **kwargs)`
  - signal_handler_disconnect(instance:GObject.Object, handler_id:int)

- **disconnect_by_func**`(bound native)`
  - documentation unavailable

- **duplicate**`(*args, **kwargs)`
  - duplicate(self) -> Gimp.Image

- **emit**`(bound native)`
  - documentation unavailable

- **emit_stop_by_name**`(self, detailed_signal)`
  - Deprecated, please use stop_emission_by_name.

- **export_path_to_file**`(*args, **kwargs)`
  - export_path_to_file(self, file:Gio.File, path:Gimp.Path=None) -> bool

- **export_path_to_string**`(*args, **kwargs)`
  - export_path_to_string(self, path:Gimp.Path=None) -> str

- **find_next_guide**`(*args, **kwargs)`
  - find_next_guide(self, guide:int) -> int

- **find_next_sample_point**`(*args, **kwargs)`
  - find_next_sample_point(self, sample_point:int) -> int

- **find_property**`(*args, **kwargs)`
  - find_property(self, property_name:str) -> GObject.ParamSpec

- **flatten**`(*args, **kwargs)`
  - flatten(self) -> Gimp.Layer

- **flip**`(*args, **kwargs)`
  - flip(self, flip_type:Gimp.OrientationType) -> bool

- **floating_sel_attached_to**`(*args, **kwargs)`
  - floating_sel_attached_to(self) -> Gimp.Drawable

- **force_floating**`(self, *args, **kargs)`
  - documentation unavailable

- **freeze_channels**`(*args, **kwargs)`
  - freeze_channels(self) -> bool

- **freeze_layers**`(*args, **kwargs)`
  - freeze_layers(self) -> bool

- **freeze_notify**`(self)`
  - Freezes the object's property-changed notification queue.<br /><br />:returns:<br />    A context manager which optionally can be used to<br />    automatically thaw notifications.<br /><br />This will freeze the object so that "notify" signals are blocked until<br />the thaw_notify() method is called.<br /><br />.. code-block:: python<br /><br />    with obj.freeze_notify():<br />        pass

- **freeze_paths**`(*args, **kwargs)`
  - freeze_paths(self) -> bool

- **get_base_type**`(*args, **kwargs)`
  - get_base_type(self) -> Gimp.ImageBaseType

- **get_by_id**`(*args, **kwargs)`
  - get_by_id(image_id:int) -> Gimp.Image or None

- **get_channel_by_name**`(*args, **kwargs)`
  - get_channel_by_name(self, name:str) -> Gimp.Channel

- **get_channel_by_tattoo**`(*args, **kwargs)`
  - get_channel_by_tattoo(self, tattoo:int) -> Gimp.Channel

- **get_channels**`(*args, **kwargs)`
  - get_channels(self) -> list

- **get_color_profile**`(*args, **kwargs)`
  - get_color_profile(self) -> Gimp.ColorProfile

- **get_component_active**`(*args, **kwargs)`
  - get_component_active(self, component:Gimp.ChannelType) -> bool

- **get_component_visible**`(*args, **kwargs)`
  - get_component_visible(self, component:Gimp.ChannelType) -> bool

- **get_data**`(self, *args, **kargs)`
  - documentation unavailable

- **get_default_new_layer_mode**`(*args, **kwargs)`
  - get_default_new_layer_mode(self) -> Gimp.LayerMode

- **get_effective_color_profile**`(*args, **kwargs)`
  - get_effective_color_profile(self) -> Gimp.ColorProfile

- **get_exported_file**`(*args, **kwargs)`
  - get_exported_file(self) -> Gio.File

- **get_file**`(*args, **kwargs)`
  - get_file(self) -> Gio.File

- **get_floating_sel**`(*args, **kwargs)`
  - get_floating_sel(self) -> Gimp.Layer

- **get_guide_orientation**`(*args, **kwargs)`
  - get_guide_orientation(self, guide:int) -> Gimp.OrientationType

- **get_guide_position**`(*args, **kwargs)`
  - get_guide_position(self, guide:int) -> int

- **get_height**`(*args, **kwargs)`
  - get_height(self) -> int

- **get_id**`(*args, **kwargs)`
  - get_id(self) -> int

- **get_imported_file**`(*args, **kwargs)`
  - get_imported_file(self) -> Gio.File

- **get_item_position**`(*args, **kwargs)`
  - get_item_position(self, item:Gimp.Item) -> int

- **get_layer_by_name**`(*args, **kwargs)`
  - get_layer_by_name(self, name:str) -> Gimp.Layer

- **get_layer_by_tattoo**`(*args, **kwargs)`
  - get_layer_by_tattoo(self, tattoo:int) -> Gimp.Layer

- **get_layers**`(*args, **kwargs)`
  - get_layers(self) -> list

- **get_metadata**`(*args, **kwargs)`
  - get_metadata(self) -> Gimp.Metadata or None

- **get_name**`(*args, **kwargs)`
  - get_name(self) -> str

- **get_palette**`(*args, **kwargs)`
  - get_palette(self) -> Gimp.Palette

- **get_parasite**`(*args, **kwargs)`
  - get_parasite(self, name:str) -> Gimp.Parasite

- **get_parasite_list**`(*args, **kwargs)`
  - get_parasite_list(self) -> list

- **get_path_by_name**`(*args, **kwargs)`
  - get_path_by_name(self, name:str) -> Gimp.Path

- **get_path_by_tattoo**`(*args, **kwargs)`
  - get_path_by_tattoo(self, tattoo:int) -> Gimp.Path

- **get_paths**`(*args, **kwargs)`
  - get_paths(self) -> list

- **get_precision**`(*args, **kwargs)`
  - get_precision(self) -> Gimp.Precision

- **get_properties**`(bound native)`
  - documentation unavailable

- **get_property**`(bound native)`
  - documentation unavailable

- **get_qdata**`(self, *args, **kargs)`
  - documentation unavailable

- **get_resolution**`(*args, **kwargs)`
  - get_resolution(self) -> bool, xresolution:float, yresolution:float

- **get_sample_point_position**`(*args, **kwargs)`
  - get_sample_point_position(self, sample_point:int) -> int, position_y:int

- **get_selected_channels**`(*args, **kwargs)`
  - get_selected_channels(self) -> list

- **get_selected_drawables**`(*args, **kwargs)`
  - get_selected_drawables(self) -> list

- **get_selected_layers**`(*args, **kwargs)`
  - get_selected_layers(self) -> list

- **get_selected_paths**`(*args, **kwargs)`
  - get_selected_paths(self) -> list

- **get_selection**`(*args, **kwargs)`
  - get_selection(self) -> Gimp.Selection

- **get_simulation_bpc**`(*args, **kwargs)`
  - get_simulation_bpc(self) -> bool

- **get_simulation_intent**`(*args, **kwargs)`
  - get_simulation_intent(self) -> Gimp.ColorRenderingIntent

- **get_simulation_profile**`(*args, **kwargs)`
  - get_simulation_profile(self) -> Gimp.ColorProfile

- **get_tattoo_state**`(*args, **kwargs)`
  - get_tattoo_state(self) -> int

- **get_thumbnail**`(*args, **kwargs)`
  - get_thumbnail(self, width:int, height:int, alpha:Gimp.PixbufTransparency) -> GdkPixbuf.Pixbuf

- **get_thumbnail_data**`(*args, **kwargs)`
  - get_thumbnail_data(self, width:int, height:int) -> GLib.Bytes, width:int, height:int, bpp:int

- **get_unit**`(*args, **kwargs)`
  - get_unit(self) -> Gimp.Unit

- **get_width**`(*args, **kwargs)`
  - get_width(self) -> int

- **get_xcf_file**`(*args, **kwargs)`
  - get_xcf_file(self) -> Gio.File

- **getv**`(*args, **kwargs)`
  - getv(self, names:list, values:list)

- **grid_get_background_color**`(*args, **kwargs)`
  - grid_get_background_color(self) -> Gegl.Color

- **grid_get_foreground_color**`(*args, **kwargs)`
  - grid_get_foreground_color(self) -> Gegl.Color

- **grid_get_offset**`(*args, **kwargs)`
  - grid_get_offset(self) -> bool, xoffset:float, yoffset:float

- **grid_get_spacing**`(*args, **kwargs)`
  - grid_get_spacing(self) -> bool, xspacing:float, yspacing:float

- **grid_get_style**`(*args, **kwargs)`
  - grid_get_style(self) -> Gimp.GridStyle

- **grid_set_background_color**`(*args, **kwargs)`
  - grid_set_background_color(self, bgcolor:Gegl.Color) -> bool

- **grid_set_foreground_color**`(*args, **kwargs)`
  - grid_set_foreground_color(self, fgcolor:Gegl.Color) -> bool

- **grid_set_offset**`(*args, **kwargs)`
  - grid_set_offset(self, xoffset:float, yoffset:float) -> bool

- **grid_set_spacing**`(*args, **kwargs)`
  - grid_set_spacing(self, xspacing:float, yspacing:float) -> bool

- **grid_set_style**`(*args, **kwargs)`
  - grid_set_style(self, style:Gimp.GridStyle) -> bool

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

- **id_is_valid**`(*args, **kwargs)`
  - id_is_valid(image_id:int) -> bool

- **import_paths_from_file**`(*args, **kwargs)`
  - import_paths_from_file(self, file:Gio.File, merge:bool, scale:bool) -> bool, paths:list

- **import_paths_from_string**`(*args, **kwargs)`
  - import_paths_from_string(self, string:str, length:int, merge:bool, scale:bool) -> bool, paths:list

- **insert_channel**`(*args, **kwargs)`
  - insert_channel(self, channel:Gimp.Channel, parent:Gimp.Channel=None, position:int) -> bool

- **insert_layer**`(*args, **kwargs)`
  - insert_layer(self, layer:Gimp.Layer, parent:Gimp.Layer=None, position:int) -> bool

- **insert_path**`(*args, **kwargs)`
  - insert_path(self, path:Gimp.Path, parent:Gimp.Path=None, position:int) -> bool

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

- **is_dirty**`(*args, **kwargs)`
  - is_dirty(self) -> bool

- **is_floating**`(*args, **kwargs)`
  - is_floating(self) -> bool

- **is_valid**`(*args, **kwargs)`
  - is_valid(self) -> bool

- **list_properties**`(*args, **kwargs)`
  - list_properties(self) -> list

- **lower_item**`(*args, **kwargs)`
  - lower_item(self, item:Gimp.Item) -> bool

- **lower_item_to_bottom**`(*args, **kwargs)`
  - lower_item_to_bottom(self, item:Gimp.Item) -> bool

- **merge_down**`(*args, **kwargs)`
  - merge_down(self, merge_layer:Gimp.Layer, merge_type:Gimp.MergeType) -> Gimp.Layer

- **merge_visible_layers**`(*args, **kwargs)`
  - merge_visible_layers(self, merge_type:Gimp.MergeType) -> Gimp.Layer

- **metadata_load_thumbnail**`(*args, **kwargs)`
  - metadata_load_thumbnail(file:Gio.File) -> Gimp.Image or None

- **metadata_save_filter**`(*args, **kwargs)`
  - metadata_save_filter(self, mime_type:str, metadata:Gimp.Metadata, flags:Gimp.MetadataSaveFlags, file:Gio.File) -> Gimp.Metadata

- **metadata_save_prepare**`(*args, **kwargs)`
  - metadata_save_prepare(self, mime_type:str, suggested_flags:Gimp.MetadataSaveFlags) -> Gimp.Metadata

- **new**`(*args, **kwargs)`
  - new(width:int, height:int, type:Gimp.ImageBaseType) -> Gimp.Image

- **new_with_precision**`(*args, **kwargs)`
  - new_with_precision(width:int, height:int, type:Gimp.ImageBaseType, precision:Gimp.Precision) -> Gimp.Image

- **newv**`(*args, **kwargs)`
  - newv(object_type:GType, parameters:list) -> GObject.Object

- **notify**`(*args, **kwargs)`
  - notify(self, property_name:str)

- **notify_by_pspec**`(self, *args, **kargs)`
  - documentation unavailable

- **override_property**`(*args, **kwargs)`
  - override_property(self, property_id:int, name:str)

- **pick_color**`(*args, **kwargs)`
  - pick_color(self, drawables:list, x:float, y:float, sample_merged:bool, sample_average:bool, average_radius:float) -> bool, color:Gegl.Color

- **pick_correlate_layer**`(*args, **kwargs)`
  - pick_correlate_layer(self, x:int, y:int) -> Gimp.Layer

- **policy_color_profile**`(*args, **kwargs)`
  - policy_color_profile(self, interactive:bool) -> bool

- **policy_rotate**`(*args, **kwargs)`
  - policy_rotate(self, interactive:bool) -> bool

- **raise_item**`(*args, **kwargs)`
  - raise_item(self, item:Gimp.Item) -> bool

- **raise_item_to_top**`(*args, **kwargs)`
  - raise_item_to_top(self, item:Gimp.Item) -> bool

- **ref**`(self, *args, **kargs)`
  - documentation unavailable

- **ref_sink**`(self, *args, **kargs)`
  - documentation unavailable

- **remove_channel**`(*args, **kwargs)`
  - remove_channel(self, channel:Gimp.Channel) -> bool

- **remove_layer**`(*args, **kwargs)`
  - remove_layer(self, layer:Gimp.Layer) -> bool

- **remove_path**`(*args, **kwargs)`
  - remove_path(self, path:Gimp.Path) -> bool

- **reorder_item**`(*args, **kwargs)`
  - reorder_item(self, item:Gimp.Item, parent:Gimp.Item=None, position:int) -> bool

- **replace_data**`(self, *args, **kargs)`
  - documentation unavailable

- **replace_qdata**`(self, *args, **kargs)`
  - documentation unavailable

- **resize**`(*args, **kwargs)`
  - resize(self, new_width:int, new_height:int, offx:int, offy:int) -> bool

- **resize_to_layers**`(*args, **kwargs)`
  - resize_to_layers(self) -> bool

- **rotate**`(*args, **kwargs)`
  - rotate(self, rotate_type:Gimp.RotationType) -> bool

- **run_dispose**`(*args, **kwargs)`
  - run_dispose(self)

- **scale**`(*args, **kwargs)`
  - scale(self, new_width:int, new_height:int) -> bool

- **select_color**`(*args, **kwargs)`
  - select_color(self, operation:Gimp.ChannelOps, drawable:Gimp.Drawable, color:Gegl.Color) -> bool

- **select_contiguous_color**`(*args, **kwargs)`
  - select_contiguous_color(self, operation:Gimp.ChannelOps, drawable:Gimp.Drawable, x:float, y:float) -> bool

- **select_ellipse**`(*args, **kwargs)`
  - select_ellipse(self, operation:Gimp.ChannelOps, x:float, y:float, width:float, height:float) -> bool

- **select_item**`(*args, **kwargs)`
  - select_item(self, operation:Gimp.ChannelOps, item:Gimp.Item) -> bool

- **select_polygon**`(*args, **kwargs)`
  - select_polygon(self, operation:Gimp.ChannelOps, segs:list) -> bool

- **select_rectangle**`(*args, **kwargs)`
  - select_rectangle(self, operation:Gimp.ChannelOps, x:float, y:float, width:float, height:float) -> bool

- **select_round_rectangle**`(*args, **kwargs)`
  - select_round_rectangle(self, operation:Gimp.ChannelOps, x:float, y:float, width:float, height:float, corner_radius_x:float, corner_radius_y:float) -> bool

- **set_color_profile**`(*args, **kwargs)`
  - set_color_profile(self, profile:Gimp.ColorProfile=None) -> bool

- **set_color_profile_from_file**`(*args, **kwargs)`
  - set_color_profile_from_file(self, file:Gio.File) -> bool

- **set_component_active**`(*args, **kwargs)`
  - set_component_active(self, component:Gimp.ChannelType, active:bool) -> bool

- **set_component_visible**`(*args, **kwargs)`
  - set_component_visible(self, component:Gimp.ChannelType, visible:bool) -> bool

- **set_data**`(self, *args, **kargs)`
  - documentation unavailable

- **set_file**`(*args, **kwargs)`
  - set_file(self, file:Gio.File) -> bool

- **set_metadata**`(*args, **kwargs)`
  - set_metadata(self, metadata:Gimp.Metadata) -> bool

- **set_palette**`(*args, **kwargs)`
  - set_palette(self, new_palette:Gimp.Palette) -> Gimp.Palette

- **set_properties**`(bound native)`
  - documentation unavailable

- **set_property**`(bound native)`
  - documentation unavailable

- **set_resolution**`(*args, **kwargs)`
  - set_resolution(self, xresolution:float, yresolution:float) -> bool

- **set_selected_channels**`(*args, **kwargs)`
  - set_selected_channels(self, channels:list) -> bool

- **set_selected_layers**`(*args, **kwargs)`
  - set_selected_layers(self, layers:list) -> bool

- **set_selected_paths**`(*args, **kwargs)`
  - set_selected_paths(self, paths:list) -> bool

- **set_simulation_bpc**`(*args, **kwargs)`
  - set_simulation_bpc(self, bpc:bool) -> bool

- **set_simulation_intent**`(*args, **kwargs)`
  - set_simulation_intent(self, intent:Gimp.ColorRenderingIntent) -> bool

- **set_simulation_profile**`(*args, **kwargs)`
  - set_simulation_profile(self, profile:Gimp.ColorProfile=None) -> bool

- **set_simulation_profile_from_file**`(*args, **kwargs)`
  - set_simulation_profile_from_file(self, file:Gio.File) -> bool

- **set_tattoo_state**`(*args, **kwargs)`
  - set_tattoo_state(self, tattoo_state:int) -> bool

- **set_unit**`(*args, **kwargs)`
  - set_unit(self, unit:Gimp.Unit) -> bool

- **steal_data**`(self, *args, **kargs)`
  - documentation unavailable

- **steal_qdata**`(self, *args, **kargs)`
  - documentation unavailable

- **stop_emission**`(self, detailed_signal)`
  - Deprecated, please use stop_emission_by_name.

- **stop_emission_by_name**`(*args, **kwargs)`
  - signal_stop_emission_by_name(instance:GObject.Object, detailed_signal:str)

- **take_selected_channels**`(*args, **kwargs)`
  - take_selected_channels(self, channels:list) -> bool

- **take_selected_layers**`(*args, **kwargs)`
  - take_selected_layers(self, layers:list) -> bool

- **take_selected_paths**`(*args, **kwargs)`
  - take_selected_paths(self, paths:list) -> bool

- **thaw_channels**`(*args, **kwargs)`
  - thaw_channels(self) -> bool

- **thaw_layers**`(*args, **kwargs)`
  - thaw_layers(self) -> bool

- **thaw_notify**`(*args, **kwargs)`
  - thaw_notify(self)

- **thaw_paths**`(*args, **kwargs)`
  - thaw_paths(self) -> bool

- **undo_disable**`(*args, **kwargs)`
  - undo_disable(self) -> bool

- **undo_enable**`(*args, **kwargs)`
  - undo_enable(self) -> bool

- **undo_freeze**`(*args, **kwargs)`
  - undo_freeze(self) -> bool

- **undo_group_end**`(*args, **kwargs)`
  - undo_group_end(self) -> bool

- **undo_group_start**`(*args, **kwargs)`
  - undo_group_start(self) -> bool

- **undo_is_enabled**`(*args, **kwargs)`
  - undo_is_enabled(self) -> bool

- **undo_thaw**`(*args, **kwargs)`
  - undo_thaw(self) -> bool

- **unref**`(self, *args, **kargs)`
  - documentation unavailable

- **unset_active_channel**`(*args, **kwargs)`
  - unset_active_channel(self) -> bool

- **watch_closure**`(self, *args, **kargs)`
  - documentation unavailable

- **weak_ref**`(bound native)`
  - documentation unavailable


