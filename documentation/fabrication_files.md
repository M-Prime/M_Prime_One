# M Prime One fabrication files

This is a document to help you find all the fabrication files in the M Prime One repository, files that are used to produce some of the parts of the printer: the printed parts and the files for laser cutting or routing the frame and the bed.

All the files are located in the `parts` directory of this repository, this file only contains all the links in one place. 

## Printed parts

All the printed parts are under the `parts` directories in the subdirectories that contain the prefix "pp_". There are also some optional parts that you can find in the `parts_optional` directory, including a beta bowden extruder that you can try if you don't want to use the PTSone extruder (however the extruder hasn't been fully tested and we cannot guarantee that it will perform reliably). We provide `.stl` files for the printed parts.

This is the list of the M Prime One printed parts:

* Arduino holder: [pp_arduino_holder](../parts/pp_arduino_holder) 
* Hotend and probe holder: [pp_hotend_and_probe_holder](../parts/pp_hotend_and_probe_holder) 
* Printer head: [pp_printer_head](../parts/pp_printer_head) 
* Smooth rod holder: [pp_smooth_rod_holder](../parts/pp_smooth_rod_holder) 
* X axis end: [pp_x_axis_end](../parts/pp_x_axis_end) 
* X motor support: [pp_x_motor_support](../parts/pp_x_motor_support) 
* Y rear end: [pp_y_rear_end](../parts/pp_y_rear_end) 
* YZ carriage: [pp_yz_carriage](../parts/pp_yz_carriage) 
* Z motor support: [pp_z_motor_support](../parts/pp_z_motor_support) 


## Laser cut or CNC routed parts

There are two parts that can be made in a laser cutter or in a CNC router. We provide `.dxf` files for them:

* Frame: [frame files](../parts/frame)
* Printing surface: [printing surface files](../parts/printing_surface)