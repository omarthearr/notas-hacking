

### Descripción

Can you find the flag in [file](https://jupiter.challenges.picoctf.org/static/315d3325dc668ab7f1af9194f2de7e7a/file)? This would be really tedious to look through manually, something tells me there is a better way.

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

