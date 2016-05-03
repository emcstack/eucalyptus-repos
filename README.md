eucalyptus-repos
================

Install / Configure the Eucalyptus repositories

Requirements
------------


Role Variables
--------------

| Name | Type | Required | Default | Description
|--- |--- |--- |--- |---
| use_baseurl | boolean | false | true | Defines if the repo uses mirror list or baseurl to download packages
| cs_qa | boolean | false | false | For CS-QA helps with installing specific versions of Eucalyptus
| eucalyptus_latest | string | true | 4.2 | Version to be installed if cs_qa is true
| euca2ools_latest | string | true | 3.3 | Version of Euca2ools to be installed if cs_qa is true
| eucalyptus_repo_url | string | false | N/A | URL for the repo when use_baseurl is true
| euca2ools_repo_url | string | false | N/A | URL for the repo when use_baseurl is true


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
