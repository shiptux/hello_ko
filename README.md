
# Usage:

## Clone:

<code> git clone git@github.com:shiptux/hello_ko.git</code>

## Install require packages:

<code>sudo  apt install build-essential linux-headers-`uname -r` debheleper</code>

## Compile:

<code>cd hello_ko && dpkg-buildpackage -us -nc -us</code>

## Install:

<code>dpkg -i ../hello_ko\*.deb</code>

# Reference: https://blog.sourcerer.io/writing-a-simple-linux-kernel-module-d9dc3762c234
