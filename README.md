<img src="https://upload.wikimedia.org/wikipedia/commons/2/24/Ansible_logo.svg" center="true" width="75" title="Ansible Logo">

A collection of Ansible Playbooks for Debian and Archlinux based systems. Tested platforms are:

- [Manjaro](https://manjaro.org/) `20.2` (Nibia)
- [Ubuntu](https://ubuntu.com/) `20.04` (Focal)

This is licensed under the [MIT license](https://opensource.org/licenses/mit-license.php); see
LICENSE in the source distribution for details.

## Running the playbooks

[Ansible](https://www.ansible.com/) `2.8` or newer is required to run the playbooks.

To run a playbook, invoke:

```console
$ ansible-playbook --ask-become-pass playbook.yml
```

## Documentation

Additional documentation for each playbook is available in the `docs/` folder.
