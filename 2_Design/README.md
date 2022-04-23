![image](https://user-images.githubusercontent.com/101916283/164882621-ff795337-ced3-4121-b5b4-e2d5b3dd5e98.png)

"The impedance buffer in the [Basic Flex Sensor Circuit] (above) is a single sided
operational amplifier, used with these sensors because the low bias current of the
op amp reduces errer due to source impedance of the flex sensor as voltage
divider. Suggested op amps are the LM358 or LM324."

![image](https://user-images.githubusercontent.com/101916283/164882810-6893e520-8d50-492f-82af-876e00607250.png)

From the above block diagram the flex sensor is attached with a door, when the
position of the door get changed the flex sensor also bend accordingly .flex sensor
is connected with a voltage divider circuit ,when the flex sensor resistance changes
the output voltage also change accordingly. The output voltage of the divider circuit
is given to a Arduino uno kit . where the analog voltage is get converted into digital
form ,according to the variation of the digital value I have written a program such
that when the door is open the display will show the door is open and a led will
glow otherwise the led will be remain off for the rest of the time.
