---
layout: default
title: GimpUi.objects
---
# GimpUi.objects

## SpinScale
- :Constructors:<br /><br />::<br /><br />    SpinScale(**properties)<br />    new(adjustment:Gtk.Adjustment, label:str, digits:int) -> Gtk.Widget

### Runtime attributes

- **entry**
- **g_type_instance**
- **parent_instance**
- **priv**
- **props**
- **qdata**
- **ref_count**

### Runtime functions
- **activate**`(*args, **kwargs)`
  - activate(self) -> bool

- **add_accelerator**`(*args, **kwargs)`
  - add_accelerator(self, accel_signal:str, accel_group:Gtk.AccelGroup, accel_key:int, accel_mods:Gdk.ModifierType, accel_flags:Gtk.AccelFlags)

- **add_child**`(*args, **kwargs)`
  - add_child(self, builder:Gtk.Builder, child:GObject.Object, type:str=None)

- **add_device_events**`(*args, **kwargs)`
  - add_device_events(self, device:Gdk.Device, events:Gdk.EventMask)

- **add_events**`(*args, **kwargs)`
  - add_events(self, events:int)

- **add_mnemonic_label**`(*args, **kwargs)`
  - add_mnemonic_label(self, label:Gtk.Widget)

- **add_tick_callback**`(*args, **kwargs)`
  - add_tick_callback(self, callback:Gtk.TickCallback, user_data=None) -> int

- **bind_property**`(bound native)`
  - documentation unavailable

- **bind_property_full**`(self, *args, **kargs)`
  - documentation unavailable

- **bind_template_callback_full**`(*args, **kwargs)`
  - bind_template_callback_full(self, callback_name:str, callback_symbol:GObject.Callback)

- **bind_template_child_full**`(*args, **kwargs)`
  - bind_template_child_full(self, name:str, internal_child:bool, struct_offset:int)

- **can_activate_accel**`(*args, **kwargs)`
  - can_activate_accel(self, signal_id:int) -> bool

- **chain**`(bound native)`
  - documentation unavailable

- **child_focus**`(*args, **kwargs)`
  - child_focus(self, direction:Gtk.DirectionType) -> bool

- **child_notify**`(*args, **kwargs)`
  - child_notify(self, child_property:str)

- **class_path**`(*args, **kwargs)`
  - class_path(self) -> path_length:int, path:str, path_reversed:str

- **compat_control**`(self, *args, **kargs)`
  - documentation unavailable

- **compute_expand**`(*args, **kwargs)`
  - compute_expand(self, orientation:Gtk.Orientation) -> bool

- **configure**`(*args, **kwargs)`
  - configure(self, adjustment:Gtk.Adjustment=None, climb_rate:float, digits:int)

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

- **copy_clipboard**`(*args, **kwargs)`
  - copy_clipboard(self)

- **create_pango_context**`(*args, **kwargs)`
  - create_pango_context(self) -> Pango.Context

- **create_pango_layout**`(*args, **kwargs)`
  - create_pango_layout(self, text:str=None) -> Pango.Layout

- **custom_finished**`(*args, **kwargs)`
  - custom_finished(self, builder:Gtk.Builder, child:GObject.Object=None, tagname:str, data=None)

- **custom_tag_end**`(*args, **kwargs)`
  - custom_tag_end(self, builder:Gtk.Builder, child:GObject.Object=None, tagname:str, data=None)

- **custom_tag_start**`(*args, **kwargs)`
  - custom_tag_start(self, builder:Gtk.Builder, child:GObject.Object=None, tagname:str) -> bool, parser:GLib.MarkupParser, data

- **cut_clipboard**`(*args, **kwargs)`
  - cut_clipboard(self)

- **delete_selection**`(*args, **kwargs)`
  - delete_selection(self)

- **delete_text**`(*args, **kwargs)`
  - delete_text(self, start_pos:int, end_pos:int)

- **destroy**`(*args, **kwargs)`
  - destroy(self)

- **destroyed**`(*args, **kwargs)`
  - destroyed(self, widget_pointer:Gtk.Widget) -> widget_pointer:Gtk.Widget

- **device_is_shadowed**`(*args, **kwargs)`
  - device_is_shadowed(self, device:Gdk.Device) -> bool

- **disconnect**`(*args, **kwargs)`
  - signal_handler_disconnect(instance:GObject.Object, handler_id:int)

- **disconnect_by_func**`(bound native)`
  - documentation unavailable

- **do_activate**`(bound native)`
  - activate(self)

- **do_adjust_baseline_allocation**`(bound native)`
  - adjust_baseline_allocation(self, baseline:int)

- **do_adjust_baseline_request**`(bound native)`
  - adjust_baseline_request(self, minimum_baseline:int, natural_baseline:int)

- **do_adjust_size_allocation**`(bound native)`
  - adjust_size_allocation(self, orientation:Gtk.Orientation, minimum_size:int, natural_size:int, allocated_pos:int, allocated_size:int)

- **do_adjust_size_request**`(bound native)`
  - adjust_size_request(self, orientation:Gtk.Orientation, minimum_size:int, natural_size:int)

- **do_backspace**`(bound native)`
  - backspace(self)

- **do_button_press_event**`(bound native)`
  - button_press_event(self, event:Gdk.EventButton) -> bool

- **do_button_release_event**`(bound native)`
  - button_release_event(self, event:Gdk.EventButton) -> bool

- **do_can_activate_accel**`(bound native)`
  - can_activate_accel(self, signal_id:int) -> bool

- **do_change_value**`(bound native)`
  - change_value(self, scroll:Gtk.ScrollType)

- **do_child_notify**`(bound native)`
  - child_notify(self, child_property:GObject.ParamSpec)

- **do_composited_changed**`(bound native)`
  - composited_changed(self)

- **do_compute_expand**`(bound native)`
  - compute_expand(self, hexpand_p:bool, vexpand_p:bool)

- **do_configure_event**`(bound native)`
  - configure_event(self, event:Gdk.EventConfigure) -> bool

- **do_copy_clipboard**`(bound native)`
  - copy_clipboard(self)

- **do_cut_clipboard**`(bound native)`
  - cut_clipboard(self)

- **do_damage_event**`(bound native)`
  - damage_event(self, event:Gdk.EventExpose) -> bool

- **do_delete_event**`(bound native)`
  - delete_event(self, event:Gdk.EventAny) -> bool

- **do_delete_from_cursor**`(bound native)`
  - delete_from_cursor(self, type:Gtk.DeleteType, count:int)

- **do_destroy**`(bound native)`
  - destroy(self)

- **do_destroy_event**`(bound native)`
  - destroy_event(self, event:Gdk.EventAny) -> bool

- **do_direction_changed**`(bound native)`
  - direction_changed(self, previous_direction:Gtk.TextDirection)

- **do_dispatch_child_properties_changed**`(bound native)`
  - dispatch_child_properties_changed(self, n_pspecs:int, pspecs:GObject.ParamSpec)

- **do_drag_begin**`(bound native)`
  - drag_begin(self, context:Gdk.DragContext)

- **do_drag_data_delete**`(bound native)`
  - drag_data_delete(self, context:Gdk.DragContext)

- **do_drag_data_get**`(bound native)`
  - drag_data_get(self, context:Gdk.DragContext, selection_data:Gtk.SelectionData, info:int, time_:int)

- **do_drag_data_received**`(bound native)`
  - drag_data_received(self, context:Gdk.DragContext, x:int, y:int, selection_data:Gtk.SelectionData, info:int, time_:int)

- **do_drag_drop**`(bound native)`
  - drag_drop(self, context:Gdk.DragContext, x:int, y:int, time_:int) -> bool

- **do_drag_end**`(bound native)`
  - drag_end(self, context:Gdk.DragContext)

