cloud3rsio.kernel_params
=========

Set kernel parammeters.

Installation
------------

```bash
$ ansible-galaxy install cloud3rsio.kernel_params
```

Requirements
------------

Nothing.

Role Variables
--------------

| Key | Default Value | Type |
| ------------- | ------------- | ------------- |
| `kernel_params` | Reference to [defaults/main.yml](defaults/main.yml) | Array |

Dependencies
------------

Nothing.

Example Playbook
----------------

```yaml
- hosts: all
  roles:
    - role: cloud3rsio.kernel_params
```

License
-------

[MIT](LICENSE)

Author Information
------------------

- youyo
