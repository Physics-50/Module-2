# Week 4: DRAFT.  DO NOT FOLLOW YET!

In Physics 50, you will ultimately get to experience what it’s like to create a physics poster, which is like a mini version of a physics paper. In Module 1, you created a single figure with a caption. For the Module 2 deliverable, you will produce a series of figures, with captions, that summarize the method and logic you used, leading to your final result for the liquid viscosity in this module.  

First, you should remind yourself of the [guidelines for creating a single figure](https://physics-50.github.io/Module-1/week4){:target="_blank"}, and look up any feedback you received about your Module 1 deliverable on Gradescope. We are building off of the single figure from Module 1, and the same standards apply to each of the figures you create for the Module 2 deliverable.


**THE INSTRUCTIONS FOR THE MODULE 2 DELIVERABLE WILL BE RELEASED FRIDAY OCTOBER 16**

Until then, we have our Ph50 Fall Break. After you submit your Week 3 checkpoint, you can take a break. The Module 2 Deliverable is due Friday October 23. 

## How to use a sequence of figures to make a claim

As with any piece of writing, we always recommend starting from an (evidentiary) outline. The first step is often to determine: **what is my main result/claim?** 

What interesting/exciting/new idea have you discovered? What was your scientific goal of doing the experiments you just completed? The answer to these kinds of questions can inform what you consider your main result. Unless you had a specific hypothesis you were testing with your experiment, since the main result is coming from your data, often you need to play around with your data by plotting it in different ways. Are there any relationships between the variables or quantities you can calculate? This will form the evidence that you will use to support your main result.

 The main result is important, so it should be the focus of your most prominent figure. This main figure/plot is often referred to as the "money plot". When others think about the results of your work, this compelling visual will provide them with a convenient way to remember your result. The evidence that supports your main result is what goes in the money plot. What evidence do you have to support the main claim/result? In experimental work, this evidence is almost always some "processed" data that is extracted out from the "raw" data of your experiment. 

For example, in our Module 1 experiments, the main result was presented in your plot of the coefficient of static friction versus mass. The "raw" data were the individual measurements of the angle, and from that "raw" data you extracted the "processed" data: coefficient of static friction.

After you have an idea of your main figure, you need to decide what information a reader will need to understand your main result. This required information/context will inform what other figures need to be included. You should provide a visual representation of how you obtained data, some of the intermediate data processing steps that occur, and any other relevant information a reader might need (e.g. other important quantities used to generate the information in the money plot).

The sequence of figures often builds in complexity towards the main result. Sometimes starting with an ["overview figure"](https://www.nature.com/articles/nmeth0511-365){:target="_blank"} provides a useful schematic context to understand your experimental process and what data will emerge. 

After you have the main result sequence down, you should ask yourself if there are any interesting secondary results that you have discovered. Then go through the same process you did for the main result, and try to weave the secondary results into your sequence of figures. Unless the main result relies on them, these secondary results usually appear in the sequence after the main result because we don't want to bury our main result behind a series of less-important secondary information. 

So to summarize:

+ start with an evidentiary outline (your evidence is your own data)
+ focus on your main result first, make a figure that summarizes the evidence you have to support your main result/claim
+ make a series of figures that build in complexity, which give your reader context to understand your evidence
+ add in any secondary claims and evidence to support them; add any additional context needed to understand evidence for these too
+ consider making an overview figure if your sequence of figures might be difficult to follow



### A note on using tables

While most of the time we want to display information in figures that contain images and plots, sometimes a table can be helpful. You might want to add a table if: 

1) There is a lot of qualitative information, or the relationship between variables is not important for what you want your reader to take away. 

**AND**

2) The information you are presenting does not appear elsewhere. **Do not include a table of data that you also plot!** 

