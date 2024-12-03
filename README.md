# ⚙️&nbsp;Not-pixel-auto-watch-ads
<img align="center" alt="line" src="https://github.com/DalpatRathore/dalpatrathore/blob/main/assets/images/line-2.svg">

Notpixel Telegram mini app bot auto watch ads using only query ids


### ⚙️&nbsp;Setup Termux
<img align="center" alt="line" src="https://github.com/DalpatRathore/dalpatrathore/blob/main/assets/images/line-2.svg">

```
pkg update && pkg upgrade
```
```
pkg rem python -y
```
```
pkg i tur-repo -y
```
```
pkg i python3.10 -y
```
```
ln -sf /data/data/com.termux/files/usr/bin/python3.10 /data/data/com.termux/files/usr/bin/python3
```
```
python3 --version
```

☣️if it showing python3.10.xx (e.g python 3.10.14) all done.


### ⚙️&nbsp; Instaction

```
pkg install git
```
```
pkg install nano
```
```
git clone https://github.com/rahatmals1/notpixel_auto_watch_ads.git
```
```
cd notpixel_auto_watch_ads
```

☣️Copy


```
pip3.10 install -r requirements.txt
```
```
nano query_ids.txt
```

✨ If you want to add proxy then use this command


```
nano proxies.txt
```
```
pkg install patchelf
```
```
patchelf --add-needed libpython3.10.so.1.0 pyarmor_runtime_004817/android_aarch64/pyarmor_runtime.so
```
```
python3.10 main.py
```

💥 Full Tutorial In YouTube Channel : <a href="https://youtu.be/wFqosKUHbRc?si=twu9eYVE0LjO03d1">Click Here</a>
