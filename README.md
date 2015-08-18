# Vagrant Base Boxes

## How these boxes were built

These boxes were automatically built using [packer](http://www.packer.io) (v0.6.0) and the definitions in this repo:

```sh
$ cd packer
$ ./build.sh
```

- Fixes [slow DNS resolution](https://github.com/NREL/vagrant-boxes/issues/5)
