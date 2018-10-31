# Machine Learning 1

### About
This repository contains code for projects of Msc. course Machine Learning 1.

### Compile
1. Installing conda
Go to https://conda.io/miniconda.html and use the provided 64bit python 3.7 installer for your operating system.
2. Setting up the environment
Download the environment.yml file, and create an environment with the command:
```
conda env create -f path/to/environment.yml
```
Removing the environment if something goes wrong
```
conda remove --name ml1labs --all
```
3. Activating / Deactivating the environment
```
source activate ml1labs
source deactivate ml1labs
```
4. Starting the server:
From the folder where you have the files stored:
```
jupyter notebook
```
You will see a bunch of messages, along with the following:
```
    Copy/paste this URL into your browser when you connect for the first time,
    to login with a token:
        http://localhost:8888/?token=asdf234asdfasdfsdaf
```
Open your browser and go the the link shown in your terminal. You can now navigate to the lab notebook from there on.