- **do_drag_failed**`(bound native)`
  - drag_failed(self, context:Gdk.DragContext, result:Gtk.DragResult) -> bool

- **do_drag_leave**`(bound native)`
  - drag_leave(self, context:Gdk.DragContext, time_:int)

- **do_drag_motion**`(bound native)`
  - drag_motion(self, context:Gdk.DragContext, x:int, y:int, time_:int) -> bool

- **do_draw**`(bound native)`
  - draw(self, cr:cairo.Context) -> bool

- **do_enter_notify_event**`(bound native)`
  - enter_notify_event(self, event:Gdk.EventCrossing) -> bool

- **do_event**`(bound native)`
  - event(self, event:Gdk.Event) -> bool

- **do_focus**`(bound native)`
  - focus(self, direction:Gtk.DirectionType) -> bool

- **do_focus_in_event**`(bound native)`
  - focus_in_event(self, event:Gdk.EventFocus) -> bool

- **do_focus_out_event**`(bound native)`
  - focus_out_event(self, event:Gdk.EventFocus) -> bool

- **do_get_accessible**`(bound native)`
  - get_accessible(self) -> Atk.Object

- **do_get_frame_size**`(bound native)`
  - get_frame_size(self, x:int, y:int, width:int, height:int)

- **do_get_preferred_height**`(bound native)`
  - get_preferred_height(self) -> minimum_height:int, natural_height:int

- **do_get_preferred_height_and_baseline_for_width**`(bound native)`
  - get_preferred_height_and_baseline_for_width(self, width:int) -> minimum_height:int, natural_height:int, minimum_baseline:int, natural_baseline:int

- **do_get_preferred_height_for_width**`(bound native)`
  - get_preferred_height_for_width(self, width:int) -> minimum_height:int, natural_height:int

- **do_get_preferred_width**`(bound native)`
  - get_preferred_width(self) -> minimum_width:int, natural_width:int

- **do_get_preferred_width_for_height**`(bound native)`
  - get_preferred_width_for_height(self, height:int) -> minimum_width:int, natural_width:int

- **do_get_request_mode**`(bound native)`
  - get_request_mode(self) -> Gtk.SizeRequestMode

- **do_get_text_area_size**`(bound native)`
  - get_text_area_size(self, x:int, y:int, width:int, height:int)

- **do_grab_broken_event**`(bound native)`
  - grab_broken_event(self, event:Gdk.EventGrabBroken) -> bool

- **do_grab_focus**`(bound native)`
  - grab_focus(self)

- **do_grab_notify**`(bound native)`
  - grab_notify(self, was_grabbed:bool)

- **do_hide**`(bound native)`
  - hide(self)

- **do_hierarchy_changed**`(bound native)`
  - hierarchy_changed(self, previous_toplevel:Gtk.Widget)

- **do_input**`(bound native)`
  - input(self, new_value:float) -> int

- **do_insert_at_cursor**`(bound native)`
  - insert_at_cursor(self, str:str)

- **do_insert_emoji**`(bound native)`
  - insert_emoji(self)

- **do_key_press_event**`(bound native)`
  - key_press_event(self, event:Gdk.EventKey) -> bool

- **do_key_release_event**`(bound native)`
  - key_release_event(self, event:Gdk.EventKey) -> bool

- **do_keynav_failed**`(bound native)`
  - keynav_failed(self, direction:Gtk.DirectionType) -> bool

- **do_leave_notify_event**`(bound native)`
  - leave_notify_event(self, event:Gdk.EventCrossing) -> bool

- **do_map**`(bound native)`
  - map(self)

- **do_map_event**`(bound native)`
  - map_event(self, event:Gdk.EventAny) -> bool

- **do_mnemonic_activate**`(bound native)`
  - mnemonic_activate(self, group_cycling:bool) -> bool

- **do_motion_notify_event**`(bound native)`
  - motion_notify_event(self, event:Gdk.EventMotion) -> bool

- **do_move_cursor**`(bound native)`
  - move_cursor(self, step:Gtk.MovementStep, count:int, extend_selection:bool)

- **do_move_focus**`(bound native)`
  - move_focus(self, direction:Gtk.DirectionType)

- **do_output**`(bound native)`
  - output(self) -> int

- **do_parent_set**`(bound native)`
  - parent_set(self, previous_parent:Gtk.Widget)

- **do_paste_clipboard**`(bound native)`
  - paste_clipboard(self)

- **do_populate_popup**`(bound native)`
  - populate_popup(self, popup:Gtk.Widget)

- **do_popup_menu**`(bound native)`
  - popup_menu(self) -> bool

- **do_property_notify_event**`(bound native)`
  - property_notify_event(self, event:Gdk.EventProperty) -> bool

- **do_proximity_in_event**`(bound native)`
  - proximity_in_event(self, event:Gdk.EventProximity) -> bool

- **do_proximity_out_event**`(bound native)`
  - proximity_out_event(self, event:Gdk.EventProximity) -> bool

- **do_query_tooltip**`(bound native)`
  - query_tooltip(self, x:int, y:int, keyboard_tooltip:bool, tooltip:Gtk.Tooltip) -> bool

- **do_queue_draw_region**`(bound native)`
  - queue_draw_region(self, region:cairo.Region)

- **do_realize**`(bound native)`
  - realize(self)

- **do_screen_changed**`(bound native)`
  - screen_changed(self, previous_screen:Gdk.Screen)

- **do_scroll_event**`(bound native)`
  - scroll_event(self, event:Gdk.EventScroll) -> bool

- **do_selection_clear_event**`(bound native)`
  - selection_clear_event(self, event:Gdk.EventSelection) -> bool

- **do_selection_get**`(bound native)`
  - selection_get(self, selection_data:Gtk.SelectionData, info:int, time_:int)

- **do_selection_notify_event**`(bound native)`
  - selection_notify_event(self, event:Gdk.EventSelection) -> bool

- **do_selection_received**`(bound native)`
  - selection_received(self, selection_data:Gtk.SelectionData, time_:int)

- **do_selection_request_event**`(bound native)`
  - selection_request_event(self, event:Gdk.EventSelection) -> bool

- **do_show**`(bound native)`
  - show(self)

- **do_show_all**`(bound native)`
  - show_all(self)

- **do_show_help**`(bound native)`
  - show_help(self, help_type:Gtk.WidgetHelpType) -> bool

- **do_size_allocate**`(bound native)`
  - size_allocate(self, allocation:Gdk.Rectangle)

- **do_state_changed**`(bound native)`
  - state_changed(self, previous_state:Gtk.StateType)

- **do_state_flags_changed**`(bound native)`
  - state_flags_changed(self, previous_state_flags:Gtk.StateFlags)

- **do_style_set**`(bound native)`
  - style_set(self, previous_style:Gtk.Style)

- **do_style_updated**`(bound native)`
  - style_updated(self)

- **do_toggle_direction**`(bound native)`
  - toggle_direction(self)

- **do_toggle_overwrite**`(bound native)`
  - toggle_overwrite(self)

- **do_touch_event**`(bound native)`
  - touch_event(self, event:Gdk.EventTouch) -> bool

- **do_unmap**`(bound native)`
  - unmap(self)

- **do_unmap_event**`(bound native)`
  - unmap_event(self, event:Gdk.EventAny) -> bool

- **do_unrealize**`(bound native)`
  - unrealize(self)

- **do_value_changed**`(bound native)`
  - value_changed(self)

- **do_visibility_notify_event**`(bound native)`
  - visibility_notify_event(self, event:Gdk.EventVisibility) -> bool

- **do_window_state_event**`(bound native)`
  - window_state_event(self, event:Gdk.EventWindowState) -> bool

- **do_wrapped**`(bound native)`
  - wrapped(self)

- **drag_begin**`(*args, **kwargs)`
  - drag_begin(self, targets:Gtk.TargetList, actions:Gdk.DragAction, button:int, event:Gdk.Event=None) -> Gdk.DragContext

