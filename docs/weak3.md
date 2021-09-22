## Week 3

1. [Background: Data Analysis](#background:-data-analysis)
2. [Instructions: In Lab this Week](#instructions:-in-lab-this-week)
3. [Checkpoint #3](#checkpoint-#3)

### Background: Data Analysis
One of the most important ideas we want you to take from Module 2 is to think of a data set as a whole, not as individual points. 

In the analysis you completed in weeks 1 and 2, you measured the spacing between a single, fixed number of nodes. But the “node number” provides us with an independent variable that we can control, so by measuring the position of multiple nodes, we can create a plot of position versus node number data. Plotting the data and looking at the data set as a whole gives us confidence in our ability to determine the speed of sound, since it allows us to fit the data to the theoretical prediction in a more robust way. You do not need beads in every node to use this method, but you do need to use sound judgement and consistency with the theory to appropriately assign the node numbers to your levitated beads. 

At the end of module 1 we introduced MATLAB and made use of it to fit a horizontal line of best fit. In this module we will continue to make use of MATLAB for data analysis. 

How do we extract a slope from our measured data? You have previously fit a horizontal line, but now you will fit a line with a nonzero slope. To understand this fitting process, you now need to carefully read the [curve fitting guide](curve-fitting){:target="_blank"}. In it you will find a MATLAB script that includes a linear fit with both an intercept and a slope.

To ensure you are prepared to analyze your data, please make use of the following figure to answer the subsequent mini-question.

[![Image of sample data](images/sample_data-beads.png)](images/sample_data-beads.png){:target="_blank"}
----

#### Miniquestion 1: Estimating the speed of sound from a sample plot
[*Click here to open in a new tab*](https://docs.google.com/forms/d/e/1FAIpQLSdyYDI3QEI4FDsfW4d0M4krPmhwPUsgcYBsDG48WcajfMYhgg/viewform?usp=sf_link){:target="_blank"}

<iframe src="https://docs.google.com/forms/d/e/1FAIpQLSdyYDI3QEI4FDsfW4d0M4krPmhwPUsgcYBsDG48WcajfMYhgg/viewform?embedded=true" width="640" height="300" frameborder="0" marginheight="0" marginwidth="0">Loading…
</iframe>

-----

## Instructions: In Lab This Week

Make sure you are using the same levitator as last week (you should have made note of the levitator number)

Last week should have convinced you that Parallax is a significant source of uncertainty in this experiment. You also should have come up with a strategry to minimize its effect and then estimated the magnitude of its effect through multiple trials in which you randomized the position of the ruler as well as the relative position of the camera and levitator.

This week we are going to collect a data set that will allow us to obtain a more accurate estimate of the speed of sound by fitting a line representing the bead position as a function of node number as discussed above.

To do this you will need a reliable mark on your levitator that you can use as a consistent origin to compare data from multiple photos. This should not be a bead (can you think why? If unsure talk to your section instructor) and also should be attached to the levitator (if you instead used for example a point on the table there is a risk it might move between images, e.g. if the levitator moved). This time you want to position as many beads in the levitator as you can. Aim for at least 5. It is okay if you skip some nodes as long as you keep track of where they are. 

Your goal is to use several distinct photos to estimate the position of each node (based on the position of beads). To prepare for this you will want to set up a sheet in your assinged spreadsheet for this module. At the top you will want to indicate that you are measuring the position of beads relative to the origin in (mm). You will want to assign a column for each node #. Note that while the assignment of which node is "node 1" is arbitrary but needs to be at a consistent location between photos. That means that if you assign "node 1" to be the left-most bead in your first photo and then have a later photo in which you were able to levitate more beads further to the left you will have to assign these "node 0", "node -1", ... extending leftward. This is fine. The y-intercept of your plot of bead position v.s. node number is arbitrary in this case, we are only interested in the slope.

Like last week you should reposition the ruler as well as the position of the levitator relative to the camera in between each measurement, but this time you will also need to levitate a fresh set of beads for each photo.

You should aim to have at least 5 beads for each of at least 5 different node numbers (coming from multiple photos). For each node number you will make use of the mean value for the bead position with an uncertianty estimated from the SEM for your plot of bead posiiton v.s. node number. You may not trap beads in exactly the same set of nodes each time. You may therefore end up with some nodes with more or less data than others. This is okay. However, if you have 3 or fewer data points for a given node you should make use of the spread in the data rather than the SEM to estimate the uncertainty (representing the uncertainty as the full spread between the smallest and largest data point for that node). This is because it is statistically meaningless to compute the SEM with 3 or fewer data points. You should not use any data from nodes for which you only have a single data point as you have no way to estimate the uncertainty for those data points.

Once you are satisified with your data set, prepare a plot of bead position v.s. node number with the curve fitting script provided at the start of this week's instructions.

Like for module 1, you will need an uncluttered image or image(s) of your experimental set-up (with a scalebar) for your deliverable. You may already have what you need in photos you've collected this module, but just in case, before leaving lab take a moment to think if you need to take any additional photos to showcase your experimental procedure in the deliverable.

Make sure to note which levitator you are using (hopefully you did this last week and used the same one this week)

# Checkpoint #3

+ a link to your organized spreadsheet in which you have calculated the mean bead posiiton and uncertainty for each node position. For any nodes for which you only have a single data point please indicate that the uncertainty is undetermined and do not use that data point in your plot. 

+ a plot of bead position v.s. node number, prepared in MATLAB. Each data point should have an uncertainty from multiple measurements following the instructions in this week's manual. Please display the fit parameters including the $$\Chi^2$$ value on the plot (the provided script will do this for you)

+ a calculation of the speed of sound with uncertainty based on your line of best fit to the previous plot









