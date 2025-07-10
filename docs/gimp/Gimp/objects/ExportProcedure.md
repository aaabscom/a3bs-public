---
layout: default
title: Gimp.objects
---
# Gimp.objects

## ExportProcedure
- :Constructors:<br /><br />::<br /><br />    ExportProcedure(**properties)<br />    new(plug_in:Gimp.PlugIn, name:str, proc_type:Gimp.PDBProcType, export_metadata:bool, run_func:Gimp.RunExportFunc, run_data=None) -> Gimp.Procedure

### Runtime attributes

- **g_type_instance**
- **parent_instance**
- **props**
- **qdata**
- **ref_count**

### Runtime functions
- **add_boolean_argument**`(*args, **kwargs)`
  - add_boolean_argument(self, name:str, nick:str, blurb:str=None, value:bool, flags:GObject.ParamFlags)

- **add_boolean_aux_argument**`(*args, **kwargs)`
  - add_boolean_aux_argument(self, name:str, nick:str, blurb:str=None, value:bool, flags:GObject.ParamFlags)

- **add_boolean_return_value**`(*args, **kwargs)`
  - add_boolean_return_value(self, name:str, nick:str, blurb:str=None, value:bool, flags:GObject.ParamFlags)

- **add_brush_argument**`(*args, **kwargs)`
  - add_brush_argument(self, name:str, nick:str, blurb:str=None, none_ok:bool, default_value:Gimp.Brush=None, default_to_context:bool, flags:GObject.ParamFlags)

- **add_brush_aux_argument**`(*args, **kwargs)`
  - add_brush_aux_argument(self, name:str, nick:str, blurb:str=None, default_value:Gimp.Brush=None, default_to_context:bool, flags:GObject.ParamFlags)

- **add_brush_return_value**`(*args, **kwargs)`
  - add_brush_return_value(self, name:str, nick:str, blurb:str=None, flags:GObject.ParamFlags)

- **add_bytes_argument**`(*args, **kwargs)`
  - add_bytes_argument(self, name:str, nick:str, blurb:str=None, flags:GObject.ParamFlags)

- **add_bytes_aux_argument**`(*args, **kwargs)`
  - add_bytes_aux_argument(self, name:str, nick:str, blurb:str=None, flags:GObject.ParamFlags)

- **add_bytes_return_value**`(*args, **kwargs)`
  - add_bytes_return_value(self, name:str, nick:str, blurb:str=None, flags:GObject.ParamFlags)

- **add_channel_argument**`(*args, **kwargs)`
  - add_channel_argument(self, name:str, nick:str, blurb:str=None, none_ok:bool, flags:GObject.ParamFlags)

- **add_channel_aux_argument**`(*args, **kwargs)`
  - add_channel_aux_argument(self, name:str, nick:str, blurb:str=None, none_ok:bool, flags:GObject.ParamFlags)

- **add_channel_return_value**`(*args, **kwargs)`
  - add_channel_return_value(self, name:str, nick:str, blurb:str=None, none_ok:bool, flags:GObject.ParamFlags)

- **add_choice_argument**`(*args, **kwargs)`
  - add_choice_argument(self, name:str, nick:str, blurb:str=None, choice:Gimp.Choice, value:str, flags:GObject.ParamFlags)

- **add_choice_aux_argument**`(*args, **kwargs)`
  - add_choice_aux_argument(self, name:str, nick:str, blurb:str=None, choice:Gimp.Choice, value:str, flags:GObject.ParamFlags)

- **add_choice_return_value**`(*args, **kwargs)`
  - add_choice_return_value(self, name:str, nick:str, blurb:str=None, choice:Gimp.Choice, value:str, flags:GObject.ParamFlags)

- **add_color_argument**`(*args, **kwargs)`
  - add_color_argument(self, name:str, nick:str, blurb:str=None, has_alpha:bool, value:Gegl.Color, flags:GObject.ParamFlags)

- **add_color_aux_argument**`(*args, **kwargs)`
  - add_color_aux_argument(self, name:str, nick:str, blurb:str=None, has_alpha:bool, value:Gegl.Color, flags:GObject.ParamFlags)

