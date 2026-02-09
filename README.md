This repo uses the intermediate-complexity coupled oceanic-atmosphere model, Planet Simulator (PlaSim), to simulate 1000 years of oceanic activity.

In this analysis I look at the strength of the Atlantic Meridional Overturning Circulation (AMOC), between 66 and 46 degrees North. Here part of the North Atlantic Deep Water (NADW) is formed by warm, salty surface water from the tropics which cools and sinks. The overturning of this water, measured in Sverdrups, is a state variable which can indicate weakening or transitions of the AMOC.

A control run is initialized with a spin-up of 1000 years to allow the state variables to reach equilibrium. The timeseries from Years 1001-2000 is shown below.

<p>
  <img src="https://github.com/amethystaurora-robo/control_run_analysis/blob/main/sheets/f_controlrun_timeseries.png">
</p>

The distribution of values for the AMOC Index in the control run is shown below.

<p>
  <img src="https://github.com/amethystaurora-robo/control_run_analysis/blob/main/sheets/control_hist.png">
</p>

The auto-correlation compares AMOC indices between each timepoint and itself at lag. Controlling for seasonal variation by taking yearly averages produces a smooth auto-correlation function, which has been averaged across ten windows of 100-year slices.
<p>
  <img src="https://github.com/amethystaurora-robo/control_run_analysis/blob/main/ac_function/acfunc_control_10slice.png">
</p>

The next step of this analysis is adding a rare event algorithm at regular sampling intervals to force the system towards a collapsed state. The research on the next step will be held in a separate repository, click below to see more.
<p>
  <a https://github.com/amethystaurora-robo/plasim_rare_events>
  <img src="https://img.shields.io/badge/See%20Repo-2b6750?style=for-the-badge&logo=tableau&logoColor=white"/>

  </a>
</p>

