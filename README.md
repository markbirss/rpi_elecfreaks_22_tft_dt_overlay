# rpi_elecfreaks_22_tft_dt_overlay
Device Tree Overlay for using an Elecfreaks 2.2" SPI TFT with a Raspberry Pi

## Wiring
| Raspberry Pi Pin | LCD Pin   |
| ---------------- | --------- |
| GPIO9 (MISO)     | SDO(MISO) |	
| GPIO18           | LED       |
| GPIO11 (CLK)     | SCK       |
| GPIO10 (MOSI)    | SDI(MOSI) |
| GPIO24           | D/C       |
| GPIO23           | RESET     |
| GPIO8 (CE0)      | CS        |
| GND              | GND       |
| 5V 	           | VCC       |
