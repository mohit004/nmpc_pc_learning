# nmpc_pc_learning
Nonlinear model predictive controller (NMPC) codes for tracking the commanded reference trajectory. The incorporated NMPC expects the learned value of the disturbance parameters $F^{x_dist}$, $F^{y_dist}$, and $F^{z_dist}$. Besodes, the utilization of the disturbance parameters can be switched off by setting "use_dist_estimates" to "false" within the launch file.

This NMPC code is utilized for the following work. Please don't forget to cite if you use this code in your work.

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
