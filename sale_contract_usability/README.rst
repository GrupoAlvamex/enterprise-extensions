.. image:: https://img.shields.io/badge/licence-AGPL--3-blue.svg
   :target: http://www.gnu.org/licenses/agpl-3.0-standalone.html
   :alt: License: AGPL-3

=======================
Sale Contract Usability
=======================

#. This module add to company form a boolean to take the field description in subcritions to recurring invoices.
#. Make date (date end) field visible in every state, by default is is only visible on close state (that does not make much sense)
#. Odoo cleans date end when you set contract opened, we delete that behviour and leave date end value
#. We add constraint so that date end must by greater than start date
#. Add require dates (template_dates_required) parameter on contract template and make them required on contracts if needed
#. Add default term (template_default_term) parameter on contract template and, if setted, compute automatically end date field when start date changes


Installation
============

To install this module, you need to:

#. Just Install this module

Configuration
=============

To configure this module, you need to:

#. No configuration needed

Usage
=====

To use this module, you need to:

#. Go to Company Configuration in "Sales" mark "Copy Contract Description"

.. image:: https://odoo-community.org/website/image/ir.attachment/5784_f2813bd/datas
   :alt: Try me on Runbot
   :target: https://runbot.adhoc.com.ar/

.. repo_id is available in https://github.com/OCA/maintainer-tools/blob/master/tools/repos_with_ids.txt
.. branch is "8.0" for example

Known issues / Roadmap
======================

* ...

Bug Tracker
===========

Bugs are tracked on `GitHub Issues
<https://github.com/ingadhoc/enterprise-extensions/issues>`_. In case of trouble, please
check there if your issue has already been reported. If you spotted it first,
help us smashing it by providing a detailed and welcomed feedback.

Credits
=======

Images
------

* ADHOC SA: `Icon <http://fotos.subefotos.com/83fed853c1e15a8023b86b2b22d6145bo.png>`_.

Contributors
------------


Maintainer
----------

.. image:: http://fotos.subefotos.com/83fed853c1e15a8023b86b2b22d6145bo.png
   :alt: Odoo Community Association
   :target: https://www.adhoc.com.ar

This module is maintained by the ADHOC SA.

To contribute to this module, please visit https://www.adhoc.com.ar.
