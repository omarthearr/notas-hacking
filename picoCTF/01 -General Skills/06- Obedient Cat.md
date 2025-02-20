
### Descripción

Can you find the flag in [file](https://jupiter.challenges.picoctf.org/static/315d3325dc668ab7f1af9194f2de7e7a/file)? This would be really tedious to look through manually, something tells me there is a better way.

### Solución 

```
omarthearr21-picoctf@webshell:~$ wget https://mercury.picoctf.net/static/fb851c1858cc762bd4eed569013d7f00/flag
--2025-02-13 18:35:17--  https://mercury.picoctf.net/static/fb851c1858cc762bd4eed569013d7f00/flag
Resolving mercury.picoctf.net (mercury.picoctf.net)... 18.189.209.142
Connecting to mercury.picoctf.net (mercury.picoctf.net)|18.189.209.142|:443... connected.
HTTP request sent, awaiting response... 200 OK
Length: 34 [application/octet-stream]
Saving to: 'flag'

flag                       100%[=======================================>]      34  --.-KB/s    in 0s      

2025-02-13 18:35:17 (18.6 MB/s) - 'flag' saved [34/34]

omarthearr21-picoctf@webshell:~$ cat flag
picoCTF{s4n1ty_v3r1f13d_28e8376d}
>>> 
```


picoCTF{s4n1ty_v3r1f13d_28e8376d}

