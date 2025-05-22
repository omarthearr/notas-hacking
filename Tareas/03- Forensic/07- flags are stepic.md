## Descripcion
A group of underground hackers might be using this legit site to communicate. Use your forensic techniques to uncover their message

Additional details will be available after launching your challenge instance.

## Solucion
```
# Descargar la imagen
wget https://artifacts.picoctf.net/c/XXX/stepic.png

# Utilizar stepic para extraer los datos ocultos
stepic --decode -i stepic.png -o output.txt

# Leer el archivo de salida para obtener la bandera
cat output.txt


```

## Flag
picoCTF{fl4g_h45_fl4g6f5548ea}