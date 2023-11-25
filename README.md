# django-tutorial
## Messing around with a Django tutorial in 2023

I first got exposed to Django in 2018 at work when I had a role that made heavy use of it.  I was on a team with two other engineers and some things I loved about Django included:
- Database abstraction - I really had a lot of appreciation for this since I've used databases a lot over the years
    - Schema definitions of tables
    - Object-oriented [CRUD](https://en.wikipedia.org/wiki/Create,_read,_update_and_delete) operations
    - Agnostic layer owning new allegiance to database providers - theoretically, you can swap out Postgres for MySQL or whatever
    - Automatic database migration scripts - great in a collaborative incremental development environment!
- Easy creation of REST APIs

I learned a lot while just carrying out our project but also through a tutorial - the use of the tutorial is the subject of [my djangogirls-tutorial repo](https://github.com/pfuntner/djangogirls-tutorial-2018) (which I've since archived).

## Revisiting Django
I left that role after about 9 months and use Python every day but didn't have a need to use Django so I didn't keep up with it.  I'm pretty sure back in 2018 I was probably still in the Python 2 camp and had some strong opinions about the Python 3 changes.  Since then I'm a Python 3 convert and have left Python 2 in the dust.

I'm really interested in playing with Django more and plan on using a new tutorial.  [A tutorial on the Django site](https://docs.djangoproject.com/en/4.2/intro/tutorial01/) is a candidate but I figure there are others as well, especially in the time since 2018.

I've already installed a pretty recent version of Django:
```
$ python -m pip install Django==4.2.6
Defaulting to user installation because normal site-packages is not writeable
Collecting Django==4.2.6
  Obtaining dependency information for Django==4.2.6 from https://files.pythonhosted.org/packages/b9/45/707dfc56f381222c1c798503546cb390934ab246fc45b5051ef66e31099c/Django-4.2.6-py3-none-any.whl.metadata
  Downloading Django-4.2.6-py3-none-any.whl.metadata (4.1 kB)
Collecting asgiref<4,>=3.6.0 (from Django==4.2.6)
  Obtaining dependency information for asgiref<4,>=3.6.0 from https://files.pythonhosted.org/packages/9b/80/b9051a4a07ad231558fcd8ffc89232711b4e618c15cb7a392a17384bbeef/asgiref-3.7.2-py3-none-any.whl.metadata
  Downloading asgiref-3.7.2-py3-none-any.whl.metadata (9.2 kB)
Collecting sqlparse>=0.3.1 (from Django==4.2.6)
  Downloading sqlparse-0.4.4-py3-none-any.whl (41 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 41.2/41.2 kB 2.2 MB/s eta 0:00:00
Collecting typing-extensions>=4 (from asgiref<4,>=3.6.0->Django==4.2.6)
  Obtaining dependency information for typing-extensions>=4 from https://files.pythonhosted.org/packages/24/21/7d397a4b7934ff4028987914ac1044d3b7d52712f30e2ac7a2ae5bc86dd0/typing_extensions-4.8.0-py3-none-any.whl.metadata
  Downloading typing_extensions-4.8.0-py3-none-any.whl.metadata (3.0 kB)
Downloading Django-4.2.6-py3-none-any.whl (8.0 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 8.0/8.0 MB 34.0 MB/s eta 0:00:00
Downloading asgiref-3.7.2-py3-none-any.whl (24 kB)
Downloading typing_extensions-4.8.0-py3-none-any.whl (31 kB)
Installing collected packages: typing-extensions, sqlparse, asgiref, Django
Successfully installed Django-4.2.6 asgiref-3.7.2 sqlparse-0.4.4 typing-extensions-4.8.0
$ python -m django --version
4.2.6
$
```

Along with learning Django in 2018 I also picked up the use of [the PyCharm IDE](https://www.jetbrains.com/pycharm/) which I continue to use and probably will continue to do so.  I'm one of those weird sorts who still likes to edit stuff directly on machines using `vi` but there are definitely advanages of an IDE.
