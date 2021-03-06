- This page will simulate multiple realizations of the animal's trajectory and estimate the average speed, which is proportional to distance traveled. See [`ctmm::speed`](https://ctmm-initiative.github.io/ctmm/reference/speed.html)
- If the data are too coarsely sampled relative to the animal’s movement, to be able to fit a correlated velocity model, no statistically significant signature of the animal’s velocity will remain in the location data. This leaves insufficient information for speed or distance estimation, and it will not be possible to estimate speed or distance travelled. 
  - See more about this in *Noonan, M.J., Fleming, C.H., Akre, T.S. et al. Scale-insensitive estimation of speed and distance traveled from animal tracking data. Mov Ecol 7, 35 (2019)*.
- There is a speed column in model summary table of `Model` page. That is a Gaussian RMS speed and here is a non-parametric mean speed.
- `Distance Traveled` tab will report the duration and distance traveled for each animal based on estimated speed.
- Selecting rows in the table will highlight the entries in plot.
