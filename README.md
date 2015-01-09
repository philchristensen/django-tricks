# django-tricks
A Django app that enables various ridiculous tricks.

## tricks.middleware.GrandpaSimpsonMiddleware
To append witticisms from Grandpa Simpson to outgoing HTTP headers (inspired by Slashdot's X-Bender and X-Fry headers),
just add `tricks.middleware.GrandpaSimpsonMiddleware` to `MIDDLEWARE_CLASSES`