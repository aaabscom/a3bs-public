---
layout: default
title: GimpUi.functions
---
# GimpUi.functions

## cairo_set_focus_line_pattern
- cairo_set_focus_line_pattern(cr:cairo.Context, widget:Gtk.Widget) -> bool

### Runtime functions †
- **can_throw_gerror**`()`
  - documentation unavailable

- **equal**`(object, /)`
  - documentation unavailable

- **get_arguments**`()`
  - documentation unavailable

- **get_attribute**`(object, /)`
  - documentation unavailable

- **get_caller_owns**`()`
  - documentation unavailable

- **get_container**`()`
  - documentation unavailable

- **get_flags**`()`
  - documentation unavailable

- **get_name**`()`
  - documentation unavailable

- **get_name_unescaped**`()`
  - documentation unavailable

- **get_namespace**`()`
  - documentation unavailable

- **get_property**`()`
  - documentation unavailable

- **get_return_attribute**`(object, /)`
  - documentation unavailable

- **get_return_type**`()`
  - documentation unavailable

- **get_symbol**`()`
  - documentation unavailable

- **get_type**`()`
  - documentation unavailable

- **get_vfunc**`()`
  - documentation unavailable

- **invoke**`(bound native)`
  - documentation unavailable

- **is_constructor**`()`
  - documentation unavailable

- **is_deprecated**`()`
  - documentation unavailable

- **is_method**`()`
  - documentation unavailable

- **may_return_null**`()`
  - documentation unavailable

- **skip_return**`()`
  - documentation unavailable



## cairo_set_source_color
- cairo_set_source_color(cr:cairo.Context, color:Gegl.Color, config:Gimp.ColorConfig, softproof:bool, widget:Gtk.Widget=None)

### Runtime functions †


## cairo_surface_create_from_pixbuf
- cairo_surface_create_from_pixbuf(pixbuf:GdkPixbuf.Pixbuf) -> cairo.Surface

### Runtime functions †


## context_help
- context_help(widget:Gtk.Widget)

### Runtime functions †


## coordinates_new
- coordinates_new(unit:Gimp.Unit, unit_format:str, menu_show_pixels:bool, menu_show_percent:bool, spinbutton_width:int, update_policy:GimpUi.SizeEntryUpdatePolicy, chainbutton_active:bool, chain_constrains_ratio:bool, xlabel:str, x:float, xres:float, lower_boundary_x:float, upper_boundary_x:float, xsize_0:float, xsize_100:float, ylabel:str, y:float, yres:float, lower_boundary_y:float, upper_boundary_y:float, ysize_0:float, ysize_100:float) -> Gtk.Widget

### Runtime functions †


## double_adjustment_update
- double_adjustment_update(adjustment:Gtk.Adjustment) -> data:float

### Runtime functions †


## enum_icon_box_new
- enum_icon_box_new(enum_type:GType, icon_prefix:str, icon_size:Gtk.IconSize, callback:GObject.Callback=None, callback_data=None) -> Gtk.Widget, first_button:Gtk.Widget

### Runtime functions †


## enum_icon_box_new_with_range
- enum_icon_box_new_with_range(enum_type:GType, minimum:int, maximum:int, icon_prefix:str, icon_size:Gtk.IconSize, callback:GObject.Callback=None, callback_data=None) -> Gtk.Widget, first_button:Gtk.Widget

### Runtime functions †


## enum_icon_box_set_child_padding
- enum_icon_box_set_child_padding(icon_box:Gtk.Widget, xpad:int, ypad:int)

### Runtime functions †


## enum_icon_box_set_icon_size
- enum_icon_box_set_icon_size(icon_box:Gtk.Widget, icon_size:Gtk.IconSize)

### Runtime functions †


## enum_radio_box_new
- enum_radio_box_new(enum_type:GType, callback:GObject.Callback=None, callback_data=None) -> Gtk.Widget, first_button:Gtk.Widget

### Runtime functions †


