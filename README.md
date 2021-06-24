ansible-role-...
================

[![Build Status]()]()
[![Build Status]()]()

A ansible role to...

Requirements
------------

* Ansible >= 2.10
* Ubuntu 20.04

Role Variables
--------------

Here is a list of all the variables for this role. The variables which are not commented are the defaults that are set in `defaults/main.yml`.

```yaml
# This role takes advantage of...
# @see 
#
# Please see example configuration below:
---
```

Dependencies
------------

None.

Example Playbook
----------------

This is an example playbook of using this role:

```yaml
```

Development & Testing
---------------------

Automated testing is performed by [TravisCI](https://www.travis-ci.com/) using [molecule](http://molecule.readthedocs.io/) framework.

To develop and test locally, you will need the following:

* \*nix Based Machine (Ubuntu, MacOS etc...)
* [Python](https://www.python.org/) (also python-pip)
* [Ansible](https://www.ansible.com/)
* [Molecule](http://molecule.readthedocs.io/)
* [Docker](https://www.docker.com/)

Installing Ansible, Molecule and dependancies:

```bash
pip install -r requirements.txt
```

Building and testing locally:

```bash
molecule converge             # Build hosts using docker
molecule login --host $host   # Logs into host
```

```bash
molecule test                 # Runs all tests, linting etc...
```

License
-------

MIT

Author Information
------------------

This role was created in 2021 by [Aaron Turner](https://github.com/lineguy).

