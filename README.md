# Robosys_DeviceDriver
Make device driver with Raspberry pi 3 model B+ <br>
Operate three LEDs using Raspberry pi with linux.

# About this decive driver
**How to use**
```python
make
sudo insmod myled.ko
sudo chmod 666 /dev/myled0
echo command /dev/myled0
```

**commands** <br>
0:Turn off all LED <br>
1:Turn on only First LED <br>
2:Turn on only Second LED <br>
3:Turn on only Third LED <br>
4:Turn on all LED <br>
5:flash like wave

**Experiment** <br>
[Experiment video]()
