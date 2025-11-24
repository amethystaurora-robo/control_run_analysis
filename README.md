This repo uses the intermediate-complexity coupled oceanic-atmosphere model, PLASIM, to simulate 1000 years of oceanic activity.

Below, a long transient is shown prior to reaching the attractor: the subset of phase space where trajectories settle.
<p>
  <img src="https://github.com/amethystaurora-robo/control_run_analysis/blob/main/sheet_averaged_unfiltered.png">
</p>

The same data is shown below, filtering out the transient. In this case, the simulation starts in Year 4. 

<p>
  <img src="https://github.com/amethystaurora-robo/control_run_analysis/blob/main/sheet_averaged_filtered.png">
</p>

In addition to near sea surface temperature, I am also looking at the strength of the Atlantic Meridional Overturning Circulation (AMOC), particularly where North Atlantic Deep Water (NADW) is formed. In the cold Labrador Sea, warm surface water from the tropics is cooled and sinks, moving southward. The overturning in this area is measured as the AMOC strength, and the value is typically between 15-20 Sverdrups. Below, the time series is shown with the transient, and then without.

<p>
  <img src="https://github.com/amethystaurora-robo/control_run_analysis/blob/main/simulation_transient.png">
</p>

<p>
  <img src="https://github.com/amethystaurora-robo/control_run_analysis/blob/main/simulation_notransient.png">
</p>

Finally, the probability distribution of AMOC indices is shown after cutting the transient.


<p>
  <img src="https://github.com/amethystaurora-robo/control_run_analysis/blob/main/PDF_amoc_cut.png">
</p>
