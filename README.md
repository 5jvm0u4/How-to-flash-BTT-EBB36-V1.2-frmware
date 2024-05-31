# How to flash EBB32 V1.2's frmware THE OLD WAY

# To do it the newer and easier way, follow this guide: https://docs.meteyou.wtf/btt-ebb/klipper/
# But still make sure config matches the ones down below on THIS page, not the ones in that guide

(Open PuTTY, connect to your klipper)

cd ~/klipper

make menuconfig

![image](https://github.com/5jvm0u4/How-to-flash-EBB32-s-frmware/assets/75752327/6b4369f3-f6cc-4ef8-9640-7e1f25e3c8bf)

Q(Quit)

Y(Yes)

make

(Open WinSCP, go find ~/klipper/out/klipper.bin, copy the file out to your PC, close WinSCP)

(Get your board, add a jumper(green arrow) to make it powered by USB, remember to remove it after everything is done)

![image](https://github.com/5jvm0u4/How-to-flash-EBB32-s-frmware/assets/75752327/74619e42-d226-4aaf-9c7b-931e311eff21)

(plug the board to your PC via onboard USB type-C connector, press and hold the BOOT botton and while holding BOOT, press and release RST botton, then release BOOT, this will make the board enter DUF-Mode)

(Open STM32CubeProgrammer and enter this page)

![image](https://github.com/5jvm0u4/How-to-flash-EBB32-s-frmware/assets/75752327/722ee06d-8f96-4f75-9a9a-01503e06c72d)

(hit refresh and a USB device should show up, hit connect and this page would show up)

![image](https://github.com/5jvm0u4/How-to-flash-EBB32-s-frmware/assets/75752327/73253df4-f1e5-47fa-b7c1-893145b7872d)

(click open file and choose the file klipper.bin you just saved, someware I guess, and this page would show up)

![image](https://github.com/5jvm0u4/How-to-flash-EBB32-s-frmware/assets/75752327/0f3f4567-a4b6-4334-a7b7-50c40db36d52)

(click download and you should see something like this)

![image](https://github.com/5jvm0u4/How-to-flash-EBB32-s-frmware/assets/75752327/e4522e1b-da43-4546-8f7f-cef41fb38c8b)

(and now you're done, close everything and remove the jumpper)



 
 
