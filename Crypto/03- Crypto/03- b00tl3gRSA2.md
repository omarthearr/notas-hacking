## Descripcion

En este desafío, se proporciona un mensaje cifrado con RSA utilizando un exponente privado `d` pequeño, lo que lo hace vulnerable al ataque de Wiener.


## Solucion
```
# Paso 1: Obtener los valores de c, n y e proporcionados en el desafío.

# Paso 2: Utilizar RsaCtfTool para aplicar el ataque de Wiener.
# RsaCtfTool es una herramienta que implementa varios ataques contra RSA.

# Comando:
python RsaCtfTool.py --uncipher <ciphertext> -n <n> -e <e>





```

## Flag
picoCTF{bad_1d3a5_4783252}