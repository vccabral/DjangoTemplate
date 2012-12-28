pinax-project-account
=====================

a starter project the incorporates account features from django-user-accounts


Usage:

    django-admin.py startproject --template=https://github.com/pinax/pinax-project-account/zipball/master <project_name>



Setup for Confirmation Emails Edit Setting.py
---------------------------------------------
#comment out this line: 
EMAIL_BACKEND = "django.core.mail.backends.smtp.EmailBackend"
DEFAULT_FROM_EMAIL = "email@example.com"
EMAIL_USE_TLS = True
EMAIL_HOST = 'smtp.example.com'
EMAIL_PORT = 587
EMAIL_HOST_USER = 'email@example.com'
EMAIL_HOST_PASSWORD = 'password'
