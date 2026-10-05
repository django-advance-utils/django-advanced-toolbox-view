[![PyPI version](https://img.shields.io/pypi/v/django-advanced-toolbox-view)](https://pypi.org/project/django-advanced-toolbox-view/)

# django-advanced-toolbox-view

The [django-advance-utils](https://github.com/django-advance-utils) line of Ian Jones's
[django-toolbox-view](https://github.com/jonesim/django-toolbox-view), forked so that it depends on the
django-advance-utils packages instead of the originals. The Python package is still `toolbox_view`, so
existing imports and `INSTALLED_APPS` entries do not change; only the pip name does.

    pip install django-advanced-toolbox-view

Gives a view showing functions defined in django apps in a toolbox module. 
Optionally functions can be run as a celery task   