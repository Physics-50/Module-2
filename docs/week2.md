# Week 2: Exploratory Phase (continued) -- DRAFT


--------------

1. [Systematic Errors](#systematic-errors)
2. [Viscous and Inertial Drag](#viscous-and-inertial-drag)
3. [Week 2 To-Do Summary](#week-2-to-do-summary)
4. [Checkpoint: So-Called Viscosity vs Sphere Diameter](#checkpoint-2)

------------------


**Make sure you have your [Module 2 Data Sheet and Lab Notebook](https://classroom.google.com/c/MTI2NjQ0NDEyMTAx/a/MTI3ODQ4MDY2NDMx/details){:target="_blank"} handy as you go through the content on this Week 2 page.**
*The link is still to Module 1 -- need to fix.*

## Systematic Errors

#### 0 Find a Preliminary Viscosity Value

From Week 1, you should have measured the terminal velocity of a 3.5-mm diameter sphere from several different videos, and calculated the average terminal speed $$v_T$$ and the standard error $$\delta v_T$$.  From that you calculated a preliminary viscosity $$\eta$$ for our glycerin solution, and propagated the uncertainty to calculate $$\delta\eta$$ based on the random error in your terminal velocity results.  If that isn't the case, please revisit [Week 1](week1) and [ask for help on Piazza](https://piazza.com/class/kdyuyniyaz052s){:target="_blank"} or [come to Office Hours](https://sakai.claremont.edu/portal/site/CX_mtg_130832/page/8bb99f43-12a4-4f97-8e47-802814328a26){:target=_"blank"}. 


#### 1 Systematic Errors

In Module 1 you learned about random and systematic errors.  Random errors cause variation in your results from trial to trial; the variation produces a distribution of results that is probably centered on the actual value you are trying to determine, so the presence of random error limits the *precision* of your measurement but not its *accuracy*.  Systematic errors, on the other hand, are consistent shifts of your results in one direction; they may allow for a deceptively high *precision* in your measurement but could be limiting the *accuracy*.  In Module 2, we will learn more about systematic errors and how to either minimize them or turn them into random errors -- thus at least avoiding the situation in which a precise result is lacking in accuracy, and we are not even aware of it!  Both of these ways of dealing with systematic error are issues of careful experimental design.


#### 2 Explore Various Factors

It's a good idea to think about how the experiment was done, and what facts go into your analysis, and make a list of factors that might affect the final viscosity result. These factors might be sources of systematic error.  We will think more carefully about some items on your list during Weeks 3 and 4, but focus on one particular issue this week.


#### 3 Systematic Error from Inertial Drag?

In your analysis from Week 1, you assumed that the terminal speed of your sphere could be calculated theoretically by considering just gravity, buoyant force, and viscous drag force.  Using this assumption, it was possible to calculate the liquid viscosity from the terminal speed and other measured or known quantities.  However, we have already mentioned that an object falling through a fluid also experiences inertial drag.  If we have missed an entire force in Newton's second law, then our formula relating velocity to terminal speed is incomplete and we can expect that to introduce a systematic error in our results.  This week we will focus on checking for that systematic error, and minimizing it by discovering which data is least affected by inertial drag and restricting our future analysis to that data.

## Viscous and Inertial Drag

You may recall that the inertial drag force is proportional to the object’s speed squared and its cross-sectional area, and also depends on the density $$\rho$$ of the fluid:  $$F_i=C\rho\pi r^2 v^2$$.  The numerical prefactor $$C$$ is of order unity (i.e., it is something closer to 1 than to 0.1 or 10).  Our method for finding viscosity from terminal speed is only valid if the inertial drag force is negligibly small compared to the viscous drag.  If inertial drag is actually significant, the fact that we have neglected it will cause a systematic error in our viscosity result.  Go back to your Week 1 theory calculation based on Newton's second law.  Consider how your calculations would change if you added an inertial drag force, and use that logic to help you answer the following questions. 

#### Miniquestion: Inertial Drag's Effect on Terminal Speed
*[Click here to open in a new tab](https://docs.google.com/forms/d/e/1FAIpQLSfZpZFcl7kh_80P_gHqDr5hORdw9DOy-DgZa1nTftGv-f_aVw/viewform){:target="_blank"}*


<iframe src="https://docs.google.com/forms/d/e/1FAIpQLSfZpZFcl7kh_80P_gHqDr5hORdw9DOy-DgZa1nTftGv-f_aVw/viewform?embedded=true" width="640" height="300" frameborder="0" marginheight="0" marginwidth="0">Loading…
</iframe>

------------------

#### Miniquestion: Inertial Drag's Effect on Our "Viscosity" Values
*[Click here to open in a new tab](https://docs.google.com/forms/d/e/1FAIpQLSfu_yOuiAE2wPP3Oe-t_9GZhQB4Bfb1yODihRUZavIwjz4WdQ/viewform){:target="_blank"}*


<iframe src="https://docs.google.com/forms/d/e/1FAIpQLSfu_yOuiAE2wPP3Oe-t_9GZhQB4Bfb1yODihRUZavIwjz4WdQ/viewform?embedded=true" width="640" height="300" frameborder="0" marginheight="0" marginwidth="0">Loading…
</iframe>

------------------

By comparing the formulas for the inertial and viscous drag formulas, we can begin to understand the conditions under which inertial drag should be negligible.  The ratio of the inertial drag to the viscous drag is $$\frac{F_i}{F_d} = \frac{C\rho\pi r^2 v^2}{6\pi\eta r v} = \frac{C\rho}{6\eta}rv$$.  In the last step we have split up the ratio into two factors; the first factor of $$\frac{C\rho}{6\eta}$$ depends only on the fluid we use and the fact that we are dropping spherical objects, but the second factor $$rv$$ depends on the details of the sphere we use.  Inertial drag is negligible if the ratio $$\frac{F_i}{F_d}$$ is much less than $$1$$.

This week you will analyze videos of falling spheres with five different diameters.  For each sphere size, you will find a terminal velocity and use it to calculate viscosity based on your formula from Week 1.  Use the discussion above, along with your Newton's second law calculations from last week, to answer the following question.

#### Miniquestion: Drag Forces and Sphere Size 
*[Click here to open in a new tab](https://docs.google.com/forms/d/e/1FAIpQLScGuhxtTAdqzns252fsxyNZMolGFawRNVmB7xkzwjH8gG2VOg/viewform){:target="_blank"}*


<iframe src="https://docs.google.com/forms/d/e/1FAIpQLScGuhxtTAdqzns252fsxyNZMolGFawRNVmB7xkzwjH8gG2VOg/viewform?embedded=true" width="640" height="300" frameborder="0" marginheight="0" marginwidth="0">Loading…
</iframe>

---------------

#### Miniquestion: What Varying Sphere Size Should Tell Us
*[Click here to open in a new tab](https://docs.google.com/forms/d/e/1FAIpQLSfagWdq8Zsw0XMmLYP9M-jMLmSEhqorlAUohRS8G6yfPmmVdw/viewform){:target="_blank"}*


<iframe src="https://docs.google.com/forms/d/e/1FAIpQLSfagWdq8Zsw0XMmLYP9M-jMLmSEhqorlAUohRS8G6yfPmmVdw/viewform?embedded=true" width="640" height="300" frameborder="0" marginheight="0" marginwidth="0">Loading…
</iframe>

---------------

*Possible digression here about how we aren't doing a hypothesis-testing experiment per se in this module, but really there is an implicit hypothesis in this little analysis, that we understand the equation of motion and inertial drag is negligible for some of the spheres we are using -- if that hypothesis is not supported by our data, we go back to the drawing board on the whole notion of what we are doing in this module and how we propose to measure the viscosity of the liquid!*


## Week 2 To-Do Summary

In Week 2 you will analyze at least one video for each nominal sphere diameter:  1.8 mm, 2.5 mm, 3.5 mm, 4.5 mm, and 6.0 mm.  Your goal for Week 2 is to sketch out how the "viscosity" of the liquid, calculated from terminal speed using a formula that neglects inertial drag, varies as a function of sphere diameter.  At the end of this week, you should have a clear idea of which sphere diameter(s), if any, truly have their trajectories negligibily influenced by inertial drag.

Choose at least one video from each sphere diameter you have not already analyzed.  Following the method you used in Week 1, extract a terminal speed from each video you have chosen, and calculate a viscosity value from that terminal speed and the other necessary quantities.

Plot your calculated viscosities as a function of sphere diameter.

Decide on a list of sphere diameters for which inertial drag is negligible, and be ready to defend your decision based on the data.

In looking for the presence or absence of trends in calculated viscosity as a function of sphere diameter, you will need to consider some estimate of the random error in each calculated viscosity; it is important to know whether variations in calculated viscosity between data points can be accounted for by the random error in each data point, or whether the variation exceeds this random error.  Your Week 1 analysis of 3.5-mm spheres can give you a sense of the random error at least for that one sphere diameter.  You can use this as an estimate of the random error in each viscosity, or you can analyze multiple trials of each sphere diameter (or of some of them) in order to make independent estimates of random error in each case.

## Checkpoint 2

+ Submit your Week 2 results in [Checkpont 2 on Gradescope](https://www.gradescope.com/courses/165932/assignments/654616){:target="_blank"} by the end of Week 2.  You should submit (1) a scatter plot of calculated viscosity vs. sphere diameter, with no lines between points.  Your axes should be labeled with the quantity shown and the units used.  If you have analyzed multiple trials for some sphere diameters, include vertical error bars showing the uncertainty in each calculated viscosity, but this is not required in Week 2 except for the 3.5-mm spheres which you have already analyzed in Week 1.  You should also submit (2) a list of the sphere diameters for which you believe inertial drag is negligible.

+ And to double-check, make sure you have finished all of this week's mini-questions by [checking here](mini-questions#week-2){:target="_blank"}

## Final Note

When you're ready, move on to [Week 3 - Final Determination of Viscosity](week3).
