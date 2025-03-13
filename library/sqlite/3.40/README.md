# SQLite 3.40 Image

This directory contains the definition for the `unikraft.org/sqlite:3.40` image.

To run this image, [install Unikraft's companion command-line toolchain `kraft`](https://unikraft.org/docs/cli) and then you can run:

```
kraft build --no-cache --no-update --log-type basic --log-level debug --plat qemu --arch x86_64 .
kraft run .
```

Once executed you will be get the output of an SQL script.

## See also

- [How to run unikernels locally in Unikraft's Documentation](https://unikraft.org/docs/cli/running).
