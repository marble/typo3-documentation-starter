.. ==================================================
.. FOR YOUR INFORMATION 
.. --------------------------------------------------
.. -*- coding: utf-8 -*- with BOM.  Check: ÄÖÜäöüß

.. include:: ../Includes.txt


.. _details-step-4:

==================================================
Details Step 4
==================================================

Send `me <martin.bless@typo3.org>`_ an email
============================================

Send `me <martin.bless@typo3.org>`_ an email with some data
so that I can extend this list `list-of-github-manuals.csv.txt 
<http://docs.typo3.org/~mbless/typo3-manage-github-repositories/list-of-github-manuals.csv.txt>`_
on the server:: 

  github_user      , repository_name                          , manual_name_in_url                , url_start
  marble           , typo3-manage-github-repositories         , ManageGithubRepositories          , typo3cms/drafts
  marble           , typo3-incoming-notes                     , IncomingNotes                     , typo3cms/drafts
  marble           , typo3-documentation-contribution-guide   , DocumentationContributionGuide    , typo3cms/drafts
  froemken         , typo3-extbase-guide                      , ExtbaseGuide                      , typo3cms/drafts
  froemken         , typo3-fluid-guide                        , FluidGuide                        , typo3cms/drafts
  

Example with fictitious data
----------------------------

If Donald Duck has a Github account "DONALDDUCK" with a documentation 
repository "duckland-docs" and wants to find it on docs.typo3.org as 
"./typo3cms/drafts/github/DONALDDUCK/Duckland" he would write to me::

  Hi Martin,

  I'm Donald Duck and I'm writing clever documentation for TYPO3
  enthusiasts.
  
  Please allow my new documentation project
     https://github.com/DONALDDUCK/duckland-docs
  on the docs.typo3.org server.
  
  It should have the name
     Duckland

  Quaak quaak and all the best.
  
  Donald

As a result the manual would then be rendered as
``docs.typo3.org/typo3cms/drafts/github/DONALDDUCK/Duckland``

Build information can be found in '.../_make', that is:
``docs.typo3.org/typo3cms/drafts/github/DONALDDUCK/Duckland/_make/``


Example with Real life example
------------------------------

::

  Hi Martin,

  I'm Martin himself. So you know me.
    
  Please allow my new documentation project
     https//github.com/marble/typo3-documentation-starter
  on the docs.typo3.org server.
  
  In the url the name should be
     DocumentationStarter
  and it belongs to typo3cms.
  
  Bye!
  
| As a result the documentation will be rendered at:
|    http://docs.typo3.org/typo3cms/drafts/github/marble/DocumentationStarter
| and Make-information can be found in:
|    http://docs.typo3.org/typo3cms/drafts/github/marble/DocumentationStarter/_make


Minimum information for the email
---------------------------------

If it comes down to a minimum I only need::

   the url of your repository at Github like:
      https://github.com/marble/typo3-documentation-starter

   the name you would like to see for it in the url like:
      DocumentationStarter
   
As you imagine I can easily guess the rest.


Just a moment, please!
----------------------

I'll react as soon as possible and respond with an email telling you
that the server now knows about your documentation project and is
willing to render it at - in this example -: `http://docs.typo3.org/typo3cms/drafts/github/marble/DocumentationStarter`_.

You can always check if the setup has already been done by inspecting 
the file `list-of-github-manuals.csv.txt 
<http://docs.typo3.org/~mbless/typo3-manage-github-repositories/list-of-github-manuals.csv.txt>`_.

Proceed with :ref:`quickstart-step-5`.