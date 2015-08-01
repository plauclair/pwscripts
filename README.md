# ProcessWire Scripts
Handy installation and post installation scripts for ProcessWire.

Place files in your path and set them to executable. ``chmod +x filename``

Tested on OSX and reported to be compatible with Debian (Wheezy).

**You might need to change the default permissions and site profiles in the files.**

## Usage
Run ``pwprepare`` in terminal. By default, the script will install ProcessWire in *./wwwroot/*. 

Alternatively, it is also possible to run the script with an optional target directory, 
e.g. ``pwprepare public_html``, where *public_html* is the name of the tagtet directory.

When the script prompts for a branch to use, select either *master* or *dev*.

Then, when it prompts for a site profile to use, select one in the list.

You will then be asked to press the enter key to remove the install files (install.php, site/install). 
Do this only after you have fully completed the ProcessWire web install procedure.
