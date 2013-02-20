LUDI
- Video Game Console
- Uses arduino + TV-OUT library to function
- 2 NES Controllers (Buy from Parallax website ~$5/controller, ~$3/connector
- Games played through arduino on plug-in cartridge
	- cartridge handles the game, console handles graphics/controller/etc.
	- save games on cartridge itself
- Simple stepping-stone into higher-end graphics and better capabilities
- Focus on easily reprogrammed
	- Chip communication is through the cartridge slot, so can be programmed there
- Turning on
	- Power indicator light
	- Power indicator light for cartridge
		- Different color
	- Shows LUDI and some icon (a tent or something)
	- Plays startup sound
	- Shows extra animation if a game is inside + normal sound
	- If no game, allows you to edit settings
		- Change brightness, calibrate volume, etc.
- Custom PCB
	- Batch PCB fabrication
	- Fabricate console & 2+ cartridges
- Enclosure
	- Slot for cartridges to be plugged in
	- NES controller connector breakout so pluggable from front of case
	- External indicator light
	- External reset button
	- Logo/Name, also etch model number, etc.
- Video/Audio
	- Arduino TV-Out Library
		- has built-in sound output (make it mono)
- Steps
	1. Research
	2. Breadboard
	3. Custom PCB
	4. Enclosure
