# Software_engineering


## Initialize a git repository

```
parallels@ubuntu-linux-22-04-desktop:~$ ls
Desktop    Downloads  Pictures  Software_Engineer_Tech_Titans  Videos
Documents  Music      Public    Templates
```


```
parallels@ubuntu-linux-22-04-desktop:~$ git init 
Reinitialized existing Git repository in /home/parallels/.git/
parallels@ubuntu-linux-22-04-desktop:~$ git clone https://github.com/bakhtiyorjondadajonov/Software_Engineer_Tech_Titans.git
Cloning into 'Software_Engineer_Tech_Titans'...
remote: Enumerating objects: 13, done.
remote: Counting objects: 100% (13/13), done.
remote: Compressing objects: 100% (10/10), done.
remote: Total 13 (delta 1), reused 13 (delta 1), pack-reused 0
Receiving objects: 100% (13/13), 85.76 KiB | 1.79 MiB/s, done.
Resolving deltas: 100% (1/1), done.
parallels@ubuntu-linux-22-04-desktop:~$ ls
Desktop    Downloads  Pictures  Software_Engineer_Tech_Titans  Videos
Documents  Music      Public    Templates
parallels@ubuntu-linux-22-04-desktop:~$ cd Desktop
parallels@ubuntu-linux-22-04-desktop:~/Desktop$ ls
'Parallels Shared Folders'
parallels@ubuntu-linux-22-04-desktop:~/Desktop$ git clone https://github.com/bakhtiyorjondadajonov/Software_Engineer_Tech_Titans.git
Cloning into 'Software_Engineer_Tech_Titans'...
remote: Enumerating objects: 13, done.
remote: Counting objects: 100% (13/13), done.
remote: Compressing objects: 100% (10/10), done.
remote: Total 13 (delta 1), reused 13 (delta 1), pack-reused 0
Receiving objects: 100% (13/13), 85.76 KiB | 3.90 MiB/s, done.
Resolving deltas: 100% (1/1), done.
parallels@ubuntu-linux-22-04-desktop:~/Desktop$ cd Software_Engineer_Tech_Titans/
parallels@ubuntu-linux-22-04-desktop:~/Desktop/Software_Engineer_Tech_Titans$ ls
ET         myfile.json  myfile.yaml           parsejson.py  parseyaml.py
README.md  myfile.xml   myfile_12200288.json  parsexml.py   re
parallels@ubuntu-linux-22-04-desktop:~/Desktop/Software_Engineer_Tech_Titans$ cp myfile.json myfile_12204550.json
parallels@ubuntu-linux-22-04-desktop:~/Desktop/Software_Engineer_Tech_Titans$ ls
ET           myfile.xml            myfile_12204550.json  parseyaml.py
README.md    myfile.yaml           parsejson.py          re
myfile.json  myfile_12200288.json  parsexml.py
parallels@ubuntu-linux-22-04-desktop:~/Desktop/Software_Engineer_Tech_Titans$ git branch Akbarjon_12204550
parallels@ubuntu-linux-22-04-desktop:~/Desktop/Software_Engineer_Tech_Titans$ git branch
  Akbarjon_12204550
* bakhtiyorjon_12200288
parallels@ubuntu-linux-22-04-desktop:~/Desktop/Software_Engineer_Tech_Titans$ git switch Akbarjon_12204550 
Switched to branch 'Akbarjon_12204550'
parallels@ubuntu-linux-22-04-desktop:~/Desktop/Software_Engineer_Tech_Titans$ git branch 
* Akbarjon_12204550
  bakhtiyorjon_12200288
parallels@ubuntu-linux-22-04-desktop:~/Desktop/Software_Engineer_Tech_Titans$ git add .
parallels@ubuntu-linux-22-04-desktop:~/Desktop/Software_Engineer_Tech_Titans$ git commit 
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'parallels@ubuntu-linux-22-04-desktop.(none)')
parallels@ubuntu-linux-22-04-desktop:~/Desktop/Software_Engineer_Tech_Titans$ git commit -m "Akbarjon's commitment for SW engineering"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'parallels@ubuntu-linux-22-04-desktop.(none)')
parallels@ubuntu-linux-22-04-desktop:~/Desktop/Software_Engineer_Tech_Titans$ cd
parallels@ubuntu-linux-22-04-desktop:~$ got config --global user.email "akbarjon3524@gmail.com"
Command 'got' not found, but there are 17 similar ones.
parallels@ubuntu-linux-22-04-desktop:~$ git config --global user.email "akbarjon3524@gmail.com"
parallels@ubuntu-linux-22-04-desktop:~$ git config --global user.name "Akbarjon Matrasulov"
parallels@ubuntu-linux-22-04-desktop:~/Desktop/Software_Engineer_Tech_Titans$ git commit -m  "Akbarjon's cpmmitment for SW engineering course"
[Akbarjon_12204550 c8d8b07] Akbarjon's cpmmitment for SW engineering course
 1 file changed, 6 insertions(+)
 create mode 100644 myfile_12204550.json
parallels@ubuntu-linux-22-04-desktop:~/Desktop/Software_Engineer_Tech_Titans$ git push -u origin Akbarjon_12204550
fatal: unable to access 'https://github.com/bakhtiyorjondadajonov/Software_Engineer_Tech_Titans.git/': Could not resolve host: github.com
parallels@ubuntu-linux-22-04-desktop:~/Desktop/Software_Engineer_Tech_Titans$ git push -u origin Akbarjon_12204550
Username for 'https://github.com': Matrasulov
Password for 'https://Matrasulov@github.com': 
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 280 bytes | 280.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote: 
remote: Create a pull request for 'Akbarjon_12204550' on GitHub by visiting:
remote:      https://github.com/bakhtiyorjondadajonov/Software_Engineer_Tech_Titans/pull/new/Akbarjon_12204550
remote: 
To https://github.com/bakhtiyorjondadajonov/Software_Engineer_Tech_Titans.git
 * [new branch]      Akbarjon_12204550 -> Akbarjon_12204550
Branch 'Akbarjon_12204550' set up to track remote branch 'Akbarjon_12204550' from 'origin'.

```
