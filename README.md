# Lecture3

Refer the Link for Heroku Deploy -----> https://devcenter.heroku.com/articles/getting-started-with-python

---------------------------------------ERRORs Resolved----------------------------------------------------------------

Naming Procfile ----> CAPITAL 'P' ; web: gunicorn lecture3.wsgi (contents inside the file)
                
******************************************************************************

Creating Requirements.txt ----> Django ; gunicorn (contents inside the file)
                                 
*******************************************************************************

Run this CLI ----> $ heroku config:set DISABLE_COLLECTSTATIC=1

*******************************************************************************

Run this CLI when you get "Everything is uptodate" ----> $ git push heroku main:master ---- It creates a new 'main' sub-branch in master.

********************************************************************************

Modify this in "Settings.py" file in Django-project ----> ALLOWED_HOSTS = ['*'] ---- This allows APP-URL to get picked & displayed on browser.

**********************************************************************************
