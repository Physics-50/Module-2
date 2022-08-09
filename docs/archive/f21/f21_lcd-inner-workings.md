## Inner Workings of a LCD
The actual operation of an LCD screen is a technically clever, miniaturization-friendly version of the tinted-window scheme presented earlier. To understand the exact process requires some new information. We present the following description of the inner workings of the LCD your enrichment but please don't get too bogged down in the details! The [takeaway](#takeaway) is at the end.


To understand how LCDs work, we must first understand what light polarization is. When a light beam moves through space, it is made up of electric and magnetic fields that point in a plane perpendicular to the direction the light is traveling, and that oscillate in their magnitude and direction. The exact axis of the electric field within the plane perpendicular to motion is in general random. And in the case of lots of randomly generated light going in the same direction, the axis of the electric field will almost certainly not be consistent. This is called unpolarized light. Sometimes, however, the electric field axis is consistent. When this happens, the light is said to be polarized along a certain direction---namely, the direction of the oscillating electric field. One can control the polarization of light by using a polarizer. There are a variety of polarizers, and just as many ways that they work. The simplest type is an absorptive polarizer, which does exactly what you'd expect it to: these polarizers transmit light polarized along one axis, and absorb light polarized perpendicular to that axis. The net effect is to remove (absorb) between some and all the light incident on this object that is polarized in any direction other than the polarization axis-- the amount that is absorbed is a function of the angle between the light polarization and the polarization axis of the polarizer. This means that only the light polarized along the polarizer's axis will pass through, and the light that passes through is now polarized even if the initial beam was not.

Let's now talk about liquid crystals. Liquid crystals are partly ordered materials existing somewhere in between a liquid and solid state of matter. The material consists of large molecules shaped like rods, like tiny Tic Tacs or pieces of penne pasta (minus the hole in the middle). The liquid crystal molecules can be encouraged to line up with each other, either by an electric or magnetic field, a film of directionally aligned material next to them, or some other mechanism. Let us assume for the remainder of this discussion that the molecules are aligned; that is, that each 'rod' (i.e., each molecule) is parallel to every other. The structure and orientation of each molecule affects how easily electrons in that molecule can move in different directions, so a liquid crystal with the molecules aligned has electrons free to move only in a particular fashion. When light passes through the liquid crystal, interaction with the electrons can change the direction of the oscillating electric field in the light -- i.e., can change the polarization of the light.

This is all we need to know to understand how an LCD screen works. First imagine a light source passing through two polarizers. Suppose the two polarizers are aligned to polarize light in the same linear direction (say vertically, so that light is polarized vertically). In this case a beam of light passing through the first will be polarized vertically. This vertically-polarized beam will then hit the second polarizer, and pass through unchanged since the light already aligns with the polarization axis of the polarizer. However, if we now rotate this second polarizer $$ 90^{\circ}$$, then no light whatever will get through since the light is exactly at the orientation in which the second polarizer completely absorbs. Thus, someone looking at a screen placed downstream of the second polarizer will see no light. Reminder: never look upstream in a setup with lasers!

Now, imagine that we sandwich a liquid crystal in between these two polarizers (whose axes are still aligned perpendicular to each other). This is a liquid crystal display sub-pixel. Without the liquid crystal between the polarizers, no light would get through. However, in the resting state of the liquid crystal (when no voltage is applied), the liquid crystal rotates the polarization of the light by approximately $$90^\circ$$ so now light is able to pass through the second polarizer. If a voltage is applied to the liquid crystal, the molecules can be reconfigured (reoriented in some technologies, or untwisted in others) so that they no longer rotate the light polarization. The cell now appears black. The degree to which the rotation is altered from the default $$90^\circ$$, and therefore the amount of light that is absorbed, is dependent upon the strength of the voltage applied to the liquid crystals.

This whole process gives us a way to control the light that gets through the polarizer-liquid crystal-polarizer sandwich by simply turning on or adjusting a voltage. Thus, we have a miniature, electronically controlled "window shade" that can control the amount of light passing through by tuning the applied voltage to an individual sub-pixel! Each sub-pixel also has a colored filter, just like the colored-glass windows we imagined earlier. One 'pixel' is therefore made up of three different liquid crystal elements, each surrounded by two polarizers and with a red, green, or blue filter. Combining these pixels into a very compact structure, or grid, gives an LCD screen. The simplicity in this approach is that only a single light source is required to illuminate the entire grid. Voltages applied to the sub-pixels then determine how much light gets through for each of the RGB sub-pixels at each pixel location on your screen, thus through a series fine RGB dots creating a picture like the one you are likely staring at on your computer screen at this very moment! That this is what is happening on the inside of your computer and phone screens is quite a remarkable fact!

## Takeaway

The liquid crystal rotates the polarization of light passing through it by some amount that is set by an applied voltage; light passing through a system of two polarizers with a liquid crystal in the middle will have its intensity depend upon how much its polarization was rotated by the liquid crystal. This tunes, electronically, the amount of light that is emitted! This is what is happening in each and every crystal. 