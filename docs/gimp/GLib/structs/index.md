---
layout: default
title: GLib.structs
---
# GLib.structs

## Allocator

### Runtime functions †
- **free**`(*args, **kwargs)`
  - free(self)



## Array

### Runtime functions ††
- **copy**`(self, /)`
  - documentation unavailable



## AsyncQueue

### Runtime functions †††
- **length**`(*args, **kwargs)`
  - length(self) -> int

- **length_unlocked**`(*args, **kwargs)`
  - length_unlocked(self) -> int

- **lock**`(*args, **kwargs)`
  - lock(self)

- **new**`(*args, **kwargs)`
  - new() -> GLib.AsyncQueue

- **new_full**`(*args, **kwargs)`
  - new_full(item_free_func:GLib.DestroyNotify=None) -> GLib.AsyncQueue

- **pop**`(*args, **kwargs)`
  - pop(self)

- **pop_unlocked**`(*args, **kwargs)`
  - pop_unlocked(self)

- **push**`(*args, **kwargs)`
  - push(self, data)

- **push_front**`(*args, **kwargs)`
  - push_front(self, item)

- **push_front_unlocked**`(*args, **kwargs)`
  - push_front_unlocked(self, item)

- **push_sorted**`(*args, **kwargs)`
  - push_sorted(self, data, func:GLib.CompareDataFunc, user_data=None)

- **push_sorted_unlocked**`(*args, **kwargs)`
  - push_sorted_unlocked(self, data=None, func:GLib.CompareDataFunc, user_data=None)

- **push_unlocked**`(*args, **kwargs)`
  - push_unlocked(self, data)

- **ref**`(*args, **kwargs)`
  - ref(self) -> GLib.AsyncQueue

- **ref_unlocked**`(*args, **kwargs)`
  - ref_unlocked(self)

- **remove**`(*args, **kwargs)`
  - remove(self, item) -> bool

- **remove_unlocked**`(*args, **kwargs)`
  - remove_unlocked(self, item=None) -> bool

- **sort**`(*args, **kwargs)`
  - sort(self, func:GLib.CompareDataFunc, user_data=None)

- **sort_unlocked**`(*args, **kwargs)`
  - sort_unlocked(self, func:GLib.CompareDataFunc, user_data=None)

- **timed_pop**`(*args, **kwargs)`
  - timed_pop(self, end_time:GLib.TimeVal)

- **timed_pop_unlocked**`(*args, **kwargs)`
  - timed_pop_unlocked(self, end_time:GLib.TimeVal)

- **timeout_pop**`(*args, **kwargs)`
  - timeout_pop(self, timeout:int)

- **timeout_pop_unlocked**`(*args, **kwargs)`
  - timeout_pop_unlocked(self, timeout:int)

- **try_pop**`(*args, **kwargs)`
  - try_pop(self)

- **try_pop_unlocked**`(*args, **kwargs)`
  - try_pop_unlocked(self)

- **unlock**`(*args, **kwargs)`
  - unlock(self)

- **unref**`(*args, **kwargs)`
  - unref(self)

- **unref_and_unlock**`(*args, **kwargs)`
  - unref_and_unlock(self)



## BookmarkFile

### Runtime functions ††


## ByteArray

### Runtime functions ††


## Bytes

### Runtime functions ††


## Cache

### Runtime functions ††††
- **destroy**`(*args, **kwargs)`
  - destroy(self)

- **insert**`(*args, **kwargs)`
  - insert(self, key=None)

- **key_foreach**`(*args, **kwargs)`
  - key_foreach(self, func:GLib.HFunc, user_data=None)

- **remove**`(*args, **kwargs)`
  - remove(self, value=None)

- **value_foreach**`(*args, **kwargs)`
  - value_foreach(self, func:GLib.HFunc, user_data=None)



## Checksum

### Runtime functions ††


## Completion
- :Constructors:<br /><br />::<br /><br />    Completion()

### Runtime functions †††††
- **clear_items**`(*args, **kwargs)`
  - clear_items(self)

- **complete_utf8**`(*args, **kwargs)`
  - complete_utf8(self, prefix:str, new_prefix:str) -> list

- **free**`(*args, **kwargs)`
  - free(self)



## Cond
- :Constructors:<br /><br />::<br /><br />    Cond()

### Runtime functions ††††††
- **broadcast**`(*args, **kwargs)`
  - broadcast(self)

- **clear**`(*args, **kwargs)`
  - clear(self)

- **init**`(*args, **kwargs)`
  - init(self)

- **signal**`(*args, **kwargs)`
  - signal(self)

- **wait**`(*args, **kwargs)`
  - wait(self, mutex:GLib.Mutex)

- **wait_until**`(*args, **kwargs)`
  - wait_until(self, mutex:GLib.Mutex, end_time:int) -> bool



## Data

## Date

### Runtime functions ††


## DateTime

### Runtime functions ††


## DebugKey
- :Constructors:<br /><br />::<br /><br />    DebugKey()

## Dir

### Runtime functions ††


## Error
- Unspecified run-time error.

### Runtime functions †††††††
- **add_note**`(self, object, /)`
  - Exception.add_note(note) --<br />add a note to the exception

- **copy**`(self)`
  - documentation unavailable

- **matches**`(self, domain, code)`
  - documentation unavailable

- **new_literal**`(domain, message, code)`
  - documentation unavailable

