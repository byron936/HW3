# HW3
Use the following command to compile:  

    $ sudo mbed compile --source . --source ~/ee2405/mbed-os-build/ -m B_L4S5I_IOT01A -t GCC_ARM --profile tflite.json -f  
Also use the following command to check the MQTT messenge  

    $ sudo python3 wifi_mqtt/mqtt_client.py  
Use the following command to open the screen  

    $ sudo screen /dev/ttyACM0
