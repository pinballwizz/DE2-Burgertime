Procedure:

* Generate burger_time prom files using script in tools/burgertime_unzip folder.
* Copy the burger_time_prog.vhd file into this folder.
* Compile the sram_loader project in quartus.
* Program DE2-35 Board (JTAG). The DE2 SRAM will now contain burgertime prog code.
* 7seg display and green leds can confirm correct hex and binary byte values using switches to select address.
* Without switching off DE2-35, compile the burgertime project in de2 folder and program DE2-35 (JTAG).
