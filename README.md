# FTP File Difference #

### What is this? ###

A utility to find difference between local & remote via FTP in just one load, i used Filezilla File Difference but i had to go through to the entire directory to find the difference so made this utility you can add some folders ignore list and increase response time. File difference algorithm is simple and it is not precise enough as it is initial version.

P.S: UI ain't good enough, i would appreciate if anyone help me in UI.

### Setup Guide ###

* Open `fileDiff-server.php`, Add your folders to scan and ignore variable (make sure path should be relative or full path)
* Upload `fileDiff-server.php` to your accessible server.
* Open `fileDiff-client.php`, Specify your basepath, HTTP URL path of that file which we uploaded `fileDiff-server.php` Add your folders to ignore on local to scan
* Thats it. You're ready to go

### Folder Scan Guide ###
* Currently only wildcard folder scanning and ignorance folder available on `server` file

### TODO :: 7th-Apr-2015 ###
1. Support `*` to scan current directory, if placed on root.
3. Local (`fileDiff-client.php`) ignore to function accurately (*directory support, wildcard support and to make it work like gitignore*)
2. Add this revision (*file*) to ignore.