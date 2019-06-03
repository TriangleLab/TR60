### 前言 Introduction

首先，非常感谢大家对 TR60 的信任与支持，大家的购买是对我们极大鼓励。同时我也要对此次团购这么长时间的延误再次表达我的歉意。也请大家相信，我们会倾尽所能继续完善产品，尽量给大家带来满意的使用体验。

Firstly, thanks for your support and trust. Your purchases were a great encouragement to us. We are sorry for the long delay during this group buy. Please have faith in us that we will keep improving our products and bring you better user experience in the future.

### 物品清单 Item list

一套典型的 TR60 蓝牙双模套件包含以下内容：

A regular TR60 Bluetooth/USB dual mode keyboard kit includes the following items: 

| **编号**  **No.**   | **物品名称**  **Item Names**   | **数量**  **Quantity**   | **备注**  **Note**   | 
|:----|:----|:----|:----|
| 01   | Bluetooth PCB   | 1   | BLE 4.0   | 
| 02   | 金属外壳（上盖+底壳）  Aluminum chassis (top+bottom)   | 1   |    | 
| 03   | 上下盖螺丝 中长度  Chassis screws - long - 4+3(replacements)   | 4+3   |    | 
| 04   | 上下盖加强 长长度拧2颗+备2颗  Chassis screws - extra long - 2+2(replacements)   | 2+2   |    | 
| 05   | PCB螺丝 短长度拧5颗+备6颗  PCB screws - short - 5+6(replacements)   | 5+6   |    | 
| 06   | 侧板螺丝 短长度金拧2颗  Side plate screws - short - 2   | 2   |    | 
| 07   | 2Pin 锂电池接口座子  2 pin lithium battery housing   | 1   | 改装锂电用的配件  For the lithium battery mod   | 
| 08   | FPC 4Pin 软排线  4 pin flexible flat cable   | 1   | 中央出线用的配件  For the center USB connector mod   | 
| 09   | 二极管——0603尺寸  diodes - 0603 size   | 4   | 备用组件  Replacement parts   | 
| 10   | 910欧姆电阻——0603尺寸  910Ω resistors - 0603 size   | 2   | 改装锂电用的配件  For the lithium battery mod   | 
| 11   | 0.3欧姆电阻——1206尺寸  0.3Ω resistors - 1206 size   | 2   | 改装锂电用的配件  For the lithium battery mod   | 
| 12   | 0欧姆电阻——0402尺寸  0Ω resistors - 0402 size   | 4   | 改装锂电用的配件  For the lithium battery mod   | 
| 13   | 跳线针座  Holtite sockets   | 4   | 刷机跳线备用组件  Work as jumpers for flashing firmware   | 
| 14   | 亚克力磨砂侧板  Matte acrylic side plates   | 2   |    | 
| 15   | 试轴器 轴+试轴器+挂绳  Switch tester, switch, lanyard   | 1   | 赠品  Gifts   | 
| 16   | 螺丝刀 十字两把+内六角  Phillips screwdrivers *2 + hex key   | 3   | 螺丝刀  Screwdrivers   | 
| 17   | 塑料拔键器  Keycap puller   | 1   |    | 
| 18   | Type-C OTG   | 1   | Dongle刷机用(选配)  For flashing firmware on the dongle (optional)   | 
| 19   | 蓝色USB板子  USB daughterboard (blue)   | 1   | 中央出线用的配件  For the center USB connector mod   | 
| 20   | Dongle   | 1   | TR60-BLE官方接收器(选配)  TR60-BLE official receiver (optional)   | 

## 配件照片概览 Preview of items

### 主PCB Main PCB

![图片](https://github.com/TriangleLab/TR60/raw/master/IMG/1.jpg)
![图片](https://github.com/TriangleLab/TR60/raw/master/IMG/2.jpg)

* ① USB Type-C接口
* ② 刷机用跳线开关A，分为 N 开关和 S 开关
* ③ 刷机用跳线开关B——搭配针座（前文表格中的13号配件)使用
* ④ 中央出线用USB接口的FPC座子
* ⑤ 锂电池充电管理芯片（备选项，改造用) 
* ⑥ 官方USB接收器刷机用USB Type-C 接口


* ① USB Type-C connector
* ② Switch A for flashing firmware. It includes the N switch and S switch. 
* ③ Switch B for flashing firmware. The holtite sockets (part No. 13) have to be installed first. 
* ④ Connector for the flexible flat cable. It can be used for the center USB connector mod.
* ⑤ Lithium battery USB charge controller (optional for the lithium battery mod)
* ⑥ USB Type-C connector for flashing the firmware on the official USB dongle

