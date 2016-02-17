.. Copyright 2015 Open Platform for NFV Project, Inc. and its contributors

.. This work is licensed under the
.. Creative Commons Attribution 4.0 International License.
.. http://creativecommons.org/licenses/by/4.0

.. -----------------------------------------------------------------------


=================================
Key artifacts and their locations
=================================

Release: OPNFV Brahmaputra


VM manager components
=====================

* OpenStack::
  location: `<http://docs.openstack.org/releases/releases/liberty.html>`_
  joid_location: cloud-archive:liberty
  release: Liberty

Network controller components
=============================

* OpenDaylight Controller::
  location: `https://nexus.opendaylight.org/content/repositories/staging/org/opendaylight/integration/distribution-karaf/0.4.0-Beryllium-RC2/distribution-karaf-0.4.0-Beryllium-RC2.tar.gz'
  release: Beryllium RC2

* OpenDaylight SFC::
  location: `<https://www.dropbox.com/s/6w76eo7loltvvb5/openstack.net-virt-sfc-karaf-1.2.1-SNAPSHOT.zip>`_

* ONOS Controller::
  location: `<http://downloads.onosproject.org/nightly/onos-1.4.0-rc2.tar.gz>`_
  release: Emu 1.4.0-rc2

vSwitch components
==================

 * OVS NSH build::
  location: `<https://github.com/openvswitch/ovs.git>`_
  commit: 121daded51b9798fe3722824b27a05c16806cbd1

 * OVS build::
  joid_location: `cloud-archive:liberty`
  release: 1.4.0

JOID components
===============

 * MAAS::
  location: ppa:maas/stable
  release: 1.9.0

 * JUJU::
  location: ppa:juju/stable
  release: 1.25.3

 * CHARM::
  location: https://code.launchpad.net/~openstack-charmers
      charm: "cs:trusty/juju-gui"
      charm: "cs:trusty/ubuntu"
      charm: "cs:trusty/mongodb"
      branch: "lp:~openstack-charmers/charms/trusty/percona-cluster/next"
      branch: "lp:~openstack-charmers/charms/trusty/hacluster/next"
      branch: "lp:~openstack-charmers/charms/trusty/ceilometer/next"
      branch: "lp:~openstack-charmers/charms/trusty/ceilometer-agent/next"
      branch: "lp:~openstack-charmers/charms/trusty/heat/next"
      branch: lp:~openstack-charmers/charms/trusty/ceph/next
      branch: lp:~openstack-charmers/charms/trusty/ceph-osd/next
      branch: lp:~openstack-charmers/charms/trusty/ceph-radosgw/next
      branch: lp:~openstack-charmers/charms/trusty/cinder/next
      branch: lp:~openstack-charmers/charms/trusty/cinder-ceph/next
      branch: lp:~openstack-charmers/charms/trusty/rabbitmq-server/next
      branch: lp:~openstack-charmers/charms/trusty/keystone/next
      branch: lp:~openstack-charmers/charms/trusty/openstack-dashboard/next
      branch: lp:~openstack-charmers/charms/trusty/nova-compute/next
      branch: lp:~openstack-charmers/charms/trusty/nova-cloud-controller/next
      branch: lp:~openstack-charmers/charms/trusty/neutron-api/next
      branch: lp:~openstack-charmers/charms/trusty/neutron-gateway/next
      branch: lp:~openstack-charmers/charms/trusty/odl-controller/next
      branch: lp:~openstack-charmers/charms/trusty/glance/next
      branch: lp:~narindergupta/charms/trusty/promise/trunk
      branch: lp:~openstack-charmers/charms/trusty/neutron-api-odl/next
      branch: lp:~openstack-charmers/charms/trusty/openvswitch-odl/trunk
      branch: lp:~charmers/charms/precise/zookeeper/trunk
      branch: lp:~stub/charms/trusty/cassandra/noauthentication
      branch: lp:~sdn-charmers/charms/trusty/contrail-configuration/trunk
      branch: lp:~sdn-charmers/charms/trusty/contrail-control/trunk
      branch: lp:~sdn-charmers/charms/trusty/contrail-analytics/trunk
      branch: lp:~sdn-charmers/charms/trusty/contrail-webui/trunk
      branch: lp:~opnfv-team/charms/trusty/neutron-api-contrail/trunk
      branch: lp:~opnfv-team/charms/trusty/neutron-contrail/trunk
      branch: lp:~sdn-charmers/charms/trusty/keepalived/trunk
      branch: "lp:~wuwenbin2/onosfw/onos-controller"
      branch: "lp:~wuwenbin2/onosfw/neutron-api-onos"
      branch: "lp:~wuwenbin2/onosfw/openvswitch-onos"

