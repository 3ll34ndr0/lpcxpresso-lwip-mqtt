# lpcxpresso-lwip-mqtt
LPC175x_6x + LWIP + MQTT

This project is a merge of the lwip_tcpecho (released on 2014) project that comes in the LDPCXPRESSO IDE library, and the latest stable (Oct 2017) LWIP version. LWIP comes with some funtions to deploy a MQTT client that can subscribe and publish to a topic. 

How to use it:
You should install a MQTT broker in any machine, and edit file lwip_mqtt.c to configure the broker ip in themqttServerIP variable. You must also configure the device ip on file lwipNuevo.c on variable ipaddr.

  
