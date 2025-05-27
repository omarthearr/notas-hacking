## Descripcion
The Network Operations Center (NOC) of your local institution picked up a suspicious file, they're getting conflicting information on what type of file it is. They've brought you in as an external expert to examine the file. Can you extract all the information from this strange file?Download the suspicious file [here](https://artifacts.picoctf.net/c_titan/8/flag2of2-final.pdf).

## Solucion
```
┌──(kali㉿kali)-[~/picoctf/forensic]  
└─$ mkdir Polyglot  
  
┌──(kali㉿kali)-[~/picoctf/forensic]  
└─$ cd Polyglot  
  
┌──(kali㉿kali)-[~/picoctf/forensic/Polyglot]  
└─$ open flag2of2-final.pdf  
  
┌──(kali㉿kali)-[~/picoctf/forensic/Polyglot]  
└─$ convert flag2of2-final.pdf flag2of2-final.png  
  
┌──(kali㉿kali)-[~/picoctf/forensic/Polyglot]  
└─$ open flag2of2-final.png  
  
┌──(kali㉿kali)-[~/picoctf/forensic/Polyglot]  
└─$

```

## Flag
picoCTF{F1u3n7_1n_pn9_&_pdf_249d05c0}