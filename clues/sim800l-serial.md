## SIM800L GSM module serial port troubleshooting

### Check serial port parameters
Baudrate 115200, 8N1 (8 bit, no parity, 1 stop bit).

### Cables
* RX of SIM800L goes to TX on Pi
* TX of SIM800L goes to RX on Pi
* No need for any other cables between SIM800L and Pi
* SIM800L should be safe to use with Pi's 3.3V TTL level
* No pull-up resistors needed

### Power
* SIM800L momentarily need lots of power, 2amps+capacitor.
* SIM800L requires 3.6-4.2V to work (5V will kill it)
