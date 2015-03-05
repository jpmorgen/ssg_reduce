Wed Mar  4 12:14:46 2015  jpmorgen@snipe

This is a meta-package that collects together routines necessary for
reducing, fitting and analyzing McMath-Pierce stellar spectrograph
data, particularly observations of Io.  To use it do something like:

cd $HOME/pro
git clone --recursive https://github.com/jpmorgen/ssg_reduce.git

and occationally do a

git submodule update --remote

to update the code with upstream changes.

If you want to modify any of the code, it would be best for you to
create your own fork on github OF THE PARTICULAR SUBMODULE YOU ARE
WORKING IN on your github account.  Say this is the util directory.
Then bring the util code down to a subdirectory on your computer, like
~/pro_development with:

cd $HOME/pro_development
git clone https://github.com/YOUR_GIT_USERNAME/util.git

Make sure the $HOME/pro_development directory is AHEAD of everything
else on your IDL_PATH:

set IDL_PATH= +$HOME/pro_development:$IDL_PATH

Tweak and test the code, then you can use git at the command line (or
other user interface in your OS) to stage (git add), inspect (git
status) and commit (git commit) the changes locally and push them back
to your GitHub account when you want to share them (git push).  Issue a pull
request on GitHub and I will go from there.


You may find the git reference book http://git-scm.com/book/en/v2/
useful, particularly:

http://git-scm.com/book/en/v2/Git-Basics-Recording-Changes-to-the-Repository
http://git-scm.com/book/en/v2/Git-Basics-Working-with-Remotes
http://git-scm.com/book/en/v2/Git-Tools-Submodules
