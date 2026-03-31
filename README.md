<div align="center">

## Reviewer 9qHM (W2 / Q1) 

Figure 1. Training loss and test error for Physics-informed NeuralODE with Adam, RoPINN, and NNCG optimizers.

<table border="0" cellpadding="0" cellspacing="0" style="border-collapse: collapse; margin: 0 auto;">
  <tr>
    <td align="center" style="padding: 10px; border: 0px;">
      <img src="figures/pi_nerualode_train_loss_heatmap.png" width="300" alt="Adam Training Loss">
      <br>
    </td>
    <td align="center" style="padding: 10px; border: 0px;">
      <img src="figures/pi_nerualode_test_error_heatmap.png" width="300" alt="Adam Test Error">
      <br>
    </td>
  </tr>
  <tr>
    <td colspan="2" align="center" style="padding: 4px 10px 10px; border: 0px;">
      <strong>(a) PI-NeuralODE with Adam</strong>
    </td>
  </tr>
  <tr>
    <td align="center" style="padding: 10px; border: 0px;">
      <img src="figures/RoPINN-NeuralODE_train_loss_heatmap.png" width="300" alt="RoPINN Training Loss">
      <br>
    </td>
    <td align="center" style="padding: 10px; border: 0px;">
      <img src="figures/RoPINN-NeuralODE_test_error_heatmap.png" width="300" alt="RoPINN Test Error">
      <br>
    </td>
  </tr>
  <tr>
    <td colspan="2" align="center" style="padding: 4px 10px 10px; border: 0px;">
      <strong>(b) PI-NeuralODE with RoPINN</strong>
    </td>
  </tr>
  <tr>
    <td align="center" style="padding: 10px; border: 0px;">
      <img src="figures/NNCG_NeuralODE_train_loss_heatmap.png" width="300" alt="NNCG Training Loss">
      <br>
    </td>
    <td align="center" style="padding: 10px; border: 0px;">
      <img src="figures/NNCG_NeuralODE_test_error_heatmap.png" width="300" alt="NNCG Test Error">
      <br>
    </td>
  </tr>
  <tr>
    <td colspan="2" align="center" style="padding: 4px 10px 10px; border: 0px;">
      <strong>(c) PI-NeuralODE with NNCG</strong>
    </td>
  </tr>
</table>

---

Figure 2. Training loss and test error for PINO with ALM, RoPINN, and Curriculum Learning (CL).

<p align="center"><img src="figures/pino_optim.png" width="700" alt="PINO"></p>

---

## Reviewer 9qHM (Q2, Q3) / Reviewer kKd9 (Q1)

Figure 3. Boundary sensitivity analysis.

