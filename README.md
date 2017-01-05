# led
ロボットシステム学
led点滅の流れ

make
↓
sudo insmod myled.ko
↓
sudo chmod 666 /dev/myled0
↓
chmod +x led.bash
↓
sudo ./led.bash
