# How to flash EBB32 V1.2's frmware

cd ~/klipper

make menuconfig

![image](https://github.com/5jvm0u4/How-to-flash-EBB32-s-frmware/assets/75752327/6b4369f3-f6cc-4ef8-9640-7e1f25e3c8bf)

Q(Quit)

Y(Yes)

make

(Open WinSCP, go find ~/out/klipper.bin, copy the file out to your PC, close WinSCP)

(Get your board, add a jumper(green arrow) to make it powered by USB, remember to remove it after everything is done)

![image](https://github.com/5jvm0u4/How-to-flash-EBB32-s-frmware/assets/75752327/74619e42-d226-4aaf-9c7b-931e311eff21)

(plug the board to your PC via onboard USB type-C connector, press and hold the BOOT botton and while holding BOOT, press and release RST botton, then release BOOT, this will make the board enter DUF-Mode)
 (Open STM32CubeProgrammer)
 
 
