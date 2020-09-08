# Week 3:  Final Determination of Viscosity -- DRAFT


--------------

1. [Thinking Through Systematic Errors](#thinking-through-systematic-errors)
2. [Week 3 To-Do Summary](#week-3-to-do-summary)
3. [Checkpoint: Final Viscosity and Uncertainty](#checkpoint-3)

------------------


**Make sure you have your [Module 2 Data Sheet and Lab Notebook](https://classroom.google.com/c/MTI2NjQ0NDEyMTAx/a/MTI3ODQ4MDY2NDMx/details){:target="_blank"} handy as you go through the content on this Week 2 page.**
*The link is still to Module 1 -- need to fix.*

## Thinking Through Systematic Errors

In Week 2 we discussed the idea of systematic error and you may have brainstormed various possible sources of systematic error in this experiment, beyond the presence of inertial drag.  However, your investigations in Week 2 were focused on understanding the effect of inertial drag and focusing on data for which that effect is minimal.  That investigation set you up with a plan for finding a final viscosity value and uncertainty, based on judicious use of the data available to you.  Before you embark on that final process, let's take some time to consider some other possible sources of systematic error.

#### 1 Systematic Error from Ruler Calibration?  Randomized!

One factor you might have put on your list is incorrect pixels-to-distance calibration.  Our calibration of distance affects the terminal speed we extract from each video and thus the viscosity we calculate.  The short video GOPR0702.mp4 shows what could happen if the calibration ruler is placed too far forward or too far backward relative to the location where the sphere actually falls; you can see that if ruler is forward/backward of the actual sphere drop, the pixels-to-distance calibration based on the ruler will be slightly off.  Using the video and stepping through your method for finding terminal speed and then viscosity, answer the following question:

#### Miniquestion: How Ruler Placement Affects Results
*[Click here to open in a new tab](https://docs.google.com/forms/d/e/1FAIpQLSfgLlDCQo_g__WABqmSmHxOC2VvgXbUYT6GBc_g0vER5hY93A/viewform){:target="_blank"}*


<iframe src="https://docs.google.com/forms/d/e/1FAIpQLSfgLlDCQo_g__WABqmSmHxOC2VvgXbUYT6GBc_g0vER5hY93A/viewform?embedded=true" width="640" height="300" frameborder="0" marginheight="0" marginwidth="0">Loading…
</iframe>

------------------

So how does this actually affect our results, since we placed the ruler separately in each video, as close as we could to the correct spot?  We can presume that when we tried to hit the correct spot each time, we were sometimes slightly in front and sometimes slightly behind.  Because we did this calibration from scratch for every single trial, the shifts caused by an incorrect ruler calibration are already built into the trial-to-trial variation we see in our measured terminal speeds!  This is an example of experimental design to randomize what could otherwise have been an unknown systematic error in our experiment.


#### 2 Systematic Error from Sphere Diameter and Mass?  Probably Randomized!

Terminal speed is not the only measured quantity that goes into our calculation of viscosity.  The mass and diameter of the sphere are also important, so we shoud examine our knowledge of these a bit more closely.  Our mass measurements had some trial-to-trial variation, while our diameter measurements were primarily limited by resolution error.  A more complete version of the sphere data table from Week 1 is shown below:

| Nominal Sphere Diameter | Average Mass | Standard Error of Mass | Measured Diameter |
| ----------------------- | ------------ | ---------------------- | ----------------- |
| 1.8 mm                  | 0.02453 g    | 0.00007 g              | 1.80 mm           |
| 2.5 mm                  | 0.06554 g    | 0.00007 g              | 2.495 mm          |
| 3.5 mm                  | 0.1772 g     | 0.0001 g               | 3.47 mm           |
| 4.5 mm                  | 0.3812 g     | 0.0002 g               | 4.50 mm           |
| 6.0 mm                  | 0.8997 g     | 0.0002 g               | 5.99 mm           |

The variatin in measured masses suggests there may be some variation in diameters that our digital calipers simply lack the digits to resolve.  For example, for the nominal 3.5-mm diameter spheres, our measurements of ten sphere diameters all came out to 3.47mm, but what if they actually ranged between about 3.467mm and 3.473mm?  This would roughly explain the variations in measured masses (mean mass 0.1772 g, but individual measurements ranged from 0.1768 g to 0.1777 g).  

How much should we worry about this?  If we had used a single sphere for each trial, then we would have a systematic error in our viscosity results if that sphere were actually slightly larger or smaller than the values we used in our calculation.  But we used a different sphere in each trial -- so the variation in terminal speeds should automatically be averaging over the range of sphere diameters and masses already!

One caveat remains:  because we used different spheres for each trial, the effect of sphere-to-sphere size variation is automatically included in the variation in terminal speed values.  However, this does not quite insure is against the possibility that the sphere diameters are distributed around some true average value that is not exactly 3.470 mm (or 1.800 mm or 2.495 mm).  Thus we could have a small systematic error in our viscosity results from sphere diameter despite our best efforts.


#### 3 Systematic Error from Liquid Density Value and Acceleration Due to Gravity

Back in Week 1 we reported our best values for the liquid density $$\rho$$ and the acceleration due to gravity in Claremont, $$g$$.  Each of these has an associated uncertainty (given in Week 1).  These uncertainties cause systematic errors in our viscosity results.  Since we use the same beaker full of liquid and the same location in each trial, our uncertainty in $$\rho$$ and our uncertainty in $$g$$ each contribute a systematic error in $$\eta$$ that is NOT included in the trial-to-trial variation.

#### 4 Do the Students Know How to Calculate an Overall Uncertainty from Several Independent Sources?

If they haven't been taught the method of adding in quadrature, then we should write it up / teach it here.  Otherwise we can just refer to it.


## Week 3 To-Do Summary

In Week 3 you will carefully analyze whichever set(s) of sphere-drop data you believe offer the most reliable basis for finding the viscosity of our glycerin solution.  You will use your careful analysis to determine your best value for the viscosity and for its uncertainty, based on all the considerations of Weeks 1-3.

## Checkpoint 3

+ Submit your Week 3 results in [Checkpont 3 on Gradescope](){:target="_blank"} by the end Week 3.  You should submit what you believe will be your final value of viscosity and its associated uncertainty, with units.  *Assignment not yet created or linked.  Do we just want these two numbers, or something more?*

+ And to double-check, make sure you have finished all of this week's mini-questions by [checking here](mini-questions#week-3){:target="_blank"}

## Final Note

When you're ready, move on to Week 4 - Scientific Communication.
