# 介绍

?>  海尔U+IoT平台提供了三大类设备接入平台的方案，分为设备直连接入，以云设备接入，以云云接入；其中设备直连接入又分直连U+物联模组和直连U+设备SDK。


| **接入方式**     | **对设备的要求**                                             | **U+**  **可实现功能**                                       | **用户体验** |
| ---------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------ |
| 直连—U+物联模组  | 设备底板按E++协议实现                                        | 1、体验类：绑定、设备APP控制、设备语音控制、场景（本地、远程）  2、数据采集类：可实现数据采集  3、OTA类：模块可OTA、底板可OTA | 优           |
| 直连—U+设备SDK | 设备底板无需改动，模块集成U+设备SDK，按设备SDK的API定义调用    | 1、体验类：绑定、设备APP控制、设备语音控制、场景（本地、远程）  2、数据采集类：可实现数据采集  3、OTA类：底板可OTA | 优           |
| 云设备           | 设备底板无需改动，设备云端按U+云设备网关API的定义调用 | 1、体验类：绑定、设备APP控制、设备语音控制、场景（远程）     | 良           |
| 云云接入         | 设备底板与模块都无需改动，设备云端按U+云设备网关API的定义调用 | 1、体验类：设备APP控制、设备语音控制、场景（远程）           | 一般         |



