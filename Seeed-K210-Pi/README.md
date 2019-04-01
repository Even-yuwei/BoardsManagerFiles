# Seeed-K210-Pi
Arduino Core for Kendryte K210
Windows
1.首选项添加下列地址 然后打开开发版管理器下载开发包

    https://raw.githubusercontent.com/Even-yuwei/platform/master/Seeed-K210-Pi/package_seeed_k210_pi_index.json

2.安装好之后添加工具链目录到PATH环境变量

    C:\Users\(username)\AppData\Local\Arduino15\packages\Kenduino\tools\riscv64-unknown-elf-gcc\8.2.0\bin

3.安装.Net core runtime
4.开发板选择Seeed-K210-Pi 编程器选 k-flash
5.连接开发板选对应的串口号
6.编写程序 编译 上传 完成
Ubuntu
1.首选项添加下列地址 然后打开开发版管理器下载开发包

    https://raw.githubusercontent.com/Even-yuwei/platform/master/Seeed-K210-Pi/package_seeed_k210_pi_index.json

2.需要解决usb串口访问权限

    sudo usermode -a -G dialout (username)

3.安装pyserial

    pip3 install pyserial

4.开发板选择Seeed-K210-Pi 编程器选 k-flash
5.连接开发板选对应的串口号
6.编写程序 编译 上传 完成