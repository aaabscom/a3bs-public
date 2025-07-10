---
layout: default
title: GLib.functions
---
# GLib.functions

## access
- access(filename:str, mode:int) -> int

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



## aligned_alloc
- aligned_alloc(n_blocks:int, n_block_bytes:int, alignment:int)

### Runtime functions †


## aligned_alloc0
- aligned_alloc0(n_blocks:int, n_block_bytes:int, alignment:int)

### Runtime functions †


## aligned_free
- aligned_free(mem=None)

### Runtime functions †


## aligned_free_sized
- aligned_free_sized(mem=None, alignment:int, size:int)

### Runtime functions †


## ascii_digit_value
- ascii_digit_value(c:int) -> int

### Runtime functions †


## ascii_dtostr
- ascii_dtostr(buffer:str, buf_len:int, d:float) -> str

### Runtime functions †


## ascii_formatd
- ascii_formatd(buffer:str, buf_len:int, format:str, d:float) -> str

### Runtime functions †


## ascii_strcasecmp
- ascii_strcasecmp(s1:str, s2:str) -> int

### Runtime functions †


## ascii_strdown
- ascii_strdown(str:str, len:int) -> str

### Runtime functions †


## ascii_string_to_signed
- ascii_string_to_signed(str:str, base:int, min:int, max:int) -> bool, out_num:int

### Runtime functions †


## ascii_string_to_unsigned
- ascii_string_to_unsigned(str:str, base:int, min:int, max:int) -> bool, out_num:int

### Runtime functions †


## ascii_strncasecmp
- ascii_strncasecmp(s1:str, s2:str, n:int) -> int

### Runtime functions †


## ascii_strtod
- ascii_strtod(nptr:str) -> float, endptr:str

### Runtime functions †


## ascii_strtoll
- ascii_strtoll(nptr:str, base:int) -> int, endptr:str

### Runtime functions †


## ascii_strtoull
- ascii_strtoull(nptr:str, base:int) -> int, endptr:str

### Runtime functions †


## ascii_strup
- ascii_strup(str:str, len:int) -> str

### Runtime functions †


## ascii_tolower
- ascii_tolower(c:int) -> int

### Runtime functions †


## ascii_toupper
- ascii_toupper(c:int) -> int

### Runtime functions †


## ascii_xdigit_value
- ascii_xdigit_value(c:int) -> int

### Runtime functions †


## assert_warning
- assert_warning(log_domain:str, file:str, line:int, pretty_function:str, expression:str)

### Runtime functions †


## assertion_message
- assertion_message(domain:str, file:str, line:int, func:str, message:str)

### Runtime functions †


## assertion_message_cmpint
- assertion_message_cmpint(domain:str, file:str, line:int, func:str, expr:str, arg1:int, cmp:str, arg2:int, numtype:int)

### Runtime functions †


## assertion_message_cmpstr
- assertion_message_cmpstr(domain:str, file:str, line:int, func:str, expr:str, arg1:str, cmp:str, arg2:str)

### Runtime functions †


## assertion_message_cmpstrv
- assertion_message_cmpstrv(domain:str, file:str, line:int, func:str, expr:str, arg1:str, arg2:str, first_wrong_idx:int)

### Runtime functions †


## assertion_message_error
- assertion_message_error(domain:str, file:str, line:int, func:str, expr:str, error:error, error_domain:int, error_code:int)

### Runtime functions †


## async_queue_new
- async_queue_new() -> GLib.AsyncQueue

### Runtime functions †


## async_queue_new_full
- async_queue_new_full(item_free_func:GLib.DestroyNotify=None) -> GLib.AsyncQueue

### Runtime functions †


## atexit
- atexit(func:GLib.VoidFunc)

### Runtime functions †


## atomic_int_add
- atomic_int_add(atomic:int, val:int) -> int

### Runtime functions †


## atomic_int_and
- atomic_int_and(atomic:int, val:int) -> int

### Runtime functions †


## atomic_int_compare_and_exchange
- atomic_int_compare_and_exchange(atomic:int, oldval:int, newval:int) -> bool

### Runtime functions †


## atomic_int_compare_and_exchange_full
- atomic_int_compare_and_exchange_full(atomic:int, oldval:int, newval:int) -> bool, preval:int

### Runtime functions †


## atomic_int_dec_and_test
- atomic_int_dec_and_test(atomic:int) -> bool

### Runtime functions †


## atomic_int_exchange
- atomic_int_exchange(atomic:int, newval:int) -> int

### Runtime functions †


## atomic_int_exchange_and_add
- atomic_int_exchange_and_add(atomic:int, val:int) -> int

### Runtime functions †


## atomic_int_get
- atomic_int_get(atomic:int) -> int

### Runtime functions †


## atomic_int_inc
- atomic_int_inc(atomic:int)

### Runtime functions †


## atomic_int_or
- atomic_int_or(atomic:int, val:int) -> int

### Runtime functions †


## atomic_int_set
- atomic_int_set(atomic:int, newval:int)

### Runtime functions †


## atomic_int_xor
- atomic_int_xor(atomic:int, val:int) -> int

### Runtime functions †


## atomic_pointer_add
- atomic_pointer_add(atomic, val:int) -> int

### Runtime functions †


## atomic_pointer_and
- atomic_pointer_and(atomic, val:int) -> int

### Runtime functions †


## atomic_pointer_compare_and_exchange
- atomic_pointer_compare_and_exchange(atomic, oldval=None, newval=None) -> bool

### Runtime functions †


## atomic_pointer_compare_and_exchange_full
- atomic_pointer_compare_and_exchange_full(atomic, oldval=None, newval=None) -> bool, preval

### Runtime functions †


## atomic_pointer_exchange
- atomic_pointer_exchange(atomic=None, newval=None)

### Runtime functions †


## atomic_pointer_get
- atomic_pointer_get(atomic)

### Runtime functions †


## atomic_pointer_or
- atomic_pointer_or(atomic, val:int) -> int

### Runtime functions †


## atomic_pointer_set
- atomic_pointer_set(atomic, newval=None)

### Runtime functions †


## atomic_pointer_xor
- atomic_pointer_xor(atomic, val:int) -> int

### Runtime functions †


## atomic_rc_box_acquire
- atomic_rc_box_acquire(mem_block)

### Runtime functions †


## atomic_rc_box_alloc
- atomic_rc_box_alloc(block_size:int)

### Runtime functions †


## atomic_rc_box_alloc0
- atomic_rc_box_alloc0(block_size:int)

### Runtime functions †


## atomic_rc_box_dup
- atomic_rc_box_dup(block_size:int, mem_block)

### Runtime functions †


## atomic_rc_box_get_size
- atomic_rc_box_get_size(mem_block) -> int

### Runtime functions †


## atomic_rc_box_release
- atomic_rc_box_release(mem_block)

### Runtime functions †


## atomic_rc_box_release_full
- atomic_rc_box_release_full(mem_block, clear_func:GLib.DestroyNotify)

### Runtime functions †


## atomic_ref_count_compare
- atomic_ref_count_compare(arc:int, val:int) -> bool

### Runtime functions †


## atomic_ref_count_dec
- atomic_ref_count_dec(arc:int) -> bool

### Runtime functions †


## atomic_ref_count_inc
- atomic_ref_count_inc(arc:int)

### Runtime functions †


## atomic_ref_count_init
- atomic_ref_count_init(arc:int)

### Runtime functions †


## base64_decode
- base64_decode(text:str) -> list

### Runtime functions †


## base64_decode_inplace
- base64_decode_inplace(text:list) -> int, text:list

### Runtime functions †


## base64_encode
- base64_encode(data:list=None) -> str

### Runtime functions †


## base64_encode_close
- base64_encode_close(break_lines:bool, state:int, save:int) -> int, out:list, state:int, save:int

### Runtime functions †


## base64_encode_step
- base64_encode_step(in_:list, break_lines:bool, state:int, save:int) -> int, out:list, state:int, save:int

### Runtime functions †


## basename
- basename(file_name:str) -> str

### Runtime functions †


## bit_lock
- bit_lock(address:int, lock_bit:int)

### Runtime functions †


## bit_nth_lsf
- bit_nth_lsf(mask:int, nth_bit:int) -> int

### Runtime functions †


## bit_nth_msf
- bit_nth_msf(mask:int, nth_bit:int) -> int

### Runtime functions †


## bit_storage
- bit_storage(number:int) -> int

### Runtime functions †


## bit_trylock
- bit_trylock(address:int, lock_bit:int) -> bool

### Runtime functions †


## bit_unlock
- bit_unlock(address:int, lock_bit:int)

### Runtime functions †


