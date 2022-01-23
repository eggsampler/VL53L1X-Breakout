# VL53L1X-Breakout

Minimal VL53L1X / VL53L1CX Breakout PCB developed in KiCad v6.

![PCB Front](etc/v2-pcb-front.png?raw=true "PCB Front")

Images and schematic available in `etc` folder.

Manufacturing output files available in `outputs` folder. Generated with [KiKit](https://github.com/yaqwsx/KiKit) using:

`kikit fab jlcpcb --nametemplate VL53L1CX-Breakout-v2-{} --drc --assembly --schematic VL53L1CX-Breakout.kicad_sch --ignore J1 --field LCSC --corrections JLCPCB_CORRECTION VL53L1CX-Breakout.kicad_pcb outputs`

Approximate cost from JLCPCB for 5 assembled boards is $59 AUD excluding shipping.