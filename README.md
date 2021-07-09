# hello-city

This is my kludgy way of running a symfony application on Heroku. This repo comes to remind me of steps to deploy a PHP based application on Heroku 

### Requirment

1. Heroku account
2. Login 
3. Cleaning the working tree 
4. Push to Master branch
5. Modify ENV_VARS
6. Composer require symfony/apache-pack
7. Create a Procfile 
 ```bash
 echo 'web: heroku-php-apache2 public/' > Procfile
 git add Procfile
 git commit -m "Heroku Procfile" 
```



### Deploy 

To create a build it is necessary to push the repo's code to Heroku 

```bash
git push heroku master

```