# RGD

This git repo contains the code used and created in my Masterthesis
*Riemannian Optimization on Elementary Statistical Manifolds*

The repo also contains the graphs showing the results of the experiments.

## Necessary Setup Steps
### __Install Git__
Download and install [Git](https://github.com/git-for-windows/git/releases/download/v2.28.0.windows.1/Git-2.28.0-64-bit.exe).

### __Install Anaconda3__
Download and install [Anaconda3](https://www.anaconda.com/products/individual#windows).<br />

### __Clone git repo__

Open the cmd consol and enter:
```
mkdir git
cd git
git clone https://github.com/Jacob-Relle/RGD.git
``` 

### __Setup Conda Env__
Open Anaconda Prompt (e.g. Windows Search `Anaconda Prompt`)
or activate conda within the cmd shell via: 
```
call "%Userprofile%\anaconda3\Scripts\activate.bat"
```
Create and activate the conda environment:
```
conda env create -f environment.yml
```
The .yml file contains all infos about the required packages
needed to run the Code.

You can check if the enviornment was created by:
```
conda activate master
```
