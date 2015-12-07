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

.. Document to list the requirements the target system a
   particular installer creates.
   Please add a bullet each for every requirement added.

==========================
Target system requirements
==========================

Release: OPNFV Brahmaputra

This document lists requirements for the target system that an installer creates. Different from the requirements document on user-experience, this document focuses on the key hardware and software components the different deployment tools install and/or configure.

Hardware components
-------------------
.. Please add the Jira story reference to each requirement.
   Note that the below listed "GENESIS-1" Jira story are place holders
   and are to be changed for the actual Jira reference.


Software components
-------------------
.. Please add the Jira story to each requirement as reference.

Minimum base Operating System distribution supported:
=====================================================
`GENESIS-4 <https://jira.opnfv.org/browse/GENESIS-4>`_: Installers support either Centos 7 or
Ubuntu 14.04 as target system base OS

Minimum base OpenStack distribution supported:
==============================================
`GENESIS-7 <https://jira.opnfv.org/browse/GENESIS-7>`_: Installers must support OpenStack Liberty
release

SDN Controller:
===============

`GENESIS-6 <https://jira.opnfv.org/browse/GENESIS-6>`_: Installers support
OpenDaylight Lithium Release

`GENESIS-49 <https://jira.opnfv.org/browse/GENESIS-49>`_: Installers support for ONOSFW


VM Controller:
==============

Hypervisor:
===========
`GENESIS-8 <https://jira.opnfv.org/browse/GENESIS-8>`_: KVM Support

`GENESIS-50 <https://jira.opnfv.org/browse/GENESIS-50>`_: nfv-kvm installation requirement
Virtual forwarder:
==================

`GENESIS-46 <https://jira.opnfv.org/browse/GENESIS-46>`_: SFC support
 The SFC project needs a version of OVS that supports Network Service Headers '
 (NSH). The required end-system state for the B-release will be an official
 OVS patch that Intel is preparing that will provide full OVS 2.4 support.
 This official OVS patch is not available yet. Until this official patch is
 available, there is a patch available in a private branch that we will have
 to use during the life cycle of the B release. This private OVS branch does
 not support all of the OVS 2.4 features. The private OVS branch can be
 obtained as follows:
 git clone https://github.com/priteshk/ovs.git
 git checkout nsh-v8


Installer Documentation:
========================

`GENESIS-34 <https://jira.opnfv.org/browse/GENESIS-34`_: Installers should provide a user guide

`GENESIS-35 <https://jira.opnfv.org/browse/GENESIS-35`_: Installers should provide release notes for an OPNFV release as part of the documentation provided