## blow_chunks
- blow_chunks()

### Runtime functions †


## bookmark_file_error_quark
- bookmark_file_error_quark() -> int

### Runtime functions †


## build_filenamev
- build_filenamev(args:list) -> str

### Runtime functions †


## build_pathv
- build_pathv(separator:str, args:list) -> str

### Runtime functions †


## byte_array_append
- byte_array_append(array:list, data:int, len:int) -> list

### Runtime functions †


## byte_array_free
- byte_array_free(array:list, free_segment:bool) -> int

### Runtime functions †


## byte_array_free_to_bytes
- byte_array_free_to_bytes(array:list) -> GLib.Bytes

### Runtime functions †


## byte_array_new
- byte_array_new() -> list

### Runtime functions †


## byte_array_new_take
- byte_array_new_take(data:list) -> list

### Runtime functions †


## byte_array_prepend
- byte_array_prepend(array:list, data:int, len:int) -> list

### Runtime functions †


## byte_array_ref
- byte_array_ref(array:list) -> list

### Runtime functions †


## byte_array_remove_index
- byte_array_remove_index(array:list, index_:int) -> list

### Runtime functions †


## byte_array_remove_index_fast
- byte_array_remove_index_fast(array:list, index_:int) -> list

### Runtime functions †


## byte_array_remove_range
- byte_array_remove_range(array:list, index_:int, length:int) -> list

### Runtime functions †


## byte_array_set_size
- byte_array_set_size(array:list, length:int) -> list

### Runtime functions †


## byte_array_sized_new
- byte_array_sized_new(reserved_size:int) -> list

### Runtime functions †


## byte_array_sort
- byte_array_sort(array:list, compare_func:GLib.CompareFunc)

### Runtime functions †


## byte_array_sort_with_data
- byte_array_sort_with_data(array:list, compare_func:GLib.CompareDataFunc, user_data=None)

### Runtime functions †


## byte_array_steal
- byte_array_steal(array:list) -> int, len:int

### Runtime functions †


## byte_array_unref
- byte_array_unref(array:list)

### Runtime functions †


## canonicalize_filename
- canonicalize_filename(filename:str, relative_to:str=None) -> str

### Runtime functions †


## chdir
- chdir(path:str) -> int

### Runtime functions †


## check_version
- check_version(required_major:int, required_minor:int, required_micro:int) -> str or None

### Runtime functions †


## checksum_type_get_length
- checksum_type_get_length(checksum_type:GLib.ChecksumType) -> int

### Runtime functions †


## child_watch_add
- child_watch_add(priority, pid, function, *data)

## child_watch_source_new
- child_watch_source_new(pid:int) -> GLib.Source

### Runtime functions †


## chmod
- chmod(filename:str, mode:int) -> int

### Runtime functions †


## clear_error
- clear_error()

### Runtime functions †


## close
- close(fd:int) -> bool

### Runtime functions †


## closefrom
- closefrom(lowfd:int) -> int

### Runtime functions †


## compute_checksum_for_bytes
- compute_checksum_for_bytes(checksum_type:GLib.ChecksumType, data:GLib.Bytes) -> str or None

### Runtime functions †


## compute_checksum_for_data
- compute_checksum_for_data(checksum_type:GLib.ChecksumType, data:list) -> str or None

### Runtime functions †


## compute_checksum_for_string
- compute_checksum_for_string(checksum_type:GLib.ChecksumType, str:str, length:int) -> str or None

### Runtime functions †


## compute_hmac_for_bytes
- compute_hmac_for_bytes(digest_type:GLib.ChecksumType, key:GLib.Bytes, data:GLib.Bytes) -> str

### Runtime functions †


## compute_hmac_for_data
- compute_hmac_for_data(digest_type:GLib.ChecksumType, key:list, data:list) -> str

### Runtime functions †


## compute_hmac_for_string
- compute_hmac_for_string(digest_type:GLib.ChecksumType, key:list, str:str, length:int) -> str

### Runtime functions †


## convert
- convert(str:list, to_codeset:str, from_codeset:str) -> list, bytes_read:int

### Runtime functions †


## convert_error_quark
- convert_error_quark() -> int

### Runtime functions †


## convert_with_fallback
- convert_with_fallback(str:list, to_codeset:str, from_codeset:str, fallback:str) -> list, bytes_read:int

### Runtime functions †


## creat
- creat(filename:str, mode:int) -> int

### Runtime functions †


## datalist_foreach
- datalist_foreach(datalist:GLib.Data, func:GLib.DataForeachFunc, user_data=None)

### Runtime functions †


## datalist_get_data
- datalist_get_data(datalist:GLib.Data, key:str)

### Runtime functions †


## datalist_get_flags
- datalist_get_flags(datalist:GLib.Data) -> int

### Runtime functions †


## datalist_id_get_data
- datalist_id_get_data(datalist:GLib.Data, key_id:int)

### Runtime functions †


## datalist_id_remove_multiple
- datalist_id_remove_multiple(datalist:GLib.Data, keys:list)

### Runtime functions †


## datalist_set_flags
- datalist_set_flags(datalist:GLib.Data, flags:int)

### Runtime functions †


## datalist_unset_flags
- datalist_unset_flags(datalist:GLib.Data, flags:int)

### Runtime functions †


## dataset_destroy
- dataset_destroy(dataset_location)

### Runtime functions †


## dataset_foreach
- dataset_foreach(dataset_location, func:GLib.DataForeachFunc, user_data=None)

### Runtime functions †


## dataset_id_get_data
- dataset_id_get_data(dataset_location, key_id:int)

### Runtime functions †


## date_get_days_in_month
- date_get_days_in_month(month:GLib.DateMonth, year:int) -> int

### Runtime functions †


## date_get_monday_weeks_in_year
- date_get_monday_weeks_in_year(year:int) -> int

### Runtime functions †


## date_get_sunday_weeks_in_year
- date_get_sunday_weeks_in_year(year:int) -> int

### Runtime functions †


## date_is_leap_year
- date_is_leap_year(year:int) -> bool

### Runtime functions †


## date_strftime
- date_strftime(s:str, slen:int, format:str, date:GLib.Date) -> int

### Runtime functions †


## date_valid_day
- date_valid_day(day:int) -> bool

### Runtime functions †


## date_valid_dmy
- date_valid_dmy(day:int, month:GLib.DateMonth, year:int) -> bool

### Runtime functions †


## date_valid_julian
- date_valid_julian(julian_date:int) -> bool

### Runtime functions †


## date_valid_month
- date_valid_month(month:GLib.DateMonth) -> bool

### Runtime functions †


## date_valid_weekday
- date_valid_weekday(weekday:GLib.DateWeekday) -> bool

### Runtime functions †


## date_valid_year
- date_valid_year(year:int) -> bool

### Runtime functions †


## dcgettext
- dcgettext(domain:str=None, msgid:str, category:int) -> str

### Runtime functions †


## dgettext
- dgettext(domain:str=None, msgid:str) -> str

### Runtime functions †


## dir_make_tmp
- dir_make_tmp(tmpl:str=None) -> str

### Runtime functions †


## direct_equal
- direct_equal(v1=None, v2=None) -> bool

### Runtime functions †


## direct_hash
- direct_hash(v=None) -> int

### Runtime functions †


## dngettext
- dngettext(domain:str=None, msgid:str, msgid_plural:str, n:int) -> str

### Runtime functions †


## double_equal
- double_equal(v1, v2) -> bool

### Runtime functions †


## double_hash
- double_hash(v) -> int

### Runtime functions †


## dpgettext
- dpgettext(domain:str=None, msgctxtid:str, msgidoffset:int) -> str

### Runtime functions †


## dpgettext2
- dpgettext2(domain:str=None, context:str, msgid:str) -> str

### Runtime functions †


## environ_getenv
- environ_getenv(envp:list=None, variable:str) -> str or None

### Runtime functions †


## environ_setenv
- environ_setenv(envp:list=None, variable:str, value:str, overwrite:bool) -> list

### Runtime functions †


## environ_unsetenv
- environ_unsetenv(envp:list=None, variable:str) -> list

### Runtime functions †


## error_domain_register
- error_domain_register(error_type_name:str, error_type_private_size:int, error_type_init:GLib.ErrorInitFunc, error_type_copy:GLib.ErrorCopyFunc, error_type_clear:GLib.ErrorClearFunc) -> int

### Runtime functions †


## error_domain_register_static
- error_domain_register_static(error_type_name:str, error_type_private_size:int, error_type_init:GLib.ErrorInitFunc, error_type_copy:GLib.ErrorCopyFunc, error_type_clear:GLib.ErrorClearFunc) -> int