<table border="0" cellpadding="0" cellspacing="0" style="border-collapse: collapse; margin: 0 auto;">
  <tr>
    <td align="center" style="padding: 10px; border: 0px;">
      <img src="figures/Boundary/convection_alm_boundary_sensitivity_overlay.png" width="400" alt="Convection ALM Overlay">
      <br>
      <strong>(a) Convection + ALM</strong>
    </td>
    <td align="center" style="padding: 10px; border: 0px;">
      <img src="figures/Boundary/convection_lbfgs_boundary_sensitivity_overlay.png" width="400" alt="Convection L-BFGS Overlay">
      <br>
      <strong>(b) Convection + L-BFGS</strong>
    </td>
  </tr>
  <tr>
    <td align="center" style="padding: 10px; border: 0px;">
      <img src="figures/Boundary/convection_nncg_boundary_sensitivity_overlay.png" width="400" alt="Convection NNCG Overlay">
      <br>
      <strong>(c) Convection + NNCG</strong>
    </td>
    <td align="center" style="padding: 10px; border: 0px;">
      <img src="figures/Boundary/ropinn_boundary_sensitivity_overlay.png" width="400" alt="RoPINN Overlay">
      <br>
      <strong>(d) RoPINN</strong>
    </td>
  </tr>
  <tr>
    <td align="center" style="padding: 10px; border: 0px;">
      <img src="figures/Boundary/reaction_lbfgs_boundary_sensitivity_overlay.png" width="400" alt="Reaction L-BFGS Overlay">
      <br>
      <strong>(e) Reaction + L-BFGS</strong>
    </td>
    <td align="center" style="padding: 10px; border: 0px;">
      <img src="figures/Boundary/wave_lbfgs_boundary_sensitivity_overlay.png" width="400" alt="Wave L-BFGS Overlay">
      <br>
      <strong>(f) Wave + L-BFGS</strong>
    </td>
  </tr>
  <tr>
    <td align="center" style="padding: 10px; border: 0px;">
      <img src="figures/Boundary/AD_FNO_boundary_sensitivity_overlay.png" width="400" alt="AD FNO Overlay">
      <br>
      <strong>(g) AD-FNO</strong>
    </td>
    <td align="center" style="padding: 10px; border: 0px;">
      <img src="figures/Boundary/poisson_fno_boundary_sensitivity_overlay.png" width="400" alt="Poisson FNO Overlay">
      <br>
      <strong>(h) Poisson-FNO</strong>
    </td>
  </tr>
</table>

---

## Reviewer sQNm （Q1）

Figure 4. Training loss and test error on convection system with resampling collocation points.

<p align="center"><img src="figures/resample.png" width="600" alt="Collocation Resampling"></p>

---

## Reviewer sQNm （Q2）

Figure 5. Comparison of Adam, RoPINN, and SOAP on the Convection system with a large network (width: 256,  depth: 4). Figures (a) and (b) show the differences in training loss and test error between the Adam and SOAP optimizers.

<table border="0" cellpadding="0" cellspacing="0" style="border-collapse: collapse; margin: 0 auto;">
  <tr>
    <td align="center" style="padding: 10px; border: 0px;">
      <img src="figures/adam_soap_training_loss.png" width="300" alt="Adam vs SOAP Training Loss">
      <br>
      <strong>(a) Training Loss (Adam - SOAP)</strong>
    </td>
    <td align="center" style="padding: 10px; border: 0px;">
      <img src="figures/adam_soap_test_error.png" width="300" alt="Adam vs SOAP Test Error">
      <br>
      <strong>(b) Test Error (Adam - SOAP)</strong>
    </td>
  </tr>
  <tr>
    <td align="center" style="padding: 10px; border: 0px;">
      <img src="figures/convection_sources_adam_ropinn_training_loss.png" width="300" alt="Adam + RoPINN Training Loss">
      <br>
      <strong>(c) Training Loss (Adam - RoPINN)</strong>
    </td>
    <td align="center" style="padding: 10px; border: 0px;">
      <img src="figures/convection_sources_adam_ropinn_test_error.png" width="300" alt="Adam + RoPINN Test Error">
      <br>
      <strong>(d) Test Error (Adam - RoPINN)</strong>
    </td>
  </tr>
</table>

---

## Reviewer sQNm （Q3）

Figure 6. Comparison of SOAP, NNCG, and RoPINN on the Convection system.

<table border="0" cellpadding="0" cellspacing="0" style="border-collapse: collapse; margin: 0 auto;">
  <tr>
    <td align="center" style="padding: 10px; border: 0px;">
      <img src="figures/convection_sources_soap_nncg_ropinn_training_loss.png" width="400" alt="SOAP NNCG RoPINN Training Loss">
      <br>
      <strong>(a) Training Loss </strong>
    </td>
    <td align="center" style="padding: 10px; border: 0px;">
      <img src="figures/convection_sources_soap_nncg_ropinn_test_error.png" width="400" alt="SOAP NNCG RoPINN Test Error">
      <br>
      <strong>(b) Test Error </strong>
    </td>
  </tr>
</table>

</div>
