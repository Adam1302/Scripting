# Scripting

In this directory you will find four scripts:

1. BACKUP
    This program allows a user to backup and use version history with their files. In other words, it is a very, very basic version of Git!
    See the program for its usage!
2. COUNTDOWN
    This program counts down to 0 using an H:MM:SS display. It can take input in seconds only, minutes and seconds, or hours, minutes, and seconds.
    "Usage: ./count_down seconds
		        ./count_down minutes seconds
		        ./count_down hours minutes seconds"
3. FILE DOWNLOADER
    This program allows a user to download all files of a specified format off of a webpage.
    Usage: ./downloader site file_format
          ex. ./downloader site .mp3
4. RECURSIVE CHMOD
    This program applies the chmod function recursively to all files in directories or subdirectories
    of the current location. The specific chmod command can be specified.
    Usage: chmod_r permission_change
          ex. chmod_r a+r
          ex. chmod_r u+r
