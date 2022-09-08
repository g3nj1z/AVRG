# Automatic-VAPT-Report-Generator
still in development

## Objectives
Open-source generator that public can use

## Project Planning Approaches
Study & Research about Django Web > RnD all possible Concepts > Implementation Accumulated Data in Project > Build 1st Demo > Test & Debug System > Find loophole > Focus visualization > Project Enchancement > Finalize Project > QA Testing > Deploy Project in Staging Environment > Clone & Deploy in Live Environment > DR monthly

## Study & Research about Django Web

### Learn Django
- Building an application

#### Installation:

    apt install python3.10-venv
    pip3 install virtualenv

#### Creating Virtual Environment:

    python3 -m venv my_env

This will create a my_env/ directory, including Py environment. Any Py libs installed while virtual environment is active will go into my_env/lib/pythonblabla/site-packages directory

#### Activate Virtual Environment:

    source venv/bin/activate

You can deactivate using `source venv/bin/deactivate`

#### Creating 1st Project

    django-admin startproject mysite

Project structure generated:

manage.py : No need to edit this file

__init__.py : Empty file that tells Python to treat as a Python module.

asgi.py : The configuration to run project as ASGI (Asynchronous Web Servers & Applications)

wsgi.py : The configuration to run project as WSGI (Web Server Gateway Interface)

settings.py : The settings and configuration for project and contains initial default settings

urls.py : The place where URL patterns live. Each URL mapped to a view.

    cd mysite
    python3 manage.py migrate

- Enchancing application with advanced features
- Extending application
- Sharing content on application
- Tracking user actions

### Learn Databases
- MySQL
- PostgreSQL

### Authentication and Authorization

## References

### Learn and research how to build Django Web Development from Zero
cs50w - Django
https://youtu.be/w8q0C-C1js4

Example Project(s)
https://github.com/sclorg/django-ex

### Available public open source report generator
pwndoc
<link>

### Export Django from html to pdf
wkhtmltopdf
https://ourcodeworld.com/articles/read/241/how-to-create-a-pdf-from-html-in-django

### Generator graph/chart
1. https://youtu.be/_SipEeFe-cw 
2. https://youtu.be/6yTYP39d9Gs (use this concept to learn how to use .csv to generate output)
3. https://github.com/jakupierblina/Youtube-expert-assist- (using chart.js to generate chart)
