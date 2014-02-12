# Makefile Buildpack

**Note**: This has only been tested with [starphleet](https://github.com/wballard/starphleet)

## Structure
This one looks for a Makefile, and optionally for a configure, Then it
runs the classic formula:

```
./configure
make
make install
make start
```

