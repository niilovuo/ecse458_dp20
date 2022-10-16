# Hysteresis data plotter, Neural Network
Implemented using Python 3 with matplotlib, numpy and tensorflow (keras)

[Link to OneDrive](https://mcgill-my.sharepoint.com/:f:/r/personal/christos_cunning_mail_mcgill_ca/Documents/ECSE%20458%20-%20DP%2020?csf=1&web=1&e=xV39kS)

## Instructions for virtual environment:
- [Instructions for PyCharm](https://www.jetbrains.com/help/pycharm/creating-virtual-environment.html#python_create_virtual_env)
- [Instructions for command line](https://docs.python.org/3/library/venv.html)
- To use venv: 
  - Activate it 
  - Inside the project folder do `pip install -r requirements.txt`

## Contents of files:
### ecse458_plotter
#### main.py
- Command line interface for demos etc.
#### neural.py
- Definitions of neural networks
- Training functions for the NNs
#### custom_activation.py
- Experiments with custom activation functions
- Can be imported to use in `neural.py`
#### data_preprocessing.py
- Formatting of data for training/validating/testing neural networks
#### test_networks.ipynb
- Jupyter notebook to be used for internal testing
- Note: May also be used for demos in presentations if time does not allow for a polished CLI
### data_simulated
- Contains datasets generated with simcenter MAGNET software
### datasets
- Contains data generated using the MatLab code in `Preisach_Matlab_Generation`
### models
- Contains neural network models generated by functions in `neural.py`
### Preisach_Matlab_Generation
- Contains MatLab code to generate Preisach data for NN training/validation/testing