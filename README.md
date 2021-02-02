# HealthInfoAutoReport

## First, u need 2 bind u wx with u phone num

**Remind: First, u need post u tmp least 1 time.**

open wx, scan this:

![wx](https://cdn.jsdelivr.net/gh/zsqw123/cdn@master/picCDN/20210202105525.png)

bind:

**Notice: u wx binded num must same with u input below.**

**If u can't, ask u leader for help.**

![bind](https://cdn.jsdelivr.net/gh/zsqw123/cdn@master/picCDN/20210202105734.png)

if binded, u will see a new QR code, scan and follow it.

![newQR](https://cdn.jsdelivr.net/gh/zsqw123/cdn@master/picCDN/20210202110147.png)

then use ur leader's way to report once

## Second: Choose one of the following to run auto report

### 1. Through Remote Environment: Github Actions

1. star and fork this repo.
2. set your own those 2 Actions secrets: NUM, PWD
3. commit anything or wait actions auto run.

### 2. Through Local Environment: Python 3.6+

```powershell
pip install requests
pip install beautifulsoup4
pip install lxml
```

Run this:

```powershell
python actions.py account pwd
```
