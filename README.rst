The course website for Delft University of Technology's Multibody Dynamics
course. The most recent (or currently running course) is rendered version can
be viewed at:

http://moorepants.github.io/me41055

Prior offerings are at:

- http://moorepants.github.io/me41055/2024
- http://moorepants.github.io/me41055/2023
- http://moorepants.github.io/me41055/2022

Editing Guide
=============

- The website is built using Pelican. Review the `Pelican documentation`_ to
  get familiar with how to create pages and articles.
- The source files are in the git branch called ``master``. This is the default
  branch of the repository. The HTML files are generated via a Github Action
  and pushed to the ``gh-pages`` branch, which is automatically served to
  https://moorepants.github.io/me41035. You should not have to ever manually
  edit files in the ``gh-pages`` branch.
- All articles, pages, and similar content should be written in
  reStructuredText. See the `Sphinx reStructuredText primer`_ to learn the
  syntax.
- All changes, in general, should be submitted as Github pull requests. Don't
  commit directly to the ``master`` branch.
- Binary Assets such as images, videos, etc should be served from an external
  hosting site. For now, send these files to Jason and he'll host using his
  Dreamhost DreamObject bucket. Do not commit binary assets to this repository.
- You can edit and add rst files directly in the contents directory using the
  Github interface. The small pencil on files lets you edit and submit pull
  requests. Just above the directory view has buttons for adding files. See
  these instructions:
  https://help.github.com/en/articles/editing-files-in-your-repository

.. _Pelican documentation: http://docs.getpelican.com/en/stable/
.. _Sphinx reStructuredText primer: http://www.sphinx-doc.org/en/master/usage/restructuredtext/basics.html

Building Locally
================

It is good practice to build the documentation locally so that you can review
change before submitting a pull request.

Install pelican and pyyaml with conda (or pip if you prefer)::

   $ conda install pelican pyyaml

Clone the theme repository (make sure to use the ``mechmotum`` branch)::

   $ git clone --branch mechmotum git@github.com:mechmotum/pelican-alchemy.git

Note the path to the theme, e.g.::

   /home/my_username/.../pelican-alchemy/alchemy

Clone the pelican-plugins repository::

   $ git clone git@github.com:getpelican/pelican-plugins.git

Note the path to the plugins directory, e.g.::

   /home/my_username/.../pelican-plugins

Clone this repository and change into the new directory::

   $ git clone git@github.com:moorepants/me41055.git
   $ cd me41055/

Create a configuration file called ``config.yml`` and add the full path to
where you installed the theme::

   $ echo "THEME_PATH: /home/my_username/.../pelican-alchemy/alchemy" > config.yml
   $ echo "PLUGIN_PATHS: /home/my_username/.../pelican-plugins" >> config.yml

Now you can build and serve the documentation with::

   $ make devserver

If this succeeds you can open the website in your web browser at
http://localhost:8000.

While the server is running you can change the website source files and they
will be build automatically. Refresh your web browser to view the changes.

To stop the web server press <CTRL + C>.

LICENSE
=======

These contents of this repository are licensed under the CC-BY 4.0 license.