- **drag_begin_with_coordinates**`(*args, **kwargs)`
  - drag_begin_with_coordinates(self, targets:Gtk.TargetList, actions:Gdk.DragAction, button:int, event:Gdk.Event=None, x:int, y:int) -> Gdk.DragContext

- **drag_check_threshold**`(*args, **kwargs)`
  - drag_check_threshold(self, start_x:int, start_y:int, current_x:int, current_y:int) -> bool

- **drag_dest_add_image_targets**`(*args, **kwargs)`
  - drag_dest_add_image_targets(self)

- **drag_dest_add_text_targets**`(*args, **kwargs)`
  - drag_dest_add_text_targets(self)

- **drag_dest_add_uri_targets**`(*args, **kwargs)`
  - drag_dest_add_uri_targets(self)

- **drag_dest_find_target**`(*args, **kwargs)`
  - drag_dest_find_target(self, context:Gdk.DragContext, target_list:Gtk.TargetList=None) -> Gdk.Atom

- **drag_dest_get_target_list**`(*args, **kwargs)`
  - drag_dest_get_target_list(self) -> Gtk.TargetList or None

- **drag_dest_get_track_motion**`(*args, **kwargs)`
  - drag_dest_get_track_motion(self) -> bool

- **drag_dest_set**`(*args, **kwargs)`
  - drag_dest_set(self, flags:Gtk.DestDefaults, targets:list=None, actions:Gdk.DragAction)

- **drag_dest_set_proxy**`(*args, **kwargs)`
  - drag_dest_set_proxy(self, proxy_window:Gdk.Window, protocol:Gdk.DragProtocol, use_coordinates:bool)

- **drag_dest_set_target_list**`(self, target_list)`
  - drag_dest_set_target_list(self, target_list:Gtk.TargetList=None)

- **drag_dest_set_track_motion**`(*args, **kwargs)`
  - drag_dest_set_track_motion(self, track_motion:bool)

- **drag_dest_unset**`(*args, **kwargs)`
  - drag_dest_unset(self)

- **drag_get_data**`(*args, **kwargs)`
  - drag_get_data(self, context:Gdk.DragContext, target:Gdk.Atom, time_:int)

- **drag_highlight**`(*args, **kwargs)`
  - drag_highlight(self)

- **drag_source_add_image_targets**`(*args, **kwargs)`
  - drag_source_add_image_targets(self)

- **drag_source_add_text_targets**`(*args, **kwargs)`
  - drag_source_add_text_targets(self)

- **drag_source_add_uri_targets**`(*args, **kwargs)`
  - drag_source_add_uri_targets(self)

- **drag_source_get_target_list**`(*args, **kwargs)`
  - drag_source_get_target_list(self) -> Gtk.TargetList or None

- **drag_source_set**`(*args, **kwargs)`
  - drag_source_set(self, start_button_mask:Gdk.ModifierType, targets:list=None, actions:Gdk.DragAction)

- **drag_source_set_icon_gicon**`(*args, **kwargs)`
  - drag_source_set_icon_gicon(self, icon:Gio.Icon)

- **drag_source_set_icon_name**`(*args, **kwargs)`
  - drag_source_set_icon_name(self, icon_name:str)

- **drag_source_set_icon_pixbuf**`(*args, **kwargs)`
  - drag_source_set_icon_pixbuf(self, pixbuf:GdkPixbuf.Pixbuf)

- **drag_source_set_icon_stock**`(*args, **kwargs)`
  - drag_source_set_icon_stock(self, stock_id:str)

- **drag_source_set_target_list**`(self, target_list)`
  - drag_source_set_target_list(self, target_list:Gtk.TargetList=None)

- **drag_source_unset**`(*args, **kwargs)`
  - drag_source_unset(self)

- **drag_unhighlight**`(*args, **kwargs)`
  - drag_unhighlight(self)

- **draw**`(*args, **kwargs)`
  - draw(self, cr:cairo.Context)

- **editing_done**`(*args, **kwargs)`
  - editing_done(self)

- **emit**`(bound native)`
  - documentation unavailable

- **emit_stop_by_name**`(self, detailed_signal)`
  - Deprecated, please use stop_emission_by_name.

- **ensure_style**`(*args, **kwargs)`
  - ensure_style(self)

- **error_bell**`(*args, **kwargs)`
  - error_bell(self)

- **event**`(*args, **kwargs)`
  - event(self, event:Gdk.Event) -> bool

- **find_property**`(*args, **kwargs)`
  - find_property(self, property_name:str) -> GObject.ParamSpec

- **find_style_property**`(*args, **kwargs)`
  - find_style_property(self, property_name:str) -> GObject.ParamSpec

- **force_floating**`(self, *args, **kargs)`
  - documentation unavailable

- **freeze_child_notify**`(self)`
  - freeze_child_notify(self)

- **freeze_notify**`(self)`
  - Freezes the object's property-changed notification queue.<br /><br />:returns:<br />    A context manager which optionally can be used to<br />    automatically thaw notifications.<br /><br />This will freeze the object so that "notify" signals are blocked until<br />the thaw_notify() method is called.<br /><br />.. code-block:: python<br /><br />    with obj.freeze_notify():<br />        pass

- **get_accessible**`(*args, **kwargs)`
  - get_accessible(self) -> Atk.Object

- **get_action_group**`(*args, **kwargs)`
  - get_action_group(self, prefix:str) -> Gio.ActionGroup or None

- **get_activates_default**`(*args, **kwargs)`
  - get_activates_default(self) -> bool

- **get_adjustment**`(*args, **kwargs)`
  - get_adjustment(self) -> Gtk.Adjustment

- **get_alignment**`(*args, **kwargs)`
  - get_alignment(self) -> float

- **get_allocated_baseline**`(*args, **kwargs)`
  - get_allocated_baseline(self) -> int

- **get_allocated_height**`(*args, **kwargs)`
  - get_allocated_height(self) -> int

- **get_allocated_size**`(*args, **kwargs)`
  - get_allocated_size(self) -> allocation:Gdk.Rectangle, baseline:int

- **get_allocated_width**`(*args, **kwargs)`
  - get_allocated_width(self) -> int

- **get_allocation**`(*args, **kwargs)`
  - get_allocation(self) -> allocation:Gdk.Rectangle

- **get_ancestor**`(*args, **kwargs)`
  - get_ancestor(self, widget_type:GType) -> Gtk.Widget or None

- **get_app_paintable**`(*args, **kwargs)`
  - get_app_paintable(self) -> bool

- **get_attributes**`(*args, **kwargs)`
  - get_attributes(self) -> Pango.AttrList or None

- **get_buffer**`(*args, **kwargs)`
  - get_buffer(self) -> Gtk.EntryBuffer

- **get_can_default**`(*args, **kwargs)`
  - get_can_default(self) -> bool

- **get_can_focus**`(*args, **kwargs)`
  - get_can_focus(self) -> bool

- **get_chars**`(*args, **kwargs)`
  - get_chars(self, start_pos:int, end_pos:int) -> str

- **get_child_requisition**`(*args, **kwargs)`
  - get_child_requisition(self) -> requisition:Gtk.Requisition

- **get_child_visible**`(*args, **kwargs)`
  - get_child_visible(self) -> bool

- **get_clip**`(*args, **kwargs)`
  - get_clip(self) -> clip:Gdk.Rectangle

- **get_clipboard**`(*args, **kwargs)`
  - get_clipboard(self, selection:Gdk.Atom) -> Gtk.Clipboard

- **get_completion**`(*args, **kwargs)`
  - get_completion(self) -> Gtk.EntryCompletion

- **get_composite_name**`(*args, **kwargs)`
  - get_composite_name(self) -> str

