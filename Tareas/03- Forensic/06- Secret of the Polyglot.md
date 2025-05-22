## Descripcion
The Network Operations Center (NOC) of your local institution picked up a suspicious file, they're getting conflicting information on what type of file it is. They've brought you in as an external expert to examine the file. Can you extract all the information from this strange file?Download the suspicious file [here](https://artifacts.picoctf.net/c_titan/8/flag2of2-final.pdf).

## Solucion
```
# Descargar el archivo
wget https://artifacts.picoctf.net/c/XXX/polyglot.pdf

# Utilizar binwalk para analizar el archivo
binwalk polyglot.pdf

# Extraer los archivos embebidos
binwalk -e polyglot.pdf

# Inspeccionar los archivos extraídos para encontrar la bandera


```

## Flag
picoCTF{p0lyg10t_f1l3s_4r3_c00l}