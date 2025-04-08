![Showcase](pcb.jpg)

<div align="center">

## Raspberry Pi Pico/W Breakout MUX Board

This PCB designed in KiCAD allows a Raspberry Pi Pico W, or normal version, to communicate with 8 I2C devices that have matching addresses. This board is based on breakout muiltiplexers sold by [Adafruit](https://www.adafruit.com/product/5626) and [SparkFun](https://www.sparkfun.com/sparkfun-qwiic-mux-breakout-8-channel-tca9548a.html).

</div>

---

## Arduino and CircuitPython
This breakout board works with either Arduino or CircuitPython.
> [!NOTE]
> For CircuitPython, I would recommend using the [libraries created by Adafruit for TCA9548a MUX use](https://learn.adafruit.com/adafruit-pca9548-8-channel-stemma-qt-qwiic-i2c-multiplexer/circuitpython-python).
>
> The main connection are
> SDA: GP4
> SCL: GP5
>
> MISO: GP16
> MOSI: GP19
> CLK: GP18
> CS: GP17
>
> Neopixel: GP6

---

## Creating and Changing this Design
1. Download the zip of this repo or clone it

2. Open the KiCAD project file.
> [!NOTE]
> This project was updated to KiCAD 9.0.

3. Examine and understand the schematic and PCB layout
> [!NOTE]
> The 3D models for the certain compnenemtsn might need to have their file path updated and their 3D models posistion adjusted to appear correctly on your PC.

4. Use your preferred PCB manufacture to order the PCB