### Runtime functions †


## fdwalk_set_cloexec
- fdwalk_set_cloexec(lowfd:int) -> int

### Runtime functions †


## file_error_from_errno
- file_error_from_errno(err_no:int) -> GLib.FileError

### Runtime functions †


## file_error_quark
- file_error_quark() -> int

### Runtime functions †


## file_get_contents
- file_get_contents(filename:str) -> bool, contents:list

### Runtime functions †


## file_open_tmp
- file_open_tmp(tmpl:str=None) -> int, name_used:str

### Runtime functions †


## file_read_link
- file_read_link(filename:str) -> str

### Runtime functions †


## file_set_contents
- file_set_contents(filename:str, contents:list) -> bool

### Runtime functions †


## file_set_contents_full
- file_set_contents_full(filename:str, contents:list, flags:GLib.FileSetContentsFlags, mode:int) -> bool

### Runtime functions †


## file_test
- file_test(filename:str, test:GLib.FileTest) -> bool

### Runtime functions †


## filename_display_basename
- filename_display_basename(filename:str) -> str

### Runtime functions †


## filename_display_name
- filename_display_name(filename:str) -> str

### Runtime functions †


## filename_from_uri
- filename_from_uri(uri:str) -> str, hostname:str

### Runtime functions †


## filename_from_utf8

## filename_to_uri
- filename_to_uri(filename:str, hostname:str=None) -> str

### Runtime functions †


## filename_to_utf8
- filename_to_utf8(opsysstring:str, len:int) -> str, bytes_read:int, bytes_written:int

### Runtime functions †


## find_program_in_path
- find_program_in_path(program:str) -> str or None

### Runtime functions †


## fopen
- fopen(filename:str, mode:str)

### Runtime functions †


## format_size
- format_size(size:int) -> str

### Runtime functions †


## format_size_for_display
- format_size_for_display(size:int) -> str

### Runtime functions †


## format_size_full
- format_size_full(size:int, flags:GLib.FormatSizeFlags) -> str

### Runtime functions †


## free
- free(mem=None)

### Runtime functions †


## free_sized
- free_sized(mem=None, size:int)

### Runtime functions †


## freopen
- freopen(filename:str, mode:str, stream=None)

### Runtime functions †


## fsync
- fsync(fd:int) -> int

### Runtime functions †


## get_application_name
- get_application_name() -> str or None

### Runtime functions †


## get_charset
- get_charset() -> bool, charset:str

### Runtime functions †


## get_codeset
- get_codeset() -> str

### Runtime functions †


## get_console_charset
- get_console_charset() -> bool, charset:str

### Runtime functions †


## get_current_dir
- get_current_dir() -> str

### Runtime functions †


## get_current_time

## get_environ
- get_environ() -> list

### Runtime functions †


## get_filename_charsets
- get_filename_charsets() -> bool, filename_charsets:list

### Runtime functions †


## get_home_dir
- get_home_dir() -> str

### Runtime functions †


## get_host_name
- get_host_name() -> str

### Runtime functions †


## get_language_names
- get_language_names() -> list

### Runtime functions †


## get_language_names_with_category
- get_language_names_with_category(category_name:str) -> list

### Runtime functions †


## get_locale_variants
- get_locale_variants(locale:str) -> list

### Runtime functions †


## get_monotonic_time
- get_monotonic_time() -> int

### Runtime functions †


## get_num_processors
- get_num_processors() -> int

### Runtime functions †


## get_os_info
- get_os_info(key_name:str) -> str or None

### Runtime functions †


## get_prgname
- get_prgname() -> str or None

### Runtime functions †


## get_real_name
- get_real_name() -> str

### Runtime functions †


## get_real_time
- get_real_time() -> int

### Runtime functions †


## get_system_config_dirs
- get_system_config_dirs() -> list

### Runtime functions †


## get_system_data_dirs
- get_system_data_dirs() -> list

### Runtime functions †


## get_tmp_dir
- get_tmp_dir() -> str

### Runtime functions †


## get_user_cache_dir
- get_user_cache_dir() -> str

### Runtime functions †


## get_user_config_dir
- get_user_config_dir() -> str

### Runtime functions †


## get_user_data_dir
- get_user_data_dir() -> str

### Runtime functions †


## get_user_name
- get_user_name() -> str

### Runtime functions †


## get_user_runtime_dir
- get_user_runtime_dir() -> str

### Runtime functions †


## get_user_special_dir
- get_user_special_dir(directory:GLib.UserDirectory) -> str or None

### Runtime functions †


## get_user_state_dir
- get_user_state_dir() -> str

### Runtime functions †


## getenv
- getenv(variable:str) -> str or None

### Runtime functions †


## hash_table_add
- hash_table_add(hash_table:dict, key=None) -> bool

### Runtime functions †


## hash_table_contains
- hash_table_contains(hash_table:dict, key=None) -> bool

### Runtime functions †


## hash_table_destroy
- hash_table_destroy(hash_table:dict)

### Runtime functions †


## hash_table_find
- hash_table_find(hash_table:dict, predicate:GLib.HRFunc, user_data=None)

### Runtime functions †


## hash_table_foreach
- hash_table_foreach(hash_table:dict, func:GLib.HFunc, user_data=None)

### Runtime functions †


## hash_table_foreach_remove
- hash_table_foreach_remove(hash_table:dict, func:GLib.HRFunc, user_data=None) -> int

### Runtime functions †


## hash_table_foreach_steal
- hash_table_foreach_steal(hash_table:dict, func:GLib.HRFunc, user_data=None) -> int

### Runtime functions †


## hash_table_insert
- hash_table_insert(hash_table:dict, key=None, value=None) -> bool

### Runtime functions †


## hash_table_lookup
- hash_table_lookup(hash_table:dict, key=None)

### Runtime functions †


## hash_table_lookup_extended
- hash_table_lookup_extended(hash_table:dict, lookup_key=None) -> bool, orig_key, value

### Runtime functions †


## hash_table_new_similar
- hash_table_new_similar(other_hash_table:dict) -> dict

### Runtime functions †


## hash_table_ref
- hash_table_ref(hash_table:dict) -> dict

### Runtime functions †


## hash_table_remove
- hash_table_remove(hash_table:dict, key=None) -> bool

### Runtime functions †


## hash_table_remove_all
- hash_table_remove_all(hash_table:dict)

### Runtime functions †


## hash_table_replace
- hash_table_replace(hash_table:dict, key=None, value=None) -> bool

### Runtime functions †


## hash_table_size
- hash_table_size(hash_table:dict) -> int

### Runtime functions †


## hash_table_steal
- hash_table_steal(hash_table:dict, key=None) -> bool

### Runtime functions †


## hash_table_steal_all
- hash_table_steal_all(hash_table:dict)

### Runtime functions †


## hash_table_steal_extended
- hash_table_steal_extended(hash_table:dict, lookup_key=None) -> bool, stolen_key, stolen_value

### Runtime functions †


## hash_table_unref
- hash_table_unref(hash_table:dict)

### Runtime functions †


## hook_destroy
- hook_destroy(hook_list:GLib.HookList, hook_id:int) -> bool

### Runtime functions †


## hook_destroy_link
- hook_destroy_link(hook_list:GLib.HookList, hook:GLib.Hook)

### Runtime functions †


## hook_free
- hook_free(hook_list:GLib.HookList, hook:GLib.Hook)

### Runtime functions †


## hook_insert_before
- hook_insert_before(hook_list:GLib.HookList, sibling:GLib.Hook=None, hook:GLib.Hook)

### Runtime functions †


## hook_insert_sorted
- hook_insert_sorted(hook_list:GLib.HookList, hook:GLib.Hook, func:GLib.HookCompareFunc)

### Runtime functions †


## hook_prepend
- hook_prepend(hook_list:GLib.HookList, hook:GLib.Hook)

### Runtime functions †


## hook_unref
- hook_unref(hook_list:GLib.HookList, hook:GLib.Hook)

### Runtime functions †


## hostname_is_ascii_encoded
- hostname_is_ascii_encoded(hostname:str) -> bool

### Runtime functions †


## hostname_is_ip_address
- hostname_is_ip_address(hostname:str) -> bool

### Runtime functions †


## hostname_is_non_ascii
- hostname_is_non_ascii(hostname:str) -> bool

### Runtime functions †


## hostname_to_ascii
- hostname_to_ascii(hostname:str) -> str or None

### Runtime functions †


## hostname_to_unicode
- hostname_to_unicode(hostname:str) -> str or None

### Runtime functions †


## idle_add

## idle_remove_by_data
- idle_remove_by_data(data=None) -> bool

