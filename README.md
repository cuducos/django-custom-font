# Django with custom CSS FONT

A friend of mine asked for a straightforward example about how to use a custom font in Django. Here it is ; )

## Install

### Dependencies

In a Python 3 (virtual) environment:

```console
$ pip install Django==2.2
```

### Run

Simply follow Django's default:

```console
$ python manage.py runserver
```

## Step-by-step implementation

This repo contains only 3 commits. Here is a summary of what they do.

### 1. Basic Django installation

This install Django and sets a home page at the root of the server that just renders `core/templates/core/index.html`.

Runnning the server and opening the home page you should see a heading with your browser's custom font.


### 2. Set basic CSS & static files

This makes the basic setup for Django to handle and serve static files. In order to test it to see if works, it applies a custom font on `h1` HTML tags.

Runnning the server and opening the home page you should see the heading with a `sans-serif` font.

### 3. Use Django ITC Std font

This commit uses [Django ITC Std](https://www.maisfontes.com/django-itc-std)'s `.otf` file to load a custom font and applies it to `h1` HTML tags.

Runnning the server and opening the home page you should see the heading with this sample custom font.

 
