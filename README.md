django-social-auth-twitter
==========================

Twitter OAuth integration for Django Admin Interface using django-social-auth 


Installation
------------

- $ virtualenv django-social-auth-twitter
- activate the virtual environment (Source/activate.bat (or) ./activate.sh) 
- $ pip install -r requirements.txt (uncomment the MySQL-python if you are using mysql)

- Create a Twitter app in http://twitter.com/apps/new and update TWITTER_CONSUMER_KEY & TWITTER_CONSUMER_SECRET

Configuration
------------

The new users can be given the super user permissions using

SOCIAL_AUTH_CREATE_USERS_AS_SUPER_ADMIN = True

Notes
-----

Twitter doesn't provide email IDs. So the user creation uses twitter username with example.com as a domain for email address.