### 装配说明 Assembly instructions

1. 在焊接按键轴之前，建议先给PCB连接USB数据线或者安装7号干电池（建议碱性电池或者锂铁电池，3个电池舱不支持安装锂离子电池)，测试PCB功能是否能正常使用；
2. 切换蓝牙1~3通道和USB有线4号通道的按键组合键依次是Fn+Z/X/C/V，请使用镊子来短接按键，并测试通过蓝牙来和PC/Mac/手机来配对；
3. TR60的PCB默认的蓝牙设备的名称是：Mickey-xxx-x，xxx代表后缀，由固件版本和实际使用时开启的蓝牙通道编号决定，例如Mickey-0104b-1；
4. 由于不同电脑的兼容性不一样，如果遇到无法搜索到蓝牙的情况，请尝试把PCB背面跳线开关的N开关（前文图片中的编号②）向上拨动到ON状态或者向下拨动到OFF状态，有些人反馈是向上拨动（ON状态）能搜索到设备，有些人反馈是向下拨动（OFF状态）才能搜索到设备；日常使用时，请保持S开关为OFF状态；
5. 对于选择中央USB口的用户，请使用附件中的FPC软排线连接；
6. 对于购买了Dongle的用户，请参阅Dongle配对的专门章节；

-

1. Before soldering switches, it is recommended to test the PCB first by connecting the USB cable or installing AAA batteries. Alkaline batteries and Li-Fe batteries are supported. AAA Li-ion batteries are not supported as in the battery housing.
2. You can switch the connection modes by shorting Fn+Z/X/C/V. Fn+Z/X/C/ is for Bluetooth channels and Fn+V is for USB connection. 
3. The default device name is Mickey-xxx-x when TR60 is working on the Bluetooth mode. The postfix xxx is decided by the firmware version and the Bluetooth channel (e.g. Mickey-0104b-1)
4. Due to the complex compatibility issues, please try to adjust the switches when the Bluetooth device cannot be found. The N switch (② in the main PCB photo) can either be ON or OFF whichever works to you. The S switch should always be OFF during usage. 
5. Use the flexible flat cable if you want the USB connector being in the center. 
6. Refer to the dongle pairing section if you bought the dongle.


### 备用刷机跳线③的安装说明 Holtite sockets ③ installation


附件包中包含了4颗跳线针座，编号13，外形如下图⬇

The accessory kit includes 4 holtitle sockets (part number 13). The following is how they look like ⬇

