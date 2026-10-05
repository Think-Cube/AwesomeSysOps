# Awesome SysOps

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A curated list of open source sysadmin resources. From backups and build automation to security and virtualization — a comprehensive collection of tools and solutions for system administration tasks.

---

## 💾 Backups

### Backup Tools

* [Amanda](http://www.amanda.org/) – client-server model backup tool.
* [Bacula](https://www.bacula.org) – another client-server model backup tool.
* [Bareos](https://www.bareos.org) – fork of Bacula backup tool.
* [Barman](https://www.pgbarman.org) – backup and recovery manager for disaster recovery of PostgreSQL servers.
* [Backuppc](https://backuppc.github.io/backuppc/) – client-server model backup tool with file pooling scheme.
* [Borg](https://www.borgbackup.org/) – deduplicating archiver with compression and authenticated encryption.
* [Borgmatic](https://torsion.org/borgmatic/) – simple, configuration-driven backup software for servers and workstations.
* [Bup](https://github.com/bup/bup) – incremental backups with rolling checksums, git packfiles, and de-duplication.
* [Burp](http://burp.grke.org/) – network backup and restore program.
* [Duplicati](https://www.duplicati.com) – multiple backends, encryption, web-ui and multi-OS backup tool.
* [Duplicity](http://duplicity.nongnu.org/) – encrypted bandwidth-efficient backup using the rsync algorithm.
* [FreeFileSync](https://www.freefilesync.org) – folder comparison and synchronization tool.
* [Lsyncd](https://github.com/axkibe/lsyncd) – file monitor which spawns a process to synchronize changes (rsync by default).
* [restic](https://restic.net/) – fast, secure, efficient backup program.
* [Rsnapshot](http://www.rsnapshot.org/) – filesystem snapshotting utility.
* [Snebu](http://www.snebu.com/) – snapshot backup with global multi-client deduplication and transparent compression.
* [UrBackup](https://www.urbackup.org/) – another client-server backup system.
* [Velero](https://velero.io/) – backup and migrate Kubernetes resources and persistent volumes.
* [ZBackup](http://zbackup.org/) – versatile deduplicating backup tool.

### Backup Libraries

* [Backup](https://github.com/backup/backup) – elegant DSL in Ruby for performing backups on UNIX-like systems.
* [DREBS](https://github.com/dojo4/drebs) – AWS EBS backup script that supports strategies.

---

## 🔨 Build Automation

* [Apache Ant](https://ant.apache.org/) – automation build tool, similar to make, written in Java.
* [Apache Maven](https://maven.apache.org/) – build automation tool mainly for Java.
* [GNU Make](https://www.gnu.org/software/make/) – the most popular automation build tool for many purposes.
* [Gradle](https://gradle.org/) – open source build automation system.

---

## 🤖 ChatOps

* [Err](https://errbot.net/) – plugin based chatbot designed to be easily deployable, extensible and maintainable.
* [Hubot](https://hubot.github.com/) – customizable life embetterment robot.
* [KeyBase](https://www.keybase.io/) – encrypted chat, cloud and git.
* [Lita](https://www.lita.io/) – robot companion for your company's chat room.

---

## 🖨️ Cloning

* [Clonezilla](https://clonezilla.org/) – partition and disk imaging/cloning program.
* [Fog](https://fogproject.org/) – another computer cloning solution.

---

## ☁️ Cloud Computing

* [CloudStack](https://cloudstack.apache.org/) – cloud computing software for creating, managing, and deploying infrastructure cloud services.
* [Cobbler](https://cobbler.github.io) – Linux installation server that allows for rapid setup of network installation environments.
* [Mesos](https://mesos.apache.org/) – develop and run resource-efficient distributed systems.
* [OpenNebula](https://opennebula.io/) – user-driven cloud management platform for sysadmins and devops.
* [OpenShift OKD](https://www.okd.io/) – open source upstream of OpenShift, the next generation application hosting platform.
* [OpenStack](https://www.openstack.org/) – open source software for building private and public clouds.
* [Terraform](https://www.terraform.io) – infrastructure as code tool, commonly used for AWS/GCE.
* [The Foreman](https://theforeman.org/) – complete lifecycle management tool for physical and virtual servers.

---

## 🎯 Cloud Orchestration

* [Ansible](https://www.ansible.com) – contains modules for controlling many types of cloud resources.
* [BOSH](https://bosh.io/) – IaaS orchestration platform for deploying and managing distributed systems.
* [Cloudify](https://cloudify.co/) – open source TOSCA-based cloud orchestration software platform.
* [Consul](https://www.consul.io/) – tool for discovering and configuring services in your infrastructure.
* [etcd](https://etcd.io/) – highly-available key value store for shared configuration and service discovery.
* [Juju](https://juju.is/) – cloud orchestration tool managing services as charms with YAML configuration.
* [MCollective](https://puppet.com/docs/mcollective/current/index.html) – Ruby framework to manage server orchestration, developed by Puppet.
* [Rundeck](https://www.rundeck.com/) – simple orchestration tool.
* [Salt](https://saltproject.io/) – fast, scalable and flexible systems management software written in Python/ZeroMQ.
* [StackStorm](https://stackstorm.com/) – event driven operations and ChatOps platform for infrastructure management.
* [ZooKeeper](https://zookeeper.apache.org/) – centralized service for configuration information, naming, and distributed synchronization.

---

## 🗄️ Cloud Storage

* [git-annex assistant](https://git-annex.branchable.com/assistant/) – synchronised folder across OSX, Linux, Android, removable drives and cloud services.
* [nextCloud](https://nextcloud.com) – provides access to your files via the web.
* [ownCloud](https://owncloud.com) – universal access to your files via the web, computer or mobile devices.
* [Seafile](https://www.seafile.com) – open source cloud storage solution.
* [SparkleShare](https://www.sparkleshare.org/) – cloud storage and file synchronization using Git as storage backend.
* [Syncthing](https://syncthing.net/) – open source system for private, encrypted and authenticated distribution of data.

---

## 👁️ Code Review

* [Gerrit](https://www.gerritcodereview.com/) – Git-based code review tool facilitating source code modifications review.
* [Gitea](https://gitea.io/) – painless self-hosted Git service, lightweight GitHub alternative.
* [GitLab](https://gitlab.com/) – complete DevOps platform with code review, CI/CD, and more.
* [Review Board](https://www.reviewboard.org/) – web-based collaborative code review tool.

---

## 🤝 Collaborative Software

* [Citadel/UX](https://www.citadel.org/) – collaboration suite (messaging and groupware) descended from the Citadel family.
* [EGroupware](https://www.egroupware.org/) – groupware software written in PHP.
* [Horde Groupware](https://www.horde.org/apps/groupware) – PHP based collaborative software suite including email, calendars, wikis and file management.
* [Kolab](https://kolab.org) – another groupware suite.
* [SOGo](https://www.sogo.nu/) – collaborative software server with a focus on simplicity and scalability.
* [Zimbra](https://www.zimbra.com/) – collaborative software suite including an email server and web client.

---

## 🗃️ Configuration Management Database

* [Clusto](https://github.com/clusto/clusto) – helps track inventory, where it is, how it's connected, with an abstracted infrastructure interface.
* [i-doit](https://www.i-doit.org/) – open source IT documentation and CMDB.
* [iTop](https://www.combodo.com/itop-193) – complete open source, ITIL, web based service management tool.
* [Netbox](https://netbox.dev/) – IP address management (IPAM) and data center infrastructure management (DCIM) tool.
* [Ralph](https://github.com/allegro/ralph) – asset management, DCIM and CMDB system for large data centers and LAN networks.

---

## ⚙️ Configuration Management

* [Ansible](https://www.ansible.com/) – written in Python, manages nodes over SSH.
* [CFEngine](https://cfengine.com/) – lightweight agent system with a declarative language for configuration state.
* [Chef](https://www.chef.io/) – written in Ruby and Erlang, uses a pure-Ruby DSL.
* [mgmt](https://github.com/purpleidea/mgmt) – next generation config management written in Go.
* [Puppet](https://www.puppet.com/) – written in Ruby, uses Puppet's declarative language or a Ruby DSL.
* [(R)?ex](https://www.rexify.org/) – written in Perl, uses plain Perl over SSH without agent.
* [Salt](https://saltproject.io/) – written in Python.

---

## 🔄 Continuous Integration & Continuous Deployment

* [Buildbot](https://buildbot.net/) – Python-based toolkit for continuous integration.
* [Concourse CI](https://concourse-ci.org/) – pipeline-based CI system written in Go.
* [Drone](https://www.drone.io/) – continuous integration server built on Docker and configured using YAML files.
* [GitLab CI](https://docs.gitlab.com/ee/ci/) – built-in CI/CD integrated with GitLab repositories.
* [GoCD](https://www.go.cd/) – open source continuous delivery server.
* [Jenkins](https://www.jenkins.io/) – extendable open source continuous integration server.
* [Spinnaker](https://spinnaker.io/) – open source, multi-cloud continuous delivery platform.
* [TeamCity](https://www.jetbrains.com/teamcity/) – powerful continuous integration out of the box.

---

## 🎛️ Control Panels

* [Ajenti](http://ajenti.org/) – control panel for Linux and BSD.
* [Cockpit](https://cockpit-project.org/) – multi-server web interface for Linux servers written in C.
* [Froxlor](https://www.froxlor.org/) – easy to use panel for Linux with Nginx and PHP-FPM support.
* [ISPConfig](https://www.ispconfig.org) – hosting control panel for Linux.
* [Virtualmin](https://www.virtualmin.com/) – control panel for Linux based on Webmin.
* [Webmin](https://www.webmin.com/) – Linux server control panel.

---

## 🚀 Deployment Automation

* [Capistrano](https://capistranorb.com) – deploy to any number of machines simultaneously or as a rolling set via SSH.
* [Fabric](https://www.fabfile.org/) – Python library and CLI tool for streamlining SSH for deployment or sysadmin tasks.
* [Mina](https://nadarei.co/mina/) – really fast deployer and server automation tool.

---

## 📐 Diagramming

* [drawthe.net](http://go.drawthe.net/) – draws network diagrams dynamically from a text file describing placement and layout.
* [draw.io](https://app.diagrams.net/) – free online diagram software for network and infrastructure diagrams.

---

## 📁 Distributed Filesystems

* [Ceph](https://ceph.io/) – distributed object store and file system.
* [DRBD](https://linbit.com/drbd/) – distributed replicated block device.
* [GlusterFS](https://www.gluster.org/) – scale-out network-attached storage file system.
* [HDFS](https://hadoop.apache.org/) – distributed, scalable, and portable file-system for the Hadoop framework.
* [Lustre](https://www.lustre.org/) – parallel distributed file system for large-scale cluster computing.
* [MooseFS](https://moosefs.com/) – fault tolerant, network distributed file system.
* [OpenAFS](https://www.openafs.org/) – distributed network file system with read-only replicas and multi-OS support.
* [TahoeLAFS](https://tahoe-lafs.org/trac/tahoe-lafs) – secure, decentralized, fault-tolerant peer-to-peer distributed data store.
* [XtreemFS](http://www.xtreemfs.org/) – fault-tolerant distributed file system for all storage needs.

---

## 🌐 DNS

* [Bind](https://www.isc.org/bind/) – the most widely used name server software.
* [CoreDNS](https://coredns.io/) – fast and flexible DNS server used in Kubernetes.
* [Designate](https://wiki.openstack.org/wiki/Designate) – DNS REST API supporting several DNS servers as backend.
* [djbdns](https://cr.yp.to/djbdns.html) – collection of DNS applications, including tinydns.
* [dnsmasq](http://www.thekelleys.org.uk/dnsmasq/doc.html) – lightweight service providing DNS, DHCP and TFTP for small-scale networks.
* [Knot](https://www.knot-dns.cz/) – high performance authoritative-only DNS server.
* [NSD](https://www.nlnetlabs.nl/projects/nsd/) – authoritative only, high performance, simple name server.
* [PowerDNS](https://www.powerdns.com/) – DNS server with a variety of data storage back-ends and load balancing features.
* [Unbound](https://unbound.net/) – validating, recursive, and caching DNS resolver.
* [Yadifa](https://www.yadifa.eu/) – lightweight authoritative name server with DNSSEC capabilities.

---

## 📝 Editors

* [GNU Emacs](https://www.gnu.org/software/emacs/) – extensible, customizable text editor and more.
* [Helix](https://helix-editor.com/) – post-modern modal text editor written in Rust.
* [IntelliJ IDEA](https://www.jetbrains.com/idea/) – capable and ergonomic IDE with a large plugin ecosystem.
* [Nano](https://www.nano-editor.org/) – popular text editor that comes by default with most Linux distributions.
* [Neovim](https://neovim.io/) – hyperextensible Vim-based text editor.
* [SciTE](https://www.scintilla.org/SciTE.html) – SCIntilla based text editor.
* [TextMate](https://github.com/textmate/textmate/) – graphical text editor for macOS.
* [Vim](https://www.vim.org) – highly configurable text editor built to enable efficient editing.
* [Visual Studio Code](https://code.visualstudio.com/) – fast, extensible, multi-platform code editor from Microsoft.
* [Zed](https://zed.dev/) – high-performance, multiplayer code editor written in Rust.

---

## 📋 IT Asset Management

* [GLPI](https://glpi-project.org/) – information resource-manager with an additional administration interface.
* [Netbox](https://netbox.dev/) – IP address management (IPAM) and data center infrastructure management (DCIM) tool.
* [OCS Inventory NG](https://ocsinventory-ng.org/) – enables users to inventory their IT assets.
* [OpenDCIM](https://www.opendcim.org/) – web based data center infrastructure management application.
* [RackTables](https://racktables.org/) – datacenter and server room asset management for hardware, network addresses, and rack space.
* [Ralph](https://github.com/allegro/ralph) – asset management, DCIM and CMDB system for large data centers and LAN networks.
* [Snipe-IT](https://snipeitapp.com/) – asset and license management software.

---

## 🔑 LDAP

### LDAP Servers

* [389 Directory Server](https://www.port389.org) – developed by Red Hat.
* [Apache Directory Server](https://directory.apache.org/) – Apache Software Foundation project written in Java.
* [Fusion Directory](https://www.fusiondirectory.org) – improves management of services and company directory based on OpenLDAP.
* [OpenLDAP](https://openldap.org/) – developed by the OpenLDAP Project.

### LDAP Management

* [Apache Directory Studio](https://directory.apache.org/studio/) – Eclipse-based LDAP browser and directory client.
* [LDAP Account Manager](https://www.ldap-account-manager.org/) – web-based tool for managing LDAP accounts.

---

## 📊 Log Management

* [Elasticsearch](https://www.elastic.co/elasticsearch/) – Lucene based document store mainly used for log indexing, storage and analysis.
* [Fluentd](https://www.fluentd.org/) – log collector and shipper.
* [Flume](https://flume.apache.org/) – distributed log collection and aggregation system.
* [Grafana Loki](https://grafana.com/oss/loki/) – horizontally scalable, multi-tenant log aggregation system inspired by Prometheus.
* [Graylog](https://www.graylog.org/) – pluggable log and event analysis server with alerting options.
* [Kibana](https://www.elastic.co/kibana/) – visualize logs and time-stamped data.
* [Logstash](https://www.elastic.co/logstash/) – tool for managing events and logs.
* [Vector](https://vector.dev/) – high-performance observability data pipeline.

---

## 📧 Mail Servers

### Mail Delivery Agents (IMAP/POP3)

* [Courier IMAP/POP3](https://www.courier-mta.org/imap/) – fast, scalable, enterprise IMAP and POP3 server.
* [Cyrus IMAP/POP3](https://www.cyrusimap.org/) – intended to run on sealed servers where normal users cannot log in.
* [Dovecot](https://www.dovecot.org/) – IMAP and POP3 server written primarily with security in mind.

### Mail Transfer Agents (SMTP)

* [Exim](https://www.exim.org/) – message transfer agent developed at the University of Cambridge.
* [Haraka](https://haraka.github.io/) – high-performance, pluggable SMTP server written in JavaScript.
* [MailCatcher](https://mailcatcher.me/) – simple SMTP MTA gateway that accepts all mail and displays in web interface.
* [Maildrop](https://github.com/m242/maildrop) – open source disposable email SMTP server, useful for development.
* [OpenSMTPD](https://www.opensmtpd.org/) – secure SMTP server implementation from the OpenBSD project.
* [Postfix](https://www.postfix.org/) – fast, easy to administer, and secure Sendmail replacement.
* [Sendmail](https://www.sendmail.org/) – message transfer agent (MTA).

### Complete Solutions

* [iRedMail](https://www.iredmail.org/) – full-featured mail server solution based on Postfix and Dovecot.
* [Mail-in-a-Box](https://mailinabox.email/) – easy-to-deploy mail server in a box.
* [Modoboa](https://modoboa.org/) – modern Django-based email hosting platform.

---

## 💬 Messaging

### XMPP Servers

* [ejabberd](https://www.ejabberd.im/) – XMPP instant messaging server written in Erlang/OTP.
* [MongooseIM](https://www.erlang-solutions.com/technologies/mongooseim/) – fullstack real-time mobile messaging platform in Erlang.
* [Openfire](https://www.igniterealtime.org/projects/openfire/) – real time collaboration server.
* [Prosody IM](https://prosody.im/) – XMPP server written in Lua.
* [Tigase](https://tigase.net/tigase-xmpp-server/) – XMPP server implementation in Java.

### XMPP Web Clients

* [Candy](https://candy-chat.github.io/candy/) – multi user XMPP client written in JavaScript.
* [Kaiwa](http://getkaiwa.com/) – web based chat client in the style of common paid alternatives.

### Modern Team Messaging

* [Mattermost](https://mattermost.com/) – open source, self-hosted Slack alternative.
* [Rocket.Chat](https://rocket.chat/) – open source team communication platform.

---

## 📡 Monitoring

### Monitoring Software

* [Alerta](https://github.com/alerta/alerta) – distributed, scalable and flexible monitoring system.
* [Cacti](https://www.cacti.net) – web-based network monitoring and graphing tool.
* [Cabot](https://cabotapp.com/) – monitoring and alerts, similar to PagerDuty.
* [Centreon](https://www.centreon.com) – IT infrastructure and application monitoring for service performance.
* [Checkmk](https://checkmk.com/) – comprehensive IT monitoring for networks, servers, and applications.
* [Flapjack](https://flapjack.io/) – monitoring notification routing and event processing system.
* [Icinga](https://icinga.com/) – fork of Nagios with a modern web interface.
* [LibreNMS](https://www.librenms.org/) – autodiscovering network monitoring system.
* [Monit](https://mmonit.com/monit/) – small open source utility for managing and monitoring Unix systems.
* [Munin](http://munin-monitoring.org/) – networked resource monitoring tool.
* [Nagios](https://www.nagios.org/) – computer system, network and infrastructure monitoring software.
* [Naemon](https://www.naemon.io/) – network monitoring tool based on Nagios 4 core with performance enhancements.
* [Observium](https://www.observium.org/) – SNMP monitoring for servers and networking devices.
* [Riemann](http://riemann.io/) – flexible and fast events processor for complex events/metrics analysis.
* [Sensu](https://sensu.io/) – open source monitoring framework.
* [Sentry](https://sentry.io/) – application monitoring, event logging and aggregation.
* [Uptime Kuma](https://github.com/louislam/uptime-kuma) – easy to use self-hosted monitoring tool.
* [Zabbix](https://www.zabbix.com/) – enterprise-class software for monitoring networks and applications.
* [Zenoss](https://www.zenoss.com) – application, server, and network management platform.

### Monitoring Dashboards

* [Adagios](http://adagios.org/) – web based Nagios configuration interface.
* [Grafana](https://grafana.com/) – analytics and interactive visualization platform.
* [Thruk](https://www.thruk.org/) – multibackend monitoring web interface for Naemon, Nagios, Icinga and Shinken.

### Monitoring Distributions

* [OMD](http://omdistro.org/) – the Open Monitoring Distribution.

---

## 📈 Metric & Metric Collection

* [Collectd](https://collectd.org/) – system statistic collection daemon.
* [Diamond](https://github.com/BrightcoveOS/Diamond) – Python based statistic collection daemon.
* [Facette](https://facette.io) – time series data visualization and graphing software written in Go.
* [Ganglia](http://ganglia.sourceforge.net/) – high performance, scalable RRD based monitoring for grids/clusters.
* [Grafana](https://grafana.com/) – metrics and log dashboard and graph editor.
* [Graphite](https://graphite.readthedocs.org/) – open source scalable graphing server.
* [InfluxDB](https://www.influxdata.com/) – open source distributed time series database.
* [NetData](https://www.netdata.cloud) – distributed real-time performance and health monitoring.
* [OpenTelemetry](https://opentelemetry.io/) – vendor-neutral observability framework for metrics, logs, and traces.
* [OpenTSDB](http://opentsdb.net/) – store and serve massive amounts of time series data without losing granularity.
* [Prometheus](https://prometheus.io/) – service monitoring system and time series database.
* [RRDtool](https://oss.oetiker.ch/rrdtool/) – high performance data logging and graphing system for time series data.
* [Smashing](https://github.com/Smashing/smashing) – Ruby gem for rapid statistical dashboard development with HTML5.
* [Statsd](https://github.com/statsd/statsd) – application statistic listener.
* [Victoria Metrics](https://victoriametrics.com/) – fast, cost-effective and scalable monitoring solution and time series database.

---

## 🔌 Network Configuration Management

* [GestióIP](https://www.gestioip.net/) – automated web based IPv4/IPv6 IP Address Management tool.
* [Netbox](https://netbox.dev/) – IP address management (IPAM) and data center infrastructure management (DCIM) tool.
* [NOC Project](https://nocproject.org/) – scalable, high-performance OSS system for ISP, service and content providers.
* [Oxidized](https://github.com/ytti/oxidized) – modern network device configuration monitoring with web interface and Git storage.
* [phpIPAM](https://phpipam.net/) – open source IP address management with PowerDNS integration.
* [RANCID](http://www.shrubbery.net/rancid/) – monitors network device configuration and maintains history of changes.
* [trigger](https://github.com/trigger/trigger) – robust network automation toolkit written in Python.

---

## 📰 Newsletters

* [DadaMail](http://dadamailproject.com/) – mailing list manager, written in Perl.
* [listmonk](https://listmonk.app/) – high performance, self-hosted newsletter and mailing list manager.
* [phpList](https://www.phplist.com/) – newsletter manager written in PHP.

---

## 🍃 NoSQL

### Column-Family

* [Apache HBase](https://hbase.apache.org/) – Hadoop database, a distributed, big data store.
* [Cassandra](https://cassandra.apache.org/) – distributed DBMS designed to handle large amounts of data across many servers.
* [ScyllaDB](https://www.scylladb.com/) – high-performance NoSQL database compatible with Apache Cassandra.

### Document Store

* [CouchDB](https://couchdb.apache.org/) – ease of use, with multi-master replication document-oriented database system.
* [Elasticsearch](https://www.elastic.co/elasticsearch/) – Java based database, popular with log aggregation and email archiving.
* [MongoDB](https://www.mongodb.com/) – document-oriented database system.
* [RethinkDB](https://rethinkdb.com/) – open source distributed document store database, focuses on JSON.

### Graph

* [Neo4j](https://neo4j.com/) – open source graph database.

### Key-Value

* [Couchbase](https://www.couchbase.com/) – in-memory, replicated, persistent key/value datastore.
* [LevelDB](https://github.com/google/leveldb) – Google's high performance key/value database.
* [Redis](https://redis.io/) – networked, in-memory, key-value data store with optional durability.
* [Valkey](https://valkey.io/) – open source Redis fork maintained by the Linux Foundation.

---

## 📦 Packaging

* [fpm](https://github.com/jordansissel/fpm) – versatile multi format package creator.
* [nFPM](https://nfpm.goreleaser.com/) – simple, 0-dependency deb, rpm and apk packager.
* [tito](https://github.com/dgoodwin/tito) – builds RPMs for git-based projects.

---

## 📨 Queuing

* [ActiveMQ](https://activemq.apache.org/) – open source message broker written in Java with full JMS client.
* [BeanstalkD](https://beanstalkd.github.io/) – simple, fast work queue.
* [Gearman](http://gearman.org/) – fast multi-language queuing/job processing platform.
* [Kafka](https://kafka.apache.org/) – high-throughput distributed messaging system.
* [NSQ](https://nsq.io/) – realtime distributed messaging platform.
* [RabbitMQ](https://www.rabbitmq.com/) – robust, fully featured, cross distro queuing system.
* [ZeroMQ](https://zeromq.org/) – high-performance asynchronous messaging library.

---

## 🐘 RDBMS

* [Firebird](https://www.firebirdsql.org/) – true universal open source database.
* [MariaDB](https://mariadb.org/) – community-developed fork of MySQL.
* [MySQL](https://dev.mysql.com/) – most popular RDBMS server.
* [Percona Server](https://www.percona.com/software) – enhanced, drop-in MySQL replacement.
* [PostgreSQL](https://www.postgresql.org/) – object-relational database management system.
* [SQLite](https://sqlite.org/) – self-contained, serverless, zero-configuration, transactional SQL database library.

---

## 🔒 Security

* [Blackbox](https://github.com/StackExchange/blackbox) – safely store secrets in Git/Mercurial using GPG encryption.
* [BounCA](https://bounca.org/) – personal SSL/Certificate Authority key management tool.
* [Denyhosts](https://github.com/denyhosts/denyhosts) – thwart SSH dictionary based attacks and brute force attacks.
* [Fail2Ban](https://www.fail2ban.org/) – scans log files and takes action on IPs that show malicious behavior.
* [fwknop](https://www.cipherdyne.org/fwknop/) – protects ports via Single Packet Authorization.
* [OSSEC](https://www.ossec.net) – HIDS performing log analysis, FIM, rootkit detection, and more.
* [OSQuery](https://osquery.io/) – query your servers status and info using a SQL-like interface.
* [pfSense](https://www.pfsense.org/) – firewall and router FreeBSD distribution.
* [Snort](https://www.snort.org/) – free and open source network intrusion prevention and detection system.
* [SpamAssassin](https://spamassassin.apache.org/) – powerful and popular email spam filter employing a variety of detection techniques.
* [Wazuh](https://wazuh.com/) – open source security platform unifying SIEM and XDR capabilities.

---

## 🔍 Service Discovery

* [Consul](https://www.consul.io/) – tool for service discovery, monitoring and configuration.
* [etcd](https://etcd.io/) – distributed reliable key-value store for service discovery.
* [ZooKeeper](https://zookeeper.apache.org/) – centralized service for configuration, naming, and distributed synchronization.

---

## 🐳 Software Containers

* [containerd](https://containerd.io/) – industry-standard container runtime.
* [Docker](https://www.docker.com/) – open platform for building, shipping, and running distributed applications.
* [Helm](https://helm.sh/) – package manager for Kubernetes.
* [k9s](https://k9scli.io/) – terminal UI for Kubernetes clusters.
* [Kubernetes](https://kubernetes.io/) – open source system for automating deployment, scaling, and management of containerized applications.
* [LXC](https://linuxcontainers.org/lxc/) – userspace interface for Linux kernel containment features.
* [LXD](https://linuxcontainers.org/lxd/) – container and virtual machine manager.
* [Podman](https://podman.io/) – daemonless container engine for developing, managing, and running OCI containers.
* [Portainer](https://www.portainer.io/) – container management UI for Docker, Kubernetes, and more.

---

## 🔐 SSH

* [Advanced SSH config](https://pypi.org/project/advanced-ssh-config/) – enhances ssh_config file capabilities, completely transparent.
* [autossh](https://www.harding.motd.ca/autossh/) – automatically respawn ssh session after network interruption.
* [Cluster SSH](https://github.com/duncs/clusterssh) – controls multiple xterm windows via a single graphical console.
* [Mosh](https://mosh.org/) – the mobile shell.
* [sshrc](https://github.com/Russell91/sshrc) – sources `~/.sshrc` on your local computer after logging in remotely.
* [stormssh](https://stormssh.readthedocs.org) – command line tool to manage SSH connections.
* [Teleport](https://goteleport.com/) – certificate-based access for SSH, Kubernetes, databases, and web apps.

---

## 📉 Statistics

* [AWStats](https://www.awstats.org/) – generates web, streaming, FTP or mail server statistics graphically.
* [GoAccess](https://goaccess.io/) – real-time web log analyzer and interactive viewer running in a terminal.
* [Matomo](https://matomo.org/) – open source web analytics platform (formerly Piwik).
* [Open Web Analytics](https://www.openwebanalytics.com/) – add web analytics to websites using JS, PHP or REST APIs.

---

## 🟢 Status Pages

* [Cachet](https://cachethq.io) – open source status page system written in PHP.
* [Gatus](https://github.com/TwiN/gatus) – automated developer-oriented status page.
* [Upptime](https://upptime.js.org/) – open source uptime monitor and status page powered by GitHub Actions.

---

## 🎫 Ticketing Systems

* [Bugzilla](https://www.bugzilla.org/) – general-purpose bugtracker and testing tool developed by the Mozilla project.
* [Flyspray](http://flyspray.org) – web-based bug tracking system written in PHP.
* [MantisBT](https://www.mantisbt.org/) – web-based bug tracking system.
* [osTicket](https://osticket.com/) – simple support ticket system.
* [OTRS](https://otrs.com/) – trouble ticket system for assigning and tracking incoming queries.
* [Redmine](https://www.redmine.org/) – open source project management/ticketing web application written in Ruby.
* [Request Tracker](https://bestpractical.com/rt/) – ticket-tracking system written in Perl.
* [Zammad](https://zammad.org/) – modern helpdesk/customer support system.

---

## 🔧 Troubleshooting

* [mitmproxy](https://mitmproxy.org/) – Python tool for intercepting, viewing and modifying network traffic.
* [Sysdig](https://sysdig.com/) – capture system state and activity from a running Linux instance, then save, filter and analyze.
* [Wireshark](https://www.wireshark.org/) – the world's foremost network protocol analyzer.

---

## 📌 Project Management

* [GitBucket](https://github.com/gitbucket/gitbucket) – GitHub clone written in Scala; single jar install.
* [GitLab](https://www.gitlab.com/) – DevOps platform with project management, CI/CD, and more.
* [Gitea](https://gitea.io/) – painless, self-hosted Git service with project management features.
* [Gogs](https://gogs.io/) – self-hosted Git service written in Go.
* [OpenProject](https://www.openproject.org) – project collaboration with open source.
* [Taiga](https://taiga.io/) – agile, open source project management tool based on Kanban and Scrum.
* [Trac](https://trac.edgewall.org/) – written in Python.

---

## 🔀 Version Control

* [Fossil](https://www.fossil-scm.org/) – distributed version control with built-in wiki and bug tracking.
* [Git](https://git-scm.com/) – distributed revision control and source code management with an emphasis on speed.
* [GNU Bazaar](https://bazaar.canonical.com/) – distributed revision control system sponsored by Canonical.
* [Mercurial](https://www.mercurial-scm.org/) – another distributed revision control.
* [Subversion](https://subversion.apache.org/) – client-server revision control system.

---

## 💻 Virtualization

* [KVM](https://www.linux-kvm.org) – Linux kernel virtualization infrastructure.
* [OpenNebula](https://opennebula.io/) – flexible enterprise cloud made simple.
* [oVirt](https://www.ovirt.org/) – manages virtual machines, storage and virtual networks.
* [Packer](https://www.packer.io/) – tool for creating identical machine images for multiple platforms from a single configuration.
* [Proxmox VE](https://www.proxmox.com/proxmox-ve) – complete open source virtualization management solution.
* [QEMU](https://www.qemu.org/) – generic and open source machine emulator and virtualizer.
* [Vagrant](https://www.vagrantup.com/) – tool for building complete development environments.
* [VirtualBox](https://www.virtualbox.org/) – virtualization product from Oracle Corporation.
* [Xen](https://xenproject.org/) – virtual machine monitor for Intel/AMD and ARM architectures.

---

## 🛡️ VPN

* [OpenVPN](https://openvpn.net/) – uses a custom security protocol utilizing SSL/TLS for key exchange.
* [Pritunl](https://pritunl.com/) – OpenVPN based solution, easy to set up.
* [SoftEther](https://www.softether.org/) – multi-protocol software VPN with advanced features.
* [sshuttle](https://github.com/sshuttle/sshuttle) – poor man's VPN over SSH.
* [strongSwan](https://www.strongswan.org/) – complete IPsec implementation for Linux.
* [tinc](https://www.tinc-vpn.org/) – distributed p2p VPN.
* [WireGuard](https://www.wireguard.com/) – extremely simple, fast and modern VPN using state-of-the-art cryptography.

---

## 🌍 Web

### Web Servers

* [Apache](https://httpd.apache.org/) – most popular web server.
* [Caddy](https://caddyserver.com/) – the HTTP/2 web server with automatic HTTPS.
* [Lighttpd](https://www.lighttpd.net/) – web server optimized for speed-critical environments.
* [Nginx](https://nginx.org/) – reverse proxy, load balancer, HTTP cache, and web server.
* [uWSGI](https://github.com/unbit/uwsgi/) – full stack for building hosting services.

### Web Performance

* [HAProxy](https://www.haproxy.org/) – software based load balancing, SSL offloading and performance optimization.
* [Squid](http://www.squid-cache.org/) – caching proxy supporting HTTP, HTTPS, FTP, and more.
* [Traefik](https://traefik.io/) – modern HTTP reverse proxy and load balancer for deploying microservices.
* [Varnish](https://varnish-cache.org/) – HTTP based web application accelerator focusing on caching and compression.

---

## 📮 Webmails

* [Mailpile](https://www.mailpile.is/) – modern, fast web-mail client with user-friendly encryption and privacy features.
* [Roundcube](https://roundcube.net/) – browser-based IMAP client with an application-like user interface.
* [SnappyMail](https://snappymail.eu/) – simple, modern and fast web-based email client.

---

## 📚 Wikis

* [BookStack](https://www.bookstackapp.com/) – simple, user-friendly wiki built with PHP using MySQL for storage.
* [DokuWiki](https://www.dokuwiki.org/dokuwiki) – simple to use and highly versatile wiki that doesn't require a database.
* [Gitea Wiki](https://gitea.io/) – built-in wiki feature in Gitea repositories.
* [Gollum](https://github.com/gollum/gollum) – simple, Git-powered wiki with a sweet API and local frontend.
* [MediaWiki](https://www.mediawiki.org/wiki/MediaWiki) – used to power Wikipedia.
* [MoinMoin](https://moinmo.in/) – advanced, easy to use and extensible wiki engine.
* [TiddlyWiki](https://tiddlywiki.com) – complete interactive wiki in JavaScript.
* [Wiki.js](https://js.wiki/) – modern, open source wiki app built on Node.js.

---

# 📖 Resources

## Blogs

* [Code as Craft](https://codeascraft.com/) – Etsy's Ops blog with lots of technical posts.
* [DevOpsGuys](https://devopsguys.com/) – devops consultants who blog about operations.
* [Rackspace Developers](https://developer.rackspace.com/blog/) – blog covering DevOps topics.

## Books

* [Learn Cisco Network Administration in a Month of Lunches](https://www.manning.com/books/learn-cisco-network-administration-in-a-month-of-lunches) – tutorial for sysadmins learning to administer Cisco switches and routers.
* [Securing DevOps](https://www.manning.com/books/securing-devops) – book on security techniques for DevOps reviewing state of the art practices.
* [The Linux Command Line](http://linuxcommand.org/tlcl.php) – a book about the Linux command line by William Shotts.
* [The Phoenix Project](https://itrevolution.com/product/the-phoenix-project/) – how DevOps techniques can fix problems in IT organizations.
* [The Practice of System and Network Administration](https://everythingsysadmin.com/books.html) – best practices independent of specific platforms.
* [UNIX and Linux System Administration Handbook](https://admin.com/) – approaches system administration from a practical perspective.

## Newsletters

* [DevOpsLinks](https://devopslinks.com) – community of DevOps, SysAdmin and Developers with a weekly newsletter.
* [Servers for Hackers](https://serversforhackers.com/) – newsletter for programmers who need to know their way around a server.

## Repositories

### Debian-based

* [Dotdeb](https://www.dotdeb.org/) – repository with LAMP updated packages for Debian.

### RPM-based

* [ElRepo](https://elrepo.org/) – community repo for Enterprise Linux (RHEL, CentOS, etc).
* [EPEL](https://fedoraproject.org/wiki/EPEL) – repository for RHEL and compatibles (CentOS, Scientific Linux).
* [Remi](https://rpms.remirepo.net/) – repository with LAMP updated packages for RHEL/CentOS/Fedora.

## Websites

* [Digital Ocean Tutorials](https://www.digitalocean.com/community/tutorials) – vast resource for applications, tools, and sysadmin topics.
* [Ops School](https://www.opsschool.org) – comprehensive program for learning operations engineering.

---

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## License

[MIT](LICENSE) © [Think Cube](https://github.com/Think-Cube)
