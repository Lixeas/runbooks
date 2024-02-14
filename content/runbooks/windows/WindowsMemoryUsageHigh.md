# WindowsMemoryUsageHigh

## Meaning

This metric tracks the percentage of physical memory used on the server. High memory usage can indicate that the server is running out of RAM.

## Impact

When memory usage is high, the server may start to use disk swap space, which significantly slows down operations. This can degrade performance for applications and services.

## Diagnosis

1. Use Task Manager or Resource Monitor to identify processes consuming significant amounts of memory.
2. Review the server's workload and running services to determine if memory usage levels are expected.
3. Check for memory leaks in applications.

## Mitigation

1. Close or restart processes that are using excessive memory, especially if they show signs of a memory leak.
2. Increase the physical memory on the server if consistently high memory usage is observed.
3. Optimize or upgrade applications to reduce memory consumption.