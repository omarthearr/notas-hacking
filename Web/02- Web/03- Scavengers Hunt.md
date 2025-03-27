
## Descripcion

There is some interesting information hidden around this site [http://mercury.picoctf.net:27393/](http://mercury.picoctf.net:27393/). Can you find it?
## Solucion
```
Tuve que inspeccionar el HTML, ahi estaba la primera parte de la bandera como un comentario. Despues me meti a la hoja css donde estaba la segunda parte, luego me meti al archivo robots.txt cambiando la URL. Finalmente me meti a la ruta no indexada .DS_Storage
```

## Flag
picoCTF{th4ts_4_l0t_0f_pl4c3s_2_lO0k_d375c750}