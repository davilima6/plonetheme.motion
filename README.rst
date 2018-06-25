=================
plonetheme.motion
=================

`Davi Lima`_'s Diazo_ version from `Wordpress Motion Theme`_ by **Volcanic**, `Web Design Company`_.


Introduction
============

*plonetheme.motion* package is an installable Plone Theme developed by `Davi Lima`_
using the **theming** and **packaging** features available in
`plone.app.theming`_.


Requirements
============

- From the Plone 4.1.x To the Plone 4.3 latest version (https://plone.org/download)
- The ``plone.app.theming`` package (*will be installed as a dependency of this package*)


Screenshots
===========

Layout of the site when viewed in a computer resolution:

.. image:: https://github.com/davilima6/plonetheme.motion/raw/master/plonetheme/motion/static/preview.png


Features
========

- It's an installable Plone_ Theme package.
- After installation from Add-ons controlpanel, this theme is enabled automatically.
- Also it's a simple Diazo_ package (Zip file).
- It's have support for clean uninstallation.


Installation
============


Buildout
--------

If you are a **developer user**, you might enjoy installing it via buildout.

For install ``plonetheme.motion`` package add it to your ``buildout`` section's 
*eggs* parameter e.g.: ::

   [buildout]
    ...
    eggs =
        ...
        plonetheme.motion


and then running ``bin/buildout``.

Or, you can add it as a dependency on your own product ``setup.py`` file: ::

    install_requires=[
        ...
        'plonetheme.motion',
    ],


Zip file
--------

If you are an **end user**, you might enjoy installation via zip file import.

1. Download a `zip file <https://github.com/davilima6/plonetheme.motion/raw/master/motion.zip>`_.
2. Import the theme from the Diazo theme control panel.


Enabling the theme
^^^^^^^^^^^^^^^^^^

Browse to ``http://yoursite/Plone/@@theming-controlpanel`` click on ``Enable`` on ``Plonetheme Motion`` theme from the Diazo control panel. That's it!


Contribute
==========

- Issue Tracker: https://github.com/davilima6/plonetheme.motion/issues
- Source Code: https://github.com/davilima6/plonetheme.motion


License
=======

The project is licensed under the GPLv2.


Credits
-------

- Davi Lima (davilima6 at gmail dot com) - Diazo rules, HTML tidying.

- Volcanic - Layout and initial HTML implementation.

- Leonardo J. Caballero G. (leonardocaballero at gmail dot com).


.. _`Davi Lima`: https://twitter.com/davilima6
.. _`Wordpress Motion Theme`: https://wordpress.com/theme/motion
.. _`Web Design Company`: http://www.webdesigncompany.net/motion/
.. _`Plone`: http://plone.org
.. _`plone.app.theming`: https://pypi.org/project/plone.app.theming/
.. _`Diazo`: http://diazo.org