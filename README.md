# EV3-AdvHTColorV2-Block
![](https://i2.wp.com/ofdl.tw/wp-content/uploads/2020/09/HTCOLV2l_OFDL.jpg?w=592&ssl=1)

You can download ev3b file to import this block：[Latest release](https://github.com/a10036gt/EV3-AdvHTColorV2-Block/releases)

What’s EV3-AdvHTColorV2-Block？

Most commonly used Sensor in WRO Regular：HT Color sensor V2, provide user read object in long distance. But it have some bugs, if when you reading sensor value then interrupt the program, next time you reading the sensor, the sensor will get stuck, and return the last value, you can try out this in EV3 port view APP.

It’s I2C protocol problem, we solve this issue in our block, make sure the robot will not effect by this issue.

And we also add the HSVL mode for you guys, it can make robot read color more accurate.

使用說明：https://ofdl.tw/ev3-hack/adv-ev3-color-sensor-block/

User Guide：https://ofdl.tw/en/ev3-hacking/adv-ev3-color-block/

