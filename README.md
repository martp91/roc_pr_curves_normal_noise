# Compute best possible ROC PR curves given that the (binary) class is decided upon a noisy measurement
The true/false positive/negatives can be calculated by integrating a 2D normal distr

Jupyter notebook requires numpy, matplotlib, scikit-learn, scipy

AUC ROC/PR are completely determined by $\rho = \sigma_{pop}/\sqrt{\sigma_{meas}^2 + \sigma_{pop}^2}$ and the number of total $\sigma$ the mean is from the cutoff.
![image](https://github.com/martp91/roc_pr_curves_normal_noise/assets/35374378/0f6a3fbc-da04-4dac-859e-98334f2fe339)
