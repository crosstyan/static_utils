# strace

```bash
./configure --target=arm-linux-gnueabihf \
    --host=arm-linux-gnueabihf \
    --build=x86_64-linux-gnu  \
    --prefix=/home/crosstyan/Image/rootfs \
    LDFLAGS='-static -pthread' \
    CC=/opt/gcc-arm-linux-guneabihf/bin/arm-linux-gnueabihf-gcc \
    CXX=/opt/gcc-arm-linux-guneabihf/bin/arm-linux-gnueabihf-g++
    CFLAGS="-O2"
```
