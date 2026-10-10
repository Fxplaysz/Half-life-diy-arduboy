# Half-life-diy-arduboy
Hello everyone, this is my repository for my diy arduboy. Here you'll find the pcb and the 3d models later on.
I have made this DIY arduboy because i like mini handheld game consoles and electronics. This DIY Arduboy is very easy to build and can be made by anyone easily.

Aruduboy is a open source game console made by Kevin Bates. He has opensourced his console and made it easier for anyone to build it and have fun with it. I remember a few years back i tried making it by myself but i failed in doing so because of the technicalities in building it. So i've decided to make this project to let anyone make a DIY Arduboy easily and have fun while doing it.

It was made using KiCad and with the help of the internet. 
I made it in 2 days in the span of 5 hours in the 2 days.

# Features
* 0.96 SPI OLED display
* ISP pins for easy programming
* Buzzer for audio
* Flash chip to store more then 500+ games
* RGB LED
* *Silent* SMD push button switches. Good for long term gaming.

# Instructions
* Flash [Arduboy bootloader](https://github.com/MrBlinky/Arduboy-homemade-package) using the ISP header and a [usb asp](https://robu.in/product/usbasp-avr-programming-device-for-atmel-proccessors/)
* Upload games using the cart builder from MrBlinky [Arduboy-Python-Utilities](https://github.com/MrBlinky/Arduboy-Python-Utilities)
* Start Playing with it!

  - *More detailed instructions will be uploaded later*
    
# Photos
These are some of the photos of my PCBs.
1) PCB with smd mounted flash chip.


2) PCB with support for flash module.
- Front
<img width="3840" height="2186" alt="diy_ardubo_flash_module_front" src="https://github.com/user-attachments/assets/f3535148-e598-4108-a012-1e93b0d5f3e3" />
- Back
<img width="3840" height="2186" alt="diy_ardubo_flash_module_back" src="https://github.com/user-attachments/assets/c00e67e3-2333-48e1-8a47-286b854b5144" />

* PCB Lay out
  <img width="1365" height="767" alt="image" src="https://github.com/user-attachments/assets/112b147f-992c-47db-8961-e1de0c638cd7" />

  
   - [DIY Arduboy with Flash Module support](https://github.com/Fxplaysz/Half-life-diy-arduboy/blob/main/diy_ardubo_flash_module.pdf)
   - [DIY Arduboy with SMD flash chip](https://github.com/Fxplaysz/Half-life-diy-arduboy/blob/main/diy_ardubo.pdf)

The flash module version supports the addition of a flash module instead of using smd flash chip. Its mainly through hole components making it easier to build and use it.

The SMD version is a little slimmer then the flash module version but its hard to solder without hot air gun. So the choice is yours to build. 

Anyone Interested in building it can check my [BOM list](https://github.com/Fxplaysz/Half-life-diy-arduboy/blob/main/BOM.md). Feel free to ask questions.
Have fun everyone!


**Firmware Credit:** The test firmware used for this project is [Back to the Jungle](https://github.com/eried/ArduboyBackToTheJungle) created by **eried**.



* **Arduboy community:** https://community.arduboy.com/

* **Arduboy:** https://www.arduboy.com/
