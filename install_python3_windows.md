Installing Python 3 on Windows.

Step 1. Download the latest version of Python 3.6 from the official website.
```
https://www.python.org/downloads/
```

Step 2. Add the directory C:\Python36\ for your default Python version to the PATH. 

PATH:
```
C:\Python36\;C:\Python36\Scripts\
```
You can do this easily by running the following in powershell:
```
[Environment]::SetEnvironmentVariable("Path", "$env:Path;C:\Python36\;C:\Python36\Scripts\", "User")
```
