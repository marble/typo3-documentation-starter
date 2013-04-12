.. ==================================================
.. FOR YOUR INFORMATION 
.. --------------------------------------------------
.. -*- coding: utf-8 -*- with BOM.  Check: ÄÖÜäöüß

.. include:: ../Includes.txt




.. to remove this chapter "Quickstart" from your documentation:

   1. delete the folder ./Documentation/Quickstart
   2. remove the line 
      "   Quickstart/Index"
      from ./Documentation/Index.rst



==================================================
Quickstart
==================================================

Some quick steps that get you going with actual *writing*
**and publishing** really fast!

Start documenting **and publishing** within five minutes
========================================================



.. _quickstart-step-1:

Step 1
------

Get yourself an account at `Github <https://github.com/>`_. It's free!
You need one? See the :ref:`details <details-step-1>` of how to get one.



.. _quickstart-step-2:

Step 2
------

Fork the `TYPO3 Documentation Starter 
<https://github.com/marble/typo3-documentation-starter>`_.
See the :ref:`details <details-step-2>`.



.. _quickstart-step-3:

Step 3
------

Rename the forked starter to something you like.
See the :ref:`details <details-step-3>`.



.. _quickstart-step-4:

Step 4
------

Send `me <martin.bless@typo3.org>`_ an email with a few words. 
See the :ref:`details <details-step-4>`.



.. _quickstart-step-5:

Step 5
------

Important: Add hook processing to your Github repository. 
See the :ref:`details <details-step-5>` on how to do it.



.. _quickstart-step-6:

Step 6
------

You're done!

- Clone your own repository
- Start writing
- Push to your repository whenever you like to.

**This is the magic** that will happen:

- The server will pull the changes and do a fresh rendering within five
  minutes.

- whenever you push to your Github repository Github will notify the 
  docs.typo3.org server.

- Visit the '\_make' folder of your documentationen to find out if there
  have been any warnings or errors. For example: See the
  `_make folder of this manual`__

__ http://docs.typo3.org/typo3cms/drafts/DocumentationStarter/_make

Enjoy!


Some help with ReST and Sphinx
------------------------------

* Look at `chapter 1 of the "Official Manual" 
  <http://docs.typo3.org/typo3cms/OfficialManualExample/Chapter1/>`_
  to find out about basic ReST idioms, lists, tables, ...
  
* Look at Sphinx: http://sphinx-doc.org/
  
  A project http://www.pocoo.org/projects/sphinx/#sphinx 
  by Georg Brandl http://www.pocoo.org/team/#georg-brandl
  at http://www.pocoo.org/
  
* The basic ReST features are provided by the "Docutils":
  http://docutils.sourceforge.net/rst.html
  
* A nicer rendering of the Docutils documentation is here:
  http://docs.typo3.org/~mbless/DOCROOT_HTDOCS/World/Docutils/html/
  
  Start with:
  
  - http://docs.typo3.org/~mbless/DOCROOT_HTDOCS/World/Docutils/html/docutils-docs/user/rst/quickstart.html
  - http://docs.typo3.org/~mbless/DOCROOT_HTDOCS/World/Docutils/html/docutils-docs/peps/ref/rst/restructuredtext.html
  - http://docs.typo3.org/~mbless/DOCROOT_HTDOCS/World/Docutils/html/_sources/docutils-docs/user/rst/demo.txt
  - http://docs.typo3.org/~mbless/DOCROOT_HTDOCS/World/Docutils/html/docutils-docs/peps/ref/rst/directives.html
  
.. attention::

   Some directives of the Docutils have different
   names in Sphinx or work differently.
  


Next pages:

.. toctree::
   :maxdepth: 5
   :glob:
   :titlesonly:

   *

:ref:`Sitemap <sitemap>`   