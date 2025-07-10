---
layout: default
title: Gimp.objects
---
# Gimp.objects

## Layer
- :Constructors:<br /><br />::<br /><br />    Layer(**properties)<br />    new(image:Gimp.Image, name:str=None, width:int, height:int, type:Gimp.ImageType, opacity:float, mode:Gimp.LayerMode) -> Gimp.Layer<br />    new_from_drawable(drawable:Gimp.Drawable, dest_image:Gimp.Image) -> Gimp.Layer<br />    new_from_pixbuf(image:Gimp.Image, name:str, pixbuf:GdkPixbuf.Pixbuf, opacity:float, mode:Gimp.LayerMode, progress_start:float, progress_end:float) -> Gimp.Layer<br />    new_from_surface(image:Gimp.Image, name:str, surface:cairo.Surface, progress_start:float, progress_end:float) -> Gimp.Layer<br />    new_from_visible(image:Gimp.Image, dest_image:Gimp.Image, name:str=None) -> Gimp.Layer

### Runtime attributes

- **g_type_instance**
- **parent_instance**
- **props**
- **qdata**
- **ref_count**

### Runtime functions
- **add_alpha**`(*args, **kwargs)`
  - add_alpha(self) -> bool

- **add_mask**`(*args, **kwargs)`
  - add_mask(self, mask:Gimp.LayerMask) -> bool

- **append_filter**`(*args, **kwargs)`
  - append_filter(self, filter:Gimp.DrawableFilter)

- **attach_parasite**`(*args, **kwargs)`
  - attach_parasite(self, parasite:Gimp.Parasite) -> bool

- **bind_property**`(bound native)`
  - documentation unavailable

- **bind_property_full**`(self, *args, **kargs)`
  - documentation unavailable

- **brightness_contrast**`(*args, **kwargs)`
  - brightness_contrast(self, brightness:float, contrast:float) -> bool

- **chain**`(bound native)`
  - documentation unavailable

- **color_balance**`(*args, **kwargs)`
  - color_balance(self, transfer_mode:Gimp.TransferMode, preserve_lum:bool, cyan_red:float, magenta_green:float, yellow_blue:float) -> bool

- **colorize_hsl**`(*args, **kwargs)`
  - colorize_hsl(self, hue:float, saturation:float, lightness:float) -> bool

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
  - copy(self) -> Gimp.Layer

- **create_mask**`(*args, **kwargs)`
  - create_mask(self, mask_type:Gimp.AddMaskType) -> Gimp.LayerMask

- **curves_explicit**`(*args, **kwargs)`
  - curves_explicit(self, channel:Gimp.HistogramChannel, values:list) -> bool

- **curves_spline**`(*args, **kwargs)`
  - curves_spline(self, channel:Gimp.HistogramChannel, points:list) -> bool

- **delete**`(*args, **kwargs)`
  - delete(self) -> bool

- **desaturate**`(*args, **kwargs)`
  - desaturate(self, desaturate_mode:Gimp.DesaturateMode) -> bool

- **detach_parasite**`(*args, **kwargs)`
  - detach_parasite(self, name:str) -> bool

- **disconnect**`(*args, **kwargs)`
  - signal_handler_disconnect(instance:GObject.Object, handler_id:int)

- **disconnect_by_func**`(bound native)`
  - documentation unavailable

- **edit_bucket_fill**`(*args, **kwargs)`
  - edit_bucket_fill(self, fill_type:Gimp.FillType, x:float, y:float) -> bool

- **edit_clear**`(*args, **kwargs)`
  - edit_clear(self) -> bool

- **edit_fill**`(*args, **kwargs)`
  - edit_fill(self, fill_type:Gimp.FillType) -> bool

- **edit_gradient_fill**`(*args, **kwargs)`
  - edit_gradient_fill(self, gradient_type:Gimp.GradientType, offset:float, supersample:bool, supersample_max_depth:int, supersample_threshold:float, dither:bool, x1:float, y1:float, x2:float, y2:float) -> bool

- **edit_stroke_item**`(*args, **kwargs)`
  - edit_stroke_item(self, item:Gimp.Item) -> bool

- **edit_stroke_selection**`(*args, **kwargs)`
  - edit_stroke_selection(self) -> bool

- **emit**`(bound native)`
  - documentation unavailable

- **emit_stop_by_name**`(self, detailed_signal)`
  - Deprecated, please use stop_emission_by_name.

- **equalize**`(*args, **kwargs)`
  - equalize(self, mask_only:bool) -> bool

