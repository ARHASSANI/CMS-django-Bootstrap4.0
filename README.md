CMS-django-Bootstrap4.0
==========

Django CRM is opensource CRM developed on django framework. It has all
the basic features of CRM to start with. We welcome code contributions
and feature requests via github.


---

# Installation
We recommend ubuntu 18.04 or ubuntu 20.04. These instructions are verified for ubuntu 20.04

#### System Requirements
---

```
sudo apt install xvfb libfontconfig wkhtmltopdf git libpq-dev python3-dev python3-pip gem ruby ruby-dev build-essential libssl-dev libffi-dev python3-venv redis-server redis-tools -y

sudo gem install sass

```

#### Install dependencies
---

```
pip install -r requirements.txt
```

#### next steps
```
python manage.py migrate
python manage.py runserver
```
Then open http://localhost:8000 in your borwser and create a new account with test as company name. We mapped test.localhost to 127.0.0.1 So, it should work properly.

