eucalyptus-repos
================

Install / Configure the Eucalyptus repositories

Requirements
------------


Role Variables
--------------


Dependencies
------------


Example Playbook
----------------

```
- hosts:
  - eucalyptus-nc
  - eucalyptus-cc
  - eucalyptus-nc
  - eucalyptus-ccsc
  - eucalyptus-ufs
  - eucalyptus-clc
  roles:
  - eucalyptus-repos

```

License
-------

GPLv3

Author Information
------------------

John Preston [JMille]
