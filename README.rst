.. _section-role-util-rolecreator:

Role **util_rolecreator**
================================================================================

.. note::

    This documentation page and role itself is still work in progress.

* `Ansible Galaxy page <https://galaxy.ansible.com/honzamach/util_rolecreator>`__
* `GitHub repository <https://github.com/honzamach/ansible-role-util-rolecreator>`__
* `Travis CI page <https://travis-ci.org/honzamach/ansible-role-util-rolecreator>`__

Ansible role for creating role skeletons.


.. _section-role-util-rolecreator-installation:

Installation
--------------------------------------------------------------------------------

To install the role `honzamach.util_rolecreator <https://galaxy.ansible.com/honzamach/util_rolecreator>`__
from `Ansible Galaxy <https://galaxy.ansible.com/>`__ please use variation of
following command::

    ansible-galaxy install honzamach.util_rolecreator

To install the role directly from `GitHub <https://github.com>`__ by cloning the
`ansible-role-util-rolecreator <https://github.com/honzamach/ansible-role-util-rolecreator>`__
repository please use variation of following command::

    git clone https://github.com/honzamach/ansible-role-util-rolecreator.git honzamach.util_rolecreator

Currently the advantage of using direct Git cloning is the ability to easily update
the role when new version comes out.


.. _section-role-util-rolecreator-usage:

Usage
--------------------------------------------------------------------------------

Use attached role playbook file ``role_util_rolecreator.yml``, there is no need
for customizations.

Example usage::

    # Run everything:
    ansible-playbook --ask-vault-pass --inventory inventory role_util_rolecreator.yml


.. _section-role-util-rolecreator-variables:

Configuration variables
--------------------------------------------------------------------------------


Internal role variables
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. envvar:: hm_util_rolecreator__docs_dir

	  Name of the directory to which to generate the documentation.

	  * *Datatype:* ``string``
    * *Default:* ``"inventory/docs"``


.. _section-role-util-rolecreator-author:

Author and license
--------------------------------------------------------------------------------

| *Copyright:* (C) since 2019 Honza Mach <honza.mach.ml@gmail.com>
| *Author:* Honza Mach <honza.mach.ml@gmail.com>
| Use of this role is governed by the MIT license, see LICENSE file.
|
