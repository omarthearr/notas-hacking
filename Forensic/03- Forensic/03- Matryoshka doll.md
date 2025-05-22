## Descripcion

Matryoshka dolls are a set of wooden dolls of decreasing size placed one inside another. What's the final one? Image: [this](https://mercury.picoctf.net/static/f6cc2560a70b1ea811c151accba5390f/dolls.jpg)
## Solucion
```
Binwalk dolls.jpg
unzip dolls.jpg
unzip 2_c.jpg
unzip 3_c.jpg
unzip4_c.jpg
cat flag.txt
```

## Flag
