# Facebox

DIY portable photo booth. 
Uses a Raspberry Pi, a camera and a thermal printer. 

> This project was made in 2014 and a lot of the equipment has evolved since. You could probably use a smaller (and cheaper) Raspberry Pi for example. Also, Adafruit has expanded its range of thermal printers (see thermal printer guts: https://www.adafruit.com/product/2753 and nano printer: https://www.adafruit.com/product/2752). 

##Basic behavior 

1. Plug in power 
2. LED switches on when ready 
3. Press button 
4. LED blinks - get ready ! 
5. Picture is taken (LED switches off) 
6. Picture prints 

( ͡° ͜ʖ ͡°)

Press the LED longer to swith power off. 

See a demonstration here: 

[![ScreenShot](/assets/images/facebox_vid_cap.png)](https://youtu.be/IuZUDrAImiY)

##Bill of Materials 

- Rasberry Pi http://www.adafruit.com/products/998 39.95$
- Rasberry Pi camera http://www.adafruit.com/products/1367 - 29.95$
- Thermal printer (Adafruit) - http://www.adafruit.com/products/597 - 49.95$ 
- (starter pack : http://www.adafruit.com/products/600) 61.95$ 
- 5V / 3A power supply (the one with the kit is not enough, we had to plug 2 2A chargers in parallel for it to work, the printer takes a lot of juice when it prints) http://www.adafruit.com/products/1466 15$ 
- button with LED https://www.adafruit.com/products/1479 1.95$
- Thermal paper 2$ 2.25” 
- Mini-magnets x8 - 2.5$ http://addison-electronique.com/catalog/product/view/id/15030/s/paquet-de-10-aimants-8mm-x-3mm-rare-earth/category/388/ 

Total estimated : 160$ 

You'll also need : 

- Access to a 3D printer 
- A soldering iron 
- Basic understanding of how electronics work 

##The 3D printed casing 

The casing has 5 parts: 

- The base 
- The top half of the head 
- The bottom part of the head 
- The mouth 
- The eye 

![Looped GIF](/assets/images/Facebox_loop.gif)

#Possible ameliorations 

[] Easier way to change text on image (ideally in a config.txt file) 
[] Better 3D file for base that supports the thermal printer 
[] 3D files for new Adafruit thermal printer guts (should allow for slimer version) 
