<b>T</b>his tool may be used for legal purposes only.  Users take full responsibility 
for any actions performed using this tool.  The author accepts no liability
for damage caused by this tool.  If these terms are not acceptable to you, then
do not use this tool.

This tool may be used for legal purposes only.  Users take full responsibility
for any actions performed using this tool.  If these terms are not acceptable to
you, then do not use this tool.

## Description

This script will make an outbound TCP connection to a hardcoded IP and port.
The recipient will be given a shell running as the current user (apache normally).

## Limitations

proc_open and stream_set_blocking require PHP version 4.3+, or 5+
Use of stream_select() on file descriptors returned by proc_open() will fail and return FALSE under Windows.
Some compile-time options are needed for daemonisation (like pcntl, posix).  These are rarely available.
