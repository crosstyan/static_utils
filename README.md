# Static Build artifacts for common tools

See [arm/bin](arm/bin) for the artifacts. Note that the tripple is `arm-linux-gnueabihf`. (Although I don't believe [glibc](https://en.wikipedia.org/wiki/Glibc) is actually used since it's a static build)

See the build instructions for cross-compilation in the corresponding markdown files.

Binaries with `_debug` suffix are the version that has not been stripped.

- [strace](strace.md)
- [gdbserver](gdbserver.md)

## Toolchains

[arm-linux-gnueabihf-linaro-bin](https://aur.archlinux.org/packages/arm-linux-gnueabihf-linaro-bin) from [snapshots.linaro.org/gnu-toolchain](https://snapshots.linaro.org/gnu-toolchain/14.0-2023.06-1/)
