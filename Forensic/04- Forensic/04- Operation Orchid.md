## Descripcion

Download this disk image and find the flag.Note: if you are using the webshell, download and extract the disk image into `/tmp` not your home directory.

- [Download compressed disk image](https://artifacts.picoctf.net/c/214/disk.flag.img.gz)


## Solucion
```
# Descargar y descomprimir la imagen de disco
wget https://artifacts.picoctf.net/c/214/disk.flag.img.gz
gunzip disk.flag.img.gz

# Utilizar 'mmls' para identificar las particiones y obtener el offset
mmls disk.flag.img

# Montar la partición correspondiente
sudo mount -o loop,offset=411648 disk.flag.img mnt

# Navegar al directorio y copiar el archivo cifrado
cp mnt/root/flag.txt.enc .

# Buscar la contraseña en el historial de bash
cat mnt/root/.bash_history | grep openssl

# Descifrar el archivo utilizando la contraseña encontrada
openssl aes-256-cbc -d -in flag.txt.enc -out flag.txt -k unbreakablepassword1234567

# Leer la bandera
cat flag.txt


```

## Flag
picoCTF{qu1t3_a_v13w_2020}