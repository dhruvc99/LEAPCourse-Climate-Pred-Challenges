# **Project 3: Machine Learning Reconstruction of Surface Ocean pCO₂**

## **Group 4**
**Team members: Alex Crookshanks, Sam Anwar, Andrew Marshall Fagerheim, Dhruv Chakraborty**

## Summary
In this project, we expanded upon the pCO₂-Residual approach from Bennington et al. (2022) by testing five different methodologies for improving machine learning reconstructions of surface ocean pCO₂: modified loss function, latitudinal split, ocean split, transfer learning, and weighted sampling. Our analysis showed that the latitudinal split approach consistently outperformed other methods, reducing bias and RMSE across multiple ocean regions, particularly in the undersampled Southern Ocean. However, the improvements were modest, suggesting that significant advances in pCO₂ reconstruction may require either higher-quality data or fundamentally different modeling approaches.

## Contribution Statement
Andrew Marshall Fagerheim focused on different visualization methods and investigated differences in ESM results. Alex Crookshanks investigated BART (Bayesian Additive Regression Trees) models, developed the transfer learning approach, and contributed commentary for the final notebook. Sam Anwar explored generalization across ensemble members, developed the ocean split model, and set up the submission notebook structure. Dhruv Chakraborty developed the weighted sampling and custom loss function approaches, implemented the latitude split model, and organized data for the final notebook. All team members contributed equally to the analysis, evaluation, and preparation of the final submission. All team members approve our work presented in this GitHub repository including this contributions statement.

## **References**

- **Gloege et al. (2020)**  
  *Quantifying Errors in Observationally Based Estimates of Ocean Carbon Sink Variability.*  
  [DOI: 10.1029/2020GB006788](https://doi.org/10.1029/2020GB006788)

- **Bennington et al. (2022)**
  *Explicit Physical Knowledge in Machine Learning for Ocean Carbon Flux Reconstruction: The pCO2-Residual Method*
   [DOI: 10.1029/2021ms002960](https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2021MS002960)

- **Heimdal et al. (2024)**  
  *Assessing improvements in global ocean pCO₂ machine learning reconstructions with Southern Ocean autonomous sampling.*  
  [DOI: 10.5194/bg-21-2159-2024](https://doi.org/10.5194/bg-21-2159-2024)