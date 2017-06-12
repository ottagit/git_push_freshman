[//]: # (Just enough command line to get started with Git)
# The Command Line
---

The command line, basically, is where it all began. It is the life of a system, from a developer's perspective, and it is the life of a developer. Essentially, with the command line, one gets to understand how systems function much better than by utilising the GUI.

In UNIX-like systems (Linux, OSX, etc), it is referred to as the **Terminal** while in Windows it is the **Command line** (or cmd). In other tongues it is the command-line user interface (**CLI**). Having been the most essential part of the computing history it follows that the CLI is as functional as the GUI. However, on the most part, the CLI provides much more functionality than the GUI, even though it may seem otherwise.

Git has been in existence for a couple of years, and with that it has achieved success in wowing a large number of people. Git starts out as fully-functional in the CLI but, with its popularity, it has been afforded the advantages of having certain GUI applications developed for it and being included in recent Integrated Development Environments (IDEs) such as Netbeans and Android Studio.

## CLI Basics
It is critical for any developer to understand the basics of the CLI. In this chapter just a few commands will be mentioned (perhaps not the full functionality).

### Terminal basics
These commands will (only) function in a **Linux** OS environment. Use them if your OS is Linux-based.

`touch` - creates a file

&emsp;e.g

&emsp;&emsp; `touch filename.txt` creates text file with the name 'filename' on the current path

`mkdir` - creates a directory (or a folder)

&emsp;e.g

&emsp;&emsp; `mkdir newfolder` creates a directory of the name 'newfolder' on the current path

`cd` - changes directory (or path)

&emsp;e.g

&emsp;&emsp; Assuming the current path is `/home/User/Developer/` on the terminal then `cd newfolder` will switch the current directory (path) to `/home/User/Developer/newfolder` if and only if the directory `newfolder` exists inside `/home/User/Developer`. If it does not exists, then create it using the previously listed command :).

&emsp;&emsp; There's also another trick to `cd`. Typing `cd ..` in the command line will switch to the parent directory. That is to say, if the current path is `/home/User/Developer/newfolder` then `cd ..` will switch to `/home/User/Developer/`. I have used `cd ..` as it will work in most Linux distributions. However, in some distributions `cd..` may be used.


### Command Line Basics
These commands will only function in a **Windows** OS environment. Use them if your OS is Windows-based.

`cd. >` - creates a file

&emsp;e.g

&emsp;&emsp; `cd. > filename.txt` creates text file with the name 'filename' on the current path

`mkdir` - creates a directory (or a folder)

&emsp;e.g

&emsp;&emsp; `mkdir newfolder` creates a directory of the name 'newfolder' on the current path

`cd` - changes directory (or path)

&emsp;e.g

&emsp;&emsp; Assuming the current path is `C:\Users\Giant\Developer` on the terminal then `cd newfolder` will switch the current directory (path) to `C:\Users\Giant\Developer\newfolder` if and only if the directory `newfolder` exists inside `C:\Users\Giant\Developer\Developer`. If it does not exists, then create it using the previously listed command :).

&emsp;&emsp; There's also another trick to `cd`. Typing `cd ..` in the command line will switch to the parent directory. That is to say, if the current path is `C:\Users\Giant\Developer\newfolder` then `cd ..` will switch to `C:\Users\Giant\Developer`. `cd..` will also work.

---

Never thought you'd be a geek? Well, then you are one now.