- **with_traceback**`(self, object, /)`
  - Exception.with_traceback(tb) --<br />set self.__traceback__ to tb and return self.



## HashTable

### Runtime functions ††


## HashTableIter
- :Constructors:<br /><br />::<br /><br />    HashTableIter()

### Runtime functions ††††††††
- **get_hash_table**`(*args, **kwargs)`
  - get_hash_table(self) -> dict

- **init**`(*args, **kwargs)`
  - init(self, hash_table:dict)

- **next**`(*args, **kwargs)`
  - next(self) -> bool, key, value

- **remove**`(*args, **kwargs)`
  - remove(self)

- **replace**`(*args, **kwargs)`
  - replace(self, value=None)

- **steal**`(*args, **kwargs)`
  - steal(self)



## Hmac

### Runtime functions ††


## Hook
- :Constructors:<br /><br />::<br /><br />    Hook()

### Runtime functions †††††††††
- **compare_ids**`(*args, **kwargs)`
  - compare_ids(self, sibling:GLib.Hook) -> int

- **destroy**`(*args, **kwargs)`
  - destroy(hook_list:GLib.HookList, hook_id:int) -> bool

- **destroy_link**`(*args, **kwargs)`
  - destroy_link(hook_list:GLib.HookList, hook:GLib.Hook)

- **free**`(*args, **kwargs)`
  - free(hook_list:GLib.HookList, hook:GLib.Hook)

- **insert_before**`(*args, **kwargs)`
  - insert_before(hook_list:GLib.HookList, sibling:GLib.Hook=None, hook:GLib.Hook)

- **insert_sorted**`(*args, **kwargs)`
  - insert_sorted(hook_list:GLib.HookList, hook:GLib.Hook, func:GLib.HookCompareFunc)

- **prepend**`(*args, **kwargs)`
  - prepend(hook_list:GLib.HookList, hook:GLib.Hook)

- **unref**`(*args, **kwargs)`
  - unref(hook_list:GLib.HookList, hook:GLib.Hook)



## HookList
- :Constructors:<br /><br />::<br /><br />    HookList()

### Runtime functions ††††††††††
- **clear**`(*args, **kwargs)`
  - clear(self)

- **init**`(*args, **kwargs)`
  - init(self, hook_size:int)

- **invoke**`(*args, **kwargs)`
  - invoke(self, may_recurse:bool)

- **invoke_check**`(*args, **kwargs)`
  - invoke_check(self, may_recurse:bool)

- **marshal**`(*args, **kwargs)`
  - marshal(self, may_recurse:bool, marshaller:GLib.HookMarshaller, marshal_data=None)

- **marshal_check**`(*args, **kwargs)`
  - marshal_check(self, may_recurse:bool, marshaller:GLib.HookCheckMarshaller, marshal_data=None)



## IOChannel
- :Constructors:<br /><br />::<br /><br />    IOChannel()<br />    new_file(filename:str, mode:str) -> GLib.IOChannel<br />    unix_new(fd:int) -> GLib.IOChannel

### Runtime functions †††††††††††
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



## IOFuncs
- :Constructors:<br /><br />::<br /><br />    IOFuncs()

## KeyFile

### Runtime functions ††


## List
- :Constructors:<br /><br />::<br /><br />    List()

### Runtime functions ††††††††††††
- **pop_allocator**`(*args, **kwargs)`
  - pop_allocator()

- **push_allocator**`(*args, **kwargs)`
  - push_allocator(allocator:GLib.Allocator)



## LogField
- :Constructors:<br /><br />::<br /><br />    LogField()

## MainContext
- :Constructors:<br /><br />::<br /><br />    new() -> GLib.MainContext<br />    new_with_flags(flags:GLib.MainContextFlags) -> GLib.MainContext

### Runtime functions †††††††††††††
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

### Runtime functions ††††††††††††††
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

### Runtime functions ††


## MarkupParseContext

### Runtime functions ††


## MarkupParser
- :Constructors:<br /><br />::<br /><br />    MarkupParser()

## MatchInfo

### Runtime functions ††


## MemChunk

### Runtime functions †††††††††††††††
- **alloc**`(*args, **kwargs)`
  - alloc(self)

- **alloc0**`(*args, **kwargs)`
  - alloc0(self)

- **clean**`(*args, **kwargs)`
  - clean(self)

- **destroy**`(*args, **kwargs)`
  - destroy(self)

- **free**`(*args, **kwargs)`
  - free(self, mem=None)

- **info**`(*args, **kwargs)`
  - info()

- **print_**`(*args, **kwargs)`
  - print_(self)

- **reset**`(*args, **kwargs)`
  - reset(self)



## MemVTable
- :Constructors:<br /><br />::<br /><br />    MemVTable()

## Node
- :Constructors:<br /><br />::<br /><br />    Node()

### Runtime functions ††††††††††††††††
- **child_index**`(*args, **kwargs)`
  - child_index(self, data=None) -> int

- **child_position**`(*args, **kwargs)`
  - child_position(self, child:GLib.Node) -> int

- **children_foreach**`(*args, **kwargs)`
  - children_foreach(self, flags:GLib.TraverseFlags, func:GLib.NodeForeachFunc, data=None)

- **depth**`(*args, **kwargs)`
  - depth(self) -> int

- **destroy**`(*args, **kwargs)`
  - destroy(self)

