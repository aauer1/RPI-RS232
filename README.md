# RPI-RS232
Dual RS232 extension board for the Raspberry Pi

# Instructions
1. Copy the overlay file into the overlays directory located on the boot 
   partition of your Raspberry Pi memory card.
2. Enable the overlay for the extension board in your config.txt by adding
   the following line at the end of the file:

   dtoverlay=sc16is752-spi0