![图片](https://github.com/TriangleLab/TR60/raw/master/IMG/3.jpg)

打开轴盖，把针座安装进去⬇

Open the switch top and install the sockets ⬇

![图片](https://github.com/TriangleLab/TR60/raw/master/IMG/4.jpg)

![图片](https://github.com/TriangleLab/TR60/raw/master/IMG/5.png)

![图片](https://github.com/TriangleLab/TR60/raw/master/IMG/6.png)

**PCB 板子上面的安装位置**

**Install positions on the PCB**

拨码开关和跳线针座的功能是完全一样的，互为备份，用户可以按自己需要来安装。

The DIP switch and the holtite sockets have exactly the same function. These two ways complement each other. You can choose to install either one or both according to your preference. 

## 按键配列生成说明 Changing the keyboard layout

### 步骤① 使用KLE生成Raw Data  Step① Generate Raw Data with KLE(keyboard-layout-editor.com)

地址 URL：[http://www.keyboard-layout-editor.com/](http://www.keyboard-layout-editor.com/)

参考配列 Default layout：

**层① Layer ①:**

![图片](https://github.com/TriangleLab/TR60/raw/master/IMG/7.png)


	["Esc","!\n1","@\n2","#\n3","$\n4","%\n5","^\n6","&\n7","*\n8","(\n9",")\n0","_\n-","+\n=","Delete","Backspace"],
	[{w:1.5},"Tab","Q","W","E","R","T","Y","U","I","O","P","{\n[","}\n]",{w:1.5},"|\n\\"],
	[{w:1.75},"Caps Lock","A","S","D","F","G","H","J","K","L",":\n;","\"\n'",{w:2.25},"Enter"],
	[{w:2.25},"Shift","Z","X","C","V","B","N","M","<\n,",">\n.","?\n/",{w:1.75},"↑","Fn0"],
	[{w:1.25},"Ctrl",{w:1.25},"Win",{w:1.25},"Alt",{w:6.25},"Space",{w:1.25},"Alt",{w:1.25},"←",{w:1.25},"↓",{w:1.25},"→"]

**层② Layer②：**

![图片](https://github.com/TriangleLab/TR60/raw/master/IMG/8.png)

	 ["~\n`","F1","F2","F3","F4","F5","F6","F7","F8","F9","F10","F11","F12",{a:7},"",{a:4},"Fn27"],
	[{a:7,w:1.5},"","","","","","","","",{a:4},"Ins",{a:7},"",{a:4},"Psc","Scrlk","Pause\nBreak",{w:1.5},"Calc"],
	[{a:7,w:1.75},"","","","","","","","","","","","",{w:2.25},""],
	[{w:2.25},"",{a:4},"Fn28","Fn29","Fn30","Fn31",{a:7},"","","",{a:4},"VolDn","VolUp","Mute",{w:1.75},"↑",{a:7},""],
	[{w:1.25},"",{w:1.25},"",{w:1.25},"",{w:6.25},"",{w:1.25},"",{a:4,w:1.25},"←",{w:1.25},"↓",{w:1.25},"→"]

### 步骤② 使用TKG生成按键配列BIN文件  Step② Generating BIN file with the TKG tool

  将配列Raw Data 粘贴到 [https://tkg.btsmartshield.com/](https://tkg.btsmartshield.com/) 
  以上述配列为例，将上述几层配列粘贴到相应框中，修改Fn0、Fn4以开启层1、层2，点击页面下方“下载.bin文件”保存配列 .bin 文件。
  请选择mb1plus这个键盘，这是TR60的PCB的开发代号。
  
  Copy the RAW DATA to [https://tkg.btsmartshield.com/](https://tkg.btsmartshield.com/) 
  If you use the above default layout, copy the two layers of RAW DATA into the corresponding text boxes. Set Fn0 as *Layer action > momentary, layer 1*. Set Fn4 as *Layer action > momentary, layer 2*. Click the *download .bin file* on the bottom of the webpage.
  The keyboard should be set to mb1plus, the code name of the TR60 PCB.
      
![图片](https://github.com/TriangleLab/TR60/raw/master/IMG/9.png)
      
![图片](https://github.com/TriangleLab/TR60/raw/master/IMG/10.png)

### 注意事项 Cautions

 如果你想要使用2U的BackSpace，请直接在分裂BackSpace的第二个按键上设置，即下图中的红色按键。在PCB设计层面，2U BackSpace和红色1U按键是逻辑等价的，因为TKG软件的目前的一个小bug，所以设置2U的时候，不要在KLE设置2U长度的按键，TKG会识别不到。
 
 If you want to use 2u Backspace, just set the keycode of the second key (the red one in the following picture) of the split Backspace. Setting 2u backspace in KLE will not work in TKG.

![图片](https://github.com/TriangleLab/TR60/raw/master/IMG/11.png)

Fn20以上功能键为键盘功能键，无需配置，具体含义如下：

* Fn27: 清除所有已经绑定的蓝牙主机。
* Fn20\~Fn22: 解除1\~3的蓝牙主机绑定。如果已经绑定，则解除已经绑定的主机；开启广播允许新设备绑定。
* Fn28\~Fn30: 选择3个不同的蓝牙主机。选择已经绑定的主机；如果尚未绑定，则开启广播允许新设备绑定
* Fn31: 选择USB通道。
* 在发货的配列中，Fn27~Fn31已经映射到了键盘的Back\Z\X\C\V，搭配层①的Fn0使用即可。

Fn20 and above function keys were set to default functions as described below：

* Fn27: delete all the paired Bluetooth devices
* Fn20\~Fn22: unpair number 1\~3 Bluetooth devices. If there are paired devices, the devices will be unpaired. The keyboard will broadcast and search for new devices.
* Fn28\~Fn30: switch among 3 different Bluetooth devices. If the device was paired before, the device will be set as the current device. If there is no paired device, the keyboard will broadcast and search for new devices.
* Fn31: switch to the USB connection.
* In the default firmware, Fn27~Fn31 have been mapped into Backspace\Z\X\C\V on layer 1.


## TR60-BLE 固件烧录办法（暂行版本）TR60-BLE firmware flashing provisional solution

目前版本的TR60-BLE 的配列文件在线烧录网站需要Google Chrome的新特性支持，所以请使用2019年版本的 **Google Chrome 浏览器**来执行以下操作。准备工作，请将电池取出，使用USB数据线来给给键盘供电。
      
On the current firmware flashing website, **Google Chrome**'s new features are required to flash the layout files. Please use the Chrome versions after 2019. Before starting the flashing, the batteries should be removed. The keyboard will be powered by the USB cable during the flashing process. 

### 步骤① 更新USB模式芯片的固件 Step ① Update the USB mode chip's firmware

  断开键盘和电脑之间的USB 连接，将PCB背面的 **S 开关**切换到ON状态，或者是把Wired 跳线位置，用硬质金属丝短接起来——比如剪下来一段插件式LED灯的针脚。
  USB 芯片会进入DFU模式，Windows系统的话，你会在设备管理器里面看到一个STM32 Bootloader 设备。
  访问 [https://mb2.btsmartshield.com/webdfu/dfu-util/](https://mb2.btsmartshield.com/webdfu/dfu-util/) ，你会看到如下界面
  
Disconnect the keyboard with your PC/Mac. Turn the **S switch** to ON status or short the holtite sockets at the wired position. 
      The PCB will enter the DFU mode. If you're using Windows OS, you can find a device named STM32 Bootloader.
      visit [https://mb2.btsmartshield.com/webdfu/dfu-util/](https://mb2.btsmartshield.com/webdfu/dfu-util/) and you will find the following interface. 

![图片](https://github.com/TriangleLab/TR60/raw/master/IMG/12.png)

点击：“Connect”，在弹出的对话框中选择 STM32 BOOTLOADER 设备，并点击连接。（对于Windows系统的设备，如果无法找到该设备，请使用Zadig将本键盘的USB驱动替换为 WinUSB 驱动，Zadig的地址 [https://zadig.akeo.ie/](https://zadig.akeo.ie/)）

Click the "Connect" button.  Select STM32 BOOTLOADER device in the appeared dialog box then choose to connect. If you are using Windows OS and cannot find the device, please use Zadig([https://zadig.akeo.ie/](https://zadig.akeo.ie/)) to install the WinUSB driver.

![图片](https://github.com/TriangleLab/TR60/raw/master/IMG/13.png)

点击页面中的“Download"，等待擦除、烧写结束。

Click the "Download" button and wait until the erasing and flashing are finished.

![图片](https://github.com/TriangleLab/TR60/raw/master/IMG/14.png)

### 步骤② 使用 TKG 生成BIN（按键配列文件）Step② Generate BIN (the layout file) with TKG

TKG的地址 URL of TKG：[https://tkg.btsmartshield.com/](https://tkg.btsmartshield.com/)

![图片](https://github.com/TriangleLab/TR60/raw/master/IMG/15.png)

请选择 mb1plus，这是TR60配套PCB的设备代号。具体的按键配列生成办法，请参考配列生成的章节。

Please select mb1plus, the code name of TR60's PCB. Please refer to the layout configuration section for detailed information. 

### 步骤③ 将BIN文件（按键配列文件）烧录进键盘 Step③ Flashing the BIN file (the layout file) into the PCB

断开键盘和电脑间的USB连线，将S开关切换到OFF，将N开关切换到ON（或者通过插针跳线的方式，也就是下图中的①②插针位开关），然后连接USB。

Tips:跳线位和拨码开关位，最好不要同时使用，以免误操作。

Disconnect the keyboard from the computer and turn the S switch to OFF, the N switch to ON (or short the respective holtite sockets). Now reconnect the keyboard with the USB cable. 

Tips: Don't use the DIP switches and the holtite sockets in the same time to avoid misoperation. 

![图片](https://github.com/TriangleLab/TR60/raw/master/IMG/16.png)

访问BIN的烧录地址：

Visit the URL for flashing BIN files: 

[https://mb2.btsmartshield.com/dapjs/examples/daplink-flash/web.html](https://mb2.btsmartshield.com/dapjs/examples/daplink-flash/web.html) 

![图片](https://github.com/TriangleLab/TR60/raw/master/IMG/17.png)
      
点击“Choose a firmware image”，在弹出的对话框中选择“步骤2”生成的BIN文件。

Click the "Choose a firmware image" button then choose the BIN file generated from  step 2. 

![图片](https://github.com/TriangleLab/TR60/raw/master/IMG/18.png)

点击“SELECT DEVICE”，在弹出的对话框中选择“**MB CMSIS DAP**” ，点击“连接”。

Click the "SELECT DEVICE" button then choose "MB CMSIS DAP" option. Click "Connect"

![图片](https://github.com/TriangleLab/TR60/raw/master/IMG/19.png)

等待烧写完成。

Wait until the flashing is finished. 

![图片](https://github.com/TriangleLab/TR60/raw/master/IMG/20.png)

如果出现错误，请拔掉键盘，等待数秒后重试。

If an error occurs, disconnect the keyboard and retry after several seconds. 
