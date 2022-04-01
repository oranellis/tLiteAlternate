# tLiteAlternate

An alternative housing for Jumper T-Lite internals for the FrSky M9 gimbals (and two of the 4 switches). Still in development so check back later for updates :)

<img src="/assets/tLiteAlternate Render.png" title="Render">

Until I get some more diagrams on here, the main important piece of informaion for swapping any radio with any other gimbals is they pretty much always only need three wires per axis and they are the same for every gimbal I've found. The pinout per axis is just 3.3V, ground and signal with the signal wire being some voltage between 0 and 3.3V. Some gimbals like the t-lite share a ground and 3.3V between both axes to reduce the number of wires at the connector so if using a gimbal that looks like it has more or less wires then mind the power could be shared or seperate.

This means you should be able to swap out any gimbal with any radio as long as you are handy enough with a soldering iron and heat-shrink/crimping tools to make up the wiring harness and have some mounting solution for the new gimbals. (Note due to the tango 2 gimbals having their hall sensors on the PCB rather than the gimbal, it's not possible to swap these into another radio without mounting your own hall sensors for each axis, though this would be an interesting project to salvage some other gimbal's hall sensors and use them with the tango gimbals)
