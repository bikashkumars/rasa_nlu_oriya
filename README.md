# RASA NLU English and Oriya
Chat Bot Natural Language Understanding for Oriya and English Language

## System Requirement
1. Ubuntu 16+
2. Mac OS Latest
3. Windows 10 (Visual C++ Build tool)

## Install Mini Conda (Part of Anaconda)
https://conda.io/miniconda.html


## Install Python
Install Python using Conda
Best working on Python 3.6
conda install python=3.6

## Create Environment for Rasa Project under Python 3.6
We except you have install python 3.6 using Conda command
conda create -n rasa python=3.6

## Install Visual studio Code and Open a Empty Folder
https://code.visualstudio.com/download

## Activate python 3.6 using Conda (important step)
source activate rasa

##Install Required Python Packages
pip install  --no-cache-dir rasa_nlu
pip install  --no-cache-dir rasa_nlu[spacy]
python -m spacy download en_core_web_md
python -m spacy link en_core_web_md en
pip install  --no-cache-dir rasa_nlu[tensorflow]