#To Do PLASIM
1. change probability distribution to one from 1001-2000
2. change potential function graph to the correct, time-averaged one

This repo uses the intermediate-complexity coupled oceanic-atmosphere model, PLASIM, to simulate 1000 years of oceanic activity.

In this brief analysis I am looking at the strength of the Atlantic Meridional Overturning Circulation (AMOC), specifically  North Atlantic Deep Water (NADW). In the cold Labrador Sea, warm surface water from the tropics is cooled and sinks, moving southward. The overturning in this area is measured as the AMOC strength, and the value is typically between 15-20 Sverdrups. Below, the time series is shown with a long transient prior to reaching the attractor: the subset of phase space where trajectories settle.

<p>
  <img src="https://github.com/amethystaurora-robo/control_run_analysis/blob/main/simulation_transient.png">
</p>

The same time series is shown after cutting the transient:

<p>
  <img src="https://github.com/amethystaurora-robo/control_run_analysis/blob/main/simulation_notransient.png">
</p>

Below, the probability distribution of AMOC indices is shown after cutting the transient.


<p>
  <img src="https://github.com/amethystaurora-robo/control_run_analysis/blob/main/PDF_amoc_cut.png">
</p>

Below, a control run is initialized after spinning up the model for 1000 years. The timeseries from Years 1001-2000 is shown below.

<p>
  <img src="https://github.com/amethystaurora-robo/control_run_analysis/blob/main/f_controlrun_timeseries.png">
</p>

The auto-correlation compares AMOC indices between present-day and lag-time values. Depending on the lag comparison, different trends emerge. Below, auto-correlation decays to zero over a 7-month time interval.

<p>
  <img src="https://github.com/amethystaurora-robo/control_run_analysis/blob/main/acfunc_control_1200slice.png">
</p>

Seasonal variation is shown in the auto-correlation plot below, where months across years are strongly correlated with each other.

<p>
  <img src="https://github.com/amethystaurora-robo/control_run_analysis/blob/main/acfunc_control_120slice.png">
</p>

A slight downward trend in auto-correlation can also be seen when the function is computed over slices of 1000 timepoints (~83 years)

<p>
  <img src="https://github.com/amethystaurora-robo/control_run_analysis/blob/main/acfunc_control_12slice.png">
</p>

