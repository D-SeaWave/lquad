arduino 自平衡四轴
==========

##程序模块

###1. 电机控制模块：

	该模块控制根据传入的值（1000~2000）调整成适合的pwm值控制电调，目前支持UNO MEGA2560

###2. 协议转换模块：

	协议格式:
		头	数据长	数据	校验和
		255	len		len-1	sum

###3.ROM模块：
	
	负责存取PID数据

###4.mpu模块：
	
	负责mpu数据的读取和调整。使用卡尔曼滤波

###5.PID模块:

	负责计算PID


