

### Descripción

What is 0x3D (base 16) in decimal (base 10)?

### Solución 

```
omarthearr21-picoctf@webshell:~$ python
Python 3.10.12 (main, Sep 11 2024, 15:47:36) [GCC 11.4.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> bin(42)
'0b101010'
>>> bin(42)[2:]
'101010'
>>> 
KeyboardInterrupt
>>> int(0x3D)
61
>>> 
```


`picoCTF{61}`

### Notas adicionales

- Puede usarse incluso el intérprete de Python para convertir de hex a ascii

### Referencias

- https://www.rapidtables.com/convert/number/hex-to-ascii.html
- https://gchq.github.io/CyberChef