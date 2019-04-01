# Arduino Core for Kendryte K210
## Windows
### 1.首选项添加下列地址 然后打开开发版管理器下载开发包
>https://raw.githubusercontent.com/Even-yuwei/platform/master/Seeed-K210-Pi/package_seeed_k210_pi_index.json
### 2.安装好之后添加工具链目录到PATH环境变量
>C:\Users\\**(username)**\AppData\Local\Arduino15\packages\Kenduino\tools\riscv64-unknown-elf-gcc\8.2.0\bin
### 3.安装[.Net core runtime](https://download.visualstudio.microsoft.com/download/pr/3f05ee2d-5372-43d6-9562-be86632a53d4/1361281426efa7ff206289adb0411f55/dotnet-runtime-3.0.0-preview3-27503-5-win-x64.exe)
### 4.开发板选择Sipeed M1 Board 编程器选 k-flash
### 5.连接开发板选对应的串口号
### 6.编写程序 编译 上传 完成
----
## Ubuntu
### 1.首选项添加下列地址 然后打开开发版管理器下载开发包
>https://raw.githubusercontent.com/Even-yuwei/platform/master/Seeed-K210-Pi/package_seeed_k210_pi_index.json
### 2.需要解决usb串口访问权限
>sudo usermode -a -G dialout **(username)**
### 3.安装pyserial
>pip3 install pyserial
### 4.开发板选择Sipeed M1 Board 编程器选 k-flash
### 5.连接开发板选对应的串口号
### 6.编写程序 编译 上传 完成
----
## Windows
### 1.Add the following address to the **Preferences** and open the **Boards Manager** to download the development kit.
>https://raw.githubusercontent.com/Even-yuwei/platform/master/Seeed-K210-Pi/package_seeed_k210_pi_index.json
### 2.Add the toolchain directory to the PATH environment variable after installation.
>C:\Users\\**(username)**\AppData\Local\Arduino15\packages\Kenduino\tools\riscv64-unknown-elf-gcc\8.2.0\bin
### 3.Install [.Net core runtime](https://download.visualstudio.microsoft.com/download/pr/3f05ee2d-5372-43d6-9562-be86632a53d4/1361281426efa7ff206289adb0411f55/dotnet-runtime-3.0.0-preview3-27503-5-win-x64.exe)
### 4.Board selects Sipeed M1 Board & Programmer to choose k-flash.
### 5.Connect the development board and then choose the serial port.
### 6.Now you can write the Arduino code and upload it to the k210 board.
----
## Ubuntu
### 1.Add the following address to the **Preferences** and open the **Boards Manager** to download the development kit.
>https://raw.githubusercontent.com/Even-yuwei/platform/master/Seeed-K210-Pi/package_seeed_k210_pi_index.json
### 2.Enter the following command in the terminal to solve the problem of usb serial port access rights.
>sudo usermode -a -G dialout **(username)**
### 3.Install pyserial
>pip3 install pyserial
### 4.Board selects Sipeed M1 Board & Programmer to choose k-flash.
### 5.Connect the development board and then choose the serial port.
### 6.Now you can write the Arduino code and upload it to the k210 board.
----