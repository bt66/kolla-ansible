==============
Support Matrix
==============

Supported Operating Systems
~~~~~~~~~~~~~~~~~~~~~~~~~~~

Kolla Ansible supports the following host Operating Systems (OS):

.. note::

   CentOS 7 is no longer supported as a host OS. The Train release supports
   both CentOS 7 and 8, and provides a route for migration. See the `Kolla
   Ansible Train documentation
   <https://docs.openstack.org/kolla-ansible/train/user/centos8.html>`_ for
   information on migrating to CentOS 8.

.. note::

   CentOS Linux 8 (as opposed to CentOS Stream 8) is no longer supported as a
   host OS. The Victoria release will in future support both CentOS Linux 8 and
   CentOS Stream 8, and provides a route for migration.

.. note::

   CentOS Linux Stream 8 will no longer be supported as a host OS from the Zed
   release onwards. The Yoga supports both CentOS Stream 8 and Rocky Linux 9,
   and provides a route for migration.

* CentOS Stream 8 (untested since EOL of CentOS Stream 8)
* Debian Bullseye (11)
* openEuler 20.03 LTS SP2
* RHEL 8 (deprecated)
* Rocky Linux 8
* Rocky Linux 9
* Ubuntu Focal (20.04)
* Ubuntu Jammy (22.04)

Supported container images
~~~~~~~~~~~~~~~~~~~~~~~~~~

For best results, the base container image distribution should match the host
OS distribution. The following values are supported for ``kolla_base_distro``:

* ``centos`` (untested since EOL of CentOS Stream 8)
* ``debian``
* ``rhel`` (deprecated)
* ``ubuntu``
* ``rocky``

For details of which images are supported on which distributions, see the
:kolla-doc:`Kolla support matrix <support_matrix>`.
.. FIXME(Alex-Welsh): At the time of writing, the Kolla support matrix is out
.. of date.
