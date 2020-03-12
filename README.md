# TunSafe
Source code of the TunSafe client.

This open sourced TunSafe code is AGPL-1.0 licensed. Do note that the repository contains BSD and OpenSSL licensed files, so if you want to release a version based off of this repository you need to take that into account.

To build on Windows, open TunSafe.sln and build, or run build.py.

To build on Linux, run build_linux.sh

To build on FreeBSD, run build_freebsd.sh

## Add modifications for the linux building
The source code of master branch on https://github.com/TunSafe/TunSafe has something wrong with the building on linux (on Centos for me), and pbiering pulled a request to solve this https://github.com/TunSafe/TunSafe/pull/56, but it seemed not to be merged into the branch in time. Here I modified the code according to pbiering's request and ran it successfully on Centos 7.3(maybe you can try to run tunsafe with my output file as "./tunsafe"). The following is the README.md of pbiering's request which showed how to build tunsafe source code on Centos or Enterprise Linux 7. Just clone the code from this repo and build it as pbiering said, thanks for the contribution of pbiering and hope everyone can enjoy it!
### Tunsafe official repo https://github.com/TunSafe/TunSafe
### pbiering's repo https://github.com/pbiering/TunSafe
<p align="right">Hickey Zhao</p>



