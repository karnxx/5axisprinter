# 5-axis printer

this is a personal project where im building a 5-axis 3d printer, inspired by multipole’s 5-axis design. after i make the printer, i will try to add a mmu to this

![image](https://github.com/user-attachments/assets/1437434e-2552-4c10-a3ee-b1c0cc9450fd)

normal 3d printers use 3 axes (x, y, z). a 5-axis printer adds two more rotational axes. this lets it print more complex shapes with fewer supports and smoother surfaces.  

## bill of materials (wip)

i’m keeping a list of all the parts i'm using. it’s not final yet.  
[bom](https://1drv.ms/x/c/a3f42e945c9caa44/EbQFKpQWxlxJoD3NqtjWvSIBQ96Bu_KVVyi092GPrF79ng?e=d1bzi9)

| Components                        | Price (INR) | Price (USD) | Quantity                                   | Link |
|----------------------------------|-------------|-------------|--------------------------------------------|------|
| 2020 extrusion                   | 3000        | 37.5        | 8.5m                                       | [link](https://novo3d.in/aluminium-profiles-2020/?srsltid=AfmBOoqdCIagKlnxuTtaedS3pP4a6XTQNW1oaKr_tbyDSgIuxD1gO6ok) |
| linear rail(mgn12c)              | 2080        | 26          | 4.2m                                       | indiamart/alibaba |
| linear rail block (mgn12c)       | 5000        | 62.5        | 11                                         | indiamart/alibaba |
| nema17hs4401                     | 3700        | 46.25       | 5 (6 for extruder, i alr have spare)       | [link](https://www.amazon.in/dp/B0DGF3VZYT?ref=ppx_yo2ov_dt_b_fed_asin_title) |
| lead screw                       | 780         | 9.75        | 3x430                                      | [link](https://robodo.in/products/500mm-trapezoidal-lead-screw-8mm-thread-2mm-pitch-lead-screw-with-copper-nut?variant=6509949091883) |
| lead screw anti backlash         | 261         | 3.2625      | 3                                          | [link](https://www.flyrobo.in/t8-anti-backlash-spring-loaded-nut-for-8mm-threaded-rod-lead-screw-2*2mm) |
| 4010 fan                         | 200         | 2.5         | 2                                          | [link](https://robocraze.com/products/dc-12v-4cm-5010-double-ball-cooling-fan-durable-turbo-blower?variant=46397911433440) |
| e3drevo6                         | 1600        | 20          | 1                                          | [link](https://nl.aliexpress.com/item/1005009068669267.html) |
| dual gear drive extruder        | 575         | 7.1875      | 1                                          | [link](https://www.amazon.in/dp/B08BNL96DX?ref=ppx_yo2ov_dt_b_fed_asin_title&th=1) |
| 16t idler pulley for gt2        | 360         | 4.5         | 6                                          | [link](https://www.flyrobo.in/16-tooth-3mm-bore-gt2-timing-idler-aluminum-pulley-for-6mm-belt) |
| 16t smooth idler pulley for gt2 | 120         | 1.5         | 2                                          | [link](https://robocraze.com/products/gt2-perlin-driven-aluminium-pulley-5mm-bore) |
| nuts and bolts                  | 300         | 3.75        | many                                       | [link](https://onlyscrews.in/) |
| bl sensor                       | 4000        | 50          | 1                                          | [link](https://novo3d.in/bl-touch/) |
| btt octopus                     | 4100        | 51.25       | 1                                          | [link](https://biqu.equipment/products/bigtreetech-octopus-pro-v1-0-chip-f446) |
| gt2 belt                        | 100         | 1.25        | 3m                                         | [link](https://novo3d.in/gt2-belt/) |
| endstops (alr have)             | 0           | 0           | 2                                          | - |
| wire                            | 99          | 1.2375      | yes                                        | [link](https://www.amazon.in/dp/B0BVSM7N3L?ref=ppx_yo2ov_dt_b_fed_asin_title&th=1) |
| psu 24V, 14.6A, 350W            | 2800        | 35          | 1                                          | [link](https://robodo.in/products/delta-industrial-power-supply-smps-24v-14-6a-350-4w-pmt) |
| ptfe tube                       | 83          | 1.0375      | 1m                                         | [link](https://robocraze.com/products/ptfe-3x5mm-white-teflon-tube-for-3mm-3d-printer-filament-1-meter-3mm-id-x-5mm-od) |
| heatbed knob set                | 550         | 6.875       | 1                                          | [link](https://www.amazon.in/dp/B088KQJZGZ?ref=ppx_yo2ov_dt_b_fed_asin_title) |
| aluminium hotend bracket        | 200         | 2.5         | 1                                          | [link](https://novo3d.in/e3d-v6-fixed-block/) |
| coupler 5x8mm                   | 122         | 1.525       | 407.5                                      | [link](https://www.fastdep.in/product/flexible-coupling-5mmx8mm/) |
| tslot nuts for 2020             | 970         | 12.125      | 100                                        | [link](https://novo3d.in/sliding-t-nut/) |
| 300x300 heatbed                 | 1600        | 20          | 1                                          | indiamart/alibaba |
| **TOTAL**                       | **32600**   | **407.5**   |                                            | indiamart/alibaba   |


## build journal

im writing down ideas, issues, and updates as i go.  
[journal](https://github.com/Fastestkyo/5-axis-printer/blob/main/journal.md)

## how to guide

this is a tutorial for how to build this printer.
[how to](https://docs.google.com/presentation/d/14-imUmjOe8GsNLc_C2gs7DdIq2Uft8Xhfen-554Q0Uw/edit?usp=sharing)

## CAD
the 3d model of the entire printer.
i have cad files in the CAD directory, of the printer and the 3d printed parts.
[cad](https://a360.co/3HxWdIz)

# INFO


##fram
-The frame is made of 2020 aluminium extrusion. Use t slot nuts + corner joining plate and 90 deg joining thing
-U need the following pieces-
-500x4
-460x14

-Total - 8.5m
![image](https://github.com/user-attachments/assets/4a4da90a-c10d-4663-af95-89834bb4e05a)


##linear
-U need about 4.5 m of linear rail. And 11 mgn12c blocks. Linear rail dimensions are-

-460x3 mm
-210x3 mm
-420x5 mm
![image](https://github.com/user-attachments/assets/2d791bde-b680-41e3-877e-02363f1ae772)

##Lead screw
-U need 3 lead screws, 425 each. U also need 3 anti backlash nuts
![image](https://github.com/user-attachments/assets/f01d6b72-4db1-42da-92e9-43d7e8ebcce3)


##XY
-Corexy xy, driven by belts and pulleys. U need 2 16t smooth idler pulleys, and 6 16t idler pulleys. U also need 2 20t pulleys for the motor
![image](https://github.com/user-attachments/assets/02eb3e9f-4abf-4f00-b3e5-d8d5b8b2e6e0)


##toolhead
-For the toolhead i will use a E3D revo, along with 2 4010 radial fans and a 3010 axial fan
-[done](images/toolhead.png)

##motor
-You will need 2 motors for xy, and 3 motors for z, a and b. And 1 for extruder.
![image](https://github.com/user-attachments/assets/1e955346-60a9-4c76-bda9-02796d99d67c)


##Z, A, B,
-For z, a, b install the cantilever 3d printer parts to the linear blocks and lead screw. Then install the 210mm linear rail to the cantilever parts. After that install the ball socket joint mount on the linear block of the linear rail which is on the cantilever thing. I will be using a 300x300 mm heatbed for this
![image](https://github.com/user-attachments/assets/16531fa3-6ca7-4d30-8bc7-4632af7b0425)


##electronics
-I wll be using a bl sensor. The motherboard thing for this will be a btt octopus pro.


## project status

this project is still in progress. i wil be updating the journal.md from time to time