### Runtime functions †


## idle_source_new
- idle_source_new() -> GLib.Source

### Runtime functions †


## int64_equal
- int64_equal(v1, v2) -> bool

### Runtime functions †


## int64_hash
- int64_hash(v) -> int

### Runtime functions †


## int_equal
- int_equal(v1, v2) -> bool

### Runtime functions †


## int_hash
- int_hash(v) -> int

### Runtime functions †


## intern_static_string
- intern_static_string(string:str=None) -> str

### Runtime functions †


## intern_string
- intern_string(string:str=None) -> str

### Runtime functions †


## io_add_watch
- io_add_watch(channel, priority, condition, func, *user_data) -> event_source_id

## io_channel_error_from_errno
- io_channel_error_from_errno(en:int) -> GLib.IOChannelError

### Runtime functions †


## io_channel_error_quark
- io_channel_error_quark() -> int

### Runtime functions †


## io_create_watch
- io_create_watch(channel:GLib.IOChannel, condition:GLib.IOCondition) -> GLib.Source

### Runtime functions †


## key_file_error_quark
- key_file_error_quark() -> int

### Runtime functions †


## list_pop_allocator
- list_pop_allocator()

### Runtime functions †


## list_push_allocator
- list_push_allocator(allocator:GLib.Allocator)

### Runtime functions †


## listenv
- listenv() -> list

### Runtime functions †


## locale_from_utf8
- locale_from_utf8(utf8string:str, len:int) -> list, bytes_read:int

### Runtime functions †


## locale_to_utf8
- locale_to_utf8(opsysstring:list) -> str, bytes_read:int, bytes_written:int

### Runtime functions †


## log_default_handler
- log_default_handler(log_domain:str=None, log_level:GLib.LogLevelFlags, message:str=None, unused_data=None)

### Runtime functions †


## log_get_debug_enabled
- log_get_debug_enabled() -> bool

### Runtime functions †


## log_remove_handler
- log_remove_handler(log_domain:str, handler_id:int)

### Runtime functions †


## log_set_always_fatal
- log_set_always_fatal(fatal_mask:GLib.LogLevelFlags) -> GLib.LogLevelFlags

### Runtime functions †


## log_set_debug_enabled
- log_set_debug_enabled(enabled:bool)

### Runtime functions †


## log_set_fatal_mask
- log_set_fatal_mask(log_domain:str, fatal_mask:GLib.LogLevelFlags) -> GLib.LogLevelFlags

### Runtime functions †


## log_set_handler
- log_set_handler(log_domain:str=None, log_levels:GLib.LogLevelFlags, log_func:GLib.LogFunc, user_data=None) -> int

### Runtime functions †


## log_set_writer_func
- log_set_writer_func(user_data=None)

### Runtime functions †


## log_structured_array
- log_structured_array(log_level:GLib.LogLevelFlags, fields:list)

### Runtime functions †


## log_variant
- log_variant(log_domain:str=None, log_level:GLib.LogLevelFlags, fields:GLib.Variant)

### Runtime functions †


## log_writer_default
- log_writer_default(log_level:GLib.LogLevelFlags, fields:list, user_data=None) -> GLib.LogWriterOutput

### Runtime functions †


## log_writer_default_set_debug_domains
- log_writer_default_set_debug_domains(domains:str=None)

### Runtime functions †


## log_writer_default_set_use_stderr
- log_writer_default_set_use_stderr(use_stderr:bool)

### Runtime functions †


## log_writer_default_would_drop
- log_writer_default_would_drop(log_level:GLib.LogLevelFlags, log_domain:str=None) -> bool

### Runtime functions †


## log_writer_format_fields
- log_writer_format_fields(log_level:GLib.LogLevelFlags, fields:list, use_color:bool) -> str

### Runtime functions †


## log_writer_is_journald
- log_writer_is_journald(output_fd:int) -> bool

### Runtime functions †


## log_writer_journald
- log_writer_journald(log_level:GLib.LogLevelFlags, fields:list, user_data=None) -> GLib.LogWriterOutput

### Runtime functions †


## log_writer_standard_streams
- log_writer_standard_streams(log_level:GLib.LogLevelFlags, fields:list, user_data=None) -> GLib.LogWriterOutput

### Runtime functions †


## log_writer_supports_color
- log_writer_supports_color(output_fd:int) -> bool

### Runtime functions †


## log_writer_syslog
- log_writer_syslog(log_level:GLib.LogLevelFlags, fields:list, user_data=None) -> GLib.LogWriterOutput

### Runtime functions †


## lstat
- lstat(filename:str, buf:GLib.StatBuf) -> int

### Runtime functions †


## main_context_default
- main_context_default() -> GLib.MainContext

### Runtime functions †


## main_context_get_thread_default
- main_context_get_thread_default() -> GLib.MainContext or None

### Runtime functions †


## main_context_ref_thread_default
- main_context_ref_thread_default() -> GLib.MainContext

### Runtime functions †


## main_current_source
- main_current_source() -> GLib.Source or None

### Runtime functions †


## main_depth
- main_depth() -> int

### Runtime functions †


## malloc
- malloc(n_bytes:int)

### Runtime functions †


## malloc0
- malloc0(n_bytes:int)

### Runtime functions †


## malloc0_n
- malloc0_n(n_blocks:int, n_block_bytes:int)

### Runtime functions †


## malloc_n
- malloc_n(n_blocks:int, n_block_bytes:int)

### Runtime functions †


## markup_error_quark
- markup_error_quark() -> int

### Runtime functions †


## markup_escape_text

## mem_chunk_info
- mem_chunk_info()

### Runtime functions †


## mem_is_system_malloc
- mem_is_system_malloc() -> bool

### Runtime functions †


## mem_profile
- mem_profile()

### Runtime functions †


## mem_set_vtable
- mem_set_vtable(vtable:GLib.MemVTable)

### Runtime functions †


## memdup
- memdup(mem=None, byte_size:int)

### Runtime functions †


## memdup2
- memdup2(mem=None, byte_size:int)

### Runtime functions †


## mkdir
- mkdir(filename:str, mode:int) -> int

### Runtime functions †


## mkdir_with_parents
- mkdir_with_parents(pathname:str, mode:int) -> int

### Runtime functions †


## node_pop_allocator
- node_pop_allocator()

### Runtime functions †


## node_push_allocator
- node_push_allocator(allocator:GLib.Allocator)

### Runtime functions †


## nullify_pointer
- nullify_pointer(nullify_location)

### Runtime functions †


## number_parser_error_quark
- number_parser_error_quark() -> int

### Runtime functions †


## on_error_query
- on_error_query(prg_name:str)

### Runtime functions †


## on_error_stack_trace
- on_error_stack_trace(prg_name:str=None)

### Runtime functions †


## once_init_enter
- once_init_enter(location) -> bool, location

### Runtime functions †


## once_init_enter_impl
- once_init_enter_impl(location:int) -> bool

### Runtime functions †


## once_init_enter_pointer
- once_init_enter_pointer(location) -> bool

### Runtime functions †


## once_init_leave
- once_init_leave(location, result:int) -> location

### Runtime functions †


## once_init_leave_pointer
- once_init_leave_pointer(location, result=None)

### Runtime functions †


## open
- open(filename:str, flags:int, mode:int) -> int

### Runtime functions †


## option_error_quark
- option_error_quark() -> int

### Runtime functions †


## parse_debug_string
- parse_debug_string(string:str=None, keys:list) -> int

### Runtime functions †


## path_buf_equal
- path_buf_equal(v1, v2) -> bool

### Runtime functions †


## path_get_basename
- path_get_basename(file_name:str) -> str

### Runtime functions †


## path_get_dirname
- path_get_dirname(file_name:str) -> str

### Runtime functions †


## path_is_absolute
- path_is_absolute(file_name:str) -> bool

### Runtime functions †


## path_skip_root
- path_skip_root(file_name:str) -> str or None

### Runtime functions †


## pattern_match_simple
- pattern_match_simple(pattern:str, string:str) -> bool

### Runtime functions †


## pointer_bit_lock
- pointer_bit_lock(address, lock_bit:int)

### Runtime functions †


## pointer_bit_lock_and_get
- pointer_bit_lock_and_get(address, lock_bit:int) -> out_ptr:int

### Runtime functions †


## pointer_bit_lock_mask_ptr
- pointer_bit_lock_mask_ptr(ptr=None, lock_bit:int, set:bool, preserve_mask:int, preserve_ptr=None)

### Runtime functions †


## pointer_bit_trylock
- pointer_bit_trylock(address, lock_bit:int) -> bool

### Runtime functions †


