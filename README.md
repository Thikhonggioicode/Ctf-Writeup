# |Ascis 2024|

 ```Reverse Engineering:```

 Challenge : *RE*

![alt text](image-1.png)

So this is a Challenge in Ascis 2024 CTF

![alt text](image-2.png)

I use ```file <file name>``` to check this ```filedanger```
and I know that it's a ELF 64-bit  

![alt text](image-3.png)

After using ```cat <filename>```, I can say it an UPX packer by look in the last line ```PX!UPX! fwww�7{��?t▒�?n� ```
![alt text](image-4.png)

All I need is unpack it and check it again with ```strings``` . 
![alt text](image-5.png)

I was right !
![alt text](image-6.png)