# Personal selfhosting list

Many open-source solutions exist to host SaaS software alternatives. Here, you can checkout my **personal list** of softwares that i **daily** use. All these software have been **tested in production** and **approuved** by users.

This list is directly inspired from great [awesome-selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted). This list is very (too ?) long, so i decided to create my own one.

--------------------

- List of Software
  - [Torrent (P2P file sharing)](#torrent-p2p-file-sharing)
  - [Content Management Systems (CMS)](#content-management-systems-cms)
  - [Communication systems](#communication-systems)
  - [Email service](#email-service)
  - [Webmail clients](#webmail-clients)
  - [File Sharing and Synchronization](#file-sharing-and-synchronization)
  - [Media Streaming](#media-streaming)
  - [Office Suites](#office-suites)
  - [Password Managers](#password-managers)
  - [Personal Dashboards](#personal-dashboards)
  - [Software Factory](#software-factory)
  - [Server administration tools](#server-administration-tools)
  - [VoIP](#voip)
  - [Kubernetes tools](#kubernetes-tools)

--------------------

<!-- BEGIN SOFTWARE LIST -->

## Torrent (P2P file sharing)
Torrent automation and download web platform.

**[`^        back to top        ^`](#)**

_Automation_

- [Lidarr](https://lidarr.audio/) - Lidarr is a music collection manager for Usenet and BitTorrent users. ([Docker image](https://hub.docker.com/r/linuxserver/lidarr)) ([Source Code](https://github.com/Lidarr/Lidarr)) `GPL-3.0` `C#`
- [Sonarr](https://sonarr.tv/) - Automatic TV Shows downloader and manager for Usenet and BitTorrent. It can grab, sort and rename new episodes and automatically upgrade the quality of files already downloaded when a better quality format becomes available. ([Docker image](https://hub.docker.com/r/linuxserver/sonarr)) ([Source Code](https://github.com/Sonarr/Sonarr)) `GPL-3.0` `C#`
- [Radarr](https://radarr.video/) - Radarr is an independent fork of Sonarr reworked for automatically downloading movies via Usenet and BitTorrent, à la Couchpotato. ([Docker image](https://hub.docker.com/r/linuxserver/radarr)) ([Source Code](https://github.com/Radarr/Radarr)) `GPL-3.0` `C#`
- [Jackett](https://github.com/Jackett/Jackett) - API Support for your favorite torrent trackers. ([Docker image](https://hub.docker.com/r/linuxserver/jackett)) ([Source Code](https://github.com/Jackett/Jackett)) `GPL-2.0` `C#`

_Web download platfform_

- [RuTorrent](https://github.com/Novik/ruTorrent) - Frontend view for rTorrent ([Docker image](https://hub.docker.com/r/romancin/rutorrent-flood)) ([Source Code](https://github.com/Novik/ruTorrent)) `GPL-3.0` `Javascript`

- [Transmission](https://transmissionbt.com/) - Torrent web client ([Docker image](https://hub.docker.com/r/linuxserver/transmission)) ([Source Code](https://github.com/transmission/transmission)) `GPL-3.0` `Javascript`


## Content Management Systems (CMS)

**[`^        back to top        ^`](#)**

_Blogging_

- [WordPress](https://wordpress.org/) - World's most-used blogging and CMS engine. ([Docker image](https://hub.docker.com/_/wordpress)) ([Source Code](https://github.com/WordPress/WordPress)) `GPL-2.0` `PHP`

- [NodeBB](https://nodebb.org/) - Node.js based forum software built for the modern web. ([Docker image](https://hub.docker.com/r/nodebb/docker)) ([Source Code](https://github.com/NodeBB/NodeBB)) `GPL-3.0` `Nodejs`

## Communication systems

**[`^        back to top        ^`](#)**

### Custom communication systems

- [Rocket.Chat](https://rocket.chat/) - Teamchat solution similar to Gitter.im or Slack. ([Docker image](https://hub.docker.com/r/rocketchat/rocket.chat)) ([Source Code](https://github.com/RocketChat/Rocket.Chat)) `MIT` `Nodejs`

- [Jitsi Meet](https://jitsi.org/Projects/JitsiMeet) - Jitsi Meet is an OpenSource (MIT) WebRTC Javascript application that uses Jitsi Videobridge to provide high quality, scalable video conferences. ([Docker image](https://hub.docker.com/r/jitsi/jvb)) ([Source Code](https://github.com/jitsi/jitsi-meet)) `MIT` `Javascript`

- [Jitsi Video Bridge](https://jitsi.org/Projects/JitsiVideobridge) - WebRTC compatible Selective Forwarding Unit (SFU) that allows for multiuser video communication. ([Docker image](https://hub.docker.com/r/jitsi/web)) ([Source Code](https://github.com/jitsi/jitsi-videobridge)) `Apache-2.0` `Java`


### Email service

**[`^        back to top        ^`](#)**

- [Mailcow](https://mailcow.email/) - Mail server suite based on Dovecot, Postfix and other open source software, that provides a modern Web UI for administration. ([Docker image](https://hub.docker.com/u/mailcow)) ([Source Code](https://github.com/andryyy/mailcow)) `GPL-2.0` `PHP`


### File Sharing and Synchronization

**[`^        back to top        ^`](#)**

_Drive_

- [Nextcloud](https://nextcloud.com/) - Access and share your files, calendars, contacts, mail and [more](https://apps.nextcloud.com/) from any device, on your terms. ([Demo](https://demo.nextcloud.com/), ([Docker image](https://hub.docker.com/_/nextcloud)) [Source Code](https://github.com/nextcloud/server)) `AGPL-3.0` `PHP`

- [Seafile](https://www.seafile.com/en/home/) - File hosting and sharing solution primary for teams and organizations. ([Docker image](https://hub.docker.com/r/seafileltd/seafile)) ([Source Code](https://github.com/haiwen/seafile)) `GPL-2.0` `C`

- [Pydio](https://pydio.com/) - Turn any web server into a powerful file management system and an alternative to mainstream cloud storage providers. ([Docker image](https://hub.docker.com/r/pydio/cells)) ([Source Code](https://github.com/pydio/pydio-core)) `AGPL-3.0` `PHP`

_Object storage_

- [Minio](https://minio.io/) - Minio is an open source object storage server compatible with Amazon S3 APIs. ([Docker](https://hub.docker.com/r/minio/minio)) ([Source Code](https://github.com/minio/minio)) `Apache-2.0` `Go`


### Media Streaming

**[`^        back to top        ^`](#)**

- [Plex](https://plex.tv/) - Plex is a centralized home media playback system with a powerful central server. ([Docker image](https://hub.docker.com/r/plexinc/pms-docker)) `⊘ Proprietary`


### Office Suites

**[`^        back to top        ^`](#)**

- [ONLYOFFICE](https://helpcenter.onlyoffice.com/faq/server-opensource.aspx) - Office suite that enables you to manage documents, projects, team and customer relations in one place. ([Docker image](https://hub.docker.com/r/onlyoffice/documentserver)) ([Source Code](https://github.com/ONLYOFFICE/DocumentServer)) `AGPL-3.0` `Nodejs`


### Password Managers

**[`^        back to top        ^`](#)**

- [Bitwarden RS](https://github.com/dani-garcia/bitwarden_rs) - Lightweight Bitwarden server API implementation written in Rust. ([Docker image](https://hub.docker.com/u/bitwardenrs)) `GPL-3.0` `Rust`


### Personal Dashboards

**[`^        back to top        ^`](#)**

- [Homer](https://github.com/bastienwirtz/homer) - A dead simple static homepage to expose your server services, with an easy yaml configuration and connectivity check. ([Docker image (build example)](https://github.com/quadeare/home)) `Apache-2.0` `HTML5`


### Software factory

**[`^        back to top        ^`](#)**

_Code source management_

- [GitLab](http://gitlab.org/) - Self Hosted Git repository management, code reviews, issue tracking, activity feeds and wikis. ([Docker image](https://hub.docker.com/r/gitlab/gitlab-ce)) ([Demo](https://gitlab.com/), [Source Code](https://gitlab.com/gitlab-org/gitlab-ce)) `MIT` `Ruby`

_CI/CD_

- [GitLab CI](https://docs.gitlab.com/ce/ci/) - GitLab CI/CD is a tool built into GitLab for software development ([Docker image](https://hub.docker.com/r/gitlab/gitlab-ce)) ([Source Code](https://gitlab.com/gitlab-org/gitlab-ce)) `MIT` `Ruby`

- [Drone CI](https://drone.io/) - Self hosted CI/CD open-source platform ([Docker image](https://hub.docker.com/r/drone/drone)) ([Source Code](https://github.com/jenkinsci/jenkins)) `Apache-2.0` `Go`

- [Jenkins](https://jenkins.io/) - Self hosted CI/CD open-source platform ([Docker image](https://hub.docker.com/r/jenkins/jenkins)) ([Source Code](https://github.com/jenkinsci/jenkins)) `MIT` `Java`


_Artifacts management_

- [Sonatype Nexus](https://www.sonatype.com/product-nexus-repository) - Self hosted binaries and build artifacts manager. ([Docker image](https://hub.docker.com/r/sonatype/nexus3)) ([Source Code](https://github.com/sonatype/nexus-public)) `Eclipse public license 1.0` `Java`

- [Artifactory](https://jfrog.com/artifactory/) - Self hosted binaries and build artifacts manager. ([Docker image](https://bintray.com/jfrog/registry/artifactory%3Aartifactory-oss)) `⊘ Proprietary`

_Wiki_

- [BookStack](https://www.bookstackapp.com/) - BookStack is a simple, self-hosted, easy-to-use platform for organizing and storing information. It allows for documentation to be stored in a book like fashion. ([Docker image](https://hub.docker.com/r/linuxserver/bookstack)) ([Demo](https://www.bookstackapp.com/#demo), [Source Code](https://github.com/ssddanbrown/BookStack)) `MIT` `PHP`

- [Wiki.js](https://wiki.js.org/) - Modern, lightweight and powerful wiki app built on NodeJS, Git and Markdown. ([Docker image](https://hub.docker.com/r/requarks/wiki)) ([Demo](https://docs.requarks.io)) `AGPL-3.0` `Nodejs`

_Docker registry_

- [Harbor](https://goharbor.io/) - Self hosted Docker registry with vulnerability check. ([Docker installation](https://github.com/goharbor/harbor/releases)) `Apache-2.0` `Go`

_Code Quality_

- [Sonarqube](https://www.sonarqube.org/) - Self hosted quality check tool. ([Docker](https://github.com/SonarSource/sonarqube)) `GNU-3.0` `Java`

_Project management_

- [Redmine](https://www.redmine.org/) - Self hosted project management web tool. ([Docker](https://hub.docker.com/_/redmine)) `GPL-2.0` `Ruby`

### Server administration tools

**[`^        back to top        ^`](#)**

_Ansible_

- [AWX](https://github.com/ansible/awx) - AWX provides a web-based user interface, REST API, and task engine built on top of Ansible. ([Docker](https://github.com/ansible/awx)) `Apache-2.0` `Javascript`

_Backup_

- [Bareos](https://www.bareos.org/en/) - Bareos (Backup Archiving Recovery Open Sourced) is a reliable, cross-network open source software for backup, archiving and recovery of data for all well-established operating systems. ([Docker](https://hub.docker.com/u/barcus)) `AGPL-3.0` `C++`

_SSO_

- [Keycloak](https://www.keycloak.org/) - Keycloak is an open source identity and access management solution. ([Docker](https://hub.docker.com/r/jboss/keycloak)) ([Source Code](https://github.com/keycloak/keycloak)) `Apache-2.0` `Java`

- [Keycloak Gatekeeper](https://github.com/keycloak/keycloak-gatekeeper) - A OpenID / Keycloak Proxy service. ([Docker](https://hub.docker.com/r/keycloak/keycloak-gatekeeper)) ([Source Code](https://github.com/keycloak/keycloak-gatekeeper)) `Apache-2.0` `Go`


### VoIP

**[`^        back to top        ^`](#)**

- [Mumble](https://mumble.info/) - Low-latency, high quality voice/text chat software. ([Docker image](https://hub.docker.com/r/phlak/mumble)) ([Source Code](https://github.com/mumble-voip/mumble)) `BSD-3-Clause` `C++`

- [Teamspeak](https://www.teamspeak.com) - TeamSpeak is a proprietary voice-over-Internet Protocol (VoIP) application for audio communication between users on a chat channel, much like a telephone conference call. ([Docker image](https://hub.docker.com/_/teamspeak)) `⊘ Proprietary`


### Kubernetes tools

**[`^        back to top        ^`](#)**

_Web orchestration platform_

- [Rancher](https://rancher.com/) - Self hosted open-source multi-cluster orchestration platform, lets operations teams deploy, manage and secure enterprise Kubernetes. ([Docker](https://hub.docker.com/r/rancher/rancher/)) `Apache-2.0` `Go`


_K8s automated deployment_

- [RKE](https://rancher.com/) - Rancher Kubernetes Engine (RKE), an extremely simple, lightning fast Kubernetes distribution that runs entirely within containers. ([Docker](https://rancher.com/docs/rke/latest/en/)) `Apache-2.0` `Go`