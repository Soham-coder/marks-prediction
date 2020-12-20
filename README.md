# Marks-Prediction

### This ML web app is deployed to heroku gunicorn server.


a[href='red'] {
    color: red;
    pointer-events: none;
    cursor: default;
    text-decoration: none;
}

<a href="red"><details><summary> HEROKU BUILD LOG </summary></a>
<p>


```prompt
-----> Python app detected
-----> Installing python-3.6.12
-----> Installing pip 20.1.1, setuptools 47.1.1 and wheel 0.34.2
-----> Installing SQLite3
-----> Installing requirements with pip
       Collecting numpy
         Downloading numpy-1.19.4-cp36-cp36m-manylinux2010_x86_64.whl (14.5 MB)
       Collecting pandas
         Downloading pandas-1.1.5-cp36-cp36m-manylinux1_x86_64.whl (9.5 MB)
       Collecting scikit-learn==0.21.2
         Downloading scikit_learn-0.21.2-cp36-cp36m-manylinux1_x86_64.whl (6.7 MB)
       Collecting Click==7.0
         Downloading Click-7.0-py2.py3-none-any.whl (81 kB)
       Collecting Flask==1.1.1
         Downloading Flask-1.1.1-py2.py3-none-any.whl (94 kB)
       Collecting gunicorn==19.9.0
         Downloading gunicorn-19.9.0-py2.py3-none-any.whl (112 kB)
       Collecting itsdangerous==1.1.0
         Downloading itsdangerous-1.1.0-py2.py3-none-any.whl (16 kB)
       Collecting Jinja2==2.10.1
         Downloading Jinja2-2.10.1-py2.py3-none-any.whl (124 kB)
       Collecting MarkupSafe==1.1.1
         Downloading MarkupSafe-1.1.1-cp36-cp36m-manylinux1_x86_64.whl (27 kB)
       Collecting Werkzeug==0.15.6
         Downloading Werkzeug-0.15.6-py2.py3-none-any.whl (328 kB)
       Collecting pytz>=2017.2
         Downloading pytz-2020.4-py2.py3-none-any.whl (509 kB)
       Collecting python-dateutil>=2.7.3
         Downloading python_dateutil-2.8.1-py2.py3-none-any.whl (227 kB)
       Collecting joblib>=0.11
         Downloading joblib-1.0.0-py3-none-any.whl (302 kB)
       Collecting scipy>=0.17.0
         Downloading scipy-1.5.4-cp36-cp36m-manylinux1_x86_64.whl (25.9 MB)
       Collecting six>=1.5
         Downloading six-1.15.0-py2.py3-none-any.whl (10 kB)
       Installing collected packages: numpy, pytz, six, python-dateutil, pandas, joblib, scipy, scikit-learn, Click, Werkzeug, MarkupSafe, Jinja2, itsdangerous, Flask, gunicorn
       Successfully installed Click-7.0 Flask-1.1.1 Jinja2-2.10.1 MarkupSafe-1.1.1 Werkzeug-0.15.6 gunicorn-19.9.0 itsdangerous-1.1.0 joblib-1.0.0 numpy-1.19.4 pandas-1.1.5 python-dateutil-2.8.1 pytz-2020.4 scikit-learn-0.21.2 scipy-1.5.4 six-1.15.0
-----> Discovering process types
       Procfile declares types -> web
-----> Compressing...
       Done: 110.8M
-----> Launching...
       Released v3
       https://marks-prediction39.herokuapp.com/ deployed to Heroku
```
</p>
</details>

https://marks-prediction39.herokuapp.com/

*It's a fun application which will get you your expected marks once you give prompt for number of hours of study*.

```diff
! Heroku does not actually encourage free gifts. If it finds less traffic/requests coming to the webapp it will delete your account without notifying you :(
# So you may find this web app getting expired
```

# Deployed app image
![Image](https://github.com/Soham-coder/marks-prediction/blob/master/heroku_app.PNG)

