# Deployments

**Common tasks and CLI commands when deploying a project**

## Heroku
**Log in to Heroku**  
`$ heroku login`  

**Initialize remote connection to Heroku project**  
`$ heroku git:remote -a <myproject>`  

**Deploy on Heroku**  
`$ git push heroku main`  

**View logs**
`$ heroku logs --tail`  


## Packages
**List packages installed on environment**  
`pip list --format=freeze > requirements.txt`  