## enum_radio_box_new_with_range
- enum_radio_box_new_with_range(enum_type:GType, minimum:int, maximum:int, callback:GObject.Callback=None, callback_data=None) -> Gtk.Widget, first_button:Gtk.Widget

### Runtime functions †


## enum_radio_frame_new
- enum_radio_frame_new(enum_type:GType, label_widget:Gtk.Widget=None, callback:GObject.Callback=None, callback_data=None) -> Gtk.Widget, first_button:Gtk.Widget

### Runtime functions †


## enum_radio_frame_new_with_range
- enum_radio_frame_new_with_range(enum_type:GType, minimum:int, maximum:int, label_widget:Gtk.Widget=None, callback:GObject.Callback=None, callback_data=None) -> Gtk.Widget, first_button:Gtk.Widget

### Runtime functions †


## event_triggers_context_menu
- event_triggers_context_menu(event:Gdk.Event, on_release:bool) -> bool

### Runtime functions †


## float_adjustment_update
- float_adjustment_update(adjustment:Gtk.Adjustment) -> data:float

### Runtime functions †


## get_monitor_at_pointer
- get_monitor_at_pointer() -> Gdk.Monitor

### Runtime functions †


## grid_attach_aligned
- grid_attach_aligned(grid:Gtk.Grid, left:int, top:int, label_text:str, label_xalign:float, label_yalign:float, widget:Gtk.Widget, widget_columns:int) -> Gtk.Widget

### Runtime functions †


## help_connect
- help_connect(widget:Gtk.Widget, tooltip:str=None, help_func:GimpUi.HelpFunc, help_id:str, help_data=None)

### Runtime functions †


## help_id_quark
- help_id_quark() -> int

### Runtime functions †


## help_set_help_data
- help_set_help_data(widget:Gtk.Widget, tooltip:str=None, help_id:str)

### Runtime functions †


## help_set_help_data_with_markup
- help_set_help_data_with_markup(widget:Gtk.Widget, tooltip:str, help_id:str)

### Runtime functions †


## icons_init
- icons_init()

### Runtime functions †


## icons_set_icon_theme
- icons_set_icon_theme(path:Gio.File) -> bool

### Runtime functions †


## init
- init(prog_name:str)

### Runtime functions †


## int_adjustment_update
- int_adjustment_update(adjustment:Gtk.Adjustment) -> data:int

### Runtime functions †


## int_radio_group_set_active
- int_radio_group_set_active(radio_button:Gtk.RadioButton, item_data:int)

### Runtime functions †


## monitor_get_color_profile
- monitor_get_color_profile(monitor:Gdk.Monitor) -> Gimp.ColorProfile or None

### Runtime functions †


## proc_view_new
- proc_view_new(procedure_name:str) -> Gtk.Widget

### Runtime functions †


## prop_boolean_combo_box_new
- prop_boolean_combo_box_new(config:GObject.Object, property_name:str, true_text:str, false_text:str) -> Gtk.Widget

### Runtime functions †


## prop_boolean_radio_frame_new
- prop_boolean_radio_frame_new(config:GObject.Object, property_name:str, title:str=None, true_text:str, false_text:str) -> Gtk.Widget

### Runtime functions †


## prop_brush_chooser_new
- prop_brush_chooser_new(config:GObject.Object, property_name:str, chooser_title:str=None) -> Gtk.Widget

### Runtime functions †


## prop_check_button_new
- prop_check_button_new(config:GObject.Object, property_name:str, label:str=None) -> Gtk.Widget

### Runtime functions †


## prop_choice_combo_box_new
- prop_choice_combo_box_new(config:GObject.Object, property_name:str) -> Gtk.Widget

### Runtime functions †


## prop_choice_radio_frame_new
- prop_choice_radio_frame_new(config:GObject.Object, property_name:str) -> Gtk.Widget

### Runtime functions †


## prop_color_area_new
- prop_color_area_new(config:GObject.Object, property_name:str, width:int, height:int, type:GimpUi.ColorAreaType) -> Gtk.Widget

### Runtime functions †


