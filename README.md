# siemens-simatic-s7-rtpmidi
Minimal rtpMIDI implementation for Siemens Simatic S7 PLCs.  
Originally developed to connect a Behringer X-Touch Exterder Unit to a S7 plc.  
  
The S7 plc acts as a UDP server, listening on port 5004 and 5005.  
The session initiator sends at first an intiation packet to port 5004. If it's answerded with ok it does the same for port 5005 with following sync messages and data messages, containing the MIDI commends.

## Credits
+ https://github.com/lathoub/Arduino-AppleMIDI-Library
+ https://github.com/jdachtera/node-rtpmidi
+ https://github.com/electricityforprogress/BiodataFeather
+ https://github.com/rinaldohack/rtpmidi2midi
+ https://github.com/natcl/node-red-contrib-rtpmidi
+ https://github.com/iKadmium/rtpmidi-to-osc
+ https://github.com/lpmorin/node-red-contrib-rtpmidi
+ https://github.com/Apfelwurm/minivolumidi
