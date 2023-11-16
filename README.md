# Disk Report Python Script

## Overview

This Python script (`disk_report.py`) is designed to analyze disk usage within a specified directory. It calculates the total disk space used by each subdirectory and generates a CSV report with directory names and their respective disk space usage.

## Prerequisites

- Python 3.x
- Pandas library (`pip install pandas`)

## Usage

### Running the Script

```bash
python disk_report.py <root_directory> - replace this with the path of the directory you want to analyze.

### Script Details

Features
Recursive calculation of disk space usage for subdirectories.
Exception handling for potential errors during directory scanning.
Utilizes the Pandas library to create a CSV report.
How It Works
The script takes a root directory path as a command line argument.
It iterates through each entry in the specified directory.
For each entry, it calculates the total disk space usage, considering subdirectories.
The script generates a CSV report (disk_home_usage.csv) with directory names and their respective disk space usage.
Script Invocation
The script can be invoked using the shebang line:

bash
Copy code
#!/usr/bin/python3
Ensure the script has executable permissions:

bash
Copy code
chmod +x disk_report.py
Notes
Make sure to have the required permissions to access the specified directory.
Install the necessary Python libraries by running pip install pandas before using the script.
License

##This project is licensed under the MIT License.