- **add_color_from_string_argument**`(*args, **kwargs)`
  - add_color_from_string_argument(self, name:str, nick:str, blurb:str=None, has_alpha:bool, value:str, flags:GObject.ParamFlags)

- **add_color_from_string_aux_argument**`(*args, **kwargs)`
  - add_color_from_string_aux_argument(self, name:str, nick:str, blurb:str=None, has_alpha:bool, value:str, flags:GObject.ParamFlags)

- **add_color_from_string_return_value**`(*args, **kwargs)`
  - add_color_from_string_return_value(self, name:str, nick:str, blurb:str=None, has_alpha:bool, value:str, flags:GObject.ParamFlags)

- **add_color_return_value**`(*args, **kwargs)`
  - add_color_return_value(self, name:str, nick:str, blurb:str=None, has_alpha:bool, value:Gegl.Color, flags:GObject.ParamFlags)

- **add_core_object_array_argument**`(*args, **kwargs)`
  - add_core_object_array_argument(self, name:str, nick:str, blurb:str=None, object_type:GType, flags:GObject.ParamFlags)

- **add_core_object_array_aux_argument**`(*args, **kwargs)`
  - add_core_object_array_aux_argument(self, name:str, nick:str, blurb:str=None, object_type:GType, flags:GObject.ParamFlags)

- **add_core_object_array_return_value**`(*args, **kwargs)`
  - add_core_object_array_return_value(self, name:str, nick:str, blurb:str=None, object_type:GType, flags:GObject.ParamFlags)

- **add_display_argument**`(*args, **kwargs)`
  - add_display_argument(self, name:str, nick:str, blurb:str=None, none_ok:bool, flags:GObject.ParamFlags)

- **add_display_aux_argument**`(*args, **kwargs)`
  - add_display_aux_argument(self, name:str, nick:str, blurb:str=None, none_ok:bool, flags:GObject.ParamFlags)

- **add_display_return_value**`(*args, **kwargs)`
  - add_display_return_value(self, name:str, nick:str, blurb:str=None, none_ok:bool, flags:GObject.ParamFlags)

- **add_double_argument**`(*args, **kwargs)`
  - add_double_argument(self, name:str, nick:str, blurb:str=None, min:float, max:float, value:float, flags:GObject.ParamFlags)

- **add_double_array_argument**`(*args, **kwargs)`
  - add_double_array_argument(self, name:str, nick:str, blurb:str=None, flags:GObject.ParamFlags)

- **add_double_array_aux_argument**`(*args, **kwargs)`
  - add_double_array_aux_argument(self, name:str, nick:str, blurb:str=None, flags:GObject.ParamFlags)

- **add_double_array_return_value**`(*args, **kwargs)`
  - add_double_array_return_value(self, name:str, nick:str, blurb:str=None, flags:GObject.ParamFlags)

- **add_double_aux_argument**`(*args, **kwargs)`
  - add_double_aux_argument(self, name:str, nick:str, blurb:str=None, min:float, max:float, value:float, flags:GObject.ParamFlags)

- **add_double_return_value**`(*args, **kwargs)`
  - add_double_return_value(self, name:str, nick:str, blurb:str=None, min:float, max:float, value:float, flags:GObject.ParamFlags)

- **add_drawable_argument**`(*args, **kwargs)`
  - add_drawable_argument(self, name:str, nick:str, blurb:str=None, none_ok:bool, flags:GObject.ParamFlags)

- **add_drawable_aux_argument**`(*args, **kwargs)`
  - add_drawable_aux_argument(self, name:str, nick:str, blurb:str=None, none_ok:bool, flags:GObject.ParamFlags)

- **add_drawable_return_value**`(*args, **kwargs)`
  - add_drawable_return_value(self, name:str, nick:str, blurb:str=None, none_ok:bool, flags:GObject.ParamFlags)

