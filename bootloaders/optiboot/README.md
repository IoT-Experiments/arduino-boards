# Custom Optiboot build

* Checkout [Optiboot repository](https://github.com/Optiboot/optiboot) (tested with #814e2a89bdf54e806c13640bfdead2033bcfad72)
* Copy the custom file named "Makefile.custom" to `optiboot/bootloaders/optiboot`
* Build the hex files with `make atmega328_pro1 BAUD_RATE=7200` and `make atmega328_pro1 BAUD_RATE=3600`

# Binaries

* optiboot_atmega328_pro_1MHz_7200bds.hex : ATmega Pro Mini @ 1Mhz (internal oscillator) @ 7200bds
* optiboot_atmega328_pro_1MHz_3600bds.hex : ATmega Pro Mini @ 1Mhz (internal oscillator) @ 3600bds