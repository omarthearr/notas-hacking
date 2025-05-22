## Descripcion

The one time pad can be cryptographically secure, but not when you know the key. Can you solve this? We've given you the encrypted flag, key, and a table to help `UFJKXQZQUNB` with the key of `SOLVECRYPTO`. Can you use this [table](https://jupiter.challenges.picoctf.org/static/1fd21547c154c678d2dab145c29f1d79/table.txt) to solve it?.

## Solucion
```
# Descargar los archivos proporcionados: mensaje cifrado y clave
wget https://artifacts.picoctf.net/c/XXX/cipher.txt
wget https://artifacts.picoctf.net/c/XXX/key.txt

# Leer el contenido de ambos archivos
cat cipher.txt
cat key.txt

# Utilizar la clave para descifrar el mensaje utilizando el cifrado Vigenère

# Herramientas como CyberChef pueden facilitar este proceso



```

## Flag
picoCTF{CRYPTOISFUN}