# Notes

> If you don't know how to do it without Ansible, then Ansible can't help you do it either.

- Ansible is a tool for solving problems that mostly arise on the "Ops" side of the DevOps world.
- Ansible is introduced in 2012 by Michael DeHaan.
    - acquired by Red Hat in 2015
- Since `2.10`, the Ansible core and additional components like modules and plugins have been developed independently.
    - The Ansible core is now called Ansible Core (in version `2.11` and later versions; in version `2.10`, it was briefly called `Ansible-base`).
- *Ansible Community Package* - This is essentially just a meta-distribution that determines the version of the included Ansible Core and the selection and versions of the bundled collections.
- Supported Python versions
    - There are Ansible requirements related to Python version you use, and you also have to distinguish between the control host and the target host.
- Ansible primarily manages its hosts via Secure Shell (SSH) and only requires Python to be installed on the target systems (along with some additional Python modules in special cases).
- Ansible mainly uses YAML as a configuration language.