- **is_ancestor**`(*args, **kwargs)`
  - is_ancestor(self, descendant:GLib.Node) -> bool

- **max_height**`(*args, **kwargs)`
  - max_height(self) -> int

- **n_children**`(*args, **kwargs)`
  - n_children(self) -> int

- **n_nodes**`(*args, **kwargs)`
  - n_nodes(self, flags:GLib.TraverseFlags) -> int

- **pop_allocator**`(*args, **kwargs)`
  - pop_allocator()

- **push_allocator**`(*args, **kwargs)`
  - push_allocator(allocator:GLib.Allocator)

- **reverse_children**`(*args, **kwargs)`
  - reverse_children(self)

- **traverse**`(*args, **kwargs)`
  - traverse(self, order:GLib.TraverseType, flags:GLib.TraverseFlags, max_depth:int, func:GLib.NodeTraverseFunc, data=None)

- **unlink**`(*args, **kwargs)`
  - unlink(self)



## Once
- :Constructors:<br /><br />::<br /><br />    Once()

### Runtime functions †††††††††††††††††
- **init_enter**`(*args, **kwargs)`
  - init_enter(location) -> bool, location

- **init_enter_impl**`(*args, **kwargs)`
  - init_enter_impl(location:int) -> bool

- **init_enter_pointer**`(*args, **kwargs)`
  - init_enter_pointer(location) -> bool

- **init_leave**`(*args, **kwargs)`
  - init_leave(location, result:int) -> location

- **init_leave_pointer**`(*args, **kwargs)`
  - init_leave_pointer(location, result=None)



## OptionContext

### Runtime functions ††††††††††††††††††
- **add_group**`(bound native)`
  - documentation unavailable

- **get_help_enabled**`(self, /)`
  - documentation unavailable

- **get_ignore_unknown_options**`(self, /)`
  - documentation unavailable

- **get_main_group**`(self, /)`
  - documentation unavailable

- **parse**`(bound native)`
  - documentation unavailable

- **set_help_enabled**`(bound native)`
  - documentation unavailable

- **set_ignore_unknown_options**`(bound native)`
  - documentation unavailable

- **set_main_group**`(bound native)`
  - documentation unavailable



## OptionEntry
- :Constructors:<br /><br />::<br /><br />    OptionEntry()

## OptionGroup

### Runtime functions †††††††††††††††††††
- **add_entries**`(bound native)`
  - documentation unavailable

- **set_translation_domain**`(bound native)`
  - documentation unavailable



## PathBuf
- :Constructors:<br /><br />::<br /><br />    PathBuf()

### Runtime functions ††††††††††††††††††††
- **clear**`(*args, **kwargs)`
  - clear(self)

- **clear_to_path**`(*args, **kwargs)`
  - clear_to_path(self) -> str or None

- **equal**`(*args, **kwargs)`
  - equal(v1, v2) -> bool

- **free**`(*args, **kwargs)`
  - free(self)

- **free_to_path**`(*args, **kwargs)`
  - free_to_path(self) -> str or None

- **init**`(*args, **kwargs)`
  - init(self) -> GLib.PathBuf

- **init_from_path**`(*args, **kwargs)`
  - init_from_path(self, path:str=None) -> GLib.PathBuf

- **pop**`(*args, **kwargs)`
  - pop(self) -> bool

- **push**`(*args, **kwargs)`
  - push(self, path:str) -> GLib.PathBuf

- **set_extension**`(*args, **kwargs)`
  - set_extension(self, extension:str=None) -> bool

- **set_filename**`(*args, **kwargs)`
  - set_filename(self, file_name:str) -> bool

- **to_path**`(*args, **kwargs)`
  - to_path(self) -> str or None



## PatternSpec

### Runtime functions ††


## PollFD
- :Constructors:<br /><br />::<br /><br />    PollFD()

### Runtime functions ††


## Private
- :Constructors:<br /><br />::<br /><br />    Private()

### Runtime functions †††††††††††††††††††††
- **get**`(*args, **kwargs)`
  - get(self)

- **replace**`(*args, **kwargs)`
  - replace(self, value=None)

- **set**`(*args, **kwargs)`
  - set(self, value=None)



## PtrArray

### Runtime functions ††


## Queue
- :Constructors:<br /><br />::<br /><br />    Queue()

### Runtime functions ††††††††††††††††††††††
- **clear**`(*args, **kwargs)`
  - clear(self)

- **clear_full**`(*args, **kwargs)`
  - clear_full(self, free_func:GLib.DestroyNotify=None)

- **foreach**`(*args, **kwargs)`
  - foreach(self, func:GLib.Func, user_data=None)

- **free**`(*args, **kwargs)`
  - free(self)

- **free_full**`(*args, **kwargs)`
  - free_full(self, free_func:GLib.DestroyNotify)

- **get_length**`(*args, **kwargs)`
  - get_length(self) -> int

- **index**`(*args, **kwargs)`
  - index(self, data=None) -> int

- **init**`(*args, **kwargs)`
  - init(self)

- **insert_sorted**`(*args, **kwargs)`
  - insert_sorted(self, data=None, func:GLib.CompareDataFunc, user_data=None)

- **is_empty**`(*args, **kwargs)`
  - is_empty(self) -> bool

- **peek_head**`(*args, **kwargs)`
  - peek_head(self)

- **peek_nth**`(*args, **kwargs)`
  - peek_nth(self, n:int)