- **get_constrain_drag**`(*args, **kwargs)`
  - get_constrain_drag(self) -> bool

- **get_css_name**`(*args, **kwargs)`
  - get_css_name(self) -> str

- **get_current_icon_drag_source**`(*args, **kwargs)`
  - get_current_icon_drag_source(self) -> int

- **get_cursor_hadjustment**`(*args, **kwargs)`
  - get_cursor_hadjustment(self) -> Gtk.Adjustment or None

- **get_data**`(self, *args, **kargs)`
  - documentation unavailable

- **get_default_direction**`(*args, **kwargs)`
  - get_default_direction() -> Gtk.TextDirection

- **get_default_style**`(*args, **kwargs)`
  - get_default_style() -> Gtk.Style

- **get_device_enabled**`(*args, **kwargs)`
  - get_device_enabled(self, device:Gdk.Device) -> bool

- **get_device_events**`(*args, **kwargs)`
  - get_device_events(self, device:Gdk.Device) -> Gdk.EventMask

- **get_digits**`(*args, **kwargs)`
  - get_digits(self) -> int

- **get_direction**`(*args, **kwargs)`
  - get_direction(self) -> Gtk.TextDirection

- **get_display**`(*args, **kwargs)`
  - get_display(self) -> Gdk.Display

- **get_double_buffered**`(*args, **kwargs)`
  - get_double_buffered(self) -> bool

- **get_editable**`(*args, **kwargs)`
  - get_editable(self) -> bool

- **get_events**`(*args, **kwargs)`
  - get_events(self) -> int

- **get_focus_on_click**`(*args, **kwargs)`
  - get_focus_on_click(self) -> bool

- **get_font_map**`(*args, **kwargs)`
  - get_font_map(self) -> Pango.FontMap or None

- **get_font_options**`(*args, **kwargs)`
  - get_font_options(self) -> cairo.FontOptions or None

- **get_frame_clock**`(*args, **kwargs)`
  - get_frame_clock(self) -> Gdk.FrameClock or None

- **get_gamma**`(*args, **kwargs)`
  - get_gamma(self) -> float

- **get_halign**`(*args, **kwargs)`
  - get_halign(self) -> Gtk.Align

- **get_has_frame**`(*args, **kwargs)`
  - get_has_frame(self) -> bool

- **get_has_tooltip**`(*args, **kwargs)`
  - get_has_tooltip(self) -> bool

- **get_has_window**`(*args, **kwargs)`
  - get_has_window(self) -> bool

- **get_hexpand**`(*args, **kwargs)`
  - get_hexpand(self) -> bool

- **get_hexpand_set**`(*args, **kwargs)`
  - get_hexpand_set(self) -> bool

- **get_icon_activatable**`(*args, **kwargs)`
  - get_icon_activatable(self, icon_pos:Gtk.EntryIconPosition) -> bool

- **get_icon_area**`(*args, **kwargs)`
  - get_icon_area(self, icon_pos:Gtk.EntryIconPosition) -> icon_area:Gdk.Rectangle

- **get_icon_at_pos**`(*args, **kwargs)`
  - get_icon_at_pos(self, x:int, y:int) -> int

- **get_icon_gicon**`(*args, **kwargs)`
  - get_icon_gicon(self, icon_pos:Gtk.EntryIconPosition) -> Gio.Icon or None

- **get_icon_name**`(*args, **kwargs)`
  - get_icon_name(self, icon_pos:Gtk.EntryIconPosition) -> str or None

- **get_icon_pixbuf**`(*args, **kwargs)`
  - get_icon_pixbuf(self, icon_pos:Gtk.EntryIconPosition) -> GdkPixbuf.Pixbuf or None

- **get_icon_sensitive**`(*args, **kwargs)`
  - get_icon_sensitive(self, icon_pos:Gtk.EntryIconPosition) -> bool

- **get_icon_stock**`(*args, **kwargs)`
  - get_icon_stock(self, icon_pos:Gtk.EntryIconPosition) -> str

- **get_icon_storage_type**`(*args, **kwargs)`
  - get_icon_storage_type(self, icon_pos:Gtk.EntryIconPosition) -> Gtk.ImageType

- **get_icon_tooltip_markup**`(*args, **kwargs)`
  - get_icon_tooltip_markup(self, icon_pos:Gtk.EntryIconPosition) -> str or None

- **get_icon_tooltip_text**`(*args, **kwargs)`
  - get_icon_tooltip_text(self, icon_pos:Gtk.EntryIconPosition) -> str or None

- **get_increments**`(*args, **kwargs)`
  - get_increments(self) -> step:float, page:float

- **get_inner_border**`(*args, **kwargs)`
  - get_inner_border(self) -> Gtk.Border or None

- **get_input_hints**`(*args, **kwargs)`
  - get_input_hints(self) -> Gtk.InputHints

- **get_input_purpose**`(*args, **kwargs)`
  - get_input_purpose(self) -> Gtk.InputPurpose

- **get_internal_child**`(*args, **kwargs)`
  - get_internal_child(self, builder:Gtk.Builder, childname:str) -> GObject.Object

- **get_invisible_char**`(*args, **kwargs)`
  - get_invisible_char(self) -> str

- **get_label**`(*args, **kwargs)`
  - get_label(self) -> str

- **get_layout**`(*args, **kwargs)`
  - get_layout(self) -> Pango.Layout

- **get_layout_offsets**`(*args, **kwargs)`
  - get_layout_offsets(self) -> x:int, y:int

- **get_mapped**`(*args, **kwargs)`
  - get_mapped(self) -> bool

- **get_margin_bottom**`(*args, **kwargs)`
  - get_margin_bottom(self) -> int

- **get_margin_end**`(*args, **kwargs)`
  - get_margin_end(self) -> int

- **get_margin_left**`(*args, **kwargs)`
  - get_margin_left(self) -> int

- **get_margin_right**`(*args, **kwargs)`
  - get_margin_right(self) -> int

- **get_margin_start**`(*args, **kwargs)`
  - get_margin_start(self) -> int

- **get_margin_top**`(*args, **kwargs)`
  - get_margin_top(self) -> int

- **get_max_length**`(*args, **kwargs)`
  - get_max_length(self) -> int

- **get_max_width_chars**`(*args, **kwargs)`
  - get_max_width_chars(self) -> int

- **get_mnemonic_keyval**`(*args, **kwargs)`
  - get_mnemonic_keyval(self) -> int

- **get_modifier_mask**`(*args, **kwargs)`
  - get_modifier_mask(self, intent:Gdk.ModifierIntent) -> Gdk.ModifierType

- **get_modifier_style**`(*args, **kwargs)`
  - get_modifier_style(self) -> Gtk.RcStyle

- **get_name**`(*args, **kwargs)`
  - get_name(self) -> str

- **get_no_show_all**`(*args, **kwargs)`
  - get_no_show_all(self) -> bool

- **get_numeric**`(*args, **kwargs)`
  - get_numeric(self) -> bool

- **get_opacity**`(*args, **kwargs)`
  - get_opacity(self) -> float

- **get_orientation**`(*args, **kwargs)`
  - get_orientation(self) -> Gtk.Orientation

- **get_overwrite_mode**`(*args, **kwargs)`
  - get_overwrite_mode(self) -> bool

- **get_pango_context**`(*args, **kwargs)`
  - get_pango_context(self) -> Pango.Context

- **get_parent**`(*args, **kwargs)`
  - get_parent(self) -> Gtk.Widget or None

- **get_parent_window**`(*args, **kwargs)`
  - get_parent_window(self) -> Gdk.Window or None

- **get_path**`(*args, **kwargs)`
  - get_path(self) -> Gtk.WidgetPath

- **get_placeholder_text**`(*args, **kwargs)`
  - get_placeholder_text(self) -> str

- **get_pointer**`(*args, **kwargs)`
  - get_pointer(self) -> x:int, y:int

