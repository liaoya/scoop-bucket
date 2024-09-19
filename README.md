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

```bash
curl -sL https://github.com/brechtsanders/winlibs_mingw/releases/download/12.2.0-14.0.6-10.0.0-ucrt-r2/winlibs-x86_64-posix-seh-gcc-12.2.0-llvm-14.0.6-mingw-w64ucrt-10.0.0-r2.7z.sha256

curl -sL https://github.com/brechtsanders/winlibs_mingw/releases/download/12.2.0-14.0.6-10.0.0-ucrt-r2/winlibs-i686-posix-dwarf-gcc-12.2.0-llvm-14.0.6-mingw-w64ucrt-10.0.0-r2.7z.sha256
```

`main` and `version` contain different `winlibs`, the version is a little old.

`notepad4.json` is copied from <https://github.com/epoweripione/scoop-bucket/blob/master/bucket/notepad4.json>
