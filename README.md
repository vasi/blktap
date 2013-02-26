- MacPorts dependencies: libuuid autoconf automake libtoolize gcc47

```
./autogen.sh
CC=gcc-mp-4.7 LDFLAGS="-L/opt/local/lib" CPPFLAGS="-I/opt/local/include" \
    ./configure
make -C vhd -j2
make -C vhd install
make -C include install
```