- **get_position**`(*args, **kwargs)`
  - get_position(self) -> int

- **get_preferred_height**`(*args, **kwargs)`
  - get_preferred_height(self) -> minimum_height:int, natural_height:int

- **get_preferred_height_and_baseline_for_width**`(*args, **kwargs)`
  - get_preferred_height_and_baseline_for_width(self, width:int) -> minimum_height:int, natural_height:int, minimum_baseline:int, natural_baseline:int

- **get_preferred_height_for_width**`(*args, **kwargs)`
  - get_preferred_height_for_width(self, width:int) -> minimum_height:int, natural_height:int

- **get_preferred_size**`(*args, **kwargs)`
  - get_preferred_size(self) -> minimum_size:Gtk.Requisition, natural_size:Gtk.Requisition

- **get_preferred_width**`(*args, **kwargs)`
  - get_preferred_width(self) -> minimum_width:int, natural_width:int

- **get_preferred_width_for_height**`(*args, **kwargs)`
  - get_preferred_width_for_height(self, height:int) -> minimum_width:int, natural_width:int

- **get_progress_fraction**`(*args, **kwargs)`
  - get_progress_fraction(self) -> float

- **get_progress_pulse_step**`(*args, **kwargs)`
  - get_progress_pulse_step(self) -> float

- **get_properties**`(bound native)`
  - documentation unavailable

- **get_property**`(bound native)`
  - documentation unavailable

- **get_qdata**`(self, *args, **kargs)`
  - documentation unavailable

- **get_range**`(*args, **kwargs)`
  - get_range(self) -> min:float, max:float

- **get_realized**`(*args, **kwargs)`
  - get_realized(self) -> bool

- **get_receives_default**`(*args, **kwargs)`
  - get_receives_default(self) -> bool

- **get_request_mode**`(*args, **kwargs)`
  - get_request_mode(self) -> Gtk.SizeRequestMode

- **get_requisition**`(*args, **kwargs)`
  - get_requisition(self) -> requisition:Gtk.Requisition

- **get_root_window**`(*args, **kwargs)`
  - get_root_window(self) -> Gdk.Window

- **get_scale_factor**`(*args, **kwargs)`
  - get_scale_factor(self) -> int

- **get_scale_limits**`(*args, **kwargs)`
  - get_scale_limits(self, lower:float, upper:float) -> bool

- **get_screen**`(*args, **kwargs)`
  - get_screen(self) -> Gdk.Screen

- **get_selection_bounds**`(*args, **kwargs)`
  - get_selection_bounds(self) -> bool, start_pos:int, end_pos:int

- **get_sensitive**`(*args, **kwargs)`
  - get_sensitive(self) -> bool

- **get_settings**`(*args, **kwargs)`
  - get_settings(self) -> Gtk.Settings

- **get_size_request**`(*args, **kwargs)`
  - get_size_request(self) -> width:int, height:int

- **get_snap_to_ticks**`(*args, **kwargs)`
  - get_snap_to_ticks(self) -> bool

- **get_state**`(*args, **kwargs)`
  - get_state(self) -> Gtk.StateType

- **get_state_flags**`(*args, **kwargs)`
  - get_state_flags(self) -> Gtk.StateFlags

- **get_style**`(*args, **kwargs)`
  - get_style(self) -> Gtk.Style

- **get_style_context**`(*args, **kwargs)`
  - get_style_context(self) -> Gtk.StyleContext

- **get_support_multidevice**`(*args, **kwargs)`
  - get_support_multidevice(self) -> bool

- **get_tabs**`(*args, **kwargs)`
  - get_tabs(self) -> Pango.TabArray or None

- **get_template_child**`(*args, **kwargs)`
  - get_template_child(self, widget_type:GType, name:str) -> GObject.Object

- **get_text**`(*args, **kwargs)`
  - get_text(self) -> str

- **get_text_area**`(*args, **kwargs)`
  - get_text_area(self) -> text_area:Gdk.Rectangle

- **get_text_length**`(*args, **kwargs)`
  - get_text_length(self) -> int

- **get_tooltip_markup**`(*args, **kwargs)`
  - get_tooltip_markup(self) -> str or None

- **get_tooltip_text**`(*args, **kwargs)`
  - get_tooltip_text(self) -> str or None

- **get_tooltip_window**`(*args, **kwargs)`
  - get_tooltip_window(self) -> Gtk.Window

- **get_toplevel**`(*args, **kwargs)`
  - get_toplevel(self) -> Gtk.Widget

- **get_update_policy**`(*args, **kwargs)`
  - get_update_policy(self) -> Gtk.SpinButtonUpdatePolicy

- **get_valign**`(*args, **kwargs)`
  - get_valign(self) -> Gtk.Align

- **get_valign_with_baseline**`(*args, **kwargs)`
  - get_valign_with_baseline(self) -> Gtk.Align

- **get_value**`(*args, **kwargs)`
  - get_value(self) -> float

- **get_value_as_int**`(*args, **kwargs)`
  - get_value_as_int(self) -> int

- **get_vexpand**`(*args, **kwargs)`
  - get_vexpand(self) -> bool

- **get_vexpand_set**`(*args, **kwargs)`
  - get_vexpand_set(self) -> bool

- **get_visibility**`(*args, **kwargs)`
  - get_visibility(self) -> bool

- **get_visible**`(*args, **kwargs)`
  - get_visible(self) -> bool

- **get_visual**`(*args, **kwargs)`
  - get_visual(self) -> Gdk.Visual

- **get_width_chars**`(*args, **kwargs)`
  - get_width_chars(self) -> int

- **get_window**`(*args, **kwargs)`
  - get_window(self) -> Gdk.Window or None

- **get_wrap**`(*args, **kwargs)`
  - get_wrap(self) -> bool

- **getv**`(*args, **kwargs)`
  - getv(self, names:list, values:list)

- **grab_add**`(*args, **kwargs)`
  - grab_add(self)

- **grab_default**`(*args, **kwargs)`
  - grab_default(self)

- **grab_focus**`(*args, **kwargs)`
  - grab_focus(self)

- **grab_focus_without_selecting**`(*args, **kwargs)`
  - grab_focus_without_selecting(self)

- **grab_remove**`(*args, **kwargs)`
  - grab_remove(self)

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

- **has_default**`(*args, **kwargs)`
  - has_default(self) -> bool

- **has_focus**`(*args, **kwargs)`
  - has_focus(self) -> bool

- **has_grab**`(*args, **kwargs)`
  - has_grab(self) -> bool

- **has_rc_style**`(*args, **kwargs)`
  - has_rc_style(self) -> bool

- **has_screen**`(*args, **kwargs)`
  - has_screen(self) -> bool

- **has_visible_focus**`(*args, **kwargs)`
  - has_visible_focus(self) -> bool

- **hide**`(*args, **kwargs)`
  - hide(self)

- **hide_on_delete**`(*args, **kwargs)`
  - hide_on_delete(self) -> bool

- **im_context_filter_keypress**`(*args, **kwargs)`
  - im_context_filter_keypress(self, event:Gdk.EventKey) -> bool

- **in_destruction**`(*args, **kwargs)`
  - in_destruction(self) -> bool

- **init_template**`(*args, **kwargs)`
  - init_template(self)

- **input_shape_combine_region**`(*args, **kwargs)`
  - input_shape_combine_region(self, region:cairo.Region=None)

- **insert_action_group**`(*args, **kwargs)`
  - insert_action_group(self, name:str, group:Gio.ActionGroup=None)

- **insert_text**`(self, text, position)`
  - insert_text(self, new_text:str, new_text_length:int, position:int) -> position:int

- **install_properties**`(*args, **kwargs)`
  - install_properties(self, pspecs:list)

- **install_property**`(*args, **kwargs)`
  - install_property(self, property_id:int, pspec:GObject.ParamSpec)

