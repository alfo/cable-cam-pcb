![](http://oshwlogo.com/logos/oshw-logo-outline.svg)

# Cable Cam PCBs

This repository contains the Fritzing source files and PDF exports of the PCBs used in my cable cam project.

The PCB is designed to be single layer, which will mean it is easier to make yourself. However, this does make it larger - so if you plan on ordering one to be made professionally I'd recommend redesigning it be be dual layer.

## Components

### Motor Board

* 5x L293D
* 5x 16-pin IC Holder (e.g. [these](http://www.rapidonline.com/Cables-Connectors/Preci-Dip-110-83-316-41-00110-2-54mm-Gold-plated-IC-Socket-16-Pins-51-8927))
* 6x sets of 4 male locking headers (e.g. [these](http://www.rapidonline.com/Cables-Connectors/CamdenBoss-CTH600-4-2-54mm-Pitch-4-Way-Crimp-Housing-PCB-Connector-Female-22-0058))

### Arduino Shield

* 2x RGB LED Common Cathode
* 1x [RF Receiver](https://www.sparkfun.com/products/10532)
* 6x sets of 4 male locking headers
* 2x sets of 4 female standard headers
* 1x PCB-mount power plug (e.g. [this](http://www.rapidonline.com/Cables-Connectors/Cliff-Electronic-FC68148-DC-POWER-SKT-DC10A-5-5X2-1mm-ANGLED-50-3266))

## Contributing

To contribute to the project, please submit a pull request from a branch with the feature in the name, and only edit the `.fzz` files, not the PDFs - I will do that when publishing a new revision.

Additionally, do not change the version number on either board when editing.