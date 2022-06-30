# os


挖个坑，以后回来填。


```
├─concurrency                   
│  ├─async_io                   
│  ├─event_driven_io            
│  ├─inter_process_communication
│  │  ├─message_queue_posix     
│  │  ├─message_queue_systemv   
│  │  ├─pipe                    
│  │  │  ├─named_pipe
│  │  │  └─unnamed_pipe
│  │  ├─semaphore_posix
│  │  ├─semaphore_systemv
│  │  ├─shared_memory_posix
│  │  ├─shared_memory_systemv
│  │  ├─signal
│  │  ├─socket_tcpip
│  │  └─socket_unix
│  ├─language_implementation
│  │  ├─go
│  │  │  └─goroutine_channel
│  │  │      ├─condition_variable
│  │  │      ├─context
│  │  │      ├─lock
│  │  │      └─semaphore
│  │  └─python
│  └─routine_synchronization
│      ├─barrier
│      ├─condition_variable
│      ├─lock
│      └─semaphore
└─concurrency_in_distributed_system
    ├─coordinator
    │  ├─etcd
    │  ├─redis
    │  └─zookeeper
    └─rpc
        ├─go
        ├─grpc
        └─python
```
