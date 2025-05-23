<h3 align="center"><img src="https://avatars.githubusercontent.com/u/197888720?s=1000" alt="logo" width="20%"></h3>

<p align="center">
    <br>Shebang is an Artix GNU/Linux based distribution offering a great blend of end user and power user experience.
    <br>Using the nimble Openbox window manager, it is highly customisable and provides a modern, full-featured GNU/Linux system without sacrificing performance.
    <p align="center"><a href="https://github.com/sponsors/DAFT-8"><img src="https://img.shields.io/static/v1?label=Sponsor&message=%E2%9D%A4&logo=GitHub&color=000000"></a><p>
</p>

### Setup Wi-Fi

Ethernet is setup automatically and Wi-Fi is setup with something like:
```
sudo vim /etc/wpa_supplicant/wpa_supplicant.conf
sudo sv restart wpa_supplicant
```

### Setup Shebang on Artix

Run the script as root:
```
bash <(curl -s https://raw.githubusercontent.com/shebang-linux/setup-shebang/main/setup.sh)
```
