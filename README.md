# matebook-13-2019-oc-efi

正常可用的部件：
1.蓝牙（无需热启动）From IntelBluetoothFirmware @zxystd
2.wifi （需要用propertree注入你自己的ssid跟password）可以做到无违和感使用 From itlwm @zxystd
3.睡眠正常
4.hdmi正常（可音频输出）
5.触摸板正常
6.解锁cfg lock后可完美原生电源管理
7.已注入缓冲帧 核显正常
8.cpu变频正常
9. usb已定制
10.键盘快捷键正常

无法正常工作的部件：
1.摄像头（这个看命，有的人能用）
2.耳机接口（只是需要使用修复进程，这个进程无法集成进efi）
3.mx250独显（这个是废话）

oc版本0.5.8
自用macos版本：10.15.5

安装方法：

先于此blog下载：10.15.5 19F101 双EFI分区版
这个文章很长，使劲往下翻，或使用网页搜索功能
下载链接
：https://blog.daliansky.net/macOS-Catalina-10.15.5-19F96-Release-version-with-Clover-5118-original-image-Double-EFI-Version-UEFI-and-MBR.html

安装视频教程：
https://www.bilibili.com/video/BV1jJ41127YT/?spm_id_from=333.788.videocard.0

安装注意点：
1.安装使用的镜像推荐使用我给的链接下载的那个，不要用他给的，以内有点旧了
2. 视频的【14:37】开始他开始吧u盘的clover efi复制进ESR（EFI）分区，这一步复制我的efi进去
3. 视频的【16:44】开始是使用easyuefi创建efi引导，这一步前面都跟他视频一样，他怎么点你就怎么点，只不过，选择引导文件为：EFI/BOOT/BOOTx64.efi


最近在努力解决摄像头问题，要是想打赏小的，请选择一个你喜欢的方式，谢谢！
https://github.com/ske1996/matebook-13-2019-oc-efi/blob/master/%E5%BE%AE%E4%BF%A1.jpg?raw=true
https://github.com/ske1996/matebook-13-2019-oc-efi/blob/master/%E6%94%AF%E4%BB%98%E5%AE%9D.jpg?raw=true


