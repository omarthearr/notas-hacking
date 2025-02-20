Find the flag in the Python script![Download Python script](https://artifacts.picoctf.net/c/36/serpentine.py)
## Solucion
```
omarthearr21-picoctf@webshell:~$ ls
README.txt    datos      flag                 level2.py            runme.py
code.py       file       level1.flag.txt.enc  level3.flag.txt.enc  serpentine.py
codebook.txt  fixme1.py  level1.py            level3.hash.bin
convertme.py  fixme2.py  level2.flag.txt.enc  level3.py
omarthearr21-picoctf@webshell:~$ 
omarthearr21-picoctf@webshell:~$ vim serpentine.py
omarthearr21-picoctf@webshell:~$ python serpentine.py

    Y
  .-^-.
 /     \      .- ~ ~ -.
()     ()    /   _ _   `.                     _ _ _
 \_   _/    /  /     \   \                . ~  _ _  ~ .
   | |     /  /       \   \             .' .~       ~-. `.
   | |    /  /         )   )           /  /             `.`.
   \ \_ _/  /         /   /           /  /                `'
    \_ _ _.'         /   /           (  (
                    /   /             \  \
                   /   /               \  \
                  /   /                 )  )
                 (   (                 /  /
                  `.  `.             .'  /
                    `.   ~ - - - - ~   .'
                       ~ . _ _ _ _ . ~

Welcome to the serpentine encourager!


a) Print encouragement
b) Print flag
c) Quit

What would you like to do? (a/b/c) b
picoCTF{7h3_r04d_l355_7r4v3l3d_aa2340b2}
a) Print encouragement
b) Print flag
c) Quit 

```
`picoCTF{7h3_r04d_l355_7r4v3l3d_aa2340b2}`