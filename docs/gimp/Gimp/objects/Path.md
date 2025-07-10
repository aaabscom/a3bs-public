---
layout: default
title: Gimp.objects
---
# Gimp.objects

## Path
- :Constructors:<br /><br />::<br /><br />    Path(**properties)<br />    new(image:Gimp.Image, name:str) -> Gimp.Path<br />    new_from_text_layer(image:Gimp.Image, layer:Gimp.Layer) -> Gimp.Path

### Runtime attributes

- **g_type_instance**
- **parent_instance**
- **props**
- **qdata**
- **ref_count**

### Runtime functions
- **attach_parasite**`(*args, **kwargs)`
  - attach_parasite(self, parasite:Gimp.Parasite) -> bool

- **bezier_stroke_conicto**`(*args, **kwargs)`
  - bezier_stroke_conicto(self, stroke_id:int, x0:float, y0:float, x1:float, y1:float) -> bool

- **bezier_stroke_cubicto**`(*args, **kwargs)`
  - bezier_stroke_cubicto(self, stroke_id:int, x0:float, y0:float, x1:float, y1:float, x2:float, y2:float) -> bool

- **bezier_stroke_lineto**`(*args, **kwargs)`
  - bezier_stroke_lineto(self, stroke_id:int, x0:float, y0:float) -> bool

- **bezier_stroke_new_ellipse**`(*args, **kwargs)`
  - bezier_stroke_new_ellipse(self, x0:float, y0:float, radius_x:float, radius_y:float, angle:float) -> int

- **bezier_stroke_new_moveto**`(*args, **kwargs)`
  - bezier_stroke_new_moveto(self, x0:float, y0:float) -> int

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

- **copy**`(*args, **kwargs)`
  - copy(self) -> Gimp.Path

- **delete**`(*args, **kwargs)`
  - delete(self) -> bool

- **detach_parasite**`(*args, **kwargs)`
  - detach_parasite(self, name:str) -> bool

- **disconnect**`(*args, **kwargs)`
  - signal_handler_disconnect(instance:GObject.Object, handler_id:int)

- **disconnect_by_func**`(bound native)`
  - documentation unavailable

- **emit**`(bound native)`
  - documentation unavailable

- **emit_stop_by_name**`(self, detailed_signal)`
  - Deprecated, please use stop_emission_by_name.

- **find_property**`(*args, **kwargs)`
  - find_property(self, property_name:str) -> GObject.ParamSpec

- **force_floating**`(self, *args, **kargs)`
  - documentation unavailable

- **free**`(*args, **kwargs)`
  - free(path:list)

- **freeze_notify**`(self)`
  - Freezes the object's property-changed notification queue.<br /><br />:returns:<br />    A context manager which optionally can be used to<br />    automatically thaw notifications.<br /><br />This will freeze the object so that "notify" signals are blocked until<br />the thaw_notify() method is called.<br /><br />.. code-block:: python<br /><br />    with obj.freeze_notify():<br />        pass

- **get_by_id**`(*args, **kwargs)`
  - get_by_id(path_id:int) -> Gimp.Path or None

- **get_children**`(*args, **kwargs)`
  - get_children(self) -> list

- **get_color_tag**`(*args, **kwargs)`
  - get_color_tag(self) -> Gimp.ColorTag

- **get_data**`(self, *args, **kargs)`
  - documentation unavailable

- **get_expanded**`(*args, **kwargs)`
  - get_expanded(self) -> bool

- **get_id**`(*args, **kwargs)`
  - get_id(self) -> int

- **get_image**`(*args, **kwargs)`
  - get_image(self) -> Gimp.Image

- **get_lock_content**`(*args, **kwargs)`
  - get_lock_content(self) -> bool

- **get_lock_position**`(*args, **kwargs)`
  - get_lock_position(self) -> bool

- **get_lock_visibility**`(*args, **kwargs)`
  - get_lock_visibility(self) -> bool

- **get_name**`(*args, **kwargs)`
  - get_name(self) -> str

- **get_parasite**`(*args, **kwargs)`
  - get_parasite(self, name:str) -> Gimp.Parasite

- **get_parasite_list**`(*args, **kwargs)`
  - get_parasite_list(self) -> list

- **get_parent**`(*args, **kwargs)`
  - get_parent(self) -> Gimp.Item

- **get_properties**`(bound native)`
  - documentation unavailable

- **get_property**`(bound native)`
  - documentation unavailable

- **get_qdata**`(self, *args, **kargs)`
  - documentation unavailable

- **get_strokes**`(*args, **kwargs)`
  - get_strokes(self) -> list

- **get_tattoo**`(*args, **kwargs)`
  - get_tattoo(self) -> int

- **get_user_writable_dir**`(*args, **kwargs)`
  - get_user_writable_dir(path:list) -> str

- **get_visible**`(*args, **kwargs)`
  - get_visible(self) -> bool

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

- **is_channel**`(*args, **kwargs)`
  - is_channel(self) -> bool

- **is_drawable**`(*args, **kwargs)`
  - is_drawable(self) -> bool

- **is_floating**`(*args, **kwargs)`
  - is_floating(self) -> bool

- **is_group**`(*args, **kwargs)`
  - is_group(self) -> bool

- **is_group_layer**`(*args, **kwargs)`
  - is_group_layer(self) -> bool

- **is_layer**`(*args, **kwargs)`
  - is_layer(self) -> bool

- **is_layer_mask**`(*args, **kwargs)`
  - is_layer_mask(self) -> bool

