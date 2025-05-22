## Descripcion

Download this disk image and find the flag.Note: if you are using the webshell, download and extract the disk image into `/tmp` not your home directory.

- [Download compressed disk image](https://artifacts.picoctf.net/c/138/disk.flag.img.gz)


## Solucion
```
wget al archivo
gzip -d disk.img.gz
ls -lah disk.img.gz
mmls disk fla.img
fls disk.flag.img -o 360448
fls disk.flag.img -o 360448 | grep flag
icat disk disk.flag.img -o 360448 2371

```

## Flag
picoCTF{qu1t3_a_v13w_2020}