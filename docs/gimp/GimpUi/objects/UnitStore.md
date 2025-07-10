---
layout: default
title: GimpUi.objects
---
# GimpUi.objects

## UnitStore
- :Constructors:<br /><br />::<br /><br />    UnitStore(**properties)<br />    new(num_values:int) -> GimpUi.UnitStore

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

- **disconnect**`(*args, **kwargs)`
  - signal_handler_disconnect(instance:GObject.Object, handler_id:int)

- **disconnect_by_func**`(bound native)`
  - documentation unavailable

- **emit**`(bound native)`
  - documentation unavailable

- **emit_stop_by_name**`(self, detailed_signal)`
  - Deprecated, please use stop_emission_by_name.

- **filter_new**`(*args, **kwargs)`
  - filter_new(self, root:Gtk.TreePath=None) -> Gtk.TreeModel

- **find_property**`(*args, **kwargs)`
  - find_property(self, property_name:str) -> GObject.ParamSpec

- **force_floating**`(self, *args, **kargs)`
  - documentation unavailable

- **foreach**`(*args, **kwargs)`
  - foreach(self, func:Gtk.TreeModelForeachFunc, user_data=None)

- **freeze_notify**`(self)`
  - Freezes the object's property-changed notification queue.<br /><br />:returns:<br />    A context manager which optionally can be used to<br />    automatically thaw notifications.<br /><br />This will freeze the object so that "notify" signals are blocked until<br />the thaw_notify() method is called.<br /><br />.. code-block:: python<br /><br />    with obj.freeze_notify():<br />        pass

- **get**`(self, treeiter, *columns)`
  - documentation unavailable

- **get_column_type**`(*args, **kwargs)`
  - get_column_type(self, index_:int) -> GType

- **get_data**`(self, *args, **kargs)`
  - documentation unavailable

- **get_flags**`(*args, **kwargs)`
  - get_flags(self) -> Gtk.TreeModelFlags

- **get_has_percent**`(*args, **kwargs)`
  - get_has_percent(self) -> bool

- **get_has_pixels**`(*args, **kwargs)`
  - get_has_pixels(self) -> bool

- **get_iter**`(self, path)`
  - get_iter(self, path:Gtk.TreePath) -> bool, iter:Gtk.TreeIter

- **get_iter_first**`(*args, **kwargs)`
  - get_iter_first(self) -> bool, iter:Gtk.TreeIter

- **get_iter_from_string**`(*args, **kwargs)`
  - get_iter_from_string(self, path_string:str) -> bool, iter:Gtk.TreeIter

- **get_n_columns**`(*args, **kwargs)`
  - get_n_columns(self) -> int

- **get_nth_value**`(*args, **kwargs)`
  - get_nth_value(self, unit:Gimp.Unit, index:int) -> float

- **get_path**`(*args, **kwargs)`
  - get_path(self, iter:Gtk.TreeIter) -> Gtk.TreePath

- **get_properties**`(bound native)`
  - documentation unavailable

- **get_property**`(bound native)`
  - documentation unavailable

- **get_qdata**`(self, *args, **kargs)`
  - documentation unavailable

- **get_string_from_iter**`(*args, **kwargs)`
  - get_string_from_iter(self, iter:Gtk.TreeIter) -> str

- **get_value**`(*args, **kwargs)`
  - get_value(self, iter:Gtk.TreeIter, column:int) -> value:GObject.Value

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

- **iter_children**`(*args, **kwargs)`
  - iter_children(self, parent:Gtk.TreeIter=None) -> bool, iter:Gtk.TreeIter

- **iter_has_child**`(*args, **kwargs)`
  - iter_has_child(self, iter:Gtk.TreeIter) -> bool

- **iter_n_children**`(*args, **kwargs)`
  - iter_n_children(self, iter:Gtk.TreeIter=None) -> int

- **iter_next**`(self, aiter)`
  - iter_next(self, iter:Gtk.TreeIter) -> bool

- **iter_nth_child**`(*args, **kwargs)`
  - iter_nth_child(self, parent:Gtk.TreeIter=None, n:int) -> bool, iter:Gtk.TreeIter

- **iter_parent**`(*args, **kwargs)`
  - iter_parent(self, child:Gtk.TreeIter) -> bool, iter:Gtk.TreeIter

- **iter_previous**`(self, aiter)`
  - iter_previous(self, iter:Gtk.TreeIter) -> bool

- **list_properties**`(*args, **kwargs)`
  - list_properties(self) -> list

- **new**`(*args, **kwargs)`
  - new(num_values:int) -> GimpUi.UnitStore

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

- **ref_node**`(*args, **kwargs)`
  - ref_node(self, iter:Gtk.TreeIter)

- **ref_sink**`(self, *args, **kargs)`
  - documentation unavailable

- **replace_data**`(self, *args, **kargs)`
  - documentation unavailable

- **replace_qdata**`(self, *args, **kargs)`
  - documentation unavailable

- **row_changed**`(self, path, iter)`
  - row_changed(self, path:Gtk.TreePath, iter:Gtk.TreeIter)

- **row_deleted**`(self, path)`
  - row_deleted(self, path:Gtk.TreePath)

- **row_has_child_toggled**`(self, path, iter)`
  - row_has_child_toggled(self, path:Gtk.TreePath, iter:Gtk.TreeIter)

- **row_inserted**`(self, path, iter)`
  - row_inserted(self, path:Gtk.TreePath, iter:Gtk.TreeIter)

- **rows_reordered**`(self, path, iter, new_order)`
  - rows_reordered(self, path:Gtk.TreePath, iter:Gtk.TreeIter=None, new_order:list)

- **run_dispose**`(*args, **kwargs)`
  - run_dispose(self)

- **set_data**`(self, *args, **kargs)`
  - documentation unavailable

- **set_has_percent**`(*args, **kwargs)`
  - set_has_percent(self, has_percent:bool)

- **set_has_pixels**`(*args, **kwargs)`
  - set_has_pixels(self, has_pixels:bool)

- **set_pixel_value**`(*args, **kwargs)`
  - set_pixel_value(self, index:int, value:float)

- **set_properties**`(bound native)`
  - documentation unavailable

- **set_property**`(bound native)`
  - documentation unavailable

- **set_resolution**`(*args, **kwargs)`
  - set_resolution(self, index:int, resolution:float)

- **set_row**`(self, treeiter, row)`
  - documentation unavailable

- **sort_new_with_model**`(self)`
  - documentation unavailable

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

- **unref_node**`(*args, **kwargs)`
  - unref_node(self, iter:Gtk.TreeIter)

- **watch_closure**`(self, *args, **kargs)`
  - documentation unavailable

- **weak_ref**`(bound native)`
  - documentation unavailable


