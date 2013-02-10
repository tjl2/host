# host - a more flexible host command
Extremely simple Ruby script that allows you to throw URLs at your system's host command.

A common workflow for me is to want to look up the IP of a URL I'm currently browsing.
Rather than copy, paste then delete everything except the hostname, I can now just throw
the whole URL at my new host command.

Simply install this somewhere, then symlink it to somewhere in your path that precedes
/usr/bin (usually /usr/local/bin will be the best place).

## Note on paths on Mac OS X
My preference is to put this in /usr/local/bin, but OS X seems to put this path after
/usr/bin. To solve this, modify `/etc/paths` and move /usr/local/bin before /usr/bin in 
the list. All new shells will now have $PATH modified.
