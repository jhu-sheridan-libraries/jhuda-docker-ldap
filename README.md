# LDAP Image

Provides an LDAP user store for the JHU Data Archive.  The Shibboleth IdP uses LDAP as a repository for user information.

The directory admin DN is `cn=admin,dc=archive`, password `password`.  The `slapd` process runs on port `389`.

There are three user DNs corresponding to the three roles of JHU DA archive users:
* `uid=honestbroker,ou=People,dc=archive`
* `uid=curator,ou=People,dc=archive`
* `uid=deositor,ou=People,dc=archive`

All users have the password `moo`.

## Status
![Automated Build](https://img.shields.io/docker/cloud/automated/jhuda/ldap) ![Build Status](https://img.shields.io/docker/cloud/build/jhuda/ldap)

## Locations
* [Docker Hub](https://hub.docker.com/r/jhuda/ldap/tags) 
* [Dockerfile](Dockerfile)
* [Build History](https://hub.docker.com/r/jhuda/ldap/builds)

## Environment Variables

|Description|Variable|Default Value| 
|---|---|---|   
| | | |
