## Descripcion
Run the Python script and convert the given number from decimal to binary to get the flag.
[Download Python script](https://artifacts.picoctf.net/c/22/convertme.py)
## Solucion
```
--2025-02-20 21:11:09--  https://artifacts.picoctf.net/c/22/convertme.py
Resolving artifacts.picoctf.net (artifacts.picoctf.net)... 3.160.5.18, 3.160.5.71, 3.160.5.93, ...
Connecting to artifacts.picoctf.net (artifacts.picoctf.net)|3.160.5.18|:443... connected.
HTTP request sent, awaiting response... 200 OK
Length: 1189 (1.2K) [application/octet-stream]
Saving to: 'convertme.py'

convertme.py           100%[==========================>]   1.16K  --.-KB/s    in 0s      

2025-02-20 21:11:09 (721 MB/s) - 'convertme.py' saved [1189/1189]

omarthearr21-picoctf@webshell:~$ ls 
README.txt  code.py  codebook.txt  convertme.py  datos  file  flag
omarthearr21-picoctf@webshell:~$ 
omarthearr21-picoctf@webshell:~$ python convertme.py
If 34 is in decimal base, what is it in binary base?
Answer: ^CTraceback (most recent call last):
  File "/home/omarthearr21-picoctf/convertme.py", line 23, in <module>
    ans = input('Answer: ')
KeyboardInterrupt

omarthearr21-picoctf@webshell:~$ python convertme.py
If 38 is in decimal base, what is it in binary base?
Answer: 00100110
That is correct! Here's your flag: picoCTF{4ll_y0ur_b4535_762f748e}

```
`picoCTF{4ll_y0ur_b4535_762f748e}`