## Descripcion

We found this [file](https://mercury.picoctf.net/static/7b2d7c26630e977197022d0af09e3aeb/tunn3l_v1s10n). Recover the flag.
## Solucion
```
wget al archivo
filee tunn3l_v1s10n
exiftool tunn3l v1s1on
xxd -l 100 tunn3l v1s1on
cp tunn3l v1s1on
hexeditor flag.bmp
eog flag.bmp
python
hex(800)
```

## Flag
picoCTF{qu1t3_a_v13w_2020}