## Using ReSpeaker Mic Array on Mac

Python examples for ReSpeaker Mic Array to show how to use it.

Fork from [here](https://github.com/respeaker/get_started_with_respeaker/wiki/Mic-Array).

### Prerequisite
	# Install virtualenv and activate my environment
	pip install virtualenv
	source ./win/bin/activate

### Usage
	python mic_array.py w 0 0x00000003    # change LEDs to waiting mode
	python mic_array.py w 0 0x00008001    # change LEDs to blue
	python mic_array.py r 0               # read current mode of LEDs
	
### [HID protocol](https://github.com/respeaker/get_started_with_respeaker/raw/master/files/protocol-20161028.xlsx)
