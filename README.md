# ElWiz

## Fork of ElWiz by iotux

This fork is re-written for the Aidon Meter and it can handle Pulse-flows with Current #2 included or excluded.

I have also added a text-file with meterId and "power"-factor in order to correct the reading when readout values have to be multiplied by a factor. This is normally found on a separate label on the meter (presumably only used in industrial environments).
The meter.txt file is organized with each line containing the following:

If the *meter.txt* file is missing the power factor will be set to 1.

**meterId[tab]powerFactor[tab]Comment**

Lines starting with **#[tab]** are ignored.

One small note:

I have not handled the small "bug" in line xx:

**if (topic === "tibber") {**

This topic text have to match the content of config.yaml !

Here is the link to the **real** ElWiz: https://github.com/iotux/ElWiz