- **add_enum_argument**`(*args, **kwargs)`
  - add_enum_argument(self, name:str, nick:str, blurb:str=None, enum_type:GType, value:int, flags:GObject.ParamFlags)

- **add_enum_aux_argument**`(*args, **kwargs)`
  - add_enum_aux_argument(self, name:str, nick:str, blurb:str=None, enum_type:GType, value:int, flags:GObject.ParamFlags)

- **add_enum_return_value**`(*args, **kwargs)`
  - add_enum_return_value(self, name:str, nick:str, blurb:str=None, enum_type:GType, value:int, flags:GObject.ParamFlags)

- **add_file_argument**`(*args, **kwargs)`
  - add_file_argument(self, name:str, nick:str, blurb:str=None, action:Gimp.FileChooserAction, none_ok:bool, default_file:Gio.File=None, flags:GObject.ParamFlags)

- **add_file_aux_argument**`(*args, **kwargs)`
  - add_file_aux_argument(self, name:str, nick:str, blurb:str=None, action:Gimp.FileChooserAction, none_ok:bool, default_file:Gio.File=None, flags:GObject.ParamFlags)

- **add_file_return_value**`(*args, **kwargs)`
  - add_file_return_value(self, name:str, nick:str, blurb:str=None, flags:GObject.ParamFlags)

- **add_font_argument**`(*args, **kwargs)`
  - add_font_argument(self, name:str, nick:str, blurb:str=None, none_ok:bool, default_value:Gimp.Font=None, default_to_context:bool, flags:GObject.ParamFlags)

- **add_font_aux_argument**`(*args, **kwargs)`
  - add_font_aux_argument(self, name:str, nick:str, blurb:str=None, default_value:Gimp.Font=None, default_to_context:bool, flags:GObject.ParamFlags)

- **add_font_return_value**`(*args, **kwargs)`
  - add_font_return_value(self, name:str, nick:str, blurb:str=None, flags:GObject.ParamFlags)

- **add_gradient_argument**`(*args, **kwargs)`
  - add_gradient_argument(self, name:str, nick:str, blurb:str=None, none_ok:bool, default_value:Gimp.Gradient=None, default_to_context:bool, flags:GObject.ParamFlags)

- **add_gradient_aux_argument**`(*args, **kwargs)`
  - add_gradient_aux_argument(self, name:str, nick:str, blurb:str=None, default_value:Gimp.Gradient=None, default_to_context:bool, flags:GObject.ParamFlags)

- **add_gradient_return_value**`(*args, **kwargs)`
  - add_gradient_return_value(self, name:str, nick:str, blurb:str=None, flags:GObject.ParamFlags)

- **add_group_layer_argument**`(*args, **kwargs)`
  - add_group_layer_argument(self, name:str, nick:str, blurb:str=None, none_ok:bool, flags:GObject.ParamFlags)

- **add_group_layer_aux_argument**`(*args, **kwargs)`
  - add_group_layer_aux_argument(self, name:str, nick:str, blurb:str=None, none_ok:bool, flags:GObject.ParamFlags)

- **add_group_layer_return_value**`(*args, **kwargs)`
  - add_group_layer_return_value(self, name:str, nick:str, blurb:str=None, none_ok:bool, flags:GObject.ParamFlags)

- **add_image_argument**`(*args, **kwargs)`
  - add_image_argument(self, name:str, nick:str, blurb:str=None, none_ok:bool, flags:GObject.ParamFlags)

- **add_image_aux_argument**`(*args, **kwargs)`
  - add_image_aux_argument(self, name:str, nick:str, blurb:str=None, none_ok:bool, flags:GObject.ParamFlags)

- **add_image_return_value**`(*args, **kwargs)`
  - add_image_return_value(self, name:str, nick:str, blurb:str=None, none_ok:bool, flags:GObject.ParamFlags)

- **add_int32_array_argument**`(*args, **kwargs)`
  - add_int32_array_argument(self, name:str, nick:str, blurb:str=None, flags:GObject.ParamFlags)

