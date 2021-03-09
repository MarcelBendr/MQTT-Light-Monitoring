# MQTT-Lux-Monitoring

In this example, all needed files in order to set up a mosquitto Broker, the IoT-Gateway and the ESP32 programming, are included. To reproduce this build, use a Linux-based platform. We used a BalenaFin (alternatively RaspberryPi) as Broker and Gateway device simultaneously. ESP32 works as sensor device and ThingsBoard is used as the Cloud platform.

Code for Mosquitto Broker is taken from here:
http://appcodelabs.com/introduction-to-iot-build-an-mqtt-server-using-raspberry-pi

Code for the Gateway setup is taken from here:
https://thingsboard.io/docs/iot-gateway/install/source-installation/

Code for Connector JSON configuration is taken from here:
https://thingsboard.io/docs/iot-gateway/config/mqtt/
