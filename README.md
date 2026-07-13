# Server Performance Stats

A Bash script to analyze basic Linux server performance statistics.

## Project Description

This project contains a shell script called `server-stats.sh` that collects and displays basic server performance information.

The script can be used on Linux servers to quickly check CPU usage, memory usage, disk usage, and running processes.

## Features

- CPU usage monitoring
- Memory usage monitoring
- Disk usage monitoring
- Display running processes
- Basic Linux server performance analysis

## Requirements

- Linux operating system
- Bash shell

## Installation

Clone the repository:

```bash
git clone https://github.com/AlfredHaber/server-performance-stats.git
```

Go to the project folder:

```bash
cd server-performance-stats
```

Give execution permission:

```bash
chmod +x server-stats.sh
```

## Usage

Run the script:

```bash
./server-stats.sh
```

## Example Output

```
Server Performance Statistics

CPU Usage:
CPU Usage: 0%

Memory Usage:
Used: 329 MB
Free: 7480 MB

Disk Usage:
Used: 55%

Top Processes:
PID USER COMMAND
```

## Project Structure

```
server-performance-stats/
│
├── server-stats.sh
└── README.md
```

## Technologies Used

- Bash
- Linux Commands
- Ubuntu WSL

## Author

Alfred Haber

## Project URL

https://github.com/AlfredHaber/server-performance-stats