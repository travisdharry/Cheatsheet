# Cheatsheet

## Data Analysis
[Python, Pandas, etc.](https://github.com/travisdharry/Cheatsheet/blob/main/DataAnalysis.ipynb)


## Local Setup
[Anaconda, VSCode, etc.](https://github.com/travisdharry/Cheatsheet/blob/main/LocalSetup.md)

#### Anaconda  
`$ conda create -n <envname> python=3.10.8`  
`$ conda activate <envname>`  
`$ conda env config vars set <my_var>="<my_value>"`  
`$ conda env config vars list`  

#### Visual Studio Code
`python3.10 -m pip install ipykernel`   


## Deployments
[Heroku](https://github.com/travisdharry/Cheatsheet/blob/main/Deployments.md)

#### Heroku 
`$ heroku login`  
`$ heroku git:remote -a <myproject>`  
`$ git push heroku main`  
`$ heroku logs --tail`  

#### Packages
`$ pip install -r requirements.txt`
`$ pip list --format=freeze > requirements.txt` 



