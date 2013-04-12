.. ==================================================
.. FOR YOUR INFORMATION 
.. --------------------------------------------------
.. -*- coding: utf-8 -*- with BOM.  Check: ÄÖÜäöüß

.. include:: ../Includes.txt


.. _details-step-5:

==================================================
Details Step 5
==================================================

Add hook processing to your repository
======================================

It's easy!

Go to the settings page of your repository at Github and and fill in
the value for *WebHook URL*. You have to fill in the following URL::

    http://docs.typo3.org/services/handle_github_post_receive_hook.php

Step by step:

(1) Go to the "Settings" for your repository
--------------------------------------------

.. figure:: images/step-5/001-settings.png
   :alt:    Click on Settings
   :class:  screenshot-detail
   :align:  left

   
   
(2) Go to "Service Hooks"
-------------------------

.. figure:: images/step-5/002-service-hooks.png
   :alt:    Click on Service Hooks
   :class:  screenshot-detail
   :align:  left



(3) Choose "WebHook URLs"
-------------------------

.. figure:: images/step-5/003-webhook-url.png
   :alt:    Choose WebHook URLs
   :class:  screenshot-detail
   :align:  left


   
(4) Enter the notification URL
------------------------------

Enter this value::

    http://docs.typo3.org/services/handle_github_post_receive_hook.php

as notification URL:

.. figure:: images/step-5/004-enter-the-url.png
   :class: screenshot-detail
   :align: left

Proceed with :ref:`quickstart-step-6`.