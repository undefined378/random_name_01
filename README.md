<div align="center">

## Reviewer 9qHM (W2 / Q1)

Figure 1. Training loss and test error for Physics-informed NeuralODE with Adam, RoPINN, and NNCG optimizers.

<p align="center">
  <img src="figures/pi_nerualode_train_loss_heatmap.png" width="300" alt="Adam Training Loss">
  <img src="figures/pi_nerualode_test_error_heatmap.png" width="300" alt="Adam Test Error">
</p>
<p align="center"><strong>(a) PI-NeuralODE with Adam</strong></p>

<p align="center">
  <img src="figures/RoPINN-NeuralODE_train_loss_heatmap.png" width="300" alt="RoPINN Training Loss">
  <img src="figures/RoPINN-NeuralODE_test_error_heatmap.png" width="300" alt="RoPINN Test Error">
</p>
<p align="center"><strong>(b) PI-NeuralODE with RoPINN</strong></p>

<p align="center">
  <img src="figures/NNCG_NeuralODE_train_loss_heatmap.png" width="300" alt="NNCG Training Loss">
  <img src="figures/NNCG_NeuralODE_test_error_heatmap.png" width="300" alt="NNCG Test Error">
</p>
<p align="center"><strong>(c) PI-NeuralODE with NNCG</strong></p>

---

Figure 2. Training loss and test error for PINO with ALM, RoPINN, and Curriculum Learning (CL).

<p align="center"><img src="figures/pino_optim.png" width="700" alt="PINO"></p>

---

## Reviewer 9qHM (Q2, Q3) / Reviewer kKd9 (Q1)

Figure 3. Boundary sensitivity analysis.

<p align="center">
  <img src="figures/Boundary/convection_alm_boundary_sensitivity_overlay.png" width="400" alt="Convection ALM Overlay">
  <img src="figures/Boundary/convection_lbfgs_boundary_sensitivity_overlay.png" width="400" alt="Convection L-BFGS Overlay">
</p>
<p align="center"><strong>(a) Convection + ALM &emsp;&emsp;&emsp; (b) Convection + L-BFGS</strong></p>

<p align="center">
  <img src="figures/Boundary/convection_nncg_boundary_sensitivity_overlay.png" width="400" alt="Convection NNCG Overlay">
  <img src="figures/Boundary/ropinn_boundary_sensitivity_overlay.png" width="400" alt="RoPINN Overlay">
</p>
<p align="center"><strong>(c) Convection + NNCG &emsp;&emsp;&emsp; (d) RoPINN</strong></p>

<p align="center">
  <img src="figures/Boundary/reaction_lbfgs_boundary_sensitivity_overlay.png" width="400" alt="Reaction L-BFGS Overlay">
  <img src="figures/Boundary/wave_lbfgs_boundary_sensitivity_overlay.png" width="400" alt="Wave L-BFGS Overlay">
</p>
<p align="center"><strong>(e) Reaction + L-BFGS &emsp;&emsp;&emsp; (f) Wave + L-BFGS</strong></p>

<p align="center">
  <img src="figures/Boundary/AD_FNO_boundary_sensitivity_overlay.png" width="400" alt="AD FNO Overlay">
  <img src="figures/Boundary/poisson_fno_boundary_sensitivity_overlay.png" width="400" alt="Poisson FNO Overlay">
</p>
<p align="center"><strong>(g) AD-FNO &emsp;&emsp;&emsp; (h) Poisson-FNO</strong></p>

---

## Reviewer sQNm (Q1)

Figure 4. Training loss and test error on convection system with resampling collocation points.

<p align="center"><img src="figures/resample.png" width="600" alt="Collocation Resampling"></p>

---

## Reviewer sQNm (Q2)

Figure 5. Comparison of Adam, RoPINN, and SOAP on the Convection system with a large network (width: 256, depth: 4). Figures (a) and (b) show the differences in training loss and test error between the Adam and SOAP optimizers.

<p align="center">
  <img src="figures/adam_soap_training_loss.png" width="300" alt="Adam vs SOAP Training Loss">
  <img src="figures/adam_soap_test_error.png" width="300" alt="Adam vs SOAP Test Error">
</p>
<p align="center"><strong>(a) Training Loss (Adam - SOAP) &emsp;&emsp;&emsp; (b) Test Error (Adam - SOAP)</strong></p>

<p align="center">
  <img src="figures/convection_sources_adam_ropinn_training_loss.png" width="300" alt="Adam + RoPINN Training Loss">
  <img src="figures/convection_sources_adam_ropinn_test_error.png" width="300" alt="Adam + RoPINN Test Error">
</p>
<p align="center"><strong>(c) Training Loss (Adam - RoPINN) &emsp;&emsp;&emsp; (d) Test Error (Adam - RoPINN)</strong></p>

---

## Reviewer sQNm (Q3)

Figure 6. Comparison of SOAP, NNCG, and RoPINN on the Convection system.

<p align="center">
  <img src="figures/convection_sources_soap_nncg_ropinn_training_loss.png" width="400" alt="SOAP NNCG RoPINN Training Loss">
  <img src="figures/convection_sources_soap_nncg_ropinn_test_error.png" width="400" alt="SOAP NNCG RoPINN Test Error">
</p>
<p align="center"><strong>(a) Training Loss &emsp;&emsp;&emsp; (b) Test Error</strong></p>

</div>
