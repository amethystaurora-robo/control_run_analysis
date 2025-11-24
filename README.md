This repository represents the second deliverable of my PhD on climate tipping points with rare event sampling. For this project, I have used PLASIM to conduct a 1000 year control run. The following is a time series and PDF of this run.

In this 1000-year climate simulation, I demonstrate that PLASIM takes some time to reach the "attractor": the subset of phase space where trajectories settle. The variables (in this case, near-sea surface temperature) in the first 3 years of the simulation are significantly below the average trend.
<p>
  <img src="https://github.com/amethystaurora-robo/control_run_analysis/blob/main/sheet_averaged_unfiltered.png">
</p>

The same data is shown below, filtering out the years the simulator takes to reach the attractor. In this case, the simulation starts in Year 4. 

<p>
  <img src="https://github.com/amethystaurora-robo/control_run_analysis/blob/main/sheet_averaged_filtered.png">
</p>

In addition to near sea surface temperature, I am also looking at the strength of the Atlantic Meridional Overturning Circulation (AMOC), particularly where North Atlantic Deep Water (NADW) is formed. In the cold Labrador Sea, warm surface water from the tropics is cooled and sinks, moving southward. The overturning in this area is measured as the AMOC strength, and the value is typically between 15-20 Sverdrups. In the 1000-year control run, we can see the same trend where the measurements begin at ~35 Sverdrups, then reach an attractor region. However, it does seem anomalous that in this run, the AMOC shows weakening in year 100 already. 

<p>
  <img src="https://github.com/amethystaurora-robo/control_run_analysis/blob/main/simulation_transient.png">
</p>

<p>
  <img src="https://github.com/amethystaurora-robo/control_run_analysis/blob/main/simulation_notransient.png">
</p>


#I am going to completely refactor this repository. 
a) Change the time series to be a real time series. 
b) Tas is not anomalous, only AMOC values are. It doesn't seem to be anything wrong with code, as diagnostic files print these very low values. Need to run a longer (200 years at least) simulation to check if the values still persist
c) 16 cores seems to be the most efficient processing for this
d) Need to do final PDF analysis of 1000-year run, see if AMOC variable is still there
