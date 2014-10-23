auto-cygwin-install
===================


## Install instructions
Automated cygwin install. Just download the project as a zip file, extract and run cygwin-install.bat to install cygwin + apt-cyg + packages required for apt-cyg + optional packages.

You can edit the `packages.bat` batch file to specify which optional packages you'd like installed. Modify the `SET PACKAGES` variable with 
which packages you wish to install.


## Current Bugs

* Sometimes fails initial install attempting to install packages.
    in this case, just wait until cygwin completes it's initial 
    installation and then run it again. The second setup
    should install the listed packages + the required 
    packages for apt-cyg.





Created by wjrogers: https://gist.github.com/wjrogers/1016065.

Suggest this workflow for this project: http://scottchacon.com/2011/08/31/github-flow.html

Source URL:
https://github.com/rtwolf/cygwin-auto-install/

If you've found this project helpful, please support me by buying me a coffee: http://www.mind-manual.com/blog/buy-me-a-coffee/

As you may know, "A programmer is just a tool which converts caffeine into code". Thanks in advance!
