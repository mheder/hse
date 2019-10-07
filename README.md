# hse - a BASH History Search Engine

## What hse does:

hse creates a directory named ~/.hse_history and writes the commands you issue into files, one file per day. This way, you have an unlimited, date-indexed history of issued commands.
On top of that, commands are instantly saved, unlike with the regular bash history that saves on bash exit and loses the history when your bash session is terminated unexpectedly, like when your ssh connection drops.

## Usage: 

1) put this file to ~/bin/ or any other suitable location
2) to the end of your .bashrc add the following line:
```source ~/bin/hse```
