=====================================================
knife raw
=====================================================

.. include:: ../../includes_knife/includes_knife_raw.rst

Syntax
=====================================================
.. include:: ../../includes_knife/includes_knife_raw_syntax.rst

Options
=====================================================
.. note:: Review the list of :doc:`common options </knife_common_options>` available to this (and all) |knife| subcommands and plugins.

.. include:: ../../includes_knife/includes_knife_raw_options.rst

knife.rb Settings
-----------------------------------------------------
.. note:: See :doc:`knife.rb </config_rb_knife>` for more information about how to add optional settings to the |knife rb| file.

.. include:: ../../includes_knife/includes_knife_client_create_settings.rst

Examples
=====================================================
To view information about a node:

.. code-block:: bash

   knife raw /nodes/<node_name>

To view information about a client:

.. code-block:: bash

   knife raw /clients/<client_name>



