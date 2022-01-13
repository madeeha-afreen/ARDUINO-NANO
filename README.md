<h1># ARDUINO-NANO</h1>
<h4>Perfectly working C program code for Arduino Nano, for my mini IOT project: NON-CONTACT THERMOMETER, using thermopile sensor and thermistor. <br>
  
<br>To make this project i have used the following components:</h4>
<h6>• MLX90614ESF IR Temperature Sensor<br>
• APDS-9960 Proximity sensor<br>
• Arduino Nano<br>
• TP4056 Battery charging module<br>
• Buzzer<br>
• 18650 li-ion rechargeable battery <br>
• 128x32 12c OLED Display<br> </h6>               

<h4>The arduino code does the following:<br></h4>
<h6>Shows “NOT DETECTED” on the OLED display.
If, the proximity sensor is inactive(i.e... no object is detected).<br>

Once the object comes within the range with proximity sensor. It activates the MLX temperature sensor and displays "Body Temp : " in degree Farenheit upto two decimal places.<br>
If, the body temperature crosses 100 degree Farenheit, the buzzer gets activated and "CRITICAL" is displayed along with the Temperature in Farenheit.</h6>
