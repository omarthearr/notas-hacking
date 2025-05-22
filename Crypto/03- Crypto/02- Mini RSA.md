## Descripcion

Este reto presenta un mensaje cifrado con RSA utilizando un exponente público pequeño (`e = 3`) y un módulo `n` ligeramente mayor que el mensaje elevado al cubo. La clave está en que el mensaje fue acolchado, haciendo que `m^e` sea apenas mayor que `n`.

## Solucion
```
# Paso 1: Obtener los valores de c, n y e proporcionados en el desafío.

# Paso 2: Dado que e es pequeño y m^e > n, se puede intentar encontrar la raíz cúbica de c + k*n para diferentes valores de k.

# Paso 3: Iterar sobre posibles valores de k hasta encontrar una raíz cúbica entera que, al convertirse a bytes, contenga el formato de la bandera.

# Ejemplo en Python:
from Crypto.Util.number import long_to_bytes
import gmpy2

for k in range(100000):
    m_candidate = gmpy2.iroot(c + k * n, e)
    if m_candidate[1]:
        flag = long_to_bytes(m_candidate[0])
        if b"picoCTF" in flag:
            print(flag.decode())
            break



```

## Flag
picoCTF{e_sh0u1d_b3_lArg3r_7adb35b1}