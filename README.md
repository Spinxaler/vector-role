Role Name
=========

Install Vector.

Requirements
------------


Role Variables
--------------

- defaults
```
vector_version: "0.22.2"
vector_dir: "/opt/vector"
```
- vars
```
vector_packages:
  - vector-server
```
Dependencies
------------


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
# vector-role
