# fix for `brew install i386-elf-gcc`

install dependency manual
```
$ brew install gmp
$ brew install libmpc
```

then install gcc
```
$ brew install i386-elf-binutils
$ brew install i386-elf-gcc
```