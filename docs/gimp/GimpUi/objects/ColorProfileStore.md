---
layout: default
title: GimpUi.objects
---
# GimpUi.objects

## ColorProfileStore
- :Constructors:<br /><br />::<br /><br />    ColorProfileStore(**properties)<br />    new(history:Gio.File) -> Gtk.ListStore

### Runtime attributes

- **g_type_instance**
- **parent**
- **priv**
- **props**
- **qdata**
- **ref_count**

### Runtime functions
- **add_child**`(*args, **kwargs)`
  - add_child(self, builder:Gtk.Builder, child:GObject.Object, type:str=None)

- **add_file**`(*args, **kwargs)`
  - add_file(self, file:Gio.File, label:str)

- **append**`(self, row=None)`
  - append(self) -> iter:Gtk.TreeIter

- **bind_property**`(bound native)`
  - documentation unavailable

- **bind_property_full**`(self, *args, **kargs)`
  - documentation unavailable

- **chain**`(bound native)`
  - documentation unavailable

- **clear**`(*args, **kwargs)`
  - clear(self)

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

- **construct_child**`(*args, **kwargs)`
  - construct_child(self, builder:Gtk.Builder, name:str) -> GObject.Object

- **custom_finished**`(*args, **kwargs)`
  - custom_finished(self, builder:Gtk.Builder, child:GObject.Object=None, tagname:str, data=None)

- **custom_tag_end**`(*args, **kwargs)`
  - custom_tag_end(self, builder:Gtk.Builder, child:GObject.Object=None, tagname:str, data=None)

- **custom_tag_start**`(*args, **kwargs)`
  - custom_tag_start(self, builder:Gtk.Builder, child:GObject.Object=None, tagname:str) -> bool, parser:GLib.MarkupParser, data

- **disconnect**`(*args, **kwargs)`
  - signal_handler_disconnect(instance:GObject.Object, handler_id:int)

- **disconnect_by_func**`(bound native)`
  - documentation unavailable

- **drag_data_delete**`(*args, **kwargs)`
  - drag_data_delete(self, path:Gtk.TreePath) -> bool

- **drag_data_get**`(*args, **kwargs)`
  - drag_data_get(self, path:Gtk.TreePath, selection_data:Gtk.SelectionData) -> bool

- **drag_data_received**`(*args, **kwargs)`
  - drag_data_received(self, dest:Gtk.TreePath, selection_data:Gtk.SelectionData) -> bool

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

- **get_internal_child**`(*args, **kwargs)`
  - get_internal_child(self, builder:Gtk.Builder, childname:str) -> GObject.Object

- **get_iter**`(self, path)`
  - get_iter(self, path:Gtk.TreePath) -> bool, iter:Gtk.TreeIter

- **get_iter_first**`(*args, **kwargs)`
  - get_iter_first(self) -> bool, iter:Gtk.TreeIter

- **get_iter_from_string**`(*args, **kwargs)`
  - get_iter_from_string(self, path_string:str) -> bool, iter:Gtk.TreeIter

- **get_n_columns**`(*args, **kwargs)`
  - get_n_columns(self) -> int

- **get_name**`(*args, **kwargs)`
  - get_name(self) -> str

- **get_path**`(*args, **kwargs)`
  - get_path(self, iter:Gtk.TreeIter) -> Gtk.TreePath

- **get_properties**`(bound native)`
  - documentation unavailable

- **get_property**`(bound native)`
  - documentation unavailable

- **get_qdata**`(self, *args, **kargs)`
  - documentation unavailable

- **get_sort_column_id**`(*args, **kwargs)`
  - get_sort_column_id(self) -> bool, sort_column_id:int, order:Gtk.SortType

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

- **has_default_sort_func**`(*args, **kwargs)`
  - has_default_sort_func(self) -> bool

- **insert**`(self, position, row=None)`
  - insert(self, position:int) -> iter:Gtk.TreeIter

- **insert_after**`(self, sibling, row=None)`
  - insert_after(self, sibling:Gtk.TreeIter=None) -> iter:Gtk.TreeIter

- **insert_before**`(self, sibling, row=None)`
  - insert_before(self, sibling:Gtk.TreeIter=None) -> iter:Gtk.TreeIter

- **insert_with_values**`(*args, **kwargs)`
  - insert_with_valuesv(self, position:int, columns:list, values:list) -> iter:Gtk.TreeIter

- **insert_with_valuesv**`(*args, **kwargs)`
  - insert_with_valuesv(self, position:int, columns:list, values:list) -> iter:Gtk.TreeIter

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

