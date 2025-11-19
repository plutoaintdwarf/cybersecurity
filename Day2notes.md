##LINUX + BANDIT (0→2)

  #1. Basic Linux Commands I Used
   Command                  Meaning                      
| `ls`                    | list files in a directory    |
| `cat file`              | read the content of a file   |
| `pwd`                   | shows current directory path |
| `ssh user@host -p port` | login to a remote machine    |
| `cd directory`          | change directory             |
| `exit`                  | logout                       |

  #2. Bandit Level 0 → 1

Used SSH to log in:

ssh bandit0@bandit.labs.overthewire.org -p 2220


Used ls to view files

Found readme

Used cat readme to reveal password




  #3. Bandit Level 1 → 2

Logged into Level 1

Found a tricky file named -

Used:

cat ./-


to read it



🎮 What Are CTF Wargames?

CTF = Capture The Flag
Wargames = cybersecurity challenges designed to train you

A CTF wargame is an online platform where you solve hacking or cybersecurity puzzles.
Each challenge gives you a flag (usually a password or secret code).
You use that flag to unlock the next level.