- **add_int32_array_aux_argument**`(*args, **kwargs)`
  - add_int32_array_aux_argument(self, name:str, nick:str, blurb:str=None, flags:GObject.ParamFlags)

- **add_int32_array_return_value**`(*args, **kwargs)`
  - add_int32_array_return_value(self, name:str, nick:str, blurb:str=None, flags:GObject.ParamFlags)

- **add_int_argument**`(*args, **kwargs)`
  - add_int_argument(self, name:str, nick:str, blurb:str=None, min:int, max:int, value:int, flags:GObject.ParamFlags)

- **add_int_aux_argument**`(*args, **kwargs)`
  - add_int_aux_argument(self, name:str, nick:str, blurb:str=None, min:int, max:int, value:int, flags:GObject.ParamFlags)

- **add_int_return_value**`(*args, **kwargs)`
  - add_int_return_value(self, name:str, nick:str, blurb:str=None, min:int, max:int, value:int, flags:GObject.ParamFlags)

- **add_item_argument**`(*args, **kwargs)`
  - add_item_argument(self, name:str, nick:str, blurb:str=None, none_ok:bool, flags:GObject.ParamFlags)

- **add_item_aux_argument**`(*args, **kwargs)`
  - add_item_aux_argument(self, name:str, nick:str, blurb:str=None, none_ok:bool, flags:GObject.ParamFlags)

- **add_item_return_value**`(*args, **kwargs)`
  - add_item_return_value(self, name:str, nick:str, blurb:str=None, none_ok:bool, flags:GObject.ParamFlags)

- **add_layer_argument**`(*args, **kwargs)`
  - add_layer_argument(self, name:str, nick:str, blurb:str=None, none_ok:bool, flags:GObject.ParamFlags)

- **add_layer_aux_argument**`(*args, **kwargs)`
  - add_layer_aux_argument(self, name:str, nick:str, blurb:str=None, none_ok:bool, flags:GObject.ParamFlags)

- **add_layer_mask_argument**`(*args, **kwargs)`
  - add_layer_mask_argument(self, name:str, nick:str, blurb:str=None, none_ok:bool, flags:GObject.ParamFlags)

- **add_layer_mask_aux_argument**`(*args, **kwargs)`
  - add_layer_mask_aux_argument(self, name:str, nick:str, blurb:str=None, none_ok:bool, flags:GObject.ParamFlags)

- **add_layer_mask_return_value**`(*args, **kwargs)`
  - add_layer_mask_return_value(self, name:str, nick:str, blurb:str=None, none_ok:bool, flags:GObject.ParamFlags)

- **add_layer_return_value**`(*args, **kwargs)`
  - add_layer_return_value(self, name:str, nick:str, blurb:str=None, none_ok:bool, flags:GObject.ParamFlags)

- **add_menu_path**`(*args, **kwargs)`
  - add_menu_path(self, menu_path:str)

- **add_palette_argument**`(*args, **kwargs)`
  - add_palette_argument(self, name:str, nick:str, blurb:str=None, none_ok:bool, default_value:Gimp.Palette=None, default_to_context:bool, flags:GObject.ParamFlags)

- **add_palette_aux_argument**`(*args, **kwargs)`
  - add_palette_aux_argument(self, name:str, nick:str, blurb:str=None, default_value:Gimp.Palette=None, default_to_context:bool, flags:GObject.ParamFlags)

- **add_palette_return_value**`(*args, **kwargs)`
  - add_palette_return_value(self, name:str, nick:str, blurb:str=None, flags:GObject.ParamFlags)

- **add_param_argument**`(*args, **kwargs)`
  - add_param_argument(self, name:str, nick:str, blurb:str=None, param_type:GType, flags:GObject.ParamFlags)

- **add_param_aux_argument**`(*args, **kwargs)`
  - add_param_aux_argument(self, name:str, nick:str, blurb:str=None, param_type:GType, flags:GObject.ParamFlags)

- **add_param_return_value**`(*args, **kwargs)`
  - add_param_return_value(self, name:str, nick:str, blurb:str=None, param_type:GType, flags:GObject.ParamFlags)

