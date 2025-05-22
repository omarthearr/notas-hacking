## Descripcion

Can you get the real meaning from this file.Download the file [here](https://artifacts.picoctf.net/c_titan/111/enc_flag).


## Solucion
```
# Descargar el archivo proporcionado por el reto
wget https://artifacts.picoctf.net/c/XXX/interencdec.txt

# Inspeccionar el contenido del archivo
cat interencdec.txt

# El archivo contiene texto cifrado. Utilizar herramientas como CyberChef para analizar y descifrar el contenido.

# pasos en CyberChef:
# - Intentar decodificar en Base64
# - Aplicar ROT13
# - Probar con cifrados comunes como Vigenère o César



```

## Flag
picoCTF{d3crypt3d_m3ss4g3}