amt8editor
==========

Ctrlr-based Editor for the AMT-8 midi interface - communicates using over midi using sysex commands.

This panel was made to edit the 32 standalone patches of the Emagic AMT8 midi-interface. These patches are stored inside the unit and are active whenever the interface is not running off a computer.

The panel reflects the state of the selected preset, and features an “initialise” button as found in the original Sounddiver-based editor, routing all inputs to all outputs except its own’s.

The labels displaying the port names can be edited to reflect your setup, so that instead of in/out 1… in/out 8 you can make them display the names of the devices connected to those ports. Just double-click on the name label and name it as you wish.

Currently only the routing matrix + routing initialise per preset is implemented – i still have to decode the filtering matrix messages, i will add those once i figure it out.
All edits are instantly saved to the unit.

Setup:

Select AMT0(all) as midi-output device, input can be any of the 8 ports but one has to be selected for the updating of the panel to work.

ps: I was not able to test this panel on the Unitor because i do not own one, but the messages should be the same as they share the same driver/editing software. The only difference in these models is more capabilities in the Unitor, so i am 99% sure this will work for that device aswell. Should you decide to try this out with a Unitor please let me know how it went (and make a dump of your settings before tinkering)


Big thank you to Roman Kubiak, the developer of the awesome, open-source and cross-platform Ctrlr software!
http://ctrlr.org/ for more info
