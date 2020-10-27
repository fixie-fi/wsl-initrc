# wsl-initrc

Run /etc/init.d/rc 2 at system boot

- This script enables you to start linux services like ssh and apache2 on system boot

# Installation

1. Import WSL init.xml to Task Scheduler
   - Type your windows credentials when asked
2. copy sudoers.d/initrc to /etc/sudoers.d in wsl or wsl2
