.. Copyright 2015 Open Platform for NFV Project, Inc. and its contributors

.. This work is licensed under the
.. Creative Commons Attribution 4.0 International License.
.. http://creativecommons.org/licenses/by/4.0

.. -----------------------------------------------------------------------

.. Document to list the requirements the target system a
   particular installer creates.
   Please add a bullet each for every requirement added.

==========================
Target system requirements
==========================

Release: OPNFV Brahmaputra

This document lists requirements for the target system that
an installer creates. Different from the requirements document
on user-experience, this document focuses on the key hardware
and software components the different deployment tools install
and/or configure.


Minimum base Operating System distribution supported:
=====================================================

* `GENESIS-4 <https://jira.opnfv.org/browse/GENESIS-4>`_:
  Installers should support either Centos 7 or Ubuntu 14.04
  as target system base OS.

Components/features installed for OpenStack:
============================================

* `GENESIS-53 <https://jira.opnfv.org/browse/GENESIS-53>`_:
  OpenStack Heat should be installed.

Minimum base OpenStack distribution supported:
==============================================

* `GENESIS-7 <https://jira.opnfv.org/browse/GENESIS-7>`_:
  Installers should support OpenStack Liberty release.

SDN Controller:
===============

* `GENESIS-6 <https://jira.opnfv.org/browse/GENESIS-6>`_:
  Installers should support OpenDaylight Beryllium Release.

* `GENESIS-49 <https://jira.opnfv.org/browse/GENESIS-49>`_:
  Installers should support ONOSFW.

VM Controller:
==============

Hypervisor:
===========

* `GENESIS-8 <https://jira.opnfv.org/browse/GENESIS-8>`_:
  Installers should support KVM hypervisor.

Virtual forwarder:
==================
