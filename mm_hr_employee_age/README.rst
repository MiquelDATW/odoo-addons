.. image:: https://img.shields.io/badge/licence-AGPL--3-blue.svg
    :alt: License: AGPL-3

HR Employee Age
===============

Adds age field on employee and creates a cron that computes and stores the age daily.
Being a stored field allows to do searches on that field.

Installation
============

* hr

Configuration
=============

Once installed, activate the developer mode and go to:

* Settings > Technical > Automation > Scheduled Actions
* Select "Compute employee's age"
* Edit and change the field "Next Execution Date" to past midnight
* Save


Usage
=======

To use this module, go to:

* Employees > Employees
* Select an employee
* Select the "Private Information" page
* Edit the field "Date of birth"
* Save
* The "Age" field is just after the "Date of birth" field

❗ Please take notice that the field "Date of birth" does not check if the date makes sense,
so it is possible to have nonsensical or even negative ages.

Credits
=======

All emojis designed by `OpenMoji <https://openmoji.org/>`__ – the open-source emoji and icon project. License: `CC BY-SA 4.0 <https://creativecommons.org/licenses/by-sa/4.0/>`__

Contributors
------------

* Miquel March <m.marchpuig@gmail.com>

Maintainer
----------

`MiquelDATW <https://github.com/MiquelDATW/odoo-addons/tree/11.0>`__
--------------------------------------------------------------------



