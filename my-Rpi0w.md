For fixing screen flashing of my display, I uncommented these lines in `config.txt` of `/boot` partition:

```
hdmi_group=1
hdmi_mode=1
config_hdmi_boost=4
```
After that for installing touch drivers:
```
git clone https://github.com/meafs/LCD-show
chmod -R 755 LCD-show
cd LCD-show/
sudo ./MPI4008-show
```

My display: http://www.lcdwiki.com/4inch_HDMI_Display-C
