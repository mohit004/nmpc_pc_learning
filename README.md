# nmpc_pc_learning
The nonlinear model predictive controller (NMPC) package. The resulting NMPC tracks a reference position trajectory. Besides, it expects the learned values for the disturbance parameters $F^{x_dist}$, $F^{y_dist}$, and $F^{z_dist}$ (as illustrated in the following work). Moreover, the following Gaussian process regression package can be utilized for learning the required disturbance parameters:\
[wind_gp_regression](https://github.com/mohit004/wind_gp_regression): A Gaussian process regression package.

**Note:** the utilization of the disturbance parameters can be switched off by setting "use_dist_estimates" to "false" within the launch file. 

This NMPC package is utilized in the following work. Please don't forget to consider citing it if you use these code in your work.

**Plain text:**
```
M. Mehndiratta and E. Kayacan, "Gaussian Process-based Learning Control of Aerial Robots for Precise Visualization of Geological Outcrops," 2020 European Control Conference (ECC), Saint Petersburg, Russia, 2020, pp. 10-16.
```
**Bibtex:**
```
@INPROCEEDINGS{9143655,
  author={M. {Mehndiratta} and E. {Kayacan}},
  booktitle={2020 European Control Conference (ECC)}, 
  title={Gaussian Process-based Learning Control of Aerial Robots for Precise Visualization of Geological Outcrops}, 
  year={2020},
  volume={},
  number={},
  pages={10-16}
}
```
