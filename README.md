# Soil-Temperatures

A teaching applet to illustrate the analytical solution to the general equation of heat conduction for a sinusoidal forcing at the surface using Lab View.

The labview VI "soilwave.vi" is the main user interface. The user can select the amplitude of the surface temperature wave, change thermal diffusivity of the soil and then explore how the wave decays and shifts with depth in the soil. The graphs show:

1. the diurnal course of soil temperature at a given depth (time selected by slider) relative to the surface
2. the vertical profile of soil temperature at a given time (time selected by slider)
3. the 2D field of temperatures over time and depth.

The labview VI "soilwave_sinusodial.vi" is a sub-VI called in "soilwave.vi" calculates the equation for one depth and one time step. Inputs are the mean (daily, annual) average soil temperature (ºC), the amplitude of the surface temperature wave, the thermal diffusivity, the period of the oscillation, and the desired time and depth.

A web implementation of this applet for teaching can be found here:
http://ibis.geog.ubc.ca/courses/geob300/applets/stwave/index.html
