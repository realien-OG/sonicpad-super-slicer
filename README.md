# sonicpad-super-slicer
config for using superslicer with the sonic pad for ender s1


SuperSlicer :

Under printer settings | custom G-code | Start G-Code


START_PRINT BED_TEMP=[first_layer_bed_temperature] EXTRUDER_TEMP=[first_layer_temperature] FILAMENT=[filament_type]


under printer settings | custom G-Code | End G-code

END_PRINT

(see START PRINT and END PRINT macros for sonic pad (based on klipper))


settings in superslicer to print remote to the sonic pad

https://github.com/realien-OG/sonicpad-super-slicer/blob/9d4be650b1bedc8e95989d541b4cc709b09f988d/super-slicer-remote-print-config.jpg

