# Pentester

- Inicial
    
    [Enum Ports](Pentester%207be37013ca104d8e8f153e9353ad8017/Enum%20Ports%20efcf68960ef349d39abc8f4c1d4ca143.md)
    
    [Scaning](Pentester%207be37013ca104d8e8f153e9353ad8017/Scaning%2077d13b7fceda4121afc7d2ef7522c405.md)
    
- Services
    
    [FTP](Pentester%207be37013ca104d8e8f153e9353ad8017/FTP%201a8b8ae8f80f4bbead5dfd6e3c8a7897.md)
    
    [SSH](Pentester%207be37013ca104d8e8f153e9353ad8017/SSH%20b40d84199e164e4a963e756f37863b7b.md)
    
    [HTTP ](Pentester%207be37013ca104d8e8f153e9353ad8017/HTTP%204645d23f7f8d4ee4966b0de67574e568.md)
    
    [Web](Pentester%207be37013ca104d8e8f153e9353ad8017/Web%20ecc715b72427446285f5870cda3e13a2.md)
    
    [SMTP](Pentester%207be37013ca104d8e8f153e9353ad8017/SMTP%20fa73565d33d74801bedaf2a9a90f4ca4.md)
    
    [SNMP](Pentester%207be37013ca104d8e8f153e9353ad8017/SNMP%209c05bf7a34d34fa59bdc3cbbc73ace2a.md)
    
    [MSSQL](Pentester%207be37013ca104d8e8f153e9353ad8017/MSSQL%20fc0d1465f7244f1f990b3de2f86df3f8.md)
    
    [MYSQL](Pentester%207be37013ca104d8e8f153e9353ad8017/MYSQL%20a5f8b284938642aa9cb182941b64f5a4.md)
    
    [LDAP](Pentester%207be37013ca104d8e8f153e9353ad8017/LDAP%205cd1610eef3b48dcb125faa5d5042a62.md)
    
    [MDB-SQL](Pentester%207be37013ca104d8e8f153e9353ad8017/MDB-SQL%20ec8c554024f042ef84148c45091ff0dd.md)
    
    [PSQL](Pentester%207be37013ca104d8e8f153e9353ad8017/PSQL%20a24f569d7cfb4e9890667a268003c29f.md)
    
- Search in linux
    
    [Expressões Uteis](Pentester%207be37013ca104d8e8f153e9353ad8017/Expresso%CC%83es%20Uteis%209a3f19cad6134711b8dc056747cbc702.md)
    

- Sistemas Operativos
    
    [Linux](Pentester%207be37013ca104d8e8f153e9353ad8017/Linux%20302a6aab6ff64e678e2be2635914552b.md)
    
    [Windows](Pentester%207be37013ca104d8e8f153e9353ad8017/Windows%207ea63eadbdee47c186c76fd19f590de6.md)
    
- Shell
    
    [Melhorar Shell](Pentester%207be37013ca104d8e8f153e9353ad8017/Melhorar%20Shell%20b68cecdbb91c4d50b79d83047f9e413a.md)
    
    [Reverse Shell](Pentester%207be37013ca104d8e8f153e9353ad8017/Reverse%20Shell%20d8d44075debc465ebddfca459e22bc99.md)
    
- Other
    
    [Mandar Ficheiros Windows](Pentester%207be37013ca104d8e8f153e9353ad8017/Mandar%20Ficheiros%20Windows%20a748adb8b4f54bc6a858916b1f973b45.md)
    
    [WI-FI](Pentester%207be37013ca104d8e8f153e9353ad8017/WI-FI%20cac3a2d71cb3483aa920ff98b931025e.md)
    
    [Git Repository](Pentester%207be37013ca104d8e8f153e9353ad8017/Git%20Repository%207ef55949920c41cabc8f667297bb517e.md)
    
    [DNS Loockup](Pentester%207be37013ca104d8e8f153e9353ad8017/DNS%20Loockup%20a254f70e663f4e899e4ede65ff4685ac.md)
    
- Enum Total
    
    [Enum](Pentester%207be37013ca104d8e8f153e9353ad8017/Enum%207e3205f5297c4b72878c984eae10db02.md)
    

[BufferOverflow](Pentester%207be37013ca104d8e8f153e9353ad8017/BufferOverflow%200578e394affe4fa68167fef75c6840c9.md)

[Creat Passwords](Pentester%207be37013ca104d8e8f153e9353ad8017/Creat%20Passwords%20afe3da82be344ddfbc18e66d3ac59fb5.md)

[Chisel- PortFoward](Pentester%207be37013ca104d8e8f153e9353ad8017/Chisel-%20PortFoward%2083d44ecde9da489585c3b0907eb112df.md)

Criar ficheiro com os bytes diferente `php → jpg`

```
└──╼ [★]$ head -c 20 /var/lib/inetsim/http/fakefiles/sample.jpg > teste
┌─[eu-dedivip-2]─[10.10.14.89]─[paulinho13@htb-nn8fi0k9bi]─[~]
└──╼ [★]$ mv teste jpg-magicbytes
┌─[eu-dedivip-2]─[10.10.14.89]─[paulinho13@htb-nn8fi0k9bi]─[~]
└──╼ [★]$ cat jpg-magicbytes jpg-magicbytes > magic-shell.php
┌─[eu-dedivip-2]─[10.10.14.89]─[paulinho13@htb-nn8fi0k9bi]─[~]
└──╼ [★]$ file magic-shell.php 
magic-shell.php: JPEG image data, JFIF standard 1.01, resolution (DPI), density 72x72, segment length 16
┌─[eu-dedivip-2]─[10.10.14.89]─[paulinho13@htb-nn8fi0k9bi]─[~]
```

![Untitled](Pentester%207be37013ca104d8e8f153e9353ad8017/Untitled.png)