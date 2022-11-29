# tr707_negative_vibes
This is a kicad project for a dc/dc converter for the roland tr707 and 727 drum machine. it can replace the negative dc supply with the hard to find Sumida coil in the tr707.

It takes the nominal 12v input voltage and transforms it to a negative 10v

It is based on an ICL7660 negative voltage dc/dc converter.
The design is based on an idea by harry axten who makes a really nice eprom swap mod for the tr707.



Installation:

Desolder the following components: Q1 Q2 T1(the sumida coil) D2 D3 D18 C7 C8 R1 R2

Fit 5 2.54mm male/male pinheaders to the bottom of the Negative vibes Pcb and solder them onto the tr707 main board.
You could fit pin header sockets if you want, but its probably better to just solder them directly.

thats it!


dual parallel ICL7660 chips provide a stable -10v supply. the jumper jp1 can be cut to disable the second ICL7660, but you probably will never want to do this.

there is a footprint for an extra filter capacitor, but it shouldn't be necessary.

Always check random designs from the internet before connecting them to your precious drum machine.

this is not a user installable modification, it is intended for synth repair people who know what they are doing and probably could have made it themselves. only install it if you take full responsibility for your work.

you should really run your tr707 with a 12v center negative psu. lots of people run them with  a 9v boss psu, *maybe* nothing bad will happen, but it's not kosher. According to the service manual it should be 12v. the negative vibes psu is tested to work properly with a 12v external psu.

i will probably respond to messages but i don't officially offer support. and i probably can't answer any questions that the ICL7660 datasheet and TR707 service manual don't already answer.

i'm much rather that you buy the pcb from me than producing your own. but i've put everything on github so that if i ever stop producing them then it will be possible for you to have a batch made, in this case i ask you to make them only for your own repair work and offer any spares at close to cost to the the synth repair community.

The first batch i will sell directly, and subsequent batches will be available for sale at an online shop. the first batch has just arrived... i will be contacting everybody who expressed interest. if i don't get in touch, send me an email.

you can contact me at ewanuno@gmail.com

![bottom](/tr707minus10v_kicad_down.png)
![top](/tr707minus10v_kicad_up.png)
