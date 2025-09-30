# Applied Econometrics & Marketing Analytics in Python

This repository contains a curated set of **Jupyter Notebooks** demonstrating advanced econometric and statistical methods for marketing analytics, forecasting, and consumer modeling. Each notebook includes:

- **When to Use / Best Applications / When Not to Use** — practical guidance.  
- **How to Interpret Results** — key takeaways for decision-making.  
- **Fully coded Python examples** using open or simulated datasets.  

<p align="center">
  <img src="brian-curry-econometrics-forecasting-media-mix-modeling.png" alt="Hero Image" width="700"/>
</p>



---

## 📂 Contents

1. **01_media_mix_modeling.ipynb**  
   - Bayesian MMM with simulated channel data.  
   - Diminishing returns, adstock, and ROI estimation.  

2. **02_multi_touch_attribution.ipynb**  
   - Logistic attribution, heuristic rules (last-touch, time-decay).  
   - Markov removal effect attribution.  

3. **03_multinomial_logit.ipynb**  
   - Consumer choice modeling with multinomial logit.  
   - Market share simulation under price changes.  

4. **04_time_series_forecasting.ipynb**  
   - Baselines, Holt-Winters, SARIMAX with exogenous variables.  
   - Walk-forward validation for forecast accuracy.  

5. **05_hierarchical_bayes.ipynb**  
   - Bayesian shrinkage with a Beta–Binomial hierarchical model.  
   - Posterior predictive checks and interval estimation.  

6. **06_panel_data_methods.ipynb**  
   - Fixed Effects (FE) and Random Effects (RE).  
   - Hausman test, cluster-robust SE, interpretation of within-entity effects.  

7. **07_censored_truncated_regressions.ipynb**  
   - Tobit regression (censoring).  
   - Truncated regression via MLE.  
   - Comparison with naive OLS.  

8. **08_selection_models.ipynb**  
   - Heckman two-step correction for sample selection.  
   - Propensity score matching (PSM) and inverse probability weighting (IPW).  

9. **09_item_response_theory.ipynb**  
   - Rasch (1PL) and 2PL models for latent trait estimation.  
   - Item characteristic curves and test information.  

10. **10_latent_class_regression.ipynb**  
    - EM algorithm for finite mixture of regressions.  
    - Segment-specific coefficients and responsibilities.  

---

## 🛠 Requirements

Install dependencies with:

```bash
pip install -r requirements.txt
