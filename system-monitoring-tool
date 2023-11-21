
#!/bin/bash

# Function to display CPU usage
function display_cpu_usage() {
    echo "=== CPU Usage ==="
    top -b -n 1 | grep "%Cpu"
    echo
}

# Function to display memory usage
function display_memory_usage() {
    echo "=== Memory Usage ==="
    free -m
    echo
}

# Function to display disk space
function display_disk_space() {
    echo "=== Disk Space ==="
    df -h
    echo
}

# Main function to display all information
function main() {
    display_cpu_usage
    display_memory_usage
    display_disk_space
}

# Run the main function
main
