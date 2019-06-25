Raspberry Pi Gauge Controller

Objective: Develop a system using a raspberry pi to simulate inputs to original gauges in restored vehicles.

Pi used:    Raspberry Pi 3 Model b
Pi OS used: Raspian
Language:   C


Data input from OBD interface (CAN bus).

Simulated gauge inputs:
    Variable voltage/resistance (1st priority)
    Boolean lights (1st priority)
    Mechanical (2nd priority)
    
Peripherals needed:

    Variable voltage/resistance
        >Use PWM from GPIO pins to simulate variable voltage
        >Need jumper cables to connect to gauge
        
    Boolean lights
        >Need jumper cables and LED lights
    
    Mechanical
        >Need reliable CIM motor and motor controller


Resources:
    https://www.hotrod.com/articles/updated-instruments-new-electronics-old-gauges-classic-instruments/
    http://www.toptechboy.com/raspberry-pi/raspberry-pi-lesson-27-analog-voltages-using-gpio-pwm-in-python/
    
