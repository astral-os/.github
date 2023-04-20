# astral-os

astral-os is an OS focused on minimalism and correctness.

Basic distro info:

* kernel - [MINIX3](https://www.minix3.org/)
* SSL Library - [wolfSSL](https://www.wolfssl.com/)
* libc - [musl-libc](https://www.musl-libc.org/)
* coreutils - suckless [sbase-box](http://core.suckless.org/sbase/) /
[ubase-box](http://core.suckless.org/ubase/)
    - awk - [onetrueawk](https://github.com/onetrueawk/awk)
* /bin/sh - [dash](http://gondor.apana.org.au/~herbert/dash/)
* interactive shell - [mksh](http://www.mirbsd.org/mksh.htm)
* init system - suckless [sinit](https://core.suckless.org/sinit/)
    - [svc](http://r-36.net/scm/svc/log.html) + custom scripts
* device netlink management - [nldev](http://r-36.net/scm/nldev/log.html)
* root execution - [OpenDoas](https://github.com/Duncaen/OpenDoas)
* C compiler toolchain:
    - compiler: [clang/llvm](https://github.com/llvm/llvm-project)
    - linker: [mold](https://github.com/rui314/mold)
* package manager: [ppmpss](https://github.com/astral-os/ppmpss)
    - packages built from source with flags for optimization
