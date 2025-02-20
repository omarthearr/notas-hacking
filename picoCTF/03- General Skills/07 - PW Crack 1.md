Can you crack the password to get the flag?Download the password checker [here](https://artifacts.picoctf.net/c/11/level1.py) and you'll need the encrypted [flag](https://artifacts.picoctf.net/c/11/level1.flag.txt.enc) in the same directory too.
## Solucion
```
Length: 876 [application/octet-stream]
Saving to: 'level1.py'

level1.py              100%[==========================>]     876  --.-KB/s    in 0s      

2025-02-20 21:29:13 (71.4 MB/s) - 'level1.py' saved [876/876]

omarthearr21-picoctf@webshell:~$ ls
README.txt  codebook.txt  datos  fixme1.py  flag       runme.py
code.py     convertme.py  file   fixme2.py  level1.py
omarthearr21-picoctf@webshell:~$ python level1.py
Traceback (most recent call last):
  File "/home/omarthearr21-picoctf/level1.py", line 13, in <module>
    flag_enc = open('level1.flag.txt.enc', 'rb').read()
FileNotFoundError: [Errno 2] No such file or directory: 'level1.flag.txt.enc'
omarthearr21-picoctf@webshell:~$ vim level1.py

omarthearr21-picoctf@webshell:~$ vim level1.py
omarthearr21-picoctf@webshell:~$ python level1.py
Traceback (most recent call last):
  File "/home/omarthearr21-picoctf/level1.py", line 13, in <module>
    flag_enc = open('level1.flag.txt.enc', 'rb').read()
FileNotFoundError: [Errno 2] No such file or directory: 'level1.flag.txt.enc'
omarthearr21-picoctf@webshell:~$ wget https://artifacts.picoctf.net/c/11/level1.flag.txt.enc
--2025-02-20 21:31:34--  https://artifacts.picoctf.net/c/11/level1.flag.txt.enc
Resolving artifacts.picoctf.net (artifacts.picoctf.net)... 3.160.5.71, 3.160.5.93, 3.160.5.18, ...
Connecting to artifacts.picoctf.net (artifacts.picoctf.net)|3.160.5.71|:443... connected.
HTTP request sent, awaiting response... 200 OK
Length: 30 [application/octet-stream]
Saving to: 'level1.flag.txt.enc'

level1.flag.txt.enc    100%[==========================>]      30  --.-KB/s    in 0s      

2025-02-20 21:31:34 (2.51 MB/s) - 'level1.flag.txt.enc' saved [30/30]

omarthearr21-picoctf@webshell:~$ python level1.py
Please enter correct password for flag: https://artifacts.picoctf.net/c/11/level1.flag.txt^[[A^[[D
That password is incorrect
omarthearr21-picoctf@webshell:~$ vim level1.py
omarthearr21-picoctf@webshell:~$ python level1.py
Please enter correct password for flag: 1e1a
Welcome back... your flag, user:
picoCTF{545h_r1ng1ng_fa343060} 

```
`picoCTF{545h_r1ng1ng_fa343060}`