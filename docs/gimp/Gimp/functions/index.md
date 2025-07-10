---
layout: default
title: Gimp.functions
---
# Gimp.functions

## adaptive_supersample_area
- adaptive_supersample_area(x1:int, y1:int, x2:int, y2:int, max_depth:int, threshold:float, render_func:Gimp.RenderFunc, render_data=None, put_pixel_func:Gimp.PutPixelFunc, put_pixel_data=None, progress_func:Gimp.ProgressFunc, progress_data=None) -> int

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



## airbrush
- airbrush(drawable:Gimp.Drawable, pressure:float, strokes:list) -> bool

### Runtime functions †


## airbrush_default
- airbrush_default(drawable:Gimp.Drawable, strokes:list) -> bool

### Runtime functions †


## attach_parasite
- attach_parasite(parasite:Gimp.Parasite) -> bool

### Runtime functions †


## babl_format_get_type
- babl_format_get_type() -> GType

### Runtime functions †


## bilinear
- bilinear(x:float, y:float, values:list) -> float

### Runtime functions †


## bilinear_16
- bilinear_16(x:float, y:float, values:list) -> int

### Runtime functions †


## bilinear_32
- bilinear_32(x:float, y:float, values:list) -> int

### Runtime functions †


## bilinear_8
- bilinear_8(x:float, y:float, values:list) -> int

### Runtime functions †


## bilinear_rgb
- bilinear_rgb(x:float, y:float, values:list, has_alpha:bool, retvalues:list)

### Runtime functions †


## bind_text_domain
- bind_text_domain(domain_name:str, dir_name:str)

### Runtime functions †


## brushes_close_popup
- brushes_close_popup(brush_callback:str) -> bool

### Runtime functions †


## brushes_get_list
- brushes_get_list(filter:str) -> list

### Runtime functions †


## brushes_popup
- brushes_popup(brush_callback:str, popup_title:str, initial_brush:Gimp.Brush=None, parent_window:GLib.Bytes=None) -> bool

### Runtime functions †


## brushes_refresh
- brushes_refresh() -> bool

### Runtime functions †


## brushes_set_popup
- brushes_set_popup(brush_callback:str, brush:Gimp.Brush) -> bool

### Runtime functions †


## buffer_delete
- buffer_delete(buffer_name:str) -> bool

### Runtime functions †


## buffer_get_bytes
- buffer_get_bytes(buffer_name:str) -> int

### Runtime functions †


## buffer_get_height
- buffer_get_height(buffer_name:str) -> int

### Runtime functions †


## buffer_get_image_type
- buffer_get_image_type(buffer_name:str) -> Gimp.ImageType

### Runtime functions †


## buffer_get_width
- buffer_get_width(buffer_name:str) -> int

### Runtime functions †


## buffer_rename
- buffer_rename(buffer_name:str, new_name:str) -> str

### Runtime functions †


## buffers_get_name_list
- buffers_get_name_list(filter:str=None) -> list

### Runtime functions †


## cache_directory
- cache_directory() -> str

### Runtime functions †


## cairo_checkerboard_create
- cairo_checkerboard_create(cr:cairo.Context, size:int, light:Gegl.Color, dark:Gegl.Color) -> cairo.Pattern

### Runtime functions †


## cairo_surface_create_buffer
- cairo_surface_create_buffer(surface:cairo.Surface, format:Babl.Object) -> Gegl.Buffer

### Runtime functions †


## cairo_surface_get_format
- cairo_surface_get_format(surface:cairo.Surface) -> Babl.Object

### Runtime functions †


## canonicalize_identifier
- canonicalize_identifier(identifier:str) -> str

### Runtime functions †


## check_custom_color1
- check_custom_color1() -> Gegl.Color

### Runtime functions †


## check_custom_color2
- check_custom_color2() -> Gegl.Color

### Runtime functions †


## check_size
- check_size() -> Gimp.CheckSize

### Runtime functions †


## check_type
- check_type() -> Gimp.CheckType

### Runtime functions †


## checks_get_colors
- checks_get_colors(type:Gimp.CheckType, color1:Gegl.Color, color2:Gegl.Color) -> color1:Gegl.Color, color2:Gegl.Color

### Runtime functions †


## clone
- clone(drawable:Gimp.Drawable, src_drawable:Gimp.Drawable, clone_type:Gimp.CloneType, src_x:float, src_y:float, strokes:list) -> bool

### Runtime functions †


## clone_default
- clone_default(drawable:Gimp.Drawable, strokes:list) -> bool

### Runtime functions †


## color_array_copy
- color_array_copy(array:Gegl.Color) -> Gegl.Color

### Runtime functions †


## color_array_free
- color_array_free(array:Gegl.Color)

### Runtime functions †


## color_array_get_length
- color_array_get_length(array:Gegl.Color) -> int

### Runtime functions †


## color_array_get_type
- color_array_get_type() -> GType

### Runtime functions †


## color_is_out_of_gamut
- color_is_out_of_gamut(color:Gegl.Color, space:Babl.Object) -> bool

### Runtime functions †


## color_is_out_of_self_gamut
- color_is_out_of_self_gamut(color:Gegl.Color) -> bool

### Runtime functions †


## color_is_perceptually_identical
- color_is_perceptually_identical(color1:Gegl.Color, color2:Gegl.Color) -> bool

### Runtime functions †


## color_list_names
- color_list_names() -> list, colors:list

### Runtime functions †


## color_parse_css
- color_parse_css(css:str) -> Gegl.Color

### Runtime functions †


## color_parse_hex
- color_parse_hex(hex:str) -> Gegl.Color

### Runtime functions †


## color_parse_name
- color_parse_name(name:str) -> Gegl.Color

### Runtime functions †


## color_set_alpha
- color_set_alpha(color:Gegl.Color, alpha:float)

### Runtime functions †


## config_build_data_path
- config_build_data_path(name:str) -> str

### Runtime functions †


## config_build_plug_in_path
- config_build_plug_in_path(name:str) -> str

### Runtime functions †


## config_build_system_path
- config_build_system_path(name:str) -> str

### Runtime functions †


## config_build_writable_path
- config_build_writable_path(name:str) -> str

### Runtime functions †


## config_deserialize_return
- config_deserialize_return(scanner:GLib.Scanner, expected_token:GLib.TokenType, nest_level:int) -> bool

### Runtime functions †


## config_diff
- config_diff(a:GObject.Object, b:GObject.Object, flags:GObject.ParamFlags) -> list

### Runtime functions †


## config_error_quark
- config_error_quark() -> int

### Runtime functions †


