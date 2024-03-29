# Week 2

--------------
1. [Overview of Week 2](#overview-of-week-2)
2. [Why we measure $$x$$ over a range of $$L$$ values](#why-we-measure-x-over-a-range-of-l-values)
3. [Data Collection](#data-collection)
4. [Checkpoint 2](#checkpoint-2)
5. [Mini-questions](#mini-questions)

--------------

## Overview of Week 2

This week we will investigate how the distance $$x$$ to the first non-central bright spot depends on $$L$$, the distance between the grating and the screen. This will lead you to a determination of the wavelength of your laser; we will do this roughly first with a single data point, but ultimately our approach will be to plot $$x$$ vs. $$L$$ and find the best fit line to that data.

Using your 500-line/mm grating, you will take data carefully (including repeated trials) for $$x$$ as a function of $$L$$ over a large range of the $$L$$ values accessible with your apparatus.  You will plot $$x$$ vs. $$L$$ to check for systematic errors and to find a value for $$\lambda$$, the wavelength of your laser, based on the slope of your data set.

Before starting this longer program of measurements, it is useful to do a very quick "back-of-the-envelope" check to make sure that your value for wavelength will be roughly in the range you'd expect (620--700 nm for red light).  From the [background theory](background-theory){:target="_blank"} presented last week, we can solve for $$\lambda$$ in terms of known and measured quantities to find $$\lambda = \frac{x d}{\sqrt{L^2 + x^2}}$$.  Go back to the data you collected last week. Pick a single pair of $$L$$ and corresponding $$x$$, and check whether the value of $$\frac{x d}{\sqrt{L^2 + x^2}}$$ lies within the range you expect for the wavelength.  Through this single-shot estimate, you are providing a reality check on your data collection and also on your process for recording data and using it in calculations (e.g., unit conversions, parentheses in formulas).

## Why we measure $$x$$ over a range of $$L$$ values

Why don't we just continue this approach over multiple trials to get a more reliable result?  That is, why not analyze multiple data points by measuring $$x$$ each time, determining $$\lambda = \frac{(x/L) d}{\sqrt{1 + (x/L)^2}}$$ for each measurement, and then averaging those? One of the ideas we would like you to take away from this course is to think of a data set as a whole, not as individual points.  $$L$$ provides us with an independent variable that we can control, so by measuring $$x$$ over a range of $$L$$ values, we can create a plot of $$x$$ versus $$L$$ data. Plotting the data and looking at the data set as a whole gives us confidence in our ability to determine $$\lambda$$, since it allows us to fit the data to the theoretical prediction in a more robust way.  We will outline the approach before pointing out some of its advantages.

Thinking back to the theoretical prediction, let's rewrite that equation in a more suggestive form
\begin{equation}
\lambda = \frac{(x/L) d}{\sqrt{1+(x/L)^2}} = \frac{md}{\sqrt{1+m^2}}
\end{equation}
where we have introduced the parameter $$m=x/L$$, the slope of a plot of $$x$$ vs. $$L$$.

Let's start with a practice calculation.

------
#### Mini-question 1: Calculating wavelength from slope
[*Click here to open in a new tab*](https://forms.gle/MPYx6nPVd54jYE359){:target="_blank"}
<iframe src="https://docs.google.com/forms/d/e/1FAIpQLSct57YgYJ1rxsHAkhGfOk_QUB638pb_MYeH7vhVZU2MGQUW5w/viewform?embedded=true" width="640" height="400" frameborder="0" marginheight="0" marginwidth="0">Loading…
</iframe>

---------------------------

There's an added power to treating the data set as a whole in this way because if our data has an intercept that isn't zero, then that would suggest a systematic error that shifted our measured values!  Consider this: what if there is a systematic uncertainty in $$L$$, _e.g._, because you accidentally measured to one edge of a post holder or because your ruler didn't start at zero? Then a set of $$\lambda$$ values calculated from your individual trials would be systematically off. However, plotting a line will still give the correct slope.  In this case the line will have a non-zero intercept that tells you about the systematic shift in $$L$$, as shown in the plot below, where the fitting parameter $$b$$ shown in the legend is clearly not equal to zero.

<img src="images/x_vs_L_offset.png" alt="basic setup" width="400" style="display: block; margin-left: auto; margin-right: auto; width: 80%;" />

To graph your data and perform a weighted linear fit, you will make use of the [same fitting script used earlier in this course](https://physics.hmc.edu/fitter/). Under "kind" you should select *linear* for a plot that includes a line of best fit. Make sure to label the axes appropriately for this experiment.  You may also want to review the [guide to interpreting plots with a least squares fit](https://physics-50.github.io/Module-1/interpreting-plots) to reinforce your understanding of how to interpret fit parameters, $$ \chi_{\nu}^2 $$ values, and other aspects of your result.

#### Mini-question 2: Interpreting a weighted linear fit
[*Click here to open in a new tab (recommended)*](https://forms.gle/BF8fQq5PNWF1Gh9U8){:target="_blank"}
<iframe src="https://docs.google.com/forms/d/e/1FAIpQLSdTk_l5gJ2boQzujZcgNKYh55iSlxR9UZNke6sgi3Chk_dvmA/viewform?embedded=true" width="640" height="400" frameborder="0" marginheight="0" marginwidth="0">Loading…
</iframe>

<br>

Before moving on, take a moment to consider how to calculate the uncertainty in the wavelength. Before completing the following mini-question you may find it helpful to review the [video on how to propagate uncertainties](https://physics-50.github.io/Module-1/helpful-guidance) from module 1.


-----------
#### Mini-question 3: Determining the uncertainty in the wavelength
[*Click here to open in a new tab (recommended)*](https://forms.gle/zKu1G3j3MG57xZhs8){:target="_blank"}
<iframe src="https://docs.google.com/forms/d/e/1FAIpQLSdsX9HYql9BGssjbNypZIRZZsAie0RDPwOavr7ixLMExrVtQA/viewform?embedded=true" width="640" height="400" frameborder="0" marginheight="0" marginwidth="0">Loading…
</iframe>


--------------



## Data Collection

**This week you will collect data only for the 500 line/mm grating spacing.**

When collecting data this week we would like you to take into consideration the sources of uncertainty you explored in Week 1 and do your best to minimize uncertainty and randomize systematic error by resetting the sensitive parameters between each trial. Please take a moment right now to go back to [Mini-question 3 from Week 1](https://docs.google.com/forms/d/e/1FAIpQLSe-Bcw3iqEcmblnBnsOJOqSbfHVNrXckA4mVs9VEvzOXHvZQQ/viewform){:target="_blank"} and review your answers to determine which parameters you need to reset and which you don't.

To collect your complete $$x$$ vs. $$L$$ dataset, make sure to do the following:

+ Choose five values of $$L$$ ranging from about 15 cm to as large a value of $$L$$ as you can while keeping the first diffraction maximum on the provided screen (this should be about 60 cm).

+ Collect five measurements of $$x$$ for each $$L$$ value, making sure that between each measurement of $$x$$ you reset all the parameters you determined you needed to in  [Miniquestion 3 from Week 1](https://docs.google.com/forms/d/e/1FAIpQLSe-Bcw3iqEcmblnBnsOJOqSbfHVNrXckA4mVs9VEvzOXHvZQQ/viewform){:target="_blank"}. Be sure to **only use the 500 line/mm diffraction grating.**  Please use the tab: "Week 2: Data: 500 lines/mm" in your Google Sheets spreadsheet to collect your data. You will need to enter the formulas to calculate the mean value and uncertainty. 

+ For each $$L$$ value, compute the mean value of $$x$$ from your five trials and the random uncertainty as measured by the SEM.

+ Prepare a .csv file with your $$x\pm \delta x$$ and $$L$$ data. There is a new tab in your Google Sheets worksheet, prepared for this: "Week 2: Plotting 500 lines/mm data". Be sure to change the column headings to reflect your data as these will appear as axis labels on your fit.

+ Load the .csv file with your data into the [curve fitting script introduced previously](https://physics.hmc.edu/fitter/), selecting "linear" under the "kind" pull-down menu. 

+ You should make use of your data, the best-fit analysis and the provided theory to determine the wavelength of your laser. You will need to use the methods you have been taught in previous modules to propagate your uncertainty and determine the uncertainty in your final result. 



-------------

## Checkpoint 2

Checkpoint 2 will take place in two parts:


**Part 1: Practice calculation**
*You may resubmit Module 2, checkpoint 2, Part 1 as many times as you like until you get the correct answer (it is auto-graded and will give you an immediate response). For this part **only** it is also okay to "save" your responses to the individual questions.*

Part 1 is a practice calculation; please complete the problem on Gradescope. You are welcome to complete this practice calculation before your time in lab to be better prepared to complete the analysis in class.

**Part 2: Post-lab analysis**

For part 2 our usual rules apply:
**Reminder:** Please prepare your assignment in a separate document, enter all entries in a single sitting without using the "save" button and then make use of the "submit" button to submit your work. You may not resubmit your work once it has been submitted (and saving in Gradescope is equivalent to submitting).

You should submit the following on Gradescope:

+ The plot used to determine the wavelength of your laser. This plot must include the uncertainties of your data points and a line of best fit that has been determined with a weighted fit. As always, make sure to include units on your axis labels. You will be asked to upload this plot 3 times. You should upload the same plot each time. You do not need to write a caption.

+ A link to your assigned Google Sheets spreadsheet with your experimental data and analysis.

+ The slope you obtained from your plot, including the uncertainty.  Do not round, as this is not a final result.

+ The wavelength you have determined for your laser, with uncertainty.  This is a final result, so follow guidelines for significant figures.

+ A list of the parameters you reset between each $$x$$ measurement.

------------

## Mini-questions:

And to double-check, make sure you have finished all of this week's mini-questions by [checking here](mini-questions#week-2){:target="_blank"}.
