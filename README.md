# smart_home_control_system
51单片机课设，智能家居控制系统

​		以STC89C52为主控芯片，以矩阵键盘输入密码，以独立按键确认、清除、进入修改密码界面和锁门（关密码锁），输入密码错误3次以后进行蜂鸣器报警，并锁定键盘，只能用红外遥控开锁；修改密码后会用EEPROM进行保存；以矩阵键盘和红外遥控共同人工控制灯和风扇的开关，用DS1302时钟芯片进行计时，用DS18B20数字温度传感器获取温度，当温度和时间达到设定的值时，会自动开启风扇和灯，智能开启的灯和风扇是可自动调节的，风扇的转速会比人工开启的稍慢，而灯会根据光强自动调节亮度，其中风扇使用ULN2003直流电机驱动模块控制，灯光的调节是通过PCF8591数模转换模块和光敏电阻控制。开密码所后，会显示当前温度时间和是否开启灯和风扇；显示部分使用的是LCD1602液晶，红外接收用的是HS0038红外接收模块。

![img](https://github.com/qq992338041/smart_home_control_system/课程设计智能家居/流程图.png)
