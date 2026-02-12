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
## feat: build simple web dashboard using Flask
- Created backend server for metrics API
- Displayed system stats in browser
- Improved usability
## feat: add auto-refresh dashboard every 5 seconds
- Implemented JavaScript auto-refresh
- Real-time monitoring experience
- Cleaner UI updates
## style: improve dashboard UI with basic CSS styling
- Better layout
- Organized metric cards
- Improved readability
## chore: optimize Dockerfile for smaller image size
- Used slim base image
- Removed unnecessary dependencies
- Reduced build size
## feat: add docker-compose configuration
- Enabled multi-container setup
- Simplified deployment
- Defined service dependencies
## feat: enable environment variable configuration
- Added configurable refresh rate
- Enabled flexible port settings
- Improved production readiness
