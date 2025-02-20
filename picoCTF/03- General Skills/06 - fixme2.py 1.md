Fix the syntax error in this Python script to print the flag.[Download Python script](https://artifacts.picoctf.net/c/26/fixme1.py)
## Solucion
```
omarthearr21-picoctf@webshell:~$ wget https://artifacts.picoctf.net/c/5/fixme2.py
--2025-02-20 21:25:17--  https://artifacts.picoctf.net/c/5/fixme2.py
Resolving artifacts.picoctf.net (artifacts.picoctf.net)... 3.160.5.42, 3.160.5.71, 3.160.5.18, ...
Connecting to artifacts.picoctf.net (artifacts.picoctf.net)|3.160.5.42|:443... connected.
HTTP request sent, awaiting response... 200 OK
Length: 1029 (1.0K) [application/octet-stream]
Saving to: 'fixme2.py'

fixme2.py              100%[==========================>]   1.00K  --.-KB/s    in 0s      

2025-02-20 21:25:17 (875 MB/s) - 'fixme2.py' saved [1029/1029]

omarthearr21-picoctf@webshell:~$ python fixme2.py
  File "/home/omarthearr21-picoctf/fixme2.py", line 22
    if flag = "":
       ^^^^^^^^^
SyntaxError: invalid syntax. Maybe you meant '==' or ':=' instead of '='?
omarthearr21-picoctf@webshell:~$ vim fixme2.py
omarthearr21-picoctf@webshell:~$ python fixme2.py
  File "/home/omarthearr21-picoctf/fixme2.py", line 22
    if flag = "":
       ^^^^^^^^^
SyntaxError: invalid syntax. Maybe you meant '==' or ':=' instead of '='?
omarthearr21-picoctf@webshell:~$ vim fixme2.py
omarthearr21-picoctf@webshell:~$ python fixme2.py
That is correct! Here is your flag: picoCTF{3qu4l1ty_n0t_4551gnm3nt_4863e11b}
omarthearr21-picoctf@webshell:~$ ^C
omarthearr21-picoctf@webshell:~$ 

```
`picoCTF{3qu4l1ty_n0t_4551gnm3nt_4863e11b}`