# midi-monitor

A simple MIDI monitor

## Getting Started

### Prerequisites

In order to use this application, you will need a [MIDI-USB interface](https://google.com/search?q=midi-usb+interface&tbm=isch) 
or a MIDI controller with embedded MIDI-USB interface, like the [TinyBox](https://www.tinybox.rocks)

### Installing

* Mac installer : [MIDI-monitor-1.0.1.dmg](https://github.com/ossandust/midi-monitor/releases/download/v1.0.1/MIDI-monitor-1.0.1.dmg)
* Windows installer : [MIDI-monitor-Setup-1.0.1.exe](https://github.com/ossandust/midi-monitor/releases/download/v1.0.1/MIDI-monitor-Setup-1.0.1.exe)

## Screenshot

![screenshot](http://fcb1010.eu/img/monitor_screenshot.png)

    1 : Selected MIDI IN port                  2 : Selected MIDI OUT port

    3 : List of incoming MIDI messages         4 : List of outgoing MIDI messages

    5 : Clear button for the MIDI IN listview  6 : Clear button for the MIDI OUT listview

    7 : Incoming Clock/ActiveSense indication  8 : Outgoing Clock/ActiveSense indication

    9 : MIDI THRU function = forward all incoming MIDI messages to the MIDI OUT port
  
    10: Send button to transmit a MIDI message to the MIDI OUT port
    
    11: MIDI message selection : specify any MIDI message to be sent to the MIDI OUT port
  
    


## Author

* **Xavier De Donder** - aka *Ossan Dust* - [FCB1010.eu](https://www.fcb1010.eu)

## Acknowledgments

* This application is built on top of the [Electron](https://www.electronjs.org/) framework
* It uses the splendid [RtMidi](https://www.music.mcgill.ca/~gary/rtmidi/) platform independent MIDI library - Copyright (C) 2011-2015 by Justin Latimer
* along with wrappers [node-midi](https://github.com/justinlatimer/node-midi) - Copyright (C) 2011 by Justin Latimer
* and [node-easymidi](https://github.com/dinchak/node-easymidi) - Copyright (c) 2019 Tom Dinchak 
