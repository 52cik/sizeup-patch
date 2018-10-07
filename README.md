# sizeup-patch

## usage

```sh
$ npx sizeup-patch
```

Can also use this command.

```sh
printf '\x00' | dd seek=$((0x947d)) conv=notrunc bs=1 of=/Applications/SizeUp.app/Contents/MacOS/SizeUp
```
