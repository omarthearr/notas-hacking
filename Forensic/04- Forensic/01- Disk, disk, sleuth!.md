## Descripcion

Use `srch_strings` from the sleuthkit and some terminal-fu to find a flag in this disk image: [dds1-alpine.flag.img.gz](https://mercury.picoctf.net/static/626ea9c275fbd02dd3451b81f9c5e249/dds1-alpine.flag.img.gz)
## Solucion
```
wget al archivo
gzip -d dds1-apline.flag.img.gz
ls -lah dds1-alpine.flag.img
string dds1-apline.flag.img | grep pico;
```

## Flag
picoCTF{qu1t3_a_v13w_2020}