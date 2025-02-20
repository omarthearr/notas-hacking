Can you crack the password to get the flag?Download the password checker [here](https://artifacts.picoctf.net/c/11/level1.py) and you'll need the encrypted [flag](https://artifacts.picoctf.net/c/11/level1.flag.txt.enc) in the same directory too.
## Solucion
```
omarthearr21-picoctf@webshell:~$ wget https://artifacts.picoctf.net/c/14/level2.py
--2025-02-20 21:33:47--  https://artifacts.picoctf.net/c/14/level2.py
Resolving artifacts.picoctf.net (artifacts.picoctf.net)... 3.160.5.93, 3.160.5.18, 3.160.5.42, ...
Connecting to artifacts.picoctf.net (artifacts.picoctf.net)|3.160.5.93|:443... connected.
HTTP request sent, awaiting response... 200 OK
Length: 914 [application/octet-stream]
Saving to: 'level2.py'

level2.py              100%[==========================>]     914  --.-KB/s    in 0s      

2025-02-20 21:33:47 (282 MB/s) - 'level2.py' saved [914/914]

omarthearr21-picoctf@webshell:~$ wget https://artifacts.picoctf.net/c/14/level2.flag.txt.enc
--2025-02-20 21:34:08--  https://artifacts.picoctf.net/c/14/level2.flag.txt.enc
Resolving artifacts.picoctf.net (artifacts.picoctf.net)... 3.160.5.18, 3.160.5.71, 3.160.5.42, ...
Connecting to artifacts.picoctf.net (artifacts.picoctf.net)|3.160.5.18|:443... connected.
HTTP request sent, awaiting response... 200 OK
Length: 31 [application/octet-stream]
Saving to: 'level2.flag.txt.enc'

level2.flag.txt.enc    100%[==========================>]      31  --.-KB/s    in 0s      

2025-02-20 21:34:08 (13.1 MB/s) - 'level2.flag.txt.enc' saved [31/31]

omarthearr21-picoctf@webshell:~$ vim level2.py
omarthearr21-picoctf@webshell:~$ python level2.py
Please enter correct password for flag: 4ec9
Welcome back... your flag, user:
picoCTF{tr45h_51ng1ng_9701e681} 

```
`picoCTF{tr45h_51ng1ng_9701e681}`