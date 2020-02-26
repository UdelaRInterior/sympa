# Changelog of ansible-sympa role

## [v0.3.0-pr](https://github.com/UdelaRInterior/ansible-sympa/releases/tag/v0.3.0-pr)

* Optional Sympa robots configuration (sympa & web interface)
* Flags to make some confis optional, backwards compatibility defaults 
* this CHANGELOG file, for versions tracking
* to be proposed for upstream PR

## [v0.3.0-pr](https://github.com/UdelaRInterior/ansible-sympa/releases/tag/v0.3.0-pr)

* Optional Apache 2 server installation and configuration (https) for Sympa
* to be proposed for upstream PR

## [v0.2.0-pr11](https://github.com/UdelaRInterior/ansible-sympa/releases/tag/v0.2.0-pr11)

* PostgreSQL management integration
* Optional Database manager (MySQL and PostgreSQL) installation by the role itself
* Upstream [Pull Request](https://github.com/stuvusIT/sympa/pull/11) for Galaxy Release



## [v0.1.0](https://github.com/stuvusIT/sympa/releases/tag/0.1.0)

* first versionning tag of the upstream role, to start collaboration
* MySQL database and user creation, MySQL server installation is a requirement
* Installs and configure Sympa, including:
  * LDAP interfacing
  * DKIM management
  * basic custom list templates
* Webserver configuration has to be perfomed elswhere

## [v0.1-arrayan](https://github.com/UdelaRInterior/ansible-sympa/releases/tag/v0.1-arrayan)

* first version built by UdelaR, forking [stuvusIT/sympa](https://github.com/stuvusIT/sympa) role 
* adaptation to PostgreSQL, Sympa robots management and Apache2 configuration 
* Ansible code is still unsatisfactory, forcing debian packages installation
* the branch diverges from original code, with some backwards incompatibilities and without MySQL testing 
