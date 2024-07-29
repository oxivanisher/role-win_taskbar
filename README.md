win_taskbar
===========

Remove unwanted things from the Windows taskbar.

Requirements
------------

This role is built to be used with Ansible oder SSH on Windows.

Role Variables
--------------

| Name               | Comment                        | Default value                    |
|--------------------|--------------------------------|----------------------------------|
| win_taskbar_users  | List of users to be configured | `[Default, "{{ ansible_user }}"]`|

Example Playbook
----------------
```yaml
- name: Configure the Windows taskbar
  hosts: windows
  roles:
    - role: oxivanisher.windows_desktop.win_taskbar
```
License
-------

BSD

Author Information
------------------

This role is part of the [oxivanisher.windows_desktop](https://galaxy.ansible.com/ui/repo/published/oxivanisher/windows_desktop/) collection, and the source for that is located on [github](https://github.com/oxivanisher/collection-windows_desktop).