- **peek_tail**`(*args, **kwargs)`
  - peek_tail(self)

- **pop_head**`(*args, **kwargs)`
  - pop_head(self)

- **pop_nth**`(*args, **kwargs)`
  - pop_nth(self, n:int)

- **pop_tail**`(*args, **kwargs)`
  - pop_tail(self)

- **push_head**`(*args, **kwargs)`
  - push_head(self, data=None)

- **push_nth**`(*args, **kwargs)`
  - push_nth(self, data=None, n:int)

- **push_tail**`(*args, **kwargs)`
  - push_tail(self, data=None)

- **remove**`(*args, **kwargs)`
  - remove(self, data=None) -> bool

- **remove_all**`(*args, **kwargs)`
  - remove_all(self, data=None) -> int

- **reverse**`(*args, **kwargs)`
  - reverse(self)

- **sort**`(*args, **kwargs)`
  - sort(self, compare_func:GLib.CompareDataFunc, user_data=None)



## RWLock
- :Constructors:<br /><br />::<br /><br />    RWLock()

### Runtime functions †††††††††††††††††††††††
- **clear**`(*args, **kwargs)`
  - clear(self)

- **init**`(*args, **kwargs)`
  - init(self)

- **reader_lock**`(*args, **kwargs)`
  - reader_lock(self)

- **reader_trylock**`(*args, **kwargs)`
  - reader_trylock(self) -> bool

- **reader_unlock**`(*args, **kwargs)`
  - reader_unlock(self)

- **writer_lock**`(*args, **kwargs)`
  - writer_lock(self)

- **writer_trylock**`(*args, **kwargs)`
  - writer_trylock(self) -> bool

- **writer_unlock**`(*args, **kwargs)`
  - writer_unlock(self)



## Rand

### Runtime functions ††


## RecMutex
- :Constructors:<br /><br />::<br /><br />    RecMutex()

### Runtime functions ††††††††††††††††††††††††
- **clear**`(*args, **kwargs)`
  - clear(self)

- **init**`(*args, **kwargs)`
  - init(self)

- **lock**`(*args, **kwargs)`
  - lock(self)

- **trylock**`(*args, **kwargs)`
  - trylock(self) -> bool

- **unlock**`(*args, **kwargs)`
  - unlock(self)



## Regex

### Runtime functions ††


## Relation

### Runtime functions †††††††††††††††††††††††††
- **count**`(*args, **kwargs)`
  - count(self, key=None, field:int) -> int

- **delete**`(*args, **kwargs)`
  - delete(self, key=None, field:int) -> int

- **destroy**`(*args, **kwargs)`
  - destroy(self)

- **print_**`(*args, **kwargs)`
  - print_(self)



## SList
- :Constructors:<br /><br />::<br /><br />    SList()

### Runtime functions ††††††††††††


## Scanner
- :Constructors:<br /><br />::<br /><br />    Scanner()

### Runtime functions ††††††††††††††††††††††††††
- **cur_line**`(*args, **kwargs)`
  - cur_line(self) -> int

- **cur_position**`(*args, **kwargs)`
  - cur_position(self) -> int

- **cur_token**`(*args, **kwargs)`
  - cur_token(self) -> GLib.TokenType

- **destroy**`(*args, **kwargs)`
  - destroy(self)

- **eof**`(*args, **kwargs)`
  - eof(self) -> bool

- **get_next_token**`(*args, **kwargs)`
  - get_next_token(self) -> GLib.TokenType

- **input_file**`(*args, **kwargs)`
  - input_file(self, input_fd:int)

- **input_text**`(*args, **kwargs)`
  - input_text(self, text:str, text_len:int)

- **lookup_symbol**`(*args, **kwargs)`
  - lookup_symbol(self, symbol:str)

- **peek_next_token**`(*args, **kwargs)`
  - peek_next_token(self) -> GLib.TokenType

- **scope_add_symbol**`(*args, **kwargs)`
  - scope_add_symbol(self, scope_id:int, symbol:str, value=None)

- **scope_foreach_symbol**`(*args, **kwargs)`
  - scope_foreach_symbol(self, scope_id:int, func:GLib.HFunc, user_data=None)

- **scope_lookup_symbol**`(*args, **kwargs)`
  - scope_lookup_symbol(self, scope_id:int, symbol:str)

- **scope_remove_symbol**`(*args, **kwargs)`
  - scope_remove_symbol(self, scope_id:int, symbol:str)

- **set_scope**`(*args, **kwargs)`
  - set_scope(self, scope_id:int) -> int

- **sync_file_offset**`(*args, **kwargs)`
  - sync_file_offset(self)

- **unexp_token**`(*args, **kwargs)`
  - unexp_token(self, expected_token:GLib.TokenType, identifier_spec:str, symbol_spec:str, symbol_name:str, message:str, is_error:int)



## ScannerConfig
- :Constructors:<br /><br />::<br /><br />    ScannerConfig()

## Sequence

### Runtime functions †††††††††††††††††††††††††††
- **append**`(*args, **kwargs)`
  - append(self, data=None) -> GLib.SequenceIter

- **foreach**`(*args, **kwargs)`
  - foreach(self, func:GLib.Func, user_data=None)

- **foreach_range**`(*args, **kwargs)`
  - foreach_range(begin:GLib.SequenceIter, end:GLib.SequenceIter, func:GLib.Func, user_data=None)

