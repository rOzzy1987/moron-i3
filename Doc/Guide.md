# Moron i3 Assembly Guide

## Frame
Prepare the extrusions following the [drawings](2040-drawings.pdf)

Note that both holes of both ends need to be tapped M6 on `2040-300` and `2040-400-bottom` parts

The frame building is up to you, but generally [blind joints](Blind.png) are preferred.

### Parts
| Quantity | Name                     |
|---------:|--------------------------|
| 1        | 2040-300                 |
| 2        | 2040-300-bottom          |
| 2        | 2040-400-horizontal      |
| 2        | 2040-400-vertical        |
| 12       | BHCS M6x15mm             |
| 4        | BHCS M6x30mm             |
| 4        | Rubber Foot - 20x12mm    |
| 4        | SHCS M4x8mm              |
| 4        | T-Nut-M4                 |

### Assembling
![img](frame.png)

## Bed rail holders
### Parts
| Quantity | Name                     |
|---------:|--------------------------|
| 2        | 8mm Linear Axis - 410mm  |
| 4        | Y Rod Holder             |
| 4        | SHCS-M3x8                |
| 4        | Nut-M3                   |
| 8        | SHCS-M4x8                |
| 8        | T-Nut-M4                 |

### Assembling
> **Note**
You will need 4 of these parts.

![img](Y_holder.png)

## Y Belt system
### Parts
| Quantity | Name                     |
|---------:|--------------------------|
| 1        | Y Motor Holder           |
| 1        | Y Tensioner Arm          |
| 1        | Y Tensioner Base         |
| 3        | SHCS-M3x25               |
| 4        | SHCS-M3x8                |
| 3        | Nut-M3                   |
| 8        | SHCS-M4x8                |
| 8        | T-Nut-M4                 |
| 1        | Nema17 Stepper           |
| 1        | 2GT 20 Teeth Idler       |
| 1        | 2GT 20 Teeth Wheel       |

### Assembling
![img](Y_belt.png)

## Bed
### Parts
| Quantity | Name                     |
|---------:|--------------------------|
| 1        | Y Bed Carriage           |
| 1        | Y Belt Clip              |
| 1        | Y Belt Clip Cap          |
| 1        | Nozzle Brush Holder      |
| 1        | Bambulab nozzle brush    |
| 4        | LM8UU Linear Bearing     |
| 1        | 220x200 MK3 Heated Bed   |
| 4        | SHCS-M3x30               |
| 4        | Bed springs              |
| 4        | Bed adjuster nuts        |
| 6        | SHCS-M3x12               |
| 6        | Nut-M3                   |
| 4        | Zip ties                 |


### Assembling
Fix the LM8UU bearings in place by wrapping a zip tie around them through the adjacent holes.

If you don't have the means to print the bed carrier, you can just get a piece of plywood you'll fix the bearings to. I used a laser cut plywood base for my build and it works just fine.

![img](Bed_core.png)

## Z axis
### Parts
| Quantity | Name                     |
|---------:|--------------------------|
| 8        | SHCS-M3x8                |
| 2        | SHCS-M3x10               |
| 2        | Nut-M3                   |
| 10       | SHCS-M4x8                |
| 10       | T-Nut-M4                 |
| 1        | Z Motor Mount L          |
| 1        | Z Motor Mount R          |
| 1        | Z Rod Holder L           | 
| 1        | Z Rod Holder R           | 
| 2        | 8mm Linear Axis - 325mm  |
| 2        | T8 Leadscrew - 300mm     |
| 2        | 8mm To 5mm Shaft Coupler |
| 2        | Nema17 Stepper           |

### Assembling
![img](Z_axis.png)

## X Gantry
### Parts
| Quantity | Name                     |
|---------:|--------------------------|
| 1        | X Belt Tensioner         |
| 1        | X Carriage               |
| 1        | X Drag Chain Mount       |
| 1        | X Gantry L               |
| 1        | X Gantry R               |
| 1        | Dragonburner Mount       |
| 2        | T8 Leadscrew Nut         |
| 1        | 2GT 20 Teeth Idler       |
| 1        | 2GT 20 Teeth Wheel       |
| 8        | LM8UU Linear Bearing     |
| 5        | M3x4x5 Heat Set Insert   |
| 4        | SHCS-M3x10               |
| 1        | SHCS-M3x16               |
| 8        | SHCS-M3x20               |
| 2        | SHCS-M3x25               |
| 11       | Nut-M3                   |
| 2        | Washer-M3                |
| 2        | 8mm Linear Axis - 350mm  |
| 1        | Nema17 Stepper           |

### Assembling
If you have problems with the gantry not going low enough for your bed setup, you can print the gantry end parts mirrored and 
use them in an upside-down configuration. Or just use these and move the X motor to the right side.

![img](Gantry.png)

## Power
### Parts
| Quantity | Name                     |
|---------:|--------------------------|
| 1        | AC Box                   |
| 1        | PSU Mount                |
| 1        | LRS-350-24 PSU           |
| 3        | BHCS-M4x6                |
| 7        | SHCS-M4x8                |
| 7        | T-Nut-M4                 |
| 1        | IEC C14 connector        | 

### Assembling
> **WARNING** 
Be sure to have the wiring attached and the box fixed to the desired position on the frame before clicking in the IEC socket! 
Once clicked in, the screws and wiring is inaccessible and there's no easy way of unclipping the socket!

![img](Power.png)

## Control box
### Parts
| Quantity | Name                     |
|---------:|--------------------------|
| 1        | Control box              |
| 1        | Control box lid          |
| 6        | M3x4x5 Heat Set Insert   |
| 6        | SHCS-M3x8                |
| 3        | SHCS-M4x8                |
| 3        | T-Nut-M4                 |
| 1        | Raspberry Pi             |
| 1        | Mellow FLY D5            |

### Assembling
Use whatever means you have to secure the boards without shorting anything. You can use screws screwed into the plastic, 
or have heat set inserts after drilling, whatever you prefer.

![img](Control.png)

## Spool holder
### Parts
| Quantity | Name                     |
|---------:|--------------------------|
| 1        | Spool Holder             |
| 2        | 2x4mm PTFE Tube - 75mm   |
| 4        | SHCS-M4x8                |
| 4        | T-Nut-M4                 |
### Assembling
![img](Spool.png)

## Final assembly
### Parts
| Quantity | Name                     |
|---------:|--------------------------|
| 1        | X Drag Chain Fixed       |
| 1        | SHCS-M4x8                |
| 1        | T-Nut-M4                 |
| 1        | 7x7mm closed drag chain  |

\+ All parts previously assembled
### Assembling
For fixing the drag chain, the same applies as for the control boards. Use whatever you have/feel like.

![img](Final.png)

# Done
You should now have a complete printer! (Without a toolhead)

Well done!

![img](Complete.png)