## config_param_spec_duplicate
- config_param_spec_duplicate(pspec:GObject.ParamSpec) -> GObject.ParamSpec

### Runtime functions †


## config_reset_properties
- config_reset_properties(object:GObject.Object)

### Runtime functions †


## config_reset_property
- config_reset_property(object:GObject.Object, property_name:str)

### Runtime functions †


## config_serialize_value
- config_serialize_value(value:GObject.Value, str:GLib.String, escaped:bool) -> bool

### Runtime functions †


## config_string_append_escaped
- config_string_append_escaped(string:GLib.String, val:str)

### Runtime functions †


## config_sync
- config_sync(src:GObject.Object, dest:GObject.Object, flags:GObject.ParamFlags) -> bool

### Runtime functions †


## config_type_register
- config_type_register(parent_type:GType, type_name:str, pspecs:list) -> GType

### Runtime functions †


## context_are_dynamics_enabled
- context_are_dynamics_enabled() -> bool

### Runtime functions †


## context_enable_dynamics
- context_enable_dynamics(enable:bool) -> bool

### Runtime functions †


## context_get_antialias
- context_get_antialias() -> bool

### Runtime functions †


## context_get_background
- context_get_background() -> Gegl.Color

### Runtime functions †


## context_get_brush
- context_get_brush() -> Gimp.Brush

### Runtime functions †


## context_get_brush_angle
- context_get_brush_angle() -> float

### Runtime functions †


## context_get_brush_aspect_ratio
- context_get_brush_aspect_ratio() -> float

### Runtime functions †


## context_get_brush_force
- context_get_brush_force() -> float

### Runtime functions †


## context_get_brush_hardness
- context_get_brush_hardness() -> float

### Runtime functions †


## context_get_brush_size
- context_get_brush_size() -> float

### Runtime functions †


## context_get_brush_spacing
- context_get_brush_spacing() -> float

### Runtime functions †


## context_get_diagonal_neighbors
- context_get_diagonal_neighbors() -> bool

### Runtime functions †


## context_get_distance_metric
- context_get_distance_metric() -> Gegl.DistanceMetric

### Runtime functions †


## context_get_dynamics_name
- context_get_dynamics_name() -> str

### Runtime functions †


## context_get_emulate_brush_dynamics
- context_get_emulate_brush_dynamics() -> bool

### Runtime functions †


## context_get_feather
- context_get_feather() -> bool

### Runtime functions †


## context_get_feather_radius
- context_get_feather_radius() -> bool, feather_radius_x:float, feather_radius_y:float

### Runtime functions †


## context_get_font
- context_get_font() -> Gimp.Font

### Runtime functions †


## context_get_foreground
- context_get_foreground() -> Gegl.Color

### Runtime functions †


## context_get_gradient
- context_get_gradient() -> Gimp.Gradient

### Runtime functions †


## context_get_gradient_blend_color_space
- context_get_gradient_blend_color_space() -> Gimp.GradientBlendColorSpace

### Runtime functions †


## context_get_gradient_repeat_mode
- context_get_gradient_repeat_mode() -> Gimp.RepeatMode

### Runtime functions †


## context_get_gradient_reverse
- context_get_gradient_reverse() -> bool

### Runtime functions †


## context_get_ink_angle
- context_get_ink_angle() -> float

### Runtime functions †


## context_get_ink_blob_angle
- context_get_ink_blob_angle() -> float

### Runtime functions †


## context_get_ink_blob_aspect_ratio
- context_get_ink_blob_aspect_ratio() -> float

### Runtime functions †


## context_get_ink_blob_type
- context_get_ink_blob_type() -> Gimp.InkBlobType

### Runtime functions †


## context_get_ink_size
- context_get_ink_size() -> float

### Runtime functions †


## context_get_ink_size_sensitivity
- context_get_ink_size_sensitivity() -> float

### Runtime functions †


## context_get_ink_speed_sensitivity
- context_get_ink_speed_sensitivity() -> float

### Runtime functions †


## context_get_ink_tilt_sensitivity
- context_get_ink_tilt_sensitivity() -> float

### Runtime functions †


## context_get_interpolation
- context_get_interpolation() -> Gimp.InterpolationType

### Runtime functions †


## context_get_line_cap_style
- context_get_line_cap_style() -> Gimp.CapStyle

### Runtime functions †


## context_get_line_dash_offset
- context_get_line_dash_offset() -> float

### Runtime functions †


## context_get_line_dash_pattern
- context_get_line_dash_pattern() -> bool, dashes:list

### Runtime functions †


## context_get_line_join_style
- context_get_line_join_style() -> Gimp.JoinStyle

### Runtime functions †


## context_get_line_miter_limit
- context_get_line_miter_limit() -> float

### Runtime functions †


## context_get_line_width
- context_get_line_width() -> float

### Runtime functions †


## context_get_line_width_unit
- context_get_line_width_unit() -> Gimp.Unit

### Runtime functions †


## context_get_mypaint_brush
- context_get_mypaint_brush() -> str

### Runtime functions †


## context_get_opacity
- context_get_opacity() -> float

### Runtime functions †


## context_get_paint_method
- context_get_paint_method() -> str

### Runtime functions †


## context_get_paint_mode
- context_get_paint_mode() -> Gimp.LayerMode

### Runtime functions †


## context_get_palette
- context_get_palette() -> Gimp.Palette

### Runtime functions †


## context_get_pattern
- context_get_pattern() -> Gimp.Pattern

### Runtime functions †


## context_get_sample_criterion
- context_get_sample_criterion() -> Gimp.SelectCriterion

### Runtime functions †


## context_get_sample_merged
- context_get_sample_merged() -> bool

### Runtime functions †


## context_get_sample_threshold
- context_get_sample_threshold() -> float

### Runtime functions †


## context_get_sample_threshold_int
- context_get_sample_threshold_int() -> int

### Runtime functions †


## context_get_sample_transparent
- context_get_sample_transparent() -> bool

### Runtime functions †


## context_get_stroke_method
- context_get_stroke_method() -> Gimp.StrokeMethod

### Runtime functions †


## context_get_transform_direction
- context_get_transform_direction() -> Gimp.TransformDirection

### Runtime functions †


## context_get_transform_resize
- context_get_transform_resize() -> Gimp.TransformResize

### Runtime functions †


## context_list_paint_methods
- context_list_paint_methods() -> bool, paint_methods:list

### Runtime functions †


## context_pop
- context_pop() -> bool

### Runtime functions †


## context_push
- context_push() -> bool

### Runtime functions †


## context_set_antialias
- context_set_antialias(antialias:bool) -> bool

