# E1DA

## How to download .hex files:
1. Navigate to the .HEX file you wish to download. It should look like this:

![Downloading HEX Step 1](https://raw.githubusercontent.com/staticV3-E1DA/E1DA/main/resources/pictures/save%20HEX/Screenshot%202020-12-31%20170850.png)

2. right-click the "Raw" button and hit "Save link as..."

![Downloading HEX Step 2](https://raw.githubusercontent.com/staticV3-E1DA/E1DA/main/resources/pictures/save%20HEX/Screenshot%202020-12-31%20172046.png)

## Regular Firmware - which one should I choose?!

- `MCLK_12MHz`/`MCLK_25Hz` stands for the DAC's Master Clock. Higher means better Dynamic Range, but worse Distortion.
- after that comes the Nyquist/Oversampling/Reconstruction filter. It's necessary to turn the periodical samples of your music files into a smooth signal.
Filters differ in their impulse response and in high frequency extension. The ES9038Q2M DAC supports the following filters:
  - Linear phase fast roll-off
  - Linear phase slow roll-off
  - Minimum phase fast roll-off
  - Minimum phase slow roll-off
  - Apodizing fast roll-off
  - Hybrid fast roll-off
  - Brickwall
