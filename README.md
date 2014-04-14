Sonatype Nexus installer
========================

This role installs and upgrades Sonatype Nexus on Ubuntu and Debian

Variables
----------

* **sonatype_nexus_version** Version to install, e.g. 2.8.0. Defaults to 'latest'
* **sonatype_nexus_application_port** Port for the app to listen on. Defaults to '8081'
* **sonatype_nexus_application_host** IP address to listen. Defaults to '0.0.0.0'
* **sonatype_nexus_pid_dir** PIDDIR. Defaults to '/var/run/sonatype-nexus'
* **sonatype_nexus_work_dir** Work directory. Defaults to '/var/lib/sonatype-nexus'

Examples
--------

```yaml
- { role: sonatype-nexus, sonatype_nexus_port: 8080 }
```

License
-------

MIT
