=====================================================
|chef solo| (executable)
=====================================================

.. include:: ../../includes_chef_solo/includes_chef_solo.rst

.. include:: ../../includes_ctl_chef_solo/includes_ctl_chef_solo.rst

Options
=====================================================
.. include:: ../../includes_ctl_chef_solo/includes_ctl_chef_solo_options.rst

Run as Non-root User
=====================================================
.. include:: ../../includes_ctl_chef_solo/includes_ctl_chef_solo_non_root.rst

Examples
=====================================================
**Run chef-solo using solo.rb settings**

.. code-block:: bash

   $ chef-solo -c ~/chef/solo.rb

**Use a URL**

.. include:: ../../step_ctl_chef_solo/step_ctl_chef_solo_use_url.rst

**Use a directory**

.. include:: ../../step_ctl_chef_solo/step_ctl_chef_solo_use_directory.rst

**Use a URL for cookbook and JSON data**

.. include:: ../../step_ctl_chef_solo/step_ctl_chef_solo_url_for_cookbook_and_json.rst
