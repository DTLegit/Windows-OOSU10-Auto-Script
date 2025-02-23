# Windows-OOSU10-Auto-Script
This GitHub repository contains a simple script that auto-applies some O&amp;O Settings to Windows

Use at your own risk! I am NOT responsible for anyone who downloads this and decides to run it.

Basic Powershell knowledge is needed in order to use this script. 

Steps to use: 

1) Download or clone this repository, go into the script folder/directory, and open terminal as Administrator or use the right click menu from the Start Menu to access Windows Terminal as Adminstrator.
2) If you used the right click start menu directory, use the "cd" command to navigate to the respectibve directory of where you saved the script and it's folder.
3) Run the "Set-ExecutionPolicy Unrestricted" command in PowerShell to run this script.
4) Type ".\OOSU10-Auto.ps1" into your terminal.
5) Running this script with arguments is required. The output will tell you all of the available options that you have.
6) When the script is ran with your desired parameters, it will check automatically to see if local "OOSU10.cfg" or "OOSU10-Default.cfg" files exist within the same directory that it is being ran from. This means you can use your own custom OOSU10.cfg or OOSU10-Default.cfg files if you wish.
7) If neither of those two files exist, this script will go out and automatically download either of these files from pre-defined URLs that are set within the script itself. You can change those to custom URLs if you so desire and have your own custom repository of OOSU config files that you would like to use.
8) If you used the recommended function with the default set OOSU10.cfg file, have a cup of coffee and enjoy better privacy settings on Windows 10 or 11! 

Credit for the logic and function to the script used in older versions of Chris Titus Tech's WinUtil that had the "Run O&O ShutUp 10" Tweak available.

This script is made publically available for use and consumption under the terms and conditions set forth by the Mozilla Public License, with an additional requirement of proper credit being given if used in other projects or software. 

NOTE: **This script is considered to be in a finished state. However, additional testing still may be required to ensure that this can fully be used under production environments. Any and all testing and feedback/PRs to help fix any potential issues and improve code quality/efficiency with this script is welcome and highly encouraged to hopefully ensure that this script gets up to production quality. Thank you in advance for your time to anyone who opts to do so.** 

