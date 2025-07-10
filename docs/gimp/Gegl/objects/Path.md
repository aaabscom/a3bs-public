---
layout: default
title: Gegl.objects
---
# Gegl.objects

## Path
- :Constructors:<br /><br />::<br /><br />    Path(**properties)<br />    new() -> Gegl.Path<br />    new_from_string(instructions:str) -> Gegl.Path

### Runtime attributes

- **g_type_instance**
- **parent_instance**
- **props**
- **qdata**
- **ref_count**

### Runtime functions
- **add_type**`(*args, **kwargs)`
  - add_type(type:int, items:int, description:str)

- **bind_property**`(bound native)`
  - documentation unavailable

- **bind_property_full**`(self, *args, **kargs)`
  - documentation unavailable

- **calc**`(*args, **kwargs)`
  - calc(self, pos:float) -> bool, x:float, y:float

- **calc_y_for_x**`(*args, **kwargs)`
  - calc_y_for_x(self, x:float) -> int, y:float

- **chain**`(bound native)`
  - documentation unavailable

- **clear**`(*args, **kwargs)`
  - clear(self)

- **closest_point**`(*args, **kwargs)`
  - closest_point(self, x:float, y:float) -> float, on_path_x:float, on_path_y:float, node_pos_before:int

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

- **dirty**`(*args, **kwargs)`
  - dirty(self)

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

- **foreach**`(*args, **kwargs)`
  - foreach(self, each_item:Gegl.NodeFunction, user_data=None)

- **foreach_flat**`(*args, **kwargs)`
  - foreach_flat(self, each_item:Gegl.NodeFunction, user_data=None)

- **freeze**`(*args, **kwargs)`
  - freeze(self)

- **freeze_notify**`(self)`
  - Freezes the object's property-changed notification queue.<br /><br />:returns:<br />    A context manager which optionally can be used to<br />    automatically thaw notifications.<br /><br />This will freeze the object so that "notify" signals are blocked until<br />the thaw_notify() method is called.<br /><br />.. code-block:: python<br /><br />    with obj.freeze_notify():<br />        pass

- **get_bounds**`(*args, **kwargs)`
  - get_bounds(self) -> min_x:float, max_x:float, min_y:float, max_y:float

- **get_data**`(self, *args, **kargs)`
  - documentation unavailable

- **get_length**`(*args, **kwargs)`
  - get_length(self) -> float

- **get_matrix**`(*args, **kwargs)`
  - get_matrix(self) -> matrix:Gegl.Matrix3

- **get_n_nodes**`(*args, **kwargs)`
  - get_n_nodes(self) -> int

- **get_node**`(*args, **kwargs)`
  - get_node(self, index:int) -> bool, node:Gegl.PathItem

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

- **insert_node**`(*args, **kwargs)`
  - insert_node(self, pos:int, node:Gegl.PathItem)

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

- **is_empty**`(*args, **kwargs)`
  - is_empty(self) -> bool

- **is_floating**`(*args, **kwargs)`
  - is_floating(self) -> bool

- **list_properties**`(*args, **kwargs)`
  - list_properties(self) -> list

- **new**`(*args, **kwargs)`
  - new() -> Gegl.Path

- **new_from_string**`(*args, **kwargs)`
  - new_from_string(instructions:str) -> Gegl.Path

- **newv**`(*args, **kwargs)`
  - newv(object_type:GType, parameters:list) -> GObject.Object

- **notify**`(*args, **kwargs)`
  - notify(self, property_name:str)

- **notify_by_pspec**`(self, *args, **kargs)`
  - documentation unavailable

- **override_property**`(*args, **kwargs)`
  - override_property(self, property_id:int, name:str)

- **parse_string**`(*args, **kwargs)`
  - parse_string(self, instructions:str)

- **ref**`(self, *args, **kargs)`
  - documentation unavailable

- **ref_sink**`(self, *args, **kargs)`
  - documentation unavailable

- **remove_node**`(*args, **kwargs)`
  - remove_node(self, pos:int)

- **replace_data**`(self, *args, **kargs)`
  - documentation unavailable

- **replace_node**`(*args, **kwargs)`
  - replace_node(self, pos:int, node:Gegl.PathItem)

- **replace_qdata**`(self, *args, **kargs)`
  - documentation unavailable

- **run_dispose**`(*args, **kwargs)`
  - run_dispose(self)

- **set_data**`(self, *args, **kargs)`
  - documentation unavailable

- **set_matrix**`(*args, **kwargs)`
  - set_matrix(self, matrix:Gegl.Matrix3)

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

- **thaw**`(*args, **kwargs)`
  - thaw(self)

- **thaw_notify**`(*args, **kwargs)`
  - thaw_notify(self)

- **to_string**`(*args, **kwargs)`
  - to_string(self) -> str

- **unref**`(self, *args, **kargs)`
  - documentation unavailable

- **watch_closure**`(self, *args, **kargs)`
  - documentation unavailable

- **weak_ref**`(bound native)`
  - documentation unavailable