## pointer_bit_unlock
- pointer_bit_unlock(address, lock_bit:int)

### Runtime functions †


## pointer_bit_unlock_and_set
- pointer_bit_unlock_and_set(address, lock_bit:int, ptr=None, preserve_mask:int)

### Runtime functions †


## poll
- poll(fds:GLib.PollFD, nfds:int, timeout:int) -> int

### Runtime functions †


## prefix_error_literal
- prefix_error_literal(err:error=None, prefix:str) -> err:error

### Runtime functions †


## propagate_error
- propagate_error(src:error) -> dest:error

### Runtime functions †


## qsort_with_data
- qsort_with_data(pbase, total_elems:int, size:int, compare_func:GLib.CompareDataFunc, user_data=None)

### Runtime functions †


## quark_from_static_string
- quark_from_static_string(string:str=None) -> int

### Runtime functions †


## quark_from_string
- quark_from_string(string:str=None) -> int

### Runtime functions †


## quark_to_string
- quark_to_string(quark:int) -> str

### Runtime functions †


## quark_try_string
- quark_try_string(string:str=None) -> int

### Runtime functions †


## random_double
- random_double() -> float

### Runtime functions †


## random_double_range
- random_double_range(begin:float, end:float) -> float

### Runtime functions †


## random_int
- random_int() -> int

### Runtime functions †


## random_int_range
- random_int_range(begin:int, end:int) -> int

### Runtime functions †


## random_set_seed
- random_set_seed(seed:int)

### Runtime functions †


## rc_box_acquire
- rc_box_acquire(mem_block)

### Runtime functions †


## rc_box_alloc
- rc_box_alloc(block_size:int)

### Runtime functions †


## rc_box_alloc0
- rc_box_alloc0(block_size:int)

### Runtime functions †


## rc_box_dup
- rc_box_dup(block_size:int, mem_block)

### Runtime functions †


## rc_box_get_size
- rc_box_get_size(mem_block) -> int

### Runtime functions †


## rc_box_release
- rc_box_release(mem_block)

### Runtime functions †


## rc_box_release_full
- rc_box_release_full(mem_block, clear_func:GLib.DestroyNotify)

### Runtime functions †


## realloc
- realloc(mem=None, n_bytes:int)

### Runtime functions †


## realloc_n
- realloc_n(mem=None, n_blocks:int, n_block_bytes:int)

### Runtime functions †


## ref_count_compare
- ref_count_compare(rc:int, val:int) -> bool

### Runtime functions †


## ref_count_dec
- ref_count_dec(rc:int) -> bool

### Runtime functions †


## ref_count_inc
- ref_count_inc(rc:int)

### Runtime functions †


## ref_count_init
- ref_count_init(rc:int)

### Runtime functions †


## ref_string_acquire
- ref_string_acquire(str:str) -> str

### Runtime functions †


## ref_string_equal
- ref_string_equal(str1:str, str2:str) -> bool

### Runtime functions †


## ref_string_length
- ref_string_length(str:str) -> int

### Runtime functions †


## ref_string_new
- ref_string_new(str:str) -> str

### Runtime functions †


## ref_string_new_intern
- ref_string_new_intern(str:str) -> str

### Runtime functions †


## ref_string_new_len
- ref_string_new_len(str:str, len:int) -> str

### Runtime functions †


## ref_string_release
- ref_string_release(str:str)

### Runtime functions †


## regex_check_replacement
- regex_check_replacement(replacement:str) -> bool, has_references:bool

### Runtime functions †


## regex_error_quark
- regex_error_quark() -> int

### Runtime functions †


## regex_escape_nul
- regex_escape_nul(string:str, length:int) -> str

### Runtime functions †


## regex_escape_string
- regex_escape_string(string:str, length:int) -> str

### Runtime functions †


## regex_match_simple
- regex_match_simple(pattern:str, string:str, compile_options:GLib.RegexCompileFlags, match_options:GLib.RegexMatchFlags) -> bool

### Runtime functions †


## regex_split_simple
- regex_split_simple(pattern:str, string:str, compile_options:GLib.RegexCompileFlags, match_options:GLib.RegexMatchFlags) -> list

### Runtime functions †


## reload_user_special_dirs_cache
- reload_user_special_dirs_cache()

### Runtime functions †


## remove
- remove(filename:str) -> int

### Runtime functions †


## rename
- rename(oldfilename:str, newfilename:str) -> int

### Runtime functions †


## rmdir
- rmdir(filename:str) -> int

### Runtime functions †


## sequence_foreach_range
- sequence_foreach_range(begin:GLib.SequenceIter, end:GLib.SequenceIter, func:GLib.Func, user_data=None)

### Runtime functions †


## sequence_get
- sequence_get(iter:GLib.SequenceIter)

### Runtime functions †


## sequence_insert_before
- sequence_insert_before(iter:GLib.SequenceIter, data=None) -> GLib.SequenceIter

### Runtime functions †


## sequence_move
- sequence_move(src:GLib.SequenceIter, dest:GLib.SequenceIter)

### Runtime functions †


## sequence_move_range
- sequence_move_range(dest:GLib.SequenceIter, begin:GLib.SequenceIter, end:GLib.SequenceIter)

### Runtime functions †


## sequence_range_get_midpoint
- sequence_range_get_midpoint(begin:GLib.SequenceIter, end:GLib.SequenceIter) -> GLib.SequenceIter

### Runtime functions †


## sequence_remove
- sequence_remove(iter:GLib.SequenceIter)

### Runtime functions †


## sequence_remove_range
- sequence_remove_range(begin:GLib.SequenceIter, end:GLib.SequenceIter)

### Runtime functions †


## sequence_set
- sequence_set(iter:GLib.SequenceIter, data=None)

### Runtime functions †


## sequence_sort_changed
- sequence_sort_changed(iter:GLib.SequenceIter, cmp_func:GLib.CompareDataFunc, cmp_data=None)

### Runtime functions †


## sequence_sort_changed_iter
- sequence_sort_changed_iter(iter:GLib.SequenceIter, iter_cmp:GLib.SequenceIterCompareFunc, cmp_data=None)

### Runtime functions †


## sequence_swap
- sequence_swap(a:GLib.SequenceIter, b:GLib.SequenceIter)

### Runtime functions †


## set_application_name
- set_application_name(application_name:str)

### Runtime functions †


## set_error_literal
- set_error_literal(domain:int, code:int, message:str) -> err:error

### Runtime functions †


## set_prgname
- set_prgname(prgname:str)

### Runtime functions †


## setenv
- setenv(variable:str, value:str, overwrite:bool) -> bool

### Runtime functions †


## shell_error_quark
- shell_error_quark() -> int

### Runtime functions †


## shell_parse_argv
- shell_parse_argv(command_line:str) -> bool, argvp:list

### Runtime functions †


## shell_quote
- shell_quote(unquoted_string:str) -> str

### Runtime functions †


## shell_unquote
- shell_unquote(quoted_string:str) -> str

### Runtime functions †


## slice_alloc
- slice_alloc(block_size:int)

### Runtime functions †


## slice_alloc0
- slice_alloc0(block_size:int)

### Runtime functions †


## slice_copy
- slice_copy(block_size:int, mem_block=None)

### Runtime functions †


## slice_free1
- slice_free1(block_size:int, mem_block=None)

### Runtime functions †


## slice_free_chain_with_offset
- slice_free_chain_with_offset(block_size:int, mem_chain=None, next_offset:int)

### Runtime functions †


## slice_get_config
- slice_get_config(ckey:GLib.SliceConfig) -> int

### Runtime functions †


## slice_get_config_state
- slice_get_config_state(ckey:GLib.SliceConfig, address:int, n_values:int) -> int

### Runtime functions †


## slice_set_config
- slice_set_config(ckey:GLib.SliceConfig, value:int)

### Runtime functions †


## slist_pop_allocator
- slist_pop_allocator()

### Runtime functions †


## slist_push_allocator
- slist_push_allocator(allocator:GLib.Allocator)

### Runtime functions †


## source_remove
- source_remove(tag:int) -> bool

### Runtime functions †


## source_remove_by_funcs_user_data
- source_remove_by_funcs_user_data(funcs:GLib.SourceFuncs, user_data=None) -> bool

### Runtime functions †


## source_remove_by_user_data
- source_remove_by_user_data(user_data=None) -> bool

### Runtime functions †


## source_set_name_by_id
- source_set_name_by_id(tag:int, name:str)

### Runtime functions †


## spaced_primes_closest
- spaced_primes_closest(num:int) -> int

### Runtime functions †


