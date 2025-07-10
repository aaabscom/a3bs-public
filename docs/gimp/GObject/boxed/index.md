---
layout: default
title: GObject.boxed
---
# GObject.boxed

## Array

### Runtime functions †
- **copy**`(self, /)`
  - documentation unavailable



## BookmarkFile

### Runtime functions †


## ByteArray

### Runtime functions †


## Bytes

### Runtime functions †


## Checksum

### Runtime functions †


## Date

### Runtime functions †


## DateTime

### Runtime functions †


## Dir

### Runtime functions †


## Error
- :Constructors:<br /><br />::<br /><br />    Error()<br />    new_literal(domain:int, code:int, message:str) -> error

### Runtime functions ††
- **copy**`(*args, **kwargs)`
  - copy(self) -> error

- **domain_register**`(*args, **kwargs)`
  - domain_register(error_type_name:str, error_type_private_size:int, error_type_init:GLib.ErrorInitFunc, error_type_copy:GLib.ErrorCopyFunc, error_type_clear:GLib.ErrorClearFunc) -> int

- **domain_register_static**`(*args, **kwargs)`
  - domain_register_static(error_type_name:str, error_type_private_size:int, error_type_init:GLib.ErrorInitFunc, error_type_copy:GLib.ErrorCopyFunc, error_type_clear:GLib.ErrorClearFunc) -> int

- **free**`(*args, **kwargs)`
  - free(self)

- **matches**`(*args, **kwargs)`
  - matches(self, domain:int, code:int) -> bool

- **new_literal**`(*args, **kwargs)`
  - new_literal(domain:int, code:int, message:str) -> error



## HashTable

### Runtime functions †


## Hmac

### Runtime functions †


## IOChannel
- :Constructors:<br /><br />::<br /><br />    IOChannel()<br />    new_file(filename:str, mode:str) -> GLib.IOChannel<br />    unix_new(fd:int) -> GLib.IOChannel

### Runtime functions †††
- **add_watch**`(self, condition, callback, *user_data, **kwargs)`
  - documentation unavailable

- **close**`(*args, **kwargs)`
  - close(self)

- **copy**`(self, /)`
  - documentation unavailable

- **error_from_errno**`(*args, **kwargs)`
  - error_from_errno(en:int) -> GLib.IOChannelError

- **error_quark**`(*args, **kwargs)`
  - error_quark() -> int

- **flush**`(*args, **kwargs)`
  - flush(self) -> GLib.IOStatus

- **get_buffer_condition**`(*args, **kwargs)`
  - get_buffer_condition(self) -> GLib.IOCondition

- **get_buffer_size**`(*args, **kwargs)`
  - get_buffer_size(self) -> int

- **get_buffered**`(*args, **kwargs)`
  - get_buffered(self) -> bool

- **get_close_on_unref**`(*args, **kwargs)`
  - get_close_on_unref(self) -> bool

- **get_encoding**`(*args, **kwargs)`
  - get_encoding(self) -> str

- **get_flags**`(*args, **kwargs)`
  - get_flags(self) -> GLib.IOFlags

- **get_line_term**`(*args, **kwargs)`
  - get_line_term(self) -> str, length:int

- **init**`(*args, **kwargs)`
  - init(self)

- **new_file**`(*args, **kwargs)`
  - new_file(filename:str, mode:str) -> GLib.IOChannel

- **read**`(self, max_count=-1)`
  - read(self, buf:str, count:int, bytes_read:int) -> GLib.IOError

- **read_chars**`(*args, **kwargs)`
  - read_chars(self) -> GLib.IOStatus, buf:list, bytes_read:int

- **read_line**`(*args, **kwargs)`
  - read_line(self) -> GLib.IOStatus, str_return:str, length:int, terminator_pos:int

- **read_line_string**`(*args, **kwargs)`
  - read_line_string(self, buffer:GLib.String, terminator_pos:int=None) -> GLib.IOStatus

- **read_to_end**`(*args, **kwargs)`
  - read_to_end(self) -> GLib.IOStatus, str_return:list

- **read_unichar**`(*args, **kwargs)`
  - read_unichar(self) -> GLib.IOStatus, thechar:str

- **readline**`(self, size_hint=-1)`
  - documentation unavailable

- **readlines**`(self, size_hint=-1)`
  - documentation unavailable

- **ref**`(*args, **kwargs)`
  - ref(self) -> GLib.IOChannel

- **seek**`(self, offset, whence=0)`
  - seek(self, offset:int, type:GLib.SeekType) -> GLib.IOError

- **seek_position**`(*args, **kwargs)`
  - seek_position(self, offset:int, type:GLib.SeekType) -> GLib.IOStatus

- **set_buffer_size**`(*args, **kwargs)`
  - set_buffer_size(self, size:int)

- **set_buffered**`(*args, **kwargs)`
  - set_buffered(self, buffered:bool)

- **set_close_on_unref**`(*args, **kwargs)`
  - set_close_on_unref(self, do_close:bool)

