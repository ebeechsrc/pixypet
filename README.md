# Pixy Pet
This is a small variation of the [Adafruit Pixy Pet](https://learn.adafruit.com/pixy-pet-robot-color-vision-follower-using-pixycam/overview)

The pixy pet is an [Arduino](https://store.arduino.cc/arduino-leonardo-with-headers) robot running on a [Pololu Zumo](https://www.pololu.com/category/169/zumo-robot-for-arduino) robot platform that uses the [Pixy CMUcam5](http://charmedlabs.com/default/pixy-cmucam5/) to perform computer vision tasks.

This version is configured to follow a single [100mm blue stage ball](https://www.firetoys.co.uk/juggling-equipment/juggling-balls/stage-balls/sil-x-100mm-stage-ball.html) and keep it at a fixed distance away from the robot. The reverse steering has been changed from the stock Adafruit example and a quiet reversing beep has also been added in the [Arduino script](Arduino/Pixy/pixypet.ino)

The [PixyMon](http://cmucam.org/projects/cmucam5/wiki/Install_PixyMon_on_Windows_Vista_7_8) configuration for tracking a single ball is included in the [PixyCam5 section](PixyCMUCam5/Config/pixypet.prm) section of this repository, along with a copy of the [pixymon installer](PixyCMUCam5/App/pixymon_windows-2.0.9.exe)

The Arduino script was written against version 1.8.1 of the Arduino CC environment. The zumo and adafruit libraries that were used are also included in the Arduino directory.