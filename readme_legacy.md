Many thanks to the VzBot and the Voron team for making excellent printers.

# VORON-2.4-TOP-MOUNT-X-RAIL

VORON-2.4-TOP-MOUNT-X-RAIL
- 2023-04-21 - Updated to work with Offical VZ-PrintablePrintHead - https://github.com/VzBoT3D/Vz-Printhead-Printed
- 2023-02-01 - v4 uploaded and running. (LEGACY)

# Features

- Top Mount X Rail
- Simple install just new xy parts and stock standard VZ_Printable tool head.
- No major belt changes just the XY idler belts are now routed to rear of x axis beam. No cuttin no trimming of belts required.
- Ultra lightweigth design with high accelerations. See Input Shaper graphs below.
- 682gram Total X-Rail Full System Install.
 ![](images/v3/682g.png)
- Bed Printable area ~336x ~(y is actually greater to access end stop and brush) 324y
 ![](images/336x324y.jpg)

# Requriments

- Sensorless homing! Recommend Y home 1st with 100mm back off. Home X 100mm back off. Move Center bed Home Z with BEACON
  - https://docs.vorondesign.com/community/howto/clee/sensorless_xy_homing.html (remeber to adjust homing acceleration to 1k)
  - Beacon Probe
  - Umbelical or some kind of no cable chain system.
  - Move the Z-Axis chain under the gantry. and replace the bed mount so they chain can sit tucked under between. - https://www.printables.com/model/279739-voron-can-bus-z-chain-move

- LEGACY Probe Requirements
  - klicky prob
  - https://github.com/jlas1/Klicky-Probe
  - My Custom adjustable KlickyProbe gantry mount that suits custom heights of different toolhead FanDucts in the STL folder.

# Inspired By

- https://github.com/VzBoT3D/Vz-Printhead-Printed
- https://github.com/VzBoT3D/VzBoT-Vz330

# Official VZPrintHead Support
2023-04-21 VZ PrintablePrintHead Supported.
Requirements to use the VZ-PrintablePrintHead mirror the Belt componetns on the X-axis.
Mirrored parts are:
- bottom plate round standoff
- front round standoff
- back plate round standoff 

Reference Spec Images before a Mirror.
![](images/vz/voron_front.png)
![](images/vz/vz_front.png)

The idlers now match the VZ PrintablePrintHead
![](images/vz/xy_old.png)
![](images/vz/updatedvzxy.png)

# InputShaper
![](images/input_shaper/x.png)
![](images/input_shaper/y.png) 

# V3 Images - legacy V4 has updates see CAD @ bottom.

![](images/v3/l_front.png) 

![](images/v3/l_side.png) 

![](images/v3/l_iso.png) 

![](images/v3/v3iso.png) 

![](images/v3/v3back.png) 

![](images/v3/v3right.png) 

# YouTube

- Watch the videos for my build journey

[![youtube journey](https://img.youtube.com/vi/8w1qv4k_UrQ/0.jpg)](https://www.youtube.com/watch?v=8w1qv4k_UrQ)

[![youtube preview](https://img.youtube.com/vi/LdVHs1veAIQ/0.jpg)](https://www.youtube.com/watch?v=LdVHs1veAIQ)

# Known Issues

- v4 has no known issues.

# zChain Hidden

 - Z-Chain under the gantry extrusion is crushed especially with short hotends. Custom length hotend extension can be required. I also designed a new bed frame extrusion mount to allow the zChain to squeeze between. See STL downloads.
![](images/zchain/zchain3.png)
![](images/zchain/zchain2.png)
![](images/zchain/zchain1.jpg)

# v4 Improvmentns Included

- Gantry collision solved by a belt clip that pads out the frame to prevent the 5015 fan from colliding. estimate Y reduction of 8mm
![](images/v4/front_belt.png)
![](images/v4/top_belt.png)
![](images/v4/front_limit_stop.png)
![](images/v4/front_limit_stop_2.png)

# Feedback

 - if you install this please send me a photo on discord!
 - TopMountXRail@jc84.com
 - Discord julianjc84#7938
 
 # CAD
 
 https://cad.onshape.com/documents/a9a183adf9bba502a9a97bd8/w/d7fe18026210d20805620ae9/e/9a3a7e08fe09ca9430e55a9d

 # RELATED MODS
 https://github.com/YoDan-V2-2027/Voron_Vz_Printhead_Mod
 