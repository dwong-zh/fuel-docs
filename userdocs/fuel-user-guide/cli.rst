.. _cli:

Use the Fuel CLI
================

The Fuel CLI is a command-line interface for Fuel that installs automatically
when you install Fuel. Using the Fuel CLI you can:

* Operate your OpenStack environments using Fuel text commands, as well as
  using standard Linux commands.
* Apply advanced configurations through configuration files that you cannot
  modify using the Fuel Web UI.

.. warning::
   We recommend using Fuel CLI only to experienced users as it may break
   your environment if not used carefully.

Modifications that you make using the Fuel CLI take precedence over the
settings applied from the Fuel web UI. If a change has been applied using
the Fuel CLI, Fuel displays the corresponding message in the Fuel web UI.

This section includes the following topics:

.. toctree::
   :maxdepth: 3

   cli/cli_comparison_matrix.rst
   cli/cli_acronyms.rst
   cli/cli_basic_usage.rst
   cli/cli_client_config_file.rst
   cli/cli_management.rst
   cli/cli_environment.rst
   cli/cli_provision.rst
   cli/cli_deploy.rst
   cli/cli_network.rst
   cli/cli_network_group.rst
   cli/cli_network_template.rst
   cli/cli_vip.rst
   cli/cli_nodes.rst
   cli/cli_node_group.rst
   cli/cli_roles.rst
   cli/cli_nodes_empty_role.rst
   cli/cli_plugins.rst
   cli/cli_workflows.rst
   cli/cli_config_openstack.rst
   cli/cli_config_openstack_services_workflow.rst
   cli/cli_change_ip_range.rst
   cli/cli_modify_environment.rst
   cli/cli_noop.rst
   cli/cli_manage_gitrepo.rst
   cli/cli_audit_enforce.rst
