# Quant-Day-6
In this notebook, I’ll build on the facilities provided by the Instrument class (that is, its ability to
detect changes in its inputs and recalculate accordingly) to show how to calculate numerical Greeks
when the engine doesn’t provide them.
Numerical calculation
What does a quant have to do? We can use numerical differentiation to approximate the Greeks, as
shown in the next figure: that is, we can approximate the derivative by calculating the option value
for two slightly different values of the underlying and by taking the slope between the resulting
points
