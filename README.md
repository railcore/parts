Railcore II 300ZL/ZLT
=======

RailCore II is a Core-XY based Reprap 3D printer designed by J. Steve White & Tony Akens under the CC-Attribution Only license.

![Railcore](RCII300ZL.png)

## Top-Level Specs
* CoreXY Motion System
* 300x300x300 (ZL) or 300x300x300 (ZLT) build volume.
* kinematically coupled bed plate (optionally)
* autotramming with 3-point bed-leveling
* ~$1700 for a single unit, including hotend. See the [BOM][bom] for the part breakdown
* User Extensible! We encourage extending the design to custom applications via custom tools and bed plates
* Full specs listed on [this page](https://railcore.org)

## Build your own Railcore

The best way to get started is to thumb through the [**Assembly Instructions**](https://railcore.dozuki.com/c/RailCore_II) and [**Bill of Materials**][bom] first. Then, your options are to self-source using the [BOM][bom], or purchase a kit. Kit options:

* https://www.filastruder.com/collections/railcore (US-Based, kits are comprised of exactly the parts on the [BOM][bom])
* https://www.printedsolid.com/collections/railcore (US-Based, kits may not be comprised of the parts on the [BOM][bom])
* https://hightemp3d.com (EU-Based, kits may not be comprised of the parts on the [BOM][bom])

## Repository Contents
* **Aluminum** contains all parts recommended to produce out of Aluminum. The halo and Y-plate are optional, the motor mount and idler mounts are recommended to be made from aluminum, but machined and finished versions are available, see [BOM][bom].
* **Electronics Box** contains DXF files for cutting the Electronics Box. 6mm HDPE is recommended, but other materials are possible.
* **print_tests** contains parts that can be used for testing/tuning a Railcore
* **Printed_Parts** contains all the parts that need to be printed to produce a Railcore. Some, like Z-Brackets and Z-Yokes, are available in aluminum. See [BOM][bom].
* **Resources** contains the font used for the Railcore II 300ZL/ZLT engraving on the panels
* **Upgrade_or_Crossgrade_Parts** contains parts that can be used optionally, for instance doors and a longer electronics box (ZLT only)
* **wiring.png** contains details on all the custom wiring that is used in a Railcore.
* **ZL_Panels** contains DXF files for cutting the side panels. 6mm HDPE is recommended, but other materials are possible.
* **ZLT_Panels** contains DXF files for cutting the side panels. 6mm HDPE is recommended, but other materials are possible.

## Support

Have questions? Building your own Railcore? **[Join the Discord!][discord]**
Lots more information available [here](https://railcore.org)

## Contributing

Railcore is meant to be extended by the community. If you are interested in contributing, there are a number of ways to get involved:

* Review, comment, or add to the **[open issues](https://github.com/railcore/parts/issues)**
* **[Join the Discord!][discord]**

### Open Source
Railcore is licensed under a [Creative Commons Attribution-ShareAlike 3.0 Unported License][cc-by] (CC BY-SA 3.0).
[![CC BY 3.0][cc-by-image]][cc-by]

[bom]: https://docs.google.com/spreadsheets/d/1sxKl6h23SXfuNM7hNiX35rIrpISw8AruEEcNl2Fvibk/edit?usp=sharing
[cc-by]: https://creativecommons.org/licenses/by-sa/3.0/
[cc-by-image]: https://i.creativecommons.org/l/by-sa/3.0/88x31.png
[discord]: https://discord.gg/Sy569Hq
[wiki]: https://railcore.org
