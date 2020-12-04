# Description
Make device driver with Raspberry pi 3 model B+ <br>
Operate three LEDs using Raspberry pi with linux.

# Requirements

|No.|Item Name|Quantity|
|:---:|:---:|:---:|
|1|Raspberry Pi 3 model B+|1|
|2|Bread board|1|
|3|LED|3|
|4|Cable|7|
|5|150Ω Resistor|3|

# Circuit diagram
![キャプチャ](https://user-images.githubusercontent.com/50652151/101168661-19692600-367f-11eb-98eb-d5c2cc75d4ee.PNG)

# How to use
**Build**
```python
$ git clone https://github.com/Chappy06260/Robosys_DeviceDriver.git
$ cd Robosys_DeviceDriver
$ make 
$ sudo insmod myled.ko
$ sudo chmod 666 /dev/myled0 
```
**Run**
```python
$ echo command > /dev/myled0
```

**command list** <br>
```python
0: Turn off all LED <br>
1: Turn on only LED1 <br>
2: Turn on only LED2 <br>
3: Turn on only LED3 <br>
4: Turn on all LED <br>
5: flash like wave
```

**video** <br>
[Experiment video]()
