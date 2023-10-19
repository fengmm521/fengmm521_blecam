# fengmm521_blecam
 
更新代码后,插上摄像头和本店的可骗程蓝牙鼠标键盘控制器,之后安装相关python库

``` bash
pip install -r requirements.txt
```
安装库有:

    opencv-python (>=4.7.0)
    pyserial
    esptool
    adafruit-ampy

上边的opencv-python,pyserial两个库是必须安装的,一个是用来处理摄像头和显示图像的,一个是用来和蓝牙鼠标键盘控制器通讯的

都弄好之后,在命令行或者终端里输入:
``` Python
python main.py
```
就可以运行项目了