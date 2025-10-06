This repository represents the second deliverable of my PhD project on climate tipping points with rare event sampling. For this project, I have used PLASIM to conduct a 1000 year 'control' run, which will then be compared to PLASIM runs with rare event sampling.

In this 1000-year simulation, I demonstrate that PLASIM takes some time to reach the "attractor": the subset of phase space where trajectories settle. The variables (in this case, near-sea surface temperature) in the first 3 years of the simulation are significantly below the average trend.
<p>
  <img src="https://github.com/amethystaurora-robo/control_run_analysis/blob/main/sheet_averaged_unfiltered.png">
</p>

The same data is shown below, filtering out the years the simulator takes to reach the attractor. In this case, the simulation starts in Year 4. 

<p>
  <img src="https://github.com/amethystaurora-robo/control_run_analysis/blob/main/sheet_averaged_filtered.png">
</p>

Rather than taking the average temperature for the whole ocean, the graph below separates the ocean into 'bins' of 20 degrees latitude. The data is shown unfiltered from Year 1 first:

<p>
  <img src="https://github.com/amethystaurora-robo/control_run_analysis/blob/main/sheet_latbins_unfiltered.png">
</p>

And again, filtered:

<p>
  <img src="https://github.com/amethystaurora-robo/control_run_analysis/blob/main/sheet_latbins_filtered.png">
</p>

In each case, the only noteworthy observation is that in Year 990, some noticeable outliers occur, where sea surface temperature drops significantly. This has not been investigated as a part of this project.

In addition to near sea surface temperature, I am also looking at the strength of the Atlantic Meridional Overturning Circulation (AMOC), particularly where North Atlantic Deep Water (NADW) is formed. Here tropical water is cooled and sinks, moving southward. The overturning in this area is measured as the AMOC strength, and the value is typically between 15-20 Sverdrups. In the 1000-year control run, we can see the same trend where the measurements begin at ~35 Sverdrups, then reach an attractor region. However, it does seem anomalous that in this run, the AMOC shows weakening in year 100 already. 

<p>
  <img src="https://github.com/amethystaurora-robo/control_run_analysis/blob/main/AMOC_strength.png">
</p>
