## Pre-Deployment Checklist
- [ ] [MVP runs](https://github.com/rstrom/CodeGuildBootCamp/blob/master/Week13/checklist.md)
- [ ] All dependencies are specified in `requirements.txt`
  * run `pip freeze > requirements.txt` to update
- [ ] All changes are committed
- [ ] No API keys are exposed in your git repository
- [ ] (Optional) you've backed up your database with the  [dumpdata](https://docs.djangoproject.com/en/1.9/ref/django-admin/#dumpdata) command

Follow the Heroku guide [to deploy an existing Django project](https://devcenter.heroku.com/articles/django-app-configuration#migrating-an-existing-django-project)

## Post-Deployment Checklist
- [ ] You've migrated the database on Heroku
- [ ] You've created a new superuser with a password > 10 characters
- [ ] (Optional) you've initialized the database with your backed up data using the [loaddata](https://docs.djangoproject.com/en/1.8/howto/initial-data/) command
