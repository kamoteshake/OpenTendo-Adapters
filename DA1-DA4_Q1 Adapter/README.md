# DA1-DA4 Q1 Adapter
DAN601 and uPA64H have been obsolete for a while. It's been difficult to find diode arrays that are close to DAN601 and uPA64H specs wise. It is easier to build an array from multiple single diodes. Since 2SA937 (Q1 in OpenTendo) is close by the diode arrays and is also obsolete, I decided to just include it in this adapter with a newer component that is somewhat close to 2SA937 spec wise.

## Gerber Files
There are two files in [Gerber Files](./Gerber%20Files/):
1. Single Board - Only consist of just one board.
2. Panelized - Consist of multiple board to fit in a 100mm x 100mm board. The panel have 9 (3x3) adapters. It is panelized using mouse bites.

![Panelized](../images/DA1-DA4_Q1%20Adapter%20Panelized.png)

## Assembly Tips
When soldering the pins, to make sure everything is lined up, put the pin through OpenTendo then put the adapter on the pins and tack some of the header pins before pulling it off from the OpenTendo. You can then finish soldering the pins on the adapter then you can solder the adapter to the OpenTendo.

## Images
![Front](../images/DA1-DA4_Q1%20Adapter%20Front.png)
![Back](../images/DA1-DA4_Q1%20Adapter%20Back.png)
![Installed](../images/DA1-DA4_Q1%20Adapter%20Installed.jpg)
