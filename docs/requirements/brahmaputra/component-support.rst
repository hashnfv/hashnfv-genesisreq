.. Copyright 2015 Open Platform for NFV Project, Inc. and its contributors

.. This work is licensed under the
.. Creative Commons Attribution 4.0 International License.
.. http://creativecommons.org/licenses/by/4.0

Deployment tools support matrix
===============================

This document provides a summary view of the features and capabilities of deployment
tools (a.k.a. "installers") which are expected to be common for all deployment tools.

The tables below only show a short abbreviation of the requirement. For details,
please refer to detailed UX-requirements and system-requirements documents.


Target system requirements
--------------------------

+----------------------------------------------+------------+-----------+------------+------------+
| Feature                                      | Apex       | Compass   | Fuel       | JOID/Juju  |
+==============================================+============+===========+============+============+
| GENESIS-4  - Centos7 or Ubuntu 14.04         | yes        | yes       | yes        | yes        |
+----------------------------------------------+------------+-----------+------------+------------+
| GENESIS-53 - OpenStack Heat                  | yes        | yes       | yes        | yes        |
+----------------------------------------------+------------+-----------+------------+------------+
| GENESIS-6  - OpenDaylight Beryllium          | yes        | yes       | yes        | yes        |
+----------------------------------------------+------------+-----------+------------+------------+
| GENESIS-49 - ONOSFW                          | yes        | yes       | yes        | yes        |
+----------------------------------------------+------------+-----------+------------+------------+
| GENESIS-8  - KVM Hypervisor                  | yes        | yes       | yes        | yes        |
+----------------------------------------------+------------+-----------+------------+------------+


User experience requirements
----------------------------

+----------------------------------------------+------------+-----------+------------+------------+
| Feature                                      | Apex       | Compass   | Fuel       | JOID/Juju  |
+==============================================+============+===========+============+============+
| GENESIS-9  - OpenStack HA                    | yes        | yes       | yes        | yes        |
+----------------------------------------------+------------+-----------+------------+------------+
| GENESIS-71 - Hitless hardware upgrade        | yes        | yes       | yes        | yes        |
+----------------------------------------------+------------+-----------+------------+------------+
| GENESIS-20 - Server discovery integrated     | yes        | yes       | yes        | yes        |
+----------------------------------------------+------------+-----------+------------+------------+
| GENESIS-28 - Common configuration file       | yes        | yes       | yes        | yes        |
+----------------------------------------------+------------+-----------+------------+------------+
| GENESIS-43 - DHCP server HA per tenant       | yes        | yes       | yes        | yes        |
+----------------------------------------------+------------+-----------+------------+------------+
| GENESIS-44 - SDN Controller L3               | yes        | yes       | yes        | no         |
+----------------------------------------------+------------+-----------+------------+------------+
| GENESIS-61 - L1/2 networking config          | yes        | yes       | yes        | yes        |
+----------------------------------------------+------------+-----------+------------+------------+
| GENESIS-62 - Logical networks                | yes        | yes       | yes        | yes        |
+----------------------------------------------+------------+-----------+------------+------------+
| GENESIS-72 - L3-neutron agent                | yes        | yes       | yes        | yes        |
+----------------------------------------------+------------+-----------+------------+------------+
| GENESIS-69 - Isolated CEPH OSD               | yes        | yes       | yes        | yes        |
+----------------------------------------------+------------+-----------+------------+------------+
| GENESIS-12 - Version control for components  | yes        | yes       | yes        | yes        |
+----------------------------------------------+------------+-----------+------------+------------+
| GENESIS-16 - Common inventory config         | yes        | yes       | yes        | yes        |
+----------------------------------------------+------------+-----------+------------+------------+
| GENESIS-17 - User-facing config files        | yes        | yes       | yes        | yes        |
+----------------------------------------------+------------+-----------+------------+------------+
| GENESIS-18 - Server roles                    | yes        | yes       | yes        | yes        |
+----------------------------------------------+------------+-----------+------------+------------+
| GENESIS-19 - Automatic device discovery      | yes        | yes       | yes        | yes        |
+----------------------------------------------+------------+-----------+------------+------------+
| GENESIS-25 - NTP config                      | yes        | yes       | yes        | yes        |
+----------------------------------------------+------------+-----------+------------+------------+
| GENESIS-40 - Hardware replacement support    | yes        | yes       | yes        | yes        |
+----------------------------------------------+------------+-----------+------------+------------+
| GENESIS-74 - "all-in-one" build              | yes        | yes       | yes        | n/a        |
+----------------------------------------------+------------+-----------+------------+------------+
| GENESIS-31 - Agnostic to type of hard drive  | yes        | yes       | yes        | yes        |
+----------------------------------------------+------------+-----------+------------+------------+
| GENESIS-23 - Mandatory Access Control        | yes        | yes       | yes        | yes        |
+----------------------------------------------+------------+-----------+------------+------------+
| GENESIS-24 - Install ssh keys                | yes        | yes       | yes        | yes        |
+----------------------------------------------+------------+-----------+------------+------------+
| GENESIS-39 - Use artifacts from upstream     | yes        | yes       | yes        | yes        |
+----------------------------------------------+------------+-----------+------------+------------+
| GENESIS-38 - Deploy script for jumphost      | yes        | yes       | yes        | yes        |
+----------------------------------------------+------------+-----------+------------+------------+
| GENESIS-42 - Offline deployment              | yes        | yes       | yes        | yes        |
+----------------------------------------------+------------+-----------+------------+------------+
| GENESIS-34 - User guide                      | yes        | yes       | yes        | yes        |
+----------------------------------------------+------------+-----------+------------+------------+
| GENESIS-35 - Release notes                   | yes        | yes       | yes        | yes        |
+----------------------------------------------+------------+-----------+------------+------------+

