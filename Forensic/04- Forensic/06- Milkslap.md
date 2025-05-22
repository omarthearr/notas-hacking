## Descripcion

Download this disk image and find the flag.Note: if you are using the webshell, download and extract the disk image into `/tmp` not your home directory.

- [Download compressed disk image](https://artifacts.picoctf.net/c/214/disk.flag.img.gz)


## Solucion
```
# Descargar la imagen oculta
wget http://mercury.picoctf.net:58537/concat_v.png

# Utilizar 'zsteg' para analizar la imagen en busca de datos ocultos
zsteg concat_v.png



```

## Flag
picoCTF{m1lk_m3_b4by_1f4e7e3}