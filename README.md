# sxstatus 💬
sxstatus <i>(shell xs status)</i> is a very simple status bar for dynamic window manager

![sxstatus](https://github.com/diws1/sxstatus/blob/main/screenshots/sxstatus.png)

## Installation ⚡
clone this repository on your ~/.config directory
```
cd ~/.config
git clone https://github.com/diws1/sxstatus
```
then go to sxstatus directory:
```
cd sxstatus/
```
run this command to start the installation:
```
make
sudo make install
```
Put sxstatus on your startup file, for example in .xsessionrc:
```
#!/bin/bash
....
# status bar
sxstatus &
```

