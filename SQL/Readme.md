## Installation of SQLite

To get started, type the following command to check if you already have SQLite installed.

```bash
$sqlite3
```

And you should see:

```
SQLite version 3.7.15.2 2014-08-15 11:53:05
Enter ".help" for instructions
Enter SQL statements terminated with a ";"
sqlite>
```

If you do not see above result, then it means you do not have SQLite installed on your machine. Go to [SQLite Download page](http://www.sqlite.org/download.html) and download the precompiled binaries for your machine.

### For Windows

You will need to download `sqlite-shell-win32-*.zip` and `sqlite-dll-win32-*.zip` zipped files.

Create a folder `C:\>sqlite` and unzip the files in this folder which will give you `sqlite3.def`, `sqlite3.dll` and `sqlite3.exe` files.

Add `C:\>sqlite` to your [PATH environment variable](http://dustindavis.me/update-windows-path-without-rebooting/) and finally go to the command prompt and issue `sqlite3` command.

### For Mac

First, try to install via Homebrew:

```
brew install sqlite3
```

If not, download the package from above. After downloading the files, follow these steps:

```
$tar -xvzf sqlite-autoconf-3071502.tar.gz
$cd sqlite-autoconf-3071502
$./configure --prefix=/usr/local
$make
$make install
```

## Install SQLite Management Tool

OSX or Windows: SQLite DB Browser
-----------------------------

Install [DB Browser for SQLite](http://sqlitebrowser.org/), which is a free tool to explore a SQLite database and execute queries on the data.