- **extract_component**`(*args, **kwargs)`
  - extract_component(self, component:int, invert:bool, linear:bool) -> bool

- **fill**`(*args, **kwargs)`
  - fill(self, fill_type:Gimp.FillType) -> bool

- **find_property**`(*args, **kwargs)`
  - find_property(self, property_name:str) -> GObject.ParamSpec

- **flatten**`(*args, **kwargs)`
  - flatten(self) -> bool

- **force_floating**`(self, *args, **kargs)`
  - documentation unavailable

- **foreground_extract**`(*args, **kwargs)`
  - foreground_extract(self, mode:Gimp.ForegroundExtractMode, mask:Gimp.Drawable) -> bool

- **free_shadow**`(*args, **kwargs)`
  - free_shadow(self) -> bool

- **freeze_notify**`(self)`
  - Freezes the object's property-changed notification queue.<br /><br />:returns:<br />    A context manager which optionally can be used to<br />    automatically thaw notifications.<br /><br />This will freeze the object so that "notify" signals are blocked until<br />the thaw_notify() method is called.<br /><br />.. code-block:: python<br /><br />    with obj.freeze_notify():<br />        pass

- **from_mask**`(*args, **kwargs)`
  - from_mask(mask:Gimp.LayerMask) -> Gimp.Layer

- **get_apply_mask**`(*args, **kwargs)`
  - get_apply_mask(self) -> bool

- **get_blend_space**`(*args, **kwargs)`
  - get_blend_space(self) -> Gimp.LayerColorSpace

- **get_bpp**`(*args, **kwargs)`
  - get_bpp(self) -> int

- **get_buffer**`(*args, **kwargs)`
  - get_buffer(self) -> Gegl.Buffer

- **get_by_id**`(*args, **kwargs)`
  - get_by_id(layer_id:int) -> Gimp.Layer or None

- **get_children**`(*args, **kwargs)`
  - get_children(self) -> list

- **get_color_tag**`(*args, **kwargs)`
  - get_color_tag(self) -> Gimp.ColorTag

- **get_composite_mode**`(*args, **kwargs)`
  - get_composite_mode(self) -> Gimp.LayerCompositeMode

- **get_composite_space**`(*args, **kwargs)`
  - get_composite_space(self) -> Gimp.LayerColorSpace

- **get_data**`(self, *args, **kargs)`
  - documentation unavailable

- **get_edit_mask**`(*args, **kwargs)`
  - get_edit_mask(self) -> bool

- **get_expanded**`(*args, **kwargs)`
  - get_expanded(self) -> bool

- **get_filters**`(*args, **kwargs)`
  - get_filters(self) -> list

- **get_format**`(*args, **kwargs)`
  - get_format(self) -> Babl.Object

- **get_height**`(*args, **kwargs)`
  - get_height(self) -> int

- **get_id**`(*args, **kwargs)`
  - get_id(self) -> int

- **get_image**`(*args, **kwargs)`
  - get_image(self) -> Gimp.Image

- **get_lock_alpha**`(*args, **kwargs)`
  - get_lock_alpha(self) -> bool

- **get_lock_content**`(*args, **kwargs)`
  - get_lock_content(self) -> bool

- **get_lock_position**`(*args, **kwargs)`
  - get_lock_position(self) -> bool

- **get_lock_visibility**`(*args, **kwargs)`
  - get_lock_visibility(self) -> bool

- **get_mask**`(*args, **kwargs)`
  - get_mask(self) -> Gimp.LayerMask

- **get_mode**`(*args, **kwargs)`
  - get_mode(self) -> Gimp.LayerMode

- **get_name**`(*args, **kwargs)`
  - get_name(self) -> str

- **get_offsets**`(*args, **kwargs)`
  - get_offsets(self) -> bool, offset_x:int, offset_y:int

- **get_opacity**`(*args, **kwargs)`
  - get_opacity(self) -> float

- **get_parasite**`(*args, **kwargs)`
  - get_parasite(self, name:str) -> Gimp.Parasite

- **get_parasite_list**`(*args, **kwargs)`
  - get_parasite_list(self) -> list

- **get_parent**`(*args, **kwargs)`
  - get_parent(self) -> Gimp.Item

- **get_pixel**`(*args, **kwargs)`
  - get_pixel(self, x_coord:int, y_coord:int) -> Gegl.Color

- **get_properties**`(bound native)`
  - documentation unavailable

- **get_property**`(bound native)`
  - documentation unavailable

- **get_qdata**`(self, *args, **kargs)`
  - documentation unavailable

