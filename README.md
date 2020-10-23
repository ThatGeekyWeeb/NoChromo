# NoChromo
A quick bootstrapper. That can bootstrap any device with `curl` and `tar` + coreutils, with just 400MB
## Latest work
Currently NoChromo can fully bootstrap armv7l Chromebooks with glibc 2.27!
## The idea
The original idea for NoChromo, was getting XBPS to Chrom\*OS, but during the development, I leaned more towards the idea that NoChromo would simply be a bootstrapper.\
Thus, NoChromo is now mainly a bootstrapper, taking devices from nothing but `bash`(or in the future `sh`), coreutils, `curl`, and `tar`(with `xz` support)\
These tarballs and scripts can be used for any usage, and are purely for the purpose of bootstrapping any device from basic utils, as a project for such seemed to not pre-exist
***
#### Extra Info
Everything within this repo is distributed under the present MIT license, althought the software within the tarballs or compiled during the bootstrap may be licensed under a different license.\
The tarballs found or used withing this repo are compiled staticly, with only static libraries (No shared libraries are compiled or provided), all binary executables are statically compiled, with zero dynamic linking.
***
##### Arch Info
ChromeOS comes on `amd64`, `i686` (or used to), `armv7hf`, and `aarch64`.\
My only device containing ChromeOS (My as in ThatGeekyWeeb), is `armv7hf` based, so until everything is *working* from said device, only tarballs/links for ARMv7hf will be found here.
