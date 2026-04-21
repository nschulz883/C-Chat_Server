#  C Chat System

A multi-client chat application written in C using TCP sockets and pthreads.

##  Features
- Multi-client server
- Real-time message broadcasting
- Thread-per-client model
- Mutex synchronization

##  Build

```bash
make
```

##  Run

Start server:
```bash
./build/server
```

Start clients:
```bash
./build/client
```

##  Concepts
- Socket programming
- Multithreading
- Synchronization
- Networking fundamentals

##  Future Improvements
- Usernames
- Chat rooms
- select() instead of threads
- Message protocol
