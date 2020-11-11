THIS PROJECT IS IN LIFE-SUPPORT MODE
This repo tracks the old version of Wifite (v1) which does not receive frequent updates and has many bugs (check out the Isuses tab!).

There's a new version of Wifite (Wifite2) available at https://github.com/derv82/wifite2. Wifite2 has more features, bug fixes, and reliability.

Try the new Wifite2, especially if you're having problems with Wifite v1

About
Wifite is for Linux only.

Wifite is an automated wireless attack tool.

Wifite was designed for use with pentesting distributions of Linux, such as Kali Linux, Pentoo, BackBox; any Linux distributions with wireless drivers patched for injection. The script appears to also operate with Ubuntu 11/10, Debian 6, and Fedora 16.

Wifite must be run as root. This is required by the suite of programs it uses. Running downloaded scripts as root is a bad idea. I recommend using the Kali Linux bootable Live CD, a bootable USB stick (for persistent), or a virtual machine. Note that Virtual Machines cannot directly access hardware so a wireless USB dongle would be required.

Wifite assumes that you have a wireless card and the appropriate drivers that are patched for injection and promiscuous/monitor mode.

Execution
To download and execute wifite, run the commands below:

wget https://raw.github.com/derv82/wifite/master/wifite.py
chmod +x wifite.py
./wifite.py

Required Programs
Please see the installation guide on the wiki for help installing any of the tools below.

Python 2.7.x. Wifite is a Python script and requires Python to run.

aircrack-ng suite. This is absolutely required. The specific programs used in the suite are:

airmon-ng,
airodump-ng,
aireplay-ng,
packetforge-ng, and
aircrack-ng.
Standard linux programs.

iwconfig, ifconfig, which, iw
Suggested Programs
