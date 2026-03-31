<div align="center">

## Reviewer 9qHM (W2 / Q1) 

Figure 1. Training loss and test error heatmaps for Physics-Informed NeuralODE, RoPINN, and NNCG on NeuralODE.

<table border="0" cellpadding="0" cellspacing="0" align="center" style="border-collapse: collapse;">
  <tr>
    <td align="center" style="padding: 10px; border: 0px;">
      <img src="./figures/pi_nerualode_train_loss_heatmap.png" width="300" alt="PI-NeuralODE Training Loss">
      <br>
      <strong>(a) PI-NeuralODE Training Loss</strong>
    </td>
    <td align="center" style="padding: 10px; border: 0px;">
      <img src="./figures/pi_nerualode_test_error_heatmap.png" width="300" alt="PI-NeuralODE Test Error">
      <br>
      <strong>(b) PI-NeuralODE Test Error</strong>
    </td>
  </tr>
  <tr>
    <td align="center" style="padding: 10px; border: 0px;">
      <img src="./figures/RoPINN-NeuralODE_train_loss_heatmap.png" width="300" alt="RoPINN Training Loss">
      <br>
      <strong>(c) RoPINN Training Loss</strong>
    </td>
    <td align="center" style="padding: 10px; border: 0px;">
      <img src="./figures/RoPINN-NeuralODE_test_error_heatmap.png" width="300" alt="RoPINN Test Error">
      <br>
      <strong>(d) RoPINN Test Error</strong>
    </td>
  </tr>
  <tr>
    <td align="center" style="padding: 10px; border: 0px;">
      <img src="./figures/NNCG_NeuralODE_train_loss_heatmap.png" width="300" alt="NNCG Training Loss">
      <br>
      <strong>(e) NNCG Training Loss</strong>
    </td>
    <td align="center" style="padding: 10px; border: 0px;">
      <img src="./figures/NNCG_NeuralODE_test_error_heatmap.png" width="300" alt="NNCG Test Error">
      <br>
      <strong>(f) NNCG Test Error</strong>
    </td>
  </tr>
</table>

---

Figure 2. Training loss and test error heatmaps for ALM, RoPINN, and Curriculum Learning on PINO.

<img src="./figures/pino_optim.png" width="700" alt="PINO">

---

## Reviewer 9qHM （Q3） / Reviewer kKd9（Q1）

Figure 3. Regime boundary contours overlaid at multiple threshold values on the same training loss and test error phase plot on PINN and FNO.

<table border="0" cellpadding="0" cellspacing="0" align="center" style="border-collapse: collapse;">
  <tr>
    <td align="center" style="padding: 10px; border: 0px;">
      <img src="./figures/Boundary/convection_alm_boundary_sensitivity_overlay.png" width="400" alt="Convection ALM Overlay">
      <br>
      <strong>(a) Convection + ALM</strong>
    </td>
    <td align="center" style="padding: 10px; border: 0px;">
      <img src="./figures/Boundary/convection_lbfgs_boundary_sensitivity_overlay.png" width="400" alt="Convection L-BFGS Overlay">
      <br>
      <strong>(b) Convection + L-BFGS</strong>
    </td>
  </tr>
  <tr>
    <td align="center" style="padding: 10px; border: 0px;">
      <img src="./figures/Boundary/convection_nncg_boundary_sensitivity_overlay.png" width="400" alt="Convection NNCG Overlay">
      <br>
      <strong>(c) Convection + NNCG</strong>
    </td>
    <td align="center" style="padding: 10px; border: 0px;">
      <img src="./figures/Boundary/ropinn_boundary_sensitivity_overlay.png" width="400" alt="RoPINN Overlay">
      <br>
      <strong>(d) RoPINN</strong>
    </td>
  </tr>
  <tr>
    <td align="center" style="padding: 10px; border: 0px;">
      <img src="./figures/Boundary/reaction_lbfgs_boundary_sensitivity_overlay.png" width="400" alt="Reaction L-BFGS Overlay">
      <br>
      <strong>(e) Reaction + L-BFGS</strong>
    </td>
    <td align="center" style="padding: 10px; border: 0px;">
      <img src="./figures/Boundary/wave_lbfgs_boundary_sensitivity_overlay.png" width="400" alt="Wave L-BFGS Overlay">
      <br>
      <strong>(f) Wave + L-BFGS</strong>
    </td>
  </tr>
  <tr>
    <td align="center" style="padding: 10px; border: 0px;">
      <img src="./figures/Boundary/AD_FNO_boundary_sensitivity_overlay.png" width="400" alt="AD FNO Overlay">
      <br>
      <strong>(g) AD-FNO</strong>
    </td>
    <td align="center" style="padding: 10px; border: 0px;">
      <img src="./figures/Boundary/poisson_fno_boundary_sensitivity_overlay.png" width="400" alt="Poisson FNO Overlay">
      <br>
      <strong>(h) Poisson-FNO</strong>
    </td>
  </tr>
</table>

---

## Reviewer sQNm （Q1）

Figure 4. Training loss and test error change with iteration under resampling at each iteration.

<img src="./figures/resample.png" width="600" alt="Collocation Resampling">

---

## Reviewer sQNm （Q2）

Figure 5. Comparison of Adam, RoPINN, and SOAP on the Convection system.

<table border="0" cellpadding="0" cellspacing="0" align="center" style="border-collapse: collapse;">
  <tr>
    <td align="center" style="padding: 10px; border: 0px;">
      <img src="./figures/adam_soap_training_loss.png" width="300" alt="Adam vs SOAP Training Loss">
      <br>
      <strong>(a) Adam vs SOAP Training Loss</strong>
    </td>
    <td align="center" style="padding: 10px; border: 0px;">
      <img src="./figures/adam_soap_test_error.png" width="300" alt="Adam vs SOAP Test Error">
      <br>
      <strong>(b) Adam vs SOAP Test Error</strong>
    </td>
  </tr>
  <tr>
    <td align="center" style="padding: 10px; border: 0px;">
      <img src="./figures/convection_sources_adam_ropinn_training_loss.png" width="300" alt="Adam + RoPINN Training Loss">
      <br>
      <strong>(c) Adam + RoPINN Training Loss (Convection)</strong>
    </td>
    <td align="center" style="padding: 10px; border: 0px;">
      <img src="./figures/convection_sources_adam_ropinn_test_error.png" width="300" alt="Adam + RoPINN Test Error">
      <br>
      <strong>(d) Adam + RoPINN Test Error (Convection)</strong>
    </td>
  </tr>
</table>

---

## Reviewer sQNm （Q3）

Figure 6. Comparison of SOAP, NNCG, and RoPINN on the Convection system.

<table border="0" cellpadding="0" cellspacing="0" align="center" style="border-collapse: collapse;">
  <tr>
    <td align="center" style="padding: 10px; border: 0px;">
      <img src="./figures/convection_sources_soap_nncg_ropinn_training_loss.png" width="400" alt="SOAP NNCG RoPINN Training Loss">
      <br>
      <strong>(a) SOAP + NNCG + RoPINN Training Loss (Convection)</strong>
    </td>
    <td align="center" style="padding: 10px; border: 0px;">
      <img src="./figures/convection_sources_soap_nncg_ropinn_test_error.png" width="400" alt="SOAP NNCG RoPINN Test Error">
      <br>
      <strong>(b) SOAP + NNCG + RoPINN Test Error (Convection)</strong>
    </td>
  </tr>
</table>

</div>
