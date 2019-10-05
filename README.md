# lorawan-poe-relay-watchdog
Simple LoraWan device to serve as a watchdog for remote reboot of gateways and other networking equipment

# Key features
 * Send a device status update at a defined interval
 * Receive a remote command for reset

## Device specification:

 * LoRaWAN connectivity
 * NFC for config/fw upgrade (optional)
 * Ethernet port in/out
 * Relay to switch off the pair carrying power 
   * basic relay if pair is not arrying data works 100Mbps solution
   * otherwise use an RF relay, for example https://eu.mouser.com/Electromechanical/Relays/High-Frequency-RF-Relays/_/N-5g31?P=1z0x0em
 * Measure current (if simple enough to implement only)
 * Supercap for devices own power, charged from PoE

