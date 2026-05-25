# Understanding Version Control & Git

## 1. Downloading Git
Git is an open-source tool available for Windows, Mac, and Linux.

Download Git from:
https://git-scm.com/downloads

Git automatically detects your operating system.

### 2. Installing Git on Windows

Steps:
- Download Git installer
- Open the installer
- Click Next and use default settings
- Click Install
- Click Finish

Git is now installed successfully.

### 3. Installing Git on Mac

Using Homebrew:

``` bash ````
brew install git
git --version

Or:

Download Git from Git website
Install using the .dmg file

### 4. Installing Git on Linux

Ubuntu/Debian:

sudo apt update
sudo apt install git -y
git --version

Fedora: A Linux distribution sponsored by Red Hat. It is known for newer features and is commonly used by developers.

sudo dnf install git

Arch Linux:A lightweight Linux distribution that gives users more control and customization.

sudo pacman -S git

###  5. What is Git Bash?

Git Bash provides a Linux-like terminal on Windows.

##### Benefits:

Run Git commands
Execute Linux commands
Manage repositories easily

### 6. Verify Git Installation

##### Run:

git --version

Example Output:

git version 2.41.0

### 7. Git Configuration

##### Configure username:

git config --global user.name "Your Name"

##### Configure email:

git config --global user.email "your-email@example.com"

##### Verify configuration:

git config --global user.name
git config --global user.email
Local vs Global Configuration


 Local:

Applies only to one repository

##### Global:

Applies to all repositories