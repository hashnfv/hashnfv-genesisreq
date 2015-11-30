.. Copyright 2015 Open Platform for NFV Project, Inc. and its contributors

.. Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

.. http://www.apache.org/licenses/LICENSE-2.0

.. Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.

.. -----------------------------------------------------------------------

.. Document to list the requirements for a common user experience
   created by the different installers.
   Please add a bullet each for every requirement added.

===============
UX requirements
===============

Release: OPNFV Brahmaputra

Requirements for a common user-experience created by the deployment tools.



High availability requirements
------------------------------
.. Please add the Jira story reference to each requirement.
   Note that the below listed "GENESIS-3" Jira story are place holders
   and are to be changed for the actual Jira reference.

* `Jira GENESIS-3 <https://jira.opnfv.org/browse/GENESIS-3>`_: new requirement...
* `Jira GENESIS-9 <https://jira.opnfv.org/browse/GENESIS-9>`_: The installer shall support the
  deployment of OpenStack with High-Availability (for those components that support it in
  Liberty) on 3 or more control nodes. Functest tests should be able to verify that the HA is
  enabled and functional.

* `Jira GENESIS-71 <https://jira.opnfv.org/browse/GENESIS-71>`_: new requirement
  Hitless hardware upgrade: Increase size of a deployment in terms of compute
  nodes (add additional compute nodes) without service interruption.
  This requirement doesn't mandate upgrade/increasing the size of the control
  node cluster.


Network setup and configuration related requirements
----------------------------------------------------
* `Jira GENESIS-20 <https://jira.opnfv.org/browse/GENESIS-20>`_: Automatically populate
  discovered servers into install tool (reduce user-intervention to a minimum).

* `Jira GENESIS-28 <https://jira.opnfv.org/browse/GENESIS-28>`_: Installers should support
  a common configuration file (e.g. kickstart file) per platform/role, so that the installed
  OS can be customized for hardware and role.

* `Jira GENESIS-43 <https://jira.opnfv.org/browse/GENESIS-43>`_: Neutron DHCP servers should
  be configured in HA per tenant

* `Jira GENESIS-62 <https://jira.opnfv.org/browse/GENESIS-62>`_: Supported Logical Networks for
  Target System

* `Jira GENESIS-72 <https://jira.opnfv.org/browse/GENESIS-72`_: Support L3-neutron agent
  as an option for L3

Versioning requirements
-----------------------
.. Please add the Jira story reference to each requirement.
   Note that the below listed "GENESIS-3" Jira stories are place holders
   and are to be changed for the actual Jira reference.

* `Jira GENESIS-3 <https://jira.opnfv.org/browse/GENESIS-3>`_: new requirement...
* `Jira GENESIS-12 <https://jira.opnfv.org/browse/GENESIS-12>`_: Installers should track/control
  all versions of all components pulled from external sources (user should be able to identify
  the versions and origins of all software components deployed).

System definition and system configuration requirements
-------------------------------------------------------
.. Please add the Jira story reference to each requirement.
   Note that the below listed "GENESIS-3" Jira stories are place holders
   and are to be changed for the actual Jira reference.

* `Jira GENESIS-3 <https://jira.opnfv.org/browse/GENESIS-3>`_: new requirement...
* `Jira GENESIS-16 <https://jira.opnfv.org/browse/GENESIS-16>`_: Common ability to input site,
  topology, and server information.
* `Jira GENESIS-18 <https://jira.opnfv.org/browse/GENESIS-18>`_: Allow assignment of different roles
  to servers, so that hardware and software can be configured according to the role.
* `Jira GENESIS-19 <https://jira.opnfv.org/browse/GENESIS-19>`_: 
  Deployment tool to provide for automatic device discovery.
* `Jira GENESIS-25 <https://jira.opnfv.org/browse/GENESIS-25`_:
  Installers should configure NTP servers on the servers for clock
  synchronization.

Requirements pertaining to the qualities of the deployment process
------------------------------------------------------------------
.. Please add the Jira story reference to each requirement.
   Note that the below listed "GENESIS-3" Jira stories are place holders
   and are to be changed for the actual Jira reference.

* `Jira GENESIS-3 <https://jira.opnfv.org/browse/GENESIS-3>`_: new requirement...

Security related requirements
-----------------------------
.. Please add the Jira story reference to each requirement.
   Note that the below listed "GENESIS-3" Jira stories are place holders
   and are to be changed for the actual Jira reference.

* `Jira GENESIS-3 <https://jira.opnfv.org/browse/GENESIS-3>`_: new requirement...
* `Jira GENESIS-23 <https://jira.opnfv.org/browse/GENESIS-23>`_: Enable Mandatory Access Control by default. Installer should enable MAC either using SElinux or AppArmour.
* `Jira GENESIS-24 <https://jira.opnfv.org/browse/GENESIS-24>`_: Installers should install ssh keys on servers so that key-based login can be used for administration

Testing related requirements
----------------------------
.. Please add the Jira story reference to each requirement.
   Note that the below listed "GENESIS-3" Jira stories are place holders
   and are to be changed for the actual Jira reference.

* `Jira GENESIS-3 <https://jira.opnfv.org/browse/GENESIS-3>`_: new requirement...

Installation method related requirements
----------------------------------------
.. Please add the Jira story reference to each requirement.
   Note that the below listed "GENESIS-3" Jira stories are place holders
   and are to be changed for the actual Jira reference.

* `Jira GENESIS-3 <https://jira.opnfv.org/browse/GENESIS-3>`_: new requirement...

* `Jira GENESIS-38 <https://jira.opnfv.org/browse/GENESIS-38>`_: Installers should supply a script or set of scripts ("deploy.sh") to automatically install the jumphost (from there, the entire OPNFV system is automatically installed).

Documentation related requirements
----------------------------------
.. Please add the Jira story reference to each requirement.
   Note that the below listed "GENESIS-3" Jira stories are place holders
   and are to be changed for the actual Jira reference.

* `Jira GENESIS-3 <https://jira.opnfv.org/browse/GENESIS-3>`_: new requirement...

