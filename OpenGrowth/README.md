# Installation of OpenGrowth

Download and unzip the [OpenGrowth](https://sourceforge.net/projects/opengrowth/), and

```bash
cd /home/*/OpenGrowth_1.0/Source
code Makefile
```

then modify the scripts to

```c++
INCLUDE =-I/usr/include/openbabel-2.0
LDFLAGS =-rdynamic /usr/lib64/libopenbabel.so
```

then in terminal,

```bash
make
```

OpenGrowth will installed in your machine. You can download the [resources](https://sourceforge.net/projects/opengrowth/files/Resources_1.0.2.zip/download) for test. Manager Ma has also install it on mazda. You can find it in /pubhome/spft/OpenGrowth.  
