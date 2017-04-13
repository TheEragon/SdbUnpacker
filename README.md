# SdbUnpacker
SdbUnpacker is a small script that converts the new Shim database (SDB) format, that is used in _Windows 10 15063_, to old format so you can use tools like _sdb2xml.exe_ again.

### Requirements
- [Visual Studio 2017 RC3 (or newer)](https://www.visualstudio.com/vs/visual-studio-2017-rc/)
- [Microsoft Windows 10 15021 (or newer) SDK](https://www.microsoft.com/en-us/software-download/windowsinsiderpreviewSDK)

### Instructions
1) python SdbUnpacker.py –i appraiser.sdb –o appraiser_decompressed.sdb
2) Use tool like _sdb2xml.exe_ to convert sdb to xml

License
----
MIT
