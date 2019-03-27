## Raspberry Pi troubleshooting

### Find your raspberry Pi
The last 16 bits of the MAC-address is written on your Pi. The Pi is connected to the local WiFi and has SSH enable. Nmap is your friend.

### I can't reach the Pi any longer and there is no external display
Pull the sd-card from the Pi and mount it on your laptop (Linux). Hopefully you can revert the breaking changes by modifying files on the SD-card.
