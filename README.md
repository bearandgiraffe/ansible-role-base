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
base_profile_d_path:    '{{ user_home_path }}/profile.d'
base_username:          vagrant
base_group_name:        '{{ username }}'
base_user_home_path:    '/home/{{ username }}'
```

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

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