- **add_parasite_argument**`(*args, **kwargs)`
  - add_parasite_argument(self, name:str, nick:str, blurb:str=None, flags:GObject.ParamFlags)

- **add_parasite_aux_argument**`(*args, **kwargs)`
  - add_parasite_aux_argument(self, name:str, nick:str, blurb:str=None, flags:GObject.ParamFlags)

- **add_parasite_return_value**`(*args, **kwargs)`
  - add_parasite_return_value(self, name:str, nick:str, blurb:str=None, flags:GObject.ParamFlags)

- **add_path_argument**`(*args, **kwargs)`
  - add_path_argument(self, name:str, nick:str, blurb:str=None, none_ok:bool, flags:GObject.ParamFlags)

- **add_path_aux_argument**`(*args, **kwargs)`
  - add_path_aux_argument(self, name:str, nick:str, blurb:str=None, none_ok:bool, flags:GObject.ParamFlags)

- **add_path_return_value**`(*args, **kwargs)`
  - add_path_return_value(self, name:str, nick:str, blurb:str=None, none_ok:bool, flags:GObject.ParamFlags)

- **add_pattern_argument**`(*args, **kwargs)`
  - add_pattern_argument(self, name:str, nick:str, blurb:str=None, none_ok:bool, default_value:Gimp.Pattern=None, default_to_context:bool, flags:GObject.ParamFlags)

- **add_pattern_aux_argument**`(*args, **kwargs)`
  - add_pattern_aux_argument(self, name:str, nick:str, blurb:str=None, default_value:Gimp.Pattern=None, default_to_context:bool, flags:GObject.ParamFlags)

- **add_pattern_return_value**`(*args, **kwargs)`
  - add_pattern_return_value(self, name:str, nick:str, blurb:str=None, flags:GObject.ParamFlags)

- **add_resource_argument**`(*args, **kwargs)`
  - add_resource_argument(self, name:str, nick:str, blurb:str=None, none_ok:bool, default_value:Gimp.Resource=None, flags:GObject.ParamFlags)

- **add_resource_aux_argument**`(*args, **kwargs)`
  - add_resource_aux_argument(self, name:str, nick:str, blurb:str=None, default_value:Gimp.Resource=None, flags:GObject.ParamFlags)

- **add_resource_return_value**`(*args, **kwargs)`
  - add_resource_return_value(self, name:str, nick:str, blurb:str=None, flags:GObject.ParamFlags)

- **add_selection_argument**`(*args, **kwargs)`
  - add_selection_argument(self, name:str, nick:str, blurb:str=None, none_ok:bool, flags:GObject.ParamFlags)

- **add_selection_aux_argument**`(*args, **kwargs)`
  - add_selection_aux_argument(self, name:str, nick:str, blurb:str=None, none_ok:bool, flags:GObject.ParamFlags)

- **add_selection_return_value**`(*args, **kwargs)`
  - add_selection_return_value(self, name:str, nick:str, blurb:str=None, none_ok:bool, flags:GObject.ParamFlags)

- **add_string_argument**`(*args, **kwargs)`
  - add_string_argument(self, name:str, nick:str, blurb:str=None, value:str, flags:GObject.ParamFlags)

- **add_string_array_argument**`(*args, **kwargs)`
  - add_string_array_argument(self, name:str, nick:str, blurb:str=None, flags:GObject.ParamFlags)

- **add_string_array_aux_argument**`(*args, **kwargs)`
  - add_string_array_aux_argument(self, name:str, nick:str, blurb:str=None, flags:GObject.ParamFlags)

- **add_string_array_return_value**`(*args, **kwargs)`
  - add_string_array_return_value(self, name:str, nick:str, blurb:str=None, flags:GObject.ParamFlags)

- **add_string_aux_argument**`(*args, **kwargs)`
  - add_string_aux_argument(self, name:str, nick:str, blurb:str=None, value:str, flags:GObject.ParamFlags)

- **add_string_return_value**`(*args, **kwargs)`
  - add_string_return_value(self, name:str, nick:str, blurb:str=None, value:str, flags:GObject.ParamFlags)

