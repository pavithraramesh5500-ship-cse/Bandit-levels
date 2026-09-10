**Level-0**

Log into the Bandit server and find the password for Level 01.

        ssh bandit0@bandit.labs.overthewire.org -p 2220

ssh → use SSH connection

bandit0 → username

bandit.labs.overthewire.org → Bandit server

-p 2220 → connect through port 2220

Think of a port like a door number.

Bandit tells you to use door 2220, not the usual SSH door 22.

After logging in, list the files in the home directory:

        ls

There is a file called : readme

read the file using : cat

        cat readme

The output gives the password for **Bandit Level 1**


