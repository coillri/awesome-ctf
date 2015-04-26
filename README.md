# CTF Tools

A curated list of CTF frameworks, libraries, resources and softwares.

### Contributing

Please take a quick gander at the [contribution guidelines](https://github.com/apsdehal/ctf-tools/CONTRIBUTING.md) first.

#### _If you know a tool that isn't present here, feel free to open a pull request._

### Contents

- [CTF Tools](#ctf-tools)
  - [Create](#create)
    - [Web](#create-web)
    - [Forensics](#create-forensics)
  - [Solve](#solve)
    - [Attacks](#solve-attacks)
    - [Bruteforcers](#solve-bruteforcers)
    - [Creation Tools](#solve-create)
    - [Cryptography](#solve-crypto)
    - [Exploits](#solve-exploits)
    - [Forensics](#solve-forensics)
    - [Miscellaneous](#solve-misc)
    - [Reversing](#solve-reversing)
    - [Services](#solve-services)
    - [Steganography](#solve-stegano)
    - [Web](#solve-web)

- [Resources](#resources)
  - [Websites](#resources-websites)
    - [Tutorials](#resources-tutorials)


# Create

*Tools used for creating CTF challenges*

## Forensics

*Tools used for creating Forensics challenges*

- [Registry Dumper](http://www.kahusecurity.com/tools/RegistryDumper_v0.1.zip) - Dump your registry

## Web

*Tools used for creating Web challenges*

*JavaScript Obfustcators*

- Metasploit JavaScript Obfustcator
- Uglify


# Solve

*Tools used for solving CTF challenges*

## Attacks

*Tools used for performing various kinds of attacks*

- [Layer 2 attacks](https://github.com/tomac/yersinia) - Attack various protocols on layer 2

## Crypto

*Tools used for solving Crypto challenges*

- XORTool
- [RSATool](https://github.com/ius/rsatool) - Generate private key with knowledge of p and q

## Bruteforcers

*Tools used for various kind of bruteforcing (passwords etc.)*

- John The Ripper
- John The Jumbo
- Ophcrack

## Exploits

*Tools used for solving Exploits challenges*

- [Metasploit](http://www.metasploit.com/) - Most used penetration testing software
- [pwntools](https://github.com/Gallopsled/pwntools) - CTF Framework for writing exploits

## Forensics

*Tools used for solving Forensics challenges*

- [Audacity](http://sourceforge.net/projects/audacity/) - Analyze sound files (mp3, m4a, whatever)
  - `apt-get install audacity`
- [bkhive and samdump2](http://sourceforge.net/projects/ophcrack/files/samdump2/) - Dump SYSTEM and SAM files
  - `apt-get install samdump2 bkhive`
- [CFF Explorer](http://www.ntcore.com/exsuite.php) - PE Editor
- [creddump](https://code.google.com/p/creddump/) - Dump windows credentials
- [extundelete](http://extundelete.sourceforge.net/) - Used for recovering lost data from mountable images
- [Foremost](http://foremost.sourceforge.net/) - Extract particular kind of files using headers
  - `apt-get install foremost`
- [fsck.ext4](http://linux.die.net/man/8/fsck.ext3) - Used to fix corrupt filesystems
- [Malzilla](http://malzilla.sourceforge.net/) - Malware hunting tool
- [PDF Streams Inflater](http://malzilla.sourceforge.net/downloads.html) - Find and extract zlib files compressed in PDF files
- [ResourcesExtract](http://www.nirsoft.net/utils/resources_extract.html) - Extract various filetypes from exes
- [Shellbags](https://github.com/williballenthin/shellbags) - Investigate NT\_USER.dat files
- [UsbForensics](http://www.forensicswiki.org/wiki/USB_History_Viewing) - Contains many tools for usb forensics
- [Volatility](https://github.com/volatilityfoundation/volatility) - To investigate memory dumps
- [Wireshark](https://www.wireshark.org/) - Analyze the network dumps
  - `apt-get install wireshark`

*Registry Viewers*
- [RegistryViewer](http://www.gaijin.at/en/getitpage.php?id=regview) - Used to view windows registries
- [Extra](http://www.forensicswiki.org/wiki/Windows_Registry)

## Reversing

*Tools used for solving Reversing challenges*

- [Androguard](https://github.com/androguard/androguard) - Reverse engineer Android applications
- [Apk2Gold](https://github.com/lxdvs/apk2gold) - Yet another Android decompiler
- [ApkTool](http://ibotpeaches.github.io/Apktool/) - Android Decompiler
- [BinWalk](https://github.com/devttys0/binwalk) - Analyze, reverse engineer, and extract firmware images.
- [Boomerang](https://github.com/nemerle/boomerang) - Decompile x86 binaries to C
- IDA Pro - Ultimate solution to reversing needs
- [Jadx](https://github.com/skylot/jadx) - Decompile Android files
- [Krakatau](https://github.com/Storyyeller/Krakatau) - Java decompiler and disassembler
- [Revelo](http://www.kahusecurity.com/tools/Revelo_v0.6.zip)
- [Uncompyle](https://github.com/williballenthin/shellbags) - Decompile Python 2.7 binaries (.pyc)

*JavaScript Deobfustcators*

- [Detox](http://relentless-coding.org/projects/jsdetox/install)

## Services

*Various kind of useful services available around the internet*

- [CSWSH](http://ironwasp.org/cswsh.html) - Cross-Site WebSocket Hijacking Tester
- [Request Bin](http://requestb.in/) - Lets you inspect http requests to a particular url

## Stegano

*Tools used for solving Steganography challenges*

- pngtools - For various analysis related to PNGs
  - `apt-get install pngtools`
- [SmartDeblur](https://github.com/Y-Vladimir/SmartDeblur) Used to deblur and fix defocused images
- Steganabara
- [Steghide](http://steghide.sourceforge.net/)
- Stegsolve

## Web

*Tools used for solving Web challenges*

- [SQLMap](https://github.com/sqlmapproject/sqlmap) - Automatic SQL injection and database takeover tooli
- [XSSer](http://xsser.sourceforge.net/) - Automated XSS testor


# Resources

*Where to discover about CTF*

## Websites

*Various general websites about and on ctf*

- [CTF Time](https://ctftime.org/) - General information on CTF occuring around the worlds

## Writeups Collections

*Collections of CTF writeups*

- [CTF Writeups (Community)](https://github.com/ctfs/) - CTF Writeups Repos maintained by community
- [Shell Storm](shell-storm.org/repo/CTF/) - CTF Writeups Repo maintained by Jonathan Salwan

## Tutorials

*Tutorials to learn how to play CTFs*
