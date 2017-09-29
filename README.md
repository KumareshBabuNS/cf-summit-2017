# cf-summit-2017
Presentation and demos for 
[Manage Distributed Secrets in Applications on Cloud Foundry With Spring Cloud Vault](https://cfeu17.sched.com/event/Bity) at 
[CloudFoundry Summit Europe 2017](https://www.cloudfoundry.org/event/europe-2017).

## Spring Vault Demo

This demonstrates the usage of the _transit_ secret backend of vault in a typical spring boot based web application with JPA.
In this sample sensible data like social security and credit card numbers are encrypted before storing in the database and
decrypted before returning these to the rest api.

## Spring Cloud Config Vault Server

This demo implements a spring cloud config server both providing access to a...

* ...Git repository for all configuration properties that are not sensible
* ...Vault secret store for all sensible configuration data

## Spring Cloud Config Vault Client

This demo implements a spring cloud config client connecting to the corresponding
demo server and reads two configuration properties, one from git repo and one from vault.