- **free**`(*args, **kwargs)`
  - free(self)

- **get**`(*args, **kwargs)`
  - get(iter:GLib.SequenceIter)

- **get_begin_iter**`(*args, **kwargs)`
  - get_begin_iter(self) -> GLib.SequenceIter

- **get_end_iter**`(*args, **kwargs)`
  - get_end_iter(self) -> GLib.SequenceIter

- **get_iter_at_pos**`(*args, **kwargs)`
  - get_iter_at_pos(self, pos:int) -> GLib.SequenceIter

- **get_length**`(*args, **kwargs)`
  - get_length(self) -> int

- **insert_before**`(*args, **kwargs)`
  - insert_before(iter:GLib.SequenceIter, data=None) -> GLib.SequenceIter

- **insert_sorted**`(*args, **kwargs)`
  - insert_sorted(self, data=None, cmp_func:GLib.CompareDataFunc, cmp_data=None) -> GLib.SequenceIter

- **insert_sorted_iter**`(*args, **kwargs)`
  - insert_sorted_iter(self, data=None, iter_cmp:GLib.SequenceIterCompareFunc, cmp_data=None) -> GLib.SequenceIter

- **is_empty**`(*args, **kwargs)`
  - is_empty(self) -> bool

- **lookup**`(*args, **kwargs)`
  - lookup(self, data=None, cmp_func:GLib.CompareDataFunc, cmp_data=None) -> GLib.SequenceIter or None

- **lookup_iter**`(*args, **kwargs)`
  - lookup_iter(self, data=None, iter_cmp:GLib.SequenceIterCompareFunc, cmp_data=None) -> GLib.SequenceIter or None

- **move**`(*args, **kwargs)`
  - move(src:GLib.SequenceIter, dest:GLib.SequenceIter)

- **move_range**`(*args, **kwargs)`
  - move_range(dest:GLib.SequenceIter, begin:GLib.SequenceIter, end:GLib.SequenceIter)

- **prepend**`(*args, **kwargs)`
  - prepend(self, data=None) -> GLib.SequenceIter

- **range_get_midpoint**`(*args, **kwargs)`
  - range_get_midpoint(begin:GLib.SequenceIter, end:GLib.SequenceIter) -> GLib.SequenceIter

- **remove**`(*args, **kwargs)`
  - remove(iter:GLib.SequenceIter)

- **remove_range**`(*args, **kwargs)`
  - remove_range(begin:GLib.SequenceIter, end:GLib.SequenceIter)

- **search**`(*args, **kwargs)`
  - search(self, data=None, cmp_func:GLib.CompareDataFunc, cmp_data=None) -> GLib.SequenceIter

- **search_iter**`(*args, **kwargs)`
  - search_iter(self, data=None, iter_cmp:GLib.SequenceIterCompareFunc, cmp_data=None) -> GLib.SequenceIter

- **set**`(*args, **kwargs)`
  - set(iter:GLib.SequenceIter, data=None)

- **sort**`(*args, **kwargs)`
  - sort(self, cmp_func:GLib.CompareDataFunc, cmp_data=None)

- **sort_changed**`(*args, **kwargs)`
  - sort_changed(iter:GLib.SequenceIter, cmp_func:GLib.CompareDataFunc, cmp_data=None)

- **sort_changed_iter**`(*args, **kwargs)`
  - sort_changed_iter(iter:GLib.SequenceIter, iter_cmp:GLib.SequenceIterCompareFunc, cmp_data=None)

- **sort_iter**`(*args, **kwargs)`
  - sort_iter(self, cmp_func:GLib.SequenceIterCompareFunc, cmp_data=None)

- **swap**`(*args, **kwargs)`
  - swap(a:GLib.SequenceIter, b:GLib.SequenceIter)



## SequenceIter

### Runtime functions ††††††††††††††††††††††††††††
- **compare**`(*args, **kwargs)`
  - compare(self, b:GLib.SequenceIter) -> int

- **get_position**`(*args, **kwargs)`
  - get_position(self) -> int

- **get_sequence**`(*args, **kwargs)`
  - get_sequence(self) -> GLib.Sequence

- **is_begin**`(*args, **kwargs)`
  - is_begin(self) -> bool

- **is_end**`(*args, **kwargs)`
  - is_end(self) -> bool

- **move**`(*args, **kwargs)`
  - move(self, delta:int) -> GLib.SequenceIter

- **next**`(*args, **kwargs)`
  - next(self) -> GLib.SequenceIter

- **prev**`(*args, **kwargs)`
  - prev(self) -> GLib.SequenceIter



## Source
- :Constructors:<br /><br />::<br /><br />    Source()<br />    new(source_funcs:GLib.SourceFuncs, struct_size:int) -> GLib.Source

### Runtime functions †††††††††††††††††††††††††††††
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



## SourceCallbackFuncs
- :Constructors:<br /><br />::<br /><br />    SourceCallbackFuncs()

## SourceFuncs
- :Constructors:<br /><br />::<br /><br />    SourceFuncs()

## SourcePrivate

## StatBuf

## String

### Runtime functions ††


## StringChunk

### Runtime functions ††††††††††††††††††††††††††††††
- **clear**`(*args, **kwargs)`
  - clear(self)

- **free**`(*args, **kwargs)`
  - free(self)

- **insert**`(*args, **kwargs)`
  - insert(self, string:str) -> str

