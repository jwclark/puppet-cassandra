Puppet Cassandra module (DataStax edition)
==========================================

[![Build Status](https://secure.travis-ci.org/smarchive/puppet-cassandra.png)](http://travis-ci.org/smarchive/puppet-cassandra)

Overview
--------

Install Apache Cassandra from the [DataStax](http://www.datastax.com/) distribution.

Usage
-----

Example:

    class { 'cassandra':
        initial_token => '42231795865117307932921825928971026432',
        cluster_name  => 'YourCassandraCluster',
        seeds         => [ '192.0.2.5', '192.0.2.23', '192.0.2.42', ],
    }

Supported Platforms
-------------------

The module has been tested on the following operating systems. Testing and patches for other platforms are welcomed.

* Debian Squeeze

License
-------

Copyright (c) 2012-2013 smarchive GmbH

This script is licensed under the Apache License, Version 2.0.

See http://www.apache.org/licenses/LICENSE-2.0.html for the full license text.

Support
-------

Please log tickets and issues at our [project site](https://github.com/smarchive/puppet-cassandra/issues).
