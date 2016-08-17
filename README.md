Join Domain

Prerequisites:

To work with AWS VPC first edit the VPC DHCP option to resole the domain name and the DNS address.
Otherwise the /etc/resolv.conf will be overwritten.

Vars:

Make sure to insert to "domain_sudo_groups" the group name without spaces (e.g Domain Users = Domain^Users).
