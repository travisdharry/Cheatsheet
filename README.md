# Cheatsheet

## Extract-Transform-Load
[Detailed Instructions](https://github.com/travisdharry/Cheatsheet/blob/main/detailed/ETL.ipynb)

#### Common commands  
```
path_current = os.getcwd()
path_parent = os.path.dirname(path_current)
path_data = os.path.join(path_parent, 'data')
```
`df = pd.read_excel(path_est, sheet_name='df', dtype={'zipcode':str})`
`df = df.astype({'zipcode': str})`
```
with pd.ExcelWriter('Results.xlsx') as writer:  
    resultA.to_excel(writer, sheet_name="resultA")
```


## Cleaning
[Detailed Instructions](https://github.com/travisdharry/Cheatsheet/blob/main/detailed/DataCleaning.ipynb)

#### Common commands  
```
df.loc[df['name']=="nameA", 'colA'] = 'valueA'
df['colA'] = df['colA'].str.replace("valueA", "valueB")
```
```
from datetime import date, datetime
from dateutil.relativedelta import *
dateStart = "2022-04-01"
dateStart = np.datetime64(dateStart)
today = date.today()
age = relativedelta(now, row["dob_datetime"]).years
xlrd.xldate_as_datetime(xl_date, 0)
```


## Local Setup
[Detailed Instructions](https://github.com/travisdharry/Cheatsheet/blob/main/detailed/LocalSetup.md)

#### Common commands   
`conda create -n <envname> python=3.10.8`  
`conda activate <envname>`  
`conda env config vars set <my_var>=<my_value>`  
`conda env config vars list`  
`pip install ipykernel`   


## Deployments
[Detailed Instructions](https://github.com/travisdharry/Cheatsheet/blob/main/detailed/Deployments.md)

#### Common commands 
`$ heroku login`  
`$ heroku git:remote -a <myproject>`  
`$ git push heroku main`  
`$ heroku logs --tail`  
`$ pip install -r requirements.txt`
`pip list --format=freeze > requirements.txt`  



