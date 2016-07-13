Role Name
=========

Installs all the basics that are usually required by any environment.

Requirements
------------

None.

Role Variables
--------------

Available variables are listed below, along with default values:

```yml
base_username:          vagrant
base_group_name:        '{{ base_username }}'
base_user_home_path:    '/home/{{ base_username }}'
base_profile_d_path:    '{{ base_user_home_path }}/profile.d'
```

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

```
- hosts: servers
  roles:
     - { role: bearandgiraffe.base, base_username: 'foo' }
```

License
-------

The Unlicense (see LICENSE)

Author Information
------------------

Youssef Chaker (@ychaker) from Bear & Giraffe LLC (@bearandgiraffe).
