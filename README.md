# Thread-Safe Counter Service

A high-performance static server class implementing a thread-safe counter with parallel read access and exclusive write operations.

## Features

- **Thread-safe operations**:
  - Multiple concurrent readers
  - Exclusive write access
  - No deadlocks or race conditions

- **Performance optimized**:
  - `ReaderWriterLockSlim` for minimal contention
  - Zero allocations in read path
  - Writer priority scheduling

