========
Software
========

:title: Software
:sortorder: 2

We will learn multibody dynamics through the use of computation in Jupyter_
Notebooks. You will use popular software packages that are part of the open
source scientific Python ecosystem of tools. The first and primary tool is
SymPy_ which is a computer algebra system that includes a sub-package for
deriving symbolic equations of motion. You will also learn to use NumPy_,
SciPy_, Matplotlib_, and various other relevant packages for simulation and
visualization.

.. _Jupyter: https://jupyter.org
.. _SymPy: https://sympy.org
.. _NumPy: https://numpy.org
.. _SciPy: https://scipy.org
.. _Matplotlib: https://matplotlib.org

Running The Software via Brightspace-Vocareum
=============================================

Log into Brightspace and navigate to Content -> Vocareum. For each assignment
you will be able to open a Vocareum workspace that gives you access to Jupyter
and Jupyter Notebooks.

Vocareum: Backing Up Your Work
------------------------------

The Vocareum server has automated backups in place should any problems occur,
but it is recommended to download your notebooks for safe keeping and use
outside of the class. Vocareum access is disabled for students once the class
is finished.

Vocareum: SymPy Version Too Old
-------------------------------

If you get errors such as these:

.. code-block:: python

   AttributeError: 'ReferenceFrame' object has not attribute 'orient_axis`
   AttributeError: 'ReferenceFrame' object has not attribute 'orient_explicit`
   AttributeError: 'ReferenceFrame' object has not attribute 'orient_body_fixed`

Then your version of SymPy is too old. SymPy should be version 1.9 or greater
for this course. You can check the version of SymPy in your notebook with:

.. code-block:: python

   import sympy as sm
   print(sm.__version__)

Vocareum only has SymPy 1.9+ available on the Python 3.8 kernel. You may need
to change your kernel by selecting "Kernel" in the toolbar menu, then "Change
kernel", and then select "Python 3.8".

Vocareum: Collaborating on Notebooks
------------------------------------

If you work on an assignment as a pair in Vocareum, you both can open the same
notebook simultaneously on each of your computers, **but you cannot edit the
notebooks simulateounsly**. If you both edit the notebook, the person who saves
the notebook first will overwrite the other's work. Vocareum does not support
simultaneous editing of Jupyter Notebooks. We recommend making a copy of the
main notebook for the second partner to work it. You can then merge your work
into the main notebook one at a time.

Installing the Software On Your Personal Computer
=================================================

You can also install all of the software used in this course on your personal
computer. There are numerous ways to set up a scientific Python environment.
For beginners, we recommend that you install the Anaconda_ distribution of
Python which includes most all of the packages you will need.

.. _Anaconda: https://www.anaconda.com/download/

Once you have Anaconda installed we recommend adding the `Conda Forge`_ channel to
expand the number of recently updated software packages available to install.
To do so, open the terminal (Linux/Mac) or Anaconda command prompt (Windows)
and execute these commands:

.. code-block:: bash

   conda config --add channels conda-forge
   conda config --set channel_priority strict

Once you've added the Conda Forge channel, you can install and update extra
packages with:

.. code-block:: bash

   conda install sympy numpy scipy matplotlib jupyter pythreejs "scikits.odes"

.. _Conda Forge: https://conda-forge.org/

.. topic:: pip vs conda
   :class: alert alert-warning

   Many websites will tell you to use ``pip package_name`` to install Python
   packages. Since you are using Anaconda, always try to ``conda install
   package_name`` the package first. Mixing pip installed packages is possible
   but can cause some issues. More info on using pip packages in conda
   enviroments can be found here:
   https://www.anaconda.com/blog/using-pip-in-a-conda-environment

You can open up Jupyter notebooks directly by typing:

.. code-block:: bash

   juypter notebook

in the terminal (Linux/Mac) or the Anaconda command prompt (Windows) or
selecting Jupyter Notebook in the Anaconda Navigator application. You can also
run Jupyter notebooks using the Spyder IDE (by typing ``spyder`` or using
Anaconda Navigator).

Learning Python For Engineering Computation
===========================================

There are many introductory resources for learning to use Jupyter which can be
found with search engines. As examples, this RealPython introduction is a good
start (ignore the installation part, as you have it installed already):

https://realpython.com/jupyter-notebook-introduction/

and this video is a 7 minute video that also gives the basics:

.. raw:: html

   <iframe width="560" height="315"
   src="https://www.youtube.com/embed/jZ952vChhuI" title="YouTube video player"
   frameborder="0" allow="accelerometer; autoplay; clipboard-write;
   encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Your search engine will lead you to many more resources.

After you are comfortable using Jupyter, start with the SymPy tutorial to get
familiar with symbolic manipulation in Python:

https://docs.sympy.org/latest/tutorial/

The SymPy Physics Vector and Mechanics documentation provides explanations for
the advanced features for rigid body mechanics:

- https://docs.sympy.org/latest/modules/physics/vector
- https://docs.sympy.org/latest/modules/physics/mechanics

To learn the core Python language (not scientific oriented computing) there are
many many resources. My recommendations for beginners are:

- Allen Downey's book ThinkPython_.
- The tutorial on Python.org: https://docs.python.org/3/tutorial/

.. _ThinkPython: http://greenteapress.com/wp/think-python/

Python becomes most powerful for engineers by using the various packages in the
scientific Python Ecosystem. Here are my recommend resources for learning these
topics:

- The SciPy Lecture Notes is a wholistic resource for all things numerical
  computing in Python: http://www.scipy-lectures.org/
- The open access book "`Python Programming and Numerical Methods
  <https://pythonnumericalmethods.berkeley.edu>`_" covers introductory
  materials in scientific and engineering computing.
- The book "Effective Computation in Physics" by Anthony Scopatz & Kathryn Huff is
  a guide that starts at ground zero for Python and leads you through the tools
  and methods to be a computational engineer. http://physics.codes/
- If you know some Matlab this guide is very helpful for looking up equivalent
  commands in NumPy: `NumPy for Matlab Users
  <https://numpy.org/doc/stable/user/numpy-for-matlab-users.html>`_.
- Getting good at asking Google about programming questions will almost always
  lead you to https://stackoverflow.com/ which is a key resources. Check out
  the sympy, numpy, scipy, and matplotlib tags, for example.

Each software package also has documentation:

- Jupyter: https://docs.jupyter.org
- Matplotlib: https://matplotlib.org/contents.html
- NumPy: https://numpy.org/doc/stable
- SciPy: https://docs.scipy.org/doc/scipy/reference/
- SymPy: http://docs.sympy.org/latest/index.html

Other Jupyter Notebook online services
======================================

There are many other services for working with Jupyter notebooks that provide
different features, for example:

- `CoCalc <https://cocalc.com/>`_
- `Google Colaboratory <https://colab.research.google.com/>`_
- `binder <https://mybinder.org/>`_

This article gives pros and cons of each:
https://www.dataschool.io/cloud-services-for-jupyter-notebook/.
