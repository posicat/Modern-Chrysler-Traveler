# Modern-Chrysler-Traveler
>A replacement PCB and Code for the Traveler computer from the Chrysler Lebaron, adding new features while keeping the same asthetic.

## Resources
 Code : https://github.com/posicat/Modern-Chrysler-Traveler
 PCB : https://oshwlab.com/posicat/modern-chrysler-traveler

## Goals of this Project

### Replicate original Traveler Functions

    ODO (MI or KM)
    ECO AVG (MPG , L/100 km)
    ECO (MPG , L/100 km)
    DTE (MI or KM)
	??? Elapsed Travel
	
Sequence

    F 1-1 (No data)
    0.0 MI ODO
    0.0 AVG MPG ECO
	0 MPG ECO
    0 MI DTE
	0:00 ET
	repeat

### Add new Functions (possibilities)

	Multiple Trip Mileage
	Oil Change Mileage
	Engine Temp
	Trans Temp
	Trip fuel use
	
### Interface for various Chrysler radios

- Infinity I-III
  - Front AUX jack
  - Rear Bluetooth jack
- "1.DiscUp" Radio
  - Emulated CD Changer
  - Selectable disk number for coexistance with changers.
- "Other" type radio
  - Find and figure out the 3rd radio type and implement interface
	
### Web Interface
	To any engine PID 
	To Traveler Data
	For Radio settings
		
## Links

| CCD/PCI Interface board |https://www.tindie.com/products/boundarycondition/ccdpci-bus-transceiver-development-board/ |
| MBUS Arduino |  https://github.com/picohari/atmega128_alpine-mbus-emulator |
| MBUS Arduino |  https://github.com/Olstyle/MBus |
| Sequence | https://www.justanswer.com/car/1di0n-1990-chrysler-lebaron-convertable-evic-traveler.html |
	

Keywords/Search Words
	Chrysler Infinity Radwood Radio AUX pinout pin-out DIN8 din-8 M-BUS CD player CD changer
	LeBaron Traveler Computer Wifi ESP ESP8266 