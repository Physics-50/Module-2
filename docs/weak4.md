## Week 4: Preparation of your Deliverable

1. [Background: Data Analysis](#background-reading-for-data-analysis)
2. [Instructions: In Lab this Week](#instructions-for-in-lab-this-week)
3. [What you need to leave lab with this week](#what-you-need-to-leave-lab-with-this-week)
3. [Checkpoint #3](#checkpoint-#3)

You are not required to attend lab this week but are welcome and encouraged to do so to ask questions of your instructor (help is also available through office hours).

Your goal this week is two-fold

+ Complete the analysis of the data you collected last week
+ Prepare your deliverable

## Data Analysis


Last week you should have taken 5 photos for which you reset the beads and ruler between each image. Each photo should have at least 5 levitated beads, hopefully more.

Last week you also analyzed the results from one photo. This week you will make use of all 5 photos to estimate the uncertainty in your determination of the position of each pressure node.

Your first step this week is to measure and record in your spreadsheet the position of each bead across the 5 images. Make sure you are using a consistent origin. Remember that the origin should be stationary with respect to the levitator and must not be a bead.

For each node number you will make use of the mean value for the bead position with an uncertainty estimated from the standard error of the mean.

You may not have trapped beads in exactly the same set of nodes each time. You may therefore end up with some nodes having more or less data than others. This is okay. However, if you have 3 or fewer data points for a given node you should make use of the spread in the data---rather than the SEM---to estimate the uncertainty (representing the uncertainty as the full spread between the smallest and largest data point for that node). This is because it is statistically meaningless to compute the SEM with 3 or fewer data points. You should not use any data from nodes for which you only have a single data point as you have no way to estimate the uncertainty for those data points.

Once you have collected this data you are ready to prepare your plot of bead position vs. node number. 

For week 4 data analysis (and also for use in module 3) please download this file for [weighted curve fitting of data with uncertainties](curve_fitting.m) and run the script. This script differs from the version you used last week in that the fit is weighted by the uncertainty of the individual data points. You may want to refer back to the information provided in the [curve fitting guide](curve_fitting).

+ A link to your organized spreadsheet in which you have calculated the mean bead position and uncertainty for each node position. For any nodes for which you only have a single data point please indicate that the uncertainty is undetermined and do not use that data point in your plot. 

+ A plot of bead position vs. node number, prepared in MATLAB. Each data point should have an uncertainty from multiple measurements following the instructions in this week's manual. Please display the fit parameters including the $$\chi_\nu^2$$ value on the plot (the provided script will do this for you).

+ A calculation of the speed of sound with uncertainty based on your line of best fit to the plot.

+ A statement responding to the following question: Based on the Matlab provided fit parameters, particularly the reduced $$\chi^2$$ value, do your error bars appear to do a good job representing the uncertainty in the experiment? Please answer in 1--2 sentences.

