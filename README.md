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

# Circuit


# How to use
**Preparation**
```python
1: make
2: sudo insmod myled.ko
3: sudo chmod 666 /dev/myled0 
```
**Command**
```python
echo command > /dev/myled0
```

**command list** <br>
```python
0: Turn off all LED <br>
1: Turn on only First LED <br>
2: Turn on only Second LED <br>
3: Turn on only Third LED <br>
4: Turn on all LED <br>
5: flash like wave
```

**video** <br>
[Experiment video]()
