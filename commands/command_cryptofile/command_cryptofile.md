Crypto File command plugin
---

Config example:
````
"@voicenter/voicenter_pastash_command_cryptofile": {
    "pluginFieldName": "FileEcryptor",
    "inputFileField": "sourceFilePath",
    "outputFileField": "destFilePath",
    "keyField": "key",
    "algorithm": "aes256"
}
````

Request example:
````
"FileEcryptor": {
    "sourceFilePath": "/tmp/file.mp3",
    "destFilePath": "/tmp/file.dat",
    "key": "encryption key"
}
````

Commands list:
````
encryptFile();
decryptFile();
````