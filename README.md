# objective-c
# This shell scripts help you to run Objective-C on your linux machine

## What do you need?
- installed `GNUStep` https://www.techotopia.com/index.php/Installing_and_Using_GNUstep_and_Objective-C_on_Linux
- installed `clang` https://clang.llvm.org/get_started.html
- create ~/bin catalog in your home folder (if you don't have it already)
```console
foo@bar:~$ mkdir ~/bin catalog
```
- put this scripts and objc-file folder into your ~/bin catalog
- add new path to your `PATH` variable (permanently)
  * open `.bashrc` file
  ```console
  foo@bar:~$ gedit .bashrc
  ```
  * add this line in the bottom of file and save
  ```console
  # Export PATH
  export PATH=$PATH:$HOME/bin/
  ```
- you can use scripts in your terminal :)
 
#### objc-main
- makes a file main.m (Objective-C file) in current directory
- main.m has already Ocjective-C template inside

#### objc-class CLASS-NAME
- takes a CLASS-NAME as an argument
- make CLASS-NAME.h interface file in current directory
- make CLASS-NAME.m implementation file in current directory

#### objc
- compiles *.m files in current directory
- makes executable file a.out
- runs a.out file if compilation was correct