## spawn_async
- spawn_async(argv, envp=None, working_directory=None,<br />            flags=0, child_setup=None, user_data=None,<br />            standard_input=None, standard_output=None,<br />            standard_error=None) -> (pid, stdin, stdout, stderr)<br /><br />Execute a child program asynchronously within a glib.MainLoop()<br />See the reference manual for a complete reference.

## spawn_async_with_fds
- spawn_async_with_fds(working_directory:str=None, argv:list, envp:list=None, flags:GLib.SpawnFlags, child_setup:GLib.SpawnChildSetupFunc=None, user_data=None, stdin_fd:int, stdout_fd:int, stderr_fd:int) -> bool, child_pid:int

### Runtime functions †


## spawn_async_with_pipes
- spawn_async_with_pipes(working_directory:str=None, argv:list, envp:list=None, flags:GLib.SpawnFlags, child_setup:GLib.SpawnChildSetupFunc=None, user_data=None) -> bool, child_pid:int, standard_input:int, standard_output:int, standard_error:int

### Runtime functions †


## spawn_async_with_pipes_and_fds
- spawn_async_with_pipes_and_fds(working_directory:str=None, argv:list, envp:list=None, flags:GLib.SpawnFlags, child_setup:GLib.SpawnChildSetupFunc=None, user_data=None, stdin_fd:int, stdout_fd:int, stderr_fd:int, source_fds:list=None, target_fds:list=None) -> bool, child_pid_out:int, stdin_pipe_out:int, stdout_pipe_out:int, stderr_pipe_out:int

### Runtime functions †


## spawn_check_exit_status
- spawn_check_exit_status(wait_status:int) -> bool

### Runtime functions †


## spawn_check_wait_status
- spawn_check_wait_status(wait_status:int) -> bool

### Runtime functions †


## spawn_close_pid
- spawn_close_pid(pid:int)

### Runtime functions †


## spawn_command_line_async
- spawn_command_line_async(command_line:str) -> bool

### Runtime functions †


## spawn_command_line_sync
- spawn_command_line_sync(command_line:str) -> bool, standard_output:list, standard_error:list, wait_status:int

### Runtime functions †


## spawn_error_quark
- spawn_error_quark() -> int

### Runtime functions †


## spawn_exit_error_quark
- spawn_exit_error_quark() -> int

### Runtime functions †


## spawn_sync
- spawn_sync(working_directory:str=None, argv:list, envp:list=None, flags:GLib.SpawnFlags, child_setup:GLib.SpawnChildSetupFunc=None, user_data=None) -> bool, standard_output:list, standard_error:list, wait_status:int

### Runtime functions †


## stat
- stat(filename:str, buf:GLib.StatBuf) -> int

### Runtime functions †


## stpcpy
- stpcpy(dest:str, src:str) -> str

### Runtime functions †


## str_equal
- str_equal(v1, v2) -> bool

### Runtime functions †


## str_has_prefix
- str_has_prefix(str:str, prefix:str) -> bool

### Runtime functions †


## str_has_suffix
- str_has_suffix(str:str, suffix:str) -> bool

### Runtime functions †


## str_hash
- str_hash(v) -> int

### Runtime functions †


## str_is_ascii
- str_is_ascii(str:str) -> bool

### Runtime functions †


## str_match_string
- str_match_string(search_term:str, potential_hit:str, accept_alternates:bool) -> bool

### Runtime functions †


## str_to_ascii
- str_to_ascii(str:str, from_locale:str=None) -> str

### Runtime functions †


## str_tokenize_and_fold
- str_tokenize_and_fold(string:str, translit_locale:str=None) -> list, ascii_alternates:list

### Runtime functions †


## strcanon
- strcanon(string:str, valid_chars:str, substitutor:int) -> str

### Runtime functions †


## strcasecmp
- strcasecmp(s1:str, s2:str) -> int

### Runtime functions †


## strchomp
- strchomp(string:str) -> str

### Runtime functions †


## strchug
- strchug(string:str) -> str

### Runtime functions †


## strcmp0
- strcmp0(str1:str=None, str2:str=None) -> int

### Runtime functions †


## strcompress
- strcompress(source:str) -> str

### Runtime functions †


## strdelimit
- strdelimit(string:str, delimiters:str=None, new_delimiter:int) -> str

### Runtime functions †


## strdown
- strdown(string:str) -> str

### Runtime functions †


## strdup
- strdup(str:str=None) -> str

### Runtime functions †


## strdupv
- strdupv(str_array:list=None) -> list or None

### Runtime functions †


## strerror
- strerror(errnum:int) -> str

### Runtime functions †


## strescape
- strescape(source:str, exceptions:str=None) -> str

### Runtime functions †


## strfreev
- strfreev(str_array:list=None)

### Runtime functions †


## strip_context
- strip_context(msgid:str, msgval:str) -> str

### Runtime functions †


## strjoinv
- strjoinv(separator:str=None, str_array:list) -> str

### Runtime functions †


## strlcat
- strlcat(dest:str, src:str, dest_size:int) -> int

### Runtime functions †


## strlcpy
- strlcpy(dest:str, src:str, dest_size:int) -> int

### Runtime functions †


## strncasecmp
- strncasecmp(s1:str, s2:str, n:int) -> int

### Runtime functions †


## strndup
- strndup(str:str=None, n:int) -> str or None

### Runtime functions †


## strnfill
- strnfill(length:int, fill_char:int) -> str

### Runtime functions †


## strreverse
- strreverse(string:str) -> str

### Runtime functions †


## strrstr
- strrstr(haystack:str, needle:str) -> str or None

### Runtime functions †


## strrstr_len
- strrstr_len(haystack:str, haystack_len:int, needle:str) -> str or None

### Runtime functions †


## strsignal
- strsignal(signum:int) -> str

### Runtime functions †


## strsplit
- strsplit(string:str, delimiter:str, max_tokens:int) -> list

### Runtime functions †


## strsplit_set
- strsplit_set(string:str, delimiters:str, max_tokens:int) -> list

### Runtime functions †


## strstr_len
- strstr_len(haystack:str, haystack_len:int, needle:str) -> str or None

### Runtime functions †


## strtod
- strtod(nptr:str) -> float, endptr:str

### Runtime functions †


## strup
- strup(string:str) -> str

### Runtime functions †


## strv_contains
- strv_contains(strv:list, str:str) -> bool

### Runtime functions †


## strv_equal
- strv_equal(strv1:list, strv2:list) -> bool

### Runtime functions †


## strv_get_type
- strv_get_type() -> GType

### Runtime functions †


## strv_length
- strv_length(str_array:list) -> int

### Runtime functions †


## test_add_data_func
- test_add_data_func(testpath:str, test_data=None, test_func:GLib.TestDataFunc)

### Runtime functions †


## test_add_data_func_full
- test_add_data_func_full(testpath:str, test_data=None, test_func:GLib.TestDataFunc)

### Runtime functions †


## test_add_func
- test_add_func(testpath:str, test_func:GLib.TestFunc)

### Runtime functions †


## test_assert_expected_messages_internal
- test_assert_expected_messages_internal(domain:str, file:str, line:int, func:str)

### Runtime functions †


## test_bug
- test_bug(bug_uri_snippet:str)

### Runtime functions †


## test_bug_base
- test_bug_base(uri_pattern:str)

### Runtime functions †


## test_disable_crash_reporting
- test_disable_crash_reporting()

### Runtime functions †


## test_expect_message
- test_expect_message(log_domain:str=None, log_level:GLib.LogLevelFlags, pattern:str)

### Runtime functions †


## test_fail
- test_fail()

### Runtime functions †


## test_failed
- test_failed() -> bool

### Runtime functions †


## test_get_dir
- test_get_dir(file_type:GLib.TestFileType) -> str

### Runtime functions †


## test_get_path
- test_get_path() -> str

### Runtime functions †


## test_incomplete
- test_incomplete(msg:str=None)

### Runtime functions †


## test_log_type_name
- test_log_type_name(log_type:GLib.TestLogType) -> str

### Runtime functions †


## test_queue_destroy
- test_queue_destroy(destroy_func:GLib.DestroyNotify, destroy_data=None)

### Runtime functions †


## test_queue_free
- test_queue_free(gfree_pointer=None)

### Runtime functions †


## test_rand_double
- test_rand_double() -> float

### Runtime functions †


## test_rand_double_range
- test_rand_double_range(range_start:float, range_end:float) -> float

### Runtime functions †


## test_rand_int
- test_rand_int() -> int

### Runtime functions †


## test_rand_int_range
- test_rand_int_range(begin:int, end:int) -> int

### Runtime functions †


## test_run
- test_run() -> int

### Runtime functions †


