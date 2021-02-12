# IEOR4575 Assignments
Instructor: Shipra Agrawal\
Assistants: Yunhao Tang, Abhi Gupta

## Install Ananconda on Linux for the first time
```
$ wget https://repo.anaconda.com/archive/Anaconda3-2020.11-Linux-x86_64.sh
$ bash Anaconda3-2020.11-Linux-x86_64.sh
[install conda at the default file path provided by the installer]
```

## Install Ananconda on Mac for the first time
```
$ wget https://repo.anaconda.com/archive/Anaconda3-2020.11-MacOSX-x86_64.sh
$ bash Anaconda3-2020.11-Linux-x86_64.sh
[install conda at the default file path provided by the installer]
```

## Install Ananconda on Windows for the first time
```
Install with the Graphical Installer here: https://repo.anaconda.com/archive/Anaconda3-2020.11-Windows-x86_64.exe
Open the windows application: Anaconda Powershell Prompt. This is the shell that you will use to run all commands.
```

## Create Conda Environment
Assuming you are at the root of this directory: (this will install all required software versions if they have not already been installed)
```
$ conda env create -f env.yml
```

## Activate Environment
```
$ conda activate ieor4575
```

## Login to WandB from the Command Line (after activating this conda environment)
```
[You will need to first create wandb login at wandb.ai]
[IMP: Please use your uni@columbia.edu email and user name uni to do this. Once you have done that, we will add you to ieor-4575 team]

$ wandb login 
[1. You will be asked to enter your API key here]
[2. Once you have logged in, it will display the account that you are logged in as. If this account does not match 'ieor-4575', please relogin with:
$ wandb --relogin]
```

## Open Lab
```
$ jupyter notebook <notebook name>
```
