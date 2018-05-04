ansible-role-vmware-workstation
=========

A role for installing VMware Workstation on Linux

Requirements
------------

Requires an internet connection to download the installer.  This can be downloaded separatly if desired.

Role Variables
--------------

* **workstation__license** is the license key to use when installing.

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: vmware.vmware-workstation, workstation_license: XXX-YYY-XXX }


## Contributing

The ansible-role-vmware-workstation project team welcomes contributions from the community. If you wish to contribute code and you have not
signed our contributor license agreement (CLA), our bot will update the issue when you open a Pull Request. For any
questions about the CLA process, please refer to our [FAQ](https://cla.vmware.com/faq). For more detailed information,
refer to [CONTRIBUTING.md](CONTRIBUTING.md).

## License
Copyright © 2018 VMware, Inc. All Rights Reserved.
SPDX-License-Identifier: MIT
