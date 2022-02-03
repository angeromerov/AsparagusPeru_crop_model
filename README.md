# asparagusPeru_crop_model
Asparagus crop model for Peru developed as part PhD research
We developed “ASPeru” a mechanistic crop model coded in Python which includes 26 physiological parameters and crop variables.  The model simulates two main phases: (1) spear growth and production during harvest accompanied by root carbohydrate depletion and (2). canopy establishment, and carbohydrate accumulation by light interception to initiate the next harvest. Our model calculates yield, numbers of spears produced by plant, spears and stems biomass and root carbohydrate in brix% values ant the end of the harvest, at stems establishment and at the end of the campaign. The validation tested mature crops (between 3 and 12 years old) of UC157-F1, for 75 campaigns reported from July 2018 to May 2020 in 38 plots. Resulting in a RRMSE of 1.21% for final yield predicted. An advantage of the ASPeru model simplicity is that it can be easily adapted by farmers in Latin-America.

This repository contains the following folders:
-  **Results and validation** : To determine the error for yield and brix prediction.
-  **Spear analisys** : To determine spear growth rate used for lenght prediction.
- **Asparagus crop model** : ASPmodel.rar contains files required to use the crop model in python
- **Matlab version**: A preliminar version .

-------------------------------------------------------------------------------------------------
To use ASPru crop model refer toAsparagus crop model.rar

To calculate spear growth rate  refer to Spear analisys.

To Caluclate the error RMSE and RRMSE between modeled resuts and field data for model validation , refer to Results and validation.

-------------------------------------------------------------------------------------------------

**Requirements**
- Python  2016 v3.6 or above.

- Other requirements: Excel. MATLAB 2017 v9.3 or above (preliminar version)

