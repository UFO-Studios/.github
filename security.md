# UFO Studios security practices

## EXE & ZIP signing

We are in the process of signing all EXEs and ZIPs with GPG. This will let you verify that the file has not been changed. 

To verify the signature, download the file, and the signature (.sig) file. Make sure you have GPG installed too.
Use the following command. `gpg --verify signature_file.sig file.exe`. Replace the file names with the ones you want!
This will verify that it is us that has made the file, and that it hasn't been tampered with.

## EXE safety

We will do our upmost to make our apps safe. You can verify the safety of them with VirusTotal(.com).
A warning for AutoIt based projects: Windows does not like autoit (see [here](https://www.autoitscript.com/wiki/AutoIt_and_Malware))


## Reporting an issue

Please email UFOStudios@TheAlienDoctor.com with any security concerns 
