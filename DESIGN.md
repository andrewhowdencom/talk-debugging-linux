# Topics
- Point people at jvns.ca

# System Calls
- strace
- sysdig

## Fielding Questions
- What about many processes?
  - strace-many.sh script
  - just supplying a bunch of pids

- What about processes that are dynamically created?
  - Use an aggregator, like sysdig
  - Get the process to report its pid and then pause, resume it when you've listened to its calls.

# Network
- tcpdump (also works for udp)
- netstat

# Signals 
- strace

