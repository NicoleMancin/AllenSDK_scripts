# AllenSDK_scripts

Code to access the Allen Brain Connectivity Atlas via AllenSDK.
A series of examples are provided in the scripts.
For more detailed information and examples, look at: 

https://github.com/AllenInstitute/SWDB_2019/blob/master/DynamicBrain/solutions/Other/Connectivity_solutions.ipynb

https://allensdk.readthedocs.io/en/latest/allensdk.api.queries.mouse_connectivity_api.html#allensdk.api.queries.mouse_connectivity_api.MouseConnectivityApi

https://community.brain-map.org/c/how-to/mouse-connectivity-atlas/31

Before starting, remind that you have to install the allenSDK package on anaconda. I suggest creating a virtual environment specifically for it, as works on older versions of python.
My suggestion:

conda create -n allensdk_env python=3.10

conda activate allensdk_env

pip install numpy==1.23.5

pip install allensdk

conda install -c conda-forge notebook

pip install notebook

pip install pandas

pip install matplotlib

pip install imageio

pip install os

pip install scipy

pip install seaborn
