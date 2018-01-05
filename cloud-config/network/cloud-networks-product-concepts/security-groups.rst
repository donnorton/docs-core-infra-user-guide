.. _security-groups:

~~~~~~~~~~~~~~~
Security groups
~~~~~~~~~~~~~~~
.. include:: /_common/note-limitedaccess-securitygroups.txt

A security group is a named container for security group rules.
Security group rules provide Rackspace Public Cloud users the ability
to specify the types of traffic that are allowed to pass
through, to, and from ports
(Public/ServiceNet)
on a cloud server.

Security groups are not yet available through the Cloud Control Panel.
To work with security groups now,
use the
:ref:`neutron CLI <neutron>`
or
:ref:`Cloud Networks API <cloudnetworks-api>`.

Actions related to managing security groups
are listed in
:ref:`cloud-networks-product-actions`.
You can read full details about API operations
related to security groups in the
Cloud Networks API documentation under
:rax-dev-devguide:`Security groups operations <cloud-networks/v2/developer-guide/#document-api-operations/sec-group-operations>`.

To learn more about security groups, read
:how-to:`Security groups FAQ <cloud-networks-faq>` and
:rax-docs:`Use security groups to control traffic <cloud-networks/v2/getting-started/controlling-network-access/security-groups>`.

.. include:: /_common/seealso-concepts-cloud-networks.txt
