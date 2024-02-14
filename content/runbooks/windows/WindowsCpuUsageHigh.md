# WindowsCpuUsageHigh

## Meaning

This metric measures the percentage of CPU utilization on a Windows Server. High values indicate that the CPU is heavily used, which could be by one or more processes.

## Impact

High CPU usage can lead to slower response times for applications and services running on the server, potentially affecting end-user experience and system reliability.

## Diagnosis

1. Use Task Manager or Performance Monitor to identify processes with high CPU usage.
2. Check for running applications or services that may not be necessary.
3. Review recent changes to the server, such as software installations or updates, that could impact CPU utilization.

## Mitigation

1. Terminate unnecessary processes or services to free up CPU resources.
2. Consider scaling up the server's hardware or balancing the load across multiple servers.
3. Optimize applications for better CPU efficiency.
4. Update or patch software that may be causing high CPU usage due to bugs or inefficiencies.