- **insert_const**`(*args, **kwargs)`
  - insert_const(self, string:str) -> str

- **insert_len**`(*args, **kwargs)`
  - insert_len(self, string:str, len:int) -> str



## StrvBuilder

### Runtime functions ††


## TestCase

### Runtime functions †


## TestConfig
- :Constructors:<br /><br />::<br /><br />    TestConfig()

## TestLogBuffer
- :Constructors:<br /><br />::<br /><br />    TestLogBuffer()

### Runtime functions †††††††††††††††††††††††††††††††
- **free**`(*args, **kwargs)`
  - free(self)

- **push**`(*args, **kwargs)`
  - push(self, n_bytes:int, bytes:int)



## TestLogMsg
- :Constructors:<br /><br />::<br /><br />    TestLogMsg()

### Runtime functions †


## TestSuite

### Runtime functions ††††††††††††††††††††††††††††††††
- **add**`(*args, **kwargs)`
  - add(self, test_case:GLib.TestCase)

- **add_suite**`(*args, **kwargs)`
  - add_suite(self, nestedsuite:GLib.TestSuite)

- **free**`(*args, **kwargs)`
  - free(self)



## Thread

### Runtime functions ††


## ThreadPool
- :Constructors:<br /><br />::<br /><br />    ThreadPool()

### Runtime functions †††††††††††††††††††††††††††††††††
- **free**`(*args, **kwargs)`
  - free(self, immediate:bool, wait_:bool)

- **get_max_idle_time**`(*args, **kwargs)`
  - get_max_idle_time() -> int

- **get_max_threads**`(*args, **kwargs)`
  - get_max_threads(self) -> int

- **get_max_unused_threads**`(*args, **kwargs)`
  - get_max_unused_threads() -> int

- **get_num_threads**`(*args, **kwargs)`
  - get_num_threads(self) -> int

- **get_num_unused_threads**`(*args, **kwargs)`
  - get_num_unused_threads() -> int

- **move_to_front**`(*args, **kwargs)`
  - move_to_front(self, data=None) -> bool

- **push**`(*args, **kwargs)`
  - push(self, data=None) -> bool

- **set_max_idle_time**`(*args, **kwargs)`
  - set_max_idle_time(interval:int)

- **set_max_threads**`(*args, **kwargs)`
  - set_max_threads(self, max_threads:int) -> bool

- **set_max_unused_threads**`(*args, **kwargs)`
  - set_max_unused_threads(max_threads:int)

- **stop_unused_threads**`(*args, **kwargs)`
  - stop_unused_threads()

- **unprocessed**`(*args, **kwargs)`
  - unprocessed(self) -> int



## TimeVal
- :Constructors:<br /><br />::<br /><br />    TimeVal()

### Runtime functions ††††††††††††††††††††††††††††††††††
- **add**`(*args, **kwargs)`
  - add(self, microseconds:int)

- **from_iso8601**`(*args, **kwargs)`
  - from_iso8601(iso_date:str) -> bool, time_:GLib.TimeVal

- **to_iso8601**`(*args, **kwargs)`
  - to_iso8601(self) -> str or None



## TimeZone

### Runtime functions ††


## Timer

### Runtime functions †††††††††††††††††††††††††††††††††††
- **continue_**`(*args, **kwargs)`
  - continue_(self)

- **destroy**`(*args, **kwargs)`
  - destroy(self)

- **elapsed**`(*args, **kwargs)`
  - elapsed(self, microseconds:int) -> float

- **is_active**`(*args, **kwargs)`
  - is_active(self) -> bool

- **reset**`(*args, **kwargs)`
  - reset(self)

- **start**`(*args, **kwargs)`
  - start(self)

- **stop**`(*args, **kwargs)`
  - stop(self)



## TrashStack
- :Constructors:<br /><br />::<br /><br />    TrashStack()

### Runtime functions ††††††††††††††††††††††††††††††††††††
- **height**`(*args, **kwargs)`
  - height(stack_p:GLib.TrashStack) -> int

- **peek**`(*args, **kwargs)`
  - peek(stack_p:GLib.TrashStack)

- **pop**`(*args, **kwargs)`
  - pop(stack_p:GLib.TrashStack)

- **push**`(*args, **kwargs)`
  - push(stack_p:GLib.TrashStack, data_p)



## Tree

### Runtime functions ††


## TreeNode

### Runtime functions †††††††††††††††††††††††††††††††††††††
- **key**`(*args, **kwargs)`
  - key(self)

- **next**`(*args, **kwargs)`
  - next(self) -> GLib.TreeNode or None

- **previous**`(*args, **kwargs)`
  - previous(self) -> GLib.TreeNode or None

- **value**`(*args, **kwargs)`
  - value(self)



## Tuples
- :Constructors:<br /><br />::<br /><br />    Tuples()

### Runtime functions ††††††††††††††††††††††††††††††††††††††
- **destroy**`(*args, **kwargs)`
  - destroy(self)

- **index**`(*args, **kwargs)`
  - index(self, index_:int, field:int)



## UnixPipe
- :Constructors:<br /><br />::<br /><br />    UnixPipe()

## Uri

### Runtime functions ††


## UriParamsIter
- :Constructors:<br /><br />::<br /><br />    UriParamsIter()

### Runtime functions †††††††††††††††††††††††††††††††††††††††
- **init**`(*args, **kwargs)`
  - init(self, params:str, length:int, separators:str, flags:GLib.UriParamsFlags)

