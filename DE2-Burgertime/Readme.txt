Burgertime Arcade for the Altera DE2-35 Dev Board.

Notes:
Controls are PS2 keyboard, see readme file in de2 folder for instructions.
Use the included SRAM loader project to load burgertime program prom code to DE2 SRAM.

Build:
* Obtain correct roms file for burgertime, see make burger time proms script in tools/burger_time_unzip folder for rom filenames.
* Unzip rom files to tools/burger_time_unzip folder.
* Run the make_burger_time_proms script in the tools/burger_time_unzip folder.
* Place the burger_time_prog.vhd prom file inside the burgertime_sram_loader folder (see readme file inside the folder).
* Compile and program the Burger time sram loader project into DE2-35. (see readme file in sram loader folder).
* Open the burger_time_de2 project file using Quartus and compile.
* Program DE2-35 Board.
