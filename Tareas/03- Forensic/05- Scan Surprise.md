## Descripcion
I've gotten bored of handing out flags as text. Wouldn't it be cool if they were an image instead?You can download the challenge files here:

- [challenge.zip](https://artifacts.picoctf.net/c_atlas/16/challenge.zip)

Additional details will be available after launching your challenge instance

## Solucion
```
# Descargar la imagen
wget https://artifacts.picoctf.net/c/XXX/qr.png

# Utilizar zbarimg para escanear el código QR
zbarimg qr.png

# El resultado mostrará la bandera


```

## Flag
picoCTF{p33k_@_b00_b5ce2572}