If you do include a table in your sequence of figures, please read [this guide to formatting tables](https://people.inf.ethz.ch/markusp/teaching/guides/guide-tables.pdf#page=6){:target="_blank"}.

Briefly summarized here:

+ Avoid vertical lines
+ Avoid “boxing up” cells with many horizontal lines
    + usually 3 horizontal lines are enough: above the table, below the table, and after the heading row
+ Avoid double horizontal lines
+ Add enough space between rows so items don't look cluttered
+ By default, align each column to its left hand side

<br>
<br>

## Example of a sequence of figures

To make some of these ideas more concrete, let's step through a made-up sequence of figures that is loosely based on [Farley et al. *Journal of Experimental Biology* (2019)](images/Farley et al Journal Experimental Biology 2019.pdf){:target="_blank"}. If you'd like to see an excellent **real example** of a sequence of figures, then please **go through that paper only looking at the figures and captions**. You should be able to follow the main results of that work just by reading the figures, and almost every figure is a great example of the lessons we wanted you to take from Module 1.

But if you'd prefer to see something that might more closely resemble the types of choices you will need to make for your Module 2 deliverable, let's look at the following made-up sequence of figures. Important: **this data is made up** and is meant only to illustrate what a short sequence of figures may look like for a simple example.

------------------------------------------------

### Outlining

Suppose we had taken videos of midge larvae jumping, and when we looked at the kinetic energy of the jumps we noticed that the smallest larvae's jumps had kinetic energy that depended on their size, but the kinetic energy of the largest larvae's jumps were all approximately constant.

So the main result here is that there's a maximum average value of the kinetic energy for the jumping midge larvae (**Reminder: this is made up and not actually true in nature**).

This is the basis of what we would want to turn into our money plot.  

But what information does a reader need to understand this money plot? They need context for the following:

+ where does the kinetic energy come from? 
    + mass and takeoff speed
+ where does mass come from?
    + measured directly
+ where does takeoff speed come from?
    + measured from position vs. time plot
+ where does the position vs. time plot come from? 
    + videos of midge jumping

We see that we have traced the evidence back to the "raw" data from the experiment. In this example, the "raw" data are the many videos of the midge larvae jumping. The "processed" data are the average kinematic quantities. 

Based on this information, and after several revisions, we might come up with the following sequence of figures to support our claim.

---------------------------------------------

### Figure 1

[*Click  to enlarge in a new tab*
![Fig 1](images/Fig1.jpg)](images/Fig1.jpg){:target="_blank"}

-----------------------------------

### Table 1
[*Click to enlarge in a new tab*
![Tab 1](images/Tab1.jpg)](images/Tab1.jpg){:target="_blank"}



-----------------------------------

### Figure 2
[*Click  to enlarge in a new tab*
![Fig 2](images/Fig2.jpg)](images/Fig2.jpg){:target="_blank"}


-------------------------------------

### Equation 1

The weighted average of the kinetic energy, $$K_\mathrm{avg}$$ is calculated from the individual measured kinetic energies $$K_i$$ and uncertainties $$\delta K_i$$ for each mass as 

\begin{equation}
K_\mathrm{avg} = \frac{\sum_{i=1}^{n} \frac{K_i}{(\delta K_i)^2}}{\sum_{i=1}^{n} \frac{1}{(\delta K_i)^2}},
\end{equation}

where $$i$$ enumerates over all $$n=4$$ data points from Fig. 2 used to calculate the weighted average. 

---------------------------------------------

### Equation 2

The uncertainty in the weighted average, $$\delta K_\mathrm{avg}$$, is estimating using 

\begin{equation}
\delta K_\mathrm{avg} = \frac{1}{\sqrt{n}}\sqrt{\frac{ \sum_{i=1}^{n} \frac{(K_i-K_\mathrm{avg})^2}{(\delta K_i)^2}   }{   \sum_{i=1}^{n} \frac{1}{(\delta K_i)^2} }   }.
\end{equation}

<br>

<br>



---------------------------

## Module 2 Deliverable

What do I need to make for Module 2?

For Module 2, your deliverable is a series of two to four figures (which might also include a table and supporting equations), summarizing the data and analysis you used (including the logic that drove your decisions) and leading up to your final result for the viscosity of the liquid in this module.  Keep in mind that your figures should make the overall process and results understandable to someone who has your physics background but who is not enrolled in this course and has not seen the experimental videos or read any of the instructions.  Your final result for the liquid viscosity (including uncertainty!) should be given somewhere in the last figure or its caption.

### Evaluation

Your sequence of figures is an example of academic writing, and so we will be evaluating it based on a similar criteria that you experienced in your Writ 1 class.

Does the main claim (and secondary claims, if applicable) meet the S.A.F.E. criteria:

**S**ignificant

**A**rguable

**F**ocused

**E**vidence-based

Arguable might seem like an unusual criteria here, and we are going to take it to apply fairly loosely here. For example, a claim that the viscosity of the liquid measured in this module was found to be $$1000 \pm 2000\, \mathrm{Pa}\,\mathrm{s}$$ would not make an arguable claim in our context.

We will also be evaluating the global coherence of your sequence of figures and the context you provide for your intended audience.

Additionally, each individual figure will be assessed according to the criteria of Module 1.  
