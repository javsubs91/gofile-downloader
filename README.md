# gofile-downloader
Download files from https://gofile.io

# Clone this repository
```
git clone https://github.com/javsubs91/gofile-downloader.git
```
___
# Requirements
```
conda install python="3.10"
pip install -r ./gofile-downloader/requirements.txt
```
**NOTICED:** This script is only running on Python version 3.10

Or

## Simply Install:
```
%%bash
sudo wget -c https://repo.anaconda.com/miniconda/Miniconda3-py310_23.1.0-1-Linux-x86_64.sh
sudo chmod +x ./Miniconda3-py310_23.1.0-1-Linux-x86_64.sh
sudo bash ./Miniconda3-py310_23.1.0-1-Linux-x86_64.sh  -b -f -p /usr/local
git clone https://github.com/ltsdw/gofile-downloader.git
pip install -r ./gofile-downloader/requirements.txt
```
## Check the Version
```
python -V
```
## Start Download
```
python ./gofile-downloader/gofile-downloader.py https://gofile.io/d/contentid
```
## Parallel Downloads
```
%%bash
python ./gofile-downloader/gofile-downloader.py https://gofile.io/d/fileid1 &
python ./gofile-downloader/gofile-downloader.py https://gofile.io/d/fileid2 &
python ./gofile-downloader/gofile-downloader.py https://gofile.io/d/fileid3 &
python ./gofile-downloader/gofile-downloader.py https://gofile.io/d/fileid4 &
```

___
# Usage
```
python ./gofile-downloader/gofile-downloader.py https://gofile.io/d/contentid
```

If it has password:
```
python ./gofile-downloader/gofile-downloader.py https://gofile.io/d/contentid password
```

Use the environment variable **`GF_DOWNLOADDIR`** to specify where to download to (the
path must exist already):
```
GF_DOWNLOADDIR="/path/to/the/directory" python gofile-downloader.py https://gofile.io/d/contentid

```
<p align="center">
<img src="https://github.com/javsubs91/gofile-downloader/blob/main/NOOOO.jpg?raw=true" height="500" align="center"/>
</p>

___

<br>

<h3>Visitors :</h3>
<br>
<img src="https://profile-counter.glitch.me/gofiledownloader/count.svg" alt="Visitors">