- **iter_is_valid**`(*args, **kwargs)`
  - iter_is_valid(self, iter:Gtk.TreeIter) -> bool

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

- **move_after**`(*args, **kwargs)`
  - move_after(self, iter:Gtk.TreeIter, position:Gtk.TreeIter=None)

- **move_before**`(*args, **kwargs)`
  - move_before(self, iter:Gtk.TreeIter, position:Gtk.TreeIter=None)

- **new**`(*args, **kwargs)`
  - new(history:Gio.File) -> Gtk.ListStore

- **newv**`(*args, **kwargs)`
  - newv(object_type:GType, parameters:list) -> GObject.Object

- **notify**`(*args, **kwargs)`
  - notify(self, property_name:str)

- **notify_by_pspec**`(self, *args, **kargs)`
  - documentation unavailable

- **override_property**`(*args, **kwargs)`
  - override_property(self, property_id:int, name:str)

- **parser_finished**`(*args, **kwargs)`
  - parser_finished(self, builder:Gtk.Builder)

- **prepend**`(self, row=None)`
  - prepend(self) -> iter:Gtk.TreeIter

- **ref**`(self, *args, **kargs)`
  - documentation unavailable

- **ref_node**`(*args, **kwargs)`
  - ref_node(self, iter:Gtk.TreeIter)

- **ref_sink**`(self, *args, **kargs)`
  - documentation unavailable

- **remove**`(*args, **kwargs)`
  - remove(self, iter:Gtk.TreeIter) -> bool

- **reorder**`(*args, **kwargs)`
  - reorder(self, new_order:list)

- **replace_data**`(self, *args, **kargs)`
  - documentation unavailable

- **replace_qdata**`(self, *args, **kargs)`
  - documentation unavailable

- **row_changed**`(self, path, iter)`
  - row_changed(self, path:Gtk.TreePath, iter:Gtk.TreeIter)

- **row_deleted**`(self, path)`
  - row_deleted(self, path:Gtk.TreePath)

- **row_draggable**`(*args, **kwargs)`
  - row_draggable(self, path:Gtk.TreePath) -> bool

- **row_drop_possible**`(*args, **kwargs)`
  - row_drop_possible(self, dest_path:Gtk.TreePath, selection_data:Gtk.SelectionData) -> bool

- **row_has_child_toggled**`(self, path, iter)`
  - row_has_child_toggled(self, path:Gtk.TreePath, iter:Gtk.TreeIter)

- **row_inserted**`(self, path, iter)`
  - row_inserted(self, path:Gtk.TreePath, iter:Gtk.TreeIter)

- **rows_reordered**`(self, path, iter, new_order)`
  - rows_reordered(self, path:Gtk.TreePath, iter:Gtk.TreeIter=None, new_order:list)

- **run_dispose**`(*args, **kwargs)`
  - run_dispose(self)

- **set**`(self, treeiter, *args)`
  - set(self, iter:Gtk.TreeIter, columns:list, values:list)

- **set_buildable_property**`(*args, **kwargs)`
  - set_buildable_property(self, builder:Gtk.Builder, name:str, value:GObject.Value)

- **set_column_types**`(*args, **kwargs)`
  - set_column_types(self, types:list)

- **set_data**`(self, *args, **kargs)`
  - documentation unavailable

- **set_default_sort_func**`(self, sort_func, user_data=None)`
  - set_default_sort_func(self, sort_func:Gtk.TreeIterCompareFunc, user_data=None)

- **set_name**`(*args, **kwargs)`
  - set_name(self, name:str)

- **set_properties**`(bound native)`
  - documentation unavailable

- **set_property**`(bound native)`
  - documentation unavailable

- **set_row**`(self, treeiter, row)`
  - documentation unavailable

- **set_sort_column_id**`(*args, **kwargs)`
  - set_sort_column_id(self, sort_column_id:int, order:Gtk.SortType)

- **set_sort_func**`(self, sort_column_id, sort_func, user_data=None)`
  - set_sort_func(self, sort_column_id:int, sort_func:Gtk.TreeIterCompareFunc, user_data=None)

- **set_value**`(self, treeiter, column, value)`
  - set_value(self, iter:Gtk.TreeIter, column:int, value:GObject.Value)

- **sort_column_changed**`(*args, **kwargs)`
  - sort_column_changed(self)

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

- **swap**`(*args, **kwargs)`
  - swap(self, a:Gtk.TreeIter, b:Gtk.TreeIter)

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


