## Descripcion

Can you read files in the root file?

Additional details will be available after launching your challenge instance.


## Solucion
```
# Paso 1: Listar los permisos del archivo.
ls -l flag.txt

# Paso 2: Verificar que el usuario actual no tiene permisos de lectura.
# Si no los tiene, otorgar permisos con chmod.
chmod +r flag.txt

# Paso 3: Leer el archivo.
cat flag.txt

```

## Flag
picoCTF{uS1ng_v1m_3dit0r_021d10ab}