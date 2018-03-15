# Read Me!!

If you're not aware, the Melzi 1.1.2 and 2.0 circuit boards being shipped with the CR-10 and CR-10s have an issue where the temperature sensors cannot reliably read temperatures. This leads to large fluctuations in temperature readings and the thermal runaway protection being triggered, as well as your heater not knowing what to do and trying to correct the bad readings it is getting, further throwing off your temperatures. I did not initially notice the problem when I first started printing with the CR-10 in PLA, I only noticed it when I began trying to print in PETG.

Now this issue has been very well documented on reddit and by TH3D for the V2.0 board, however no one has posted how one can fix their V1.1.2 so this repo will basically document how I fixed mine. 

Preface, I have flashed the bootloader to my board and installed Marlin which I highly suggest everyone do with the Melzi boards given with the Creality 3D printers (I used this tutorial: http://www.instructables.com/id/Flashing-a-Bootloader-to-the-CR-10/), I will be uploading my Marlin configurations to this github as well.

## How do you know if this problem effects you?

The easiest way to tell if this problem effects you is to check your hotend temperature readings at room temperature. If the readings fluctuate by a few degrees then you most likely have this issue. However, you should tune your PID before and check that all wires are in properly before jumping to any conclusions. TH3D made a very good little gif showing what the flucuations look like: https://i0.wp.com/www.th3dstudio.com/wp-content/uploads/2018/01/2018-01-25_18-22-43.gif?resize=1080%2C607&ssl=1

## I have a CR-10S with a V2.0 board, what do I do?

This issue has been very well documented for the V2.0 board so I will refer you to Jozer99 of Jozerworx and their tutorial on how to fix it here: https://www.jozerworx.com/creality-cr-10s-c4-capacitor-diy-fix-tutorial/

And if you don't have the equipment and knowhow to do so, TH3D can fix the issue for you here: https://www.th3dstudio.com/product/creality-cr-10s-v2-0-board-repair-temperature-fluctuation/

