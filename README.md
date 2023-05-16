# Friedmann
A modelization via Python/Scipy of Friedmann equation for Cosmology

Cosmology is made by a few fundamental equations. In this part, we interess ourselves at the first Friedmann-Lemaître equation which describes the evolution of the Universe depending on its density, based on the general relativity equations and by application of the cosmological principle :
$$H=\frac{\dot a}{a}=H_0\sqrt{\Omega_r^0 a^{-4}+\Omega_m^0 a^{-3}+\Omega_k^0 a^{-2}+\Omega_\Lambda^0}$$

our goal is to plot the evolution of the scale factor $a(t)$ depending on comoving time for different scenarios. We will accomplish it by integrating the equation using the function *odeint* in the **scipy** python module.
