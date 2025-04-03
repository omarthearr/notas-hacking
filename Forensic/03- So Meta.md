## Descripcion

Find the flag in this [picture](https://jupiter.challenges.picoctf.org/static/89b371a46702a31aa9931a2a2b12f8bf/pico_img.png).
## Solucion
```
Hice un wget al arhivo picture
man exiftool
exiftool pico_img.png
eiftool pico_img.png -Artist
```

## Flag
picoCTF{s0_m3ta_eb36bf44}