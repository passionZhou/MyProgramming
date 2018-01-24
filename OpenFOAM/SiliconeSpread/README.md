# SiliconeSpread1.0
---------------------

初步完成硅胶流体在表面的铺展现象

可应用在OpenFOAM4.0版本

##20180121
	
尝试在OF5.0版本下运行，出现error

##20180123

###发现了bug原因
	0/U文件中，边界walls少写了一个字母s

###处理方法：
	将边界walls改为leftAndRight



#SiliconeSpread1.1
-----------------------------

##20180123

###更改了部分参数

	1. 0/alpha.silicone中surface的type改为dynamicAlphaContactAngle

	2. 0/p_rgh中top的参数增加
	gamma           1;
	value           uniform 0;

#SiliconeSpread1.2
-----------------------------------

##20180123

###


