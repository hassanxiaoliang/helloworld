# helloworld
first program

##温度转换程序-Python
#tempconvert.py
# -*- coding:utf-8 -*-
Tempstr = input("请输入带有符号的温度值：")
if Tempstr[-1] in ['F','f']:
    C =(eval(Tempstr[0:-1])-32)/1.8
    print ("转换后的温度是{:.2f}C".format(C))
elif Tempstr[-1] in ['C','c']:
    F = 1.8*eval(Tempstr[0:-1]) + 32
    print ("转换后的温度是{:.2f}F".format(F))
else:
    print ("格式输入错误")

