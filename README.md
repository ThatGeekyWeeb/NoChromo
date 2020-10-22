# NoChromo
A WIP future replacement for Chromebrew, as the code lacks any innovation, and in simple terms, is truly just bad.\
## Latest work
Currently NoChromo can fully bootstrap armv7l Chromebooks with glibc 2.27!
## The idea
The original idea was (and still is) bootstrapping Chrom\*OS with all the required deps to install [XBPS](https://github.com/void-linux/xbps) on it.
!["qouteimg"](https://cdn.discordapp.com/attachments/699685435198144553/767871920779165727/kIPjyPCj6SXtQpKLy4EqpHdSVxNonwoAhQBigBFQIwIVCO7kxhbRVlRBCgCFAGKgLgQoHpCXEhSPhQBigBFoHYiQPVE7exX2iqKA.png)\
Although these tarballs and scripts can be used for any usage, and are purely for the purpose of bootstrapping Chrom\*OS and allowing for anything other than Chromebrew to take over from there.
***
#### Extra Info
Everything within this repo is distributed under the present MIT license, althought the software within the tarballs or compiled during the bootstrap may be licensed under a different license.\
The tarballs found or used withing this repo are compiled staticly, with only static libraries (No shared libraries are compiled or provided), all binary executables are statically compiled, with zero dynamic linking.
***
##### Arch Info
ChromeOS comes on `amd64`, `i686` (or used to), `armv7hf`, and `aarch64`.\
My only device containing ChromeOS (My as in ThatGeekyWeeb), is `armv7hf` based, so until everything is *working* from said device, only tarballs/links for ARMv7hf will be found here.