- **next**`(*args, **kwargs)`
  - next(self) -> bool, attribute:str, value:str



## Variant
- :Constructors:<br /><br />::<br /><br />    new_array(child_type:GLib.VariantType=None, children:list=None) -> GLib.Variant<br />    new_boolean(value:bool) -> GLib.Variant<br />    new_byte(value:int) -> GLib.Variant<br />    new_bytestring(string:list) -> GLib.Variant<br />    new_bytestring_array(strv:list) -> GLib.Variant<br />    new_dict_entry(key:GLib.Variant, value:GLib.Variant) -> GLib.Variant<br />    new_double(value:float) -> GLib.Variant<br />    new_fixed_array(element_type:GLib.VariantType, elements=None, n_elements:int, element_size:int) -> GLib.Variant<br />    new_from_bytes(type:GLib.VariantType, bytes:GLib.Bytes, trusted:bool) -> GLib.Variant<br />    new_from_data(type:GLib.VariantType, data:list, trusted:bool, notify:GLib.DestroyNotify, user_data=None) -> GLib.Variant<br />    new_handle(value:int) -> GLib.Variant<br />    new_int16(value:int) -> GLib.Variant<br />    new_int32(value:int) -> GLib.Variant<br />    new_int64(value:int) -> GLib.Variant<br />    new_maybe(child_type:GLib.VariantType=None, child:GLib.Variant=None) -> GLib.Variant<br />    new_object_path(object_path:str) -> GLib.Variant<br />    new_objv(strv:list) -> GLib.Variant<br />    new_signature(signature:str) -> GLib.Variant<br />    new_string(string:str) -> GLib.Variant<br />    new_strv(strv:list) -> GLib.Variant<br />    new_tuple(children:list) -> GLib.Variant<br />    new_uint16(value:int) -> GLib.Variant<br />    new_uint32(value:int) -> GLib.Variant<br />    new_uint64(value:int) -> GLib.Variant<br />    new_variant(value:GLib.Variant) -> GLib.Variant

### Runtime functions ††††††††††††††††††††††††††††††††††††††††
- **byteswap**`(*args, **kwargs)`
  - byteswap(self) -> GLib.Variant

- **check_format_string**`(*args, **kwargs)`
  - check_format_string(self, format_string:str, copy_only:bool) -> bool

- **classify**`(*args, **kwargs)`
  - classify(self) -> GLib.VariantClass

- **compare**`(*args, **kwargs)`
  - compare(self, two:GLib.Variant) -> int

- **dup_bytestring**`(*args, **kwargs)`
  - dup_bytestring(self) -> list

- **dup_bytestring_array**`(*args, **kwargs)`
  - dup_bytestring_array(self) -> list

- **dup_objv**`(*args, **kwargs)`
  - dup_objv(self) -> list

- **dup_string**`(*args, **kwargs)`
  - dup_string(self) -> str, length:int

- **dup_strv**`(*args, **kwargs)`
  - dup_strv(self) -> list

- **equal**`(*args, **kwargs)`
  - equal(self, two:GLib.Variant) -> bool

- **get_boolean**`(*args, **kwargs)`
  - get_boolean(self) -> bool

- **get_byte**`(*args, **kwargs)`
  - get_byte(self) -> int

- **get_bytestring**`(*args, **kwargs)`
  - get_bytestring(self) -> list

- **get_bytestring_array**`(*args, **kwargs)`
  - get_bytestring_array(self) -> list

- **get_child_value**`(*args, **kwargs)`
  - get_child_value(self, index_:int) -> GLib.Variant

- **get_data**`(*args, **kwargs)`
  - get_data(self)

- **get_data_as_bytes**`(*args, **kwargs)`
  - get_data_as_bytes(self) -> GLib.Bytes

- **get_double**`(*args, **kwargs)`
  - get_double(self) -> float

- **get_handle**`(*args, **kwargs)`
  - get_handle(self) -> int

- **get_int16**`(*args, **kwargs)`
  - get_int16(self) -> int

- **get_int32**`(*args, **kwargs)`
  - get_int32(self) -> int

- **get_int64**`(*args, **kwargs)`
  - get_int64(self) -> int

- **get_maybe**`(*args, **kwargs)`
  - get_maybe(self) -> GLib.Variant or None

- **get_normal_form**`(*args, **kwargs)`
  - get_normal_form(self) -> GLib.Variant

- **get_objv**`(*args, **kwargs)`
  - get_objv(self) -> list

- **get_size**`(*args, **kwargs)`
  - get_size(self) -> int

- **get_string**`(self)`
  - documentation unavailable

- **get_strv**`(*args, **kwargs)`
  - get_strv(self) -> list

- **get_type**`(*args, **kwargs)`
  - get_type(self) -> GLib.VariantType

- **get_type_string**`(*args, **kwargs)`
  - get_type_string(self) -> str

- **get_uint16**`(*args, **kwargs)`
  - get_uint16(self) -> int

- **get_uint32**`(*args, **kwargs)`
  - get_uint32(self) -> int

- **get_uint64**`(*args, **kwargs)`
  - get_uint64(self) -> int

- **get_variant**`(*args, **kwargs)`
  - get_variant(self) -> GLib.Variant

- **hash**`(*args, **kwargs)`
  - hash(self) -> int

- **is_container**`(*args, **kwargs)`
  - is_container(self) -> bool

