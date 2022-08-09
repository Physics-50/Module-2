# Week 2:  2D Grating Patterns / Pixel Arrays

--------------
1. [Background](#background)
2. [Goals for This Week](#goals-for-this-week)
3. [Instrumentation](#instrumentation)
4. [Data Collection](#data-collection)
5. [Things to Turn In](#things to turn in)

--------------

Last week you determined the spacing of a diffraction grating by shining a red laser through it and measuring the distances $$L$$ from grating to viewing screen required to make the first diffraction maximum appear at certain distances $$x$$ from the central bright spot.  In that investigation, you became very familiar with diffraction from a one-dimensional pattern of barriers and apertures (the grating slits).

The theme of this week's session is two-dimensional grating patterns, of which pixel arrays on a projector or phone screen are fun examples.  You will observe the diffraction pattern created by two gratings oriented perpendicular to each other, and then use techniques from last week to measure the spacing of pixels on an LCD panel we have pulled from an old projector.  You may have time at the end to explore what it would take to measure your phone screen's pixel pattern via a similar method.

## Background

A _liquid crystal display (LCD)_ consists of a two-dimensional grid of small boxes called _pixels_ (originally short for "picture elements") that, together, display an image on a screen. Each pixel is itself composed of three 'sub-pixels' with colors red, green, and blue. If you look at your computer screen through a camera, you might be able to see the pixelated nature of the screen. Some common arrangements of pixels and sub-pixels in different devices are shown in the figure below. Voltages are applied across a pixel to control the colors and their relative intensities in that pixel.


<p class='center' markdown='0'>
  <img class="size-full wp-image-1891" src="https://www.physics.hmc.edu/~physics50/wp/wp-content/uploads/2018/10/LCD-pixels.jpg" alt="" width="224" height="224"> 
</p>

<p class='mycap' markdown='1'>
**Figure 1** --- LCD sub-pixel layouts for various types of screens.
</p>


You can think of the panel as a grid of windows with either red, green or blue glass, illuminated by a bright light from behind. Some mechanism -- perhaps a person adjusting the window shade, or (actually) a series of polarizers -- determines how much light passes through each individual window. If you stand far enough away, an adjacent set of red, green, and blue windows is too small for you to see each color separately; instead you see a splotch of color made up of whatever red, green, and blue light is getting through that set of windows. Again, if you stand far enough away, the individual splotches blend together and you see a color picture made up of dots the size of each individual window. Projector displays, your computer screen, and any LCD screen --such as the one on your phone-- for that matter, operate like this with "windows" or pixels on the order of tens to hundreds of micrometers wide. The more pixels a panel has, the sharper the image it produces, since there is more room for 'perfecting' the image on small scales.

If we shine a red laser through an unpowered LCD panel, the red light can transmit only through the red sub-pixels, of which there is one per pixel overall.  Thus, you can think of the LCD as a two-dimensional grid of apertures, where the distance between the apertures is the center-to-center pixel spacing.

#### Mini-question 1: Effective "Grating Spacing" for LCD Panel in Transmission
*[Click here to open in a new tab](https://docs.google.com/forms/d/e/1FAIpQLScJSe1HXQlHtpjEAGBMD8XrU6Ih5MUk9bq8BC3PBYkPJXcddw/viewform){:target="_blank"}*

<iframe src="https://docs.google.com/forms/d/e/1FAIpQLScJSe1HXQlHtpjEAGBMD8XrU6Ih5MUk9bq8BC3PBYkPJXcddw/viewform?embedded=true" width="640" height="400" frameborder="0" marginheight="0" marginwidth="0">Loading…
</iframe>


-----

## Goals for This Week

If you need to revisit aspects of last week's investigation, you should have some time to do so this week by spending less time on the last, open-ended part of this week's activities.

Your formal, quantitative goal this week is to measure the vertical and horizontal spacing of pixels on the LCD panel we have provided, using a two-dimensional version of the diffraction technique you used in Week 1.  You will also measure the physical dimensions of the LCD panel, and determine a size in pixels from your results.  That is, at the end of this week's careful measurements you will be able to say that the LCD panel is (number $$\pm$$ uncertainty) pixels across by (number $$\pm$$ uncertainty) pixels high.

All your diffraction measurements up to and including the LCD panel above have been done by transmitting laser light straight through the object being studied.  If you wanted to measure your phone screen without tearing it out of the your phone, such an approach would clearly not be viable.  Time permitting, you will spend the rest of this week using diffraction gratings, the LCD panel, and/or your phone to explore how diffraction patterns from light _reflected_ off a periodic array relate to diffraction patterns observed in transmission.

## Instrumentation

Each station should have an LCD panel in an acrylic case that is fastened to an optical post and mounted on the optical rail, as shown in the figure below.

[![LCD](images/LCD.png)](images/LCD.png){:target="_blank"}

<p class='mycap' markdown='1'>
**Figure 2** --- (left) When you set it up, the laser beam should travel from left to right through the LCD panel. (right) Layout of components on the optical rail. Click on the image to see a larger version.
</p>


An HDMI cable to connect the LCD to a computer, as well as a power cable, are attached to the LCD panel. *You will not need to use these cables at all for this simple investigation.  Please do not attempt to unplug either of these cables from the acrylic box.* The LCD should be oriented so that the laser shines through it in a direction going from left to right in the figure on the left above.


<!--
One of the goals for this exploration is to dissect (please do not take this literally!) the LCD panel,i.e. to deduce portions of its internal structure and to better understand how it works. 

In terms of deducing the internal structure, it would be nice to be able to 'look' inside. This is not so easy since the features of the LCD panel are quite small. However, humanity overcame this issue years ago when Hans and Zacharias Janssen invented the microscope.
-->
Figure 3 shows a photo taken of our LCD panel via the eyepiece of a microscope. You are encouraged to observe an LCD under the microscope (through the eyepiece) in the rear of the lab. A microscope calibration slide is available that you can use to estimate the pixel spacing and compare with your results. You may find this helpful when assessing if your results are reasonable for the final question on the checkpoint.

<p class='center' markdown='0'>
<img class="wp-image-1953 size-medium" src="https://www.physics.hmc.edu/~physics50/wp/wp-content/uploads/2018/10/LCD-microscope-300x230.jpg" alt="" width="300" height="230"> 
</p>
<p class='mycap' markdown='1'>
**Figure 3** --- Microscope image of an LCD panel identical to the one you have on your optical rail. **Note: the LCD that is pre-placed in the microscope is the same model as the one on your optical rail. Please do not disassemble your own LCD or its housing, and please do not touch the LCD panel area itself.**
</p>

<img src="images/microscope-calibration.png" alt="basic setup" width="400" style="display: block; margin-left: auto; margin-right: auto; width: 80%;" />
Figure 4 --- There is a calibration slide by the microscope that you can use to calibrate length scales in your view. The finest lines in the grid feature near the center of the slide are $$10 \mu m$$


<!--
The LCD has structure that looks like a two-dimensional array of windows, or two-dimensional array of slits. In other words, it has a diffraction grating-like structure. It makes sense, then, that if we shine a laser through, there ought to be some sort of diffraction pattern. -->

Another LCD panel of the same model can be found at the instructor bench at the front of the lab, along with the complete disassembled projector it came from.  Use the LCD panel at the instructor bench when you need to measure the physical size of the LCD array using a ruler or calipers.  This way, only one LCD panel will get handled extensively and build up fingerprints and scratches on its surface.

## Data Collection

To get a sense of what the diffraction pattern of a two-dimensional grating look like, take two 500-line/mm gratings and stack them like two pieces of paper, but with one grating rotated so its lines are perpendicular to the lines of the first grating.  Mount this two-grating sandwich on the optical rail as you would mount a single grating, and shine the laser through both gratings. You do not need to collect any formal data; just describe in your lab notebook what the diffraction pattern from a 2-dimensional grid looks like.  Replace one or the other grating with a 1000-line/mm grating and note how the diffraction pattern changes.


Now mount the LCD on your optical rail and shine your laser through the LCD (refer to Fig. 2). You will see a pattern of bright dots creating a rectangular grid, with roughly uniform spacing between maxima. By observing the distance  ($$x$$ or $$y$$) between these maxima, and finding the values of $$L$$ required to produce given $$x$$ or $$y$$ values, you can determine the spacing of the pixels in both directions. Based on your experience with last week's investigation, design and execute a procedure for taking reliable data and analyzing it to find the LCD pixel spacing both horizontally and vertically.

Measure the physical dimensions of the LCD using the unmounted one at the instructor's bench. You can use the pixel spacing and the physical dimensions of the array to determine a number of pixels horizontally and vertically across the panel.  The box the LCD came in will also be available at the front of class. Please make note of the manufacturer's specification on the box so that you can compare your measured pixel numbers to the manufacturer's specifications.

Finally, use a diffraction grating, the LCD panel, and/or your phone screen to explore what a diffraction pattern looks like when light is _reflected_ rather than transmitted off a periodic array.  What about when light shines on the periodic array _at an angle_ and is reflected? Get creative with paper, tape, and mounts to view the reflected patterns as best you can!  You could also do some internet research to help make sense of what you are seeing.  This portion of the lab might give you some ideas for a tech report at the end of the semester.


## Things to Turn In:

+ Bring a rough draft of your Module 2 lab report (hard copy, please!) to class next week for peer review.
+ The final version of your Module 2 lab report will be due three days before the next module begins, as stated in the syllabus.  As a reminder, the report due dates are:
  + Monday sections:  report due Friday 10/28 at 10p.m.
  + Wednesday sections:  report due Sunday 10/23 at 10p.m.
  + Thursday sections:  report due Monday 10/24 at 10p.m.
  + Friday sections:  report due Tuesday 10/25 at 10p.m.  

And make sure you have finished all of this week's mini-questions before lab by [checking here](mini-questions#week-2){:target="_blank"}.
