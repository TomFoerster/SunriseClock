# SunriseClock
## Features
- Wakeup with warm to cold light transition
- Webinterface for easy setup
- raspi/orange pi zero for cheap and ez WLAN-Setup with python integration
- 12V power supply for RGB leds
- power pcb with FETs for led dimming and buck converter for the 5V supply of the raspi
- either pigpio or hardware i2c interface (cheap atmel as i2c slave) for rgb pwm (http://abyz.co.uk/rpi/pigpio/) whatever works with the available cpu-power (keeping the voice recognition enhancement in mind)
- Tube to wrap RGB strip around

## Possible Enhancements
- Sleep as Android integration?
- birdsounds and other relaxing sounds/music
- BME280 or BME680 for humidity, temperature, pressure (and gas) detection
- accelerometer for sleep monitoring and smart alarm features
- voice recognision capability with pocketsphinx or SpeakPython
  * set alarm via voice command
  * play relaxing sounds via voice command
  * turn light on or off via voice command
  * tell current air quality and maybe visualize it via colors
- discolight by using FFT for bass detection

  
 


