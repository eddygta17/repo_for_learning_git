# Learning Git in a Day

### Installing git
In most modern GNU/Linux systems, Git is already installed. Even if they are not, it is easy to install them.

> sudo apt-get install git -y

for installing on Debian based systems, or,

> sudo pacman -Sy git 

for installing on Arch based systems.


### Cloning a project
The most basic command in Git is to clone a repository. It is done as:

> git clone < url to the repository >

The repository URL may use any protocol such as git, ftp, or https. To clone a project into a specific folder, use the command:

> git clone < url to the repository > < name of folder >
