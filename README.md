# Server Performance Stats

A Bash script that analyzes basic Linux server performance statistics.

## About

Server Performance Stats is a simple Linux monitoring script that collects and displays basic server information.

The script provides:

- Total CPU usage
- Memory usage (used and free)
- Disk usage
- Top 5 processes by CPU usage
- Top 5 processes by memory usage

## Requirements

- Linux operating system
- Bash shell

## Installation

Clone the repository:

```bash
git clone https://github.com/AlfredHaber/server-performance-stats.git
```

Navigate to the project folder:

```bash
cd server-performance-stats
```

Give execution permission:

```bash
chmod +x server-stats.sh
```

## Running the Script

Execute:

```bash
./server-stats.sh
```

## Example

Output example:

```
Server Performance Statistics

CPU Usage:
CPU Usage: 10%

Memory Usage:
Used: 2GB
Free: 6GB

Disk Usage:
Used: 55%

Top Processes:
PID USER COMMAND
```

## Project Structure

```
server-performance-stats
│
├── server-stats.sh
└── README.md
```

## Project URL

https://github.com/AlfredHaber/server-performance-stats