- **add_text_layer_argument**`(*args, **kwargs)`
  - add_text_layer_argument(self, name:str, nick:str, blurb:str=None, none_ok:bool, flags:GObject.ParamFlags)

- **add_text_layer_aux_argument**`(*args, **kwargs)`
  - add_text_layer_aux_argument(self, name:str, nick:str, blurb:str=None, none_ok:bool, flags:GObject.ParamFlags)

- **add_text_layer_return_value**`(*args, **kwargs)`
  - add_text_layer_return_value(self, name:str, nick:str, blurb:str=None, none_ok:bool, flags:GObject.ParamFlags)

- **add_uint_argument**`(*args, **kwargs)`
  - add_uint_argument(self, name:str, nick:str, blurb:str=None, min:int, max:int, value:int, flags:GObject.ParamFlags)

- **add_uint_aux_argument**`(*args, **kwargs)`
  - add_uint_aux_argument(self, name:str, nick:str, blurb:str=None, min:int, max:int, value:int, flags:GObject.ParamFlags)

- **add_uint_return_value**`(*args, **kwargs)`
  - add_uint_return_value(self, name:str, nick:str, blurb:str=None, min:int, max:int, value:int, flags:GObject.ParamFlags)

- **add_unit_argument**`(*args, **kwargs)`
  - add_unit_argument(self, name:str, nick:str, blurb:str=None, show_pixels:bool, show_percent:bool, value:Gimp.Unit, flags:GObject.ParamFlags)

- **add_unit_aux_argument**`(*args, **kwargs)`
  - add_unit_aux_argument(self, name:str, nick:str, blurb:str=None, show_pixels:bool, show_percent:bool, value:Gimp.Unit, flags:GObject.ParamFlags)

- **add_unit_return_value**`(*args, **kwargs)`
  - add_unit_return_value(self, name:str, nick:str, blurb:str=None, show_pixels:bool, show_percent:bool, value:Gimp.Unit, flags:GObject.ParamFlags)

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

- **create_config**`(*args, **kwargs)`
  - create_config(self) -> Gimp.ProcedureConfig

- **disconnect**`(*args, **kwargs)`
  - signal_handler_disconnect(instance:GObject.Object, handler_id:int)

- **disconnect_by_func**`(bound native)`
  - documentation unavailable

- **do_install**`(bound native)`
  - install(self)

- **do_run**`(bound native)`
  - run(self, args:Gimp.ValueArray) -> Gimp.ValueArray

- **do_set_sensitivity**`(bound native)`
  - set_sensitivity(self, sensitivity_mask:int) -> bool

- **do_uninstall**`(bound native)`
  - uninstall(self)

- **emit**`(bound native)`
  - documentation unavailable

- **emit_stop_by_name**`(self, detailed_signal)`
  - Deprecated, please use stop_emission_by_name.

- **find_argument**`(*args, **kwargs)`
  - find_argument(self, name:str) -> GObject.ParamSpec

- **find_aux_argument**`(*args, **kwargs)`
  - find_aux_argument(self, name:str) -> GObject.ParamSpec

- **find_property**`(*args, **kwargs)`
  - find_property(self, property_name:str) -> GObject.ParamSpec

- **find_return_value**`(*args, **kwargs)`
  - find_return_value(self, name:str) -> GObject.ParamSpec

- **force_floating**`(self, *args, **kargs)`
  - documentation unavailable

- **freeze_notify**`(self)`
  - Freezes the object's property-changed notification queue.<br /><br />:returns:<br />    A context manager which optionally can be used to<br />    automatically thaw notifications.<br /><br />This will freeze the object so that "notify" signals are blocked until<br />the thaw_notify() method is called.<br /><br />.. code-block:: python<br /><br />    with obj.freeze_notify():<br />        pass

- **get_argument_sync**`(*args, **kwargs)`
  - get_argument_sync(self, arg_name:str) -> Gimp.ArgumentSync