## test_run_suite
- test_run_suite(suite:GLib.TestSuite) -> int

### Runtime functions †


## test_set_nonfatal_assertions
- test_set_nonfatal_assertions()

### Runtime functions †


## test_skip
- test_skip(msg:str=None)

### Runtime functions †


## test_subprocess
- test_subprocess() -> bool

### Runtime functions †


## test_summary
- test_summary(summary:str)

### Runtime functions †


## test_timer_elapsed
- test_timer_elapsed() -> float

### Runtime functions †


## test_timer_last
- test_timer_last() -> float

### Runtime functions †


## test_timer_start
- test_timer_start()

### Runtime functions †


## test_trap_assertions
- test_trap_assertions(domain:str, file:str, line:int, func:str, assertion_flags:int, pattern:str)

### Runtime functions †


## test_trap_fork
- test_trap_fork(usec_timeout:int, test_trap_flags:GLib.TestTrapFlags) -> bool

### Runtime functions †


## test_trap_has_passed
- test_trap_has_passed() -> bool

### Runtime functions †


## test_trap_reached_timeout
- test_trap_reached_timeout() -> bool

### Runtime functions †


## test_trap_subprocess
- test_trap_subprocess(test_path:str=None, usec_timeout:int, test_flags:GLib.TestSubprocessFlags)

### Runtime functions †


## test_trap_subprocess_with_envp
- test_trap_subprocess_with_envp(test_path:str=None, envp:list=None, usec_timeout:int, test_flags:GLib.TestSubprocessFlags)

### Runtime functions †


## thread_error_quark
- thread_error_quark() -> int

### Runtime functions †


## thread_exit
- thread_exit(retval=None)

### Runtime functions †


## thread_pool_get_max_idle_time
- thread_pool_get_max_idle_time() -> int

### Runtime functions †


## thread_pool_get_max_unused_threads
- thread_pool_get_max_unused_threads() -> int

### Runtime functions †


## thread_pool_get_num_unused_threads
- thread_pool_get_num_unused_threads() -> int

### Runtime functions †


## thread_pool_set_max_idle_time
- thread_pool_set_max_idle_time(interval:int)

### Runtime functions †


## thread_pool_set_max_unused_threads
- thread_pool_set_max_unused_threads(max_threads:int)

### Runtime functions †


## thread_pool_stop_unused_threads
- thread_pool_stop_unused_threads()

### Runtime functions †


## thread_self
- thread_self() -> GLib.Thread

### Runtime functions †


## thread_yield
- thread_yield()

### Runtime functions †


## time_val_from_iso8601
- time_val_from_iso8601(iso_date:str) -> bool, time_:GLib.TimeVal

### Runtime functions †


## timeout_add

## timeout_add_seconds

## timeout_source_new
- timeout_source_new(interval:int) -> GLib.Source

### Runtime functions †


## timeout_source_new_seconds
- timeout_source_new_seconds(interval:int) -> GLib.Source

### Runtime functions †


## trash_stack_height
- trash_stack_height(stack_p:GLib.TrashStack) -> int

### Runtime functions †


## trash_stack_peek
- trash_stack_peek(stack_p:GLib.TrashStack)

### Runtime functions †


## trash_stack_pop
- trash_stack_pop(stack_p:GLib.TrashStack)

### Runtime functions †


## trash_stack_push
- trash_stack_push(stack_p:GLib.TrashStack, data_p)

### Runtime functions †


## try_malloc
- try_malloc(n_bytes:int)

### Runtime functions †


## try_malloc0
- try_malloc0(n_bytes:int)

### Runtime functions †


## try_malloc0_n
- try_malloc0_n(n_blocks:int, n_block_bytes:int)

### Runtime functions †


## try_malloc_n
- try_malloc_n(n_blocks:int, n_block_bytes:int)

### Runtime functions †


## try_realloc
- try_realloc(mem=None, n_bytes:int)

### Runtime functions †


## try_realloc_n
- try_realloc_n(mem=None, n_blocks:int, n_block_bytes:int)

### Runtime functions †


## ucs4_to_utf16
- ucs4_to_utf16(str:list) -> int, items_read:int, items_written:int

### Runtime functions †


## ucs4_to_utf8
- ucs4_to_utf8(str:list) -> str, items_read:int, items_written:int

### Runtime functions †


## unichar_break_type
- unichar_break_type(c:str) -> GLib.UnicodeBreakType

### Runtime functions †


## unichar_combining_class
- unichar_combining_class(uc:str) -> int

### Runtime functions †


## unichar_compose
- unichar_compose(a:str, b:str) -> bool, ch:str

### Runtime functions †


## unichar_decompose
- unichar_decompose(ch:str) -> bool, a:str, b:str

### Runtime functions †


## unichar_digit_value
- unichar_digit_value(c:str) -> int

### Runtime functions †


## unichar_fully_decompose
- unichar_fully_decompose(ch:str, compat:bool, result_len:int) -> int, result:str

### Runtime functions †


## unichar_get_mirror_char
- unichar_get_mirror_char(ch:str) -> bool, mirrored_ch:str

### Runtime functions †


## unichar_get_script
- unichar_get_script(ch:str) -> GLib.UnicodeScript

### Runtime functions †


## unichar_isalnum
- unichar_isalnum(c:str) -> bool

### Runtime functions †


## unichar_isalpha
- unichar_isalpha(c:str) -> bool

### Runtime functions †


## unichar_iscntrl
- unichar_iscntrl(c:str) -> bool

### Runtime functions †


## unichar_isdefined
- unichar_isdefined(c:str) -> bool

### Runtime functions †


## unichar_isdigit
- unichar_isdigit(c:str) -> bool

### Runtime functions †


## unichar_isgraph
- unichar_isgraph(c:str) -> bool

### Runtime functions †


## unichar_islower
- unichar_islower(c:str) -> bool

### Runtime functions †


## unichar_ismark
- unichar_ismark(c:str) -> bool

### Runtime functions †


## unichar_isprint
- unichar_isprint(c:str) -> bool

### Runtime functions †


## unichar_ispunct
- unichar_ispunct(c:str) -> bool

### Runtime functions †


## unichar_isspace
- unichar_isspace(c:str) -> bool

### Runtime functions †


## unichar_istitle
- unichar_istitle(c:str) -> bool

### Runtime functions †


## unichar_isupper
- unichar_isupper(c:str) -> bool

### Runtime functions †


## unichar_iswide
- unichar_iswide(c:str) -> bool

### Runtime functions †


## unichar_iswide_cjk
- unichar_iswide_cjk(c:str) -> bool

### Runtime functions †


## unichar_isxdigit
- unichar_isxdigit(c:str) -> bool

### Runtime functions †


## unichar_iszerowidth
- unichar_iszerowidth(c:str) -> bool

### Runtime functions †


## unichar_to_utf8
- unichar_to_utf8(c:str) -> int, outbuf:str

### Runtime functions †


## unichar_tolower
- unichar_tolower(c:str) -> str

### Runtime functions †


## unichar_totitle
- unichar_totitle(c:str) -> str

### Runtime functions †


## unichar_toupper
- unichar_toupper(c:str) -> str

### Runtime functions †


## unichar_type
- unichar_type(c:str) -> GLib.UnicodeType

### Runtime functions †


## unichar_validate
- unichar_validate(ch:str) -> bool

### Runtime functions †


## unichar_xdigit_value
- unichar_xdigit_value(c:str) -> int

### Runtime functions †


## unicode_canonical_decomposition
- unicode_canonical_decomposition(ch:str, result_len:int) -> str

### Runtime functions †


## unicode_canonical_ordering
- unicode_canonical_ordering(string:list)

### Runtime functions †


## unicode_script_from_iso15924
- unicode_script_from_iso15924(iso15924:int) -> GLib.UnicodeScript

### Runtime functions †


## unicode_script_to_iso15924
- unicode_script_to_iso15924(script:GLib.UnicodeScript) -> int

### Runtime functions †


## unix_error_quark
- unix_error_quark() -> int

### Runtime functions †


## unix_fd_add_full
- unix_fd_add_full(priority:int, fd:int, condition:GLib.IOCondition, function:GLib.UnixFDSourceFunc, user_data=None) -> int

### Runtime functions †


## unix_fd_source_new
- unix_fd_source_new(fd:int, condition:GLib.IOCondition) -> GLib.Source

### Runtime functions †


## unix_get_passwd_entry
- unix_get_passwd_entry(user_name:str)

### Runtime functions †


## unix_open_pipe
- unix_open_pipe(fds:list, flags:int) -> bool

### Runtime functions †


