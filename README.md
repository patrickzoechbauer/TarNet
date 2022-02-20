# Implementation of TarNet in pytorch 

The notebook "TarNet.ipynb" defines and trains a TarNet on the IHDP dataset. Model tuning  selects the model with the lowest error on the validation set. No further tuning for "number of epochs", "batch size" or "learning rate" is currently implemented. 

Additional documentation on the individual steps of the script can be found within the notebook. 

How to run the notebook: 
*************************

1) Install the dependencies as described in "requirements.txt"
2) Run the TarNet.ipynb. 

Note the script automatically downloads the IHDP dataset from "https://github.com/vdorie/npci/raw/master/examples/ihdp_sim/data/ihdp.RData". 
