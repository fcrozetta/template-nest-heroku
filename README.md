<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo_text.svg" width="320" alt="Nest Logo" /></a>
</p>

---

# About this template
This is a small template to make the project run on heroku.

Since nest is a typescript project and have to be compiled to work on heroku, this is a template with a few modifications that will make it work. 

# Setup
To make it work propperly, you may have to change a few variables in heeroku. To do that, you will need [heroku CLI](https://devcenter.heroku.com/articles/heroku-cli).

After creating the app, check if your deploy works correctly. If not, execute the following commands, changing **<APP-NAME>** for the nname of your app in heroku.

``` bash
heroku config:set NODE_ENV=production -a <APP-NAME>
heroku config:set NPM_CONFIG_PRODUCTION=false -a <APP-NAME>
```

