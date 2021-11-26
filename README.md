# Causally-Formulated-Hazard-Ratio

The repository is for the paper: 

[Adib, R., Griffin, P., Ahamed, S.I. and Adibuzzaman, M., 2020, September. A Causally Formulated Hazard Ratio Estimation through Backdoor Adjustment on Structural Causal Model. In Machine Learning for Healthcare Conference (pp. 376-396). PMLR.](http://proceedings.mlr.press/v126/adib20a)

Description of the files here (please read the paper for understanding the references):

1. Datasets:

    a. strong_bias_data.csv *(simulated dataset with strong bias through confounder)*
 
    b. weak_bias_data.csv *(simulated dataset with weak bias through confounder)*
    
    c. ewing-data.csv *(real-world dataset)*
    
    d. adj_surv_data_transformA.csv *(adjusted datasets through SCM, using transformation A)*
    
    e. adj_surv_data_transformB.csv *(adjusted datasets through SCM, using transformation B)*

2. Main code:
    
    a. 1_simulate-data.ipynb *(code for simulation of data)*
    
    b. 2a_ipw_simulated_data.ipynb *(code for adjustment on simulated data)*
    
    c. 2b_ipw_ewing_data.ipynb *(code for adjustment on real-world data)*
    
    d. ipw_ewing_data_new_graph.ipynb *(code for adjustment on real-world data, using transformation B)*

3. Images:
    
    a. unadjusted.eps & unadjusted_ewing.eps *(unadjusted/direct survival curves for both simulated and real data)*
    
    b. adjusted.eps & adjusted_ewing.eps *(adjusted survival curves for both simulated and real data)*

4. Extras:
    
    a. or_rr_simpsons_paradox.ipynb *(code for similar explorations on odds and risk ratio, already known in literature as Causal Odds Ratio and Causal Risk Ratio)*
    
    b. desmos.png *(baseline for simulated data survival curve, plotted as mathematical functions)*