## prop_color_select_new
- prop_color_select_new(config:GObject.Object, property_name:str, width:int, height:int, type:GimpUi.ColorAreaType) -> Gtk.Widget

### Runtime functions †


## prop_coordinates_connect
- prop_coordinates_connect(config:GObject.Object, x_property_name:str, y_property_name:str, unit_property_name:str, sizeentry:Gtk.Widget, chainbutton:Gtk.Widget, xresolution:float, yresolution:float) -> bool

### Runtime functions †


## prop_coordinates_new
- prop_coordinates_new(config:GObject.Object, x_property_name:str, y_property_name:str, unit_property_name:str, unit_format:str, update_policy:GimpUi.SizeEntryUpdatePolicy, xresolution:float, yresolution:float, has_chainbutton:bool) -> Gtk.Widget

### Runtime functions †


## prop_drawable_chooser_new
- prop_drawable_chooser_new(config:GObject.Object, property_name:str, chooser_title:str=None) -> Gtk.Widget

### Runtime functions †


## prop_entry_new
- prop_entry_new(config:GObject.Object, property_name:str, max_len:int) -> Gtk.Widget

### Runtime functions †


## prop_enum_check_button_new
- prop_enum_check_button_new(config:GObject.Object, property_name:str, label:str=None, false_value:int, true_value:int) -> Gtk.Widget

### Runtime functions †


## prop_enum_combo_box_new
- prop_enum_combo_box_new(config:GObject.Object, property_name:str, minimum:int, maximum:int) -> Gtk.Widget

### Runtime functions †


## prop_enum_icon_box_new
- prop_enum_icon_box_new(config:GObject.Object, property_name:str, icon_prefix:str, minimum:int, maximum:int) -> Gtk.Widget

### Runtime functions †


## prop_enum_label_new
- prop_enum_label_new(config:GObject.Object, property_name:str) -> Gtk.Widget

### Runtime functions †


## prop_enum_radio_box_new
- prop_enum_radio_box_new(config:GObject.Object, property_name:str, minimum:int, maximum:int) -> Gtk.Widget

### Runtime functions †


## prop_enum_radio_frame_new
- prop_enum_radio_frame_new(config:GObject.Object, property_name:str, title:str=None, minimum:int, maximum:int) -> Gtk.Widget

### Runtime functions †


## prop_expander_new
- prop_expander_new(config:GObject.Object, property_name:str, label:str=None) -> Gtk.Widget

### Runtime functions †


## prop_file_chooser_button_new
- prop_file_chooser_button_new(config:GObject.Object, property_name:str, title:str=None, action:Gtk.FileChooserAction) -> Gtk.Widget

### Runtime functions †


## prop_file_chooser_button_new_with_dialog
- prop_file_chooser_button_new_with_dialog(config:GObject.Object, property_name:str, dialog:Gtk.Widget) -> Gtk.Widget

### Runtime functions †


## prop_file_chooser_new
- prop_file_chooser_new(config:GObject.Object, property_name:str, label:str=None, title:str=None) -> Gtk.Widget

### Runtime functions †


## prop_font_chooser_new
- prop_font_chooser_new(config:GObject.Object, property_name:str, chooser_title:str=None) -> Gtk.Widget

### Runtime functions †


## prop_gradient_chooser_new
- prop_gradient_chooser_new(config:GObject.Object, property_name:str, chooser_title:str=None) -> Gtk.Widget

### Runtime functions †


## prop_hscale_new
- prop_hscale_new(config:GObject.Object, property_name:str, step_increment:float, page_increment:float, digits:int) -> Gtk.Widget

### Runtime functions †


## prop_icon_image_new
- prop_icon_image_new(config:GObject.Object, property_name:str, icon_size:Gtk.IconSize) -> Gtk.Widget

### Runtime functions †


## prop_int_combo_box_new
- prop_int_combo_box_new(config:GObject.Object, property_name:str, store:GimpUi.IntStore) -> Gtk.Widget

### Runtime functions †


## prop_int_radio_frame_new
- prop_int_radio_frame_new(config:GObject.Object, property_name:str, title:str=None, store:GimpUi.IntStore) -> Gtk.Widget