- **install_style_property**`(*args, **kwargs)`
  - install_style_property(self, pspec:GObject.ParamSpec)

- **interface_find_property**`(self, *args, **kargs)`
  - documentation unavailable

- **interface_install_property**`(self, *args, **kargs)`
  - documentation unavailable

- **interface_list_properties**`(self, *args, **kargs)`
  - documentation unavailable

- **intersect**`(*args, **kwargs)`
  - intersect(self, area:Gdk.Rectangle) -> bool, intersection:Gdk.Rectangle

- **is_ancestor**`(*args, **kwargs)`
  - is_ancestor(self, ancestor:Gtk.Widget) -> bool

- **is_composited**`(*args, **kwargs)`
  - is_composited(self) -> bool

- **is_drawable**`(*args, **kwargs)`
  - is_drawable(self) -> bool

- **is_floating**`(*args, **kwargs)`
  - is_floating(self) -> bool

- **is_focus**`(*args, **kwargs)`
  - is_focus(self) -> bool

- **is_sensitive**`(*args, **kwargs)`
  - is_sensitive(self) -> bool

- **is_toplevel**`(*args, **kwargs)`
  - is_toplevel(self) -> bool

- **is_visible**`(*args, **kwargs)`
  - is_visible(self) -> bool

- **keynav_failed**`(*args, **kwargs)`
  - keynav_failed(self, direction:Gtk.DirectionType) -> bool

- **layout_index_to_text_index**`(*args, **kwargs)`
  - layout_index_to_text_index(self, layout_index:int) -> int

- **list_accel_closures**`(*args, **kwargs)`
  - list_accel_closures(self) -> list

- **list_action_prefixes**`(*args, **kwargs)`
  - list_action_prefixes(self) -> list

- **list_mnemonic_labels**`(*args, **kwargs)`
  - list_mnemonic_labels(self) -> list

- **list_properties**`(*args, **kwargs)`
  - list_properties(self) -> list

- **list_style_properties**`(*args, **kwargs)`
  - list_style_properties(self) -> list

- **map**`(*args, **kwargs)`
  - map(self)

- **mnemonic_activate**`(*args, **kwargs)`
  - mnemonic_activate(self, group_cycling:bool) -> bool

- **modify_base**`(*args, **kwargs)`
  - modify_base(self, state:Gtk.StateType, color:Gdk.Color=None)

- **modify_bg**`(*args, **kwargs)`
  - modify_bg(self, state:Gtk.StateType, color:Gdk.Color=None)

- **modify_cursor**`(*args, **kwargs)`
  - modify_cursor(self, primary:Gdk.Color=None, secondary:Gdk.Color=None)

- **modify_fg**`(*args, **kwargs)`
  - modify_fg(self, state:Gtk.StateType, color:Gdk.Color=None)

- **modify_font**`(*args, **kwargs)`
  - modify_font(self, font_desc:Pango.FontDescription=None)

- **modify_style**`(*args, **kwargs)`
  - modify_style(self, style:Gtk.RcStyle)

- **modify_text**`(*args, **kwargs)`
  - modify_text(self, state:Gtk.StateType, color:Gdk.Color=None)

- **new**`(*args, **kwargs)`
  - new(adjustment:Gtk.Adjustment, label:str, digits:int) -> Gtk.Widget

- **new_with_buffer**`(*args, **kwargs)`
  - new_with_buffer(buffer:Gtk.EntryBuffer) -> Gtk.Widget

- **new_with_range**`(*args, **kwargs)`
  - new_with_range(min:float, max:float, step:float) -> Gtk.Widget

- **newv**`(*args, **kwargs)`
  - newv(object_type:GType, parameters:list) -> GObject.Object

- **notify**`(*args, **kwargs)`
  - notify(self, property_name:str)

- **notify_by_pspec**`(self, *args, **kargs)`
  - documentation unavailable

- **override_background_color**`(*args, **kwargs)`
  - override_background_color(self, state:Gtk.StateFlags, color:Gdk.RGBA=None)

- **override_color**`(*args, **kwargs)`
  - override_color(self, state:Gtk.StateFlags, color:Gdk.RGBA=None)

- **override_cursor**`(*args, **kwargs)`
  - override_cursor(self, cursor:Gdk.RGBA=None, secondary_cursor:Gdk.RGBA=None)

- **override_font**`(*args, **kwargs)`
  - override_font(self, font_desc:Pango.FontDescription=None)

- **override_property**`(*args, **kwargs)`
  - override_property(self, property_id:int, name:str)

- **override_symbolic_color**`(*args, **kwargs)`
  - override_symbolic_color(self, name:str, color:Gdk.RGBA=None)

- **parser_finished**`(*args, **kwargs)`
  - parser_finished(self, builder:Gtk.Builder)

- **paste_clipboard**`(*args, **kwargs)`
  - paste_clipboard(self)

- **path**`(*args, **kwargs)`
  - path(self) -> path_length:int, path:str, path_reversed:str

- **pop_composite_child**`(*args, **kwargs)`
  - pop_composite_child()

- **progress_pulse**`(*args, **kwargs)`
  - progress_pulse(self)

- **push_composite_child**`(*args, **kwargs)`
  - push_composite_child()

- **queue_allocate**`(*args, **kwargs)`
  - queue_allocate(self)

- **queue_compute_expand**`(*args, **kwargs)`
  - queue_compute_expand(self)

- **queue_draw**`(*args, **kwargs)`
  - queue_draw(self)

- **queue_draw_area**`(*args, **kwargs)`
  - queue_draw_area(self, x:int, y:int, width:int, height:int)

- **queue_draw_region**`(*args, **kwargs)`
  - queue_draw_region(self, region:cairo.Region)

- **queue_resize**`(*args, **kwargs)`
  - queue_resize(self)

- **queue_resize_no_redraw**`(*args, **kwargs)`
  - queue_resize_no_redraw(self)

- **realize**`(*args, **kwargs)`
  - realize(self)

- **ref**`(self, *args, **kargs)`
  - documentation unavailable

- **ref_sink**`(self, *args, **kargs)`
  - documentation unavailable

- **region_intersect**`(*args, **kwargs)`
  - region_intersect(self, region:cairo.Region) -> cairo.Region

- **register_window**`(*args, **kwargs)`
  - register_window(self, window:Gdk.Window)

- **remove_accelerator**`(*args, **kwargs)`
  - remove_accelerator(self, accel_group:Gtk.AccelGroup, accel_key:int, accel_mods:Gdk.ModifierType) -> bool

- **remove_mnemonic_label**`(*args, **kwargs)`
  - remove_mnemonic_label(self, label:Gtk.Widget)

- **remove_tick_callback**`(*args, **kwargs)`
  - remove_tick_callback(self, id:int)

- **remove_widget**`(*args, **kwargs)`
  - remove_widget(self)

- **render_icon**`(*args, **kwargs)`
  - render_icon(self, stock_id:str, size:int, detail:str=None) -> GdkPixbuf.Pixbuf or None

- **render_icon_pixbuf**`(*args, **kwargs)`
  - render_icon_pixbuf(self, stock_id:str, size:int) -> GdkPixbuf.Pixbuf or None

- **reparent**`(*args, **kwargs)`
  - reparent(self, new_parent:Gtk.Widget)

- **replace_data**`(self, *args, **kargs)`
  - documentation unavailable

- **replace_qdata**`(self, *args, **kargs)`
  - documentation unavailable

- **reset_im_context**`(*args, **kwargs)`
  - reset_im_context(self)

- **reset_rc_styles**`(*args, **kwargs)`
  - reset_rc_styles(self)

- **reset_style**`(*args, **kwargs)`
  - reset_style(self)

- **run_dispose**`(*args, **kwargs)`
  - run_dispose(self)

