============
Mass Editing
============

.. 
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! This file is generated by oca-gen-addon-readme !!
   !! changes will be overwritten.                   !!
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! source digest: sha256:c9d51d11bc437ae3e1379c30ac2c63217b0aac275c04106221192a358ebb5d57
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

.. |badge1| image:: https://img.shields.io/badge/maturity-Beta-yellow.png
    :target: https://odoo-community.org/page/development-status
    :alt: Beta
.. |badge2| image:: https://img.shields.io/badge/licence-AGPL--3-blue.png
    :target: http://www.gnu.org/licenses/agpl-3.0-standalone.html
    :alt: License: AGPL-3
.. |badge3| image:: https://img.shields.io/badge/github-OCA%2Fserver--ux-lightgray.png?logo=github
    :target: https://github.com/OCA/server-ux/tree/16.0/server_action_mass_edit
    :alt: OCA/server-ux
.. |badge4| image:: https://img.shields.io/badge/weblate-Translate%20me-F47D42.png
    :target: https://translation.odoo-community.org/projects/server-ux-16-0/server-ux-16-0-server_action_mass_edit
    :alt: Translate me on Weblate
.. |badge5| image:: https://img.shields.io/badge/runboat-Try%20me-875A7B.png
    :target: https://runboat.odoo-community.org/builds?repo=OCA/server-ux&target_branch=16.0
    :alt: Try me on Runboat

|badge1| |badge2| |badge3| |badge4| |badge5|

This module provides the following features:

* You can add, update or remove the values of more than one records on the fly at the same time.

* You can configure mass editing for any Odoo model.

**Difference between the Odoo 13.0 CE Feature**

Since Odoo V13, a limited "mass Editing feature" is available in Odoo CE.

This module provides the following extra features that are not in the Core
for the time being:

* Possibility to mass edit many fields in a single action
* Possibility to add a group to limit the usage of this function to given
  people
* Possibility to filter the items the user can mass update
* Possibility to mass edit any fields with any widget. (For exemple
  color fields, image fields, etc...)

**Table of contents**

.. contents::
   :local:

Configuration
=============

* Go to *Settings / Technical / Actions / Server Actions* and configure the object and fields for Mass Editing.

* Select the object and add the fields of that object on which you want to apply mass editing.

.. image:: https://raw.githubusercontent.com/OCA/server-ux/16.0/server_action_mass_edit/static/description/mass_editing_form.png
   :width: 70%

* *Add Action*: Click on *Create Contextual Action* to add mass editing in *Action* menu.


**Options**

* You can add an extra message that will be displayed in the wizard.

* This module plays nicely with `server_action_domain`, allowing you to limit
  the mass editing action with a domain.

Usage
=====

* *Go for Mass Editing*: select the records which you want to modify and click on *Action* to open mass editing popup.

.. image:: https://raw.githubusercontent.com/OCA/server-ux/16.0/server_action_mass_edit/static/description/mass_editing-item_tree.png
   :width: 70%

* Select *Set / Remove* action and write down the value to set or remove the value for the given field.

.. image:: https://raw.githubusercontent.com/OCA/server-ux/16.0/server_action_mass_edit/static/description/mass_editing-wizard_form.png
   :width: 70%

* This way you can set / remove the values of the fields.

.. image:: https://raw.githubusercontent.com/OCA/server-ux/16.0/server_action_mass_edit/static/description/mass_editing-item_tree-result.png
   :width: 70%

Known issues / Roadmap
======================

- Auto add fields that are used in related domains if apply_domain=True

Bug Tracker
===========

Bugs are tracked on `GitHub Issues <https://github.com/OCA/server-ux/issues>`_.
In case of trouble, please check there if your issue has already been reported.
If you spotted it first, help us to smash it by providing a detailed and welcomed
`feedback <https://github.com/OCA/server-ux/issues/new?body=module:%20server_action_mass_edit%0Aversion:%2016.0%0A%0A**Steps%20to%20reproduce**%0A-%20...%0A%0A**Current%20behavior**%0A%0A**Expected%20behavior**>`_.

Do not contact contributors directly about support or help with technical issues.

Credits
=======

Authors
~~~~~~~

* Serpent Consulting Services Pvt. Ltd.
* Tecnativa
* GRAP
* Iván Todorovich

Contributors
~~~~~~~~~~~~

* Oihane Crucelaegui <oihanecrucelaegi@gmail.com>
* Serpent Consulting Services Pvt. Ltd. <support@serpentcs.com>
* Jay Vora <jay.vora@serpentcs.com>
* Juan Negrete <jnegrete@casasalce.com>
* Raul Martin <raul.martin@braintec-group.com>
* Aitor Bouzas <aitor.bouzas@adaptivecity.com>
* Sylvain LE GAL (https://twitter.com/legalsylvain)
* Iván Todorovich <ivan.todorovich@gmail.com>

* `Tecnativa <https://www.tecnativa.com>`_

  * Jairo Llopis
  * Víctor Martínez
  * Carlos Dauden
* Tatiana Deribina <tatiana.deribina@spritnit.fi>
* Hieu, Vo Minh Bao <hieu.vmb@komit-consulting.com>

Maintainers
~~~~~~~~~~~

This module is maintained by the OCA.

.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

This module is part of the `OCA/server-ux <https://github.com/OCA/server-ux/tree/16.0/server_action_mass_edit>`_ project on GitHub.

You are welcome to contribute. To learn how please visit https://odoo-community.org/page/Contribute.
