This repository contains supporting materials for the upcoming tasks to be completed before the Shinewave Kickstarter.

Shinewave is a project aimed at competitive Super Smash Bros players that seeks to modify and improve GameCube controllers with programmable LEDs and various USB functionalities. The electronics and firmware have already been prototyped and are showcased on my blog at [Electric Exploits](http://electricexploits.net/).

However, official clear controller backs(necessary to see the LEDs) are difficult to find, tend to be in used condition, and cost about $40 each. Therefore, I hope to produce my own replica of the official injection molded backs.

Since I will have full control over the new model, I hope to include several modifications that will make assembly easier and allow for easy USB connections.

# Contents

| Folder                   | Contents                                          |
| ------------------------ | ------------------------------------------------- |
| `./controller-model`     | Rough 3D scan of a GameCube controller back       |
| `./shinewave-board/main` | Schematics and board for the main Shinewave PCB   |
| `./shinewave-board/leds` | Schematics and board for each LED                 |

# Todo

## Produce injection molded clear backs

It is the most important to produce a piece that mates well with the official top half of the shell, so that the two pieces join together seamlessly. The controller has a lot of odd curves in its geometry, so this may be difficult.

I tried taking a 3D scan of the controller back with a NextEngine desktop scanner, but the scan quality wasn't too great. I uploaded it anyways, because it may be a good place to start.

Additionally, there are several modifications that I would like to make to the base model.

## PCB mounting points

As it stands, I have been either hot gluing parts into the case, or letting wire tension keep them in place. This works fine for small scales of production, but would error-prone in larger quantities.

I would like to include some mounting mechanism for the main PCB, and each of the five LED PCBs. I'm not sure what kind of mounting mechanism would be injection-molding friendly.

In the album below, I've marked the approximate mounting point locations. The LEDs are marked by X's, while the Shinewave PCB is marked by the rectangle on the back. Additionally, the USB port is the filled inner rectangle on the back.

[PCB Mounting points](http://imgur.com/a/13wrS)

## USB access

In order to use the controller as a USB joystick, update the firmware, or modify the LEDs without disassembling the controller, a microUSB port in the back would be necessary. The port would be orthogonal(probably) to the main Shinewave PCB, which will have a right-angle microUSB connector, similar to [this](http://www.mouser.com/ProductDetail/Hirose-Connector/ZX80-B-5S/?qs=XQjbzJWzFPUrLcP5tM9rJg%3D%3D).

## Misc

Finally, I would like to get an opinion on the following tasks

 * Choosing good board to board connectors, and finding a source for the custom length wires
 * Finding a medium-run manufacturer to do production and PCB assembly, and getting a quote
