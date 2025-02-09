====================
Account Cut-off Base
====================

.. 
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! This file is generated by oca-gen-addon-readme !!
   !! changes will be overwritten.                   !!
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! source digest: sha256:716c6fa0395c53ee96ebb540f14b2957c9bd4287da0e780dfe301799becadfb5
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

.. |badge1| image:: https://img.shields.io/badge/maturity-Beta-yellow.png
    :target: https://odoo-community.org/page/development-status
    :alt: Beta
.. |badge2| image:: https://img.shields.io/badge/licence-AGPL--3-blue.png
    :target: http://www.gnu.org/licenses/agpl-3.0-standalone.html
    :alt: License: AGPL-3
.. |badge3| image:: https://img.shields.io/badge/github-OCA%2Faccount--closing-lightgray.png?logo=github
    :target: https://github.com/OCA/account-closing/tree/12.0/account_cutoff_base
    :alt: OCA/account-closing
.. |badge4| image:: https://img.shields.io/badge/weblate-Translate%20me-F47D42.png
    :target: https://translation.odoo-community.org/projects/account-closing-12-0/account-closing-12-0-account_cutoff_base
    :alt: Translate me on Weblate
.. |badge5| image:: https://img.shields.io/badge/runboat-Try%20me-875A7B.png
    :target: https://runboat.odoo-community.org/builds?repo=OCA/account-closing&target_branch=12.0
    :alt: Try me on Runboat

|badge1| |badge2| |badge3| |badge4| |badge5|

This module contains models, fields and menu entries that are used by
other cut-off modules ; it doesn't provide useful features by itself. You
need to install other cut-off modules to get the useful features:

* the module *account_cutoff_prepaid* will manage prepaid cut-offs based on
  start date and end date,

* the module *account_cutoff_accrual_picking* will manage the accruals based
  on the status of the pickings.

**Table of contents**

.. contents::
   :local:

Usage
=====

This module is used as a base for other account_cutoff modules.

Bug Tracker
===========

Bugs are tracked on `GitHub Issues <https://github.com/OCA/account-closing/issues>`_.
In case of trouble, please check there if your issue has already been reported.
If you spotted it first, help us to smash it by providing a detailed and welcomed
`feedback <https://github.com/OCA/account-closing/issues/new?body=module:%20account_cutoff_base%0Aversion:%2012.0%0A%0A**Steps%20to%20reproduce**%0A-%20...%0A%0A**Current%20behavior**%0A%0A**Expected%20behavior**>`_.

Do not contact contributors directly about support or help with technical issues.

Credits
=======

Authors
~~~~~~~

* Akretion

Contributors
~~~~~~~~~~~~

* Alexis de Lattre <alexis.delattre@akretion.com>
* Alexandre Fayolle <alexandre.fayolle@camptocamp.com>
* Stéphane Bidoul (ACSONE)
* Adrien Peiffer (ACSONE)
* Pedro M. Baeza <pedro.baeza@gmail.com>
* Jeroen Evens <jeroen.evenss@dynapps.be>

Maintainers
~~~~~~~~~~~

This module is maintained by the OCA.

.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

This module is part of the `OCA/account-closing <https://github.com/OCA/account-closing/tree/12.0/account_cutoff_base>`_ project on GitHub.

You are welcome to contribute. To learn how please visit https://odoo-community.org/page/Contribute.
