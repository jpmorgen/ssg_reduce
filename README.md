Wed Mar  4 12:14:46 2015  jpmorgen@snipe

This is a meta-package that collects together routines necessary for
reducing, fitting and analyzing McMath-Pierce stellar spectrograph
data, particularly observations of Io.  Following the documentation at:

http://git-scm.com/book/en/v2/Git-Tools-Submodules

to use it do

git clone --recursive https://github.com/jpmorgen/ssg_reduce.git

and occationally do a

git submodule update --remote

to update the code.

If you want to modify any of the code, do so from the individual
sub-directories by creating your own branch and pushing your changes
from there.  To avoid the problems with submodule commits getting out
of order on the main project, I'll be the only one keeping track of
that.


