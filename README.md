> [!IMPORTANT]
> Please note that this guide is for educational purposes only. It is not intended for production use. For production environments, please refer to the official documentation of the respective cloud image provider.

# About

![logo.png](/logo.png)

A collections of documentations, repositories and tools for Cloud Images and Cloud Init

## What is Cloud Images/Init?

**Cloud images** are operating system templates and every instance starts out as an identical clone of every other instance. It is the user data that gives every cloud instance its personality and cloud-init is the tool that applies user data to your instances automatically.

**Cloud-init** is the industry standard multi-distribution method for cross-platform cloud instance initialization. It is supported across all major public cloud providers, provisioning systems for private cloud infrastructure, and bare-metal installations.

https://cloud-init.io/ | https://github.com/canonical/cloud-init

## Cloud Images
These are the publicly available cloud images repositories:

- Ubuntu: [site](https://ubuntu.com/) | [download](https://cloud-images.ubuntu.com/) | [guide](./ubuntu/README.md)
- Red Hat Enterprise Linux: [site](https://www.redhat.com/en/technologies/linux-platforms/enterprise-linux/) | [download](https://developers.redhat.com/products/rhel/download/) | [guide](./rhel/README.md)

## Virtualization Environments
These are the virtualization environments that supports virtual machine deployment using cloud image:
- LXD: [site](https://canonical.com/lxd)
- Proxmox: [site](https://www.proxmox.com/)
- VMware vSphere: [site](https://www.vmware.com/products/cloud-infrastructure/vsphere/)

## Tools
- cloud-init: [site](https://cloud-init.io/) | [docs](https://cloudinit.readthedocs.io/en/latest/)
- Image Builder: [site](https://osbuild.org/)
