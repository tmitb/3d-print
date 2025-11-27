# Sensor box for 170-Tie point bread board
This project is comprised of multiple 3D models to be used with 170-Tie point bread boards that can be easily found in a shopping places like AliExpress. One such item can be found like in the link [170-Tie Point Bread Board](https://www.aliexpress.com/w/wholesale-170%2525252dTie-Point-Bread-Board.html).

The entire idea was born when I needed to create a box for my mmWave presence sensor, such as [LD2420](https://www.aliexpress.com/w/wholesale-ld2420.html). I would like to build a sensor with the least amount of soldering meaning that I need to house some what bulky items in a tidy compact space. When I finished the simple sensor box initially, I naturally wanted add more to the sensor and decided to add Temperature/Humidity sesnor. Having no space at all with the orignal box, I had a choice of creating a entire new design to house both, or create a modular system to extend it as much as I can. After all, you never know what you want in the future, right? Hence the sensor box models are born.

As much as I would like to claim it a modular system, the current state of models are quite lacking in terms of the extendability. I would want to make the entire thing a lot more modular and flexible evetually, however, this is just the begining.

This project is Work-In-Progress and the designs are not finalized. Contributions are welcome.

## Design considerations
The blank box is designed to house the breadboard either flat on the surface or the board side facing the bottom, with enough spaces in either way to have a small MCU module and typical dupont connectors used without much obstructions. The natural shape of the breadboards allow the wires to pass through at the two side to get to the extender or outside without an issue.

The breadboard is meant to be friction fit into the box, though it can also be stick to the top panel using the double sided tape typically comes with the breadboards themselves.

The sensor box itself is not designed to be very durable and that is on purpose because my primary goal is to hide the components from outside and it must be printed as cheap as possible.


## Current models
| Name                | Description                                                                                                                                       |
|---------------------|---------------------------------------------------------------------------------------------------------------------------------------------------|
| blank               | Default box with no other means of access to the internals from outside. This is a useful box to create a enclosed sensor.                        |
| blank-with-use-slot | Default box with a single rectangular slot. The slot is aligned with typical MCU development modules' USB port location.                          |
| extender            | Extension shell to add more space to the box. It can be clipped on to the another module.                                                         |
| extender-with-holes | Extension shell with holes on all four panels. This is designed to provide air flow for sensor modules like temperature/humidity and gas sensors. |
| lid                 | A simple panel with notches to snap into other modules.                                                                                           |

Extender modules have interal lips to the notch side to prevent the breadboard to be moved out of the intended location.

## Current plans
- A space divider to seal off compartments with dupont connector holes to ensure the connection points.
- blank-with-holes

## Known issues
- The tolerance for the notch holes are a bit loose, though the notch themselves snapped into place way too tight, often causing breakage of the notches.

## License
This work adopts CC SA-BY license. Check the License section for more details.
