## Descripcion

Download the disk image and use `mmls` on it to find the size of the Linux partition. Connect to the remote checker service to check your answer and get the flag.Note: if you are using the webshell, download and extract the disk image into `/tmp` not your home directory.[Download disk image](https://artifacts.picoctf.net/c/164/disk.img.gz)

Additional details will be available after launching your challenge instance.
## Solucion
```
wget al archivo
gzip -d disk.img.gz
ls -lah disk.img.gz
mmls disk.img
nc saturn.picoctf.net
20275 (O lo que mida el length la particion de linux)
```

## Flag
picoCTF{qu1t3_a_v13w_2020}