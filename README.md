This utility provides an enhanced command history for Bash, keeping track of all commands ever entered in any terminal window as well as the directory in which the command was entered and when.

PREREQUISITES
-------------

This script currently only works with Bash.  A modified version that works with zsh will be uploaded soon.
The script makes use of `xmlstarlet`, which can be downloaded from [http://xmlstar.sourceforge.net](http://xmlstar.sourceforge.net). 
The script also includes and uses a copy of `bash-preexec` by Ryan Caloras.


INSTALLATION
------------

1.  Copy the `.bash.capture` and `.bash-preexec.sh` scripts to your home directory.

2.  Copy the empty `.command.log` file to your home directory.

3.  Add a `source bash.capture` line to the bottom of your `.profile` or `.bashrc` file.
