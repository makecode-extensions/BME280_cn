# BME280

makecode BME280 ������ʪ�ȡ���ѹ������ micro:bit �����  

Author: shaoziyang  
Date:   2018.Mar  

![](https://raw.githubusercontent.com/microbit-makecode-packages/BME280_cn/master/icon.png)  
  
![](https://raw.githubusercontent.com/microbit-makecode-packages/BME280_cn/master/bme280.jpg)

## ʹ�÷���

�� makecode �༭��������Ŀ��ѡ������������Ȼ���ڵ�ַ������������ַ  

https://github.com/microbit-makecode-packages/BME280_cn  

������Ϳ�����Ӳ�ʹ�ñ�������ˡ�

## I2C ��ַ  

- 0x76/0x77  

## API

- function pressure()  
��ȡ��ѹ(hpa)  

- function temperature()  
��ȡ�¶�(��)

- function humidity()
��ȡʪ��(%)

- function PowerOn()
����ģʽ.

- function PowerOff()  
����͹���ģʽ  

- function Address(addr: BME280_I2C_ADDRESS)  
���� BME280 I2C ��ַ����ַ���������²���:  
  - BME280_I2C_ADDRESS.ADDR_0x76
  - BME280_I2C_ADDRESS.ADDR_0x77

## ��ʾ

![](https://raw.githubusercontent.com/microbit-makecode-packages/BME280_cn/master/demo.jpg)

## ��Ȩ��ʽ

MIT

microbit/micropython ����������Ȩ���� (c) 2018  

## ֧��Ӳ��

* for PXT/microbit


[���� microbit/micropython ��������](http://www.micropython.org.cn) 
