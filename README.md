# Welcome to the ADIVSE workshop
This github repository provides you with information and data required for the workshop.

# Getting the codebase and data
## Method 1: Direct cloning via github (requires pre-installed git or git desktop)
    git clone https://github.com/Fraunhofer-ITMP/advise_workshop.git
    cd advise_workshop

## Method 2: Download the repo manually
On the top of the page, you'll see "Code" with green color. Click it and you'll see the option "Download zip" at the end.

# Setting up environment

Press windows button and search for anaconda powershell. Click and open. 

    conda info --env
    conda create --name=workshop python=3.9
    conda activate workshop
    pip install -r requirements.txt
