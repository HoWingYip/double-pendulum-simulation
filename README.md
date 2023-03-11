# double-pendulum-simulation
Double pendulum simulation powered by SciPy and Matplotlib. Made in 2022.

Main code lies in `double-pendulum.ipynb`. Video files are organised according to the integration method used to generate the respective simulations, namely under the directories `dop853/` and `rk45/`.

## Note on numerical integration methods
DOP853 provides far higher accuracy than RK45. Use the former if you would like conservation of energy to (largely) hold — which of course you do... right?

Integration method can be set using the `method` argument in the call to `scipy.integrate.solve_ivp`. (See https://docs.scipy.org/doc/scipy/reference/integrate.html)
