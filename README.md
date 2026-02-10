# solar-demo

# Simple Solar Array Degradation Model

This is a small demo to show how solar array power can degrade over time in Low Earth Orbit (LEO).

I start with an initial solar array power of 100 W and apply a yearly degradation. The total degradation each year is made up of two parts:
- a constant loss that represents general aging, UV exposure and atomic oxygen
- an additional radiation-related loss that depends on orbit altitude

Two LEO altitudes are compared:
- 400 km (lower radiation environment)
- 700 km (higher radiation environment)

The model applies the same percentage loss every year and tracks the remaining power over a 10-year mission. Results are plotted as relative power (%) versus mission time.

The numbers used are not meant to be exact. They are chosen to be reasonable and to clearly show the effect of higher altitude on long-term power degradation.

## Libraries used
- NumPy is used for simple numerical calculations and arrays.
- Matplotlib is used to plot the degradation curves.

Both libraries are widely used, easy to understand, and suitable for small engineering models like this
