connman
=========

Installs and configures connman on a Debian 10 system.

Requirements
------------

None.

Role Variables
--------------

| Variable Name | Default Value | Description |
--------------- |---------------|--------------
`connman_enable_online_check` | "false" | whether to enable the online-check (connect to a specific ip), string variabled required
`connman_use_wpa_supplicant` | true | whether to install wpa\_supplicant
`connman_networks` | [] | optional, networks to configure

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in
regards to parameters that may need to be set for other roles, or variables that
are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables
passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: connman, x: 42 }

License
-------

BSD

Author Information
------------------

Find me on [GitHub](https://github.com/ThreeFx).
