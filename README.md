# stArticle

This is a small blogging page that lets you to write articles with your friends or whoever you want

# Requirements

For this application to work you must install these packages by using the [pip] (https://pip.pypa.io/en/stable/) package installer

```bash
from flask import Flask, render_template, flash, redirect, url_for, session, request, logging
from flask_mysqldb import MySQL
from wtforms import Form, StringField, TextAreaField, PasswordField, validators
from passlib.hash import sha256_crypt
from functools import wraps

```
# stArting the application

To start the application just simply go to [app.py] and run it. If you have visual studio code installed just use the [F5] button on your keyboard.

This mini project was made during my time at [BONEVET]