### Runtime functions †


## prop_label_color_new
- prop_label_color_new(config:GObject.Object, property_name:str, editable:bool) -> Gtk.Widget

### Runtime functions †


## prop_label_entry_new
- prop_label_entry_new(config:GObject.Object, property_name:str, max_len:int) -> Gtk.Widget

### Runtime functions †


## prop_label_new
- prop_label_new(config:GObject.Object, property_name:str) -> Gtk.Widget

### Runtime functions †


## prop_label_spin_new
- prop_label_spin_new(config:GObject.Object, property_name:str, digits:int) -> Gtk.Widget

### Runtime functions †


## prop_memsize_entry_new
- prop_memsize_entry_new(config:GObject.Object, property_name:str) -> Gtk.Widget

### Runtime functions †


## prop_palette_chooser_new
- prop_palette_chooser_new(config:GObject.Object, property_name:str, chooser_title:str=None) -> Gtk.Widget

### Runtime functions †


## prop_path_editor_new
- prop_path_editor_new(config:GObject.Object, path_property_name:str, writable_property_name:str, filechooser_title:str) -> Gtk.Widget

### Runtime functions †


## prop_pattern_chooser_new
- prop_pattern_chooser_new(config:GObject.Object, property_name:str, chooser_title:str=None) -> Gtk.Widget

### Runtime functions †


## prop_pointer_combo_box_new
- prop_pointer_combo_box_new(config:GObject.Object, property_name:str, store:GimpUi.IntStore) -> Gtk.Widget

### Runtime functions †


## prop_scale_entry_new
- prop_scale_entry_new(config:GObject.Object, property_name:str, label:str=None, factor:float, limit_scale:bool, lower_limit:float, upper_limit:float) -> Gtk.Widget

### Runtime functions †


## prop_size_entry_new
- prop_size_entry_new(config:GObject.Object, property_name:str, property_is_pixel:bool, unit_property_name:str, unit_format:str, update_policy:GimpUi.SizeEntryUpdatePolicy, resolution:float) -> Gtk.Widget

### Runtime functions †


## prop_spin_button_new
- prop_spin_button_new(config:GObject.Object, property_name:str, step_increment:float, page_increment:float, digits:int) -> Gtk.Widget

### Runtime functions †


## prop_spin_scale_new
- prop_spin_scale_new(config:GObject.Object, property_name:str, step_increment:float, page_increment:float, digits:int) -> Gtk.Widget

### Runtime functions †


## prop_string_combo_box_new
- prop_string_combo_box_new(config:GObject.Object, property_name:str, model:Gtk.TreeModel, id_column:int, label_column:int) -> Gtk.Widget

### Runtime functions †


## prop_switch_new
- prop_switch_new(config:GObject.Object, property_name:str, label:str) -> Gtk.Widget, label_out:Gtk.Widget, switch_out:Gtk.Widget

### Runtime functions †


## prop_text_buffer_new
- prop_text_buffer_new(config:GObject.Object, property_name:str, max_len:int) -> Gtk.TextBuffer

### Runtime functions †


## prop_unit_combo_box_new
- prop_unit_combo_box_new(config:GObject.Object, property_name:str) -> Gtk.Widget

### Runtime functions †


## prop_widget_set_factor
- prop_widget_set_factor(widget:Gtk.Widget, factor:float, step_increment:float, page_increment:float, digits:int)

### Runtime functions †


## query_boolean_box
- query_boolean_box(title:str, parent:Gtk.Widget, help_func:GimpUi.HelpFunc, help_id:str, icon_name:str, message:str, true_button:str, false_button:str, object:GObject.Object, signal:str, callback:GimpUi.QueryBooleanCallback, data=None) -> Gtk.Widget

### Runtime functions †


## query_double_box
- query_double_box(title:str, parent:Gtk.Widget, help_func:GimpUi.HelpFunc, help_id:str, message:str, initial:float, lower:float, upper:float, digits:int, object:GObject.Object, signal:str, callback:GimpUi.QueryDoubleCallback, data=None) -> Gtk.Widget

