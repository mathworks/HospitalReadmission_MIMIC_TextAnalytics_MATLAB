### Predict Hospital Readmissions using Text Analytics in MATLAB
**Goal**: Build a model to predict if there will be an unintended readmission within 30 days by analyzing notes of doctors and nurses using text analytics techniques in MATLAB.

For this analysis, MIMIC-III data has been downloaded from https://physionet.org/content/mimiciii/1.4/ and used to bulid a model to predict hospital readmissions. The steps for accessing the database are outlined here: https://mimic.physionet.org/gettingstarted/access/. You will be able to download the data once you obtain credentials to access the it.

![](Picture2.png)

This demo has 4 .mlx files.
* Overview_MIMIC_Demo_00.mlx: This provides overview of the demo.
* ReadData_MIMIC_Demo_01.mlx: Import all relevant information, manipulate to clean and filter the data, and finally combine to make a single dataset for building the model.
* Preprocess_MIMIC_Demo_02.mlx: Preprocess the data to get it ready for building a predictive model.
* BuildModel_MIMIC_Demo_03.mlx: Build a model and test to ensure acceptable accuracy.

### References
* Johnson, A., Pollard, T., & Mark, R. (2016). MIMIC-III Clinical Database (version 1.4). PhysioNet. https://doi.org/10.13026/C2XW26.
* Johnson, A. E. W., Pollard, T. J., Shen, L., Lehman, L. H., Feng, M., Ghassemi, M., Moody, B., Szolovits, P., Celi, L. A., & Mark, R. G. (2016). MIMIC-III, a freely accessible critical care database. Scientific Data, 3, 160035.
* Goldberger, A., Amaral, L., Glass, L., Hausdorff, J., Ivanov, P. C., Mark, R., ... & Stanley, H. E. (2000). PhysioBank, PhysioToolkit, and PhysioNet: Components of a new research resource for complex physiologic signals. Circulation [Online]. 101 (23), pp. e215–e220.