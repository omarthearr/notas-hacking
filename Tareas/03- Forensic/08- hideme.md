## Descripcion
Every file gets a flag.The SOC analyst saw one image been sent back and forth between two people. They decided to investigate and found out that there was more than what meets the eye [here](https://artifacts.picoctf.net/c/262/flag.png).
## Solucion
```
Descargue la imagen, le hice un binwalk -e archivo -d. Eso me llevo a otras carpetas, hasta la ultima carpeta habia una imagen png que contenia la bandera

```

## Flag
picoCTF{Hidding_An_imag3_within_@n_image_82101824