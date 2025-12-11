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

The auto-correlation compares AMOC indices between present-day and lag-time values. Controlling for seasonal variation by taking yearly averages produces a smooth auto-correlation function, which has been averaged across ten windows of 100-year slices in the control run.

<p>
  <img src="https://github.com/amethystaurora-robo/control_run_analysis/blob/main/acfunc_control_10slice.png">
</p>

