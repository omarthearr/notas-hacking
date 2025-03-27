Can you break into this super secure portal? `https://jupiter.challenges.picoctf.org/problem/56816/` ([link](https://jupiter.challenges.picoctf.org/problem/56816/)) or http://jupiter.challenges.picoctf.org:56816

Solucion
```
Inspeccione la pagina y adentro del codigo HTML venia la verificacion de la contrasena. En esa funcion de verificacion venia el password en partes, solo tuve que encontrar el orden correcto y armar la contrasena. Lo hice sacando partes del array
flag[8] + flag[2] + flag[5]...
>>'picoCTF{not_this_again_33775b}'

```
picoCTF{not_this_again_33775b}