- **set_encoding**`(*args, **kwargs)`
  - set_encoding(self, encoding:str=None) -> GLib.IOStatus

- **set_flags**`(*args, **kwargs)`
  - set_flags(self, flags:GLib.IOFlags) -> GLib.IOStatus

- **set_line_term**`(*args, **kwargs)`
  - set_line_term(self, line_term:str=None, length:int)

- **shutdown**`(*args, **kwargs)`
  - shutdown(self, flush:bool) -> GLib.IOStatus

- **unix_get_fd**`(*args, **kwargs)`
  - unix_get_fd(self) -> int

- **unix_new**`(*args, **kwargs)`
  - unix_new(fd:int) -> GLib.IOChannel

- **unref**`(*args, **kwargs)`
  - unref(self)

- **write**`(self, buf, buflen=-1)`
  - write(self, buf:str, count:int, bytes_written:int) -> GLib.IOError

- **write_chars**`(*args, **kwargs)`
  - write_chars(self, buf:list, count:int) -> GLib.IOStatus, bytes_written:int

- **write_unichar**`(*args, **kwargs)`
  - write_unichar(self, thechar:str) -> GLib.IOStatus

- **writelines**`(self, lines)`
  - documentation unavailable



## KeyFile

### Runtime functions †


## MainContext
- :Constructors:<br /><br />::<br /><br />    new() -> GLib.MainContext<br />    new_with_flags(flags:GLib.MainContextFlags) -> GLib.MainContext

### Runtime functions ††††
- **acquire**`(*args, **kwargs)`
  - acquire(self) -> bool

- **add_poll**`(*args, **kwargs)`
  - add_poll(self, fd:GLib.PollFD, priority:int)

- **check**`(*args, **kwargs)`
  - check(self, max_priority:int, fds:list) -> bool

- **copy**`(self, /)`
  - documentation unavailable

- **default**`(*args, **kwargs)`
  - default() -> GLib.MainContext

- **dispatch**`(*args, **kwargs)`
  - dispatch(self)

- **find_source_by_funcs_user_data**`(*args, **kwargs)`
  - find_source_by_funcs_user_data(self, funcs:GLib.SourceFuncs, user_data=None) -> GLib.Source

- **find_source_by_id**`(*args, **kwargs)`
  - find_source_by_id(self, source_id:int) -> GLib.Source

- **find_source_by_user_data**`(*args, **kwargs)`
  - find_source_by_user_data(self, user_data=None) -> GLib.Source

- **get_thread_default**`(*args, **kwargs)`
  - get_thread_default() -> GLib.MainContext or None

- **invoke_full**`(*args, **kwargs)`
  - invoke_full(self, priority:int, function:GLib.SourceFunc, data=None)

- **is_owner**`(*args, **kwargs)`
  - is_owner(self) -> bool

- **iteration**`(self, may_block=True)`
  - iteration(self, may_block:bool) -> bool

- **new**`(*args, **kwargs)`
  - new() -> GLib.MainContext

- **new_with_flags**`(*args, **kwargs)`
  - new_with_flags(flags:GLib.MainContextFlags) -> GLib.MainContext

- **pending**`(*args, **kwargs)`
  - pending(self) -> bool

- **pop_thread_default**`(*args, **kwargs)`
  - pop_thread_default(self)

- **prepare**`(*args, **kwargs)`
  - prepare(self) -> bool, priority:int

- **push_thread_default**`(*args, **kwargs)`
  - push_thread_default(self)

- **pusher_new**`(*args, **kwargs)`
  - pusher_new(self)

- **query**`(*args, **kwargs)`
  - query(self, max_priority:int) -> int, timeout_:int, fds:list

- **ref**`(*args, **kwargs)`
  - ref(self) -> GLib.MainContext

- **ref_thread_default**`(*args, **kwargs)`
  - ref_thread_default() -> GLib.MainContext

- **release**`(*args, **kwargs)`
  - release(self)

- **remove_poll**`(*args, **kwargs)`
  - remove_poll(self, fd:GLib.PollFD)

- **unref**`(*args, **kwargs)`
  - unref(self)

- **wait**`(*args, **kwargs)`
  - wait(self, cond:GLib.Cond, mutex:GLib.Mutex) -> bool

- **wakeup**`(*args, **kwargs)`
  - wakeup(self)



## MainLoop
- :Constructors:<br /><br />::<br /><br />    new(context:GLib.MainContext=None, is_running:bool) -> GLib.MainLoop

### Runtime functions †††††
- **copy**`(self, /)`
  - documentation unavailable

- **get_context**`(*args, **kwargs)`
  - get_context(self) -> GLib.MainContext

- **is_running**`(*args, **kwargs)`
  - is_running(self) -> bool

- **new**`(*args, **kwargs)`
  - new(context:GLib.MainContext=None, is_running:bool) -> GLib.MainLoop

- **quit**`(*args, **kwargs)`
  - quit(self)

- **ref**`(*args, **kwargs)`
  - ref(self) -> GLib.MainLoop

