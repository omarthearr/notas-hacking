## Descripcion
Run the `runme.py` script to get the flag. Download the script with your browser or with `wget` in the webshell.[Download runme.py Python script](https://artifacts.picoctf.net/c/34/runme.py)
## Solucion
```
omarthearr21-picoctf@webshell:~$ wget https://artifacts.picoctf.net/c/34/runme.py
--2025-02-20 21:16:23--  https://artifacts.picoctf.net/c/34/runme.py
Resolving artifacts.picoctf.net (artifacts.picoctf.net)... 3.160.5.93, 3.160.5.18, 3.160.5.42, ...
Connecting to artifacts.picoctf.net (artifacts.picoctf.net)|3.160.5.93|:443... connected.
HTTP request sent, awaiting response... 200 OK
Length: 270 [application/octet-stream]
Saving to: 'runme.py'

runme.py               100%[==========================>]     270  --.-KB/s    in 0s      

2025-02-20 21:16:23 (18.8 MB/s) - 'runme.py' saved [270/270]

omarthearr21-picoctf@webshell:~$ ls
README.txt  code.py  codebook.txt  convertme.py  datos  file  flag  runme.py
omarthearr21-picoctf@webshell:~$ python runme.py
picoCTF{run_s4n1ty_run}

```
`picoCTF{run_s4n1ty_run}`