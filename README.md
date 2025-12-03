
# YouTube RTSP Streaming Tool - Setup & Usage Guide

A simple tool designed to maintain RTSP streams to the YouTube Live servers.

Features:

    Monitors the bandwidth used by each stream and restarts if necessary.
    Uses Python and runs on Ubuntu and likely other Linux versions.
    Easy to set up - just requires editing a few variables in the config file. 

Quick Start:

    Open the config.template.json file in a text editor. 
    Edit the ip, stream_key, and program_location variables for your specific setup.
    Save the file as config.json and exit the editor.


Run the Program:
    To run the program type "python3 main.py"
    It may be necessary to install a few dependencies. Simply use PIP or apt to install them. 
    Installing the dependencies is only necessary the first time the program is run. 