- **is_path**`(*args, **kwargs)`
  - is_path(self) -> bool

- **is_selection**`(*args, **kwargs)`
  - is_selection(self) -> bool

- **is_text_layer**`(*args, **kwargs)`
  - is_text_layer(self) -> bool

- **is_valid**`(*args, **kwargs)`
  - is_valid(self) -> bool

- **list_properties**`(*args, **kwargs)`
  - list_properties(self) -> list

- **new**`(*args, **kwargs)`
  - new(image:Gimp.Image, name:str) -> Gimp.Path

- **new_from_text_layer**`(*args, **kwargs)`
  - new_from_text_layer(image:Gimp.Image, layer:Gimp.Layer) -> Gimp.Path

- **newv**`(*args, **kwargs)`
  - newv(object_type:GType, parameters:list) -> GObject.Object

- **notify**`(*args, **kwargs)`
  - notify(self, property_name:str)

- **notify_by_pspec**`(self, *args, **kargs)`
  - documentation unavailable

- **override_property**`(*args, **kwargs)`
  - override_property(self, property_id:int, name:str)

- **parse**`(*args, **kwargs)`
  - parse(path:str, max_paths:int, check:bool) -> list, check_failed:list

- **ref**`(self, *args, **kargs)`
  - documentation unavailable

- **ref_sink**`(self, *args, **kargs)`
  - documentation unavailable

- **remove_stroke**`(*args, **kwargs)`
  - remove_stroke(self, stroke_id:int) -> bool

- **replace_data**`(self, *args, **kargs)`
  - documentation unavailable

- **replace_qdata**`(self, *args, **kargs)`
  - documentation unavailable

- **run_dispose**`(*args, **kwargs)`
  - run_dispose(self)

- **set_color_tag**`(*args, **kwargs)`
  - set_color_tag(self, color_tag:Gimp.ColorTag) -> bool

- **set_data**`(self, *args, **kargs)`
  - documentation unavailable

- **set_expanded**`(*args, **kwargs)`
  - set_expanded(self, expanded:bool) -> bool

- **set_lock_content**`(*args, **kwargs)`
  - set_lock_content(self, lock_content:bool) -> bool

- **set_lock_position**`(*args, **kwargs)`
  - set_lock_position(self, lock_position:bool) -> bool

- **set_lock_visibility**`(*args, **kwargs)`
  - set_lock_visibility(self, lock_visibility:bool) -> bool

- **set_name**`(*args, **kwargs)`
  - set_name(self, name:str) -> bool

- **set_properties**`(bound native)`
  - documentation unavailable

- **set_property**`(bound native)`
  - documentation unavailable

- **set_tattoo**`(*args, **kwargs)`
  - set_tattoo(self, tattoo:int) -> bool

- **set_visible**`(*args, **kwargs)`
  - set_visible(self, visible:bool) -> bool

- **steal_data**`(self, *args, **kargs)`
  - documentation unavailable

- **steal_qdata**`(self, *args, **kargs)`
  - documentation unavailable

- **stop_emission**`(self, detailed_signal)`
  - Deprecated, please use stop_emission_by_name.

- **stop_emission_by_name**`(*args, **kwargs)`
  - signal_stop_emission_by_name(instance:GObject.Object, detailed_signal:str)

- **stroke_close**`(*args, **kwargs)`
  - stroke_close(self, stroke_id:int) -> bool

- **stroke_flip**`(*args, **kwargs)`
  - stroke_flip(self, stroke_id:int, flip_type:Gimp.OrientationType, axis:float) -> bool

- **stroke_flip_free**`(*args, **kwargs)`
  - stroke_flip_free(self, stroke_id:int, x1:float, y1:float, x2:float, y2:float) -> bool

- **stroke_get_length**`(*args, **kwargs)`
  - stroke_get_length(self, stroke_id:int, precision:float) -> float

- **stroke_get_point_at_dist**`(*args, **kwargs)`
  - stroke_get_point_at_dist(self, stroke_id:int, dist:float, precision:float) -> bool, x_point:float, y_point:float, slope:float, valid:bool

- **stroke_get_points**`(*args, **kwargs)`
  - stroke_get_points(self, stroke_id:int) -> Gimp.PathStrokeType, controlpoints:list, closed:bool

- **stroke_interpolate**`(*args, **kwargs)`
  - stroke_interpolate(self, stroke_id:int, precision:float) -> list, closed:bool

- **stroke_new_from_points**`(*args, **kwargs)`
  - stroke_new_from_points(self, type:Gimp.PathStrokeType, controlpoints:list, closed:bool) -> int

- **stroke_reverse**`(*args, **kwargs)`
  - stroke_reverse(self, stroke_id:int) -> bool

- **stroke_rotate**`(*args, **kwargs)`
  - stroke_rotate(self, stroke_id:int, center_x:float, center_y:float, angle:float) -> bool

- **stroke_scale**`(*args, **kwargs)`
  - stroke_scale(self, stroke_id:int, scale_x:float, scale_y:float) -> bool

- **stroke_translate**`(*args, **kwargs)`
  - stroke_translate(self, stroke_id:int, off_x:float, off_y:float) -> bool

- **thaw_notify**`(*args, **kwargs)`
  - thaw_notify(self)

- **to_str**`(*args, **kwargs)`
  - to_str(path:list) -> str

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

- **unref**`(self, *args, **kargs)`
  - documentation unavailable

- **watch_closure**`(self, *args, **kargs)`
  - documentation unavailable

- **weak_ref**`(bound native)`
  - documentation unavailable


