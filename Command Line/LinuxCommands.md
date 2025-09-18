# Navigating File System

**pwd** (print working directory): prints the directory you're in

**cd** (change directory): changes your directory

**ls** (list directories): lists all the files in your current directory

**touch**: creates a new blank file

**cat**: displays simple short text file

**less**: page-like text file viewer for larger text files

**history**: shows some of the previous commands ran

**clear**: what u think dipshit

**cp** (COPY!!): (filename) (path to copy to)
- Wildcards: placeholders used to copy multiple files at once
  - *: represents any char/string
  - ?: represents one char
  - [] : represents any character within the brackets

**mv** (move): moving or renaming files
- renaming: (oldfilename) (newfilename) (works with directories too)
- moving: (filename) (path) !works with multiple files as well: (file1) (file2) (path)

**mkdir** (make directory): making directories and subdirectories
- (directoryname)
- subdirectories: mkdir -p (directory)/(subdirectory)/(subdirectory)

**rm** (remove): removes files
- rm (file)
- rm -r directory (r for recursive, as all files in the directory need to be deleted as well)
  - rmdir (directory) also works

**find**: 
- find (directoryname) -name (filename)
- find (directory) -type (filetype (like d for directory)) -name (foldername)

**help**: common command for executable programs
- -help, --help, -?, etc.

**man** (manual): shows manual, similar to help, for programs

**whatis**: provides a brief summary of what a command does.

**alias**: creates a name for a long command so you don't have to keep typing it. almost like a method
- alias (aliasName) = (longCommand)
- now just type aliasName and long command will be run

**exit/logout**: closes terminal. If using a GUI, same thing as clicking x on the tab