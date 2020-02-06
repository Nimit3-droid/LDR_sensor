# LDR_sensor

The color sensor needs to be calibrated before using. First connect the RGB LED and the LDR to an arduino
  and uploade the code to it. Then connect the arduino to the PC and open the 'processing' application. By using
  the interface select the correct COM Port for the arduino. When establishing the connection the arduino will
  automatically 'reset' itself. Then by following the 'calibration' calibrate the sensor
  Calibration : Point the sensor to a white surface after the first color cycle.
                When the white calibration is done the second color cycle will begin.
                After the second cycle, point the sensor to a black surface to begin the next stage.
                When that is done the LED will turn to green and blink three times to indicate the end of the calibration.
  
  After calibrating the sensor by using black and white surfaces, 
  the sensor will measure the color on a targeted surface and get its color in RGB color code.

