# FAIR_batch

There are eight types of experiments presented (all results are for multiple subpopulations):
For each of the .ipynb files run the cells from top to bottom. The main() function gives the output of our algorithms.
[Adult] results are in the main folder, all other dataset results are in [Comparative_Results] folder. In all
the .ipynb files LPCA is implemented as python function [min_sum_lpca] and LPC is implemented as function [min_max_lpc].

1. To run LPCA to generate configurations with given input and target configurations for different datasets [1LPCA_adult_multiple_(config_generator).ipynb, 1LPCA_bank_multiple_(config_generator).ipynb, 1LPCA_compas_multiple_(config_generator).ipynb, 1LPCA_german_multiple_(config_generator).ipynb]

2. To run LPCA and get the results on a target configuration for different datasets [2LPCA_adult_multiple_(beta_avg_variations).ipynb, 2LPCA_bank_multiple_(beta_avg_variations).ipynb, 2LPCA_compas_multiple_(beta_avg_variations).ipynb, 2LPCA_german_multiple_(beta_avg_variations).ipynb] 

3. To run LPCA on the configurations generated by Zafar et al. [3LPCA_adult_multiple_bilal_zafar_(comparative_config).ipynb] (we have omitted similar files for other datasets and other baselines)

4. To run the LPCA results on change in training distribution for Adult dataset. [4LPCA_adult_multiple_config_(train_distribution_corruption).ipynb]


5. To run LPCA (without confidence values) [5LPCA_wcv_adult_multiple.ipynb, 5LPCA_wcv_bank_multiple.ipynb , 5LPCA_wcv_compas_multiple.ipynb, 5LPCA_wcv_bank_multiple.ipynb] 


6. To run LPC on real and synthetic datasets [6LPC_adult_multiple.ipynb, 6LPC_bank_multiple.ipynb , 6LPC_compas_multiple.ipynb, 6LPC_bank_multiple.ipynb, 6LPC_synthetic_multiple.ipynb] 


7. To run the LPCA for gerrymandering results for different datasets [7LPCA_BANK_multiple_gerrymendering_comparison.ipynb, 7LPCA_COMPAS_gerrymendering_copararison.ipynb, 7LPCA_adult_gerrymendering_copararison.ipynb, 7LPCA_German_gerrymendering_copararison.ip]


8. To run the LPCEO for multiple subpopulations for different datasets [8LPCEO_Bank_multiple.ipynb,8LPCEO_german_multiple.ipynb, 8LPCEO_COMPAS_multiple.ipynb, 8LPCEO_adult_multiple.ipynb]


