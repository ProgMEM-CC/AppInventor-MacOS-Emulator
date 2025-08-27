# AppInventor-MacOS-Emulator

A fixed port of MIT AppInventor Emulator for MacOS (Old one was broken completely)

Made using android emulator, command line tools, and a long shell script.

# Installation 

Step 1:

Go to [Releases](https://github.com/ProgMEM-CC/AppInventor-MacOS-Emulator/releases) for a fully made binary zip.
Unzip the archive and then run the run-emulator script (double click on it)
It WILL say untrusted or smth, as it is not codesigned.

Step 2:

With admin:

Go to Settings > Privacy and Security 
Scroll down to the bottom.
You will see a prompt saying run-emulator cannot be opened because ... 
Click open anyway, then enter your admin password. 

Without admin:

Open Terminal

Type `xattr -c path/to/run-emulator`
Press enter
Type `xattr -d com.apple.quarantine path/to/run-emulator`
Press enter
Type `chmod +x path/to/run-emulator`
Press enter
And then run the script.


Step 3:

And once the Terminal app opens, you just need to wait for the emulator to install and boot.


