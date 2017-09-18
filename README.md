# PowerShell-Encryptor
Encrypt/Decrypt Directories or Files using PowerShell, AES-256 encryption

# Description
This project was created in PowerShell Studio 2017. It will encrypt files, directories (recursivly) and also decrypt file and directories

The encryption used is AES-256 and the module for the encryption/decryption process was created by Tyler Siegrist
https://gallery.technet.microsoft.com/EncryptDecrypt-files-use-65e7ae5d

Uses C# to specify the file/directory you want to encrypt/decrypt so you will get the normal open file/folder dialog box
After encrypting one file you can specify other files to encrypt, by default it will use the same AES-256 key as the previous file as long as your keep the AES-256 key present in the key textbox. Once you clear the key textbox it will generate a new AES-256 key.

![alt tag](https://github.com/bwya77/PowerShell-Encryptor/blob/master/_About/main_UI.png)

![alt tag](https://github.com/bwya77/PowerShell-Encryptor/blob/master/_About/encryptfile-1.png)

![alt tag](https://github.com/bwya77/PowerShell-Encryptor/blob/master/_About/opendiag1.png)