- **run**`(self)`
  - run(self)

- **unref**`(*args, **kwargs)`
  - unref(self)



## MappedFile

### Runtime functions †


## MarkupParseContext

### Runtime functions †


## MatchInfo

### Runtime functions †


## OptionGroup

### Runtime functions ††††††
- **add_entries**`(bound native)`
  - documentation unavailable

- **set_translation_domain**`(bound native)`
  - documentation unavailable



## PatternSpec

### Runtime functions †


## PollFD
- :Constructors:<br /><br />::<br /><br />    PollFD()

### Runtime functions †


## PtrArray

### Runtime functions †


## Rand

### Runtime functions †


## Regex

### Runtime functions †


## Source
- :Constructors:<br /><br />::<br /><br />    Source()<br />    new(source_funcs:GLib.SourceFuncs, struct_size:int) -> GLib.Source

### Runtime functions †††††††
- **add_child_source**`(*args, **kwargs)`
  - add_child_source(self, child_source:GLib.Source)

- **add_poll**`(*args, **kwargs)`
  - add_poll(self, fd:GLib.PollFD)

- **add_unix_fd**`(*args, **kwargs)`
  - add_unix_fd(self, fd:int, events:GLib.IOCondition)

- **attach**`(*args, **kwargs)`
  - attach(self, context:GLib.MainContext=None) -> int

- **copy**`(self, /)`
  - documentation unavailable

- **destroy**`(*args, **kwargs)`
  - destroy(self)

- **finalize**`(self)`
  - documentation unavailable

- **get_can_recurse**`(*args, **kwargs)`
  - get_can_recurse(self) -> bool

- **get_context**`(*args, **kwargs)`
  - get_context(self) -> GLib.MainContext or None

- **get_current_time**`(self)`
  - get_current_time(self, timeval:GLib.TimeVal)

- **get_id**`(*args, **kwargs)`
  - get_id(self) -> int

- **get_name**`(*args, **kwargs)`
  - get_name(self) -> str or None

- **get_priority**`(*args, **kwargs)`
  - get_priority(self) -> int

- **get_ready_time**`(*args, **kwargs)`
  - get_ready_time(self) -> int

- **get_time**`(*args, **kwargs)`
  - get_time(self) -> int

- **is_destroyed**`(*args, **kwargs)`
  - is_destroyed(self) -> bool

- **modify_unix_fd**`(*args, **kwargs)`
  - modify_unix_fd(self, tag, new_events:GLib.IOCondition)

- **new**`(*args, **kwargs)`
  - new(source_funcs:GLib.SourceFuncs, struct_size:int) -> GLib.Source

- **query_unix_fd**`(*args, **kwargs)`
  - query_unix_fd(self, tag) -> GLib.IOCondition

- **ref**`(*args, **kwargs)`
  - ref(self) -> GLib.Source

- **remove**`(*args, **kwargs)`
  - remove(tag:int) -> bool

- **remove_by_funcs_user_data**`(*args, **kwargs)`
  - remove_by_funcs_user_data(funcs:GLib.SourceFuncs, user_data=None) -> bool

- **remove_by_user_data**`(*args, **kwargs)`
  - remove_by_user_data(user_data=None) -> bool

- **remove_child_source**`(*args, **kwargs)`
  - remove_child_source(self, child_source:GLib.Source)

- **remove_poll**`(*args, **kwargs)`
  - remove_poll(self, fd:GLib.PollFD)

- **remove_unix_fd**`(*args, **kwargs)`
  - remove_unix_fd(self, tag)

- **set_callback**`(self, fn, user_data=None)`
  - set_callback(self, func:GLib.SourceFunc, data=None)

- **set_callback_indirect**`(*args, **kwargs)`
  - set_callback_indirect(self, callback_data=None, callback_funcs:GLib.SourceCallbackFuncs)

- **set_can_recurse**`(*args, **kwargs)`
  - set_can_recurse(self, can_recurse:bool)

- **set_funcs**`(*args, **kwargs)`
  - set_funcs(self, funcs:GLib.SourceFuncs)

- **set_name**`(*args, **kwargs)`
  - set_name(self, name:str)

- **set_name_by_id**`(*args, **kwargs)`
  - set_name_by_id(tag:int, name:str)

- **set_priority**`(*args, **kwargs)`
  - set_priority(self, priority:int)

- **set_ready_time**`(*args, **kwargs)`
  - set_ready_time(self, ready_time:int)

- **set_static_name**`(*args, **kwargs)`
  - set_static_name(self, name:str)

- **unref**`(*args, **kwargs)`
  - unref(self)



## String

### Runtime functions †


## Strv

### Runtime functions †


## StrvBuilder

### Runtime functions †


## Thread

### Runtime functions †


## TimeZone

### Runtime functions †


## Tree

### Runtime functions †


## Uri

### Runtime functions †


## VariantBuilder

### Runtime functions †


## VariantDict

### Runtime functions †


## VariantType

### Runtime functions †