- **get_arguments**`(*args, **kwargs)`
  - get_arguments(self) -> list

- **get_authors**`(*args, **kwargs)`
  - get_authors(self) -> str

- **get_aux_arguments**`(*args, **kwargs)`
  - get_aux_arguments(self) -> list

- **get_blurb**`(*args, **kwargs)`
  - get_blurb(self) -> str

- **get_copyright**`(*args, **kwargs)`
  - get_copyright(self) -> str

- **get_data**`(self, *args, **kargs)`
  - documentation unavailable

- **get_date**`(*args, **kwargs)`
  - get_date(self) -> str

- **get_extensions**`(*args, **kwargs)`
  - get_extensions(self) -> str

- **get_format_name**`(*args, **kwargs)`
  - get_format_name(self) -> str

- **get_handles_remote**`(*args, **kwargs)`
  - get_handles_remote(self) -> bool

- **get_help**`(*args, **kwargs)`
  - get_help(self) -> str

- **get_help_id**`(*args, **kwargs)`
  - get_help_id(self) -> str

- **get_icon_file**`(*args, **kwargs)`
  - get_icon_file(self) -> Gio.File or None

- **get_icon_name**`(*args, **kwargs)`
  - get_icon_name(self) -> str or None

- **get_icon_pixbuf**`(*args, **kwargs)`
  - get_icon_pixbuf(self) -> GdkPixbuf.Pixbuf or None

- **get_icon_type**`(*args, **kwargs)`
  - get_icon_type(self) -> Gimp.IconType

- **get_image_types**`(*args, **kwargs)`
  - get_image_types(self) -> str

- **get_magics**`(*args, **kwargs)`
  - get_magics(self) -> str

- **get_menu_label**`(*args, **kwargs)`
  - get_menu_label(self) -> str

- **get_menu_paths**`(*args, **kwargs)`
  - get_menu_paths(self) -> list

- **get_mime_types**`(*args, **kwargs)`
  - get_mime_types(self) -> str

- **get_name**`(*args, **kwargs)`
  - get_name(self) -> str

- **get_plug_in**`(*args, **kwargs)`
  - get_plug_in(self) -> Gimp.PlugIn

- **get_prefixes**`(*args, **kwargs)`
  - get_prefixes(self) -> str

- **get_priority**`(*args, **kwargs)`
  - get_priority(self) -> int

- **get_proc_type**`(*args, **kwargs)`
  - get_proc_type(self) -> Gimp.PDBProcType

- **get_properties**`(bound native)`
  - documentation unavailable

- **get_property**`(bound native)`
  - documentation unavailable

- **get_qdata**`(self, *args, **kargs)`
  - documentation unavailable

- **get_return_values**`(*args, **kwargs)`
  - get_return_values(self) -> list

- **get_sensitivity_mask**`(*args, **kwargs)`
  - get_sensitivity_mask(self) -> int

- **get_support_comment**`(*args, **kwargs)`
  - get_support_comment(self) -> bool

- **get_support_exif**`(*args, **kwargs)`
  - get_support_exif(self) -> bool

- **get_support_iptc**`(*args, **kwargs)`
  - get_support_iptc(self) -> bool

- **get_support_profile**`(*args, **kwargs)`
  - get_support_profile(self) -> bool

- **get_support_thumbnail**`(*args, **kwargs)`
  - get_support_thumbnail(self) -> bool

- **get_support_xmp**`(*args, **kwargs)`
  - get_support_xmp(self) -> bool

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

- **is_internal**`(*args, **kwargs)`
  - is_internal(self) -> bool

- **list_properties**`(*args, **kwargs)`
  - list_properties(self) -> list

- **new**`(*args, **kwargs)`
  - new(plug_in:Gimp.PlugIn, name:str, proc_type:Gimp.PDBProcType, export_metadata:bool, run_func:Gimp.RunExportFunc, run_data=None) -> Gimp.Procedure

- **new_return_values**`(*args, **kwargs)`
  - new_return_values(self, status:Gimp.PDBStatusType, error:error=None) -> Gimp.ValueArray

