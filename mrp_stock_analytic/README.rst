==================
MRP Stock Analytic
==================

.. 
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! This file is generated by oca-gen-addon-readme !!
   !! changes will be overwritten.                   !!
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! source digest: sha256:c9d68859541dd43ed5f6e30c0a788dadd8b6d859c7c69bf28fc4559b658c6ec8
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

.. |badge1| image:: https://img.shields.io/badge/maturity-Beta-yellow.png
    :target: https://odoo-community.org/page/development-status
    :alt: Beta
.. |badge2| image:: https://img.shields.io/badge/licence-AGPL--3-blue.png
    :target: http://www.gnu.org/licenses/agpl-3.0-standalone.html
    :alt: License: AGPL-3
.. |badge3| image:: https://img.shields.io/badge/github-OCA%2Faccount--analytic-lightgray.png?logo=github
    :target: https://github.com/OCA/account-analytic/tree/16.0/mrp_stock_analytic
    :alt: OCA/account-analytic
.. |badge4| image:: https://img.shields.io/badge/weblate-Translate%20me-F47D42.png
    :target: https://translation.odoo-community.org/projects/account-analytic-16-0/account-analytic-16-0-mrp_stock_analytic
    :alt: Translate me on Weblate
.. |badge5| image:: https://img.shields.io/badge/runboat-Try%20me-875A7B.png
    :target: https://runboat.odoo-community.org/builds?repo=OCA/account-analytic&target_branch=16.0
    :alt: Try me on Runboat

|badge1| |badge2| |badge3| |badge4| |badge5|

Allows to assign the analytic distribution in the manufacturing order, which should
propagate the value to the corresponding field of the related component stock moves.

This function can be useful when cost analysis needs to be done on flushed components.

This module depends on OCA module stock_analytic.

**Table of contents**

.. contents::
   :local:

Configuration
=============

Refer to the relevant section of the stock_analytic module.

Usage
=====

Set analytic distribution on a manufacturing order, complete it, and analytic lines will
be generated accordingly for the flushed components when automatic inventory valuation
is enabled for the product category.

Bug Tracker
===========

Bugs are tracked on `GitHub Issues <https://github.com/OCA/account-analytic/issues>`_.
In case of trouble, please check there if your issue has already been reported.
If you spotted it first, help us to smash it by providing a detailed and welcomed
`feedback <https://github.com/OCA/account-analytic/issues/new?body=module:%20mrp_stock_analytic%0Aversion:%2016.0%0A%0A**Steps%20to%20reproduce**%0A-%20...%0A%0A**Current%20behavior**%0A%0A**Expected%20behavior**>`_.

Do not contact contributors directly about support or help with technical issues.

Credits
=======

Authors
~~~~~~~

* Quartile Limited

Contributors
~~~~~~~~~~~~

* `Quartile <https://www.quartile.co>`__:

  * Yoshi Tashiro

Maintainers
~~~~~~~~~~~

This module is maintained by the OCA.

.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

This module is part of the `OCA/account-analytic <https://github.com/OCA/account-analytic/tree/16.0/mrp_stock_analytic>`_ project on GitHub.

You are welcome to contribute. To learn how please visit https://odoo-community.org/page/Contribute.
