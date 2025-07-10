---
layout: default
title: GimpUi.objects
---
# GimpUi.objects

## CellRendererToggle
- :Constructors:<br /><br />::<br /><br />    CellRendererToggle(**properties)<br />    new(icon_name:str) -> Gtk.CellRenderer

### Runtime attributes

- **g_type_instance**
- **parent**
- **parent_instance**
- **priv**
- **props**
- **qdata**
- **ref_count**

### Runtime functions
- **activate**`(*args, **kwargs)`
  - activate(self, event:Gdk.Event, widget:Gtk.Widget, path:str, background_area:Gdk.Rectangle, cell_area:Gdk.Rectangle, flags:Gtk.CellRendererState) -> bool

- **bind_property**`(bound native)`
  - documentation unavailable

- **bind_property_full**`(self, *args, **kargs)`
  - documentation unavailable

- **chain**`(bound native)`
  - documentation unavailable

- **clicked**`(*args, **kwargs)`
  - clicked(self, path:str, state:Gdk.ModifierType)

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

- **do_activate**`(bound native)`
  - activate(self, event:Gdk.Event, widget:Gtk.Widget, path:str, background_area:Gdk.Rectangle, cell_area:Gdk.Rectangle, flags:Gtk.CellRendererState) -> bool

- **do_editing_canceled**`(bound native)`
  - editing_canceled(self)

- **do_editing_started**`(bound native)`
  - editing_started(self, editable:Gtk.CellEditable, path:str)

- **do_get_aligned_area**`(bound native)`
  - get_aligned_area(self, widget:Gtk.Widget, flags:Gtk.CellRendererState, cell_area:Gdk.Rectangle) -> aligned_area:Gdk.Rectangle

- **do_get_preferred_height**`(bound native)`
  - get_preferred_height(self, widget:Gtk.Widget) -> minimum_size:int, natural_size:int

- **do_get_preferred_height_for_width**`(bound native)`
  - get_preferred_height_for_width(self, widget:Gtk.Widget, width:int) -> minimum_height:int, natural_height:int

- **do_get_preferred_width**`(bound native)`
  - get_preferred_width(self, widget:Gtk.Widget) -> minimum_size:int, natural_size:int

- **do_get_preferred_width_for_height**`(bound native)`
  - get_preferred_width_for_height(self, widget:Gtk.Widget, height:int) -> minimum_width:int, natural_width:int

- **do_get_request_mode**`(bound native)`
  - get_request_mode(self) -> Gtk.SizeRequestMode

- **do_get_size**`(bound native)`
  - get_size(self, widget:Gtk.Widget, cell_area:Gdk.Rectangle=None) -> x_offset:int, y_offset:int, width:int, height:int

- **do_render**`(bound native)`
  - render(self, cr:cairo.Context, widget:Gtk.Widget, background_area:Gdk.Rectangle, cell_area:Gdk.Rectangle, flags:Gtk.CellRendererState)

- **do_start_editing**`(bound native)`
  - start_editing(self, event:Gdk.Event=None, widget:Gtk.Widget, path:str, background_area:Gdk.Rectangle, cell_area:Gdk.Rectangle, flags:Gtk.CellRendererState) -> Gtk.CellEditable or None

- **do_toggled**`(bound native)`
  - toggled(self, path:str)

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

- **get_activatable**`(*args, **kwargs)`
  - get_activatable(self) -> bool

- **get_active**`(*args, **kwargs)`
  - get_active(self) -> bool

- **get_aligned_area**`(*args, **kwargs)`
  - get_aligned_area(self, widget:Gtk.Widget, flags:Gtk.CellRendererState, cell_area:Gdk.Rectangle) -> aligned_area:Gdk.Rectangle

- **get_alignment**`(*args, **kwargs)`
  - get_alignment(self) -> xalign:float, yalign:float

- **get_data**`(self, *args, **kargs)`
  - documentation unavailable

- **get_fixed_size**`(*args, **kwargs)`
  - get_fixed_size(self) -> width:int, height:int

- **get_padding**`(*args, **kwargs)`
  - get_padding(self) -> xpad:int, ypad:int

- **get_preferred_height**`(*args, **kwargs)`
  - get_preferred_height(self, widget:Gtk.Widget) -> minimum_size:int, natural_size:int

