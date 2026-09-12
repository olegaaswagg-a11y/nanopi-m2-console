# NanoPi M2 Console image

Cloud-built diagnostic console image for the original FriendlyARM NanoPi M2
(PCB revision 1602, Samsung S5P4418, 1 GiB DDR3).

The first milestone deliberately keeps FriendlyELEC's known boot chain and
kernel. It adds a local boot-complete screen and serial diagnostics so hardware
compatibility can be verified before RetroArch and the final game launcher are
added.

## Build

Open **Actions**, select **Build NanoPi M2 diagnostic image**, and choose
**Run workflow**. The resulting compressed SD-card image is published as the
`nanopi-m2-diagnostic-image` artifact.

## Test

Extract the artifact and flash the `.img.gz` file with balenaEtcher. Boot with
only microSD, HDMI and a 5 V / 2 A power supply attached.

