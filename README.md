# gofile-downloader
Download files from https://gofile.io
# Clone this repository
```
git clone https://github.com/javsubs91/gofile-downloader.git
```

# Requirements
```
conda install python="3.10"
pip install -r ./gofile-downloader/requirements.txt
```
**NOTICED:** This script is only running on Python version 3.10
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



___




<br>

<h3>Visitors :</h3>
<br>
<img src="https://profile-counter.glitch.me/gofiledownloader/count.svg" alt="Visitors">

