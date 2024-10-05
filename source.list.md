kali linux

deb http://http.kali.org/kali kali-rolling main contrib non-free
deb-src http://http.kali.org/kali kali-rolling main contrib non-free



deb http://archive.ubuntu.com/ubuntu noble main restricted universe multiverse
deb http://archive.ubuntu.com/ubuntu noble-updates main restricted universe multiverse
deb http://archive.ubuntu.com/ubuntu noble-backports main restricted universe multiverse
deb http://security.ubuntu.com/ubuntu noble-security main restricted universe multiverse



# Ubuntu sources have moved to the /etc/apt/sources.list.d/ubuntu.sources
# file, which uses the deb822 format. Use deb822-formatted .sources files
# to manage package sources in the /etc/apt/sources.list.d/ directory.
# See the sources.list(5) manual page for details.
# Main repository
deb http://archive.ubuntu.com/ubuntu/ 24.0.1 main restricted universe multiverse
deb-src http://archive.ubuntu.com/ubuntu/ 24.0.1 main restricted universe multiverse

# Updates
deb http://archive.ubuntu.com/ubuntu/ 24.0.1-updates main restricted universe multiverse
deb-src http://archive.ubuntu.com/ubuntu/ 24.0.1-updates main restricted universe multiverse

# Security updates
deb http://security.ubuntu.com/ubuntu/ 24.0.1-security main restricted universe multiverse
deb-src http://security.ubuntu.com/ubuntu/ 24.0.1-security main restricted universe multiverse

# Backports
deb http://archive.ubuntu.com/ubuntu/ 24.0.1-backports main restricted universe multiverse
deb-src http://archive.ubuntu.com/ubuntu/ 24.0.1-backports main restricted universe multiverse
