Eaglercraft 26
A lightweight setup guide to host and run Eaglercraft 26 locally using a Python HTTP server.

Prerequisites
Before starting, make sure you have Python 3.x installed on your system.

You can check by running python --version or python3 --version in your terminal.

If you don't have it, download it from python.org (be sure to check "Add Python to PATH" during installation).

Quick Setup Guide
Create the Folder
Create a new folder named Eagler26 on your computer (for example, inside your Documents directory).

Add the Game File
Place your Eaglercraft .html file inside the Eagler26 folder.

Open Terminal / Command Prompt
Open Command Prompt, VS Code Terminal, or PowerShell, then navigate to your folder:

Bash
cd C:\Users\YOUR_USERNAME\Documents\Eaglercraft\Eagler26
(Replace YOUR_USERNAME with your actual Windows username).

Start the Local Server
Run the following command to start a local server:

Bash
python -m http.server 8000
(If python doesn't work, try python3 -m http.server 8000).

Play the Game
Open your browser and visit:
