Wed Mar  4 12:14:46 2015  jpmorgen@snipe

This is a meta-package that collects together routines necessary for
reducing, fitting and analyzing McMath-Pierce stellar spectrograph
data, particularly observations of Io.  To use it do

git clone --recursive https://github.com/jpmorgen/ssg_reduce.git

and occationally do a

git submodule update --remote

to update the code with upstream changes.

If you want to modify any of the code, it would be best for you to
create your own fork on github OF THE PARTICULAR SUBMODULE YOU ARE
WORKING IN on your github account.  Tweak the code there to your
heart's delight and then issue a pull request for me to incorportate
it into the whole package.
