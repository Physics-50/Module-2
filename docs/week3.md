# Week 3:  Final Determination of Viscosity -- DRAFT


--------------

1. [Thinking Through Systematic Errors](#thinking-through-systematic-errors)
2. [Mathematical Tools for Final Value and Uncertainty](#mathematical-tools-for-final-value-and-uncertainty)
3. [Week 3 To-Do Summary](#week-3-to-do-summary)
4. [Checkpoint: Final Viscosity and Uncertainty](#checkpoint-3)

------------------


**Make sure you have your [Module 2 Data Sheet and Lab Notebook](https://classroom.google.com/c/MTI2NjQ0NDEyMTAx/a/MTYyMDg1ODM5NjY3/details){:target="_blank"} handy as you go through the content on this Week 2 page.**

## Thinking Through Systematic Errors

In Week 2 we discussed the idea of systematic error and you may have brainstormed various possible sources of systematic error in this experiment, beyond the presence of inertial drag.  However, your investigations in Week 2 were focused on understanding the effect of inertial drag and identifying data for which that effect is minimal.  That investigation set you up with a plan for finding a final viscosity value and uncertainty, based on judicious use of the data available to you.  Before you embark on that final process, let's take some time to consider some other possible sources of systematic error.

#### 1 Systematic Error from Ruler Calibration?  Randomized!

One factor you might have put on your list is error in the pixels-to-distance calibration.  Our calibration of distance affects the terminal speed we extract from each video and thus the viscosity we calculate.  The short video [GOPR0702.mp4](https://drive.google.com/file/d/11u-_Ott90CjFBwaUwRasEXF7gqRn2tDB/view?usp=sharing){:target="_blank"} shows what could happen if the calibration ruler is placed too far forward or too far backward relative to the location where the sphere actually falls; you can see that if the ruler is forward/backward of the actual sphere drop, the pixels-to-distance calibration based on the ruler will be slightly off.  Using the video and stepping through your method for finding terminal speed and then viscosity, answer the following question:

#### Miniquestion 1: How Ruler Placement Affects Results
*[Click here to open in a new tab](https://docs.google.com/forms/d/e/1FAIpQLSfgLlDCQo_g__WABqmSmHxOC2VvgXbUYT6GBc_g0vER5hY93A/viewform){:target="_blank"}*


<iframe src="https://docs.google.com/forms/d/e/1FAIpQLSfgLlDCQo_g__WABqmSmHxOC2VvgXbUYT6GBc_g0vER5hY93A/viewform?embedded=true" width="640" height="300" frameborder="0" marginheight="0" marginwidth="0">Loading…
</iframe>

------------------

So how does this actually affect our results, since we placed the ruler separately in each video, as close as we could to the correct spot?  We can presume that when we tried to hit the correct spot each time, we were sometimes slightly in front and sometimes slightly behind.  Because we did this calibration from scratch for every single trial, **the shifts caused by an incorrect ruler calibration are already built into the trial-to-trial variation we see in our measured terminal speeds!**  This is an example of experimental design to randomize what could otherwise have been an unknown systematic error in our experiment.


#### 2 Systematic Error from Sphere Diameter and Mass?  Probably Randomized!

Terminal speed is not the only measured quantity that goes into our calculation of viscosity.  The mass and diameter of the sphere are also important, so we shoud examine our knowledge of these a bit more closely.  Our mass measurements had some trial-to-trial variation, while our diameter measurements were primarily limited by resolution error.  For example, for the nominal 3.5-mm diameter spheres, our measurements of ten sphere diameters all came out to 3.47mm.

| Nominal Sphere Diameter | Average Mass | Standard Error of Mass | Measured Diameter |
| ----------------------- | ------------ | ---------------------- | ----------------- |
| 1.8 mm                  | 0.02453 g    | 0.00007 g              | 1.80 mm           |
| 2.5 mm                  | 0.06554 g    | 0.00007 g              | 2.495 mm          |
| 3.5 mm                  | 0.1772 g     | 0.0001 g               | 3.47 mm           |
| 4.5 mm                  | 0.3812 g     | 0.0002 g               | 4.50 mm           |
| 6.0 mm                  | 0.8997 g     | 0.0002 g               | 5.99 mm           |

The variation in measured masses suggests there may also be some variation in diameters that our digital calipers simply lack the digits to resolve.  What if the diameters of the 3.5-mm spheres actually ranged between about 3.467mm and 3.473mm?  This would roughly explain the variations in measured masses (mean mass 0.1772 g, but individual measurements ranged from 0.1768 g to 0.1777 g).  

How much should we worry about this?  If we had used a single sphere for all the videos, then we would have a systematic error in our viscosity results if that sphere were actually slightly larger or smaller than the values we used in our calculation.  But we used a different sphere in each video -- so the variation in terminal speeds should automatically be averaging over the range of sphere diameters and masses already!

One caveat remains:  because we used different spheres for each trial, the effect of sphere-to-sphere size variation is automatically included in the variation in terminal speed values.  However, this does not quite insure us against the possibility that the sphere diameters are distributed around some true average value that is not exactly 3.470 mm (or 1.800 mm or 2.495 mm ...).  Thus we could have a small systematic error in our viscosity results from sphere diameter despite our best efforts.  However, results from each nominal sphere diameter would not all be shifted in the same direction, or at least there is no reason to suppose that would be the case.  Using data from several nominal sphere diameters might allow us to randomize this sytematic error as well.


#### 3 Systematic Error from Liquid Density Value and Acceleration Due to Gravity

Back in Week 1 we reported our best values for the liquid density $$\rho$$ and the acceleration due to gravity in Claremont, $$g$$.  Each of these has an associated uncertainty (given in Week 1):  $$\rho=1.241 \pm 0.003 \mathrm{g}/\mathrm{cm}^3$$ and $$g=9.7959 \pm 0.0001 \mathrm{m}/\mathrm{s}^2$$.  We have used the values $$\rho=1.241 \mathrm{g}/\mathrm{cm}^3$$ and $$g=9.7959 \mathrm{m}/\mathrm{s}^2$$ in all our calculations, but these values could be slightly shifted from the true liquid density and acceleration due to gravity.  Since we use the same beaker full of liquid and the same location in Earth's gravitational field in each video, our uncertainty in $$\rho$$ and our uncertainty in $$g$$ each contribute a systematic error in $$\eta$$ that is NOT included in the trial-to-trial variation.  For each of these, we can find out the size of the systematic error in $$\eta$$ by treating every other quantity in the $$\eta$$ formula as a constant and propagating the error due to just $$\delta\rho$$, or due to just $$\delta g$$.


## Mathematical Tools for Final Value and Uncertainty

At this point you have quite a few things to take into account as you work toward your final value for the liquid viscosity and its uncertainty.  Two mathematical tools will probably be useful at this stage.  The first, which might be useful as you find your final viscosity *value*, is a technique for averaging several different values that have different uncertainties.  The second, which might be useful as you find your overall *uncertainty*, is a reminder of how to mathematically combine several independent sources of error.

#### 1 Weighted Average of Several Values with Uncertainties

If you have decided that data from several sphere sizes can be used reliably to find viscosity, you may be wondering how to combine the viscosity values and random errors from different sphere sizes to get a single final value.  Before you are ready to do this, you will need to analyze multiple videos of each chosen sphere size; unlike Week 2, this is no longer an exploratory analysis, and for each chosen sphere size you will need to do a full, multi-trial analysis like the one you did for 3.5-mm spheres in Week 1.  After you have done this, you will have multiple viscosity values $$\eta_1, \eta_2, ..., \eta_n$$ which each have their own random error $$\delta\eta_1, \delta\eta_2, ..., \delta\eta_n$$.  How should you combine these to get the best final value for viscosity?  What is the correct random error for that final value?

Just averaging the different values is not the best method, because some of the values are more certain than others.  If we are getting directions in a strange town, we naturally weight conflicting advice according to how certain each person seems about the directions they are giving us.  We need to do something similar -- but more quantitative -- with our several viscosity values.  It makes sense to do a *weighted* average, in which the values with smaller uncertainties are given the most weight in determining the final value.  A much more detailed mathematical analysis leads to a specific formula for the best weighted average and its uncertainty.  The best weighted average is:

$$\eta_{weighted} = \frac{\frac{1}{(\delta\eta_1)^2}\eta_1 + \frac{1}{(\delta\eta_2)^2}\eta_2 + ... + \frac{1}{(\delta\eta_n)^2}\eta_n}{\frac{1}{(\delta\eta_1)^2} + \frac{1}{(\delta\eta_2)^2} + ... + \frac{1}{(\delta\eta_n)^2}}$$

and its random error is best represented by:

$$\delta\eta_{weighted} = \frac{1}{\sqrt{n}}\sqrt{\frac{\frac{1}{(\delta\eta_1)^2}(\eta_1-\eta_{weighted})^2 + \frac{1}{(\delta\eta_2)^2}(\eta_2-\eta_{weighted})^2 + ... + \frac{1}{(\delta\eta_n)^2}(\eta_n-\eta_{weighted})^2}{\frac{1}{(\delta\eta_1)^2} + \frac{1}{(\delta\eta_2)^2} + ... + \frac{1}{(\delta\eta_n)^2}}}$$

You do not need to understand the detailed justification of these formulas -- in fact, we have not presented it at all -- but you should be able to use the formulas to combine several values with different random errors.  The following miniquestion asks you to practice that skill.

#### Miniquestion 2: Weighted Average with Random Errors
*[Click here to open in a new tab](https://docs.google.com/forms/d/e/1FAIpQLSeW-8yZSb0sUzIWmsd7WmYPsJQJpFcopulOO81FoRn0jRWqbA/viewform){:target="_blank"}*


<iframe src="https://docs.google.com/forms/d/e/1FAIpQLSeW-8yZSb0sUzIWmsd7WmYPsJQJpFcopulOO81FoRn0jRWqbA/viewform?embedded=true" width="640" height="300" frameborder="0" marginheight="0" marginwidth="0">Loading…
</iframe>

------------------

#### 2 Adding Independent Uncertainties in Quadrature

After you have found your best overall viscosity value and random error, you may still have some separate systematic errors to take into account.  In Module 1 you read about a method for combining uncertainties from several independent sources; we remind you of it quickly here.  By "independent sources," we mean factors that have no correlation, i.e., that have no particular reason to cause errors in the same direction as each other (or in opposite directions) when it comes to the final value.  One source of error steps us away from the true value in one direction, and the next source steps us either in the same direction or back toward the true value -- but we have no way of knowing which.  In this case the theory of random walks tells us to estimate our overall distance from the final value by combining the independent errors *in quadrature* as follows:

$$\delta\eta_{final} = \sqrt{(\delta\eta_{random})^2 + (\delta\eta_{systematic1})^2 + (\delta\eta_{systematic2})^2 + ...}.$$

However, remember that you will only report the most significant digit of the final uncertainty value.  Therefore, if one of the contributing $$\delta\eta$$ terms in the expression above is much larger than the others, then actually using the formula above turns out to be overkill!  In this situation you will do just as well by simply using the largest $$\delta\eta$$ contribution and ignoring the others.  How much larger is "much larger?"  One $$\delta\eta$$ contributor that is just 2-3 times the sum of the others turns out to be large enough to be dominant; you can play with the formula above if you want to convince yourself that this is true.


## Week 3 To-Do Summary

In Week 3 you will carefully analyze whichever set(s) of sphere-drop data you believe offer the most reliable basis for finding the viscosity of our glycerin solution.  For example, you may now need to analyze multiple videos for some sphere sizes.  Use appropriate data from your careful analysis to determine your best value for the viscosity and for its uncertainty, based on all the considerations of Weeks 1-3.

## Checkpoint 3

+ Submit your Week 3 results in [Checkpont 3 on Gradescope](){:target="_blank"} by the end Week 3.  You should submit what you believe will be your final value of viscosity and its associated uncertainty, with units.  *Assignment not yet created or linked.  Do we just want these two numbers, or something more?*

+ And to double-check, make sure you have finished all of this week's mini-questions by [checking here](mini-questions#week-3){:target="_blank"}

## Final Note

When you're ready, move on to Week 4 - Scientific Communication.
