# spycam

## About

The goal of this project is the unnoticed photographic capture of any larger mammals (including humans!) passing a certain area.
However, the result should mainly focus on human visitors, thus wildlife-cams are no option, since their IR-LEDs can be spotted in very dark environments.

## Philosophy

- low cost
- low maintainance
- long durability

## Hardware

- low cost smartphone (bluetooth, wireless broadband, android)
- motion sensor (bluetooth)
- cloud/email server

## Software

The android device should sleep by default.
As the motion sensor is triggered, the smartphone should start up and take a picture.
Once the picture is taken, it should be uploaded to a cloud/email server via wireless broadband.
This step is necessary to prevent the data from being lost or stolen.
With the target moving out of the frame, the android device should be put back to sleep mode, waiting for another trigger.

## TODO

- choose low cost smartphone
- choose motion sensor