- **is_floating**`(*args, **kwargs)`
  - is_floating(self) -> bool

- **is_normal_form**`(*args, **kwargs)`
  - is_normal_form(self) -> bool

- **is_object_path**`(*args, **kwargs)`
  - is_object_path(string:str) -> bool

- **is_of_type**`(*args, **kwargs)`
  - is_of_type(self, type:GLib.VariantType) -> bool

- **is_signature**`(*args, **kwargs)`
  - is_signature(string:str) -> bool

- **keys**`(self)`
  - documentation unavailable

- **lookup_value**`(*args, **kwargs)`
  - lookup_value(self, key:str, expected_type:GLib.VariantType=None) -> GLib.Variant

- **n_children**`(*args, **kwargs)`
  - n_children(self) -> int

- **new_array**`(*args, **kwargs)`
  - new_array(child_type:GLib.VariantType=None, children:list=None) -> GLib.Variant

- **new_boolean**`(*args, **kwargs)`
  - new_boolean(value:bool) -> GLib.Variant

- **new_byte**`(*args, **kwargs)`
  - new_byte(value:int) -> GLib.Variant

- **new_bytestring**`(*args, **kwargs)`
  - new_bytestring(string:list) -> GLib.Variant

- **new_bytestring_array**`(*args, **kwargs)`
  - new_bytestring_array(strv:list) -> GLib.Variant

- **new_dict_entry**`(*args, **kwargs)`
  - new_dict_entry(key:GLib.Variant, value:GLib.Variant) -> GLib.Variant

- **new_double**`(*args, **kwargs)`
  - new_double(value:float) -> GLib.Variant

- **new_fixed_array**`(*args, **kwargs)`
  - new_fixed_array(element_type:GLib.VariantType, elements=None, n_elements:int, element_size:int) -> GLib.Variant

- **new_from_bytes**`(*args, **kwargs)`
  - new_from_bytes(type:GLib.VariantType, bytes:GLib.Bytes, trusted:bool) -> GLib.Variant

- **new_from_data**`(*args, **kwargs)`
  - new_from_data(type:GLib.VariantType, data:list, trusted:bool, notify:GLib.DestroyNotify, user_data=None) -> GLib.Variant

- **new_handle**`(*args, **kwargs)`
  - new_handle(value:int) -> GLib.Variant

- **new_int16**`(*args, **kwargs)`
  - new_int16(value:int) -> GLib.Variant

- **new_int32**`(*args, **kwargs)`
  - new_int32(value:int) -> GLib.Variant

- **new_int64**`(*args, **kwargs)`
  - new_int64(value:int) -> GLib.Variant

- **new_maybe**`(*args, **kwargs)`
  - new_maybe(child_type:GLib.VariantType=None, child:GLib.Variant=None) -> GLib.Variant

- **new_object_path**`(*args, **kwargs)`
  - new_object_path(object_path:str) -> GLib.Variant

- **new_objv**`(*args, **kwargs)`
  - new_objv(strv:list) -> GLib.Variant

- **new_signature**`(*args, **kwargs)`
  - new_signature(signature:str) -> GLib.Variant

- **new_string**`(*args, **kwargs)`
  - new_string(string:str) -> GLib.Variant

- **new_strv**`(*args, **kwargs)`
  - new_strv(strv:list) -> GLib.Variant

- **new_tuple**`(*elements)`
  - new_tuple(children:list) -> GLib.Variant

- **new_uint16**`(*args, **kwargs)`
  - new_uint16(value:int) -> GLib.Variant

- **new_uint32**`(*args, **kwargs)`
  - new_uint32(value:int) -> GLib.Variant

- **new_uint64**`(*args, **kwargs)`
  - new_uint64(value:int) -> GLib.Variant

- **new_variant**`(*args, **kwargs)`
  - new_variant(value:GLib.Variant) -> GLib.Variant

- **parse**`(*args, **kwargs)`
  - parse(type:GLib.VariantType=None, text:str, limit:str=None, endptr:str=None) -> GLib.Variant

- **parse_error_print_context**`(*args, **kwargs)`
  - parse_error_print_context(error:error, source_str:str) -> str

- **parse_error_quark**`(*args, **kwargs)`
  - parse_error_quark() -> int

- **parser_get_error_quark**`(*args, **kwargs)`
  - parser_get_error_quark() -> int

- **print_**`(*args, **kwargs)`
  - print_(self, type_annotate:bool) -> str

- **ref**`(*args, **kwargs)`
  - ref(self) -> GLib.Variant

- **ref_sink**`(*args, **kwargs)`
  - ref_sink(self) -> GLib.Variant

- **split_signature**`(signature)`
  - Return a list of the element signatures of the topmost signature tuple.<br /><br />If the signature is not a tuple, it returns one element with the entire<br />signature. If the signature is an empty tuple, the result is [].<br /><br />This is useful for e. g. iterating over method parameters which are<br />passed as a single Variant.

- **store**`(*args, **kwargs)`
  - store(self, data)

- **take_ref**`(*args, **kwargs)`
  - take_ref(self) -> GLib.Variant

- **unpack**`(self)`
  - Decompose a GVariant into a native Python object.

- **unref**`(*args, **kwargs)`
  - unref(self)



## VariantBuilder

### Runtime functions ††


## VariantDict

### Runtime functions ††


## VariantType

### Runtime functions ††

