# newTweetSpkr
**New tweet speaker** -- listen to new tweets and broadcast them  This project listens to the latest news from the twitter owner you are interested in. Then broadcast it by voice. Support English and Chinese.

### Basic function
On the server side, a twitter message crawler is responsible for getting the latest tweets and then opening them to the internet via a web service.

On the client side, it constantly queries the internet for information, and if it is new, it will broadcast it by voice.

The client side is a web server developed in python. The client side is a C program running on ESP8266 MCU (micro controll unit). ESP8266 microChip comes with a wifi module, which can access the resources on the internet and is a cheap solution for IoT application development.

## New tweet speaker -- 监听新的tweet并广播

这个项目可以监听你感兴趣的twitter主人的最新消息。然后通过语音播报出来。支持英文和中文。

在服务端，一个twitter消息爬取器负责获取最新的tweet，然后通过web服务开放给internet.

在客户端，不断的查询internet上的信息，如果是新的，就进行语音播报。

服务端是使用python开发的一个web server. 客户端是运行在ESP8266 MCU(micro controll unit)上的C程序。ESP8266 microChip 自带wifi模组，可以访问internet上的资源，是物联网应用开发的廉价解决方案。