- **get_shadow_buffer**`(*args, **kwargs)`
  - get_shadow_buffer(self) -> Gegl.Buffer

- **get_show_mask**`(*args, **kwargs)`
  - get_show_mask(self) -> bool

- **get_sub_thumbnail**`(*args, **kwargs)`
  - get_sub_thumbnail(self, src_x:int, src_y:int, src_width:int, src_height:int, dest_width:int, dest_height:int, alpha:Gimp.PixbufTransparency) -> GdkPixbuf.Pixbuf

- **get_sub_thumbnail_data**`(*args, **kwargs)`
  - get_sub_thumbnail_data(self, src_x:int, src_y:int, src_width:int, src_height:int, dest_width:int, dest_height:int) -> GLib.Bytes, actual_width:int, actual_height:int, bpp:int

- **get_tattoo**`(*args, **kwargs)`
  - get_tattoo(self) -> int

- **get_thumbnail**`(*args, **kwargs)`
  - get_thumbnail(self, width:int, height:int, alpha:Gimp.PixbufTransparency) -> GdkPixbuf.Pixbuf

- **get_thumbnail_data**`(*args, **kwargs)`
  - get_thumbnail_data(self, width:int, height:int) -> GLib.Bytes or None, actual_width:int, actual_height:int, bpp:int

- **get_thumbnail_format**`(*args, **kwargs)`
  - get_thumbnail_format(self) -> Babl.Object

- **get_visible**`(*args, **kwargs)`
  - get_visible(self) -> bool

- **get_width**`(*args, **kwargs)`
  - get_width(self) -> int

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

- **has_alpha**`(*args, **kwargs)`
  - has_alpha(self) -> bool

- **histogram**`(*args, **kwargs)`
  - histogram(self, channel:Gimp.HistogramChannel, start_range:float, end_range:float) -> bool, mean:float, std_dev:float, median:float, pixels:float, count:float, percentile:float

- **hue_saturation**`(*args, **kwargs)`
  - hue_saturation(self, hue_range:Gimp.HueRange, hue_offset:float, lightness:float, saturation:float, overlap:float) -> bool

- **id_is_channel**`(*args, **kwargs)`
  - id_is_channel(item_id:int) -> bool

- **id_is_drawable**`(*args, **kwargs)`
  - id_is_drawable(item_id:int) -> bool

- **id_is_group_layer**`(*args, **kwargs)`
  - id_is_group_layer(item_id:int) -> bool

- **id_is_layer**`(*args, **kwargs)`
  - id_is_layer(item_id:int) -> bool

- **id_is_layer_mask**`(*args, **kwargs)`
  - id_is_layer_mask(item_id:int) -> bool

- **id_is_path**`(*args, **kwargs)`
  - id_is_path(item_id:int) -> bool

- **id_is_selection**`(*args, **kwargs)`
  - id_is_selection(item_id:int) -> bool

- **id_is_text_layer**`(*args, **kwargs)`
  - id_is_text_layer(item_id:int) -> bool

- **id_is_valid**`(*args, **kwargs)`
  - id_is_valid(item_id:int) -> bool

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

- **invert**`(*args, **kwargs)`
  - invert(self, linear:bool) -> bool

- **is_channel**`(*args, **kwargs)`
  - is_channel(self) -> bool

- **is_drawable**`(*args, **kwargs)`
  - is_drawable(self) -> bool

- **is_floating**`(*args, **kwargs)`
  - is_floating(self) -> bool

- **is_floating_sel**`(*args, **kwargs)`
  - is_floating_sel(self) -> bool

- **is_gray**`(*args, **kwargs)`
  - is_gray(self) -> bool

- **is_group**`(*args, **kwargs)`
  - is_group(self) -> bool

- **is_group_layer**`(*args, **kwargs)`
  - is_group_layer(self) -> bool

- **is_indexed**`(*args, **kwargs)`
  - is_indexed(self) -> bool

- **is_layer**`(*args, **kwargs)`
  - is_layer(self) -> bool

- **is_layer_mask**`(*args, **kwargs)`
  - is_layer_mask(self) -> bool

- **is_path**`(*args, **kwargs)`
  - is_path(self) -> bool

- **is_rgb**`(*args, **kwargs)`
  - is_rgb(self) -> bool

- **is_selection**`(*args, **kwargs)`
  - is_selection(self) -> bool

- **is_text_layer**`(*args, **kwargs)`
  - is_text_layer(self) -> bool

- **is_valid**`(*args, **kwargs)`
  - is_valid(self) -> bool

