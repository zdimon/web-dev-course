##Virtual environment

A Virtual Environment is a tool to keep the dependencies required by different projects in separate places, by creating virtual Python environments for them.

    sudo apt-get install python-virtualenv

###Creating virtual environment

    virtualenv blog_ve

This command will create a new folder in the current directory with specific structure.
Also it will install pip library which you can use to install othe packages.

###Activation virtual environment.

    cd blog_ve
    source ./bin/activate

    nano bin/activate

###Check PATH

    echo $PATH


###Install Django 1.8

    pip install django==1.8

###Creating a new project

    django-admin startproject blog

###manage.py

    cd blog
    ./manage.py

###Creating tables
    
    ./manage.py migrate

###Creating superadmin

    ./manage.py createsuperuser

###Starting webserver

    ./manage.py runserver 8888





