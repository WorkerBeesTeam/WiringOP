# wiringOP README

This is a modified WiringPi for OrangePi. We call it WiringOP.
Test for OrangePi Zero Plus H5

## Download
### For Orangepi Pi
    git clone https://github.com/lirik90/WiringOP.git -b h5
## Installation
    cd WiringOP
    chmod +x ./build
    sudo ./build

```    
orangepi@orangepi:~$ gpio readall
 +-----+-----+----------+------+---+-Orange Pi+---+---+------+---------+-----+--+
 | BCM | wPi |   Name   | Mode | V | Physical | V | Mode | Name     | wPi | BCM |
 +-----+-----+----------+------+---+----++----+---+------+----------+-----+-----+
 |     |     |     3.3v |      |   |  1 || 2  |   |      | 5v       |     |     |
 |  12 |   8 |    SDA.0 | ALT5 | 0 |  3 || 4  |   |      | 5V       |     |     |
 |  11 |   9 |    SCL.0 | ALT5 | 0 |  5 || 6  |   |      | 0v       |     |     |
 |   6 |   7 |     PWM1 | ALT3 | 0 |  7 || 8  | 0 | ALT3 | TxD1     | 15  | 198 |
 |     |     |      GND |      |   |  9 || 10 | 0 | ALT3 | RxD1     | 16  | 199 |
 |   1 |   0 |     RxD2 | ALT5 | 0 | 11 || 12 | 0 | OUT  | PA07     | 1   | 7   |
 |   0 |   2 |     TxD2 | ALT5 | 0 | 13 || 14 |   |      | GND      |     |     |
 |   3 |   3 |     CTS2 | ALT5 | 0 | 15 || 16 | 0 | OUT  | SDA.1    | 4   | 19  |
 |     |     |     3.3v |      |   | 17 || 18 | 0 | ALT3 | SCL.1    | 5   | 18  |
 |  15 |  12 |    MOSI1 | ALT5 | 0 | 19 || 20 |   |      | GND      |     |     |
 |  16 |  13 |    MISO1 |  OUT | 1 | 21 || 22 | 0 | ALT5 | RTS2     | 6   | 2   |
 |  14 |  14 |    SCLK1 | ALT5 | 0 | 23 || 24 | 0 | ALT5 | CS1      | 10  | 13  |
 |     |     |      GND |      |   | 25 || 26 | 0 | ALT3 | PA10     | 11  | 10  |
 +-----+-----+----------+------+---+----++----+---+------+----------+-----+-----+
 | BCM | wPi |   Name   | Mode | V | Physical | V | Mode | Name     | wPi | BCM |
 +-----+-----+----------+------+---+-Orange Pi+---+------+----------+-----+-----+

 ```    
Thanks!
