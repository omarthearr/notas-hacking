
### Descripción

Our flag printing service has started glitching!

Additional details will be available after launching your challenge instance.
### Solución 
Nos conectamos al puerto y recibimos una cadena
Luego nos pasamos a python y pegamos la cadena
```
omarthearr21-picoctf@webshell:~$ nc saturn.picoctf.net 56736
'picoCTF{gl17ch_m3_n07_' + chr(0x61) + chr(0x34) + chr(0x33) + chr(0x39) + chr(0x32) + chr(0x64) + chr(0x32) + chr(0x65) + '}'
^C
omarthearr21-picoctf@webshell:~$ python
Python 3.10.12 (main, Sep 11 2024, 15:47:36) [GCC 11.4.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> 
KeyboardInterrupt
>>> 'picoCTF{gl17ch_m3_n07_' + chr(0x61) + chr(0x34) + chr(0x33) + chr(0x39) + chr(0x32) + chr(0x64) + chr(0x32) + chr(0x65) + '}'
'picoCTF{gl17ch_m3_n07_a4392d2e}'
```


picoCTF{gl17ch_m3_n07_a4392d2e}