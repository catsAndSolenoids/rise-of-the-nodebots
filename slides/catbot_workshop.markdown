# Nodebots, the begining

<img src="imgs/lzc.png" alt="" class="noBrd lzc">

> A story including Arduinos, Node.js, and more ...

Made with love by

- [NodebotsUK](https://twitter.com/NodeBotsUK)
- [Zhi Zhang](https://twitter.com/zhizh2)
- [Les Nodebots](https://twitter.com/lesNodebots)




# Arduino

Arduino is an open source development platform, it make thing blinks and move !

<img src="imgs/arduino.png" alt="" class="noBrd board">

# Node js

 if you don't know what node.js is

> the Visual Basic conference is in another castle


<audio data-autoplay src="audio/smbF.mp3"></audio>

# Perfect match ?

- arduino
    - small processing power (ATmega328 @ 20MHz)
    - electric I/O
    - sensor / hardware extensions
    - http module far from perfect
- node.js
    - fast, scalable
    - non blocking I/O
    - know a thing or two about the internet

# Nodebots \o/

the best of both world ! by using arduino you can empower node with sensors and actuators to interact with the physical world
##MAGIC ?
there is a bit of voodoo involved but not the way you think ...

## firmata
To expose the guts of your arduino over serial communication we use firmata an arduino C sketch

## Serial port is voodoo magic
small MCUs more efficient way to communicate with the outside world is serial port comunication Chris Williams, [@vodootikigod](https://twitter.com/voodootikigod) gave us node-serial port ...

## Johnny-Five is the roseta stone
serial port is really efficient, but is about sending and receiving bytes, buffers are perfect for that etc etc, but still a little abstraction is welcome
J5 offert a convenient api to talk to MCUs or other prototype boards in an unified maner
