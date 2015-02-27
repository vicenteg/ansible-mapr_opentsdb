mapr-opentsdb
=========

Install opentsdb with MapR DB as backend.

Requirements
------------

You need a MapR cluster. This will work with either the free community edition or the enterprise database edition.

Role Variables
--------------

Set the hbase version and hadoop version using hbase_version and hadoop_version.

Dependencies
------------



Example Playbook
----------------

	- hosts: hbasemaster
	  roles:
	    - { role: mapr-opentsdb, hbase_version: 0.98.7, hadoop_version: 0.20.2 }

License
-------

MIT

Author Information
------------------

Vince Gonzalez
