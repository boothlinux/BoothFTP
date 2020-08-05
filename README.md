# About:
BoothFTP is a FTP/SFTP client written in Python 3 using the tkinter GUI toolkit. BoothFTP can upload, download, create, rename, copy, move and search files/and folders.
#### Currently supported platforms:
+ Linux
+ Windows XP/7/10
+ MacOS / OS X (Should work from 10.4 Tiger to 10.15 Catalina)

# Use BoothFTP:

#### Linux:
+  Clone the source, cd to the BoothFTP-master folder. In a new virtual environment type: `python -m pip install -r requirements.txt` once the dependencies
downloaded then simply type: `python BoothFTP.py`

#### MacOS:
+  Clone the source, cd to the BoothFTP-master folder. In a new virtual environment type: `python -m pip install -r requirements_mac.txt` once the dependencies are downloaded then simply type: `python BoothFTP.py`

#### Windows:
+  Clone the source. Using cmd change to the BoothFTP-master directory. If building on Windows XP, change  `psutil` to `psutil==3.4.2` and `pypiwin32` to `pypiwin32==2.1.9` in requirements.txt. In a new virtual environment type: `python -m pip install -r requirements_windows.txt` once the dependencies are downloaded then run the `BoothFTP.py` file with Python.

# Screenshots:
![Alt text](https://raw.github.com/boothlinux/BoothFTP/master/Screenshots/screenshot0.png "Screenshot 0")
![Alt text](https://raw.github.com/boothlinux/BoothFTP/master/Screenshots/screenshot1.png "Screenshot 1")
# License:
+ MIT License. Do as you will.

# Todo list:
+ Save connection info for frequently used ftp sites
+ Inline code editor OR open external editor and when save is uploaded back to the open FTP site

# Bugs:
+ Application looks blurry when DPI scaling is enabled.
+ Search on the root directory does not work.
