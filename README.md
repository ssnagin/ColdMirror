
![GitHub followers](https://img.shields.io/github/followers/ssnagin?label=Subscribe&style=for-the-badge) ![GitHub all releases](https://img.shields.io/github/downloads/ssnagin/ColdMirror/total?style=for-the-badge)

[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)

# ColdMirror

ColdMirror is a simple open-source application that uploads files to different cloud storage.
It will be developed as the final project of Samsung IT School Ivanovo.

## Small description

Here is a small description, as it is required. At the beginning user would see an intro tab, where explains what to do (accounts connection, password etc.). Then the main window shows. It contains only two big buttons at the center and menu bar at left top corner. First button -- upload file, second -- download file. Menu bar: file explorer, preferences (settings) and about.


Application will have such functions as:

- Uploading files to cloud storage. It can be everything: photos and videos, documents etc. I still don't know which services will be used, but Telegram Bookmarks, Google Drive and its Russian replacement Yandex Drive are in priority.
- File encryption. How to prevent data leakage? Set a strong password. All files will be archived with LZMA2 algorythm and in safe untill the password is stolen. (LZMA2 gives a good files compression). According to this, it's possible to keep them **everywhere** 
- Loading existing data from storage.

Settings section:
- Accounts
- Synchronizing files with clouds just in time or while using this app only
- File size limits. Uploading and downloading with wi-fi only, package size etc.
- Password: set, generate (16, 32, 64 and 128 digits).
- Filename. Set it from name of file or generate unique sha1 key. Datetime

Some probles that may appear during the usage:

- Memory limits. Google Drive - 15 GB, Yandex Disk - 10 GB and Telegram - no limits. Could be easily fixed by changing account.

## Requirements

Android 7.0 or higher (API level 24)
## Contributing

Feel free to contribute!

If you have any questions or you want to propose new features, open an issue or write me - s_lstoo@bk.ru

## Authors

- [@ssnagin](https://www.github.com/ssnagin)