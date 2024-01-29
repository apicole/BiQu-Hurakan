Please find in this Repo, the information relevant to BiQu Hurakan.

1- you can putty to your Hurakan with biqu:biqu as much as with root:root

2- H2 extruder install needs some tweaking in the file generic-bigtreetech-hurakan-m4p.cfg, this is the one shared here.

3- I have set mAcros to reflect the temperature, both in screen and hotend_rgb - see START_PRINT and END_PRINT CANCEL_PRINT macros in printer.cfg file
  it basically uses commands     SET_LED LED="mini12864" RED=0 GREEN=0 BLUE=1 SYNC=0 TRANSMIT=1 /  SET_LED LED="hotend_rgb" RED=0 GREEN=0 BLUE=0 SYNC=0 TRANSMIT=1

4- Include a camera over the USB port and run timelapse within timelapse.cfg. Include in the first lines of printer.cfg : [include timelapse.cfg]