### Runtime functions †


## context_set_background
- context_set_background(background:Gegl.Color) -> bool

### Runtime functions †


## context_set_brush
- context_set_brush(brush:Gimp.Brush) -> bool

### Runtime functions †


## context_set_brush_angle
- context_set_brush_angle(angle:float) -> bool

### Runtime functions †


## context_set_brush_aspect_ratio
- context_set_brush_aspect_ratio(aspect:float) -> bool

### Runtime functions †


## context_set_brush_default_hardness
- context_set_brush_default_hardness() -> bool

### Runtime functions †


## context_set_brush_default_size
- context_set_brush_default_size() -> bool

### Runtime functions †


## context_set_brush_default_spacing
- context_set_brush_default_spacing() -> bool

### Runtime functions †


## context_set_brush_force
- context_set_brush_force(force:float) -> bool

### Runtime functions †


## context_set_brush_hardness
- context_set_brush_hardness(hardness:float) -> bool

### Runtime functions †


## context_set_brush_size
- context_set_brush_size(size:float) -> bool

### Runtime functions †


## context_set_brush_spacing
- context_set_brush_spacing(spacing:float) -> bool

### Runtime functions †


## context_set_default_colors
- context_set_default_colors() -> bool

### Runtime functions †


## context_set_defaults
- context_set_defaults() -> bool

### Runtime functions †


## context_set_diagonal_neighbors
- context_set_diagonal_neighbors(diagonal_neighbors:bool) -> bool

### Runtime functions †


## context_set_distance_metric
- context_set_distance_metric(metric:Gegl.DistanceMetric) -> bool

### Runtime functions †


## context_set_dynamics_name
- context_set_dynamics_name(name:str) -> bool

### Runtime functions †


## context_set_emulate_brush_dynamics
- context_set_emulate_brush_dynamics(emulate_dynamics:bool) -> bool

### Runtime functions †


## context_set_feather
- context_set_feather(feather:bool) -> bool

### Runtime functions †


## context_set_feather_radius
- context_set_feather_radius(feather_radius_x:float, feather_radius_y:float) -> bool

### Runtime functions †


## context_set_font
- context_set_font(font:Gimp.Font) -> bool

### Runtime functions †


## context_set_foreground
- context_set_foreground(foreground:Gegl.Color) -> bool

### Runtime functions †


## context_set_gradient
- context_set_gradient(gradient:Gimp.Gradient) -> bool

### Runtime functions †


## context_set_gradient_blend_color_space
- context_set_gradient_blend_color_space(blend_color_space:Gimp.GradientBlendColorSpace) -> bool

### Runtime functions †


## context_set_gradient_fg_bg_hsv_ccw
- context_set_gradient_fg_bg_hsv_ccw() -> bool

### Runtime functions †


## context_set_gradient_fg_bg_hsv_cw
- context_set_gradient_fg_bg_hsv_cw() -> bool

### Runtime functions †


## context_set_gradient_fg_bg_rgb
- context_set_gradient_fg_bg_rgb() -> bool

### Runtime functions †


## context_set_gradient_fg_transparent
- context_set_gradient_fg_transparent() -> bool

### Runtime functions †


## context_set_gradient_repeat_mode
- context_set_gradient_repeat_mode(repeat_mode:Gimp.RepeatMode) -> bool

### Runtime functions †


## context_set_gradient_reverse
- context_set_gradient_reverse(reverse:bool) -> bool

### Runtime functions †


## context_set_ink_angle
- context_set_ink_angle(angle:float) -> bool

### Runtime functions †


## context_set_ink_blob_angle
- context_set_ink_blob_angle(angle:float) -> bool

### Runtime functions †


## context_set_ink_blob_aspect_ratio
- context_set_ink_blob_aspect_ratio(aspect:float) -> bool

### Runtime functions †


## context_set_ink_blob_type
- context_set_ink_blob_type(type:Gimp.InkBlobType) -> bool

### Runtime functions †


## context_set_ink_size
- context_set_ink_size(size:float) -> bool

### Runtime functions †


## context_set_ink_size_sensitivity
- context_set_ink_size_sensitivity(size:float) -> bool

### Runtime functions †


## context_set_ink_speed_sensitivity
- context_set_ink_speed_sensitivity(speed:float) -> bool

### Runtime functions †


## context_set_ink_tilt_sensitivity
- context_set_ink_tilt_sensitivity(tilt:float) -> bool

### Runtime functions †


## context_set_interpolation
- context_set_interpolation(interpolation:Gimp.InterpolationType) -> bool

### Runtime functions †


## context_set_line_cap_style
- context_set_line_cap_style(cap_style:Gimp.CapStyle) -> bool

### Runtime functions †


## context_set_line_dash_offset
- context_set_line_dash_offset(dash_offset:float) -> bool

### Runtime functions †


## context_set_line_dash_pattern
- context_set_line_dash_pattern(dashes:list) -> bool

### Runtime functions †


## context_set_line_join_style
- context_set_line_join_style(join_style:Gimp.JoinStyle) -> bool

### Runtime functions †


## context_set_line_miter_limit
- context_set_line_miter_limit(miter_limit:float) -> bool

### Runtime functions †


## context_set_line_width
- context_set_line_width(line_width:float) -> bool

### Runtime functions †


## context_set_line_width_unit
- context_set_line_width_unit(line_width_unit:Gimp.Unit) -> bool

### Runtime functions †


## context_set_mypaint_brush
- context_set_mypaint_brush(name:str) -> bool

### Runtime functions †


## context_set_opacity
- context_set_opacity(opacity:float) -> bool

### Runtime functions †


## context_set_paint_method
- context_set_paint_method(name:str) -> bool

### Runtime functions †


## context_set_paint_mode
- context_set_paint_mode(paint_mode:Gimp.LayerMode) -> bool

### Runtime functions †


## context_set_palette
- context_set_palette(palette:Gimp.Palette) -> bool

### Runtime functions †


## context_set_pattern
- context_set_pattern(pattern:Gimp.Pattern) -> bool

### Runtime functions †


## context_set_sample_criterion
- context_set_sample_criterion(sample_criterion:Gimp.SelectCriterion) -> bool

### Runtime functions †


## context_set_sample_merged
- context_set_sample_merged(sample_merged:bool) -> bool

### Runtime functions †


## context_set_sample_threshold
- context_set_sample_threshold(sample_threshold:float) -> bool

### Runtime functions †


## context_set_sample_threshold_int
- context_set_sample_threshold_int(sample_threshold:int) -> bool

### Runtime functions †


