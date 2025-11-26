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

Additionally, a time series and distribution of values is shown for globally averaged sea surface temperature (taken 5m below sea surface):

<p>
  <img src="https://github.com/amethystaurora-robo/control_run_analysis/blob/main/lineplot_sst.png">
</p>


<p>
  <img src="https://github.com/amethystaurora-robo/control_run_analysis/blob/main/histplot_sst.png">
</p>
