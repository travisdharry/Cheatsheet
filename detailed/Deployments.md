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

**Set Config Vars**
Settings > Reveal Config Vars

**Set up scheduler**
Resources > Add-ons > Heroku Scheduler > Add Job
    - Set Schedule (7:30am UTC)
    - Set Run Command = "python script.py"

**Set up Buildpacks**
Settings > Add Buildpack
https://github.com/heroku/heroku-buildpack-google-chrome
https://github.com/heroku/heroku-buildpack-chromedriver


## Packages
**List packages installed on environment**  
`pip list --format=freeze > requirements.txt`  


