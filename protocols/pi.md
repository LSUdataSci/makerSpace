## Raspberry pi Zero W starter kit

This is a collection of resources as you start your journey setting up the Raspberry pi Zero W. This is a microcomputer capable of running a basic linux-based operating system off of a microSD card. The computer is smaller than a deck of cards (by a lot), but is a fully functional computer, complete with wi-fi, an OS, etc. etc. Below are some helpful guides for setting up your Raspberry pi and starting to develop some appreciation for what the pi can do. 



![pi zero](https://cdn.sparkfun.com/r/500-500/assets/parts/1/2/2/3/2/14277-01.jpg) 




### Raspberry pi Zero W setup

+ [raspberry pi setup on YouTube](https://www.youtube.com/watch?v=TUz2mVtJVsM)

+ [text-based tutorial from SparkFun](https://learn.sparkfun.com/tutorials/getting-started-with-the-raspberry-pi-zero-wireless/all)

+ [getting started and specs](https://www.tomshardware.com/features/raspberry-pi-zero): really great guide and setup that gives inforamtion on GPIO, hats, and much of the information further along in this document

+ [the official quickstart guide](https://www.raspberrypi.org/magpi-issues/QuickStart_v1.pdf)



### Connecting to wifi

This is actually harder than it should be with LSU's eduroam. Grant Foster wrote a [nice tutorial on this](LINK TO TUTORIAL) though. 

If you are not connecting to campus `eduroam`, please see [this guide](https://learn.sparkfun.com/tutorials/getting-started-with-the-raspberry-pi-zero-wireless/all#connecting-to-wifi) 




### GPIO 

The GPIO are the set of 2x20 holes in the pi board itself that allow peripheral connections. Each one of these holes corresponds to a different ability in terms of power, etc. 

![labeled pi zero](https://www.seeedstudio.com/blog/wp-content/uploads/2019/10/r4.png)


![GPIO pi zero](https://othermod.com/wp-content/uploads/button.jpg)


However, you won't necessarily have to worry too much about this unless you want to. This is because folks have designed what are referred to as `hats` or `bonnets` which sit on top of the 2x20 pin connection and have internal drivers to do the thing for you, essentially. An example of this is the [RGB matrix hat](https://learn.adafruit.com/adafruit-rgb-matrix-bonnet-for-raspberry-pi/), which we have and you may access.



