## context_set_sample_transparent
- context_set_sample_transparent(sample_transparent:bool) -> bool

### Runtime functions †


## context_set_stroke_method
- context_set_stroke_method(stroke_method:Gimp.StrokeMethod) -> bool

### Runtime functions †


## context_set_transform_direction
- context_set_transform_direction(transform_direction:Gimp.TransformDirection) -> bool

### Runtime functions †


## context_set_transform_resize
- context_set_transform_resize(transform_resize:Gimp.TransformResize) -> bool

### Runtime functions †


## context_swap_colors
- context_swap_colors() -> bool

### Runtime functions †


## convolve
- convolve(drawable:Gimp.Drawable, pressure:float, convolve_type:Gimp.ConvolveType, strokes:list) -> bool

### Runtime functions †


## convolve_default
- convolve_default(drawable:Gimp.Drawable, strokes:list) -> bool

### Runtime functions †


## core_object_array_get_length
- core_object_array_get_length(array:GObject.Object) -> int

### Runtime functions †


## core_object_array_get_type
- core_object_array_get_type() -> GType

### Runtime functions †


## cpu_accel_get_support
- cpu_accel_get_support() -> Gimp.CpuAccelFlags

### Runtime functions †


## data_directory
- data_directory() -> str

### Runtime functions †


## debug_timer_end
- debug_timer_end() -> float

### Runtime functions †


## debug_timer_start
- debug_timer_start() -> bool

### Runtime functions †


## default_display
- default_display() -> Gimp.Display

### Runtime functions †


## detach_parasite
- detach_parasite(name:str) -> bool

### Runtime functions †


## directory
- directory() -> str

### Runtime functions †


## displays_flush
- displays_flush() -> bool

### Runtime functions †


## displays_reconnect
- displays_reconnect(old_image:Gimp.Image, new_image:Gimp.Image) -> bool

### Runtime functions †


## dodgeburn
- dodgeburn(drawable:Gimp.Drawable, exposure:float, dodgeburn_type:Gimp.DodgeBurnType, dodgeburn_mode:Gimp.TransferMode, strokes:list) -> bool

### Runtime functions †


## dodgeburn_default
- dodgeburn_default(drawable:Gimp.Drawable, strokes:list) -> bool

### Runtime functions †


## double_array_get_values
- double_array_get_values(array:Gimp.Array) -> list

### Runtime functions †


## double_array_set_values
- double_array_set_values(array:Gimp.Array, values:list, static_data:bool)

### Runtime functions †


## drawables_close_popup
- drawables_close_popup(callback:str) -> bool

### Runtime functions †


## drawables_popup
- drawables_popup(callback:str, popup_title:str, drawable_type:str, initial_drawable:Gimp.Drawable=None, parent_window:GLib.Bytes=None) -> bool

### Runtime functions †


## drawables_set_popup
- drawables_set_popup(callback:str, drawable:Gimp.Drawable) -> bool

### Runtime functions †


## dynamics_get_name_list
- dynamics_get_name_list(filter:str=None) -> list

### Runtime functions †


## dynamics_refresh
- dynamics_refresh() -> bool

### Runtime functions †


## edit_copy
- edit_copy(drawables:list) -> bool

### Runtime functions †


## edit_copy_visible
- edit_copy_visible(image:Gimp.Image) -> bool

### Runtime functions †


## edit_cut
- edit_cut(drawables:list) -> bool

### Runtime functions †


## edit_named_copy
- edit_named_copy(drawables:list, buffer_name:str) -> str

### Runtime functions †


## edit_named_copy_visible
- edit_named_copy_visible(image:Gimp.Image, buffer_name:str) -> str

### Runtime functions †


## edit_named_cut
- edit_named_cut(drawables:list, buffer_name:str) -> str

### Runtime functions †


## edit_named_paste
- edit_named_paste(drawable:Gimp.Drawable, buffer_name:str, paste_into:bool) -> Gimp.Layer

### Runtime functions †


## edit_named_paste_as_new_image
- edit_named_paste_as_new_image(buffer_name:str) -> Gimp.Image

### Runtime functions †


## edit_paste
- edit_paste(drawable:Gimp.Drawable, paste_into:bool) -> list

### Runtime functions †


## edit_paste_as_new_image
- edit_paste_as_new_image() -> Gimp.Image

### Runtime functions †


## enum_get_desc
- enum_get_desc(enum_class:GObject.EnumClass, value:int) -> Gimp.EnumDesc or None

### Runtime functions †


## enum_get_value
- enum_get_value(enum_type:GType, value:int) -> bool, value_name:str, value_nick:str, value_desc:str, value_help:str

### Runtime functions †


## enum_get_value_descriptions
- enum_get_value_descriptions(enum_type:GType) -> Gimp.EnumDesc

### Runtime functions †


## enum_set_value_descriptions
- enum_set_value_descriptions(enum_type:GType, descriptions:Gimp.EnumDesc)

### Runtime functions †


## enum_value_get_abbrev
- enum_value_get_abbrev(enum_class:GObject.EnumClass, enum_value:GObject.EnumValue) -> str

### Runtime functions †


## enum_value_get_desc
- enum_value_get_desc(enum_class:GObject.EnumClass, enum_value:GObject.EnumValue) -> str

### Runtime functions †


## enum_value_get_help
- enum_value_get_help(enum_class:GObject.EnumClass, enum_value:GObject.EnumValue) -> str

### Runtime functions †


## enums_get_type_names
- enums_get_type_names() -> list

### Runtime functions †


## enums_init
- enums_init()

### Runtime functions †


## eraser
- eraser(drawable:Gimp.Drawable, strokes:list, hardness:Gimp.BrushApplicationMode, method:Gimp.PaintApplicationMode) -> bool

### Runtime functions †


## eraser_default
- eraser_default(drawable:Gimp.Drawable, strokes:list) -> bool

### Runtime functions †


## escape_uline
- escape_uline(str:str=None) -> str

### Runtime functions †


## export_color_profile
- export_color_profile() -> bool

### Runtime functions †


## export_comment
- export_comment() -> bool

### Runtime functions †


## export_exif
- export_exif() -> bool

### Runtime functions †


## export_iptc
- export_iptc() -> bool

### Runtime functions †


## export_thumbnail
- export_thumbnail() -> bool

### Runtime functions †


## export_xmp
- export_xmp() -> bool

### Runtime functions †


## file_create_thumbnail
- file_create_thumbnail(image:Gimp.Image, file:Gio.File) -> bool

### Runtime functions †


## file_get_config_path
- file_get_config_path(file:Gio.File) -> str

### Runtime functions †


