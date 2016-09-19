# #244 DPDT Toggle Switches

All about double-pole, double-thow toggle switches.

![DPDT_part](./assets/DPDT_part.jpg?raw=true)

## Notes

A double-pole switch controls two circuits with a single action.

The double-thow nomenclature indicates that each circuit can be switched between two states.

### Example Part: DPDT 2.54mm pitch Switch

Product example: [8x8mm Self-locking Push Button Switch](http://www.aliexpress.com/item/8x8mm-Self-locking-Type-Square-Button-Tactile-Push-Button-Switch-Momentary-Tact-DIP-Through-Hole-4pin/2036527668.html)

This is a convenient DPDT switch for PCB construction, having a pin pitch of 2.54mm.
Unfortunately, the pin rows are only separated by two pitches (5.08mm), so it is one pitch short of a standard DIP layout.
This means it cannot directly plug into a breadboard and span the centre line.

![DPDT_part](./assets/DPDT_part.jpg?raw=true)

This particular part has the common poles on pins 3 and 6. Other parts may use a different layout.

![DPDT_part_design](./assets/DPDT_part_design.jpg?raw=true)

### Test Circuit

The simple circuit described below demonstrates the DPDT toggle switch.
The reverse polarities on each pole demonstrate the isolation.

Operation:

* when switch is "off" (i.e. not pressed), the red LEDs light on each pole
* when switch is "on" (i.e. pressed), the yellow LEDs light on each pole


## Construction

![Breadboard](./assets/DPDT_bb.jpg?raw=true)

![Schematic](./assets/DPDT_schematic.jpg?raw=true)

![Build](./assets/DPDT_build.jpg?raw=true)

## Credits and References
* [Switches](../)
* [Switch](https://en.wikipedia.org/wiki/Switch) - wikipedia
* [8x8mm Self-locking Push Button Switch](http://www.aliexpress.com/item/8x8mm-Self-locking-Type-Square-Button-Tactile-Push-Button-Switch-Momentary-Tact-DIP-Through-Hole-4pin/2036527668.html) - example part from aliexpress seller.