# SwiftFi
WiFi interface for Commodore 128D

This is an attempt at an internal WiFi modem for the Commodore 128D based on the SwiftLink cartridge as described in https://www.commodoreserver.com/BlogEntryView.asp?EID=FA5AE758474345A9A0A7208C7F408538

The PCB's dimensions were tailored for a C128D(DCR) mainboard since this is the only model of C128 I have available.

The PCB is sandwiched between U1 (CIA). Two additional signals need to be routed to this PCB. DOTCLK can be tapped from pin 6 on the expansion port. CS (chip select) can be tapped from (the unused) pin 16 of U3.
