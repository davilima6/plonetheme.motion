===============================================
Diazo Motion
===============================================

.. contents:: Table of Contents
   :depth: 2

Overview
--------

Diazo Motion is an installable Plone Theme developed by `Davi Lima`_
using the **theming** and **packaging** features available in
`plone.app.theming`_.

Requirements
------------

    * Plone 4.1.x (http://plone.org/products/plone)
    
    * plone.app.theming (*will be installed as a dependency of this package*)

Screenshots
------------

Layout of the site when viewed in a computer resolution:

.. image:: http://svn.plone.org/svn/collective/plonetheme.motion/trunk/screenshot.jpg

Installation
------------

Getting the theme
~~~~~~~~~~~~~~~~~~~~

Zip file
++++++++++

If you are an end user, you might enjoy installation via zip file import.

    1. Download a `zip file <http://svn.plone.org/svn/collective/plonetheme.motion/trunk/motion.zip>`_ 
        
    2. Import the theme from the Diazo theme control panel.

Buildout
++++++++++

If you are a developer, you might enjoy installing it via buildout.

Add ``plonetheme.motion`` to your ``plone.recipe.zope2instance`` section's *eggs* parameter e.g.::

    [instance]
    eggs =
        Plone
        ...
        plonetheme.motion

Or, you can add it as a dependency on your own product *setup.py*::

    install_requires=[
        ...
        'plonetheme.motion',
    ],


Enabling the theme
~~~~~~~~~~~~~~~~~~~~

    Select and enable the theme from the Diazo control panel. That's it!


Credits
-------

    * Davi Lima (davilima6 at gmail dot com) - Diazo rules, HTML tidying.

    * Volcanic - Layout and initial HTML implementation.
    
.. _`plone.app.theming`: http://pypi.python.org/pypi/plone.app.theming
.. _`Plone 4.1`: http://pypi.python.org/pypi/Plone/4.1

