# Week 1: Exploration and Measurement of Grating Spacing

--------------
1. [Background](#background)
2. [Goals for This Week](#goals-for-this-week)
3. [Instrumentation](#instrumentation)
4. [Collecting Data](#collecting-data)
6. [Things to Turn In](#things-to-turn-in)

--------------

You should have received new Google Doc and Google Sheets notebooks through Google classroom. Please make use of the new notebooks for this module. 

In this module you will be studying a light interference effect called **diffraction**. By leveraging this phenomenon, you will use a ruler and your naked eye to measure the line spacing of a grating, even though the lines are only about 0.002 mm apart!  Diffraction as a tool for measuring small-scale periodic structure has applications from biology -- including the famous Rosalind Franklin double-helix data -- to materials science and many other fields.

## Background

In Module 1 we worked with sound as a wave of air pressure; in this module we will be viewing light as an electromagnetic wave--- a set of periodic oscillations of electric and magnetic fields, propagating through empty space at speed $$c$$.  In the last module we considered how two waves traveling in opposite directions could sum, or _interfere_, to produce a standing wave.  In this module, we will again be considering interference, but in this case of waves traveling in almost the same direction as each other.  

In the diffraction scenarios we will consider, a monochromatic plane wave of light -- that is, a wave of a certain wavelength and frequency and with simple, planar wavefronts -- is incident on a barrier with a series of small openings (_apertures_) in it.  The light that makes it through each small aperture travels outwards from that spot, and on a screen far downstream we observe a regular **_diffraction pattern_** that comes from the interference between the light waves coming from all of the individual apertures.  Before we get into the mathematical details, let's get a better visualization of what is happening by thinking about water waves. In the right half of the photo below (taken for Google Earth off the Australian coastline) we can see water waves traveling as a plane wave from right to left and encountering a series of apertures.

![ocean waves](https://www.physics.hmc.edu/~physics50/wp/wp-content/uploads/2018/10/water-diffraction-ocean.jpg)
**Figure 1**: A photo off the coast of Australia showing the diffraction of a wave as it passes from right to left through several **apertures**, or openings, in a rocky barrier. First, notice that the wave coming out of each aperture is no longer a **plane wave** with straight wavefronts but rather is coming out as circular ripples traveling away from the center of the aperture. It is as though the aperture is a wave source of its own, sending waves out in all forward directions rather than just the initial right-to-left direction! Second, notice that the circular wavefronts from several apertures begin to overlap with each other to the left of the apertures. The overall downstream pattern of strong and weak disturbance created by the cured wavefronts interfering with each other is called the _**diffraction pattern**_. *Photo credit: Google Earth.*


Let us now return to light waves, which behave just as we have seen above for water waves.  If you send a single laser beam through a narrow slit and observe the light that has passed through the slit on a screen then you will see two main effects, as shown below in Figure 2. First, the light spreads out over a much broader angle than the original laser beam---even though the slit was much narrower than the original laser beam. This behavior is similar to what we saw for water waves in the photo above: a narrow aperture sends waves out in all directions, not just the original direction. Second, the spread-out light displays an interference pattern. The interference pattern here comes from superposition of waves spreading out from the different spots within the same narrow slit.

![single slit diffraction](images/week1-fig2.jpg)

 **Figure 2**: The diffraction pattern from a monochromatic light source traveling through a single slit.

The mathematical details of how the interference pattern comes about are beyond the scope of Physics 50, but the take-away is this. After passing through the single-slit aperture the beam will form a central, spread-out bright spot and sometimes several dimmer spots on either side. The width of the central bright spot depends upon the frequency and wavelength of the monochromatic (single-wavelength) light passing through the slit, as well as the size of the slit and the distance between the slit and the screen upon which you are observing the pattern. A narrower slit causes a wider central diffraction spot.

Now let’s imagine the laser light passes through two slits rather than one. In other words, the laser beam is now blocked by an opaque slide that has two narrow, identical slits that the light can pass through. The light passing through two slits will now create a pattern as shown below in Figure 3.


![double slit diffraction](images/week1-fig3.jpg)

**Figure 3**: Diffraction pattern from laser light passing through a double slit. What similarities and differences do you observe between the single slit (Figure 2) and double slit patterns?

To understand the pattern of bright spots caused by two slits, we consider the light traveling outward from each slit. Figure 4 below shows a simplified schematic of the waves emanating from two slits - the semicircular curves represent wave crests, and the separation between the curves is the wavelength of the light. This schematic is dramatically not to scale, since typically both the spacing $$d$$ between the slits and the wavelength $$\lambda$$ of the laser light are much, much smaller than the distance $$L$$ between the slits and the screen where the diffraction pattern is being viewed.



![waves passing through double slit](images/week1-fig4.png)

**Figure 4**: Simplified schematic of light waves passing upward through a double-slit slide, leading to constructive interference at certain angles---red lines indicate angles where the two waves interfere constructively to cause bright spots where the red lines meet the screen. *This schematic is very much not to scale.*

In Figure 4, the red lines represent positions where wave crests interfere constructively with each other---that is, the positions where the two waves are in phase and superpose to give a large-amplitude wave overall. Notice that constructive interference happens at certain angles away from the straight-ahead direction, leading to the specific bright spots located where the red lines meet the screen in the figure. Between these maxima, there are dark spots at angles where the two waves interfere destructively with each other -- that is, positions where the two waves are out of phase and perfectly cancel each other out.

## Diffraction Gratings

In Module 2, you will be investigating the diffraction pattern caused not by two slits, but by a **diffraction grating** with many, many slits, all separated by the same distance $$d$$. For such a scenario, it’s not as easy to see the angles of constructive interference by drawing the wave crests (see Fig. 5 below). 

![diffraction grating wave crests](images/DiffGratWavecrests.png)

**Figure 5**: Schematic of wave crests emerging from a diffraction grating. *This schematic is very much not to scale.*

<br>

Instead of drawing out wave crests, for the diffraction grating we will think about the light as rays emanating in all directions from each slit, and focus on just those rays that all eventually land at a single point on the screen, as shown by the green lines in Fig. 6. For simplicity, only 4 rays have been shown, from four neighboring slits. Each ray ends at the same point a distance $$x$$ from the center of the screen, and we are interested in whether the light from the 4 slits interferese constructively or destructively at this point.  We emphasize that this schematic is very, very much not to scale.

<img src="images/week1-fig6.png" alt="" width="350"> 

**Figure 6**: Schematic of light rays emerging from a diffraction grating. Only four rays have been sketched, and all four reach the same point on the screen, a distance $$x$$ away from the center. *This schematic is very much not to scale.*

In real situations we care about, the distance $$d$$ between the slits in the diffraction grating is six orders of magnitude smaller than the distance $$L$$ between the grating and the screen---that's like the difference between 1 cm and 10 km! Under these conditions makes sense to use the following approximation, which offends our sense of geometry definitions but is very accurate for our experiment:

**We can approximate that all the rays that end at the same point on the screen are parallel to one another.**

That means that the four green lines in Fig. 6 are treated as approximately parallel to each other as long as $$L \gg x$$. A better-scaled and ultimately more useful drawing would zoom in to just the region right above the diffraction grating, where the screen is *way* out of view and the rays that are all headed to the same position $$x$$ are shown in Fig. 7.

<img src="images/week1-fig7.png" alt="" width="350"> 

**Figure 7**: Schematic of light rays emerging from a diffraction grating. All five rays shown land at the same point on the very distant screen. The paths of the five rays to the screen are the same above the diagonal dashed line, but differ in the portions shaded black below the dashed line. *This schematic is reasonably to scale.* 

In Fig. 7, we can see that the distance traveled by the light to get to the screen is different along rays coming from different slits. Relative to the rightmost ray in Fig. 7, each consecutive ray's path is longer by an additional length $$d \sin \theta$$.  When the extra distance $$d \sin \theta$$ traveled by light on adjacent rays is equal to an integer number of wavelengths, then all the rays will interfere constructively at the point where they land on the screen, creating a bright spot.

Mathematically, this condition is met if 
\begin{equation}\label{eq:grating}
d \sin \theta = n \lambda
\end{equation}
where $$n$$ is an integer and $$\lambda$$ is the wavelength of the light.

We can do a little more to simplify this expression. From Fig. 6, we can see that $$\sin \theta = x / \sqrt{(x^2 + L^2)}$$. Substituting this into our constructive interference condition gives **_Young's equation_ for the $$n^{th}$$ bright spot from the center of our diffraction pattern:**

**\begin{equation}\label{eq:sYoung} 
\frac{xd}{\sqrt{(x^2 + L^2)} }= n \lambda
\end{equation}**

**You will use Young's equation to determine $$d$$, the line spacing of your grating, by measuring $$x$$ and $$L$$ and using the quoted value of $$\lambda$$ given by the manufacturer of your laser.**

#### Mini-question 1: Spacing of Diffraction Gratings
*[Click here to open in a new tab](https://docs.google.com/forms/d/e/1FAIpQLSc91z681gWz9ej6xEaYywPRHQWdlkKDwwGL0V46HMknP90hPg/viewform){:target="_blank"}*

<iframe src="https://docs.google.com/forms/d/e/1FAIpQLSc91z681gWz9ej6xEaYywPRHQWdlkKDwwGL0V46HMknP90hPg/viewform?embedded=true" width="640" height="400" frameborder="0" marginheight="0" marginwidth="0">Loading…
</iframe>


-----

#### Mini-question 2: Spacing of Interference Maxima
*[Click here to open in a new tab](https://docs.google.com/forms/d/e/1FAIpQLScZD277T20i9LkcYO8Uj3AM8CEtfC9wYynMl2redGVRwMuFLg/viewform){:target="_blank"}*

<iframe src="https://docs.google.com/forms/d/e/1FAIpQLScZD277T20i9LkcYO8Uj3AM8CEtfC9wYynMl2redGVRwMuFLg/viewform?embedded=true" width="640" height="400" frameborder="0" marginheight="0" marginwidth="0">Loading…
</iframe>


-----

## Goals for This Week

This week, you will use Young's equation to find the spacing $$d$$ between lines in your diffraction grating.  The printed label indicates an approximate spacing, but your measurement will refine this estimate.  After an initial exploration of sources of error, you will take a careful set of data to find $$d$$ by measuring the $$L$$ values required to make the first diffracted spot ($$n=1$$ in Young's equation) appear at different values of $$x$$.  You will graph $$L$$ as a function of $$x$$, find the best-fit slope, and use this slope and its uncertainty in Young's equation to calculate $$d \pm \delta d$$.

### The Value of Plotting and Fitting

Why don't you just set a single $$x$$ value, measure the corresponding $$L$$, and plug these into Young's equation and solve for $$d$$?  You could even do repeated trials, including varying $$x$$ if you wanted to, and average the resulting $$d$$ values.  

One of the ideas we would like you to take away from this course is to respect the power of a data set as a whole, rather than just individual points. In this case the theory suggests that, as long as we use a single grating and laser, $$L$$ and $$x$$ should be related to each other in a simple way:  they should be directly proportional.  Plotting the data and looking at the data set as a whole allows us to test this theory while letting the combined data tell us as much as possible about our results.  We will outline the approach before pointing out some of its advantages.

Let's go back to Young's equation, solve it for $$d$$, and rewrite the result in a more suggestive form:
\begin{equation}
d = n\lambda\sqrt{1+\Bigl(\frac{L}{x}\Bigr)^2} = n\lambda\sqrt{1+m^2}
\end{equation}
where we have introduced the parameter $$m=L/x$$, or the slope of a plot of $$L$$ vs. $$x$$.  (Make sure you can get this result from Young's equation.  You might want to write out the calculation in your lab notebook.)  As mentioned above, in your experiments you will focus on the $$n=1$$ diffracted spot.

Let's pause for a practice calculation and an example of what the graph of $$L$$ vs. $$x$$ might look like.

------
#### Mini-question 1: Calculating d from slope
[*Click here to open in a new tab*](https://docs.google.com/forms/d/e/1FAIpQLSewqupEcZn39DFWA4u5VqGXwGsVT5lAWeszwl0yCS0upCANug/viewform){:target="_blank"}
<iframe src="https://docs.google.com/forms/d/e/1FAIpQLSewqupEcZn39DFWA4u5VqGXwGsVT5lAWeszwl0yCS0upCANug/viewform?embedded=true" width="640" height="400" frameborder="0" marginheight="0" marginwidth="0">Loading…
</iframe>

---------------------------

There's an added power to treating the data set as a whole in this way.  First, we can test whether our data obeys the theory.  Is $$L$$ in fact a linear function of $$x$$, as the theory suggests?   Furthermore, consider what might happen if you had a systematic error that shifted all of your measured $$L$$ values.  Individual $$L/x$$ values would all be influenced by such an error, but plotting a line would give you correct slope plus a non-zero intercept, as shown in the mini-question sample data above, where the fitting parameter $$b$$ shown in the legend is clearly not equal to zero.
<!-- **Replace graph with L vs x**
<img src="images/x_vs_L_offset.png" alt="basic setup" width="400" style="display: block; margin-left: auto; margin-right: auto; width: 80%;" /> -->

At the end of this week you should have a graph and weighted fit similar to the one above but constructed from your own carefully-taken data.  You should use the fit results to evaluate the quality of your data set, and if you are satisfied with it you should calculate a final result for $$d\pm \delta d$$ based on the slope of the best-fit line and its uncertainty. 

## Instrumentation

You will begin by setting up the experiment on an optical rail.

Attach the red laser to the laser holder mount, shown below in Figure 8, and attach it to a post holder placed on the optical rail with the laser facing the wall. (We don't want the laser light shooting across the room; please make sure when you set up your laser pointer that it is aimed at the wall, away from your classmates.) When adjusting the laser, the post, or the entire mount, be sure to loosen the relevant set screw and then re-tighten it by hand once you achieve the desired positioning.

{: .center}
![alt text](https://www.physics.hmc.edu/~physics50/wp/wp-content/uploads/2018/10/Laser-holder-web.png){: width="400px;"}


{: .mycap}
**Figure 8** --- Laser holder, both with and without laser itself mounted. When adjusting a piece of the apparatus, be sure to loosen the relevant set screw before making adjustments, and then re-tighten it firmly afterwards.

**NEVER place your eye directly in the path of any laser beam.** Even if you are sure the laser is currently off, you should **never look directly down the beam path.**

Mount the grid paper "screen" to the vertical support at the end of your optical rail (in the direction the laser is pointing, i.e., near the wall).

Near the center of the rail, between the laser and the screen, attach another post holder, and use it to mount a diffraction grating, shown in Fig. 9.

**When handling the diffraction grating make sure to only touch the cardboard rim. Getting fingerprints on the transparent grating could affect your results and those of later lab groups.**

{: .center}
![alt text](https://www.physics.hmc.edu/~physics50/wp/wp-content/uploads/2018/10/Diffraction-grating.jpg){: width="400px;"}


{: .mycap}
**Figure 9** ---  Diffraction grating. Touch only the cardboard with your fingers, and store in a vertical holder or on a piece of lint-free tissue.  <!-- A diffraction grating is essentially just an array of slits placed right next to each other, with a very small slit distance <em>d</em> between each (on the order of one slit per micron). Each neighboring pair of slits can be thought of as a double slit. -->

<!-- A diffraction grating is essentially just an array of slits placed right next to each other, with a very small slit distance $$d$$ between each (on the order of one slit per micron). Each neighboring pair of slits can be thought of as a double slit. -->

Slide the diffraction grating (in its mount!) along the rail so it is very close to the screen; turn on the laser. You should see three or more dots on the screen. Slowly pull the grating away from the screen until the central three dots are spread across most of the screen. Do not pull the grating back too far, as you want to be sure that the diffracted spots are hitting the screen and not flying across the room to a neighboring lab group.

It's possible that you will find it easier to see the diffraction patterns with the room lights turned off.  After all groups have completed the basic setup of optical elements on the rail, anyone who wants to try the lights off should notify the rest of the class first.  You will find a lamp at your bench that you can use to illuminate your workspace as needed.

Alternately, you may find the diffracted spots too bright; in particular, reducing the brightness of your diffraction maxima will reduce their spot size and may help with placing them more precisely later on. One way to reduce the intensity of light is by adding a rotatable polarizer. [Click here for more information about polarizers](polarizers). The laser emits linearly polarized light, and the polarizer will only transmit light polarized parallel to its axis, so by adding a polarizer and rotating the axis of its polarization you can control how much light gets through. **Remember to turn off the laser when inserting components into the beam path of your laser.** Speak to your instructor if you would like to reduce the intensity of your beam but aren't sure how to make use of the rotatable polarizer.

The distance $$x$$ between the central laser spot and the first interference maximum can be measured with a ruler or directly on the grid paper, and the distance $$L$$ of the diffraction grating from the screen can be measured with a meter stick or directly from the optical rail. If you measure the position of a certain part of the grating mount instead of the grating itself, your results should come out fine as long as you are consistent (see ["The Value of Plotting and Fitting"](#the-value-of-plotting-and-fitting) above).


## Collecting Data

### Exploratory Measurements

As in the last module, you should first perform some exploratory measurements and record them in your data sheet assigned from Google Classroom.

**Please take careful note that these first measurements are just intended as a very quick exploration. We want to make sure you have time to do a careful study in the later part of today's lab. For this first exploration please just take one quick measurement at each setting, as suggested. The settings can be approximate, and you do not need to estimate uncertainties. You are just trying to work out whether the measurement is sensitive to each parameter or not.**

The ultimate goal of Module 2 is to determine the wavelength of your laser by measuring $$L$$ for various values of $$x$$. However, at first you should get to know your apparatus and what quantities must be set carefully to give you precise and accurate results.  Because this system is a little more abstract than your levitated beads, we provide a list of settings that you should be sure to check.  For each setting, we ask you to change the experimental settings slightly and record how the change affects your measurements.

To get started, quickly find the $$L$$ value required to produce an $$x$$ value of 10 cm.  Use this single trial to estimate $$d$$ and check that your results are in the right range (no factors of ten or a thousand from incorrect unit conversions, for example).

Now focus on the angle of the diffraction grating, which ideally should be exactly perpendicular to the laser beam. Perhaps you might not notice if it were off by angles up to $$\pm 5^{\circ}$$ (though this is actually pretty noticeable if you are paying attention). How important is this? To answer this question, first carefully set the diffraction grating perpendicular to the laser beam. You can do this by looking at the dim beam reflected by the diffraction grating. Adjust the diffraction grating so that the reflected beam retraces the incident beam (at least in the horizontal direction) by adjusting the diffraction grating until a spot from the reflected beam is visible on or just above/below the laser itself. Speak to your instructor if unclear and **remember never to put your eye in the path of a laser beam**. Measure $$L$$ required for $$x=10$$ cm under these conditions. Now purposefully "wiggle" the grating by adjusting the angle of the grating to $$\approx 5^{\circ}$$ relative to the perpendicular; you can get a rough idea of the angle using a protractor held above the center of the grating. Measure $$L$$ again.  Now repeat the test with the grating rotated by $$\approx 5^{\circ}$$ relative to the perpendicular in the other direction.

For the exploration above and those below, **repeated trials are not necessary** to give you a rough idea of your measurement's sensitivity to each factor.

1. Distance from laser to diffraction grating. Change it by $$\pm$$ 1 cm and record how $$L$$ changes.

2. The value of the diffraction spacing $$d$$ is also a parameter we can "wiggle," in a slightly less obvious way. Each diffraction grating could have manufacturing defects that cause $$d$$ to be slightly off from the stated value. We can explore this possibility by measuring $$L$$ at three positions on one diffraction grating. This is just exploratory so you do not need to record the exact position you use on the grating; just take one measurement with the beam passing through the left side of the grating, one through the center and one to the right. You can adjust the position of the grating by sliding it in its holder - remember to only touch the grating by the cardboard edge.  Record $$L$$ for three different parts of the grating.

3. The distance $$x$$ between the $$n=0$$ and $$n=1$$ bright spots is something we will be systematically varying later, of course.  But each time we set the value of $$x$$, we can only do so with some precision. Set <em>x</em> = 9 cm or 11 cm instead of 10 cm, and see how much the resulting $$L$$ changes.

If you can think of other factors that might unintentionally influence your results, explore their effect in a similar way.

**The takeaway from this exploratory exercise is that the factors that cause a larger variation in $$L$$ should be carefully reset before each $$L$$ measurement. The ones that don't make much difference in $$L$$ do not need to be treated with as much care.**

### Careful Measurements to Find $$d$$

**Please go to the second sheet in your assigned Google Sheet. Week 1: Part 2 (Careful Data) which includes a template for the second half of this week's lab.**

Armed with a clear idea of which factors you need to carefully control (to reduce systematic error) and reset between trials (to randomize remaining error)... you are ready for the careful determination of $$d$$ that should take the bulk of your time in lab this week.

**For each of about five (no fewer) different $$x$$ values, take at least five individual measurements of $$L$$** and find the average and SEM of your trials.  Try to pick $$x$$ values that cover most of the range you can measure well with your apparatus.  Also, **remember to reset all the factors that also have significant effects on $$L$$, for each measurement.** For example, you should mess up and re-achieve the desired value of $$x$$ between each of the five trials, not just leave the grating in one spot and measure its position five times.  

Now you have a value for $$L \pm \delta L$$ at each $$x$$.  

<!-- ## Resolution error
We have discussed the importance of resetting parameters and using the SEM to randomize and account for systematic error, but this is not the only source of uncertainty. 

Please read the [discussion of resolution error in our guide to uncertainties](https://physics-50.github.io/Module-1/uncertainty-introduction#resolution-uncertainty).


## Combining Uncertainties

Before collecting and analyzing your data this week, please make sure that you have read this [discussion about combining uncertainties](https://physics-50.github.io/Module-1/uncertainty-introduction#combining-uncertainties)

To make sure you've understood these ideas, please complete the following mini-question. This is going to come up repeatedly throughout the rest of the course. If you have any questions about your response please stop by office hours and talk to us or consult with your classmates through Piazza.

---------------


#### Mini-question 4: Combining Random and Resolution Uncertainty
[*Click here to open in a new tab*](https://forms.gle/KMCCqJZxdkchbBvdA){:target="_blank"}
<iframe src="https://docs.google.com/forms/d/e/1FAIpQLSc7wj6OMBqqybagJhwZb0-Mkk8UnW2WOf5G7v474S0ryLvJOw/viewform?embedded=true" width="640" height="600" frameborder="0" marginheight="0" marginwidth="0">Loading…
</iframe>

--------------------------------------------------- --> 

Graph your data and fit a line to it using [the Physics 50 fitting routine](https://physics.hmc.edu/fitter){:target="_blank"}. Use the fit results to evaluate the quality of your data set.  If you are satisfied with it, calculate a final result for $$d\pm \delta d$$ based on the slope of the best-fit line and its uncertainty.

## Things to Turn In

Since this week is an intermediate week in lab, you will have a checkpoint due on Gradescope three days before the next lab meeting (see syllabus).

-------------


## Mini-questions:

And to double-check, make sure you have finished all of this week's mini-questions by [checking here](mini-questions#week-1){:target="_blank"}.
