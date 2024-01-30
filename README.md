POC-Ransomware - Fernet Key

This POC is run through Windows using powershell.

This is only POC. The use of bad action is not creator responsibility.


**Description**

RanSim is a ransomware simulation script written in PowerShell. It recurisively encrypts files in the target directory using 256-bit AES encryption. RanSim has no self-spreading capabilities and will only run on the system you execute it on.

You can use RanSim to test your defenses and backups against real ransomware-like activity in a controlled setting. The same script can be used to decrypt the files if needed.



**Usage**

**Encrypt**

```PowerShell
.\RanSim.ps1 -Mode encrypt
```

**Decrypt**

```PowerShell
.\RanSim.ps1 -Mode decrypt
```

**Optional Parameters and Defaults**

`-TargetPath` -> C:\RanSim

`-Extension` -> .encrypted

`-Key` -> Q5KyUru6wn82hlY9k8xUjJOPIC9da41jgRkpt21jo2L=

**Other Global Variables**

`TargetFiles` -> .pdf .xls* .ppt* .doc* .accd* .rtf .txt .csv .jpg .jpeg .png .gif .avi .midi .mov mp3 .mp4 .mpeg .mpeg2 .mpeg3 .mpg .ogg

