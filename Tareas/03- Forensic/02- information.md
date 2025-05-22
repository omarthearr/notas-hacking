## Descripcion
Files can always be changed in a secret way. Can you find the flag? [cat.jpg](https://mercury.picoctf.net/static/b4d62f6e431dc8e563309ea8c33a06b3/cat.jpg)


## Solucion
```
# Descargar la imagen
wget https://artifacts.picoctf.net/c/XXX/cat.jpg

# Utilizar exiftool para inspeccionar los metadatos
exiftool cat.jpg

# Buscar campos sospechosos, como "License"
# Decodificar el valor si está en base64
echo "cGljb0NURntleWVzX2FyZV9jb29sXX0=" | base64 -d

La bandera se encuentra en el campo "License" de los metadatos, codificada en base64.
```

## Flag
picoCTF{keys_are_cool}