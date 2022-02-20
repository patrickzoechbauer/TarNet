# Implementation of TarNet in pytorch 

The notebook "TarNet.ipynb" defines and trains a TarNet on the IHDP dataset. Model tuning  selects the model with the lowest error on the validation set. No further tuning for "number of epochs", "batch size" or "learning rate" is currently implemented. 

Additional documentation on the individual steps of the script can be found within the notebook. 

How to run the notebook: 
*************************

1) Run the below in your terminal to setup a new python environement based on "requirements.txt" and start a jupyter notebook:\
python3 -m venv tarnet\
source tarnet/bin/activate\
pip install -r requirements.txt\
ipython kernel install --user --name=tarnet\
jupyter notebook

2) Change ipython kernel to "tarnet" and run "TarNet.ipynb"

Note the script automatically downloads the IHDP dataset from "https://github.com/vdorie/npci/raw/master/examples/ihdp_sim/data/ihdp.RData". 



