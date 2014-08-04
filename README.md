OpenStack-Icehouse-Installation
===============================

In this installation guide, we cover the step-by-step process of installing Openstack Icehouse on Ubuntu 14.04.  We consider a multi-node architecture with Openstack Networking (Neutron) that requires three node types: 

+ **Controller Node** that runs management services (keystone, Horizon…) needed for OpenStack to function.

+ **Network Node** that runs networking services and is responsible for virtual network provisioning  and for connecting virtual machines to external networks.

+ **Compute Node** that runs the virtual machine instances in OpenStack. 

We have deployed a single compute node (see the Figure below) but you can simply add more compute nodes to our multi-node installation, if needed.  

The Installation guide is available here [OpenStack-Icehouse-Installation](https://github.com/ChaimaGhribi/OpenStack-Icehouse-Installation/blob/master/OpenStack-Icehouse-Installation.rst).

![Network Configuration Example](https://raw.githubusercontent.com/ChaimaGhribi/OpenStack-Icehouse-Installation/master/images/network-topo.jpg)


If you want to create your first instance with Neutron, follow the instructions in our VM creation guide available
here [Create-First-Instance-with-Neutron](https://github.com/ChaimaGhribi/OpenStack-Icehouse-Installation/blob/master/Create-your-first-instance-with-Neutron.rst).   