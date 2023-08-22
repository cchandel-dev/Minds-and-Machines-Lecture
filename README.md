# Minds-and-Machines-Lecture
this repo contains a demo of a custom made object detector that uses vision transformers that was shown at Western Universities Minds &amp; Machines Lecture Series


**Prerequisites**
[] miniconda/anaconda installed  
[] python 3.10.12 & pip installed  

**Installation Steps**  

Step 1. generate a virtual environment  
&emsp;&emsp;&emsp;&emsp;`conda create --name minds_and_machines_env1 python=3.10.12`  
Step 2. download/clone the repo  
&emsp;&emsp;&emsp;&emsp;`git clone 'enter hash here'`  
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;OR  
&emsp;&emsp;&emsp;&emsp;just download this repo through the github page  
Step 3. navigate to where the repo is downloaded locally (use cd in Windows) and then step into the virtual environment  
&emsp;&emsp;&emsp;&emsp;`cd 'enter path here'`  
&emsp;&emsp;&emsp;&emsp;`conda activate minds_and_machines_env1`  
Step 4. install all of the required modules  
&emsp;&emsp;&emsp;&emsp; pip install -r requirements.txt
Step 5. push the conda environment to jupyter notebook  
&emsp;&emsp;&emsp;&emsp;`python -m ipykernel install --user --name=minds_and_machines_env1`  

**Open the Jupyter Notebook**  
Step 1. type `jupyter notebook` into the command prompt  
Step 2. select minds_and_machines_env1 kernel  
Step 3. select/open the Transformer based Object Detection.ipynb file  