- **select_region**`(*args, **kwargs)`
  - select_region(self, start_pos:int, end_pos:int)

- **send_expose**`(*args, **kwargs)`
  - send_expose(self, event:Gdk.Event) -> int

- **send_focus_change**`(*args, **kwargs)`
  - send_focus_change(self, event:Gdk.Event) -> bool

- **set_accel_path**`(*args, **kwargs)`
  - set_accel_path(self, accel_path:str=None, accel_group:Gtk.AccelGroup=None)

- **set_accessible_role**`(*args, **kwargs)`
  - set_accessible_role(self, role:Atk.Role)

- **set_accessible_type**`(*args, **kwargs)`
  - set_accessible_type(self, type:GType)

- **set_activates_default**`(*args, **kwargs)`
  - set_activates_default(self, setting:bool)

- **set_adjustment**`(*args, **kwargs)`
  - set_adjustment(self, adjustment:Gtk.Adjustment)

- **set_alignment**`(*args, **kwargs)`
  - set_alignment(self, xalign:float)

- **set_allocation**`(*args, **kwargs)`
  - set_allocation(self, allocation:Gdk.Rectangle)

- **set_app_paintable**`(*args, **kwargs)`
  - set_app_paintable(self, app_paintable:bool)

- **set_attributes**`(*args, **kwargs)`
  - set_attributes(self, attrs:Pango.AttrList)

- **set_buffer**`(*args, **kwargs)`
  - set_buffer(self, buffer:Gtk.EntryBuffer)

- **set_buildable_property**`(*args, **kwargs)`
  - set_buildable_property(self, builder:Gtk.Builder, name:str, value:GObject.Value)

- **set_can_default**`(*args, **kwargs)`
  - set_can_default(self, can_default:bool)

- **set_can_focus**`(*args, **kwargs)`
  - set_can_focus(self, can_focus:bool)

- **set_child_visible**`(*args, **kwargs)`
  - set_child_visible(self, is_visible:bool)

- **set_clip**`(*args, **kwargs)`
  - set_clip(self, clip:Gdk.Rectangle)

- **set_completion**`(*args, **kwargs)`
  - set_completion(self, completion:Gtk.EntryCompletion=None)

- **set_composite_name**`(*args, **kwargs)`
  - set_composite_name(self, name:str)

- **set_connect_func**`(*args, **kwargs)`
  - set_connect_func(self, connect_func:Gtk.BuilderConnectFunc, connect_data=None)

- **set_constrain_drag**`(*args, **kwargs)`
  - set_constrain_drag(self, constrain:bool)

- **set_css_name**`(*args, **kwargs)`
  - set_css_name(self, name:str)

- **set_cursor_hadjustment**`(*args, **kwargs)`
  - set_cursor_hadjustment(self, adjustment:Gtk.Adjustment=None)

- **set_data**`(self, *args, **kargs)`
  - documentation unavailable

- **set_default_direction**`(*args, **kwargs)`
  - set_default_direction(dir:Gtk.TextDirection)

- **set_device_enabled**`(*args, **kwargs)`
  - set_device_enabled(self, device:Gdk.Device, enabled:bool)

- **set_device_events**`(*args, **kwargs)`
  - set_device_events(self, device:Gdk.Device, events:Gdk.EventMask)

- **set_digits**`(*args, **kwargs)`
  - set_digits(self, digits:int)

- **set_direction**`(*args, **kwargs)`
  - set_direction(self, dir:Gtk.TextDirection)

- **set_double_buffered**`(*args, **kwargs)`
  - set_double_buffered(self, double_buffered:bool)

- **set_editable**`(*args, **kwargs)`
  - set_editable(self, is_editable:bool)

- **set_events**`(*args, **kwargs)`
  - set_events(self, events:int)

- **set_focus_on_click**`(*args, **kwargs)`
  - set_focus_on_click(self, focus_on_click:bool)

- **set_font_map**`(*args, **kwargs)`
  - set_font_map(self, font_map:Pango.FontMap=None)

- **set_font_options**`(*args, **kwargs)`
  - set_font_options(self, options:cairo.FontOptions=None)

- **set_gamma**`(*args, **kwargs)`
  - set_gamma(self, gamma:float)

- **set_halign**`(*args, **kwargs)`
  - set_halign(self, align:Gtk.Align)

- **set_has_frame**`(*args, **kwargs)`
  - set_has_frame(self, setting:bool)

- **set_has_tooltip**`(*args, **kwargs)`
  - set_has_tooltip(self, has_tooltip:bool)

- **set_has_window**`(*args, **kwargs)`
  - set_has_window(self, has_window:bool)

- **set_hexpand**`(*args, **kwargs)`
  - set_hexpand(self, expand:bool)

- **set_hexpand_set**`(*args, **kwargs)`
  - set_hexpand_set(self, set:bool)

- **set_icon_activatable**`(*args, **kwargs)`
  - set_icon_activatable(self, icon_pos:Gtk.EntryIconPosition, activatable:bool)

- **set_icon_drag_source**`(*args, **kwargs)`
  - set_icon_drag_source(self, icon_pos:Gtk.EntryIconPosition, target_list:Gtk.TargetList, actions:Gdk.DragAction)

- **set_icon_from_gicon**`(*args, **kwargs)`
  - set_icon_from_gicon(self, icon_pos:Gtk.EntryIconPosition, icon:Gio.Icon=None)

- **set_icon_from_icon_name**`(*args, **kwargs)`
  - set_icon_from_icon_name(self, icon_pos:Gtk.EntryIconPosition, icon_name:str=None)

- **set_icon_from_pixbuf**`(*args, **kwargs)`
  - set_icon_from_pixbuf(self, icon_pos:Gtk.EntryIconPosition, pixbuf:GdkPixbuf.Pixbuf=None)

- **set_icon_from_stock**`(*args, **kwargs)`
  - set_icon_from_stock(self, icon_pos:Gtk.EntryIconPosition, stock_id:str=None)

- **set_icon_sensitive**`(*args, **kwargs)`
  - set_icon_sensitive(self, icon_pos:Gtk.EntryIconPosition, sensitive:bool)

- **set_icon_tooltip_markup**`(*args, **kwargs)`
  - set_icon_tooltip_markup(self, icon_pos:Gtk.EntryIconPosition, tooltip:str=None)

- **set_icon_tooltip_text**`(*args, **kwargs)`
  - set_icon_tooltip_text(self, icon_pos:Gtk.EntryIconPosition, tooltip:str=None)

- **set_increments**`(*args, **kwargs)`
  - set_increments(self, step:float, page:float)

- **set_inner_border**`(*args, **kwargs)`
  - set_inner_border(self, border:Gtk.Border=None)

- **set_input_hints**`(*args, **kwargs)`
  - set_input_hints(self, hints:Gtk.InputHints)

- **set_input_purpose**`(*args, **kwargs)`
  - set_input_purpose(self, purpose:Gtk.InputPurpose)

- **set_invisible_char**`(*args, **kwargs)`
  - set_invisible_char(self, ch:str)

- **set_label**`(*args, **kwargs)`
  - set_label(self, label:str)

- **set_mapped**`(*args, **kwargs)`
  - set_mapped(self, mapped:bool)

- **set_margin_bottom**`(*args, **kwargs)`
  - set_margin_bottom(self, margin:int)

- **set_margin_end**`(*args, **kwargs)`
  - set_margin_end(self, margin:int)

- **set_margin_left**`(*args, **kwargs)`
  - set_margin_left(self, margin:int)

- **set_margin_right**`(*args, **kwargs)`
  - set_margin_right(self, margin:int)

- **set_margin_start**`(*args, **kwargs)`
  - set_margin_start(self, margin:int)

- **set_margin_top**`(*args, **kwargs)`
  - set_margin_top(self, margin:int)

