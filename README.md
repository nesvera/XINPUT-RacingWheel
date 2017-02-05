# XINPUT-RacingWheel

This racing wheel is based in an XINPUT Xbox 360 controller.

I ported a code from a TeensyLC to a STM32F103C8T6 Dev Board.

The original code is here https://github.com/zlittell/MSF-FightStick.

Thanks Zack.

I talk more about this project im my blog, take a look. https://engenhariaegambiarras.wordpress.com/2017/02/04/racing-wheel-xinput-controller/

<img src="https://cloud.githubusercontent.com/assets/17488425/22621683/a518770a-eb10-11e6-9fed-834b1cdd1bd9.JPG" width="600px" height="500px" />

You will need uVision IDE to open this project. Open the file "stm32_xinput" inside "MDK-ARM" folder.

To do list:
* Read led and rumble feedback
* Improve the code
* Need to change interruption handler from encoder, sometimes the steering wheel lost the center
* Expand to others families of STM32

Some bugs may apper!

Version 1*10^0.0
