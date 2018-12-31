# raspberry_LED
The assignment of robot system in Chiba Institute of Technology.

Hichon Kimu
====

Overview

##Description
Light the LED with my Raspberry Pi. I wrote the device driver in my Raspberry Pi.
If I write 1 to the myled0, turn on the LED, and if I write 0 to the myledo, turn off the LED.


##Demo
Please look at this site. You can see the operation.
https://youtu.be/IJDaOOR2aKs

##Requirement
After you clone my site, wirte 'make' in your commandline.
And next, write these commands.

sudo insmod mylied.ko
chmod 666 /dev/myled0
echo 1 > /dev/myled0     # If you want to turn off LED, change '1' to '0'.

Finally, you can finish the work for writing this command.

sudo rmmod myled


Tanks.