### Runtime functions †


## query_int_box
- query_int_box(title:str, parent:Gtk.Widget, help_func:GimpUi.HelpFunc, help_id:str, message:str, initial:int, lower:int, upper:int, object:GObject.Object, signal:str, callback:GimpUi.QueryIntCallback, data=None) -> Gtk.Widget

### Runtime functions †


## query_size_box
- query_size_box(title:str, parent:Gtk.Widget, help_func:GimpUi.HelpFunc, help_id:str, message:str, initial:float, lower:float, upper:float, digits:int, unit:Gimp.Unit, resolution:float, dot_for_dot:bool, object:GObject.Object, signal:str, callback:GimpUi.QuerySizeCallback, data=None) -> Gtk.Widget

### Runtime functions †


## query_string_box
- query_string_box(title:str, parent:Gtk.Widget, help_func:GimpUi.HelpFunc, help_id:str, message:str, initial:str, object:GObject.Object, signal:str, callback:GimpUi.QueryStringCallback, data=None) -> Gtk.Widget

### Runtime functions †


## radio_button_update
- radio_button_update(widget:Gtk.Widget) -> data:int

### Runtime functions †


## random_seed_new
- random_seed_new(seed:int, random_seed:bool) -> Gtk.Widget

### Runtime functions †


## scroll_adjustment_values
- scroll_adjustment_values(sevent:Gdk.EventScroll, hadj:Gtk.Adjustment=None, vadj:Gtk.Adjustment=None) -> hvalue:float, vvalue:float

### Runtime functions †


## standard_help_func
- standard_help_func(help_id:str, help_data=None)

### Runtime functions †


## toggle_button_update
- toggle_button_update(widget:Gtk.Widget) -> data:bool

### Runtime functions †


## uint_adjustment_update
- uint_adjustment_update(adjustment:Gtk.Adjustment) -> data:int

### Runtime functions †


## widget_animation_enabled
- widget_animation_enabled() -> bool

### Runtime functions †


## widget_free_native_handle
- widget_free_native_handle(widget:Gtk.Widget) -> window_handle:GLib.Bytes

### Runtime functions †


## widget_get_color_profile
- widget_get_color_profile(widget:Gtk.Widget) -> Gimp.ColorProfile or None

### Runtime functions †


## widget_get_color_transform
- widget_get_color_transform(widget:Gtk.Widget, config:Gimp.ColorConfig, src_profile:Gimp.ColorProfile, src_format:Babl.Object, dest_format:Babl.Object, softproof_profile:Gimp.ColorProfile, proof_intent:Gimp.ColorRenderingIntent, proof_bpc:bool) -> Gimp.ColorTransform or None

### Runtime functions †


## widget_get_monitor
- widget_get_monitor(widget:Gtk.Widget) -> Gdk.Monitor

### Runtime functions †


## widget_get_render_space
- widget_get_render_space(widget:Gtk.Widget, config:Gimp.ColorConfig) -> Babl.Object

### Runtime functions †


## widget_set_native_handle
- widget_set_native_handle(widget:Gtk.Widget) -> handle:GLib.Bytes

### Runtime functions †


## widget_track_monitor
- widget_track_monitor(widget:Gtk.Widget, monitor_changed_callback:GObject.Callback, user_data=None)

### Runtime functions †


## widgets_error_quark
- widgets_error_quark() -> int

### Runtime functions †


## window_set_transient
- window_set_transient(window:Gtk.Window)

### Runtime functions †


## window_set_transient_for
- window_set_transient_for(window:Gtk.Window, handle:GLib.Bytes)

### Runtime functions †


## window_set_transient_for_display
- window_set_transient_for_display(window:Gtk.Window, display:Gimp.Display)

### Runtime functions †


## zoom_button_new
- zoom_button_new(model:GimpUi.ZoomModel, zoom_type:GimpUi.ZoomType, icon_size:Gtk.IconSize) -> Gtk.Widget

### Runtime functions †

