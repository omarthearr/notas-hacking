## Descripcion

Download this disk image and find the flag.Note: if you are using the webshell, download and extract the disk image into `/tmp` not your home directory.

- [Download compressed disk image](https://artifacts.picoctf.net/c/214/disk.flag.img.gz)


## Solucion
```
# Descargar y descomprimir la imagen de disco
wget https://artifacts.picoctf.net/c/376/disk.img.gz
gunzip disk.img.gz

# Crear un punto de montaje y montar la imagen
mkdir mnt
sudo mount -o loop,offset=1048576 disk.img mnt

# Navegar al directorio .ssh y copiar la clave privada
cp mnt/home/ctf-player/.ssh/id_rsa key_file
chmod 600 key_file

# Conectarse a la máquina remota utilizando la clave
ssh -i key_file -p 60303 ctf-player@saturn.picoctf.net


```

## Flag
picoCTF{0p3r4710n_0n1_5ucc355}