### Descripción

What does this `bDNhcm5fdGgzX3IwcDM1` mean? I think it has something to do with bases.

### Solución 

```
Input: `bDNhcm5fdGgzX3IwcDM1`
Output: l3arn_th3_r0p35
```

```
omarthearr21-picoctf@webshell:~$ python
Python 3.10.12 (main, Sep 11 2024, 15:47:36) [GCC 11.4.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> import base64
>>> base64.b64decode('bDNhcm5fdGgzX3IwcDM1')
b'l3arn_th3_r0p35'
```

`picoCTF{l3arn_th3_r0p35}`