## Descripcion
Now you DON’T see me.This [report](https://artifacts.picoctf.net/c/84/Financial_Report_for_ABC_Labs.pdf) has some critical data in it, some of which have been redacted correctly, while some were not. Can you find an important key that was not redacted properly?
## Solucion
```
# Descargar el archivo PDF
wget https://artifacts.picoctf.net/c/264/Financial_Report_for_ABC_Labs.pdf

# Utilizar pdftotext para extraer el texto del PDF
pdftotext Financial_Report_for_ABC_Labs.pdf output.txt

# Leer el archivo de salida para encontrar la bandera
cat output.txt



```

## Flag
picoCTF{C4n_Y0u_S33_m3_fully}