- **get_preferred_height_for_width**`(*args, **kwargs)`
  - get_preferred_height_for_width(self, widget:Gtk.Widget, width:int) -> minimum_height:int, natural_height:int

- **get_preferred_size**`(*args, **kwargs)`
  - get_preferred_size(self, widget:Gtk.Widget) -> minimum_size:Gtk.Requisition, natural_size:Gtk.Requisition

- **get_preferred_width**`(*args, **kwargs)`
  - get_preferred_width(self, widget:Gtk.Widget) -> minimum_size:int, natural_size:int

- **get_preferred_width_for_height**`(*args, **kwargs)`
  - get_preferred_width_for_height(self, widget:Gtk.Widget, height:int) -> minimum_width:int, natural_width:int

- **get_properties**`(bound native)`
  - documentation unavailable

- **get_property**`(bound native)`
  - documentation unavailable

- **get_qdata**`(self, *args, **kargs)`
  - documentation unavailable

- **get_radio**`(*args, **kwargs)`
  - get_radio(self) -> bool

- **get_request_mode**`(*args, **kwargs)`
  - get_request_mode(self) -> Gtk.SizeRequestMode

- **get_sensitive**`(*args, **kwargs)`
  - get_sensitive(self) -> bool

- **get_size**`(*args, **kwargs)`
  - get_size(self, widget:Gtk.Widget, cell_area:Gdk.Rectangle=None) -> x_offset:int, y_offset:int, width:int, height:int

- **get_state**`(*args, **kwargs)`
  - get_state(self, widget:Gtk.Widget=None, cell_state:Gtk.CellRendererState) -> Gtk.StateFlags

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

- **is_activatable**`(*args, **kwargs)`
  - is_activatable(self) -> bool

- **is_floating**`(*args, **kwargs)`
  - is_floating(self) -> bool

- **list_properties**`(*args, **kwargs)`
  - list_properties(self) -> list

- **new**`(*args, **kwargs)`
  - new(icon_name:str) -> Gtk.CellRenderer

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

- **render**`(*args, **kwargs)`
  - render(self, cr:cairo.Context, widget:Gtk.Widget, background_area:Gdk.Rectangle, cell_area:Gdk.Rectangle, flags:Gtk.CellRendererState)

- **replace_data**`(self, *args, **kargs)`
  - documentation unavailable

- **replace_qdata**`(self, *args, **kargs)`
  - documentation unavailable

- **run_dispose**`(*args, **kwargs)`
  - run_dispose(self)

- **set_accessible_type**`(*args, **kwargs)`
  - set_accessible_type(self, type:GType)

- **set_activatable**`(*args, **kwargs)`
  - set_activatable(self, setting:bool)

- **set_active**`(*args, **kwargs)`
  - set_active(self, setting:bool)

- **set_alignment**`(*args, **kwargs)`
  - set_alignment(self, xalign:float, yalign:float)

- **set_data**`(self, *args, **kargs)`
  - documentation unavailable

- **set_fixed_size**`(*args, **kwargs)`
  - set_fixed_size(self, width:int, height:int)

- **set_padding**`(*args, **kwargs)`
  - set_padding(self, xpad:int, ypad:int)

- **set_properties**`(bound native)`
  - documentation unavailable

- **set_property**`(bound native)`
  - documentation unavailable

- **set_radio**`(*args, **kwargs)`
  - set_radio(self, radio:bool)

- **set_sensitive**`(*args, **kwargs)`
  - set_sensitive(self, sensitive:bool)

- **set_visible**`(*args, **kwargs)`
  - set_visible(self, visible:bool)

- **start_editing**`(*args, **kwargs)`
  - start_editing(self, event:Gdk.Event=None, widget:Gtk.Widget, path:str, background_area:Gdk.Rectangle, cell_area:Gdk.Rectangle, flags:Gtk.CellRendererState) -> Gtk.CellEditable or None

- **steal_data**`(self, *args, **kargs)`
  - documentation unavailable

- **steal_qdata**`(self, *args, **kargs)`
  - documentation unavailable

- **stop_editing**`(*args, **kwargs)`
  - stop_editing(self, canceled:bool)

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