## file_get_utf8_name
- file_get_utf8_name(file:Gio.File) -> str

### Runtime functions †


## file_has_extension
- file_has_extension(file:Gio.File, extension:str) -> bool

### Runtime functions †


## file_load
- file_load(run_mode:Gimp.RunMode, file:Gio.File) -> Gimp.Image

### Runtime functions †


## file_load_layer
- file_load_layer(run_mode:Gimp.RunMode, image:Gimp.Image, file:Gio.File) -> Gimp.Layer

### Runtime functions †


## file_load_layers
- file_load_layers(run_mode:Gimp.RunMode, image:Gimp.Image, file:Gio.File) -> list

### Runtime functions †


## file_new_for_config_path
- file_new_for_config_path(path:str) -> Gio.File or None

### Runtime functions †


## file_save
- file_save(run_mode:Gimp.RunMode, image:Gimp.Image, file:Gio.File, options:Gimp.ExportOptions=None) -> bool

### Runtime functions †


## file_show_in_file_manager
- file_show_in_file_manager(file:Gio.File) -> bool

### Runtime functions †


## filename_to_utf8
- filename_to_utf8(filename:str) -> str

### Runtime functions †


## flags_get_first_desc
- flags_get_first_desc(flags_class:GObject.FlagsClass, value:int) -> Gimp.FlagsDesc or None

### Runtime functions †


## flags_get_first_value
- flags_get_first_value(flags_type:GType, value:int) -> bool, value_name:str, value_nick:str, value_desc:str, value_help:str

### Runtime functions †


## flags_get_value_descriptions
- flags_get_value_descriptions(flags_type:GType) -> Gimp.FlagsDesc

### Runtime functions †


## flags_set_value_descriptions
- flags_set_value_descriptions(flags_type:GType, descriptions:Gimp.FlagsDesc)

### Runtime functions †


## flags_value_get_abbrev
- flags_value_get_abbrev(flags_class:GObject.FlagsClass, flags_value:GObject.FlagsValue) -> str

### Runtime functions †


## flags_value_get_desc
- flags_value_get_desc(flags_class:GObject.FlagsClass, flags_value:GObject.FlagsValue) -> str

### Runtime functions †


## flags_value_get_help
- flags_value_get_help(flags_class:GObject.FlagsClass, flags_value:GObject.FlagsValue) -> str

### Runtime functions †


## floating_sel_anchor
- floating_sel_anchor(floating_sel:Gimp.Layer) -> bool

### Runtime functions †


## floating_sel_attach
- floating_sel_attach(layer:Gimp.Layer, drawable:Gimp.Drawable) -> bool

### Runtime functions †


## floating_sel_remove
- floating_sel_remove(floating_sel:Gimp.Layer) -> bool

### Runtime functions †


## floating_sel_to_layer
- floating_sel_to_layer(floating_sel:Gimp.Layer) -> bool

### Runtime functions †


## fonts_close_popup
- fonts_close_popup(font_callback:str) -> bool

### Runtime functions †


## fonts_get_list
- fonts_get_list(filter:str=None) -> list

### Runtime functions †


## fonts_popup
- fonts_popup(font_callback:str, popup_title:str, initial_font:Gimp.Font=None, parent_window:GLib.Bytes=None) -> bool

### Runtime functions †


## fonts_refresh
- fonts_refresh() -> bool

### Runtime functions †


## fonts_set_popup
- fonts_set_popup(font_callback:str, font:Gimp.Font) -> bool

### Runtime functions †


## get_color_configuration
- get_color_configuration() -> Gimp.ColorConfig

### Runtime functions †


## get_default_comment
- get_default_comment() -> str

### Runtime functions †


## get_default_unit
- get_default_unit() -> Gimp.Unit

### Runtime functions †


## get_images
- get_images() -> list

### Runtime functions †


## get_module_load_inhibit
- get_module_load_inhibit() -> str

### Runtime functions †


## get_monitor_resolution
- get_monitor_resolution() -> bool, xres:float, yres:float

### Runtime functions †


## get_num_processors
- get_num_processors() -> int

### Runtime functions †


## get_parasite
- get_parasite(name:str) -> Gimp.Parasite

### Runtime functions †


## get_parasite_list
- get_parasite_list() -> list

### Runtime functions †


## get_pdb
- get_pdb() -> Gimp.PDB or None

### Runtime functions †


## get_plug_in
- get_plug_in() -> Gimp.PlugIn or None

### Runtime functions †


## get_progname
- get_progname() -> str

### Runtime functions †


## getpid
- getpid() -> int

### Runtime functions †


## gimprc_query
- gimprc_query(token:str) -> str

### Runtime functions †


## gimprc_set
- gimprc_set(token:str, value:str) -> bool

### Runtime functions †


## gradients_close_popup
- gradients_close_popup(gradient_callback:str) -> bool

### Runtime functions †


## gradients_get_list
- gradients_get_list(filter:str=None) -> list

### Runtime functions †


## gradients_popup
- gradients_popup(gradient_callback:str, popup_title:str, initial_gradient:Gimp.Gradient=None, parent_window:GLib.Bytes=None) -> bool

### Runtime functions †


## gradients_refresh
- gradients_refresh() -> bool

### Runtime functions †


## gradients_set_popup
- gradients_set_popup(gradient_callback:str, gradient:Gimp.Gradient) -> bool

### Runtime functions †


## heal
- heal(drawable:Gimp.Drawable, src_drawable:Gimp.Drawable, src_x:float, src_y:float, strokes:list) -> bool

### Runtime functions †


## heal_default
- heal_default(drawable:Gimp.Drawable, strokes:list) -> bool

### Runtime functions †


## help
- help(help_domain:str=None, help_id:str) -> bool

### Runtime functions †


## icon_theme_dir
- icon_theme_dir() -> str

### Runtime functions †


## installation_directory
- installation_directory() -> str

### Runtime functions †


## int32_array_get_values
- int32_array_get_values(array:Gimp.Array) -> list

### Runtime functions †


## int32_array_set_values
- int32_array_set_values(array:Gimp.Array, values:list, static_data:bool)

### Runtime functions †


## is_canonical_identifier
- is_canonical_identifier(identifier:str) -> bool

### Runtime functions †


## locale_directory
- locale_directory() -> str

### Runtime functions †


## main
- main(plug_in_type:GType, argv:list) -> int

### Runtime functions †


## message
- message(message:str) -> bool

### Runtime functions †


## message_get_handler
- message_get_handler() -> Gimp.MessageHandlerType

### Runtime functions †


## message_set_handler
- message_set_handler(handler:Gimp.MessageHandlerType) -> bool

