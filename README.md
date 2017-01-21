## dtruss for OSX

A copy of dtruss distributed with Brendan Gregg's [Dtrace Tools](http://www.brendangregg.com/dtrace.html)

It's been changed so the old -o argument  (print CPU times) has been moved to
-x.  -o is now an optional argument to specify a filename to send the syscall
info to.  Default is to send to stderr.
