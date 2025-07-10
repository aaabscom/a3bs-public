---
layout: default
title: Gegl.objects
---
# Gegl.objects

## Node
- :Constructors:<br /><br />::<br /><br />    Node(**properties)<br />    new() -> Gegl.Node<br />    new_from_file(path:str) -> Gegl.Node<br />    new_from_serialized(chaindata:str, path_root:str) -> Gegl.Node<br />    new_from_xml(xmldata:str, path_root:str) -> Gegl.Node

### Runtime attributes

- **g_type_instance**
- **props**
- **qdata**
- **ref_count**

### Runtime functions
- **add_child**`(*args, **kwargs)`
  - add_child(self, child:Gegl.Node) -> Gegl.Node

- **bind_property**`(bound native)`
  - documentation unavailable

- **bind_property_full**`(self, *args, **kargs)`
  - documentation unavailable

- **blit_buffer**`(*args, **kwargs)`
  - blit_buffer(self, buffer:Gegl.Buffer=None, roi:Gegl.Rectangle=None, level:int, abyss_policy:Gegl.AbyssPolicy)

- **chain**`(bound native)`
  - documentation unavailable

- **compat_control**`(self, *args, **kargs)`
  - documentation unavailable

- **connect**`(*args, **kwargs)`
  - connect(self, a_pad_name:str, b:Gegl.Node, b_pad_name:str) -> bool

- **connect_after**`(bound native)`
  - documentation unavailable

- **connect_data**`(self, detailed_signal, handler, *data, **kwargs)`
  - Connect a callback to the given signal with optional user data.<br /><br />:param str detailed_signal:<br />    A detailed signal to connect to.<br />:param callable handler:<br />    Callback handler to connect to the signal.<br />:param *data:<br />    Variable data which is passed through to the signal handler.<br />:param GObject.ConnectFlags connect_flags:<br />    Flags used for connection options.<br />:returns:<br />    A signal id which can be used with disconnect.

- **connect_from**`(*args, **kwargs)`
  - connect_from(self, input_pad_name:str, source:Gegl.Node, output_pad_name:str) -> bool

- **connect_object**`(bound native)`
  - documentation unavailable

- **connect_object_after**`(bound native)`
  - documentation unavailable

- **connect_to**`(*args, **kwargs)`
  - connect_to(self, output_pad_name:str, sink:Gegl.Node, input_pad_name:str) -> bool

- **create_child**`(*args, **kwargs)`
  - create_child(self, operation:str) -> Gegl.Node

- **detect**`(*args, **kwargs)`
  - detect(self, x:int, y:int) -> Gegl.Node

- **disconnect**`(*args, **kwargs)`
  - disconnect(self, input_pad:str) -> bool

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

- **freeze_notify**`(self)`
  - Freezes the object's property-changed notification queue.<br /><br />:returns:<br />    A context manager which optionally can be used to<br />    automatically thaw notifications.<br /><br />This will freeze the object so that "notify" signals are blocked until<br />the thaw_notify() method is called.<br /><br />.. code-block:: python<br /><br />    with obj.freeze_notify():<br />        pass

- **get_bounding_box**`(*args, **kwargs)`
  - get_bounding_box(self) -> Gegl.Rectangle

- **get_children**`(*args, **kwargs)`
  - get_children(self) -> list

- **get_consumers**`(*args, **kwargs)`
  - get_consumers(self, output_pad:str) -> int, nodes:list, pads:list

- **get_data**`(self, *args, **kargs)`
  - documentation unavailable

- **get_gegl_operation**`(*args, **kwargs)`
  - get_gegl_operation(self) -> Gegl.Operation or None

- **get_input_proxy**`(*args, **kwargs)`
  - get_input_proxy(self, pad_name:str) -> Gegl.Node

- **get_operation**`(*args, **kwargs)`
  - get_operation(self) -> str

- **get_output_proxy**`(*args, **kwargs)`
  - get_output_proxy(self, pad_name:str) -> Gegl.Node

