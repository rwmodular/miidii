## Support for 2 just friends modules:
You can now connect 2 just friends modules to your miidii module.
- Connect just from jf module you want to be number 2
- Use the miidii web config tool to set it to address 2
- Connect your other jf module
- Use the miidii web config tool to add the second device and configure midi ports

Note: Turn off your eurorack system when plugging and unplugging power or i2c cables!

New config tool is here until release - https://random-works.co.uk/modules/miidii/configure_new.html

## Support pitch bend:
+/- 2 semitone pitch bend while notes are held.

## JF Run CC control:
Use midi CC 16 to control just friend's run value - 0 to 64 map to 0v to 5v, 64 to 127 map to 0v to -5v.

## Support midi running status:
Running status lets you send multiple midi messages of the same type without specifying the type each time. 

Rather than sending a Note On message for each note in a chord you can send the first Note On message and then just the note information for other notes.

Devices such as the M8 tracker use running status and so would only trigger the first note when sending a chord to miidii.

## Note On 0 Velocity:
Some devices send a midi Note On message with a velocity of 0 instead of a Note Off message.
These are now treated as Note Off.

## Turn all voices off on switch up:
If you move the switch on miidii to the up position, all just friends voices will be turned off.

This can be handy if you ever get a note stuck on.

## Support midi CC 'all notes off':
Another helper for stuck notes - clicking Stop in your DAW should send an 'all notes off' message.

## Don't set synth mode when powering on with switch up:
When powering on with the switch in the up position miidii would put Just Friends into synth mode.

It now doesn't send any messages to Just Friends when starting in the up position.
