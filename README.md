ansible-kibana-packages
=======================

[![Build Status](https://travis-ci.org/lsst-sqre/ansible-kibana-packages.svg?branch=master)](https://travis-ci.org/lsst-sqre/ansible-kibana-packages)

Install kibana v 5.0 packages for LSST SQuaRE infrastructure.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: lsst-sqre.kibana-packages }

License
-------

The MIT License. See the [LICENSE file](https://github.com/lsst-sqre/ansible-kibana-packages/blob/master/LICENSE).