- **levels**`(*args, **kwargs)`
  - levels(self, channel:Gimp.HistogramChannel, low_input:float, high_input:float, clamp_input:bool, gamma:float, low_output:float, high_output:float, clamp_output:bool) -> bool

- **levels_stretch**`(*args, **kwargs)`
  - levels_stretch(self) -> bool

- **list_properties**`(*args, **kwargs)`
  - list_properties(self) -> list

- **mask_bounds**`(*args, **kwargs)`
  - mask_bounds(self) -> bool, x1:int, y1:int, x2:int, y2:int

- **mask_intersect**`(*args, **kwargs)`
  - mask_intersect(self) -> bool, x:int, y:int, width:int, height:int

- **merge_filter**`(*args, **kwargs)`
  - merge_filter(self, filter:Gimp.DrawableFilter)

- **merge_filters**`(*args, **kwargs)`
  - merge_filters(self) -> bool

- **merge_shadow**`(*args, **kwargs)`
  - merge_shadow(self, undo:bool) -> bool

- **new**`(*args, **kwargs)`
  - new(image:Gimp.Image, name:str=None, width:int, height:int, type:Gimp.ImageType, opacity:float, mode:Gimp.LayerMode) -> Gimp.Layer

- **new_from_drawable**`(*args, **kwargs)`
  - new_from_drawable(drawable:Gimp.Drawable, dest_image:Gimp.Image) -> Gimp.Layer

- **new_from_pixbuf**`(*args, **kwargs)`
  - new_from_pixbuf(image:Gimp.Image, name:str, pixbuf:GdkPixbuf.Pixbuf, opacity:float, mode:Gimp.LayerMode, progress_start:float, progress_end:float) -> Gimp.Layer

- **new_from_surface**`(*args, **kwargs)`
  - new_from_surface(image:Gimp.Image, name:str, surface:cairo.Surface, progress_start:float, progress_end:float) -> Gimp.Layer

- **new_from_visible**`(*args, **kwargs)`
  - new_from_visible(image:Gimp.Image, dest_image:Gimp.Image, name:str=None) -> Gimp.Layer

- **newv**`(*args, **kwargs)`
  - newv(object_type:GType, parameters:list) -> GObject.Object

- **notify**`(*args, **kwargs)`
  - notify(self, property_name:str)

- **notify_by_pspec**`(self, *args, **kargs)`
  - documentation unavailable

- **offset**`(*args, **kwargs)`
  - offset(self, wrap_around:bool, fill_type:Gimp.OffsetType, color:Gegl.Color, offset_x:int, offset_y:int) -> bool

- **override_property**`(*args, **kwargs)`
  - override_property(self, property_id:int, name:str)

- **posterize**`(*args, **kwargs)`
  - posterize(self, levels:int) -> bool

- **ref**`(self, *args, **kargs)`
  - documentation unavailable

- **ref_sink**`(self, *args, **kargs)`
  - documentation unavailable

- **remove_mask**`(*args, **kwargs)`
  - remove_mask(self, mode:Gimp.MaskApplyMode) -> bool

- **replace_data**`(self, *args, **kargs)`
  - documentation unavailable

- **replace_qdata**`(self, *args, **kargs)`
  - documentation unavailable

- **resize**`(*args, **kwargs)`
  - resize(self, new_width:int, new_height:int, offx:int, offy:int) -> bool

- **resize_to_image_size**`(*args, **kwargs)`
  - resize_to_image_size(self) -> bool

- **run_dispose**`(*args, **kwargs)`
  - run_dispose(self)

- **scale**`(*args, **kwargs)`
  - scale(self, new_width:int, new_height:int, local_origin:bool) -> bool

- **set_apply_mask**`(*args, **kwargs)`
  - set_apply_mask(self, apply_mask:bool) -> bool

- **set_blend_space**`(*args, **kwargs)`
  - set_blend_space(self, blend_space:Gimp.LayerColorSpace) -> bool

- **set_color_tag**`(*args, **kwargs)`
  - set_color_tag(self, color_tag:Gimp.ColorTag) -> bool

- **set_composite_mode**`(*args, **kwargs)`
  - set_composite_mode(self, composite_mode:Gimp.LayerCompositeMode) -> bool

- **set_composite_space**`(*args, **kwargs)`
  - set_composite_space(self, composite_space:Gimp.LayerColorSpace) -> bool

- **set_data**`(self, *args, **kargs)`
  - documentation unavailable

- **set_edit_mask**`(*args, **kwargs)`
  - set_edit_mask(self, edit_mask:bool) -> bool

