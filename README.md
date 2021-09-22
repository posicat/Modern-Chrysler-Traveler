# Modern-Chrysler-Traveler
A replacement PCB and Code for the Traveler computer from the Chrysler Lebaron, adding new features while keeping the same asthetic.

PCB : 

Goals of this Project:
	Replicate original Traveler Functions
		DTE (MI or KM)
		ODO
		ECO (MPG , L/100 km)
		ECO AVG (MPG , L/100 km)
		
		Sequence : 
			F 1-1 (No data)
			0.0 MI ODO
			0.0 AVG MPG ECO
			0 MPG ECO
			0 MI DTE
			0:00 ET
		
	Add new Functions
	
		MPG
		Gal Remaining
		Trip Mileage
		
		Engine Temp
		Trans Temp
		
	Radio Control
		Aux Audio for Infinity I-III
			2 inputs for front panel Aux, and Bluetooth Connections
		Emulated CD Changer for 1.DiscUP Radio
			Customizable Which DISC number so it can coexist with an existing CD changer
			
		Find and figure out the 3rd radio type for the other CD Changer??
		
		
	Web Interface
		To any engine PID 
		To Traveler Data
		For Radio settings
		
Links
	CCD/PCI Interface board : https://www.tindie.com/products/boundarycondition/ccdpci-bus-transceiver-development-board/
	MBUS Arduino : https://github.com/picohari/atmega128_alpine-mbus-emulator
	Sequence : https://www.justanswer.com/car/1di0n-1990-chrysler-lebaron-convertable-evic-traveler.html
	

Keywords/Search Words
	Chrysler Infinity Radwood Radio AUX pinout pin-out DIN8 din-8 M-BUS CD player CD changer
	LeBaron Traveler Computer Wifi ESP ESP8266 