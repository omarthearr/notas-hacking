## Descripcion

En este desafío, se proporciona un mensaje cifrado mediante RSA con un módulo `n` pequeño. El objetivo es descifrar el mensaje utilizando las claves públicas proporcionadas.


## Solucion
```
# Paso 1: Obtener los valores de c, n y e proporcionados en el desafío.

# Paso 2: Factorizar n para obtener p y q.
# Esto se puede hacer utilizando herramientas como factordb.com.

# Paso 3: Calcular φ(n) = (p - 1) * (q - 1).

# Paso 4: Calcular d, el inverso modular de e módulo φ(n).
# d = inverse(e, φ(n))

# Paso 5: Descifrar el mensaje.
# m = pow(c, d, n)

# Paso 6: Convertir m a bytes y luego a una cadena legible.
# flag = long_to_bytes(m).decode()


```

## Flag
picoCTF{sma11_N_n0_g0od_00264570}