- **set_expanded**`(*args, **kwargs)`
  - set_expanded(self, expanded:bool) -> bool

- **set_lock_alpha**`(*args, **kwargs)`
  - set_lock_alpha(self, lock_alpha:bool) -> bool

- **set_lock_content**`(*args, **kwargs)`
  - set_lock_content(self, lock_content:bool) -> bool

- **set_lock_position**`(*args, **kwargs)`
  - set_lock_position(self, lock_position:bool) -> bool

- **set_lock_visibility**`(*args, **kwargs)`
  - set_lock_visibility(self, lock_visibility:bool) -> bool

- **set_mode**`(*args, **kwargs)`
  - set_mode(self, mode:Gimp.LayerMode) -> bool

- **set_name**`(*args, **kwargs)`
  - set_name(self, name:str) -> bool

- **set_offsets**`(*args, **kwargs)`
  - set_offsets(self, offx:int, offy:int) -> bool

- **set_opacity**`(*args, **kwargs)`
  - set_opacity(self, opacity:float) -> bool

- **set_pixel**`(*args, **kwargs)`
  - set_pixel(self, x_coord:int, y_coord:int, color:Gegl.Color) -> bool

- **set_properties**`(bound native)`
  - documentation unavailable

- **set_property**`(bound native)`
  - documentation unavailable

- **set_show_mask**`(*args, **kwargs)`
  - set_show_mask(self, show_mask:bool) -> bool

- **set_tattoo**`(*args, **kwargs)`
  - set_tattoo(self, tattoo:int) -> bool

- **set_visible**`(*args, **kwargs)`
  - set_visible(self, visible:bool) -> bool

- **shadows_highlights**`(*args, **kwargs)`
  - shadows_highlights(self, shadows:float, highlights:float, whitepoint:float, radius:float, compress:float, shadows_ccorrect:float, highlights_ccorrect:float) -> bool

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

- **threshold**`(*args, **kwargs)`
  - threshold(self, channel:Gimp.HistogramChannel, low_threshold:float, high_threshold:float) -> bool

- **transform_2d**`(*args, **kwargs)`
  - transform_2d(self, source_x:float, source_y:float, scale_x:float, scale_y:float, angle:float, dest_x:float, dest_y:float) -> Gimp.Item

- **transform_flip**`(*args, **kwargs)`
  - transform_flip(self, x0:float, y0:float, x1:float, y1:float) -> Gimp.Item

- **transform_flip_simple**`(*args, **kwargs)`
  - transform_flip_simple(self, flip_type:Gimp.OrientationType, auto_center:bool, axis:float) -> Gimp.Item

- **transform_matrix**`(*args, **kwargs)`
  - transform_matrix(self, coeff_0_0:float, coeff_0_1:float, coeff_0_2:float, coeff_1_0:float, coeff_1_1:float, coeff_1_2:float, coeff_2_0:float, coeff_2_1:float, coeff_2_2:float) -> Gimp.Item

- **transform_perspective**`(*args, **kwargs)`
  - transform_perspective(self, x0:float, y0:float, x1:float, y1:float, x2:float, y2:float, x3:float, y3:float) -> Gimp.Item

- **transform_rotate**`(*args, **kwargs)`
  - transform_rotate(self, angle:float, auto_center:bool, center_x:float, center_y:float) -> Gimp.Item

- **transform_rotate_simple**`(*args, **kwargs)`
  - transform_rotate_simple(self, rotate_type:Gimp.RotationType, auto_center:bool, center_x:float, center_y:float) -> Gimp.Item

- **transform_scale**`(*args, **kwargs)`
  - transform_scale(self, x0:float, y0:float, x1:float, y1:float) -> Gimp.Item

- **transform_shear**`(*args, **kwargs)`
  - transform_shear(self, shear_type:Gimp.OrientationType, magnitude:float) -> Gimp.Item

- **transform_translate**`(*args, **kwargs)`
  - transform_translate(self, off_x:float, off_y:float) -> Gimp.Item

- **type**`(*args, **kwargs)`
  - type(self) -> Gimp.ImageType

- **type_with_alpha**`(*args, **kwargs)`
  - type_with_alpha(self) -> Gimp.ImageType

- **unref**`(self, *args, **kargs)`
  - documentation unavailable

- **update**`(*args, **kwargs)`
  - update(self, x:int, y:int, width:int, height:int) -> bool

- **watch_closure**`(self, *args, **kargs)`
  - documentation unavailable

- **weak_ref**`(bound native)`
  - documentation unavailable


