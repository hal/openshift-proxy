
## Proxy for the HAL Console

This is the openshift wrapper for the HAL proxy [1], that serves the web console builds (tagged versions).

The builds will be published to the JBoss maven repository [2], from which they are typically pulled and bundled with Wildfly itself. 

The proxy serves the builds artefacts contents that reside with the maven repo through an embedded HTTP server.

Licensed under ASL V2, http://www.apache.org/licenses/LICENSE-2.0

[1] http://github.com/hal/mvn-cdn
[2] http://repository.jboss.org