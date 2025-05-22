## Descripcion
A digital ghost has breached my defenses, and my sensitive data has been stolen! 😱💻 Your mission is to uncover how this phantom intruder infiltrated my system and retrieve the hidden flag.To solve this challenge, you'll need to analyze the provided PCAP file and track down the attack method. The attacker has cleverly concealed his moves in well timely manner. Dive into the network traffic, apply the right filters and show off your forensic prowess and unmask the digital intruder!Find the PCAP file here [Network Traffic PCAP file](https://challenge-files.picoctf.net/c_verbal_sleep/a681faccaaa199ce75c3abeef9525f813b6451644a8d8d27cc097e4b1ccb741a/myNetworkTraffic.pcap) and try to get the flag.


## Solucion
```
# Abrir el archivo PCAP con Wireshark
wireshark phantom_intruder.pcap

# Filtrar por protocolos como HTTP o DNS
# Buscar paquetes con datos sospechosos o cadenas codificadas
# Extraer y decodificar los datos para encontrar la bandera


```

## Flag
picoCTF{n3tw0rk_tr4ff1c_4n4lys1s}