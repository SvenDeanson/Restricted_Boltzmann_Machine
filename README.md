# Restricted_Boltzmann_Machine
This repository contains some data:

NUM_ANGLES = 100 <br>
NUM_EPOCHS = 5000 <br>
NUM_SAMPLES = 10 or 5 <br>

$J = \pm 1$

$h = [0.25, 0.5, 0.75, 1.0, 1.25, 1.5]$ <br>

Exact angles $\theta$ that were used are in "exact_angles_used.csv"

At the moment I will provide only relative errors but for the whole duration of training.

$$ \epsilon_{r} = \left |\frac{(\tilde{E} - E_{0})}{E_{0}} \right |$$

Data is organized by size $N$ in folders, with names being:<br>
## name - $N$ - $J$ - $H$ - $\alpha$ - $\eta$ - $\theta_{i}$ <br>
example - data_frustrated_N3_J1_H0.5_A1_E0.05_T0.csv
