## Toolchains built for arm, x86, mips and mipseb

### All toolchains are built using buildroot

#### List:
  * **arm** -- uClibc, musl-libc
  * **arm64** -- uClibc
  * **mipsel** -- uClibc, musl-libc
  * **mips64el** -- uClibc
  * **x86** -- uClibc, musl-libc
  * **x86_64** -- uClibc
  * **mipseb** -- uClibc

gcc v6.3.0 (uClibc)

**Note:** All uClibc toolchains can build selinux enabled busybox and are patched to use google dns server addresses
    as a fallback if a valid nameserver is not found.

*libfl files are needed for the toolchains to work in Travis CI environment*

##### Check arch specific branches for their toolchains
