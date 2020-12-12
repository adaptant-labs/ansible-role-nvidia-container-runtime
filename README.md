Ansible Role: NVIDIA Container Runtime
=========

An Ansible Role for installing and configuring the [NVIDIA Container Runtime][nvidia-container-runtime].

[nvidia-container-runtime]: https://github.com/NVIDIA/nvidia-docker

Supported Platforms
-------------------

This role can be used on most Debian and Ubuntu-based systems, please refer to [meta/main.yml][meta] for an updated list.

[meta]: https://github.com/adaptant-labs/ansible-role-nvidia-container-runtime/blob/master/meta/main.yml

Requirements
------------

None.

Role Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
    - hosts: localhost
      roles:
         - adaptant.nvidia-container-runtime
```

License
-------

MIT / BSD

Author Information
------------------

Adaptant Labs ([labs@adaptant.io](mailto:labs@adaptant.io))