- **newv**`(*args, **kwargs)`
  - newv(object_type:GType, parameters:list) -> GObject.Object

- **notify**`(*args, **kwargs)`
  - notify(self, property_name:str)

- **notify_by_pspec**`(self, *args, **kargs)`
  - documentation unavailable

- **override_property**`(*args, **kwargs)`
  - override_property(self, property_id:int, name:str)

- **persistent_ready**`(*args, **kwargs)`
  - persistent_ready(self)

- **ref**`(self, *args, **kargs)`
  - documentation unavailable

- **ref_sink**`(self, *args, **kargs)`
  - documentation unavailable

- **replace_data**`(self, *args, **kargs)`
  - documentation unavailable

- **replace_qdata**`(self, *args, **kargs)`
  - documentation unavailable

- **run**`(*args, **kwargs)`
  - run(self, config:Gimp.ProcedureConfig=None) -> Gimp.ValueArray

- **run_dispose**`(*args, **kwargs)`
  - run_dispose(self)

- **set_argument_sync**`(*args, **kwargs)`
  - set_argument_sync(self, arg_name:str, sync:Gimp.ArgumentSync)

- **set_attribution**`(*args, **kwargs)`
  - set_attribution(self, authors:str, copyright:str, date:str)

- **set_capabilities**`(*args, **kwargs)`
  - set_capabilities(self, capabilities:Gimp.ExportCapabilities, get_capabilities_func:Gimp.ExportGetCapabilitiesFunc=None, get_capabilities_data=None)

- **set_data**`(self, *args, **kargs)`
  - documentation unavailable

- **set_documentation**`(*args, **kwargs)`
  - set_documentation(self, blurb:str, help:str=None, help_id:str=None)

- **set_extensions**`(*args, **kwargs)`
  - set_extensions(self, extensions:str)

- **set_format_name**`(*args, **kwargs)`
  - set_format_name(self, format_name:str)

- **set_handles_remote**`(*args, **kwargs)`
  - set_handles_remote(self, handles_remote:bool)

- **set_icon_file**`(*args, **kwargs)`
  - set_icon_file(self, file:Gio.File=None)

- **set_icon_name**`(*args, **kwargs)`
  - set_icon_name(self, icon_name:str=None)

- **set_icon_pixbuf**`(*args, **kwargs)`
  - set_icon_pixbuf(self, pixbuf:GdkPixbuf.Pixbuf=None)

- **set_image_types**`(*args, **kwargs)`
  - set_image_types(self, image_types:str)

- **set_magics**`(*args, **kwargs)`
  - set_magics(self, magics:str)

- **set_menu_label**`(*args, **kwargs)`
  - set_menu_label(self, menu_label:str)

- **set_mime_types**`(*args, **kwargs)`
  - set_mime_types(self, mime_types:str)

- **set_prefixes**`(*args, **kwargs)`
  - set_prefixes(self, prefixes:str)

- **set_priority**`(*args, **kwargs)`
  - set_priority(self, priority:int)

- **set_properties**`(bound native)`
  - documentation unavailable

- **set_property**`(bound native)`
  - documentation unavailable

- **set_sensitivity_mask**`(*args, **kwargs)`
  - set_sensitivity_mask(self, sensitivity_mask:int)

- **set_support_comment**`(*args, **kwargs)`
  - set_support_comment(self, supports:bool)

- **set_support_exif**`(*args, **kwargs)`
  - set_support_exif(self, supports:bool)

- **set_support_iptc**`(*args, **kwargs)`
  - set_support_iptc(self, supports:bool)

- **set_support_profile**`(*args, **kwargs)`
  - set_support_profile(self, supports:bool)

- **set_support_thumbnail**`(*args, **kwargs)`
  - set_support_thumbnail(self, supports:bool)

- **set_support_xmp**`(*args, **kwargs)`
  - set_support_xmp(self, supports:bool)

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

- **watch_closure**`(self, *args, **kargs)`
  - documentation unavailable

- **weak_ref**`(bound native)`
  - documentation unavailable


