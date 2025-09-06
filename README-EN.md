# CCUtilCommons

## What is CCUtilCommons?

> Libaries Can be or be expected to apply in C90 ~ C11, C++ 98 ~ C++17

​	Hello, this is a Utilities Repositories Collections including Common Middlewares for C And C++. Any one can use it or learn it for free. Libaries can be specified to apply from Embedded System to UpperLevel Programmings. 

## What are CCUtilCommons expected to includes?

### Data Structure Libraries

> Data Structure Libraries for C and C++. But As C++ owns STL, so DS Library for C++ are only for learning usage but not recommended to be applied in Production Environments

| Data Structure       | Descriptions                            |
| -------------------- | --------------------------------------- |
| Dynamic Array        | Dynamic Array owns dynamic size         |
| Linked List          | Linked Lists implemented by common ways |
| Stacked/Queued/Deque | Based on DA or LL operations            |
| Hash Map             | Just the Hash Map and Hash Libraries    |
| Balanced Tree        | AVL or RBTree                           |
| Nnary Tree           | Or B Tree Linke                         |
| CCString             | Common String for Operations            |

## 🕸 Network Module

Built around sockets, DNS, and HTTP:

| Submodules | Workflow |
| ------------------------ | ------------------------------------------------------------ |
| **Socket Encapsulation Layer** | Encapsulates `socket()`, `bind()`, `listen()`, `accept()`, `connect()`, etc. |
| **DNS Resolution** | Uses `getaddrinfo()`/`getnameinfo()` to support IPv4/IPv6 ([en.wikipedia.org](https://en.wikipedia.org/wiki/Getaddrinfo?utm_source=chatgpt.com)) |
| **TCP and UDP Support** | Configure non-blocking/timeout, buffering, and select/poll mode APIs |
| **HTTP Client/Server** | Implements basic HTTP requests/responses, supporting headers and chunked packets |
| **(Optional) Raw Packet Capture** | Encapsulates the `libpcap` interface to implement packet capture, filtering, and playback |

------

## 🛡 Concurrency and Synchronization Module

| Function | Work Content |
| ----------------- | --------------------------------------- |
| **Threads** | Encapsulates POSIX `pthread_create/join/detach` |
| **Mutex/Condition Variables** | Implements `mutex` and `cond` abstractions to avoid data races |
| **Thread Pool** | Worker threads, task queues, graceful start and end |
| **Atomic and Lock-Free** | Small module implementing atomic operations or lock-free queues (optional) |

------

## 📝 Logging and Configuration Module

| Function | Work Content |
| -------------- | ------------------------------------------------------------ |
| **Logging System** | Supports SEMVER-level logging (DEBUG/INFO/WARN/ERROR), with optional output to the terminal/file |
| **Configuration Parser** | Simple INI/JSON parser, or wraps `libconfuse` or `jansson` |
| **Command Line Parsing** | Implement `--flag` and `-o value` APIs, or refer to the Single Header Library |

------

## 🕰 Time and Timing Module

| Function | Subtasks |
| ---------------- | --------------------------------------------------- |
| **Time Processing** | Encapsulate `clock_gettime()` and `gettimeofday()` to obtain timestamps |
| **Sleep and Timer** | Implement millisecond/microsecond sleep, `timerfd`, and signal timing |
| **Performance Timing** | Record high-precision runtime for profiling |

------

## 🔐 Encoding and Compression Module

| Function | Workflow |
| ---------------- | ---------------------------------------- |
| **Character Encoding Conversion** | UTF-8/UTF-16/ISO8859-1 Conversion API |
| **Compression Tool** | Encapsulate `zlib` and implement `deflate/inflate` functionality |
| **Encryption and Hashing** | MD5/SHA1 or optional AES for digest/authentication and other functions |

## Bonus Library for Embedded System For MCUs

Waiting to be added...
