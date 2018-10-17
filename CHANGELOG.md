## 3.5 2018-10-17 <dave at tiredofit dot ca>

* Force executible permissions on S6 Directories

## 3.4 2018-10-14 <dave at tiredofit dot ca>

* Bump Zabbix to 4.x Branch

## 3.3 2018-07-02 <dave at tiredofit dot ca>

* Revert back to using && \ instead of ; \ in Dockerfile
* Add ENABLE_GMAIL_SMTP environment variable thanks to @joeyberkovitz

## 3.2 2018-04-22 <dave at tiredofit dot ca>

* Update 01-permissions to quiet down if no UIDs changed.
* Refinements to MailHog, to always route through msmtp

## 3.1 2018-03-25 <dave at tiredofit dot ca>

* Update MailHog Test Server Startup

## 3.0 2018-03-14 <lesliesit at outlook dot com>

* Add 01-permissions script to support change uid & gid and add user to group:
* USER_<USERNAME>=<aNewNumber>
* GROUP_<GROUPNAME>=<aNewNumber>
* GROUP_ADD_<USERNAME>=<aGroupName>
* UID & GID in /etc/passwd & /etc/group will be modified.
* Old 01- 02- 03- scripts renamed after the new 01-permissions as 02- 03- 04-

## 2.9 2018-02-17 <dave at tiredofit dot ca>

* Update Permissions via fix-attrs.d

## 2.8 2017-12-24 <dave at tiredofit dot ca>

* Add custom crontab importing from /assets/cron-custom/

## 2.7 2017-10-23 <dave at tiredofit dot ca>

* Update S6 Overlay to 1.21.1.1

## 2.6.2 2017-09-30 <dave at tiredofit dot ca>

* Remove Dependency on Wget

## 2.6.1 2017-09-27 <dave at tiredofit dot ca>

* Tamed Verbosity 

## 2.6 2017-09-26 <dave at tiredofit dot ca>

* Increase Verbosity for Services being enabled/disabled

## 2.5 2017-09-17 <dave at tiredofit dot ca>

* Update Init Script Statements

## 2.4 2017-09-01 <dave at tiredofit dot ca>

* Update S6 Overlay to 1.20.0.0

## 2.3 2017-08-29 <dave at tiredofit dot ca>

* Used Official Zabbix Agent 3.4 instead of compiling from Trunk

## 2.2 2017-08-27 <dave at tiredofit dot ca>

* Added MSMTP to be able to route mail to external hosts

## 2.1 2017-08-27 <dave at tiredofit dot ca>

* Added DEBUG_MODE environment variable
* Added TIMEZONE environment variable
* Added ENABLE_CRON, ENABLE_ZABBIX switches
* Built mechanisms to not start processes until container initialized
* Zabbix Agent Configuration can be controlled and adjusted via Environment Variables
* General Tidying Up
