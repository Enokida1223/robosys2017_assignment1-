# robosys2017_assignment1 
RaspberryPi3での簡単なGPIO制御
## Demo
[Lチカと寿司](https://youtu.be/EXtv9RNmdGU)
## Requirements
+ RaspberryPi3
  + Raspbian
+ linux kernel sorce  
  + `/usr/src/linux`をダウンロード  
  + kernel build scripts:https://github.com/ryuichiueda/raspberry_pi_kernel_build_scripts  
+ LED  
+ 抵抗器(10Ω)  
## Usage
+ LEDを光らせる  
`echo 1 > /dev/myled0`
+ LEDを消す  
`echo 0 > /dev/myled0`
+ 寿司を大量に表示させる  
`cat /dev/myled0`
## Reference/Quotation
[ロボットシステム学 講義資料](https://github.com/ryuichiueda/robosys2017/blob/master/07.md)
