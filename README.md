# 4chan_Bash
a simple bash script which sends you to any 4chan board via the command line

this is just a simple project i did since i recently learned how to put arguments in my shell scripts

## usage

in a terminal, type "4chan", followed by the (abbrieviated) name of the board you want to visit (e.g. "4chan g")

a new firefox window will pop up with the board you typed

## installation

for now, download this repository as a zip file

in the terminal the main script '4chan' must be made executable.
do this by typing "chmod +x 4chan" in the "4chan_Bash" directory

from there put the script in any "bin" directory 
the command can then be used normally
alternatively, after making the script executable, just type "./4chan 'board name here'" in the "4chan_Bash" directory

## dependencies

### operating system

this script can be used in any UNIX-based OS 
(i.e. linux, mac OS, BSD) (sorry windows users)

### browsers

for now, you must have firefox installed (not a problem since most linux beginner distros come with firefox)

## upcoming features

- ability to go to 4chan homepage by default
- support for other browsers (e.g. chromium, brave)
