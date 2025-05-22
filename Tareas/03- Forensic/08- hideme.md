## Descripcion
Every file gets a flag.The SOC analyst saw one image been sent back and forth between two people. They decided to investigate and found out that there was more than what meets the eye [here](https://artifacts.picoctf.net/c/262/flag.png).
## Solucion
```
# Descargar la imagen
wget https://artifacts.picoctf.net/c/XXX/hideme.png

# Utilizar binwalk para analizar la imagen
binwalk -e hideme.png

# Inspeccionar los archivos extraídos para encontrar la bandera
La herramienta binwalk extrae archivos embebidos en la imagen, uno de los cuales contiene la bandera.


```

## Flag
picoCTF{h1d1ng_1n_p14n_s1ght}