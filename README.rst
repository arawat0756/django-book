Django Book Revival
===================

A revival of Django Book, the comprehensive guide to Django.

I learned Django from this book originally and felt it was a great resource. Now
that Django has (finally) moved on, it would be great to bring the book back up
to date.

*A current work in progress. If you'd like to help, please do. There's plenty of
work to be done!*

Goals
-----

The goal is to overhaul this book with Django 1.5 compatibility and hopefully
keep it up to date with Django 1.5 and beyond!

- Update content and project idioms to be Django 1.5 compatible
- Approach Django advice with a pragmatic attitude, that respects the times and
  tools currently available.
- Remove deprecated Django 1.2 and 1.3 content/idioms
- Work toward a release that is peer reviewed before Django 1.6 launches
- Repeat for Django 1.7 and beyond!

Current Status
--------------

The latest version is always available at ReadTheDocs: http://django-book.readthedocs.org/en/latest/

See the project issues for more current status: https://github.com/askedrelic/django-book/issues

Errata
-------

This book is a fork from the original source code used in the Djagno 1.0 book.
Multiple forks exist and code/advice may be in different states of progress.

- https://github.com/askedrelic/django-book is a fork with the goal of updating
  the Django Book with pragmatic advice from current Django practices. It lives
  at http://django-book.readthedocs.org/en/latest/index.html

- https://github.com/mariuz/django-book is the original fork, which was created
  by importing the original Djagno Book SVN code repository and history.
  (AskedRelic's version was forked from this version).

- https://github.com/jacobian/djangobook.com is a newer fork, from the
  original author of the Django Book. Code/ideas from this fork have tried to be
  incorporated in AskedRelic's fork, but it is a seperate entity. It lives at
  https://github.com/jacobian/djangobook.com


Development
-----------

Assuming you have Python installed, the only dependency is sphinx, available via pip:

 pip install sphinx

Build from the top directory:

 make build

And now the latest HTML documentation will be waiting in *en/_build/html/*

Contribute
----------

Want to contribute some changes?

Pull requests or discussion is pretty open right now, submit what you think
will help via GitHub.

License
-------

From http://djangobook.com/, the original First Edition of The Django book content was released under the
GNU Free Documentation License.

Since the Second Edition, which this project was created from, was also released
on http://djangobook.com/, assuming the same license, this project is also
released under the GNU Free Documentation License.

Meta
----

- Home: https://github.com/askedrelic/django-book
- Authors: https://github.com/askedrelic/django-book/graphs/contributors
