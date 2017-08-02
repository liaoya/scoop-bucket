# README

Tom's scoop bucket which contain the software does not exist in main and extras scoop bucket

The process to create a new json file

* Create a json file
* Copy to scoop\buckets\liaoya
* Make sure it work
* Check into git

## Check whether there're new software

Run the following command in PowerShell environment

    C:\Users\huifshen\scoop\apps\scoop\current\bin\checkver.ps1 * C:\Users\huifshen\scoop\buckets\liaoya -u

## Github release check

Run the command like `curl -s https://api.github.com/repos/PowerShell/Win32-OpenSSH/releases/latest`

Refer <https://developer.github.com/v3/repos/releases/>