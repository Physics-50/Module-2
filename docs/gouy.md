# Why am I getting too large a value for the speed of sound?

We have assumed that the levitator produces  **plane waves**, which are waves whose phase fronts are flat (planar). As illustrated in Fig. 1, this is not a particularly good assumption. Could the curvature of the wavefronts influence what we measure for the wavelength?

{: .center}
![A figure from the paper describing our levitators](images/1.4989995.figures.online.f1.jpg)

{: .mycap}
**Figure 1** --- Taken from https://aip.scitation.org/doi/10.1063/1.4989995.


# Gaussian beams

We might approximate the shape of the wavefronts following the well-established theory of [Gaussian beams](https://en.wikipedia.org/wiki/Gaussian_beam){: target="_new" }. To apply this theory to the levitator, we need to estimate the **Rayleigh range** $$z_R$$, which is the distance from the center of the pattern to the place along the symmetry axis at which the wavefront is most curved. Traditionally, we measure distance along the axis with the variable $$z$$, with the zero at the exact center of the pattern.

{: .center}
![alt text](images/Rayleigh-range.jpg){: width="400px;"}


{: .mycap}
**Figure 2** --- An estimate of the Rayleigh range made by eyeballing a circle centered at $$z = 0$$.


From the picture, it appears that the diameter of the circle is about $$2 z_R \approx 9 \frac{\lambda_{\rm obs}}{2}$$. If we use the uncorrected estimate of the wavelength from the expected value using $$v_{\rm sound} = 343 \text{ m/s}$$ and the drive frequency of 40 kHz, we get an estimated Rayleigh range of
\begin{equation}\label{eq:Rayleigh-range}
  z_R \approx \frac{9}{4} \times (343\text{ m/s}) (40\text{ kHz}) = 31\text{ mm}
\end{equation}

As discussed on the page about [Gaussian beams](https://en.wikipedia.org/wiki/Gaussian_beam){: target="_new" }, along the $$z$$ axis the amplitude of the standing wave should be proportional to
\begin{equation}\label{eq:Gouy}
  y \propto \sin \bigg[\frac{2\pi z}{\lambda} - \text{arctan}(z/z_R) \bigg]
\end{equation}
If we can approximate the arctangent by its argument, we get the altered expression
\begin{equation}\label{eq:Gouy-approx}
    y \approx A \sin \bigg[ \bigg(\frac{2 \pi}{\lambda} - \frac{1}{z_R} \bigg) z \bigg]
    = A \sin \bigg( \frac{2 \pi z}{\lambda_{\rm eff}} \bigg)
\end{equation}
where
\begin{equation}
  \lambda_{\rm eff} = \frac{\lambda}{1-\frac{\lambda}{2 \pi z_R}}
\end{equation}
Using the unshifted wavelength, $$\lambda = 8.575\text{ mm}$$, we get
\begin{equation}
  \lambda_{\rm eff} = 8.970\text{ mm}
\end{equation}
from which we would naively estimate the speed of sound to be
\begin{equation}
  v_{\rm naive} = (8.970\text{ mm})(40\text{ kHz}) = 359\text{ m/s}
\end{equation}

To simplify the correction in the manual we introduce a parameter
\begin{equation}
  n = \frac{2 z_R}{\lambda_eff}
\end{equation}

based on the discussion on this page, we will use n~4.5 in the analysis. 

Using this definition to substitute for $$z_R$$ in equation 4:

\begin{equation}
  \lambda = \frac{\lambda_{\rm eff}}}{1+\frac{1}{\pi n}}
\end{equation}

<!--I commented this out for now but am willing to switch back - You can use the above analysis to determine how to correct the value you measure for the wavelength to that of a plane wave from which you can easily determine the speed of sound. (Note: We are not providing you the final formula to use; you need to read and understand the above analysis to determine how to correct the value you measured for the wavelength under the assumption that you were looking at plane waves to a more honest estimate that accounts for the curvature of the wavefronts from which you may infer an accurate speed of sound.)-->
