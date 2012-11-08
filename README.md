DjangoTemplate
==============
forked from
pinax-project-account
=====================

a starter project the incorporates account features from django-user-accounts


Usage:

    django-admin.py startproject --template=https://github.com/vccabral/DjangoTemplate/zipball/master <project_name>

Example:

    rm -rf SexyKisses/
    django-admin.py startproject --template=https://github.com/vccabral/pinax-project-account/zipball/master SexyKisses
    cd SexyKisses/
    virtualenv localpython --distribute
    pip install -r requirements.txt
    //edit your settings.py to reflect your database settings. 
    python manage.py syncdb
    python manage.py runserver