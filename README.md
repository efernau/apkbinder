# apkbinder
Automatic backdooring apk with meterpreter (PoC)

# How to
apk place within "apkbinder" directory, named app-debug.apk

# Dependencies
```
Kali-Rolling:
	python 2.7.x libraries: os re shutil zipfile tempfile argparse
	metasploit
	apktool 2.0
	dex2jar
```
	
# Components
```
apkbinder.py - APK automatic backdooring script
permisos.xml - Permission of meterpreter
```

# Command line
```
usage: apkbinder.py [-h] -l LHOST [-p LPORT]

Backdooring APK with meterpreter

optional arguments:
  -h, --help            show this help message and exit
  -l LHOST, --lhost LHOST
                        LHOST select local host
  -p LPORT, --lport LPORT
                        LPORT select local port
```

# Comments
script based by https://github.com/nodoraiz/AndroidAnalysis/blob/master/modify.py (nodoraiz)

# Bugs
create multiple sessions, but only one has privileges

# Authors
vay3t & 4c1d0_b1n4r10
