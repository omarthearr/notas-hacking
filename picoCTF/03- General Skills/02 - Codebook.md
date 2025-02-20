## Descripcion
Run the Python script `code.py` in the same directory as `codebook.txt`.

- [Download code.py](https://artifacts.picoctf.net/c/2/code.py)
- [Download codebook.txt](https://artifacts.picoctf.net/c/2/codebook.txt)

## Solucion
```
omarthearr21-picoctf@webshell:~$ wget https://artifacts.picoctf.net/c/2/code.py
--2025-02-20 21:07:59--  https://artifacts.picoctf.net/c/2/code.py
Resolving artifacts.picoctf.net (artifacts.picoctf.net)... 3.160.5.18, 3.160.5.93, 3.160.5.71, ...
Connecting to artifacts.picoctf.net (artifacts.picoctf.net)|3.160.5.18|:443... connected.
HTTP request sent, awaiting response... 200 OK
Length: 1278 (1.2K) [application/octet-stream]
Saving to: 'code.py'

code.py                100%[==========================>]   1.25K  --.-KB/s    in 0s      

2025-02-20 21:07:59 (82.4 MB/s) - 'code.py' saved [1278/1278]

omarthearr21-picoctf@webshell:~$ ls
README.txt  code.py  datos  file  flag
omarthearr21-picoctf@webshell:~$ wget https://artifacts.picoctf.net/c/2/codebook.txt
--2025-02-20 21:08:34--  https://artifacts.picoctf.net/c/2/codebook.txt
Resolving artifacts.picoctf.net (artifacts.picoctf.net)... 3.160.5.18, 3.160.5.71, 3.160.5.42, ...
Connecting to artifacts.picoctf.net (artifacts.picoctf.net)|3.160.5.18|:443... connected.
HTTP request sent, awaiting response... 200 OK
Length: 27 [application/octet-stream]
Saving to: 'codebook.txt'

codebook.txt           100%[==========================>]      27  --.-KB/s    in 0s      

2025-02-20 21:08:34 (22.0 MB/s) - 'codebook.txt' saved [27/27]

omarthearr21-picoctf@webshell:~$ ls
README.txt  code.py  codebook.txt  datos  file  flag
omarthearr21-picoctf@webshell:~$ python code.py
picoCTF{c0d3b00k_455157_7d102d7a}
omarthearr21-picoctf@webshell:~$ ^C
omarthearr21-picoctf@webshell:~$ 
```
`picoCTF{c0d3b00k_455157_7d102d7a}`