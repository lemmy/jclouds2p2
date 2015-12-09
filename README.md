[![Build Status](https://travis-ci.org/lemmy/jclouds2p2.png?branch=master)](https://travis-ci.org/lemmy/jclouds2p2)

jclouds2p2
==========

Aggregates jclouds and its dependencies into a p2 repository

Make sure to start these jclouds bundles explicitly in a launch config to activate OSGi. Otherwise expect NoClassDefFoundExceptions:

* aws-ec2_1.9.1
* com.jcraft.jsch.agentproxy.connector-factory_0.0.7
* ec2_1.9.1
* jclouds-core_1.9.1
* sts_1.9.1


Additionally to Travis CI, a build is at http://tla.msr-inria.inria.fr/jclouds2p2/
