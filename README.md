# LPI Linux Essentials

# 1.1. Linux Distributions

<ins>**1.1.1**</ins> 
- RHEL
- CentOs
- Ubuntu
- Fedora
- Debian
- OpenSUSE

<ins>**Components**</ins>

**![alt text](https://github.com/shubhdev79/LinuxCommands/blob/master/Components.png)**

- Checking the Version - **lsb_release -a**
- Checking the Kernel - **uname -r**
- Checking the GNU Core - **ls --version**
- Checking the X-Server Version - **sudo X -version**
# ------------------------------------------------------------

**1.1.2**
<ins> Linux Embeded Systems </ins>
- Android
- Raspberry Pi

**![alt text](https://github.com/shubhdev79/LinuxCommands/blob/master/1.1.2.png)**

# ------------------------------------------------------------

**1.1.3**
<ins> Linux in the Cloud </ins>

**![alt text](https://github.com/shubhdev79/LinuxCommands/blob/master/1.1.3.png)**

# ------------------------------------------------------------

<ins>**LAB - Some Commands**</ins>
- whoami (show username)
- pwd
- ls
- last (show listing of last logged in users)
- uptime 

# ------------------------------------------------------------

**1.2 Major Open Source Applications**

- 1.2.1 - Desktop Applications - Libre office, GIMP, FireFox, Mail Client- ThunderBird etc.
- 1.2.2 - Server Applications 

**![alt text](https://github.com/shubhdev79/LinuxCommands/blob/master/1.2.2.png)**

# ------------------------------------------------------------

# Package Management
**1. Debian Based- Ubuntu**
- .deb files
- (Installing the Deb Package- sudo dpkg -i htop_2.0.2-1_amd64.deb)
**HTOP** - This utility shows us system load and running processes
- Remove Package - sudo dpkg --remove htop
- apt-get

**2. RPM Based - Fedora, CentOS, OpenSuse**
- .rpm files
- (Installing the RPM Package - sudo rpm -i htop-2.2.0-3.el7.x86_64.rpm)
- Package is already present in /home/directory.
- Remove Package - sudo rpm --e htop
- yum 

**3. Compiling from Source**

**![alt text](https://github.com/shubhdev79/LinuxLPI-Course/blob/master/PackageInstall.png)**

# ------------------------------------------------------------

