# container-monitoring-app
Containerized System Monitoring App is a Docker-based application that tracks real-time system metrics like CPU, memory, disk usage, and container health. It ensures consistent deployment, improves visibility, and helps understand system behavior in modern containerized environments.
# Containerized System Monitoring App
This project helps monitor system performance using containerized services.
## Technologies Used
- Docker
- Basic Linux commands
- System monitoring concepts
## Project Objective
To understand how system monitoring works in containerized environments.
## Features
- CPU usage monitoring
- Memory usage tracking
- Container-based deployment
## Learning Outcome
- Understood Docker basics
- Learned importance of system monitoring
## feat: add disk usage monitoring module
- Implemented disk usage tracking using Linux commands (df -h)
- Parsed and displayed disk statistics in the console
- Improved overall system coverage
## feat: integrate real-time CPU and memory stats using /proc
- Used /proc/stat and /proc/meminfo
- Calculated CPU usage percentage dynamically
- Improved monitoring accuracy
## refactor: optimize system metrics collection script
- Reduced redundant command calls
- Improved performance and reduced overhead
- Cleaned up function structure
## feat: add container health check functionality
- Used docker ps and docker inspect
- Displayed container status (running, exited, unhealthy)
- Added basic error handling
## feat: add logging mechanism for system metrics
- Created log file for CPU, memory, disk stats
- Implemented timestamped entries
- Enabled persistent monitoring data storage