### Runtime functions †


## monitor_number
- monitor_number() -> int

### Runtime functions †


## paintbrush
- paintbrush(drawable:Gimp.Drawable, fade_out:float, strokes:list, method:Gimp.PaintApplicationMode, gradient_length:float) -> bool

### Runtime functions †


## paintbrush_default
- paintbrush_default(drawable:Gimp.Drawable, strokes:list) -> bool

### Runtime functions †


## palettes_close_popup
- palettes_close_popup(palette_callback:str) -> bool

### Runtime functions †


## palettes_get_list
- palettes_get_list(filter:str=None) -> list

### Runtime functions †


## palettes_popup
- palettes_popup(palette_callback:str, popup_title:str, initial_palette:Gimp.Palette=None, parent_window:GLib.Bytes=None) -> bool

### Runtime functions †


## palettes_refresh
- palettes_refresh() -> bool

### Runtime functions †


## palettes_set_popup
- palettes_set_popup(palette_callback:str, palette:Gimp.Palette) -> bool

### Runtime functions †


## param_spec_array
- param_spec_array(name:str, nick:str, blurb:str, flags:GObject.ParamFlags) -> GObject.ParamSpec

### Runtime functions †


## param_spec_brush
- param_spec_brush(name:str, nick:str, blurb:str, none_ok:bool, default_value:Gimp.Brush=None, default_to_context:bool, flags:GObject.ParamFlags) -> GObject.ParamSpec

### Runtime functions †


## param_spec_channel
- param_spec_channel(name:str, nick:str, blurb:str, none_ok:bool, flags:GObject.ParamFlags) -> GObject.ParamSpec

### Runtime functions †


## param_spec_choice
- param_spec_choice(name:str, nick:str, blurb:str, choice:Gimp.Choice, default_value:str, flags:GObject.ParamFlags) -> GObject.ParamSpec

### Runtime functions †


## param_spec_choice_get_choice
- param_spec_choice_get_choice(pspec:GObject.ParamSpec) -> Gimp.Choice

### Runtime functions †


## param_spec_choice_get_default
- param_spec_choice_get_default(pspec:GObject.ParamSpec) -> str

### Runtime functions †


## param_spec_color
- param_spec_color(name:str, nick:str, blurb:str, has_alpha:bool, default_color:Gegl.Color, flags:GObject.ParamFlags) -> GObject.ParamSpec

### Runtime functions †


## param_spec_color_from_string
- param_spec_color_from_string(name:str, nick:str, blurb:str, has_alpha:bool, default_color_string:str, flags:GObject.ParamFlags) -> GObject.ParamSpec

### Runtime functions †


## param_spec_color_has_alpha
- param_spec_color_has_alpha(pspec:GObject.ParamSpec) -> bool

### Runtime functions †


## param_spec_config_path
- param_spec_config_path(name:str, nick:str, blurb:str, type:Gimp.ConfigPathType, default_value:str, flags:GObject.ParamFlags) -> GObject.ParamSpec

### Runtime functions †


## param_spec_config_path_type
- param_spec_config_path_type(pspec:GObject.ParamSpec) -> Gimp.ConfigPathType

### Runtime functions †


## param_spec_core_object_array
- param_spec_core_object_array(name:str, nick:str, blurb:str, object_type:GType, flags:GObject.ParamFlags) -> GObject.ParamSpec

### Runtime functions †


## param_spec_core_object_array_get_object_type
- param_spec_core_object_array_get_object_type(pspec:GObject.ParamSpec) -> GType

### Runtime functions †


## param_spec_display
- param_spec_display(name:str, nick:str, blurb:str, none_ok:bool, flags:GObject.ParamFlags) -> GObject.ParamSpec

### Runtime functions †


## param_spec_display_none_allowed
- param_spec_display_none_allowed(pspec:GObject.ParamSpec) -> bool

### Runtime functions †


## param_spec_double_array
- param_spec_double_array(name:str, nick:str, blurb:str, flags:GObject.ParamFlags) -> GObject.ParamSpec

### Runtime functions †


## param_spec_drawable
- param_spec_drawable(name:str, nick:str, blurb:str, none_ok:bool, flags:GObject.ParamFlags) -> GObject.ParamSpec

### Runtime functions †


## param_spec_drawable_filter
- param_spec_drawable_filter(name:str, nick:str, blurb:str, none_ok:bool, flags:GObject.ParamFlags) -> GObject.ParamSpec

### Runtime functions †


## param_spec_drawable_filter_none_allowed
- param_spec_drawable_filter_none_allowed(pspec:GObject.ParamSpec) -> bool

### Runtime functions †


## param_spec_export_options
- param_spec_export_options(name:str, nick:str, blurb:str, flags:GObject.ParamFlags) -> GObject.ParamSpec

### Runtime functions †


## param_spec_file
- param_spec_file(name:str, nick:str, blurb:str, action:Gimp.FileChooserAction, none_ok:bool, default_value:Gio.File=None, flags:GObject.ParamFlags) -> GObject.ParamSpec

### Runtime functions †


## param_spec_file_get_action
- param_spec_file_get_action(pspec:GObject.ParamSpec) -> Gimp.FileChooserAction

### Runtime functions †


## param_spec_file_none_allowed
- param_spec_file_none_allowed(pspec:GObject.ParamSpec) -> bool

### Runtime functions †


## param_spec_file_set_action
- param_spec_file_set_action(pspec:GObject.ParamSpec, action:Gimp.FileChooserAction)

### Runtime functions †


## param_spec_font
- param_spec_font(name:str, nick:str, blurb:str, none_ok:bool, default_value:Gimp.Font=None, default_to_context:bool, flags:GObject.ParamFlags) -> GObject.ParamSpec

### Runtime functions †


## param_spec_gradient
- param_spec_gradient(name:str, nick:str, blurb:str, none_ok:bool, default_value:Gimp.Gradient=None, default_to_context:bool, flags:GObject.ParamFlags) -> GObject.ParamSpec

### Runtime functions †


## param_spec_group_layer
- param_spec_group_layer(name:str, nick:str, blurb:str, none_ok:bool, flags:GObject.ParamFlags) -> GObject.ParamSpec

### Runtime functions †


## param_spec_image
- param_spec_image(name:str, nick:str, blurb:str, none_ok:bool, flags:GObject.ParamFlags) -> GObject.ParamSpec

### Runtime functions †


## param_spec_image_none_allowed
- param_spec_image_none_allowed(pspec:GObject.ParamSpec) -> bool

### Runtime functions †


