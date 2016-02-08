# Awesome-Ansible-Roles

A collaborative curated list of awesome Ansible roles.
Ansible is a really great tool but unfortunately its not very easy to find top quality roles. Platforms like [Ansible galaxy](https://galaxy.ansible.com/) are really limited compared with [Puppet Forge](forge.puppetlabs.com) for example.

The idea of this repo is to improve that, and make a list of top quality Ansible roles, curated by the community.

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

---

## Ansible roles

### Languages

* [geerlingguy.php](https://github.com/geerlingguy/ansible-role-php) - Installs PHP on RedHat/CentOS and Debian/Ubuntu servers.
* [geerlingguy.composer](https://github.com/geerlingguy/ansible-role-composer) - Installs Composer, the PHP Dependency Manager, on any Linux or UNIX system.
* [geerlingguy.nodejs](https://github.com/geerlingguy/ansible-role-nodejs) - Installs Node.js on RHEL/CentOS or Debian/Ubuntu.
* [pablocrivella.nvm](https://github.com/pablocrivella/ansible-role-nvm) - Role to install nvm and multiple nodejs versions.
* [geerlingguy.ruby](https://github.com/geerlingguy/ansible-role-ruby) - Installs Ruby and bundler gem on Linux.
* [rvm_io.rvm1-ruby](https://github.com/rvm/rvm1-ansible) - Ansible role to install and manage ruby versions using rvm.
* [williamyeh.oracle-java](https://github.com/William-Yeh/ansible-oracle-java) - Install oracle java.
* [geerlingguy.java](https://github.com/geerlingguy/ansible-role-java) - Installs Java for RedHat/CentOS and Debian/Ubuntu linux servers.
* [azavea.golang](https://github.com/azavea/ansible-golang) - An Ansible role for installing the Go programming language.

---

### Webservers

* [geerlingguy.nginx](https://github.com/geerlingguy/ansible-role-nginx) - Installs Nginx on RedHat/CentOS or Debian/Ubuntu linux servers.
* [geerlingguy.apache](https://github.com/geerlingguy/ansible-role-apache) - An Ansible Role that installs Apache 2.x on RHEL/CentOS, Debian/Ubuntu, SLES and Solaris.

---

## Reverse Proxy

* [geerlingguy.haproxy](https://github.com/geerlingguy/ansible-role-haproxy) - Installs HAProxy on RedHat/CentOS and Debian/Ubuntu Linux servers.
* [geerlingguy.varnish](https://github.com/geerlingguy/ansible-role-varnish) - An Ansible Role that installs Varnish on RedHat/CentOS or Debian/Ubuntu Linux.

---

### Databases

* [geerlingguy.mysql](https://github.com/geerlingguy/ansible-role-mysql) - Installs and configures MySQL or MariaDB server on RHEL/CentOS or Debian/Ubuntu servers.
* [ANXS.postgresql](https://github.com/ANXS/postgresql) - Ansible role which installs and configures PostgreSQL, extensions, databases and users.
* [greendayonfire.mongodb](https://github.com/UnderGreen/ansible-role-mongodb) - Ansible role to configure MongoDB
* [christophermancini.riak-kv](https://github.com/basho-labs/ansible-riak) - Ansible Riak is an Ansible role designed to install & configure Riak KV. In combination with Ansible hosts, it can be used to configure a single node or an entire cluster.
* [influxdb](https://github.com/mtchavez/ansible-influxdb) - InfluxDB Ansible Galaxy role. Sets up a working InfluxDB server.

---

### Caching

* [geerlingguy/ansible-role-memcached](https://github.com/geerlingguy/ansible-role-memcached) - Ansible Role - Memcached for Linux.
* [DavidWittman.redis](https://github.com/DavidWittman/ansible-redis) - Ansible role to manage Redis

---

## Search Engines

* [aloysius.elasticsearch](https://github.com/aloysius-lim/ansible-elasticsearch) - Ansible role to install Elasticsearch on Debian (Ubuntu) and Enterprise Linux (RedHat, CentOS) systems, with full configuration capabilities. This role uses the official packages from Elastic. It may also work on Fedora and Amazon Linux, but these have not been tested.
* [geerlingguy.solr](https://github.com/geerlingguy/ansible-role-solr) - An Ansible Role that installs Apache Solr on Linux servers.

## Message Queues

* [mrlesmithjr.rabbitmq](https://github.com/mrlesmithjr/ansible-rabbitmq) - Installs rabbitmq (Configurable...HA and Clustering ready)

---

## System

* [ntp](https://github.com/resmo/ansible-role-ntp) - Configures ntp
* [azmelanar.timezone](https://github.com/azmelanar/ansible-timezone) - Role for installation packages of timezone and configuration system timezone.

---

## Security

* [geerlingguy.firewall](https://github.com/geerlingguy/ansible-role-firewall) - Installs a simple iptables-based firewall for RHEL/CentOS or Debian/Ubunty systems.
* [geerlingguy.security](https://github.com/geerlingguy/ansible-role-security) - This role performs some basic security configuration on RedHat and Debian-based linux systems.
* [franklinkim.ssh](https://github.com/weareinteractive/ansible-ssh) - Ansible role which configures ssh.

---

### Logging and Monitoring

* [franklinkim.newrelic](https://github.com/weareinteractive/ansible-newrelic) - Ansible role which installs and configures New Relic Server Monitoring Daemon
* [Datadog.datadog](https://github.com/DataDog/ansible-datadog) - Install and configure Datadog base agent & checks.
* [geerlingguy.logstash-forwarder](https://github.com/geerlingguy/ansible-role-logstash-forwarder) - An Ansible Role that installs Logstash Forwarder on RedHat/CentOS or Debian/Ubuntu. This role is well-tested on Debian/Ubuntu, but is still undergoing development for RedHat/CentOS.
* [geerlingguy.logstash](https://github.com/geerlingguy/ansible-role-logstash) - An Ansible Role that installs Logstash on RedHat/CentOS Debian/Ubuntu.
* [ricbra.logentries](https://github.com/ricbra/ansible-logentries) - Ansible role for installing logentries agent and daemon
* [monit](https://github.com/pgolm/ansible-playbook-monit) - Ansible role for configuring Monit.
* [valentinogagliardi.collectd](https://github.com/valentinogagliardi/collectd) - Ansible role to install and configure CollectD
* [nsg.graphite](https://github.com/nsg/ansible-graphite) - Install graphite.
* [dmichel1.statsd ](https://github.com/dmichel1/ansible-statsd) - se Ansible to install and configure statsd
* [logrotate](https://github.com/retr0h/ansible-logrotate) - A role which manages the logrotate package, and provides a means to manage specific log rotate configurations.

---

## Version Control

* [geerlingguy.git](https://github.com/geerlingguy/ansible-role-git) - Installs Git, a distributed version control system, on any RHEL/CentOS or Debian/Ubuntu Linux system.

---

### Other

* [geerlingguy.jenkins](https://github.com/geerlingguy/ansible-role-jenkins) - Installs Jenkins CI on RHEL/CentOS and Debian/Ubuntu servers.
* [geerlingguy.postfix](https://github.com/geerlingguy/ansible-role-postfix) - Installs postfix on RedHat/CentOS or Debian/Ubuntu.
