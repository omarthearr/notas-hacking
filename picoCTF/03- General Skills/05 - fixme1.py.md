Fix the syntax error in this Python script to print the flag.[Download Python script](https://artifacts.picoctf.net/c/26/fixme1.py)
## Solucion
```
omarthearr21-picoctf@webshell:~$ wget https://artifacts.picoctf.net/c/26/fixme1.py
--2025-02-20 21:17:37--  https://artifacts.picoctf.net/c/26/fixme1.py
Resolving artifacts.picoctf.net (artifacts.picoctf.net)... 3.160.5.93, 3.160.5.71, 3.160.5.18, ...
Connecting to artifacts.picoctf.net (artifacts.picoctf.net)|3.160.5.93|:443... connected.
HTTP request sent, awaiting response... 200 OK
Length: 837 [application/octet-stream]
Saving to: 'fixme1.py'

fixme1.py              100%[==========================>]     837  --.-KB/s    in 0s      

2025-02-20 21:17:38 (35.6 MB/s) - 'fixme1.py' saved [837/837]

omarthearr21-picoctf@webshell:~$ python fixme1.py
  File "/home/omarthearr21-picoctf/fixme1.py", line 20
    print('That is correct! Here\'s your flag: ' + flag)
IndentationError: unexpected indent
omarthearr21-picoctf@webshell:~$ vim fixme1.py
omarthearr21-picoctf@webshell:~$ python fixme1.py
That is correct! Here is your flag: picoCTF{1nd3nt1ty_cr1515_09ee727a}


```
`picoCTF{1nd3nt1ty_cr1515_09ee727a}`