## param_spec_int32_array
- param_spec_int32_array(name:str, nick:str, blurb:str, flags:GObject.ParamFlags) -> GObject.ParamSpec

### Runtime functions †


## param_spec_item
- param_spec_item(name:str, nick:str, blurb:str, none_ok:bool, flags:GObject.ParamFlags) -> GObject.ParamSpec

### Runtime functions †


## param_spec_item_none_allowed
- param_spec_item_none_allowed(pspec:GObject.ParamSpec) -> bool

### Runtime functions †


## param_spec_layer
- param_spec_layer(name:str, nick:str, blurb:str, none_ok:bool, flags:GObject.ParamFlags) -> GObject.ParamSpec

### Runtime functions †


## param_spec_layer_mask
- param_spec_layer_mask(name:str, nick:str, blurb:str, none_ok:bool, flags:GObject.ParamFlags) -> GObject.ParamSpec

### Runtime functions †


## param_spec_matrix2
- param_spec_matrix2(name:str, nick:str, blurb:str, default_value:Gimp.Matrix2, flags:GObject.ParamFlags) -> GObject.ParamSpec

### Runtime functions †


## param_spec_matrix3
- param_spec_matrix3(name:str, nick:str, blurb:str, default_value:Gimp.Matrix3, flags:GObject.ParamFlags) -> GObject.ParamSpec

### Runtime functions †


## param_spec_memsize
- param_spec_memsize(name:str, nick:str, blurb:str, minimum:int, maximum:int, default_value:int, flags:GObject.ParamFlags) -> GObject.ParamSpec

### Runtime functions †


## param_spec_object_duplicate
- param_spec_object_duplicate(pspec:GObject.ParamSpec) -> GObject.ParamSpec

### Runtime functions †


## param_spec_object_get_default
- param_spec_object_get_default(pspec:GObject.ParamSpec) -> GObject.Object

### Runtime functions †


## param_spec_object_has_default
- param_spec_object_has_default(pspec:GObject.ParamSpec) -> bool

### Runtime functions †


## param_spec_object_set_default
- param_spec_object_set_default(pspec:GObject.ParamSpec, default_value:GObject.Object=None)

### Runtime functions †


## param_spec_palette
- param_spec_palette(name:str, nick:str, blurb:str, none_ok:bool, default_value:Gimp.Palette=None, default_to_context:bool, flags:GObject.ParamFlags) -> GObject.ParamSpec

### Runtime functions †


## param_spec_parasite
- param_spec_parasite(name:str, nick:str, blurb:str, flags:GObject.ParamFlags) -> GObject.ParamSpec

### Runtime functions †


## param_spec_path
- param_spec_path(name:str, nick:str, blurb:str, none_ok:bool, flags:GObject.ParamFlags) -> GObject.ParamSpec

### Runtime functions †


## param_spec_pattern
- param_spec_pattern(name:str, nick:str, blurb:str, none_ok:bool, default_value:Gimp.Pattern=None, default_to_context:bool, flags:GObject.ParamFlags) -> GObject.ParamSpec

### Runtime functions †


## param_spec_resource
- param_spec_resource(name:str, nick:str, blurb:str, resource_type:GType, none_ok:bool, default_value:Gimp.Resource=None, default_to_context:bool, flags:GObject.ParamFlags) -> GObject.ParamSpec

### Runtime functions †


## param_spec_resource_defaults_to_context
- param_spec_resource_defaults_to_context(pspec:GObject.ParamSpec) -> bool

### Runtime functions †


## param_spec_resource_none_allowed
- param_spec_resource_none_allowed(pspec:GObject.ParamSpec) -> bool

### Runtime functions †


## param_spec_selection
- param_spec_selection(name:str, nick:str, blurb:str, none_ok:bool, flags:GObject.ParamFlags) -> GObject.ParamSpec

### Runtime functions †


## param_spec_text_layer
- param_spec_text_layer(name:str, nick:str, blurb:str, none_ok:bool, flags:GObject.ParamFlags) -> GObject.ParamSpec

### Runtime functions †


## param_spec_unit
- param_spec_unit(name:str, nick:str, blurb:str, allow_pixel:bool, allow_percent:bool, default_value:Gimp.Unit, flags:GObject.ParamFlags) -> GObject.ParamSpec

### Runtime functions †


## param_spec_unit_percent_allowed
- param_spec_unit_percent_allowed(pspec:GObject.ParamSpec) -> bool

### Runtime functions †


## param_spec_unit_pixel_allowed
- param_spec_unit_pixel_allowed(pspec:GObject.ParamSpec) -> bool

### Runtime functions †


## param_spec_value_array
- param_spec_value_array(name:str, nick:str, blurb:str, element_spec:GObject.ParamSpec=None, flags:GObject.ParamFlags) -> GObject.ParamSpec

### Runtime functions †


## param_spec_value_array_get_element_spec
- param_spec_value_array_get_element_spec(pspec:GObject.ParamSpec) -> GObject.ParamSpec

### Runtime functions †


## patterns_close_popup
- patterns_close_popup(pattern_callback:str) -> bool

### Runtime functions †


## patterns_get_list
- patterns_get_list(filter:str=None) -> list

### Runtime functions †


## patterns_popup
- patterns_popup(pattern_callback:str, popup_title:str, initial_pattern:Gimp.Pattern=None, parent_window:GLib.Bytes=None) -> bool

### Runtime functions †


## patterns_refresh
- patterns_refresh() -> bool

### Runtime functions †


## patterns_set_popup
- patterns_set_popup(pattern_callback:str, pattern:Gimp.Pattern) -> bool

### Runtime functions †


## pencil
- pencil(drawable:Gimp.Drawable, strokes:list) -> bool

### Runtime functions †


## pixbuf_create_buffer
- pixbuf_create_buffer(pixbuf:GdkPixbuf.Pixbuf) -> Gegl.Buffer

### Runtime functions †


## pixbuf_get_format
- pixbuf_get_format(pixbuf:GdkPixbuf.Pixbuf) -> Babl.Object

### Runtime functions †


## pixbuf_get_icc_profile
- pixbuf_get_icc_profile(pixbuf:GdkPixbuf.Pixbuf) -> list or None

### Runtime functions †


## pixels_to_units
- pixels_to_units(pixels:float, unit:Gimp.Unit, resolution:float) -> float

### Runtime functions †


## pixpipe_params_build
- pixpipe_params_build(params:Gimp.PixPipeParams) -> str

### Runtime functions †


## pixpipe_params_free
- pixpipe_params_free(params:Gimp.PixPipeParams)

### Runtime functions †


