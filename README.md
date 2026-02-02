# YouTube RTSP Streaming Tool

A lightweight Python utility for maintaining stable RTSP streams to YouTube Live.
This tool is designed to help keep long-running RTSP streams reliable by monitoring bandwidth usage and automatically restarting streams when issues are detected.

## Features
Monitors bandwidth usage for each active stream
Automatically restarts streams if performance drops or disconnects occur
Written in Python
Designed for Ubuntu/Linux (should work on most Linux distributions)
Simple configuration with only a few required settings

## Quick Start
1. Clone the Repository
git clone https://github.com/yourusername/yourrepo.git
cd yourrepo

2. Configure the Program
Open the template configuration file:
nano config.template.json

Update the following variables for your setup:
ip — IP address of your RTSP source
stream_key — YouTube Live stream key
program_location — Path to your streaming executable (ffmpeg, etc.)
Save the file as:
config.json

## Running the Program
Start the tool with:
python3 main.py

## Dependencies
Some dependencies may need to be installed the first time you run the program.
You can install Python packages with:
pip install -r requirements.txt
Or install system packages using:
sudo apt install <package-name>
(Only needed once.)

## Notes
This tool is intended for long-duration YouTube Live RTSP streaming setups.
Ideal for monitoring unattended streams and reducing downtime.