- **get_pad_description**`(*args, **kwargs)`
  - get_pad_description(self, pad_name:str) -> str

- **get_pad_label**`(*args, **kwargs)`
  - get_pad_label(self, pad_name:str) -> str

- **get_parent**`(*args, **kwargs)`
  - get_parent(self) -> Gegl.Node

- **get_passthrough**`(*args, **kwargs)`
  - get_passthrough(self) -> bool

- **get_producer**`(*args, **kwargs)`
  - get_producer(self, input_pad_name:str, output_pad_name:str=None) -> Gegl.Node

- **get_properties**`(bound native)`
  - documentation unavailable

- **get_property**`(*args, **kwargs)`
  - get_property(self, property_name:str) -> GObject.Value

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

- **has_pad**`(*args, **kwargs)`
  - has_pad(self, pad_name:str) -> bool

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

- **is_graph**`(*args, **kwargs)`
  - is_graph(self) -> bool

- **link**`(*args, **kwargs)`
  - link(self, sink:Gegl.Node)

- **list_input_pads**`(*args, **kwargs)`
  - list_input_pads(self) -> list

- **list_output_pads**`(*args, **kwargs)`
  - list_output_pads(self) -> list

- **list_properties**`(*args, **kwargs)`
  - list_properties(self) -> list

- **new**`(*args, **kwargs)`
  - new() -> Gegl.Node

- **new_from_file**`(*args, **kwargs)`
  - new_from_file(path:str) -> Gegl.Node

- **new_from_serialized**`(*args, **kwargs)`
  - new_from_serialized(chaindata:str, path_root:str) -> Gegl.Node

- **new_from_xml**`(*args, **kwargs)`
  - new_from_xml(xmldata:str, path_root:str) -> Gegl.Node

- **new_processor**`(*args, **kwargs)`
  - new_processor(self, rectangle:Gegl.Rectangle) -> Gegl.Processor

- **newv**`(*args, **kwargs)`
  - newv(object_type:GType, parameters:list) -> GObject.Object

- **notify**`(*args, **kwargs)`
  - notify(self, property_name:str)

- **notify_by_pspec**`(self, *args, **kargs)`
  - documentation unavailable

- **override_property**`(*args, **kwargs)`
  - override_property(self, property_id:int, name:str)

- **process**`(*args, **kwargs)`
  - process(self)

- **progress**`(*args, **kwargs)`
  - progress(self, progress:float, message:str)

- **ref**`(self, *args, **kargs)`
  - documentation unavailable

- **ref_sink**`(self, *args, **kargs)`
  - documentation unavailable

- **remove_child**`(*args, **kwargs)`
  - remove_child(self, child:Gegl.Node) -> Gegl.Node

- **replace_data**`(self, *args, **kargs)`
  - documentation unavailable

- **replace_qdata**`(self, *args, **kargs)`
  - documentation unavailable

- **run_dispose**`(*args, **kwargs)`
  - run_dispose(self)

- **set_data**`(self, *args, **kargs)`
  - documentation unavailable

- **set_enum_as_string**`(*args, **kwargs)`
  - set_enum_as_string(self, key:str, value:str)

- **set_passthrough**`(*args, **kwargs)`
  - set_passthrough(self, passthrough:bool)

- **set_properties**`(bound native)`
  - documentation unavailable

- **set_property**`(*args, **kwargs)`
  - set_property(self, property_name:str, value:GObject.Value)

- **set_time**`(*args, **kwargs)`
  - set_time(self, time:float)

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

- **to_xml**`(*args, **kwargs)`
  - to_xml(self, path_root:str) -> str

- **to_xml_full**`(*args, **kwargs)`
  - to_xml_full(self, tail:Gegl.Node=None, path_root:str) -> str

- **unref**`(self, *args, **kargs)`
  - documentation unavailable

- **watch_closure**`(self, *args, **kargs)`
  - documentation unavailable

- **weak_ref**`(bound native)`
  - documentation unavailable


