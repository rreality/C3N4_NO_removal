# Prediction and Interpretation of Photocatalytic NO Removal on g-C3N4-based Catalysts Using Machine Learning 

This github repository contains the data and code of `Prediction and Interpretation of Photocatalytic NO Removal on g-C3N4-based Catalysts Using Machine Learning`.

## Quick Start
The jupyter folder contains the results of the experiments that have been run, which can be viewed directly through your browser. If you want to run the program yourself, you can do so by following these steps.

First, check that you have the python3.7. Other versions of the python interpreter will not work properly, as we only provide the .pyc source codes, which depends on python 3.7.

Then install the dependency libraries:
> pip install -r requirements.txt

Finally, using your favorite IDE, run `jupyter/C3N4_NO_Regression.ipynb`.


## Project Structure

```
├─config
├─data_preprocessing
├─jupyter
├─plot
└─training_model
```
- config: This folder contains code for setting configuration options.
- data_preprocessing: This folder contains code for data pre-processing.
- jupyter: This folder contains the code used to present the results of the experiment.
- plot: This folder contains the code for drawing and visualization.
- training_model: This folder contains classification models and data analysis tools.


