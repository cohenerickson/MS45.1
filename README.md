# MS45.1 DME Tuning

Maps, Definitions, and Documentation for MS45.1 Tuning on my 2004 325Ci

This repo is not meant to copy or replace the MS4x Wiki or any other resources that are linked, but simply just as a personal documentation of the tuning process for my vehicle.

## Resources

Most of the information here comes from the [MS4x Wiki](https://www.ms4x.net/) and the [MS45.1 Tuning Thread on e46fanatics](https://www.e46fanatics.com/threads/siemens-ms45-1-tuning-thread-xdfs-inside.1269619/page-2?nested_view=1). Any other external resources will be linked within their respective folder.

## Software

### Flashing

To read, and flash tunes to the ECU you will need software comaptable with the MS45.1. I use [MS45.1 QuickFlash](https://www.bimmertuningtools.com/product/ms45-quickflash/) however there are other options out there which are documented on the [MS4x Wiki](https://www.ms4x.net/index.php?title=Siemens_MS45#Flashing_software).

### Firmware Update

In order to update the firmware you will need WinKFP which is included in [BMW Standard Tools](https://www.e46fanatics.com/threads/installing-bmw-standard-tools.1322014/), A package put together by [Bali from e46fanatics](https://www.e46fanatics.com/members/bali.219532/). Installation details can be found in the link above.

## Hardware

For most communication with the car you will need a K+D CAN cable such as [this](https://www.amazon.com/Taotao-FT232RQ-Interface-Ediabas-Diagnostic/dp/B07L498NGZ/) one.

If coding out airbags with PA Soft you will also need a PA Soft cable which can be purchased [here](https://www.amazon.com/AMHTDOL-Scanner-Programmer-Programming-Diagnostic/dp/B0CFPW2F2N/).

## Order

Each tune is based off the previous in the following order, documentation is provided at the respective links

- [Base Tune](./base)
- [457LO02S Firmware Update](./firmware)
- [Immobilizer Delete](./immo)
- [Speed Limiter Delete](./vslimiter)

## Future Goals

- SAP Delete
- Cat Delete
- Exhaust Pops
- E85
- 3L Stroker
- Forced Induction
