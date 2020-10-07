# virtual_env-jupyter
describe how I config a virtual_env and connect with jupyter notebook


## Here I am using python venv to create virtual environmrnt

noramlly, when we use 
python3 -m venv filename(i,e:env3_mstar) to create a virtual environment, it will use default python version in you machine.  
check your default version by command python3

If you have py3.6 in your machine, but not by default you can use python3.6 -m venv env3.6_mstar to specify py version.  
If any problem happens, you can try apt install python3.6-venv, then everything should work.

## Add vir_env kernel to jupyter notebook

First, activate your virtual_machine.

Then, ipython kernel install --user --name=kernel_name (py36_shap)