## unix_set_fd_nonblocking
- unix_set_fd_nonblocking(fd:int, nonblock:bool) -> bool

### Runtime functions †


## unix_signal_add
- unix_signal_add(priority:int, signum:int, handler:GLib.SourceFunc, user_data=None) -> int

### Runtime functions †


## unix_signal_source_new
- unix_signal_source_new(signum:int) -> GLib.Source

### Runtime functions †


## unlink
- unlink(filename:str) -> int

### Runtime functions †


## unsetenv
- unsetenv(variable:str)

### Runtime functions †


## uri_build
- uri_build(flags:GLib.UriFlags, scheme:str, userinfo:str=None, host:str=None, port:int, path:str, query:str=None, fragment:str=None) -> GLib.Uri

### Runtime functions †


## uri_build_with_user
- uri_build_with_user(flags:GLib.UriFlags, scheme:str, user:str=None, password:str=None, auth_params:str=None, host:str=None, port:int, path:str, query:str=None, fragment:str=None) -> GLib.Uri

### Runtime functions †


## uri_error_quark
- uri_error_quark() -> int

### Runtime functions †


## uri_escape_bytes
- uri_escape_bytes(unescaped:list, reserved_chars_allowed:str=None) -> str

### Runtime functions †


## uri_escape_string
- uri_escape_string(unescaped:str, reserved_chars_allowed:str=None, allow_utf8:bool) -> str

### Runtime functions †


## uri_is_valid
- uri_is_valid(uri_string:str, flags:GLib.UriFlags) -> bool

### Runtime functions †


## uri_join
- uri_join(flags:GLib.UriFlags, scheme:str=None, userinfo:str=None, host:str=None, port:int, path:str, query:str=None, fragment:str=None) -> str

### Runtime functions †


## uri_join_with_user
- uri_join_with_user(flags:GLib.UriFlags, scheme:str=None, user:str=None, password:str=None, auth_params:str=None, host:str=None, port:int, path:str, query:str=None, fragment:str=None) -> str

### Runtime functions †


## uri_list_extract_uris
- uri_list_extract_uris(uri_list:str) -> list

### Runtime functions †


## uri_parse
- uri_parse(uri_string:str, flags:GLib.UriFlags) -> GLib.Uri

### Runtime functions †


## uri_parse_params
- uri_parse_params(params:str, length:int, separators:str, flags:GLib.UriParamsFlags) -> dict

### Runtime functions †


## uri_parse_scheme
- uri_parse_scheme(uri:str) -> str or None

### Runtime functions †


## uri_peek_scheme
- uri_peek_scheme(uri:str) -> str or None

### Runtime functions †


## uri_resolve_relative
- uri_resolve_relative(base_uri_string:str=None, uri_ref:str, flags:GLib.UriFlags) -> str

### Runtime functions †


## uri_split
- uri_split(uri_ref:str, flags:GLib.UriFlags) -> scheme:str, userinfo:str, host:str, port:int, path:str, query:str, fragment:str

### Runtime functions †


## uri_split_network
- uri_split_network(uri_string:str, flags:GLib.UriFlags) -> scheme:str, host:str, port:int

### Runtime functions †


## uri_split_with_user
- uri_split_with_user(uri_ref:str, flags:GLib.UriFlags) -> scheme:str, user:str, password:str, auth_params:str, host:str, port:int, path:str, query:str, fragment:str

### Runtime functions †


## uri_unescape_bytes
- uri_unescape_bytes(escaped_string:str, length:int, illegal_characters:str=None) -> GLib.Bytes

### Runtime functions †


## uri_unescape_segment
- uri_unescape_segment(escaped_string:str=None, escaped_string_end:str=None, illegal_characters:str=None) -> str or None

### Runtime functions †


## uri_unescape_string
- uri_unescape_string(escaped_string:str, illegal_characters:str=None) -> str or None

### Runtime functions †


## usleep
- usleep(microseconds:int)

### Runtime functions †


## utf16_to_ucs4
- utf16_to_ucs4(str:list) -> str, items_read:int, items_written:int

### Runtime functions †


## utf16_to_utf8
- utf16_to_utf8(str:list) -> str, items_read:int, items_written:int

### Runtime functions †


## utf8_casefold
- utf8_casefold(str:str, len:int) -> str

### Runtime functions †


## utf8_collate
- utf8_collate(str1:str, str2:str) -> int

### Runtime functions †


## utf8_collate_key
- utf8_collate_key(str:str, len:int) -> str

### Runtime functions †


## utf8_collate_key_for_filename
- utf8_collate_key_for_filename(str:str, len:int) -> str

### Runtime functions †


## utf8_find_next_char
- utf8_find_next_char(p:str, end:str=None) -> str or None

### Runtime functions †


## utf8_find_prev_char
- utf8_find_prev_char(str:str, p:str) -> str or None

### Runtime functions †


## utf8_get_char
- utf8_get_char(p:str) -> str

### Runtime functions †


## utf8_get_char_validated
- utf8_get_char_validated(p:str, max_len:int) -> str

### Runtime functions †


## utf8_make_valid
- utf8_make_valid(str:str, len:int) -> str

### Runtime functions †


## utf8_normalize
- utf8_normalize(str:str, len:int, mode:GLib.NormalizeMode) -> str or None

### Runtime functions †


## utf8_offset_to_pointer
- utf8_offset_to_pointer(str:str, offset:int) -> str

### Runtime functions †


## utf8_pointer_to_offset
- utf8_pointer_to_offset(str:str, pos:str) -> int

### Runtime functions †


## utf8_prev_char
- utf8_prev_char(p:str) -> str

### Runtime functions †


## utf8_strchr
- utf8_strchr(p:str, len:int, c:str) -> str or None

### Runtime functions †


## utf8_strdown
- utf8_strdown(str:str, len:int) -> str

### Runtime functions †


## utf8_strlen
- utf8_strlen(p:str, max:int) -> int

### Runtime functions †


## utf8_strncpy
- utf8_strncpy(dest:str, src:str, n:int) -> str

### Runtime functions †


## utf8_strrchr
- utf8_strrchr(p:str, len:int, c:str) -> str or None

### Runtime functions †


## utf8_strreverse
- utf8_strreverse(str:str, len:int) -> str

### Runtime functions †


## utf8_strup
- utf8_strup(str:str, len:int) -> str

### Runtime functions †


## utf8_substring
- utf8_substring(str:str, start_pos:int, end_pos:int) -> str

### Runtime functions †


## utf8_to_ucs4
- utf8_to_ucs4(str:str, len:int) -> str, items_read:int, items_written:int

### Runtime functions †


## utf8_to_ucs4_fast
- utf8_to_ucs4_fast(str:str, len:int) -> str, items_written:int

### Runtime functions †


## utf8_to_utf16
- utf8_to_utf16(str:str, len:int) -> int, items_read:int, items_written:int

### Runtime functions †


## utf8_truncate_middle
- utf8_truncate_middle(string:str, truncate_length:int) -> str

### Runtime functions †


## utf8_validate
- utf8_validate(str:list) -> bool, end:str

### Runtime functions †


## utf8_validate_len
- utf8_validate_len(str:list) -> bool, end:str

### Runtime functions †


## utime
- utime(filename:str, utb=None) -> int

### Runtime functions †


## uuid_string_is_valid
- uuid_string_is_valid(str:str) -> bool

### Runtime functions †


## uuid_string_random
- uuid_string_random() -> str

### Runtime functions †


## variant_get_gtype
- variant_get_gtype() -> GType

### Runtime functions †


## variant_is_object_path
- variant_is_object_path(string:str) -> bool

### Runtime functions †


## variant_is_signature
- variant_is_signature(string:str) -> bool

### Runtime functions †


## variant_parse
- variant_parse(type:GLib.VariantType=None, text:str, limit:str=None, endptr:str=None) -> GLib.Variant

### Runtime functions †


## variant_parse_error_print_context
- variant_parse_error_print_context(error:error, source_str:str) -> str

### Runtime functions †


## variant_parse_error_quark
- variant_parse_error_quark() -> int

### Runtime functions †


## variant_parser_get_error_quark
- variant_parser_get_error_quark() -> int

### Runtime functions †


## variant_type_checked_
- variant_type_checked_(type_string:str) -> GLib.VariantType

### Runtime functions †


## variant_type_string_get_depth_
- variant_type_string_get_depth_(type_string:str) -> int

### Runtime functions †


## variant_type_string_is_valid
- variant_type_string_is_valid(type_string:str) -> bool

### Runtime functions †


## variant_type_string_scan
- variant_type_string_scan(string:str, limit:str=None) -> bool, endptr:str

### Runtime functions †

