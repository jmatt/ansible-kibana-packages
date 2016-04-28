ansible-kibana-packages
=======================

[![Build Status](https://travis-ci.org/jmatt/ansible-kibana-packages.svg?branch=master)](https://travis-ci.org/jmatt/ansible-kibana-packages)

Install Kibana v 5.0 packages for LSST SQuaRE infrastructure.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: jmatt.kibana-packages }

License
-------

The MIT License. See the [LICENSE file](https://github.com/lsst-sqre/ansible-kibana-packages/blob/master/LICENSE).
