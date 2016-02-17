.. Copyright 2015 Open Platform for NFV Project, Inc. and its contributors

.. This work is licensed under the
.. Creative Commons Attribution 4.0 International License.
.. http://creativecommons.org/licenses/by/4.0


UX requirements
===============

Release: OPNFV Brahmaputra

Requirements for a common user-experience created by the deployment tools.

High availability requirements
------------------------------
.. Please add the story reference to each requirement.

* `GENESIS-9 <https://jira.opnfv.org/browse/GENESIS-9>`_:
  Installers shall support the deployment of OpenStack with
  High-Availability (for those components that support it in
  Liberty) on 3 or more control nodes. Functest tests should
  be able to verify that the HA is enabled and functional.

* `GENESIS-71 <https://jira.opnfv.org/browse/GENESIS-71>`_:
  Hitless hardware upgrade: Increase size of a deployment in terms of compute
  nodes (add additional compute nodes) without service interruption.
  This requirement doesn't mandate upgrade/increasing the size of the control
  node cluster.


Network setup and configuration related requirements
----------------------------------------------------
* `GENESIS-20 <https://jira.opnfv.org/browse/GENESIS-20>`_:
  Automatically populate discovered servers into install
  tool (reduce user-intervention to a minimum).

* `GENESIS-28 <https://jira.opnfv.org/browse/GENESIS-28>`_:
  Installers should support a common configuration file (e.g. kickstart file)
  per platform/role, so that the installed OS can be customized
  for hardware and role.

* `GENESIS-43 <https://jira.opnfv.org/browse/GENESIS-43>`_:
  Neutron DHCP servers should be configured in HA per tenant.

* `GENESIS-44 <https://jira.opnfv.org/browse/GENESIS-44>`_:
  SDN Controller layer 3 forwarding support.

* `GENESIS-61 <https://jira.opnfv.org/browse/GENESIS-61>`_:
  Support layer 1/2 networking configuration.

* `GENESIS-62 <https://jira.opnfv.org/browse/GENESIS-62>`_:
  Support logical networks for target system.

* `GENESIS-72 <https://jira.opnfv.org/browse/GENESIS-72>`_:
  Support L3-neutron agent as an option for L3.

* `GENESIS-69 <https://jira.opnfv.org/browse/GENESIS-69>`_:
  Provide isolated compute node resources for CEPH OSD.

Versioning requirements
-----------------------
.. Please add the story reference to each requirement.

* `GENESIS-12 <https://jira.opnfv.org/browse/GENESIS-12>`_:
  Installers should track/control all versions of all components pulled
  from external sources (user should be able to identify
  the versions and origins of all software components deployed).

System definition and system configuration requirements
-------------------------------------------------------
.. Please add the story reference to each requirement.

* `GENESIS-16 <https://jira.opnfv.org/browse/GENESIS-16>`_:
  Common ability to input site, topology, and server information.
* `GENESIS-17 <https://jira.opnfv.org/browse/GENESIS-17>`_:
  User-configurable parameters available via config files.
* `GENESIS-18 <https://jira.opnfv.org/browse/GENESIS-18>`_:
  Allow assignment of different roles to servers, so that hardware and
  software can be configured according to the role.
* `GENESIS-19 <https://jira.opnfv.org/browse/GENESIS-19>`_:
  Deployment tool to provide for automatic device discovery.
* `GENESIS-25 <https://jira.opnfv.org/browse/GENESIS-25>`_:
  Installers should configure NTP servers on the servers for clock
  synchronization.
* `GENESIS-40 <https://jira.opnfv.org/browse/GENESIS-40>`_:
  Hardware replacement.

Requirements pertaining to the qualities of the deployment process
------------------------------------------------------------------

* `GENESIS-74 <https://jira.opnfv.org/browse/GENESIS-74>`_:
  Installers which create a build for Brahmaputra, should create
  the build as an "all-in-one" build. The the build process of
  the installer creates a single entity (e.g. ISO) - which has
  all the artifacts considered and required by all the projects
  for Brahmaputra packaged in. Or in other terms and as an example:
  If there are 4 different versions of OVS - all these 4 versions
  would be contained in the "all in one build".
  Note: This requirement only applies to installers which support
  a "build" phase (i.e. create a bootable image, like an iso-image
  from the different artifacts required).
* `GENESIS-31 <https://jira.opnfv.org/browse/GENESIS-31>`_:
  Installers to be agnostic to type of hard drives used.

Security related requirements
-----------------------------

* `GENESIS-23 <https://jira.opnfv.org/browse/GENESIS-23>`_:
  Installers should enable Mandatory Access Control by default.
  Installers should enable MAC either using SElinux or AppArmour.
* `GENESIS-24 <https://jira.opnfv.org/browse/GENESIS-24>`_:
  Installers should install ssh keys on servers so that key-based login
  can be used for administration.

Testing related requirements
----------------------------
.. Please add the story reference to each requirement.

Installation method related requirements
----------------------------------------

* `GENESIS-39 <https://jira.opnfv.org/browse/GENESIS-39>`_:
  Ability to install with upstream artifacts.

* `GENESIS-38 <https://jira.opnfv.org/browse/GENESIS-38>`_:
  Installers should supply a script or set of scripts ("deploy.sh") to
  automatically install the jumphost (from there, the
  entire OPNFV system is automatically installed).

* `GENESIS-42 <https://jira.opnfv.org/browse/GENESIS-42>`_:
  Installers should support offline deployment. Jump host may have
  Internet access, but the installers should support offline
  installation on target hosts during the deployment phase (either
  manually or automatically).

Documentation related requirements
----------------------------------

* `GENESIS-34 <https://jira.opnfv.org/browse/GENESIS-34>`_:
  Installers should provide a user guide.

* `GENESIS-35 <https://jira.opnfv.org/browse/GENESIS-35>`_:
  Installers should provide release notes for an OPNFV release as part of
  the documentation provided.


