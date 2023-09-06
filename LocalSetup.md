# Local Setup
**Common tasks and CLI commands when setting up a local version**


## Anaconda

**Create virtual environment**  
```conda create -n <envname> python=3.10.8```  

**Activate virtual environment**  
`conda activate <envname>`  

**Configure environment variables**  
`conda env config vars set <my_var>=<my_value>`  
(reactivate environment when complete)  

**Check environment variables**  
`conda env config vars list`  


## Visual Studio Code

**Set up Jupyter Notebooks in VS Code**  
`pip install ipykernel`  
