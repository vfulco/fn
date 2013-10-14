Food News
=========

[Food News](http://food.hypertexthero.com) is a Hacker News clone, built using [Drum](http://drum.jupo.org/) & [Mezzanine](http://http://mezzanine.jupo.org/). Uses [Mozilla Persona](https://persona.org) for authentication. More [in this post](http://hypertexthero.com/logbook/2013/10/intro-food-news/).

Things To Do
==========

- IE test
- Deployment Issues
    - Find out why gunicorn command throws an error (currently running with `gunicorn_django` instead)
    - Find out why when using memcached the site breaks and shows code inside `{% nevercache %}` tags.
- FAQ and guidelines
- HTTPS
- Search comments
- [Title case](https://pypi.python.org/pypi/titlecase/0.4) for link title?


For Future Refactoring
======================

- [Users should be be redirected to proper page & action after login](https://github.com/mozilla/django-browserid/issues/205)
- [Disable password fields in profile update form](http://stackoverflow.com/a/12648124/412329)