## pixpipe_params_init
- pixpipe_params_init(params:Gimp.PixPipeParams)

### Runtime functions †


## pixpipe_params_parse
- pixpipe_params_parse(parameters:str, params:Gimp.PixPipeParams)

### Runtime functions †


## progress_cancel
- progress_cancel(progress_callback:str) -> bool

### Runtime functions †


## progress_end
- progress_end() -> bool

### Runtime functions †


## progress_get_window_handle
- progress_get_window_handle() -> GLib.Bytes

### Runtime functions †


## progress_init
- progress_init(message:str) -> bool

### Runtime functions †


## progress_install_vtable
- progress_install_vtable(vtable:Gimp.ProgressVtable, user_data=None, user_data_destroy:GLib.DestroyNotify=None) -> str

### Runtime functions †


## progress_pulse
- progress_pulse() -> bool

### Runtime functions †


## progress_set_text
- progress_set_text(message:str=None) -> bool

### Runtime functions †


## progress_uninstall
- progress_uninstall(progress_callback:str)

### Runtime functions †


## progress_update
- progress_update(percentage:float) -> bool

### Runtime functions †


## quit
- quit()

### Runtime functions †


## range_estimate_settings
- range_estimate_settings(lower:float, upper:float) -> step:float, page:float, digits:int

### Runtime functions †


## rectangle_intersect
- rectangle_intersect(x1:int, y1:int, width1:int, height1:int, x2:int, y2:int, width2:int, height2:int) -> bool, dest_x:int, dest_y:int, dest_width:int, dest_height:int

### Runtime functions †


## rectangle_union
- rectangle_union(x1:int, y1:int, width1:int, height1:int, x2:int, y2:int, width2:int, height2:int) -> dest_x:int, dest_y:int, dest_width:int, dest_height:int

### Runtime functions †


## show_help_button
- show_help_button() -> bool

### Runtime functions †


## smudge
- smudge(drawable:Gimp.Drawable, pressure:float, strokes:list) -> bool

### Runtime functions †


## smudge_default
- smudge_default(drawable:Gimp.Drawable, strokes:list) -> bool

### Runtime functions †


## stack_trace_available
- stack_trace_available(optimal:bool) -> bool

### Runtime functions †


## stack_trace_print
- stack_trace_print(prog_name:str, stream=None) -> bool, trace:str

### Runtime functions †


## stack_trace_query
- stack_trace_query(prog_name:str)

### Runtime functions †


## strip_uline
- strip_uline(str:str=None) -> str

### Runtime functions †


## sysconf_directory
- sysconf_directory() -> str

### Runtime functions †


## temp_directory
- temp_directory() -> str

### Runtime functions †


## temp_file
- temp_file(extension:str=None) -> Gio.File

### Runtime functions †


## text_font
- text_font(image:Gimp.Image, drawable:Gimp.Drawable=None, x:float, y:float, text:str, border:int, antialias:bool, size:float, font:Gimp.Font) -> Gimp.Layer or None

### Runtime functions †


## text_get_extents_font
- text_get_extents_font(text:str, size:float, font:Gimp.Font) -> bool, width:int, height:int, ascent:int, descent:int

### Runtime functions †


## tile_height
- tile_height() -> int

### Runtime functions †


## tile_width
- tile_width() -> int

### Runtime functions †


## type_get_translation_context
- type_get_translation_context(type:GType) -> str

### Runtime functions †


## type_get_translation_domain
- type_get_translation_domain(type:GType) -> str

### Runtime functions †


## type_set_translation_context
- type_set_translation_context(type:GType, context:str)

### Runtime functions †


## type_set_translation_domain
- type_set_translation_domain(type:GType, domain:str)

### Runtime functions †


## units_to_pixels
- units_to_pixels(value:float, unit:Gimp.Unit, resolution:float) -> float

### Runtime functions †


## units_to_points
- units_to_points(value:float, unit:Gimp.Unit, resolution:float) -> float

### Runtime functions †


## user_time
- user_time() -> int

### Runtime functions †


## utf8_strtrim
- utf8_strtrim(str:str=None, max_chars:int) -> str

### Runtime functions †


## value_dup_double_array
- value_dup_double_array(value:GObject.Value) -> list

### Runtime functions †


## value_dup_int32_array
- value_dup_int32_array(value:GObject.Value) -> list

### Runtime functions †


## value_get_double_array
- value_get_double_array(value:GObject.Value) -> list

### Runtime functions †


## value_get_int32_array
- value_get_int32_array(value:GObject.Value) -> list

### Runtime functions †


## value_set_double_array
- value_set_double_array(value:GObject.Value, data:list)

### Runtime functions †


## value_set_int32_array
- value_set_int32_array(value:GObject.Value, data:list)

### Runtime functions †


## value_set_static_double_array
- value_set_static_double_array(value:GObject.Value, data:list)

### Runtime functions †


## value_set_static_int32_array
- value_set_static_int32_array(value:GObject.Value, data:list)

### Runtime functions †


## value_take_double_array
- value_take_double_array(value:GObject.Value, data:list)

### Runtime functions †


## value_take_int32_array
- value_take_int32_array(value:GObject.Value, data:list)

### Runtime functions †


## vector2_add
- vector2_add(vector1:Gimp.Vector2, vector2:Gimp.Vector2) -> result:Gimp.Vector2

### Runtime functions †


## vector2_sub
- vector2_sub(vector1:Gimp.Vector2, vector2:Gimp.Vector2) -> result:Gimp.Vector2

### Runtime functions †


## vector3_add
- vector3_add(vector1:Gimp.Vector3, vector2:Gimp.Vector3) -> result:Gimp.Vector3

### Runtime functions †


## vector3_sub
- vector3_sub(vector1:Gimp.Vector3, vector2:Gimp.Vector3) -> result:Gimp.Vector3

### Runtime functions †


## vector_2d_to_3d
- vector_2d_to_3d(sx:int, sy:int, w:int, h:int, x:int, y:int, vp:Gimp.Vector3, p:Gimp.Vector3)

### Runtime functions †


## vector_2d_to_3d_val
- vector_2d_to_3d_val(sx:int, sy:int, w:int, h:int, x:int, y:int, vp:Gimp.Vector3, p:Gimp.Vector3) -> Gimp.Vector3

### Runtime functions †


## vector_3d_to_2d
- vector_3d_to_2d(sx:int, sy:int, w:int, h:int, vp:Gimp.Vector3, p:Gimp.Vector3) -> x:float, y:float

### Runtime functions †


## version
- version() -> str

### Runtime functions †


## wm_class
- wm_class() -> str

### Runtime functions †

