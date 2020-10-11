## M3 BLE Thermometer
![M3_product](/images/M3.png)

# Bluetooth Data Format

It has BLE name as Bluetoth BP and it will send BLE notify data when user has done the temperature scanning.
Data format comprise of 8-BYTE that starting as 
FE-FD-1A-01-01-XX-0D-0A
where XX is the temperature (HEX) ==> convert to DEC ==> 

Temperature = (DEC+256)/10
