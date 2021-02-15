# Rasberry-boot-with-python-and-web-camera

程序实现了树莓派开机时自动运行指定的 python 脚本，从而实现在局域网中访问树莓派摄像头，实时获取摄像头的画面。

为完成以上的功能，请将该库中的文件放到对应的文件夹中，并将代码中设置的路径进行相应的更改，使其与你电脑上的路径相一致。

`/home/pi/.config/autostart`文件夹中

* `pistreaming.desktop`
* `shutdown.desktop`

`/home/pi`文件夹中

* `shutdown.py`

- `pistream`文件夹（`pistream`的来源[Github链接](https://github.com/waveform80/pistreaming)）

`/home/pi/pistream`文件夹中

* `start.py`
