# ESP8266-WebConfig
程序描述:
软件平台：Arduino IDE
硬件平台：ESP8266（NodeMCU）
功能：web配网，和自动连接
工作流程：开机后自动连接配置的WiFi（LED周期1s闪烁），如果不范围内，或连接超时；
	则进入web配网模式（LED常亮）；连接成功（LED周期200ms闪烁）
