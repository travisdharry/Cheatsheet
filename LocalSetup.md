# Local Setup
Common tasks and CLI commands when setting up a local version

## Anaconda
**Create virtual environment**
```conda create -n <envname> python=3.10.8```
Activate the new virtual environment
conda activate <envname>
Configure environment variables (reactivate environment when complete) 
conda env config vars set <my_var=value>
Check environment variables
conda env config vars list

## Visual Studio Code
Set up Jupyter Notebooks in VS Code
python3.10 -m pip install ipykernel
