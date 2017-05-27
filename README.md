# Bandwidth

Clone from <http://zsmith.co/bandwidth.htm>

Bandwidth: a memory bandwidth benchmark for x86 / x86_64 based GNU/Linux/Windows/MacOS

---

Quick Start

    yum install nasm

    rpm -ivh nasm-2.10.07-7.el7.x86_64.rpm

    touch /usr/include/stropts.h

        main.c:60:21: fatal error: stropts.h: No such file or directory

        #include <stropts.h>

    cd ./bandwidth-1.3.1

    make bandwidth64

    ./bandwidth64 --h

    ./bandwidth64 --fastest --title inspurXXX_perf --csv inspurXXX_perf.csv

