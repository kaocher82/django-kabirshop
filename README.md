# django-shupp-ecommerce
Django eCommerce website 


Create and activate fresh Python virtualenv

virtualenv env 

Run pip install -r requirements.txt.

Optionally copy .env.template to .env and setup environment variables for your project. You can also modify Django settings directly to the settings file or setup local settings file.
Initialize database by running 

python manage.py migrate

Initialize installation by running 

python manage.py shuup_init

Create superuser to access admin 

python manage.py createsuperuser

Run server 

python manage.py runserver 0.0.0.0:8888

Navigate to 127.0.0.1:8888/sa and login

Complete Shuup onborading wizard and you should be all set
Now for your own project you can just update git remote with your own git repository and start pushing new commits.

For example git remote set-url origin git@github.com:username/shuup-project-template.git


