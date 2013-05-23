# OpenShift Cassandra Cartridge

The `cassandra` cartridge provides [Cassandra](http://cassandra.apache.org/) on OpenShift.

## Environment Variables

The `cassandra` cartridge provides several environment variables to reference for ease
of use:

    OPENSHIFT_CASSANDRA_HOST      The Cassandra IP address
    OPENSHIFT_CASSANDRA_PORT      The Cassandra port
    OPENSHIFT_CASSANDRA_LOG_DIR     The path to the Cassandra log directory

For more information about environment variables, consult the
[OpenShift Application Author Guide](https://github.com/openshift/origin-server/blob/master/node/README.writing_applications.md).
