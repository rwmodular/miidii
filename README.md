# miidii
miidii is a eurorack module that lets you play the manequins just friends module using midi.

see https://www.random-works.co.uk/modules/midi for more information.

### updating the firmware:
if your module has firmware 1.0 or greater:
- power on your eurorack case
- connect a usb cable from the module to your computer
- visit https://random-works.co.uk/modules/miidii/configure.html in the Chrome browser
- click on the 'Enter Firmware Program Mode' button
- drop the .uf2 firmware file onto the new drive that now shows on your computer

otherwise:
- hold the small button on the module circuit board while powering on your eurorack case
- connect a usb cable between the module and your computer
- drop the .uf2 firmware file onto the new drive that now shows on your computer

### resetting the flash:
you can completely clear the flash memory removing the firmware, settings and any tuning tables using the miidii_clear_flash.uf2 file:
- follow the above instructions to update the firmware using the miidii_clear_flash.uf2 file
- after copying the file to the module leave it connected to your computer and wait a few minutes
- when the flash has been cleared it will show up as a drive on your computer again
- copy the desired firmware file onto the module

more details can be found in the manual.
