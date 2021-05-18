# HW3
Use the following command to compile:  

    $ sudo mbed compile --source . --source ~/ee2405/mbed-os-build/ -m B_L4S5I_IOT01A -t GCC_ARM --profile tflite.json -f  
Also use the following command to check the MQTT messenge:  

    $ sudo python3 wifi_mqtt/mqtt_client.py  
Use the following command to open the screen:  

    $ sudo screen /dev/ttyACM0
Enter the following code on the screen:  

    /get_th_angle/run
Then you can use the gesture "slope" to increase the threshold angle by 5. Note that now the LED1 is on, and you can see the current angle on the uLCD.  
After you selected the disired angle, press the user button to jump out of this function. You will see LED1 is off and the broker get the threshold number.  
Then Enter the following code on the screen:  

    /det_angle/run
