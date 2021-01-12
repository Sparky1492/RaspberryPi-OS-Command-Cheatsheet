Change root into Raspberry OS in Linux
```
sudo apt install qemu-user proot    [Credit: nerd65536 @ https://raspberrypi.stackexchange.com/a/24011/43081]
sudo mount /mnt/path/to/raspbian /mnt/path/to/raspbian
sudo mount /mnt/path/to/raspbian/boot /mnt/path/to/raspbian/boot
sudo proot -q qemu-arm -S /mnt/path/to/raspbian/    [Credit: nerd65536 @ https://raspberrypi.stackexchange.com/a/24011/43081]
```