- **set_max_length**`(*args, **kwargs)`
  - set_max_length(self, max:int)

- **set_max_width_chars**`(*args, **kwargs)`
  - set_max_width_chars(self, n_chars:int)

- **set_name**`(*args, **kwargs)`
  - set_name(self, name:str)

- **set_no_show_all**`(*args, **kwargs)`
  - set_no_show_all(self, no_show_all:bool)

- **set_numeric**`(*args, **kwargs)`
  - set_numeric(self, numeric:bool)

- **set_opacity**`(*args, **kwargs)`
  - set_opacity(self, opacity:float)

- **set_orientation**`(*args, **kwargs)`
  - set_orientation(self, orientation:Gtk.Orientation)

- **set_overwrite_mode**`(*args, **kwargs)`
  - set_overwrite_mode(self, overwrite:bool)

- **set_parent**`(*args, **kwargs)`
  - set_parent(self, parent:Gtk.Widget)

- **set_parent_window**`(*args, **kwargs)`
  - set_parent_window(self, parent_window:Gdk.Window)

- **set_placeholder_text**`(*args, **kwargs)`
  - set_placeholder_text(self, text:str=None)

- **set_position**`(*args, **kwargs)`
  - set_position(self, position:int)

- **set_progress_fraction**`(*args, **kwargs)`
  - set_progress_fraction(self, fraction:float)

- **set_progress_pulse_step**`(*args, **kwargs)`
  - set_progress_pulse_step(self, fraction:float)

- **set_properties**`(bound native)`
  - documentation unavailable

- **set_property**`(bound native)`
  - documentation unavailable

- **set_range**`(*args, **kwargs)`
  - set_range(self, min:float, max:float)

- **set_realized**`(*args, **kwargs)`
  - set_realized(self, realized:bool)

- **set_receives_default**`(*args, **kwargs)`
  - set_receives_default(self, receives_default:bool)

- **set_redraw_on_allocate**`(*args, **kwargs)`
  - set_redraw_on_allocate(self, redraw_on_allocate:bool)

- **set_scale_limits**`(*args, **kwargs)`
  - set_scale_limits(self, lower:float, upper:float)

- **set_sensitive**`(*args, **kwargs)`
  - set_sensitive(self, sensitive:bool)

- **set_size_request**`(*args, **kwargs)`
  - set_size_request(self, width:int, height:int)

- **set_snap_to_ticks**`(*args, **kwargs)`
  - set_snap_to_ticks(self, snap_to_ticks:bool)

- **set_state**`(*args, **kwargs)`
  - set_state(self, state:Gtk.StateType)

- **set_state_flags**`(*args, **kwargs)`
  - set_state_flags(self, flags:Gtk.StateFlags, clear:bool)

- **set_style**`(*args, **kwargs)`
  - set_style(self, style:Gtk.Style=None)

- **set_support_multidevice**`(*args, **kwargs)`
  - set_support_multidevice(self, support_multidevice:bool)

- **set_tabs**`(*args, **kwargs)`
  - set_tabs(self, tabs:Pango.TabArray)

- **set_template**`(*args, **kwargs)`
  - set_template(self, template_bytes:GLib.Bytes)

- **set_template_from_resource**`(*args, **kwargs)`
  - set_template_from_resource(self, resource_name:str)

- **set_text**`(*args, **kwargs)`
  - set_text(self, text:str)

- **set_tooltip_markup**`(*args, **kwargs)`
  - set_tooltip_markup(self, markup:str=None)

- **set_tooltip_text**`(*args, **kwargs)`
  - set_tooltip_text(self, text:str=None)

- **set_tooltip_window**`(*args, **kwargs)`
  - set_tooltip_window(self, custom_window:Gtk.Window=None)

- **set_update_policy**`(*args, **kwargs)`
  - set_update_policy(self, policy:Gtk.SpinButtonUpdatePolicy)

- **set_valign**`(*args, **kwargs)`
  - set_valign(self, align:Gtk.Align)

- **set_value**`(*args, **kwargs)`
  - set_value(self, value:float)

- **set_vexpand**`(*args, **kwargs)`
  - set_vexpand(self, expand:bool)

- **set_vexpand_set**`(*args, **kwargs)`
  - set_vexpand_set(self, set:bool)

- **set_visibility**`(*args, **kwargs)`
  - set_visibility(self, visible:bool)

- **set_visible**`(*args, **kwargs)`
  - set_visible(self, visible:bool)

- **set_visual**`(*args, **kwargs)`
  - set_visual(self, visual:Gdk.Visual=None)

- **set_width_chars**`(*args, **kwargs)`
  - set_width_chars(self, n_chars:int)

- **set_window**`(*args, **kwargs)`
  - set_window(self, window:Gdk.Window)

- **set_wrap**`(*args, **kwargs)`
  - set_wrap(self, wrap:bool)

- **shape_combine_region**`(*args, **kwargs)`
  - shape_combine_region(self, region:cairo.Region=None)

- **show**`(*args, **kwargs)`
  - show(self)

- **show_all**`(*args, **kwargs)`
  - show_all(self)

- **show_now**`(*args, **kwargs)`
  - show_now(self)

- **size_allocate**`(*args, **kwargs)`
  - size_allocate(self, allocation:Gdk.Rectangle)

- **size_allocate_with_baseline**`(*args, **kwargs)`
  - size_allocate_with_baseline(self, allocation:Gdk.Rectangle, baseline:int)

- **size_request**`(*args, **kwargs)`
  - size_request(self) -> requisition:Gtk.Requisition

- **spin**`(*args, **kwargs)`
  - spin(self, direction:Gtk.SpinType, increment:float)

- **start_editing**`(*args, **kwargs)`
  - start_editing(self, event:Gdk.Event=None)

- **steal_data**`(self, *args, **kargs)`
  - documentation unavailable

- **steal_qdata**`(self, *args, **kargs)`
  - documentation unavailable

- **stop_emission**`(self, detailed_signal)`
  - Deprecated, please use stop_emission_by_name.

- **stop_emission_by_name**`(*args, **kwargs)`
  - signal_stop_emission_by_name(instance:GObject.Object, detailed_signal:str)

- **style_attach**`(*args, **kwargs)`
  - style_attach(self)

- **style_get_property**`(self, property_name, value=None)`
  - style_get_property(self, property_name:str, value:GObject.Value)

- **text_index_to_layout_index**`(*args, **kwargs)`
  - text_index_to_layout_index(self, text_index:int) -> int

- **thaw_child_notify**`(*args, **kwargs)`
  - thaw_child_notify(self)

- **thaw_notify**`(*args, **kwargs)`
  - thaw_notify(self)

- **translate_coordinates**`(*args, **kwargs)`
  - translate_coordinates(self, dest_widget:Gtk.Widget, src_x:int, src_y:int) -> bool, dest_x:int, dest_y:int

- **trigger_tooltip_query**`(*args, **kwargs)`
  - trigger_tooltip_query(self)

- **unmap**`(*args, **kwargs)`
  - unmap(self)

- **unparent**`(*args, **kwargs)`
  - unparent(self)

- **unrealize**`(*args, **kwargs)`
  - unrealize(self)

- **unref**`(self, *args, **kargs)`
  - documentation unavailable

- **unregister_window**`(*args, **kwargs)`
  - unregister_window(self, window:Gdk.Window)

- **unset_invisible_char**`(*args, **kwargs)`
  - unset_invisible_char(self)

- **unset_scale_limits**`(*args, **kwargs)`
  - unset_scale_limits(self)

- **unset_state_flags**`(*args, **kwargs)`
  - unset_state_flags(self, flags:Gtk.StateFlags)

- **update**`(*args, **kwargs)`
  - update(self)

- **watch_closure**`(self, *args, **kargs)`
  - documentation unavailable

- **weak_ref**`(bound native)`
  - documentation unavailable


