# ElWiz
Fork of ElWiz by iotux

This fork is written from the Aidon Meter and it can handle Pulse-flows with Current #2 included or excluded

I have also added a text-file with meterId and "power"-factor in order to correct the reading when readout values have to be multiplied by a factor. This is normally found on a separate label on the meter (presumably only used in indistrial environments).
The meter.txt file is organized with each line containg the following:

meterId<tab>powerFactor<tab>Comment
Lines starting with #<tab> are ignored.
