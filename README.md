This repo uses the intermediate-complexity coupled oceanic-atmosphere model, PLASIM, to simulate 1000 years of oceanic activity.

In this brief analysis I am looking at the strength of the Atlantic Meridional Overturning Circulation (AMOC), specifically  North Atlantic Deep Water (NADW). In the cold Labrador Sea, warm surface water from the tropics is cooled and sinks, moving southward. The overturning in this area is measured as the AMOC strength, and the value is typically between 15-20 Sverdrups. 

A simulation is initialized with a spin-up of 1000 years-this allows a transient period prior to reaching the attractor, the phase space where the trajectory settles in equilibrium. The timeseries from Years 1001-2000 is shown below.

<p>
  <img src="https://github.com/amethystaurora-robo/control_run_analysis/blob/main/sheets/f_controlrun_timeseries.png">
</p>

The distribution of values for the AMOC Index is shown below.

<p>
  <img src="https://github.com/amethystaurora-robo/control_run_analysis/blob/main/sheets/control_hist.png">
</p>

The auto-correlation compares AMOC indices between present-day and lag-time values. Controlling for seasonal variation by taking yearly averages produces a smooth auto-correlation function, which has been averaged across ten windows of 100-year slices in the control run.

<p>
  <img src="https://github.com/amethystaurora-robo/control_run_analysis/blob/main/ac_function/acfunc_control_10slice.png">
</p>

