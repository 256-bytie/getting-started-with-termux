# **Getting-started-with-termux**
A beginner-friendly guide to using Termux, covering installation, setup, basic commands, and essential tools.

# **Info**

• Termux is a terminal emulator for Android that provides a Linux environment.

• It allows users to run a full Linux distribution, install packages, and develop software directly on their device.

**Requirements**

• Android device with version 7.0 or higher.

• Recommended: At least 2GB of free storage space.

**Features**

• Access to the Linux command line on Android.

• Support for a variety of programming languages and tools.

• Ability to run scripts and manage files.

# **Installation**

1. Go to the [Termux page on F-Droid](https://f-droid.org/en/packages/com.termux/)
2. Download and install the APK.
3. Open the app and allow permissions as prompted.

**∆ Basic Commands**

After opening Termux, familiarize yourself with a few basic commands:

• Update packages: Before installing any packages, update your package list:

```bash
pkg update
pkg upgrade
```
• Install basic packages: 
   • Git (version control): 

```bash
pkg install git
```
• Python (for programming):

```bash
pkg install python
```
• Nano or Vim (text editors):

```bash
pkg install nano  # or vim
```
• Curl (to transfer data):

```bash
pkg install curl
```

**Customize Environment**

• Bash configuration: Edit your '.bashrc' file to add aliases or environment variables:

```bash
nano ~/.bashrc
```
Add aliases like:
```bash
alias ll='ls -la'
```
Reload with:
```bash
source ~/.bashrc
```

**Install and Use Development Tools**
 • Programming: Install languages like Node.js, Python, or PHP.

```bash
pkg install nodejs
pkg install php
```

**Accessing and Managing Files**
 • Storage permissions: Allow Termux access to your Android storage:

```bash
termux-setup-storage
```
This creates a storage directory in Termux, linked to shared storage folders.

**Learn and Practice Linux Commands**
Start with basics like ls, cd, cp, mv, mkdir, rm, etc.

Let me know if you'd like help setting up anything specific!
